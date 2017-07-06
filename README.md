# cscart-tests

## Setup

jmeter -t cscart.jmx -JsetupUsers=100

## Run tests

jmeter -t cscart.jmx -JconsumerCreationThreads=100 -JorderUsers=100

## Test configuration parameters

| Parameter | Default Value | Description
| --- | --- | ---
| serverUrl | limitless-inlet-94061.herokuapp.com | The tget URL of the server to test
| consumerCreationUsers | 0 | The number of users which will create a profile
| orderUsers | 0 | The number of users which will create a profile


Additional parameters

| Parameter | Default Value | Description
| --- | --- | ---
| setupUsers | 0 | The number of users to setup
| consumerCreationRampup | 60 | The time in seconds to ramp-up
| consumerCreationCount | 1 | The number of scenarios to be played
| orderRampup | 60 | The time in seconds to ramp-up
| orderCount | 1 | The number of scenarios to be played