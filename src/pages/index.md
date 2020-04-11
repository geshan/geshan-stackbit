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
  content: This is the "about" excerpt. It can be used to provide a paragraph about
    yourself that people can read on the homepage to get a sense of who you are. There
    also exists a dedicated about page where you can write more about yourself for
    those who are interested.
  image: ''
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
