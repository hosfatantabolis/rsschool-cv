# Maksim Litvinov

## Contacts

**Location**: St.Petersburg, Russia  
**Phone**: [+7(911)727-94-07](tel:+79117279407)  
**E-mail**: <litvinov.maksim.konstantinovich@gmail.com>  
**Telegram**: [@hosfatantabolis](https://t.me/hosfatantabolis)  
**Website**: [hosfatantabolis.ru](https://hosfatantabolis.ru)  
**Github**: [github.com/hosfatantabolis](https://github.com/hosfatantabolis)

![My photo](./img/me.jpg)

## About me

I've been learning frontend for quite a while now and I want to proceed and progress. I think that web-development is a challenging and exciting. I'm looking for a variety of different assignments, that will help me become a proficient developer.

I've made some Arduino projects, mostly basic. Photos of the best one can be seen [here](https://www.instagram.com/p/BlbShpsnTBT/?igshid=YmMyMTA2M2Y=).

In my spare time I like to shoot photos, I also collect vinyl records.

## Skills

- JS
  - React.js
  - React Native (Basic knowledge)
  - Vue.js (Basic knowledge)
  - Node.js
  - Express.js
- HTML5
- CSS3
- MongoDB
- BEM methodology
- Git
- VSCode
- Figma

## Code examples

**Edit note**

```
const handleEdit = (e, item) => {
    dispatch(editSelectedNoteAction({
        ...selectedNote, list: selectedNote.list.map(listItem => {
            return listItem.id === item.id ? { ...listItem, text: e.target.textContent } : listItem
        })
    }));
}
```

**Reducers: index.js**

```
import { configureStore } from '@reduxjs/toolkit';
import { combineReducers } from 'redux';
import { noteReducer } from './noteReducer';
import { themeReducer } from './modeReducer';

const rootReducer = combineReducers({
    notes: noteReducer,
    theme: themeReducer,
});

export const store = configureStore({ reducer: rootReducer });
```

## Work experience

### Study projects:

- [Mesto Project](https://mesto.hosfatantabolis.ru/)
  - React
  - Express
  - MongoDB
- [Movies Project](https://movies.hosfatantabolis.ru/)
  - React
  - Express
  - MongoDB
- [Project How-to-learn](https://how-to-learn.hosfatantabolis.ru/)
  - HTML5, CSS3
- [Travel Project](https://russian-travel.hosfatantabolis.ru/)
  - CSS3 Responsive mark-up (grid, flex), HTML5, BEM methodology

### Pet-projects:

- [Random Beer Project](https://random-beer.hosfatantabolis.ru/)
  - Vue.js basic usage
- [Notes Project](https://notes.hosfatantabolis.ru/)
  - React / Redux
- [Scanner Project](https://hosfatantabolis.ru/scanner)
  - React Native basic usage for my current job
  - Telegram bots

Projects' code can be viewed on my [github](https://github.com/hosfatantabolis).

## Education

- Yandex.Prakticum Web-Developer 10-month course
- ITMO college (Institute of Precise Mechanics and Optics)

## Languages

**English**: upper-intermediate  
**Russian**: native speaker
