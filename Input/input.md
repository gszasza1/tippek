# Input

## Controlled:
State visszatöltésre kerül. Ha szeretnél alap értéket, akkor state-ben kell megadnod 

```<input value={this.state.inputValue} onChange={e => this.setState({inputValue:e.target.value})}/>```

## Uncontrolled

State nem kerül visszatöltésre. Ha szeretnél alap értéket, akkor **defaultState** kell megadni-ben kell megadnod

```<input defaultState=”Alma” onChange={e => this.setState({inputValue:e.target.value})}/>```

## Függvények
Párat csak említés szintjén.

### OnBlur
    Kikerül focusból az input

### OnChange
    Változik az input
