### Lounge DB

This is an open source collection of lounge information for most of the major airports in the United States, and later Canada / Mexico.

The lounge data is organized in the following directory structure:

```
<iata_code>/
  |- lounge.yml
  | ...
  | ...
```

Each lounge has a similar common schema:

```yml
name: The Centurion Lounge
slug: sfo-centurion-lounge-f1
location: Terminal 3, Concourse F, near gate F1 (see directions due to ongoing
  construction)
access:
  - credential: amex_centurion
    restrictions: null
  - credential: amex_platinum
    restrictions: null
  - credential: amex_platinum_business
    restrictions: null
  - credential: amex_platinum_intl
    restrictions: null
  - credential: amex_delta_reserve
    restrictions: null
allowsArrivals: false
operator: American Express
alliance: None
allianceLevel: None
allianceMembers: []
latitude: "37.617261147191066"
longitude: "-122.38793134689332"
terminal: Terminal 3
hours:
  days:
    - day: Monday
      startTime: 05:00
      endTime: 23:00
    - day: Tuesday
      startTime: 05:00
      endTime: 23:00
    - day: Wednesday
      startTime: 05:00
      endTime: 23:00
    - day: Thursday
      startTime: 05:00
      endTime: 23:00
    - day: Friday
      startTime: 05:00
      endTime: 23:00
    - day: Saturday
      startTime: 05:00
      endTime: 23:00
    - day: Sunday
      startTime: 05:00
      endTime: 23:00
  timezone: America/Los_Angeles
amenities:
  - bathroom
  - bar
  - business_center
  - complimentary_wifi
  - showers
  - family_room
  - air_conditioning
  - accessible
  - press
  - tv
  - fim
foodOptions:
  - Complimentary Cold Buffet
  - Complimentary Hot Buffet
drinks:
  - Complimentary Soft Drinks
  - Complimentary Full Bar
closed: false
```

### Contributing

All of the lounge data in this repository is specifically in YAML format so it easier to contribute and make changes. If you notice anything wrong, or would like to contribute new lounge information, please feel free to submit a PR.

### License
[Mozilla Public License Version 2.0](./LICENSE.md)