#  Metadata Project

This project is designed to extract and manage metadata from audio files. Below is an overview of the project structure and the purpose of each main directory.

## Project Structure

### cmd

The `cmd` folder is the main entry point for two different applications that are part of the audio metadata project:

1. API
2. CLI

This folder contains the necessary code to initialize and run both the API and command-line interface applications.

### extractors

The `extractors` folder holds packages that extract metadata from audio files. Initially, we will start with two extractor packages:

1. tags
2. transcript

As the project grows, more extractor packages may be added to this folder.

### models

The `models` folder contains all the structs for the domain entities. The main entities include:

1. audio
2. metadata

Each of the extractors may also have its own data model, which will be stored in this folder.

### services

The `services` folder contains both existing and new services for the project. Three main services have been defined:

1. Metadata (extraction) service
2. Transcript review service
3. Event listener service
    - This service listens for processing events and outputs notifications.

### storage

The `storage` folder contains:

1. The interface for storage operations
2. Individual implementations for different storage solutions

## Getting Started

(Add information about how to set up and run the project, including any dependencies or configuration steps.)

## Contributing

(Add guidelines for contributing to the project, if applicable.)

## License

(Add license information for the project.)