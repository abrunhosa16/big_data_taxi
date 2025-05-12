big_data_taxi — Setup Instructions

1. Set the Python version to 3.8.12.

2. Create a virtual environment:
   python -m venv myenv

3. Activate the virtual environment:
   - On Linux/macOS:
     source myenv/bin/activate
   - On Windows:
     myenv\Scripts\activate

4. Create a folder named "datasets":
   mkdir datasets

5. Install dependencies:
   pip install -r requirements.txt

6. Download the dataset:
   Visit: https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
   Select year 2025, then download:
   "February - Green Taxi Trip Records (PARQUET format)"

7. Move the downloaded file into the "datasets" folder.
