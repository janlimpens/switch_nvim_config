# switch_nvim_config

This is a simple script that helps you to easily run different configurations of nvim.
Copy it somewhere to your $PATH.

To copy your current nvim config to a named location and link to it, issue:
  
  > switch_nvim_config init my_config

Now you can reset your nvim configs to 0 state:

  > switch_nvim_config purge

Now install astronvim, lazy or whatever is hip.

Run

  > switch_nvim_config init astro (or lazy or whatever)

to keep its files at a named locations

  > switch_nvim_config relink my_config

to get your original config back. Rinse and repeat.

  > switch_nvim_config relink astro

