# Digital Alarm Clock App
<img src="https://github.com/user-attachments/assets/e346e835-4d59-40bb-a291-46be811fe47b" width="500" />

### Description

This project is a simple Digital Alarm Clock application developed using C# and Windows Forms. It displays the current time, date, and day of the week while allowing users to set an alarm.

### Features

- Displays the current system time, date, and day of the week.
- Allows users to set an alarm.
- When the alarm time is reached, an image is displayed.
- Users can turn the alarm on or off.

### Technologies Used

- C#
- Windows Forms
- .NET Framework

### Installation & Usage

#### Open the project in Visual Studio.
#### Build and run the application.

### Code Overview

#### `DigitalAlarm.cs`
- Initializes the alarm clock UI and event handlers.
- Uses Timer components to update the current time and check the alarm.
- Toggles visibility of an alarm image when the set time is reached.

### How It Works

1. The application retrieves the system's current time upon launch.
2. Users can set an alarm using a date-time picker.
3. When the system time matches the set alarm time, an image is displayed.
4. The alarm can be manually turned off to hide the image.

### Future Enhancements

- Add sound notification when the alarm is triggered.
- Improve the UI with additional customization options.
- Allow users to set multiple alarms.

### Authors

- **Chiayin Yang**
- **Yanping Guo**

### License

This project is open-source. Feel free to modify and use it for learning purposes.
