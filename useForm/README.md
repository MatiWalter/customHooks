# useForm Hook

Ejemplo:

```js
    const initialForm = {
        name: '',
        age: 0,
        email: ''
    };
    
    const [ formValues, handleInputChange, reset ] = useForm(initialForm);
```
