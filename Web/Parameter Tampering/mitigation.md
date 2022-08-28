1. Do not rely on user-originating input in the application when performing operations in the system.

1. Validate every input on the server side as soon as it is received.

1. Store the user’s identity information and privileges in the session memory on the server. After successful authentication, validate the user's privileges in accordance with the session identifier provided in the request.
