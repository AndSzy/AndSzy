## 👋 Hey! Nice to see you.

Welcome to my page!

I'm Andrew, **Frontend** developer from **Gdansk**, Poland, currently living in **Oxford**, England.

```javascript
let skills = [
    { id: 1, name: 'React' },
    { id: 2, name: 'Redux' },
    { id: 3, name: 'Typescript' },
    { id: 4, name: 'Vue' },
    { id: 5, name: 'JavaScript' },
    { id: 6, name: 'SQL' },
    { id: 7, name: 'CSS' },
    { id: 8, name: 'HTML5' }, 
];

const About = ({ skills }: AboutType) => {

    const mediumScreen = useMediaQuery(`(min-width: ${BREAKPOINTS.medium}px)`);

    return (
        <>
            <GlobalHeaderStyled>
                {mediumScreen && <h1>About</h1>}
            </GlobalHeaderStyled>
            <Workplace company='Savills' position='Frontend Developer' />
            <SkillsWrapperStyled>
                {skills.map((skill) => {
                    <Skill key={skill.id} name={skill.name} />
                })}
            </SkillsWrapperStyled>
        </>
    )
};

export default About;

```


<!--
**AndSzy/AndSzy** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
