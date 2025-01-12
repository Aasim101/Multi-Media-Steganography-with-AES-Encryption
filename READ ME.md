**READ ME**

**Multi-Media Steganography with AES Encryption**

This project is a steganography tool that allows you to hide secret messages in image, audio, and video files using encryption and LSB (Least Significant Bit) techniques. It also supports message decryption. The project is implemented using Python and developed on Google Colab Notebook.

## **Features**

* **Multi-Media Support**: Encode and decode messages in images, audio, and video files.  
* **Encryption**: Messages are encrypted using AES (Advanced Encryption Standard) for security.  
* **LSB Technique**: Messages are embedded using the Least Significant Bit technique.  
* **Graphical User Interface (GUI)**: A user-friendly interface is built using the Gradio library.

---

## **Installation and Setup**

To run the project, follow these steps:

### **Prerequisites**

Ensure you have Python installed. The project was developed on **Google Colab**, but it can also run locally with the necessary dependencies installed.

### **Dependencies**

Install the required libraries using the following command:

`pip install opencv-python numpy pydub moviepy pycryptodome gradio`

### **Running on Google Colab**

1. Open Google Colab.  
2. Copy and paste the project code into a new notebook cell.  
3. Run each cell sequentially to initialize the project.

## **Usage Instructions**

### **Running the GUI**

1. Execute the final cell in the notebook to launch the Gradio GUI.  
2. Use the following tabs for functionality:  
   * **Hide Message**: Encode a secret message into an image, audio, or video file.  
   * **Reveal Message**: Decode the hidden message from a file.

---

### **Encoding a Message**

1. Select the file type: **Image**, **Audio**, or **Video**.  
2. Upload the file in which you want to hide the message.  
3. Enter the secret message and the encryption key.  
4. Specify the output file path (e.g., `encoded_image.png`).  
5. Click the **Encode Message** button. The encoded file will be saved at the specified location.

---

### **Decoding a Message**

1. Select the file type: **Image**, **Audio**, or **Video**.  
2. Upload the file with the hidden message.  
3. Enter the decryption key used during encoding.  
4. Click the **Decode Message** button to extract the hidden message.

## **File Types Supported**

* **Images**: PNG  
* **Audio**: WAV  
* **Video**: MP4, AVI

