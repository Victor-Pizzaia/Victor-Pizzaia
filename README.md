# Hi everyone 👋

Very Welcome to my profile, here you will find several personal projects and challenges that I practice in courses.
A lot of JavaScript, ReactJs and NodeJs.
Thanks for your visit.

```javascript
export default function Pizzaia(props) {
    const { data, abilities} = props;
    
    return (
        <>
            <h1>{data.firstName}</h1>
            <ul>
                {abilities.map(skill => (
                    <li>{skill}</li>  
                ))}
            </ul>
        </>
    )
}

function App() {
    const data = {
        firstName: "Victor",
        lastName: "Pizzaia"
    }
    
    const abilities = [
        JavaScript,
        React,
        Node,
        HTML,
        CSS,
        TypeScript,
        Docker
    ]
    
    return (
        <Pizzaia data={data} abilities={abilities} />
    )
}
```

<!--
**Victor-Pizzaia/Victor-Pizzaia** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
