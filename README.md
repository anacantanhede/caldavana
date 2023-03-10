# CalDAV compatible API implementation

The objective of this project is to implement API's which are compatible with the CalDAV specification.

The main initial focus are the resources which will be useful to create a TODO application.

## CalDAV Standard

`Calendaring Extensions to WebDAV (CalDAV)` is a standard specified on [RFC 4791](https://www.rfc-editor.org/rfc/rfc4791), which defines a way to access, manage and share calendaring and scheduling information.

Some notes from the specification:

1. _a CalDAV calendar is modeled as a WebDAV collection with a defined structure_.
2. _each calendar collection contains a number of resources representing calendar objects as its direct child resource_.
3. _Each resource representing a calendar object (event, to-do, journal entry, or other calendar components) is called a "calendar object resource"_.
4. _Each calendar object resource and each calendar collection can be individually locked and have individual WebDAV properties_



