# sveltekit-next-200-reproduction-mailto
reproducing a error in @sveltejs/kit@next.200

```
✓ 14 modules transformed.
.svelte-kit/output/server/app.js                      0.07 KiB
.svelte-kit/output/server/chunks/app-15aed414.js      48.53 KiB
.svelte-kit/output/server/chunks/layout-16a4b7f3.js   0.23 KiB
.svelte-kit/output/server/chunks/error-1cd6baa4.js    0.71 KiB
.svelte-kit/output/server/chunks/index-13515498.js    0.24 KiB

Run npm run preview to preview your production build locally.

> Using @sveltejs/adapter-static
> ENOENT: no such file or directory, mkdir 'build/mailto:hi@example.com'
Error: ENOENT: no such file or directory, mkdir 'build/mailto:hi@example.com'
```