### lich-bot

This repo publishes the mirror for [lich-bot.github.io](https://lich-bot.github.io)/[lich-bot.dev](https://lich-bot.dev) at [lich-bot.com](https://lich-bot.com). This is done by syncing [`lich-bot/lich-bot.github.io/master` branch](https://github.com/lich-bot/lich-bot.github.io/tree/master) with [`lich-bot/lich-bot.com/mirror` branch](https://github.com/lich-bot/lich-bot.com/tree/mirror), except the [`CNAME`](https://github.com/lich-bot/lich-bot.com/blob/mirror/CNAME) file, which **must** always be set to `lich-bot.dev`. When a `push` is done on `lich-bot/lich-bot.github.io` repo `master` branch, then [`lich-bot/lich-bot.github.io/trigger lich-bot com_sync` workflow](https://github.com/lich-bot/lich-bot.github.io/blob/master/.github/workflows/trigger_lich-bot_com_sync.yml) will automatically trigger a sync by dispatching the [`lich-bot/lich-bot.com/sync_lich-bot_com` workflow](https://github.com/lich-bot/lich-bot.com/blob/master/.github/workflows/sync_lich-bot_com.yml).
##
