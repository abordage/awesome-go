# Awesome Go

![Awesome](https://raw.githubusercontent.com/abordage/schemas/main/badges/awesome.svg)
[![Last update](https://img.shields.io/github/last-commit/abordage/awesome-go?label=last%20update)](README.md)
![Repositories](https://img.shields.io/badge/repositories-1,223-06b6d4)
![Total Stars](https://img.shields.io/badge/total%20stars-4,928,407-gold)
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

- [sashabaranov/go-openai](https://github.com/sashabaranov/go-openai) — OpenAI API client for Go ☆`10,548`
- [otiai10/openaigo](https://github.com/otiai10/openaigo) — OpenAI GPT client library ☆`299`
- [wit-ai/wit-go](https://github.com/wit-ai/wit-go) — Go client for wit.ai HTTP API ☆`170`
### Artificial Intelligence

- [ollama/ollama](https://github.com/ollama/ollama) — Run LLMs locally ☆`162,669`
- [mudler/LocalAI](https://github.com/mudler/LocalAI) — Local OpenAI alternative ☆`42,824`
- [tmc/langchaingo](https://github.com/tmc/langchaingo) — LangChain for Go, the easiest way to write LLM-based programs in Go ☆`8,651`
- [maximhq/bifrost](https://github.com/maximhq/bifrost) — Fastest LLM gateway for Go ☆`2,352`
- [philippgille/chromem-go](https://github.com/philippgille/chromem-go) — Embeddable vector database for Go ☆`860`
- [universal-tool-calling-protocol/go-utcp](https://github.com/universal-tool-calling-protocol/go-utcp) — Official Go implementation of the UTCP ☆`98`
- [presbrey/ollamafarm](https://github.com/presbrey/ollamafarm) — Manage multiple Ollama instances ☆`95`
### Machine Learning

- [gorgonia/gorgonia](https://github.com/gorgonia/gorgonia) — Machine learning library for Go ☆`5,908`
- [otiai10/gosseract](https://github.com/otiai10/gosseract) — OCR using Tesseract in Go ☆`3,068`
- [galeone/tfgo](https://github.com/galeone/tfgo) — Tensorflow + Go, the gopher way ☆`2,493`
- [gomlx/gomlx](https://github.com/gomlx/gomlx) — GoMLX: An Accelerated Machine Learning Framework For Go ☆`1,312`
- [jbrukh/bayesian](https://github.com/jbrukh/bayesian) — Naive Bayesian Classification for Golang. ☆`809`
- [knights-analytics/hugot](https://github.com/knights-analytics/hugot) — Onnx transformer pipelines in Golang ☆`563`
- [patrikeh/go-deep](https://github.com/patrikeh/go-deep) — Artificial Neural Network ☆`559`
- [c-bata/goptuna](https://github.com/c-bata/goptuna) — A hyperparameter optimization framework, inspired by Optuna. ☆`276`
## Audio & Video

### Audio

- [ebitengine/oto](https://github.com/ebitengine/oto) — A low-level library to play sound on multiple platforms ☆`1,863`
- [gordonklaus/portaudio](https://github.com/gordonklaus/portaudio) — Go bindings for the PortAudio audio I/O library ☆`826`
- [gen2brain/malgo](https://github.com/gen2brain/malgo) — Mini audio library ☆`387`
- [DylanMeeus/GoAudio](https://github.com/DylanMeeus/GoAudio) — Go tools for audio processing & creation ☆`404`
- [mewkiz/flac](https://github.com/mewkiz/flac) — Package flac provides access to FLAC (Free Lossless Audio Codec) streams. ☆`350`
- [tosone/minimp3](https://github.com/tosone/minimp3) — Decode mp3 ☆`133`
### Images

- [hybridgroup/gocv](https://github.com/hybridgroup/gocv) — Computer vision with OpenCV 4 ☆`7,380`
- [anthonynsimon/bild](https://github.com/anthonynsimon/bild) — Image processing algorithms in pure Go ☆`4,173`
- [cshum/imagor](https://github.com/cshum/imagor) — Fast, secure image processing server and Go library, using libvips ☆`3,895`
- [thoas/picfit](https://github.com/thoas/picfit) — An image resizing server written in Go ☆`2,326`
- [gographics/imagick](https://github.com/gographics/imagick) — Go binding to ImageMagick's MagickWand C API ☆`1,863`
- [tdewolff/canvas](https://github.com/tdewolff/canvas) — Vector graphics in Go ☆`1,780`
- [davidbyttow/govips](https://github.com/davidbyttow/govips) — A lightning fast image processing and resizing library for Go ☆`1,526`
- [yeqown/go-qrcode](https://github.com/yeqown/go-qrcode) — Customizable QR code generator ☆`810`
- [HugoSmits86/nativewebp](https://github.com/HugoSmits86/nativewebp) — Native webp encoder for Go ☆`388`
- [auyer/steganography](https://github.com/auyer/steganography) — LSB steganography in pure Go ☆`353`
- [kolesa-team/go-webp](https://github.com/kolesa-team/go-webp) — Simple and fast webp library for golang ☆`298`
- [Pixboost/transformimgs](https://github.com/Pixboost/transformimgs) — Open source image CDN. ☆`286`
- [qmuntal/gltf](https://github.com/qmuntal/gltf) — Go library for encoding glTF 2.0 files ☆`275`
- [gojek/darkroom](https://github.com/gojek/darkroom) — Image processing engine and proxy service ☆`236`
- [ungerik/go-cairo](https://github.com/ungerik/go-cairo) — Go binding for the cairo graphics library ☆`151`
- [aofei/cameron](https://github.com/aofei/cameron) — An avatar generator for Go. ☆`130`
- [piglig/go-qr](https://github.com/piglig/go-qr) — A native, high-quality and minimalistic QR code generator ☆`47`
### Video

- [asticode/go-astisub](https://github.com/asticode/go-astisub) — Manipulate subtitles in Go ☆`683`
- [asticode/go-astiav](https://github.com/asticode/go-astiav) — Golang ffmpeg and libav C bindings ☆`677`
- [asticode/go-astits](https://github.com/asticode/go-astits) — Demux and mux MPEG Transport Streams (.ts) natively in GO ☆`609`
- [Eyevinn/mp4ff](https://github.com/Eyevinn/mp4ff) — MP4/ISOBMFF tools and library ☆`595`
- [adrg/libvlc-go](https://github.com/adrg/libvlc-go) — Go bindings for libVLC ☆`505`
- [korandiz/v4l](https://github.com/korandiz/v4l) — Facade to the Video4Linux video capture interface. ☆`90`
- [Eyevinn/hls-m3u8](https://github.com/Eyevinn/hls-m3u8) — HLS m3u8 library in Go ☆`49`
- [unki2aut/go-mpd](https://github.com/unki2aut/go-mpd) — MPEG-DASH manifest library ☆`32`
- [jonoton/scout](https://github.com/jonoton/scout) — Video surveillance with motion detection ☆`26`
## Auth

### Authentication

- [golang-jwt/jwt](https://github.com/golang-jwt/jwt) — Go implementation of JSON Web Tokens (JWT). ☆`8,902`
- [markbates/goth](https://github.com/markbates/goth) — Multi-provider authentication ☆`6,449`
- [golang/oauth2](https://github.com/golang/oauth2) — Go OAuth2 ☆`5,812`
- [aarondl/authboss](https://github.com/aarondl/authboss) — The boss of http auth. ☆`4,149`
- [alexedwards/scs](https://github.com/alexedwards/scs) — HTTP Session Management for Go ☆`2,523`
- [lestrrat-go/jwx](https://github.com/lestrrat-go/jwx) — Complete JWx implementation ☆`2,317`
- [openshift/osin](https://github.com/openshift/osin) — Golang OAuth2 server library ☆`1,934`
- [dghubble/gologin](https://github.com/dghubble/gologin) — Go login handlers for authentication providers (OAuth1, OAuth2) ☆`1,945`
- [zitadel/oidc](https://github.com/zitadel/oidc) — OpenID Connect client and server ☆`1,761`
- [cristalhq/jwt](https://github.com/cristalhq/jwt) — Safe, simple and fast JSON Web Tokens for Go ☆`687`
- [shaj13/go-guardian](https://github.com/shaj13/go-guardian) — Authentication library for Go ☆`608`
- [go-jose/go-jose](https://github.com/go-jose/go-jose) — An implementation of JOSE standards (JWE, JWS, JWT) in Go ☆`480`
- [abraithwaite/jeff](https://github.com/abraithwaite/jeff) — Jeff provides the simplest way to manage web sessions in Go. ☆`270`
- [Kwynto/gosession](https://github.com/Kwynto/gosession) — Quick session for net/http ☆`258`
- [leodip/goiabada](https://github.com/leodip/goiabada) — Goiabada is an OAuth2 / OpenID Connect server written in Go. ☆`183`
- [jellydator/sessionup](https://github.com/jellydator/sessionup) — Straightforward HTTP session management ☆`130`
- [brianvoe/sjwt](https://github.com/brianvoe/sjwt) — Simple JWT Golang ☆`122`
- [essentialkaos/branca](https://github.com/essentialkaos/branca) — Encrypted API tokens ☆`95`
- [icza/session](https://github.com/icza/session) — Session management for web servers ☆`118`
- [mengzhuo/cookiestxt](https://github.com/mengzhuo/cookiestxt) — cookiestxt implement parser of cookies txt format ☆`22`
### Authorization

- [casbin/casbin](https://github.com/casbin/casbin) — Authorization library for Go ☆`19,833`
- [ory/keto](https://github.com/ory/keto) — Customizable permission server ☆`5,269`
- [openfga/openfga](https://github.com/openfga/openfga) — Fine-grained authorization server ☆`4,763`
- [cerbos/cerbos](https://github.com/cerbos/cerbos) — Open core authorization layer ☆`4,220`
## Bots & Chat

### Bot Frameworks

- [tucnak/telebot](https://github.com/tucnak/telebot) — Telebot is a Telegram bot framework in Go. ☆`4,562`
- [go-telegram/bot](https://github.com/go-telegram/bot) — Telegram Bot API Go framework ☆`1,585`
- [mymmrac/telego](https://github.com/mymmrac/telego) — Telegram Bot API library for Go ☆`943`
- [diamondburned/arikawa](https://github.com/diamondburned/arikawa) — A Golang library and framework for the Discord API. ☆`568`
- [NicoNex/echotron](https://github.com/NicoNex/echotron) — An elegant and concurrent library for the Telegram bot API in Go. ☆`415`
- [gempir/go-twitch-irc](https://github.com/gempir/go-twitch-irc) — go irc client for twitch.tv ☆`392`
- [innogames/slack-bot](https://github.com/innogames/slack-bot) — Slack bot for Jenkins, Jira, PRs ☆`206`
- [mr-linch/go-tg](https://github.com/mr-linch/go-tg) — Telegram Bot API client ☆`124`
- [slack-io/slacker](https://github.com/slack-io/slacker) — Slack Bot Framework ☆`60`
- [onrik/micha](https://github.com/onrik/micha) — Client lib for Telegram bot api ☆`31`
### Chat APIs

- [bwmarrin/discordgo](https://github.com/bwmarrin/discordgo) — (Golang) Go bindings for Discord ☆`5,776`
- [slack-go/slack](https://github.com/slack-go/slack) — Slack API in Go ☆`4,894`
- [huandu/facebook](https://github.com/huandu/facebook) — A Facebook Graph API SDK For Go. ☆`1,441`
- [chyroc/lark](https://github.com/chyroc/lark) — Lark/Feishu Open API SDK ☆`461`
- [go-lark/lark](https://github.com/go-lark/lark) — Feishu/Lark SDK for Go ☆`238`
- [switchupcb/disgo](https://github.com/switchupcb/disgo) — Next-gen Discord API library ☆`109`
## CLI & Terminal

### Advanced Console UIs

- [charmbracelet/bubbletea](https://github.com/charmbracelet/bubbletea) — A powerful little TUI framework ☆`39,423`
- [antonmedv/fx](https://github.com/antonmedv/fx) — Terminal JSON viewer & processor ☆`20,267`
- [gizak/termui](https://github.com/gizak/termui) — Golang terminal dashboard ☆`13,517`
- [jroimartin/gocui](https://github.com/jroimartin/gocui) — Minimalist Go package aimed at creating Console User Interfaces. ☆`10,511`
- [charmbracelet/lipgloss](https://github.com/charmbracelet/lipgloss) — Style definitions for nice terminal layouts ☆`10,552`
- [charmbracelet/bubbles](https://github.com/charmbracelet/bubbles) — TUI components for Bubble Tea ☆`7,769`
- [c-bata/go-prompt](https://github.com/c-bata/go-prompt) — Interactive prompts for Go ☆`5,464`
- [pterm/pterm](https://github.com/pterm/pterm) — Modern terminal output library ☆`5,362`
- [schollz/progressbar](https://github.com/schollz/progressbar) — Thread-safe progress bar ☆`4,639`
- [mum4k/termdash](https://github.com/mum4k/termdash) — Terminal-based dashboard ☆`2,977`
- [guptarohit/asciigraph](https://github.com/guptarohit/asciigraph) — ASCII line graphs in terminal ☆`2,953`
- [briandowns/spinner](https://github.com/briandowns/spinner) — Terminal spinner indicators ☆`2,508`
- [vbauerster/mpb](https://github.com/vbauerster/mpb) — Multi progress bar ☆`2,477`
- [muesli/termenv](https://github.com/muesli/termenv) — Terminal color support ☆`1,965`
- [gookit/color](https://github.com/gookit/color) — Terminal color rendering ☆`1,571`
- [logrusorgru/aurora](https://github.com/logrusorgru/aurora) — ANSI colors for Printf ☆`1,476`
- [mattn/go-isatty](https://github.com/mattn/go-isatty) — Check if terminal is TTY ☆`887`
- [mattn/go-colorable](https://github.com/mattn/go-colorable) — Colorable writer for Windows ☆`803`
- [box-cli-maker/box-cli-maker](https://github.com/box-cli-maker/box-cli-maker) — Render highly customizable boxes in the terminal ☆`608`
- [Evertras/bubble-table](https://github.com/Evertras/bubble-table) — Table component for Bubble Tea ☆`550`
- [DMcP89/tinycare-tui](https://github.com/DMcP89/tinycare-tui) — TUI application written in GO inspired by tiny-care-terminal ☆`16`
### Standard CLI

- [spf13/cobra](https://github.com/spf13/cobra) — A Commander for modern Go CLI interactions ☆`43,152`
- [urfave/cli](https://github.com/urfave/cli) — Fast CLI framework for Go ☆`23,885`
- [elves/elvish](https://github.com/elves/elvish) — Scripting shell for Go ☆`6,234`
- [alecthomas/kingpin](https://github.com/alecthomas/kingpin) — Command-line parser ☆`3,561`
- [dnote/dnote](https://github.com/dnote/dnote) — Command-line notebook ☆`3,006`
- [spf13/pflag](https://github.com/spf13/pflag) — POSIX/GNU-style flags ☆`2,704`
- [jessevdk/go-flags](https://github.com/jessevdk/go-flags) — Command-line option parser ☆`2,688`
- [alexflint/go-arg](https://github.com/alexflint/go-arg) — Struct-based argument parsing ☆`2,226`
- [carapace-sh/carapace-bin](https://github.com/carapace-sh/carapace-bin) — Multi-shell completion binary ☆`1,690`
- [nanovms/ops](https://github.com/nanovms/ops) — Build and run unikernels ☆`1,465`
- [carapace-sh/carapace](https://github.com/carapace-sh/carapace) — Multi-shell completion library ☆`1,156`
- [posener/complete](https://github.com/posener/complete) — Bash completion in Go ☆`951`
- [ddddddO/gtree](https://github.com/ddddddO/gtree) — Generate ASCII tree from Markdown ☆`326`
- [leaanthony/clir](https://github.com/leaanthony/clir) — Simple CLI library ☆`196`
- [urfave/sflags](https://github.com/urfave/sflags) — Generate flags from structs ☆`167`
- [hedzr/cmdr](https://github.com/hedzr/cmdr) — POSIX-compliant CLI parser ☆`141`
- [reeflective/readline](https://github.com/reeflective/readline) — Shell library with inputrc ☆`133`
- [cristalhq/acmd](https://github.com/cristalhq/acmd) — Simple CLI package ☆`137`
- [reeflective/console](https://github.com/reeflective/console) — Console library for Cobra ☆`103`
- [codingconcepts/env](https://github.com/codingconcepts/env) — Tag-based environment configuration for structs ☆`126`
- [dixonwille/wlog](https://github.com/dixonwille/wlog) — Cross-platform logging ☆`67`
- [jxskiss/mcli](https://github.com/jxskiss/mcli) — Minimal but powerful CLI ☆`43`
- [DavidGamba/go-getoptions](https://github.com/DavidGamba/go-getoptions) — Command line option parser with completion ☆`61`
- [nyaosorg/go-readline-ny](https://github.com/nyaosorg/go-readline-ny) — Readline for Go ☆`32`
- [carapace-sh/carapace-spec](https://github.com/carapace-sh/carapace-spec) — Multi-shell completion library ☆`29`
- [sgreben/flagvar](https://github.com/sgreben/flagvar) — CLI argument types for flag ☆`48`
- [hashicorp/cli](https://github.com/hashicorp/cli) — CLI library for Go ☆`35`
## Concurrency

### Actor Model

- [asynkron/protoactor-go](https://github.com/asynkron/protoactor-go) — Ultra fast distributed actors for Go ☆`5,419`
- [ergo-services/ergo](https://github.com/ergo-services/ergo) — Actor framework with network transparency ☆`4,425`
- [anthdm/hollywood](https://github.com/anthdm/hollywood) — Blazingly fast and light-weight Actor engine written in Golang ☆`2,177`
- [Tochemey/goakt](https://github.com/Tochemey/goakt) — Distributed actor framework ☆`321`
### Goroutines

- [panjf2000/ants](https://github.com/panjf2000/ants) — ants is the most powerful and reliable pooling solution for Go. ☆`14,324`
- [benmanns/goworker](https://github.com/benmanns/goworker) — Resque-compatible background worker ☆`2,847`
- [alitto/pond](https://github.com/alitto/pond) — High-performance worker pool ☆`2,080`
- [destel/rill](https://github.com/destel/rill) — Channel-based concurrency toolkit ☆`1,803`
- [xxjwxc/gowp](https://github.com/xxjwxc/gowp) — Goroutine worker pool ☆`522`
- [earthboundkid/flowmatic](https://github.com/earthboundkid/flowmatic) — Structured concurrency ☆`397`
- [reugn/async](https://github.com/reugn/async) — Async computation package ☆`294`
- [timandy/routine](https://github.com/timandy/routine) — ThreadLocal for Go ☆`287`
- [vladopajic/go-actor](https://github.com/vladopajic/go-actor) — Actor model library ☆`279`
- [mborders/artifex](https://github.com/mborders/artifex) — In-memory job queue ☆`214`
### Stream Processing

- [reugn/go-streams](https://github.com/reugn/go-streams) — Stream processing library ☆`2,157`
- [Breeze0806/go-etl](https://github.com/Breeze0806/go-etl) — ETL toolset for Go ☆`182`
- [fulminate-io/machine](https://github.com/fulminate-io/machine) — Machine is a workflow/pipeline library for processing data ☆`165`
- [mariomac/gostream](https://github.com/mariomac/gostream) — Java Streams port for Go ☆`171`
- [rulego/streamsql](https://github.com/rulego/streamsql) — SQL-based stream processing for IoT ☆`53`
## Configuration

- [spf13/viper](https://github.com/spf13/viper) — Go configuration with fangs ☆`29,992`
- [caarlos0/env](https://github.com/caarlos0/env) — Parse environment variables to structs ☆`5,996`
- [knadh/koanf](https://github.com/knadh/koanf) — Lightweight config management ☆`3,859`
- [alecthomas/kong](https://github.com/alecthomas/kong) — Command-line parser for Go ☆`2,971`
- [ilyakaznacheev/cleanenv](https://github.com/ilyakaznacheev/cleanenv) — Minimalistic environment config reader ☆`2,052`
- [adrg/xdg](https://github.com/adrg/xdg) — XDG Base Directory implementation ☆`953`
- [cristalhq/aconfig](https://github.com/cristalhq/aconfig) — Simple config loader ☆`623`
- [gookit/config](https://github.com/gookit/config) — Config management with formats ☆`578`
- [kkyr/fig](https://github.com/kkyr/fig) — Minimalist config library ☆`385`
- [nil-go/konf](https://github.com/nil-go/konf) — Simplest config loader for Go ☆`362`
- [hjson/hjson-go](https://github.com/hjson/hjson-go) — Hjson for Go ☆`347`
- [vrischmann/envconfig](https://github.com/vrischmann/envconfig) — Env config library ☆`250`
- [chaindead/zerocfg](https://github.com/chaindead/zerocfg) — Zero-effort config management ☆`199`
- [beatlabs/harvester](https://github.com/beatlabs/harvester) — Watch and notify config changes ☆`134`
- [gurkankaymak/hocon](https://github.com/gurkankaymak/hocon) — HOCON config library for Go ☆`88`
- [BoRuDar/configuration](https://github.com/BoRuDar/configuration) — Set struct fields from env, flags, files ☆`108`
- [PaddleHQ/go-aws-ssm](https://github.com/PaddleHQ/go-aws-ssm) — AWS System Manager interface ☆`62`
- [go-simpler/env](https://github.com/go-simpler/env) — Load env vars to struct ☆`80`
- [omeid/uconfig](https://github.com/omeid/uconfig) — Lightweight config management ☆`72`
- [sakirsensoy/genv](https://github.com/sakirsensoy/genv) — Easy env variable handling ☆`43`
- [num30/config](https://github.com/num30/config) — Declarative configuration ☆`60`
- [wkhere/bcl](https://github.com/wkhere/bcl) — Basic Configuration Language ☆`29`
- [dsbasko/go-cfg](https://github.com/dsbasko/go-cfg) — Unified config reading ☆`47`
- [atelpis/enflag](https://github.com/atelpis/enflag) — Unify env and flag parsing ☆`37`
- [greencoda/confiq](https://github.com/greencoda/confiq) — Config struct decoder ☆`39`
- [nasermirzaei89/env](https://github.com/nasermirzaei89/env) — Zero-dep env package ☆`22`
- [deatil/go-array](https://github.com/deatil/go-array) — Read/set map, slice, JSON data ☆`22`
- [romshark/yamagiconf](https://github.com/romshark/yamagiconf) — YAML config framework ☆`18`
## Data Formats

### JSON

- [tidwall/gjson](https://github.com/tidwall/gjson) — Fast JSON value extraction ☆`15,439`
- [bytedance/sonic](https://github.com/bytedance/sonic) — A blazingly fast JSON serializing & deserializing library ☆`9,195`
- [Jeffail/gabs](https://github.com/Jeffail/gabs) — Dynamic JSON parsing ☆`3,529`
- [valyala/fastjson](https://github.com/valyala/fastjson) — Fast JSON parser for Go ☆`2,435`
- [ohler55/ojg](https://github.com/ohler55/ojg) — Optimized JSON for Go ☆`935`
- [wI2L/jsondiff](https://github.com/wI2L/jsondiff) — JSON Patch diff computation ☆`622`
- [spyzhov/ajson](https://github.com/spyzhov/ajson) — Abstract JSON with JSONPath ☆`291`
- [Andrew-M-C/go.jsonvalue](https://github.com/Andrew-M-C/go.jsonvalue) — Unstructured JSON solution ☆`202`
- [iOliverNguyen/ujson](https://github.com/iOliverNguyen/ujson) — Minimal JSON parser ☆`85`
- [neilotoole/jsoncolor](https://github.com/neilotoole/jsoncolor) — Colorized JSON output ☆`50`
- [ake-persson/mapslice-json](https://github.com/ake-persson/mapslice-json) — Ordered JSON map slices ☆`20`
- [vtopc/epoch](https://github.com/vtopc/epoch) — Unix timestamp marshaling ☆`17`
### Serialization

- [golang/protobuf](https://github.com/golang/protobuf) — Protocol buffers for Go ☆`10,060`
- [ugorji/go](https://github.com/ugorji/go) — Codec for msgpack, cbor, json ☆`1,938`
- [linkedin/goavro](https://github.com/linkedin/goavro) — Goavro is a library that encodes and decodes Avro data. ☆`1,055`
- [fxamacker/cbor](https://github.com/fxamacker/cbor) — CBOR codec with extensions ☆`1,021`
- [jszwec/csvutil](https://github.com/jszwec/csvutil) — CSV to struct mapping ☆`1,030`
- [ghostiam/binstruct](https://github.com/ghostiam/binstruct) — Binary to struct decoder ☆`112`
- [csweichel/bel](https://github.com/csweichel/bel) — Generate TypeScript from Go ☆`45`
- [o1egl/fwencoder](https://github.com/o1egl/fwencoder) — Fixed width file parser ☆`27`
- [tiendc/go-csvlib](https://github.com/tiendc/go-csvlib) — High-level CSV library ☆`18`
### XML

- [miku/zek](https://github.com/miku/zek) — Generate Go struct from XML ☆`823`
- [antchfx/xpath](https://github.com/antchfx/xpath) — XPath for Go ☆`735`
- [antchfx/xmlquery](https://github.com/antchfx/xmlquery) — XPath XML query ☆`486`
## Data Structures

### Bit-packing and Compression

- [RoaringBitmap/roaring](https://github.com/RoaringBitmap/roaring) — Compressed bitmaps for Go ☆`2,835`
- [iancmcc/bingo](https://github.com/iancmcc/bingo) — Zero-allocation binary encoding ☆`50`
- [amallia/go-ef](https://github.com/amallia/go-ef) — A Go implementation of the Elias-Fano encoding ☆`41`
### Bloom and Cuckoo Filters

- [bits-and-blooms/bloom](https://github.com/bits-and-blooms/bloom) — Bloom filter implementation ☆`2,750`
- [tylertreat/BoomFilters](https://github.com/tylertreat/BoomFilters) — Probabilistic data structures for streams ☆`1,641`
- [seiflotfy/cuckoofilter](https://github.com/seiflotfy/cuckoofilter) — Cuckoo Filter: Practically Better Than Bloom ☆`1,216`
- [OldPanda/bloomfilter](https://github.com/OldPanda/bloomfilter) — Bloom filter compatible with pybloom ☆`20`
### Maps

- [mhmtszr/concurrent-swiss-map](https://github.com/mhmtszr/concurrent-swiss-map) — Thread-safe concurrent hash map ☆`261`
- [goradd/maps](https://github.com/goradd/maps) — Generic map library for Go ☆`51`
- [srfrog/dict](https://github.com/srfrog/dict) — Python-like dictionaries for Go ☆`46`
### Miscellaneous

- [Workiva/go-datastructures](https://github.com/Workiva/go-datastructures) — Performant, threadsafe data structures ☆`7,897`
- [deckarep/golang-set](https://github.com/deckarep/golang-set) — Generic set type for Go ☆`4,646`
- [bits-and-blooms/bitset](https://github.com/bits-and-blooms/bitset) — Go package implementing bitsets ☆`1,482`
- [liyue201/gostl](https://github.com/liyue201/gostl) — Data structures modeled on C++ STL ☆`1,135`
- [axiomhq/hyperloglog](https://github.com/axiomhq/hyperloglog) — HyperLogLog with optimizations ☆`1,028`
- [kelindar/bitmap](https://github.com/kelindar/bitmap) — Simple dense bitmap index in Go with binary operators ☆`374`
- [barweiss/go-tuple](https://github.com/barweiss/go-tuple) — Go 1.18+ generic tuple ☆`96`
- [seiflotfy/count-min-log](https://github.com/seiflotfy/count-min-log) — Go implementation of Count-Min-Log ☆`68`
- [s0rg/quadtree](https://github.com/s0rg/quadtree) — Generic, zero-alloc, 100%-test covered Quadtree for golang ☆`41`
- [StudioSol/set](https://github.com/StudioSol/set) — Simple set data structure ☆`29`
- [nazar256/parapipe](https://github.com/nazar256/parapipe) — Paralleling pipeline ☆`37`
- [bobg/merkle](https://github.com/bobg/merkle) — Merkle hash trees ☆`21`
### Queues

- [gammazero/deque](https://github.com/gammazero/deque) — Fast ring-buffer deque (double-ended queue) ☆`756`
- [adrianbrad/queue](https://github.com/adrianbrad/queue) — Multiple queue implementations ☆`330`
- [embano1/memlog](https://github.com/embano1/memlog) — A Kafka log inspired in-memory and append-only data structure ☆`135`
- [mikestefanello/backlite](https://github.com/mikestefanello/backlite) — SQLite-backed task queues ☆`136`
## Databases

### Caches

- [golang/groupcache](https://github.com/golang/groupcache) — Distributed cache library ☆`13,322`
- [dgraph-io/ristretto](https://github.com/dgraph-io/ristretto) — A high performance memory-bound Go cache ☆`6,766`
- [eko/gocache](https://github.com/eko/gocache) — Multi-store caching library ☆`2,838`
- [bluele/gcache](https://github.com/bluele/gcache) — In-memory cache with eviction ☆`2,729`
- [maypok86/otter](https://github.com/maypok86/otter) — A high performance caching library for Go ☆`2,508`
- [VictoriaMetrics/fastcache](https://github.com/VictoriaMetrics/fastcache) — Fast in-memory cache for Go ☆`2,336`
- [jellydator/ttlcache](https://github.com/jellydator/ttlcache) — An in-memory cache with item expiration and generics ☆`1,214`
- [viccon/sturdyc](https://github.com/viccon/sturdyc) — Caching with advanced concurrency ☆`1,248`
- [EchoVault/SugarDB](https://github.com/EchoVault/SugarDB) — Embeddable and distributed in-memory alternative to Redis. ☆`521`
- [faabiosr/cachego](https://github.com/faabiosr/cachego) — Golang Cache component - Multiple drivers ☆`372`
- [Yiling-J/theine-go](https://github.com/Yiling-J/theine-go) — high performance in-memory cache ☆`362`
- [elastic/go-freelru](https://github.com/elastic/go-freelru) — GC-less, fast and generic LRU cache for Go ☆`261`
- [samber/hot](https://github.com/samber/hot) — In-memory caching library for read-intensive Go applications ☆`239`
- [naughtygopher/pocache](https://github.com/naughtygopher/pocache) — Preemptive optimistic caching ☆`231`
- [OrlovEvgeny/go-mcache](https://github.com/OrlovEvgeny/go-mcache) — Sharded in-memory KV cache ☆`103`
- [erni27/imcache](https://github.com/erni27/imcache) — A zero-dependency generic in-memory cache Go library ☆`123`
- [zekroTJA/timedmap](https://github.com/zekroTJA/timedmap) — A thread safe map which has expiring key-value pairs. ☆`74`
- [codingsince1985/couchcache](https://github.com/codingsince1985/couchcache) — A RESTful caching micro-service in Go backed by Couchbase ☆`66`
- [mdaliyan/icache](https://github.com/mdaliyan/icache) — High-performance generic cache ☆`23`
### Database Schema Migration

- [golang-migrate/migrate](https://github.com/golang-migrate/migrate) — Database migrations. CLI and Golang library. ☆`18,099`
- [bytebase/bytebase](https://github.com/bytebase/bytebase) — Database DevSecOps platform ☆`13,728`
- [pressly/goose](https://github.com/pressly/goose) — A database migration tool. Supports SQL migrations and Go functions. ☆`10,176`
- [ariga/atlas](https://github.com/ariga/atlas) — Declarative schema migrations with schema-as-code workflows ☆`8,083`
- [amacneil/dbmate](https://github.com/amacneil/dbmate) — A lightweight, framework-agnostic database migration tool. ☆`6,721`
- [rubenv/sql-migrate](https://github.com/rubenv/sql-migrate) — SQL schema migration tool for Go. ☆`3,402`
- [skeema/skeema](https://github.com/skeema/skeema) — Declarative pure-SQL schema management for MySQL and MariaDB ☆`1,357`
- [go-gormigrate/gormigrate](https://github.com/go-gormigrate/gormigrate) — Minimalistic database migration helper for Gorm ORM ☆`1,150`
- [sunary/sqlize](https://github.com/sunary/sqlize) — SQL parsing and migration toolkit ☆`124`
- [robinjoseph08/go-pg-migrations](https://github.com/robinjoseph08/go-pg-migrations) — A Go package to help write migrations with go-pg/pg. ☆`86`
- [adlio/schema](https://github.com/adlio/schema) — Embedded schema migration package for Go ☆`42`
- [khezen/avro](https://github.com/khezen/avro) — Apache AVRO for go ☆`48`
- [muir/libschema](https://github.com/muir/libschema) — database schema migrations on a per-library basis [Go] ☆`17`
### Database Tools

- [vitessio/vitess](https://github.com/vitessio/vitess) — Database clustering for MySQL ☆`20,697`
- [sosedoff/pgweb](https://github.com/sosedoff/pgweb) — Cross-platform client for PostgreSQL databases ☆`9,256`
- [go-mysql-org/go-mysql](https://github.com/go-mysql-org/go-mysql) — a powerful mysql toolset with Go ☆`4,920`
- [prest/prest](https://github.com/prest/prest) — PostgreSQL REST API server ☆`4,519`
- [ContentSquare/chproxy](https://github.com/ContentSquare/chproxy) — Open-Source ClickHouse http proxy and load balancer ☆`1,437`
- [cybertec-postgresql/pg_timetable](https://github.com/cybertec-postgresql/pg_timetable) — Advanced PostgreSQL scheduler ☆`1,318`
- [liweiyi88/onedump](https://github.com/liweiyi88/onedump) — Effortless database administration tool ☆`922`
- [HDT3213/rdb](https://github.com/HDT3213/rdb) — Redis RDB parser for Go ☆`597`
- [nikepan/clickhouse-bulk](https://github.com/nikepan/clickhouse-bulk) — Batch inserts for ClickHouse ☆`505`
- [wesql/wescale](https://github.com/wesql/wescale) — MySQL proxy with read/write split ☆`313`
- [gatewayd-io/gatewayd](https://github.com/gatewayd-io/gatewayd) — database gateway for building data-driven applications ☆`275`
- [sj14/dbbench](https://github.com/sj14/dbbench) — Database benchmarking tool ☆`115`
- [bartventer/gorm-multitenancy](https://github.com/bartventer/gorm-multitenancy) — Multi-tenancy for GORM ☆`78`
- [kazhuravlev/database-gateway](https://github.com/kazhuravlev/database-gateway) — Safe access to production databases ☆`29`
- [codingconcepts/dg](https://github.com/codingconcepts/dg) — Generate CSV from data models ☆`43`
### Databases Implemented in Go

- [prometheus/prometheus](https://github.com/prometheus/prometheus) — The Prometheus monitoring system and time series database. ☆`62,710`
- [milvus-io/milvus](https://github.com/milvus-io/milvus) — Cloud-native vector database ☆`42,767`
- [pingcap/tidb](https://github.com/pingcap/tidb) — Cloud-native distributed SQL DB ☆`39,741`
- [cockroachdb/cockroach](https://github.com/cockroachdb/cockroach) — Cloud native distributed SQL database ☆`31,852`
- [influxdata/influxdb](https://github.com/influxdata/influxdb) — Scalable datastore for metrics, events, and real-time analytics ☆`31,221`
- [dgraph-io/dgraph](https://github.com/dgraph-io/dgraph) — high-performance graph database for real-time use cases ☆`21,530`
- [dolthub/dolt](https://github.com/dolthub/dolt) — Dolt – Git for Data ☆`19,808`
- [rqlite/rqlite](https://github.com/rqlite/rqlite) — Lightweight distributed SQLite ☆`17,310`
- [VictoriaMetrics/VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) — Fast time series database and monitoring ☆`16,324`
- [dgraph-io/badger](https://github.com/dgraph-io/badger) — Fast key-value DB in Go. ☆`15,468`
- [dicedb/dicedb](https://github.com/dicedb/dicedb) — Open-source, low-latency key/value engine built on Valkey with hierarchical storage tiers. ☆`10,685`
- [etcd-io/bbolt](https://github.com/etcd-io/bbolt) — An embedded key/value database for Go. ☆`9,364`
- [codenotary/immudb](https://github.com/codenotary/immudb) — Immutable database with SQL ☆`8,917`
- [cockroachdb/pebble](https://github.com/cockroachdb/pebble) — RocksDB/LevelDB inspired key-value database in Go ☆`5,770`
- [rosedblabs/rosedb](https://github.com/rosedblabs/rosedb) — Fast key/value storage engine ☆`4,877`
- [tidwall/buntdb](https://github.com/tidwall/buntdb) — Embeddable in-memory key/value DB ☆`4,834`
- [nalgeon/redka](https://github.com/nalgeon/redka) — Redis re-implemented with SQL ☆`4,514`
- [HDT3213/godis](https://github.com/HDT3213/godis) — A Golang implemented Redis Server and Cluster ☆`3,821`
- [nutsdb/nutsdb](https://github.com/nutsdb/nutsdb) — Simple embeddable key/value store ☆`3,551`
- [lindb/lindb](https://github.com/lindb/lindb) — Scalable time-series database ☆`3,060`
- [lotusdblabs/lotusdb](https://github.com/lotusdblabs/lotusdb) — Key-value database with LSM and B+ tree ☆`2,250`
- [kelindar/column](https://github.com/kelindar/column) — Columnar in-memory store ☆`1,506`
- [akrylysov/pogreb](https://github.com/akrylysov/pogreb) — Embedded key-value store for read-heavy workloads written in Go ☆`1,349`
- [objectbox/objectbox-go](https://github.com/objectbox/objectbox-go) — Embedded database for Go ☆`1,258`
- [couchbase/moss](https://github.com/couchbase/moss) — Simple, fast key-val storage ☆`1,017`
- [amit-davidson/LibraDB](https://github.com/amit-davidson/LibraDB) — Simple persistent key/value store ☆`198`
- [claygod/transaction](https://github.com/claygod/transaction) — Embedded database for accounts transactions. ☆`139`
- [xgzlucario/rotom](https://github.com/xgzlucario/rotom) — Tiny Redis server in Go ☆`41`
### Distributed Storage

- [seaweedfs/seaweedfs](https://github.com/seaweedfs/seaweedfs) — Fast distributed storage for blobs ☆`30,248`
- [juicedata/juicefs](https://github.com/juicedata/juicefs) — Distributed POSIX filesystem ☆`13,217`
### Interfaces to Multiple Backends

- [philippgille/gokv](https://github.com/philippgille/gokv) — Key-value store abstraction ☆`821`
- [avito-tech/go-transaction-manager](https://github.com/avito-tech/go-transaction-manager) — Transaction manager for Go ☆`383`
- [viant/dsc](https://github.com/viant/dsc) — Datastore Connectivity in go ☆`35`
- [fogfish/dynamo](https://github.com/fogfish/dynamo) — Generic Golang Key/Value trait for AWS storage services ☆`22`
### NoSQL Database Drivers

- [redis/go-redis](https://github.com/redis/go-redis) — Redis Go client ☆`21,927`
- [gomodule/redigo](https://github.com/gomodule/redigo) — Go client for Redis ☆`9,884`
- [mongodb/mongo-go-driver](https://github.com/mongodb/mongo-go-driver) — The Official Golang driver for MongoDB ☆`8,505`
- [bradfitz/gomemcache](https://github.com/bradfitz/gomemcache) — Go Memcached client library #golang ☆`1,867`
- [qiniu/qmgo](https://github.com/qiniu/qmgo) — Go driver for MongoDB ☆`1,349`
- [aerospike/aerospike-client-go](https://github.com/aerospike/aerospike-client-go) — Aerospike Client Go ☆`457`
- [couchbase/gocb](https://github.com/couchbase/gocb) — The Couchbase Go SDK ☆`376`
- [go-kivik/kivik](https://github.com/go-kivik/kivik) — CouchDB client interface ☆`336`
- [couchbase/go-couchbase](https://github.com/couchbase/go-couchbase) — Couchbase client in Go ☆`324`
- [chenmingyong0423/go-mongox](https://github.com/chenmingyong0423/go-mongox) — MongoDB driver wrapper with generics ☆`217`
- [aliexpressru/gomemcached](https://github.com/aliexpressru/gomemcached) — Binary Memcached client with sharding ☆`22`
- [btnguyen2k/gocosmos](https://github.com/btnguyen2k/gocosmos) — Go database/sql driver for Azure Cosmos DB SQL API ☆`22`
### ORM

- [go-gorm/gorm](https://github.com/go-gorm/gorm) — The fantastic ORM library for Golang, aims to be developer friendly ☆`39,493`
- [ent/ent](https://github.com/ent/ent) — An entity framework for Go ☆`16,918`
- [aarondl/sqlboiler](https://github.com/aarondl/sqlboiler) — Generate a Go ORM tailored to your database schema. ☆`6,977`
- [uptrace/bun](https://github.com/uptrace/bun) — SQL-first Golang ORM ☆`4,662`
- [upper/db](https://github.com/upper/db) — Data access layer for databases ☆`3,641`
- [huandu/go-sqlbuilder](https://github.com/huandu/go-sqlbuilder) — SQL builder with zero-config ORM ☆`1,665`
- [stephenafamo/bob](https://github.com/stephenafamo/bob) — SQL builder with ORM generator ☆`1,630`
- [go-rel/rel](https://github.com/go-rel/rel) — Modern ORM for Golang ☆`781`
- [FrancoLiberali/cql](https://github.com/FrancoLiberali/cql) — CQL: Compiled Query Language ☆`17`
- [hashicorp/go-dbw](https://github.com/hashicorp/go-dbw) — A simple package that encapsulates database operations. ☆`16`
### Query Language

- [99designs/gqlgen](https://github.com/99designs/gqlgen) — go generate based graphql server library ☆`10,663`
- [TomWright/dasel](https://github.com/TomWright/dasel) — Query and modify data formats ☆`7,830`
- [graph-gophers/graphql-go](https://github.com/graph-gophers/graphql-go) — GraphQL server with a focus on ease of use ☆`4,739`
- [bhmj/jsonslice](https://github.com/bhmj/jsonslice) — json slicer ☆`92`
- [hashicorp/mql](https://github.com/hashicorp/mql) — Model Query Language (mql) is a query language for your database models. ☆`65`
- [ccbrown/api-fu](https://github.com/ccbrown/api-fu) — A collection of Go packages for creating robust GraphQL APIs ☆`57`
- [AsaiYusuke/jsonpath](https://github.com/AsaiYusuke/jsonpath) — JSONPath query library ☆`30`
### Relational Database Drivers

- [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) — MySQL driver for database/sql ☆`15,422`
- [jackc/pgx](https://github.com/jackc/pgx) — PostgreSQL driver and toolkit for Go ☆`13,330`
- [denisenkom/go-mssqldb](https://github.com/denisenkom/go-mssqldb) — Microsoft SQL server driver written in go language ☆`1,880`
- [ncruces/go-sqlite3](https://github.com/ncruces/go-sqlite3) — Go bindings to SQLite using wazero ☆`913`
- [godror/godror](https://github.com/godror/godror) — GO DRiver for ORacle DB ☆`587`
- [cvilsmeier/sqinn-go](https://github.com/cvilsmeier/sqinn-go) — Golang SQLite without cgo ☆`510`
- [VinGarcia/ksql](https://github.com/VinGarcia/ksql) — A Simple and Powerful Golang SQL Library ☆`353`
- [surrealdb/surrealdb.go](https://github.com/surrealdb/surrealdb.go) — SurrealDB SDK for Golang ☆`300`
- [nakagami/firebirdsql](https://github.com/nakagami/firebirdsql) — Firebird RDBMS sql driver for Go (golang) ☆`255`
- [ydb-platform/ydb-go-sdk](https://github.com/ydb-platform/ydb-go-sdk) — Pure Go native and database/sql driver for YDB ☆`174`
- [rqlite/gorqlite](https://github.com/rqlite/gorqlite) — A Go client for rqlite, the distributed database built on SQLite ☆`178`
- [apache/calcite-avatica-go](https://github.com/apache/calcite-avatica-go) — Apache Calcite Go ☆`124`
- [viant/bgc](https://github.com/viant/bgc) — Datastore Connectivity for BigQuery in go ☆`21`
### SQL Query Builders

- [sqlc-dev/sqlc](https://github.com/sqlc-dev/sqlc) — Generate type-safe code from SQL ☆`16,939`
- [Masterminds/squirrel](https://github.com/Masterminds/squirrel) — Fluent SQL generation for golang ☆`7,862`
- [xo/dbtpl](https://github.com/xo/dbtpl) — Generate Go code for databases ☆`3,885`
- [go-jet/jet](https://github.com/go-jet/jet) — Type-safe SQL builder with codegen ☆`3,574`
- [doug-martin/goqu](https://github.com/doug-martin/goqu) — SQL builder and query library for golang ☆`2,635`
- [didi/gendry](https://github.com/didi/gendry) — a golang library for sql builder ☆`1,642`
- [lqs/sqlingo](https://github.com/lqs/sqlingo) — A lightweight DSL & ORM which helps you to write SQL in Go. ☆`448`
- [nullism/bqb](https://github.com/nullism/bqb) — Lightweight query builder ☆`186`
- [arthurkushman/buildsqlx](https://github.com/arthurkushman/buildsqlx) — Go database query builder library for PostgreSQL ☆`185`
- [galeone/igor](https://github.com/galeone/igor) — igor is an abstraction layer for PostgreSQL with a gorm like syntax. ☆`126`
- [cristalhq/builq](https://github.com/cristalhq/builq) — Easily build SQL queries in Go. ☆`97`
- [HnH/qry](https://github.com/HnH/qry) — SQL queries in raw files ☆`35`
- [JiveGroup/FluentSQL](https://github.com/JiveGroup/FluentSQL) — Fluent SQL - flexible and powerful SQL string builder ☆`18`
### Search and Analytic Databases

- [elastic/go-elasticsearch](https://github.com/elastic/go-elasticsearch) — The official Go client for Elasticsearch ☆`6,026`
- [ClickHouse/clickhouse-go](https://github.com/ClickHouse/clickhouse-go) — Golang driver for ClickHouse ☆`3,247`
- [sourcegraph/zoekt](https://github.com/sourcegraph/zoekt) — Fast trigram-based code search ☆`1,395`
- [sdqri/effdsl](https://github.com/sdqri/effdsl) — Elasticsearch query builder for golang ☆`34`
## DevOps & Build

### Backup

- [restic/restic](https://github.com/restic/restic) — Fast, secure backup program ☆`32,235`
- [gilbertchen/duplicacy](https://github.com/gilbertchen/duplicacy) — Cloud backup tool ☆`5,619`
### Build Automation

- [air-verse/air](https://github.com/air-verse/air) — Live reload for Go apps ☆`22,970`
- [go-task/task](https://github.com/go-task/task) — A fast, cross-platform build tool inspired by Make, designed for modern workflows. ☆`14,832`
- [joerdav/xc](https://github.com/joerdav/xc) — Markdown defined task runner. ☆`1,369`
- [goyek/goyek](https://github.com/goyek/goyek) — Task automation Go library ☆`677`
- [flowexec/flow](https://github.com/flowexec/flow) — Local developer automation platform that flows with you ☆`131`
### CI/CD

- [harness/harness](https://github.com/harness/harness) — End-to-end developer platform ☆`33,874`
- [woodpecker-ci/woodpecker](https://github.com/woodpecker-ci/woodpecker) — Simple, powerful CI/CD engine ☆`6,474`
- [ovh/cds](https://github.com/ovh/cds) — Enterprise CI/CD platform ☆`4,799`
- [raviqqe/muffet](https://github.com/raviqqe/muffet) — Fast website link checker ☆`2,591`
- [pipe-cd/pipecd](https://github.com/pipe-cd/pipecd) — The One CD for All {applications, platforms, operations} ☆`1,250`
- [jenkins-zh/jenkins-cli](https://github.com/jenkins-zh/jenkins-cli) — Jenkins CLI allows you to manage your Jenkins in an easy way ☆`410`
- [vladopajic/go-test-coverage](https://github.com/vladopajic/go-test-coverage) — Report test coverage threshold issues ☆`216`
- [appleboy/drone-scp](https://github.com/appleboy/drone-scp) — Copy files via SSH for Drone ☆`166`
- [nikogura/gomason](https://github.com/nikogura/gomason) — A tool for testing, building, signing, and publishing binaries. ☆`66`
- [appleboy/drone-jenkins](https://github.com/appleboy/drone-jenkins) — Drone plugin for trigger Jenkins jobs. ☆`41`
- [opnlabs/dot](https://github.com/opnlabs/dot) — Minimal CI using Docker ☆`33`
- [gha-common/go-beautiful-html-coverage](https://github.com/gha-common/go-beautiful-html-coverage) — GitHub Action for code coverage reports ☆`20`
### Containers

- [moby/moby](https://github.com/moby/moby) — Container ecosystem components ☆`71,469`
- [traefik/traefik](https://github.com/traefik/traefik) — The Cloud Native Application Proxy ☆`61,637`
- [ko-build/ko](https://github.com/ko-build/ko) — Build and deploy Go applications ☆`8,339`
- [s0rg/decompose](https://github.com/s0rg/decompose) — Reverse-engineering tool for docker environments ☆`123`
- [x1unix/docker-go-mingw](https://github.com/x1unix/docker-go-mingw) — Docker for Go with MinGW toolchain ☆`53`
### DevOps Utilities

- [go-gitea/gitea](https://github.com/go-gitea/gitea) — Self-hosted Git service ☆`53,706`
- [moovweb/gvm](https://github.com/moovweb/gvm) — Go Version Manager ☆`11,535`
- [TwiN/gatus](https://github.com/TwiN/gatus) — Automated developer-oriented status page with alerting and incident support ☆`10,121`
- [bitfield/script](https://github.com/bitfield/script) — Making it easy to write shell-like scripts in Go ☆`6,932`
- [fleetdm/fleet](https://github.com/fleetdm/fleet) — Open device management ☆`6,039`
- [taubyte/tau](https://github.com/taubyte/tau) — Fullstack Workspace for Humans & Machines ☆`4,969`
- [megaease/easeprobe](https://github.com/megaease/easeprobe) — Service health monitoring tool ☆`2,294`
- [ajvb/kala](https://github.com/ajvb/kala) — Modern Job Scheduler ☆`2,162`
- [gabrie30/ghorg](https://github.com/gabrie30/ghorg) — Clone entire GitHub orgs ☆`1,972`
- [sanbornm/go-selfupdate](https://github.com/sanbornm/go-selfupdate) — Enable your Go applications to self update ☆`1,677`
- [yusufcanb/tlm](https://github.com/yusufcanb/tlm) — Local CLI Copilot, powered by Ollama. ☆`1,467`
- [ovh/utask](https://github.com/ovh/utask) — Automation engine with YAML config ☆`1,360`
- [TimothyYe/skm](https://github.com/TimothyYe/skm) — A simple and powerful SSH keys manager ☆`1,008`
- [scaleway/scaleway-cli](https://github.com/scaleway/scaleway-cli) — Command Line Interface for Scaleway ☆`955`
- [alexliesenfeld/health](https://github.com/alexliesenfeld/health) — A simple and flexible health check library for Go. ☆`828`
- [kool-dev/kool](https://github.com/kool-dev/kool) — Dev to cloud web apps made easy ☆`713`
- [kevincobain2000/gobrew](https://github.com/kevincobain2000/gobrew) — Go version manager without root ☆`411`
- [appleboy/easyssh-proxy](https://github.com/appleboy/easyssh-proxy) — Simple SSH protocol implementation ☆`345`
- [xitonix/trubka](https://github.com/xitonix/trubka) — A CLI tool for Kafka ☆`337`
- [emicklei/mora](https://github.com/emicklei/mora) — MongoDB generic REST server in Go ☆`316`
- [thevxn/dish](https://github.com/thevxn/dish) — A simple, remotely configurable monitoring service. ☆`275`
- [jkaninda/goma-gateway](https://github.com/jkaninda/goma-gateway) — Lightweight API gateway and proxy ☆`175`
- [datarootsio/tf-profile](https://github.com/datarootsio/tf-profile) — Profile Terraform runs ☆`162`
- [kazhuravlev/healthcheck](https://github.com/kazhuravlev/healthcheck) — Readiness probes for Kubernetes application ☆`21`
### Infrastructure

- [hashicorp/packer](https://github.com/hashicorp/packer) — Build machine images from config ☆`15,603`
- [pomerium/pomerium](https://github.com/pomerium/pomerium) — Pomerium is an identity and context-aware access proxy. ☆`4,672`
- [peak/s5cmd](https://github.com/peak/s5cmd) — Parallel S3 and local filesystem execution tool. ☆`3,909`
- [aptly-dev/aptly](https://github.com/aptly-dev/aptly) — aptly - Debian repository management tool ☆`2,768`
- [KusionStack/kusion](https://github.com/KusionStack/kusion) — Declarative platform orchestrator ☆`1,270`
- [oxyno-zeta/s3-proxy](https://github.com/oxyno-zeta/s3-proxy) — S3 reverse proxy with auth ☆`433`
### Kubernetes

- [kubernetes/kubernetes](https://github.com/kubernetes/kubernetes) — Production-Grade Container Scheduling and Management ☆`120,504`
- [k3s-io/k3s](https://github.com/k3s-io/k3s) — Lightweight Kubernetes ☆`32,180`
- [kubernetes/minikube](https://github.com/kubernetes/minikube) — Run Kubernetes locally ☆`31,488`
- [kubernetes-sigs/kind](https://github.com/kubernetes-sigs/kind) — Kubernetes IN Docker - local clusters for testing Kubernetes ☆`15,014`
- [kubeshark/kubeshark](https://github.com/kubeshark/kubeshark) — API traffic analyzer for Kubernetes ☆`11,773`
- [flannel-io/flannel](https://github.com/flannel-io/flannel) — Network fabric for containers ☆`9,403`
- [getanteon/anteon](https://github.com/getanteon/anteon) — eBPF Kubernetes monitoring tool ☆`8,544`
- [kubevela/kubevela](https://github.com/kubevela/kubevela) — The Modern Application Platform. ☆`7,686`
- [k3d-io/k3d](https://github.com/k3d-io/k3d) — Little helper to run CNCF's k3s in Docker ☆`6,256`
- [stefanprodan/podinfo](https://github.com/stefanprodan/podinfo) — Go microservice template for Kubernetes ☆`5,826`
- [apecloud/kubeblocks](https://github.com/apecloud/kubeblocks) — Kubernetes operator for databases ☆`2,980`
- [kubenetworks/kubevpn](https://github.com/kubenetworks/kubevpn) — Connect to Kubernetes cluster network ☆`1,293`
- [abahmed/kwatch](https://github.com/abahmed/kwatch) — monitor & detect crashes in your Kubernetes(K8s) cluster instantly ☆`994`
- [getanteon/alaz](https://github.com/getanteon/alaz) — eBPF agent for K8s observability ☆`716`
### Load Testing

- [grafana/k6](https://github.com/grafana/k6) — A modern load testing tool, using Go and JavaScript ☆`29,905`
- [tsenart/vegeta](https://github.com/tsenart/vegeta) — HTTP load testing tool and library. It's over 9000! ☆`24,900`
- [codesenberg/bombardier](https://github.com/codesenberg/bombardier) — Fast cross-platform HTTP benchmarking tool written in Go ☆`6,726`
- [rogerwelin/cassowary](https://github.com/rogerwelin/cassowary) — Modern cross-platform HTTP load-testing tool written in Go ☆`809`
## Email

- [axllent/mailpit](https://github.com/axllent/mailpit) — An email and SMTP testing tool with API for developers ☆`8,724`
- [foxcpp/maddy](https://github.com/foxcpp/maddy) — Composable all-in-one mail server. ☆`5,844`
- [mjl-/mox](https://github.com/mjl-/mox) — Modern secure mail server ☆`5,470`
- [matcornic/hermes](https://github.com/matcornic/hermes) — Clean HTML email generator ☆`3,045`
- [AfterShip/email-verifier](https://github.com/AfterShip/email-verifier) — Email verification without sending emails ☆`1,516`
- [wneessen/go-mail](https://github.com/wneessen/go-mail) — Easy to use, yet comprehensive library for sending mails with Go ☆`1,277`
- [sendgrid/sendgrid-go](https://github.com/sendgrid/sendgrid-go) — The Official Twilio SendGrid Golang API Library ☆`1,048`
- [mailgun/mailgun-go](https://github.com/mailgun/mailgun-go) — Go library for the Mailgun API. ☆`743`
- [xhit/go-simple-mail](https://github.com/xhit/go-simple-mail) — Simple mail sending with TLS/SSL ☆`693`
- [emersion/go-message](https://github.com/emersion/go-message) — Internet Message Format library ☆`438`
- [vanng822/go-premailer](https://github.com/vanng822/go-premailer) — Inline CSS for HTML mail ☆`187`
- [truemail-rb/truemail-go](https://github.com/truemail-rb/truemail-go) — Email validator via Regex, DNS, SMTP ☆`129`
- [toorop/go-dkim](https://github.com/toorop/go-dkim) — DKIM package for golang ☆`99`
- [dimuska139/go-email-normalizer](https://github.com/dimuska139/go-email-normalizer) — Normalize email addresses ☆`77`
- [valord577/mailx](https://github.com/valord577/mailx) — A library that makes it easier to send email via SMTP. ☆`20`
## Finance & Blockchain

### Blockchain

- [ethereum/go-ethereum](https://github.com/ethereum/go-ethereum) — Go implementation of the Ethereum protocol ☆`50,809`
- [ipfs/kubo](https://github.com/ipfs/kubo) — An IPFS implementation in Go ☆`16,907`
- [lightningnetwork/lnd](https://github.com/lightningnetwork/lnd) — Lightning Network Daemon ☆`8,108`
- [cosmos/cosmos-sdk](https://github.com/cosmos/cosmos-sdk) — A Framework for Building High Value Public Blockchains ☆`6,929`
- [gagliardetto/solana-go](https://github.com/gagliardetto/solana-go) — Go SDK library and RPC client for the Solana Blockchain ☆`1,508`
- [gnolang/gno](https://github.com/gnolang/gno) — Interpreted Go virtual machine ☆`1,052`
- [cometbft/cometbft](https://github.com/cometbft/cometbft) — Byzantine fault-tolerant consensus ☆`858`
- [ChainSafe/gossamer](https://github.com/ChainSafe/gossamer) — Go Implementation of the Polkadot Host ☆`455`
### Financial

- [shopspring/decimal](https://github.com/shopspring/decimal) — Arbitrary-precision fixed-point decimal numbers in Go ☆`7,234`
- [achannarasappa/ticker](https://github.com/achannarasappa/ticker) — Terminal stock and crypto tracker ☆`5,935`
- [Rhymond/go-money](https://github.com/Rhymond/go-money) — Go implementation of Fowler's Money pattern ☆`1,880`
- [c9s/bbgo](https://github.com/c9s/bbgo) — The modern cryptocurrency trading bot framework written in Go. ☆`1,599`
- [formancehq/ledger](https://github.com/formancehq/ledger) — The programmable open source core ledger for fintech ☆`1,144`
- [bojanz/currency](https://github.com/bojanz/currency) — Currency handling for Go. ☆`624`
- [moov-io/ach](https://github.com/moov-io/ach) — ACH file reader, writer, validator ☆`528`
- [invopop/gobl](https://github.com/invopop/gobl) — Go Business Language ☆`255`
- [govalues/decimal](https://github.com/govalues/decimal) — Correctly rounded decimals for Go ☆`222`
- [quagmt/udecimal](https://github.com/quagmt/udecimal) — High-precision decimal library ☆`171`
- [jovandeginste/payme](https://github.com/jovandeginste/payme) — QR code generator (ASCII & PNG) for SEPA payments ☆`89`
- [jokruger/dec128](https://github.com/jokruger/dec128) — High performance 128-bit fixed-point decimal numbers in go. ☆`41`
- [govalues/money](https://github.com/govalues/money) — Correctly rounded monetary amounts and exchange rates for Go ☆`48`
- [nikolaydubina/fpmoney](https://github.com/nikolaydubina/fpmoney) — Fixed-Point Decimal Money ☆`35`
- [nikolaydubina/fpdecimal](https://github.com/nikolaydubina/fpdecimal) — Fixed-Point Decimals ☆`34`
### Payment APIs

- [stripe/stripe-go](https://github.com/stripe/stripe-go) — Stripe API library for Go ☆`2,527`
- [plutov/paypal](https://github.com/plutov/paypal) — Golang client for PayPal REST API ☆`772`
- [brunomvsouza/ynab.go](https://github.com/brunomvsouza/ynab.go) — Client for YNAB API ☆`79`
## GUI & Desktop

### GUI

- [fyne-io/fyne](https://github.com/fyne-io/fyne) — Cross platform GUI toolkit in Go inspired by Material Design ☆`27,931`
- [webview/webview](https://github.com/webview/webview) — Tiny webview library for Go ☆`13,898`
- [therecipe/qt](https://github.com/therecipe/qt) — Qt bindings for Go ☆`10,785`
- [go-vgo/robotgo](https://github.com/go-vgo/robotgo) — Cross-platform RPA and GUI automation ☆`10,611`
- [maxence-charriere/go-app](https://github.com/maxence-charriere/go-app) — Build progressive web apps with Go and WASM ☆`8,858`
- [progrium/darwinkit](https://github.com/progrium/darwinkit) — Native Mac APIs for Go. Previously known as MacDriver ☆`5,396`
- [getlantern/systray](https://github.com/getlantern/systray) — Cross-platform systray library ☆`3,658`
- [cogentcore/core](https://github.com/cogentcore/core) — Powerful GUI framework for Go ☆`2,308`
- [gotk3/gotk3](https://github.com/gotk3/gotk3) — Go bindings for GTK3 ☆`2,202`
- [roblillack/spot](https://github.com/roblillack/spot) — React-like desktop GUI toolkit for Go ☆`1,258`
- [ncruces/zenity](https://github.com/ncruces/zenity) — Zenity dialogs for Golang, Windows, macOS ☆`893`
- [energye/energy](https://github.com/energye/energy) — CEF-based GUI framework ☆`575`
- [AllenDang/cimgui-go](https://github.com/AllenDang/cimgui-go) — Auto generated Go wrapper for Dear ImGui via cimgui ☆`493`
- [richardwilkes/unison](https://github.com/richardwilkes/unison) — Unified GUI toolkit for Go ☆`317`
### Windows

- [go-ole/go-ole](https://github.com/go-ole/go-ole) — win32 ole implementation for golang ☆`1,292`
- [gonutz/d3d9](https://github.com/gonutz/d3d9) — Direct3D9 wrapper for Go. ☆`163`
## Game Development

### Game Engines

- [hajimehoshi/ebiten](https://github.com/hajimehoshi/ebiten) — A dead simple 2D game engine for Go ☆`12,958`
- [fogleman/nes](https://github.com/fogleman/nes) — NES emulator written in Go. ☆`5,638`
- [topfreegames/pitaya](https://github.com/topfreegames/pitaya) — Game server with clustering support ☆`2,736`
- [xiaonanln/goworld](https://github.com/xiaonanln/goworld) — Distributed game server engine ☆`2,703`
- [gen2brain/raylib-go](https://github.com/gen2brain/raylib-go) — Go bindings for raylib ☆`2,355`
- [oakmound/oak](https://github.com/oakmound/oak) — A pure Go game engine ☆`1,652`
- [JoelOtter/termloop](https://github.com/JoelOtter/termloop) — Terminal-based game engine for Go, built on top of Termbox ☆`1,469`
- [gopxl/pixel](https://github.com/gopxl/pixel) — A hand-crafted 2D game library in Go. ☆`376`
- [ungerik/go3d](https://github.com/ungerik/go3d) — A performance oriented 2D/3D math package for Go ☆`338`
- [mlange-42/ark](https://github.com/mlange-42/ark) — Ark -- Archetype-based Entity Component System (ECS) for Go. ☆`215`
- [kelindar/tile](https://github.com/kelindar/tile) — 2D grid engine for games ☆`211`
- [andygeiss/ecs](https://github.com/andygeiss/ecs) — Entity Component System for games ☆`170`
- [gonutz/prototype](https://github.com/gonutz/prototype) — 2D game prototyping framework ☆`108`
- [s0rg/grid](https://github.com/s0rg/grid) — Generic 2D grid ☆`25`
- [s0rg/fantasyname](https://github.com/s0rg/fantasyname) — RinkWorks fantasy name generator for golang ☆`39`
### OpenGL

- [go-gl/glfw](https://github.com/go-gl/glfw) — Go bindings for GLFW 3 ☆`1,661`
- [go-gl/gl](https://github.com/go-gl/gl) — Go bindings for OpenGL (generated via glow) ☆`1,188`
- [go-gl/mathgl](https://github.com/go-gl/mathgl) — A pure Go 3D math library. ☆`596`
## Geospatial

- [tidwall/tile38](https://github.com/tidwall/tile38) — Real-time Geospatial and Geofencing ☆`9,577`
- [golang/geo](https://github.com/golang/geo) — S2 geometry library in Go ☆`1,818`
- [consbio/mbtileserver](https://github.com/consbio/mbtileserver) — MBTiles server in Go ☆`771`
- [spatial-go/geoos](https://github.com/spatial-go/geoos) — Spatial data and geometric algorithms ☆`532`
- [paulmach/osm](https://github.com/paulmach/osm) — OpenStreetMap data library ☆`443`
- [uber/h3-go](https://github.com/uber/h3-go) — H3 hexagonal geospatial indexing ☆`406`
- [airbusgeo/godal](https://github.com/airbusgeo/godal) — GDAL wrapper for Go ☆`173`
- [peterstace/simplefeatures](https://github.com/peterstace/simplefeatures) — OpenGIS Simple Feature implementation ☆`168`
- [wroge/wgs84](https://github.com/wroge/wgs84) — Zero-dep coordinate transformations ☆`140`
- [pantrif/s2-geojson](https://github.com/pantrif/s2-geojson) — Visualize S2 cells on a map ☆`36`
## Go Tooling

### Compilers

- [gopherjs/gopherjs](https://github.com/gopherjs/gopherjs) — A compiler from Go to JavaScript for running Go code in a browser ☆`13,124`
- [yassinebenaid/bunster](https://github.com/yassinebenaid/bunster) — Compile shell scripts to static binaries. ☆`2,643`
- [Konstantin8105/c4go](https://github.com/Konstantin8105/c4go) — Transpiling C code to Go code ☆`378`
- [go2hx/go2hx](https://github.com/go2hx/go2hx) — Import Go libraries in Haxe ☆`149`
### Editor Plugins

- [fatih/vim-go](https://github.com/fatih/vim-go) — Go development plugin for Vim ☆`16,238`
- [visualfc/liteide](https://github.com/visualfc/liteide) — LiteIDE is a simple, open source, cross-platform Go IDE. ☆`7,757`
- [nsf/gocode](https://github.com/nsf/gocode) — An autocompletion daemon for the Go programming language ☆`4,999`
- [golang/vscode-go](https://github.com/golang/vscode-go) — Go extension for Visual Studio Code ☆`4,202`
- [dominikh/go-mode.el](https://github.com/dominikh/go-mode.el) — Emacs mode for the Go programming language ☆`1,445`
- [incu6us/goimports-reviser](https://github.com/incu6us/goimports-reviser) — Imports sorting and code formatting tool ☆`711`
### Generate Tools

- [xuri/xgen](https://github.com/xuri/xgen) — XSD parser and code generator ☆`406`
- [kazhuravlev/options-gen](https://github.com/kazhuravlev/options-gen) — Codegen for functional options in go projects ☆`103`
- [g4s8/envdoc](https://github.com/g4s8/envdoc) — Go tool to generate documentation for environment variables ☆`94`
### Go Tools

- [go-swagger/go-swagger](https://github.com/go-swagger/go-swagger) — Swagger 2.0 implementation for go ☆`9,942`
- [ondrajz/go-callvis](https://github.com/ondrajz/go-callvis) — Visualize call graph of a Go program using Graphviz ☆`6,452`
- [Zxilly/go-size-analyzer](https://github.com/Zxilly/go-size-analyzer) — Analyze compiled Go binary size ☆`1,967`
- [pointlander/peg](https://github.com/pointlander/peg) — PEG parser generator for Go ☆`1,100`
- [janpfeifer/gonb](https://github.com/janpfeifer/gonb) — Go notebook kernel for Jupyter ☆`979`
- [safedep/vet](https://github.com/safedep/vet) — Protect against malicious open source packages ☆`948`
- [alajmo/sake](https://github.com/alajmo/sake) — Task runner for local and remote hosts ☆`743`
- [goccmack/gocc](https://github.com/goccmack/gocc) — Parser and scanner generator ☆`657`
- [moshebe/gebug](https://github.com/moshebe/gebug) — Debug Dockerized Go apps ☆`634`
- [edwingeng/hotswap](https://github.com/edwingeng/hotswap) — Hot reload Go code without restart ☆`421`
- [iyashjayesh/monigo](https://github.com/iyashjayesh/monigo) — Performance monitoring library ☆`397`
- [becheran/roumon](https://github.com/becheran/roumon) — Universal goroutine monitor using pprof and termui ☆`234`
- [bitfield/gotestdox](https://github.com/bitfield/gotestdox) — A tool for formatting Go test results as readable documentation ☆`192`
- [ahmedakef/gotutor](https://github.com/ahmedakef/gotutor) — Online Go Debugger & Visualizer ☆`74`
- [bobg/decouple](https://github.com/bobg/decouple) — find overspecified function parameters in Go code ☆`35`
- [bobg/modver](https://github.com/bobg/modver) — a tool that helps you obey semantic versioning rules in your Go module ☆`21`
- [dustinblackman/gomodrun](https://github.com/dustinblackman/gomodrun) — Run binaries from go.mod ☆`38`
## Hardware & IoT

### Hardware

- [shirou/gopsutil](https://github.com/shirou/gopsutil) — psutil for golang ☆`11,706`
- [arduino/arduino-cli](https://github.com/arduino/arduino-cli) — Arduino command line tool ☆`4,800`
- [jaypipes/ghw](https://github.com/jaypipes/ghw) — Go HardWare discovery/inspection library ☆`1,821`
- [zcalusic/sysinfo](https://github.com/zcalusic/sysinfo) — Linux system information library ☆`575`
### IoT

- [hybridgroup/gobot](https://github.com/hybridgroup/gobot) — Robotics and IoT framework ☆`9,379`
- [lf-edge/ekuiper](https://github.com/lf-edge/ekuiper) — Lightweight data stream processing engine for IoT edge ☆`1,678`
- [rulego/rulego](https://github.com/rulego/rulego) — Lightweight rule engine framework ☆`1,430`
- [Edgenesis/shifu](https://github.com/Edgenesis/shifu) — Kubernetes-native IoT gateway ☆`1,401`
- [e154/smart-home](https://github.com/e154/smart-home) — software package for automation ☆`96`
- [maxatome/go-vitotrol](https://github.com/maxatome/go-vitotrol) — golang client library to Viessmann Vitotrol web service ☆`23`
## Networking

### Consensus

- [hashicorp/raft](https://github.com/hashicorp/raft) — Golang implementation of the Raft consensus protocol ☆`8,923`
- [lni/dragonboat](https://github.com/lni/dragonboat) — Multi-group Raft consensus library ☆`5,298`
- [etcd-io/raft](https://github.com/etcd-io/raft) — Raft library for maintaining a replicated state machine ☆`986`
- [vadiminshakov/committer](https://github.com/vadiminshakov/committer) — 2PC and 3PC protocols for Go ☆`40`
### DNS

- [miekg/dns](https://github.com/miekg/dns) — DNS library in Go ☆`8,631`
- [0xERR0R/blocky](https://github.com/0xERR0R/blocky) — DNS ad-blocker for local networks ☆`6,106`
- [hashicorp/mdns](https://github.com/hashicorp/mdns) — Simple mDNS client/server library in Golang ☆`1,333`
- [semihalev/sdns](https://github.com/semihalev/sdns) — High-performance recursive DNS ☆`1,027`
- [mosajjal/dnsmonster](https://github.com/mosajjal/dnsmonster) — Passive DNS Capture and Monitoring Toolkit ☆`350`
- [joeig/go-powerdns](https://github.com/joeig/go-powerdns) — PowerDNS API client for Go (community project) ☆`103`
### Distributed Utilities

- [luraproject/lura](https://github.com/luraproject/lura) — Ultra-performant API gateway ☆`6,734`
- [chrislusf/gleam](https://github.com/chrislusf/gleam) — Distributed map/reduce in Go ☆`3,554`
- [bsm/redislock](https://github.com/bsm/redislock) — Simplified distributed locking implementation using Redis ☆`1,737`
- [k8gb-io/k8gb](https://github.com/k8gb-io/k8gb) — A cloud native Kubernetes Global Balancer ☆`1,145`
- [temporalio/sdk-go](https://github.com/temporalio/sdk-go) — Temporal Go SDK ☆`830`
- [AppsFlyer/go-sundheit](https://github.com/AppsFlyer/go-sundheit) — Health checks library for Go ☆`560`
- [tarmac-project/tarmac](https://github.com/tarmac-project/tarmac) — Functions as Monolith or Microservices ☆`342`
- [italolelis/outboxer](https://github.com/italolelis/outboxer) — A library that implements the outboxer pattern in go ☆`166`
- [capillariesio/capillaries](https://github.com/capillariesio/capillaries) — Distributed batch data processing framework ☆`69`
- [svcavallar/celeriac.v1](https://github.com/svcavallar/celeriac.v1) — Celery client for Go ☆`76`
- [sanketplus/go-mysql-lock](https://github.com/sanketplus/go-mysql-lock) — MySQL Backed Locking Primitive ☆`66`
- [pdupub/go-pdu](https://github.com/pdupub/go-pdu) — An PDU implementation in Go ☆`49`
- [mbrostami/consistenthash](https://github.com/mbrostami/consistenthash) — Consistent hashing implementation ☆`31`
### HTTP & Proxy

- [valyala/fasthttp](https://github.com/valyala/fasthttp) — Fast HTTP package for Go ☆`23,259`
- [elazarl/goproxy](https://github.com/elazarl/goproxy) — An HTTP proxy library for Go ☆`6,607`
- [eduardonunesp/sslb](https://github.com/eduardonunesp/sslb) — Simple load balancer ☆`151`
- [wzshiming/httpproxy](https://github.com/wzshiming/httpproxy) — HTTP proxy handler and dialer ☆`31`
### HTTP Clients

- [go-resty/resty](https://github.com/go-resty/resty) — Simple HTTP, REST, and SSE client library for Go ☆`11,537`
- [imroc/req](https://github.com/imroc/req) — Simple Go HTTP client with Black Magic ☆`4,759`
- [gojek/heimdall](https://github.com/gojek/heimdall) — An enhanced HTTP client for Go ☆`2,699`
- [hashicorp/go-retryablehttp](https://github.com/hashicorp/go-retryablehttp) — Retryable HTTP client in Go ☆`2,274`
- [levigross/grequests](https://github.com/levigross/grequests) — A Go "clone" of the great and famous Requests library ☆`2,184`
- [dghubble/sling](https://github.com/dghubble/sling) — A Go HTTP client library for creating and sending API requests ☆`1,717`
- [earthboundkid/requests](https://github.com/earthboundkid/requests) — HTTP requests for Gophers ☆`1,665`
- [bogdanfinn/tls-client](https://github.com/bogdanfinn/tls-client) — HTTP client with TLS fingerprint spoofing ☆`1,460`
- [Noooste/azuretls-client](https://github.com/Noooste/azuretls-client) — HTTP client to spoof TLS/JA3 fingerprint ☆`425`
- [monaco-io/request](https://github.com/monaco-io/request) — go request, go http client ☆`295`
- [opus-domini/fast-shot](https://github.com/opus-domini/fast-shot) — Fluent HTTP client for Go ☆`114`
- [go-zoox/fetch](https://github.com/go-zoox/fetch) — Powerful HTTP client for Go ☆`89`
- [NdoleStudio/go-otelroundtripper](https://github.com/NdoleStudio/go-otelroundtripper) — OpenTelemetry metrics for HTTP clients ☆`85`
- [rezmoss/axios4go](https://github.com/rezmoss/axios4go) — Axios-inspired HTTP client ☆`32`
### Servers

- [caddyserver/caddy](https://github.com/caddyserver/caddy) — Multi-platform web server with HTTPS ☆`69,978`
- [pocketbase/pocketbase](https://github.com/pocketbase/pocketbase) — Open Source realtime backend in 1 file ☆`56,097`
- [etcd-io/etcd](https://github.com/etcd-io/etcd) — Distributed key-value store ☆`51,511`
- [drakkan/sftpgo](https://github.com/drakkan/sftpgo) — Full-featured SFTP/FTP/HTTP server ☆`11,683`
- [adnanh/webhook](https://github.com/adnanh/webhook) — Lightweight webhook server ☆`11,587`
- [roadrunner-server/roadrunner](https://github.com/roadrunner-server/roadrunner) — High-performance PHP application server ☆`8,391`
- [easegress-io/easegress](https://github.com/easegress-io/easegress) — A Cloud Native traffic orchestration system ☆`5,866`
- [charmbracelet/wish](https://github.com/charmbracelet/wish) — Make SSH apps, just like that! ☆`4,900`
- [flipt-io/flipt](https://github.com/flipt-io/flipt) — Enterprise-ready, Git native feature management solution ☆`4,712`
- [getfider/fider](https://github.com/getfider/fider) — Open platform to collect and prioritize feedback ☆`4,092`
- [xyproto/algernon](https://github.com/xyproto/algernon) — Web server with Lua and Markdown ☆`2,986`
- [openflagr/flagr](https://github.com/openflagr/flagr) — Feature flagging and A/B testing ☆`2,573`
- [thomaspoignant/go-feature-flag](https://github.com/thomaspoignant/go-feature-flag) — Open source feature flag solution ☆`1,935`
- [msoap/shell2http](https://github.com/msoap/shell2http) — Executing shell commands via HTTP server ☆`1,471`
- [openrundev/openrun](https://github.com/openrundev/openrun) — Open source Cloud Run alternative ☆`772`
- [webhookx-io/webhookx](https://github.com/webhookx-io/webhookx) — The Next-Generation Webhooks Gateway. ☆`270`
- [baalimago/wd-41](https://github.com/baalimago/wd-41) — Web-Development 41, a static web server with live-reload ☆`151`
- [blind-oracle/cortex-tenant](https://github.com/blind-oracle/cortex-tenant) — Prometheus proxy with tenant ID injection ☆`132`
- [rekby/lets-proxy2](https://github.com/rekby/lets-proxy2) — Reverse proxy with auto TLS ☆`101`
- [42atomys/webhooked](https://github.com/42atomys/webhooked) — A webhook receiver on steroids. ☆`42`
### Network Utilities

- [fortio/fortio](https://github.com/fortio/fortio) — Load testing and echo server ☆`3,676`
- [hashicorp/go-getter](https://github.com/hashicorp/go-getter) — Download files from URLs ☆`1,805`
- [TimothyYe/godns](https://github.com/TimothyYe/godns) — Dynamic DNS client for multiple providers ☆`1,736`
- [cavaliergopher/grab](https://github.com/cavaliergopher/grab) — Download manager package ☆`1,471`
- [schollz/peerdiscovery](https://github.com/schollz/peerdiscovery) — Cross-platform local peer discovery ☆`668`
- [fclairamb/ftpserverlib](https://github.com/fclairamb/ftpserverlib) — FTP server library for Go ☆`462`
- [skibish/ddns](https://github.com/skibish/ddns) — Personal DDNS client with Digital Ocean Networking DNS as backend. ☆`267`
- [assafmo/joincap](https://github.com/assafmo/joincap) — Merge pcap files ☆`220`
- [c-robinson/iplib](https://github.com/c-robinson/iplib) — A library for working with IP addresses and networks in Go ☆`151`
- [gaissmai/bart](https://github.com/gaissmai/bart) — Balanced routing table ☆`117`
- [alegrey91/fwdctl](https://github.com/alegrey91/fwdctl) — Manage IPTables forwards via CLI ☆`72`
### P2P & Torrent

- [anacrolix/torrent](https://github.com/anacrolix/torrent) — Full-featured BitTorrent client package and utilities ☆`5,964`
- [dragonflyoss/dragonfly](https://github.com/dragonflyoss/dragonfly) — P2P-based container image distribution ☆`3,032`
- [cenkalti/rain](https://github.com/cenkalti/rain) — BitTorrent client and library in Go ☆`1,111`
- [anacrolix/dht](https://github.com/anacrolix/dht) — DHT for BitTorrent ☆`348`
### Protocols

- [pion/webrtc](https://github.com/pion/webrtc) — Pure Go implementation of the WebRTC API ☆`16,033`
- [quic-go/quic-go](https://github.com/quic-go/quic-go) — A production-ready QUIC implementation in pure Go ☆`11,425`
- [google/gopacket](https://github.com/google/gopacket) — Provides packet processing capabilities for Go ☆`6,743`
- [osrg/gobgp](https://github.com/osrg/gobgp) — BGP implemented in the Go Programming Language ☆`3,984`
- [lxzan/gws](https://github.com/lxzan/gws) — Fast websocket server and client ☆`1,704`
- [gosnmp/gosnmp](https://github.com/gosnmp/gosnmp) — An SNMP library written in Go ☆`1,239`
- [bluenviron/gortsplib](https://github.com/bluenviron/gortsplib) — RTSP client and server library for the Go programming language ☆`891`
- [ccding/go-stun](https://github.com/ccding/go-stun) — A go implementation of the STUN client (RFC 3489 and RFC 5389) ☆`718`
- [google/gnxi](https://github.com/google/gnxi) — gNXI Tools - gRPC Network Management/Operations Interface Tools ☆`283`
- [jeroenrinzema/psql-wire](https://github.com/jeroenrinzema/psql-wire) — PostgreSQL wire protocol for Go ☆`217`
- [jimlambrt/gldap](https://github.com/jimlambrt/gldap) — Build LDAP services w/ Go ☆`118`
- [soypat/natiu-mqtt](https://github.com/soypat/natiu-mqtt) — Extensible MQTT for embedded systems ☆`104`
### RPC

- [grpc/grpc-go](https://github.com/grpc/grpc-go) — The Go language implementation of gRPC. HTTP/2 based RPC ☆`22,783`
- [hprose/hprose-golang](https://github.com/hprose/hprose-golang) — Cross-language RPC for Go ☆`1,264`
- [lesismal/arpc](https://github.com/lesismal/arpc) — Two-way RPC with broadcast support ☆`1,089`
- [ybbus/jsonrpc](https://github.com/ybbus/jsonrpc) — A simple go implementation of json rpc 2.0 client over http ☆`369`
- [osamingo/jsonrpc](https://github.com/osamingo/jsonrpc) — The jsonrpc package helps implement of JSON-RPC 2.0 ☆`192`
### SSH & SFTP

- [gliderlabs/ssh](https://github.com/gliderlabs/ssh) — Easy SSH servers in Golang ☆`4,086`
- [pkg/sftp](https://github.com/pkg/sftp) — SFTP support for the go.crypto/ssh package ☆`1,634`
- [masterzen/winrm](https://github.com/masterzen/winrm) — Windows remote command library ☆`459`
### TCP/UDP Frameworks

- [panjf2000/gnet](https://github.com/panjf2000/gnet) — High-performance event-loop network ☆`11,085`
- [xtaci/kcp-go](https://github.com/xtaci/kcp-go) — A crypto-secure Reliable-UDP library for Golang with FEC support. ☆`4,491`
- [cloudwego/netpoll](https://github.com/cloudwego/netpoll) — High-performance I/O framework ☆`4,530`
- [lesismal/nbio](https://github.com/lesismal/nbio) — High-performance network library ☆`2,700`
- [xtaci/gaio](https://github.com/xtaci/gaio) — High-performance, minimalist async-io (proactor) networking for Golang. ☆`1,070`
- [cheng-zhongliang/event](https://github.com/cheng-zhongliang/event) — Simple I/O event notification library wirtten in Golang ☆`119`
- [fish-tennis/gnet](https://github.com/fish-tennis/gnet) — high performance net library for game server ☆`26`
### VPN & Tunneling

- [cloudflare/cloudflared](https://github.com/cloudflare/cloudflared) — Cloudflare Tunnel client ☆`13,042`
- [xjasonlyu/tun2socks](https://github.com/xjasonlyu/tun2socks) — TUN to SOCKS proxy ☆`4,900`
- [songgao/water](https://github.com/songgao/water) — A simple TUN/TAP library written in native Go. ☆`2,138`
- [NodePassProject/nodepass](https://github.com/NodePassProject/nodepass) — Secure TCP/UDP tunneling with TLS ☆`2,066`
## Queues & Pub/Sub

### Brokers

- [nats-io/nats-server](https://github.com/nats-io/nats-server) — High-performance NATS message server ☆`19,152`
- [emitter-io/emitter](https://github.com/emitter-io/emitter) — High-performance pub/sub broker ☆`4,000`
- [mochi-mqtt/server](https://github.com/mochi-mqtt/server) — Embeddable MQTT v5 broker ☆`1,787`
### Clients & Libraries

- [hibiken/asynq](https://github.com/hibiken/asynq) — Simple, reliable, and efficient distributed task queue in Go ☆`12,894`
- [IBM/sarama](https://github.com/IBM/sarama) — Sarama is a Go library for Apache Kafka. ☆`12,425`
- [centrifugal/centrifugo](https://github.com/centrifugal/centrifugo) — Scalable real-time messaging server ☆`9,957`
- [ThreeDotsLabs/watermill](https://github.com/ThreeDotsLabs/watermill) — Building event-driven applications the easy way in Go. ☆`9,524`
- [appleboy/gorush](https://github.com/appleboy/gorush) — A push notification server written in Go (Golang). ☆`8,690`
- [RichardKnop/machinery](https://github.com/RichardKnop/machinery) — Async task queue with message passing ☆`7,948`
- [nats-io/nats.go](https://github.com/nats-io/nats.go) — Golang client for NATS, the cloud native messaging system. ☆`6,438`
- [dunglas/mercure](https://github.com/dunglas/mercure) — Server-Sent Events hub ☆`5,181`
- [confluentinc/confluent-kafka-go](https://github.com/confluentinc/confluent-kafka-go) — Confluent's Apache Kafka Golang client ☆`5,104`
- [olahol/melody](https://github.com/olahol/melody) — Minimalist websocket framework for Go ☆`4,064`
- [sideshow/apns2](https://github.com/sideshow/apns2) — Apple Push Notification Service ☆`3,161`
- [lovoo/goka](https://github.com/lovoo/goka) — Kafka stream processing library ☆`2,507`
- [rabbitmq/amqp091-go](https://github.com/rabbitmq/amqp091-go) — An AMQP 0-9-1 Go client maintained by the RabbitMQ team ☆`1,969`
- [asaskevich/EventBus](https://github.com/asaskevich/EventBus) — [Go] Lightweight eventbus with async compatibility for Go ☆`1,959`
- [containrrr/shoutrrr](https://github.com/containrrr/shoutrrr) — Notification library for gophers and their furry friends. ☆`1,504`
- [pebbe/zmq4](https://github.com/pebbe/zmq4) — A Go interface to ZeroMQ version 4 ☆`1,246`
- [timbray/quamina](https://github.com/timbray/quamina) — Fast pattern-matching library ☆`476`
- [cskr/pubsub](https://github.com/cskr/pubsub) — A simple pubsub package for go. ☆`448`
- [jandelgado/rabtap](https://github.com/jandelgado/rabtap) — RabbitMQ wire tap and swiss army knife ☆`278`
- [mehdihadeli/Go-MediatR](https://github.com/mehdihadeli/Go-MediatR) — Mediator pattern for CQRS ☆`274`
- [goptics/varmq](https://github.com/goptics/varmq) — Zero-dep message queue library ☆`177`
- [hyperonym/ratus](https://github.com/hyperonym/ratus) — RESTful async task queue server ☆`124`
- [robinjoseph08/redisqueue](https://github.com/robinjoseph08/redisqueue) — Redis streams producer and consumer ☆`139`
- [oagudo/outbox](https://github.com/oagudo/outbox) — Transactional outbox pattern ☆`118`
- [furdarius/rabbitroutine](https://github.com/furdarius/rabbitroutine) — RabbitMQ auto-reconnect library ☆`114`
- [dailymotion/oplog](https://github.com/dailymotion/oplog) — A generic oplog/replication system for microservices ☆`110`
- [jirenius/go-res](https://github.com/jirenius/go-res) — RES Service protocol library for Go ☆`67`
- [Protocol-Lattice/GoEventBus](https://github.com/Protocol-Lattice/GoEventBus) — A lock-free, ultra-fast event bus for Go ☆`57`
- [SchwarzIT/hypermatch](https://github.com/SchwarzIT/hypermatch) — High-performance rule matching ☆`33`
## Science

- [gonum/gonum](https://github.com/gonum/gonum) — Numeric libraries for Go ☆`8,308`
- [gonum/plot](https://github.com/gonum/plot) — Plotting and visualization ☆`2,939`
- [paulmach/orb](https://github.com/paulmach/orb) — 2D geometry types and utilities ☆`1,087`
- [madelynnblue/go-dsp](https://github.com/madelynnblue/go-dsp) — Digital Signal Processing for Go ☆`907`
- [bebop/poly](https://github.com/bebop/poly) — Synthetic biology library for Go ☆`720`
- [hmdsefi/gograph](https://github.com/hmdsefi/gograph) — Generic graph algorithms library ☆`105`
- [nikolaydubina/jsonl-graph](https://github.com/nikolaydubina/jsonl-graph) — JSONL Graph Tools ☆`77`
- [claygod/PiHex](https://github.com/claygod/PiHex) — Generate hexadecimal Pi digits ☆`20`
## Scripting

### Embeddable Languages

- [php/frankenphp](https://github.com/php/frankenphp) — The modern PHP app server ☆`10,772`
- [expr-lang/expr](https://github.com/expr-lang/expr) — Expression evaluation for Go ☆`7,691`
- [yuin/gopher-lua](https://github.com/yuin/gopher-lua) — Lua VM and compiler in Go ☆`6,850`
- [dop251/goja](https://github.com/dop251/goja) — ECMAScript engine in pure Go ☆`6,740`
- [d5/tengo](https://github.com/d5/tengo) — Fast script language for Go ☆`3,774`
- [Shopify/go-lua](https://github.com/Shopify/go-lua) — Lua VM in Go ☆`3,414`
- [google/cel-go](https://github.com/google/cel-go) — Common Expression Language for Go ☆`2,867`
- [google/starlark-go](https://github.com/google/starlark-go) — Starlark config language in Go ☆`2,633`
- [metacall/core](https://github.com/metacall/core) — Polyglot programming runtime ☆`1,759`
- [wa-lang/wa](https://github.com/wa-lang/wa) — The Wa Programming Language ☆`1,753`
- [mattn/anko](https://github.com/mattn/anko) — Scriptable interpreter in Go ☆`1,558`
- [PaesslerAG/gval](https://github.com/PaesslerAG/gval) — Expression evaluation in Go ☆`810`
- [ichiban/prolog](https://github.com/ichiban/prolog) — Prolog scripting engine for Go ☆`706`
- [aarzilli/golua](https://github.com/aarzilli/golua) — Lua C API bindings for Go ☆`689`
- [1set/starlet](https://github.com/1set/starlet) — Starlark wrapper with batteries ☆`40`
### Code Generators

- [oapi-codegen/oapi-codegen](https://github.com/oapi-codegen/oapi-codegen) — Generate Go code from OpenAPI 3 specs ☆`8,062`
- [dave/jennifer](https://github.com/dave/jennifer) — Code generator for Go ☆`3,601`
- [hexdigest/gowrap](https://github.com/hexdigest/gowrap) — Generate interface decorators ☆`1,309`
- [awalterschulze/goderive](https://github.com/awalterschulze/goderive) — Generate mundane Go functions ☆`1,266`
- [abice/go-enum](https://github.com/abice/go-enum) — Enum generator for Go ☆`923`
- [jmattheis/goverter](https://github.com/jmattheis/goverter) — Generate type-safe converters ☆`813`
- [rjeczalik/interfaces](https://github.com/rjeczalik/interfaces) — Code generation tools for Go ☆`432`
- [switchupcb/copygen](https://github.com/switchupcb/copygen) — Copy values between types ☆`399`
- [reedom/convergen](https://github.com/reedom/convergen) — Type-to-type copy code generator ☆`48`
## Security

### Certificates

- [go-acme/lego](https://github.com/go-acme/lego) — Let's Encrypt/ACME client and library written in Go ☆`9,250`
- [caddyserver/certmagic](https://github.com/caddyserver/certmagic) — Automatic HTTPS certificate management ☆`5,439`
- [tg123/go-htpasswd](https://github.com/tg123/go-htpasswd) — Apache htpasswd Parser for Go. ☆`46`
- [adrianosela/sslmgr](https://github.com/adrianosela/sslmgr) — SSL certificate abstraction ☆`30`
### Cryptography

- [FiloSottile/age](https://github.com/FiloSottile/age) — Simple encryption tool ☆`21,308`
- [authzed/spicedb](https://github.com/authzed/spicedb) — Zanzibar-inspired permissions DB ☆`6,433`
- [awnumar/memguard](https://github.com/awnumar/memguard) — Software sandbox for storage of sensitive information in memory. ☆`2,713`
- [cossacklabs/themis](https://github.com/cossacklabs/themis) — Cryptographic framework for data protection ☆`1,949`
- [dromara/dongle](https://github.com/dromara/dongle) — A simple, semantic and developer-friendly crypto package for golang ☆`1,098`
- [anatol/booster](https://github.com/anatol/booster) — Fast and secure initramfs generator ☆`620`
- [kevinburke/nacl](https://github.com/kevinburke/nacl) — Pure Go implementation of the NaCL set of API's ☆`552`
- [ssh-vault/ssh-vault](https://github.com/ssh-vault/ssh-vault) — encrypt/decrypt using ssh keys ☆`494`
- [number571/go-peer](https://github.com/number571/go-peer) — Secure decentralized networking ☆`315`
- [lingrino/vaku](https://github.com/lingrino/vaku) — Extended Vault API and CLI ☆`158`
- [anatol/luks.go](https://github.com/anatol/luks.go) — Pure Golang library to manage LUKS partitions ☆`95`
- [zitadel/passwap](https://github.com/zitadel/passwap) — Unified password hashing ☆`72`
- [rsjethani/secret](https://github.com/rsjethani/secret) — Prevent your secrets from leaking into logs, std* etc. ☆`32`
- [andskur/argon2-hashing](https://github.com/andskur/argon2-hashing) — Argon2 password hashing ☆`25`
### WAF & Protection

- [Ullaakut/cameradar](https://github.com/Ullaakut/cameradar) — Cameradar hacks its way into RTSP videosurveillance cameras ☆`4,860`
- [corazawaf/coraza](https://github.com/corazawaf/coraza) — ModSecurity-compatible WAF in Go ☆`3,278`
- [mojocn/base64Captcha](https://github.com/mojocn/base64Captcha) — captcha of base64 image string ☆`2,345`
- [unrolled/secure](https://github.com/unrolled/secure) — HTTP middleware for Go that facilitates some quick security wins. ☆`2,334`
- [mariocandela/beelzebub](https://github.com/mariocandela/beelzebub) — AI-powered honeypot framework ☆`1,843`
- [cossacklabs/acra](https://github.com/cossacklabs/acra) — Database security proxy ☆`1,453`
- [securitybunker/databunker](https://github.com/securitybunker/databunker) — Secure vault for PII/PHI/KYC records ☆`1,384`
- [hillu/go-yara](https://github.com/hillu/go-yara) — Go bindings for YARA ☆`385`
- [teler-sh/teler-waf](https://github.com/teler-sh/teler-waf) — HTTP middleware for WAF ☆`399`
- [steambap/captcha](https://github.com/steambap/captcha) — Easy captcha library ☆`162`
### Zero Trust

- [sigstore/cosign](https://github.com/sigstore/cosign) — Code signing and transparency for containers and binaries ☆`5,651`
- [openziti/ziti](https://github.com/openziti/ziti) — Zero trust networking platform ☆`3,874`
- [spiffe/spire](https://github.com/spiffe/spire) — The SPIFFE Runtime Environment ☆`2,205`
- [philips-labs/spiffe-vault](https://github.com/philips-labs/spiffe-vault) — Integrates Spiffe and Vault to have secretless authentication ☆`97`
## Testing & Quality

### Benchmarks

- [smallnest/go-web-framework-benchmark](https://github.com/smallnest/go-web-framework-benchmark) — Web framework benchmarks ☆`2,137`
- [alecthomas/go_serialization_benchmarks](https://github.com/alecthomas/go_serialization_benchmarks) — Serialization benchmarks for Go ☆`1,621`
- [SimonWaldherr/golang-benchmarks](https://github.com/SimonWaldherr/golang-benchmarks) — Go(lang) benchmarks - (measure the speed of golang) ☆`142`
- [feyeleanor/gospeed](https://github.com/feyeleanor/gospeed) — Go language construct benchmarks ☆`126`
- [nikolaydubina/go-ml-benchmarks](https://github.com/nikolaydubina/go-ml-benchmarks) — Benchmarks of machine learning inference for Go ☆`32`
### Code Analysis

- [golangci/golangci-lint](https://github.com/golangci/golangci-lint) — Fast linters runner for Go ☆`18,498`
- [boyter/scc](https://github.com/boyter/scc) — Fast code counter and stats ☆`8,048`
- [mgechev/revive](https://github.com/mgechev/revive) — Fast, extensible Go linter ☆`5,396`
- [kisielk/errcheck](https://github.com/kisielk/errcheck) — errcheck checks that you checked errors. ☆`2,472`
- [go-critic/go-critic](https://github.com/go-critic/go-critic) — The most opinionated Go source code linter for code audit. ☆`2,035`
- [daveshanley/vacuum](https://github.com/daveshanley/vacuum) — Fast OpenAPI linter ☆`1,006`
- [presmihaylov/todocheck](https://github.com/presmihaylov/todocheck) — Analyser for TODO comments ☆`437`
- [mdempsky/unconvert](https://github.com/mdempsky/unconvert) — Remove unnecessary type conversions ☆`388`
- [tomarrell/wrapcheck](https://github.com/tomarrell/wrapcheck) — Check errors are wrapped ☆`358`
- [mibk/dupl](https://github.com/mibk/dupl) — Code clone detection tool ☆`363`
- [shurcooL/gostatus](https://github.com/shurcooL/gostatus) — Show status of Go repositories ☆`245`
- [Antonboom/testifylint](https://github.com/Antonboom/testifylint) — Linter for testify usage ☆`163`
- [Crocmagnon/fatcontext](https://github.com/Crocmagnon/fatcontext) — Detect nested contexts in loops ☆`66`
- [antham/ghokin](https://github.com/antham/ghokin) — Parallelized Gherkin formatter ☆`52`
- [asticode/go-astitodo](https://github.com/asticode/go-astitodo) — Parse TODOs in your GO code ☆`66`
- [sashamelentyev/usestdlibvars](https://github.com/sashamelentyev/usestdlibvars) — Linter for stdlib variables usage ☆`47`
- [borovikovd/gomsort](https://github.com/borovikovd/gomsort) — Go msort - linter that sorts methods ☆`26`
### Mock

- [vektra/mockery](https://github.com/vektra/mockery) — Mock code autogenerator for Go ☆`6,992`
- [DATA-DOG/go-sqlmock](https://github.com/DATA-DOG/go-sqlmock) — SQL mock driver for testing ☆`6,522`
- [brianvoe/gofakeit](https://github.com/brianvoe/gofakeit) — Random fake data generator written in go ☆`5,302`
- [uber-go/mock](https://github.com/uber-go/mock) — GoMock is a mocking framework for the Go programming language. ☆`3,259`
- [SpectoLabs/hoverfly](https://github.com/SpectoLabs/hoverfly) — API simulation and virtualization ☆`2,466`
- [matryer/moq](https://github.com/matryer/moq) — Interface mocking via go generate ☆`2,178`
- [jarcoal/httpmock](https://github.com/jarcoal/httpmock) — HTTP mocking for Go ☆`2,075`
- [maxbrunsfeld/counterfeiter](https://github.com/maxbrunsfeld/counterfeiter) — Generate type-safe test doubles ☆`1,118`
- [gojuno/minimock](https://github.com/gojuno/minimock) — Powerful mock generator ☆`746`
- [DATA-DOG/go-txdb](https://github.com/DATA-DOG/go-txdb) — Transaction-isolated SQL driver ☆`743`
- [pashagolub/pgxmock](https://github.com/pashagolub/pgxmock) — pgx mock driver for testing ☆`560`
- [xhd2015/xgo](https://github.com/xhd2015/xgo) — All-in-one Go testing library ☆`430`
- [seborama/govcr](https://github.com/seborama/govcr) — Record and replay HTTP interactions ☆`196`
- [mocktools/go-smtp-mock](https://github.com/mocktools/go-smtp-mock) — SMTP mock server for testing ☆`160`
- [elgohr/go-localstack](https://github.com/elgohr/go-localstack) — Go wrapper for LocalStack ☆`85`
### Performance

- [jaegertracing/jaeger](https://github.com/jaegertracing/jaeger) — Distributed tracing platform ☆`22,462`
- [pixie-io/pixie](https://github.com/pixie-io/pixie) — Kubernetes-native observability ☆`6,353`
- [arl/statsviz](https://github.com/arl/statsviz) — Visualize Go runtime metrics ☆`3,623`
- [nikolaydubina/go-instrument](https://github.com/nikolaydubina/go-instrument) — Add trace spans to Go functions ☆`288`
- [joetifa2003/mm-go](https://github.com/joetifa2003/mm-go) — Manual memory management for Go ☆`193`
### Browser Automation

- [chromedp/chromedp](https://github.com/chromedp/chromedp) — Chrome DevTools Protocol driver ☆`12,732`
- [go-rod/rod](https://github.com/go-rod/rod) — Chrome DevTools driver for scraping ☆`6,675`
- [sensepost/gowitness](https://github.com/sensepost/gowitness) — Web screenshot utility with Chrome ☆`4,167`
- [playwright-community/playwright-go](https://github.com/playwright-community/playwright-go) — Browser automation for Chromium, Firefox, WebKit ☆`3,192`
- [mafredri/cdp](https://github.com/mafredri/cdp) — Chrome DevTools Protocol bindings ☆`782`
### Testing Frameworks

- [stretchr/testify](https://github.com/stretchr/testify) — Assertions and mocks for testing ☆`25,778`
- [keploy/keploy](https://github.com/keploy/keploy) — API testing with auto mocks ☆`15,673`
- [Shopify/toxiproxy](https://github.com/Shopify/toxiproxy) — TCP proxy for chaos testing ☆`11,830`
- [testcontainers/testcontainers-go](https://github.com/testcontainers/testcontainers-go) — Docker containers for integration tests ☆`4,669`
- [google/go-cmp](https://github.com/google/go-cmp) — Package for comparing Go values in tests ☆`4,594`
- [gavv/httpexpect](https://github.com/gavv/httpexpect) — End-to-end HTTP and REST API testing for Go. ☆`2,711`
- [cucumber/godog](https://github.com/cucumber/godog) — Cucumber for golang ☆`2,590`
- [orlangure/gnomock](https://github.com/orlangure/gnomock) — Test with ephemeral Docker containers ☆`1,480`
- [dnaeon/go-vcr](https://github.com/dnaeon/go-vcr) — Record and replay HTTP for tests ☆`1,358`
- [go-testfixtures/testfixtures](https://github.com/go-testfixtures/testfixtures) — Rails-like test fixtures for Go ☆`1,220`
- [fergusstrange/embedded-postgres](https://github.com/fergusstrange/embedded-postgres) — Embedded PostgreSQL for testing ☆`1,123`
- [chapar-rest/chapar](https://github.com/chapar-rest/chapar) — API testing for HTTP and gRPC ☆`690`
- [gotestyourself/gotest.tools](https://github.com/gotestyourself/gotest.tools) — Testing utilities for Go ☆`577`
- [maxatome/go-testdeep](https://github.com/maxatome/go-testdeep) — Flexible deep comparison in tests ☆`457`
- [appleboy/gofight](https://github.com/appleboy/gofight) — Testing API Handler written in Golang. ☆`445`
- [viant/endly](https://github.com/viant/endly) — End to end functional test and automation framework ☆`266`
- [ysmood/got](https://github.com/ysmood/got) — An enjoyable golang test framework. ☆`269`
- [kinbiko/jsonassert](https://github.com/kinbiko/jsonassert) — JSON assertion library for tests ☆`140`
- [adamluzsi/testcase](https://github.com/adamluzsi/testcase) — Opinionated testing framework ☆`127`
- [earthboundkid/be](https://github.com/earthboundkid/be) — The Go test helper for minimalists ☆`131`
- [corbym/gocrest](https://github.com/corbym/gocrest) — GoCrest - Hamcrest-like matchers for Go ☆`106`
- [hedhyw/gherkingen](https://github.com/hedhyw/gherkingen) — Behaviour Driven Development tests generator for Golang ☆`94`
- [madflojo/testcerts](https://github.com/madflojo/testcerts) — Generate test certificates on the fly ☆`84`
- [viant/dsunit](https://github.com/viant/dsunit) — Datastore Testibility ☆`45`
- [go-restit/restit](https://github.com/go-restit/restit) — A Go library help testing your RESTful API application ☆`55`
- [rekby/fixenv](https://github.com/rekby/fixenv) — Pytest-inspired fixture caching for Go tests ☆`33`
- [abecodes/dft](https://github.com/abecodes/dft) — Docker wrapper for testing ☆`19`
### Testing Utilities

- [dvyukov/go-fuzz](https://github.com/dvyukov/go-fuzz) — Randomized testing for Go ☆`4,847`
- [pingcap/failpoint](https://github.com/pingcap/failpoint) — Failpoint implementation for Go ☆`873`
### Validation

- [go-playground/validator](https://github.com/go-playground/validator) — Struct and field validation for Go ☆`19,698`
- [gookit/validate](https://github.com/gookit/validate) — Struct and data validation ☆`1,126`
- [Oudwins/zog](https://github.com/Oudwins/zog) — Zod-inspired schema validation ☆`1,138`
- [faceair/jio](https://github.com/faceair/jio) — JSON schema validator like Joi ☆`125`
- [twharmon/govalid](https://github.com/twharmon/govalid) — Struct validation using tags ☆`112`
- [osamingo/checkdigit](https://github.com/osamingo/checkdigit) — Check digit algorithms ☆`114`
- [marrow16/valix](https://github.com/marrow16/valix) — Request validation package ☆`31`
- [tiendc/go-validator](https://github.com/tiendc/go-validator) — Intuitive validation library ☆`32`
## Text & NLP

### Formatters

- [dustin/go-humanize](https://github.com/dustin/go-humanize) — Human-friendly unit formatting ☆`4,802`
- [neilotoole/sq](https://github.com/neilotoole/sq) — SQL data wrangler ☆`2,432`
- [bojanz/address](https://github.com/bojanz/address) — Address handling for Go ☆`82`
### Markup Languages

- [BurntSushi/toml](https://github.com/BurntSushi/toml) — TOML parser with reflection ☆`4,897`
- [yuin/goldmark](https://github.com/yuin/goldmark) — Markdown parser for Go ☆`4,593`
- [JohannesKaufmann/html-to-markdown](https://github.com/JohannesKaufmann/html-to-markdown) — Convert HTML to Markdown ☆`3,413`
- [pelletier/go-toml](https://github.com/pelletier/go-toml) — TOML library for Go ☆`1,903`
- [antchfx/htmlquery](https://github.com/antchfx/htmlquery) — XPath for HTML queries ☆`781`
- [clbanning/mxj](https://github.com/clbanning/mxj) — XML to/from map conversion ☆`632`
- [mmalcek/bafi](https://github.com/mmalcek/bafi) — Universal format converter ☆`112`
- [drewstinnett/gout](https://github.com/drewstinnett/gout) — Output Go objects in YAML, JSON ☆`18`
### Miscellaneous

- [microcosm-cc/bluemonday](https://github.com/microcosm-cc/bluemonday) — Fast HTML sanitizer for Go ☆`3,622`
- [gosimple/slug](https://github.com/gosimple/slug) — URL-friendly slugify ☆`1,319`
- [pemistahl/lingua-go](https://github.com/pemistahl/lingua-go) — Natural language detection ☆`1,319`
- [arunsupe/semantic-grep](https://github.com/arunsupe/semantic-grep) — Grep for similar words ☆`1,209`
- [mattn/go-runewidth](https://github.com/mattn/go-runewidth) — Rune width for terminals ☆`676`
- [hedhyw/rex](https://github.com/hedhyw/rex) — Flexible regex constructor ☆`210`
- [IGLOU-EU/go-wildcard](https://github.com/IGLOU-EU/go-wildcard) — Fast wildcard matching ☆`99`
- [JoshuaDoes/gofuckyourself](https://github.com/JoshuaDoes/gofuckyourself) — Swear filter for Go ☆`68`
- [alexsergivan/transliterator](https://github.com/alexsergivan/transliterator) — Text transliterator ☆`46`
- [Dynom/TySug](https://github.com/Dynom/TySug) — Typo suggestions with keyboard layout ☆`19`
### Morphological Analyzers

- [nlpodyssey/spago](https://github.com/nlpodyssey/spago) — ML and NLP library for Go ☆`1,848`
- [ikawaha/kagome](https://github.com/ikawaha/kagome) — Japanese morphological analyzer ☆`943`
- [afjoseph/RAKE.Go](https://github.com/afjoseph/RAKE.Go) — Rapid Keyword Extraction in Go ☆`123`
- [jonreiter/govader](https://github.com/jonreiter/govader) — VADER sentiment analysis ☆`52`
### Parsers/Encoders/Decoders

- [mvdan/sh](https://github.com/mvdan/sh) — Shell parser and formatter ☆`8,460`
- [mmcdole/gofeed](https://github.com/mmcdole/gofeed) — Parse RSS, Atom, JSON feeds ☆`2,806`
- [google/go-querystring](https://github.com/google/go-querystring) — Encode structs to URL query strings ☆`2,132`
- [olebedev/when](https://github.com/olebedev/when) — Natural language date parser ☆`1,459`
- [adrianmo/go-nmea](https://github.com/adrianmo/go-nmea) — NMEA sentence parser ☆`257`
- [yassinebenaid/godump](https://github.com/yassinebenaid/godump) — Dump any Go variable ☆`224`
- [editorconfig/editorconfig-core-go](https://github.com/editorconfig/editorconfig-core-go) — EditorConfig core in Go ☆`151`
- [bzick/tokenizer](https://github.com/bzick/tokenizer) — Tokenizer/lexer for Go ☆`138`
- [emersion/go-vcard](https://github.com/emersion/go-vcard) — vCard parser and formatter ☆`123`
- [polera/gonameparts](https://github.com/polera/gonameparts) — Takes a full name and splits it into individual name parts ☆`43`
### Scrapers

- [gocolly/colly](https://github.com/gocolly/colly) — Web scraping framework for Go ☆`25,083`
- [PuerkitoBio/goquery](https://github.com/PuerkitoBio/goquery) — jQuery-like HTML manipulation ☆`14,900`
- [mvdan/xurls](https://github.com/mvdan/xurls) — Extract URLs from text ☆`1,247`
- [s0rg/crawley](https://github.com/s0rg/crawley) — The unix-way web crawler ☆`330`
- [zoomio/tagify](https://github.com/zoomio/tagify) — Extract tags from HTML/Markdown/text ☆`39`
### Text Analysis

- [blevesearch/bleve](https://github.com/blevesearch/bleve) — Text/numeric/geo/vector indexing library ☆`10,976`
- [derekparker/trie](https://github.com/derekparker/trie) — Trie for extremely fast prefix search ☆`788`
- [agnivade/levenshtein](https://github.com/agnivade/levenshtein) — Go implementation to calculate Levenshtein Distance. ☆`454`
- [plar/go-adaptive-radix-tree](https://github.com/plar/go-adaptive-radix-tree) — Adaptive Radix Trees implemented in Go ☆`411`
- [viant/ptrie](https://github.com/viant/ptrie) — A prefix tree implementation in go ☆`45`
### Tokenizers

- [go-ego/gse](https://github.com/go-ego/gse) — Multilingual text segmentation ☆`2,779`
- [pebbe/textcat](https://github.com/pebbe/textcat) — N-gram text categorization ☆`73`
### Translation

- [nicksnyder/go-i18n](https://github.com/nicksnyder/go-i18n) — Translate Go programs ☆`3,468`
- [leonelquinteros/gotext](https://github.com/leonelquinteros/gotext) — GNU gettext for Go ☆`490`
- [vorlif/spreak](https://github.com/vorlif/spreak) — Gettext-based translation library ☆`93`
- [invopop/ctxi18n](https://github.com/invopop/ctxi18n) — Context-based i18n for Go ☆`92`
- [mehanizm/iuliia-go](https://github.com/mehanizm/iuliia-go) — Cyrillic to Latin transliteration ☆`56`
- [youthlin/t](https://github.com/youthlin/t) — Translation util using gettext ☆`21`
## Third-party APIs

### Cloud Provider APIs

- [googleapis/google-cloud-go](https://github.com/googleapis/google-cloud-go) — Google Cloud Client Libraries for Go. ☆`4,416`
- [googleapis/google-api-go-client](https://github.com/googleapis/google-api-go-client) — Auto-generated Google APIs for Go. ☆`4,392`
- [aws/aws-sdk-go-v2](https://github.com/aws/aws-sdk-go-v2) — AWS SDK for the Go programming language. ☆`3,464`
- [minio/minio-go](https://github.com/minio/minio-go) — High-performance object storage ☆`2,903`
- [rhnvrm/simples3](https://github.com/rhnvrm/simples3) — Simple AWS S3 library using REST ☆`194`
- [chainifynet/aws-encryption-sdk-go](https://github.com/chainifynet/aws-encryption-sdk-go) — AWS Encryption SDK for Go ☆`22`
- [circa10a/go-aws-news](https://github.com/circa10a/go-aws-news) — Go app + library to fetch what's new from AWS ☆`18`
### Other APIs

- [codingsince1985/geo-golang](https://github.com/codingsince1985/geo-golang) — Go library to access geocoding and reverse geocoding APIs ☆`538`
- [cyruzin/golang-tmdb](https://github.com/cyruzin/golang-tmdb) — Wrapper for TMDb API ☆`155`
- [gregdel/pushover](https://github.com/gregdel/pushover) — Go wrapper for the Pushover API ☆`154`
- [mvrilo/go-redoc](https://github.com/mvrilo/go-redoc) — Embedded OpenAPI documentation ☆`94`
- [rapito/go-spotify](https://github.com/rapito/go-spotify) — Go library for the Spotify Web API ☆`50`
- [rinchsan/device-check-go](https://github.com/rinchsan/device-check-go) — iOS DeviceCheck SDK for Go ☆`25`
- [zc2638/swag](https://github.com/zc2638/swag) — Generate Swagger from code ☆`50`
- [staskobzar/goami2](https://github.com/staskobzar/goami2) — Simple Asterisk Manager Interface (AMI) library fo golang ☆`21`
- [sostronk/go-steam](https://github.com/sostronk/go-steam) — Go library for querying Source servers ☆`33`
- [Icelain/jokeapi](https://github.com/Icelain/jokeapi) — Official golang wrapper for Sv443's jokeapi. ☆`27`
### Productivity APIs

- [mk-5/fjira](https://github.com/mk-5/fjira) — The golang fuzzy-find cli jira interface ☆`254`
- [adlio/trello](https://github.com/adlio/trello) — Trello API wrapper for Go ☆`227`
- [ctreminiom/go-atlassian](https://github.com/ctreminiom/go-atlassian) — Atlassian Cloud API client ☆`194`
- [koltyakov/gosip](https://github.com/koltyakov/gosip) — SharePoint SDK for Go ☆`167`
- [FreeLeh/GoFreeDB](https://github.com/FreeLeh/GoFreeDB) — Database on top of Google Sheets ☆`90`
- [mehanizm/airtable](https://github.com/mehanizm/airtable) — Simple golang airtable API wrapper ☆`82`
- [k-capehart/go-salesforce](https://github.com/k-capehart/go-salesforce) — Salesforce REST API client ☆`53`
## Utilities

### Build & Release

- [goreleaser/goreleaser](https://github.com/goreleaser/goreleaser) — Release engineering simplified ☆`15,577`
- [create-go-app/cli](https://github.com/create-go-app/cli) — Create production-ready Go projects ☆`2,740`
- [miniscruff/changie](https://github.com/miniscruff/changie) — Automated changelog tool ☆`857`
- [jaschaephraim/lrserver](https://github.com/jaschaephraim/lrserver) — LiveReload server for Go [golang] ☆`129`
- [karl-cardenas-coding/go-lambda-cleanup](https://github.com/karl-cardenas-coding/go-lambda-cleanup) — Remove old AWS Lambda versions ☆`96`
### CLI Tools

- [junegunn/fzf](https://github.com/junegunn/fzf) — Command-line fuzzy finder ☆`77,783`
- [wagoodman/dive](https://github.com/wagoodman/dive) — Explore Docker image layers ☆`53,338`
- [xo/usql](https://github.com/xo/usql) — Universal SQL CLI ☆`9,813`
- [minio/mc](https://github.com/minio/mc) — Unix utilities for object stores ☆`3,379`
- [joshmedeski/sesh](https://github.com/joshmedeski/sesh) — Terminal session manager ☆`1,699`
- [itchyny/bed](https://github.com/itchyny/bed) — Binary editor in Go ☆`1,344`
- [owenthereal/upterm](https://github.com/owenthereal/upterm) — Instant terminal sharing ☆`1,121`
- [alajmo/mani](https://github.com/alajmo/mani) — CLI for managing repositories ☆`656`
- [Unrud/remote-touchpad](https://github.com/Unrud/remote-touchpad) — Control mouse/keyboard remotely ☆`644`
- [chenquan/diskusage](https://github.com/chenquan/diskusage) — Fast disk usage analyzer ☆`300`
- [reugn/wifiqr](https://github.com/reugn/wifiqr) — Generate Wi-Fi QR codes ☆`282`
- [hedhyw/json-log-viewer](https://github.com/hedhyw/json-log-viewer) — Interactive JSON log viewer ☆`215`
- [hrtsegv/gitcs](https://github.com/hrtsegv/gitcs) — Git contributions graph generator ☆`130`
- [antham/yogo](https://github.com/antham/yogo) — Check yopmail from CLI ☆`46`
### Data Conversion

- [samber/lo](https://github.com/samber/lo) — Lodash-style utilities for Go ☆`20,965`
- [duke-git/lancet](https://github.com/duke-git/lancet) — Comprehensive util library ☆`5,271`
- [darccio/mergo](https://github.com/darccio/mergo) — Merge Go structs and maps ☆`3,084`
- [goforj/godump](https://github.com/goforj/godump) — Pretty-printer for Go structs ☆`1,694`
- [gookit/filter](https://github.com/gookit/filter) — Data filtering and conversion ☆`151`
- [tiendc/gofn](https://github.com/tiendc/gofn) — High-performance generic functions ☆`51`
- [xorcare/pointer](https://github.com/xorcare/pointer) — Create optional field pointers ☆`48`
- [shockerli/cvt](https://github.com/shockerli/cvt) — Safe type conversion ☆`54`
### Database Extensions

- [jmoiron/sqlx](https://github.com/jmoiron/sqlx) — Extensions for database/sql ☆`17,505`
- [georgysavva/scany](https://github.com/georgysavva/scany) — Scan database rows to structs ☆`1,498`
- [blockloop/scan](https://github.com/blockloop/scan) — Scan SQL rows to structs ☆`610`
- [wroge/scan](https://github.com/wroge/scan) — Generic SQL row scanner ☆`68`
### Date and Time

- [dromara/carbon](https://github.com/dromara/carbon) — Developer-friendly time package ☆`5,222`
- [yaa110/go-persian-calendar](https://github.com/yaa110/go-persian-calendar) — Persian calendar for Go ☆`237`
- [bykof/gostradamus](https://github.com/bykof/gostradamus) — Better DateTimes for Go ☆`210`
- [nathan-osman/go-sunrise](https://github.com/nathan-osman/go-sunrise) — Calculate sunrise and sunset times ☆`172`
- [rickb777/date](https://github.com/rickb777/date) — Date handling package ☆`142`
- [relvacode/iso8601](https://github.com/relvacode/iso8601) — Fast ISO8601 date parser ☆`157`
### Dependency Injection

- [uber-go/fx](https://github.com/uber-go/fx) — DI-based application framework ☆`7,342`
- [uber-go/dig](https://github.com/uber-go/dig) — Reflection-based DI toolkit ☆`4,434`
- [goioc/di](https://github.com/goioc/di) — Simple DI for Go ☆`377`
- [go-kod/kod](https://github.com/go-kod/kod) — DI with aspect-oriented support ☆`195`
- [i-love-flamingo/dingo](https://github.com/i-love-flamingo/dingo) — DI framework for Go ☆`187`
- [junioryono/godi](https://github.com/junioryono/godi) — DI with service lifetimes ☆`68`
- [NVIDIA/gontainer](https://github.com/NVIDIA/gontainer) — Simple DI container ☆`64`
- [matzefriedrich/parsley](https://github.com/matzefriedrich/parsley) — Reflection-based DI package ☆`30`
- [muir/nject](https://github.com/muir/nject) — Type-safe DI for Go ☆`30`
- [logrange/linker](https://github.com/logrange/linker) — DI and IoC package ☆`35`
- [componego/componego](https://github.com/componego/componego) — Component-oriented framework ☆`28`
- [firasdarwish/ore](https://github.com/firasdarwish/ore) — Advanced DI solution ☆`24`
- [gontainer/gontainer](https://github.com/gontainer/gontainer) — YAML-based DI container ☆`16`
### Error Handling

- [hashicorp/go-multierror](https://github.com/hashicorp/go-multierror) — Represent multiple errors as one ☆`2,549`
- [cockroachdb/errors](https://github.com/cockroachdb/errors) — Error library with portability ☆`2,351`
- [rotisserie/eris](https://github.com/rotisserie/eris) — Errors with readable stack traces ☆`1,765`
- [joomcode/errorx](https://github.com/joomcode/errorx) — Comprehensive error handling ☆`1,270`
- [ztrue/tracerr](https://github.com/ztrue/tracerr) — Errors with stack trace ☆`1,104`
- [samber/oops](https://github.com/samber/oops) — Structured error handling ☆`856`
- [Southclaws/fault](https://github.com/Southclaws/fault) — Composable error wrapping ☆`308`
### File Handling

- [schollz/croc](https://github.com/schollz/croc) — Easily and securely send things from one computer to another ☆`34,158`
- [qax-os/excelize](https://github.com/qax-os/excelize) — Excel XLSX library for Go ☆`20,291`
- [pdfcpu/pdfcpu](https://github.com/pdfcpu/pdfcpu) — PDF processor in Go ☆`8,467`
- [spf13/afero](https://github.com/spf13/afero) — Filesystem abstraction for Go ☆`6,557`
- [dundee/gdu](https://github.com/dundee/gdu) — Fast disk usage analyzer ☆`5,311`
- [unidoc/unioffice](https://github.com/unidoc/unioffice) — Office document library ☆`4,806`
- [SpatiumPortae/portal](https://github.com/SpatiumPortae/portal) — Command-line file transfer utility ☆`1,746`
- [root-gg/plik](https://github.com/root-gg/plik) — Temporary file upload system ☆`1,693`
- [SebastiaanKlippert/go-wkhtmltopdf](https://github.com/SebastiaanKlippert/go-wkhtmltopdf) — HTML to PDF wrapper ☆`1,177`
- [otiai10/copy](https://github.com/otiai10/copy) — Copy directories recursively ☆`769`
- [ulikunitz/xz](https://github.com/ulikunitz/xz) — Pure golang package for reading and writing xz-compressed files ☆`549`
- [no-src/gofs](https://github.com/no-src/gofs) — Cross-platform file sync ☆`526`
- [viant/afs](https://github.com/viant/afs) — Abstract file storage ☆`374`
- [mholt/archives](https://github.com/mholt/archives) — Create and extract archives ☆`371`
- [C2FO/vfs](https://github.com/C2FO/vfs) — Virtual file system for Go ☆`356`
- [gen2brain/go-unarr](https://github.com/gen2brain/go-unarr) — Decompression library bindings ☆`305`
- [barasher/go-exiftool](https://github.com/barasher/go-exiftool) — Exiftool wrapper for metadata ☆`293`
- [gomutex/godocx](https://github.com/gomutex/godocx) — Go library for reading and writing Microsoft Docx ☆`238`
- [charlievieth/fastwalk](https://github.com/charlievieth/fastwalk) — Fast directory traversal ☆`117`
- [artonge/go-csv-tag](https://github.com/artonge/go-csv-tag) — CSV reading with tags ☆`129`
- [parsyl/parquet](https://github.com/parsyl/parquet) — Parquet file library ☆`127`
- [adelowo/gulter](https://github.com/adelowo/gulter) — Multipart form handling ☆`68`
- [go-the-way/exl](https://github.com/go-the-way/exl) — Excel binding to struct written in Go.(Only supports Go1.18+) ☆`32`
### Forms

- [justinas/nosurf](https://github.com/justinas/nosurf) — CSRF protection middleware ☆`1,726`
- [gorilla/csrf](https://github.com/gorilla/csrf) — CSRF prevention middleware ☆`1,178`
- [go-playground/form](https://github.com/go-playground/form) — URL values to structs ☆`902`
- [ggicci/httpin](https://github.com/ggicci/httpin) — HTTP request to struct binding ☆`382`
- [sonh/qs](https://github.com/sonh/qs) — Encode structs to query params ☆`80`
- [cinar/checker](https://github.com/cinar/checker) — Input validation with struct tags ☆`47`
### Functional

- [samber/mo](https://github.com/samber/mo) — Monads and FP for Go ☆`3,287`
- [BooleanCat/go-functional](https://github.com/BooleanCat/go-functional) — Iterator library for Go ☆`526`
- [seborama/fuego](https://github.com/seborama/fuego) — Functional programming in Go ☆`146`
- [rjNemo/underscore](https://github.com/rjNemo/underscore) — Functional helpers for Go ☆`118`
### General

- [wabarc/wayback](https://github.com/wabarc/wayback) — Web archiving tool with IM interface ☆`2,140`
- [gabriel-vasile/mimetype](https://github.com/gabriel-vasile/mimetype) — MIME type detection by magic numbers ☆`1,950`
- [qmuntal/stateless](https://github.com/qmuntal/stateless) — Go library for creating finite state machines ☆`1,207`
- [jonboulle/clockwork](https://github.com/jonboulle/clockwork) — a fake clock for golang ☆`723`
- [Boeing/config-file-validator](https://github.com/Boeing/config-file-validator) — Cross Platform tool to validate configuration files ☆`495`
- [biter777/countries](https://github.com/biter777/countries) — ISO country codes library ☆`501`
- [ungerik/go-dry](https://github.com/ungerik/go-dry) — DRY (don't repeat yourself) package for Go ☆`488`
- [subosito/gotenv](https://github.com/subosito/gotenv) — Load environment variables from `.env` or `io.Reader` in Go. ☆`306`
- [viant/toolbox](https://github.com/viant/toolbox) — Toolbox - go utility library ☆`227`
- [ikeikeikeike/go-sitemap-generator](https://github.com/ikeikeikeike/go-sitemap-generator) — Generate XML sitemaps ☆`229`
- [maja42/goval](https://github.com/maja42/goval) — Expression evaluation in golang ☆`173`
- [commander-cli/cmd](https://github.com/commander-cli/cmd) — A simple package to execute shell commands on linux, windows and osx ☆`160`
- [tiendc/go-deepcopy](https://github.com/tiendc/go-deepcopy) — Fast deep-copy library for Go ☆`125`
- [jfcg/sorty](https://github.com/jfcg/sorty) — Fast Concurrent / Parallel Sorting in Go ☆`144`
- [syntaqx/cookie](https://github.com/syntaqx/cookie) — Cookies, but with structs, for happiness. ☆`112`
- [pioz/countries](https://github.com/pioz/countries) — All you need when you are working with countries in Go. ☆`95`
- [arthurkushman/pgo](https://github.com/arthurkushman/pgo) — Go library for PHP community with convenient functions ☆`88`
- [wzshiming/gotype](https://github.com/wzshiming/gotype) — Golang source code parsing, usage like reflect package ☆`64`
- [rkoesters/xdg](https://github.com/rkoesters/xdg) — FreeDesktop.org (xdg) Specs implemented in Go ☆`48`
- [icza/backscanner](https://github.com/icza/backscanner) — Scan file lines backward ☆`69`
- [mikekonan/go-types](https://github.com/mikekonan/go-types) — OpenAPI3 types for Go ☆`23`
- [ik5/gostrutils](https://github.com/ik5/gostrutils) — Collections of string utils I have created over the years ☆`47`
- [osamingo/gosh](https://github.com/osamingo/gosh) — Provide Go Statistics Handler, Struct, Measure Method ☆`36`
- [kazhuravlev/just](https://github.com/kazhuravlev/just) — Collection of useful functions. Complete simple tasks faster! ☆`35`
- [lrita/numa](https://github.com/lrita/numa) — NUMA utility library for Go ☆`38`
- [floatdrop/debounce](https://github.com/floatdrop/debounce) — A zero-allocation debouncer ☆`34`
- [skovtunenko/graterm](https://github.com/skovtunenko/graterm) — Graceful termination primitives ☆`30`
- [nikolaydubina/watchhttp](https://github.com/nikolaydubina/watchhttp) — Expose command output via HTTP ☆`34`
### Logging

- [sirupsen/logrus](https://github.com/sirupsen/logrus) — Structured, pluggable logging for Go. ☆`25,690`
- [uber-go/zap](https://github.com/uber-go/zap) — Fast structured logging ☆`24,239`
- [rs/zerolog](https://github.com/rs/zerolog) — Zero allocation JSON logger ☆`12,211`
- [davecgh/go-spew](https://github.com/davecgh/go-spew) — Deep pretty printer for debugging ☆`6,369`
- [golang/glog](https://github.com/golang/glog) — Leveled execution logs ☆`3,615`
- [k0kubun/pp](https://github.com/k0kubun/pp) — Colored pretty printer for Go ☆`2,031`
- [lmittmann/tint](https://github.com/lmittmann/tint) — Colorized slog handler ☆`1,230`
- [Lifailon/lazyjournal](https://github.com/Lifailon/lazyjournal) — TUI for journald, Docker, K8s logs ☆`1,112`
- [getsentry/sentry-go](https://github.com/getsentry/sentry-go) — Official Sentry SDK for Go ☆`1,041`
- [phuslu/log](https://github.com/phuslu/log) — Fastest structured logging ☆`834`
- [samber/slog-multi](https://github.com/samber/slog-multi) — Workflow design for slog handlers ☆`609`
- [gookit/slog](https://github.com/gookit/slog) — Configurable logging library ☆`534`
- [henvic/httpretty](https://github.com/henvic/httpretty) — Pretty-print HTTP requests ☆`413`
- [simukti/sqldb-logger](https://github.com/simukti/sqldb-logger) — SQL database logger ☆`382`
- [hashicorp/logutils](https://github.com/hashicorp/logutils) — Logging utilities for Go ☆`371`
- [samber/slog-formatter](https://github.com/samber/slog-formatter) — Slog attribute formatting ☆`212`
- [DeRuina/timberjack](https://github.com/DeRuina/timberjack) — Log rolling library ☆`116`
- [rs/xlog](https://github.com/rs/xlog) — Context-aware HTTP logger ☆`141`
- [yuseferi/zax](https://github.com/yuseferi/zax) — Zap logger with context ☆`33`
- [clok/kemba](https://github.com/clok/kemba) — Tiny debug logging tool ☆`17`
### Networking Utils

- [cristianoliveira/ergo](https://github.com/cristianoliveira/ergo) — Manage apps on different ports ☆`649`
- [htcat/htcat](https://github.com/htcat/htcat) — Parallel HTTP download ☆`559`
- [ferama/rospo](https://github.com/ferama/rospo) — Persistent SSH tunnels ☆`358`
### Project Layout

- [golang-standards/project-layout](https://github.com/golang-standards/project-layout) — Standard Go project layout ☆`55,367`
- [Melkeydev/go-blueprint](https://github.com/Melkeydev/go-blueprint) — Spin up Go projects with popular frameworks ☆`8,644`
- [ardanlabs/service](https://github.com/ardanlabs/service) — K8s service starter kit ☆`3,937`
- [Shpota/goxygen](https://github.com/Shpota/goxygen) — Generate full-stack web projects ☆`3,602`
- [mikestefanello/pagoda](https://github.com/mikestefanello/pagoda) — Full-stack web development starter kit ☆`2,907`
- [go-nunu/nunu](https://github.com/go-nunu/nunu) — CLI for building Go apps ☆`2,544`
- [sagikazarmark/modern-go-application](https://github.com/sagikazarmark/modern-go-application) — Modern Go app example ☆`1,936`
- [naughtygopher/goapp](https://github.com/naughtygopher/goapp) — Opinionated web app structure ☆`1,050`
- [allaboutapps/go-starter](https://github.com/allaboutapps/go-starter) — Production-ready RESTful API template ☆`595`
- [golang-templates/seed](https://github.com/golang-templates/seed) — Go app GitHub template ☆`554`
- [raeperd/kickstart.go](https://github.com/raeperd/kickstart.go) — Minimal HTTP server template ☆`104`
- [wangyoucao577/go-project-layout](https://github.com/wangyoucao577/go-project-layout) — Go project structure guide ☆`26`
### Resilience & Retry

- [avast/retry-go](https://github.com/avast/retry-go) — Simple retry mechanism ☆`2,884`
- [eapache/go-resiliency](https://github.com/eapache/go-resiliency) — Resiliency patterns for golang ☆`2,336`
- [failsafe-go/failsafe-go](https://github.com/failsafe-go/failsafe-go) — Fault tolerance patterns ☆`2,140`
- [rubyist/circuitbreaker](https://github.com/rubyist/circuitbreaker) — Circuit breakers in Go ☆`1,164`
- [cep21/circuit](https://github.com/cep21/circuit) — Hystrix-like circuit breaker ☆`798`
- [mennanov/limiters](https://github.com/mennanov/limiters) — Distributed rate limiters ☆`620`
- [kamilsk/retry](https://github.com/kamilsk/retry) — Advanced retry mechanism ☆`346`
- [webriots/rate](https://github.com/webriots/rate) — High-performance rate limiter ☆`166`
- [reugn/equalizer](https://github.com/reugn/equalizer) — Performant rate limiters ☆`90`
### Strings

- [huandu/xstrings](https://github.com/huandu/xstrings) — String functions from other langs ☆`1,417`
- [abhimanyu003/sttr](https://github.com/abhimanyu003/sttr) — CLI string operations ☆`1,289`
- [gobeam/stringy](https://github.com/gobeam/stringy) — String case conversions ☆`251`
- [ozgio/strutil](https://github.com/ozgio/strutil) — String utilities for Go ☆`207`
### System & Process

- [cilium/ebpf](https://github.com/cilium/ebpf) — eBPF library for Go ☆`7,521`
- [maruel/panicparse](https://github.com/maruel/panicparse) — Crash your app in style ☆`3,714`
- [immortal/immortal](https://github.com/immortal/immortal) — Cross-platform supervisor ☆`832`
- [derekparker/delve](https://github.com/derekparker/delve) — Delve is a debugger for the Go programming language. ☆`662`
- [gotranspile/cxgo](https://github.com/gotranspile/cxgo) — Transpile C to Go ☆`387`
### UUID

- [google/uuid](https://github.com/google/uuid) — UUID generation and parsing ☆`5,988`
- [oklog/ulid](https://github.com/oklog/ulid) — ULID implementation ☆`4,983`
- [gofrs/uuid](https://github.com/gofrs/uuid) — UUID library for Go ☆`1,764`
- [osamingo/indigo](https://github.com/osamingo/indigo) — Sonyflake-based ID generator ☆`112`
- [sdrapkin/guid](https://github.com/sdrapkin/guid) — Fast cryptographically safe Guid generator for Go ☆`73`
- [twharmon/gouid](https://github.com/twharmon/gouid) — Fast, dependable universally unique ids ☆`26`
## Version Control & Packages

### Git APIs

- [google/go-github](https://github.com/google/go-github) — Go library for accessing the GitHub v3 API ☆`11,132`
- [shurcooL/githubv4](https://github.com/shurcooL/githubv4) — GitHub GraphQL API v4 client ☆`1,183`
- [go-playground/webhooks](https://github.com/go-playground/webhooks) — Webhook receiver for GitHub, Bitbucket, GitLab, Gogs ☆`1,027`
- [andygrunwald/go-trending](https://github.com/andygrunwald/go-trending) — Access GitHub trending repositories ☆`146`
- [andygrunwald/go-gerrit](https://github.com/andygrunwald/go-gerrit) — Go client/library for Gerrit Code Review ☆`104`
### Package Management

- [anchore/syft](https://github.com/anchore/syft) — SBOM generator for containers ☆`8,377`
- [nao1215/gup](https://github.com/nao1215/gup) — gup - Update binaries installed by "go install" with goroutines. ☆`538`
- [marwanhawari/stew](https://github.com/marwanhawari/stew) — An independent package manager for compiled binaries. ☆`329`
- [chaindead/modup](https://github.com/chaindead/modup) — TUI for Go dependency updates ☆`63`
### Version Control

- [go-git/go-git](https://github.com/go-git/go-git) — Pure Go Git implementation ☆`7,196`
- [antham/chyle](https://github.com/antham/chyle) — Changelog generator from Git ☆`159`
- [gabyx/Githooks](https://github.com/gabyx/Githooks) — Per-repo shared Git hooks ☆`120`
- [antham/gommit](https://github.com/antham/gommit) — Enforce git message commit consistency ☆`115`
- [jfrog/froggit-go](https://github.com/jfrog/froggit-go) — Universal VCS client library ☆`52`
- [kazhuravlev/git-tools](https://github.com/kazhuravlev/git-tools) — Useful set of tools which helps to manage git tags ☆`29`
## Web Development

### Microservices

- [zeromicro/go-zero](https://github.com/zeromicro/go-zero) — Microservices framework with CLI tools ☆`32,627`
- [go-kit/kit](https://github.com/go-kit/kit) — A standard library for microservices. ☆`27,608`
- [go-kratos/kratos](https://github.com/go-kratos/kratos) — Your ultimate Go microservices framework for the cloud-native era. ☆`25,445`
- [micro/go-micro](https://github.com/micro/go-micro) — A Go microservices framework ☆`22,698`
- [smallnest/rpcx](https://github.com/smallnest/rpcx) — Feature-rich RPC framework ☆`8,278`
- [cloudwego/kitex](https://github.com/cloudwego/kitex) — High-performance Go RPC framework ☆`7,861`
- [go-dev-frame/sponge](https://github.com/go-dev-frame/sponge) — Code generation framework for Go ☆`2,792`
- [go-eagle/eagle](https://github.com/go-eagle/eagle) — A Go framework for the API or Microservice ☆`2,416`
- [unionj-cloud/go-doudou](https://github.com/unionj-cloud/go-doudou) — OpenAPI 3 and gRPC microservices framework ☆`1,206`
- [trpc-group/trpc-go](https://github.com/trpc-group/trpc-go) — A pluggable, high-performance RPC framework written in golang ☆`1,116`
- [gmsec/micro](https://github.com/gmsec/micro) — A Go distributed systems development framework ☆`25`
### Middlewares

- [urfave/negroni](https://github.com/urfave/negroni) — Idiomatic HTTP Middleware for Golang ☆`7,543`
- [tdewolff/minify](https://github.com/tdewolff/minify) — Go minifiers for web formats ☆`4,063`
- [justinas/alice](https://github.com/justinas/alice) — Painless middleware chaining for Go ☆`3,352`
- [rs/cors](https://github.com/rs/cors) — Go net/http configurable handler to handle CORS requests ☆`2,860`
- [didip/tollbooth](https://github.com/didip/tollbooth) — Simple middleware to rate-limit HTTP requests. ☆`2,856`
- [unrolled/render](https://github.com/unrolled/render) — Render JSON, XML, HTML, binary ☆`1,991`
- [lingrino/go-fault](https://github.com/lingrino/go-fault) — go fault injection library ☆`512`
- [jub0bs/cors](https://github.com/jub0bs/cors) — perhaps the best CORS middleware library for Go ☆`174`
- [rookie-ninja/rk-gin](https://github.com/rookie-ninja/rk-gin) — Start gin microservice from YAML, plugin of rk-boot ☆`51`
- [faabiosr/echo-middleware](https://github.com/faabiosr/echo-middleware) — Middlewares for Echo framework ☆`16`
### Routers

- [gorilla/mux](https://github.com/gorilla/mux) — Powerful HTTP router ☆`21,795`
- [go-chi/chi](https://github.com/go-chi/chi) — Lightweight idiomatic HTTP router ☆`21,586`
- [gowww/router](https://github.com/gowww/router) — A lightning fast HTTP router ☆`186`
- [gernest/alien](https://github.com/gernest/alien) — A lightweight and fast http router from outer space ☆`134`
- [ngamux/ngamux](https://github.com/ngamux/ngamux) — Simple HTTP router for Go ☆`70`
- [bmf-san/goblin](https://github.com/bmf-san/goblin) — A golang http router based on trie tree. ☆`81`
- [muir/nchi](https://github.com/muir/nchi) — golang http router with elegance, speed, and flexibility ☆`18`
### Template Engines

- [a-h/templ](https://github.com/a-h/templ) — A language for writing HTML user interfaces in Go. ☆`10,071`
- [valyala/quicktemplate](https://github.com/valyala/quicktemplate) — Fast template engine for Go ☆`3,295`
- [johnfercher/maroto](https://github.com/johnfercher/maroto) — Create PDFs with Bootstrap grid ☆`2,639`
- [CloudyKit/jet](https://github.com/CloudyKit/jet) — Jet template engine ☆`1,383`
- [osteele/liquid](https://github.com/osteele/liquid) — A Liquid template engine in Go ☆`339`
- [go-sprout/sprout](https://github.com/go-sprout/sprout) — Template functions for Go ☆`210`
- [robfig/soy](https://github.com/robfig/soy) — Go implementation for Soy templates (Google Closure templates) ☆`177`
- [goradd/got](https://github.com/goradd/got) — Template engine with Go code output ☆`38`
### Web Frameworks

- [gin-gonic/gin](https://github.com/gin-gonic/gin) — High-performance HTTP framework ☆`87,998`
- [gofiber/fiber](https://github.com/gofiber/fiber) — Express inspired web framework written in Go ☆`39,218`
- [beego/beego](https://github.com/beego/beego) — High-performance web framework ☆`32,418`
- [labstack/echo](https://github.com/labstack/echo) — High performance, minimalist Go web framework ☆`32,156`
- [gofr-dev/gofr](https://github.com/gofr-dev/gofr) — Microservice framework for Go ☆`15,966`
- [gogf/gf](https://github.com/gogf/gf) — Powerful full-stack framework ☆`13,032`
- [cloudwego/hertz](https://github.com/cloudwego/hertz) — High-performance HTTP framework ☆`7,090`
- [goadesign/goa](https://github.com/goadesign/goa) — Design-first API framework ☆`6,053`
- [apache/dubbo-go](https://github.com/apache/dubbo-go) — Go Implementation For Apache Dubbo . ☆`4,882`
- [goravel/goravel](https://github.com/goravel/goravel) — The full-featured Golang Development Framework skeleton ☆`4,426`
- [danielgtaylor/huma](https://github.com/danielgtaylor/huma) — Huma REST/HTTP API Framework for Golang with OpenAPI 3.1 ☆`3,818`
- [documize/community](https://github.com/documize/community) — Modern Confluence alternative ☆`2,366`
- [go-sonic/sonic](https://github.com/go-sonic/sonic) — Blogging platform in Go ☆`2,118`
- [go-goyave/goyave](https://github.com/go-goyave/goyave) — The enterprise REST API framework ☆`1,761`
- [go-fuego/fuego](https://github.com/go-fuego/fuego) — Web framework with OpenAPI 3 ☆`1,663`
- [templui/templui](https://github.com/templui/templui) — UI components for Templ ☆`1,343`
- [savsgio/atreugo](https://github.com/savsgio/atreugo) — Micro web framework on fasthttp ☆`1,299`
- [ankorstore/yokai](https://github.com/ankorstore/yokai) — Modular framework for Go apps ☆`819`
- [indeedeng/iwf](https://github.com/indeedeng/iwf) — Workflow-as-code orchestration ☆`631`
- [i-love-flamingo/flamingo-commerce](https://github.com/i-love-flamingo/flamingo-commerce) — Flexible Go web framework ☆`588`
- [i-love-flamingo/flamingo](https://github.com/i-love-flamingo/flamingo) — Flexible Go web framework ☆`554`
- [rookie-ninja/rk-boot](https://github.com/rookie-ninja/rk-boot) — Enterprise microservice framework ☆`575`
- [fastschema/fastschema](https://github.com/fastschema/fastschema) — All-in-One Backend as a Service with Headless CMS Power ☆`535`
- [uadmin/uadmin](https://github.com/uadmin/uadmin) — The web framework for Golang ☆`355`
- [xxjwxc/ginrpc](https://github.com/xxjwxc/ginrpc) — gin auto binding, grpc and annotated route ☆`301`
- [hidevopsio/hiboot](https://github.com/hidevopsio/hiboot) — High-performance CLI and web apps ☆`181`
- [beatlabs/patron](https://github.com/beatlabs/patron) — Cloud-native microservice framework ☆`126`
- [gone-io/gone](https://github.com/gone-io/gone) — Lightweight DI framework ☆`132`
- [claygod/microservice](https://github.com/claygod/microservice) — Simple microservice framework ☆`122`
- [gookit/rux](https://github.com/gookit/rux) — Simple and fast web framework ☆`99`
- [yaitoo/xun](https://github.com/yaitoo/xun) — Web framework on html/template ☆`91`
- [napsy/go-css](https://github.com/napsy/go-css) — A very simple CSS parser, written in Go ☆`90`
- [go-spring/spring-core](https://github.com/go-spring/spring-core) — Spring-inspired framework for Go ☆`75`
- [abemedia/go-don](https://github.com/abemedia/go-don) — API framework written in Golang. ☆`57`
- [JiveGroup/gFly](https://github.com/JiveGroup/gFly) — Laravel inspired web framework written in Go ☆`48`
- [clubpay/ronykit](https://github.com/clubpay/ronykit) — API Framework supporting REST and RPC. ☆`36`
- [SaiNageswarS/go-api-boot](https://github.com/SaiNageswarS/go-api-boot) — gRPC + HTTP/2 production framework ☆`35`
- [jvcoutinho/lit](https://github.com/jvcoutinho/lit) — A simple, fast and expressive HTTP framework for Go. ☆`31`
### WebAssembly

- [tinygo-org/tinygo](https://github.com/tinygo-org/tinygo) — Go compiler for microcontrollers ☆`17,158`
- [agnivade/wasmbrowsertest](https://github.com/agnivade/wasmbrowsertest) — Run WASM tests inside your browser ☆`206`
- [extism/go-sdk](https://github.com/extism/go-sdk) — Extism Go SDK - easily run WebAssembly modules in your Go applications ☆`167`
## Workflow & Scheduling

### Job Scheduler

- [go-co-op/gocron](https://github.com/go-co-op/gocron) — Easy and fluent Go cron scheduling ☆`6,917`
- [hatchet-dev/hatchet](https://github.com/hatchet-dev/hatchet) — Run Background Tasks at Scale ☆`6,588`
- [reugn/go-quartz](https://github.com/reugn/go-quartz) — Minimalist and zero-dependency scheduling library for Go ☆`2,000`
- [adhocore/gronx](https://github.com/adhocore/gronx) — Lightweight cron expression parser ☆`489`
- [fieldryand/goflow](https://github.com/fieldryand/goflow) — Simple but powerful DAG scheduler and dashboard ☆`472`
- [madflojo/tasks](https://github.com/madflojo/tasks) — In-process task scheduler ☆`323`
- [bart6114/cheek](https://github.com/bart6114/cheek) — cheek: a pico-sized declarative job scheduler ☆`194`
- [onatm/clockwerk](https://github.com/onatm/clockwerk) — Job Scheduling Library ☆`182`
- [deepaksinghvi/cdule](https://github.com/deepaksinghvi/cdule) — Golang job scheduler ☆`60`
- [pardnchiu/go-scheduler](https://github.com/pardnchiu/go-scheduler) — Scheduler with standard cron and task dependencies ☆`32`
- [romshark/sched](https://github.com/romshark/sched) — A job scheduler for Go with the ability to fast-forward time. ☆`28`
### Workflow Frameworks

- [redpanda-data/connect](https://github.com/redpanda-data/connect) — Fancy stream processing made operationally mundane ☆`8,586`
- [dagu-org/dagu](https://github.com/dagu-org/dagu) — Workflow engine with Web UI ☆`3,070`
- [jf-tech/omniparser](https://github.com/jf-tech/omniparser) — ETL streaming parser for Go ☆`1,078`
- [noneback/go-taskflow](https://github.com/noneback/go-taskflow) — Task-parallel programming library ☆`612`
- [cadence-workflow/cadence-go-client](https://github.com/cadence-workflow/cadence-go-client) — Cadence workflow client for Go ☆`374`
- [luno/workflow](https://github.com/luno/workflow) — Type-safe workflow orchestration ☆`217`
- [rhosocial/go-dag](https://github.com/rhosocial/go-dag) — DAG-based workflow framework ☆`35`


---

## 🏆 Top 100 by Stars

> The most starred projects in this list, sorted by GitHub stars.

1. [ollama/ollama](https://github.com/ollama/ollama) — Run LLMs locally ☆`162,669`
1. [kubernetes/kubernetes](https://github.com/kubernetes/kubernetes) — Production-Grade Container Scheduling and Management ☆`120,504`
1. [gin-gonic/gin](https://github.com/gin-gonic/gin) — High-performance HTTP framework ☆`87,998`
1. [junegunn/fzf](https://github.com/junegunn/fzf) — Command-line fuzzy finder ☆`77,783`
1. [moby/moby](https://github.com/moby/moby) — Container ecosystem components ☆`71,469`
1. [caddyserver/caddy](https://github.com/caddyserver/caddy) — Multi-platform web server with HTTPS ☆`69,978`
1. [prometheus/prometheus](https://github.com/prometheus/prometheus) — The Prometheus monitoring system and time series database. ☆`62,710`
1. [traefik/traefik](https://github.com/traefik/traefik) — The Cloud Native Application Proxy ☆`61,637`
1. [pocketbase/pocketbase](https://github.com/pocketbase/pocketbase) — Open Source realtime backend in 1 file ☆`56,097`
1. [golang-standards/project-layout](https://github.com/golang-standards/project-layout) — Standard Go project layout ☆`55,367`
1. [go-gitea/gitea](https://github.com/go-gitea/gitea) — Self-hosted Git service ☆`53,706`
1. [wagoodman/dive](https://github.com/wagoodman/dive) — Explore Docker image layers ☆`53,338`
1. [etcd-io/etcd](https://github.com/etcd-io/etcd) — Distributed key-value store ☆`51,511`
1. [ethereum/go-ethereum](https://github.com/ethereum/go-ethereum) — Go implementation of the Ethereum protocol ☆`50,809`
1. [spf13/cobra](https://github.com/spf13/cobra) — A Commander for modern Go CLI interactions ☆`43,152`
1. [mudler/LocalAI](https://github.com/mudler/LocalAI) — Local OpenAI alternative ☆`42,824`
1. [milvus-io/milvus](https://github.com/milvus-io/milvus) — Cloud-native vector database ☆`42,767`
1. [pingcap/tidb](https://github.com/pingcap/tidb) — Cloud-native distributed SQL DB ☆`39,741`
1. [go-gorm/gorm](https://github.com/go-gorm/gorm) — The fantastic ORM library for Golang, aims to be developer friendly ☆`39,493`
1. [charmbracelet/bubbletea](https://github.com/charmbracelet/bubbletea) — A powerful little TUI framework ☆`39,423`
1. [gofiber/fiber](https://github.com/gofiber/fiber) — Express inspired web framework written in Go ☆`39,218`
1. [schollz/croc](https://github.com/schollz/croc) — Easily and securely send things from one computer to another ☆`34,158`
1. [harness/harness](https://github.com/harness/harness) — End-to-end developer platform ☆`33,874`
1. [zeromicro/go-zero](https://github.com/zeromicro/go-zero) — Microservices framework with CLI tools ☆`32,627`
1. [beego/beego](https://github.com/beego/beego) — High-performance web framework ☆`32,418`
1. [restic/restic](https://github.com/restic/restic) — Fast, secure backup program ☆`32,235`
1. [k3s-io/k3s](https://github.com/k3s-io/k3s) — Lightweight Kubernetes ☆`32,180`
1. [labstack/echo](https://github.com/labstack/echo) — High performance, minimalist Go web framework ☆`32,156`
1. [cockroachdb/cockroach](https://github.com/cockroachdb/cockroach) — Cloud native distributed SQL database ☆`31,852`
1. [kubernetes/minikube](https://github.com/kubernetes/minikube) — Run Kubernetes locally ☆`31,488`
1. [influxdata/influxdb](https://github.com/influxdata/influxdb) — Scalable datastore for metrics, events, and real-time analytics ☆`31,221`
1. [seaweedfs/seaweedfs](https://github.com/seaweedfs/seaweedfs) — Fast distributed storage for blobs ☆`30,248`
1. [spf13/viper](https://github.com/spf13/viper) — Go configuration with fangs ☆`29,992`
1. [grafana/k6](https://github.com/grafana/k6) — A modern load testing tool, using Go and JavaScript ☆`29,905`
1. [fyne-io/fyne](https://github.com/fyne-io/fyne) — Cross platform GUI toolkit in Go inspired by Material Design ☆`27,931`
1. [go-kit/kit](https://github.com/go-kit/kit) — A standard library for microservices. ☆`27,608`
1. [stretchr/testify](https://github.com/stretchr/testify) — Assertions and mocks for testing ☆`25,778`
1. [sirupsen/logrus](https://github.com/sirupsen/logrus) — Structured, pluggable logging for Go. ☆`25,690`
1. [go-kratos/kratos](https://github.com/go-kratos/kratos) — Your ultimate Go microservices framework for the cloud-native era. ☆`25,445`
1. [gocolly/colly](https://github.com/gocolly/colly) — Web scraping framework for Go ☆`25,083`
1. [tsenart/vegeta](https://github.com/tsenart/vegeta) — HTTP load testing tool and library. It's over 9000! ☆`24,900`
1. [uber-go/zap](https://github.com/uber-go/zap) — Fast structured logging ☆`24,239`
1. [urfave/cli](https://github.com/urfave/cli) — Fast CLI framework for Go ☆`23,885`
1. [valyala/fasthttp](https://github.com/valyala/fasthttp) — Fast HTTP package for Go ☆`23,259`
1. [air-verse/air](https://github.com/air-verse/air) — Live reload for Go apps ☆`22,970`
1. [grpc/grpc-go](https://github.com/grpc/grpc-go) — The Go language implementation of gRPC. HTTP/2 based RPC ☆`22,783`
1. [micro/go-micro](https://github.com/micro/go-micro) — A Go microservices framework ☆`22,698`
1. [jaegertracing/jaeger](https://github.com/jaegertracing/jaeger) — Distributed tracing platform ☆`22,462`
1. [redis/go-redis](https://github.com/redis/go-redis) — Redis Go client ☆`21,927`
1. [gorilla/mux](https://github.com/gorilla/mux) — Powerful HTTP router ☆`21,795`
1. [go-chi/chi](https://github.com/go-chi/chi) — Lightweight idiomatic HTTP router ☆`21,586`
1. [dgraph-io/dgraph](https://github.com/dgraph-io/dgraph) — high-performance graph database for real-time use cases ☆`21,530`
1. [FiloSottile/age](https://github.com/FiloSottile/age) — Simple encryption tool ☆`21,308`
1. [samber/lo](https://github.com/samber/lo) — Lodash-style utilities for Go ☆`20,965`
1. [vitessio/vitess](https://github.com/vitessio/vitess) — Database clustering for MySQL ☆`20,697`
1. [qax-os/excelize](https://github.com/qax-os/excelize) — Excel XLSX library for Go ☆`20,291`
1. [antonmedv/fx](https://github.com/antonmedv/fx) — Terminal JSON viewer & processor ☆`20,267`
1. [casbin/casbin](https://github.com/casbin/casbin) — Authorization library for Go ☆`19,833`
1. [dolthub/dolt](https://github.com/dolthub/dolt) — Dolt – Git for Data ☆`19,808`
1. [go-playground/validator](https://github.com/go-playground/validator) — Struct and field validation for Go ☆`19,698`
1. [nats-io/nats-server](https://github.com/nats-io/nats-server) — High-performance NATS message server ☆`19,152`
1. [golangci/golangci-lint](https://github.com/golangci/golangci-lint) — Fast linters runner for Go ☆`18,498`
1. [golang-migrate/migrate](https://github.com/golang-migrate/migrate) — Database migrations. CLI and Golang library. ☆`18,099`
1. [jmoiron/sqlx](https://github.com/jmoiron/sqlx) — Extensions for database/sql ☆`17,505`
1. [rqlite/rqlite](https://github.com/rqlite/rqlite) — Lightweight distributed SQLite ☆`17,310`
1. [tinygo-org/tinygo](https://github.com/tinygo-org/tinygo) — Go compiler for microcontrollers ☆`17,158`
1. [sqlc-dev/sqlc](https://github.com/sqlc-dev/sqlc) — Generate type-safe code from SQL ☆`16,939`
1. [ent/ent](https://github.com/ent/ent) — An entity framework for Go ☆`16,918`
1. [ipfs/kubo](https://github.com/ipfs/kubo) — An IPFS implementation in Go ☆`16,907`
1. [VictoriaMetrics/VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) — Fast time series database and monitoring ☆`16,324`
1. [fatih/vim-go](https://github.com/fatih/vim-go) — Go development plugin for Vim ☆`16,238`
1. [pion/webrtc](https://github.com/pion/webrtc) — Pure Go implementation of the WebRTC API ☆`16,033`
1. [gofr-dev/gofr](https://github.com/gofr-dev/gofr) — Microservice framework for Go ☆`15,966`
1. [keploy/keploy](https://github.com/keploy/keploy) — API testing with auto mocks ☆`15,673`
1. [hashicorp/packer](https://github.com/hashicorp/packer) — Build machine images from config ☆`15,603`
1. [goreleaser/goreleaser](https://github.com/goreleaser/goreleaser) — Release engineering simplified ☆`15,577`
1. [dgraph-io/badger](https://github.com/dgraph-io/badger) — Fast key-value DB in Go. ☆`15,468`
1. [tidwall/gjson](https://github.com/tidwall/gjson) — Fast JSON value extraction ☆`15,439`
1. [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) — MySQL driver for database/sql ☆`15,422`
1. [kubernetes-sigs/kind](https://github.com/kubernetes-sigs/kind) — Kubernetes IN Docker - local clusters for testing Kubernetes ☆`15,014`
1. [PuerkitoBio/goquery](https://github.com/PuerkitoBio/goquery) — jQuery-like HTML manipulation ☆`14,900`
1. [go-task/task](https://github.com/go-task/task) — A fast, cross-platform build tool inspired by Make, designed for modern workflows. ☆`14,832`
1. [panjf2000/ants](https://github.com/panjf2000/ants) — ants is the most powerful and reliable pooling solution for Go. ☆`14,324`
1. [webview/webview](https://github.com/webview/webview) — Tiny webview library for Go ☆`13,898`
1. [bytebase/bytebase](https://github.com/bytebase/bytebase) — Database DevSecOps platform ☆`13,728`
1. [gizak/termui](https://github.com/gizak/termui) — Golang terminal dashboard ☆`13,517`
1. [jackc/pgx](https://github.com/jackc/pgx) — PostgreSQL driver and toolkit for Go ☆`13,330`
1. [golang/groupcache](https://github.com/golang/groupcache) — Distributed cache library ☆`13,322`
1. [juicedata/juicefs](https://github.com/juicedata/juicefs) — Distributed POSIX filesystem ☆`13,217`
1. [gopherjs/gopherjs](https://github.com/gopherjs/gopherjs) — A compiler from Go to JavaScript for running Go code in a browser ☆`13,124`
1. [cloudflare/cloudflared](https://github.com/cloudflare/cloudflared) — Cloudflare Tunnel client ☆`13,042`
1. [gogf/gf](https://github.com/gogf/gf) — Powerful full-stack framework ☆`13,032`
1. [hajimehoshi/ebiten](https://github.com/hajimehoshi/ebiten) — A dead simple 2D game engine for Go ☆`12,958`
1. [hibiken/asynq](https://github.com/hibiken/asynq) — Simple, reliable, and efficient distributed task queue in Go ☆`12,894`
1. [chromedp/chromedp](https://github.com/chromedp/chromedp) — Chrome DevTools Protocol driver ☆`12,732`
1. [IBM/sarama](https://github.com/IBM/sarama) — Sarama is a Go library for Apache Kafka. ☆`12,425`
1. [rs/zerolog](https://github.com/rs/zerolog) — Zero allocation JSON logger ☆`12,211`
1. [Shopify/toxiproxy](https://github.com/Shopify/toxiproxy) — TCP proxy for chaos testing ☆`11,830`
1. [kubeshark/kubeshark](https://github.com/kubeshark/kubeshark) — API traffic analyzer for Kubernetes ☆`11,773`
1. [shirou/gopsutil](https://github.com/shirou/gopsutil) — psutil for golang ☆`11,706`


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