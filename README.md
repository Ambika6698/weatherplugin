
## Overview

This Jenkins plugin checks the current temperature of a given location using the OpenWeatherMap API before deploying an application.
The deployment is allowed only if the temperature is more than 20 degrees Celsius; otherwise, it is declined. Additionally, the plugin displays a message indicating the reason
for the deployment status.


## Configuration

1. Configure  Jenkins job.

2. Add "weather Jenkins Plugin" as a build step.

3. Provide the OpenWeatherMap API key and city name.

## Usage

- This plugin retrieves weather information using the OpenWeatherMap API during the Jenkins build process.
- Deployment is allowed only if the temperature is more than 20 degrees Celsius; otherwise, it is declined.
- The Jenkins console output will display a message indicating the reason for the deployment status.

