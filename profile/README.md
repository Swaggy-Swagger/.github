
<img width="1497" alt="스크린샷 2024-08-28 오후 8 15 40" src="https://github.com/user-attachments/assets/bf668c9b-6c7f-4c9b-b1f0-6f883fe7699e">

# Swaggy Swagger
Demo Video: [Watch on YouTube](https://www.youtube.com/watch?v=oD8ShZGQrqo)

## Overview
**Swaggy-Swagger** is a library designed to enhance the functionality 
and user experience of the popular API documentation tool, Swagger.  

This project addresses common pain points faced by developers, 
improving the Swagger UI and adding new features to make API documentation more intuitive and effective.

## Features
### Enhanced UI/UX
#### Sidebar Navigation
- A new sidebar allows for quick navigation to specific API sections, improving accessibility and ease of use.
<p>
    <img src="https://github.com/user-attachments/assets/b09bf788-df68-4975-82cf-dc623d8e4ddc" alt="Image 1" width="65%">
    <img src="https://github.com/user-attachments/assets/c39f7cda-b13f-49d4-b277-4fa7f175557b" alt="Image 2" width="30%" align="top">
</p>

#### Horizontal Layout
- The default vertical layout has been changed to a horizontal format, enabling easier viewing of parameters and responses, and reducing the need for scrolling.
  <p>
    
  <img width="50%" alt="스크린샷 2024-08-28 오후 11 24 29" src="https://github.com/user-attachments/assets/c1181e35-da40-4124-b56c-d1bd9ea35c76">
  <img width="48%" src = "https://github.com/user-attachments/assets/8bf549d0-3f8f-4f99-8669-8b36cbef356c" align="top">
  </p>

### Change Tracking and Visualization
- Server-Side Change Management: Every server restart triggers the storage of Swagger snapshots in JSON format. These snapshots are versioned, and changes are logged.
- Client-Side Change Indicators: APIs with recent changes are marked with a red dot. Hovering over the API reveals information about the changes (e.g. endpoints, parameters, request/response schemas)
  <p>
  <img width="49%" alt="스크린샷 2024-08-28 오후 10 54 36" src="https://github.com/user-attachments/assets/c36539b7-0e2d-474a-b074-59e007feef8a">
  <img width="49%" alt="스크린샷 2024-08-28 오후 10 54 12" src="https://github.com/user-attachments/assets/9c6e1e6f-4949-4f05-a695-10332ce32720"> 
  </p>
  <img width="100%" src = "https://github.com/user-attachments/assets/bf1daf8d-17ca-411a-a4a4-3c2b4f1139c9">

- After checking changes, the red dot disappears (it reappears upon refreshing)
  <img width="100%" src = "https://github.com/user-attachments/assets/4b158a0c-9a46-4861-92c7-134083d5e83c">
  
### API Sorting By Line Number
- User-Defined Sorting: Swaggy-Swagger allows APIs to be sorted based on the line numbers in the code. This custom sorting improves readability and reflects the developer’s intent.

### Enjoy Swaggy Swagger 😎
  <p>
  <img width="49%" alt="스크린샷 2024-08-28 오후 10 54 36" src="https://github.com/user-attachments/assets/101098d5-8b3d-4886-a4c4-8e00006053e2">
  <img width="49%" alt="스크린샷 2024-08-28 오후 10 54 12" src="https://github.com/user-attachments/assets/a007719b-be2b-41e5-ba56-fa1871bcfed3"> 
  </p>
## How to Use
- You can find detailed information on requirements and installation in the [Repository of Spring Boot Library](https://github.com/Swaggy-Swagger/swagger-custom-java)

## How to Contribute

## License
## License
**Swaggy-Swagger** is licensed under the Apache License, Version 2.0.  
See the [LICENSE](https://github.com/Swaggy-Swagger/swagger-custom-java/blob/main/LICENSE) file for more details.

[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FSwaggy-Swagger%2Fswagger-custom-java.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2FSwaggy-Swagger%2Fswagger-custom-java?ref=badge_large)

## Contact
