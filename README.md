# Multicast Chat Application

This project provides a multicast chat application implemented in Java. It utilizes the multicast socket capabilities to allow multiple users to join a chat group and communicate with each other in real-time. The application features a graphical user interface (GUI) for easy interaction.

## Features

- **GUI for Interaction**: A user-friendly interface that allows for seamless interaction with the chat functionalities.
- **Multicast Group Chat**: Users can join a multicast group by specifying the group's IP and port number.
- **Real-time Messaging**: Enables real-time message sending and receiving within the multicast group.
- **Timestamps and Sender IP**: Displays each message with the sender's IP address and the time it was sent.


## Preview
![Captura de ecrã 2024-02-27 215208](https://github.com/JustCabaret/JavaMulticastChat/assets/67253335/8c48230b-ab39-4c2d-af27-50d79e847bae)


## Getting Started

### Prerequisites

- Java Development Kit (JDK) 21 or above.

### Running the Application

1. Clone the repository to your local machine.
2. Navigate to the `src/multicastChat` directory.
3. Compile the `MulticastFrame.java` file using `javac MulticastFrame.java`.
4. Run the application using `java multicastChat.MulticastFrame`.

## Usage

- Upon launching the application, enter your name, the multicast group IP, and the port number.
- Click "Join" to enter the chat room.
- Write your message in the message box and click "Send" to broadcast it to all members of the group.
- Click "Leave" to exit the chat room.

## Contributing

Feel free to fork the project, submit pull requests, report bugs, or suggest features.

## Authors

- **Hugo Cabaret** - [JustCabaret](https://github.com/JustCabaret)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
