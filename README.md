# LedBuzz
<p align="center"><img src="https://github.com/himanshushah05/LedBuzz/blob/main/LedBuzz.png"/></p>


# What it does

<p> LedBuzz is a NodeMCU-powered see-through propeller display. By simply staring at your ceiling fan, you receive notification alert. You can use the app to add future alarms. After you've entered the information, you'll see the text message on the fan and receive a notification on your phone. We even have a website that can be used to sync the device as per the motor's RPM. </p>
<p align="center"><img src="https://github.com/himanshushah05/LedBuzz/blob/main/LedBuzz_demo.png"/></p>

# Images and demonstration video
## Perf board

  <table>
    <tr>
      <td>
       <img src="https://github.com/himanshushah05/LedBuzz/blob/main/LedBuzz_perfboard.jpeg" width="500px" height="400px" /></p>
      </td>
      <td>
        <img src="https://github.com/himanshushah05/LedBuzz/blob/main/LedBuzz_perfboard%202.jpeg" width="500px" height="400px"/></p>
  </table>
  
## RPM calibration 
<p> Motor RPM can be controlled by using this webserver hosted by NodeMCU </p>
<p align="center"><img src="https://github.com/himanshushah05/LedBuzz/blob/main/RPM%20compensation.jpeg"/></p>

## App UI
<table>
    <tr>
      <td>
        <img width="250px" src="https://github.com/himanshushah05/LedBuzz/blob/main/App1.jpeg">
      </td>
      <td>
        <img width="250px" src="https://github.com/himanshushah05/LedBuzz/blob/main/App2.jpeg">
      </td>
      <td>
        <img width="250px" src="https://github.com/himanshushah05/LedBuzz/blob/main/App3.jpeg">
      </td>
      <td>
        <img width="250px" src="https://github.com/himanshushah05/LedBuzz/blob/main/App4.jpeg">
      </td>
      <td>
        <img width="250px" src="https://github.com/himanshushah05/LedBuzz/blob/main/App5.jpeg">
      </td>
      
    
  </table>

# Demonstration video
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/7GXgpqfqqgQ/0.jpg)](https://youtu.be/7GXgpqfqqgQ)


# Setup
![image](https://user-images.githubusercontent.com/78071859/148664538-45368c92-b2d6-4540-b29a-91d7f5feb47e.png)

- Make the connections on perf board as per the above circuit diagram.   
- Assemble the batteries and NodeMCU such that the weight of the perf board is balanced.
- Open the (arduino code ka link) and add your firebase account host URL and authorization token and SSID and password of your local network.
- Clone the repo.
  `git clone https://github.com/himanshushah05/LedBuzz`
- Checkout to a new branch.
  `git checkout -b my-amazing-feature`
- Make some amazing changes.
- `git add .`
- `git commit -m "<Verb>: <Action>"`
- `git push origin my-amazing-feature`
- Open a pull request :)
  
# Usage
- Plug in NodeMCU and upload the sketch
- set up the perf board on a motor 
- Add your name and timings for a particular task/class and even assign a priority to that task.  
- You are now set to get your notifications on your phone and FAN. 

## Future Implementation
- We will implement IR sensors to determine the RPM of the motor or fan
 

# Contributions

- Feel Free to Open a PR/Issue for any feature or bug(s).
- Make sure to follow the [community guidelines](https://docs.github.com/en/github/site-policy/github-community-guidelines) when contributing.
- Please open an issue if you want to ask a question/discuss anything about ActivityOverYou.
- Want to add an action? add a feature? Open an Issue!


