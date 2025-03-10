# UTC-IST-Time-Converter
UTC IST Time Converter - 

## How It Works

#### Auto-detection: 
> The JavaScript code checks the input against a series of regular
> expressions that cover each supported format. Once a match is found,
> the corresponding parser extracts the time components.

#### Time Conversion: 
> Depending on the selected conversion direction (UTC to IST or IST to
> UTC), the script adds or subtracts 5 hours and 30 minutes. Because,
> IST => +5.30 hrs

#### Formatting: 
> The result is formatted back to the same style as the input (for
> example, if you input “HH:mm:ss” it outputs in that style).
