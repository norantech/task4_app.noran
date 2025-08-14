# README (English)

## Robot Arm Control Panel – Flutter App

This project is a Flutter application designed to control a robotic arm with **four motors**.  
It allows the user to:
- Adjust each motor’s position using sliders.
- Save multiple poses for future use.
- Execute saved poses.
- Reset motor positions.

The app connects to a backend (PHP + MySQL) to store and retrieve saved poses.

---

## Features
- **Motor Control:** 4 sliders to adjust motor values.
- **Save Poses:** Store current motor values into the database.
- **Run Poses:** Execute any saved pose directly.
- **Reset:** Set all motors back to zero position.

---

## Technologies Used
- **Flutter** – Frontend app development.
- **PHP** – Backend scripts (`get_run_pose.php`, `update_status.php`).
- **MySQL** – Database for storing motor values.
- **HTTP Requests** – Communication between Flutter and PHP backend.

---

## Usage
- Move sliders to adjust motor positions.
- Click **Save Pose** to store current values.
- Select a saved pose and click **Run** to execute it.
- Click **Reset** to return all motors to 0.

---

## License
This project is developed for educational purposes as part of Smart Methods tasks.
