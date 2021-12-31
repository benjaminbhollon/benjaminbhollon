```js
const benjamin = {
  greeting: () => {
    return 'Howdy! Nice to meet you!';
  },
  status: 'awesome',
  hobbies: [
    'Reading',
    'Writing',
    'Coding',
    'Stargazing',
    'Making Music'
  ],
  languages: [
    {
      name: 'HTML/CSS',
      frameworks: [
        'Pug',
        'Markdown'
      ],
      projects: [
        'benjaminbhollon/see-with-eyes-closed',
        'benjaminbhollon/verbose-guacamole',
        'benjaminbhollon/verboseguacamole.com',
        'benjaminbhollon/serial-microfiction',
        'benjaminbhollon/learn-clef'
      ],
      confidence: 0.93
    },
    {
      name: 'JavaScript',
      frameworks: [
        'Node',
        'Express',
        'Pug',
        'Electron',
        'Mongoose',
        'MongoDB'
      ],
      projects: [
        'benjaminbhollon/see-with-eyes-closed',
        'benjaminbhollon/verbose-guacamole',
        'benjaminbhollon/serial-microfiction',
        'benjaminbhollon/umify',
        'benjaminbhollon/avo-js'
      ],
      confidence: 0.90
    },
    {
      name: 'PHP',
      frameworks: [
        'MySQL'
      ],
      confidence: 0.85
    },
    {
      name: 'Python',
      frameworks: [
        'Tensorflow'
      ],
      confidence: 0.45
    },
    {
      name: 'C#',
      frameworks: [
        'Unity3D'
      ],
      confidence: 0.32
    }
  ],
  links: [
    {
      href: 'https://benjaminhollon.com',
      description: 'Personal Website',
      repo: 'benjaminbhollon/personal-website'
    },
    {
      href: 'https://seewitheyesclosed.com',
      description: 'Blog',
      repo: 'benjaminbhollon/see-with-eyes-closed'
    },
    {
      href: 'https://fosstodon.org/@benjaminhollon',
      description: 'Mastodon',
      repo: undefined
    },
    {
      href: 'https://verboseguacamole.com',
      description: 'Self-coded Novel Editor',
      repo: 'benjaminbhollon/verboseguacamole.com'
    },
    {
      href: 'https://kesslercascades.com',
      description: 'School project on space junk',
      repo: 'benjaminbhollon/kessler-cascades'
    }
  ],
  farewell: () => {
    return "Goodbye! Come again soon!"
  }
}
```
