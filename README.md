# cscart-tests

## Setup

jmeter -t cscart.jmx -JsetupUsers=100

## Run tests

jmeter -t cscart.jmx -JconsumerCreationThreads=100 -JorderUsers=100