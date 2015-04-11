Loadouts are an array collection of Loadout objects.

## Storage Location
Loadouts are preserved in a data store that is appropriate for the platform.

* Chrome Extension: Chrome Storage API

## Schema

`{
  id: string<guid>,
  name: string,
  items: Array<item>
}`