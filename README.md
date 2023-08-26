
# Web Server Application in Go

This is a simple HTTP Web Server application writthen in Go that servers static content. 

## Requeriments

In order to run this project you should have 
Golang installed version 22.0 or higher
A proper module directory build 

## Getting Started
`
1. Make sure you have Go installed. If not 

1. Make sure you have Go installed and check your version typing "go -version" on your terminal. If is no the case, you can download it from the official website: https://golang.org/dl

2. Clone` this repository 

    ```sh
        git clone git@github.com:mauric/robust-go-server.git
    ```
3. Navig`ate the project directory:

    ```sh
        cd robust-go-server
    ```
4. Build and run the application 

    ```sh
        go build ./main.go
    ```

    The server should now be running at http://localhost:8080. You can access it using your web browser. 


## Features

- Simple static file serving
- Use of standar Golang library
- Basic routing and handling of HTTP request
- Extensible and customizable for your own use cases. 


## Configuration 

In order to configure the server a `config.json` file will be implemented in the future. That way you should be able
to modify setting such as  port number, file directory, etc.  

## Usage

1. Place your static files (HTML, CSS, JS, etc.) in the 'static' directory. 
2. Run the server as described in the Getting Started section
3. Open your web browse and navigate to http://localhost:8080

## Contributing

This project has developed with the goal of creating a simple platform to perform some experiments around software robustness.

Contributions are welcome! If youo find a bug or want to add a new feature or simply you recognize a better to write the code, 
please follow these steps:

1. Fork the repository. 
2. Create a new branch for your feature/fix 'git checkout -b feature-new-feature_name' or 'git checkout -b bugfix-issue'
3. Commit your changes: `git commit -am 'Add new feature'` or 'git commit -am 'Fix issue #1234'
4. Push the branch to your fork: `git push origin feature-new-feature`
5. Create a pull request on Github.``


## License

This project is licensed under the [MIT License](LICENSE).
