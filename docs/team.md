# Our Team

<VPTeamMembers size="small" :members="members" />

(Some icons may not be correct, since vitepress does not yet support custom icons)

<script setup>
import { VPTeamMembers } from 'vitepress/theme'

const members = [
  // https://github.com/vuejs/vitepress/issues/738
  // When finished, change opschneckles "twitter" to a web icon

  {
    avatar: 'https://avatars.githubusercontent.com/u/69014593',
    name: 'FrederoxDev',
    title: 'Creator',
    links: [
      { icon: 'github', link: 'https://github.com/FrederoxDev' },
      { icon: 'twitter', link: 'https://twitter.com/FrederoxDev' }
    ]
  },
  {
    avatar: "https://avatars.githubusercontent.com/u/80198925",
    name: "opschnecke",
    title: "German Translations",
    links: [
      { icon: "github", link: "https://github.com/opschnecke" },
      { icon: "twitter", link: "https://schneckengames.xyz/" }
    ]
  },
  {
    avatar: "",
    name: "Zorhu",
    title: "Russian Translations"
  }
]
</script>