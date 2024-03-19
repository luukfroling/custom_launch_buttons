# custom launch buttons v1

First version of custom launch buttons for jupyter-book. Install using

```
pip install git+https://github.com/luukfroling/custom_launch_buttons_v1.git#egg=custom_launch_buttons
```

to use, include a _launch_buttons.yml file along the _config.yml file. Buttons can be defined follows:
```
buttons:
  - type: dropdown
    icon: <svg> </svg>
    items:
      - label: item 1
        url: https://linkone.com
      - label: item 2
        url: https://linktwo.com
  - type: dropdown
    label: languages
    items:
      - label: Dutch
        url: https://www.dutch.com
      - label: English
        url: https://www.english.com
      - label: French
        url: https://www.french.com
```
where buttons is an array of launch buttons, each which can be identified using 'dropdown' or 'button'.

```
buttons:
  - type : dropdown

  - type : button
```

The button/dropdown can be visualised using either an svg icon (https://icons.getbootstrap.com/#icons) or text. 

```
buttons:
  - type : dropdown
    label: Language
  - type : button
    label : <svg></svg> 
```

Then the same story goes for each of the items in the dropdown menu.


