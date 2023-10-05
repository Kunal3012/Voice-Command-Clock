# Voice Command Clock

**Author:** Kunal Yadav  
**Email:** mailmekunal2002@gmail.com

## Abstract

The Voice Command Clock project leverages Azure Cognitive Services to create a voice-controlled clock that responds to spoken commands. It uses Azure's Speech Service to transcribe and synthesize speech. The clock can provide the current time upon user request, making it a convenient and accessible timekeeping tool.

## Introduction

Voice-activated devices are becoming increasingly popular for their ease of use and accessibility. This project focuses on building a voice command clock that utilizes Azure Cognitive Services for speech recognition and synthesis. Users can interact with the clock by asking for the current time, and the clock responds in audio format.

## Methods

### Configuration

- The project loads configuration settings, such as the Cognitive Services key and region, from environment variables using the `dotenv` library.

### Speech Service

- Azure's Speech Service is configured using the provided key and region.
- The clock continuously listens for user input.
- When a command is recognized, it is transcribed and processed.

### Time Reporting

- If the recognized command is "What time is it?" the clock responds with the current time.
- The response is synthesized into speech using Azure's Speech Synthesis service.
- The clock provides the time in audio format.

## Results

- The Voice Command Clock successfully recognizes the command "What time is it?" and responds with the current time in audio format.
- It utilizes Azure Cognitive Services to enable voice interaction and time reporting.

## Conclusion

The Voice Command Clock project demonstrates the integration of speech recognition and synthesis to create a voice-controlled clock. This application has potential use cases in various scenarios where hands-free interaction with time information is desired.
