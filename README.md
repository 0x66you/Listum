<h2 align="center">
  📆 Hard to KEEP TRACK of work? Try 📎 <a href="https://0x66you.github.io/Listum-vue.js/index.html">List'um</a>&nbsp;(Live demo)
</h2>

<p align="center"><img src="https://i.postimg.cc/P5rDV4kg/LIST-UM-4.png" width="860" alt="workerize"></p>

## About project
A simple yet elegant to-do list demonstrating how vue.js works.<br/>
Feel free to download source code and customize settings to your liking.<br/>
Learn to build user interfaces with Vue, make THIS your first project.<br/>
Not into programming? Great! It's still an excellent productivity tool.

## Prerequisites
* Html Css (duh!)
* Javascript
* bootstrap v4/v5

### Vue Instance (preview)
```js
new Vue({
            el:'#app',
            data:{
                noteSelected:{
                    ...
                },
                newNote:{  // store new input
                    ...
                },
                notes:JSON.parse(localStorage.getItem('notes')) || [] //store catelogue content
            },
            watch:{
                ...
                }
            },
            methods:{
                selectNote(note){
                    ...
                },
                addNote(){
                    //check if user filled both bars
                    ...
                },
                deleteNote(note){
                    ...
                },
                saveNotes(){
                    localStorage.setItem('notes',JSON.stringify(this.notes))
                }
            }
        })
```

## License

[MIT License](https://oss.ninja/mit/0x66you) © Yeh,Chun-Chen
