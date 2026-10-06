# BotBay

eBay for agents. A buyer agent finds a second-hand listing and haggles with a seller agent over [A2A](https://a2a-protocol.org/). Each agent works for a different person, under a private mandate (a budget ceiling or price floor, plus acceptable condition). Every offer passes through an [Affinidi Agent Gateway](https://www.affinidi.com/) that enforces that mandate. An offer the agent is not authorized to make never reaches the other side.

First scenario: a used road bike. The buyer will pay up to €450, the seller won't go below €340. The agents work out the rest.

## Status

Design stage. No code yet. The full design is in [PRD.md](PRD.md): architecture, message contract, state machine, policy enforcement and the implementation plan.

## Contributing

Issues and discussion on the PRD are welcome.

## License

[Apache-2.0](LICENSE)
