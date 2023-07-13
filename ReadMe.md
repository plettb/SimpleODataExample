## Introduction
This code comes from https://learn.microsoft.com/en-us/odata/webapi-8/getting-started

What I need is trivial to demonstrate: simply rename "Customer.Id" to "RandomProperty" and get it running.

### Background
I have a view in SQL Server that has no key. I've scaffolded it with Entity Framework.
I'd like to expose this view with OData.
Obviously some of the functionality wouldn't be available (e.g. lookups by key, edits), but the filtering, ordering, and selecting should still work.
I don't need "expand"  - my view is flat, but I see no reason that couldn't work as well.
