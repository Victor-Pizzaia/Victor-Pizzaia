# Hi everyone š

Very Welcome to my profile, here you will find several personal projects and challenges that I practice in courses.
A lot of JavaScript, ReactJs and NodeJs.
Thanks for your visit.

```javascript
export default function Pizzaia(props) {
    const { data, abilities } = props;
    
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
**Victor-Pizzaia/Victor-Pizzaia** is a āØ _special_ āØ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- š­ Iām currently working on ...
- š± Iām currently learning ...
- šÆ Iām looking to collaborate on ...
- š¤ Iām looking for help with ...
- š¬ Ask me about ...
- š« How to reach me: ...
- š Pronouns: ...
- ā” Fun fact: ...
-->
