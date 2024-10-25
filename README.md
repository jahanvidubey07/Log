# LOG

**LOG** is a server-side program designed to monitor a specified log file and stream updates to a web-based client in real-time. The client displays the most recent updates as they happen without requiring page refreshes, making it easy to keep track of the latest log entries continuously.

## Features

- **Real-Time Log Updates**: Streams updates from the log file to the web client as soon as they occur.
- **Initial View**: Shows the last 10 lines of the log file upon loading the page.
- **Web-Based Client**: Accessible via `http://localhost/log`, providing an easy way to monitor logs from a browser.
- **No Refresh Needed**: The client receives updates automatically, so the page only needs to load once.

## Getting Started

### Prerequisites

- Node.js
- WebSocket library or a similar real-time technology to enable live data streaming.

### Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/LOG.git
    cd LOG
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Start the server:
    ```bash
    npm start
    ```

### Usage

1. Run the application and navigate to `http://localhost/log` in your web browser.
2. The client will display the last 10 lines of the monitored log file upon loading.
3. Updates will be streamed to the client in real-time, so you’ll see any new log entries as they are added.

### Configuration

You may configure the file path of the log file to be monitored in the `config.js` file.

## Technology Stack

- **Backend**: Node.js, WebSocket or other streaming tech
- **Frontend**: HTML, CSS, JavaScript

## License

This project is licensed under the MIT License.
