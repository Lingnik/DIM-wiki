Loadouts are an array collection of Loadout objects.

## Storage Location
Loadouts are preserved in a data store that is appropriate for the platform.

* Chrome Extension: Chrome Storage API

## Schema v1.1

    {
      id: string<guid>,
      name: string,
      items: Array<ids>,
      equip: Array<ids>,
      version: string
    }

## Schema v1.0

    {
      name: string,
      items: Array<ids>
    }