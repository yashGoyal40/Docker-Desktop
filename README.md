# GitHub Desktop Using React and Flask

Welcome to the GitHub Desktop-like application built with React and Flask! This application syncs with Docker CLI on your local machine to provide a seamless development experience.

## Installation

To use this application, follow these steps:

1. **Install Docker CLI**:
   - Follow the official Docker documentation to install Docker CLI on your operating system.
   - For Linux:
     ```bash
     sudo apt-get update
     sudo apt-get install docker-ce docker-ce-cli containerd.io
     ```
   - For other operating systems, refer to the Docker documentation.

2. **Clone the Repository**:
   ```bash
   git clone https://github.com/yashGoyal40/Docker-Desktop
   cd Docker-Desktop

Install Dependencies:
Install dependencies for both the frontend (React) and backend (Flask):
```Ubuntu
Install Nodejs by refring the official documentation
sudo apt-get install python3 
sudo apt-get update
sudo apt-get install python-flask
#inside the repo directory
npm install
```
```Arch
Install Nodejs by refring the official documentation
sudo pacman -Su python3
sudo pacman -S python-flask
#inside the repo directory
npm install
```
- For other operating systems, refer to the Distribution/Operating system documentation

Usage
Follow these steps to run the application:

1. Run the Flask Backend:
```bash
cd backend
python app.py
```
2. Start the Frontend Server:

Initialize the Node.js project:
```bash
npm start
```
3. Access the Application:

Once both backend and frontend servers are running, you can access the application in your web browser at http://localhost:3000.

 -Incase your localhost:3000 not able to communicate with localhost:5000 [website not working properly]
 
 -use https://addons.mozilla.org/en-US/firefox/addon/cors-everywhere/ Extention [Firefox]


## Contributing

We welcome contributions from the community! Feel free to submit pull requests or open issues if you encounter any problems or have suggestions for improvements.

## License

https://github.com/yashGoyal40/Docker-Desktop. This README.md provides clear instructions for users to install and run your application, as well as guidelines for contributing and information about the project.

