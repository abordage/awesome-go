# Awesome Go

[![Last update](https://img.shields.io/github/last-commit/abordage/awesome-go?label=last%20update)](README.md)
[![License](https://img.shields.io/github/license/abordage/awesome-go)](LICENSE)

**Automated. Curated. Ranked.**

Go libraries, tools, and applications from the community. This awesome list is automatically maintained with daily GitHub API updates. Projects are re-ranked daily based on current activity metrics.

**Daily process:** Merge community PRs → Scan repos → Filter stale projects → Recalculate scores → Rebuild list

- [Actor Model](#actor-model)
- [Artificial Intelligence](#artificial-intelligence)
- [Audio and Music](#audio-and-music)
- [Authentication and OAuth](#authentication-and-oauth)
- [Benchmarks](#benchmarks)
- [Blockchain](#blockchain)
- [Bot Building](#bot-building)
- [Build Automation](#build-automation)
- [Code Analysis](#code-analysis)
- [Command Line](#command-line)
  - [Advanced Console UIs](#advanced-console-uis)
  - [Standard CLI](#standard-cli)
- [Configuration](#configuration)
- [Continuous Integration](#continuous-integration)
- [CSS Preprocessors](#css-preprocessors)
- [Data Integration Frameworks](#data-integration-frameworks)
- [Data Structures and Algorithms](#data-structures-and-algorithms)
  - [Bit Sets](#bit-sets)
  - [Bit-packing and Compression](#bit-packing-and-compression)
  - [Bloom and Cuckoo Filters](#bloom-and-cuckoo-filters)
  - [Data Structure and Algorithm Collections](#data-structure-and-algorithm-collections)
  - [Maps](#maps)
  - [Miscellaneous Data Structures and Algorithms](#miscellaneous-data-structures-and-algorithms)
  - [Nullable Types](#nullable-types)
  - [Pipes](#pipes)
  - [Queues](#queues)
  - [Sets](#sets)
  - [Text Analysis](#text-analysis)
  - [Trees](#trees)
- [Database](#database)
  - [Caches](#caches)
  - [Database Schema Migration](#database-schema-migration)
  - [Database Tools](#database-tools)
  - [Databases Implemented in Go](#databases-implemented-in-go)
  - [SQL Query Builders](#sql-query-builders)
- [Database Drivers](#database-drivers)
  - [Interfaces to Multiple Backends](#interfaces-to-multiple-backends)
  - [NoSQL Database Drivers](#nosql-database-drivers)
  - [Relational Database Drivers](#relational-database-drivers)
  - [Search and Analytic Databases](#search-and-analytic-databases)
- [Date and Time](#date-and-time)
- [Distributed Systems](#distributed-systems)
- [Dynamic DNS](#dynamic-dns)
- [Editor Plugins](#editor-plugins)
- [Email](#email)
- [Embeddable Scripting Languages](#embeddable-scripting-languages)
- [Error Handling](#error-handling)
- [File Handling](#file-handling)
- [Financial](#financial)
- [Forms](#forms)
- [Functional](#functional)
- [Game Development](#game-development)
- [Generators](#generators)
- [Geographic](#geographic)
- [Go Compilers](#go-compilers)
- [Go Generate Tools](#go-generate-tools)
- [Go Tools](#go-tools)
- [Goroutines](#goroutines)
- [GUI](#gui)
- [Hardware](#hardware)
- [Images](#images)
- [IoT (Internet of Things)](#iot-(internet-of-things))
- [Job Scheduler](#job-scheduler)
- [JSON](#json)
- [Logging](#logging)
- [Machine Learning](#machine-learning)
- [Messaging](#messaging)
- [Microsoft Office](#microsoft-office)
  - [Microsoft Excel](#microsoft-excel)
  - [Microsoft Word](#microsoft-word)
- [Middlewares](#middlewares)
- [Miscellaneous](#miscellaneous)
  - [Dependency Injection](#dependency-injection)
  - [Project Layout](#project-layout)
  - [Strings](#strings)
  - [Uncategorized](#uncategorized)
- [Natural Language Processing](#natural-language-processing)
  - [Language Detection](#language-detection)
  - [Morphological Analyzers](#morphological-analyzers)
  - [Slugifiers](#slugifiers)
  - [Tokenizers](#tokenizers)
  - [Translation](#translation)
  - [Transliteration](#transliteration)
- [Networking](#networking)
  - [HTTP Clients](#http-clients)
- [OpenGL](#opengl)
- [ORM](#orm)
- [Package Management](#package-management)
- [Performance](#performance)
- [Query Language](#query-language)
- [Reflection](#reflection)
- [Resource Embedding](#resource-embedding)
- [Routers](#routers)
- [Science and Data Analysis](#science-and-data-analysis)
- [Security](#security)
- [Serialization](#serialization)
- [Server Applications](#server-applications)
- [Software Packages](#software-packages)
  - [DevOps Tools](#devops-tools)
  - [Other Software](#other-software)
- [Stream Processing](#stream-processing)
- [Style Guides](#style-guides)
- [Template Engines](#template-engines)
- [Testing](#testing)
  - [Fail injection](#fail-injection)
  - [Fuzzing](#fuzzing)
  - [Mock](#mock)
  - [Selenium and browser control tools](#selenium-and-browser-control-tools)
  - [Testing Frameworks](#testing-frameworks)
- [Text Processing](#text-processing)
  - [Formatters](#formatters)
  - [Markup Languages](#markup-languages)
  - [Parsers/Encoders/Decoders](#parsers/encoders/decoders)
  - [Regular Expressions](#regular-expressions)
  - [Sanitation](#sanitation)
  - [Scrapers](#scrapers)
  - [Utility/Miscellaneous](#utility/miscellaneous)
- [Third-party APIs](#third-party-apis)
- [Utilities](#utilities)
- [UUID](#uuid)
- [Validation](#validation)
- [Version Control](#version-control)
- [Video](#video)
- [Web Frameworks](#web-frameworks)
- [WebAssembly](#webassembly)
- [Webhooks Server](#webhooks-server)
- [Windows](#windows)
- [Workflow Frameworks](#workflow-frameworks)
- [XML](#xml)
- [Zero Trust](#zero-trust)


## Actor Model

- [asynkron/protoactor-go](https://github.com/asynkron/protoactor-go) — Proto Actor - Ultra fast distributed actors for Go, C# and Java/Kotlin ☆`5,251`
- [ergo-services/ergo](https://github.com/ergo-services/ergo) — An actor-based Framework with network transparency for creating event-driven architecture in Golang. Inspired by Erlang. Zero dependencies. ☆`4,002`
- [anthdm/hollywood](https://github.com/anthdm/hollywood) — Blazingly fast and light-weight Actor engine written in Golang ☆`1,965`
- [Tochemey/goakt](https://github.com/Tochemey/goakt) — [Go] Distributed Actor framework using protocol buffers as message for Golang ☆`259`
## Artificial Intelligence

- [ollama/ollama](https://github.com/ollama/ollama) — Get up and running with Llama 3.3, DeepSeek-R1, Phi-4, Gemma 3, Mistral Small 3.1 and other large language models. ☆`145,020`
- [mudler/LocalAI](https://github.com/mudler/LocalAI) — The free, Open Source alternative to OpenAI, Claude and others. Self-hosted and local-first. Drop-in replacement for OpenAI, running on consumer-grade hardware. No GPU required. Runs gguf, transformers, diffusers and many more models architectures. Features: Generate Text, Audio, Video, Images, Voice Cloning, Distributed, P2P inference ☆`33,544`
- [tmc/langchaingo](https://github.com/tmc/langchaingo) — LangChain for Go, the easiest way to write LLM-based programs in Go ☆`6,996`
- [philippgille/chromem-go](https://github.com/philippgille/chromem-go) — Embeddable vector database for Go with Chroma-like interface and zero third-party dependencies. In-memory with optional persistence. ☆`608`
- [presbrey/ollamafarm](https://github.com/presbrey/ollamafarm) — Manage and use multiple Ollama instances with automatic offline detection/failover and model availability tracking ☆`78`
## Audio and Music

- [ebitengine/oto](https://github.com/ebitengine/oto) — A low-level library to play sound on multiple platforms ☆`1,731`
- [gordonklaus/portaudio](https://github.com/gordonklaus/portaudio) — Go bindings for the PortAudio audio I/O library ☆`776`
- [DylanMeeus/GoAudio](https://github.com/DylanMeeus/GoAudio) — Go tools for audio processing & creation ☆`375`
- [gen2brain/malgo](https://github.com/gen2brain/malgo) — Mini audio library ☆`334`
- [mewkiz/flac](https://github.com/mewkiz/flac) — Package flac provides access to FLAC (Free Lossless Audio Codec) streams. ☆`332`
- [tosone/minimp3](https://github.com/tosone/minimp3) — Decode mp3 ☆`129`
- [dh1tw/gosamplerate](https://github.com/dh1tw/gosamplerate) — Go Bindings for libsamplerate ☆`35`
## Authentication and OAuth

- [casbin/casbin](https://github.com/casbin/casbin) — An authorization library that supports access control models like ACL, RBAC, ABAC in Golang ☆`18,800`
- [golang-jwt/jwt](https://github.com/golang-jwt/jwt) — Go implementation of JSON Web Tokens (JWT). ☆`8,189`
- [markbates/goth](https://github.com/markbates/goth) — Package goth provides a simple, clean, and idiomatic way to write authentication packages for Go web applications. ☆`6,062`
- [golang/oauth2](https://github.com/golang/oauth2) — Go OAuth2 ☆`5,638`
- [ory/keto](https://github.com/ory/keto) — The most scalable and customizable permission server on the market. Fix your slow or broken permission system with Google's proven "Zanzibar" approach. Supports ACL, RBAC, and more. Written in Go, cloud native, headless, API-first. Available as a service on Ory Network and for self-hosters. ☆`5,051`
- [aarondl/authboss](https://github.com/aarondl/authboss) — The boss of http auth. ☆`3,980`
- [cerbos/cerbos](https://github.com/cerbos/cerbos) — Cerbos is the open core, language-agnostic, scalable authorization solution that makes user permissions and authorization simple to implement and manage by writing context-aware access control policies for your application resources. ☆`3,911`
- [openfga/openfga](https://github.com/openfga/openfga) — A high performance and flexible authorization/permission engine built for developers and inspired by Google Zanzibar ☆`3,758`
- [alexedwards/scs](https://github.com/alexedwards/scs) — HTTP Session Management for Go ☆`2,351`
- [lestrrat-go/jwx](https://github.com/lestrrat-go/jwx) — Complete implementation of JWx (Javascript Object Signing and Encryption/JOSE) technologies for Go ☆`2,125`
- [openshift/osin](https://github.com/openshift/osin) — Golang OAuth2 server library ☆`1,927`
- [dghubble/gologin](https://github.com/dghubble/gologin) — Go login handlers for authentication providers (OAuth1, OAuth2) ☆`1,914`
- [zitadel/oidc](https://github.com/zitadel/oidc) — Easy to use OpenID Connect client and server library written for Go and certified by the OpenID Foundation ☆`1,591`
- [cristalhq/jwt](https://github.com/cristalhq/jwt) — Safe, simple and fast JSON Web Tokens for Go ☆`683`
- [shaj13/go-guardian](https://github.com/shaj13/go-guardian) — Go-Guardian is a golang library that provides a simple, clean, and idiomatic way to create powerful modern API and web authentication. ☆`588`
- [go-jose/go-jose](https://github.com/go-jose/go-jose) — An implementation of JOSE standards (JWE, JWS, JWT) in Go ☆`408`
- [abraithwaite/jeff](https://github.com/abraithwaite/jeff) — Jeff provides the simplest way to manage web sessions in Go. ☆`266`
- [Kwynto/gosession](https://github.com/Kwynto/gosession) — This is quick session for net/http in golang. This package is perhaps the best implementation of the session mechanism, at least it tries to become one. ☆`257`
- [leodip/goiabada](https://github.com/leodip/goiabada) — Goiabada is an OAuth2 / OpenID Connect server written in Go. ☆`154`
- [RijulGulati/otpgen](https://github.com/RijulGulati/otpgen) — Library to generate TOTP/HOTP codes ☆`139`
- [jellydator/sessionup](https://github.com/jellydator/sessionup) — Straightforward HTTP session management ☆`126`
- [icza/session](https://github.com/icza/session) — Go session management for web servers (including support for Google App Engine - GAE). ☆`118`
- [brianvoe/sjwt](https://github.com/brianvoe/sjwt) — Simple JWT Golang ☆`122`
- [essentialkaos/branca](https://github.com/essentialkaos/branca) — Authenticated encrypted API tokens (IETF XChaCha20-Poly1305 AEAD) for Golang ☆`90`
- [mengzhuo/cookiestxt](https://github.com/mengzhuo/cookiestxt) — cookiestxt implement parser of cookies txt format ☆`19`
## Benchmarks

- [smallnest/go-web-framework-benchmark](https://github.com/smallnest/go-web-framework-benchmark) — Go web framework benchmark ☆`2,124`
- [julienschmidt/go-http-routing-benchmark](https://github.com/julienschmidt/go-http-routing-benchmark) — Go HTTP request router and web framework benchmark ☆`1,656`
- [alecthomas/go_serialization_benchmarks](https://github.com/alecthomas/go_serialization_benchmarks) — Benchmarks of Go serialization methods ☆`1,593`
- [atemerev/skynet](https://github.com/atemerev/skynet) — Skynet 1M threads microbenchmark ☆`1,058`
- [SimonWaldherr/golang-benchmarks](https://github.com/SimonWaldherr/golang-benchmarks) — Go(lang) benchmarks - (measure the speed of golang) ☆`136`
- [feyeleanor/gospeed](https://github.com/feyeleanor/gospeed) — Go micro-benchmarks for calculating the speed of language constructs ☆`126`
- [nikolaydubina/go-ml-benchmarks](https://github.com/nikolaydubina/go-ml-benchmarks) — Benchmarks of machine learning inference for Go ☆`32`
## Blockchain

- [ethereum/go-ethereum](https://github.com/ethereum/go-ethereum) — Go implementation of the Ethereum protocol ☆`49,205`
- [ipfs/kubo](https://github.com/ipfs/kubo) — An IPFS implementation in Go ☆`16,540`
- [lightningnetwork/lnd](https://github.com/lightningnetwork/lnd) — Lightning Network Daemon ☆`7,958`
- [cosmos/cosmos-sdk](https://github.com/cosmos/cosmos-sdk) — A Framework for Building High Value Public Blockchains ☆`6,633`
- [gagliardetto/solana-go](https://github.com/gagliardetto/solana-go) — Go SDK library and RPC client for the Solana Blockchain ☆`1,342`
- [gnolang/gno](https://github.com/gnolang/gno) — Gno: An interpreted, stack-based Go virtual machine to build succinct and composable apps + gno.land: a blockchain for timeless code and fair open-source. ☆`970`
- [cometbft/cometbft](https://github.com/cometbft/cometbft) — CometBFT: A distributed, Byzantine fault-tolerant, deterministic state machine replication engine. A fork and successor to Tendermint Core. ☆`755`
- [ChainSafe/gossamer](https://github.com/ChainSafe/gossamer) — Go Implementation of the Polkadot Host ☆`451`
## Bot Building

- [tucnak/telebot](https://github.com/tucnak/telebot) — Telebot is a Telegram bot framework in Go. ☆`4,375`
- [wabarc/wayback](https://github.com/wabarc/wayback) — An archiving tool with an IM-style interface that prioritizes privacy and accessibility, integrated with various archival services including Internet Archive, archive.today, Ghostarchive, IPFS, Telegraph, and file systems. ☆`1,984`
- [go-telegram/bot](https://github.com/go-telegram/bot) — Telegram Bot API Go framework ☆`1,207`
- [mymmrac/telego](https://github.com/mymmrac/telego) — Telegram Bot API library for Go ☆`729`
- [diamondburned/arikawa](https://github.com/diamondburned/arikawa) — A Golang library and framework for the Discord API. ☆`526`
- [NicoNex/echotron](https://github.com/NicoNex/echotron) — An elegant and concurrent library for the Telegram bot API in Go. ☆`405`
- [gempir/go-twitch-irc](https://github.com/gempir/go-twitch-irc) — go irc client for twitch.tv ☆`375`
- [innogames/slack-bot](https://github.com/innogames/slack-bot) — Ready to use Slack bot for lazy developers: start Jenkins jobs, watch Jira tickets, watch pull requests with AI support... ☆`198`
- [mr-linch/go-tg](https://github.com/mr-linch/go-tg) — Go client library for accessing Telegram Bot API, with batteries for building complex bots included. ☆`118`
- [slack-io/slacker](https://github.com/slack-io/slacker) — Slack Bot Framework ☆`54`
- [onrik/micha](https://github.com/onrik/micha) — Client lib for Telegram bot api ☆`30`
## Build Automation

- [air-verse/air](https://github.com/air-verse/air) — Live reload for Go apps ☆`20,867`
- [go-task/task](https://github.com/go-task/task) — A task runner / simpler Make alternative written in Go ☆`13,033`
- [joerdav/xc](https://github.com/joerdav/xc) — Markdown defined task runner. ☆`1,295`
- [goyek/goyek](https://github.com/goyek/goyek) — Task automation Go library ☆`628`
## Code Analysis

- [golangci/golangci-lint](https://github.com/golangci/golangci-lint) — Fast linters runner for Go ☆`17,219`
- [mgechev/revive](https://github.com/mgechev/revive) — ~6x faster, stricter, configurable, extensible, and beautiful drop-in replacement for golint ☆`5,216`
- [kisielk/errcheck](https://github.com/kisielk/errcheck) — errcheck checks that you checked errors. ☆`2,419`
- [go-critic/go-critic](https://github.com/go-critic/go-critic) — The most opinionated Go source code linter for code audit. ☆`1,972`
- [segmentio/golines](https://github.com/segmentio/golines) — A golang formatter that fixes long lines ☆`1,074`
- [daveshanley/vacuum](https://github.com/daveshanley/vacuum) — vacuum is the worlds fastest OpenAPI 3, OpenAPI 2 / Swagger linter and quality analysis tool. Built in go, it tears through API specs faster than you can think. vacuum is compatible with Spectral rulesets and generates compatible reports. ☆`787`
- [yuroyoro/goast-viewer](https://github.com/yuroyoro/goast-viewer) — Golang AST visualizer ☆`782`
- [sqs/goreturns](https://github.com/sqs/goreturns) — A gofmt/goimports-like tool for Go programmers that fills in Go return statements with zero values to match the func return types ☆`533`
- [presmihaylov/todocheck](https://github.com/presmihaylov/todocheck) — A static code analyser for annotated TODO comments ☆`433`
- [mdempsky/unconvert](https://github.com/mdempsky/unconvert) — Remove unnecessary type conversions from Go source ☆`383`
- [mibk/dupl](https://github.com/mibk/dupl) — a tool for code clone detection ☆`351`
- [tomarrell/wrapcheck](https://github.com/tomarrell/wrapcheck) — A Go linter to check that errors from external packages are wrapped ☆`339`
- [shurcooL/gostatus](https://github.com/shurcooL/gostatus) — A command line tool that shows the status of Go repositories. ☆`244`
- [Antonboom/testifylint](https://github.com/Antonboom/testifylint) — The Golang linter that checks usage of github.com/stretchr/testify. ☆`141`
- [Crocmagnon/fatcontext](https://github.com/Crocmagnon/fatcontext) — detects nested contexts in loops or function literals ☆`47`
- [sashamelentyev/usestdlibvars](https://github.com/sashamelentyev/usestdlibvars) — A linter that detect the possibility to use variables/constants from the Go standard library. ☆`45`
- [mccoyst/validate](https://github.com/mccoyst/validate) — A Go package to automatically validate fields with tags ☆`62`
## Command Line

### Advanced Console UIs

- [charmbracelet/bubbletea](https://github.com/charmbracelet/bubbletea) — A powerful little TUI framework ☆`32,684`
- [antonmedv/fx](https://github.com/antonmedv/fx) — Terminal JSON viewer & processor ☆`19,628`
- [gizak/termui](https://github.com/gizak/termui) — Golang terminal dashboard ☆`13,373`
- [jroimartin/gocui](https://github.com/jroimartin/gocui) — Minimalist Go package aimed at creating Console User Interfaces. ☆`10,278`
- [charmbracelet/lipgloss](https://github.com/charmbracelet/lipgloss) — Style definitions for nice terminal layouts ☆`9,176`
- [charmbracelet/bubbles](https://github.com/charmbracelet/bubbles) — TUI components for Bubble Tea ☆`6,498`
- [c-bata/go-prompt](https://github.com/c-bata/go-prompt) — Building powerful interactive prompts in Go, inspired by python-prompt-toolkit. ☆`5,377`
- [pterm/pterm](https://github.com/pterm/pterm) — #PTerm is a modern Go module to easily beautify console output. Featuring charts, progressbars, tables, trees, text input, select menus and much more It's completely configurable and 100% cross-platform compatible. ☆`5,124`
- [schollz/progressbar](https://github.com/schollz/progressbar) — A really basic thread-safe progress bar for Golang applications ☆`4,428`
- [mum4k/termdash](https://github.com/mum4k/termdash) — Terminal based dashboard. ☆`2,834`
- [guptarohit/asciigraph](https://github.com/guptarohit/asciigraph) — make lightweight ASCII line graph in command line apps with no other dependencies ☆`2,838`
- [briandowns/spinner](https://github.com/briandowns/spinner) — Go (golang) package with 90 configurable terminal spinner/progress indicators. ☆`2,442`
- [vbauerster/mpb](https://github.com/vbauerster/mpb) — multi progress bar for Go cli applications ☆`2,408`
- [muesli/termenv](https://github.com/muesli/termenv) — Advanced ANSI style & color support for your terminal applications ☆`1,854`
- [gookit/color](https://github.com/gookit/color) — Terminal color rendering library, support 8/16 colors, 256 colors, RGB color rendering output ☆`1,546`
- [logrusorgru/aurora](https://github.com/logrusorgru/aurora) — Golang ultimate ANSI-colors that supports Printf/Sprintf methods ☆`1,457`
- [mattn/go-isatty](https://github.com/mattn/go-isatty) —  ☆`864`
- [mattn/go-colorable](https://github.com/mattn/go-colorable) —  ☆`792`
- [Delta456/box-cli-maker](https://github.com/Delta456/box-cli-maker) — Make Highly Customized Boxes for CLI ☆`564`
- [Evertras/bubble-table](https://github.com/Evertras/bubble-table) — A customizable, interactive table component for the Bubble Tea framework ☆`502`
- [cyucelen/marker](https://github.com/cyucelen/marker) — Marker is the easiest way to match and mark strings for colorful terminal outputs! ☆`51`
### Standard CLI

- [spf13/cobra](https://github.com/spf13/cobra) — A Commander for modern Go CLI interactions ☆`40,930`
- [urfave/cli](https://github.com/urfave/cli) — A declarative, simple, fast, and fun package for building command line tools in Go ☆`23,280`
- [elves/elvish](https://github.com/elves/elvish) — Powerful scripting language & versatile interactive shell ☆`6,044`
- [alecthomas/kingpin](https://github.com/alecthomas/kingpin) — A Go command line and flag parser ☆`3,535`
- [dnote/dnote](https://github.com/dnote/dnote) — A simple command line notebook for programmers ☆`2,884`
- [jessevdk/go-flags](https://github.com/jessevdk/go-flags) — go command line option parser ☆`2,664`
- [spf13/pflag](https://github.com/spf13/pflag) — Drop-in replacement for Go's flag package, implementing POSIX/GNU-style --flags. ☆`2,584`
- [alexflint/go-arg](https://github.com/alexflint/go-arg) — Struct-based argument parsing in Go ☆`2,157`
- [nanovms/ops](https://github.com/nanovms/ops) — ops - build and run nanos unikernels ☆`1,359`
- [carapace-sh/carapace-bin](https://github.com/carapace-sh/carapace-bin) — A multi-shell completion binary. ☆`1,316`
- [posener/complete](https://github.com/posener/complete) — bash completion written in go + bash completion for go command ☆`938`
- [carapace-sh/carapace](https://github.com/carapace-sh/carapace) — A multi-shell completion library. ☆`711`
- [leaanthony/clir](https://github.com/leaanthony/clir) — A Simple and Clear CLI library. Dependency free. ☆`193`
- [urfave/sflags](https://github.com/urfave/sflags) — Generate flags by parsing structures ☆`161`
- [hedzr/cmdr](https://github.com/hedzr/cmdr) — POSIX-compliant command-line UI (CLI) parser and Hierarchical-configuration operations ☆`140`
- [reeflective/readline](https://github.com/reeflective/readline) — Shell library with powerful and modern UI, large feature set, and `.inputrc` support ☆`119`
- [cristalhq/acmd](https://github.com/cristalhq/acmd) — Simple, useful and opinionated CLI package in Go. ☆`125`
- [codingconcepts/env](https://github.com/codingconcepts/env) — Tag-based environment configuration for structs ☆`120`
- [reeflective/console](https://github.com/reeflective/console) — Closed-loop application library for Cobra commands (powerful, ready-to-run and easy to use) ☆`96`
- [DavidGamba/go-getoptions](https://github.com/DavidGamba/go-getoptions) — Fully featured Go (golang) command line option parser with built-in auto-completion support. ☆`61`
- [dixonwille/wlog](https://github.com/dixonwille/wlog) — A simple logging interface that supports cross-platform color and concurrency. ☆`67`
- [nyaosorg/go-readline-ny](https://github.com/nyaosorg/go-readline-ny) — The New Yet another Readline for Go ☆`29`
- [hashicorp/cli](https://github.com/hashicorp/cli) — A Go library for implementing command-line interfaces. ☆`25`
- [sgreben/flagvar](https://github.com/sgreben/flagvar) — A collection of CLI argument types for the Go `flag` package. ☆`45`
- [carapace-sh/carapace-spec](https://github.com/carapace-sh/carapace-spec) — A multi-shell completion spec. ☆`21`
- [jxskiss/mcli](https://github.com/jxskiss/mcli) — A minimal but powerful cli library for Go ☆`41`
## Configuration

- [spf13/viper](https://github.com/spf13/viper) — Go configuration with fangs ☆`28,769`
- [bytedance/sonic](https://github.com/bytedance/sonic) — A blazingly fast JSON serializing & deserializing library ☆`8,283`
- [caarlos0/env](https://github.com/caarlos0/env) — A simple, zero-dependencies library to parse environment variables into structs ☆`5,589`
- [knadh/koanf](https://github.com/knadh/koanf) — Simple, extremely lightweight, extensible, configuration management library for Go. Supports JSON, TOML, YAML, env, command line, file, S3 etc. Alternative to viper. ☆`3,261`
- [alecthomas/kong](https://github.com/alecthomas/kong) — Kong is a command-line parser for Go ☆`2,697`
- [ilyakaznacheev/cleanenv](https://github.com/ilyakaznacheev/cleanenv) — Clean and minimalistic environment configuration reader for Golang ☆`1,854`
- [adrg/xdg](https://github.com/adrg/xdg) — Go implementation of the XDG Base Directory Specification and XDG user directories ☆`835`
- [cristalhq/aconfig](https://github.com/cristalhq/aconfig) — Simple, useful and opinionated config loader. ☆`593`
- [gookit/config](https://github.com/gookit/config) — Go configuration manage (load, get, set, export). support JSON, YAML, TOML, Properties, INI, HCL, ENV and Flags. ☆`555`
- [kkyr/fig](https://github.com/kkyr/fig) — A minimalist Go configuration library ☆`381`
- [hjson/hjson-go](https://github.com/hjson/hjson-go) — Hjson for Go ☆`336`
- [nil-go/konf](https://github.com/nil-go/konf) — The simplest config loader for Go that reads/watches from file, env, flag and clouds (AWS, Azure, GCP). ☆`324`
- [vrischmann/envconfig](https://github.com/vrischmann/envconfig) — Small library to read your configuration from environment variables ☆`244`
- [chaindead/zerocfg](https://github.com/chaindead/zerocfg) — Zero-effort, concise configuration management that avoids boilerplate and repetitive actions. ☆`189`
- [beatlabs/harvester](https://github.com/beatlabs/harvester) — Harvest configuration, watch and notify subscriber ☆`132`
- [BoRuDar/configuration](https://github.com/BoRuDar/configuration) — Library for setting values to structs' fields from env, flags, files or default tag ☆`108`
- [gurkankaymak/hocon](https://github.com/gurkankaymak/hocon) — go implementation of lightbend's HOCON configuration library https://github.com/lightbend/config ☆`85`
- [go-simpler/env](https://github.com/go-simpler/env) — Load environment variables into a config struct ☆`70`
- [omeid/uconfig](https://github.com/omeid/uconfig) — Lightweight, zero-dependency, and extendable configuration management library for Go ☆`71`
- [num30/config](https://github.com/num30/config) — Declarative configuration for Go ☆`58`
- [PaddleHQ/go-aws-ssm](https://github.com/PaddleHQ/go-aws-ssm) — Go package that interfaces with AWS System Manager ☆`61`
- [sakirsensoy/genv](https://github.com/sakirsensoy/genv) — Genv is a library for Go (golang) that makes it easy to read and use environment variables in your projects. It also allows environment variables to be loaded from the .env file. ☆`42`
- [dsbasko/go-cfg](https://github.com/dsbasko/go-cfg) — The library provides a unified way to read configuration data from different sources, such as environment variables, command line flags, and configuration files. ☆`46`
- [wkhere/bcl](https://github.com/wkhere/bcl) — Basic Configuration Language ☆`26`
- [greencoda/confiq](https://github.com/greencoda/confiq) — Structured data format to config struct decoder library for Go ☆`38`
- [romshark/yamagiconf](https://github.com/romshark/yamagiconf) — YAML configuration framework for Go. ☆`18`
- [nasermirzaei89/env](https://github.com/nasermirzaei89/env) — Golang Get Environment Variables Package ☆`18`
- [deatil/go-array](https://github.com/deatil/go-array) — A Go package that read or set data from map, slice or json ☆`19`
## Continuous Integration

- [harness/harness](https://github.com/harness/harness) — Harness Open Source is an end-to-end developer platform with Source Control Management, CI/CD Pipelines, Hosted Developer Environments, and Artifact Registries. ☆`32,914`
- [woodpecker-ci/woodpecker](https://github.com/woodpecker-ci/woodpecker) — Woodpecker is a simple, yet powerful CI/CD engine with great extensibility. ☆`5,191`
- [ovh/cds](https://github.com/ovh/cds) — Enterprise-Grade Continuous Delivery & DevOps Automation Open Source Platform ☆`4,724`
- [raviqqe/muffet](https://github.com/raviqqe/muffet) — Fast website link checker in Go ☆`2,568`
- [vladopajic/go-test-coverage](https://github.com/vladopajic/go-test-coverage) — go-test-coverage is a tool designed to report issues when test coverage falls below a specified threshold ☆`156`
- [nikogura/gomason](https://github.com/nikogura/gomason) — A tool for testing, building, signing, and publishing binaries. ☆`65`
- [opnlabs/dot](https://github.com/opnlabs/dot) — A minimal continuous integration system. Uses docker to run jobs concurrently in stages. ☆`24`
- [gha-common/go-beautiful-html-coverage](https://github.com/gha-common/go-beautiful-html-coverage) — A GitHub Action to track code coverage in your pull requests, with a beautiful HTML preview, for free. ☆`16`
## CSS Preprocessors

- [wellington/go-libsass](https://github.com/wellington/go-libsass) — Go wrapper for libsass, the only Sass 3.5 compiler for Go ☆`212`
- [napsy/go-css](https://github.com/napsy/go-css) — A very simple CSS parser, written in Go ☆`81`
## Data Integration Frameworks

- [redpanda-data/connect](https://github.com/redpanda-data/connect) — Fancy stream processing made operationally mundane ☆`8,390`
- [jf-tech/omniparser](https://github.com/jf-tech/omniparser) — omniparser: a native Golang ETL streaming parser and transform library for CSV, JSON, XML, EDI, text, etc. ☆`1,048`
## Data Structures and Algorithms

### Bit Sets

- [bits-and-blooms/bitset](https://github.com/bits-and-blooms/bitset) — Go package implementing bitsets ☆`1,426`
- [kelindar/bitmap](https://github.com/kelindar/bitmap) — Simple dense bitmap index in Go with binary operators ☆`338`
### Bit-packing and Compression

- [RoaringBitmap/roaring](https://github.com/RoaringBitmap/roaring) — Roaring bitmaps in Go (golang), used by InfluxDB, Bleve, DataDog ☆`2,723`
- [iancmcc/bingo](https://github.com/iancmcc/bingo) — Fast, zero-allocation, lexicographic-order-preserving packing/unpacking of native Go types to bytes. ☆`45`
- [amallia/go-ef](https://github.com/amallia/go-ef) — A Go implementation of the Elias-Fano encoding ☆`39`
### Bloom and Cuckoo Filters

- [bits-and-blooms/bloom](https://github.com/bits-and-blooms/bloom) — Go package implementing Bloom filters, used by Milvus and Beego. ☆`2,613`
- [tylertreat/BoomFilters](https://github.com/tylertreat/BoomFilters) — Probabilistic data structures for processing continuous, unbounded streams. ☆`1,615`
- [seiflotfy/cuckoofilter](https://github.com/seiflotfy/cuckoofilter) — Cuckoo Filter: Practically Better Than Bloom ☆`1,179`
- [OldPanda/bloomfilter](https://github.com/OldPanda/bloomfilter) — Yet another Bloomfilter implementation in Go, compatible with Java's Guava library ☆`18`
### Data Structure and Algorithm Collections

- [Workiva/go-datastructures](https://github.com/Workiva/go-datastructures) — A collection of useful, performant, and threadsafe Go datastructures. ☆`7,813`
- [liyue201/gostl](https://github.com/liyue201/gostl) — Data structure and algorithm library for go, designed to provide functions similar to C++ STL ☆`1,096`
### Maps

- [mhmtszr/concurrent-swiss-map](https://github.com/mhmtszr/concurrent-swiss-map) — A high-performance, thread-safe generic concurrent hash map implementation with Swiss Map. ☆`244`
- [lrita/cmap](https://github.com/lrita/cmap) — a thread-safe concurrent map for go ☆`96`
- [goradd/maps](https://github.com/goradd/maps) — map library using Go generics that offers a standard interface, go routine synchronization, and sorting ☆`49`
- [srfrog/dict](https://github.com/srfrog/dict) — Python-like dictionaries for Go ☆`47`
### Miscellaneous Data Structures and Algorithms

- [axiomhq/hyperloglog](https://github.com/axiomhq/hyperloglog) — HyperLogLog with lots of sugar (Sparse, LogLog-Beta bias correction and TailCut space reduction) brought to you by Axiom ☆`983`
- [barweiss/go-tuple](https://github.com/barweiss/go-tuple) — Go 1.18+ generic tuple ☆`93`
- [seiflotfy/count-min-log](https://github.com/seiflotfy/count-min-log) — Go implementation of Count-Min-Log ☆`67`
- [s0rg/quadtree](https://github.com/s0rg/quadtree) — Generic, zero-alloc, 100%-test covered Quadtree for golang ☆`38`
### Nullable Types

- [kak-tus/nan](https://github.com/kak-tus/nan) — Zero allocation Nullable structures in one library with handy conversion functions, marshallers and unmarshallers ☆`87`
### Pipes

- [nazar256/parapipe](https://github.com/nazar256/parapipe) — Paralleling pipeline ☆`37`
### Queues

- [hatchet-dev/hatchet](https://github.com/hatchet-dev/hatchet) — Run Background Tasks at Scale ☆`5,765`
- [gammazero/deque](https://github.com/gammazero/deque) — Fast ring-buffer deque (double-ended queue) ☆`688`
- [adrianbrad/queue](https://github.com/adrianbrad/queue) — Go package providing multiple queue implementations. Developed in a thread-safe generic way. ☆`310`
- [embano1/memlog](https://github.com/embano1/memlog) — A Kafka log inspired in-memory and append-only data structure ☆`133`
- [mikestefanello/backlite](https://github.com/mikestefanello/backlite) — Type-safe, persistent, embedded task queues and background job runner w/ SQLite ☆`96`
### Sets

- [deckarep/golang-set](https://github.com/deckarep/golang-set) — A simple, battle-tested and generic set type for the Go language. Trusted by Docker, 1Password, Ethereum and Hashicorp. ☆`4,538`
### Text Analysis

- [blevesearch/bleve](https://github.com/blevesearch/bleve) — A modern text/numeric/geo-spatial/vector indexing library for go ☆`10,426`
- [derekparker/trie](https://github.com/derekparker/trie) — Data structure and relevant algorithms for extremely fast prefix/fuzzy string searching. ☆`775`
- [agnivade/levenshtein](https://github.com/agnivade/levenshtein) — Go implementation to calculate Levenshtein Distance. ☆`404`
- [plar/go-adaptive-radix-tree](https://github.com/plar/go-adaptive-radix-tree) — Adaptive Radix Trees implemented in Go ☆`391`
- [viant/ptrie](https://github.com/viant/ptrie) — A prefix tree implementation in go ☆`43`
### Trees

- [bobg/merkle](https://github.com/bobg/merkle) — Merkle hash trees ☆`19`
## Database

### Caches

- [golang/groupcache](https://github.com/golang/groupcache) — groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases. ☆`13,194`
- [hypermodeinc/ristretto](https://github.com/hypermodeinc/ristretto) — A high performance memory-bound Go cache ☆`6,154`
- [eko/gocache](https://github.com/eko/gocache) — A complete Go cache library that brings you multiple ways of managing your caches ☆`2,679`
- [bluele/gcache](https://github.com/bluele/gcache) — An in-memory cache library for golang. It supports multiple eviction policies: LRU, LFU, ARC ☆`2,688`
- [VictoriaMetrics/fastcache](https://github.com/VictoriaMetrics/fastcache) — Fast thread-safe inmemory cache for big number of entries in Go. Minimizes GC overhead ☆`2,232`
- [maypok86/otter](https://github.com/maypok86/otter) — A high performance caching library for Go ☆`1,934`
- [viccon/sturdyc](https://github.com/viccon/sturdyc) — A caching library with advanced concurrency features designed to make I/O heavy applications robust and highly performant ☆`1,210`
- [jellydator/ttlcache](https://github.com/jellydator/ttlcache) — An in-memory cache with item expiration and generics ☆`1,098`
- [EchoVault/SugarDB](https://github.com/EchoVault/SugarDB) — Embeddable and distributed in-memory alternative to Redis. ☆`493`
- [faabiosr/cachego](https://github.com/faabiosr/cachego) — Golang Cache component - Multiple drivers ☆`373`
- [Yiling-J/theine-go](https://github.com/Yiling-J/theine-go) — high performance in-memory cache ☆`297`
- [elastic/go-freelru](https://github.com/elastic/go-freelru) —  ☆`242`
- [naughtygopher/pocache](https://github.com/naughtygopher/pocache) — Pocache is a minimal cache package which focuses on a preemptive optimistic caching strategy ☆`225`
- [erni27/imcache](https://github.com/erni27/imcache) — A zero-dependency generic in-memory cache Go library ☆`125`
- [OrlovEvgeny/go-mcache](https://github.com/OrlovEvgeny/go-mcache) — High-throughput, sharded in-memory KV cache for Go with minimal allocations ☆`98`
- [zekroTJA/timedmap](https://github.com/zekroTJA/timedmap) — A thread safe map which has expiring key-value pairs. ☆`75`
- [codingsince1985/couchcache](https://github.com/codingsince1985/couchcache) — A RESTful caching micro-service in Go backed by Couchbase ☆`67`
- [mdaliyan/icache](https://github.com/mdaliyan/icache) — A High Performance, Generic, thread-safe, zero-dependency, key-value, in-memory cache ☆`21`
### Database Schema Migration

- [golang-migrate/migrate](https://github.com/golang-migrate/migrate) — Database migrations. CLI and Golang library. ☆`16,906`
- [bytebase/bytebase](https://github.com/bytebase/bytebase) — World's most advanced database DevSecOps solution for Developer, Security, DBA and Platform Engineering teams. The GitHub/GitLab for database DevSecOps. ☆`12,649`
- [pressly/goose](https://github.com/pressly/goose) — A database migration tool. Supports SQL migrations and Go functions. ☆`8,604`
- [ariga/atlas](https://github.com/ariga/atlas) — Manage your database schema as code ☆`6,978`
- [amacneil/dbmate](https://github.com/amacneil/dbmate) — A lightweight, framework-agnostic database migration tool. ☆`6,089`
- [rubenv/sql-migrate](https://github.com/rubenv/sql-migrate) — SQL schema migration tool for Go. ☆`3,345`
- [skeema/skeema](https://github.com/skeema/skeema) — Declarative pure-SQL schema management for MySQL and MariaDB ☆`1,320`
- [go-gormigrate/gormigrate](https://github.com/go-gormigrate/gormigrate) — Minimalistic database migration helper for Gorm ORM ☆`1,098`
- [linkedin/goavro](https://github.com/linkedin/goavro) — Goavro is a library that encodes and decodes Avro data. ☆`1,031`
- [sunary/sqlize](https://github.com/sunary/sqlize) — powerful SQL toolkit; offering parsing, building, and migration capabilities. ☆`122`
- [robinjoseph08/go-pg-migrations](https://github.com/robinjoseph08/go-pg-migrations) — A Go package to help write migrations with go-pg/pg. ☆`86`
- [khezen/avro](https://github.com/khezen/avro) — Apache AVRO for go ☆`47`
- [adlio/schema](https://github.com/adlio/schema) — Embedded schema migration package for Go ☆`42`
- [muir/libschema](https://github.com/muir/libschema) — database schema migrations on a per-library basis [Go] ☆`17`
### Database Tools

- [vitessio/vitess](https://github.com/vitessio/vitess) — Vitess is a database clustering system for horizontal scaling of MySQL. ☆`19,732`
- [sosedoff/pgweb](https://github.com/sosedoff/pgweb) — Cross-platform client for PostgreSQL databases ☆`8,928`
- [go-mysql-org/go-mysql](https://github.com/go-mysql-org/go-mysql) — a powerful mysql toolset with Go ☆`4,773`
- [prest/prest](https://github.com/prest/prest) — PostgreSQL REST, low-code, simplify and accelerate development, instant, realtime, high-performance on any Postgres application, existing or new ☆`4,362`
- [ContentSquare/chproxy](https://github.com/ContentSquare/chproxy) — Open-Source ClickHouse http proxy and load balancer ☆`1,362`
- [cybertec-postgresql/pg_timetable](https://github.com/cybertec-postgresql/pg_timetable) — pg_timetable: Advanced scheduling for PostgreSQL ☆`1,191`
- [HDT3213/rdb](https://github.com/HDT3213/rdb) — Golang implemented Redis RDB parser for secondary development and memory analysis ☆`542`
- [nikepan/clickhouse-bulk](https://github.com/nikepan/clickhouse-bulk) — Collects many small inserts to ClickHouse and send in big inserts ☆`498`
- [wesql/wescale](https://github.com/wesql/wescale) — WeScale is a Modern MySQL proxy that supports read-write-split, read-after-write-consistency, load balancing and OnlineDDL. ☆`302`
- [gatewayd-io/gatewayd](https://github.com/gatewayd-io/gatewayd) — Database Gateway for Building Data-Driven Applications ☆`263`
- [liweiyi88/onedump](https://github.com/liweiyi88/onedump) — Effortless database administration tool ☆`194`
- [sj14/dbbench](https://github.com/sj14/dbbench) — dbbench is a simple database benchmarking tool which supports several databases and own scripts ☆`108`
- [bartventer/gorm-multitenancy](https://github.com/bartventer/gorm-multitenancy) — Multi-tenancy support for GORM managed databases ☆`60`
- [kazhuravlev/database-gateway](https://github.com/kazhuravlev/database-gateway) — Safe access to production databases ☆`28`
- [codingconcepts/dg](https://github.com/codingconcepts/dg) — A fast data generator that produces CSV files from generated relational data ☆`35`
### Databases Implemented in Go

- [prometheus/prometheus](https://github.com/prometheus/prometheus) — The Prometheus monitoring system and time series database. ☆`59,195`
- [pingcap/tidb](https://github.com/pingcap/tidb) — TiDB - the open-source, cloud-native, distributed SQL database designed for modern applications. ☆`38,638`
- [milvus-io/milvus](https://github.com/milvus-io/milvus) — Milvus is a high-performance, cloud-native vector database built for scalable vector ANN search ☆`35,639`
- [cockroachdb/cockroach](https://github.com/cockroachdb/cockroach) — CockroachDB — the cloud native, distributed SQL database designed for high availability, effortless scale, and control over data placement. ☆`31,030`
- [influxdata/influxdb](https://github.com/influxdata/influxdb) — Scalable datastore for metrics, events, and real-time analytics ☆`30,240`
- [hypermodeinc/dgraph](https://github.com/hypermodeinc/dgraph) — high-performance graph database for real-time use cases ☆`20,972`
- [dolthub/dolt](https://github.com/dolthub/dolt) — Dolt – Git for Data ☆`18,780`
- [rqlite/rqlite](https://github.com/rqlite/rqlite) — The lightweight, user-friendly, distributed relational database built on SQLite. ☆`16,704`
- [hypermodeinc/badger](https://github.com/hypermodeinc/badger) — Fast key-value DB in Go. ☆`14,700`
- [VictoriaMetrics/VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) — VictoriaMetrics: fast, cost-effective monitoring solution and time series database ☆`14,391`
- [etcd-io/bbolt](https://github.com/etcd-io/bbolt) — An embedded key/value database for Go. ☆`8,871`
- [codenotary/immudb](https://github.com/codenotary/immudb) — immudb - immutable database based on zero trust, SQL/Key-Value/Document model, tamperproof, data change history ☆`8,764`
- [authzed/spicedb](https://github.com/authzed/spicedb) — Open Source, Google Zanzibar-inspired database for scalably storing and querying fine-grained authorization data ☆`5,810`
- [cockroachdb/pebble](https://github.com/cockroachdb/pebble) — RocksDB/LevelDB inspired key-value database in Go ☆`5,359`
- [rosedblabs/rosedb](https://github.com/rosedblabs/rosedb) — Lightweight, fast and reliable key/value storage engine based on Bitcask. ☆`4,823`
- [tidwall/buntdb](https://github.com/tidwall/buntdb) — BuntDB is an embeddable, in-memory key/value database for Go with custom indexing and geospatial support ☆`4,724`
- [nalgeon/redka](https://github.com/nalgeon/redka) — Redis re-implemented with SQLite ☆`3,813`
- [HDT3213/godis](https://github.com/HDT3213/godis) — A Golang implemented Redis Server and Cluster ☆`3,707`
- [nutsdb/nutsdb](https://github.com/nutsdb/nutsdb) — A simple, fast, embeddable, persistent key/value store written in pure Go. It supports fully serializable transactions and many data structures such as list, set, sorted set. ☆`3,481`
- [lindb/lindb](https://github.com/lindb/lindb) — LinDB is a scalable, high performance, high availability distributed time series database. ☆`3,040`
- [lotusdblabs/lotusdb](https://github.com/lotusdblabs/lotusdb) — Most advanced key-value database written in Go, extremely fast, compatible with LSM tree and B+ tree. ☆`2,168`
- [kelindar/column](https://github.com/kelindar/column) — High-performance, columnar, in-memory store with bitmap indexing in Go ☆`1,478`
- [akrylysov/pogreb](https://github.com/akrylysov/pogreb) — Embedded key-value store for read-heavy workloads written in Go ☆`1,342`
- [securitybunker/databunker](https://github.com/securitybunker/databunker) — Secure Vault for Customer PII/PHI/PCI/KYC Records ☆`1,309`
- [objectbox/objectbox-go](https://github.com/objectbox/objectbox-go) — Embedded Go Database, the fast alternative to SQLite, gorm, etc. ☆`1,232`
- [couchbase/moss](https://github.com/couchbase/moss) — moss - a simple, fast, ordered, persistable, key-val storage library for golang ☆`1,007`
- [marcboeker/go-duckdb](https://github.com/marcboeker/go-duckdb) — go-duckdb provides a database/sql driver for the DuckDB database engine. ☆`954`
- [amit-davidson/LibraDB](https://github.com/amit-davidson/LibraDB) — LibraDB is a simple, persistent key/value store written in pure Go in less than 1000 lines for learning purposes. ☆`187`
- [xgzlucario/rotom](https://github.com/xgzlucario/rotom) — A tiny Redis server built with Golang, compatible with RESP protocols. ☆`39`
### SQL Query Builders

- [sqlc-dev/sqlc](https://github.com/sqlc-dev/sqlc) — Generate type-safe code from SQL ☆`15,393`
- [Masterminds/squirrel](https://github.com/Masterminds/squirrel) — Fluent SQL generation for golang ☆`7,476`
- [xo/dbtpl](https://github.com/xo/dbtpl) — Command line tool to generate idiomatic Go code for SQL databases supporting PostgreSQL, MySQL, SQLite, Oracle, and Microsoft SQL Server ☆`3,827`
- [go-jet/jet](https://github.com/go-jet/jet) — Type safe SQL builder with code generation and automatic query result data mapping ☆`3,244`
- [doug-martin/goqu](https://github.com/doug-martin/goqu) — SQL builder and query library for golang ☆`2,532`
- [didi/gendry](https://github.com/didi/gendry) — a golang library for sql builder ☆`1,636`
- [qustavo/dotsql](https://github.com/qustavo/dotsql) — A Golang library for using SQL. ☆`748`
- [lqs/sqlingo](https://github.com/lqs/sqlingo) — A lightweight DSL & ORM which helps you to write SQL in Go. ☆`428`
- [arthurkushman/buildsqlx](https://github.com/arthurkushman/buildsqlx) — Go database query builder library for PostgreSQL ☆`181`
- [nullism/bqb](https://github.com/nullism/bqb) — BQB is a lightweight and easy to use query builder that works with sqlite, mysql, mariadb, postgres, and others. ☆`171`
- [galeone/igor](https://github.com/galeone/igor) — igor is an abstraction layer for PostgreSQL with a gorm like syntax. ☆`126`
- [cristalhq/builq](https://github.com/cristalhq/builq) — Easily build SQL queries in Go. ☆`94`
- [HnH/qry](https://github.com/HnH/qry) — Write your SQL queries in raw files with all benefits of modern IDEs, use them in an easy way inside your application with all the profit of compile time constants ☆`35`
- [motrboat/hotcoal](https://github.com/motrboat/hotcoal) — Hotcoal - Secure your handcrafted SQL against injection ☆`24`
## Database Drivers

### Interfaces to Multiple Backends

- [philippgille/gokv](https://github.com/philippgille/gokv) — Simple key-value store abstraction and implementations for Go (Redis, Consul, etcd, bbolt, BadgerDB, LevelDB, Memcached, DynamoDB, S3, PostgreSQL, MongoDB, CockroachDB and many more) ☆`797`
- [avito-tech/go-transaction-manager](https://github.com/avito-tech/go-transaction-manager) — Transaction manager for GoLang ☆`317`
- [fogfish/dynamo](https://github.com/fogfish/dynamo) — Generic Golang Key/Value trait for AWS storage services ☆`21`
- [viant/dsc](https://github.com/viant/dsc) — Datastore Connectivity in go ☆`34`
### NoSQL Database Drivers

- [redis/go-redis](https://github.com/redis/go-redis) — Redis Go client ☆`21,013`
- [gomodule/redigo](https://github.com/gomodule/redigo) — Go client for Redis ☆`9,829`
- [mongodb/mongo-go-driver](https://github.com/mongodb/mongo-go-driver) — The Official Golang driver for MongoDB ☆`8,383`
- [bradfitz/gomemcache](https://github.com/bradfitz/gomemcache) — Go Memcached client library #golang ☆`1,820`
- [qiniu/qmgo](https://github.com/qiniu/qmgo) — Qmgo - The Go driver for MongoDB. It‘s based on official mongo-go-driver but easier to use like Mgo. ☆`1,326`
- [Kamva/mgm](https://github.com/Kamva/mgm) — Mongo Go Models (mgm) is a fast and simple MongoDB ODM for Go (based on official Mongo Go Driver) ☆`759`
- [aerospike/aerospike-client-go](https://github.com/aerospike/aerospike-client-go) — Aerospike Client Go ☆`450`
- [couchbase/gocb](https://github.com/couchbase/gocb) — The Couchbase Go SDK ☆`372`
- [go-kivik/kivik](https://github.com/go-kivik/kivik) — Common interface to CouchDB or CouchDB-like databases for Go and GopherJS ☆`323`
- [nitishm/go-rejson](https://github.com/nitishm/go-rejson) — Golang client for redislabs' ReJSON module with support for multilple redis clients (redigo, go-redis) ☆`343`
- [couchbase/go-couchbase](https://github.com/couchbase/go-couchbase) — Couchbase client in Go ☆`323`
- [chenmingyong0423/go-mongox](https://github.com/chenmingyong0423/go-mongox) — A Go Mongo library based on the official MongoDB driver, featuring streamlined document operations, generic binding of structs to collections, built-in BSON doc builder, automated field updates, struct validation, hooks, and plugin-based programming. ☆`196`
- [btnguyen2k/gocosmos](https://github.com/btnguyen2k/gocosmos) — Go database/sql driver for Azure Cosmos DB SQL API ☆`22`
- [aliexpressru/gomemcached](https://github.com/aliexpressru/gomemcached) — A Binary Memcached client for Go with support for sharding using consistent hashing, along with SASL. ☆`20`
### Relational Database Drivers

- [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) — Go MySQL Driver is a MySQL driver for Go's (golang) database/sql package ☆`14,893`
- [jackc/pgx](https://github.com/jackc/pgx) — PostgreSQL driver and toolkit for Go ☆`12,043`
- [denisenkom/go-mssqldb](https://github.com/denisenkom/go-mssqldb) — Microsoft SQL server driver written in go language ☆`1,855`
- [ncruces/go-sqlite3](https://github.com/ncruces/go-sqlite3) — Go bindings to SQLite using wazero ☆`723`
- [godror/godror](https://github.com/godror/godror) — GO DRiver for ORacle DB ☆`558`
- [cvilsmeier/sqinn-go](https://github.com/cvilsmeier/sqinn-go) — Golang SQLite without cgo ☆`449`
- [VinGarcia/ksql](https://github.com/VinGarcia/ksql) — A Simple and Powerful Golang SQL Library ☆`334`
- [surrealdb/surrealdb.go](https://github.com/surrealdb/surrealdb.go) — SurrealDB SDK for Golang ☆`278`
- [nakagami/firebirdsql](https://github.com/nakagami/firebirdsql) — Firebird RDBMS sql driver for Go (golang) ☆`242`
- [ydb-platform/ydb-go-sdk](https://github.com/ydb-platform/ydb-go-sdk) — Pure Go native and database/sql driver for YDB ☆`165`
- [rqlite/gorqlite](https://github.com/rqlite/gorqlite) — A Go client for rqlite, the distributed database built on SQLite ☆`165`
- [apache/calcite-avatica-go](https://github.com/apache/calcite-avatica-go) — Apache Calcite Go ☆`122`
- [viant/bgc](https://github.com/viant/bgc) — Datastore Connectivity for BigQuery in go ☆`21`
### Search and Analytic Databases

- [elastic/go-elasticsearch](https://github.com/elastic/go-elasticsearch) — The official Go client for Elasticsearch ☆`5,898`
- [ClickHouse/clickhouse-go](https://github.com/ClickHouse/clickhouse-go) — Golang driver for ClickHouse ☆`3,085`
- [sourcegraph/zoekt](https://github.com/sourcegraph/zoekt) — Fast trigram based code search ☆`991`
- [sdqri/effdsl](https://github.com/sdqri/effdsl) — Elasticsearch query builder for golang ☆`30`
## Date and Time

- [dromara/carbon](https://github.com/dromara/carbon) — A simple, semantic and developer-friendly time package for golang ☆`5,088`
- [araddon/dateparse](https://github.com/araddon/dateparse) — GoLang Parse many date strings without knowing format in advance. ☆`2,090`
- [yaa110/go-persian-calendar](https://github.com/yaa110/go-persian-calendar) — The implementation of Persian (Solar Hijri) Calendar in Go ☆`221`
- [bykof/gostradamus](https://github.com/bykof/gostradamus) — Gostradamus: Better DateTimes for Go ☆`210`
- [nathan-osman/go-sunrise](https://github.com/nathan-osman/go-sunrise) — Go package for calculating the sunrise and sunset times for a given location ☆`168`
- [rickb777/date](https://github.com/rickb777/date) — A Go package for working with dates ☆`140`
- [relvacode/iso8601](https://github.com/relvacode/iso8601) — A fast ISO8601 date parser for Go ☆`151`
## Distributed Systems

- [zeromicro/go-zero](https://github.com/zeromicro/go-zero) — A cloud-native Go microservices framework with cli tool for productivity. ☆`31,307`
- [go-kit/kit](https://github.com/go-kit/kit) — A standard library for microservices. ☆`27,122`
- [go-kratos/kratos](https://github.com/go-kratos/kratos) — Your ultimate Go microservices framework for the cloud-native era. ☆`24,521`
- [grpc/grpc-go](https://github.com/grpc/grpc-go) — The Go language implementation of gRPC. HTTP/2 based RPC ☆`21,967`
- [micro/go-micro](https://github.com/micro/go-micro) — A Go microservices framework ☆`22,366`
- [nats-io/nats-server](https://github.com/nats-io/nats-server) — High-Performance server for NATS.io, the cloud and edge native messaging system. ☆`17,405`
- [micro/micro](https://github.com/micro/micro) — A microservices toolkit ☆`12,263`
- [hashicorp/raft](https://github.com/hashicorp/raft) — Golang implementation of the Raft consensus protocol ☆`8,654`
- [smallnest/rpcx](https://github.com/smallnest/rpcx) — Best microservices framework in Go, like alibaba Dubbo, but with more features, Scale easily ☆`8,230`
- [cloudwego/kitex](https://github.com/cloudwego/kitex) — Go RPC framework with high-performance and strong-extensibility for building micro-services. ☆`7,496`
- [luraproject/lura](https://github.com/luraproject/lura) — Ultra performant API Gateway with middlewares. A project hosted at The Linux Foundation ☆`6,571`
- [anacrolix/torrent](https://github.com/anacrolix/torrent) — Full-featured BitTorrent client package and utilities ☆`5,798`
- [lni/dragonboat](https://github.com/lni/dragonboat) — A feature complete and high performance multi-group Raft library in Go. ☆`5,192`
- [emitter-io/emitter](https://github.com/emitter-io/emitter) — High performance, distributed and low latency publish-subscribe platform. ☆`3,937`
- [chrislusf/gleam](https://github.com/chrislusf/gleam) — Fast, efficient, and scalable distributed map/reduce system, DAG execution, in memory or on disk, written in pure Go, runs standalone or distributedly. ☆`3,526`
- [dragonflyoss/dragonfly](https://github.com/dragonflyoss/dragonfly) — Dragonfly is an open source P2P-based file distribution and image acceleration system. It is hosted by the Cloud Native Computing Foundation (CNCF) as an Incubating Level Project. ☆`2,641`
- [go-eagle/eagle](https://github.com/go-eagle/eagle) — A Go framework for the API or Microservice ☆`2,321`
- [go-dev-frame/sponge](https://github.com/go-dev-frame/sponge) — A powerful and easy-to-use Go development framework that enables you to effortlessly build stable, reliable, and high-performance backend services with a "low-code" approach. ☆`1,962`
- [bsm/redislock](https://github.com/bsm/redislock) — Simplified distributed locking implementation using Redis ☆`1,629`
- [mochi-mqtt/server](https://github.com/mochi-mqtt/server) — The fully compliant, embeddable high-performance Go MQTT v5 server for IoT, smarthome, and pubsub ☆`1,560`
- [hprose/hprose-golang](https://github.com/hprose/hprose-golang) — Hprose is a cross-language RPC. This project is Hprose for Golang. ☆`1,261`
- [unionj-cloud/go-doudou](https://github.com/unionj-cloud/go-doudou) — go-doudou（doudou pronounce /dəudəu/）is OpenAPI 3.0 (for REST) spec and Protobuf v3 (for grpc) based lightweight microservice framework. It supports monolith service application as well. ☆`1,202`
- [k8gb-io/k8gb](https://github.com/k8gb-io/k8gb) — A cloud native Kubernetes Global Balancer ☆`1,048`
- [cenkalti/rain](https://github.com/cenkalti/rain) — BitTorrent client and library in Go ☆`1,048`
- [lesismal/arpc](https://github.com/lesismal/arpc) — More effective network communication, two-way calling, notify and broadcast supported. ☆`1,045`
- [trpc-group/trpc-go](https://github.com/trpc-group/trpc-go) — A pluggable, high-performance RPC framework written in golang ☆`978`
- [etcd-io/raft](https://github.com/etcd-io/raft) — Raft library for maintaining a replicated state machine ☆`865`
- [temporalio/sdk-go](https://github.com/temporalio/sdk-go) — Temporal Go SDK ☆`653`
- [AppsFlyer/go-sundheit](https://github.com/AppsFlyer/go-sundheit) — A library built to provide support for defining service health for golang services. It allows you to register async health checks for your dependencies and the service itself, provides a health endpoint that exposes their status, and health metrics. ☆`556`
- [ybbus/jsonrpc](https://github.com/ybbus/jsonrpc) — A simple go implementation of json rpc 2.0 client over http ☆`355`
- [anacrolix/dht](https://github.com/anacrolix/dht) — dht is used by anacrolix/torrent, and is intended for use as a library in other projects both torrent related and otherwise ☆`331`
- [tarmac-project/tarmac](https://github.com/tarmac-project/tarmac) — Write as Functions, Deploy as a Monolith or Microservice with WebAssembly ☆`335`
- [osamingo/jsonrpc](https://github.com/osamingo/jsonrpc) — The jsonrpc package helps implement of JSON-RPC 2.0 ☆`187`
- [italolelis/outboxer](https://github.com/italolelis/outboxer) — A library that implements the outboxer pattern in go ☆`163`
- [capillariesio/capillaries](https://github.com/capillariesio/capillaries) — Distributed batch data processing framework ☆`66`
- [svcavallar/celeriac.v1](https://github.com/svcavallar/celeriac.v1) — Golang client library for adding support for interacting and monitoring Celery workers, tasks and events. ☆`72`
- [sanketplus/go-mysql-lock](https://github.com/sanketplus/go-mysql-lock) — MySQL Backed Locking Primitive ☆`63`
- [vadiminshakov/committer](https://github.com/vadiminshakov/committer) — Two-phase (2PC) and three-phase (3PC) protocols implementaion in Golang ☆`38`
- [pdupub/go-pdu](https://github.com/pdupub/go-pdu) — An PDU implementation in Go ☆`48`
- [gmsec/micro](https://github.com/gmsec/micro) — A Go distributed systems development framework ☆`25`
- [mbrostami/consistenthash](https://github.com/mbrostami/consistenthash) — A Go library that implements Consistent Hashing (+Block Partitioning) ☆`27`
## Dynamic DNS

- [TimothyYe/godns](https://github.com/TimothyYe/godns) — A dynamic DNS client tool that supports AliDNS, Cloudflare, Google Domains, DNSPod, HE.net & DuckDNS & DreamHost, etc, written in Go. ☆`1,591`
- [skibish/ddns](https://github.com/skibish/ddns) — Personal DDNS client with Digital Ocean Networking DNS as backend. ☆`262`
## Editor Plugins

- [fatih/vim-go](https://github.com/fatih/vim-go) — Go development plugin for Vim ☆`16,149`
- [nsf/gocode](https://github.com/nsf/gocode) — An autocompletion daemon for the Go programming language ☆`5,005`
- [golang/vscode-go](https://github.com/golang/vscode-go) — Go extension for Visual Studio Code ☆`4,075`
- [dominikh/go-mode.el](https://github.com/dominikh/go-mode.el) — Emacs mode for the Go programming language ☆`1,421`
- [incu6us/goimports-reviser](https://github.com/incu6us/goimports-reviser) — Right imports sorting & code formatting tool (goimports alternative) ☆`672`
## Email

- [axllent/mailpit](https://github.com/axllent/mailpit) — An email and SMTP testing tool with API for developers ☆`7,282`
- [foxcpp/maddy](https://github.com/foxcpp/maddy) — Composable all-in-one mail server. ☆`5,582`
- [mjl-/mox](https://github.com/mjl-/mox) — modern full-featured open source secure mail server for low-maintenance self-hosted email ☆`5,037`
- [matcornic/hermes](https://github.com/matcornic/hermes) — Golang package that generates clean, responsive HTML e-mails for sending transactional mail ☆`2,906`
- [AfterShip/email-verifier](https://github.com/AfterShip/email-verifier) — A Go library for email verification without sending any emails. ☆`1,392`
- [sendgrid/sendgrid-go](https://github.com/sendgrid/sendgrid-go) — The Official Twilio SendGrid Golang API Library ☆`1,018`
- [wneessen/go-mail](https://github.com/wneessen/go-mail) — Easy to use, yet comprehensive library for sending mails with Go ☆`1,021`
- [mailgun/mailgun-go](https://github.com/mailgun/mailgun-go) — Go library for sending mail with the Mailgun API. ☆`730`
- [xhit/go-simple-mail](https://github.com/xhit/go-simple-mail) — Golang package for send email. Support keep alive connection, TLS and SSL. Easy for bulk SMTP. ☆`678`
- [emersion/go-message](https://github.com/emersion/go-message) — A streaming Go library for the Internet Message Format and mail messages ☆`417`
- [vanng822/go-premailer](https://github.com/vanng822/go-premailer) — Inline styling for html mail in golang ☆`171`
- [mocktools/go-smtp-mock](https://github.com/mocktools/go-smtp-mock) — SMTP mock server written on Golang. Mimic any SMTP server behavior for your test environment with fake SMTP server. ☆`152`
- [truemail-rb/truemail-go](https://github.com/truemail-rb/truemail-go) — Configurable Golang email validator/verifier. Verify email via Regex, DNS, SMTP and even more. Be sure that email address valid and exists. ☆`119`
- [toorop/go-dkim](https://github.com/toorop/go-dkim) — DKIM package for golang ☆`97`
- [dimuska139/go-email-normalizer](https://github.com/dimuska139/go-email-normalizer) — Golang library for providing a canonical representation of email address. ☆`72`
- [valord577/mailx](https://github.com/valord577/mailx) — A library that makes it easier to send email via SMTP. ☆`19`
## Embeddable Scripting Languages

- [php/frankenphp](https://github.com/php/frankenphp) — The modern PHP app server ☆`9,418`
- [expr-lang/expr](https://github.com/expr-lang/expr) — Expression language and expression evaluation for Go ☆`6,968`
- [yuin/gopher-lua](https://github.com/yuin/gopher-lua) — GopherLua: VM and compiler for Lua in Go ☆`6,627`
- [dop251/goja](https://github.com/dop251/goja) — ECMAScript/JavaScript engine in pure Go ☆`6,245`
- [d5/tengo](https://github.com/d5/tengo) — A fast script language for Go ☆`3,658`
- [Shopify/go-lua](https://github.com/Shopify/go-lua) — A Lua VM in Go ☆`3,282`
- [google/cel-go](https://github.com/google/cel-go) — Fast, portable, non-Turing complete expression evaluation with gradual typing (Go) ☆`2,596`
- [google/starlark-go](https://github.com/google/starlark-go) — Starlark in Go: the Starlark configuration language, implemented in Go ☆`2,488`
- [metacall/core](https://github.com/metacall/core) — MetaCall: The ultimate polyglot programming experience. ☆`1,660`
- [wa-lang/wa](https://github.com/wa-lang/wa) — The Wa Programming Language ☆`1,587`
- [mattn/anko](https://github.com/mattn/anko) — Scriptable interpreter written in golang ☆`1,522`
- [PaesslerAG/gval](https://github.com/PaesslerAG/gval) — Expression evaluation in golang ☆`793`
- [aarzilli/golua](https://github.com/aarzilli/golua) — Go bindings for Lua C API - in progress ☆`674`
- [ichiban/prolog](https://github.com/ichiban/prolog) — The only reasonable scripting engine for Go. ☆`676`
- [1set/starlet](https://github.com/1set/starlet) — Yet another Go wrapper for Starlark that simplifies usage, offers data conversion and useful Starlark libraries ☆`30`
## Error Handling

- [hashicorp/go-multierror](https://github.com/hashicorp/go-multierror) — A Go (golang) package for representing a list of errors as a single error. ☆`2,466`
- [cockroachdb/errors](https://github.com/cockroachdb/errors) — Go error library with error portability over the network ☆`2,241`
- [rotisserie/eris](https://github.com/rotisserie/eris) — Error handling library with readable stack traces and flexible formatting support ☆`1,674`
- [joomcode/errorx](https://github.com/joomcode/errorx) — A comprehensive error handling library for Go ☆`1,257`
- [ztrue/tracerr](https://github.com/ztrue/tracerr) — Golang errors with stack trace and source fragments. ☆`1,091`
- [samber/oops](https://github.com/samber/oops) — Error handling library with context, assertion, stack trace and source fragments ☆`696`
- [Southclaws/fault](https://github.com/Southclaws/fault) — Go errors but structured and composable. Fault provides an extensible yet ergonomic mechanism for wrapping errors. ☆`284`
## File Handling

- [pdfcpu/pdfcpu](https://github.com/pdfcpu/pdfcpu) — A PDF processor written in Go. ☆`7,751`
- [spf13/afero](https://github.com/spf13/afero) — A FileSystem Abstraction System for Go ☆`6,254`
- [dundee/gdu](https://github.com/dundee/gdu) — Fast disk usage analyzer with console interface written in Go ☆`4,565`
- [SebastiaanKlippert/go-wkhtmltopdf](https://github.com/SebastiaanKlippert/go-wkhtmltopdf) — Golang commandline wrapper for wkhtmltopdf ☆`1,126`
- [otiai10/copy](https://github.com/otiai10/copy) — Go copy directory recursively ☆`761`
- [no-src/gofs](https://github.com/no-src/gofs) — A cross-platform real-time file synchronization tool out of the box based on Golang ☆`510`
- [C2FO/vfs](https://github.com/C2FO/vfs) — Pluggable, extensible virtual file system for Go ☆`340`
- [viant/afs](https://github.com/viant/afs) — Abstract File Storage ☆`339`
- [kdomanski/iso9660](https://github.com/kdomanski/iso9660) — A go library for reading and creating ISO9660 images ☆`275`
- [barasher/go-exiftool](https://github.com/barasher/go-exiftool) — Golang wrapper for Exiftool : extract as much metadata as possible (EXIF, ...) from files (pictures, pdf, office documents, ...) ☆`268`
- [artonge/go-csv-tag](https://github.com/artonge/go-csv-tag) — Read csv file from go using tags ☆`126`
- [parsyl/parquet](https://github.com/parsyl/parquet) — A library for reading and writing parquet files. ☆`117`
- [codingsince1985/checksum](https://github.com/codingsince1985/checksum) — Compute message digest for large files in Go ☆`110`
- [qmuntal/opc](https://github.com/qmuntal/opc) — Go implementation of the Open Packaging Conventions (OPC) ☆`75`
- [adelowo/gulter](https://github.com/adelowo/gulter) — Golang middleware for handling multipart/form-data and uploading files ☆`65`
- [artonge/go-gtfs](https://github.com/artonge/go-gtfs) — Load GTFS files in golang ☆`48`
- [1set/todotxt](https://github.com/1set/todotxt) — Parser for todo.txt files in Go ☆`25`
## Financial

- [shopspring/decimal](https://github.com/shopspring/decimal) — Arbitrary-precision fixed-point decimal numbers in Go ☆`6,810`
- [achannarasappa/ticker](https://github.com/achannarasappa/ticker) — Track stocks, crypto, and derivatives prices and positions in real time from your terminal ☆`5,299`
- [Rhymond/go-money](https://github.com/Rhymond/go-money) — Go implementation of Fowler's Money pattern ☆`1,777`
- [c9s/bbgo](https://github.com/c9s/bbgo) — The modern cryptocurrency trading bot framework written in Go. ☆`1,373`
- [formancehq/ledger](https://github.com/formancehq/ledger) — The programmable open source ledger for fintechs ☆`984`
- [bojanz/currency](https://github.com/bojanz/currency) — Currency handling for Go. ☆`593`
- [moov-io/ach](https://github.com/moov-io/ach) — ACH implements a reader, writer, and validator for Automated Clearing House (ACH) files. The HTTP server is available in a Docker image and the Go package is available. ☆`490`
- [govalues/decimal](https://github.com/govalues/decimal) — Correctly rounded decimals for Go ☆`170`
- [quagmt/udecimal](https://github.com/quagmt/udecimal) — A high-performance, high precision, zero allocation fixed-point decimal library for financial applications ☆`149`
- [claygod/transaction](https://github.com/claygod/transaction) — Embedded database for accounts transactions. ☆`136`
- [dannyvankooten/vat](https://github.com/dannyvankooten/vat) — Go package for dealing with EU VAT. Does VAT number validation & rates retrieval. ☆`116`
- [jovandeginste/payme](https://github.com/jovandeginste/payme) — QR code generator (ASCII & PNG) for SEPA payments ☆`88`
- [nikolaydubina/fpmoney](https://github.com/nikolaydubina/fpmoney) — Fixed-Point Decimal Money ☆`34`
- [govalues/money](https://github.com/govalues/money) — Correctly rounded monetary amounts and exchange rates for Go ☆`36`
- [nikolaydubina/fpdecimal](https://github.com/nikolaydubina/fpdecimal) — Fixed-Point Decimals ☆`32`
## Forms

- [justinas/nosurf](https://github.com/justinas/nosurf) — CSRF protection middleware for Go. ☆`1,674`
- [gorilla/csrf](https://github.com/gorilla/csrf) — Package gorilla/csrf provides Cross Site Request Forgery (CSRF) prevention middleware for Go web applications & services ☆`1,127`
- [go-playground/form](https://github.com/go-playground/form) — Decodes url.Values into Go value(s) and Encodes Go value(s) into url.Values. Dual Array and Full map support. ☆`841`
- [ggicci/httpin](https://github.com/ggicci/httpin) — HTTP Input for Go - HTTP Request from/to Go Struct (Bi-directional Data Binding between Go Struct and http.Request) ☆`360`
- [sonh/qs](https://github.com/sonh/qs) — Go module for encoding structs into URL query parameters ☆`78`
- [cinar/checker](https://github.com/cinar/checker) — Effortless input validation in Go with the power of struct tags. No dependencies, just pure simplicity. See how! ☆`42`
## Functional

- [samber/mo](https://github.com/samber/mo) — Monads and popular FP abstractions, powered by Go 1.18+ Generics (Option, Result, Either...) ☆`3,008`
- [BooleanCat/go-functional](https://github.com/BooleanCat/go-functional) — go-functional is a library of iterators to augment the standard library ☆`504`
- [seborama/fuego](https://github.com/seborama/fuego) — Functional Experiment in Golang ☆`144`
- [rjNemo/underscore](https://github.com/rjNemo/underscore) — Useful functional programming helpers for Go ☆`116`
## Game Development

- [hajimehoshi/ebiten](https://github.com/hajimehoshi/ebiten) — Ebitengine - A dead simple 2D game engine for Go ☆`12,178`
- [xiaonanln/goworld](https://github.com/xiaonanln/goworld) — Scalable Distributed Game Server Engine with Hot Swapping in Golang ☆`2,654`
- [topfreegames/pitaya](https://github.com/topfreegames/pitaya) — Scalable game server framework with clustering support and client libraries for iOS, Android, Unity and others through the C SDK. ☆`2,567`
- [gen2brain/raylib-go](https://github.com/gen2brain/raylib-go) — Go bindings for raylib, a simple and easy-to-use library to enjoy videogames programming. ☆`2,092`
- [EngoEngine/engo](https://github.com/EngoEngine/engo) — Engo is an open-source 2D game engine written in Go. ☆`1,801`
- [oakmound/oak](https://github.com/oakmound/oak) — A pure Go game engine ☆`1,630`
- [JoelOtter/termloop](https://github.com/JoelOtter/termloop) — Terminal-based game engine for Go, built on top of Termbox ☆`1,459`
- [xtaci/gonet](https://github.com/xtaci/gonet) — A Game Server Skeleton in golang. ☆`1,284`
- [harfang3d/harfang3d](https://github.com/harfang3d/harfang3d) — HARFANG 3D source code public repository ☆`618`
- [gopxl/pixel](https://github.com/gopxl/pixel) — A hand-crafted 2D game library in Go. ☆`331`
- [ungerik/go3d](https://github.com/ungerik/go3d) — A performance oriented 2D/3D math package for Go ☆`323`
- [kelindar/tile](https://github.com/kelindar/tile) — Tile is a 2D grid engine, built with data and cache friendly ways, includes pathfinding and observers. ☆`196`
- [andygeiss/ecs](https://github.com/andygeiss/ecs) — Build your own Game-Engine based on the Entity Component System concept in Golang. ☆`146`
- [gonutz/prototype](https://github.com/gonutz/prototype) — Simple 2D game prototyping framework. ☆`90`
- [mlange-42/ark](https://github.com/mlange-42/ark) — Ark -- Archetype-based Entity Component System (ECS) for Go. ☆`85`
- [s0rg/fantasyname](https://github.com/s0rg/fantasyname) — RinkWorks fantasy name generator for golang ☆`36`
- [s0rg/grid](https://github.com/s0rg/grid) — Generic 2D grid ☆`20`
## Generators

- [oapi-codegen/oapi-codegen](https://github.com/oapi-codegen/oapi-codegen) — Generate Go client and server boilerplate from OpenAPI 3 specifications ☆`7,261`
- [dave/jennifer](https://github.com/dave/jennifer) — Jennifer is a code generator for Go ☆`3,512`
- [awalterschulze/goderive](https://github.com/awalterschulze/goderive) — Derives and generates mundane golang functions that you do not want to maintain yourself ☆`1,260`
- [hexdigest/gowrap](https://github.com/hexdigest/gowrap) — GoWrap is a command line tool for generating decorators for Go interfaces ☆`1,228`
- [abice/go-enum](https://github.com/abice/go-enum) — An enum generator for go ☆`839`
- [jmattheis/goverter](https://github.com/jmattheis/goverter) — Generate type-safe Go converters by defining function signatures. ☆`709`
- [rjeczalik/interfaces](https://github.com/rjeczalik/interfaces) — Code generation tools for Go. ☆`431`
- [switchupcb/copygen](https://github.com/switchupcb/copygen) — Copygen generates code based on Go types. Generate type-based code to copy values from type to type and fields from struct to struct by default (copier without reflection). ☆`391`
- [reedom/convergen](https://github.com/reedom/convergen) — A type-to-type copy function code generator. ☆`47`
## Geographic

- [tidwall/tile38](https://github.com/tidwall/tile38) — Real-time Geospatial and Geofencing ☆`9,357`
- [golang/geo](https://github.com/golang/geo) — S2 geometry library in Go ☆`1,757`
- [consbio/mbtileserver](https://github.com/consbio/mbtileserver) — Basic Go server for mbtiles ☆`732`
- [spatial-go/geoos](https://github.com/spatial-go/geoos) — A library provides spatial data and geometric algorithms ☆`520`
- [paulmach/osm](https://github.com/paulmach/osm) — General purpose library for reading, writing and working with OpenStreetMap data ☆`410`
- [uber/h3-go](https://github.com/uber/h3-go) — Go bindings for H3, a hierarchical hexagonal geospatial indexing system ☆`353`
- [airbusgeo/godal](https://github.com/airbusgeo/godal) — golang wrapper for github.com/OSGEO/gdal ☆`165`
- [peterstace/simplefeatures](https://github.com/peterstace/simplefeatures) — Simple Features is a pure Go Implementation of the OpenGIS Simple Feature Access Specification ☆`149`
- [wroge/wgs84](https://github.com/wroge/wgs84) — A zero-dependency Go package for coordinate transformations. ☆`138`
- [pantrif/s2-geojson](https://github.com/pantrif/s2-geojson) — Draw a polygon on the map or paste a geoJSON and explore how the s2.RegionCoverer covers it with S2 cells depending on the min and max levels ☆`35`
## Go Compilers

- [gopherjs/gopherjs](https://github.com/gopherjs/gopherjs) — A compiler from Go to JavaScript for running Go code in a browser ☆`12,988`
- [yassinebenaid/bunster](https://github.com/yassinebenaid/bunster) — Compile shell scripts to static binaries. ☆`2,414`
- [Konstantin8105/c4go](https://github.com/Konstantin8105/c4go) — Transpiling C code to Go code ☆`373`
- [go2hx/go2hx](https://github.com/go2hx/go2hx) — Import Go libraries in your Haxe projects Go -> Haxe source-to-source compiler ☆`136`
- [Konstantin8105/f4go](https://github.com/Konstantin8105/f4go) — Transpiling fortran code to golang code ☆`48`
## Go Generate Tools

- [xuri/xgen](https://github.com/xuri/xgen) — XSD (XML Schema Definition) parser and Go/C/Java/Rust/TypeScript code generator ☆`372`
- [kazhuravlev/options-gen](https://github.com/kazhuravlev/options-gen) — Codegen for functional options in go projects ☆`94`
- [g4s8/envdoc](https://github.com/g4s8/envdoc) — Go tool to generate documentation for environment variables ☆`86`
## Go Tools

- [go-swagger/go-swagger](https://github.com/go-swagger/go-swagger) — Swagger 2.0 implementation for go ☆`9,787`
- [ondrajz/go-callvis](https://github.com/ondrajz/go-callvis) — Visualize call graph of a Go program using Graphviz ☆`6,300`
- [Zxilly/go-size-analyzer](https://github.com/Zxilly/go-size-analyzer) — A tool for analyzing the size of compiled Go binaries, offering cross-platform support, detailed breakdowns, and multiple output formats. ☆`1,614`
- [safedep/vet](https://github.com/safedep/vet) — Next Generation Software Composition Analysis (SCA) with Malicious Package Detection, Code Context & Policy as Code ☆`518`
- [iyashjayesh/monigo](https://github.com/iyashjayesh/monigo) — MoniGo is a performance monitoring library for Go apps, offering real-time insights into service-level and function-level metrics. With an intuitive UI, it enables developers to track and optimize performance. Get your Go app's dashboard up in just 10 seconds! ☆`272`
- [becheran/roumon](https://github.com/becheran/roumon) — Universal goroutine monitor using pprof and termui ☆`217`
- [dtgorski/typex](https://github.com/dtgorski/typex) — [TOOL/CLI] - Filter and examine Go type structures, interfaces and their transitive dependencies and relationships. Export structural types as TypeScript value object or bare type representations. ☆`206`
- [bitfield/gotestdox](https://github.com/bitfield/gotestdox) — A tool for formatting Go test results as readable documentation ☆`143`
- [bobg/modver](https://github.com/bobg/modver) — a tool that helps you obey semantic versioning rules in your Go module ☆`20`
- [bobg/decouple](https://github.com/bobg/decouple) — find overspecified function parameters in Go code ☆`30`
- [dustinblackman/gomodrun](https://github.com/dustinblackman/gomodrun) — The forgotten go tool that executes and caches binaries included in go.mod files. ☆`38`
## Goroutines

- [panjf2000/ants](https://github.com/panjf2000/ants) — ants is the most powerful and reliable pooling solution for Go. ☆`13,780`
- [benmanns/goworker](https://github.com/benmanns/goworker) — goworker is a Go-based background worker that runs 10 to 100,000* times faster than Ruby-based workers. ☆`2,824`
- [alitto/pond](https://github.com/alitto/pond) — Minimalistic and High-performance goroutine worker pool written in Go ☆`1,867`
- [destel/rill](https://github.com/destel/rill) — Go toolkit for clean, composable, channel-based concurrency ☆`1,685`
- [xxjwxc/gowp](https://github.com/xxjwxc/gowp) — golang worker pool , Concurrency limiting goroutine pool ☆`526`
- [earthboundkid/flowmatic](https://github.com/earthboundkid/flowmatic) — Structured concurrency made easy ☆`387`
- [timandy/routine](https://github.com/timandy/routine) — ThreadLocal for Golang. ☆`266`
- [reugn/async](https://github.com/reugn/async) — Synchronization and asynchronous computation package for Go ☆`249`
- [vladopajic/go-actor](https://github.com/vladopajic/go-actor) — A lightweight library for writing concurrent programs in Go using the Actor model. ☆`227`
- [mborders/artifex](https://github.com/mborders/artifex) — Simple in-memory job queue for Golang using worker-based dispatching ☆`212`
- [hmdsefi/gowl](https://github.com/hmdsefi/gowl) — Gowl is a process management and process monitoring tool at once. An infinite worker pool gives you the ability to control the pool and processes and monitor their status. ☆`70`
- [loveleshsharma/gohive](https://github.com/loveleshsharma/gohive) — A Highly Performant and easy to use goroutine pool for Go ☆`53`
## GUI

- [fyne-io/fyne](https://github.com/fyne-io/fyne) — Cross platform GUI toolkit in Go inspired by Material Design ☆`26,662`
- [webview/webview](https://github.com/webview/webview) — Tiny cross-platform webview library for C/C++. Uses WebKit (GTK/Cocoa) and Edge WebView2 (Windows). ☆`13,192`
- [therecipe/qt](https://github.com/therecipe/qt) — Qt binding for Go (Golang) with support for Windows / macOS / Linux / FreeBSD / Android / iOS / Sailfish OS / Raspberry Pi / AsteroidOS / Ubuntu Touch / JavaScript / WebAssembly ☆`10,682`
- [go-vgo/robotgo](https://github.com/go-vgo/robotgo) — RobotGo, Go Native cross-platform RPA and GUI automation @vcaesar ☆`10,220`
- [maxence-charriere/go-app](https://github.com/maxence-charriere/go-app) — A package to build progressive web apps with Go programming language and WebAssembly. ☆`8,717`
- [lxn/walk](https://github.com/lxn/walk) — A Windows GUI toolkit for the Go Programming Language ☆`6,981`
- [progrium/darwinkit](https://github.com/progrium/darwinkit) — Native Mac APIs for Go. Previously known as MacDriver ☆`5,265`
- [getlantern/systray](https://github.com/getlantern/systray) — a cross platfrom Go library to place an icon and menu in the notification area ☆`3,499`
- [gotk3/gotk3](https://github.com/gotk3/gotk3) — Go bindings for GTK3 ☆`2,166`
- [cogentcore/core](https://github.com/cogentcore/core) — A free and open source framework for building powerful, fast, elegant 2D and 3D apps that run on macOS, Windows, Linux, iOS, Android, and web with a single Go codebase, allowing you to Code Once, Run Everywhere. ☆`2,031`
- [roblillack/spot](https://github.com/roblillack/spot) — React-like desktop GUI toolkit for Go ☆`1,225`
- [ncruces/zenity](https://github.com/ncruces/zenity) — Zenity dialogs for Golang, Windows, macOS ☆`818`
- [energye/energy](https://github.com/energye/energy) — Energy is a framework developed by Go language based on CEF (Chromium Embedded Framework) for developing cross-platform desktop applications for Windows, Mac OS X, and Linux ☆`485`
- [AllenDang/cimgui-go](https://github.com/AllenDang/cimgui-go) — Auto generated Go wrapper for Dear ImGui via cimgui ☆`417`
- [richardwilkes/unison](https://github.com/richardwilkes/unison) — A unified graphical user experience toolkit for Go desktop applications ☆`271`
- [shurcooL/trayhost](https://github.com/shurcooL/trayhost) — Cross-platform Go library to place an icon in the host operating system's taskbar. ☆`256`
- [prashantgupta24/activity-tracker](https://github.com/prashantgupta24/activity-tracker) — A library to notify about any (pluggable) activity on your machine, and let you take action as needed ☆`31`
## Hardware

- [arduino/arduino-cli](https://github.com/arduino/arduino-cli) — Arduino command line tool ☆`4,582`
- [jaypipes/ghw](https://github.com/jaypipes/ghw) — Go HardWare discovery/inspection library ☆`1,759`
- [zcalusic/sysinfo](https://github.com/zcalusic/sysinfo) — Sysinfo is a Go library providing Linux OS / kernel / hardware system information. ☆`549`
## Images

- [hybridgroup/gocv](https://github.com/hybridgroup/gocv) — Go package for computer vision using OpenCV 4 and beyond. Includes support for DNN, CUDA, OpenCV Contrib, and OpenVINO. ☆`7,112`
- [anthonynsimon/bild](https://github.com/anthonynsimon/bild) — Image processing algorithms in pure Go ☆`4,114`
- [sensepost/gowitness](https://github.com/sensepost/gowitness) — gowitness - a golang, web screenshot utility using Chrome Headless ☆`3,817`
- [cshum/imagor](https://github.com/cshum/imagor) — Fast, secure image processing server and Go library, using libvips ☆`3,660`
- [thoas/picfit](https://github.com/thoas/picfit) — An image resizing server written in Go ☆`2,248`
- [gographics/imagick](https://github.com/gographics/imagick) — Go binding to ImageMagick's MagickWand C API ☆`1,823`
- [disintegration/gift](https://github.com/disintegration/gift) — Go Image Filtering Toolkit ☆`1,773`
- [tdewolff/canvas](https://github.com/tdewolff/canvas) — Vector graphics in Go ☆`1,590`
- [davidbyttow/govips](https://github.com/davidbyttow/govips) — A lightning fast image processing and resizing library for Go ☆`1,451`
- [yeqown/go-qrcode](https://github.com/yeqown/go-qrcode) — To help gophers generate QR Codes with customized styles, such as color, block size, block shape, and icon. ☆`721`
- [koyachi/go-nude](https://github.com/koyachi/go-nude) — Nudity detection with Go. ☆`419`
- [auyer/steganography](https://github.com/auyer/steganography) — Pure Golang Library that allows LSB steganography on images using ZERO dependencies ☆`339`
- [HugoSmits86/nativewebp](https://github.com/HugoSmits86/nativewebp) — Native webp encoder for Go ☆`296`
- [kolesa-team/go-webp](https://github.com/kolesa-team/go-webp) — Simple and fast webp library for golang ☆`266`
- [Pixboost/transformimgs](https://github.com/Pixboost/transformimgs) — Open source image CDN. ☆`265`
- [qmuntal/gltf](https://github.com/qmuntal/gltf) — Go library for encoding glTF 2.0 files ☆`258`
- [gojek/darkroom](https://github.com/gojek/darkroom) —  ☆`234`
- [ungerik/go-cairo](https://github.com/ungerik/go-cairo) — Go binding for the cairo graphics library ☆`149`
- [aofei/cameron](https://github.com/aofei/cameron) — An avatar generator for Go. ☆`127`
- [marekm4/color-extractor](https://github.com/marekm4/color-extractor) — Simple image color extractor written in Go with no external dependencies ☆`98`
- [jonoton/scout](https://github.com/jonoton/scout) — Scout is a standalone open source software solution for DIY video security. ☆`20`
## IoT (Internet of Things)

- [hybridgroup/gobot](https://github.com/hybridgroup/gobot) — Golang framework for robotics, drones, and the Internet of Things (IoT) ☆`9,198`
- [lf-edge/ekuiper](https://github.com/lf-edge/ekuiper) — Lightweight data stream processing engine for IoT edge ☆`1,602`
- [Edgenesis/shifu](https://github.com/Edgenesis/shifu) — Kubernetes-native IoT gateway ☆`1,347`
- [rulego/rulego](https://github.com/rulego/rulego) — RuleGo is a lightweight, high-performance, embedded, next-generation component orchestration rule engine framework for Go. ☆`1,173`
- [e154/smart-home](https://github.com/e154/smart-home) — software package for automation ☆`92`
## Job Scheduler

- [go-co-op/gocron](https://github.com/go-co-op/gocron) — Easy and fluent Go cron scheduling ☆`6,329`
- [reugn/go-quartz](https://github.com/reugn/go-quartz) — Minimalist and zero-dependency scheduling library for Go ☆`1,885`
- [adhocore/gronx](https://github.com/adhocore/gronx) — Lightweight, fast and dependency-free Cron expression parser (due checker, next/prev due date finder), task runner, job scheduler and/or daemon for Golang (tested on v1.13+) and standalone usage. If you are bold, use it to replace crontab entirely. ☆`454`
- [fieldryand/goflow](https://github.com/fieldryand/goflow) — Simple but powerful DAG scheduler and dashboard ☆`441`
- [madflojo/tasks](https://github.com/madflojo/tasks) — Package tasks is an easy to use in-process scheduler for recurring tasks in Go ☆`313`
- [bart6114/cheek](https://github.com/bart6114/cheek) — cheek: a pico-sized declarative job scheduler ☆`190`
- [onatm/clockwerk](https://github.com/onatm/clockwerk) — Job Scheduling Library ☆`181`
- [deepaksinghvi/cdule](https://github.com/deepaksinghvi/cdule) — cdule (pronounce as Schedule) Golang based scheduler library with database support. ☆`55`
- [romshark/sched](https://github.com/romshark/sched) — A job scheduler for Go with the ability to fast-forward time. ☆`28`
## JSON

- [tidwall/gjson](https://github.com/tidwall/gjson) — Get JSON values quickly - JSON parser for Go ☆`15,004`
- [Jeffail/gabs](https://github.com/Jeffail/gabs) — For parsing, creating and editing unknown or dynamic JSON in Go ☆`3,512`
- [valyala/fastjson](https://github.com/valyala/fastjson) — Fast JSON parser and validator for Go. No custom structs, no code generation, no reflection ☆`2,386`
- [ohler55/ojg](https://github.com/ohler55/ojg) — Optimized JSON for Go ☆`897`
- [wI2L/jsondiff](https://github.com/wI2L/jsondiff) — Compute the diff between two JSON documents as a series of RFC6902 (JSON Patch) operations ☆`583`
- [PerimeterX/marshmallow](https://github.com/PerimeterX/marshmallow) — Marshmallow provides a flexible and performant JSON unmarshalling in Go. It specializes in dealing with unstructured struct - when some fields are known and some aren't, with zero performance overhead nor extra coding needed. ☆`386`
- [spyzhov/ajson](https://github.com/spyzhov/ajson) — Abstract JSON for Golang with JSONPath support ☆`276`
- [Andrew-M-C/go.jsonvalue](https://github.com/Andrew-M-C/go.jsonvalue) — Quick Solution with Unstructured JSON data ☆`197`
- [romshark/jscan](https://github.com/romshark/jscan) — High performance JSON iterator & validator for Go ☆`95`
- [iOliverNguyen/ujson](https://github.com/iOliverNguyen/ujson) — µjson - A fast and minimal JSON parser and transformer that works on unstructured JSON ☆`82`
- [simonnilsson/ask](https://github.com/simonnilsson/ask) — A Go package that provides a simple way of accessing nested properties in maps and slices. ☆`53`
- [neilotoole/jsoncolor](https://github.com/neilotoole/jsoncolor) — Colorized JSON output for Go ☆`47`
- [ake-persson/mapslice-json](https://github.com/ake-persson/mapslice-json) — Go MapSlice for ordered marshal/ unmarshal of maps in JSON ☆`20`
- [vtopc/epoch](https://github.com/vtopc/epoch) — Contains primitives for marshaling/unmarshaling Unix timestamp/epoch to/from built-in time.Time type in JSON ☆`16`
## Logging

- [sirupsen/logrus](https://github.com/sirupsen/logrus) — Structured, pluggable logging for Go. ☆`25,335`
- [uber-go/zap](https://github.com/uber-go/zap) — Blazing fast, structured, leveled logging in Go. ☆`23,273`
- [rs/zerolog](https://github.com/rs/zerolog) — Zero Allocation JSON Logger ☆`11,542`
- [davecgh/go-spew](https://github.com/davecgh/go-spew) — Implements a deep pretty printer for Go data structures to aid in debugging ☆`6,261`
- [golang/glog](https://github.com/golang/glog) — Leveled execution logs for Go ☆`3,604`
- [k0kubun/pp](https://github.com/k0kubun/pp) — Colored pretty printer for Go language ☆`1,960`
- [apex/log](https://github.com/apex/log) — Structured logging package for Go. ☆`1,369`
- [lmittmann/tint](https://github.com/lmittmann/tint) — slog.Handler that writes tinted (colorized) logs ☆`1,025`
- [getsentry/sentry-go](https://github.com/getsentry/sentry-go) — The official Go SDK for Sentry (sentry.io) ☆`973`
- [phuslu/log](https://github.com/phuslu/log) — Fastest structured logging ☆`777`
- [Lifailon/lazyjournal](https://github.com/Lifailon/lazyjournal) — A TUI for reading logs from journald, auditd, file system, Docker containers, Podman and Kubernetes pods for quick viewing, coloring output and filtering with fuzzy find, regex support and timestamp. ☆`586`
- [samber/slog-multi](https://github.com/samber/slog-multi) — Design workflows of slog handlers: pipeline, middleware, fanout, routing, failover, load balancing... ☆`493`
- [gookit/slog](https://github.com/gookit/slog) — Lightweight, configurable, extensible logging library written in Go ☆`479`
- [henvic/httpretty](https://github.com/henvic/httpretty) — Package httpretty prints the HTTP requests you make with Go pretty on your terminal. ☆`407`
- [simukti/sqldb-logger](https://github.com/simukti/sqldb-logger) — A logger for Go SQL database driver without modifying existing *sql.DB stdlib usage. ☆`377`
- [hashicorp/logutils](https://github.com/hashicorp/logutils) — Utilities for slightly better logging in Go (Golang). ☆`367`
- [go-playground/log](https://github.com/go-playground/log) — Simple, configurable and scalable Structured Logging for Go. ☆`295`
- [samber/slog-formatter](https://github.com/samber/slog-formatter) — slog: Attribute formatting ☆`173`
- [rs/xlog](https://github.com/rs/xlog) — xlog is a logger for net/context aware HTTP applications ☆`139`
- [yuseferi/zax](https://github.com/yuseferi/zax) — Golang Zap logger with context ☆`27`
- [clok/kemba](https://github.com/clok/kemba) — A tiny debug logging tool. Ideal for CLI tools and command applications ☆`16`
## Machine Learning

- [sjwhitworth/golearn](https://github.com/sjwhitworth/golearn) — Machine Learning for Go ☆`9,408`
- [gorgonia/gorgonia](https://github.com/gorgonia/gorgonia) — Gorgonia is a library that helps facilitate machine learning in Go. ☆`5,793`
- [otiai10/gosseract](https://github.com/otiai10/gosseract) — Go package for OCR (Optical Character Recognition), by using Tesseract C++ library ☆`2,894`
- [galeone/tfgo](https://github.com/galeone/tfgo) — Tensorflow + Go, the gopher way ☆`2,473`
- [gomlx/gomlx](https://github.com/gomlx/gomlx) — GoMLX: An Accelerated Machine Learning Framework For Go ☆`815`
- [jbrukh/bayesian](https://github.com/jbrukh/bayesian) — Naive Bayesian Classification for Golang. ☆`808`
- [patrikeh/go-deep](https://github.com/patrikeh/go-deep) — Artificial Neural Network ☆`550`
- [knights-analytics/hugot](https://github.com/knights-analytics/hugot) — Onnx transformer pipelines in Golang ☆`420`
- [c-bata/goptuna](https://github.com/c-bata/goptuna) — A hyperparameter optimization framework, inspired by Optuna. ☆`268`
- [malaschitz/randomForest](https://github.com/malaschitz/randomForest) — Random Forest implementation in golang ☆`53`
## Messaging

- [IBM/sarama](https://github.com/IBM/sarama) — Sarama is a Go library for Apache Kafka. ☆`12,060`
- [hibiken/asynq](https://github.com/hibiken/asynq) — Simple, reliable, and efficient distributed task queue in Go ☆`11,461`
- [centrifugal/centrifugo](https://github.com/centrifugal/centrifugo) — Scalable real-time messaging server in a language-agnostic way. Self-hosted alternative to Pubnub, Pusher, Ably. Set up once and forever. ☆`9,067`
- [ThreeDotsLabs/watermill](https://github.com/ThreeDotsLabs/watermill) — Building event-driven applications the easy way in Go. ☆`8,587`
- [appleboy/gorush](https://github.com/appleboy/gorush) — A push notification server written in Go (Golang). ☆`8,413`
- [RichardKnop/machinery](https://github.com/RichardKnop/machinery) — Machinery is an asynchronous task queue/job queue based on distributed message passing. ☆`7,772`
- [nats-io/nats.go](https://github.com/nats-io/nats.go) — Golang client for NATS, the cloud native messaging system. ☆`5,986`
- [confluentinc/confluent-kafka-go](https://github.com/confluentinc/confluent-kafka-go) — Confluent's Apache Kafka Golang client ☆`4,914`
- [dunglas/mercure](https://github.com/dunglas/mercure) — An open, easy, fast, reliable and battery-efficient solution for real-time communications ☆`4,969`
- [olahol/melody](https://github.com/olahol/melody) — Minimalist websocket framework for Go ☆`3,935`
- [sideshow/apns2](https://github.com/sideshow/apns2) — HTTP/2 Apple Push Notification Service (APNs) push provider for Go — Send push notifications to iOS, tvOS, Safari and OSX apps, using the APNs HTTP/2 protocol. ☆`3,094`
- [lovoo/goka](https://github.com/lovoo/goka) — Goka is a compact yet powerful distributed stream processing library for Apache Kafka written in Go. ☆`2,451`
- [asaskevich/EventBus](https://github.com/asaskevich/EventBus) — [Go] Lightweight eventbus with async compatibility for Go ☆`1,884`
- [rabbitmq/amqp091-go](https://github.com/rabbitmq/amqp091-go) — An AMQP 0-9-1 Go client maintained by the RabbitMQ team ☆`1,793`
- [pebbe/zmq4](https://github.com/pebbe/zmq4) — A Go interface to ZeroMQ version 4 ☆`1,211`
- [jcuga/golongpoll](https://github.com/jcuga/golongpoll) — golang long polling library. Makes web pub-sub easy via HTTP long-poll servers and clients ☆`662`
- [timbray/quamina](https://github.com/timbray/quamina) — Home of Quamina, a fast pattern-matching library in Go ☆`429`
- [cskr/pubsub](https://github.com/cskr/pubsub) — A simple pubsub package for go. ☆`438`
- [jandelgado/rabtap](https://github.com/jandelgado/rabtap) — RabbitMQ wire tap and swiss army knife ☆`269`
- [mehdihadeli/Go-MediatR](https://github.com/mehdihadeli/Go-MediatR) — A library for handling mediator patterns and simplified CQRS patterns within an event-driven architecture, inspired by csharp MediatR library. ☆`245`
- [hyperonym/ratus](https://github.com/hyperonym/ratus) — Ratus is a RESTful asynchronous task queue server. It translated concepts of distributed task queues into a set of resources that conform to REST principles and provides a consistent HTTP API for various backends. ☆`120`
- [robinjoseph08/redisqueue](https://github.com/robinjoseph08/redisqueue) — redisqueue provides a producer and consumer of a queue that uses Redis streams ☆`134`
- [dailymotion/oplog](https://github.com/dailymotion/oplog) — A generic oplog/replication system for microservices ☆`110`
- [furdarius/rabbitroutine](https://github.com/furdarius/rabbitroutine) — Lightweight library that handles RabbitMQ auto-reconnect and publishing retry routine for you. ☆`112`
- [oagudo/outbox](https://github.com/oagudo/outbox) — Lightweight library for the transactional outbox pattern in Go, not tied to any specific relational database or broker. ☆`74`
- [jirenius/go-res](https://github.com/jirenius/go-res) — RES Service protocol library for Go ☆`65`
- [SchwarzIT/hypermatch](https://github.com/SchwarzIT/hypermatch) — hypermatch is a high-performance Go library designed for rapid matching of a large number of rules to events. It processes thousands of events per second against extensive rule sets in-memory with minimal latency . ☆`28`
- [maxatome/go-vitotrol](https://github.com/maxatome/go-vitotrol) — golang client library to Viessmann Vitotrol web service ☆`23`
## Microsoft Office

- [unidoc/unioffice](https://github.com/unidoc/unioffice) — Pure go library for creating and processing Office Word (.docx), Excel (.xlsx) and Powerpoint (.pptx) documents ☆`4,607`
### Microsoft Excel

- [qax-os/excelize](https://github.com/qax-os/excelize) — Go language library for reading and writing Microsoft Excel (XLAM / XLSM / XLSX / XLTM / XLTX) spreadsheets ☆`19,302`
- [tealeg/xlsx](https://github.com/tealeg/xlsx) — Go library for reading and writing XLSX files. ☆`5,979`
- [go-the-way/exl](https://github.com/go-the-way/exl) — Excel binding to struct written in Go.(Only supports Go1.18+) ☆`32`
### Microsoft Word

- [gomutex/godocx](https://github.com/gomutex/godocx) — Go library for reading and writing Microsoft Docx ☆`184`
## Middlewares

- [urfave/negroni](https://github.com/urfave/negroni) — Idiomatic HTTP Middleware for Golang ☆`7,527`
- [justinas/alice](https://github.com/justinas/alice) — Painless middleware chaining for Go ☆`3,263`
- [didip/tollbooth](https://github.com/didip/tollbooth) — Simple middleware to rate-limit HTTP requests. ☆`2,804`
- [rs/cors](https://github.com/rs/cors) — Go net/http configurable handler to handle CORS requests ☆`2,792`
- [unrolled/render](https://github.com/unrolled/render) — Go package for easily rendering JSON, XML, binary data, and HTML templates responses. ☆`1,967`
- [lingrino/go-fault](https://github.com/lingrino/go-fault) — fault injection library in go using standard http middleware ☆`509`
- [jub0bs/cors](https://github.com/jub0bs/cors) — perhaps the best CORS middleware library for Go ☆`96`
- [rookie-ninja/rk-grpc](https://github.com/rookie-ninja/rk-grpc) — Start gRPC microservice from YAML, plugin of rk-boot ☆`77`
- [rookie-ninja/rk-gin](https://github.com/rookie-ninja/rk-gin) — Start gin microservice from YAML, plugin of rk-boot ☆`50`
- [faabiosr/echo-middleware](https://github.com/faabiosr/echo-middleware) — Go package that provides multiple middlewares for Echo Framework. ☆`16`
## Miscellaneous

### Dependency Injection

- [google/wire](https://github.com/google/wire) — Compile-time Dependency Injection for Go ☆`13,884`
- [uber-go/fx](https://github.com/uber-go/fx) — A dependency injection based application framework for Go. ☆`6,615`
- [uber-go/dig](https://github.com/uber-go/dig) — A reflection based dependency injection toolkit for Go. ☆`4,210`
- [goioc/di](https://github.com/goioc/di) — Simple and yet powerful Dependency Injection for Go ☆`365`
- [d3fvxl/di](https://github.com/d3fvxl/di) — A full-featured dependency injection container for go programming language. ☆`238`
- [go-kod/kod](https://github.com/go-kod/kod) — A generics based dependency injection application framework for Go, supporting aspect oriented programming based on interceptors ☆`186`
- [i-love-flamingo/dingo](https://github.com/i-love-flamingo/dingo) — Go Dependency Injection Framework ☆`184`
- [NVIDIA/gontainer](https://github.com/NVIDIA/gontainer) — Dependency Injection container for Golang projects. ☆`49`
- [muir/nject](https://github.com/muir/nject) — Golang type-safe dependency injection ☆`30`
- [matzefriedrich/parsley](https://github.com/matzefriedrich/parsley) — An easy-to-use reflection-based dependency injection package that fits into any Go application. ☆`27`
- [logrange/linker](https://github.com/logrange/linker) — Dependency Injection and Inversion of Control package ☆`35`
- [componego/componego](https://github.com/componego/componego) — The most flexible component-oriented framework for GoLang applications ☆`28`
- [firasdarwish/ore](https://github.com/firasdarwish/ore) — Advanced Dependency Injection Solution for Go ☆`22`
- [gontainer/gontainer](https://github.com/gontainer/gontainer) — YAML-based Dependency Injection container for GO ☆`16`
### Project Layout

- [golang-standards/project-layout](https://github.com/golang-standards/project-layout) — Standard Go Project Layout ☆`52,884`
- [Melkeydev/go-blueprint](https://github.com/Melkeydev/go-blueprint) — Go-blueprint allows users to spin up a quick Go project using a popular framework ☆`7,700`
- [ardanlabs/service](https://github.com/ardanlabs/service) — Starter-kit for writing services in Go using Kubernetes. ☆`3,807`
- [Shpota/goxygen](https://github.com/Shpota/goxygen) — Generate a modern Web project with Go and Angular, React, or Vue in seconds ☆`3,585`
- [mikestefanello/pagoda](https://github.com/mikestefanello/pagoda) — Rapid, easy full-stack web development starter kit and admin panel in Go ☆`2,555`
- [go-nunu/nunu](https://github.com/go-nunu/nunu) — A CLI tool for building Go applications. ☆`2,281`
- [sagikazarmark/modern-go-application](https://github.com/sagikazarmark/modern-go-application) — Modern Go Application example ☆`1,920`
- [naughtygopher/goapp](https://github.com/naughtygopher/goapp) — An opinionated guideline to structure & develop a Go web application/service ☆`978`
- [lacion/cookiecutter-golang](https://github.com/lacion/cookiecutter-golang) — A Go project template ☆`718`
- [allaboutapps/go-starter](https://github.com/allaboutapps/go-starter) — An opinionated production-ready SQL-/Swagger-first RESTful JSON API written in Go, highly integrated with VSCode DevContainers by allaboutapps. ☆`556`
- [golang-templates/seed](https://github.com/golang-templates/seed) — Go application GitHub repository template. ☆`527`
- [raeperd/kickstart.go](https://github.com/raeperd/kickstart.go) — Minimalistic HTTP server template in Go ☆`85`
- [wangyoucao577/go-project-layout](https://github.com/wangyoucao577/go-project-layout) — My understanding of how to structure a golang project. ☆`26`
### Strings

- [huandu/xstrings](https://github.com/huandu/xstrings) — Implements string functions widely used in other languages but absent in Go. ☆`1,408`
- [abhimanyu003/sttr](https://github.com/abhimanyu003/sttr) — cross-platform, cli app to perform various operations on string ☆`1,129`
- [gobeam/stringy](https://github.com/gobeam/stringy) — Convert string to camel case, snake case, kebab case / slugify, custom delimiter, pad string, tease string and many other functionalities with help of by Stringy package. ☆`250`
- [ozgio/strutil](https://github.com/ozgio/strutil) — String utilities for Go ☆`206`
### Uncategorized

- [shirou/gopsutil](https://github.com/shirou/gopsutil) — psutil for golang ☆`11,271`
- [TwiN/gatus](https://github.com/TwiN/gatus) — Automated developer-oriented status page ☆`7,606`
- [brianvoe/gofakeit](https://github.com/brianvoe/gofakeit) — Random fake data generator written in go ☆`4,967`
- [eapache/go-resiliency](https://github.com/eapache/go-resiliency) — Resiliency patterns for golang ☆`2,297`
- [mojocn/base64Captcha](https://github.com/mojocn/base64Captcha) — captcha of base64 image string ☆`2,253`
- [containrrr/shoutrrr](https://github.com/containrrr/shoutrrr) — Notification library for gophers and their furry friends. ☆`1,275`
- [qmuntal/stateless](https://github.com/qmuntal/stateless) — Go library for creating finite state machines ☆`1,074`
- [alexliesenfeld/health](https://github.com/alexliesenfeld/health) — A simple and flexible health check library for Go. ☆`812`
- [ulikunitz/xz](https://github.com/ulikunitz/xz) — Pure golang package for reading and writing xz-compressed files ☆`515`
- [dimiro1/health](https://github.com/dimiro1/health) — An easy to use, extensible health check library for Go applications. ☆`450`
- [ddddddO/gtree](https://github.com/ddddddO/gtree) — Using either Markdown or Programmatically to generate trees and directories, and to verify directories. Provide CLI, Go package and Web. ☆`302`
- [gen2brain/go-unarr](https://github.com/gen2brain/go-unarr) — Go bindings for unarr (decompression library for RAR, TAR, ZIP and 7z archives) ☆`293`
- [mholt/archives](https://github.com/mholt/archives) — Cross-platform library to create & extract archives, compress & decompress files, and walk virtual file systems across various formats ☆`253`
- [distatus/battery](https://github.com/distatus/battery) — cross-platform, normalized battery information library ☆`262`
- [steambap/captcha](https://github.com/steambap/captcha) — Package captcha provides an easy to use, unopinionated API for captcha generation ☆`159`
- [antham/gommit](https://github.com/antham/gommit) — Enforce git message commit consistency ☆`115`
- [osamingo/indigo](https://github.com/osamingo/indigo) — A distributed unique ID generator of using Sonyflake and encoded by Base58 ☆`110`
- [pioz/faker](https://github.com/pioz/faker) — Random fake data and struct generator for Go. ☆`99`
- [aofei/sandid](https://github.com/aofei/sandid) — Every grain of sand on Earth has its own ID. ☆`47`
- [rkoesters/xdg](https://github.com/rkoesters/xdg) — FreeDesktop.org (xdg) Specs implemented in Go ☆`48`
- [osamingo/gosh](https://github.com/osamingo/gosh) — Provide Go Statistics Handler, Struct, Measure Method ☆`35`
- [lrita/numa](https://github.com/lrita/numa) — NUMA is a utility library, which is written in go. It help us to write some NUMA-AWARED code. ☆`34`
## Natural Language Processing

### Language Detection

- [pemistahl/lingua-go](https://github.com/pemistahl/lingua-go) — The most accurate natural language detection library for Go, suitable for short text and mixed-language text ☆`1,249`
### Morphological Analyzers

- [nlpodyssey/spago](https://github.com/nlpodyssey/spago) — Self-contained Machine Learning and Natural Language Processing library in Go ☆`1,807`
- [ikawaha/kagome](https://github.com/ikawaha/kagome) — Self-contained Japanese Morphological Analyzer written in pure Go ☆`878`
- [afjoseph/RAKE.Go](https://github.com/afjoseph/RAKE.Go) — A Go port of the Rapid Automatic Keyword Extraction algorithm (RAKE) ☆`120`
- [jonreiter/govader](https://github.com/jonreiter/govader) — vader sentiment analysis in go ☆`50`
### Slugifiers

- [gosimple/slug](https://github.com/gosimple/slug) — URL-friendly slugify with multiple languages support. ☆`1,257`
### Tokenizers

- [go-ego/gse](https://github.com/go-ego/gse) — Go efficient multilingual NLP and text segmentation; support English, Chinese, Japanese and others. ☆`2,677`
- [pebbe/textcat](https://github.com/pebbe/textcat) — A Go package for n-gram based text categorization, with support for utf-8 and raw text ☆`73`
### Translation

- [nicksnyder/go-i18n](https://github.com/nicksnyder/go-i18n) — Translate your Go program into multiple languages. ☆`3,275`
- [leonelquinteros/gotext](https://github.com/leonelquinteros/gotext) — Go (Golang) GNU gettext utilities package ☆`473`
- [invopop/ctxi18n](https://github.com/invopop/ctxi18n) — Go Context Internationalization - translating apps easily ☆`72`
- [vorlif/spreak](https://github.com/vorlif/spreak) — Flexible translation and humanization library for Go, based on the concepts behind gettext. ☆`64`
- [mehanizm/iuliia-go](https://github.com/mehanizm/iuliia-go) — Transliterate Cyrillic → Latin in every possible way ☆`53`
- [youthlin/t](https://github.com/youthlin/t) — t: translation util for go, using GNU gettext ☆`20`
### Transliteration

- [alexsergivan/transliterator](https://github.com/alexsergivan/transliterator) — Golang text Transliterator (i.e München -> Muenchen) ☆`45`
## Networking

- [valyala/fasthttp](https://github.com/valyala/fasthttp) — Fast HTTP package for Go. Tuned for high performance. Zero memory allocations in hot paths. Up to 10x faster than net/http ☆`22,692`
- [pion/webrtc](https://github.com/pion/webrtc) — Pure Go implementation of the WebRTC API ☆`14,981`
- [xtaci/kcptun](https://github.com/xtaci/kcptun) — A Quantum-Safe Secure Tunnel based on QPP, KCP, FEC, and N:M multiplexing. ☆`14,156`
- [cloudflare/cloudflared](https://github.com/cloudflare/cloudflared) — Cloudflare Tunnel client (formerly Argo Tunnel) ☆`10,903`
- [quic-go/quic-go](https://github.com/quic-go/quic-go) — A QUIC implementation in pure Go ☆`10,780`
- [panjf2000/gnet](https://github.com/panjf2000/gnet) — gnet is a high-performance, lightweight, non-blocking, event-driven networking framework written in pure Go. ☆`10,615`
- [miekg/dns](https://github.com/miekg/dns) — DNS library in Go ☆`8,399`
- [google/gopacket](https://github.com/google/gopacket) — Provides packet processing capabilities for Go ☆`6,553`
- [elazarl/goproxy](https://github.com/elazarl/goproxy) — An HTTP proxy library for Go ☆`6,395`
- [cloudwego/netpoll](https://github.com/cloudwego/netpoll) — A high-performance non-blocking I/O networking framework focusing on RPC scenarios. ☆`4,338`
- [xtaci/kcp-go](https://github.com/xtaci/kcp-go) — A Crypto-Secure Reliable-UDP Library for golang with FEC ☆`4,280`
- [xjasonlyu/tun2socks](https://github.com/xjasonlyu/tun2socks) — tun2socks - powered by gVisor TCP/IP stack ☆`3,946`
- [gliderlabs/ssh](https://github.com/gliderlabs/ssh) — Easy SSH servers in Golang ☆`3,929`
- [osrg/gobgp](https://github.com/osrg/gobgp) — BGP implemented in the Go Programming Language ☆`3,820`
- [fortio/fortio](https://github.com/fortio/fortio) — Fortio load testing library, command line tool, advanced echo server and web UI in go (golang). Allows to specify a set query-per-second load and record latency histograms and other useful stats. ☆`3,548`
- [lesismal/nbio](https://github.com/lesismal/nbio) — Pure Go 1000k+ connections solution, support tls/http1.x/websocket and basically compatible with net/http, with high-performance and low memory cost, non-blocking, event-driven, easy-to-use. ☆`2,509`
- [songgao/water](https://github.com/songgao/water) — A simple TUN/TAP library written in native Go. ☆`2,046`
- [Allenxuxu/gev](https://github.com/Allenxuxu/gev) — Gev is a lightweight, fast non-blocking TCP network library / websocket server based on Reactor mode. Support custom protocols to quickly and easily build high-performance servers. ☆`1,754`
- [hashicorp/go-getter](https://github.com/hashicorp/go-getter) — Package for downloading things from a string URL using a variety of protocols. ☆`1,709`
- [pkg/sftp](https://github.com/pkg/sftp) — SFTP support for the go.crypto/ssh package ☆`1,585`
- [lxzan/gws](https://github.com/lxzan/gws) — simple, fast, reliable websocket server & client, supports running over tcp/kcp/unix domain socket. keywords: ws, proxy, chat, go, golang... ☆`1,563`
- [cavaliergopher/grab](https://github.com/cavaliergopher/grab) — A download manager package for Go ☆`1,443`
- [hashicorp/mdns](https://github.com/hashicorp/mdns) — Simple mDNS client/server library in Golang ☆`1,269`
- [gosnmp/gosnmp](https://github.com/gosnmp/gosnmp) — An SNMP library written in Go ☆`1,193`
- [yosebyte/nodepass](https://github.com/yosebyte/nodepass) — A secure, efficient TCP/UDP tunneling solution that delivers fast, reliable access across network restrictions using pre-established TLS/TCP connections ☆`1,056`
- [DrmagicE/gmqtt](https://github.com/DrmagicE/gmqtt) — Gmqtt is a flexible, high-performance MQTT broker library that fully implements the MQTT protocol V3.x and V5 in golang ☆`1,007`
- [semihalev/sdns](https://github.com/semihalev/sdns) — A high-performance, recursive DNS resolver server with DNSSEC support, focused on preserving privacy. ☆`997`
- [yahoo/vssh](https://github.com/yahoo/vssh) — Go Library to Execute Commands Over SSH at Scale ☆`972`
- [DarthPestilane/easytcp](https://github.com/DarthPestilane/easytcp) — EasyTCP is a light-weight TCP framework written in Go (Golang), built with message router. EasyTCP helps you build a TCP server easily fast and less painful. ☆`821`
- [xtaci/gaio](https://github.com/xtaci/gaio) — High performance minimalism async-io(proactor) networking for Golang. ☆`791`
- [ccding/go-stun](https://github.com/ccding/go-stun) — A go implementation of the STUN client (RFC 3489 and RFC 5389) ☆`709`
- [schollz/peerdiscovery](https://github.com/schollz/peerdiscovery) — Pure-Go library for cross-platform local peer discovery using UDP multicast ☆`659`
- [gansidui/gotcp](https://github.com/gansidui/gotcp) — A Go package for quickly building tcp servers ☆`514`
- [fclairamb/ftpserverlib](https://github.com/fclairamb/ftpserverlib) — golang ftp server library ☆`448`
- [masterzen/winrm](https://github.com/masterzen/winrm) — Command-line tool and library for Windows remote command execution in Go ☆`444`
- [mosajjal/dnsmonster](https://github.com/mosajjal/dnsmonster) — Passive DNS Capture and Monitoring Toolkit ☆`330`
- [google/gnxi](https://github.com/google/gnxi) — gNXI Tools - gRPC Network Management/Operations Interface Tools ☆`275`
- [udhos/jazigo](https://github.com/udhos/jazigo) — Jazigo is a tool written in Go for retrieving configuration for multiple devices, similar to rancid, fetchconfig, oxidized, Sweet. ☆`221`
- [jeroenrinzema/psql-wire](https://github.com/jeroenrinzema/psql-wire) — PostgreSQL server wire protocol. Build your own server and start serving connections. ☆`148`
- [lim-yoona/tcpack](https://github.com/lim-yoona/tcpack) — tcpack is an application protocol based on TCP to Pack and Unpack bytes stream in go program. ☆`170`
- [eduardonunesp/sslb](https://github.com/eduardonunesp/sslb) — Golang Super Simple Load Balance ☆`151`
- [c-robinson/iplib](https://github.com/c-robinson/iplib) — A library for working with IP addresses and networks in Go ☆`148`
- [joeig/go-powerdns](https://github.com/joeig/go-powerdns) — PowerDNS API client for Go (community project) ☆`97`
- [cheng-zhongliang/event](https://github.com/cheng-zhongliang/event) — Simple I/O event notification library wirtten in Golang ☆`120`
- [jimlambrt/gldap](https://github.com/jimlambrt/gldap) — Build LDAP services w/ Go ☆`114`
- [soypat/natiu-mqtt](https://github.com/soypat/natiu-mqtt) — A dead-simple, extensible MQTT implementation well suited for embedded systems. ☆`94`
- [gaissmai/bart](https://github.com/gaissmai/bart) — The Balanced Routing Table is an adaptation of D. Knuth's ART algorithm and requires significantly less memory and has an even better lookup speed. ☆`72`
- [shoriwe/fullproxy](https://github.com/shoriwe/fullproxy) — Proxy toolkit including SOCKS5, HTTP, port forward and reverse base proxying ☆`81`
- [alegrey91/fwdctl](https://github.com/alegrey91/fwdctl) — CLI tool to easily manage IPTables forwards ☆`66`
- [wzshiming/httpproxy](https://github.com/wzshiming/httpproxy) — HTTP proxy handler and dialer ☆`30`
- [fish-tennis/gnet](https://github.com/fish-tennis/gnet) — high performance net library for game server ☆`22`
### HTTP Clients

- [go-resty/resty](https://github.com/go-resty/resty) — Simple HTTP, REST, and SSE client library for Go ☆`11,005`
- [imroc/req](https://github.com/imroc/req) — Simple Go HTTP client with Black Magic ☆`4,535`
- [gojek/heimdall](https://github.com/gojek/heimdall) — An enhanced HTTP client for Go ☆`2,675`
- [hashicorp/go-retryablehttp](https://github.com/hashicorp/go-retryablehttp) — Retryable HTTP client in Go ☆`2,148`
- [levigross/grequests](https://github.com/levigross/grequests) — A Go "clone" of the great and famous Requests library ☆`2,157`
- [dghubble/sling](https://github.com/dghubble/sling) — A Go HTTP client library for creating and sending API requests ☆`1,705`
- [earthboundkid/requests](https://github.com/earthboundkid/requests) — HTTP requests for Gophers ☆`1,609`
- [bogdanfinn/tls-client](https://github.com/bogdanfinn/tls-client) — net/http.Client like HTTP Client with options to select specific client TLS Fingerprints to use for requests. ☆`1,180`
- [monaco-io/request](https://github.com/monaco-io/request) — go request, go http client ☆`292`
- [Noooste/azuretls-client](https://github.com/Noooste/azuretls-client) — An easy-to-use HTTP client to spoof TLS/JA3, HTTP2 and HTTP3 fingerprint ☆`270`
- [go-zoox/fetch](https://github.com/go-zoox/fetch) — Go Fetch - A Powerful, Lightweight, Easy Http Client, inspired by Web Fetch API ☆`78`
- [opus-domini/fast-shot](https://github.com/opus-domini/fast-shot) — Hit your API targets with rapid-fire precision using Go's fastest and simple HTTP Client. ☆`85`
- [NdoleStudio/go-otelroundtripper](https://github.com/NdoleStudio/go-otelroundtripper) — Go http.RoundTripper that emits open telemetry metrics. This helps you easily get metrics for all external APIs you interact with. ☆`85`
- [rezmoss/axios4go](https://github.com/rezmoss/axios4go) — A Go HTTP client library inspired by Axios, providing a simple and intuitive API for making HTTP requests with features like interceptors, JSON handling, configurable instances, and automatic retries ☆`28`
## OpenGL

- [go-gl/glfw](https://github.com/go-gl/glfw) — Go bindings for GLFW 3 ☆`1,629`
- [go-gl/gl](https://github.com/go-gl/gl) — Go bindings for OpenGL (generated via glow) ☆`1,159`
- [go-gl/mathgl](https://github.com/go-gl/mathgl) — A pure Go 3D math library. ☆`579`
- [goxjs/gl](https://github.com/goxjs/gl) — Go cross-platform OpenGL bindings. ☆`178`
- [goxjs/glfw](https://github.com/goxjs/glfw) — Go cross-platform glfw library for creating an OpenGL context and receiving events. ☆`83`
## ORM

- [go-gorm/gorm](https://github.com/go-gorm/gorm) — The fantastic ORM library for Golang, aims to be developer friendly ☆`38,423`
- [ent/ent](https://github.com/ent/ent) — An entity framework for Go ☆`16,302`
- [aarondl/sqlboiler](https://github.com/aarondl/sqlboiler) — Generate a Go ORM tailored to your database schema. ☆`6,885`
- [uptrace/bun](https://github.com/uptrace/bun) — SQL-first Golang ORM ☆`4,224`
- [upper/db](https://github.com/upper/db) — Data Access Layer (DAL) for PostgreSQL, CockroachDB, MySQL, SQLite and MongoDB with ORM-like features. ☆`3,600`
- [steebchen/prisma-client-go](https://github.com/steebchen/prisma-client-go) — Prisma Client Go is an auto-generated and fully type-safe database client ☆`2,304`
- [huandu/go-sqlbuilder](https://github.com/huandu/go-sqlbuilder) — A flexible and powerful SQL string builder library plus a zero-config ORM. ☆`1,564`
- [stephenafamo/bob](https://github.com/stephenafamo/bob) — SQL query builder and ORM/Factory generator for Go with support for PostgreSQL, MySQL and SQLite ☆`1,327`
- [go-rel/rel](https://github.com/go-rel/rel) — Modern ORM for Golang - Testable, Extendable and Crafted Into a Clean and Elegant API ☆`783`
- [hashicorp/go-dbw](https://github.com/hashicorp/go-dbw) — A simple package that encapsulates database operations. ☆`17`
- [FrancoLiberali/cql](https://github.com/FrancoLiberali/cql) — CQL: Compiled Query Language ☆`17`
## Package Management

- [anchore/syft](https://github.com/anchore/syft) — CLI tool and library for generating a Software Bill of Materials from container images and filesystems ☆`7,261`
- [nao1215/gup](https://github.com/nao1215/gup) — gup - Update binaries installed by "go install" with goroutines. ☆`415`
## Performance

- [jaegertracing/jaeger](https://github.com/jaegertracing/jaeger) — CNCF Jaeger, a Distributed Tracing Platform ☆`21,520`
- [pixie-io/pixie](https://github.com/pixie-io/pixie) — Instant Kubernetes-Native Application Observability ☆`6,069`
- [arl/statsviz](https://github.com/arl/statsviz) — Visualise your Go program runtime metrics in real time in the browser ☆`3,306`
- [nikolaydubina/go-instrument](https://github.com/nikolaydubina/go-instrument) — Automatically add Trace Spans to Go methods and functions ☆`268`
- [joetifa2003/mm-go](https://github.com/joetifa2003/mm-go) — Generic manual memory management for golang ☆`171`
## Query Language

- [99designs/gqlgen](https://github.com/99designs/gqlgen) — go generate based graphql server library ☆`10,394`
- [TomWright/dasel](https://github.com/TomWright/dasel) — Select, put and delete data from JSON, TOML, YAML, XML and CSV files with a single tool. Supports conversion between formats and can be used as a Go package. ☆`7,488`
- [graph-gophers/graphql-go](https://github.com/graph-gophers/graphql-go) — GraphQL server with a focus on ease of use ☆`4,711`
- [bhmj/jsonslice](https://github.com/bhmj/jsonslice) — json slicer ☆`92`
- [timsolov/rest-query-parser](https://github.com/timsolov/rest-query-parser) — Query Parser for REST ☆`85`
- [hashicorp/mql](https://github.com/hashicorp/mql) — Model Query Language (mql) is a query language for your database models. ☆`60`
- [ccbrown/api-fu](https://github.com/ccbrown/api-fu) — A collection of Go packages for creating robust GraphQL APIs ☆`57`
- [AsaiYusuke/jsonpath](https://github.com/AsaiYusuke/jsonpath) — A query library for retrieving part of JSON based on JSONPath syntax. ☆`26`
## Reflection

- [tiendc/go-deepcopy](https://github.com/tiendc/go-deepcopy) — Fast deep-copy library for Go ☆`97`
- [wzshiming/gotype](https://github.com/wzshiming/gotype) — Golang source code parsing, usage like reflect package ☆`63`
## Resource Embedding

- [shurcooL/vfsgen](https://github.com/shurcooL/vfsgen) — Takes an input http.FileSystem (likely at go generate time) and generates Go code that statically implements it. ☆`982`
## Routers

- [gorilla/mux](https://github.com/gorilla/mux) — Package gorilla/mux is a powerful HTTP router and URL matcher for building Go web servers with ☆`21,429`
- [go-chi/chi](https://github.com/go-chi/chi) — lightweight, idiomatic and composable router for building Go HTTP services ☆`20,022`
- [gowww/router](https://github.com/gowww/router) — A lightning fast HTTP router ☆`185`
- [go-playground/pure](https://github.com/go-playground/pure) — Is a lightweight HTTP router that sticks to the std "net/http" implementation ☆`150`
- [gernest/alien](https://github.com/gernest/alien) — A lightweight and fast http router from outer space ☆`135`
- [bmf-san/goblin](https://github.com/bmf-san/goblin) — A golang http router based on trie tree. ☆`80`
- [ngamux/ngamux](https://github.com/ngamux/ngamux) — Simple HTTP router for Go ☆`71`
- [muir/nchi](https://github.com/muir/nchi) — golang http router with elegance, speed, and flexibility ☆`18`
## Science and Data Analysis

- [gonum/gonum](https://github.com/gonum/gonum) — Gonum is a set of numeric libraries for the Go programming language. It contains libraries for matrices, statistics, optimization, and more ☆`8,064`
- [gonum/plot](https://github.com/gonum/plot) — A repository for plotting and visualizing data ☆`2,875`
- [nytlabs/streamtools](https://github.com/nytlabs/streamtools) — tools for working with streams of data ☆`1,311`
- [paulmach/orb](https://github.com/paulmach/orb) — Types and utilities for working with 2d geometry in Golang ☆`1,001`
- [maddyblue/go-dsp](https://github.com/maddyblue/go-dsp) — Digital Signal Processing for Go ☆`880`
- [bebop/poly](https://github.com/bebop/poly) — A Go package for engineering organisms. ☆`704`
- [go-hep/hep](https://github.com/go-hep/hep) — hep is the mono repository holding all of go-hep.org/x/hep packages and tools ☆`247`
- [hmdsefi/gograph](https://github.com/hmdsefi/gograph) — A golang generic graph library that provides mathematical graph-theory and algorithms. ☆`86`
- [nikolaydubina/jsonl-graph](https://github.com/nikolaydubina/jsonl-graph) — JSONL Graph Tools ☆`75`
- [claygod/PiHex](https://github.com/claygod/PiHex) — PiHex Library, written in Go, generates a hexadecimal number sequence in the number Pi in the range from 0 to 10,000,000. ☆`20`
- [ndabAP/assocentity](https://github.com/ndabAP/assocentity) — Package assocentity returns the mean distance from tokens to an entity and its synonyms ☆`17`
- [sgreben/piecewiselinear](https://github.com/sgreben/piecewiselinear) — tiny linear interpolation library for go ☆`28`
## Security

- [FiloSottile/age](https://github.com/FiloSottile/age) — A simple, modern and secure encryption tool (and Go library) with small explicit keys, no config options, and UNIX-style composability. ☆`19,131`
- [go-acme/lego](https://github.com/go-acme/lego) — Let's Encrypt/ACME client and library written in Go ☆`8,690`
- [caddyserver/certmagic](https://github.com/caddyserver/certmagic) — Automatic HTTPS for any Go program: fully-managed TLS certificate issuance and renewal ☆`5,267`
- [Ullaakut/cameradar](https://github.com/Ullaakut/cameradar) — Cameradar hacks its way into RTSP videosurveillance cameras ☆`4,435`
- [corazawaf/coraza](https://github.com/corazawaf/coraza) — OWASP Coraza WAF is a golang modsecurity compatible web application firewall library ☆`2,719`
- [awnumar/memguard](https://github.com/awnumar/memguard) — Secure software enclave for storage of sensitive information in memory. ☆`2,638`
- [unrolled/secure](https://github.com/unrolled/secure) — HTTP middleware for Go that facilitates some quick security wins. ☆`2,310`
- [cossacklabs/themis](https://github.com/cossacklabs/themis) — Easy to use cryptographic framework for data protection: secure messaging with forward secrecy and secure data storage. Has unified APIs across 14 platforms. ☆`1,926`
- [cossacklabs/acra](https://github.com/cossacklabs/acra) — Database security suite. Database proxy with field-level encryption, search through encrypted data, SQL injections prevention, intrusion detection, honeypots. Supports client-side and proxy-side ("transparent") encryption. SQL, NoSQL. ☆`1,404`
- [mariocandela/beelzebub](https://github.com/mariocandela/beelzebub) — A secure low code honeypot framework, leveraging LLM for System Virtualization. ☆`1,187`
- [dromara/dongle](https://github.com/dromara/dongle) — A simple, semantic and developer-friendly golang crypto package ☆`985`
- [anatol/booster](https://github.com/anatol/booster) — Fast and secure initramfs generator ☆`568`
- [kevinburke/nacl](https://github.com/kevinburke/nacl) — Pure Go implementation of the NaCL set of API's ☆`547`
- [ssh-vault/ssh-vault](https://github.com/ssh-vault/ssh-vault) — encrypt/decrypt using ssh keys ☆`471`
- [hillu/go-yara](https://github.com/hillu/go-yara) — Go bindings for YARA ☆`372`
- [teler-sh/teler-waf](https://github.com/teler-sh/teler-waf) — teler-waf is a Go HTTP middleware that protects local web services from OWASP Top 10 threats, known vulnerabilities, malicious actors, botnets, unwanted crawlers, and brute force attacks. ☆`380`
- [number571/go-peer](https://github.com/number571/go-peer) — Library for developing secure, decentralized, anonymous and quantum-resistant networks in Go language ☆`294`
- [anatol/luks.go](https://github.com/anatol/luks.go) — Pure Golang library to manage LUKS partitions ☆`90`
- [zitadel/passwap](https://github.com/zitadel/passwap) — Package passwap provides a unified implementation between different password hashing algorithms. It allows for easy swapping between algorithms, using the same API for all of them. ☆`66`
- [tg123/go-htpasswd](https://github.com/tg123/go-htpasswd) — Apache htpasswd Parser for Go. ☆`44`
- [adrianosela/sslmgr](https://github.com/adrianosela/sslmgr) — A layer of abstraction the around acme/autocert certificate manager (Golang) ☆`30`
- [andskur/argon2-hashing](https://github.com/andskur/argon2-hashing) — A light package for generating and comparing password hashing with argon2 in Go ☆`22`
- [rsjethani/secret](https://github.com/rsjethani/secret) — Prevent your secrets from leaking into logs, std* etc. ☆`31`
- [bitfield/qrand](https://github.com/bitfield/qrand) — Quantum randomness source using the ANU hardware QRNG ☆`16`
## Serialization

- [golang/protobuf](https://github.com/golang/protobuf) — Go support for Google's protocol buffers ☆`9,962`
- [ugorji/go](https://github.com/ugorji/go) — idiomatic codec and rpc lib for msgpack, cbor, json, etc. msgpack.org[Go] ☆`1,895`
- [jszwec/csvutil](https://github.com/jszwec/csvutil) — csvutil provides fast and idiomatic mapping between CSV and Go (golang) values. ☆`986`
- [fxamacker/cbor](https://github.com/fxamacker/cbor) — CBOR codec (RFC 8949, RFC 8742) with CBOR tags, Go struct tag options (toarray, keyasint, omitempty, omitzero), float64/32/16, big.Int, and fuzz tested. ☆`886`
- [ghostiam/binstruct](https://github.com/ghostiam/binstruct) — Golang binary decoder for mapping data into the structure ☆`106`
- [csweichel/bel](https://github.com/csweichel/bel) — Generate TypeScript interfaces from Go structs/interfaces - useful for JSON RPC ☆`44`
- [o1egl/fwencoder](https://github.com/o1egl/fwencoder) — Fixed width file parser (encoder/decoder) in GO (golang) ☆`27`
- [tiendc/go-csvlib](https://github.com/tiendc/go-csvlib) — High-level performant CSV encoding and decoding library ☆`18`
## Server Applications

- [caddyserver/caddy](https://github.com/caddyserver/caddy) — Fast and extensible multi-platform HTTP/1-2-3 web server with automatic HTTPS ☆`65,181`
- [minio/minio](https://github.com/minio/minio) — MinIO is a high-performance, S3 compatible object store, open sourced under GNU AGPLv3 license. ☆`53,404`
- [etcd-io/etcd](https://github.com/etcd-io/etcd) — Distributed reliable key-value store for the most critical data of a distributed system ☆`49,710`
- [pocketbase/pocketbase](https://github.com/pocketbase/pocketbase) — Open Source realtime backend in 1 file ☆`47,988`
- [drakkan/sftpgo](https://github.com/drakkan/sftpgo) — Full-featured and highly configurable SFTP, HTTP/S, FTP/S and WebDAV server - S3, Google Cloud Storage, Azure Blob ☆`10,631`
- [roadrunner-server/roadrunner](https://github.com/roadrunner-server/roadrunner) — High-performance PHP application server, process manager written in Go and powered with plugins ☆`8,176`
- [easegress-io/easegress](https://github.com/easegress-io/easegress) — A Cloud Native traffic orchestration system ☆`5,833`
- [flipt-io/flipt](https://github.com/flipt-io/flipt) — Enterprise-ready, GitOps enabled, CloudNative feature management solution ☆`4,440`
- [charmbracelet/wish](https://github.com/charmbracelet/wish) — Make SSH apps, just like that! ☆`4,174`
- [getfider/fider](https://github.com/getfider/fider) — Open platform to collect and prioritize feedback ☆`3,568`
- [xyproto/algernon](https://github.com/xyproto/algernon) — Small self-contained pure-Go web server with Lua, Teal, Markdown, Ollama, HTTP/2, QUIC, Redis, SQLite and PostgreSQL support ++ ☆`2,918`
- [openflagr/flagr](https://github.com/openflagr/flagr) — Flagr is a feature flagging, A/B testing and dynamic configuration microservice ☆`2,503`
- [thomaspoignant/go-feature-flag](https://github.com/thomaspoignant/go-feature-flag) — GO Feature Flag is a simple, complete and lightweight self-hosted feature flag solution 100% Open Source. ☆`1,684`
- [claceio/clace](https://github.com/claceio/clace) — Application server for deploying containerized web apps. Easily deploy internal tools across a team. ☆`636`
- [blind-oracle/cortex-tenant](https://github.com/blind-oracle/cortex-tenant) — Prometheus remote write proxy that adds Cortex/Mimir tenant ID based on metric labels ☆`123`
- [baalimago/wd-41](https://github.com/baalimago/wd-41) — Web-Development 41, a static web server with live-reload ☆`149`
- [rekby/lets-proxy2](https://github.com/rekby/lets-proxy2) — Reverse proxy with automatically obtains TLS certificates from Let's Encrypt ☆`100`
## Software Packages

### DevOps Tools

- [kubernetes/kubernetes](https://github.com/kubernetes/kubernetes) — Production-Grade Container Scheduling and Management ☆`116,006`
- [moby/moby](https://github.com/moby/moby) — The Moby Project - a collaborative project for the container ecosystem to assemble container-based systems ☆`69,992`
- [traefik/traefik](https://github.com/traefik/traefik) — The Cloud Native Application Proxy ☆`55,317`
- [go-gitea/gitea](https://github.com/go-gitea/gitea) — Git with a cup of tea! Painless self-hosted all-in-one software development service, including Git hosting, code review, team collaboration, package registry and CI/CD ☆`49,279`
- [kubernetes/minikube](https://github.com/kubernetes/minikube) — Run Kubernetes locally ☆`30,603`
- [k3s-io/k3s](https://github.com/k3s-io/k3s) — Lightweight Kubernetes ☆`30,071`
- [grafana/k6](https://github.com/grafana/k6) — A modern load testing tool, using Go and JavaScript ☆`28,136`
- [tsenart/vegeta](https://github.com/tsenart/vegeta) — HTTP load testing tool and library. It's over 9000! ☆`24,315`
- [hashicorp/packer](https://github.com/hashicorp/packer) — Packer is a tool for creating identical machine images for multiple platforms from a single source configuration. ☆`15,402`
- [kubernetes-sigs/kind](https://github.com/kubernetes-sigs/kind) — Kubernetes IN Docker - local clusters for testing Kubernetes ☆`14,248`
- [kubeshark/kubeshark](https://github.com/kubeshark/kubeshark) — The API traffic analyzer for Kubernetes providing real-time K8s protocol-level visibility, capturing and monitoring all traffic and payloads going in, out and across containers, pods, nodes and clusters. Inspired by Wireshark, purposely built for Kubernetes ☆`11,400`
- [moovweb/gvm](https://github.com/moovweb/gvm) — Go Version Manager ☆`11,031`
- [flannel-io/flannel](https://github.com/flannel-io/flannel) — flannel is a network fabric for containers, designed for Kubernetes ☆`9,165`
- [getanteon/anteon](https://github.com/getanteon/anteon) — Anteon (formerly Ddosify) - Effortless Kubernetes Monitoring and Performance Testing. Available on CLI, Self-Hosted, and Cloud ☆`8,478`
- [ko-build/ko](https://github.com/ko-build/ko) — Build and deploy Go applications ☆`8,050`
- [kubevela/kubevela](https://github.com/kubevela/kubevela) — The Modern Application Platform. ☆`6,744`
- [bitfield/script](https://github.com/bitfield/script) — Making it easy to write shell-like scripts in Go ☆`6,763`
- [codesenberg/bombardier](https://github.com/codesenberg/bombardier) — Fast cross-platform HTTP benchmarking tool written in Go ☆`6,409`
- [stefanprodan/podinfo](https://github.com/stefanprodan/podinfo) — Go microservice template for Kubernetes ☆`5,628`
- [k3d-io/k3d](https://github.com/k3d-io/k3d) — Little helper to run CNCF's k3s in Docker ☆`5,870`
- [fleetdm/fleet](https://github.com/fleetdm/fleet) — Open device management ☆`5,150`
- [gaia-pipeline/gaia](https://github.com/gaia-pipeline/gaia) — Build powerful pipelines in any programming language. ☆`5,226`
- [pomerium/pomerium](https://github.com/pomerium/pomerium) — Pomerium is an identity and context-aware access proxy. ☆`4,321`
- [taubyte/tau](https://github.com/taubyte/tau) — Open source distributed Platform as a Service (PaaS). A self-hosted Vercel / Netlify / Cloudflare alternative. ☆`4,041`
- [peak/s5cmd](https://github.com/peak/s5cmd) — Parallel S3 and local filesystem execution tool. ☆`3,371`
- [apecloud/kubeblocks](https://github.com/apecloud/kubeblocks) — KubeBlocks is an open-source control plane software that runs and manages databases, message queues and other stateful applications on K8s. ☆`2,747`
- [aptly-dev/aptly](https://github.com/aptly-dev/aptly) — aptly - Debian repository management tool ☆`2,669`
- [ajvb/kala](https://github.com/ajvb/kala) — Modern Job Scheduler ☆`2,154`
- [gabrie30/ghorg](https://github.com/gabrie30/ghorg) — Quickly clone or backup an entire org/users repositories into one directory - Supports GitHub, GitLab, Bitbucket, and more ☆`1,764`
- [sanbornm/go-selfupdate](https://github.com/sanbornm/go-selfupdate) — Enable your Go applications to self update ☆`1,617`
- [yusufcanb/tlm](https://github.com/yusufcanb/tlm) — Local CLI Copilot, powered by Ollama. ☆`1,432`
- [ovh/utask](https://github.com/ovh/utask) — µTask is an automation engine that models and executes business processes declared in yaml. ☆`1,288`
- [pipe-cd/pipecd](https://github.com/pipe-cd/pipecd) — The One CD for All {applications, platforms, operations} ☆`1,179`
- [kubenetworks/kubevpn](https://github.com/kubenetworks/kubevpn) — KubeVPN offers a Cloud Native Dev Environment that connects to kubernetes cluster network. ☆`1,178`
- [KusionStack/kusion](https://github.com/KusionStack/kusion) — Declarative Intent Driven Platform Orchestrator for Internal Developer Platform (IDP). ☆`1,137`
- [abahmed/kwatch](https://github.com/abahmed/kwatch) — monitor & detect crashes in your Kubernetes(K8s) cluster instantly ☆`982`
- [TimothyYe/skm](https://github.com/TimothyYe/skm) — A simple and powerful SSH keys manager ☆`977`
- [scaleway/scaleway-cli](https://github.com/scaleway/scaleway-cli) — Command Line Interface for Scaleway ☆`922`
- [rogerwelin/cassowary](https://github.com/rogerwelin/cassowary) — Modern cross-platform HTTP load-testing tool written in Go ☆`802`
- [kool-dev/kool](https://github.com/kool-dev/kool) — From local development to the cloud: web apps development with containers made easy. ☆`687`
- [getanteon/alaz](https://github.com/getanteon/alaz) — Alaz: Advanced eBPF Agent for Kubernetes Observability – Effortlessly monitor K8s service interactions and performance metrics in your K8s environment. Gain in-depth insights with service maps, metrics, and more, while staying alert to crucial system anomalies ☆`688`
- [jenkins-zh/jenkins-cli](https://github.com/jenkins-zh/jenkins-cli) — Jenkins CLI allows you to manage your Jenkins in an easy way ☆`405`
- [kevincobain2000/gobrew](https://github.com/kevincobain2000/gobrew) — Go version manager, written in Go. Super simple tool to install and manage Go versions. Install go without root. Gobrew doesn't require shell rehash. ☆`395`
- [oxyno-zeta/s3-proxy](https://github.com/oxyno-zeta/s3-proxy) — S3 Reverse Proxy with GET, PUT and DELETE methods and authentication (OpenID Connect and Basic Auth) ☆`362`
- [xitonix/trubka](https://github.com/xitonix/trubka) — A CLI tool for Kafka ☆`333`
- [appleboy/easyssh-proxy](https://github.com/appleboy/easyssh-proxy) — easyssh-proxy provides a simple implementation of some SSH protocol features in Go ☆`331`
- [emicklei/mora](https://github.com/emicklei/mora) — MongoDB generic REST server in Go ☆`316`
- [appleboy/drone-scp](https://github.com/appleboy/drone-scp) — Copy files and artifacts via SSH using a binary, docker or Drone CI. ☆`155`
- [datarootsio/tf-profile](https://github.com/datarootsio/tf-profile) — CLI tool to profile Terraform runs, written in Go ☆`158`
- [s0rg/decompose](https://github.com/s0rg/decompose) — Reverse-engineering tool for docker environments ☆`104`
- [x1unix/docker-go-mingw](https://github.com/x1unix/docker-go-mingw) — Docker image for building Go binaries with MinGW toolchain. Supports Windows on ARM! ☆`51`
- [appleboy/drone-jenkins](https://github.com/appleboy/drone-jenkins) — Drone plugin for trigger Jenkins jobs. ☆`38`
### Other Software

- [schollz/croc](https://github.com/schollz/croc) — Easily and securely send things from one computer to another ☆`30,451`
- [restic/restic](https://github.com/restic/restic) — Fast, secure, efficient backup program ☆`29,120`
- [seaweedfs/seaweedfs](https://github.com/seaweedfs/seaweedfs) — SeaweedFS is a fast distributed storage system for blobs, objects, files, and data lake, for billions of files! Blob store has O(1) disk seek, cloud tiering. Filer supports Cloud Drive, xDC replication, Kubernetes, POSIX FUSE mount, S3 API, S3 Gateway, Hadoop, WebDAV, encryption, Erasure Coding. Enterprise version is at seaweedfs.com. ☆`24,948`
- [juicedata/juicefs](https://github.com/juicedata/juicefs) — JuiceFS is a distributed POSIX file system built on top of Redis and S3. ☆`11,789`
- [Shopify/toxiproxy](https://github.com/Shopify/toxiproxy) — A TCP proxy to simulate network and system conditions for chaos and resiliency testing ☆`11,334`
- [visualfc/liteide](https://github.com/visualfc/liteide) — LiteIDE is a simple, open source, cross-platform Go IDE. ☆`7,691`
- [boyter/scc](https://github.com/boyter/scc) — Sloc, Cloc and Code: scc is a very fast accurate code counter with complexity calculations and COCOMO estimates written in pure Go ☆`7,431`
- [fogleman/nes](https://github.com/fogleman/nes) — NES emulator written in Go. ☆`5,569`
- [gilbertchen/duplicacy](https://github.com/gilbertchen/duplicacy) — A new generation cloud backup tool ☆`5,468`
- [0xERR0R/blocky](https://github.com/0xERR0R/blocky) — Fast and lightweight DNS proxy as ad-blocker for local network with many features ☆`5,418`
- [documize/community](https://github.com/documize/community) — Modern Confluence alternative designed for internal & external docs, built with Go + EmberJS ☆`2,264`
- [go-sonic/sonic](https://github.com/go-sonic/sonic) — Sonic is a blogging platform developed by Go. Simple and powerful ☆`2,092`
- [Forceu/Gokapi](https://github.com/Forceu/Gokapi) — Lightweight selfhosted Firefox Send alternative without public upload. AWS S3 supported. ☆`1,985`
- [gocircuit/circuit](https://github.com/gocircuit/circuit) — Circuit: Dynamic cloud orchestration ☆`1,987`
- [SpatiumPortae/portal](https://github.com/SpatiumPortae/portal) — Portal is a quick and easy command-line file transfer utility from any computer to another ☆`1,655`
- [root-gg/plik](https://github.com/root-gg/plik) — Plik is a temporary file upload system (Wetransfer like) in Go. ☆`1,578`
- [msoap/shell2http](https://github.com/msoap/shell2http) — Executing shell commands via HTTP server ☆`1,413`
- [pointlander/peg](https://github.com/pointlander/peg) — Peg, Parsing Expression Grammar, is an implementation of a Packrat parser generator. ☆`1,062`
- [janpfeifer/gonb](https://github.com/janpfeifer/gonb) — GoNB, a Go Notebook Kernel for Jupyter ☆`876`
- [shurcooL/Go-Package-Store](https://github.com/shurcooL/Go-Package-Store) — An app that displays updates for the Go packages in your GOPATH. ☆`897`
- [alajmo/sake](https://github.com/alajmo/sake) — task runner for local and remote hosts ☆`700`
- [goccmack/gocc](https://github.com/goccmack/gocc) — Parser / Scanner Generator ☆`642`
- [moshebe/gebug](https://github.com/moshebe/gebug) — Debug Dockerized Go applications better ☆`632`
- [chapar-rest/chapar](https://github.com/chapar-rest/chapar) — Chapar is a simple and easy to use api testing tools aims to help developers to test their api endpoints. it support http and grpc protocols. ☆`581`
- [edwingeng/hotswap](https://github.com/edwingeng/hotswap) — A complete solution to reload your go code without restarting your server, interrupting or blocking any ongoing procedure. ☆`397`
- [s0rg/crawley](https://github.com/s0rg/crawley) — The unix-way web crawler ☆`302`
- [marwanhawari/stew](https://github.com/marwanhawari/stew) — An independent package manager for compiled binaries. ☆`273`
- [assafmo/joincap](https://github.com/assafmo/joincap) — Merge multiple pcap files together, gracefully. ☆`217`
- [mk-5/fjira](https://github.com/mk-5/fjira) — The golang fuzzy-find cli jira interface ☆`181`
- [lingrino/vaku](https://github.com/lingrino/vaku) — vaku extends the vault api & cli ☆`155`
## Stream Processing

- [reugn/go-streams](https://github.com/reugn/go-streams) — A lightweight stream processing library for Go ☆`2,049`
- [whitaker-io/machine](https://github.com/whitaker-io/machine) — Machine is a workflow/pipeline library for processing data ☆`162`
- [Breeze0806/go-etl](https://github.com/Breeze0806/go-etl) — go-etl is a toolset for data extraction, transformation and loading. ☆`149`
## Style Guides

- [bahlo/go-styleguide](https://github.com/bahlo/go-styleguide) — Opinionated Styleguide for the Go language ☆`1,510`
## Template Engines

- [a-h/templ](https://github.com/a-h/templ) — A language for writing HTML user interfaces in Go. ☆`9,427`
- [valyala/quicktemplate](https://github.com/valyala/quicktemplate) — Fast, powerful, yet easy to use template engine for Go. Optimized for speed, zero memory allocations in hot paths. Up to 20x faster than html/template ☆`3,230`
- [johnfercher/maroto](https://github.com/johnfercher/maroto) — A maroto way to create PDFs. Maroto is inspired in Bootstrap and uses gofpdf. Fast and simple. ☆`2,467`
- [CloudyKit/jet](https://github.com/CloudyKit/jet) — Jet template engine ☆`1,335`
- [valyala/fasttemplate](https://github.com/valyala/fasttemplate) — Simple and fast template engine for Go ☆`874`
- [osteele/liquid](https://github.com/osteele/liquid) — A Liquid template engine in Go ☆`307`
- [go-sprout/sprout](https://github.com/go-sprout/sprout) — From sprig to sprout - Useful template functions for Go templates with steroids ☆`172`
- [robfig/soy](https://github.com/robfig/soy) — Go implementation for Soy templates (Google Closure templates) ☆`175`
- [goradd/got](https://github.com/goradd/got) — GoT is a template engine that turns templates into Go code to compile into your app. ☆`37`
## Testing

### Fail injection

- [pingcap/failpoint](https://github.com/pingcap/failpoint) — An implementation of failpoints for Golang. ☆`852`
### Fuzzing

- [dvyukov/go-fuzz](https://github.com/dvyukov/go-fuzz) — Randomized testing for Go ☆`4,833`
### Mock

- [vektra/mockery](https://github.com/vektra/mockery) — A mock code autogenerator for Go ☆`6,655`
- [DATA-DOG/go-sqlmock](https://github.com/DATA-DOG/go-sqlmock) — Sql mock driver for golang to test database interactions ☆`6,385`
- [uber-go/mock](https://github.com/uber-go/mock) — GoMock is a mocking framework for the Go programming language. ☆`2,872`
- [SpectoLabs/hoverfly](https://github.com/SpectoLabs/hoverfly) — Lightweight service virtualization/ API simulation / API mocking tool for developers and testers ☆`2,421`
- [matryer/moq](https://github.com/matryer/moq) — Interface mocking tool for go generate ☆`2,102`
- [jarcoal/httpmock](https://github.com/jarcoal/httpmock) — HTTP mocking for Golang ☆`2,034`
- [maxbrunsfeld/counterfeiter](https://github.com/maxbrunsfeld/counterfeiter) — A tool for generating self-contained, type-safe test doubles in go ☆`1,052`
- [DATA-DOG/go-txdb](https://github.com/DATA-DOG/go-txdb) — Immutable transaction isolated sql driver for golang ☆`720`
- [gojuno/minimock](https://github.com/gojuno/minimock) — Powerful mock generation tool for Go programming language ☆`690`
- [pashagolub/pgxmock](https://github.com/pashagolub/pgxmock) — pgx mock driver for golang to test database interactions ☆`486`
- [xhd2015/xgo](https://github.com/xhd2015/xgo) — All-in-one go testing library ☆`408`
- [seborama/govcr](https://github.com/seborama/govcr) — HTTP mock for Golang: record and replay HTTP/HTTPS interactions for offline testing ☆`188`
- [elgohr/go-localstack](https://github.com/elgohr/go-localstack) — Go Wrapper for using localstack ☆`83`
### Selenium and browser control tools

- [chromedp/chromedp](https://github.com/chromedp/chromedp) — A faster, simpler way to drive browsers supporting the Chrome DevTools Protocol. ☆`11,965`
- [go-rod/rod](https://github.com/go-rod/rod) — A Chrome DevTools Protocol driver for web automation and scraping. ☆`6,029`
- [playwright-community/playwright-go](https://github.com/playwright-community/playwright-go) — Playwright for Go a browser automation library to control Chromium, Firefox and WebKit with a single API. ☆`2,756`
- [mafredri/cdp](https://github.com/mafredri/cdp) — Package cdp provides type-safe bindings for the Chrome DevTools Protocol (CDP), written in the Go programming language. ☆`754`
### Testing Frameworks

- [stretchr/testify](https://github.com/stretchr/testify) — A toolkit with common assertions and mocks that plays nicely with the standard library ☆`24,834`
- [keploy/keploy](https://github.com/keploy/keploy) — Unit, API & Integration Testing Agent for Developers. Generate tests, mocks/stubs for your APIs that actually work! ☆`10,277`
- [google/go-cmp](https://github.com/google/go-cmp) — Package for comparing Go values in tests ☆`4,440`
- [testcontainers/testcontainers-go](https://github.com/testcontainers/testcontainers-go) — Testcontainers for Go is a Go package that makes it simple to create and clean up container-based dependencies for automated integration/smoke tests. The clean, easy-to-use API enables developers to programmatically define containers that should be run as part of a test and clean up those resources when the test is done. ☆`4,153`
- [gavv/httpexpect](https://github.com/gavv/httpexpect) — End-to-end HTTP and REST API testing for Go. ☆`2,650`
- [cucumber/godog](https://github.com/cucumber/godog) — Cucumber for golang ☆`2,449`
- [orlangure/gnomock](https://github.com/orlangure/gnomock) — Test your code without writing mocks with ephemeral Docker containers Setup popular services with just a couple lines of code No bash, no yaml, only code ☆`1,443`
- [dnaeon/go-vcr](https://github.com/dnaeon/go-vcr) — Record and replay your HTTP interactions for fast, deterministic and accurate tests ☆`1,311`
- [go-testfixtures/testfixtures](https://github.com/go-testfixtures/testfixtures) — Ruby on Rails like test fixtures for Go. Write tests against a real database ☆`1,162`
- [fergusstrange/embedded-postgres](https://github.com/fergusstrange/embedded-postgres) — Run a real Postgres database locally on Linux, OSX or Windows as part of another Go application or test ☆`967`
- [gotestyourself/gotest.tools](https://github.com/gotestyourself/gotest.tools) — A collection of packages to augment the go testing package and support common patterns. ☆`563`
- [maxatome/go-testdeep](https://github.com/maxatome/go-testdeep) — Extremely flexible golang deep comparison, extends the go testing package, tests HTTP APIs and provides tests suite ☆`448`
- [appleboy/gofight](https://github.com/appleboy/gofight) — Testing API Handler written in Golang. ☆`440`
- [MarvinJWendt/testza](https://github.com/MarvinJWendt/testza) — Full-featured test framework for Go! Assertions, fuzzing, input testing, output capturing, and much more! ☆`421`
- [viant/endly](https://github.com/viant/endly) — End to end functional test and automation framework ☆`267`
- [ysmood/got](https://github.com/ysmood/got) — An enjoyable golang test framework. ☆`269`
- [adamluzsi/testcase](https://github.com/adamluzsi/testcase) — testcase is an opinionated testing framework to support test driven design. ☆`123`
- [kinbiko/jsonassert](https://github.com/kinbiko/jsonassert) — A Go test assertion library for verifying that two representations of JSON are semantically equal ☆`138`
- [earthboundkid/be](https://github.com/earthboundkid/be) — The Go test helper for minimalists ☆`109`
- [corbym/gocrest](https://github.com/corbym/gocrest) — GoCrest - Hamcrest-like matchers for Go ☆`106`
- [cunicu/gont](https://github.com/cunicu/gont) — A Go testing framework for distributed applications ☆`83`
- [hedhyw/gherkingen](https://github.com/hedhyw/gherkingen) — Behaviour Driven Development tests generator for Golang ☆`81`
- [madflojo/testcerts](https://github.com/madflojo/testcerts) — Dynamically generate self-signed certificates and certificate authorities for Go tests ☆`74`
- [go-restit/restit](https://github.com/go-restit/restit) — A Go library help testing your RESTful API application ☆`55`
- [viant/dsunit](https://github.com/viant/dsunit) — Datastore Testibility ☆`45`
- [rekby/fixenv](https://github.com/rekby/fixenv) —  ☆`32`
- [abecodes/dft](https://github.com/abecodes/dft) — Docker For Testing is a zero dependency wrapper around the `docker` command. ☆`16`
## Text Processing

### Formatters

- [dustin/go-humanize](https://github.com/dustin/go-humanize) — Go Humans! (formatters for units to human friendly sizes) ☆`4,565`
- [neilotoole/sq](https://github.com/neilotoole/sq) — sq data wrangler ☆`2,302`
- [ianlopshire/go-fixedwidth](https://github.com/ianlopshire/go-fixedwidth) — Encoding and decoding for fixed-width formatted data ☆`86`
- [bojanz/address](https://github.com/bojanz/address) — Address handling for Go. ☆`77`
### Markup Languages

- [BurntSushi/toml](https://github.com/BurntSushi/toml) — TOML parser for Golang with reflection. ☆`4,748`
- [yuin/goldmark](https://github.com/yuin/goldmark) — A markdown parser written in Go. Easy to extend, standard(CommonMark) compliant, well structured. ☆`4,145`
- [JohannesKaufmann/html-to-markdown](https://github.com/JohannesKaufmann/html-to-markdown) — Convert HTML to Markdown. Even works with entire websites and can be extended through rules. ☆`2,900`
- [pelletier/go-toml](https://github.com/pelletier/go-toml) — Go library for the TOML file format ☆`1,826`
- [antchfx/htmlquery](https://github.com/antchfx/htmlquery) — htmlquery is golang XPath package for HTML query. ☆`768`
- [clbanning/mxj](https://github.com/clbanning/mxj) — Decode / encode XML to/from map[string]interface{} (or JSON); extract values with dot-notation paths and wildcards. Replaces x2j and j2x packages. ☆`627`
- [mmalcek/bafi](https://github.com/mmalcek/bafi) — Universal JSON, BSON, YAML, CSV, XML, mt940 converter with templates ☆`107`
- [drewstinnett/gout](https://github.com/drewstinnett/gout) — Output go objects in standard formats, such as YAML, JSON, etc ☆`18`
### Parsers/Encoders/Decoders

- [mvdan/sh](https://github.com/mvdan/sh) — A shell parser, formatter, and interpreter with bash support; includes shfmt ☆`7,820`
- [mmcdole/gofeed](https://github.com/mmcdole/gofeed) — Parse RSS, Atom and JSON feeds in Go ☆`2,708`
- [google/go-querystring](https://github.com/google/go-querystring) — go-querystring is Go library for encoding structs into URL query strings. ☆`2,053`
- [olebedev/when](https://github.com/olebedev/when) — A natural language date/time parser with pluggable rules ☆`1,437`
- [adrianmo/go-nmea](https://github.com/adrianmo/go-nmea) — A NMEA parser library in pure Go ☆`244`
- [yassinebenaid/godump](https://github.com/yassinebenaid/godump) — Dump any GO variable with ease ☆`214`
- [editorconfig/editorconfig-core-go](https://github.com/editorconfig/editorconfig-core-go) — EditorConfig Core written in Go ☆`146`
- [bzick/tokenizer](https://github.com/bzick/tokenizer) — Tokenizer (lexer) for golang ☆`127`
- [emersion/go-vcard](https://github.com/emersion/go-vcard) — A Go library to parse and format vCard ☆`116`
- [polera/gonameparts](https://github.com/polera/gonameparts) — Takes a full name and splits it into individual name parts ☆`43`
### Regular Expressions

- [hedhyw/rex](https://github.com/hedhyw/rex) — Flexible regular expressions constructor for Golang. ☆`204`
- [IGLOU-EU/go-wildcard](https://github.com/IGLOU-EU/go-wildcard) — Fast and light wildcard pattern matching. ☆`85`
### Sanitation

- [microcosm-cc/bluemonday](https://github.com/microcosm-cc/bluemonday) — bluemonday: a fast golang HTML sanitizer (inspired by the OWASP Java HTML Sanitizer) to scrub user generated content of XSS ☆`3,425`
- [JoshuaDoes/gofuckyourself](https://github.com/JoshuaDoes/gofuckyourself) — A sanitization-based swear filter for Go. ☆`69`
### Scrapers

- [gocolly/colly](https://github.com/gocolly/colly) — Elegant Scraper and Crawler Framework for Golang ☆`24,372`
- [PuerkitoBio/goquery](https://github.com/PuerkitoBio/goquery) — A little like that j-thing, only in Go. ☆`14,554`
- [mvdan/xurls](https://github.com/mvdan/xurls) — Extract urls from text ☆`1,224`
- [foolin/pagser](https://github.com/foolin/pagser) — Pagser is a simple, extensible, configurable parse and deserialize html page to struct based on goquery and struct tags for golang crawler ☆`108`
- [zoomio/tagify](https://github.com/zoomio/tagify) — Tagify produces a set of tags from a given source. Source can be either an HTML page, a Markdown document or a plain text. Supports English, Russian, Chinese, Hindi, Spanish, Arabic, Japanese, German, Hebrew, French and Korean languages. ☆`39`
### Utility/Miscellaneous

- [arunsupe/semantic-grep](https://github.com/arunsupe/semantic-grep) — grep for words with similar meaning to the query ☆`1,167`
- [mattn/go-runewidth](https://github.com/mattn/go-runewidth) — wcwidth for golang ☆`641`
- [striker2000/petrovich](https://github.com/striker2000/petrovich) — Golang port of Petrovich - an inflector for Russian anthroponyms. ☆`50`
## Third-party APIs

- [google/go-github](https://github.com/google/go-github) — Go library for accessing the GitHub v3 API ☆`10,843`
- [sashabaranov/go-openai](https://github.com/sashabaranov/go-openai) — OpenAI ChatGPT, GPT-3, GPT-4, DALL·E, Whisper API wrapper for Go ☆`10,112`
- [bwmarrin/discordgo](https://github.com/bwmarrin/discordgo) — (Golang) Go bindings for Discord ☆`5,441`
- [slack-go/slack](https://github.com/slack-go/slack) — Slack API in Go ☆`4,803`
- [googleapis/google-cloud-go](https://github.com/googleapis/google-cloud-go) — Google Cloud Client Libraries for Go. ☆`4,277`
- [googleapis/google-api-go-client](https://github.com/googleapis/google-api-go-client) — Auto-generated Google APIs for Go. ☆`4,273`
- [aws/aws-sdk-go-v2](https://github.com/aws/aws-sdk-go-v2) — AWS SDK for the Go programming language. ☆`3,123`
- [minio/minio-go](https://github.com/minio/minio-go) — MinIO Go client SDK for S3 compatible object storage ☆`2,720`
- [stripe/stripe-go](https://github.com/stripe/stripe-go) — Go library for the Stripe API. ☆`2,338`
- [huandu/facebook](https://github.com/huandu/facebook) — A Facebook Graph API SDK For Go. ☆`1,377`
- [ChimeraCoder/anaconda](https://github.com/ChimeraCoder/anaconda) — A Go client library for the Twitter 1.1 API ☆`1,144`
- [shurcooL/githubv4](https://github.com/shurcooL/githubv4) — client library for accessing GitHub GraphQL API v4 ☆`1,151`
- [go-playground/webhooks](https://github.com/go-playground/webhooks) — Webhook receiver for GitHub, Bitbucket, GitLab, Gogs ☆`989`
- [plutov/paypal](https://github.com/plutov/paypal) — Golang client for PayPal REST API ☆`736`
- [codingsince1985/geo-golang](https://github.com/codingsince1985/geo-golang) — Go library to access geocoding and reverse geocoding APIs ☆`532`
- [chyroc/lark](https://github.com/chyroc/lark) — Lark Open API Go SDK, Support ALL Open API and Event Callback ☆`449`
- [otiai10/openaigo](https://github.com/otiai10/openaigo) — OpenAI GPT3/3.5 and GPT4 ChatGPT API Client Library for Go, simple, less dependencies, and well-tested ☆`295`
- [onrik/ethrpc](https://github.com/onrik/ethrpc) — Golang client for ethereum json rpc api ☆`272`
- [go-lark/lark](https://github.com/go-lark/lark) — An easy-to-use SDK for Feishu and Lark Open Platform (Instant Messaging API only) ☆`225`
- [adlio/trello](https://github.com/adlio/trello) — Trello API wrapper for Go ☆`225`
- [ctreminiom/go-atlassian](https://github.com/ctreminiom/go-atlassian) — Golang Client Library for Atlassian Cloud. ☆`166`
- [rhnvrm/simples3](https://github.com/rhnvrm/simples3) — Simple no frills AWS S3 Golang Library using REST with V4 Signing (without AWS Go SDK) ☆`165`
- [koltyakov/gosip](https://github.com/koltyakov/gosip) — SharePoint SDK for Go ☆`159`
- [wit-ai/wit-go](https://github.com/wit-ai/wit-go) — Go client for wit.ai HTTP API ☆`167`
- [andygrunwald/go-trending](https://github.com/andygrunwald/go-trending) — Go library for accessing trending repositories and developers at Github. ☆`145`
- [cyruzin/golang-tmdb](https://github.com/cyruzin/golang-tmdb) — This is a Golang wrapper for working with TMDb API. It aims to support version 3. ☆`138`
- [gregdel/pushover](https://github.com/gregdel/pushover) — Go wrapper for the Pushover API ☆`146`
- [andygrunwald/go-gerrit](https://github.com/andygrunwald/go-gerrit) — Go client/library for Gerrit Code Review ☆`100`
- [FreeLeh/GoFreeDB](https://github.com/FreeLeh/GoFreeDB) — GoFreeDB is a Golang library that provides common and simple database abstractions on top of Google Sheets. ☆`87`
- [switchupcb/disgo](https://github.com/switchupcb/disgo) — Disgo is the next generation of Discord API Consumption. Create a Discord Bot with Go using this Discord API Wrapper (SDK Client). ☆`103`
- [mvrilo/go-redoc](https://github.com/mvrilo/go-redoc) — go-redoc is an embedded OpenAPI/Swagger documentation ui for Go using ReDoc ☆`85`
- [mehanizm/airtable](https://github.com/mehanizm/airtable) — Simple golang airtable API wrapper ☆`80`
- [brunomvsouza/ynab.go](https://github.com/brunomvsouza/ynab.go) — Go client for the YNAB API. Unofficial. It covers 100% of the resources made available by the YNAB API. ☆`72`
- [k-capehart/go-salesforce](https://github.com/k-capehart/go-salesforce) — Salesforce REST API client written in Go ☆`43`
- [rapito/go-spotify](https://github.com/rapito/go-spotify) — Go library for the Spotify Web API ☆`51`
- [rinchsan/device-check-go](https://github.com/rinchsan/device-check-go) — iOS DeviceCheck SDK for Go - query and modify the per-device bits ☆`24`
- [zc2638/swag](https://github.com/zc2638/swag) — No comments, simple go wrapper to create swagger 2.0 compatible APIs. Support most routing frameworks, such as built-in, gin, chi, mux, echo, httprouter, fasthttp and more. ☆`48`
- [chainifynet/aws-encryption-sdk-go](https://github.com/chainifynet/aws-encryption-sdk-go) — AWS Encryption SDK for Go ☆`21`
- [sostronk/go-steam](https://github.com/sostronk/go-steam) — Go library for querying Source servers ☆`33`
- [Icelain/jokeapi](https://github.com/Icelain/jokeapi) — Official golang wrapper for Sv443's jokeapi. ☆`25`
- [staskobzar/goami2](https://github.com/staskobzar/goami2) — Simple Asterisk Manager Interface (AMI) library fo golang ☆`17`
- [circa10a/go-aws-news](https://github.com/circa10a/go-aws-news) — Go app + library to fetch what's new from AWS ☆`17`
- [OTA-Insight/bqwriter](https://github.com/OTA-Insight/bqwriter) — Stream data into Google BigQuery concurrently using InsertAll() or BQ Storage. ☆`16`
## Utilities

- [junegunn/fzf](https://github.com/junegunn/fzf) — A command-line fuzzy finder ☆`71,352`
- [wagoodman/dive](https://github.com/wagoodman/dive) — A tool for exploring each layer in a docker image ☆`51,224`
- [samber/lo](https://github.com/samber/lo) — A Lodash-style Go library based on Go 1.18+ Generics (map, filter, contains, find...) ☆`19,674`
- [jmoiron/sqlx](https://github.com/jmoiron/sqlx) — general purpose extensions to golang's database/sql ☆`17,013`
- [goreleaser/goreleaser](https://github.com/goreleaser/goreleaser) — Release engineering, simplified ☆`14,795`
- [xo/usql](https://github.com/xo/usql) — Universal command-line interface for SQL databases ☆`9,408`
- [cilium/ebpf](https://github.com/cilium/ebpf) — ebpf-go is a pure-Go library to read, modify and load eBPF programs and attach them to various hooks in the Linux kernel. ☆`6,934`
- [duke-git/lancet](https://github.com/duke-git/lancet) — A comprehensive, efficient, and reusable util function library of Go. ☆`5,086`
- [dropbox/godropbox](https://github.com/dropbox/godropbox) — Common libraries for writing Go services/applications. ☆`4,196`
- [tdewolff/minify](https://github.com/tdewolff/minify) — Go minifiers for web formats ☆`3,901`
- [maruel/panicparse](https://github.com/maruel/panicparse) — Crash your app in style (Golang) ☆`3,670`
- [minio/mc](https://github.com/minio/mc) — Unix like utilities for object store ☆`3,072`
- [darccio/mergo](https://github.com/darccio/mergo) — Mergo: merging Go structs and maps since 2013 ☆`3,013`
- [create-go-app/cli](https://github.com/create-go-app/cli) — A complete and self-contained solution for developers of any qualification to create a production-ready project with backend (Go), frontend (JavaScript, TypeScript) and deploy automation (Ansible, Docker) by running only one CLI command. ☆`2,704`
- [avast/retry-go](https://github.com/avast/retry-go) — Simple golang library for retry mechanism ☆`2,714`
- [megaease/easeprobe](https://github.com/megaease/easeprobe) — A simple, standalone, and lightweight tool that can do health/status checking, written in Go. ☆`2,251`
- [gabriel-vasile/mimetype](https://github.com/gabriel-vasile/mimetype) — A fast Golang library for media type and file extension detection, based on magic numbers ☆`1,819`
- [failsafe-go/failsafe-go](https://github.com/failsafe-go/failsafe-go) — Fault tolerance and resilience patterns for Go ☆`1,801`
- [georgysavva/scany](https://github.com/georgysavva/scany) — Library for scanning data from a database into Go structs and more ☆`1,438`
- [itchyny/bed](https://github.com/itchyny/bed) — Binary editor written in Go ☆`1,301`
- [goforj/godump](https://github.com/goforj/godump) — A minimal, developer-friendly pretty-printer and debug dumper for Go structs, inspired by Laravel’s dump() and Symfony’s VarDumper. ☆`1,237`
- [rubyist/circuitbreaker](https://github.com/rubyist/circuitbreaker) — Circuit Breakers in Go ☆`1,146`
- [joshmedeski/sesh](https://github.com/joshmedeski/sesh) — Smart session manager for the terminal ☆`1,111`
- [owenthereal/upterm](https://github.com/owenthereal/upterm) — Instant Terminal Sharing ☆`930`
- [immortal/immortal](https://github.com/immortal/immortal) — A *nix cross-platform (OS agnostic) supervisor ☆`818`
- [cep21/circuit](https://github.com/cep21/circuit) — An efficient and feature complete Hystrix like Go implementation of the circuit breaker pattern. ☆`785`
- [miniscruff/changie](https://github.com/miniscruff/changie) — Automated changelog tool for preparing releases with lots of customization options ☆`776`
- [jonboulle/clockwork](https://github.com/jonboulle/clockwork) — a fake clock for golang ☆`709`
- [derekparker/delve](https://github.com/derekparker/delve) — Delve is a debugger for the Go programming language. ☆`652`
- [cristianoliveira/ergo](https://github.com/cristianoliveira/ergo) — The management of multiple apps running over different ports made easy ☆`634`
- [Unrud/remote-touchpad](https://github.com/Unrud/remote-touchpad) — Control mouse and keyboard from a smartphone ☆`607`
- [blockloop/scan](https://github.com/blockloop/scan) — Tiny lib to scan SQL rows directly to structs, slices, and primitive types ☆`596`
- [mennanov/limiters](https://github.com/mennanov/limiters) — Golang rate limiters for distributed applications ☆`567`
- [alajmo/mani](https://github.com/alajmo/mani) — CLI tool to help you manage repositories ☆`558`
- [htcat/htcat](https://github.com/htcat/htcat) — Parallel and Pipelined HTTP GET Utility ☆`556`
- [ungerik/go-dry](https://github.com/ungerik/go-dry) — DRY (don't repeat yourself) package for Go ☆`487`
- [biter777/countries](https://github.com/biter777/countries) — Countries - ISO-639, ISO-3166 countries codes with subdivisions and names, ISO-4217 currency designators, ITU-T E.164 IDD phone codes, countries capitals, UN M.49 codes, IANA ccTLD countries domains, FIPS, IOC/NOC and FIFA codes, VERY VERY FAST, compatible with Databases/JSON/BSON/GOB/XML/CSV, Emoji countries flags and currencies, Unicode CLDR. ☆`457`
- [Boeing/config-file-validator](https://github.com/Boeing/config-file-validator) — Cross Platform tool to validate configuration files ☆`377`
- [gotranspile/cxgo](https://github.com/gotranspile/cxgo) — Tool for transpiling C to Go. ☆`360`
- [ferama/rospo](https://github.com/ferama/rospo) — Effortless persistent SSH tunnels with embedded server for seamless connectivity ☆`335`
- [kamilsk/retry](https://github.com/kamilsk/retry) — The most advanced interruptible mechanism to perform actions repetitively until successful. ☆`343`
- [subosito/gotenv](https://github.com/subosito/gotenv) — Load environment variables from `.env` or `io.Reader` in Go. ☆`305`
- [chenquan/diskusage](https://github.com/chenquan/diskusage) — A tool for showing disk usage(Linux, MacOS and Windows), it is a very fast utility to find largest directories or files. ☆`292`
- [reugn/wifiqr](https://github.com/reugn/wifiqr) — Create a QR code with your Wi-Fi login details ☆`272`
- [ikeikeikeike/go-sitemap-generator](https://github.com/ikeikeikeike/go-sitemap-generator) — go-sitemap-generator is the easiest way to generate Sitemaps in Go ☆`225`
- [viant/toolbox](https://github.com/viant/toolbox) — Toolbox - go utility library ☆`218`
- [antham/chyle](https://github.com/antham/chyle) — Changelog generator : use a git repository and various data sources and publish the result on external services ☆`158`
- [maja42/goval](https://github.com/maja42/goval) — Expression evaluation in golang ☆`170`
- [hedhyw/json-log-viewer](https://github.com/hedhyw/json-log-viewer) — Interactive viewer for JSON logs. ☆`157`
- [webriots/rate](https://github.com/webriots/rate) — A high-performance rate limiter library for Go applications ☆`149`
- [commander-cli/cmd](https://github.com/commander-cli/cmd) — A simple package to execute shell commands on linux, windows and osx ☆`159`
- [gookit/filter](https://github.com/gookit/filter) — Provide filtering, sanitizing, and conversion of Golang data ☆`151`
- [knbr13/gitcs](https://github.com/knbr13/gitcs) — Command line tool written in Go. It allows developers to scan their local Git repositories and generate a visual contributions graph. ☆`122`
- [jfcg/sorty](https://github.com/jfcg/sorty) — Fast Concurrent / Parallel Sorting in Go ☆`137`
- [syntaqx/cookie](https://github.com/syntaqx/cookie) — Cookies, but with structs, for happiness. ☆`111`
- [jaschaephraim/lrserver](https://github.com/jaschaephraim/lrserver) — LiveReload server for Go [golang] ☆`128`
- [karl-cardenas-coding/go-lambda-cleanup](https://github.com/karl-cardenas-coding/go-lambda-cleanup) — go-lambda-cleanup - A solution for removing previous versions of AWS Lambdas ☆`95`
- [linxGnu/mssqlx](https://github.com/linxGnu/mssqlx) — Database client library, proxy for any master slave, master master structures. Lightweight, performant and auto balancing in mind. ☆`102`
- [PhakornKiong/go-pattern-match](https://github.com/PhakornKiong/go-pattern-match) — Pattern Matching library for go ☆`93`
- [pioz/countries](https://github.com/pioz/countries) — All you need when you are working with countries in Go. ☆`91`
- [reugn/equalizer](https://github.com/reugn/equalizer) — A set of performant rate limiters for Go ☆`91`
- [arthurkushman/pgo](https://github.com/arthurkushman/pgo) — Go library for PHP community with convenient functions ☆`88`
- [VividCortex/pm](https://github.com/VividCortex/pm) — Processlist manager with TCP listener ☆`79`
- [icza/backscanner](https://github.com/icza/backscanner) — A scanner similar to bufio.Scanner, but it reads and returns lines in reverse order, starting at a given position and going backward. ☆`67`
- [antham/ghokin](https://github.com/antham/ghokin) — Parallelized formatter with no external dependencies for gherkin (cucumber, behat...) ☆`46`
- [antham/yogo](https://github.com/antham/yogo) — Check yopmail mails from command line. ☆`45`
- [asticode/go-astitodo](https://github.com/asticode/go-astitodo) — Parse TODOs in your GO code ☆`66`
- [wroge/scan](https://github.com/wroge/scan) — scan sql rows into any type powered by generics ☆`65`
- [tiendc/gofn](https://github.com/tiendc/gofn) — High performance utility functions using Generics ☆`52`
- [kazhuravlev/just](https://github.com/kazhuravlev/just) — Collection of useful functions. Complete simple tasks faster! ☆`36`
- [shockerli/cvt](https://github.com/shockerli/cvt) — Easy and safe convert any value to another type in Go ☆`53`
- [kazhuravlev/git-tools](https://github.com/kazhuravlev/git-tools) — Useful set of tools which helps to manage git tags ☆`33`
- [ik5/gostrutils](https://github.com/ik5/gostrutils) — Collections of string utils I have created over the years ☆`47`
- [xorcare/pointer](https://github.com/xorcare/pointer) — Helper routines for simplifying the creation of optional fields of basic type. ☆`44`
- [mozillazg/go-httpheader](https://github.com/mozillazg/go-httpheader) — A Go library for encoding structs into Header fields. ☆`47`
- [piglig/go-qr](https://github.com/piglig/go-qr) — A native, high-quality and minimalistic QR code generator ☆`39`
- [kazhuravlev/healthcheck](https://github.com/kazhuravlev/healthcheck) — Readiness probes for Kubernetes application ☆`19`
- [nikolaydubina/watchhttp](https://github.com/nikolaydubina/watchhttp) — Run command periodically and expose latest STDOUT as HTTP endpoint ☆`34`
- [skovtunenko/graterm](https://github.com/skovtunenko/graterm) — Provides primitives to perform ordered GRAceful TERmination for Golang applications ☆`28`
- [mikekonan/go-types](https://github.com/mikekonan/go-types) — Library providing opanapi3 and Go types for store/validation and transfer of ISO-4217, ISO-3166, and other types. ☆`21`
## UUID

- [google/uuid](https://github.com/google/uuid) — Go package for UUIDs based on RFC 4122 and DCE 1.1: Authentication and Security Services. ☆`5,707`
- [oklog/ulid](https://github.com/oklog/ulid) — Universally Unique Lexicographically Sortable Identifier (ULID) in Go ☆`4,745`
- [gofrs/uuid](https://github.com/gofrs/uuid) — A UUID package for Go ☆`1,698`
- [edwingeng/wuid](https://github.com/edwingeng/wuid) — An extremely fast globally unique number generator. ☆`540`
- [twharmon/gouid](https://github.com/twharmon/gouid) — Fast, dependable universally unique ids ☆`26`
## Validation

- [go-playground/validator](https://github.com/go-playground/validator) — Go Struct and Field validation, including Cross Field, Cross Struct, Map, Slice and Array diving ☆`18,567`
- [gookit/validate](https://github.com/gookit/validate) — Go package for data validation and filtering. support Map, Struct, Form data ☆`1,097`
- [Oudwins/zog](https://github.com/Oudwins/zog) — Go with Zod inspired simple schema validation ☆`892`
- [faceair/jio](https://github.com/faceair/jio) — jio is a json schema validator similar to joi ☆`118`
- [osamingo/checkdigit](https://github.com/osamingo/checkdigit) — Provide check digit algorithms and calculators written in Go ☆`111`
- [twharmon/govalid](https://github.com/twharmon/govalid) — Struct validation using tags ☆`94`
- [marrow16/valix](https://github.com/marrow16/valix) — Go package for validating requests ☆`31`
- [tiendc/go-validator](https://github.com/tiendc/go-validator) — Intuitive validation library for Golang ☆`31`
## Version Control

- [go-git/go-git](https://github.com/go-git/go-git) — A highly extensible Git implementation in pure Go. ☆`6,668`
- [gabyx/Githooks](https://github.com/gabyx/Githooks) — Githooks: per-repo and shared Git hooks with version control and auto update. [✩Star] if you're using it! ☆`110`
- [sourcegraph/go-vcs](https://github.com/sourcegraph/go-vcs) — manipulate and inspect VCS repositories in Go ☆`80`
- [jfrog/froggit-go](https://github.com/jfrog/froggit-go) — Froggit-Go is a universal Go library, allowing to perform actions on VCS providers. ☆`47`
## Video

- [bluenviron/gortsplib](https://github.com/bluenviron/gortsplib) — RTSP client and server library for the Go programming language ☆`795`
- [asticode/go-astisub](https://github.com/asticode/go-astisub) — Manipulate subtitles in GO (.srt, .ssa/.ass, .stl, .ttml, .vtt (webvtt), teletext, etc.) ☆`643`
- [asticode/go-astits](https://github.com/asticode/go-astits) — Demux and mux MPEG Transport Streams (.ts) natively in GO ☆`571`
- [Eyevinn/mp4ff](https://github.com/Eyevinn/mp4ff) — Library and tools for working with MP4 files containing video, audio, subtitles, or metadata. The focus is on fragmented files. Includes mp4ff-info, mp4ff-encrypt, mp4ff-decrypt and other tools. ☆`527`
- [asticode/go-astiav](https://github.com/asticode/go-astiav) — Golang ffmpeg and libav C bindings ☆`515`
- [adrg/libvlc-go](https://github.com/adrg/libvlc-go) — Handcrafted Go bindings for libVLC and high-level media player interface ☆`470`
- [korandiz/v4l](https://github.com/korandiz/v4l) — Facade to the Video4Linux video capture interface. ☆`85`
- [unki2aut/go-mpd](https://github.com/unki2aut/go-mpd) — Go library for parsing and generating MPEG-DASH Media Presentation Description (MPD) files ☆`26`
## Web Frameworks

- [gin-gonic/gin](https://github.com/gin-gonic/gin) — Gin is a HTTP web framework written in Go (Golang). It features a Martini-like API with much better performance -- up to 40 times faster. If you need smashing performance, get yourself some Gin. ☆`82,910`
- [gofiber/fiber](https://github.com/gofiber/fiber) — Express inspired web framework written in Go ☆`36,986`
- [beego/beego](https://github.com/beego/beego) — beego is an open-source, high-performance web framework for the Go programming language. ☆`32,124`
- [labstack/echo](https://github.com/labstack/echo) — High performance, minimalist Go web framework ☆`31,203`
- [gogf/gf](https://github.com/gogf/gf) — A powerful framework for faster, easier, and more efficient project development. ☆`12,485`
- [gofr-dev/gofr](https://github.com/gofr-dev/gofr) — An opinionated GoLang framework for accelerated microservice development. Built in support for databases and observability. ☆`11,755`
- [cloudwego/hertz](https://github.com/cloudwego/hertz) — Go HTTP framework with high-performance and strong-extensibility for building micro-services. ☆`6,339`
- [goadesign/goa](https://github.com/goadesign/goa) — Design-first Go framework that generates API code, documentation, and clients. Define once in an elegant DSL, deploy as HTTP and gRPC services with zero drift between code and docs. ☆`5,885`
- [apache/dubbo-go](https://github.com/apache/dubbo-go) — Go Implementation For Apache Dubbo . ☆`4,815`
- [goravel/goravel](https://github.com/goravel/goravel) — A Golang framework for web artisans. Tribute to Laravel. ☆`3,888`
- [danielgtaylor/huma](https://github.com/danielgtaylor/huma) — Huma REST/HTTP API Framework for Golang with OpenAPI 3.1 ☆`3,192`
- [go-goyave/goyave](https://github.com/go-goyave/goyave) — The enterprise REST API framework ☆`1,711`
- [go-fuego/fuego](https://github.com/go-fuego/fuego) — Golang Fuego - Web framework generating OpenAPI 3 spec from source code - Pluggable to existing Gin & Echo APIs ☆`1,427`
- [savsgio/atreugo](https://github.com/savsgio/atreugo) — High performance and extensible micro web framework. Zero memory allocations in hot paths. ☆`1,282`
- [axzilla/templui](https://github.com/axzilla/templui) — The UI Kit for templ ☆`740`
- [ankorstore/yokai](https://github.com/ankorstore/yokai) — Simple, modular, and observable Go framework for backend applications. ☆`730`
- [indeedeng/iwf](https://github.com/indeedeng/iwf) — iWF is a Workflow-As-Code microservice orchestration platform offering an orchestration coding framework and service for building resilient, fault-tolerant, scalable long-running processes ☆`579`
- [i-love-flamingo/flamingo-commerce](https://github.com/i-love-flamingo/flamingo-commerce) — Flexible E-Commerce Framework on top of Flamingo. Used to build E-Commerce "Portals" and connect it with the help of individual Adapters to other services. ☆`564`
- [i-love-flamingo/flamingo](https://github.com/i-love-flamingo/flamingo) — Flamingo Framework and Core Library. Flamingo is a go based framework to build pluggable applications. Focus is on clean architecture, maintainability and operation readiness. ☆`530`
- [rookie-ninja/rk-boot](https://github.com/rookie-ninja/rk-boot) — Build microservice with rk-boot and let the team take over clean and tidy code. ☆`543`
- [fastschema/fastschema](https://github.com/fastschema/fastschema) — All-in-One Backend as a Service with Headless CMS Power ☆`463`
- [uadmin/uadmin](https://github.com/uadmin/uadmin) — The web framework for Golang ☆`352`
- [xxjwxc/ginrpc](https://github.com/xxjwxc/ginrpc) — gin auto binding, grpc and annotated route ☆`297`
- [hidevopsio/hiboot](https://github.com/hidevopsio/hiboot) — hiboot is a high performance web and cli application framework with dependency injection support ☆`181`
- [beatlabs/patron](https://github.com/beatlabs/patron) — Microservice framework following best cloud practices with a focus on productivity. ☆`125`
- [gone-io/gone](https://github.com/gone-io/gone) — Gone - A Lightweight Dependency Injection Framework for Go | Tag-based Auto Injection | Supports Config Center/Lifecycle Management | Provides Rich Ecosystem Components and Scaffolding Tool ☆`131`
- [claygod/microservice](https://github.com/claygod/microservice) — This library provides a simple microservice framework based on clean architecture principles with a working example implemented. ☆`118`
- [gookit/rux](https://github.com/gookit/rux) — Rux is an simple and fast web framework. Support route group, param route binding, middleware, compatible http.Handler interface ☆`97`
- [yaitoo/xun](https://github.com/yaitoo/xun) — Xun is a web framework built on Go's built-in html/template and net/http package’s router (1.22). ☆`86`
- [abemedia/go-don](https://github.com/abemedia/go-don) — API framework written in Golang. ☆`54`
- [go-spring/spring-core](https://github.com/go-spring/spring-core) — Go-Spring is a high-performance Go framework inspired by Spring Boot, offering DI, auto-configuration, and lifecycle management while maintaining Go's simplicity and efficiency. ☆`48`
- [clubpay/ronykit](https://github.com/clubpay/ronykit) — API Framework supporting REST and RPC. ☆`34`
- [SaiNageswarS/go-api-boot](https://github.com/SaiNageswarS/go-api-boot) — Complete framework to build API applications in Golang using grpc ☆`33`
- [jvcoutinho/lit](https://github.com/jvcoutinho/lit) — A simple, fast and expressive HTTP framework for Go. ☆`30`
## WebAssembly

- [tinygo-org/tinygo](https://github.com/tinygo-org/tinygo) — Go compiler for small places. Microcontrollers, WebAssembly (WASM/WASI), and command-line tools. Based on LLVM. ☆`16,398`
- [agnivade/wasmbrowsertest](https://github.com/agnivade/wasmbrowsertest) — Run WASM tests inside your browser ☆`199`
- [extism/go-sdk](https://github.com/extism/go-sdk) — Extism Go SDK - easily run WebAssembly modules in your Go applications ☆`124`
## Webhooks Server

- [adnanh/webhook](https://github.com/adnanh/webhook) — webhook is a lightweight incoming webhook server to run shell commands ☆`11,006`
- [webhookx-io/webhookx](https://github.com/webhookx-io/webhookx) — an open-source webhooks gateway for message receiving, processing, and delivering. ☆`233`
- [42atomys/webhooked](https://github.com/42atomys/webhooked) — A webhook receiver on steroids. ☆`40`
## Windows

- [go-ole/go-ole](https://github.com/go-ole/go-ole) — win32 ole implementation for golang ☆`1,247`
- [gonutz/d3d9](https://github.com/gonutz/d3d9) — Direct3D9 wrapper for Go. ☆`161`
## Workflow Frameworks

- [dagu-org/dagu](https://github.com/dagu-org/dagu) — Local-first workflow engine, built for self-hosting. Alternative to Airflow, Cron, etc. It aims to solve greater problems. ☆`2,339`
- [noneback/go-taskflow](https://github.com/noneback/go-taskflow) — A pure go General-purpose Task-parallel Programming Framework with integrated visualizer and profiler ☆`557`
- [cadence-workflow/cadence-go-client](https://github.com/cadence-workflow/cadence-go-client) — Framework for authoring workflows and activities running on top of the Cadence orchestration engine. ☆`359`
- [luno/workflow](https://github.com/luno/workflow) — A tech stack agnostic Event Driven Workflow framework, written in Go, that supports durable, robust, and idempotent state changes with timeouts, callbacks, scheduled triggers, and await calls. Compatible with Kafka and Reflex out of the box. ☆`172`
- [rhosocial/go-dag](https://github.com/rhosocial/go-dag) — A Go-based framework has been developed to oversee the execution of workflows delineated by directed acyclic graphs (DAGs). ☆`29`
## XML

- [miku/zek](https://github.com/miku/zek) — Generate a Go struct from XML. ☆`770`
- [antchfx/xpath](https://github.com/antchfx/xpath) — XPath package for golang, supports HTML, XML, JSON document query and more ☆`719`
- [antchfx/xmlquery](https://github.com/antchfx/xmlquery) — xmlquery is Golang XPath package for XML query. ☆`470`
## Zero Trust

- [sigstore/cosign](https://github.com/sigstore/cosign) — Code signing and transparency for containers and binaries ☆`5,025`
- [openziti/ziti](https://github.com/openziti/ziti) — The parent project for OpenZiti. Here you will find the executables for a fully zero trust, application embedded, programmable network @OpenZiti ☆`3,401`
- [spiffe/spire](https://github.com/spiffe/spire) — The SPIFFE Runtime Environment ☆`1,977`
- [philips-labs/spiffe-vault](https://github.com/philips-labs/spiffe-vault) — Integrates Spiffe and Vault to have secretless authentication ☆`89`


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