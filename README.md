```
import React from 'react';

const AboutMe = () => {
  const technologies = {
    frontend: ['HTML5', 'CSS3', 'JavaScript', 'React', 'Reactstrap', 'Bootstrap'],
    backend: ['Ruby', 'Ruby on Rails'],
    databases: ['PostgreSQL'],
    tools: ['Git', 'GitHub', 'Yarn', 'NPM', 'Jest', 'RSpec', 'Firebase', 'PGAdmin', 'Postman', 'Visily', 'Canva', 'Slack', 'Trello'],
    platforms: ['Salesforce (in progress)'],
  };

  const futureGoal = 'To drive innovation in AI, robotics, and IT Automation';

  const Technologies = ({ technologies }) => (
    <>
      {Object.entries(technologies).map(([category, items]) => (
        <p key={category}><strong>{category.charAt(0).toUpperCase() + category.slice(1)}:</strong> {items.join(', ')}</p>
      ))}
    </>
  );

  const FunFact = () => (
    <p>Fun fact: When I’m not immersed in coding, I’m weaving tales of imagination — my debut sci-fi romance novel is on the horizon!</p>
  );

  return (
    <div>
      <h1>Hi, I'm Jeremie Joseph</h1>
      <p><strong>Software Engineer</strong></p>
      <p>As a full-stack developer with a flair for solving complex problems, I'm diving deep into Salesforce Development. I'm keen on collaborating on transformative projects and exploring new opportunities.</p>
      <h3>Expertise:</h3>
      <Technologies technologies={technologies} />
      <h3>Currently:</h3>
      <p>Full-Stack Developer at LEARN Academy</p>
      <h3>Aspiration:</h3>
      <p>{futureGoal}</p>
      <FunFact />
    </div>
  );
};

export default AboutMe;
```
