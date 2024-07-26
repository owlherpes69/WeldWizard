# WeldWizard

WeldWizard is a versatile job pricing tool for welding and metal fabrication projects. It helps fabricators and businesses accurately calculate the costs associated with projects, including material, labor, equipment, and consumables.

## Features

- **CLI and GUI**: Offers both a command-line interface and a graphical user interface.
- **Cost Calculation**: Accurately calculates costs for materials, labor, equipment usage, and consumables.
- **Customizable**: Easily configurable to suit different types of projects and business needs.
- **Project Management**: Save and manage multiple projects with detailed breakdowns.

## Getting Started

### Prerequisites

- **Python 3.x**: Ensure you have Python installed on your system. You can download it from [python.org](https://www.python.org/downloads/).
- **Virtual Environment**: It is recommended to use a virtual environment to manage dependencies.

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/WeldWizard.git
   cd WeldWizard
2. Setup virtual environment:
python3 -m venv env
source env/bin/activate  # On Windows, use `env\Scripts\activate`
3. Install the dependencies:
pip install -r requirements.txt

### Configuration
1. Environment Variables: Copy '.env.example' to '.env' and update the variables as needed:
cp config/.env.example config/.env
2. Database setup: ensure your database is set up and accessable, then configure the 'config.yaml' file with your database credentials.

### usage
CLI 

to start the CLI version: 
python src/cli/main.py

GUI
[GUI instructions will be added once the GUI is implemented]

### Development 
running tests

to run the tests, use: 
pytest

### Contributing
We welcome contributions! Please read our CONTRIBUTING.md guide for details on our code of conduct and the process for submitting pull requests.

### License
This project is licensed under the MIT License - see the LICENSE file for details.

### Acknowledgments
Thanks to all the contributors and the open-source community for their valuable work and support.


### Key Sections

- **Project Overview**: A brief introduction to the tool and its main features.
- **Getting Started**: Instructions for setting up the development environment, including cloning the repository, setting up a virtual environment, and installing dependencies.
- **Configuration**: Guidance on setting environment variables and configuring the database.
- **Usage**: Basic instructions for running the CLI (and GUI when available).
- **Development**: Instructions for running tests and contributing to the project.
- **License**: Information about the project's license.
- **Acknowledgments**: A space to thank contributors or mention any resources used.

### Customization

Feel free to customize the content based on the specific details and progress of your project. As the project evolves, you can update the README to reflect new features, changes, and other important information.
