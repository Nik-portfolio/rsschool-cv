[Rsschool-cv](https://Nik-portfolio/rsschool-cv/cv#rsschool-cv)

# Nikita Carolingov

## My contact Info:

- email: example@gmail.com
- [github](https://github.com/Nik-portfolio)

## Summary:

I live and work in Rotterdam. I used to successfully pass the first 2 stages of RS School, but then I quit. Recently, I've been looking forward to resuming my studies.

## Skills:

- HTML
- CSS
- JS
- TS
- Basic React
- Git
- Strong working discipline

## Code Example, Basic Component:

```
type UserFormState = {
  name: string;
  age: number;
};

class UserForm extends Component<{}, UserFormState> {
  state: CounterState = {
    name: 'John',
    age: 42,
  };
  handelNameChange = (e: ChangeEvent<HTMLInputElement>) => {
    this.setState({
      name: e.target.value,
    });
  };

  handelAgeChange = (e: ChangeEvent<HTMLInputElement>) => {
    this.setState({
      age: +e.target.value,
    });
  };
  render(): ReactNode {
    return (
      <form>
        <label htmlFor="name">Name: </label>
        <input
          type="text"
          value={this.state.name}
          onChange={this.handelNameChange}
          id="name"
        />
        <br />
        <label htmlFor="age">Age: </label>
        <input
          type="text"
          value={this.state.age}
          onChange={this.handelAgeChange}
          id="age"
        />
      </form>
    );
  }
}

```

## Education:

- KNEY FKISIT (2022-2025)

## Experience:

- Rs School 2 Stages

## Language:

- English B2
- Russian C1
- Ukrainian C2
