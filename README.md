# Sapphire Deno repro

A very tiny sample to reproduce [Sapphire] not working with [Deno]

## Instructions

1. Install [Deno]
1. Copy `.env` and rename the copy to `.env.local`
1. Add your Discord bot token to `.env.local`
1. Run `deno task start` to start the bot

## Debugging

1. Open this project in VSCode
1. Ensure that the [Deno VSCode extension][] is installed
1. Follow steps 1-3 of [the instructions above](#instructions)
1. Press F5 to start debugging

[Sapphire]: https://github.com/sapphiredev/framework
[Deno]: https://deno.com/
[Deno VSCode extension]: https://marketplace.visualstudio.com/items?itemName=denoland.vscode-deno
