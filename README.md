# CodeAlpha_Jenkins-Remoting-Project
# Jenkins Remoting Project

## Author
Vivek Giri

## Project Description

This project demonstrates Jenkins Remoting by connecting a remote Jenkins Agent to a Jenkins Controller and executing build jobs remotely.

## Objectives

- Set up Jenkins Remoting
- Connect a remote Jenkins Agent
- Execute jobs on a remote node
- Learn distributed build execution
- Improve security using node isolation
- Gain hands-on experience with Jenkins Remoting

## Technologies Used

- Jenkins
- Java
- WebSocket
- Windows
- GitHub
- HTML
- CSS

## Project Workflow

1. Installed Java.
2. Installed and configured Jenkins Controller.
3. Created a Jenkins Agent (ubuntu-agent).
4. Downloaded agent.jar.
5. Connected the agent using WebSocket.
6. Created a Freestyle Job.
7. Executed the build on the remote agent.
8. Generated a static website using Jenkins.

## Build Result

The build was successfully executed on the remote Jenkins Agent.

```text
Building remotely on ubuntu-agent
Finished: SUCCESS
```

## Security Benefits

- Node Isolation
- Remote Job Execution
- Reduced Load on Controller
- Secure Agent Communication

## Project Structure

```text
jenkins-remoting-project/
│
├── index.html
├── README.md
├── css/
│   └── style.css
└── screenshots/
```

## Screenshots

Include screenshots of:

- Jenkins Agent Online
- Agent Connected
- Build Console Output
- Build Success
- Generated Website

## Conclusion

This project successfully demonstrates Jenkins Remoting by connecting a remote agent to the Jenkins Controller and executing build jobs remotely. It provides hands-on experience with Jenkins distributed architecture and remote execution capabilities.

## Status

✅ Completed Successfully
