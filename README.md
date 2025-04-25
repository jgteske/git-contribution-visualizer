# Visualizer for local git histories

## Install requirements

```bash
go install
```

## Run app

```bash
git-contribution-visualizer -add /path/to/folders
git-contribution-visualizer -email "email@gmail.com"

# go run main.go scan.go stats.go -email "email@gmail.com" -add "path/to/git/repo"
```

## Config Saved

> Important not to add an empty line in the beginning
>
> Git Repo need head information of commits

`~/.gogitlocalstats`

## Build App

```bash
go build

# run app
./git-contribution-visualizer -add /path/to/folders
./git-contribution-visualizer -email "email@gmail.com"
```
