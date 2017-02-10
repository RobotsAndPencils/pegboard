# Pegboard

Pegboard sets up your tools.

## Terms

- Pegboard: A base script that sets up common tools
- Peg: A script that extends your development environment's capabilities with a particular set of tools

## Usage

Run `pegboard` to setup the base tools.

Install additional pegs with `pegboard peg_name_one peg_name_two`. You can see a list of included pegs in the pegs/ directory.

Pegboard is designed to be idempotent, which is a fancy way of saying that you can run it multiple times without breaking anything. It tries to "install or update" whenever it can, which means there's only one thing you need to run to get your development environment going and keep it that way.

## Contributing

Pegboard is what we use everyday. If you have some ideas for new tools that everyone on our team could use, we'd love to hear about it. We might not merge everything, but you can always keep your own fork that works for yourself or your team.

If you'd like to set up your development environment for work at Robots and Pencils, check out our [jobs](https://robotsandpencils.com/jobs) page.

pegboard started as a fork of [laptop](https://github.com/thoughtbot/laptop) and has grown into its own.

