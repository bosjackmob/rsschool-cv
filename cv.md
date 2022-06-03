# Serhii Stotskyi

##Contact information
Phone: +38 (097) 888-02-40
E-mail: bosjack.mob@gmail.com
Skype: bosjack

##Briefly About Myself

##Skills and Proficiency
HTML5, CSS3
JavaScript Basics
Git, GitHub
PHP, Bitrix CMS

##Code example
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

##Experience
Backend developer - some years
##Languages
English - Basic
Russian - Intermediate
Ukrainian - Native
