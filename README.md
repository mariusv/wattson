# Wattson

**Your Smart Energy Assistant**
Open-source dashboard to track your home's electricity usage, solar efficiency, heat pump stats, and energy costs — powered by real-time data, Modbus/MQTT integration, and AI insights.

---

## Features

### Input & Tracking
- Input your electricity price (with support for future price changes)
- Add costs for green energy equipment (solar panels, batteries, heat pumps)
- Log monthly meter readings (electricity & water)
- Upload energy invoices for AI-based analysis

### Real-Time & Historical Monitoring
- Read data from Modbus-enabled devices (e.g., Victron, heat pumps)
- Support for MQTT sensors and other integrations
- Use energy company meter readings as the billing source of truth
- Separate heat pump consumption by heating and hot water

### Graphs & Insights
- Track solar vs. grid usage and energy independence (daily/monthly/yearly)
- Cost and ROI breakdowns
- Visualize COP (coefficient of performance) for heat pumps
- Forecast solar production using weather data + AI

### AI-Powered
- Use your own OpenAI or Claude tokens
- AI-based energy invoice analysis and anomaly detection
- Configurable AI temperature (default: 0.2 for factual accuracy)

### Modular by Design
- Plugin support for new devices via MQTT or Modbus
- Config-as-code (YAML/JSON)
- Webhooks, export/import settings, REST/GraphQL API (planned)

---

## Getting Started

Coming soon...

- `docker-compose up`
- Web dashboard accessible at `http://localhost:8080`

---

## Vision

Wattson aims to be the most accessible and focused energy monitoring app in the open-source space — a beautiful alternative to overly complex solutions.

---

## License

MIT — feel free to use, fork, contribute, and share.

