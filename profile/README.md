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
<img width="1624" alt="스크린샷 2024-08-28 오후 11 24 36" src="https://github.com/user-attachments/assets/b09bf788-df68-4975-82cf-dc623d8e4ddc">

#### Horizontal Layout
- The default vertical layout has been changed to a horizontal format, enabling easier viewing of parameters and responses, and reducing the need for scrolling.
  <img width="1624" alt="스크린샷 2024-08-28 오후 11 24 29" src="https://github.com/user-attachments/assets/c1181e35-da40-4124-b56c-d1bd9ea35c76">
### Change Tracking and Visualization
- Server-Side Change Management: Every server restart triggers the storage of Swagger snapshots in JSON format. These snapshots are versioned, and changes are logged.
- Client-Side Change Indicators: APIs with recent changes are marked with a red dot. Hovering over the API reveals information about the changes (e.g. endpoints, parameters, request/response schemas)
  <img width="1624" alt="스크린샷 2024-08-28 오후 10 54 36" src="https://github.com/user-attachments/assets/c36539b7-0e2d-474a-b074-59e007feef8a">
  <img width="1624" alt="스크린샷 2024-08-28 오후 10 54 12" src="https://github.com/user-attachments/assets/9c6e1e6f-4949-4f05-a695-10332ce32720">

### API Sorting By Line Number
- User-Defined Sorting: Swaggy-Swagger allows APIs to be sorted based on the line numbers in the code. This custom sorting improves readability and reflects the developer’s intent.

## How to Use
- You can find detailed information on requirements and installation in the [Repository of Spring Boot Library](https://github.com/Swaggy-Swagger/swagger-custom-java)

## How to Contribute

## License

## Contact