*I'm not English, if you find a mistake, write to me!*
# EN:
## The plugin allows you to create your own forms and display them to players.

Command: ```/sformopen <form id> <player>```

To create a form you need to write the following code in the file:

```
test:
  type: 'Simple'
  name: 'Test Form'
  content: 'Test Form. Click to Buttons!'
  buttons:
    - name: 'Button 1'
      cmd: '@log gamemode c %p'
    - name: 'Button 2'
      cmds: 'tp %p %p / say Hi, I'm %p' 
    - name: 'Button 3'
      message: '%p, this is a form button!'
```

# RU:
  
## Этот плагин служит для создания всплывающих окон и отображения их игроку.

Команда: ```/sformopen <id окна> <игрок>```

Для создания вашего окна надо добавить следующий код в файл forms.yml

```
test:
  type: 'Simple'
  name: 'Test Form'
  content: 'Test Form. Click to Buttons!'
  buttons:
    - name: 'Button 1'
      cmd: '@log gamemode c %p'
    - name: 'Button 2'
      cmds: 'tp %p %p  / say Hi, I'm %p'
    - name: 'Button 3'
      message: '%p, this is a form button!'
```
