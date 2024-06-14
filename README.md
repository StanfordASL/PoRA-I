# Principle of Robot Autonomy I Course Website

Follow the same development guide [here](https://github.com/StanfordASL/StanfordASL.github.io/blob/main/README.md)

## Prepare for a New Quarter
1. Clone this repo and follow the development guide linked above. Make sure you can preview 
    the pages from your local machine with `rake preview`.

2. Make a copy of the latest quarter folders, e.g.

    ```sh
    cp aa174a_aut2324 aa174a_aut2425
    cp _aa174_aut2324 _aa174a_aut2425
    ```

3. Include the new quarter in the [config file](_config.yml) 
    ([here](_config.yml#L43) and [here](_config.yml#L46-L61)) and edit the 
    root [`index.html`](index.html#L2) to redirect homepage to the new quarter.

4. Edit everything inside the new quarter folder (e.g. `aa174a_aut2425`) 
    to include new materials / logistics / etc. Use `rake preview` to test
    out website changes locally.

