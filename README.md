Kid Cudi–Inspired Motivation Generator
======================================

A website that generates Kid Cudi motivational qoutes.

Build:
  docker build -t my-first-container .

Run:
  docker rm -f my-first-container 2>/dev/null || true
  docker run -d -p 8080:80 --name my-first-container my-first-container

Open:
  http://localhost:8080
