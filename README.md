# action-build-stm32
This action builds the release and debug for the STM32CubeIDE project 

# Inputs 
project-path 
Required path to the STM .project file

project-target
Required Target in the STM32CubeIde project file to build. Format: target/[build-configuration]
note: When no build-configuration is given all the projects configuration are build


# Example
- uses: gfriedholm/action-build-stm32@v11.0
  with:
    project-path: STM
    project-target: 'stm_app/Debug' 

