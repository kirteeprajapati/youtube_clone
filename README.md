# Jhootube: A YouTube Clone Project

Jhootube is a project aimed at creating a clone of the popular video-sharing platform YouTube. It encompasses a range of technologies and features, making it a great learning experience and a functional project.

## Key Technologies and Concepts

- **Media Query**: It utilize media queries to ensure that our application is responsive, providing a seamless experience on various devices and screen sizes.

- **Material UI**: The project leverages the Material UI library, offering a consistent and visually appealing design for our YouTube clone.

- **React Folder and Structure**: It follow best practices in structuring our React application, organizing components, files, and directories for clarity and maintainability.

- **Rapid API**: It incorporate the Rapid API VS Code extension, which facilitates the integration of external APIs into our project.

- **Testing API**: The project includes testing APIs to ensure the reliability and functionality of our YouTube clone.

## REST API Overview

We implement a REST API (Representational State Transfer Application Programming Interface) that follows HTTP methods for interacting with resources:

- **GET**: Used to retrieve information about a resource, such as videos or user profiles.

- **POST**: Enables the creation of new resources, allowing users to upload videos or post comments.

- **PUT**: Used to update existing resources, ideal for modifying video details or user information.

- **PATCH**: Similar to PUT, this method is employed for resource updates, often used for making partial modifications.

- **DELETE**: Allows the deletion of resources, useful for removing videos, comments, or user accounts.

These HTTP methods are employed over secure HTTPS connections, ensuring data privacy and integrity while transferring information between different layers of our system:

- **Client -> Data -> Server**: Data flows from the client to the server, facilitating user interactions, such as uploading videos or searching for content.

- **Server -> Data -> Server**: In some cases, data needs to be transferred between server components or layers for processing and management.

The data is transmitted using the JSON format, providing a lightweight and versatile means of representing data. This format is vital for passing the state of resources between different layers of our application.

## URI and Path Parameters

- **URI (Uniform Resource Identifier)**: It serves as the address for our resources, uniquely identifying them. In the context of our YouTube clone, URIs are used for accessing videos, user profiles, and more.

- **Path Parameter**: These are variables included in the URI path itself. They allow us to point to specific resources or perform actions on them. For instance, It might use path parameters to indicate a particular video or user profile.

Jhootube is an exciting project that encompasses modern web development practices, API integration, and a deep dive into RESTful architecture. excited to share our progress and continue building this YouTube clone!

ScreenShots
![Home Page](https://github.com/kirteeprajapati/youtube_clone/blob/main/Assest/Video_cards.png)

![Video Player](https://github.com/kirteeprajapati/youtube_clone/blob/main/Assest/Videoplayer.png)

![Channel Card](https://github.com/kirteeprajapati/youtube_clone/blob/main/Assest/ChannelCard.png)
