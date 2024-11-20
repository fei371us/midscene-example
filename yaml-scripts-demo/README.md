# Yaml Scripts

## Preparation

Ensure that Node.js is installed. Install the `@midscene/cli` globally

```shell
npm i -g @midscene/cli
```

Config the API key

```shell
# replace by your own
export OPENAI_API_KEY="sk-abcdefghijklmnopqrstuvwxyz"
```

## Run

Run all scripts

```shell
midscene ./midscene-scripts/
```

Extract status info from github status page

```shell
midscene ./midscene-scripts/extract-github-status.yaml
```

Perform a testing case on sauce demo

```shell
midscene ./midscene-scripts/sauce-demo.yaml
```

Perform a search on ebay.com

```shell
midscene ./midscene-scripts/search-headphone-on-ebay.yaml
```

Serve the `server_root` folder as a static server and test the `index.html` file

```shell
midscene ./midscene-scripts/local-static-server.yml
```

## Debug

Run a script with headed mode (i.e. you can see the browser window when running)

```shell
midscene --headed ./midscene-scripts/sauce-demo.yaml
```

Keep the browser window open after the script finishes

```shell
midscene --keep-open ./midscene-scripts/sauce-demo.yaml
```

# Reference

https://midscenejs.com/automate-with-scripts-in-yaml.html