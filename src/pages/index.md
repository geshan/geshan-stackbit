---
title: Home
sections:
- type: heroblock
  template: heroblock
  section_id: hero
  component: HeroBlock
  content: A blog about software engineering, devops and web development covering
    topics like php, javascript, docker, microservices etc.
  title: ''
  actions: []
- type: contentblock
  template: contentblock
  title: About
  section_id: about
  actions:
  - label: Contact Me
    url: "/contact"
  component: ContentBlock
  content: "**Geshan** is a seasoned software engineer, with more than a decade of
    software engineering experience. Currently, in Sydney, Australia serving THE ICONIC
    as a senior software engineer. He has a keen interest in REST architecture, microservices
    and servereless. He has spoken at tech conferences in 4 continents. He is actively
    involved with the developer community in his hometown Kathmandu, Nepal. He occasionally
    blogs in his free time."
  image: "/images/geshan.jpg"
- type: postsblock
  template: postsblock
  title: Recent Posts
  section_id: recent-posts
  actions:
  - label: View Blog
    url: blog/index.html
  component: PostsBlock
  num_posts_displayed: 4
menus:
  main:
    title: Home
    weight: 1
template: home

---
