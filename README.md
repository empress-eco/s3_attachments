<div align="center">
  <img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="Project Logo">
  <h1>S3 Attachments: A Seamless File Management Solution</h1>
  <p>
    Automate file uploads and data management with S3 Attachments. 
    <br />
    <a href="https://grow.empress.eco/">Explore the Docs</a>
    ·
    <a href="https://github.com/empress-eco/s3_attachments/issues">Report Bug</a>
    ·
    <a href="https://github.com/empress-eco/s3_attachments/issues">Request Feature</a>
  </p>
</div>

## About The Project

S3 Attachments is a comprehensive tool designed for developers and data specialists to streamline file upload and retrieval processes. It automates file uploads and read functionalities from S3, eliminating manual efforts and increasing efficiency.

### Key Features

- Automatic upload of both public and private files to S3.
- Stream files from S3 upon file view.
- Easily add S3 credentials (AWS key, AWS secret, bucket name, folder name) and migrate existing files via a user-friendly UI.
- Automatic deletion from S3 when a file is removed in the UI.
- Categorically structured file upload for easy search and retrieval.

This project is built with the robust and scalable framework of [Empress](https://Empress.io/).

## Technical Stack and Setup Instructions

### Prerequisites

Ensure you have Empress installed in your system.

### Installation

To set up a development environment, follow these steps:

1. Clone the repository from GitHub:

```sh
git clone https://github.com/empress-eco/s3_attachments.git
```

2. Install the application using the bench command:

```sh
bench get-app s3_attachments
bench install-app s3_attachments
```

## Usage

Open single doctype "S3 File Attachment" and enter your Bucket Name, AWS key, AWS secret, S3 bucket Region name, and Folder Name. You can also choose to migrate existing files to S3 and select the option to delete files from the cloud when they're removed from the UI.

## Contribution Guidelines

We welcome your contributions! Here's how you can help:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License and Acknowledgements

This project is licensed under the MIT License. Your contributions will also be licensed under the MIT License.

We extend our heartfelt thanks to the Empress Community for their foundational contributions and to [Empress](https://empress.eco/) for their unwavering support.