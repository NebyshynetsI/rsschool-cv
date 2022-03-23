# Nebyshynets Ivan
### Contacts
* ##### **E-mail:** ***carassic.4ever@gmail.com***
* ##### **GitHub:** ***NebyshynetsI***
### About Me
##### ***I am a strongly motivated, result-oriented person, with a high level of problem-solving capabilities.***
### Skills
* #####  ***HTML***
* #####  ***CSS***
* #####  ***JS***
* #####  ***C#***
* ##### ***Git/GitHub***
* #####  ***.Net***
### Code Example
```
getTasksButton.addEventListener("click", () => {
    const promise = getTasks(1234567);
    promise
    .then(onTasksReceived); 
});
function onTasksReceived(tasks){
    const result = document.querySelector('#tasks-result'); 
    result.innerHTML = '';
    tasks.forEach(task => {        
        const li = document.createElement('li');
        li.innerHTML = task.title;
        li.id = task.id;
        result.appendChild(li);
    });
}
```
### English
##### Intermediate - ***B1***