# Website Playgrounds

A collection of small webpages. This repository contains several small pagaes each ready to launch with a `docker-compose`  file.

## The Collection

| Project | Description |
| ----------- | ----------- |
| Christmas 🎄 | A small collection of gifts for family. |
| Flower 🌸 | A flower for your loved ones. |
| Valentine's Day ❤️ | A romantic way to confess your love. |
| Birthday 🌸 | A personalized Birthday site. |


## Getting Started

Every project in this repository is equipped with a `docker-compose.yml` file for quick deployment.

### Running a Playground
Navigate to the specific project folder:

```bash
cd christmas
```
Launch the container:

```bash
docker-compose up -d
```
View the site by opening your browser to `http://localhost:[PORT]`

Check the specific docker-compose.yml file in each folder to verify the assigned port.
