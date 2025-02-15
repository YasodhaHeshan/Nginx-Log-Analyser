# Nginx-Log-Analyser

This project contains a shell script to analyze Nginx access logs and provide useful insights such as the top 5 IP addresses with the most requests, the top 5 most requested paths, the top 5 response status codes, and the top 5 user agents.

## Files

- `analyze_logs.sh`: The shell script to analyze the Nginx access logs.
- `nginx-access.log`: Sample Nginx access log file.

## Usage

1. Ensure the `nginx-access.log` file is in the same directory as the `analyze_logs.sh` script.
2. Open a terminal and navigate to the directory containing the script.
3. Make the script executable (if necessary):
   ```sh
   chmod +x analyze_logs.sh
   ```
4. Run the script:
   ```sh
   ./analyze_logs.sh
   ```

The script will output the following information:

- Top 5 IP addresses with the most requests
- Top 5 most requested paths
- Top 5 response status codes
- Top 5 user agents

## Example Output

```
Top 5 IP addresses with the most requests:
45.76.135.253 - 1000 requests
142.93.143.8 - 600 requests
178.128.94.113 - 50 requests
43.224.43.187 - 30 requests
178.128.94.113 - 20 requests

Top 5 most requested paths:
/api/v1/users - 1000 requests
/api/v1/products - 600 requests
/api/v1/orders - 50 requests
/api/v1/payments - 30 requests
/api/v1/reviews - 20 requests

Top 5 response status codes:
200 - 1000 requests
404 - 600 requests
500 - 50 requests
401 - 30 requests
304 - 20 requests

Top 5 user agents:
Mozilla/5.0 - 1000 requests
DigitalOcean Uptime Probe 0.22.0 - 600 requests
StatusCake - 50 requests
Go-http-client/1.1 - 30 requests
Custom-AsyncHttpClient - 20 requests

## Project Repository

You can find more project details at:
[https://roadmap.sh/projects/nginx-log-analyser](https://roadmap.sh/projects/nginx-log-analyser)