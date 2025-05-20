# Attacker Endpoints

My personal resume site frequently experiences scans from various bots, which I find to be interesting data. You might find this information useful as well. Feel free to use it to set up a catch-all on your server to thwart these bots.

This list is updated twice daily via a GitHub action, based on data collected from naamloos.dev through a catch-all endpoint.

> [!CAUTION]
> I have stopped filtering endpoints, as the list has become way too big. There may be some false positives and domain-specific (naamloos.dev) that slip through now.

## Format

> [!WARNING]
> This data is provided as-is. It may not be exhaustive or entirely accurate. Use it at your own discretion and risk.

The `endpoints.json` file contains a JSON array with objects that include the following fields:

| Field       | Type    | Description                                                                 |
|-------------|---------|-----------------------------------------------------------------------------|
| endpoint    | string  | The endpoint that the bot attempted to access                               |
| method      | string  | HTTP method: `GET`, `HEAD`, `POST`, `PUT`, `DELETE`, `CONNECT`, `OPTIONS`, `TRACE`, `PATCH` |
| occurrences | integer | The number of times the endpoint was accessed by bots at the time of update |

## Suggested Uses


1. **Blocking Bots**: Configure your web server or firewall to block requests to the endpoints listed in `endpoints.json`.
2. **Monitoring**: Use the data to monitor for suspicious activity by integrating it with your monitoring tools.
3. **Honeypots**: Deploy honeypots on your server to collect more information about bot behavior.
4. **Analytics**: Analyze the data to identify patterns and frequencies of bot attacks.
5. **Enhancing Security**: Leverage the insights from the data to strengthen your web security measures.


