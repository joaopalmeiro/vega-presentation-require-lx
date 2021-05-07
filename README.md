# Plotting the first point w/ the Vega ecosystem.

📍 require('lx') (Lisbon)

📅 Friday, May 8, 2020

## Links

- [Meetup](https://www.meetup.com/require-lx/events/270355425/)
- [Recording](https://youtu.be/dIKl7Mc288Q?t=2020)
- [Slides](https://joaopalmeiro.github.io/vega-presentation-require-lx/)

## Development

- `npm ci`
- `npm start`

## Notes

- [`npm ci`](https://docs.npmjs.com/cli/v7/commands/npm-ci) (alternative to `npm install` to install from the `package-lock.json` file).
- Problems with `gyp` ([source](https://stackoverflow.com/a/60860951))?
  - `xcode-select --print-path`
  - `sudo rm -r -f /Library/Developer/CommandLineTools` (confirm the path with the previous command)
  - `xcode-select --install`
