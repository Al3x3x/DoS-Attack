# DoS Attack Java Application

This Java application is designed for Denial-of-Service (DoS) attacks. It includes a graphical user interface (GUI) built with Swing and allows users to launch DoS attacks by flooding a target server with HTTP requests.

## Disclaimer

**Warning:** This software is provided for educational purposes only. Do not use it for any malicious activities. The authors do not endorse or support any illegal or unethical use of this software. Use it responsibly and in accordance with applicable laws and regulations.

## Usage

1. Launch the application.
2. Enter the IP address of the target server.
3. Specify the number of threads to use for the attack.
4. Enter the port number of the target server.
5. Click the "Start Attack" button to initiate the DoS attack.
6. To stop the attack, click the "Stop Attack" button.

## Features

- Graphical user interface (GUI) for easy interaction.
- Adjustable number of threads for customizing the intensity of the attack.
- Ability to specify the target server IP address and port number.
- Real-time feedback on the attack status through the text area.

![Sin título](https://github.com/Al3x3x/DoS-Attack/assets/166667273/5f5bf37d-af11-4fc9-8ada-6a57894362ef)


## How It Works

The application creates multiple threads, each responsible for sending HTTP requests to the target server. These requests are sent in a loop until the attack is stopped. By overwhelming the server with a high volume of requests, the application aims to disrupt the server's normal operation and cause denial of service to legitimate users.

## Code Overview

The code consists of a Java Swing GUI application that utilizes threads to perform the attack. Key components include:

- **GUI Components:** Text fields for IP address and port, spinners for configuring the number of threads, and buttons for starting and stopping the attack.
- **Event Handling:** Action listeners are used to capture user interactions with GUI components and trigger appropriate actions.
- **Thread Management:** The application creates and manages multiple threads for sending HTTP requests concurrently.
- **Socket Communication:** Sockets are used to establish connections with the target server and send HTTP GET requests.

## How to Run

To run the application:

1. Compile the Java file (`DoSAtt.java`).
2. Execute the compiled class file (`DoSAtt.class`).

Or just open the DosAttack.jar file if you don't want to see the code or compile it. 

## Contributing

Contributions are welcome! If you'd like to contribute to the project, feel free to submit a pull request or open an issue on GitHub.

