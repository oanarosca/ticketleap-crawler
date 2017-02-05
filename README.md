# TickeLeap crawler and converter

Created during GCI16 for FOSSASIA. Given a query, it scrapes the [TicketLeap](https://ticketleap.com) website
and then converts the data to match the [Open Event](https://github.com/fossasia/open-event) format.

## Usage

Run the following command: `path/to/python3 scrape_ticketleap.py [SEARCH QUERY]`

## Requirements

The `requirements.txt` file contains all the necessary modules for the script to run. Using `pip install -r requirements.txt`, the
following dependencies will be installed:

```
requests==2.12.1
lxml==3.6.4
beautifulsoup4==4.5.1
```
