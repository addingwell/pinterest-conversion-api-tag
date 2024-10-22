# Pinterest Conversion API Tag for Google Tag Manager (server-side)

The Pinterest Conversions API Tag allows advertisers to send web events from their servers directly to Conversions API. The tag simplifies dual tracking by triggering both CAPI and the Pixel from a single server-side tag, improving web performance, data governance, and ensuring effective event deduplication.

## Background

The Pinterest Conversion API (CAPI) is essential for overcoming the limitations of the Pinterest Pixel, which has become less effective due to ad blockers and the decline of third-party cookies. Pinterest recommends using both CAPI and the Pixel together for optimal tracking.

Follow our complete guide on [Pinterest CAPI benefits](https://docs.addingwell.com/pinterest-capi/benefits).

## How does the Addingwell tag work?

This template is a tag that reads the standard event schema sent from the client running on a tagging server. It then converts events to the appropriate schema and sends them through the Conversions API. It also allows sending a response to the browser that triggers a call to the Pinterest Pixel. This enables the removal of the Pinterest SDK from the browser side, improving web performance while ensuring event deduplication.

The tag supports only GA4 client.

## Implementation

You can follow our [step-by-step instructions](https://docs.addingwell.com/pinterest-capi/tag-setup).

## How to check received data

Is your tag already live, and you're unsure whether everything is working correctly?

Follow our complete guide on [how to check the received data](https://docs.addingwell.com/pinterest-capi/data-check).

## Reporting Bugs/Feedback

Please raise any issues on GitHub or contact us directly at support@addingwell.com.

## Open Source

Pinterest Conversion API Tag for GTM Server Side is developed and maintained by [Addingwell](https://www.addingwell.com/) under the Apache 2.0 license.
