# Add this block of code to glaze-wm
```
window_rules:
  - commands: ['set-floating --shown-on-top=true --x-pos=0 --y-pos=0']
    match:
      - window_process: { equals: 'zebar' }
```