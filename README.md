# deniz-blue/events-data

Repository for events in [@evnt](https://github.com/deniz-blue/evnt) format

## Contributing

Feel free to contribute data into this repository!

The scope of the events listed here are any events that are *accessible to the public*.

If you use VSCode, you should get schema validation automatically. Otherwise, use [this json schema (url)](https://raw.githubusercontent.com/deniz-blue/evnt/refs/heads/main/event-data.schema.json) for validation.

## Folder Structure

```
events/
└─ <year>/
   └─ <category>/
      └─ <abbr>.json
```

- `<year>` is the year where the event takes place
  - If the date is unknown, use the *current year*; until an instance date changes, keep the same year
  - If the event spans multiple years, use the lowest year
- `<category>` is a generic category for the event; doesn't matter that much
- `<abbr>` is an abbreviation of the event; if possible, use a distinguishing identifier (i.e `fosdem26` instead of `fosdem`); if the abbreviation is too generic, you may spell out the entire name of the event
- Use kebab-case if neccesary

## Events

This section is auto-generated

<!-- EVENTS LIST START -->
if you see this deniz fucked up
<!-- EVENTS LIST END -->
