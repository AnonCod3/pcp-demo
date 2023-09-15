# Project INDIGO

Anonymized technical preview:

Source code available on [GitHub](https://github.com/AnonCod3/pcp-demo)

## Usage

NOTE: Videos may not work on Apple devices.

**Axes and Export**


**Prosection**


**Distribution**


**Confusion**


**gm/ID**


## Run Locally

Adjust `port` in `./.streamlit/config.toml`

```sh
$ streamlit run ./ui.py
```

## Known Issues

- [ ] Changing primary column for coloring reverts color map to turbo
- [ ] Changing ckt model after removing a column through the UI adds design
  paramters to pcp that previously didn't exist, possibly an issue with hiding
  columns in `make_experiment`.
- [ ] Sometimes **Performance Space Exploration** plot disappears after switching tabs.
