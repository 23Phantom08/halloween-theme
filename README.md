# Halloween Theme


## Preparation

Make sure that under the configuration.yaml file you have the following:

```
frontend:
  themes: !include_dir_merge_named themes
```

Within the Home Assistant Config folder, create a new folder named themes
Restart Home assistant to apply the changes.


## Installation

Within the Home assistant themes folder, create a file named halloween.yaml

In this GitHub repo, go into the themes folder, open the halloween.yaml file and copy the contents
Paste the contents in the uglychristmas.yaml file created under your Home Assistant themes folder
Restart Home-Assistant or reload your themes
Apply the theme from within your profile settings or set it as backend-selected theme.
