<template>
  <div class="flex flex-col min-h-screen p-8 pb-20 gap-16 sm:p-20">
    <main class="flex-1 flex flex-col gap-8 items-center">
      <Card class="w-full max-w-2xl">
        <CardHeader>
          <CardTitle>nuxt-shadcn-template</CardTitle>
          <CardDescription>
            Get started by editing pages/index.vue
          </CardDescription>
        </CardHeader>
        <CardContent>
          <p class="mb-4">
            A simple template with Nuxt 3 and shadcn/vue.
            <br />
            Build by LikeDreamwalker with love❤️.
          </p>
          <ul class="list-disc list-inside space-y-2">
            <li>Customizable components</li>
            <li>Dark mode support</li>
          </ul>
        </CardContent>
        <CardFooter class="flex justify-between">
          <Button asChild>
            <NuxtLink
              href="https://www.shadcn-vue.com/"
              target="_blank"
              rel="noopener noreferrer"
            >
              Learn shadcn/vue
            </NuxtLink>
          </Button>
          <Badge variant="outline">v0.1.0</Badge>
        </CardFooter>
      </Card>

      <div class="flex gap-4 items-center flex-col sm:flex-row">
        <Button asChild class="bg-[#0066ff]">
          <NuxtLink
            href="https://ldwid.com"
            target="_blank"
            rel="noopener noreferrer"
          >
            <NuxtImg class="mr-2 h-full" src="/ldw.svg" />
          </NuxtLink>
        </Button>
        <Button variant="outline" asChild>
          <NuxtLink
            href="https://nuxt.com/"
            target="_blank"
            rel="noopener noreferrer"
          >
            Read Nuxt docs
          </NuxtLink>
        </Button>
        <ThemeButton />
      </div>
    </main>
  </div>
</template>
