# Dev-Ops-1

## 1-1 For which reason is it better to run the container with a flag -e to give the environment variables rather than put them directly in the Dockerfile?
- It's better to add -e because that way we can protect our image if it's being uploaded or shared avoiding leackages
## 1-2 Why do we need a volume to be attached to our postgres container?
- We use a volume so our data dosen't get distroyed, this way if the container get´s distroyed or upgraded our data will remain intact
- It creates an storage in the data so you can share it across containers

## 1-3 Document your database container essentials: commands and Dockerfile.
- 

## 1-4 Why so we need a multistage blind?
We need it to make the process lighter and so we can eficientate process of creating an image
- also reduces image size

## Explain each step
### Build stage
- Names the stage, and sets a working environment where we can work later on
- It later on install the needed packages and run the mvn package shiping the test practice
### Run stage
- It builds a jar file so we can run the file

## 1-5 

## 1-6

## 1-7

## 1-8

## 1-9

## 2-1  What are testcontainers?
This are Javalibraries that help you run the container during automated test

## 2-2  For what purpose do we need to use secured variables ?
This is because github is by default a public space where everyone can add their own info therefore if you want to add sensible information this way it would be protected and open to the public

