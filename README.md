
# Proxy Test Script <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/82/Gnu-bash-logo.svg/2560px-Gnu-bash-logo.svg.png" alt="Bash Logo" width="125"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Python-logo-notext.svg/121px-Python-logo-notext.svg.png" alt="Python" width="80">

This script allows you to test a list of proxies to determine their availability. It checks if the proxies are working by sending requests to a specified domain. You can choose the domain for testing or use the default domain if not specified.

## Prerequisites

For Python script:
- Python 3.x installed on your machine
- Required Python packages installed. You can install them by running:
  ```
  pip install -r requirements.txt
  ```

For Bash script:
- cURL command-line tool installed on your machine

## Usage

### Python Script

1. Clone the repository to your local machine using the following command:
   ```
   git clone https://github.com/5h4kun1/proxy-test-script.git
   ```

2. Change to the cloned repository's directory:
   ```
   cd proxy-test-script
   ```

3. Prepare the proxy files:
   - Create two text files named `http.txt` and `https.txt`.
   - Add one proxy IP address per line in each file.

4. Run the script:
   ```
   python script.py
   ```

5. Follow the on-screen instructions to select the file to test and choose a domain for testing. If no domain is provided, the script will use the default domain.

6. The script will display an animation indicating the progress of the proxy testing. Once completed, it will save the results in a file named `results.txt`.

### Bash Script

1. Clone the repository to your local machine using the following command:
   ```
   git clone https://github.com/5h4kun1/proxy-test-script.git
   ```

2. Change to the cloned repository's directory:
   ```
   cd proxy-test-script
   ```

3. Prepare the proxy files:
   - Create two text files named `http.txt` and `https.txt`.
   - Add one proxy IP address per line in each file.

4. Run the script:
   ```
   ./script.sh
   ```

5. Follow the on-screen instructions to select the file to test and choose a domain for testing. If no domain is provided, the script will use the default domain.

6. The script will display an animation indicating the progress of the proxy testing. Once completed, it will save the results in a file named `results.txt`.

## Domain Options

The following domain options are available for testing:

1. www.google.com
2. www.example.com
3. www.yahoo.com
4. www.microsoft.com
5. www.facebook.com
   ...

You can choose any of these domains by providing the corresponding number during the script execution.

## License

This project is licensed under the [MIT License](LICENSE).
<img src="https://cdn.dnaindia.com/sites/default/files/styles/full/public/2016/12/05/525927-automation.jpg" alt="Image" />

