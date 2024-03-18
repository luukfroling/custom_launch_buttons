# custom launch buttons v1

First version of custom launch buttons for jupyter-book. Install using

```
pip install git+https://github.com/luukfroling/custom_launch_buttons_v1.git#egg=custom_launch_buttons
```

to use, include a _launch_buttons.yml file along the _config.yml file. Buttons can be defined according to their label and their href as follows:
```
custom_launch_buttons:
  - label: EN
    url: https://www.google.com
  - label: QM2
    url: https://www.google.com
```
where the label tells the text in the button and the url where the button leads to.

### Todo version 2
- add icons
- add dropdown

