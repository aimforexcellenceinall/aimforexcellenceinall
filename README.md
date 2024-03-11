<h1 align="center">
    <img src="https://readme-typing-svg.herokuapp.com/?lines=Hi,+I'm+Jeremie!+👋🏽;Nice+to+meet+you!+🙂&center=true&size=30&color=29d2a">
</h1>

<h1 align="center">A software engineer</h1>
<h3 align="center">react | rails | learning Salesforce</h3>

```
import React from 'react'

const AboutMe = () => {
  const technologies = {
    frontend: ['HTML5', 'CSS3', 'JavaScript', 'React', 'Reactstrap', 'Bootstrap'],
    backend: ['Ruby', 'Ruby on Rails'],
    databases: ['PostgreSQL'],
    tools: ['Git', 'GitHub', 'Yarn', 'NPM', 'Jest', 'RSpec', 'Firebase', 'PGAdmin', 'Postman', 'Visily', 'Canva', 'Slack', 'Trello'],
    platforms: ['Salesforce (in progress)'],
  }

  const introduction = 'Pursuing Salesforce Development, eager for transformative collaborations and new frontiers'

  const futureGoal = 'To advance AI, robotics, and automation for meaningful societal impact'

  const renderTechnologies = () => (
    <>
      {Object.entries(technologies).map(([category, items]) => (
        <p key={category}><strong>{category.charAt(0).toUpperCase() + category.slice(1)}:</strong> {items.join(', ')}</p>
      ))}
    </>
  )

  const funFact = () => (
    <p>As a storyteller at heart, I'm working on my debut sci-fi romance novel.</p>
  )

  return (
    <div>
      <p>{introduction}</p>
      <h3>Expertise:</h3>
      {renderTechnologies()}
      <h3>Currently:</h3>
      <p>Full-Stack Developer at LEARN Academy</p>
      <h3>Aspiration:</h3>
      <p>{futureGoal}</p>
      {funFact()}
    </div>
  )
}

export default AboutMe
```

<h3 align="left">Let's Connect:</h3>
<p align="left">
  <a href="https://linkedin.com/in/jeremiejoseph" target="_blank">
    <img src="https://img.shields.io/badge/-Jeremie%20Joseph-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://linkedin.com/in/jeremiejoseph" alt="LinkedIn Badge">
  </a>
</p>
