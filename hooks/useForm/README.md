# useForm

Ejemplo:

```
    const initialForm = {
        name: 'Alejandro',
        age: 23,
        email:'email@gmail.com'
    }
    const [formValues, handleInputChange, reset] = useForm(initialForm);
```