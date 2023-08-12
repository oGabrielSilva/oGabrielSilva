## Gabriel
### What's up, Dev
:computer: I'm Full-Stack Developer!
:house_with_garden: I’m from Brazil.
:books: I’m currently learning everything.
:outbox_tray: 2021 Goals: create a new project and find a new job.
## Tools and Technologies

```js
export const gabriel = new Developer({
  name: 'Gabriel Silva',
  gitUser: 'oGabrielSilva',
  job: 'FullStack Developer & IT Manager',
  languages: ['JavaScript', 'TypeScript', 'Java'],
  frameworks: ['React/React-Native', 'NextJS', 'NodeJS', 'Express'],
  tools: ['MySQL', 'Firebase', 'MongoDB', 'Prisma'],
});
```

```js
export class Developer extends AboutMe {
  readonly languages: Array<string>;
  readonly frameworks: Array<string>;
  readonly tools: Array<string>;

  constructor({ name, gitUser, job, languages, tools, frameworks }: Developer) {
    super(name, gitUser, job);
    this.languages = languages;
    this.frameworks = frameworks;
    this.tools = tools;
  }
}

```


```js
export class AboutMe {
  constructor(readonly name: string, readonly gitUser: string, readonly job: string) {}
}
```



## Statistics

<div>
 <a href="https://github.com/oGabrielSilva">
 <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=oGabrielSilva&layout=compact&langs_count=7&theme=dracula"/>
</div>

