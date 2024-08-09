Project 1

## Nama Kelompok - Data Divers

1. AMINUDIN
2. SENDHI A RAHMANSYAH
3. HANIFAH RIZKY MUFIIDAH
4. M QORI RAMADHAN NASUTION
5. HAMZAH AL FARISI

## Getting Started

### Prerequisites

Ensure you have the following installed:

- Python 3.7
- pip (Python package installer)

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/hotspoon/project_1
   cd project_1
   ```

2. Create a virtual environment:

   ```sh
   python3 -m venv devEnv
   ```

3. Activate the virtual environment:

   - On Windows:
     ```sh
     .\devEnv\Scripts\activate
     ```
   - On macOS/Linux:
     ```sh
     source devEnv/bin/activate
     ```

4. Install the required packages:
   ```sh
   pip install -r requirements.txt
   ```

### Configuration

1. Update the [`config.json`] file with your database credentials if necessary.

### Running the ETL Process

1. Run the ETL script:
   ```sh
   python main.py
   ```

This will connect to the data source and data warehouse, execute the queries, and ingest the data into the data warehouse.
