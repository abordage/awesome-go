# Awesome Go

![Awesome](https://raw.githubusercontent.com/abordage/schemas/main/badges/awesome.svg)
[![Last update](https://img.shields.io/github/last-commit/abordage/awesome-go?label=last%20update)](README.md)
![Repositories](https://img.shields.io/badge/repositories-1,236-06b6d4)
![Total Stars](https://img.shields.io/badge/total%20stars-4,957,821-gold)
[![License](https://img.shields.io/github/license/abordage/awesome-go)](LICENSE)

**Automated. Curated. Ranked.**

Go libraries, tools, and applications from the community. This awesome list is automatically maintained with daily GitHub API updates. Projects are re-ranked daily based on current activity metrics.

**Daily process:** Merge community PRs → Scan repos → Filter stale projects → Recalculate scores → Rebuild list

- [AI & Machine Learning](#ai--machine-learning)
  - [AI APIs](#ai-apis)
  - [Artificial Intelligence](#artificial-intelligence)
  - [Machine Learning](#machine-learning)
- [Audio & Video](#audio--video)
  - [Audio](#audio)
  - [Images](#images)
  - [Video](#video)
- [Auth](#auth)
  - [Authentication](#authentication)
  - [Authorization](#authorization)
- [Bots & Chat](#bots--chat)
  - [Bot Frameworks](#bot-frameworks)
  - [Chat APIs](#chat-apis)
- [CLI & Terminal](#cli--terminal)
  - [Advanced Console UIs](#advanced-console-uis)
  - [Standard CLI](#standard-cli)
- [Concurrency](#concurrency)
  - [Actor Model](#actor-model)
  - [Goroutines](#goroutines)
  - [Stream Processing](#stream-processing)
- [Configuration](#configuration)
- [Data Formats](#data-formats)
  - [JSON](#json)
  - [Serialization](#serialization)
  - [XML](#xml)
- [Data Structures](#data-structures)
  - [Bit-packing and Compression](#bit-packing-and-compression)
  - [Bloom and Cuckoo Filters](#bloom-and-cuckoo-filters)
  - [Maps](#maps)
  - [Miscellaneous](#miscellaneous)
  - [Queues](#queues)
- [Databases](#databases)
  - [Caches](#caches)
  - [Database Schema Migration](#database-schema-migration)
  - [Database Tools](#database-tools)
  - [Databases Implemented in Go](#databases-implemented-in-go)
  - [Distributed Storage](#distributed-storage)
  - [Interfaces to Multiple Backends](#interfaces-to-multiple-backends)
  - [NoSQL Database Drivers](#nosql-database-drivers)
  - [ORM](#orm)
  - [Query Language](#query-language)
  - [Relational Database Drivers](#relational-database-drivers)
  - [SQL Query Builders](#sql-query-builders)
  - [Search and Analytic Databases](#search-and-analytic-databases)
- [DevOps & Build](#devops--build)
  - [Backup](#backup)
  - [Build Automation](#build-automation)
  - [CI/CD](#cicd)
  - [Containers](#containers)
  - [DevOps Utilities](#devops-utilities)
  - [Infrastructure](#infrastructure)
  - [Kubernetes](#kubernetes)
  - [Load Testing](#load-testing)
- [Email](#email)
- [Finance & Blockchain](#finance--blockchain)
  - [Blockchain](#blockchain)
  - [Financial](#financial)
  - [Payment APIs](#payment-apis)
- [GUI & Desktop](#gui--desktop)
  - [GUI](#gui)
  - [Windows](#windows)
- [Game Development](#game-development)
  - [Game Engines](#game-engines)
  - [OpenGL](#opengl)
- [Geospatial](#geospatial)
- [Go Tooling](#go-tooling)
  - [Compilers](#compilers)
  - [Editor Plugins](#editor-plugins)
  - [Generate Tools](#generate-tools)
  - [Go Tools](#go-tools)
- [Hardware & IoT](#hardware--iot)
  - [Hardware](#hardware)
  - [IoT](#iot)
- [Networking](#networking)
  - [Consensus](#consensus)
  - [DNS](#dns)
  - [Distributed Utilities](#distributed-utilities)
  - [HTTP & Proxy](#http--proxy)
  - [HTTP Clients](#http-clients)
  - [Servers](#servers)
  - [Network Utilities](#network-utilities)
  - [P2P & Torrent](#p2p--torrent)
  - [Protocols](#protocols)
  - [RPC](#rpc)
  - [SSH & SFTP](#ssh--sftp)
  - [TCP/UDP Frameworks](#tcpudp-frameworks)
  - [VPN & Tunneling](#vpn--tunneling)
- [Queues & Pub/Sub](#queues--pubsub)
  - [Brokers](#brokers)
  - [Clients & Libraries](#clients--libraries)
- [Science](#science)
- [Scripting](#scripting)
  - [Embeddable Languages](#embeddable-languages)
  - [Code Generators](#code-generators)
- [Security](#security)
  - [Certificates](#certificates)
  - [Cryptography](#cryptography)
  - [WAF & Protection](#waf--protection)
  - [Zero Trust](#zero-trust)
- [Testing & Quality](#testing--quality)
  - [Benchmarks](#benchmarks)
  - [Code Analysis](#code-analysis)
  - [Mock](#mock)
  - [Performance](#performance)
  - [Browser Automation](#browser-automation)
  - [Testing Frameworks](#testing-frameworks)
  - [Testing Utilities](#testing-utilities)
  - [Validation](#validation)
- [Text & NLP](#text--nlp)
  - [Formatters](#formatters)
  - [Markup Languages](#markup-languages)
  - [Miscellaneous](#miscellaneous)
  - [Morphological Analyzers](#morphological-analyzers)
  - [Parsers/Encoders/Decoders](#parsersencodersdecoders)
  - [Scrapers](#scrapers)
  - [Text Analysis](#text-analysis)
  - [Tokenizers](#tokenizers)
  - [Translation](#translation)
- [Third-party APIs](#third-party-apis)
  - [Cloud Provider APIs](#cloud-provider-apis)
  - [Other APIs](#other-apis)
  - [Productivity APIs](#productivity-apis)
- [Utilities](#utilities)
  - [Build & Release](#build--release)
  - [CLI Tools](#cli-tools)
  - [Data Conversion](#data-conversion)
  - [Database Extensions](#database-extensions)
  - [Date and Time](#date-and-time)
  - [Dependency Injection](#dependency-injection)
  - [Error Handling](#error-handling)
  - [File Handling](#file-handling)
  - [Forms](#forms)
  - [Functional](#functional)
  - [General](#general)
  - [Logging](#logging)
  - [Networking Utils](#networking-utils)
  - [Project Layout](#project-layout)
  - [Resilience & Retry](#resilience--retry)
  - [Strings](#strings)
  - [System & Process](#system--process)
  - [UUID](#uuid)
- [Version Control & Packages](#version-control--packages)
  - [Git APIs](#git-apis)
  - [Package Management](#package-management)
  - [Version Control](#version-control)
- [Web Development](#web-development)
  - [Microservices](#microservices)
  - [Middlewares](#middlewares)
  - [Routers](#routers)
  - [Template Engines](#template-engines)
  - [Web Frameworks](#web-frameworks)
  - [WebAssembly](#webassembly)
- [Workflow & Scheduling](#workflow--scheduling)
  - [Job Scheduler](#job-scheduler)
  - [Workflow Frameworks](#workflow-frameworks)


## AI & Machine Learning

### AI APIs

- [sashabaranov/go-openai](https://github.com/sashabaranov/go-openai) — OpenAI API client for Go ☆`10,489`
- [otiai10/openaigo](https://github.com/otiai10/openaigo) — OpenAI GPT client library ☆`299`
- [wit-ai/wit-go](https://github.com/wit-ai/wit-go) — Go client for wit.ai HTTP API ☆`170`
### Artificial Intelligence

- [ollama/ollama](https://github.com/ollama/ollama) — Run LLMs locally ☆`158,685`
- [mudler/LocalAI](https://github.com/mudler/LocalAI) — Local OpenAI alternative ☆`40,977`
- [tmc/langchaingo](https://github.com/tmc/langchaingo) — LangChain for Go, the easiest way to write LLM-based programs in Go ☆`8,353`
- [maximhq/bifrost](https://github.com/maximhq/bifrost) — Fastest LLM gateway for Go ☆`1,518`
- [philippgille/chromem-go](https://github.com/philippgille/chromem-go) — Embeddable vector database for Go ☆`816`
- [universal-tool-calling-protocol/go-utcp](https://github.com/universal-tool-calling-protocol/go-utcp) — Official Go implementation of the UTCP ☆`93`
- [presbrey/ollamafarm](https://github.com/presbrey/ollamafarm) — Manage multiple Ollama instances ☆`93`
### Machine Learning

- [sjwhitworth/golearn](https://github.com/sjwhitworth/golearn) — Machine Learning for Go ☆`9,454`
- [gorgonia/gorgonia](https://github.com/gorgonia/gorgonia) — Machine learning library for Go ☆`5,899`
- [otiai10/gosseract](https://github.com/otiai10/gosseract) — OCR using Tesseract in Go ☆`3,041`
- [galeone/tfgo](https://github.com/galeone/tfgo) — Tensorflow + Go, the gopher way ☆`2,492`
- [gomlx/gomlx](https://github.com/gomlx/gomlx) — GoMLX: An Accelerated Machine Learning Framework For Go ☆`1,268`
- [jbrukh/bayesian](https://github.com/jbrukh/bayesian) — Naive Bayesian Classification for Golang. ☆`810`
- [patrikeh/go-deep](https://github.com/patrikeh/go-deep) — Artificial Neural Network ☆`559`
- [knights-analytics/hugot](https://github.com/knights-analytics/hugot) — Onnx transformer pipelines in Golang ☆`532`
- [c-bata/goptuna](https://github.com/c-bata/goptuna) — A hyperparameter optimization framework, inspired by Optuna. ☆`273`
## Audio & Video

### Audio

- [ebitengine/oto](https://github.com/ebitengine/oto) — A low-level library to play sound on multiple platforms ☆`1,838`
- [gordonklaus/portaudio](https://github.com/gordonklaus/portaudio) — Go bindings for the PortAudio audio I/O library ☆`818`
- [gen2brain/malgo](https://github.com/gen2brain/malgo) — Mini audio library ☆`373`
- [DylanMeeus/GoAudio](https://github.com/DylanMeeus/GoAudio) — Go tools for audio processing & creation ☆`399`
- [mewkiz/flac](https://github.com/mewkiz/flac) — Package flac provides access to FLAC (Free Lossless Audio Codec) streams. ☆`350`
- [tosone/minimp3](https://github.com/tosone/minimp3) — Decode mp3 ☆`133`
- [dh1tw/gosamplerate](https://github.com/dh1tw/gosamplerate) — Go Bindings for libsamplerate ☆`38`
### Images

- [hybridgroup/gocv](https://github.com/hybridgroup/gocv) — Computer vision with OpenCV 4 ☆`7,331`
- [anthonynsimon/bild](https://github.com/anthonynsimon/bild) — Image processing algorithms in pure Go ☆`4,168`
- [cshum/imagor](https://github.com/cshum/imagor) — Fast, secure image processing server and Go library, using libvips ☆`3,866`
- [thoas/picfit](https://github.com/thoas/picfit) — An image resizing server written in Go ☆`2,320`
- [gographics/imagick](https://github.com/gographics/imagick) — Go binding to ImageMagick's MagickWand C API ☆`1,859`
- [tdewolff/canvas](https://github.com/tdewolff/canvas) — Vector graphics in Go ☆`1,751`
- [davidbyttow/govips](https://github.com/davidbyttow/govips) — A lightning fast image processing and resizing library for Go ☆`1,514`
- [yeqown/go-qrcode](https://github.com/yeqown/go-qrcode) — Customizable QR code generator ☆`796`
- [HugoSmits86/nativewebp](https://github.com/HugoSmits86/nativewebp) — Native webp encoder for Go ☆`380`
- [auyer/steganography](https://github.com/auyer/steganography) — LSB steganography in pure Go ☆`352`
- [Pixboost/transformimgs](https://github.com/Pixboost/transformimgs) — Open source image CDN. ☆`284`
- [kolesa-team/go-webp](https://github.com/kolesa-team/go-webp) — Simple and fast webp library for golang ☆`294`
- [qmuntal/gltf](https://github.com/qmuntal/gltf) — Go library for encoding glTF 2.0 files ☆`266`
- [gojek/darkroom](https://github.com/gojek/darkroom) — Image processing engine and proxy service ☆`235`
- [ungerik/go-cairo](https://github.com/ungerik/go-cairo) — Go binding for the cairo graphics library ☆`151`
- [aofei/cameron](https://github.com/aofei/cameron) — An avatar generator for Go. ☆`130`
- [piglig/go-qr](https://github.com/piglig/go-qr) — A native, high-quality and minimalistic QR code generator ☆`45`
### Video

- [asticode/go-astisub](https://github.com/asticode/go-astisub) — Manipulate subtitles in Go ☆`679`
- [asticode/go-astiav](https://github.com/asticode/go-astiav) — Golang ffmpeg and libav C bindings ☆`613`
- [asticode/go-astits](https://github.com/asticode/go-astits) — Demux and mux MPEG Transport Streams (.ts) natively in GO ☆`600`
- [Eyevinn/mp4ff](https://github.com/Eyevinn/mp4ff) — MP4/ISOBMFF tools and library ☆`579`
- [adrg/libvlc-go](https://github.com/adrg/libvlc-go) — Go bindings for libVLC ☆`500`
- [korandiz/v4l](https://github.com/korandiz/v4l) — Facade to the Video4Linux video capture interface. ☆`88`
- [Eyevinn/hls-m3u8](https://github.com/Eyevinn/hls-m3u8) — HLS m3u8 library in Go ☆`38`
- [jonoton/scout](https://github.com/jonoton/scout) — Video surveillance with motion detection ☆`26`
- [unki2aut/go-mpd](https://github.com/unki2aut/go-mpd) — MPEG-DASH manifest library ☆`33`
## Auth

### Authentication

- [golang-jwt/jwt](https://github.com/golang-jwt/jwt) — Go implementation of JSON Web Tokens (JWT). ☆`8,807`
- [markbates/goth](https://github.com/markbates/goth) — Multi-provider authentication ☆`6,396`
- [golang/oauth2](https://github.com/golang/oauth2) — Go OAuth2 ☆`5,792`
- [aarondl/authboss](https://github.com/aarondl/authboss) — The boss of http auth. ☆`4,138`
- [alexedwards/scs](https://github.com/alexedwards/scs) — HTTP Session Management for Go ☆`2,495`
- [lestrrat-go/jwx](https://github.com/lestrrat-go/jwx) — Complete JWx implementation ☆`2,289`
- [openshift/osin](https://github.com/openshift/osin) — Golang OAuth2 server library ☆`1,932`
- [dghubble/gologin](https://github.com/dghubble/gologin) — Go login handlers for authentication providers (OAuth1, OAuth2) ☆`1,943`
- [zitadel/oidc](https://github.com/zitadel/oidc) — OpenID Connect client and server ☆`1,739`
- [cristalhq/jwt](https://github.com/cristalhq/jwt) — Safe, simple and fast JSON Web Tokens for Go ☆`688`
- [shaj13/go-guardian](https://github.com/shaj13/go-guardian) — Authentication library for Go ☆`604`
- [go-jose/go-jose](https://github.com/go-jose/go-jose) — An implementation of JOSE standards (JWE, JWS, JWT) in Go ☆`471`
- [abraithwaite/jeff](https://github.com/abraithwaite/jeff) — Jeff provides the simplest way to manage web sessions in Go. ☆`270`
- [Kwynto/gosession](https://github.com/Kwynto/gosession) — Quick session for net/http ☆`259`
- [leodip/goiabada](https://github.com/leodip/goiabada) — Goiabada is an OAuth2 / OpenID Connect server written in Go. ☆`180`
- [brianvoe/sjwt](https://github.com/brianvoe/sjwt) — Simple JWT Golang ☆`121`
- [RijulGulati/otpgen](https://github.com/RijulGulati/otpgen) — Library to generate TOTP/HOTP codes ☆`142`
- [jellydator/sessionup](https://github.com/jellydator/sessionup) — Straightforward HTTP session management ☆`128`
- [essentialkaos/branca](https://github.com/essentialkaos/branca) — Encrypted API tokens ☆`95`
- [icza/session](https://github.com/icza/session) — Session management for web servers ☆`118`
- [mengzhuo/cookiestxt](https://github.com/mengzhuo/cookiestxt) — cookiestxt implement parser of cookies txt format ☆`21`
### Authorization

- [casbin/casbin](https://github.com/casbin/casbin) — Authorization library for Go ☆`19,624`
- [ory/keto](https://github.com/ory/keto) — Customizable permission server ☆`5,233`
- [openfga/openfga](https://github.com/openfga/openfga) — Fine-grained authorization server ☆`4,591`
- [cerbos/cerbos](https://github.com/cerbos/cerbos) — Open core authorization layer ☆`4,180`
## Bots & Chat

### Bot Frameworks

- [tucnak/telebot](https://github.com/tucnak/telebot) — Telebot is a Telegram bot framework in Go. ☆`4,516`
- [go-telegram/bot](https://github.com/go-telegram/bot) — Telegram Bot API Go framework ☆`1,516`
- [mymmrac/telego](https://github.com/mymmrac/telego) — Telegram Bot API library for Go ☆`862`
- [diamondburned/arikawa](https://github.com/diamondburned/arikawa) — A Golang library and framework for the Discord API. ☆`566`
- [NicoNex/echotron](https://github.com/NicoNex/echotron) — An elegant and concurrent library for the Telegram bot API in Go. ☆`414`
- [gempir/go-twitch-irc](https://github.com/gempir/go-twitch-irc) — go irc client for twitch.tv ☆`390`
- [innogames/slack-bot](https://github.com/innogames/slack-bot) — Slack bot for Jenkins, Jira, PRs ☆`204`
- [mr-linch/go-tg](https://github.com/mr-linch/go-tg) — Telegram Bot API client ☆`124`
- [slack-io/slacker](https://github.com/slack-io/slacker) — Slack Bot Framework ☆`61`
- [onrik/micha](https://github.com/onrik/micha) — Client lib for Telegram bot api ☆`31`
### Chat APIs

- [bwmarrin/discordgo](https://github.com/bwmarrin/discordgo) — (Golang) Go bindings for Discord ☆`5,726`
- [slack-go/slack](https://github.com/slack-go/slack) — Slack API in Go ☆`4,881`
- [huandu/facebook](https://github.com/huandu/facebook) — A Facebook Graph API SDK For Go. ☆`1,434`
- [ChimeraCoder/anaconda](https://github.com/ChimeraCoder/anaconda) — A Go client library for the Twitter 1.1 API ☆`1,141`
- [chyroc/lark](https://github.com/chyroc/lark) — Lark/Feishu Open API SDK ☆`460`
- [go-lark/lark](https://github.com/go-lark/lark) — Feishu/Lark SDK for Go ☆`234`
- [switchupcb/disgo](https://github.com/switchupcb/disgo) — Next-gen Discord API library ☆`109`
## CLI & Terminal

### Advanced Console UIs

- [charmbracelet/bubbletea](https://github.com/charmbracelet/bubbletea) — A powerful little TUI framework ☆`37,890`
- [antonmedv/fx](https://github.com/antonmedv/fx) — Terminal JSON viewer & processor ☆`20,141`
- [gizak/termui](https://github.com/gizak/termui) — Golang terminal dashboard ☆`13,502`
- [jroimartin/gocui](https://github.com/jroimartin/gocui) — Minimalist Go package aimed at creating Console User Interfaces. ☆`10,477`
- [charmbracelet/lipgloss](https://github.com/charmbracelet/lipgloss) — Style definitions for nice terminal layouts ☆`10,240`
- [charmbracelet/bubbles](https://github.com/charmbracelet/bubbles) — TUI components for Bubble Tea ☆`7,462`
- [c-bata/go-prompt](https://github.com/c-bata/go-prompt) — Interactive prompts for Go ☆`5,443`
- [pterm/pterm](https://github.com/pterm/pterm) — Modern terminal output library ☆`5,327`
- [schollz/progressbar](https://github.com/schollz/progressbar) — Thread-safe progress bar ☆`4,622`
- [mum4k/termdash](https://github.com/mum4k/termdash) — Terminal-based dashboard ☆`2,959`
- [guptarohit/asciigraph](https://github.com/guptarohit/asciigraph) — ASCII line graphs in terminal ☆`2,936`
- [briandowns/spinner](https://github.com/briandowns/spinner) — Terminal spinner indicators ☆`2,500`
- [vbauerster/mpb](https://github.com/vbauerster/mpb) — Multi progress bar ☆`2,463`
- [muesli/termenv](https://github.com/muesli/termenv) — Terminal color support ☆`1,949`
- [gookit/color](https://github.com/gookit/color) — Terminal color rendering ☆`1,571`
- [logrusorgru/aurora](https://github.com/logrusorgru/aurora) — ANSI colors for Printf ☆`1,475`
- [mattn/go-isatty](https://github.com/mattn/go-isatty) — Check if terminal is TTY ☆`881`
- [mattn/go-colorable](https://github.com/mattn/go-colorable) — Colorable writer for Windows ☆`804`
- [Evertras/bubble-table](https://github.com/Evertras/bubble-table) — Table component for Bubble Tea ☆`547`
- [DMcP89/tinycare-tui](https://github.com/DMcP89/tinycare-tui) — TUI application written in GO inspired by tiny-care-terminal ☆`16`
### Standard CLI

- [spf13/cobra](https://github.com/spf13/cobra) — A Commander for modern Go CLI interactions ☆`42,774`
- [urfave/cli](https://github.com/urfave/cli) — Fast CLI framework for Go ☆`23,792`
- [elves/elvish](https://github.com/elves/elvish) — Scripting shell for Go ☆`6,200`
- [alecthomas/kingpin](https://github.com/alecthomas/kingpin) — Command-line parser ☆`3,557`
- [dnote/dnote](https://github.com/dnote/dnote) — Command-line notebook ☆`3,001`
- [spf13/pflag](https://github.com/spf13/pflag) — POSIX/GNU-style flags ☆`2,680`
- [jessevdk/go-flags](https://github.com/jessevdk/go-flags) — Command-line option parser ☆`2,691`
- [alexflint/go-arg](https://github.com/alexflint/go-arg) — Struct-based argument parsing ☆`2,218`
- [carapace-sh/carapace-bin](https://github.com/carapace-sh/carapace-bin) — Multi-shell completion binary ☆`1,637`
- [nanovms/ops](https://github.com/nanovms/ops) — Build and run unikernels ☆`1,445`
- [carapace-sh/carapace](https://github.com/carapace-sh/carapace) — Multi-shell completion library ☆`1,066`
- [posener/complete](https://github.com/posener/complete) — Bash completion in Go ☆`949`
- [ddddddO/gtree](https://github.com/ddddddO/gtree) — Generate ASCII tree from Markdown ☆`323`
- [leaanthony/clir](https://github.com/leaanthony/clir) — Simple CLI library ☆`196`
- [urfave/sflags](https://github.com/urfave/sflags) — Generate flags from structs ☆`165`
- [hedzr/cmdr](https://github.com/hedzr/cmdr) — POSIX-compliant CLI parser ☆`141`
- [reeflective/readline](https://github.com/reeflective/readline) — Shell library with inputrc ☆`132`
- [cristalhq/acmd](https://github.com/cristalhq/acmd) — Simple CLI package ☆`137`
- [codingconcepts/env](https://github.com/codingconcepts/env) — Tag-based environment configuration for structs ☆`126`
- [reeflective/console](https://github.com/reeflective/console) — Console library for Cobra ☆`100`
- [dixonwille/wlog](https://github.com/dixonwille/wlog) — Cross-platform logging ☆`67`
- [DavidGamba/go-getoptions](https://github.com/DavidGamba/go-getoptions) — Command line option parser with completion ☆`61`
- [hashicorp/cli](https://github.com/hashicorp/cli) — CLI library for Go ☆`33`
- [nyaosorg/go-readline-ny](https://github.com/nyaosorg/go-readline-ny) — Readline for Go ☆`32`
- [carapace-sh/carapace-spec](https://github.com/carapace-sh/carapace-spec) — Multi-shell completion library ☆`26`
- [sgreben/flagvar](https://github.com/sgreben/flagvar) — CLI argument types for flag ☆`48`
- [jxskiss/mcli](https://github.com/jxskiss/mcli) — Minimal but powerful CLI ☆`42`
## Concurrency

### Actor Model

- [asynkron/protoactor-go](https://github.com/asynkron/protoactor-go) — Ultra fast distributed actors for Go ☆`5,401`
- [ergo-services/ergo](https://github.com/ergo-services/ergo) — Actor framework with network transparency ☆`4,322`
- [anthdm/hollywood](https://github.com/anthdm/hollywood) — Blazingly fast and light-weight Actor engine written in Golang ☆`2,160`
- [Tochemey/goakt](https://github.com/Tochemey/goakt) — Distributed actor framework ☆`311`
### Goroutines

- [panjf2000/ants](https://github.com/panjf2000/ants) — ants is the most powerful and reliable pooling solution for Go. ☆`14,231`
- [benmanns/goworker](https://github.com/benmanns/goworker) — Resque-compatible background worker ☆`2,847`
- [alitto/pond](https://github.com/alitto/pond) — High-performance worker pool ☆`2,054`
- [destel/rill](https://github.com/destel/rill) — Channel-based concurrency toolkit ☆`1,800`
- [xxjwxc/gowp](https://github.com/xxjwxc/gowp) — Goroutine worker pool ☆`521`
- [earthboundkid/flowmatic](https://github.com/earthboundkid/flowmatic) — Structured concurrency ☆`396`
- [reugn/async](https://github.com/reugn/async) — Async computation package ☆`285`
- [timandy/routine](https://github.com/timandy/routine) — ThreadLocal for Go ☆`282`
- [vladopajic/go-actor](https://github.com/vladopajic/go-actor) — Actor model library ☆`273`
- [mborders/artifex](https://github.com/mborders/artifex) — In-memory job queue ☆`213`
### Stream Processing

- [reugn/go-streams](https://github.com/reugn/go-streams) — Stream processing library ☆`2,147`
- [Breeze0806/go-etl](https://github.com/Breeze0806/go-etl) — ETL toolset for Go ☆`180`
- [fulminate-io/machine](https://github.com/fulminate-io/machine) — Machine is a workflow/pipeline library for processing data ☆`164`
- [mariomac/gostream](https://github.com/mariomac/gostream) — Java Streams port for Go ☆`169`
- [rulego/streamsql](https://github.com/rulego/streamsql) — SQL-based stream processing for IoT ☆`51`
## Configuration

- [spf13/viper](https://github.com/spf13/viper) — Go configuration with fangs ☆`29,773`
- [caarlos0/env](https://github.com/caarlos0/env) — Parse environment variables to structs ☆`5,913`
- [knadh/koanf](https://github.com/knadh/koanf) — Lightweight config management ☆`3,722`
- [alecthomas/kong](https://github.com/alecthomas/kong) — Command-line parser for Go ☆`2,911`
- [ilyakaznacheev/cleanenv](https://github.com/ilyakaznacheev/cleanenv) — Minimalistic environment config reader ☆`2,024`
- [adrg/xdg](https://github.com/adrg/xdg) — XDG Base Directory implementation ☆`937`
- [cristalhq/aconfig](https://github.com/cristalhq/aconfig) — Simple config loader ☆`617`
- [gookit/config](https://github.com/gookit/config) — Config management with formats ☆`575`
- [kkyr/fig](https://github.com/kkyr/fig) — Minimalist config library ☆`386`
- [nil-go/konf](https://github.com/nil-go/konf) — Simplest config loader for Go ☆`359`
- [hjson/hjson-go](https://github.com/hjson/hjson-go) — Hjson for Go ☆`347`
- [vrischmann/envconfig](https://github.com/vrischmann/envconfig) — Env config library ☆`250`
- [chaindead/zerocfg](https://github.com/chaindead/zerocfg) — Zero-effort config management ☆`198`
- [beatlabs/harvester](https://github.com/beatlabs/harvester) — Watch and notify config changes ☆`134`
- [BoRuDar/configuration](https://github.com/BoRuDar/configuration) — Set struct fields from env, flags, files ☆`108`
- [gurkankaymak/hocon](https://github.com/gurkankaymak/hocon) — HOCON config library for Go ☆`86`
- [PaddleHQ/go-aws-ssm](https://github.com/PaddleHQ/go-aws-ssm) — AWS System Manager interface ☆`62`
- [omeid/uconfig](https://github.com/omeid/uconfig) — Lightweight config management ☆`72`
- [go-simpler/env](https://github.com/go-simpler/env) — Load env vars to struct ☆`80`
- [num30/config](https://github.com/num30/config) — Declarative configuration ☆`60`
- [wkhere/bcl](https://github.com/wkhere/bcl) — Basic Configuration Language ☆`27`
- [sakirsensoy/genv](https://github.com/sakirsensoy/genv) — Easy env variable handling ☆`43`
- [greencoda/confiq](https://github.com/greencoda/confiq) — Config struct decoder ☆`39`
- [dsbasko/go-cfg](https://github.com/dsbasko/go-cfg) — Unified config reading ☆`47`
- [atelpis/enflag](https://github.com/atelpis/enflag) — Unify env and flag parsing ☆`35`
- [nasermirzaei89/env](https://github.com/nasermirzaei89/env) — Zero-dep env package ☆`22`
- [romshark/yamagiconf](https://github.com/romshark/yamagiconf) — YAML config framework ☆`18`
- [deatil/go-array](https://github.com/deatil/go-array) — Read/set map, slice, JSON data ☆`22`
## Data Formats

### JSON

- [tidwall/gjson](https://github.com/tidwall/gjson) — Fast JSON value extraction ☆`15,387`
- [bytedance/sonic](https://github.com/bytedance/sonic) — A blazingly fast JSON serializing & deserializing library ☆`8,999`
- [Jeffail/gabs](https://github.com/Jeffail/gabs) — Dynamic JSON parsing ☆`3,529`
- [valyala/fastjson](https://github.com/valyala/fastjson) — Fast JSON parser for Go ☆`2,423`
- [ohler55/ojg](https://github.com/ohler55/ojg) — Optimized JSON for Go ☆`932`
- [wI2L/jsondiff](https://github.com/wI2L/jsondiff) — JSON Patch diff computation ☆`619`
- [spyzhov/ajson](https://github.com/spyzhov/ajson) — Abstract JSON with JSONPath ☆`291`
- [Andrew-M-C/go.jsonvalue](https://github.com/Andrew-M-C/go.jsonvalue) — Unstructured JSON solution ☆`202`
- [romshark/jscan](https://github.com/romshark/jscan) — High-performance JSON iterator ☆`97`
- [iOliverNguyen/ujson](https://github.com/iOliverNguyen/ujson) — Minimal JSON parser ☆`85`
- [neilotoole/jsoncolor](https://github.com/neilotoole/jsoncolor) — Colorized JSON output ☆`49`
- [ake-persson/mapslice-json](https://github.com/ake-persson/mapslice-json) — Ordered JSON map slices ☆`20`
- [vtopc/epoch](https://github.com/vtopc/epoch) — Unix timestamp marshaling ☆`17`
### Serialization

- [golang/protobuf](https://github.com/golang/protobuf) — Protocol buffers for Go ☆`10,051`
- [ugorji/go](https://github.com/ugorji/go) — Codec for msgpack, cbor, json ☆`1,924`
- [linkedin/goavro](https://github.com/linkedin/goavro) — Goavro is a library that encodes and decodes Avro data. ☆`1,050`
- [jszwec/csvutil](https://github.com/jszwec/csvutil) — CSV to struct mapping ☆`1,026`
- [fxamacker/cbor](https://github.com/fxamacker/cbor) — CBOR codec with extensions ☆`1,003`
- [ghostiam/binstruct](https://github.com/ghostiam/binstruct) — Binary to struct decoder ☆`111`
- [csweichel/bel](https://github.com/csweichel/bel) — Generate TypeScript from Go ☆`45`
- [o1egl/fwencoder](https://github.com/o1egl/fwencoder) — Fixed width file parser ☆`27`
- [tiendc/go-csvlib](https://github.com/tiendc/go-csvlib) — High-level CSV library ☆`19`
### XML

- [miku/zek](https://github.com/miku/zek) — Generate Go struct from XML ☆`821`
- [antchfx/xpath](https://github.com/antchfx/xpath) — XPath for Go ☆`731`
- [antchfx/xmlquery](https://github.com/antchfx/xmlquery) — XPath XML query ☆`484`
## Data Structures

### Bit-packing and Compression

- [RoaringBitmap/roaring](https://github.com/RoaringBitmap/roaring) — Compressed bitmaps for Go ☆`2,814`
- [iancmcc/bingo](https://github.com/iancmcc/bingo) — Zero-allocation binary encoding ☆`49`
- [amallia/go-ef](https://github.com/amallia/go-ef) — A Go implementation of the Elias-Fano encoding ☆`40`
### Bloom and Cuckoo Filters

- [bits-and-blooms/bloom](https://github.com/bits-and-blooms/bloom) — Bloom filter implementation ☆`2,722`
- [tylertreat/BoomFilters](https://github.com/tylertreat/BoomFilters) — Probabilistic data structures for streams ☆`1,629`
- [seiflotfy/cuckoofilter](https://github.com/seiflotfy/cuckoofilter) — Cuckoo Filter: Practically Better Than Bloom ☆`1,208`
- [OldPanda/bloomfilter](https://github.com/OldPanda/bloomfilter) — Bloom filter compatible with pybloom ☆`20`
### Maps

- [mhmtszr/concurrent-swiss-map](https://github.com/mhmtszr/concurrent-swiss-map) — Thread-safe concurrent hash map ☆`259`
- [srfrog/dict](https://github.com/srfrog/dict) — Python-like dictionaries for Go ☆`46`
- [goradd/maps](https://github.com/goradd/maps) — Generic map library for Go ☆`51`
### Miscellaneous

- [Workiva/go-datastructures](https://github.com/Workiva/go-datastructures) — Performant, threadsafe data structures ☆`7,883`
- [deckarep/golang-set](https://github.com/deckarep/golang-set) — Generic set type for Go ☆`4,637`
- [bits-and-blooms/bitset](https://github.com/bits-and-blooms/bitset) — Go package implementing bitsets ☆`1,473`
- [liyue201/gostl](https://github.com/liyue201/gostl) — Data structures modeled on C++ STL ☆`1,129`
- [axiomhq/hyperloglog](https://github.com/axiomhq/hyperloglog) — HyperLogLog with optimizations ☆`1,019`
- [kelindar/bitmap](https://github.com/kelindar/bitmap) — Simple dense bitmap index in Go with binary operators ☆`370`
- [barweiss/go-tuple](https://github.com/barweiss/go-tuple) — Go 1.18+ generic tuple ☆`95`
- [seiflotfy/count-min-log](https://github.com/seiflotfy/count-min-log) — Go implementation of Count-Min-Log ☆`69`
- [s0rg/quadtree](https://github.com/s0rg/quadtree) — Generic, zero-alloc, 100%-test covered Quadtree for golang ☆`41`
- [StudioSol/set](https://github.com/StudioSol/set) — Simple set data structure ☆`29`
- [nazar256/parapipe](https://github.com/nazar256/parapipe) — Paralleling pipeline ☆`37`
- [bobg/merkle](https://github.com/bobg/merkle) — Merkle hash trees ☆`21`
### Queues

- [gammazero/deque](https://github.com/gammazero/deque) — Fast ring-buffer deque (double-ended queue) ☆`747`
- [adrianbrad/queue](https://github.com/adrianbrad/queue) — Multiple queue implementations ☆`327`
- [embano1/memlog](https://github.com/embano1/memlog) — A Kafka log inspired in-memory and append-only data structure ☆`135`
- [mikestefanello/backlite](https://github.com/mikestefanello/backlite) — SQLite-backed task queues ☆`131`
## Databases

### Caches

- [golang/groupcache](https://github.com/golang/groupcache) — Distributed cache library ☆`13,295`
- [dgraph-io/ristretto](https://github.com/dgraph-io/ristretto) — A high performance memory-bound Go cache ☆`6,644`
- [eko/gocache](https://github.com/eko/gocache) — Multi-store caching library ☆`2,824`
- [bluele/gcache](https://github.com/bluele/gcache) — In-memory cache with eviction ☆`2,725`
- [maypok86/otter](https://github.com/maypok86/otter) — A high performance caching library for Go ☆`2,468`
- [VictoriaMetrics/fastcache](https://github.com/VictoriaMetrics/fastcache) — Fast in-memory cache for Go ☆`2,306`
- [viccon/sturdyc](https://github.com/viccon/sturdyc) — Caching with advanced concurrency ☆`1,244`
- [jellydator/ttlcache](https://github.com/jellydator/ttlcache) — An in-memory cache with item expiration and generics ☆`1,200`
- [EchoVault/SugarDB](https://github.com/EchoVault/SugarDB) — Embeddable and distributed in-memory alternative to Redis. ☆`518`
- [faabiosr/cachego](https://github.com/faabiosr/cachego) — Golang Cache component - Multiple drivers ☆`373`
- [Yiling-J/theine-go](https://github.com/Yiling-J/theine-go) — high performance in-memory cache ☆`359`
- [elastic/go-freelru](https://github.com/elastic/go-freelru) — GC-less, fast and generic LRU cache for Go ☆`258`
- [samber/hot](https://github.com/samber/hot) — In-memory caching library for read-intensive Go applications ☆`232`
- [naughtygopher/pocache](https://github.com/naughtygopher/pocache) — Preemptive optimistic caching ☆`231`
- [erni27/imcache](https://github.com/erni27/imcache) — A zero-dependency generic in-memory cache Go library ☆`123`
- [OrlovEvgeny/go-mcache](https://github.com/OrlovEvgeny/go-mcache) — Sharded in-memory KV cache ☆`101`
- [zekroTJA/timedmap](https://github.com/zekroTJA/timedmap) — A thread safe map which has expiring key-value pairs. ☆`74`
- [codingsince1985/couchcache](https://github.com/codingsince1985/couchcache) — A RESTful caching micro-service in Go backed by Couchbase ☆`66`
- [mdaliyan/icache](https://github.com/mdaliyan/icache) — High-performance generic cache ☆`23`
### Database Schema Migration

- [golang-migrate/migrate](https://github.com/golang-migrate/migrate) — Database migrations. CLI and Golang library. ☆`17,885`
- [bytebase/bytebase](https://github.com/bytebase/bytebase) — Database DevSecOps platform ☆`13,509`
- [pressly/goose](https://github.com/pressly/goose) — A database migration tool. Supports SQL migrations and Go functions. ☆`9,867`
- [ariga/atlas](https://github.com/ariga/atlas) — Manage your database schema as code ☆`7,827`
- [amacneil/dbmate](https://github.com/amacneil/dbmate) — A lightweight, framework-agnostic database migration tool. ☆`6,603`
- [rubenv/sql-migrate](https://github.com/rubenv/sql-migrate) — SQL schema migration tool for Go. ☆`3,399`
- [skeema/skeema](https://github.com/skeema/skeema) — Declarative pure-SQL schema management for MySQL and MariaDB ☆`1,352`
- [go-gormigrate/gormigrate](https://github.com/go-gormigrate/gormigrate) — Minimalistic database migration helper for Gorm ORM ☆`1,145`
- [sunary/sqlize](https://github.com/sunary/sqlize) — SQL parsing and migration toolkit ☆`123`
- [robinjoseph08/go-pg-migrations](https://github.com/robinjoseph08/go-pg-migrations) — A Go package to help write migrations with go-pg/pg. ☆`86`
- [adlio/schema](https://github.com/adlio/schema) — Embedded schema migration package for Go ☆`42`
- [khezen/avro](https://github.com/khezen/avro) — Apache AVRO for go ☆`48`
- [muir/libschema](https://github.com/muir/libschema) — database schema migrations on a per-library basis [Go] ☆`17`
### Database Tools

- [vitessio/vitess](https://github.com/vitessio/vitess) — Database clustering for MySQL ☆`20,597`
- [sosedoff/pgweb](https://github.com/sosedoff/pgweb) — Cross-platform client for PostgreSQL databases ☆`9,205`
- [go-mysql-org/go-mysql](https://github.com/go-mysql-org/go-mysql) — a powerful mysql toolset with Go ☆`4,903`
- [prest/prest](https://github.com/prest/prest) — PostgreSQL REST API server ☆`4,504`
- [ContentSquare/chproxy](https://github.com/ContentSquare/chproxy) — Open-Source ClickHouse http proxy and load balancer ☆`1,426`
- [cybertec-postgresql/pg_timetable](https://github.com/cybertec-postgresql/pg_timetable) — Advanced PostgreSQL scheduler ☆`1,302`
- [liweiyi88/onedump](https://github.com/liweiyi88/onedump) — Effortless database administration tool ☆`799`
- [HDT3213/rdb](https://github.com/HDT3213/rdb) — Redis RDB parser for Go ☆`592`
- [nikepan/clickhouse-bulk](https://github.com/nikepan/clickhouse-bulk) — Batch inserts for ClickHouse ☆`505`
- [wesql/wescale](https://github.com/wesql/wescale) — MySQL proxy with read/write split ☆`312`
- [gatewayd-io/gatewayd](https://github.com/gatewayd-io/gatewayd) — database gateway for building data-driven applications ☆`272`
- [sj14/dbbench](https://github.com/sj14/dbbench) — Database benchmarking tool ☆`115`
- [bartventer/gorm-multitenancy](https://github.com/bartventer/gorm-multitenancy) — Multi-tenancy for GORM ☆`75`
- [kazhuravlev/database-gateway](https://github.com/kazhuravlev/database-gateway) — Safe access to production databases ☆`30`
- [codingconcepts/dg](https://github.com/codingconcepts/dg) — Generate CSV from data models ☆`43`
### Databases Implemented in Go

- [prometheus/prometheus](https://github.com/prometheus/prometheus) — The Prometheus monitoring system and time series database. ☆`62,007`
- [milvus-io/milvus](https://github.com/milvus-io/milvus) — Cloud-native vector database ☆`42,038`
- [pingcap/tidb](https://github.com/pingcap/tidb) — Cloud-native distributed SQL DB ☆`39,548`
- [cockroachdb/cockroach](https://github.com/cockroachdb/cockroach) — Cloud native distributed SQL database ☆`31,682`
- [influxdata/influxdb](https://github.com/influxdata/influxdb) — Scalable datastore for metrics, events, and real-time analytics ☆`31,051`
- [dgraph-io/dgraph](https://github.com/dgraph-io/dgraph) — high-performance graph database for real-time use cases ☆`21,442`
- [dolthub/dolt](https://github.com/dolthub/dolt) — Dolt – Git for Data ☆`19,507`
- [rqlite/rqlite](https://github.com/rqlite/rqlite) — Lightweight distributed SQLite ☆`17,199`
- [VictoriaMetrics/VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) — Fast time series database and monitoring ☆`15,853`
- [dgraph-io/badger](https://github.com/dgraph-io/badger) — Fast key-value DB in Go. ☆`15,335`
- [etcd-io/bbolt](https://github.com/etcd-io/bbolt) — An embedded key/value database for Go. ☆`9,284`
- [codenotary/immudb](https://github.com/codenotary/immudb) — Immutable database with SQL ☆`8,889`
- [cockroachdb/pebble](https://github.com/cockroachdb/pebble) — RocksDB/LevelDB inspired key-value database in Go ☆`5,688`
- [rosedblabs/rosedb](https://github.com/rosedblabs/rosedb) — Fast key/value storage engine ☆`4,876`
- [tidwall/buntdb](https://github.com/tidwall/buntdb) — Embeddable in-memory key/value DB ☆`4,821`
- [nalgeon/redka](https://github.com/nalgeon/redka) — Redis re-implemented with SQL ☆`4,432`
- [HDT3213/godis](https://github.com/HDT3213/godis) — A Golang implemented Redis Server and Cluster ☆`3,812`
- [nutsdb/nutsdb](https://github.com/nutsdb/nutsdb) — Simple embeddable key/value store ☆`3,542`
- [lindb/lindb](https://github.com/lindb/lindb) — Scalable time-series database ☆`3,045`
- [lotusdblabs/lotusdb](https://github.com/lotusdblabs/lotusdb) — Key-value database with LSM and B+ tree ☆`2,244`
- [kelindar/column](https://github.com/kelindar/column) — Columnar in-memory store ☆`1,503`
- [akrylysov/pogreb](https://github.com/akrylysov/pogreb) — Embedded key-value store for read-heavy workloads written in Go ☆`1,347`
- [objectbox/objectbox-go](https://github.com/objectbox/objectbox-go) — Embedded database for Go ☆`1,255`
- [couchbase/moss](https://github.com/couchbase/moss) — Simple, fast key-val storage ☆`1,016`
- [amit-davidson/LibraDB](https://github.com/amit-davidson/LibraDB) — Simple persistent key/value store ☆`199`
- [claygod/transaction](https://github.com/claygod/transaction) — Embedded database for accounts transactions. ☆`138`
- [xgzlucario/rotom](https://github.com/xgzlucario/rotom) — Tiny Redis server in Go ☆`41`
### Distributed Storage

- [seaweedfs/seaweedfs](https://github.com/seaweedfs/seaweedfs) — Fast distributed storage for blobs ☆`29,300`
- [juicedata/juicefs](https://github.com/juicedata/juicefs) — Distributed POSIX filesystem ☆`12,625`
### Interfaces to Multiple Backends

- [philippgille/gokv](https://github.com/philippgille/gokv) — Key-value store abstraction ☆`821`
- [avito-tech/go-transaction-manager](https://github.com/avito-tech/go-transaction-manager) — Transaction manager for Go ☆`371`
- [viant/dsc](https://github.com/viant/dsc) — Datastore Connectivity in go ☆`35`
- [fogfish/dynamo](https://github.com/fogfish/dynamo) — Generic Golang Key/Value trait for AWS storage services ☆`22`
### NoSQL Database Drivers

- [redis/go-redis](https://github.com/redis/go-redis) — Redis Go client ☆`21,774`
- [gomodule/redigo](https://github.com/gomodule/redigo) — Go client for Redis ☆`9,878`
- [mongodb/mongo-go-driver](https://github.com/mongodb/mongo-go-driver) — The Official Golang driver for MongoDB ☆`8,488`
- [bradfitz/gomemcache](https://github.com/bradfitz/gomemcache) — Go Memcached client library #golang ☆`1,862`
- [qiniu/qmgo](https://github.com/qiniu/qmgo) — Go driver for MongoDB ☆`1,345`
- [aerospike/aerospike-client-go](https://github.com/aerospike/aerospike-client-go) — Aerospike Client Go ☆`457`
- [couchbase/gocb](https://github.com/couchbase/gocb) — The Couchbase Go SDK ☆`375`
- [nitishm/go-rejson](https://github.com/nitishm/go-rejson) — ReJSON client for Go ☆`346`
- [go-kivik/kivik](https://github.com/go-kivik/kivik) — CouchDB client interface ☆`335`
- [couchbase/go-couchbase](https://github.com/couchbase/go-couchbase) — Couchbase client in Go ☆`324`
- [chenmingyong0423/go-mongox](https://github.com/chenmingyong0423/go-mongox) — MongoDB driver wrapper with generics ☆`218`
- [aliexpressru/gomemcached](https://github.com/aliexpressru/gomemcached) — Binary Memcached client with sharding ☆`22`
- [btnguyen2k/gocosmos](https://github.com/btnguyen2k/gocosmos) — Go database/sql driver for Azure Cosmos DB SQL API ☆`22`
### ORM

- [go-gorm/gorm](https://github.com/go-gorm/gorm) — The fantastic ORM library for Golang, aims to be developer friendly ☆`39,327`
- [ent/ent](https://github.com/ent/ent) — An entity framework for Go ☆`16,804`
- [aarondl/sqlboiler](https://github.com/aarondl/sqlboiler) — Generate a Go ORM tailored to your database schema. ☆`6,968`
- [uptrace/bun](https://github.com/uptrace/bun) — SQL-first Golang ORM ☆`4,575`
- [upper/db](https://github.com/upper/db) — Data access layer for databases ☆`3,631`
- [huandu/go-sqlbuilder](https://github.com/huandu/go-sqlbuilder) — SQL builder with zero-config ORM ☆`1,652`
- [stephenafamo/bob](https://github.com/stephenafamo/bob) — SQL builder with ORM generator ☆`1,586`
- [go-rel/rel](https://github.com/go-rel/rel) — Modern ORM for Golang ☆`781`
- [FrancoLiberali/cql](https://github.com/FrancoLiberali/cql) — CQL: Compiled Query Language ☆`17`
- [hashicorp/go-dbw](https://github.com/hashicorp/go-dbw) — A simple package that encapsulates database operations. ☆`16`
### Query Language

- [99designs/gqlgen](https://github.com/99designs/gqlgen) — go generate based graphql server library ☆`10,621`
- [TomWright/dasel](https://github.com/TomWright/dasel) — Query and modify data formats ☆`7,765`
- [graph-gophers/graphql-go](https://github.com/graph-gophers/graphql-go) — GraphQL server with a focus on ease of use ☆`4,740`
- [bhmj/jsonslice](https://github.com/bhmj/jsonslice) — json slicer ☆`92`
- [hashicorp/mql](https://github.com/hashicorp/mql) — Model Query Language (mql) is a query language for your database models. ☆`65`
- [ccbrown/api-fu](https://github.com/ccbrown/api-fu) — A collection of Go packages for creating robust GraphQL APIs ☆`57`
- [AsaiYusuke/jsonpath](https://github.com/AsaiYusuke/jsonpath) — JSONPath query library ☆`29`
### Relational Database Drivers

- [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) — MySQL driver for database/sql ☆`15,365`
- [jackc/pgx](https://github.com/jackc/pgx) — PostgreSQL driver and toolkit for Go ☆`13,118`
- [denisenkom/go-mssqldb](https://github.com/denisenkom/go-mssqldb) — Microsoft SQL server driver written in go language ☆`1,876`
- [ncruces/go-sqlite3](https://github.com/ncruces/go-sqlite3) — Go bindings to SQLite using wazero ☆`890`
- [godror/godror](https://github.com/godror/godror) — GO DRiver for ORacle DB ☆`579`
- [cvilsmeier/sqinn-go](https://github.com/cvilsmeier/sqinn-go) — Golang SQLite without cgo ☆`511`
- [VinGarcia/ksql](https://github.com/VinGarcia/ksql) — A Simple and Powerful Golang SQL Library ☆`349`
- [surrealdb/surrealdb.go](https://github.com/surrealdb/surrealdb.go) — SurrealDB SDK for Golang ☆`297`
- [nakagami/firebirdsql](https://github.com/nakagami/firebirdsql) — Firebird RDBMS sql driver for Go (golang) ☆`253`
- [ydb-platform/ydb-go-sdk](https://github.com/ydb-platform/ydb-go-sdk) — Pure Go native and database/sql driver for YDB ☆`173`
- [rqlite/gorqlite](https://github.com/rqlite/gorqlite) — A Go client for rqlite, the distributed database built on SQLite ☆`177`
- [apache/calcite-avatica-go](https://github.com/apache/calcite-avatica-go) — Apache Calcite Go ☆`123`
- [viant/bgc](https://github.com/viant/bgc) — Datastore Connectivity for BigQuery in go ☆`21`
### SQL Query Builders

- [sqlc-dev/sqlc](https://github.com/sqlc-dev/sqlc) — Generate type-safe code from SQL ☆`16,634`
- [Masterminds/squirrel](https://github.com/Masterminds/squirrel) — Fluent SQL generation for golang ☆`7,831`
- [xo/dbtpl](https://github.com/xo/dbtpl) — Generate Go code for databases ☆`3,885`
- [go-jet/jet](https://github.com/go-jet/jet) — Type-safe SQL builder with codegen ☆`3,516`
- [doug-martin/goqu](https://github.com/doug-martin/goqu) — SQL builder and query library for golang ☆`2,620`
- [didi/gendry](https://github.com/didi/gendry) — a golang library for sql builder ☆`1,641`
- [lqs/sqlingo](https://github.com/lqs/sqlingo) — A lightweight DSL & ORM which helps you to write SQL in Go. ☆`447`
- [nullism/bqb](https://github.com/nullism/bqb) — Lightweight query builder ☆`184`
- [arthurkushman/buildsqlx](https://github.com/arthurkushman/buildsqlx) — Go database query builder library for PostgreSQL ☆`184`
- [galeone/igor](https://github.com/galeone/igor) — igor is an abstraction layer for PostgreSQL with a gorm like syntax. ☆`126`
- [cristalhq/builq](https://github.com/cristalhq/builq) — Easily build SQL queries in Go. ☆`96`
- [HnH/qry](https://github.com/HnH/qry) — SQL queries in raw files ☆`35`
- [JiveGroup/FluentSQL](https://github.com/JiveGroup/FluentSQL) — Fluent SQL - flexible and powerful SQL string builder ☆`18`
### Search and Analytic Databases

- [elastic/go-elasticsearch](https://github.com/elastic/go-elasticsearch) — The official Go client for Elasticsearch ☆`6,004`
- [ClickHouse/clickhouse-go](https://github.com/ClickHouse/clickhouse-go) — Golang driver for ClickHouse ☆`3,223`
- [sourcegraph/zoekt](https://github.com/sourcegraph/zoekt) — Fast trigram-based code search ☆`1,321`
- [sdqri/effdsl](https://github.com/sdqri/effdsl) — Elasticsearch query builder for golang ☆`34`
## DevOps & Build

### Backup

- [restic/restic](https://github.com/restic/restic) — Fast, secure backup program ☆`31,559`
- [gilbertchen/duplicacy](https://github.com/gilbertchen/duplicacy) — Cloud backup tool ☆`5,597`
### Build Automation

- [air-verse/air](https://github.com/air-verse/air) — Live reload for Go apps ☆`22,593`
- [go-task/task](https://github.com/go-task/task) — A task runner / simpler Make alternative written in Go ☆`14,516`
- [joerdav/xc](https://github.com/joerdav/xc) — Markdown defined task runner. ☆`1,362`
- [goyek/goyek](https://github.com/goyek/goyek) — Task automation Go library ☆`675`
- [flowexec/flow](https://github.com/flowexec/flow) — Local developer automation platform that flows with you ☆`128`
### CI/CD

- [harness/harness](https://github.com/harness/harness) — End-to-end developer platform ☆`33,753`
- [woodpecker-ci/woodpecker](https://github.com/woodpecker-ci/woodpecker) — Simple, powerful CI/CD engine ☆`6,188`
- [ovh/cds](https://github.com/ovh/cds) — Enterprise CI/CD platform ☆`4,794`
- [raviqqe/muffet](https://github.com/raviqqe/muffet) — Fast website link checker ☆`2,580`
- [pipe-cd/pipecd](https://github.com/pipe-cd/pipecd) — The One CD for All {applications, platforms, operations} ☆`1,239`
- [jenkins-zh/jenkins-cli](https://github.com/jenkins-zh/jenkins-cli) — Jenkins CLI allows you to manage your Jenkins in an easy way ☆`408`
- [vladopajic/go-test-coverage](https://github.com/vladopajic/go-test-coverage) — Report test coverage threshold issues ☆`208`
- [appleboy/drone-scp](https://github.com/appleboy/drone-scp) — Copy files via SSH for Drone ☆`163`
- [nikogura/gomason](https://github.com/nikogura/gomason) — A tool for testing, building, signing, and publishing binaries. ☆`66`
- [appleboy/drone-jenkins](https://github.com/appleboy/drone-jenkins) — Drone plugin for trigger Jenkins jobs. ☆`41`
- [opnlabs/dot](https://github.com/opnlabs/dot) — Minimal CI using Docker ☆`32`
- [gha-common/go-beautiful-html-coverage](https://github.com/gha-common/go-beautiful-html-coverage) — GitHub Action for code coverage reports ☆`20`
### Containers

- [moby/moby](https://github.com/moby/moby) — Container ecosystem components ☆`71,307`
- [traefik/traefik](https://github.com/traefik/traefik) — The Cloud Native Application Proxy ☆`60,866`
- [ko-build/ko](https://github.com/ko-build/ko) — Build and deploy Go applications ☆`8,289`
- [s0rg/decompose](https://github.com/s0rg/decompose) — Reverse-engineering tool for docker environments ☆`122`
- [x1unix/docker-go-mingw](https://github.com/x1unix/docker-go-mingw) — Docker for Go with MinGW toolchain ☆`53`
### DevOps Utilities

- [go-gitea/gitea](https://github.com/go-gitea/gitea) — Self-hosted Git service ☆`52,910`
- [moovweb/gvm](https://github.com/moovweb/gvm) — Go Version Manager ☆`11,469`
- [TwiN/gatus](https://github.com/TwiN/gatus) — The most advanced status page in the world ☆`9,453`
- [bitfield/script](https://github.com/bitfield/script) — Making it easy to write shell-like scripts in Go ☆`6,903`
- [fleetdm/fleet](https://github.com/fleetdm/fleet) — Open device management ☆`5,881`
- [taubyte/tau](https://github.com/taubyte/tau) — Fullstack Workspace for Humans & Machines ☆`4,871`
- [megaease/easeprobe](https://github.com/megaease/easeprobe) — Service health monitoring tool ☆`2,287`
- [ajvb/kala](https://github.com/ajvb/kala) — Modern Job Scheduler ☆`2,162`
- [gabrie30/ghorg](https://github.com/gabrie30/ghorg) — Clone entire GitHub orgs ☆`1,917`
- [sanbornm/go-selfupdate](https://github.com/sanbornm/go-selfupdate) — Enable your Go applications to self update ☆`1,661`
- [yusufcanb/tlm](https://github.com/yusufcanb/tlm) — Local CLI Copilot, powered by Ollama. ☆`1,462`
- [ovh/utask](https://github.com/ovh/utask) — Automation engine with YAML config ☆`1,349`
- [TimothyYe/skm](https://github.com/TimothyYe/skm) — A simple and powerful SSH keys manager ☆`998`
- [scaleway/scaleway-cli](https://github.com/scaleway/scaleway-cli) — Command Line Interface for Scaleway ☆`946`
- [alexliesenfeld/health](https://github.com/alexliesenfeld/health) — A simple and flexible health check library for Go. ☆`826`
- [kool-dev/kool](https://github.com/kool-dev/kool) — Dev to cloud web apps made easy ☆`711`
- [kevincobain2000/gobrew](https://github.com/kevincobain2000/gobrew) — Go version manager without root ☆`411`
- [appleboy/easyssh-proxy](https://github.com/appleboy/easyssh-proxy) — Simple SSH protocol implementation ☆`344`
- [xitonix/trubka](https://github.com/xitonix/trubka) — A CLI tool for Kafka ☆`336`
- [emicklei/mora](https://github.com/emicklei/mora) — MongoDB generic REST server in Go ☆`316`
- [thevxn/dish](https://github.com/thevxn/dish) — A simple, remotely configurable monitoring service. ☆`263`
- [jkaninda/goma-gateway](https://github.com/jkaninda/goma-gateway) — Lightweight API gateway and proxy ☆`163`
- [datarootsio/tf-profile](https://github.com/datarootsio/tf-profile) — Profile Terraform runs ☆`163`
- [kazhuravlev/healthcheck](https://github.com/kazhuravlev/healthcheck) — Readiness probes for Kubernetes application ☆`22`
### Infrastructure

- [hashicorp/packer](https://github.com/hashicorp/packer) — Build machine images from config ☆`15,543`
- [pomerium/pomerium](https://github.com/pomerium/pomerium) — Pomerium is an identity and context-aware access proxy. ☆`4,604`
- [peak/s5cmd](https://github.com/peak/s5cmd) — Parallel S3 and local filesystem execution tool. ☆`3,822`
- [aptly-dev/aptly](https://github.com/aptly-dev/aptly) — aptly - Debian repository management tool ☆`2,744`
- [KusionStack/kusion](https://github.com/KusionStack/kusion) — Declarative platform orchestrator ☆`1,243`
- [oxyno-zeta/s3-proxy](https://github.com/oxyno-zeta/s3-proxy) — S3 reverse proxy with auth ☆`426`
### Kubernetes

- [kubernetes/kubernetes](https://github.com/kubernetes/kubernetes) — Production-Grade Container Scheduling and Management ☆`119,626`
- [kubernetes/minikube](https://github.com/kubernetes/minikube) — Run Kubernetes locally ☆`31,332`
- [k3s-io/k3s](https://github.com/k3s-io/k3s) — Lightweight Kubernetes ☆`31,796`
- [kubernetes-sigs/kind](https://github.com/kubernetes-sigs/kind) — Kubernetes IN Docker - local clusters for testing Kubernetes ☆`14,873`
- [kubeshark/kubeshark](https://github.com/kubeshark/kubeshark) — API traffic analyzer for Kubernetes ☆`11,657`
- [flannel-io/flannel](https://github.com/flannel-io/flannel) — Network fabric for containers ☆`9,362`
- [getanteon/anteon](https://github.com/getanteon/anteon) — eBPF Kubernetes monitoring tool ☆`8,541`
- [kubevela/kubevela](https://github.com/kubevela/kubevela) — The Modern Application Platform. ☆`7,653`
- [k3d-io/k3d](https://github.com/k3d-io/k3d) — Little helper to run CNCF's k3s in Docker ☆`6,191`
- [stefanprodan/podinfo](https://github.com/stefanprodan/podinfo) — Go microservice template for Kubernetes ☆`5,804`
- [apecloud/kubeblocks](https://github.com/apecloud/kubeblocks) — Kubernetes operator for databases ☆`2,938`
- [kubenetworks/kubevpn](https://github.com/kubenetworks/kubevpn) — Connect to Kubernetes cluster network ☆`1,279`
- [abahmed/kwatch](https://github.com/abahmed/kwatch) — monitor & detect crashes in your Kubernetes(K8s) cluster instantly ☆`992`
- [getanteon/alaz](https://github.com/getanteon/alaz) — eBPF agent for K8s observability ☆`714`
### Load Testing

- [grafana/k6](https://github.com/grafana/k6) — A modern load testing tool, using Go and JavaScript ☆`29,564`
- [tsenart/vegeta](https://github.com/tsenart/vegeta) — HTTP load testing tool and library. It's over 9000! ☆`24,813`
- [codesenberg/bombardier](https://github.com/codesenberg/bombardier) — Fast cross-platform HTTP benchmarking tool written in Go ☆`6,680`
- [rogerwelin/cassowary](https://github.com/rogerwelin/cassowary) — Modern cross-platform HTTP load-testing tool written in Go ☆`810`
## Email

- [axllent/mailpit](https://github.com/axllent/mailpit) — An email and SMTP testing tool with API for developers ☆`8,389`
- [foxcpp/maddy](https://github.com/foxcpp/maddy) — Composable all-in-one mail server. ☆`5,780`
- [mjl-/mox](https://github.com/mjl-/mox) — Modern secure mail server ☆`5,336`
- [matcornic/hermes](https://github.com/matcornic/hermes) — Clean HTML email generator ☆`3,023`
- [AfterShip/email-verifier](https://github.com/AfterShip/email-verifier) — Email verification without sending emails ☆`1,490`
- [wneessen/go-mail](https://github.com/wneessen/go-mail) — Easy to use, yet comprehensive library for sending mails with Go ☆`1,229`
- [sendgrid/sendgrid-go](https://github.com/sendgrid/sendgrid-go) — The Official Twilio SendGrid Golang API Library ☆`1,045`
- [mailgun/mailgun-go](https://github.com/mailgun/mailgun-go) — Go library for the Mailgun API. ☆`742`
- [xhit/go-simple-mail](https://github.com/xhit/go-simple-mail) — Simple mail sending with TLS/SSL ☆`689`
- [emersion/go-message](https://github.com/emersion/go-message) — Internet Message Format library ☆`432`
- [vanng822/go-premailer](https://github.com/vanng822/go-premailer) — Inline CSS for HTML mail ☆`183`
- [truemail-rb/truemail-go](https://github.com/truemail-rb/truemail-go) — Email validator via Regex, DNS, SMTP ☆`129`
- [toorop/go-dkim](https://github.com/toorop/go-dkim) — DKIM package for golang ☆`99`
- [dimuska139/go-email-normalizer](https://github.com/dimuska139/go-email-normalizer) — Normalize email addresses ☆`76`
- [valord577/mailx](https://github.com/valord577/mailx) — A library that makes it easier to send email via SMTP. ☆`20`
## Finance & Blockchain

### Blockchain

- [ethereum/go-ethereum](https://github.com/ethereum/go-ethereum) — Go implementation of the Ethereum protocol ☆`50,599`
- [ipfs/kubo](https://github.com/ipfs/kubo) — An IPFS implementation in Go ☆`16,864`
- [lightningnetwork/lnd](https://github.com/lightningnetwork/lnd) — Lightning Network Daemon ☆`8,081`
- [cosmos/cosmos-sdk](https://github.com/cosmos/cosmos-sdk) — A Framework for Building High Value Public Blockchains ☆`6,888`
- [gagliardetto/solana-go](https://github.com/gagliardetto/solana-go) — Go SDK library and RPC client for the Solana Blockchain ☆`1,493`
- [gnolang/gno](https://github.com/gnolang/gno) — Interpreted Go virtual machine ☆`1,039`
- [cometbft/cometbft](https://github.com/cometbft/cometbft) — Byzantine fault-tolerant consensus ☆`837`
- [ChainSafe/gossamer](https://github.com/ChainSafe/gossamer) — Go Implementation of the Polkadot Host ☆`458`
### Financial

- [shopspring/decimal](https://github.com/shopspring/decimal) — Arbitrary-precision fixed-point decimal numbers in Go ☆`7,166`
- [achannarasappa/ticker](https://github.com/achannarasappa/ticker) — Terminal stock and crypto tracker ☆`5,867`
- [Rhymond/go-money](https://github.com/Rhymond/go-money) — Go implementation of Fowler's Money pattern ☆`1,835`
- [c9s/bbgo](https://github.com/c9s/bbgo) — The modern cryptocurrency trading bot framework written in Go. ☆`1,581`
- [formancehq/ledger](https://github.com/formancehq/ledger) — The programmable open source core ledger for fintech ☆`1,102`
- [bojanz/currency](https://github.com/bojanz/currency) — Currency handling for Go. ☆`620`
- [moov-io/ach](https://github.com/moov-io/ach) — ACH file reader, writer, validator ☆`521`
- [invopop/gobl](https://github.com/invopop/gobl) — Go Business Language ☆`240`
- [govalues/decimal](https://github.com/govalues/decimal) — Correctly rounded decimals for Go ☆`213`
- [quagmt/udecimal](https://github.com/quagmt/udecimal) — High-precision decimal library ☆`170`
- [jovandeginste/payme](https://github.com/jovandeginste/payme) — QR code generator (ASCII & PNG) for SEPA payments ☆`89`
- [jokruger/dec128](https://github.com/jokruger/dec128) — High performance 128-bit fixed-point decimal numbers in go. ☆`38`
- [govalues/money](https://github.com/govalues/money) — Correctly rounded monetary amounts and exchange rates for Go ☆`46`
- [nikolaydubina/fpmoney](https://github.com/nikolaydubina/fpmoney) — Fixed-Point Decimal Money ☆`35`
- [nikolaydubina/fpdecimal](https://github.com/nikolaydubina/fpdecimal) — Fixed-Point Decimals ☆`34`
### Payment APIs

- [stripe/stripe-go](https://github.com/stripe/stripe-go) — Stripe API library for Go ☆`2,492`
- [plutov/paypal](https://github.com/plutov/paypal) — Golang client for PayPal REST API ☆`769`
- [brunomvsouza/ynab.go](https://github.com/brunomvsouza/ynab.go) — Client for YNAB API ☆`78`
## GUI & Desktop

### GUI

- [fyne-io/fyne](https://github.com/fyne-io/fyne) — Cross platform GUI toolkit in Go inspired by Material Design ☆`27,716`
- [webview/webview](https://github.com/webview/webview) — Tiny webview library for Go ☆`13,767`
- [therecipe/qt](https://github.com/therecipe/qt) — Qt bindings for Go ☆`10,768`
- [go-vgo/robotgo](https://github.com/go-vgo/robotgo) — Cross-platform RPA and GUI automation ☆`10,556`
- [maxence-charriere/go-app](https://github.com/maxence-charriere/go-app) — Build progressive web apps with Go and WASM ☆`8,849`
- [lxn/walk](https://github.com/lxn/walk) — A Windows GUI toolkit for the Go Programming Language ☆`7,050`
- [progrium/darwinkit](https://github.com/progrium/darwinkit) — Native Mac APIs for Go. Previously known as MacDriver ☆`5,374`
- [getlantern/systray](https://github.com/getlantern/systray) — Cross-platform systray library ☆`3,641`
- [cogentcore/core](https://github.com/cogentcore/core) — Powerful GUI framework for Go ☆`2,296`
- [gotk3/gotk3](https://github.com/gotk3/gotk3) — Go bindings for GTK3 ☆`2,201`
- [roblillack/spot](https://github.com/roblillack/spot) — React-like desktop GUI toolkit for Go ☆`1,251`
- [ncruces/zenity](https://github.com/ncruces/zenity) — Zenity dialogs for Golang, Windows, macOS ☆`882`
- [energye/energy](https://github.com/energye/energy) — CEF-based GUI framework ☆`564`
- [AllenDang/cimgui-go](https://github.com/AllenDang/cimgui-go) — Auto generated Go wrapper for Dear ImGui via cimgui ☆`484`
- [richardwilkes/unison](https://github.com/richardwilkes/unison) — Unified GUI toolkit for Go ☆`310`
### Windows

- [go-ole/go-ole](https://github.com/go-ole/go-ole) — win32 ole implementation for golang ☆`1,287`
- [gonutz/d3d9](https://github.com/gonutz/d3d9) — Direct3D9 wrapper for Go. ☆`163`
## Game Development

### Game Engines

- [hajimehoshi/ebiten](https://github.com/hajimehoshi/ebiten) — A dead simple 2D game engine for Go ☆`12,822`
- [fogleman/nes](https://github.com/fogleman/nes) — NES emulator written in Go. ☆`5,633`
- [topfreegames/pitaya](https://github.com/topfreegames/pitaya) — Game server with clustering support ☆`2,705`
- [xiaonanln/goworld](https://github.com/xiaonanln/goworld) — Distributed game server engine ☆`2,695`
- [gen2brain/raylib-go](https://github.com/gen2brain/raylib-go) — Go bindings for raylib ☆`2,299`
- [oakmound/oak](https://github.com/oakmound/oak) — A pure Go game engine ☆`1,649`
- [JoelOtter/termloop](https://github.com/JoelOtter/termloop) — Terminal-based game engine for Go, built on top of Termbox ☆`1,470`
- [xtaci/gonet](https://github.com/xtaci/gonet) — A Game Server Skeleton in golang. ☆`1,289`
- [gopxl/pixel](https://github.com/gopxl/pixel) — A hand-crafted 2D game library in Go. ☆`369`
- [ungerik/go3d](https://github.com/ungerik/go3d) — A performance oriented 2D/3D math package for Go ☆`335`
- [mlange-42/ark](https://github.com/mlange-42/ark) — Ark -- Archetype-based Entity Component System (ECS) for Go. ☆`196`
- [kelindar/tile](https://github.com/kelindar/tile) — 2D grid engine for games ☆`209`
- [andygeiss/ecs](https://github.com/andygeiss/ecs) — Entity Component System for games ☆`166`
- [gonutz/prototype](https://github.com/gonutz/prototype) — 2D game prototyping framework ☆`108`
- [s0rg/fantasyname](https://github.com/s0rg/fantasyname) — RinkWorks fantasy name generator for golang ☆`39`
- [s0rg/grid](https://github.com/s0rg/grid) — Generic 2D grid ☆`25`
### OpenGL

- [go-gl/glfw](https://github.com/go-gl/glfw) — Go bindings for GLFW 3 ☆`1,657`
- [go-gl/gl](https://github.com/go-gl/gl) — Go bindings for OpenGL (generated via glow) ☆`1,181`
- [go-gl/mathgl](https://github.com/go-gl/mathgl) — A pure Go 3D math library. ☆`593`
## Geospatial

- [tidwall/tile38](https://github.com/tidwall/tile38) — Real-time Geospatial and Geofencing ☆`9,553`
- [golang/geo](https://github.com/golang/geo) — S2 geometry library in Go ☆`1,811`
- [consbio/mbtileserver](https://github.com/consbio/mbtileserver) — MBTiles server in Go ☆`767`
- [spatial-go/geoos](https://github.com/spatial-go/geoos) — Spatial data and geometric algorithms ☆`527`
- [paulmach/osm](https://github.com/paulmach/osm) — OpenStreetMap data library ☆`438`
- [uber/h3-go](https://github.com/uber/h3-go) — H3 hexagonal geospatial indexing ☆`387`
- [airbusgeo/godal](https://github.com/airbusgeo/godal) — GDAL wrapper for Go ☆`173`
- [peterstace/simplefeatures](https://github.com/peterstace/simplefeatures) — OpenGIS Simple Feature implementation ☆`165`
- [wroge/wgs84](https://github.com/wroge/wgs84) — Zero-dep coordinate transformations ☆`140`
- [pantrif/s2-geojson](https://github.com/pantrif/s2-geojson) — Visualize S2 cells on a map ☆`36`
## Go Tooling

### Compilers

- [gopherjs/gopherjs](https://github.com/gopherjs/gopherjs) — A compiler from Go to JavaScript for running Go code in a browser ☆`13,093`
- [yassinebenaid/bunster](https://github.com/yassinebenaid/bunster) — Compile shell scripts to static binaries. ☆`2,628`
- [Konstantin8105/c4go](https://github.com/Konstantin8105/c4go) — Transpiling C code to Go code ☆`376`
- [go2hx/go2hx](https://github.com/go2hx/go2hx) — Import Go libraries in Haxe ☆`146`
### Editor Plugins

- [fatih/vim-go](https://github.com/fatih/vim-go) — Go development plugin for Vim ☆`16,220`
- [visualfc/liteide](https://github.com/visualfc/liteide) — LiteIDE is a simple, open source, cross-platform Go IDE. ☆`7,738`
- [nsf/gocode](https://github.com/nsf/gocode) — An autocompletion daemon for the Go programming language ☆`5,002`
- [golang/vscode-go](https://github.com/golang/vscode-go) — Go extension for Visual Studio Code ☆`4,175`
- [dominikh/go-mode.el](https://github.com/dominikh/go-mode.el) — Emacs mode for the Go programming language ☆`1,447`
- [incu6us/goimports-reviser](https://github.com/incu6us/goimports-reviser) — Imports sorting and code formatting tool ☆`708`
### Generate Tools

- [xuri/xgen](https://github.com/xuri/xgen) — XSD parser and code generator ☆`402`
- [kazhuravlev/options-gen](https://github.com/kazhuravlev/options-gen) — Codegen for functional options in go projects ☆`104`
- [g4s8/envdoc](https://github.com/g4s8/envdoc) — Go tool to generate documentation for environment variables ☆`94`
### Go Tools

- [go-swagger/go-swagger](https://github.com/go-swagger/go-swagger) — Swagger 2.0 implementation for go ☆`9,914`
- [ondrajz/go-callvis](https://github.com/ondrajz/go-callvis) — Visualize call graph of a Go program using Graphviz ☆`6,438`
- [Zxilly/go-size-analyzer](https://github.com/Zxilly/go-size-analyzer) — Analyze compiled Go binary size ☆`1,867`
- [pointlander/peg](https://github.com/pointlander/peg) — PEG parser generator for Go ☆`1,093`
- [janpfeifer/gonb](https://github.com/janpfeifer/gonb) — Go notebook kernel for Jupyter ☆`970`
- [safedep/vet](https://github.com/safedep/vet) — Protect against malicious open source packages ☆`927`
- [alajmo/sake](https://github.com/alajmo/sake) — Task runner for local and remote hosts ☆`739`
- [goccmack/gocc](https://github.com/goccmack/gocc) — Parser and scanner generator ☆`654`
- [moshebe/gebug](https://github.com/moshebe/gebug) — Debug Dockerized Go apps ☆`634`
- [edwingeng/hotswap](https://github.com/edwingeng/hotswap) — Hot reload Go code without restart ☆`415`
- [iyashjayesh/monigo](https://github.com/iyashjayesh/monigo) — Performance monitoring library ☆`390`
- [becheran/roumon](https://github.com/becheran/roumon) — Universal goroutine monitor using pprof and termui ☆`235`
- [bitfield/gotestdox](https://github.com/bitfield/gotestdox) — A tool for formatting Go test results as readable documentation ☆`183`
- [ahmedakef/gotutor](https://github.com/ahmedakef/gotutor) — Online Go Debugger & Visualizer ☆`71`
- [bobg/decouple](https://github.com/bobg/decouple) — find overspecified function parameters in Go code ☆`33`
- [bobg/modver](https://github.com/bobg/modver) — a tool that helps you obey semantic versioning rules in your Go module ☆`21`
- [dustinblackman/gomodrun](https://github.com/dustinblackman/gomodrun) — Run binaries from go.mod ☆`38`
## Hardware & IoT

### Hardware

- [shirou/gopsutil](https://github.com/shirou/gopsutil) — psutil for golang ☆`11,636`
- [arduino/arduino-cli](https://github.com/arduino/arduino-cli) — Arduino command line tool ☆`4,759`
- [jaypipes/ghw](https://github.com/jaypipes/ghw) — Go HardWare discovery/inspection library ☆`1,803`
- [zcalusic/sysinfo](https://github.com/zcalusic/sysinfo) — Linux system information library ☆`572`
### IoT

- [hybridgroup/gobot](https://github.com/hybridgroup/gobot) — Robotics and IoT framework ☆`9,358`
- [lf-edge/ekuiper](https://github.com/lf-edge/ekuiper) — Lightweight data stream processing engine for IoT edge ☆`1,664`
- [rulego/rulego](https://github.com/rulego/rulego) — Lightweight rule engine framework ☆`1,390`
- [Edgenesis/shifu](https://github.com/Edgenesis/shifu) — Kubernetes-native IoT gateway ☆`1,388`
- [e154/smart-home](https://github.com/e154/smart-home) — software package for automation ☆`96`
- [maxatome/go-vitotrol](https://github.com/maxatome/go-vitotrol) — golang client library to Viessmann Vitotrol web service ☆`23`
## Networking

### Consensus

- [hashicorp/raft](https://github.com/hashicorp/raft) — Golang implementation of the Raft consensus protocol ☆`8,885`
- [lni/dragonboat](https://github.com/lni/dragonboat) — Multi-group Raft consensus library ☆`5,288`
- [etcd-io/raft](https://github.com/etcd-io/raft) — Raft library for maintaining a replicated state machine ☆`970`
- [vadiminshakov/committer](https://github.com/vadiminshakov/committer) — 2PC and 3PC protocols for Go ☆`41`
### DNS

- [miekg/dns](https://github.com/miekg/dns) — DNS library in Go ☆`8,603`
- [0xERR0R/blocky](https://github.com/0xERR0R/blocky) — DNS ad-blocker for local networks ☆`5,860`
- [hashicorp/mdns](https://github.com/hashicorp/mdns) — Simple mDNS client/server library in Golang ☆`1,322`
- [semihalev/sdns](https://github.com/semihalev/sdns) — High-performance recursive DNS ☆`1,024`
- [mosajjal/dnsmonster](https://github.com/mosajjal/dnsmonster) — Passive DNS Capture and Monitoring Toolkit ☆`348`
- [joeig/go-powerdns](https://github.com/joeig/go-powerdns) — PowerDNS API client for Go (community project) ☆`103`
### Distributed Utilities

- [luraproject/lura](https://github.com/luraproject/lura) — Ultra-performant API gateway ☆`6,710`
- [chrislusf/gleam](https://github.com/chrislusf/gleam) — Distributed map/reduce in Go ☆`3,553`
- [bsm/redislock](https://github.com/bsm/redislock) — Simplified distributed locking implementation using Redis ☆`1,728`
- [k8gb-io/k8gb](https://github.com/k8gb-io/k8gb) — A cloud native Kubernetes Global Balancer ☆`1,134`
- [temporalio/sdk-go](https://github.com/temporalio/sdk-go) — Temporal Go SDK ☆`793`
- [AppsFlyer/go-sundheit](https://github.com/AppsFlyer/go-sundheit) — Health checks library for Go ☆`560`
- [tarmac-project/tarmac](https://github.com/tarmac-project/tarmac) — Functions as Monolith or Microservices ☆`340`
- [italolelis/outboxer](https://github.com/italolelis/outboxer) — A library that implements the outboxer pattern in go ☆`166`
- [capillariesio/capillaries](https://github.com/capillariesio/capillaries) — Distributed batch data processing framework ☆`69`
- [svcavallar/celeriac.v1](https://github.com/svcavallar/celeriac.v1) — Celery client for Go ☆`76`
- [sanketplus/go-mysql-lock](https://github.com/sanketplus/go-mysql-lock) — MySQL Backed Locking Primitive ☆`66`
- [pdupub/go-pdu](https://github.com/pdupub/go-pdu) — An PDU implementation in Go ☆`49`
- [mbrostami/consistenthash](https://github.com/mbrostami/consistenthash) — Consistent hashing implementation ☆`30`
### HTTP & Proxy

- [valyala/fasthttp](https://github.com/valyala/fasthttp) — Fast HTTP package for Go ☆`23,182`
- [elazarl/goproxy](https://github.com/elazarl/goproxy) — An HTTP proxy library for Go ☆`6,554`
- [eduardonunesp/sslb](https://github.com/eduardonunesp/sslb) — Simple load balancer ☆`151`
- [wzshiming/httpproxy](https://github.com/wzshiming/httpproxy) — HTTP proxy handler and dialer ☆`31`
### HTTP Clients

- [go-resty/resty](https://github.com/go-resty/resty) — Simple HTTP, REST, and SSE client library for Go ☆`11,443`
- [imroc/req](https://github.com/imroc/req) — Simple Go HTTP client with Black Magic ☆`4,720`
- [gojek/heimdall](https://github.com/gojek/heimdall) — An enhanced HTTP client for Go ☆`2,700`
- [hashicorp/go-retryablehttp](https://github.com/hashicorp/go-retryablehttp) — Retryable HTTP client in Go ☆`2,256`
- [levigross/grequests](https://github.com/levigross/grequests) — A Go "clone" of the great and famous Requests library ☆`2,183`
- [dghubble/sling](https://github.com/dghubble/sling) — A Go HTTP client library for creating and sending API requests ☆`1,717`
- [earthboundkid/requests](https://github.com/earthboundkid/requests) — HTTP requests for Gophers ☆`1,661`
- [bogdanfinn/tls-client](https://github.com/bogdanfinn/tls-client) — HTTP client with TLS fingerprint spoofing ☆`1,389`
- [Noooste/azuretls-client](https://github.com/Noooste/azuretls-client) — HTTP client to spoof TLS/JA3 fingerprint ☆`402`
- [monaco-io/request](https://github.com/monaco-io/request) — go request, go http client ☆`294`
- [NdoleStudio/go-otelroundtripper](https://github.com/NdoleStudio/go-otelroundtripper) — OpenTelemetry metrics for HTTP clients ☆`85`
- [opus-domini/fast-shot](https://github.com/opus-domini/fast-shot) — Fluent HTTP client for Go ☆`94`
- [go-zoox/fetch](https://github.com/go-zoox/fetch) — Powerful HTTP client for Go ☆`88`
- [rezmoss/axios4go](https://github.com/rezmoss/axios4go) — Axios-inspired HTTP client ☆`30`
### Servers

- [caddyserver/caddy](https://github.com/caddyserver/caddy) — Multi-platform web server with HTTPS ☆`68,925`
- [minio/minio](https://github.com/minio/minio) — High-performance object storage ☆`59,569`
- [pocketbase/pocketbase](https://github.com/pocketbase/pocketbase) — Open Source realtime backend in 1 file ☆`54,841`
- [etcd-io/etcd](https://github.com/etcd-io/etcd) — Distributed key-value store ☆`51,233`
- [drakkan/sftpgo](https://github.com/drakkan/sftpgo) — Full-featured SFTP/FTP/HTTP server ☆`11,531`
- [adnanh/webhook](https://github.com/adnanh/webhook) — Lightweight webhook server ☆`11,471`
- [roadrunner-server/roadrunner](https://github.com/roadrunner-server/roadrunner) — High-performance PHP application server ☆`8,364`
- [easegress-io/easegress](https://github.com/easegress-io/easegress) — A Cloud Native traffic orchestration system ☆`5,867`
- [flipt-io/flipt](https://github.com/flipt-io/flipt) — Enterprise-ready, Git native feature management solution ☆`4,672`
- [charmbracelet/wish](https://github.com/charmbracelet/wish) — Make SSH apps, just like that! ☆`4,683`
- [getfider/fider](https://github.com/getfider/fider) — Open platform to collect and prioritize feedback ☆`3,969`
- [xyproto/algernon](https://github.com/xyproto/algernon) — Web server with Lua and Markdown ☆`2,969`
- [openflagr/flagr](https://github.com/openflagr/flagr) — Feature flagging and A/B testing ☆`2,562`
- [thomaspoignant/go-feature-flag](https://github.com/thomaspoignant/go-feature-flag) — Open source feature flag solution ☆`1,895`
- [msoap/shell2http](https://github.com/msoap/shell2http) — Executing shell commands via HTTP server ☆`1,467`
- [openrundev/openrun](https://github.com/openrundev/openrun) — Open source Cloud Run alternative ☆`713`
- [webhookx-io/webhookx](https://github.com/webhookx-io/webhookx) — The Next-Generation Webhooks Gateway. ☆`270`
- [baalimago/wd-41](https://github.com/baalimago/wd-41) — Web-Development 41, a static web server with live-reload ☆`150`
- [blind-oracle/cortex-tenant](https://github.com/blind-oracle/cortex-tenant) — Prometheus proxy with tenant ID injection ☆`130`
- [rekby/lets-proxy2](https://github.com/rekby/lets-proxy2) — Reverse proxy with auto TLS ☆`101`
- [42atomys/webhooked](https://github.com/42atomys/webhooked) — A webhook receiver on steroids. ☆`41`
### Network Utilities

- [fortio/fortio](https://github.com/fortio/fortio) — Load testing and echo server ☆`3,656`
- [hashicorp/go-getter](https://github.com/hashicorp/go-getter) — Download files from URLs ☆`1,788`
- [TimothyYe/godns](https://github.com/TimothyYe/godns) — Dynamic DNS client for multiple providers ☆`1,723`
- [cavaliergopher/grab](https://github.com/cavaliergopher/grab) — Download manager package ☆`1,464`
- [schollz/peerdiscovery](https://github.com/schollz/peerdiscovery) — Cross-platform local peer discovery ☆`668`
- [fclairamb/ftpserverlib](https://github.com/fclairamb/ftpserverlib) — FTP server library for Go ☆`461`
- [skibish/ddns](https://github.com/skibish/ddns) — Personal DDNS client with Digital Ocean Networking DNS as backend. ☆`267`
- [assafmo/joincap](https://github.com/assafmo/joincap) — Merge pcap files ☆`219`
- [c-robinson/iplib](https://github.com/c-robinson/iplib) — A library for working with IP addresses and networks in Go ☆`151`
- [gaissmai/bart](https://github.com/gaissmai/bart) — Balanced routing table ☆`112`
- [alegrey91/fwdctl](https://github.com/alegrey91/fwdctl) — Manage IPTables forwards via CLI ☆`73`
### P2P & Torrent

- [anacrolix/torrent](https://github.com/anacrolix/torrent) — Full-featured BitTorrent client package and utilities ☆`5,925`
- [dragonflyoss/dragonfly](https://github.com/dragonflyoss/dragonfly) — P2P-based container image distribution ☆`2,951`
- [cenkalti/rain](https://github.com/cenkalti/rain) — BitTorrent client and library in Go ☆`1,102`
- [anacrolix/dht](https://github.com/anacrolix/dht) — DHT for BitTorrent ☆`346`
### Protocols

- [pion/webrtc](https://github.com/pion/webrtc) — Pure Go implementation of the WebRTC API ☆`15,881`
- [quic-go/quic-go](https://github.com/quic-go/quic-go) — A production-ready QUIC implementation in pure Go ☆`11,290`
- [google/gopacket](https://github.com/google/gopacket) — Provides packet processing capabilities for Go ☆`6,706`
- [osrg/gobgp](https://github.com/osrg/gobgp) — BGP implemented in the Go Programming Language ☆`3,947`
- [lxzan/gws](https://github.com/lxzan/gws) — Fast websocket server and client ☆`1,687`
- [gosnmp/gosnmp](https://github.com/gosnmp/gosnmp) — An SNMP library written in Go ☆`1,235`
- [bluenviron/gortsplib](https://github.com/bluenviron/gortsplib) — RTSP client and server library for the Go programming language ☆`874`
- [ccding/go-stun](https://github.com/ccding/go-stun) — A go implementation of the STUN client (RFC 3489 and RFC 5389) ☆`715`
- [google/gnxi](https://github.com/google/gnxi) — gNXI Tools - gRPC Network Management/Operations Interface Tools ☆`284`
- [jeroenrinzema/psql-wire](https://github.com/jeroenrinzema/psql-wire) — PostgreSQL wire protocol for Go ☆`210`
- [jimlambrt/gldap](https://github.com/jimlambrt/gldap) — Build LDAP services w/ Go ☆`118`
- [soypat/natiu-mqtt](https://github.com/soypat/natiu-mqtt) — Extensible MQTT for embedded systems ☆`101`
### RPC

- [grpc/grpc-go](https://github.com/grpc/grpc-go) — The Go language implementation of gRPC. HTTP/2 based RPC ☆`22,686`
- [hprose/hprose-golang](https://github.com/hprose/hprose-golang) — Cross-language RPC for Go ☆`1,263`
- [lesismal/arpc](https://github.com/lesismal/arpc) — Two-way RPC with broadcast support ☆`1,085`
- [ybbus/jsonrpc](https://github.com/ybbus/jsonrpc) — A simple go implementation of json rpc 2.0 client over http ☆`367`
- [osamingo/jsonrpc](https://github.com/osamingo/jsonrpc) — The jsonrpc package helps implement of JSON-RPC 2.0 ☆`192`
### SSH & SFTP

- [gliderlabs/ssh](https://github.com/gliderlabs/ssh) — Easy SSH servers in Golang ☆`4,055`
- [pkg/sftp](https://github.com/pkg/sftp) — SFTP support for the go.crypto/ssh package ☆`1,629`
- [masterzen/winrm](https://github.com/masterzen/winrm) — Windows remote command library ☆`456`
### TCP/UDP Frameworks

- [xtaci/kcptun](https://github.com/xtaci/kcptun) — Quantum-safe secure tunnel ☆`14,324`
- [panjf2000/gnet](https://github.com/panjf2000/gnet) — High-performance event-loop network ☆`11,018`
- [cloudwego/netpoll](https://github.com/cloudwego/netpoll) — High-performance I/O framework ☆`4,505`
- [xtaci/kcp-go](https://github.com/xtaci/kcp-go) — A crypto-secure Reliable-UDP library for Golang with FEC support. ☆`4,377`
- [lesismal/nbio](https://github.com/lesismal/nbio) — High-performance network library ☆`2,687`
- [Allenxuxu/gev](https://github.com/Allenxuxu/gev) — Lightweight non-blocking TCP library ☆`1,771`
- [xtaci/gaio](https://github.com/xtaci/gaio) — High-performance, minimalist async-io (proactor) networking for Golang. ☆`800`
- [cheng-zhongliang/event](https://github.com/cheng-zhongliang/event) — Simple I/O event notification library wirtten in Golang ☆`119`
- [fish-tennis/gnet](https://github.com/fish-tennis/gnet) — high performance net library for game server ☆`26`
### VPN & Tunneling

- [cloudflare/cloudflared](https://github.com/cloudflare/cloudflared) — Cloudflare Tunnel client ☆`12,533`
- [xjasonlyu/tun2socks](https://github.com/xjasonlyu/tun2socks) — TUN to SOCKS proxy ☆`4,774`
- [songgao/water](https://github.com/songgao/water) — A simple TUN/TAP library written in native Go. ☆`2,114`
- [yosebyte/nodepass](https://github.com/yosebyte/nodepass) — Secure TCP/UDP tunneling with TLS ☆`1,913`
## Queues & Pub/Sub

### Brokers

- [nats-io/nats-server](https://github.com/nats-io/nats-server) — High-performance NATS message server ☆`18,901`
- [emitter-io/emitter](https://github.com/emitter-io/emitter) — High-performance pub/sub broker ☆`3,995`
- [mochi-mqtt/server](https://github.com/mochi-mqtt/server) — Embeddable MQTT v5 broker ☆`1,752`
### Clients & Libraries

- [hibiken/asynq](https://github.com/hibiken/asynq) — Simple, reliable, and efficient distributed task queue in Go ☆`12,694`
- [IBM/sarama](https://github.com/IBM/sarama) — Sarama is a Go library for Apache Kafka. ☆`12,365`
- [centrifugal/centrifugo](https://github.com/centrifugal/centrifugo) — Scalable real-time messaging server ☆`9,684`
- [ThreeDotsLabs/watermill](https://github.com/ThreeDotsLabs/watermill) — Building event-driven applications the easy way in Go. ☆`9,378`
- [appleboy/gorush](https://github.com/appleboy/gorush) — A push notification server written in Go (Golang). ☆`8,661`
- [RichardKnop/machinery](https://github.com/RichardKnop/machinery) — Async task queue with message passing ☆`7,923`
- [nats-io/nats.go](https://github.com/nats-io/nats.go) — Golang client for NATS, the cloud native messaging system. ☆`6,333`
- [dunglas/mercure](https://github.com/dunglas/mercure) — Server-Sent Events hub ☆`5,151`
- [confluentinc/confluent-kafka-go](https://github.com/confluentinc/confluent-kafka-go) — Confluent's Apache Kafka Golang client ☆`5,074`
- [olahol/melody](https://github.com/olahol/melody) — Minimalist websocket framework for Go ☆`4,042`
- [sideshow/apns2](https://github.com/sideshow/apns2) — Apple Push Notification Service ☆`3,152`
- [lovoo/goka](https://github.com/lovoo/goka) — Kafka stream processing library ☆`2,495`
- [rabbitmq/amqp091-go](https://github.com/rabbitmq/amqp091-go) — An AMQP 0-9-1 Go client maintained by the RabbitMQ team ☆`1,950`
- [asaskevich/EventBus](https://github.com/asaskevich/EventBus) — [Go] Lightweight eventbus with async compatibility for Go ☆`1,951`
- [containrrr/shoutrrr](https://github.com/containrrr/shoutrrr) — Notification library for gophers and their furry friends. ☆`1,450`
- [pebbe/zmq4](https://github.com/pebbe/zmq4) — A Go interface to ZeroMQ version 4 ☆`1,245`
- [timbray/quamina](https://github.com/timbray/quamina) — Fast pattern-matching library ☆`440`
- [cskr/pubsub](https://github.com/cskr/pubsub) — A simple pubsub package for go. ☆`447`
- [jandelgado/rabtap](https://github.com/jandelgado/rabtap) — RabbitMQ wire tap and swiss army knife ☆`279`
- [mehdihadeli/Go-MediatR](https://github.com/mehdihadeli/Go-MediatR) — Mediator pattern for CQRS ☆`271`
- [goptics/varmq](https://github.com/goptics/varmq) — Zero-dep message queue library ☆`175`
- [hyperonym/ratus](https://github.com/hyperonym/ratus) — RESTful async task queue server ☆`124`
- [robinjoseph08/redisqueue](https://github.com/robinjoseph08/redisqueue) — Redis streams producer and consumer ☆`139`
- [oagudo/outbox](https://github.com/oagudo/outbox) — Transactional outbox pattern ☆`115`
- [furdarius/rabbitroutine](https://github.com/furdarius/rabbitroutine) — RabbitMQ auto-reconnect library ☆`113`
- [dailymotion/oplog](https://github.com/dailymotion/oplog) — A generic oplog/replication system for microservices ☆`110`
- [Protocol-Lattice/GoEventBus](https://github.com/Protocol-Lattice/GoEventBus) — A lock-free, ultra-fast event bus for Go ☆`50`
- [jirenius/go-res](https://github.com/jirenius/go-res) — RES Service protocol library for Go ☆`68`
- [SchwarzIT/hypermatch](https://github.com/SchwarzIT/hypermatch) — High-performance rule matching ☆`33`
## Science

- [gonum/gonum](https://github.com/gonum/gonum) — Numeric libraries for Go ☆`8,276`
- [gonum/plot](https://github.com/gonum/plot) — Plotting and visualization ☆`2,934`
- [paulmach/orb](https://github.com/paulmach/orb) — 2D geometry types and utilities ☆`1,073`
- [bebop/poly](https://github.com/bebop/poly) — Synthetic biology library for Go ☆`719`
- [hmdsefi/gograph](https://github.com/hmdsefi/gograph) — Generic graph algorithms library ☆`102`
- [nikolaydubina/jsonl-graph](https://github.com/nikolaydubina/jsonl-graph) — JSONL Graph Tools ☆`77`
- [claygod/PiHex](https://github.com/claygod/PiHex) — Generate hexadecimal Pi digits ☆`20`
## Scripting

### Embeddable Languages

- [php/frankenphp](https://github.com/php/frankenphp) — The modern PHP app server ☆`10,600`
- [expr-lang/expr](https://github.com/expr-lang/expr) — Expression evaluation for Go ☆`7,568`
- [yuin/gopher-lua](https://github.com/yuin/gopher-lua) — Lua VM and compiler in Go ☆`6,814`
- [dop251/goja](https://github.com/dop251/goja) — ECMAScript engine in pure Go ☆`6,666`
- [d5/tengo](https://github.com/d5/tengo) — Fast script language for Go ☆`3,756`
- [Shopify/go-lua](https://github.com/Shopify/go-lua) — Lua VM in Go ☆`3,390`
- [google/cel-go](https://github.com/google/cel-go) — Common Expression Language for Go ☆`2,809`
- [google/starlark-go](https://github.com/google/starlark-go) — Starlark config language in Go ☆`2,598`
- [metacall/core](https://github.com/metacall/core) — Polyglot programming runtime ☆`1,749`
- [wa-lang/wa](https://github.com/wa-lang/wa) — The Wa Programming Language ☆`1,744`
- [mattn/anko](https://github.com/mattn/anko) — Scriptable interpreter in Go ☆`1,551`
- [PaesslerAG/gval](https://github.com/PaesslerAG/gval) — Expression evaluation in Go ☆`809`
- [ichiban/prolog](https://github.com/ichiban/prolog) — Prolog scripting engine for Go ☆`703`
- [aarzilli/golua](https://github.com/aarzilli/golua) — Lua C API bindings for Go ☆`687`
- [1set/starlet](https://github.com/1set/starlet) — Starlark wrapper with batteries ☆`40`
### Code Generators

- [oapi-codegen/oapi-codegen](https://github.com/oapi-codegen/oapi-codegen) — Generate Go code from OpenAPI 3 specs ☆`7,937`
- [dave/jennifer](https://github.com/dave/jennifer) — Code generator for Go ☆`3,590`
- [hexdigest/gowrap](https://github.com/hexdigest/gowrap) — Generate interface decorators ☆`1,301`
- [awalterschulze/goderive](https://github.com/awalterschulze/goderive) — Generate mundane Go functions ☆`1,267`
- [abice/go-enum](https://github.com/abice/go-enum) — Enum generator for Go ☆`909`
- [jmattheis/goverter](https://github.com/jmattheis/goverter) — Generate type-safe converters ☆`800`
- [rjeczalik/interfaces](https://github.com/rjeczalik/interfaces) — Code generation tools for Go ☆`432`
- [switchupcb/copygen](https://github.com/switchupcb/copygen) — Copy values between types ☆`398`
- [reedom/convergen](https://github.com/reedom/convergen) — Type-to-type copy code generator ☆`48`
## Security

### Certificates

- [go-acme/lego](https://github.com/go-acme/lego) — Let's Encrypt/ACME client and library written in Go ☆`9,117`
- [caddyserver/certmagic](https://github.com/caddyserver/certmagic) — Automatic HTTPS certificate management ☆`5,412`
- [tg123/go-htpasswd](https://github.com/tg123/go-htpasswd) — Apache htpasswd Parser for Go. ☆`46`
- [adrianosela/sslmgr](https://github.com/adrianosela/sslmgr) — SSL certificate abstraction ☆`30`
### Cryptography

- [FiloSottile/age](https://github.com/FiloSottile/age) — Simple encryption tool ☆`20,787`
- [authzed/spicedb](https://github.com/authzed/spicedb) — Zanzibar-inspired permissions DB ☆`6,320`
- [awnumar/memguard](https://github.com/awnumar/memguard) — Software sandbox for storage of sensitive information in memory. ☆`2,697`
- [cossacklabs/themis](https://github.com/cossacklabs/themis) — Cryptographic framework for data protection ☆`1,944`
- [dromara/dongle](https://github.com/dromara/dongle) — A simple, semantic and developer-friendly crypto package for golang ☆`1,095`
- [anatol/booster](https://github.com/anatol/booster) — Fast and secure initramfs generator ☆`611`
- [kevinburke/nacl](https://github.com/kevinburke/nacl) — Pure Go implementation of the NaCL set of API's ☆`551`
- [ssh-vault/ssh-vault](https://github.com/ssh-vault/ssh-vault) — encrypt/decrypt using ssh keys ☆`489`
- [number571/go-peer](https://github.com/number571/go-peer) — Secure decentralized networking ☆`312`
- [lingrino/vaku](https://github.com/lingrino/vaku) — Extended Vault API and CLI ☆`158`
- [anatol/luks.go](https://github.com/anatol/luks.go) — Pure Golang library to manage LUKS partitions ☆`94`
- [zitadel/passwap](https://github.com/zitadel/passwap) — Unified password hashing ☆`72`
- [rsjethani/secret](https://github.com/rsjethani/secret) — Prevent your secrets from leaking into logs, std* etc. ☆`32`
- [andskur/argon2-hashing](https://github.com/andskur/argon2-hashing) — Argon2 password hashing ☆`25`
- [bitfield/qrand](https://github.com/bitfield/qrand) — Quantum randomness source using the ANU hardware QRNG ☆`17`
### WAF & Protection

- [Ullaakut/cameradar](https://github.com/Ullaakut/cameradar) — Cameradar hacks its way into RTSP videosurveillance cameras ☆`4,812`
- [corazawaf/coraza](https://github.com/corazawaf/coraza) — ModSecurity-compatible WAF in Go ☆`3,180`
- [mojocn/base64Captcha](https://github.com/mojocn/base64Captcha) — captcha of base64 image string ☆`2,328`
- [unrolled/secure](https://github.com/unrolled/secure) — HTTP middleware for Go that facilitates some quick security wins. ☆`2,330`
- [mariocandela/beelzebub](https://github.com/mariocandela/beelzebub) — AI-powered honeypot framework ☆`1,797`
- [cossacklabs/acra](https://github.com/cossacklabs/acra) — Database security proxy ☆`1,447`
- [securitybunker/databunker](https://github.com/securitybunker/databunker) — Secure vault for PII/PHI/KYC records ☆`1,374`
- [hillu/go-yara](https://github.com/hillu/go-yara) — Go bindings for YARA ☆`384`
- [teler-sh/teler-waf](https://github.com/teler-sh/teler-waf) — HTTP middleware for WAF ☆`397`
- [steambap/captcha](https://github.com/steambap/captcha) — Easy captcha library ☆`161`
### Zero Trust

- [sigstore/cosign](https://github.com/sigstore/cosign) — Code signing and transparency for containers and binaries ☆`5,539`
- [openziti/ziti](https://github.com/openziti/ziti) — Zero trust networking platform ☆`3,783`
- [spiffe/spire](https://github.com/spiffe/spire) — The SPIFFE Runtime Environment ☆`2,164`
- [philips-labs/spiffe-vault](https://github.com/philips-labs/spiffe-vault) — Integrates Spiffe and Vault to have secretless authentication ☆`97`
## Testing & Quality

### Benchmarks

- [smallnest/go-web-framework-benchmark](https://github.com/smallnest/go-web-framework-benchmark) — Web framework benchmarks ☆`2,137`
- [alecthomas/go_serialization_benchmarks](https://github.com/alecthomas/go_serialization_benchmarks) — Serialization benchmarks for Go ☆`1,620`
- [SimonWaldherr/golang-benchmarks](https://github.com/SimonWaldherr/golang-benchmarks) — Go(lang) benchmarks - (measure the speed of golang) ☆`141`
- [feyeleanor/gospeed](https://github.com/feyeleanor/gospeed) — Go language construct benchmarks ☆`126`
- [nikolaydubina/go-ml-benchmarks](https://github.com/nikolaydubina/go-ml-benchmarks) — Benchmarks of machine learning inference for Go ☆`32`
### Code Analysis

- [golangci/golangci-lint](https://github.com/golangci/golangci-lint) — Fast linters runner for Go ☆`18,234`
- [boyter/scc](https://github.com/boyter/scc) — Fast code counter and stats ☆`7,911`
- [mgechev/revive](https://github.com/mgechev/revive) — Fast, extensible Go linter ☆`5,372`
- [kisielk/errcheck](https://github.com/kisielk/errcheck) — errcheck checks that you checked errors. ☆`2,462`
- [go-critic/go-critic](https://github.com/go-critic/go-critic) — The most opinionated Go source code linter for code audit. ☆`2,027`
- [daveshanley/vacuum](https://github.com/daveshanley/vacuum) — Fast OpenAPI linter ☆`973`
- [presmihaylov/todocheck](https://github.com/presmihaylov/todocheck) — Analyser for TODO comments ☆`436`
- [mdempsky/unconvert](https://github.com/mdempsky/unconvert) — Remove unnecessary type conversions ☆`386`
- [tomarrell/wrapcheck](https://github.com/tomarrell/wrapcheck) — Check errors are wrapped ☆`355`
- [mibk/dupl](https://github.com/mibk/dupl) — Code clone detection tool ☆`360`
- [shurcooL/gostatus](https://github.com/shurcooL/gostatus) — Show status of Go repositories ☆`245`
- [Antonboom/testifylint](https://github.com/Antonboom/testifylint) — Linter for testify usage ☆`162`
- [Crocmagnon/fatcontext](https://github.com/Crocmagnon/fatcontext) — Detect nested contexts in loops ☆`63`
- [antham/ghokin](https://github.com/antham/ghokin) — Parallelized Gherkin formatter ☆`49`
- [asticode/go-astitodo](https://github.com/asticode/go-astitodo) — Parse TODOs in your GO code ☆`66`
- [sashamelentyev/usestdlibvars](https://github.com/sashamelentyev/usestdlibvars) — Linter for stdlib variables usage ☆`46`
- [borovikovd/gomsort](https://github.com/borovikovd/gomsort) — Go msort - linter that sorts methods ☆`26`
### Mock

- [vektra/mockery](https://github.com/vektra/mockery) — Mock code autogenerator for Go ☆`6,927`
- [DATA-DOG/go-sqlmock](https://github.com/DATA-DOG/go-sqlmock) — SQL mock driver for testing ☆`6,503`
- [brianvoe/gofakeit](https://github.com/brianvoe/gofakeit) — Random fake data generator written in go ☆`5,272`
- [uber-go/mock](https://github.com/uber-go/mock) — GoMock is a mocking framework for the Go programming language. ☆`3,218`
- [SpectoLabs/hoverfly](https://github.com/SpectoLabs/hoverfly) — API simulation and virtualization ☆`2,456`
- [matryer/moq](https://github.com/matryer/moq) — Interface mocking via go generate ☆`2,170`
- [jarcoal/httpmock](https://github.com/jarcoal/httpmock) — HTTP mocking for Go ☆`2,076`
- [maxbrunsfeld/counterfeiter](https://github.com/maxbrunsfeld/counterfeiter) — Generate type-safe test doubles ☆`1,110`
- [gojuno/minimock](https://github.com/gojuno/minimock) — Powerful mock generator ☆`743`
- [DATA-DOG/go-txdb](https://github.com/DATA-DOG/go-txdb) — Transaction-isolated SQL driver ☆`739`
- [pashagolub/pgxmock](https://github.com/pashagolub/pgxmock) — pgx mock driver for testing ☆`548`
- [xhd2015/xgo](https://github.com/xhd2015/xgo) — All-in-one Go testing library ☆`428`
- [seborama/govcr](https://github.com/seborama/govcr) — Record and replay HTTP interactions ☆`196`
- [mocktools/go-smtp-mock](https://github.com/mocktools/go-smtp-mock) — SMTP mock server for testing ☆`158`
- [elgohr/go-localstack](https://github.com/elgohr/go-localstack) — Go wrapper for LocalStack ☆`86`
### Performance

- [jaegertracing/jaeger](https://github.com/jaegertracing/jaeger) — Distributed tracing platform ☆`22,306`
- [pixie-io/pixie](https://github.com/pixie-io/pixie) — Kubernetes-native observability ☆`6,304`
- [arl/statsviz](https://github.com/arl/statsviz) — Visualize Go runtime metrics ☆`3,609`
- [nikolaydubina/go-instrument](https://github.com/nikolaydubina/go-instrument) — Add trace spans to Go functions ☆`287`
- [joetifa2003/mm-go](https://github.com/joetifa2003/mm-go) — Manual memory management for Go ☆`191`
### Browser Automation

- [chromedp/chromedp](https://github.com/chromedp/chromedp) — Chrome DevTools Protocol driver ☆`12,613`
- [go-rod/rod](https://github.com/go-rod/rod) — Chrome DevTools driver for scraping ☆`6,526`
- [sensepost/gowitness](https://github.com/sensepost/gowitness) — Web screenshot utility with Chrome ☆`4,105`
- [playwright-community/playwright-go](https://github.com/playwright-community/playwright-go) — Browser automation for Chromium, Firefox, WebKit ☆`3,097`
- [mafredri/cdp](https://github.com/mafredri/cdp) — Chrome DevTools Protocol bindings ☆`773`
### Testing Frameworks

- [stretchr/testify](https://github.com/stretchr/testify) — Assertions and mocks for testing ☆`25,588`
- [keploy/keploy](https://github.com/keploy/keploy) — API testing with auto mocks ☆`14,581`
- [Shopify/toxiproxy](https://github.com/Shopify/toxiproxy) — TCP proxy for chaos testing ☆`11,756`
- [testcontainers/testcontainers-go](https://github.com/testcontainers/testcontainers-go) — Docker containers for integration tests ☆`4,576`
- [google/go-cmp](https://github.com/google/go-cmp) — Package for comparing Go values in tests ☆`4,569`
- [gavv/httpexpect](https://github.com/gavv/httpexpect) — End-to-end HTTP and REST API testing for Go. ☆`2,700`
- [cucumber/godog](https://github.com/cucumber/godog) — Cucumber for golang ☆`2,570`
- [orlangure/gnomock](https://github.com/orlangure/gnomock) — Test with ephemeral Docker containers ☆`1,473`
- [dnaeon/go-vcr](https://github.com/dnaeon/go-vcr) — Record and replay HTTP for tests ☆`1,344`
- [go-testfixtures/testfixtures](https://github.com/go-testfixtures/testfixtures) — Rails-like test fixtures for Go ☆`1,209`
- [fergusstrange/embedded-postgres](https://github.com/fergusstrange/embedded-postgres) — Embedded PostgreSQL for testing ☆`1,098`
- [chapar-rest/chapar](https://github.com/chapar-rest/chapar) — API testing for HTTP and gRPC ☆`677`
- [gotestyourself/gotest.tools](https://github.com/gotestyourself/gotest.tools) — Testing utilities for Go ☆`575`
- [maxatome/go-testdeep](https://github.com/maxatome/go-testdeep) — Flexible deep comparison in tests ☆`456`
- [appleboy/gofight](https://github.com/appleboy/gofight) — Testing API Handler written in Golang. ☆`445`
- [viant/endly](https://github.com/viant/endly) — End to end functional test and automation framework ☆`267`
- [ysmood/got](https://github.com/ysmood/got) — An enjoyable golang test framework. ☆`269`
- [kinbiko/jsonassert](https://github.com/kinbiko/jsonassert) — JSON assertion library for tests ☆`140`
- [adamluzsi/testcase](https://github.com/adamluzsi/testcase) — Opinionated testing framework ☆`127`
- [earthboundkid/be](https://github.com/earthboundkid/be) — The Go test helper for minimalists ☆`125`
- [corbym/gocrest](https://github.com/corbym/gocrest) — GoCrest - Hamcrest-like matchers for Go ☆`106`
- [hedhyw/gherkingen](https://github.com/hedhyw/gherkingen) — Behaviour Driven Development tests generator for Golang ☆`92`
- [madflojo/testcerts](https://github.com/madflojo/testcerts) — Generate test certificates on the fly ☆`84`
- [viant/dsunit](https://github.com/viant/dsunit) — Datastore Testibility ☆`45`
- [go-restit/restit](https://github.com/go-restit/restit) — A Go library help testing your RESTful API application ☆`55`
- [rekby/fixenv](https://github.com/rekby/fixenv) — Pytest-inspired fixture caching for Go tests ☆`33`
- [abecodes/dft](https://github.com/abecodes/dft) — Docker wrapper for testing ☆`19`
### Testing Utilities

- [dvyukov/go-fuzz](https://github.com/dvyukov/go-fuzz) — Randomized testing for Go ☆`4,842`
- [pingcap/failpoint](https://github.com/pingcap/failpoint) — Failpoint implementation for Go ☆`872`
### Validation

- [go-playground/validator](https://github.com/go-playground/validator) — Struct and field validation for Go ☆`19,533`
- [gookit/validate](https://github.com/gookit/validate) — Struct and data validation ☆`1,124`
- [Oudwins/zog](https://github.com/Oudwins/zog) — Zod-inspired schema validation ☆`1,089`
- [twharmon/govalid](https://github.com/twharmon/govalid) — Struct validation using tags ☆`111`
- [faceair/jio](https://github.com/faceair/jio) — JSON schema validator like Joi ☆`124`
- [osamingo/checkdigit](https://github.com/osamingo/checkdigit) — Check digit algorithms ☆`114`
- [marrow16/valix](https://github.com/marrow16/valix) — Request validation package ☆`31`
- [tiendc/go-validator](https://github.com/tiendc/go-validator) — Intuitive validation library ☆`32`
## Text & NLP

### Formatters

- [dustin/go-humanize](https://github.com/dustin/go-humanize) — Human-friendly unit formatting ☆`4,760`
- [neilotoole/sq](https://github.com/neilotoole/sq) — SQL data wrangler ☆`2,409`
- [bojanz/address](https://github.com/bojanz/address) — Address handling for Go ☆`81`
- [ianlopshire/go-fixedwidth](https://github.com/ianlopshire/go-fixedwidth) — Fixed-width data encoding ☆`87`
### Markup Languages

- [BurntSushi/toml](https://github.com/BurntSushi/toml) — TOML parser with reflection ☆`4,872`
- [yuin/goldmark](https://github.com/yuin/goldmark) — Markdown parser for Go ☆`4,489`
- [JohannesKaufmann/html-to-markdown](https://github.com/JohannesKaufmann/html-to-markdown) — Convert HTML to Markdown ☆`3,303`
- [pelletier/go-toml](https://github.com/pelletier/go-toml) — TOML library for Go ☆`1,894`
- [antchfx/htmlquery](https://github.com/antchfx/htmlquery) — XPath for HTML queries ☆`776`
- [clbanning/mxj](https://github.com/clbanning/mxj) — XML to/from map conversion ☆`632`
- [mmalcek/bafi](https://github.com/mmalcek/bafi) — Universal format converter ☆`110`
- [drewstinnett/gout](https://github.com/drewstinnett/gout) — Output Go objects in YAML, JSON ☆`18`
### Miscellaneous

- [microcosm-cc/bluemonday](https://github.com/microcosm-cc/bluemonday) — Fast HTML sanitizer for Go ☆`3,591`
- [pemistahl/lingua-go](https://github.com/pemistahl/lingua-go) — Natural language detection ☆`1,308`
- [gosimple/slug](https://github.com/gosimple/slug) — URL-friendly slugify ☆`1,305`
- [arunsupe/semantic-grep](https://github.com/arunsupe/semantic-grep) — Grep for similar words ☆`1,197`
- [mattn/go-runewidth](https://github.com/mattn/go-runewidth) — Rune width for terminals ☆`672`
- [hedhyw/rex](https://github.com/hedhyw/rex) — Flexible regex constructor ☆`210`
- [IGLOU-EU/go-wildcard](https://github.com/IGLOU-EU/go-wildcard) — Fast wildcard matching ☆`99`
- [JoshuaDoes/gofuckyourself](https://github.com/JoshuaDoes/gofuckyourself) — Swear filter for Go ☆`68`
- [alexsergivan/transliterator](https://github.com/alexsergivan/transliterator) — Text transliterator ☆`46`
- [Dynom/TySug](https://github.com/Dynom/TySug) — Typo suggestions with keyboard layout ☆`19`
### Morphological Analyzers

- [nlpodyssey/spago](https://github.com/nlpodyssey/spago) — ML and NLP library for Go ☆`1,839`
- [ikawaha/kagome](https://github.com/ikawaha/kagome) — Japanese morphological analyzer ☆`929`
- [afjoseph/RAKE.Go](https://github.com/afjoseph/RAKE.Go) — Rapid Keyword Extraction in Go ☆`122`
- [jonreiter/govader](https://github.com/jonreiter/govader) — VADER sentiment analysis ☆`52`
### Parsers/Encoders/Decoders

- [mvdan/sh](https://github.com/mvdan/sh) — Shell parser and formatter ☆`8,366`
- [mmcdole/gofeed](https://github.com/mmcdole/gofeed) — Parse RSS, Atom, JSON feeds ☆`2,792`
- [google/go-querystring](https://github.com/google/go-querystring) — Encode structs to URL query strings ☆`2,124`
- [olebedev/when](https://github.com/olebedev/when) — Natural language date parser ☆`1,453`
- [adrianmo/go-nmea](https://github.com/adrianmo/go-nmea) — NMEA sentence parser ☆`255`
- [yassinebenaid/godump](https://github.com/yassinebenaid/godump) — Dump any Go variable ☆`222`
- [editorconfig/editorconfig-core-go](https://github.com/editorconfig/editorconfig-core-go) — EditorConfig core in Go ☆`150`
- [bzick/tokenizer](https://github.com/bzick/tokenizer) — Tokenizer/lexer for Go ☆`138`
- [emersion/go-vcard](https://github.com/emersion/go-vcard) — vCard parser and formatter ☆`123`
- [polera/gonameparts](https://github.com/polera/gonameparts) — Takes a full name and splits it into individual name parts ☆`43`
### Scrapers

- [gocolly/colly](https://github.com/gocolly/colly) — Web scraping framework for Go ☆`24,974`
- [PuerkitoBio/goquery](https://github.com/PuerkitoBio/goquery) — jQuery-like HTML manipulation ☆`14,860`
- [mvdan/xurls](https://github.com/mvdan/xurls) — Extract URLs from text ☆`1,239`
- [s0rg/crawley](https://github.com/s0rg/crawley) — The unix-way web crawler ☆`321`
- [zoomio/tagify](https://github.com/zoomio/tagify) — Extract tags from HTML/Markdown/text ☆`39`
### Text Analysis

- [blevesearch/bleve](https://github.com/blevesearch/bleve) — Text/numeric/geo/vector indexing library ☆`10,867`
- [derekparker/trie](https://github.com/derekparker/trie) — Trie for extremely fast prefix search ☆`787`
- [agnivade/levenshtein](https://github.com/agnivade/levenshtein) — Go implementation to calculate Levenshtein Distance. ☆`443`
- [plar/go-adaptive-radix-tree](https://github.com/plar/go-adaptive-radix-tree) — Adaptive Radix Trees implemented in Go ☆`410`
- [viant/ptrie](https://github.com/viant/ptrie) — A prefix tree implementation in go ☆`44`
### Tokenizers

- [go-ego/gse](https://github.com/go-ego/gse) — Multilingual text segmentation ☆`2,766`
- [pebbe/textcat](https://github.com/pebbe/textcat) — N-gram text categorization ☆`73`
### Translation

- [nicksnyder/go-i18n](https://github.com/nicksnyder/go-i18n) — Translate Go programs ☆`3,432`
- [leonelquinteros/gotext](https://github.com/leonelquinteros/gotext) — GNU gettext for Go ☆`487`
- [vorlif/spreak](https://github.com/vorlif/spreak) — Gettext-based translation library ☆`90`
- [invopop/ctxi18n](https://github.com/invopop/ctxi18n) — Context-based i18n for Go ☆`89`
- [mehanizm/iuliia-go](https://github.com/mehanizm/iuliia-go) — Cyrillic to Latin transliteration ☆`55`
- [youthlin/t](https://github.com/youthlin/t) — Translation util using gettext ☆`20`
## Third-party APIs

### Cloud Provider APIs

- [googleapis/google-cloud-go](https://github.com/googleapis/google-cloud-go) — Google Cloud Client Libraries for Go. ☆`4,389`
- [googleapis/google-api-go-client](https://github.com/googleapis/google-api-go-client) — Auto-generated Google APIs for Go. ☆`4,368`
- [aws/aws-sdk-go-v2](https://github.com/aws/aws-sdk-go-v2) — AWS SDK for the Go programming language. ☆`3,408`
- [minio/minio-go](https://github.com/minio/minio-go) — High-performance object storage ☆`2,882`
- [rhnvrm/simples3](https://github.com/rhnvrm/simples3) — Simple AWS S3 library using REST ☆`184`
- [chainifynet/aws-encryption-sdk-go](https://github.com/chainifynet/aws-encryption-sdk-go) — AWS Encryption SDK for Go ☆`22`
- [circa10a/go-aws-news](https://github.com/circa10a/go-aws-news) — Go app + library to fetch what's new from AWS ☆`17`
### Other APIs

- [codingsince1985/geo-golang](https://github.com/codingsince1985/geo-golang) — Go library to access geocoding and reverse geocoding APIs ☆`540`
- [onrik/ethrpc](https://github.com/onrik/ethrpc) — Golang client for ethereum json rpc api ☆`277`
- [cyruzin/golang-tmdb](https://github.com/cyruzin/golang-tmdb) — Wrapper for TMDb API ☆`152`
- [gregdel/pushover](https://github.com/gregdel/pushover) — Go wrapper for the Pushover API ☆`154`
- [mvrilo/go-redoc](https://github.com/mvrilo/go-redoc) — Embedded OpenAPI documentation ☆`94`
- [rapito/go-spotify](https://github.com/rapito/go-spotify) — Go library for the Spotify Web API ☆`50`
- [rinchsan/device-check-go](https://github.com/rinchsan/device-check-go) — iOS DeviceCheck SDK for Go ☆`25`
- [zc2638/swag](https://github.com/zc2638/swag) — Generate Swagger from code ☆`50`
- [sostronk/go-steam](https://github.com/sostronk/go-steam) — Go library for querying Source servers ☆`33`
- [Icelain/jokeapi](https://github.com/Icelain/jokeapi) — Official golang wrapper for Sv443's jokeapi. ☆`27`
- [staskobzar/goami2](https://github.com/staskobzar/goami2) — Simple Asterisk Manager Interface (AMI) library fo golang ☆`21`
### Productivity APIs

- [mk-5/fjira](https://github.com/mk-5/fjira) — The golang fuzzy-find cli jira interface ☆`250`
- [adlio/trello](https://github.com/adlio/trello) — Trello API wrapper for Go ☆`227`
- [ctreminiom/go-atlassian](https://github.com/ctreminiom/go-atlassian) — Atlassian Cloud API client ☆`190`
- [koltyakov/gosip](https://github.com/koltyakov/gosip) — SharePoint SDK for Go ☆`166`
- [FreeLeh/GoFreeDB](https://github.com/FreeLeh/GoFreeDB) — Database on top of Google Sheets ☆`90`
- [mehanizm/airtable](https://github.com/mehanizm/airtable) — Simple golang airtable API wrapper ☆`82`
- [k-capehart/go-salesforce](https://github.com/k-capehart/go-salesforce) — Salesforce REST API client ☆`54`
## Utilities

### Build & Release

- [goreleaser/goreleaser](https://github.com/goreleaser/goreleaser) — Release engineering simplified ☆`15,431`
- [create-go-app/cli](https://github.com/create-go-app/cli) — Create production-ready Go projects ☆`2,735`
- [miniscruff/changie](https://github.com/miniscruff/changie) — Automated changelog tool ☆`847`
- [jaschaephraim/lrserver](https://github.com/jaschaephraim/lrserver) — LiveReload server for Go [golang] ☆`129`
- [karl-cardenas-coding/go-lambda-cleanup](https://github.com/karl-cardenas-coding/go-lambda-cleanup) — Remove old AWS Lambda versions ☆`96`
### CLI Tools

- [junegunn/fzf](https://github.com/junegunn/fzf) — Command-line fuzzy finder ☆`76,508`
- [wagoodman/dive](https://github.com/wagoodman/dive) — Explore Docker image layers ☆`53,046`
- [xo/usql](https://github.com/xo/usql) — Universal SQL CLI ☆`9,732`
- [minio/mc](https://github.com/minio/mc) — Unix utilities for object stores ☆`3,320`
- [joshmedeski/sesh](https://github.com/joshmedeski/sesh) — Terminal session manager ☆`1,538`
- [itchyny/bed](https://github.com/itchyny/bed) — Binary editor in Go ☆`1,344`
- [owenthereal/upterm](https://github.com/owenthereal/upterm) — Instant terminal sharing ☆`1,080`
- [Unrud/remote-touchpad](https://github.com/Unrud/remote-touchpad) — Control mouse/keyboard remotely ☆`639`
- [alajmo/mani](https://github.com/alajmo/mani) — CLI for managing repositories ☆`639`
- [chenquan/diskusage](https://github.com/chenquan/diskusage) — Fast disk usage analyzer ☆`297`
- [reugn/wifiqr](https://github.com/reugn/wifiqr) — Generate Wi-Fi QR codes ☆`279`
- [hedhyw/json-log-viewer](https://github.com/hedhyw/json-log-viewer) — Interactive JSON log viewer ☆`199`
- [knbr13/gitcs](https://github.com/knbr13/gitcs) — Git contributions graph generator ☆`128`
- [antham/yogo](https://github.com/antham/yogo) — Check yopmail from CLI ☆`46`
### Data Conversion

- [samber/lo](https://github.com/samber/lo) — Lodash-style utilities for Go ☆`20,821`
- [duke-git/lancet](https://github.com/duke-git/lancet) — Comprehensive util library ☆`5,244`
- [darccio/mergo](https://github.com/darccio/mergo) — Merge Go structs and maps ☆`3,078`
- [goforj/godump](https://github.com/goforj/godump) — Pretty-printer for Go structs ☆`1,546`
- [gookit/filter](https://github.com/gookit/filter) — Data filtering and conversion ☆`150`
- [tiendc/gofn](https://github.com/tiendc/gofn) — High-performance generic functions ☆`52`
- [xorcare/pointer](https://github.com/xorcare/pointer) — Create optional field pointers ☆`48`
- [shockerli/cvt](https://github.com/shockerli/cvt) — Safe type conversion ☆`53`
### Database Extensions

- [jmoiron/sqlx](https://github.com/jmoiron/sqlx) — Extensions for database/sql ☆`17,443`
- [georgysavva/scany](https://github.com/georgysavva/scany) — Scan database rows to structs ☆`1,490`
- [blockloop/scan](https://github.com/blockloop/scan) — Scan SQL rows to structs ☆`607`
- [wroge/scan](https://github.com/wroge/scan) — Generic SQL row scanner ☆`68`
### Date and Time

- [dromara/carbon](https://github.com/dromara/carbon) — Developer-friendly time package ☆`5,195`
- [yaa110/go-persian-calendar](https://github.com/yaa110/go-persian-calendar) — Persian calendar for Go ☆`237`
- [bykof/gostradamus](https://github.com/bykof/gostradamus) — Better DateTimes for Go ☆`210`
- [nathan-osman/go-sunrise](https://github.com/nathan-osman/go-sunrise) — Calculate sunrise and sunset times ☆`172`
- [relvacode/iso8601](https://github.com/relvacode/iso8601) — Fast ISO8601 date parser ☆`157`
- [rickb777/date](https://github.com/rickb777/date) — Date handling package ☆`140`
### Dependency Injection

- [uber-go/fx](https://github.com/uber-go/fx) — DI-based application framework ☆`7,184`
- [uber-go/dig](https://github.com/uber-go/dig) — Reflection-based DI toolkit ☆`4,414`
- [goioc/di](https://github.com/goioc/di) — Simple DI for Go ☆`375`
- [go-kod/kod](https://github.com/go-kod/kod) — DI with aspect-oriented support ☆`196`
- [i-love-flamingo/dingo](https://github.com/i-love-flamingo/dingo) — DI framework for Go ☆`186`
- [junioryono/godi](https://github.com/junioryono/godi) — DI with service lifetimes ☆`65`
- [NVIDIA/gontainer](https://github.com/NVIDIA/gontainer) — Simple DI container ☆`62`
- [matzefriedrich/parsley](https://github.com/matzefriedrich/parsley) — Reflection-based DI package ☆`30`
- [muir/nject](https://github.com/muir/nject) — Type-safe DI for Go ☆`30`
- [logrange/linker](https://github.com/logrange/linker) — DI and IoC package ☆`35`
- [firasdarwish/ore](https://github.com/firasdarwish/ore) — Advanced DI solution ☆`24`
- [componego/componego](https://github.com/componego/componego) — Component-oriented framework ☆`28`
- [gontainer/gontainer](https://github.com/gontainer/gontainer) — YAML-based DI container ☆`16`
### Error Handling

- [hashicorp/go-multierror](https://github.com/hashicorp/go-multierror) — Represent multiple errors as one ☆`2,536`
- [cockroachdb/errors](https://github.com/cockroachdb/errors) — Error library with portability ☆`2,334`
- [rotisserie/eris](https://github.com/rotisserie/eris) — Errors with readable stack traces ☆`1,749`
- [joomcode/errorx](https://github.com/joomcode/errorx) — Comprehensive error handling ☆`1,268`
- [ztrue/tracerr](https://github.com/ztrue/tracerr) — Errors with stack trace ☆`1,102`
- [samber/oops](https://github.com/samber/oops) — Structured error handling ☆`836`
- [Southclaws/fault](https://github.com/Southclaws/fault) — Composable error wrapping ☆`302`
### File Handling

- [schollz/croc](https://github.com/schollz/croc) — Easily and securely send things from one computer to another ☆`33,675`
- [qax-os/excelize](https://github.com/qax-os/excelize) — Excel XLSX library for Go ☆`20,146`
- [pdfcpu/pdfcpu](https://github.com/pdfcpu/pdfcpu) — PDF processor in Go ☆`8,339`
- [spf13/afero](https://github.com/spf13/afero) — Filesystem abstraction for Go ☆`6,509`
- [dundee/gdu](https://github.com/dundee/gdu) — Fast disk usage analyzer ☆`5,185`
- [unidoc/unioffice](https://github.com/unidoc/unioffice) — Office document library ☆`4,763`
- [root-gg/plik](https://github.com/root-gg/plik) — Temporary file upload system ☆`1,682`
- [SpatiumPortae/portal](https://github.com/SpatiumPortae/portal) — Command-line file transfer utility ☆`1,717`
- [SebastiaanKlippert/go-wkhtmltopdf](https://github.com/SebastiaanKlippert/go-wkhtmltopdf) — HTML to PDF wrapper ☆`1,172`
- [otiai10/copy](https://github.com/otiai10/copy) — Copy directories recursively ☆`768`
- [ulikunitz/xz](https://github.com/ulikunitz/xz) — Pure golang package for reading and writing xz-compressed files ☆`545`
- [no-src/gofs](https://github.com/no-src/gofs) — Cross-platform file sync ☆`523`
- [viant/afs](https://github.com/viant/afs) — Abstract file storage ☆`370`
- [mholt/archives](https://github.com/mholt/archives) — Create and extract archives ☆`359`
- [C2FO/vfs](https://github.com/C2FO/vfs) — Virtual file system for Go ☆`356`
- [gen2brain/go-unarr](https://github.com/gen2brain/go-unarr) — Decompression library bindings ☆`300`
- [barasher/go-exiftool](https://github.com/barasher/go-exiftool) — Exiftool wrapper for metadata ☆`290`
- [kdomanski/iso9660](https://github.com/kdomanski/iso9660) — ISO9660 image library ☆`281`
- [gomutex/godocx](https://github.com/gomutex/godocx) — Go library for reading and writing Microsoft Docx ☆`234`
- [charlievieth/fastwalk](https://github.com/charlievieth/fastwalk) — Fast directory traversal ☆`113`
- [artonge/go-csv-tag](https://github.com/artonge/go-csv-tag) — CSV reading with tags ☆`128`
- [parsyl/parquet](https://github.com/parsyl/parquet) — Parquet file library ☆`127`
- [adelowo/gulter](https://github.com/adelowo/gulter) — Multipart form handling ☆`67`
- [go-the-way/exl](https://github.com/go-the-way/exl) — Excel binding to struct written in Go.(Only supports Go1.18+) ☆`32`
### Forms

- [justinas/nosurf](https://github.com/justinas/nosurf) — CSRF protection middleware ☆`1,716`
- [gorilla/csrf](https://github.com/gorilla/csrf) — CSRF prevention middleware ☆`1,169`
- [go-playground/form](https://github.com/go-playground/form) — URL values to structs ☆`896`
- [ggicci/httpin](https://github.com/ggicci/httpin) — HTTP request to struct binding ☆`381`
- [sonh/qs](https://github.com/sonh/qs) — Encode structs to query params ☆`79`
- [cinar/checker](https://github.com/cinar/checker) — Input validation with struct tags ☆`47`
### Functional

- [samber/mo](https://github.com/samber/mo) — Monads and FP for Go ☆`3,263`
- [BooleanCat/go-functional](https://github.com/BooleanCat/go-functional) — Iterator library for Go ☆`524`
- [seborama/fuego](https://github.com/seborama/fuego) — Functional programming in Go ☆`146`
- [rjNemo/underscore](https://github.com/rjNemo/underscore) — Functional helpers for Go ☆`118`
### General

- [wabarc/wayback](https://github.com/wabarc/wayback) — Web archiving tool with IM interface ☆`2,118`
- [gabriel-vasile/mimetype](https://github.com/gabriel-vasile/mimetype) — MIME type detection by magic numbers ☆`1,921`
- [qmuntal/stateless](https://github.com/qmuntal/stateless) — Go library for creating finite state machines ☆`1,151`
- [jonboulle/clockwork](https://github.com/jonboulle/clockwork) — a fake clock for golang ☆`722`
- [Boeing/config-file-validator](https://github.com/Boeing/config-file-validator) — Cross Platform tool to validate configuration files ☆`486`
- [ungerik/go-dry](https://github.com/ungerik/go-dry) — DRY (don't repeat yourself) package for Go ☆`488`
- [biter777/countries](https://github.com/biter777/countries) — ISO country codes library ☆`496`
- [subosito/gotenv](https://github.com/subosito/gotenv) — Load environment variables from `.env` or `io.Reader` in Go. ☆`306`
- [ikeikeikeike/go-sitemap-generator](https://github.com/ikeikeikeike/go-sitemap-generator) — Generate XML sitemaps ☆`228`
- [viant/toolbox](https://github.com/viant/toolbox) — Toolbox - go utility library ☆`227`
- [maja42/goval](https://github.com/maja42/goval) — Expression evaluation in golang ☆`173`
- [commander-cli/cmd](https://github.com/commander-cli/cmd) — A simple package to execute shell commands on linux, windows and osx ☆`160`
- [jfcg/sorty](https://github.com/jfcg/sorty) — Fast Concurrent / Parallel Sorting in Go ☆`143`
- [tiendc/go-deepcopy](https://github.com/tiendc/go-deepcopy) — Fast deep-copy library for Go ☆`122`
- [syntaqx/cookie](https://github.com/syntaqx/cookie) — Cookies, but with structs, for happiness. ☆`112`
- [pioz/countries](https://github.com/pioz/countries) — All you need when you are working with countries in Go. ☆`93`
- [arthurkushman/pgo](https://github.com/arthurkushman/pgo) — Go library for PHP community with convenient functions ☆`88`
- [wzshiming/gotype](https://github.com/wzshiming/gotype) — Golang source code parsing, usage like reflect package ☆`64`
- [rkoesters/xdg](https://github.com/rkoesters/xdg) — FreeDesktop.org (xdg) Specs implemented in Go ☆`48`
- [icza/backscanner](https://github.com/icza/backscanner) — Scan file lines backward ☆`69`
- [ik5/gostrutils](https://github.com/ik5/gostrutils) — Collections of string utils I have created over the years ☆`48`
- [kazhuravlev/just](https://github.com/kazhuravlev/just) — Collection of useful functions. Complete simple tasks faster! ☆`37`
- [osamingo/gosh](https://github.com/osamingo/gosh) — Provide Go Statistics Handler, Struct, Measure Method ☆`35`
- [floatdrop/debounce](https://github.com/floatdrop/debounce) — A zero-allocation debouncer ☆`34`
- [lrita/numa](https://github.com/lrita/numa) — NUMA utility library for Go ☆`37`
- [skovtunenko/graterm](https://github.com/skovtunenko/graterm) — Graceful termination primitives ☆`30`
- [mikekonan/go-types](https://github.com/mikekonan/go-types) — OpenAPI3 types for Go ☆`22`
- [nikolaydubina/watchhttp](https://github.com/nikolaydubina/watchhttp) — Expose command output via HTTP ☆`34`
### Logging

- [sirupsen/logrus](https://github.com/sirupsen/logrus) — Structured, pluggable logging for Go. ☆`25,643`
- [uber-go/zap](https://github.com/uber-go/zap) — Fast structured logging ☆`24,092`
- [rs/zerolog](https://github.com/rs/zerolog) — Zero allocation JSON logger ☆`12,094`
- [davecgh/go-spew](https://github.com/davecgh/go-spew) — Deep pretty printer for debugging ☆`6,363`
- [golang/glog](https://github.com/golang/glog) — Leveled execution logs ☆`3,619`
- [k0kubun/pp](https://github.com/k0kubun/pp) — Colored pretty printer for Go ☆`2,021`
- [lmittmann/tint](https://github.com/lmittmann/tint) — Colorized slog handler ☆`1,194`
- [getsentry/sentry-go](https://github.com/getsentry/sentry-go) — Official Sentry SDK for Go ☆`1,029`
- [Lifailon/lazyjournal](https://github.com/Lifailon/lazyjournal) — TUI for journald, Docker, K8s logs ☆`1,045`
- [phuslu/log](https://github.com/phuslu/log) — Fastest structured logging ☆`826`
- [samber/slog-multi](https://github.com/samber/slog-multi) — Workflow design for slog handlers ☆`592`
- [gookit/slog](https://github.com/gookit/slog) — Configurable logging library ☆`525`
- [henvic/httpretty](https://github.com/henvic/httpretty) — Pretty-print HTTP requests ☆`413`
- [simukti/sqldb-logger](https://github.com/simukti/sqldb-logger) — SQL database logger ☆`383`
- [hashicorp/logutils](https://github.com/hashicorp/logutils) — Logging utilities for Go ☆`371`
- [samber/slog-formatter](https://github.com/samber/slog-formatter) — Slog attribute formatting ☆`206`
- [rs/xlog](https://github.com/rs/xlog) — Context-aware HTTP logger ☆`140`
- [DeRuina/timberjack](https://github.com/DeRuina/timberjack) — Log rolling library ☆`109`
- [yuseferi/zax](https://github.com/yuseferi/zax) — Zap logger with context ☆`32`
- [clok/kemba](https://github.com/clok/kemba) — Tiny debug logging tool ☆`17`
### Networking Utils

- [cristianoliveira/ergo](https://github.com/cristianoliveira/ergo) — Manage apps on different ports ☆`644`
- [htcat/htcat](https://github.com/htcat/htcat) — Parallel HTTP download ☆`557`
- [ferama/rospo](https://github.com/ferama/rospo) — Persistent SSH tunnels ☆`350`
### Project Layout

- [golang-standards/project-layout](https://github.com/golang-standards/project-layout) — Standard Go project layout ☆`54,895`
- [Melkeydev/go-blueprint](https://github.com/Melkeydev/go-blueprint) — Spin up Go projects with popular frameworks ☆`8,538`
- [ardanlabs/service](https://github.com/ardanlabs/service) — K8s service starter kit ☆`3,924`
- [Shpota/goxygen](https://github.com/Shpota/goxygen) — Generate full-stack web projects ☆`3,605`
- [mikestefanello/pagoda](https://github.com/mikestefanello/pagoda) — Full-stack web development starter kit ☆`2,886`
- [go-nunu/nunu](https://github.com/go-nunu/nunu) — CLI for building Go apps ☆`2,524`
- [sagikazarmark/modern-go-application](https://github.com/sagikazarmark/modern-go-application) — Modern Go app example ☆`1,939`
- [naughtygopher/goapp](https://github.com/naughtygopher/goapp) — Opinionated web app structure ☆`1,041`
- [lacion/cookiecutter-golang](https://github.com/lacion/cookiecutter-golang) — Go project template ☆`733`
- [allaboutapps/go-starter](https://github.com/allaboutapps/go-starter) — Production-ready RESTful API template ☆`587`
- [golang-templates/seed](https://github.com/golang-templates/seed) — Go app GitHub template ☆`551`
- [raeperd/kickstart.go](https://github.com/raeperd/kickstart.go) — Minimal HTTP server template ☆`101`
- [wangyoucao577/go-project-layout](https://github.com/wangyoucao577/go-project-layout) — Go project structure guide ☆`26`
### Resilience & Retry

- [avast/retry-go](https://github.com/avast/retry-go) — Simple retry mechanism ☆`2,865`
- [eapache/go-resiliency](https://github.com/eapache/go-resiliency) — Resiliency patterns for golang ☆`2,339`
- [failsafe-go/failsafe-go](https://github.com/failsafe-go/failsafe-go) — Fault tolerance patterns ☆`2,046`
- [rubyist/circuitbreaker](https://github.com/rubyist/circuitbreaker) — Circuit breakers in Go ☆`1,164`
- [cep21/circuit](https://github.com/cep21/circuit) — Hystrix-like circuit breaker ☆`794`
- [mennanov/limiters](https://github.com/mennanov/limiters) — Distributed rate limiters ☆`610`
- [kamilsk/retry](https://github.com/kamilsk/retry) — Advanced retry mechanism ☆`346`
- [webriots/rate](https://github.com/webriots/rate) — High-performance rate limiter ☆`163`
- [reugn/equalizer](https://github.com/reugn/equalizer) — Performant rate limiters ☆`91`
### Strings

- [huandu/xstrings](https://github.com/huandu/xstrings) — String functions from other langs ☆`1,416`
- [abhimanyu003/sttr](https://github.com/abhimanyu003/sttr) — CLI string operations ☆`1,257`
- [gobeam/stringy](https://github.com/gobeam/stringy) — String case conversions ☆`251`
- [ozgio/strutil](https://github.com/ozgio/strutil) — String utilities for Go ☆`207`
### System & Process

- [cilium/ebpf](https://github.com/cilium/ebpf) — eBPF library for Go ☆`7,425`
- [maruel/panicparse](https://github.com/maruel/panicparse) — Crash your app in style ☆`3,715`
- [immortal/immortal](https://github.com/immortal/immortal) — Cross-platform supervisor ☆`830`
- [derekparker/delve](https://github.com/derekparker/delve) — Delve is a debugger for the Go programming language. ☆`663`
- [gotranspile/cxgo](https://github.com/gotranspile/cxgo) — Transpile C to Go ☆`382`
### UUID

- [google/uuid](https://github.com/google/uuid) — UUID generation and parsing ☆`5,942`
- [oklog/ulid](https://github.com/oklog/ulid) — ULID implementation ☆`4,956`
- [gofrs/uuid](https://github.com/gofrs/uuid) — UUID library for Go ☆`1,753`
- [edwingeng/wuid](https://github.com/edwingeng/wuid) — An extremely fast globally unique number generator. ☆`545`
- [osamingo/indigo](https://github.com/osamingo/indigo) — Sonyflake-based ID generator ☆`112`
- [sdrapkin/guid](https://github.com/sdrapkin/guid) — Fast cryptographically safe Guid generator for Go ☆`73`
- [twharmon/gouid](https://github.com/twharmon/gouid) — Fast, dependable universally unique ids ☆`26`
## Version Control & Packages

### Git APIs

- [google/go-github](https://github.com/google/go-github) — Go library for accessing the GitHub v3 API ☆`11,061`
- [shurcooL/githubv4](https://github.com/shurcooL/githubv4) — GitHub GraphQL API v4 client ☆`1,178`
- [go-playground/webhooks](https://github.com/go-playground/webhooks) — Webhook receiver for GitHub, Bitbucket, GitLab, Gogs ☆`1,020`
- [andygrunwald/go-trending](https://github.com/andygrunwald/go-trending) — Access GitHub trending repositories ☆`146`
- [andygrunwald/go-gerrit](https://github.com/andygrunwald/go-gerrit) — Go client/library for Gerrit Code Review ☆`102`
### Package Management

- [anchore/syft](https://github.com/anchore/syft) — SBOM generator for containers ☆`8,175`
- [nao1215/gup](https://github.com/nao1215/gup) — gup - Update binaries installed by "go install" with goroutines. ☆`519`
- [marwanhawari/stew](https://github.com/marwanhawari/stew) — An independent package manager for compiled binaries. ☆`314`
- [chaindead/modup](https://github.com/chaindead/modup) — TUI for Go dependency updates ☆`61`
### Version Control

- [go-git/go-git](https://github.com/go-git/go-git) — Pure Go Git implementation ☆`7,105`
- [antham/chyle](https://github.com/antham/chyle) — Changelog generator from Git ☆`159`
- [gabyx/Githooks](https://github.com/gabyx/Githooks) — Per-repo shared Git hooks ☆`115`
- [antham/gommit](https://github.com/antham/gommit) — Enforce git message commit consistency ☆`115`
- [jfrog/froggit-go](https://github.com/jfrog/froggit-go) — Universal VCS client library ☆`49`
- [kazhuravlev/git-tools](https://github.com/kazhuravlev/git-tools) — Useful set of tools which helps to manage git tags ☆`33`
## Web Development

### Microservices

- [zeromicro/go-zero](https://github.com/zeromicro/go-zero) — Microservices framework with CLI tools ☆`32,393`
- [go-kit/kit](https://github.com/go-kit/kit) — A standard library for microservices. ☆`27,576`
- [go-kratos/kratos](https://github.com/go-kratos/kratos) — Your ultimate Go microservices framework for the cloud-native era. ☆`25,289`
- [micro/go-micro](https://github.com/micro/go-micro) — A Go microservices framework ☆`22,657`
- [smallnest/rpcx](https://github.com/smallnest/rpcx) — Feature-rich RPC framework ☆`8,271`
- [cloudwego/kitex](https://github.com/cloudwego/kitex) — High-performance Go RPC framework ☆`7,800`
- [go-dev-frame/sponge](https://github.com/go-dev-frame/sponge) — Code generation framework for Go ☆`2,745`
- [go-eagle/eagle](https://github.com/go-eagle/eagle) — A Go framework for the API or Microservice ☆`2,412`
- [unionj-cloud/go-doudou](https://github.com/unionj-cloud/go-doudou) — OpenAPI 3 and gRPC microservices framework ☆`1,208`
- [trpc-group/trpc-go](https://github.com/trpc-group/trpc-go) — A pluggable, high-performance RPC framework written in golang ☆`1,092`
- [gmsec/micro](https://github.com/gmsec/micro) — A Go distributed systems development framework ☆`25`
### Middlewares

- [urfave/negroni](https://github.com/urfave/negroni) — Idiomatic HTTP Middleware for Golang ☆`7,541`
- [tdewolff/minify](https://github.com/tdewolff/minify) — Go minifiers for web formats ☆`4,036`
- [justinas/alice](https://github.com/justinas/alice) — Painless middleware chaining for Go ☆`3,344`
- [rs/cors](https://github.com/rs/cors) — Go net/http configurable handler to handle CORS requests ☆`2,846`
- [didip/tollbooth](https://github.com/didip/tollbooth) — Simple middleware to rate-limit HTTP requests. ☆`2,848`
- [unrolled/render](https://github.com/unrolled/render) — Render JSON, XML, HTML, binary ☆`1,989`
- [lingrino/go-fault](https://github.com/lingrino/go-fault) — go fault injection library ☆`511`
- [jub0bs/cors](https://github.com/jub0bs/cors) — perhaps the best CORS middleware library for Go ☆`164`
- [rookie-ninja/rk-gin](https://github.com/rookie-ninja/rk-gin) — Start gin microservice from YAML, plugin of rk-boot ☆`51`
- [faabiosr/echo-middleware](https://github.com/faabiosr/echo-middleware) — Middlewares for Echo framework ☆`16`
### Routers

- [gorilla/mux](https://github.com/gorilla/mux) — Powerful HTTP router ☆`21,759`
- [go-chi/chi](https://github.com/go-chi/chi) — Lightweight idiomatic HTTP router ☆`21,262`
- [gernest/alien](https://github.com/gernest/alien) — A lightweight and fast http router from outer space ☆`134`
- [ngamux/ngamux](https://github.com/ngamux/ngamux) — Simple HTTP router for Go ☆`70`
- [bmf-san/goblin](https://github.com/bmf-san/goblin) — A golang http router based on trie tree. ☆`81`
- [muir/nchi](https://github.com/muir/nchi) — golang http router with elegance, speed, and flexibility ☆`18`
### Template Engines

- [a-h/templ](https://github.com/a-h/templ) — A language for writing HTML user interfaces in Go. ☆`9,948`
- [valyala/quicktemplate](https://github.com/valyala/quicktemplate) — Fast template engine for Go ☆`3,295`
- [johnfercher/maroto](https://github.com/johnfercher/maroto) — Create PDFs with Bootstrap grid ☆`2,606`
- [CloudyKit/jet](https://github.com/CloudyKit/jet) — Jet template engine ☆`1,374`
- [osteele/liquid](https://github.com/osteele/liquid) — A Liquid template engine in Go ☆`332`
- [go-sprout/sprout](https://github.com/go-sprout/sprout) — Template functions for Go ☆`198`
- [robfig/soy](https://github.com/robfig/soy) — Go implementation for Soy templates (Google Closure templates) ☆`177`
- [goradd/got](https://github.com/goradd/got) — Template engine with Go code output ☆`38`
### Web Frameworks

- [gin-gonic/gin](https://github.com/gin-gonic/gin) — High-performance HTTP framework ☆`87,575`
- [gofiber/fiber](https://github.com/gofiber/fiber) — Express inspired web framework written in Go ☆`38,892`
- [beego/beego](https://github.com/beego/beego) — High-performance web framework ☆`32,383`
- [labstack/echo](https://github.com/labstack/echo) — High performance, minimalist Go web framework ☆`31,978`
- [gofr-dev/gofr](https://github.com/gofr-dev/gofr) — Microservice framework for Go ☆`15,402`
- [gogf/gf](https://github.com/gogf/gf) — Powerful full-stack framework ☆`12,975`
- [cloudwego/hertz](https://github.com/cloudwego/hertz) — High-performance HTTP framework ☆`6,999`
- [goadesign/goa](https://github.com/goadesign/goa) — Design-first API framework ☆`6,026`
- [apache/dubbo-go](https://github.com/apache/dubbo-go) — Go Implementation For Apache Dubbo . ☆`4,874`
- [goravel/goravel](https://github.com/goravel/goravel) — The full-featured Golang Development Framework skeleton ☆`4,363`
- [danielgtaylor/huma](https://github.com/danielgtaylor/huma) — Huma REST/HTTP API Framework for Golang with OpenAPI 3.1 ☆`3,707`
- [documize/community](https://github.com/documize/community) — Modern Confluence alternative ☆`2,350`
- [go-sonic/sonic](https://github.com/go-sonic/sonic) — Blogging platform in Go ☆`2,119`
- [go-goyave/goyave](https://github.com/go-goyave/goyave) — The enterprise REST API framework ☆`1,757`
- [go-fuego/fuego](https://github.com/go-fuego/fuego) — Web framework with OpenAPI 3 ☆`1,624`
- [savsgio/atreugo](https://github.com/savsgio/atreugo) — Micro web framework on fasthttp ☆`1,300`
- [templui/templui](https://github.com/templui/templui) — UI components for Templ ☆`1,268`
- [ankorstore/yokai](https://github.com/ankorstore/yokai) — Modular framework for Go apps ☆`809`
- [indeedeng/iwf](https://github.com/indeedeng/iwf) — Workflow-as-code orchestration ☆`627`
- [i-love-flamingo/flamingo-commerce](https://github.com/i-love-flamingo/flamingo-commerce) — Flexible Go web framework ☆`585`
- [i-love-flamingo/flamingo](https://github.com/i-love-flamingo/flamingo) — Flexible Go web framework ☆`551`
- [rookie-ninja/rk-boot](https://github.com/rookie-ninja/rk-boot) — Enterprise microservice framework ☆`572`
- [fastschema/fastschema](https://github.com/fastschema/fastschema) — All-in-One Backend as a Service with Headless CMS Power ☆`526`
- [uadmin/uadmin](https://github.com/uadmin/uadmin) — The web framework for Golang ☆`353`
- [xxjwxc/ginrpc](https://github.com/xxjwxc/ginrpc) — gin auto binding, grpc and annotated route ☆`300`
- [hidevopsio/hiboot](https://github.com/hidevopsio/hiboot) — High-performance CLI and web apps ☆`182`
- [beatlabs/patron](https://github.com/beatlabs/patron) — Cloud-native microservice framework ☆`126`
- [gone-io/gone](https://github.com/gone-io/gone) — Lightweight DI framework ☆`132`
- [claygod/microservice](https://github.com/claygod/microservice) — Simple microservice framework ☆`122`
- [gookit/rux](https://github.com/gookit/rux) — Simple and fast web framework ☆`98`
- [yaitoo/xun](https://github.com/yaitoo/xun) — Web framework on html/template ☆`91`
- [napsy/go-css](https://github.com/napsy/go-css) — A very simple CSS parser, written in Go ☆`88`
- [go-spring/spring-core](https://github.com/go-spring/spring-core) — Spring-inspired framework for Go ☆`74`
- [abemedia/go-don](https://github.com/abemedia/go-don) — API framework written in Golang. ☆`57`
- [JiveGroup/gFly](https://github.com/JiveGroup/gFly) — Laravel inspired web framework written in Go ☆`49`
- [SaiNageswarS/go-api-boot](https://github.com/SaiNageswarS/go-api-boot) — gRPC + HTTP/2 production framework ☆`35`
- [clubpay/ronykit](https://github.com/clubpay/ronykit) — API Framework supporting REST and RPC. ☆`34`
- [jvcoutinho/lit](https://github.com/jvcoutinho/lit) — A simple, fast and expressive HTTP framework for Go. ☆`30`
### WebAssembly

- [tinygo-org/tinygo](https://github.com/tinygo-org/tinygo) — Go compiler for microcontrollers ☆`17,030`
- [agnivade/wasmbrowsertest](https://github.com/agnivade/wasmbrowsertest) — Run WASM tests inside your browser ☆`206`
- [extism/go-sdk](https://github.com/extism/go-sdk) — Extism Go SDK - easily run WebAssembly modules in your Go applications ☆`163`
## Workflow & Scheduling

### Job Scheduler

- [go-co-op/gocron](https://github.com/go-co-op/gocron) — Easy and fluent Go cron scheduling ☆`6,834`
- [hatchet-dev/hatchet](https://github.com/hatchet-dev/hatchet) — Run Background Tasks at Scale ☆`6,396`
- [reugn/go-quartz](https://github.com/reugn/go-quartz) — Minimalist and zero-dependency scheduling library for Go ☆`1,990`
- [adhocore/gronx](https://github.com/adhocore/gronx) — Lightweight cron expression parser ☆`481`
- [fieldryand/goflow](https://github.com/fieldryand/goflow) — Simple but powerful DAG scheduler and dashboard ☆`470`
- [madflojo/tasks](https://github.com/madflojo/tasks) — In-process task scheduler ☆`321`
- [bart6114/cheek](https://github.com/bart6114/cheek) — cheek: a pico-sized declarative job scheduler ☆`197`
- [onatm/clockwerk](https://github.com/onatm/clockwerk) — Job Scheduling Library ☆`182`
- [deepaksinghvi/cdule](https://github.com/deepaksinghvi/cdule) — Golang job scheduler ☆`59`
- [pardnchiu/go-scheduler](https://github.com/pardnchiu/go-scheduler) — Scheduler with standard cron and task dependencies ☆`32`
- [romshark/sched](https://github.com/romshark/sched) — A job scheduler for Go with the ability to fast-forward time. ☆`28`
### Workflow Frameworks

- [redpanda-data/connect](https://github.com/redpanda-data/connect) — Fancy stream processing made operationally mundane ☆`8,541`
- [dagu-org/dagu](https://github.com/dagu-org/dagu) — Workflow engine with Web UI ☆`2,960`
- [jf-tech/omniparser](https://github.com/jf-tech/omniparser) — ETL streaming parser for Go ☆`1,076`
- [noneback/go-taskflow](https://github.com/noneback/go-taskflow) — Task-parallel programming library ☆`607`
- [cadence-workflow/cadence-go-client](https://github.com/cadence-workflow/cadence-go-client) — Cadence workflow client for Go ☆`375`
- [luno/workflow](https://github.com/luno/workflow) — Type-safe workflow orchestration ☆`213`
- [rhosocial/go-dag](https://github.com/rhosocial/go-dag) — DAG-based workflow framework ☆`35`


---

## 🏆 Top 100 by Stars

> The most starred projects in this list, sorted by GitHub stars.

1. [ollama/ollama](https://github.com/ollama/ollama) — Run LLMs locally ☆`158,685`
1. [kubernetes/kubernetes](https://github.com/kubernetes/kubernetes) — Production-Grade Container Scheduling and Management ☆`119,626`
1. [gin-gonic/gin](https://github.com/gin-gonic/gin) — High-performance HTTP framework ☆`87,575`
1. [junegunn/fzf](https://github.com/junegunn/fzf) — Command-line fuzzy finder ☆`76,508`
1. [moby/moby](https://github.com/moby/moby) — Container ecosystem components ☆`71,307`
1. [caddyserver/caddy](https://github.com/caddyserver/caddy) — Multi-platform web server with HTTPS ☆`68,925`
1. [prometheus/prometheus](https://github.com/prometheus/prometheus) — The Prometheus monitoring system and time series database. ☆`62,007`
1. [traefik/traefik](https://github.com/traefik/traefik) — The Cloud Native Application Proxy ☆`60,866`
1. [minio/minio](https://github.com/minio/minio) — High-performance object storage ☆`59,569`
1. [golang-standards/project-layout](https://github.com/golang-standards/project-layout) — Standard Go project layout ☆`54,895`
1. [pocketbase/pocketbase](https://github.com/pocketbase/pocketbase) — Open Source realtime backend in 1 file ☆`54,841`
1. [wagoodman/dive](https://github.com/wagoodman/dive) — Explore Docker image layers ☆`53,046`
1. [go-gitea/gitea](https://github.com/go-gitea/gitea) — Self-hosted Git service ☆`52,910`
1. [etcd-io/etcd](https://github.com/etcd-io/etcd) — Distributed key-value store ☆`51,233`
1. [ethereum/go-ethereum](https://github.com/ethereum/go-ethereum) — Go implementation of the Ethereum protocol ☆`50,599`
1. [spf13/cobra](https://github.com/spf13/cobra) — A Commander for modern Go CLI interactions ☆`42,774`
1. [milvus-io/milvus](https://github.com/milvus-io/milvus) — Cloud-native vector database ☆`42,038`
1. [mudler/LocalAI](https://github.com/mudler/LocalAI) — Local OpenAI alternative ☆`40,977`
1. [pingcap/tidb](https://github.com/pingcap/tidb) — Cloud-native distributed SQL DB ☆`39,548`
1. [go-gorm/gorm](https://github.com/go-gorm/gorm) — The fantastic ORM library for Golang, aims to be developer friendly ☆`39,327`
1. [gofiber/fiber](https://github.com/gofiber/fiber) — Express inspired web framework written in Go ☆`38,892`
1. [charmbracelet/bubbletea](https://github.com/charmbracelet/bubbletea) — A powerful little TUI framework ☆`37,890`
1. [harness/harness](https://github.com/harness/harness) — End-to-end developer platform ☆`33,753`
1. [schollz/croc](https://github.com/schollz/croc) — Easily and securely send things from one computer to another ☆`33,675`
1. [zeromicro/go-zero](https://github.com/zeromicro/go-zero) — Microservices framework with CLI tools ☆`32,393`
1. [beego/beego](https://github.com/beego/beego) — High-performance web framework ☆`32,383`
1. [labstack/echo](https://github.com/labstack/echo) — High performance, minimalist Go web framework ☆`31,978`
1. [k3s-io/k3s](https://github.com/k3s-io/k3s) — Lightweight Kubernetes ☆`31,796`
1. [cockroachdb/cockroach](https://github.com/cockroachdb/cockroach) — Cloud native distributed SQL database ☆`31,682`
1. [restic/restic](https://github.com/restic/restic) — Fast, secure backup program ☆`31,559`
1. [kubernetes/minikube](https://github.com/kubernetes/minikube) — Run Kubernetes locally ☆`31,332`
1. [influxdata/influxdb](https://github.com/influxdata/influxdb) — Scalable datastore for metrics, events, and real-time analytics ☆`31,051`
1. [spf13/viper](https://github.com/spf13/viper) — Go configuration with fangs ☆`29,773`
1. [grafana/k6](https://github.com/grafana/k6) — A modern load testing tool, using Go and JavaScript ☆`29,564`
1. [seaweedfs/seaweedfs](https://github.com/seaweedfs/seaweedfs) — Fast distributed storage for blobs ☆`29,300`
1. [fyne-io/fyne](https://github.com/fyne-io/fyne) — Cross platform GUI toolkit in Go inspired by Material Design ☆`27,716`
1. [go-kit/kit](https://github.com/go-kit/kit) — A standard library for microservices. ☆`27,576`
1. [sirupsen/logrus](https://github.com/sirupsen/logrus) — Structured, pluggable logging for Go. ☆`25,643`
1. [stretchr/testify](https://github.com/stretchr/testify) — Assertions and mocks for testing ☆`25,588`
1. [go-kratos/kratos](https://github.com/go-kratos/kratos) — Your ultimate Go microservices framework for the cloud-native era. ☆`25,289`
1. [gocolly/colly](https://github.com/gocolly/colly) — Web scraping framework for Go ☆`24,974`
1. [tsenart/vegeta](https://github.com/tsenart/vegeta) — HTTP load testing tool and library. It's over 9000! ☆`24,813`
1. [uber-go/zap](https://github.com/uber-go/zap) — Fast structured logging ☆`24,092`
1. [urfave/cli](https://github.com/urfave/cli) — Fast CLI framework for Go ☆`23,792`
1. [valyala/fasthttp](https://github.com/valyala/fasthttp) — Fast HTTP package for Go ☆`23,182`
1. [grpc/grpc-go](https://github.com/grpc/grpc-go) — The Go language implementation of gRPC. HTTP/2 based RPC ☆`22,686`
1. [micro/go-micro](https://github.com/micro/go-micro) — A Go microservices framework ☆`22,657`
1. [air-verse/air](https://github.com/air-verse/air) — Live reload for Go apps ☆`22,593`
1. [jaegertracing/jaeger](https://github.com/jaegertracing/jaeger) — Distributed tracing platform ☆`22,306`
1. [redis/go-redis](https://github.com/redis/go-redis) — Redis Go client ☆`21,774`
1. [gorilla/mux](https://github.com/gorilla/mux) — Powerful HTTP router ☆`21,759`
1. [dgraph-io/dgraph](https://github.com/dgraph-io/dgraph) — high-performance graph database for real-time use cases ☆`21,442`
1. [go-chi/chi](https://github.com/go-chi/chi) — Lightweight idiomatic HTTP router ☆`21,262`
1. [samber/lo](https://github.com/samber/lo) — Lodash-style utilities for Go ☆`20,821`
1. [FiloSottile/age](https://github.com/FiloSottile/age) — Simple encryption tool ☆`20,787`
1. [vitessio/vitess](https://github.com/vitessio/vitess) — Database clustering for MySQL ☆`20,597`
1. [qax-os/excelize](https://github.com/qax-os/excelize) — Excel XLSX library for Go ☆`20,146`
1. [antonmedv/fx](https://github.com/antonmedv/fx) — Terminal JSON viewer & processor ☆`20,141`
1. [casbin/casbin](https://github.com/casbin/casbin) — Authorization library for Go ☆`19,624`
1. [go-playground/validator](https://github.com/go-playground/validator) — Struct and field validation for Go ☆`19,533`
1. [dolthub/dolt](https://github.com/dolthub/dolt) — Dolt – Git for Data ☆`19,507`
1. [nats-io/nats-server](https://github.com/nats-io/nats-server) — High-performance NATS message server ☆`18,901`
1. [golangci/golangci-lint](https://github.com/golangci/golangci-lint) — Fast linters runner for Go ☆`18,234`
1. [golang-migrate/migrate](https://github.com/golang-migrate/migrate) — Database migrations. CLI and Golang library. ☆`17,885`
1. [jmoiron/sqlx](https://github.com/jmoiron/sqlx) — Extensions for database/sql ☆`17,443`
1. [rqlite/rqlite](https://github.com/rqlite/rqlite) — Lightweight distributed SQLite ☆`17,199`
1. [tinygo-org/tinygo](https://github.com/tinygo-org/tinygo) — Go compiler for microcontrollers ☆`17,030`
1. [ipfs/kubo](https://github.com/ipfs/kubo) — An IPFS implementation in Go ☆`16,864`
1. [ent/ent](https://github.com/ent/ent) — An entity framework for Go ☆`16,804`
1. [sqlc-dev/sqlc](https://github.com/sqlc-dev/sqlc) — Generate type-safe code from SQL ☆`16,634`
1. [fatih/vim-go](https://github.com/fatih/vim-go) — Go development plugin for Vim ☆`16,220`
1. [pion/webrtc](https://github.com/pion/webrtc) — Pure Go implementation of the WebRTC API ☆`15,881`
1. [VictoriaMetrics/VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) — Fast time series database and monitoring ☆`15,853`
1. [hashicorp/packer](https://github.com/hashicorp/packer) — Build machine images from config ☆`15,543`
1. [goreleaser/goreleaser](https://github.com/goreleaser/goreleaser) — Release engineering simplified ☆`15,431`
1. [gofr-dev/gofr](https://github.com/gofr-dev/gofr) — Microservice framework for Go ☆`15,402`
1. [tidwall/gjson](https://github.com/tidwall/gjson) — Fast JSON value extraction ☆`15,387`
1. [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) — MySQL driver for database/sql ☆`15,365`
1. [dgraph-io/badger](https://github.com/dgraph-io/badger) — Fast key-value DB in Go. ☆`15,335`
1. [kubernetes-sigs/kind](https://github.com/kubernetes-sigs/kind) — Kubernetes IN Docker - local clusters for testing Kubernetes ☆`14,873`
1. [PuerkitoBio/goquery](https://github.com/PuerkitoBio/goquery) — jQuery-like HTML manipulation ☆`14,860`
1. [keploy/keploy](https://github.com/keploy/keploy) — API testing with auto mocks ☆`14,581`
1. [go-task/task](https://github.com/go-task/task) — A task runner / simpler Make alternative written in Go ☆`14,516`
1. [xtaci/kcptun](https://github.com/xtaci/kcptun) — Quantum-safe secure tunnel ☆`14,324`
1. [panjf2000/ants](https://github.com/panjf2000/ants) — ants is the most powerful and reliable pooling solution for Go. ☆`14,231`
1. [webview/webview](https://github.com/webview/webview) — Tiny webview library for Go ☆`13,767`
1. [bytebase/bytebase](https://github.com/bytebase/bytebase) — Database DevSecOps platform ☆`13,509`
1. [gizak/termui](https://github.com/gizak/termui) — Golang terminal dashboard ☆`13,502`
1. [golang/groupcache](https://github.com/golang/groupcache) — Distributed cache library ☆`13,295`
1. [jackc/pgx](https://github.com/jackc/pgx) — PostgreSQL driver and toolkit for Go ☆`13,118`
1. [gopherjs/gopherjs](https://github.com/gopherjs/gopherjs) — A compiler from Go to JavaScript for running Go code in a browser ☆`13,093`
1. [gogf/gf](https://github.com/gogf/gf) — Powerful full-stack framework ☆`12,975`
1. [hajimehoshi/ebiten](https://github.com/hajimehoshi/ebiten) — A dead simple 2D game engine for Go ☆`12,822`
1. [hibiken/asynq](https://github.com/hibiken/asynq) — Simple, reliable, and efficient distributed task queue in Go ☆`12,694`
1. [juicedata/juicefs](https://github.com/juicedata/juicefs) — Distributed POSIX filesystem ☆`12,625`
1. [chromedp/chromedp](https://github.com/chromedp/chromedp) — Chrome DevTools Protocol driver ☆`12,613`
1. [cloudflare/cloudflared](https://github.com/cloudflare/cloudflared) — Cloudflare Tunnel client ☆`12,533`
1. [IBM/sarama](https://github.com/IBM/sarama) — Sarama is a Go library for Apache Kafka. ☆`12,365`
1. [rs/zerolog](https://github.com/rs/zerolog) — Zero allocation JSON logger ☆`12,094`
1. [Shopify/toxiproxy](https://github.com/Shopify/toxiproxy) — TCP proxy for chaos testing ☆`11,756`


## Gophers

- [MariaLetta/free-gophers-pack](https://github.com/MariaLetta/free-gophers-pack) — This pack of 100+ gopher pictures and elements
- [keygx/Go-gopher-Vector](https://github.com/keygx/Go-gopher-Vector) — Go gopher Vector Data (.ai, .svg)
- [ashleymcnamara/gophers](https://github.com/ashleymcnamara/gophers) — Gopher Artwork by Ashley McNamara
- [sillecelik/go-gopher](https://github.com/sillecelik/go-gopher) — The Go Gopher Amigurumi Pattern
- [GolangUA/gopher-logos](https://github.com/GolangUA/gopher-logos) — adorable gopher logos
- [egonelbre/gophers](https://github.com/egonelbre/gophers) — gophers artwork
- [scraly/gophers](https://github.com/scraly/gophers) — Gopher artwork (Golang mascot)

## Contributing

Please see [CONTRIBUTING](.github/CONTRIBUTING.md) for details.

## Feedback

Found something wrong? Open an issue or submit a pull request — contributions are welcome!

## Credits

- [avelino/awesome-go](https://github.com/avelino/awesome-go)
- [All Contributors](https://github.com/abordage/awesome-go/graphs/contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE) for more information.