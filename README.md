big_data_taxi — Setup Instructions

1. Set the Python version to 3.8.12.

2. Create a virtual environment:
   ```bash
   python -m venv myenv
   ```

4. Activate the virtual environment:
   - On Linux/macOS:
        ```bash

     source myenv/bin/activate
        ```
   - On Windows:
        ```bash

     myenv\Scripts\activate
        ```

5. Create a folder named "datasets":
      ```bash

   mkdir datasets
   ```
7. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

9. Download the dataset:
   Visit: https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
   Select year 2025, then download:
   "February - Green Taxi Trip Records (PARQUET format)"

10. Move the downloaded file into the "datasets" folder.
