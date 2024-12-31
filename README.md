# Attacker Endpoints

My personal resume site experiences frequent scans, which I find to be interesting data. You might find it useful as well. Feel free to use this information to set up a catch-all on your server to thwart these bots.

This list is updated twice daily via a GitHub action, based on data collected from naamloos.dev through a catch-all endpoint. While I strive to filter out invalid endpoints, some "valid" endpoints may still slip through.

> **WARNING:** This data is provided as-is and may not be exhaustive or completely accurate. Use it at your own risk.


> **NOTE:** While I do indeed have a real-time endpoint set up on my site, please use the list provided through GitHub instead.

## Format

The `endpoints.json` file contains a JSON array with objects that include the following fields:

| Field      | Type    | Description                                                   |
|------------|---------|---------------------------------------------------------------|
| endpoint   | string  | The endpoint that the bot attempted to access                 |
| method     | string  | HTTP method: `GET`, `HEAD`, `POST`, `PUT`, `DELETE`, `CONNECT`, `OPTIONS`, `TRACE`, `PATCH` |
| occurrences | integer | The number of occurrences at the time of the update           |
