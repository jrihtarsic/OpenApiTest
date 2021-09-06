 <h1>Predefined Signals</h1>
The following pre-defined signals MUST be supported by both the client and the server implementing the Messaging API Specification:
<h2 id="message-accepted">Message Accepted</h2>
Status: 202<BR/>
Type: https://raw.githubusercontent.com/isa2-api4ips/rest-api-profile/messaging-api-specification/predefined-signal.html#message-accepted<BR/>
Detail: Sent when the message is properly validated. It may include a status monitor that can provide the user with an
estimate of when the request will be fulfilled (see [RFC7231])<BR/>

<h2 id="message-validation-failed">Validation Failed</h2>
Status: 400<BR/>
Type: https://raw.githubusercontent.com/isa2-api4ips/rest-api-profile/messaging-api-specification/predefined-signal.html#message-validation-failed<BR/>
Detail: Sent when the message fails the validation process<BR/>

<h2 id="invalid-message-id">Invalid or Duplicate Message ID</h2>
Status: 400<BR/>
Type:https://raw.githubusercontent.com/isa2-api4ips/rest-api-profile/messaging-api-specification/predefined-signal.html#invalid-message-id<BR/>
Detail: Sent when the MessageId is not valid<BR/>

<h2 id="invalid-message-signature">Invalid Message Signature</h2>
Status: 400<BR/>
Type: https://raw.githubusercontent.com/isa2-api4ips/rest-api-profile/messaging-api-specification/predefined-signal.html#invalid-message-signature<BR/>
Detail: Sent when the message signature cannot be verified<BR/>

<h2 id="invalid-addressing">Invalid Addressing</h2>
Status: 400<BR/>
Type: https://raw.githubusercontent.com/isa2-api4ips/rest-api-profile/messaging-api-specification/predefined-signal.html#invalid-addressing<BR/>
Detail: Sent when the Original Sender or Final Recipient(s) cannot be resolved<BR/>

<h2 id="invalid-format">Invalid Message Format</h2>
Status: 400<BR/>
Type: https://raw.githubusercontent.com/isa2-api4ips/rest-api-profile/messaging-api-specification/predefined-signal.html#invalid-format<BR/>
Detail: Sent when the message format does not adhere to the specification<BR/>

<h2 id="no-final-recipient">No final recipient configured for the pulling user</h2>
Status: 400<BR/>
Type: https://raw.githubusercontent.com/isa2-api4ips/rest-api-profile/messaging-api-specification/predefined-signal.html#pull/no-final-recipient<BR/>
Detail: Sent when the server cannot resolve/match the pulling user to a final recipient<BR/>

<h2 id="no-message-found">No Message Found</h2>
Status: 404<BR/>
Type: https://raw.githubusercontent.com/isa2-api4ips/rest-api-profile/messaging-api-specification/predefined-signal.html#pull/no-message-found<BR/>
Detail: Sent when no message is found that maps to the pull request<BR/>

<h2 id="unauthorized">Unauthorized</h2>
Status: 401<BR/>
Type: https://raw.githubusercontent.com/isa2-api4ips/rest-api-profile/messaging-api-specification/predefined-signal.html#pull/unauthorized<BR/>
Detail: Sent when the pull request is unauthorized<BR/>

<h2 id="message-ready">Message Response is ready</h2>
Status: 201<BR/>
Type: https://raw.githubusercontent.com/isa2-api4ips/rest-api-profile/messaging-api-specification/predefined-signal.html#message-ready<BR/>
Detail: An HTTP Request following [RFC7807] MUST be sent when a message response is ready to be retrieve<BR/>

<h2 id="internal-server-error">Internal Server Error</h2>
Status: 500<BR/>
Type:https://raw.githubusercontent.com/isa2-api4ips/rest-api-profile/messaging-api-specification/predefined-signal.html#internal-server-error<BR/>
Detail: The server encountered an unexpected condition that prevented it from fulfilling the request<BR/>
