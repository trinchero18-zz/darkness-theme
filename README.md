# Darkness Theme

### Adding support for **Fira Code iScript**.

1. Download [Fira Code iScript](https://github.com/kencrocken/FiraCodeiScript) (free) and copy fonts to your OS font folder.
2. In VScode press `ctr + ,` to open `User Settings` then add the following options and save changes.
    ```
    {
      ...
      "editor.fontFamily": "Fira Code iScript",
      "editor.fontLigatures": true,
      ...
    }
    ```
3. Tweek font appearance by editing VScode internal styles *(optional step)*.
    1. Find in your OS `<path to VScode>\resources\app\out\vs\workbench.main.css`
    2. with administrator rights open `workbench.main.css` and prepend the style below:
        ```
        .mtki {
            font-size: 1.125em;
            font-stretch: ultra-condensed;
        }
        ...
        ```
    3. Close and reopen VScode.