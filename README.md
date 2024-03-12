> Why do I have a folder named ".expo" in my project?
The ".expo" folder is created when an Expo project is started using "expo start" command.
> What do the files contain?
- "devices.json": contains information about devices that have recently opened this project. This is used to populate the "Development sessions" list in your development builds.
- "settings.json": contains the server configuration that is used to serve the application manifest.
> Should I commit the ".expo" folder?
No, you should not share the ".expo" folder. It does not contain any information that is relevant for other developers working on the project, it is specific to your machine.
Upon project creation, the ".expo" folder is already added to your ".gitignore" file.

>Getting Started
- Clone the Repository: Start by cloning the repository using the command 
"git clone"  in a command line terminal.
- Navigate into the project directory: Move into the project directory using "cd compuquiz". This should be done in a command line terminal.
- Install the dependencies: Install with the command "npm install --force"
- Running the App: To Launch the App use the command 
"npx expo start --tunnel" .This will start the Expo development server and display a QRcode in the server.
- Expo Go App: Install the Expo Go app on your device from the app store
- Scan the QR code : Open the Expo Go app and use the device's camera to scan the QR code displayed in the terminal. This will load the app on your device.

>Folder Structure
Here's a brief overview:
src: Contains the main source code of the app.
components: Reusable UI components.
screens: Different app screens, including the quiz screen.which is 3 screens.
data: Quiz data and questions.
App.js: The entry point of the app.
package.json: Lists project dependencies and scripts.
