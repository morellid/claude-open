# claude-open

A static page that hands a link off to the Claude desktop app: `https://morellid.github.io/claude-open/?s=local_<id>` opens `claude://code/needs-input?session=local_<id>`.

Why: Telegram only makes `http(s)` (and `tg:`) links tappable, so notifications about Claude Code sessions waiting for input link here instead of to `claude://` directly. The page holds no data and accepts only a desktop session id (`local_` + up to 64 letters, digits or dashes), so it cannot redirect anywhere else.
