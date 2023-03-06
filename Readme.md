# .NET 6 + ReactJS on Docker
Project name: DotReact

## Useful commands

### Building
run `docker build -f DotReact/Dockerfile -t dotreact:latest .`
in the root directory to build the image

### Running on specific port
run `docker run -p 8080:80/tcp dotreact:latest`
to launch the app from the image

Open your browser: `http://localhost:8080/`

### References
[MS container tools](https://learn.microsoft.com/en-us/visualstudio/containers/container-tools-react?view=vs-2022)
[Github issue](https://github.com/MicrosoftDocs/visualstudio-docs/issues/7702)