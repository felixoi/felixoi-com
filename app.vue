<template>
  <div class="Aligner-item">
    <div>
      <img alt="Avatar" src="~assets/images/avatar.jpg" />
    </div>
  </div>
</template>

<script>
export default {
  setup () {
    useHead({
      title: 'felixoi.com',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'felixoi\'s personal website'
        }
      ],
      bodyAttrs: {
        class: 'Aligner'
      },
      link: [
        {
          rel: 'apple-touch-icon',
          sizes: '180x180',
          href: '~assets/img/apple-touch-icon.png'
        },
        {
          rel: 'icon',
          type: 'image/x-icon',
          href: '~public/img/favicon.ico'
        },
        {
          rel: 'icon',
          type: 'image/png',
          sizes: '16x16',
          href: '~public/img/favicon-16x16.png'
        },
        {
          rel: 'icon',
          type: 'image/png',
          sizes: '32x32',
          href: '~public/img/favicon-32x32.png'
        },
        {
          rel: 'mask-icon',
          color: '#00142a',
          href: '~public/img/safari-pinned-tab.svg'
        }
      ]
    })
  }
}
</script>
