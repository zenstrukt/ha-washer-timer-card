# Washer Timer Card using Custom Button Card template
Custom Button Card for a Fisher &amp; Paykel Washer. Can be customised to match other sensors.

![image](https://github.com/user-attachments/assets/496588c3-f2be-4f26-9ffc-854b55605431)

## Using the card
1. Create a new vertial stack card
2. In card 1, switch to show code editor and paste in the button-card.yaml contents.
3. Modify the visibility of the card to show/hide based on your sensor activity to keep it tidy on your dashboard.

## Optional
GE appliances do not often have an initial value set for the cycle time. To incorporate this and use with the progress bar dynamically, refer to repo files to add automations, configuration & templates.

The below input_text will be made available and referenced in the button card.
```
input_text.static_initial_laundry_time
```
