# useForm

Ejemplo:

```
    const initialForm = {
        name: '',
        age: 0,
        email: ''
    };
    
    const [ formValues, handleInputChange, reset ] = useForm( initialForm );

```

De esta manera se utiliza al otro lado.
```
    <div className="form-group">
        <input
            type="text"
            name"=name"
            className="form-control"
            placeholder="Enter the name"
            value={ name }
            onChange={ handleInputChange }
            
        />
    </div>
```
