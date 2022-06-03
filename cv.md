# Serhii Stotskyi

## Contact information
- Phone: +38 (097) 888-02-40 
- E-mail: bosjack.mob@gmail.com 
- Skype: bosjack

## About Myself
I am a fat seal in the frontend sea

## Skills and Proficiency
* HTML5, CSS3
* JavaScript basics, React basics
* Git, GitHub
* PHP, Bitrix CMS

## Code example
*Switcher to filter*
```
import React from 'react'
import { useSelector } from 'react-redux'
import { selectIsInStock, setIsInStock } from '../filterSlice'
import Switch from '../base/Switch'

const Availability = () => {
    const isInStock = useSelector(selectIsInStock)

    return <Switch name={'Только в наличии'} action={setIsInStock} defaultChecked={isInStock} />
}

export default Availability
```

## Experience
I have some years backend development expierence.
## Languages
1. Ukrainian - Native
2. English - Basic
3. Russian - Intermediate
