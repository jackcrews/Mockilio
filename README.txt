This project is intended to provide a mock Twilio service to help with automated testing.

When writing automated tests we don't want to call the real service but we do want to make sure our interactions are coded correctly. This is a simple REST service that will mock out behavior in different ways depending on the content sent to it.

For example, the mock may be configured to answer the phone when a number starts with 3 but doesn't answer the phone for any calls starting with 4. 

This will only support the current (2010-04-01) api for now. 