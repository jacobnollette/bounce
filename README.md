# OLLAMA Bounce

[![Demo Video](https://img.youtube.com/vi/beaTfXrJ5Jw/0.jpg)](https://www.youtube.com/watch?v=beaTfXrJ5Jw)


## Overview
Bounce is a command-line utility to simplify the process of command line RAG. It's somewhat immature, and assumes that you're basically the only user of the location /tmp/bounce, so it would probably work well in container environments.


# Usage
## ./bounce
You can pipe strings into bounce or you can place them on the right side; that is it. Bounce will combine your current input with the RAG from prevous sessions. And when Ollama output, it will add that to the existing RAG, so the next session.
## ./squash
Squash simply echos your current rag to the stdout, and clear you're tmp buffer., so you can start new.

# Installation
You could certainly put this in your path.

# Maintenance and updates
I envision I will probably add some expanded support for model based env variables., PR's welcome.

# License
This project is licensed under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0).