
# RemoteCu

RemoteCu was a remote app that was very customizable.



## Why I made it

whats missing with current remote app was how about the remotes that was no brand or generic remotes. I had this scenario that i had 5 remote controlled appliance and i had to find their remote and my phone support IR blaster so why not make an app to  support these remotes.
## How I plan to make it

### CORE
- make a receiver to capture specific signal from existing remote(using microcontroller Arduino based boards)
- pass it to remote app to save it and map it to buttons on ui. To pass it to the app, protocols can be used was:
    - BLE -supported by esp32 KROOM boards
    - Serial using otg cable
    - ...

### Extras
- remote management to group all the buttons
- button management for each remotes
- if you know the signal, you can add it manually


## Requirements

- arduino board support bluetooth bluetooth
- IR reciever
- android phone with IR blaster sensor


## extra Possible features

- repository or storage for generic remotes (website)
