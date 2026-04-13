# Homik Tracker

**Live site:** [czywyjebalohomika.xyz](https://czywyjebalohomika.xyz)

---

## What is this?

A status website mainly for [szkopul.edu.pl](https://szkopul.edu.pl), and other judges. They are commonly known in the community for having outages. This website tracks, ranks and notifies of outages.

### *czy wyjebalo homika?*

## Features

- Current status
- Historical data
- Ranking
- Notifies when an outage is detected
- Open API

## Tech stack

- **Node.js**

## Running locally

```bash
git clone https://github.com/matthberendt/homik-tracker
cd homik-tracker
npm install
npm install express
npm install pm2
pm2 start server.js --name "homik-tracker"
```
DEFAULT PORT: 6741

## Contributing

Feel free to contribiute.

## License

Apache-2.0 license

