# jenkins-git

This workspace contains two small CI/CD demo projects:

- `ci-cd-demo-1`: a simple Python app with a basic test file.
- `ci-cd-demo-2`: a Python app prepared for container-based deployment with a `Dockerfile` and GitHub Actions workflow.

## Demo 1

Run the app:

```bash
cd ci-cd-demo-1
python app.py
```

Run the tests:

```bash
cd ci-cd-demo-1
python -m pytest
```

## Demo 2

Build the container image:

```bash
cd ci-cd-demo-2
docker build -t ci-cd-demo-2 .
```

## Notes

The workspace is set up for experimenting with CI and CD pipelines, so you can extend either demo with build, test, or deployment automation as needed.
