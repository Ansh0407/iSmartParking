

```markdown
# Mask-Based Parking Detection System(iSmartParking)

This project is a **Mask-Based Parking Detection System** that detects and monitors parking slot occupancy using computer vision techniques. The system uses OpenCV for image processing and Flask for creating a simple web interface. Users can upload a video of a parking lot, and the system processes the video to identify parking slots and determine their occupancy status.

---

## Features

- **Parking Slot Detection**: Identifies parking slots using contour detection and clustering.
- **Occupancy Detection**: Determines if a parking slot is occupied or empty using background subtraction and occupancy ratios.
- **Web Interface**: Provides a user-friendly interface to upload videos and monitor real-time parking status.
- **Live Updates**: Displays video feed with visual indications of slot occupancy and a summary of parking statistics.

---

## Prerequisites

Before running the project, ensure you have the following installed:

- Python 3.8 or higher
- Flask
- OpenCV
- NumPy
- scikit-learn
- Basic understanding of HTML and CSS (for minor customizations, if needed)

---

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/iSmartParking.git
   cd iSmartParking
   ```

2. Install required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Create a folder for uploaded videos (if not already created by the script):

   ```bash
   mkdir uploads
   ```

---

## Running the Project

1. Start the Flask server:

   ```bash
   python app.py
   ```

2. Open your browser and navigate to:

   ```
   http://127.0.0.1:5000
   ```

3. Use the interface to upload a video of a parking lot.

4. The system will process the video, detect parking slots, and display the live status feed.

---

## Usage Instructions

1. **Uploading Video**:
   - Use the "Upload Video" button to upload a `.mp4` file of the parking lot.
   - Ensure the video shows a clear view of the parking area.

2. **Viewing Results**:
   - The system will process the video and start showing live updates.
   - Occupied slots are highlighted in **red**, while empty slots are highlighted in **green**.

3. **Monitoring Statistics**:
   - View real-time statistics such as total slots, occupied slots, empty slots, and occupancy percentage on the `/status` endpoint.

---

## Project Structure

- `app.py`: Main Flask application.
- `index.html`: Web interface for uploading videos and viewing results.
- `main.py`: Contains the `MaskBasedParkingDetector` class for parking slot detection and occupancy analysis.
- `static/`: Contains CSS for styling the web interface.
- `templates/`: Contains HTML templates for the web pages.
- `uploads/`: Stores uploaded video files.
- `requirements.txt`: List of required Python libraries.

---

## Technologies Used

- **Backend**: Python (Flask)
- **Computer Vision**: OpenCV
- **Machine Learning**: DBSCAN (clustering algorithm from scikit-learn)
- **Frontend**: HTML, CSS

---

## Example Workflow

1. Upload a video:
 
3. View live feed with slot status:

4. Check real-time statistics:
   

---

## Contributing

Feel free to fork the repository and submit pull requests. Contributions are welcome!

---


## Author

- **Pavan, Ansh**  
  [GitHub Profile](https://github.com/pavan-kumar-25)
  [GitHub Profile](https://github.com/Ansh0407)
```
