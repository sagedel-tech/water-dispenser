Here's a step-by-step procedure for the initial setup to program an Arduino board:

1. Install Arduino IDE:
   - Download and install the Arduino Integrated Development Environment (IDE) from the official Arduino website: [Arduino Software](https://www.arduino.cc/en/software).
   - Follow the installation instructions provided for your operating system.

2. Connect Arduino Board:
   - Connect your Arduino board to your computer using a USB cable. 
   - Ensure that the board is properly connected and recognized by your computer.

3. Select Board:
   - Open the Arduino IDE software.
   - Go to `Tools` > `Board` and select the appropriate Arduino board you are using (e.g., Arduino Uno, Arduino Nano, etc.).
   
4. Select Port:
   - In the Arduino IDE, navigate to `Tools` > `Port` and select the port that corresponds to your connected Arduino board.
   - If you're unsure which port to select, you can check the available ports before and after connecting the Arduino to determine which one is added.

5. Verify Installation:
   - To ensure that everything is set up correctly, you can upload a simple example sketch to your Arduino board.
   - Go to `File` > `Examples` > `01.Basics` > `Blink`.
   - This will open the Blink sketch, which blinks an LED connected to pin 13 on the Arduino board.
   - Click the "Upload" button (arrow icon) or press `Ctrl + U` to compile and upload the sketch to your Arduino board.
   - If everything is set up correctly, you should see the built-in LED on your Arduino board blinking.

6. Install Additional Libraries (if required):
   - If your project requires additional libraries beyond the standard Arduino libraries, you may need to install them.
   - Go to `Sketch` > `Include Library` > `Manage Libraries...`.
   - Use the Library Manager to search for and install the necessary libraries for your project.

7. Prepare Your Project:
   - Write or obtain the code for your project and open it in the Arduino IDE.
   - Ensure that your code includes any necessary libraries and is correctly configured for your specific hardware setup.

8. Upload Code:
   - Once your code is ready, connect your Arduino board to your computer if it isn't already connected.
   - Click the "Upload" button (arrow icon) or press `Ctrl + U` to compile and upload your code to the Arduino board.
   - Monitor the upload process in the bottom status bar of the Arduino IDE.
   - After successful upload, your project should begin running on the Arduino board.


Procedure to run the program.

1) Make the circuit as per the given diagram in the manual and in the printed breadboard.

   * This step is crucial, and it's important to ensure that the circuit is assembled correctly according to the provided diagram.

2) Connect your Arduino Nano with the provided USB cable to your computer.

   * sure that the USB cable is securely connected to both the Arduino Nano and your computer.

3) Open the Arduino IDE software.

   * Make sure that you have the Arduino IDE installed on your computer. If not, you can download it from the Arduino website.

4) Upload the sketch to the Arduino Nano by clicking on the Upload button (arrow icon) or pressing Ctrl + U.

   * Ensure that the correct board and port are selected in the Arduino IDE before uploading the sketch.

5) Monitor the Serial Monitor for any debugging messages or sensor readings by going to Tools -> Serial Monitor or pressing Ctrl + Shift + M.

   * This step is helpful for debugging and verifying that your program is working as expected.
   
6) Perform your activity.

   * Once the sketch is successfully uploaded and running, you can proceed with your intended activity or experiment.
