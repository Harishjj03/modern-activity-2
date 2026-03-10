## app.jsx:
```
import Student from "./student";

function App() {
  return (
    <div>
      <h1>Student Details</h1>

      <Student name="Harish" course="Modern Web Development" />
      <Student name="Arun" course="React JS" />
      <Student name="Kumar" course="JavaScript" />

    </div>
  );
}

export default App;
```
## student.jsx
```
function Student(props) {
  return (
    <div>
      <h2>Name: {props.name}</h2>
      <p>Course: {props.course}</p>
    </div>
  );
}

export default Student;
```