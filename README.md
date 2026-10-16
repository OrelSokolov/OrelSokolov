# Hi, I'm Oleg Orlov 👋

> The nickname **OrelSokolov** is a silly pun I came up with as a kid and
> never changed since: the given name **Orel** (Орёл — "eagle") + the
> surname **Sokolov** (Сокол — "falcon") — two birds of prey stitched
> together in English. Younger me couldn't invent anything better, and it
> just stuck. 🦅

I build **CRails** — a from-scratch port of the Ruby on Rails ecosystem to
**Crystal**, verified gem-by-gem against the originals with oracle test
suites (behavior recorded from the real Ruby gems, replayed byte-for-byte
in Crystal). Around it: FFI bridges to Python/Ruby/R, ports of C
libraries, GUI experiments and desktop tooling.

## 💖 Support my work

- Donate (contact me: orelcokolov@gmail.com)
- Hire me (the same email: orelcokolov@gmail.com)
- Or make pull requests — to make these projects better

## 🛤 CRails — Rails on the most beautiful compiled language!

**Framework core**

- [crails](https://github.com/OrelSokolov/crails) — the CRails umbrella (boot, railties, generators)
- [active_support.cr](https://github.com/OrelSokolov/active_support.cr) — ActiveSupport 8.1.4: core_ext, Duration, Inflector, Concern, Notifications, cache stores, I18n, TimeWithZone
- [active_record.cr](https://github.com/OrelSokolov/active_record.cr) — ActiveRecord 8.1.4 for PostgreSQL: Relation, associations, validations, callbacks, transactions, migrations, encryption
- [action_pack.cr](https://github.com/OrelSokolov/action_pack.cr) — ActionPack 8.1.4: controllers, routing, strong params, cookies/CSRF, HTTP caching, Live/SSE streaming
- [action_view.cr](https://github.com/OrelSokolov/action_view.cr) — ActionView 8.1.4: ERB, layouts/partials, FormBuilder, Vite integration
- [action_mailer.cr](https://github.com/OrelSokolov/action_mailer.cr) — ActionMailer 8.1.4 + a minimal `mail`-gem port (MIME, SMTP)
- [action_cable.cr](https://github.com/OrelSokolov/action_cable.cr) — ActionCable port
- [action_mailbox.cr](https://github.com/OrelSokolov/action_mailbox.cr) / [action_text.cr](https://github.com/OrelSokolov/action_text.cr) — ActionMailbox / ActionText ports
- [active_storage.cr](https://github.com/OrelSokolov/active_storage.cr) — ActiveStorage port
- [active_backup.cr](https://github.com/OrelSokolov/active_backup.cr) — backup layer for the stack
- [importmap.cr](https://github.com/OrelSokolov/importmap.cr) — importmap-rails 2.2.3 (pin DSL + tag helpers)
- [jbuilder.cr](https://github.com/OrelSokolov/jbuilder.cr) — jbuilder 2.14.1 JSON builder + view integration
- [turbo.cr](https://github.com/OrelSokolov/turbo.cr) — Hotwire Turbo layer, speaks the Rails Turbo protocol
- [live_view.cr](https://github.com/OrelSokolov/live_view.cr) — Phoenix LiveView layer

## 🤖 AI Agents

- [h2code](https://github.com/byOrlov/h2code) — lightweight coding agent written in Crystal
- [h2voice](https://github.com/OrelSokolov/h2voice) — Audio To Text converter (see [h2code.dev](https://h2code.dev))
- [action_mcp.cr](https://github.com/OrelSokolov/action_mcp.cr) / [active_agent.cr](https://github.com/OrelSokolov/active_agent.cr) — MCP and agent layers of CRails

**Jobs & queues**

- [kiq.cr](https://github.com/OrelSokolov/kiq.cr) — Sidekiq 8.1.7 port with batches and DAG pipelines
- [sidekiq_dags.cr](https://github.com/OrelSokolov/sidekiq_dags.cr) — sidekiq-dags port (batches + DAG pipelines, SVG visualizer)
- [active_job.cr](https://github.com/OrelSokolov/active_job.cr) — ActiveJob port with a solid_queue-style PG queue and Redis adapter

**Auth & authorization**

- [devise.cr](https://github.com/OrelSokolov/devise.cr) — Devise 4.9.4: all model modules, controllers/routes, mailer, OmniAuth, JWT
- [devise_i18n.cr](https://github.com/OrelSokolov/devise_i18n.cr) — devise-i18n 1.16.1: 73 community locales
- [cancancan.cr](https://github.com/OrelSokolov/cancancan.cr) — CanCanCan 3.6.1 abilities + `accessible_by` scope extraction
- [rolify.cr](https://github.com/OrelSokolov/rolify.cr) — rolify 6.0.1 role management

**Testing**

- [factory_bot.cr](https://github.com/OrelSokolov/factory_bot.cr) — factory_bot 6.5.6 fixtures
- [capybara.cr](https://github.com/OrelSokolov/capybara.cr) — Capybara 3.40 system testing on a homegrown CDP client

**More Rails-ecosystem gems**

- [rails_settings_cached.cr](https://github.com/OrelSokolov/rails_settings_cached.cr) — rails-settings-cached 2.9.5 (Psych-compatible YAML storage)
- [will_paginate.cr](https://github.com/OrelSokolov/will_paginate.cr) — will_paginate 4.0.1
- [counted](https://github.com/OrelSokolov/counted) — fast PostgreSQL COUNT for Ruby on Rails on big tables

## 🔗 FFI: other languages from Crystal

- [pycall.cr](https://github.com/OrelSokolov/pycall.cr) — CPython from Crystal over libpython (port of the pycall gem)
- [rubycall.cr](https://github.com/OrelSokolov/rubycall.cr) — MRI Ruby from Crystal over libruby
- [rcall.cr](https://github.com/OrelSokolov/rcall.cr) — R from Crystal over libR (design stage)

## 📚 Ports of C libraries & formats

- [freetype.cr](https://github.com/OrelSokolov/freetype.cr) — font rendering layer
- [nanosvg.cr](https://github.com/OrelSokolov/nanosvg.cr) — 1:1 port of nanosvg
- [brotli.cr](https://github.com/OrelSokolov/brotli.cr) — Brotli compressor for WOFF font rendering
- [mathjax.cr](https://github.com/OrelSokolov/mathjax.cr) — LaTeX math → SVG rendering

## 💎 Ruby gem ports & bridges beyond Rails

- [highlight.cr](https://github.com/OrelSokolov/highlight.cr) — highlight.js 11.12.0, byte-identical HTML output
- [rqrcode.cr](https://github.com/OrelSokolov/rqrcode.cr) — rqrcode 2.2.0: QR encoding + HTML/ANSI/SVG/PNG
- [net_ssh.cr](https://github.com/OrelSokolov/net_ssh.cr) — net-ssh 7.3 API over libssh2 + sshkey + bcrypt_pbkdf
- [tron.cr](https://github.com/OrelSokolov/tron.cr) — tron.rb 1.2.4: TRON crypto core, TronGrid client, Solidity ABI, protobuf
- [os.cr](https://github.com/OrelSokolov/os) — port of the Ruby `os` gem (same API)
- [uname](https://github.com/OrelSokolov/uname) — uname access for Crystal, naive implementation
- [ruby-try](https://github.com/OrelSokolov/ruby-try) — Rails `try()` for plain Ruby, extended with `try?()` — 130k downloads on RubyGems since 2014
- [crystalize](https://github.com/OrelSokolov/crystalize) — very naive Ruby → Crystal converter, an experiment from 2019, just a draft (before the AI era)
- [icr.cr](https://github.com/OrelSokolov/icr.cr) — IRB-like REPL for Crystal (0.2 s response delay)

## 🖥 GUI, terminal & desktop

- [egui.cr](https://github.com/OrelSokolov/egui.cr) — cross-platform GUI for Windows, Mac, Linux, Android, iOS
- [positron.cr](https://github.com/OrelSokolov/positron.cr) — cross-platform Crystal GUI framework (Linux/Windows/macOS), an Electron alternative built on WebKit
- [h2term.cr](https://github.com/OrelSokolov/h2term.cr) — GUI terminal with sidebar (Crystal)
- [h2term](https://github.com/OrelSokolov/h2term) — GUI terminal with sidebar (Rust implementation)
- [kodkod](https://github.com/OrelSokolov/kodkod) — tiny GUI code editor with syntax highlight, Windows, Mac, Linux
- [mdview](https://github.com/OrelSokolov/mdview) — GUI Markdown viewer (Bun + Webview), naive Markdown implementation
- [sysinfo.cr](https://github.com/OrelSokolov/sysinfo.cr) — system info for Crystal: RAM, CPU, NETWORK, VRAM
- [serverx.cr](https://github.com/OrelSokolov/serverx.cr) — high-performance HTTP/1.1 web server in Crystal, designed on nginx ideas with ZeroCopy
- [cedar-folder-size-analyzer](https://github.com/OrelSokolov/cedar-folder-size-analyzer) — folder size analyzer for Windows & Ubuntu (Rust)
- [bitlocker-detector](https://github.com/OrelSokolov/bitlocker-detector) — detect BitLocker sections on HDD/SSD (Rust), experimental
- [deepseek-history-viewer](https://github.com/OrelSokolov/deepseek-history-viewer) — viewer & search over DeepSeek chat history (Rust); a handy 2025 utility for browsing AI conversations and a hobby project

## 🌍 Web, docs & misc

- [crystal-shards.online](https://github.com/OrelSokolov/crystal-shards.online) — Crystal shards catalog
- [orelsokolov.github.io](https://github.com/OrelSokolov/orelsokolov.github.io) — CV
- [milewski-ctfp-pdf-russian](https://github.com/OrelSokolov/milewski-ctfp-pdf-russian) — «Category Theory for Programmers» by Bartosz Milewski, Russian translation (PDF)
- [SovietBookFont](https://github.com/OrelSokolov/SovietBookFont) / [sovietbook-font](https://github.com/OrelSokolov/sovietbook-font) — шрифт из старых советских книг (partially ported)
- [Raf-1-schematic](https://github.com/OrelSokolov/Raf-1-schematic) — schematics for my robot with an ultrasonic sensor (Prolog, 2014)
- [redmibook-dummy-output-fix](https://github.com/OrelSokolov/redmibook-dummy-output-fix) — RedmiBook 16 2024 Intel sound fix
- [timetracker](https://github.com/OrelSokolov/timetracker) — naive stopwatch, my first C++/Qt project (2013)
- [whisper-vosk-demo](https://github.com/OrelSokolov/whisper-vosk-demo) — Vosk vs Whisper recognition comparison
- [tkinter-wizard](https://github.com/OrelSokolov/tkinter-wizard) / [wx-wizard](https://github.com/OrelSokolov/wx-wizard) — wizard libraries for Python Tkinter/WX
- [sshface](https://github.com/OrelSokolov/sshface) — simple SSH identity changer (Ruby)
- [ocra2](https://github.com/OrelSokolov/ocra2) — (Ruby)
- [action_bot.cr](https://github.com/OrelSokolov/action_bot.cr) — (Crystal)
- [crossbuild](https://github.com/OrelSokolov/crossbuild) / [crosspack](https://github.com/OrelSokolov/crosspack) — cross-building helpers

## 🍴 Forks I keep an eye on

[crystal](https://github.com/OrelSokolov/crystal) · [zed](https://github.com/OrelSokolov/zed) · [opencode](https://github.com/OrelSokolov/opencode) · [whisper.cpp](https://github.com/OrelSokolov/whisper.cpp) · [quic-go](https://github.com/OrelSokolov/quic-go) · [Telethon](https://github.com/OrelSokolov/Telethon) · [OSX-KVM](https://github.com/OrelSokolov/OSX-KVM) · [egui_term](https://github.com/OrelSokolov/egui_term) · [asdf-ruby](https://github.com/OrelSokolov/asdf-ruby) · [Darcula-Dark](https://github.com/OrelSokolov/Darcula-Dark) · [GigaAM](https://github.com/OrelSokolov/GigaAM) · [backprop-explainer](https://github.com/OrelSokolov/backprop-explainer) · [systray](https://github.com/OrelSokolov/systray) · [sidekiq-dags](https://github.com/OrelSokolov/sidekiq-dags)
