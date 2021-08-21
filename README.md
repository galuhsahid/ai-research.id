# AI-Research.id

A placeholder for the https://ai-research.id website.

* [Getting started](#getting-started)

## Getting started
There are two ways to run this website, without Docker and using Docker.

Clone this repo:
```
git clone https://github.com/indonesian-nlp/ai-research.id.git
```

```
cd ai-research.id
```

### Development
First, make sure to [install `hugo`](https://gohugo.io/getting-started/installing/).

After that, run:

```
hugo server
```

The website will be run in `localhost:1313`.

### Deployment

Build image:
```
docker build -t airesearch .
```

Run:
```
docker run -d -p 8080:80 airesearch
```

## Acknowledge
This website template is based on [Blogophonic](https://github.com/formspree/blogophonic-hugo/).