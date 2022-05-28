Attendance system based on face recognition

**Overview and How It Works**

In this application, I am using web technologies like ReactJS, NodeJS and database is MongoDB.It is the client-server architecture which is linked to the MongoDB. The client side will carry out all the procedure of face recognition such as face detection, facial landmark detection, feature extraction and feature matching. The extracted feature is sent over to the server and stored into the database. During the matching process, all the feature vectors are fetched accordingly to match with the detected feature vectors.

**How to make and Get Started**
Step-1 -> Download the source code
Step-2 -> Download and install NodeJS and check Node Package Manager (NPM) also have been installed.
Step-3 -> Create an account in MongoDB Cloud and configure
Step-4 -> Create an account in Cloudinary media storage and configure
Step-5 -> Create Google OAuth Credential to enable google login and sending email
Step 6 -> Configure server environment variables.

**Running the Application**

**Server**
1-Make sure the 10 env variables have been assigned in ".env" file.
2-Install the "nodemon" which can restart the server script automatically if changes are detected.
3-Open CMD, execute command "npm i -g nodemon" to install nodemon globally.
4-Take a look at "server/package.json".
5-Open CMD under directory "server", type "npm run dev".

**Client**
1-The client script is built using ReactJS, through CRA command.
2-Open CMD under directory "client", type "npm start".

**How to use**
1- Create account on both lecturer and student sections.
2- A course will be created by the lecturer and share the courseID of that course with the students.
3- Students should upload their respective photos in their respective accounts.
4- When student will come in the class, lecturer will take the attendance of that student either by remote or face to face recognition.
