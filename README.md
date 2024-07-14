Github Pages link: [TinDog](https://singhsakshi-21.github.io/static)


```mermaid
graph TD
    subgraph Frontend
        A1[HTML, CSS, JavaScript]
        A2[Responsive UI]
        A3[Mapping with Leaflet/OpenLayers]
        A4[Voice Capture in JavaScript]
    end

    subgraph Backend
        B1[Python-based Flask API]
        B2[Offline Whisper Model for Audio Transcription]
        B3[Command Parsing for Geospatial Commands]
    end

    subgraph Interaction
        C1[Audio Commands from Frontend to Backend]
        C2[Transcribed Commands from Backend to Frontend]
        C3[JavaScript Executes Map Updates in Real Time]
    end

    A1 --> A2
    A2 --> A3
    A3 --> A4
    A4 --> C1
    C1 --> B1
    B1 --> B2
    B2 --> B3
    B3 --> C2
    C2 --> C3
    C3 --> A3
