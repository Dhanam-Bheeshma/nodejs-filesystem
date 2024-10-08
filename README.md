﻿# nodejs-filesystem

 This API allows users to create and retrieve text files. The text files are stored in a specific folder, and each created file contains the current timestamp.

Render Deployment:
Render URL: https://nodejs-filesystem-rk7o.onrender.com
GitHub Repository:
GitHub Repository: https://github.com/Dhanam-Bheeshma/nodejs-filesystem.git

Endpoints:
POST /api/create-file
Creates a text file in the specified folder. The content of the file is the current timestamp, and the filename is in the format "current-date-time.txt".
URL: https://nodejs-filesystem-rk7o.onrender.com/api/create-file
Method: POST
Request Body: None
Response:
201 Created: File created successfully.

GET /api/get-files
Retrieves a list of all text files in the specified folder.
URL: https://nodejs-filesystem-rk7o.onrender.com/api/get-files
Method: GET
Response:
200 OK: Returns a list of all text files.


Postman API Documentation: https://documenter.getpostman.com/view/36384516/2sAXqqcNST

Last Commit Hash: a69c19ac46478a4c7b958e3335b4dd3666d495299
This documentation provides the necessary details about your API endpoints, their functionality, and how to interact with them via Postman or any other tool.
