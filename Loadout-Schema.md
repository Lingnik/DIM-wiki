Loadouts are an array collection of Loadout objects.

### Storage Location
Loadouts are preserved in a data store that is appropriate for the platform.

* Chrome Extension: Chrome Storage API

### Schema v2.0

    {
      id: string,
      name: string,
      classType: number,
      items: Array<{ 
        id: string, 
        hash: number,
        amount: number,
        equipped: bool
      }>,
      version: string
    }

### Schema v1.0

    {
      name: string,
      items: Array<id:string>
    }