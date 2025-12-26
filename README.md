# Awesome Go

[![Last update](https://img.shields.io/github/last-commit/abordage/awesome-go?label=last%20update)](README.md)
[![License](https://img.shields.io/github/license/abordage/awesome-go)](LICENSE)

**Automated. Curated. Ranked.**

Go libraries, tools, and applications from the community. This awesome list is automatically maintained with daily GitHub API updates. Projects are re-ranked daily based on current activity metrics.

**Daily process:** Merge community PRs → Scan repos → Filter stale projects → Recalculate scores → Rebuild list

- [AI & Machine Learning](#ai--machine-learning)
  - [Artificial Intelligence](#artificial-intelligence)
  - [Machine Learning](#machine-learning)
- [Audio & Video](#audio--video)
  - [Audio](#audio)
  - [Images](#images)
  - [Video](#video)
- [Authentication & Security](#authentication--security)
  - [Authentication](#authentication)
  - [Security](#security)
  - [Zero Trust](#zero-trust)
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
  - [Miscellaneous Data Structures and Algorithms](#miscellaneous-data-structures-and-algorithms)
  - [Queues](#queues)
  - [Text Analysis](#text-analysis)
- [Databases](#databases)
  - [Caches](#caches)
  - [Database Schema Migration](#database-schema-migration)
  - [Database Tools](#database-tools)
  - [Databases Implemented in Go](#databases-implemented-in-go)
  - [Interfaces to Multiple Backends](#interfaces-to-multiple-backends)
  - [NoSQL Database Drivers](#nosql-database-drivers)
  - [Relational Database Drivers](#relational-database-drivers)
  - [SQL Query Builders](#sql-query-builders)
  - [Search and Analytic Databases](#search-and-analytic-databases)
- [DevOps & Build](#devops--build)
  - [Build Automation](#build-automation)
  - [CI/CD](#cicd)
  - [Containers](#containers)
  - [Continuous Integration](#continuous-integration)
  - [DevOps Utilities](#devops-utilities)
  - [Infrastructure](#infrastructure)
  - [Kubernetes](#kubernetes)
  - [Load Testing](#load-testing)
- [Finance & Blockchain](#finance--blockchain)
  - [Blockchain](#blockchain)
  - [Financial](#financial)
- [GUI & Desktop](#gui--desktop)
  - [GUI](#gui)
  - [Windows](#windows)
- [Game Development](#game-development)
  - [Game Engines](#game-engines)
  - [OpenGL](#opengl)
- [Go Tooling](#go-tooling)
  - [Compilers](#compilers)
  - [Editor Plugins](#editor-plugins)
  - [Generate Tools](#generate-tools)
  - [Go Tools](#go-tools)
- [Hardware & IoT](#hardware--iot)
  - [Hardware](#hardware)
  - [IoT](#iot)
- [Integrations](#integrations)
  - [AI & ML APIs](#ai--ml-apis)
  - [Cloud Provider APIs](#cloud-provider-apis)
  - [GitHub & Git APIs](#github--git-apis)
  - [Microsoft Office](#microsoft-office)
  - [ORM](#orm)
  - [Other APIs](#other-apis)
  - [Payment APIs](#payment-apis)
  - [Productivity APIs](#productivity-apis)
  - [Query Language](#query-language)
  - [Social & Chat APIs](#social--chat-apis)
- [Messaging & Bots](#messaging--bots)
  - [Bot Building](#bot-building)
  - [Email](#email)
  - [Messaging](#messaging)
  - [Webhooks](#webhooks)
- [Networking](#networking)
  - [Consensus](#consensus)
  - [DNS](#dns)
  - [Distributed Utilities](#distributed-utilities)
  - [HTTP & Proxy](#http--proxy)
  - [HTTP Clients](#http-clients)
  - [Message Brokers](#message-brokers)
  - [Microservices](#microservices)
  - [Network Utilities](#network-utilities)
  - [P2P & Torrent](#p2p--torrent)
  - [Protocols](#protocols)
  - [RPC](#rpc)
  - [SSH & SFTP](#ssh--sftp)
  - [Server Applications](#server-applications)
  - [TCP/UDP Frameworks](#tcpudp-frameworks)
  - [VPN & Tunneling](#vpn--tunneling)
- [Other](#other)
  - [Other Software](#other-software)
- [Science & Geography](#science--geography)
  - [Geographic](#geographic)
  - [Science](#science)
- [Scripting](#scripting)
  - [Embeddable Languages](#embeddable-languages)
  - [Generators](#generators)
- [Testing & Quality](#testing--quality)
  - [Benchmarks](#benchmarks)
  - [Code Analysis](#code-analysis)
  - [Mock](#mock)
  - [Performance](#performance)
  - [Selenium and browser control tools](#selenium-and-browser-control-tools)
  - [Testing Frameworks](#testing-frameworks)
  - [Testing Utilities](#testing-utilities)
  - [Validation](#validation)
- [Text & NLP](#text--nlp)
  - [Formatters](#formatters)
  - [Markup Languages](#markup-languages)
  - [Morphological Analyzers](#morphological-analyzers)
  - [Parsers/Encoders/Decoders](#parsersencodersdecoders)
  - [Scrapers](#scrapers)
  - [Tokenizers](#tokenizers)
  - [Translation](#translation)
  - [Utility/Miscellaneous](#utilitymiscellaneous)
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
  - [Package Management](#package-management)
  - [Version Control](#version-control)
- [Web Development](#web-development)
  - [Middlewares](#middlewares)
  - [Routers](#routers)
  - [Template Engines](#template-engines)
  - [Web Frameworks](#web-frameworks)
  - [WebAssembly](#webassembly)
- [Workflow & Scheduling](#workflow--scheduling)
  - [Job Scheduler](#job-scheduler)
  - [Workflow Frameworks](#workflow-frameworks)


## AI & Machine Learning

### Artificial Intelligence

- [ollama/ollama](https://github.com/ollama/ollama) — Get up and running with OpenAI gpt-oss, DeepSeek-R1, Gemma 3 and other models. ☆`158,197`
- [mudler/LocalAI](https://github.com/mudler/LocalAI) — The free, Open Source alternative to OpenAI, Claude and others. Self-hosted and local-first. Drop-in replacement for OpenAI, running on consumer-grade hardware. No GPU required. Runs gguf, transformers, diffusers and many more. Features: Generate Text, MCP, Audio, Video, Images, Voice Cloning, Distributed, P2P and decentralized inference ☆`40,708`
- [tmc/langchaingo](https://github.com/tmc/langchaingo) — LangChain for Go, the easiest way to write LLM-based programs in Go ☆`8,300`
- [maximhq/bifrost](https://github.com/maximhq/bifrost) — Fastest LLM gateway (50x faster than LiteLLM) with adaptive load balancer, cluster mode, guardrails, 1000+ models support & <100 µs overhead at 5k RPS. ☆`1,427`
- [philippgille/chromem-go](https://github.com/philippgille/chromem-go) — Embeddable vector database for Go ☆`807`
- [universal-tool-calling-protocol/go-utcp](https://github.com/universal-tool-calling-protocol/go-utcp) — Official Go implementation of the UTCP ☆`93`
- [presbrey/ollamafarm](https://github.com/presbrey/ollamafarm) — Manage and use multiple Ollama instances with automatic offline detection/failover and model availability tracking ☆`92`
### Machine Learning

- [sjwhitworth/golearn](https://github.com/sjwhitworth/golearn) — Machine Learning for Go ☆`9,452`
- [gorgonia/gorgonia](https://github.com/gorgonia/gorgonia) — Gorgonia is a library that helps facilitate machine learning in Go. ☆`5,898`
- [otiai10/gosseract](https://github.com/otiai10/gosseract) — Go package for OCR (Optical Character Recognition), by using Tesseract C++ library ☆`3,036`
- [galeone/tfgo](https://github.com/galeone/tfgo) — Tensorflow + Go, the gopher way ☆`2,491`
- [gomlx/gomlx](https://github.com/gomlx/gomlx) — GoMLX: An Accelerated Machine Learning Framework For Go ☆`1,254`
- [jbrukh/bayesian](https://github.com/jbrukh/bayesian) — Naive Bayesian Classification for Golang. ☆`811`
- [patrikeh/go-deep](https://github.com/patrikeh/go-deep) — Artificial Neural Network ☆`559`
- [knights-analytics/hugot](https://github.com/knights-analytics/hugot) — Onnx transformer pipelines in Golang ☆`527`
- [c-bata/goptuna](https://github.com/c-bata/goptuna) — A hyperparameter optimization framework, inspired by Optuna. ☆`273`
## Audio & Video

### Audio

- [ebitengine/oto](https://github.com/ebitengine/oto) — A low-level library to play sound on multiple platforms ☆`1,835`
- [gordonklaus/portaudio](https://github.com/gordonklaus/portaudio) — Go bindings for the PortAudio audio I/O library ☆`817`
- [gen2brain/malgo](https://github.com/gen2brain/malgo) — Mini audio library ☆`370`
- [DylanMeeus/GoAudio](https://github.com/DylanMeeus/GoAudio) — Go tools for audio processing & creation ☆`398`
- [mewkiz/flac](https://github.com/mewkiz/flac) — Package flac provides access to FLAC (Free Lossless Audio Codec) streams. ☆`348`
- [tosone/minimp3](https://github.com/tosone/minimp3) — Decode mp3 ☆`133`
- [dh1tw/gosamplerate](https://github.com/dh1tw/gosamplerate) — Go Bindings for libsamplerate ☆`38`
### Images

- [hybridgroup/gocv](https://github.com/hybridgroup/gocv) — Go package for computer vision using OpenCV 4 and beyond. Includes support for DNN, CUDA, OpenCV Contrib, and OpenVINO. ☆`7,322`
- [anthonynsimon/bild](https://github.com/anthonynsimon/bild) — Image processing algorithms in pure Go ☆`4,164`
- [cshum/imagor](https://github.com/cshum/imagor) — Fast, secure image processing server and Go library, using libvips ☆`3,858`
- [thoas/picfit](https://github.com/thoas/picfit) — An image resizing server written in Go ☆`2,319`
- [gographics/imagick](https://github.com/gographics/imagick) — Go binding to ImageMagick's MagickWand C API ☆`1,859`
- [tdewolff/canvas](https://github.com/tdewolff/canvas) — Vector graphics in Go ☆`1,749`
- [davidbyttow/govips](https://github.com/davidbyttow/govips) — A lightning fast image processing and resizing library for Go ☆`1,512`
- [yeqown/go-qrcode](https://github.com/yeqown/go-qrcode) — To help gophers generate QR Codes with customized styles, such as color, block size, block shape, and icon. ☆`796`
- [HugoSmits86/nativewebp](https://github.com/HugoSmits86/nativewebp) — Native webp encoder for Go ☆`381`
- [auyer/steganography](https://github.com/auyer/steganography) — Pure Golang Library that allows LSB steganography on images using ZERO dependencies ☆`353`
- [Pixboost/transformimgs](https://github.com/Pixboost/transformimgs) — Open source image CDN. ☆`283`
- [kolesa-team/go-webp](https://github.com/kolesa-team/go-webp) — Simple and fast webp library for golang ☆`295`
- [qmuntal/gltf](https://github.com/qmuntal/gltf) — Go library for encoding glTF 2.0 files ☆`266`
- [gojek/darkroom](https://github.com/gojek/darkroom) — Image processing engine and proxy service ☆`235`
- [ungerik/go-cairo](https://github.com/ungerik/go-cairo) — Go binding for the cairo graphics library ☆`151`
- [aofei/cameron](https://github.com/aofei/cameron) — An avatar generator for Go. ☆`130`
- [piglig/go-qr](https://github.com/piglig/go-qr) — A native, high-quality and minimalistic QR code generator ☆`45`
### Video

- [bluenviron/gortsplib](https://github.com/bluenviron/gortsplib) — RTSP client and server library for the Go programming language ☆`875`
- [asticode/go-astisub](https://github.com/asticode/go-astisub) — Manipulate subtitles in GO (.srt, .ssa/.ass, .stl, .ttml, .vtt (webvtt), teletext, etc.) ☆`676`
- [asticode/go-astiav](https://github.com/asticode/go-astiav) — Golang ffmpeg and libav C bindings ☆`610`
- [asticode/go-astits](https://github.com/asticode/go-astits) — Demux and mux MPEG Transport Streams (.ts) natively in GO ☆`600`
- [Eyevinn/mp4ff](https://github.com/Eyevinn/mp4ff) — Library and tools for working with MP4 files containing video, audio, subtitles, or metadata. The focus is on fragmented files. Includes mp4ff-info, mp4ff-encrypt, mp4ff-decrypt and other tools. ☆`580`
- [adrg/libvlc-go](https://github.com/adrg/libvlc-go) — Handcrafted Go bindings for libVLC and high-level media player interface ☆`498`
- [korandiz/v4l](https://github.com/korandiz/v4l) — Facade to the Video4Linux video capture interface. ☆`88`
- [Eyevinn/hls-m3u8](https://github.com/Eyevinn/hls-m3u8) — HLS m3u8 library in Go ☆`35`
- [jonoton/scout](https://github.com/jonoton/scout) — Scout is a standalone open source software solution for DIY video security. ☆`26`
- [unki2aut/go-mpd](https://github.com/unki2aut/go-mpd) — Go library for parsing and generating MPEG-DASH Media Presentation Description (MPD) files ☆`33`
## Authentication & Security

### Authentication

- [casbin/casbin](https://github.com/casbin/casbin) — An authorization library that supports access control models like ACL, RBAC, ABAC in Golang ☆`19,590`
- [golang-jwt/jwt](https://github.com/golang-jwt/jwt) — Go implementation of JSON Web Tokens (JWT). ☆`8,794`
- [markbates/goth](https://github.com/markbates/goth) — Package goth provides a simple, clean, and idiomatic way to write authentication packages for Go web applications. ☆`6,382`
- [golang/oauth2](https://github.com/golang/oauth2) — Go OAuth2 ☆`5,785`
- [ory/keto](https://github.com/ory/keto) — The most scalable and customizable permission server on the market. Fix your slow or broken permission system with Google's proven "Zanzibar" approach. Supports ACL, RBAC, and more. Written in Go, cloud native, headless, API-first. Available as a service on Ory Network and for self-hosters. ☆`5,223`
- [openfga/openfga](https://github.com/openfga/openfga) — A high performance and flexible authorization/permission engine built for developers and inspired by Google Zanzibar ☆`4,572`
- [cerbos/cerbos](https://github.com/cerbos/cerbos) — Cerbos is the open core, language-agnostic, scalable authorization solution that makes user permissions and authorization simple to implement and manage by writing context-aware access control policies for your application resources. ☆`4,173`
- [aarondl/authboss](https://github.com/aarondl/authboss) — The boss of http auth. ☆`4,130`
- [alexedwards/scs](https://github.com/alexedwards/scs) — HTTP Session Management for Go ☆`2,489`
- [lestrrat-go/jwx](https://github.com/lestrrat-go/jwx) — Complete implementation of JWx (Javascript Object Signing and Encryption/JOSE) technologies for Go ☆`2,288`
- [openshift/osin](https://github.com/openshift/osin) — Golang OAuth2 server library ☆`1,932`
- [dghubble/gologin](https://github.com/dghubble/gologin) — Go login handlers for authentication providers (OAuth1, OAuth2) ☆`1,940`
- [zitadel/oidc](https://github.com/zitadel/oidc) — Easy to use OpenID Connect client and server library written for Go and certified by the OpenID Foundation ☆`1,737`
- [cristalhq/jwt](https://github.com/cristalhq/jwt) — Safe, simple and fast JSON Web Tokens for Go ☆`687`
- [shaj13/go-guardian](https://github.com/shaj13/go-guardian) — Go-Guardian is a golang library that provides a simple, clean, and idiomatic way to create powerful modern API and web authentication. ☆`602`
- [go-jose/go-jose](https://github.com/go-jose/go-jose) — An implementation of JOSE standards (JWE, JWS, JWT) in Go ☆`471`
- [abraithwaite/jeff](https://github.com/abraithwaite/jeff) — Jeff provides the simplest way to manage web sessions in Go. ☆`270`
- [Kwynto/gosession](https://github.com/Kwynto/gosession) — This is quick session for net/http in golang. This package is perhaps the best implementation of the session mechanism, at least it tries to become one. ☆`259`
- [leodip/goiabada](https://github.com/leodip/goiabada) — Goiabada is an OAuth2 / OpenID Connect server written in Go. ☆`179`
- [brianvoe/sjwt](https://github.com/brianvoe/sjwt) — Simple JWT Golang ☆`121`
- [RijulGulati/otpgen](https://github.com/RijulGulati/otpgen) — Library to generate TOTP/HOTP codes ☆`142`
- [jellydator/sessionup](https://github.com/jellydator/sessionup) — Straightforward HTTP session management ☆`128`
- [icza/session](https://github.com/icza/session) — Go session management for web servers (including support for Google App Engine - GAE). ☆`118`
- [essentialkaos/branca](https://github.com/essentialkaos/branca) — Authenticated encrypted API tokens (IETF XChaCha20-Poly1305 AEAD) for Golang ☆`93`
- [mengzhuo/cookiestxt](https://github.com/mengzhuo/cookiestxt) — cookiestxt implement parser of cookies txt format ☆`21`
### Security

- [FiloSottile/age](https://github.com/FiloSottile/age) — A simple, modern and secure encryption tool (and Go library) with small explicit keys, no config options, and UNIX-style composability. ☆`20,456`
- [go-acme/lego](https://github.com/go-acme/lego) — Let's Encrypt/ACME client and library written in Go ☆`9,099`
- [caddyserver/certmagic](https://github.com/caddyserver/certmagic) — Automatic HTTPS certificate management ☆`5,408`
- [Ullaakut/cameradar](https://github.com/Ullaakut/cameradar) — Cameradar hacks its way into RTSP videosurveillance cameras ☆`4,807`
- [corazawaf/coraza](https://github.com/corazawaf/coraza) — OWASP Coraza WAF is a golang modsecurity compatible web application firewall library ☆`3,163`
- [awnumar/memguard](https://github.com/awnumar/memguard) — Software sandbox for storage of sensitive information in memory. ☆`2,696`
- [mojocn/base64Captcha](https://github.com/mojocn/base64Captcha) — captcha of base64 image string ☆`2,323`
- [unrolled/secure](https://github.com/unrolled/secure) — HTTP middleware for Go that facilitates some quick security wins. ☆`2,334`
- [cossacklabs/themis](https://github.com/cossacklabs/themis) — Easy to use cryptographic framework for data protection: secure messaging with forward secrecy and secure data storage. Has unified APIs across 14 platforms. ☆`1,944`
- [mariocandela/beelzebub](https://github.com/mariocandela/beelzebub) — AI-powered honeypot framework ☆`1,772`
- [cossacklabs/acra](https://github.com/cossacklabs/acra) — Database security suite. Database proxy with field-level encryption, search through encrypted data, SQL injections prevention, intrusion detection, honeypots. Supports client-side and proxy-side ("transparent") encryption. SQL, NoSQL. ☆`1,447`
- [dromara/dongle](https://github.com/dromara/dongle) — A simple, semantic and developer-friendly crypto package for golang ☆`1,094`
- [anatol/booster](https://github.com/anatol/booster) — Fast and secure initramfs generator ☆`609`
- [kevinburke/nacl](https://github.com/kevinburke/nacl) — Pure Go implementation of the NaCL set of API's ☆`551`
- [ssh-vault/ssh-vault](https://github.com/ssh-vault/ssh-vault) — encrypt/decrypt using ssh keys ☆`487`
- [hillu/go-yara](https://github.com/hillu/go-yara) — Go bindings for YARA ☆`383`
- [teler-sh/teler-waf](https://github.com/teler-sh/teler-waf) — teler-waf is a Go HTTP middleware that protects local web services from OWASP Top 10 threats, known vulnerabilities, malicious actors, botnets, unwanted crawlers, and brute force attacks. ☆`395`
- [number571/go-peer](https://github.com/number571/go-peer) — Library for developing secure, decentralized, anonymous and quantum-resistant networks in Go language ☆`312`
- [steambap/captcha](https://github.com/steambap/captcha) — Package captcha provides an easy to use, unopinionated API for captcha generation ☆`161`
- [anatol/luks.go](https://github.com/anatol/luks.go) — Pure Golang library to manage LUKS partitions ☆`94`
- [zitadel/passwap](https://github.com/zitadel/passwap) — Package passwap provides a unified implementation between different password hashing algorithms. It allows for easy swapping between algorithms, using the same API for all of them. ☆`72`
- [tg123/go-htpasswd](https://github.com/tg123/go-htpasswd) — Apache htpasswd Parser for Go. ☆`46`
- [adrianosela/sslmgr](https://github.com/adrianosela/sslmgr) — A layer of abstraction the around acme/autocert certificate manager (Golang) ☆`30`
- [rsjethani/secret](https://github.com/rsjethani/secret) — Prevent your secrets from leaking into logs, std* etc. ☆`32`
- [andskur/argon2-hashing](https://github.com/andskur/argon2-hashing) — Argon2 password hashing ☆`25`
- [bitfield/qrand](https://github.com/bitfield/qrand) — Quantum randomness source using the ANU hardware QRNG ☆`17`
### Zero Trust

- [sigstore/cosign](https://github.com/sigstore/cosign) — Code signing and transparency for containers and binaries ☆`5,519`
- [openziti/ziti](https://github.com/openziti/ziti) — The parent project for OpenZiti. Here you will find the executables for a fully zero trust, application embedded, programmable network @OpenZiti ☆`3,774`
- [spiffe/spire](https://github.com/spiffe/spire) — The SPIFFE Runtime Environment ☆`2,159`
- [philips-labs/spiffe-vault](https://github.com/philips-labs/spiffe-vault) — Integrates Spiffe and Vault to have secretless authentication ☆`96`
## CLI & Terminal

### Advanced Console UIs

- [charmbracelet/bubbletea](https://github.com/charmbracelet/bubbletea) — A powerful little TUI framework ☆`37,625`
- [antonmedv/fx](https://github.com/antonmedv/fx) — Terminal JSON viewer & processor ☆`20,111`
- [gizak/termui](https://github.com/gizak/termui) — Golang terminal dashboard ☆`13,494`
- [jroimartin/gocui](https://github.com/jroimartin/gocui) — Minimalist Go package aimed at creating Console User Interfaces. ☆`10,471`
- [charmbracelet/lipgloss](https://github.com/charmbracelet/lipgloss) — Style definitions for nice terminal layouts ☆`10,194`
- [charmbracelet/bubbles](https://github.com/charmbracelet/bubbles) — TUI components for Bubble Tea ☆`7,417`
- [c-bata/go-prompt](https://github.com/c-bata/go-prompt) — Building powerful interactive prompts in Go, inspired by python-prompt-toolkit. ☆`5,441`
- [pterm/pterm](https://github.com/pterm/pterm) — Modern terminal output library ☆`5,320`
- [schollz/progressbar](https://github.com/schollz/progressbar) — Thread-safe progress bar ☆`4,617`
- [mum4k/termdash](https://github.com/mum4k/termdash) — Terminal-based dashboard ☆`2,953`
- [guptarohit/asciigraph](https://github.com/guptarohit/asciigraph) — ASCII line graphs in terminal ☆`2,934`
- [briandowns/spinner](https://github.com/briandowns/spinner) — Terminal spinner indicators ☆`2,499`
- [vbauerster/mpb](https://github.com/vbauerster/mpb) — Multi progress bar ☆`2,460`
- [muesli/termenv](https://github.com/muesli/termenv) — Terminal color support ☆`1,949`
- [gookit/color](https://github.com/gookit/color) — Terminal color rendering ☆`1,570`
- [logrusorgru/aurora](https://github.com/logrusorgru/aurora) — ANSI colors for Printf ☆`1,476`
- [mattn/go-isatty](https://github.com/mattn/go-isatty) — Check if terminal is TTY ☆`881`
- [mattn/go-colorable](https://github.com/mattn/go-colorable) — Colorable writer for Windows ☆`804`
- [Evertras/bubble-table](https://github.com/Evertras/bubble-table) — Table component for Bubble Tea ☆`545`
### Standard CLI

- [spf13/cobra](https://github.com/spf13/cobra) — A Commander for modern Go CLI interactions ☆`42,720`
- [urfave/cli](https://github.com/urfave/cli) — A declarative, simple, fast, and fun package for building command line tools in Go ☆`23,776`
- [elves/elvish](https://github.com/elves/elvish) — Scripting shell for Go ☆`6,195`
- [alecthomas/kingpin](https://github.com/alecthomas/kingpin) — Command-line parser ☆`3,558`
- [dnote/dnote](https://github.com/dnote/dnote) — Command-line notebook ☆`2,995`
- [spf13/pflag](https://github.com/spf13/pflag) — POSIX/GNU-style flags ☆`2,678`
- [jessevdk/go-flags](https://github.com/jessevdk/go-flags) — Command-line option parser ☆`2,690`
- [alexflint/go-arg](https://github.com/alexflint/go-arg) — Struct-based argument parsing ☆`2,214`
- [carapace-sh/carapace-bin](https://github.com/carapace-sh/carapace-bin) — Multi-shell completion binary ☆`1,630`
- [nanovms/ops](https://github.com/nanovms/ops) — Build and run unikernels ☆`1,442`
- [carapace-sh/carapace](https://github.com/carapace-sh/carapace) — Multi-shell completion library ☆`1,049`
- [posener/complete](https://github.com/posener/complete) — Bash completion in Go ☆`949`
- [ddddddO/gtree](https://github.com/ddddddO/gtree) — Easily output ASCII tree from Go program or Markdown unordered list (and it does more than just output tree!) ☆`321`
- [leaanthony/clir](https://github.com/leaanthony/clir) — Simple CLI library ☆`197`
- [urfave/sflags](https://github.com/urfave/sflags) — Generate flags from structs ☆`165`
- [hedzr/cmdr](https://github.com/hedzr/cmdr) — POSIX-compliant CLI parser ☆`141`
- [reeflective/readline](https://github.com/reeflective/readline) — Shell library with inputrc ☆`130`
- [cristalhq/acmd](https://github.com/cristalhq/acmd) — Simple CLI package ☆`137`
- [codingconcepts/env](https://github.com/codingconcepts/env) — Tag-based environment configuration for structs ☆`126`
- [reeflective/console](https://github.com/reeflective/console) — Console library for Cobra ☆`100`
- [dixonwille/wlog](https://github.com/dixonwille/wlog) — Cross-platform logging ☆`67`
- [DavidGamba/go-getoptions](https://github.com/DavidGamba/go-getoptions) — Command line option parser with completion ☆`61`
- [hashicorp/cli](https://github.com/hashicorp/cli) — CLI library for Go ☆`32`
- [nyaosorg/go-readline-ny](https://github.com/nyaosorg/go-readline-ny) — Readline for Go ☆`32`
- [carapace-sh/carapace-spec](https://github.com/carapace-sh/carapace-spec) — Multi-shell completion library ☆`26`
- [sgreben/flagvar](https://github.com/sgreben/flagvar) — CLI argument types for flag ☆`48`
- [jxskiss/mcli](https://github.com/jxskiss/mcli) — Minimal but powerful CLI ☆`42`
## Concurrency

### Actor Model

- [asynkron/protoactor-go](https://github.com/asynkron/protoactor-go) — Ultra fast distributed actors for Go ☆`5,393`
- [ergo-services/ergo](https://github.com/ergo-services/ergo) — An actor-based Framework with network transparency for creating event-driven architecture in Golang. Inspired by Erlang. Zero dependencies. ☆`4,318`
- [anthdm/hollywood](https://github.com/anthdm/hollywood) — Blazingly fast and light-weight Actor engine written in Golang ☆`2,151`
- [Tochemey/goakt](https://github.com/Tochemey/goakt) — [Go] Distributed Actor/Grain framework using protocol buffers as message for Golang ☆`306`
### Goroutines

- [panjf2000/ants](https://github.com/panjf2000/ants) — ants is the most powerful and reliable pooling solution for Go. ☆`14,207`
- [benmanns/goworker](https://github.com/benmanns/goworker) — goworker is a Go-based background worker that runs 10 to 100,000* times faster than Ruby-based workers. ☆`2,847`
- [alitto/pond](https://github.com/alitto/pond) — High-performance worker pool ☆`2,049`
- [destel/rill](https://github.com/destel/rill) — Channel-based concurrency toolkit ☆`1,799`
- [xxjwxc/gowp](https://github.com/xxjwxc/gowp) — Goroutine worker pool ☆`523`
- [earthboundkid/flowmatic](https://github.com/earthboundkid/flowmatic) — Structured concurrency ☆`396`
- [reugn/async](https://github.com/reugn/async) — Async computation package ☆`284`
- [timandy/routine](https://github.com/timandy/routine) — ThreadLocal for Go ☆`281`
- [vladopajic/go-actor](https://github.com/vladopajic/go-actor) — Actor model library ☆`272`
- [mborders/artifex](https://github.com/mborders/artifex) — In-memory job queue ☆`213`
### Stream Processing

- [reugn/go-streams](https://github.com/reugn/go-streams) — Stream processing library ☆`2,143`
- [Breeze0806/go-etl](https://github.com/Breeze0806/go-etl) — ETL toolset for Go ☆`180`
- [fulminate-io/machine](https://github.com/fulminate-io/machine) — Machine is a workflow/pipeline library for processing data ☆`164`
- [mariomac/gostream](https://github.com/mariomac/gostream) — Java Streams port for Go ☆`169`
- [rulego/streamsql](https://github.com/rulego/streamsql) — SQL-based stream processing for IoT ☆`51`
## Configuration

- [spf13/viper](https://github.com/spf13/viper) — Go configuration with fangs ☆`29,734`
- [caarlos0/env](https://github.com/caarlos0/env) — A simple, zero-dependencies library to parse environment variables into structs ☆`5,903`
- [knadh/koanf](https://github.com/knadh/koanf) — Lightweight config management ☆`3,691`
- [alecthomas/kong](https://github.com/alecthomas/kong) — Command-line parser for Go ☆`2,887`
- [ilyakaznacheev/cleanenv](https://github.com/ilyakaznacheev/cleanenv) — Minimalistic environment config reader ☆`2,018`
- [adrg/xdg](https://github.com/adrg/xdg) — XDG Base Directory implementation ☆`936`
- [cristalhq/aconfig](https://github.com/cristalhq/aconfig) — Simple config loader ☆`615`
- [gookit/config](https://github.com/gookit/config) — Config management with formats ☆`575`
- [kkyr/fig](https://github.com/kkyr/fig) — Minimalist config library ☆`387`
- [nil-go/konf](https://github.com/nil-go/konf) — Simplest config loader for Go ☆`359`
- [hjson/hjson-go](https://github.com/hjson/hjson-go) — Hjson for Go ☆`347`
- [vrischmann/envconfig](https://github.com/vrischmann/envconfig) — Env config library ☆`249`
- [chaindead/zerocfg](https://github.com/chaindead/zerocfg) — Zero-effort config management ☆`198`
- [beatlabs/harvester](https://github.com/beatlabs/harvester) — Watch and notify config changes ☆`134`
- [BoRuDar/configuration](https://github.com/BoRuDar/configuration) — Set struct fields from env, flags, files ☆`108`
- [gurkankaymak/hocon](https://github.com/gurkankaymak/hocon) — HOCON config library for Go ☆`86`
- [PaddleHQ/go-aws-ssm](https://github.com/PaddleHQ/go-aws-ssm) — AWS System Manager interface ☆`62`
- [omeid/uconfig](https://github.com/omeid/uconfig) — Lightweight config management ☆`72`
- [go-simpler/env](https://github.com/go-simpler/env) — Load env vars to struct ☆`80`
- [num30/config](https://github.com/num30/config) — Declarative configuration ☆`60`
- [atelpis/enflag](https://github.com/atelpis/enflag) — Unify env and flag parsing ☆`35`
- [wkhere/bcl](https://github.com/wkhere/bcl) — Basic Configuration Language ☆`27`
- [sakirsensoy/genv](https://github.com/sakirsensoy/genv) — Easy env variable handling ☆`43`
- [greencoda/confiq](https://github.com/greencoda/confiq) — Config struct decoder ☆`39`
- [dsbasko/go-cfg](https://github.com/dsbasko/go-cfg) — Unified config reading ☆`47`
- [nasermirzaei89/env](https://github.com/nasermirzaei89/env) — Zero-dep env package ☆`22`
- [romshark/yamagiconf](https://github.com/romshark/yamagiconf) — YAML config framework ☆`18`
- [deatil/go-array](https://github.com/deatil/go-array) — Read/set map, slice, JSON data ☆`22`
## Data Formats

### JSON

- [tidwall/gjson](https://github.com/tidwall/gjson) — Fast JSON value extraction ☆`15,375`
- [bytedance/sonic](https://github.com/bytedance/sonic) — A blazingly fast JSON serializing & deserializing library ☆`8,980`
- [Jeffail/gabs](https://github.com/Jeffail/gabs) — Dynamic JSON parsing ☆`3,524`
- [valyala/fastjson](https://github.com/valyala/fastjson) — Fast JSON parser and validator for Go. No custom structs, no code generation, no reflection ☆`2,417`
- [ohler55/ojg](https://github.com/ohler55/ojg) — Optimized JSON for Go ☆`932`
- [wI2L/jsondiff](https://github.com/wI2L/jsondiff) — JSON Patch diff computation ☆`617`
- [spyzhov/ajson](https://github.com/spyzhov/ajson) — Abstract JSON with JSONPath ☆`288`
- [Andrew-M-C/go.jsonvalue](https://github.com/Andrew-M-C/go.jsonvalue) — Unstructured JSON solution ☆`202`
- [romshark/jscan](https://github.com/romshark/jscan) — High-performance JSON iterator ☆`97`
- [iOliverNguyen/ujson](https://github.com/iOliverNguyen/ujson) — Minimal JSON parser ☆`85`
- [neilotoole/jsoncolor](https://github.com/neilotoole/jsoncolor) — Colorized JSON output ☆`49`
- [ake-persson/mapslice-json](https://github.com/ake-persson/mapslice-json) — Ordered JSON map slices ☆`20`
- [vtopc/epoch](https://github.com/vtopc/epoch) — Unix timestamp marshaling ☆`17`
### Serialization

- [golang/protobuf](https://github.com/golang/protobuf) — Protocol buffers for Go ☆`10,052`
- [ugorji/go](https://github.com/ugorji/go) — Codec for msgpack, cbor, json ☆`1,923`
- [linkedin/goavro](https://github.com/linkedin/goavro) — Goavro is a library that encodes and decodes Avro data. ☆`1,050`
- [jszwec/csvutil](https://github.com/jszwec/csvutil) — CSV to struct mapping ☆`1,023`
- [fxamacker/cbor](https://github.com/fxamacker/cbor) — CBOR codec with extensions ☆`991`
- [ghostiam/binstruct](https://github.com/ghostiam/binstruct) — Binary to struct decoder ☆`110`
- [csweichel/bel](https://github.com/csweichel/bel) — Generate TypeScript from Go ☆`45`
- [o1egl/fwencoder](https://github.com/o1egl/fwencoder) — Fixed width file parser ☆`27`
- [tiendc/go-csvlib](https://github.com/tiendc/go-csvlib) — High-level CSV library ☆`19`
### XML

- [miku/zek](https://github.com/miku/zek) — Generate Go struct from XML ☆`821`
- [antchfx/xpath](https://github.com/antchfx/xpath) — XPath for Go ☆`732`
- [antchfx/xmlquery](https://github.com/antchfx/xmlquery) — XPath XML query ☆`484`
## Data Structures

### Bit-packing and Compression

- [RoaringBitmap/roaring](https://github.com/RoaringBitmap/roaring) — Compressed bitmaps for Go ☆`2,809`
- [iancmcc/bingo](https://github.com/iancmcc/bingo) — Fast, zero-allocation, lexicographic-order-preserving packing/unpacking of native Go types to bytes. ☆`49`
- [amallia/go-ef](https://github.com/amallia/go-ef) — A Go implementation of the Elias-Fano encoding ☆`40`
### Bloom and Cuckoo Filters

- [bits-and-blooms/bloom](https://github.com/bits-and-blooms/bloom) — Bloom filter implementation ☆`2,716`
- [tylertreat/BoomFilters](https://github.com/tylertreat/BoomFilters) — Probabilistic data structures for streams ☆`1,628`
- [seiflotfy/cuckoofilter](https://github.com/seiflotfy/cuckoofilter) — Cuckoo Filter: Practically Better Than Bloom ☆`1,206`
- [OldPanda/bloomfilter](https://github.com/OldPanda/bloomfilter) — Yet another Bloomfilter implementation in Go, compatible with Java's Guava library ☆`20`
### Maps

- [mhmtszr/concurrent-swiss-map](https://github.com/mhmtszr/concurrent-swiss-map) — Thread-safe concurrent hash map ☆`259`
- [srfrog/dict](https://github.com/srfrog/dict) — Python-like dictionaries for Go ☆`46`
- [goradd/maps](https://github.com/goradd/maps) — map library using Go generics that offers a standard interface, go routine synchronization, and sorting ☆`51`
### Miscellaneous Data Structures and Algorithms

- [Workiva/go-datastructures](https://github.com/Workiva/go-datastructures) — Performant, threadsafe data structures ☆`7,879`
- [deckarep/golang-set](https://github.com/deckarep/golang-set) — Generic set type for Go ☆`4,630`
- [bits-and-blooms/bitset](https://github.com/bits-and-blooms/bitset) — Go package implementing bitsets ☆`1,468`
- [liyue201/gostl](https://github.com/liyue201/gostl) — Data structure and algorithm library for go, designed to provide functions similar to C++ STL ☆`1,129`
- [axiomhq/hyperloglog](https://github.com/axiomhq/hyperloglog) — HyperLogLog with optimizations ☆`1,017`
- [kelindar/bitmap](https://github.com/kelindar/bitmap) — Simple dense bitmap index in Go with binary operators ☆`369`
- [barweiss/go-tuple](https://github.com/barweiss/go-tuple) — Go 1.18+ generic tuple ☆`95`
- [seiflotfy/count-min-log](https://github.com/seiflotfy/count-min-log) — Go implementation of Count-Min-Log ☆`69`
- [StudioSol/set](https://github.com/StudioSol/set) — A simple Set data structure implementation in Go (Golang) using LinkedHashMap. ☆`29`
- [s0rg/quadtree](https://github.com/s0rg/quadtree) — Generic, zero-alloc, 100%-test covered Quadtree for golang ☆`41`
- [nazar256/parapipe](https://github.com/nazar256/parapipe) — Paralleling pipeline ☆`37`
- [bobg/merkle](https://github.com/bobg/merkle) — Merkle hash trees ☆`21`
### Queues

- [gammazero/deque](https://github.com/gammazero/deque) — Fast ring-buffer deque (double-ended queue) ☆`746`
- [adrianbrad/queue](https://github.com/adrianbrad/queue) — Go package providing multiple queue implementations. Developed in a thread-safe generic way. ☆`326`
- [embano1/memlog](https://github.com/embano1/memlog) — A Kafka log inspired in-memory and append-only data structure ☆`136`
- [mikestefanello/backlite](https://github.com/mikestefanello/backlite) — SQLite-backed task queues ☆`130`
### Text Analysis

- [blevesearch/bleve](https://github.com/blevesearch/bleve) — Text/numeric/geo/vector indexing library ☆`10,853`
- [derekparker/trie](https://github.com/derekparker/trie) — Data structure and relevant algorithms for extremely fast prefix/fuzzy string searching. ☆`786`
- [agnivade/levenshtein](https://github.com/agnivade/levenshtein) — Go implementation to calculate Levenshtein Distance. ☆`443`
- [plar/go-adaptive-radix-tree](https://github.com/plar/go-adaptive-radix-tree) — Adaptive Radix Trees implemented in Go ☆`408`
- [viant/ptrie](https://github.com/viant/ptrie) — A prefix tree implementation in go ☆`44`
## Databases

### Caches

- [golang/groupcache](https://github.com/golang/groupcache) — groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases. ☆`13,292`
- [dgraph-io/ristretto](https://github.com/dgraph-io/ristretto) — A high performance memory-bound Go cache ☆`6,638`
- [eko/gocache](https://github.com/eko/gocache) — A complete Go cache library that brings you multiple ways of managing your caches ☆`2,817`
- [bluele/gcache](https://github.com/bluele/gcache) — An in-memory cache library for golang. It supports multiple eviction policies: LRU, LFU, ARC ☆`2,725`
- [maypok86/otter](https://github.com/maypok86/otter) — A high performance caching library for Go ☆`2,456`
- [VictoriaMetrics/fastcache](https://github.com/VictoriaMetrics/fastcache) — Fast in-memory cache for Go ☆`2,303`
- [viccon/sturdyc](https://github.com/viccon/sturdyc) — A caching library with advanced concurrency features designed to make I/O heavy applications robust and highly performant ☆`1,242`
- [jellydator/ttlcache](https://github.com/jellydator/ttlcache) — An in-memory cache with item expiration and generics ☆`1,198`
- [EchoVault/SugarDB](https://github.com/EchoVault/SugarDB) — Embeddable and distributed in-memory alternative to Redis. ☆`518`
- [faabiosr/cachego](https://github.com/faabiosr/cachego) — Golang Cache component - Multiple drivers ☆`373`
- [Yiling-J/theine-go](https://github.com/Yiling-J/theine-go) — high performance in-memory cache ☆`359`
- [elastic/go-freelru](https://github.com/elastic/go-freelru) —  ☆`257`
- [samber/hot](https://github.com/samber/hot) — In-memory caching library for read-intensive Go applications ☆`229`
- [naughtygopher/pocache](https://github.com/naughtygopher/pocache) — Preemptive optimistic caching ☆`231`
- [erni27/imcache](https://github.com/erni27/imcache) — A zero-dependency generic in-memory cache Go library ☆`123`
- [OrlovEvgeny/go-mcache](https://github.com/OrlovEvgeny/go-mcache) — Sharded in-memory KV cache ☆`101`
- [zekroTJA/timedmap](https://github.com/zekroTJA/timedmap) — A thread safe map which has expiring key-value pairs. ☆`74`
- [codingsince1985/couchcache](https://github.com/codingsince1985/couchcache) — A RESTful caching micro-service in Go backed by Couchbase ☆`66`
- [mdaliyan/icache](https://github.com/mdaliyan/icache) — A High Performance, Generic, thread-safe, zero-dependency, key-value, in-memory cache ☆`23`
### Database Schema Migration

- [golang-migrate/migrate](https://github.com/golang-migrate/migrate) — Database migrations. CLI and Golang library. ☆`17,843`
- [bytebase/bytebase](https://github.com/bytebase/bytebase) — Database DevSecOps platform ☆`13,475`
- [pressly/goose](https://github.com/pressly/goose) — A database migration tool. Supports SQL migrations and Go functions. ☆`9,659`
- [ariga/atlas](https://github.com/ariga/atlas) — Manage your database schema as code ☆`7,793`
- [amacneil/dbmate](https://github.com/amacneil/dbmate) — A lightweight, framework-agnostic database migration tool. ☆`6,582`
- [rubenv/sql-migrate](https://github.com/rubenv/sql-migrate) — SQL schema migration tool for Go. ☆`3,398`
- [skeema/skeema](https://github.com/skeema/skeema) — Declarative pure-SQL schema management for MySQL and MariaDB ☆`1,350`
- [go-gormigrate/gormigrate](https://github.com/go-gormigrate/gormigrate) — Minimalistic database migration helper for Gorm ORM ☆`1,145`
- [sunary/sqlize](https://github.com/sunary/sqlize) — powerful SQL toolkit; offering parsing, building, and migration capabilities. ☆`123`
- [robinjoseph08/go-pg-migrations](https://github.com/robinjoseph08/go-pg-migrations) — A Go package to help write migrations with go-pg/pg. ☆`86`
- [adlio/schema](https://github.com/adlio/schema) — Embedded schema migration package for Go ☆`42`
- [khezen/avro](https://github.com/khezen/avro) — Apache AVRO for go ☆`47`
- [muir/libschema](https://github.com/muir/libschema) — database schema migrations on a per-library basis [Go] ☆`17`
### Database Tools

- [vitessio/vitess](https://github.com/vitessio/vitess) — Vitess is a database clustering system for horizontal scaling of MySQL. ☆`20,583`
- [sosedoff/pgweb](https://github.com/sosedoff/pgweb) — Cross-platform client for PostgreSQL databases ☆`9,193`
- [go-mysql-org/go-mysql](https://github.com/go-mysql-org/go-mysql) — a powerful mysql toolset with Go ☆`4,899`
- [prest/prest](https://github.com/prest/prest) — PostgreSQL REST, low-code, simplify and accelerate development, instant, realtime, high-performance on any Postgres application, existing or new ☆`4,502`
- [ContentSquare/chproxy](https://github.com/ContentSquare/chproxy) — Open-Source ClickHouse http proxy and load balancer ☆`1,424`
- [cybertec-postgresql/pg_timetable](https://github.com/cybertec-postgresql/pg_timetable) — Advanced PostgreSQL scheduler ☆`1,286`
- [liweiyi88/onedump](https://github.com/liweiyi88/onedump) — Effortless database administration tool ☆`784`
- [HDT3213/rdb](https://github.com/HDT3213/rdb) — Golang implemented Redis RDB parser for secondary development and memory analysis ☆`591`
- [nikepan/clickhouse-bulk](https://github.com/nikepan/clickhouse-bulk) — Batch inserts for ClickHouse ☆`504`
- [wesql/wescale](https://github.com/wesql/wescale) — WeScale is a Modern MySQL proxy that supports read-write-split, read-after-write-consistency, load balancing and OnlineDDL. ☆`312`
- [gatewayd-io/gatewayd](https://github.com/gatewayd-io/gatewayd) — database gateway for building data-driven applications ☆`272`
- [sj14/dbbench](https://github.com/sj14/dbbench) — dbbench is a simple database benchmarking tool which supports several databases and own scripts ☆`115`
- [bartventer/gorm-multitenancy](https://github.com/bartventer/gorm-multitenancy) — Multi-tenancy for GORM ☆`75`
- [kazhuravlev/database-gateway](https://github.com/kazhuravlev/database-gateway) — Safe access to production databases ☆`30`
- [codingconcepts/dg](https://github.com/codingconcepts/dg) — A fast data generator that produces CSV files from generated relational data ☆`43`
### Databases Implemented in Go

- [prometheus/prometheus](https://github.com/prometheus/prometheus) — The Prometheus monitoring system and time series database. ☆`61,905`
- [milvus-io/milvus](https://github.com/milvus-io/milvus) — Milvus is a high-performance, cloud-native vector database built for scalable vector ANN search ☆`41,905`
- [pingcap/tidb](https://github.com/pingcap/tidb) — TiDB - the open-source, cloud-native, distributed SQL database designed for modern applications. ☆`39,504`
- [cockroachdb/cockroach](https://github.com/cockroachdb/cockroach) — Cloud native distributed SQL database ☆`31,648`
- [influxdata/influxdb](https://github.com/influxdata/influxdb) — Scalable datastore for metrics, events, and real-time analytics ☆`31,011`
- [dgraph-io/dgraph](https://github.com/dgraph-io/dgraph) — high-performance graph database for real-time use cases ☆`21,424`
- [dolthub/dolt](https://github.com/dolthub/dolt) — Dolt – Git for Data ☆`19,487`
- [rqlite/rqlite](https://github.com/rqlite/rqlite) — The lightweight, fault-tolerant database built on SQLite. Designed to keep your data highly available with minimal effort. ☆`17,180`
- [VictoriaMetrics/VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) — Fast time series database and monitoring ☆`15,796`
- [dgraph-io/badger](https://github.com/dgraph-io/badger) — Fast key-value DB in Go. ☆`15,302`
- [etcd-io/bbolt](https://github.com/etcd-io/bbolt) — An embedded key/value database for Go. ☆`9,273`
- [codenotary/immudb](https://github.com/codenotary/immudb) — immudb - immutable database based on zero trust, SQL/Key-Value/Document model, tamperproof, data change history ☆`8,881`
- [authzed/spicedb](https://github.com/authzed/spicedb) — Open Source, Google Zanzibar-inspired database for scalably storing and querying fine-grained authorization data ☆`6,300`
- [cockroachdb/pebble](https://github.com/cockroachdb/pebble) — RocksDB/LevelDB inspired key-value database in Go ☆`5,676`
- [rosedblabs/rosedb](https://github.com/rosedblabs/rosedb) — Lightweight, fast and reliable key/value storage engine based on Bitcask. ☆`4,877`
- [tidwall/buntdb](https://github.com/tidwall/buntdb) — BuntDB is an embeddable, in-memory key/value database for Go with custom indexing and geospatial support ☆`4,821`
- [nalgeon/redka](https://github.com/nalgeon/redka) — Redis re-implemented with SQL ☆`4,424`
- [HDT3213/godis](https://github.com/HDT3213/godis) — A Golang implemented Redis Server and Cluster ☆`3,805`
- [nutsdb/nutsdb](https://github.com/nutsdb/nutsdb) — A simple, fast, embeddable, persistent key/value store written in pure Go. It supports fully serializable transactions and many data structures such as list, set, sorted set. ☆`3,539`
- [lindb/lindb](https://github.com/lindb/lindb) — LinDB is a scalable, high performance, high availability distributed time series database. ☆`3,045`
- [lotusdblabs/lotusdb](https://github.com/lotusdblabs/lotusdb) — Most advanced key-value database written in Go, extremely fast, compatible with LSM tree and B+ tree. ☆`2,243`
- [kelindar/column](https://github.com/kelindar/column) — High-performance, columnar, in-memory store with bitmap indexing in Go ☆`1,503`
- [securitybunker/databunker](https://github.com/securitybunker/databunker) — Secure vault for PII/PHI/KYC records ☆`1,374`
- [akrylysov/pogreb](https://github.com/akrylysov/pogreb) — Embedded key-value store for read-heavy workloads written in Go ☆`1,347`
- [objectbox/objectbox-go](https://github.com/objectbox/objectbox-go) — Embedded database for Go ☆`1,254`
- [couchbase/moss](https://github.com/couchbase/moss) — Simple, fast key-val storage ☆`1,016`
- [amit-davidson/LibraDB](https://github.com/amit-davidson/LibraDB) — LibraDB is a simple, persistent key/value store written in pure Go in less than 1000 lines for learning purposes. ☆`198`
- [xgzlucario/rotom](https://github.com/xgzlucario/rotom) — Tiny Redis server in Go ☆`41`
### Interfaces to Multiple Backends

- [philippgille/gokv](https://github.com/philippgille/gokv) — Simple key-value store abstraction and implementations for Go (Redis, Consul, etcd, bbolt, BadgerDB, LevelDB, Memcached, DynamoDB, S3, PostgreSQL, MongoDB, CockroachDB and many more) ☆`820`
- [avito-tech/go-transaction-manager](https://github.com/avito-tech/go-transaction-manager) — Transaction manager for Go ☆`370`
- [viant/dsc](https://github.com/viant/dsc) — Datastore Connectivity in go ☆`35`
- [fogfish/dynamo](https://github.com/fogfish/dynamo) — Generic Golang Key/Value trait for AWS storage services ☆`22`
### NoSQL Database Drivers

- [redis/go-redis](https://github.com/redis/go-redis) — Redis Go client ☆`21,764`
- [gomodule/redigo](https://github.com/gomodule/redigo) — Go client for Redis ☆`9,879`
- [mongodb/mongo-go-driver](https://github.com/mongodb/mongo-go-driver) — The Official Golang driver for MongoDB ☆`8,490`
- [bradfitz/gomemcache](https://github.com/bradfitz/gomemcache) — Go Memcached client library #golang ☆`1,862`
- [qiniu/qmgo](https://github.com/qiniu/qmgo) — Qmgo - The Go driver for MongoDB. It‘s based on official mongo-go-driver but easier to use like Mgo. ☆`1,345`
- [aerospike/aerospike-client-go](https://github.com/aerospike/aerospike-client-go) — Aerospike Client Go ☆`457`
- [couchbase/gocb](https://github.com/couchbase/gocb) — The Couchbase Go SDK ☆`374`
- [nitishm/go-rejson](https://github.com/nitishm/go-rejson) — Golang client for redislabs' ReJSON module with support for multilple redis clients (redigo, go-redis) ☆`346`
- [go-kivik/kivik](https://github.com/go-kivik/kivik) — Common interface to CouchDB or CouchDB-like databases for Go and GopherJS ☆`334`
- [couchbase/go-couchbase](https://github.com/couchbase/go-couchbase) — Couchbase client in Go ☆`324`
- [chenmingyong0423/go-mongox](https://github.com/chenmingyong0423/go-mongox) — MongoDB driver wrapper with generics ☆`215`
- [aliexpressru/gomemcached](https://github.com/aliexpressru/gomemcached) — Binary Memcached client with sharding ☆`22`
- [btnguyen2k/gocosmos](https://github.com/btnguyen2k/gocosmos) — Go database/sql driver for Azure Cosmos DB SQL API ☆`22`
### Relational Database Drivers

- [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) — MySQL driver for database/sql ☆`15,359`
- [jackc/pgx](https://github.com/jackc/pgx) — PostgreSQL driver and toolkit for Go ☆`13,067`
- [denisenkom/go-mssqldb](https://github.com/denisenkom/go-mssqldb) — Microsoft SQL server driver written in go language ☆`1,876`
- [ncruces/go-sqlite3](https://github.com/ncruces/go-sqlite3) — Go bindings to SQLite using wazero ☆`880`
- [godror/godror](https://github.com/godror/godror) — GO DRiver for ORacle DB ☆`577`
- [cvilsmeier/sqinn-go](https://github.com/cvilsmeier/sqinn-go) — Golang SQLite without cgo ☆`509`
- [VinGarcia/ksql](https://github.com/VinGarcia/ksql) — A Simple and Powerful Golang SQL Library ☆`349`
- [surrealdb/surrealdb.go](https://github.com/surrealdb/surrealdb.go) — SurrealDB SDK for Golang ☆`296`
- [nakagami/firebirdsql](https://github.com/nakagami/firebirdsql) — Firebird RDBMS sql driver for Go (golang) ☆`253`
- [ydb-platform/ydb-go-sdk](https://github.com/ydb-platform/ydb-go-sdk) — Pure Go native and database/sql driver for YDB ☆`173`
- [rqlite/gorqlite](https://github.com/rqlite/gorqlite) — A Go client for rqlite, the distributed database built on SQLite ☆`177`
- [apache/calcite-avatica-go](https://github.com/apache/calcite-avatica-go) — Apache Calcite Go ☆`123`
- [viant/bgc](https://github.com/viant/bgc) — Datastore Connectivity for BigQuery in go ☆`21`
### SQL Query Builders

- [sqlc-dev/sqlc](https://github.com/sqlc-dev/sqlc) — Generate type-safe code from SQL ☆`16,576`
- [Masterminds/squirrel](https://github.com/Masterminds/squirrel) — Fluent SQL generation for golang ☆`7,822`
- [xo/dbtpl](https://github.com/xo/dbtpl) — Command line tool to generate idiomatic Go code for SQL databases supporting PostgreSQL, MySQL, SQLite, Oracle, and Microsoft SQL Server ☆`3,877`
- [go-jet/jet](https://github.com/go-jet/jet) — Type safe SQL builder with code generation and automatic query result data mapping ☆`3,502`
- [doug-martin/goqu](https://github.com/doug-martin/goqu) — SQL builder and query library for golang ☆`2,618`
- [didi/gendry](https://github.com/didi/gendry) — a golang library for sql builder ☆`1,640`
- [lqs/sqlingo](https://github.com/lqs/sqlingo) — A lightweight DSL & ORM which helps you to write SQL in Go. ☆`447`
- [nullism/bqb](https://github.com/nullism/bqb) — BQB is a lightweight and easy to use query builder that works with sqlite, mysql, mariadb, postgres, and others. ☆`183`
- [arthurkushman/buildsqlx](https://github.com/arthurkushman/buildsqlx) — Go database query builder library for PostgreSQL ☆`184`
- [galeone/igor](https://github.com/galeone/igor) — igor is an abstraction layer for PostgreSQL with a gorm like syntax. ☆`126`
- [cristalhq/builq](https://github.com/cristalhq/builq) — Easily build SQL queries in Go. ☆`95`
- [HnH/qry](https://github.com/HnH/qry) — Write your SQL queries in raw files with all benefits of modern IDEs, use them in an easy way inside your application with all the profit of compile time constants ☆`35`
- [JiveGroup/FluentSQL](https://github.com/JiveGroup/FluentSQL) — Fluent SQL - flexible and powerful SQL string builder ☆`18`
### Search and Analytic Databases

- [elastic/go-elasticsearch](https://github.com/elastic/go-elasticsearch) — The official Go client for Elasticsearch ☆`6,006`
- [ClickHouse/clickhouse-go](https://github.com/ClickHouse/clickhouse-go) — Golang driver for ClickHouse ☆`3,218`
- [sourcegraph/zoekt](https://github.com/sourcegraph/zoekt) — Fast trigram-based code search ☆`1,312`
- [sdqri/effdsl](https://github.com/sdqri/effdsl) — Elasticsearch query builder for golang ☆`34`
## DevOps & Build

### Build Automation

- [air-verse/air](https://github.com/air-verse/air) — Live reload for Go apps ☆`22,540`
- [go-task/task](https://github.com/go-task/task) — A task runner / simpler Make alternative written in Go ☆`14,467`
- [joerdav/xc](https://github.com/joerdav/xc) — Markdown defined task runner. ☆`1,363`
- [goyek/goyek](https://github.com/goyek/goyek) — Task automation Go library ☆`674`
- [flowexec/flow](https://github.com/flowexec/flow) — Local developer automation platform that flows with you ☆`128`
### CI/CD

- [pipe-cd/pipecd](https://github.com/pipe-cd/pipecd) — The One CD for All {applications, platforms, operations} ☆`1,235`
- [jenkins-zh/jenkins-cli](https://github.com/jenkins-zh/jenkins-cli) — Jenkins CLI allows you to manage your Jenkins in an easy way ☆`408`
- [appleboy/drone-scp](https://github.com/appleboy/drone-scp) — Copy files and artifacts via SSH using a binary, docker or Drone CI. ☆`162`
- [appleboy/drone-jenkins](https://github.com/appleboy/drone-jenkins) — Drone plugin for trigger Jenkins jobs. ☆`41`
### Containers

- [moby/moby](https://github.com/moby/moby) — The Moby Project - a collaborative project for the container ecosystem to assemble container-based systems ☆`71,269`
- [traefik/traefik](https://github.com/traefik/traefik) — The Cloud Native Application Proxy ☆`60,721`
- [ko-build/ko](https://github.com/ko-build/ko) — Build and deploy Go applications ☆`8,274`
- [s0rg/decompose](https://github.com/s0rg/decompose) — Reverse-engineering tool for docker environments ☆`121`
- [x1unix/docker-go-mingw](https://github.com/x1unix/docker-go-mingw) — Docker image for building Go binaries with MinGW toolchain. Supports Windows on ARM! ☆`53`
### Continuous Integration

- [harness/harness](https://github.com/harness/harness) — Harness Open Source is an end-to-end developer platform with Source Control Management, CI/CD Pipelines, Hosted Developer Environments, and Artifact Registries. ☆`33,728`
- [woodpecker-ci/woodpecker](https://github.com/woodpecker-ci/woodpecker) — Simple, powerful CI/CD engine ☆`6,101`
- [ovh/cds](https://github.com/ovh/cds) — Enterprise-Grade Continuous Delivery & DevOps Automation Open Source Platform ☆`4,794`
- [raviqqe/muffet](https://github.com/raviqqe/muffet) — Fast website link checker ☆`2,580`
- [vladopajic/go-test-coverage](https://github.com/vladopajic/go-test-coverage) — Report test coverage threshold issues ☆`208`
- [nikogura/gomason](https://github.com/nikogura/gomason) — A tool for testing, building, signing, and publishing binaries. ☆`66`
- [opnlabs/dot](https://github.com/opnlabs/dot) — A minimal continuous integration system. Uses docker to run jobs concurrently in stages. ☆`31`
- [gha-common/go-beautiful-html-coverage](https://github.com/gha-common/go-beautiful-html-coverage) — GitHub Action for code coverage reports ☆`20`
### DevOps Utilities

- [go-gitea/gitea](https://github.com/go-gitea/gitea) — Git with a cup of tea! Painless self-hosted all-in-one software development service, including Git hosting, code review, team collaboration, package registry and CI/CD ☆`52,709`
- [moovweb/gvm](https://github.com/moovweb/gvm) — Go Version Manager ☆`11,454`
- [TwiN/gatus](https://github.com/TwiN/gatus) — The most advanced status page in the world ☆`9,374`
- [bitfield/script](https://github.com/bitfield/script) — Making it easy to write shell-like scripts in Go ☆`6,904`
- [fleetdm/fleet](https://github.com/fleetdm/fleet) — Open device management ☆`5,863`
- [taubyte/tau](https://github.com/taubyte/tau) — Fullstack Workspace for Humans & Machines ☆`4,856`
- [megaease/easeprobe](https://github.com/megaease/easeprobe) — A simple, standalone, and lightweight tool that can do health/status checking, written in Go. ☆`2,286`
- [ajvb/kala](https://github.com/ajvb/kala) — Modern Job Scheduler ☆`2,163`
- [gabrie30/ghorg](https://github.com/gabrie30/ghorg) — Quickly clone or backup an entire org/users repositories into one directory - Supports GitHub, GitLab, Bitbucket, and more ☆`1,911`
- [sanbornm/go-selfupdate](https://github.com/sanbornm/go-selfupdate) — Enable your Go applications to self update ☆`1,660`
- [yusufcanb/tlm](https://github.com/yusufcanb/tlm) — Local CLI Copilot, powered by Ollama. ☆`1,461`
- [ovh/utask](https://github.com/ovh/utask) — µTask is an automation engine that models and executes business processes declared in yaml. ☆`1,346`
- [TimothyYe/skm](https://github.com/TimothyYe/skm) — A simple and powerful SSH keys manager ☆`1,000`
- [scaleway/scaleway-cli](https://github.com/scaleway/scaleway-cli) — Command Line Interface for Scaleway ☆`946`
- [alexliesenfeld/health](https://github.com/alexliesenfeld/health) — A simple and flexible health check library for Go. ☆`825`
- [kool-dev/kool](https://github.com/kool-dev/kool) — From local development to the cloud: web apps development with containers made easy. ☆`709`
- [kevincobain2000/gobrew](https://github.com/kevincobain2000/gobrew) — Go version manager without root ☆`411`
- [appleboy/easyssh-proxy](https://github.com/appleboy/easyssh-proxy) — Simple SSH protocol implementation ☆`343`
- [xitonix/trubka](https://github.com/xitonix/trubka) — A CLI tool for Kafka ☆`336`
- [emicklei/mora](https://github.com/emicklei/mora) — MongoDB generic REST server in Go ☆`316`
- [thevxn/dish](https://github.com/thevxn/dish) — A simple, remotely configurable monitoring service. ☆`263`
- [jkaninda/goma-gateway](https://github.com/jkaninda/goma-gateway) — Lightweight API gateway and proxy ☆`155`
- [datarootsio/tf-profile](https://github.com/datarootsio/tf-profile) — Profile Terraform runs ☆`163`
- [kazhuravlev/healthcheck](https://github.com/kazhuravlev/healthcheck) — Readiness probes for Kubernetes application ☆`22`
### Infrastructure

- [hashicorp/packer](https://github.com/hashicorp/packer) — Packer is a tool for creating identical machine images for multiple platforms from a single source configuration. ☆`15,539`
- [pomerium/pomerium](https://github.com/pomerium/pomerium) — Pomerium is an identity and context-aware access proxy. ☆`4,554`
- [peak/s5cmd](https://github.com/peak/s5cmd) — Parallel S3 and local filesystem execution tool. ☆`3,809`
- [aptly-dev/aptly](https://github.com/aptly-dev/aptly) — aptly - Debian repository management tool ☆`2,742`
- [KusionStack/kusion](https://github.com/KusionStack/kusion) — Declarative platform orchestrator ☆`1,236`
- [oxyno-zeta/s3-proxy](https://github.com/oxyno-zeta/s3-proxy) — S3 Reverse Proxy with GET, PUT and DELETE methods and authentication (OpenID Connect and Basic Auth) ☆`425`
### Kubernetes

- [kubernetes/kubernetes](https://github.com/kubernetes/kubernetes) — Production-Grade Container Scheduling and Management ☆`119,442`
- [kubernetes/minikube](https://github.com/kubernetes/minikube) — Run Kubernetes locally ☆`31,294`
- [k3s-io/k3s](https://github.com/k3s-io/k3s) — Lightweight Kubernetes ☆`31,723`
- [kubernetes-sigs/kind](https://github.com/kubernetes-sigs/kind) — Kubernetes IN Docker - local clusters for testing Kubernetes ☆`14,845`
- [kubeshark/kubeshark](https://github.com/kubeshark/kubeshark) — API traffic analyzer for Kubernetes ☆`11,604`
- [flannel-io/flannel](https://github.com/flannel-io/flannel) — flannel is a network fabric for containers, designed for Kubernetes ☆`9,361`
- [getanteon/anteon](https://github.com/getanteon/anteon) — Anteon (formerly Ddosify): eBPF-based Kubernetes Monitoring and Performance Testing ☆`8,541`
- [kubevela/kubevela](https://github.com/kubevela/kubevela) — The Modern Application Platform. ☆`7,644`
- [k3d-io/k3d](https://github.com/k3d-io/k3d) — Little helper to run CNCF's k3s in Docker ☆`6,176`
- [stefanprodan/podinfo](https://github.com/stefanprodan/podinfo) — Go microservice template for Kubernetes ☆`5,800`
- [apecloud/kubeblocks](https://github.com/apecloud/kubeblocks) — Kubernetes operator for databases ☆`2,930`
- [kubenetworks/kubevpn](https://github.com/kubenetworks/kubevpn) — Connect to Kubernetes cluster network ☆`1,278`
- [abahmed/kwatch](https://github.com/abahmed/kwatch) — monitor & detect crashes in your Kubernetes(K8s) cluster instantly ☆`991`
- [getanteon/alaz](https://github.com/getanteon/alaz) — eBPF agent for K8s observability ☆`713`
### Load Testing

- [grafana/k6](https://github.com/grafana/k6) — A modern load testing tool, using Go and JavaScript ☆`29,522`
- [tsenart/vegeta](https://github.com/tsenart/vegeta) — HTTP load testing tool and library. It's over 9000! ☆`24,803`
- [codesenberg/bombardier](https://github.com/codesenberg/bombardier) — Fast cross-platform HTTP benchmarking tool written in Go ☆`6,673`
- [rogerwelin/cassowary](https://github.com/rogerwelin/cassowary) — Modern cross-platform HTTP load-testing tool written in Go ☆`811`
## Finance & Blockchain

### Blockchain

- [ethereum/go-ethereum](https://github.com/ethereum/go-ethereum) — Go implementation of the Ethereum protocol ☆`50,545`
- [ipfs/kubo](https://github.com/ipfs/kubo) — An IPFS implementation in Go ☆`16,851`
- [lightningnetwork/lnd](https://github.com/lightningnetwork/lnd) — Lightning Network Daemon ☆`8,074`
- [cosmos/cosmos-sdk](https://github.com/cosmos/cosmos-sdk) — A Framework for Building High Value Public Blockchains ☆`6,874`
- [gagliardetto/solana-go](https://github.com/gagliardetto/solana-go) — Go SDK library and RPC client for the Solana Blockchain ☆`1,491`
- [gnolang/gno](https://github.com/gnolang/gno) — Gno: An interpreted, stack-based Go virtual machine to build succinct and composable apps + gno.land: a blockchain for timeless code and fair open-source. ☆`1,039`
- [cometbft/cometbft](https://github.com/cometbft/cometbft) — CometBFT: A distributed, Byzantine fault-tolerant, deterministic state machine replication engine. A fork and successor to Tendermint Core. ☆`836`
- [ChainSafe/gossamer](https://github.com/ChainSafe/gossamer) — Go Implementation of the Polkadot Host ☆`458`
### Financial

- [shopspring/decimal](https://github.com/shopspring/decimal) — Arbitrary-precision fixed-point decimal numbers in Go ☆`7,156`
- [achannarasappa/ticker](https://github.com/achannarasappa/ticker) — Terminal stock and crypto tracker ☆`5,860`
- [Rhymond/go-money](https://github.com/Rhymond/go-money) — Go implementation of Fowler's Money pattern ☆`1,836`
- [c9s/bbgo](https://github.com/c9s/bbgo) — The modern cryptocurrency trading bot framework written in Go. ☆`1,579`
- [formancehq/ledger](https://github.com/formancehq/ledger) — The programmable open source core ledger for fintech ☆`1,095`
- [bojanz/currency](https://github.com/bojanz/currency) — Currency handling for Go. ☆`618`
- [moov-io/ach](https://github.com/moov-io/ach) — ACH implements a reader, writer, and validator for Automated Clearing House (ACH) files. The HTTP server is available in a Docker image and the Go package is available. ☆`521`
- [invopop/gobl](https://github.com/invopop/gobl) — Go Business Language ☆`240`
- [govalues/decimal](https://github.com/govalues/decimal) — Correctly rounded decimals for Go ☆`211`
- [quagmt/udecimal](https://github.com/quagmt/udecimal) — A high-performance, high precision, zero allocation fixed-point decimal library for financial applications ☆`169`
- [claygod/transaction](https://github.com/claygod/transaction) — Embedded database for accounts transactions. ☆`138`
- [jovandeginste/payme](https://github.com/jovandeginste/payme) — QR code generator (ASCII & PNG) for SEPA payments ☆`89`
- [jokruger/dec128](https://github.com/jokruger/dec128) — High performance 128-bit fixed-point decimal numbers in go. ☆`37`
- [govalues/money](https://github.com/govalues/money) — Correctly rounded monetary amounts and exchange rates for Go ☆`46`
- [nikolaydubina/fpmoney](https://github.com/nikolaydubina/fpmoney) — Fixed-Point Decimal Money ☆`35`
- [nikolaydubina/fpdecimal](https://github.com/nikolaydubina/fpdecimal) — Fixed-Point Decimals ☆`34`
## GUI & Desktop

### GUI

- [fyne-io/fyne](https://github.com/fyne-io/fyne) — Cross platform GUI toolkit in Go inspired by Material Design ☆`27,680`
- [webview/webview](https://github.com/webview/webview) — Tiny cross-platform webview library for C/C++. Uses WebKit (GTK/Cocoa) and Edge WebView2 (Windows). ☆`13,739`
- [therecipe/qt](https://github.com/therecipe/qt) — Qt binding for Go (Golang) with support for Windows / macOS / Linux / FreeBSD / Android / iOS / Sailfish OS / Raspberry Pi / AsteroidOS / Ubuntu Touch / JavaScript / WebAssembly ☆`10,771`
- [go-vgo/robotgo](https://github.com/go-vgo/robotgo) — RobotGo, Go Native cross-platform RPA, GUI automation, Auto test and Computer use @vcaesar ☆`10,548`
- [maxence-charriere/go-app](https://github.com/maxence-charriere/go-app) — Build progressive web apps with Go and WASM ☆`8,845`
- [lxn/walk](https://github.com/lxn/walk) — A Windows GUI toolkit for the Go Programming Language ☆`7,045`
- [progrium/darwinkit](https://github.com/progrium/darwinkit) — Native Mac APIs for Go. Previously known as MacDriver ☆`5,370`
- [getlantern/systray](https://github.com/getlantern/systray) — a cross platfrom Go library to place an icon and menu in the notification area ☆`3,634`
- [cogentcore/core](https://github.com/cogentcore/core) — A free and open source framework for building powerful, fast, elegant 2D and 3D apps that run on macOS, Windows, Linux, iOS, Android, and web with a single Go codebase, allowing you to Code Once, Run Everywhere. ☆`2,288`
- [gotk3/gotk3](https://github.com/gotk3/gotk3) — Go bindings for GTK3 ☆`2,199`
- [roblillack/spot](https://github.com/roblillack/spot) — React-like desktop GUI toolkit for Go ☆`1,251`
- [ncruces/zenity](https://github.com/ncruces/zenity) — Zenity dialogs for Golang, Windows, macOS ☆`876`
- [energye/energy](https://github.com/energye/energy) — Energy is a framework developed by Go language based on CEF (Chromium Embedded Framework) for developing cross-platform desktop applications for Windows, Mac OS X, and Linux ☆`561`
- [AllenDang/cimgui-go](https://github.com/AllenDang/cimgui-go) — Auto generated Go wrapper for Dear ImGui via cimgui ☆`482`
- [richardwilkes/unison](https://github.com/richardwilkes/unison) — A unified graphical user experience toolkit for Go desktop applications ☆`308`
### Windows

- [go-ole/go-ole](https://github.com/go-ole/go-ole) — win32 ole implementation for golang ☆`1,286`
- [gonutz/d3d9](https://github.com/gonutz/d3d9) — Direct3D9 wrapper for Go. ☆`163`
## Game Development

### Game Engines

- [hajimehoshi/ebiten](https://github.com/hajimehoshi/ebiten) — A dead simple 2D game engine for Go ☆`12,786`
- [topfreegames/pitaya](https://github.com/topfreegames/pitaya) — Scalable game server framework with clustering support and client libraries for iOS, Android, Unity and others through the C SDK. ☆`2,701`
- [xiaonanln/goworld](https://github.com/xiaonanln/goworld) — Scalable Distributed Game Server Engine with Hot Swapping in Golang ☆`2,693`
- [gen2brain/raylib-go](https://github.com/gen2brain/raylib-go) — Go bindings for raylib, a simple and easy-to-use library to enjoy videogames programming. ☆`2,283`
- [oakmound/oak](https://github.com/oakmound/oak) — A pure Go game engine ☆`1,647`
- [JoelOtter/termloop](https://github.com/JoelOtter/termloop) — Terminal-based game engine for Go, built on top of Termbox ☆`1,470`
- [xtaci/gonet](https://github.com/xtaci/gonet) — A Game Server Skeleton in golang. ☆`1,288`
- [gopxl/pixel](https://github.com/gopxl/pixel) — A hand-crafted 2D game library in Go. ☆`369`
- [ungerik/go3d](https://github.com/ungerik/go3d) — A performance oriented 2D/3D math package for Go ☆`335`
- [kelindar/tile](https://github.com/kelindar/tile) — Tile is a 2D grid engine, built with data and cache friendly ways, includes pathfinding and observers. ☆`208`
- [mlange-42/ark](https://github.com/mlange-42/ark) — Ark -- Archetype-based Entity Component System (ECS) for Go. ☆`193`
- [andygeiss/ecs](https://github.com/andygeiss/ecs) — Build your own Game-Engine based on the Entity Component System concept in Golang. ☆`167`
- [gonutz/prototype](https://github.com/gonutz/prototype) — Simple 2D game prototyping framework targetting Windows, Mac, Linux, WASM. ☆`108`
- [s0rg/fantasyname](https://github.com/s0rg/fantasyname) — RinkWorks fantasy name generator for golang ☆`39`
- [s0rg/grid](https://github.com/s0rg/grid) — Generic 2D grid ☆`25`
### OpenGL

- [go-gl/glfw](https://github.com/go-gl/glfw) — Go bindings for GLFW 3 ☆`1,656`
- [go-gl/gl](https://github.com/go-gl/gl) — Go bindings for OpenGL (generated via glow) ☆`1,180`
- [go-gl/mathgl](https://github.com/go-gl/mathgl) — A pure Go 3D math library. ☆`593`
## Go Tooling

### Compilers

- [gopherjs/gopherjs](https://github.com/gopherjs/gopherjs) — A compiler from Go to JavaScript for running Go code in a browser ☆`13,091`
- [yassinebenaid/bunster](https://github.com/yassinebenaid/bunster) — Compile shell scripts to static binaries. ☆`2,624`
- [Konstantin8105/c4go](https://github.com/Konstantin8105/c4go) — Transpiling C code to Go code ☆`376`
- [go2hx/go2hx](https://github.com/go2hx/go2hx) — Import Go libraries in your Haxe projects Go -> Haxe source-to-source compiler ☆`145`
### Editor Plugins

- [fatih/vim-go](https://github.com/fatih/vim-go) — Go development plugin for Vim ☆`16,217`
- [visualfc/liteide](https://github.com/visualfc/liteide) — LiteIDE is a simple, open source, cross-platform Go IDE. ☆`7,734`
- [nsf/gocode](https://github.com/nsf/gocode) — An autocompletion daemon for the Go programming language ☆`5,001`
- [golang/vscode-go](https://github.com/golang/vscode-go) — Go extension for Visual Studio Code ☆`4,170`
- [dominikh/go-mode.el](https://github.com/dominikh/go-mode.el) — Emacs mode for the Go programming language ☆`1,445`
- [incu6us/goimports-reviser](https://github.com/incu6us/goimports-reviser) — Imports sorting and code formatting tool ☆`708`
### Generate Tools

- [xuri/xgen](https://github.com/xuri/xgen) — XSD (XML Schema Definition) parser and Go/C/Java/Rust/TypeScript code generator ☆`402`
- [kazhuravlev/options-gen](https://github.com/kazhuravlev/options-gen) — Codegen for functional options in go projects ☆`104`
- [g4s8/envdoc](https://github.com/g4s8/envdoc) — Go tool to generate documentation for environment variables ☆`94`
### Go Tools

- [go-swagger/go-swagger](https://github.com/go-swagger/go-swagger) — Swagger 2.0 implementation for go ☆`9,907`
- [ondrajz/go-callvis](https://github.com/ondrajz/go-callvis) — Visualize call graph of a Go program using Graphviz ☆`6,434`
- [Zxilly/go-size-analyzer](https://github.com/Zxilly/go-size-analyzer) — Analyze compiled Go binary size ☆`1,857`
- [safedep/vet](https://github.com/safedep/vet) — Protect against malicious open source packages ☆`920`
- [iyashjayesh/monigo](https://github.com/iyashjayesh/monigo) — MoniGo is a performance monitoring library for Go apps, offering real-time insights into service-level and function-level metrics. With an intuitive UI, it enables developers to track and optimize performance. Get your Go app's dashboard up in just 10 seconds! ☆`386`
- [becheran/roumon](https://github.com/becheran/roumon) — Universal goroutine monitor using pprof and termui ☆`235`
- [bitfield/gotestdox](https://github.com/bitfield/gotestdox) — A tool for formatting Go test results as readable documentation ☆`183`
- [ahmedakef/gotutor](https://github.com/ahmedakef/gotutor) — Online Go Debugger & Visualizer ☆`71`
- [bobg/decouple](https://github.com/bobg/decouple) — find overspecified function parameters in Go code ☆`33`
- [bobg/modver](https://github.com/bobg/modver) — a tool that helps you obey semantic versioning rules in your Go module ☆`21`
- [dustinblackman/gomodrun](https://github.com/dustinblackman/gomodrun) — Run binaries from go.mod ☆`38`
## Hardware & IoT

### Hardware

- [shirou/gopsutil](https://github.com/shirou/gopsutil) — psutil for golang ☆`11,620`
- [arduino/arduino-cli](https://github.com/arduino/arduino-cli) — Arduino command line tool ☆`4,752`
- [jaypipes/ghw](https://github.com/jaypipes/ghw) — Go HardWare discovery/inspection library ☆`1,800`
- [zcalusic/sysinfo](https://github.com/zcalusic/sysinfo) — Sysinfo is a Go library providing Linux OS / kernel / hardware system information. ☆`571`
### IoT

- [hybridgroup/gobot](https://github.com/hybridgroup/gobot) — Golang framework for robotics, drones, and the Internet of Things (IoT) ☆`9,355`
- [lf-edge/ekuiper](https://github.com/lf-edge/ekuiper) — Lightweight data stream processing engine for IoT edge ☆`1,664`
- [Edgenesis/shifu](https://github.com/Edgenesis/shifu) — Kubernetes-native IoT gateway ☆`1,390`
- [rulego/rulego](https://github.com/rulego/rulego) — RuleGo is a lightweight, high-performance, embedded, next-generation component orchestration rule engine framework for Go. ☆`1,382`
- [e154/smart-home](https://github.com/e154/smart-home) — software package for automation ☆`96`
## Integrations

### AI & ML APIs

- [sashabaranov/go-openai](https://github.com/sashabaranov/go-openai) — OpenAI API client for Go ☆`10,474`
- [otiai10/openaigo](https://github.com/otiai10/openaigo) — OpenAI GPT3/3.5 and GPT4 ChatGPT API Client Library for Go, simple, less dependencies, and well-tested ☆`299`
- [wit-ai/wit-go](https://github.com/wit-ai/wit-go) — Go client for wit.ai HTTP API ☆`170`
### Cloud Provider APIs

- [googleapis/google-cloud-go](https://github.com/googleapis/google-cloud-go) — Google Cloud Client Libraries for Go. ☆`4,385`
- [googleapis/google-api-go-client](https://github.com/googleapis/google-api-go-client) — Auto-generated Google APIs for Go. ☆`4,362`
- [aws/aws-sdk-go-v2](https://github.com/aws/aws-sdk-go-v2) — AWS SDK for the Go programming language. ☆`3,398`
- [minio/minio-go](https://github.com/minio/minio-go) — MinIO Go client SDK for S3 compatible object storage ☆`2,880`
- [rhnvrm/simples3](https://github.com/rhnvrm/simples3) — Simple no frills AWS S3 Golang Library using REST with V4 Signing (without AWS Go SDK) ☆`184`
- [chainifynet/aws-encryption-sdk-go](https://github.com/chainifynet/aws-encryption-sdk-go) — AWS Encryption SDK for Go ☆`22`
- [circa10a/go-aws-news](https://github.com/circa10a/go-aws-news) — Go app + library to fetch what's new from AWS ☆`17`
### GitHub & Git APIs

- [google/go-github](https://github.com/google/go-github) — Go library for accessing the GitHub v3 API ☆`11,056`
- [shurcooL/githubv4](https://github.com/shurcooL/githubv4) — GitHub GraphQL API v4 client ☆`1,178`
- [go-playground/webhooks](https://github.com/go-playground/webhooks) — Webhook receiver for GitHub, Bitbucket, GitLab, Gogs ☆`1,016`
- [andygrunwald/go-trending](https://github.com/andygrunwald/go-trending) — Access GitHub trending repositories ☆`146`
- [andygrunwald/go-gerrit](https://github.com/andygrunwald/go-gerrit) — Go client/library for Gerrit Code Review ☆`102`
### Microsoft Office

- [qax-os/excelize](https://github.com/qax-os/excelize) — Go language library for reading and writing Microsoft Excel (XLAM / XLSM / XLSX / XLTM / XLTX) spreadsheets ☆`20,121`
- [unidoc/unioffice](https://github.com/unidoc/unioffice) — Pure go library for creating and processing Office Word (.docx), Excel (.xlsx) and Powerpoint (.pptx) documents ☆`4,757`
- [gomutex/godocx](https://github.com/gomutex/godocx) — Go library for reading and writing Microsoft Docx ☆`232`
- [go-the-way/exl](https://github.com/go-the-way/exl) — Excel binding to struct written in Go.(Only supports Go1.18+) ☆`32`
### ORM

- [go-gorm/gorm](https://github.com/go-gorm/gorm) — The fantastic ORM library for Golang, aims to be developer friendly ☆`39,290`
- [ent/ent](https://github.com/ent/ent) — An entity framework for Go ☆`16,794`
- [aarondl/sqlboiler](https://github.com/aarondl/sqlboiler) — Generate a Go ORM tailored to your database schema. ☆`6,971`
- [uptrace/bun](https://github.com/uptrace/bun) — SQL-first Golang ORM ☆`4,546`
- [upper/db](https://github.com/upper/db) — Data Access Layer (DAL) for PostgreSQL, CockroachDB, MySQL, SQLite and MongoDB with ORM-like features. ☆`3,630`
- [huandu/go-sqlbuilder](https://github.com/huandu/go-sqlbuilder) — SQL builder with zero-config ORM ☆`1,647`
- [stephenafamo/bob](https://github.com/stephenafamo/bob) — SQL query builder and ORM/Factory generator for Go with support for PostgreSQL, MySQL and SQLite ☆`1,584`
- [go-rel/rel](https://github.com/go-rel/rel) — Modern ORM for Golang - Testable, Extendable and Crafted Into a Clean and Elegant API ☆`781`
- [FrancoLiberali/cql](https://github.com/FrancoLiberali/cql) — CQL: Compiled Query Language ☆`17`
- [hashicorp/go-dbw](https://github.com/hashicorp/go-dbw) — A simple package that encapsulates database operations. ☆`16`
### Other APIs

- [codingsince1985/geo-golang](https://github.com/codingsince1985/geo-golang) — Go library to access geocoding and reverse geocoding APIs ☆`540`
- [onrik/ethrpc](https://github.com/onrik/ethrpc) — Golang client for ethereum json rpc api ☆`277`
- [cyruzin/golang-tmdb](https://github.com/cyruzin/golang-tmdb) — This is a Golang wrapper for working with TMDb API. It aims to support version 3. ☆`152`
- [gregdel/pushover](https://github.com/gregdel/pushover) — Go wrapper for the Pushover API ☆`154`
- [mvrilo/go-redoc](https://github.com/mvrilo/go-redoc) — go-redoc is an embedded OpenAPI/Swagger documentation ui for Go using ReDoc ☆`94`
- [rapito/go-spotify](https://github.com/rapito/go-spotify) — Go library for the Spotify Web API ☆`50`
- [rinchsan/device-check-go](https://github.com/rinchsan/device-check-go) — iOS DeviceCheck SDK for Go ☆`25`
- [zc2638/swag](https://github.com/zc2638/swag) — No comments, simple go wrapper to create swagger 2.0 compatible APIs. Support most routing frameworks, such as built-in, gin, chi, mux, echo, httprouter, fasthttp and more. ☆`50`
- [sostronk/go-steam](https://github.com/sostronk/go-steam) — Go library for querying Source servers ☆`33`
- [Icelain/jokeapi](https://github.com/Icelain/jokeapi) — Official golang wrapper for Sv443's jokeapi. ☆`27`
- [staskobzar/goami2](https://github.com/staskobzar/goami2) — Simple Asterisk Manager Interface (AMI) library fo golang ☆`21`
### Payment APIs

- [stripe/stripe-go](https://github.com/stripe/stripe-go) — Stripe API library for Go ☆`2,484`
- [plutov/paypal](https://github.com/plutov/paypal) — Golang client for PayPal REST API ☆`769`
- [brunomvsouza/ynab.go](https://github.com/brunomvsouza/ynab.go) — Go client for the YNAB API. Unofficial. It covers 100% of the resources made available by the YNAB API. ☆`78`
### Productivity APIs

- [mk-5/fjira](https://github.com/mk-5/fjira) — The golang fuzzy-find cli jira interface ☆`250`
- [adlio/trello](https://github.com/adlio/trello) — Trello API wrapper for Go ☆`227`
- [ctreminiom/go-atlassian](https://github.com/ctreminiom/go-atlassian) — Atlassian Cloud API client ☆`190`
- [koltyakov/gosip](https://github.com/koltyakov/gosip) — SharePoint SDK for Go ☆`166`
- [FreeLeh/GoFreeDB](https://github.com/FreeLeh/GoFreeDB) — Database on top of Google Sheets ☆`90`
- [mehanizm/airtable](https://github.com/mehanizm/airtable) — Simple golang airtable API wrapper ☆`82`
- [k-capehart/go-salesforce](https://github.com/k-capehart/go-salesforce) — Salesforce REST API client ☆`53`
### Query Language

- [99designs/gqlgen](https://github.com/99designs/gqlgen) — go generate based graphql server library ☆`10,620`
- [TomWright/dasel](https://github.com/TomWright/dasel) — Select, put and delete data from JSON, TOML, YAML, XML, INI, HCL and CSV files with a single tool. Also available as a go mod. ☆`7,749`
- [graph-gophers/graphql-go](https://github.com/graph-gophers/graphql-go) — GraphQL server with a focus on ease of use ☆`4,741`
- [bhmj/jsonslice](https://github.com/bhmj/jsonslice) — json slicer ☆`92`
- [hashicorp/mql](https://github.com/hashicorp/mql) — Model Query Language (mql) is a query language for your database models. ☆`65`
- [ccbrown/api-fu](https://github.com/ccbrown/api-fu) — A collection of Go packages for creating robust GraphQL APIs ☆`57`
- [AsaiYusuke/jsonpath](https://github.com/AsaiYusuke/jsonpath) — A query library for retrieving part of JSON based on JSONPath syntax. ☆`29`
### Social & Chat APIs

- [bwmarrin/discordgo](https://github.com/bwmarrin/discordgo) — (Golang) Go bindings for Discord ☆`5,715`
- [slack-go/slack](https://github.com/slack-go/slack) — Slack API in Go ☆`4,881`
- [huandu/facebook](https://github.com/huandu/facebook) — A Facebook Graph API SDK For Go. ☆`1,432`
- [ChimeraCoder/anaconda](https://github.com/ChimeraCoder/anaconda) — A Go client library for the Twitter 1.1 API ☆`1,142`
- [chyroc/lark](https://github.com/chyroc/lark) — Lark/Feishu Open API SDK ☆`458`
- [go-lark/lark](https://github.com/go-lark/lark) — An easy-to-use SDK for Feishu and Lark Open Platform (Instant Messaging API only) ☆`233`
- [switchupcb/disgo](https://github.com/switchupcb/disgo) — Disgo is the next generation of Discord API Consumption. Create a Discord Bot with Go using this Discord API Wrapper (SDK Client). ☆`109`
## Messaging & Bots

### Bot Building

- [tucnak/telebot](https://github.com/tucnak/telebot) — Telebot is a Telegram bot framework in Go. ☆`4,515`
- [go-telegram/bot](https://github.com/go-telegram/bot) — Telegram Bot API Go framework ☆`1,501`
- [mymmrac/telego](https://github.com/mymmrac/telego) — Telegram Bot API library for Go ☆`855`
- [diamondburned/arikawa](https://github.com/diamondburned/arikawa) — A Golang library and framework for the Discord API. ☆`562`
- [NicoNex/echotron](https://github.com/NicoNex/echotron) — An elegant and concurrent library for the Telegram bot API in Go. ☆`413`
- [gempir/go-twitch-irc](https://github.com/gempir/go-twitch-irc) — go irc client for twitch.tv ☆`389`
- [innogames/slack-bot](https://github.com/innogames/slack-bot) — Slack bot for Jenkins, Jira, PRs ☆`204`
- [mr-linch/go-tg](https://github.com/mr-linch/go-tg) — Go client library for accessing Telegram Bot API, with batteries for building complex bots included. ☆`124`
- [slack-io/slacker](https://github.com/slack-io/slacker) — Slack Bot Framework ☆`61`
- [onrik/micha](https://github.com/onrik/micha) — Client lib for Telegram bot api ☆`31`
### Email

- [axllent/mailpit](https://github.com/axllent/mailpit) — An email and SMTP testing tool with API for developers ☆`8,336`
- [foxcpp/maddy](https://github.com/foxcpp/maddy) — Composable all-in-one mail server. ☆`5,775`
- [mjl-/mox](https://github.com/mjl-/mox) — modern full-featured open source secure mail server for low-maintenance self-hosted email ☆`5,322`
- [matcornic/hermes](https://github.com/matcornic/hermes) — Clean HTML email generator ☆`3,018`
- [AfterShip/email-verifier](https://github.com/AfterShip/email-verifier) — Email verification without sending emails ☆`1,487`
- [wneessen/go-mail](https://github.com/wneessen/go-mail) — Easy to use, yet comprehensive library for sending mails with Go ☆`1,223`
- [sendgrid/sendgrid-go](https://github.com/sendgrid/sendgrid-go) — The Official Twilio SendGrid Golang API Library ☆`1,044`
- [mailgun/mailgun-go](https://github.com/mailgun/mailgun-go) — Go library for sending mail with the Mailgun API. ☆`742`
- [xhit/go-simple-mail](https://github.com/xhit/go-simple-mail) — Simple mail sending with TLS/SSL ☆`688`
- [emersion/go-message](https://github.com/emersion/go-message) — Internet Message Format library ☆`432`
- [vanng822/go-premailer](https://github.com/vanng822/go-premailer) — Inline CSS for HTML mail ☆`180`
- [mocktools/go-smtp-mock](https://github.com/mocktools/go-smtp-mock) — SMTP mock server for testing ☆`158`
- [truemail-rb/truemail-go](https://github.com/truemail-rb/truemail-go) — Email validator via Regex, DNS, SMTP ☆`129`
- [toorop/go-dkim](https://github.com/toorop/go-dkim) — DKIM package for golang ☆`99`
- [dimuska139/go-email-normalizer](https://github.com/dimuska139/go-email-normalizer) — Normalize email addresses ☆`76`
- [valord577/mailx](https://github.com/valord577/mailx) — A library that makes it easier to send email via SMTP. ☆`20`
### Messaging

- [hibiken/asynq](https://github.com/hibiken/asynq) — Simple, reliable, and efficient distributed task queue in Go ☆`12,651`
- [IBM/sarama](https://github.com/IBM/sarama) — Sarama is a Go library for Apache Kafka. ☆`12,352`
- [centrifugal/centrifugo](https://github.com/centrifugal/centrifugo) — Scalable real-time messaging server ☆`9,663`
- [ThreeDotsLabs/watermill](https://github.com/ThreeDotsLabs/watermill) — Building event-driven applications the easy way in Go. ☆`9,343`
- [appleboy/gorush](https://github.com/appleboy/gorush) — A push notification server written in Go (Golang). ☆`8,652`
- [RichardKnop/machinery](https://github.com/RichardKnop/machinery) — Async task queue with message passing ☆`7,914`
- [nats-io/nats.go](https://github.com/nats-io/nats.go) — Golang client for NATS, the cloud native messaging system. ☆`6,319`
- [confluentinc/confluent-kafka-go](https://github.com/confluentinc/confluent-kafka-go) — Confluent's Apache Kafka Golang client ☆`5,071`
- [dunglas/mercure](https://github.com/dunglas/mercure) — An open, easy, fast, reliable and battery-efficient solution for real-time communications ☆`5,142`
- [olahol/melody](https://github.com/olahol/melody) — Minimalist websocket framework for Go ☆`4,036`
- [sideshow/apns2](https://github.com/sideshow/apns2) — HTTP/2 Apple Push Notification Service (APNs) push provider for Go — Send push notifications to iOS, tvOS, Safari and OSX apps, using the APNs HTTP/2 protocol. ☆`3,149`
- [lovoo/goka](https://github.com/lovoo/goka) — Goka is a compact yet powerful distributed stream processing library for Apache Kafka written in Go. ☆`2,494`
- [asaskevich/EventBus](https://github.com/asaskevich/EventBus) — [Go] Lightweight eventbus with async compatibility for Go ☆`1,949`
- [rabbitmq/amqp091-go](https://github.com/rabbitmq/amqp091-go) — An AMQP 0-9-1 Go client maintained by the RabbitMQ team ☆`1,943`
- [containrrr/shoutrrr](https://github.com/containrrr/shoutrrr) — Notification library for gophers and their furry friends. ☆`1,434`
- [pebbe/zmq4](https://github.com/pebbe/zmq4) — A Go interface to ZeroMQ version 4 ☆`1,240`
- [timbray/quamina](https://github.com/timbray/quamina) — Fast pattern-matching library ☆`437`
- [cskr/pubsub](https://github.com/cskr/pubsub) — A simple pubsub package for go. ☆`446`
- [jandelgado/rabtap](https://github.com/jandelgado/rabtap) — RabbitMQ wire tap and swiss army knife ☆`279`
- [mehdihadeli/Go-MediatR](https://github.com/mehdihadeli/Go-MediatR) — Mediator pattern for CQRS ☆`269`
- [goptics/varmq](https://github.com/goptics/varmq) — A Simplest Storage-Agnostic and Zero-dep Message Queue for Your Concurrent Go Program ☆`176`
- [hyperonym/ratus](https://github.com/hyperonym/ratus) — Ratus is a RESTful asynchronous task queue server. It translated concepts of distributed task queues into a set of resources that conform to REST principles and provides a consistent HTTP API for various backends. ☆`124`
- [robinjoseph08/redisqueue](https://github.com/robinjoseph08/redisqueue) — Redis streams producer and consumer ☆`138`
- [oagudo/outbox](https://github.com/oagudo/outbox) — Lightweight library for the transactional outbox pattern in Go, not tied to any specific relational database or broker. ☆`113`
- [furdarius/rabbitroutine](https://github.com/furdarius/rabbitroutine) — RabbitMQ auto-reconnect library ☆`113`
- [dailymotion/oplog](https://github.com/dailymotion/oplog) — A generic oplog/replication system for microservices ☆`110`
- [Protocol-Lattice/GoEventBus](https://github.com/Protocol-Lattice/GoEventBus) — A lock-free, ultra-fast event bus for Go ☆`48`
- [jirenius/go-res](https://github.com/jirenius/go-res) — RES Service protocol library for Go ☆`68`
- [SchwarzIT/hypermatch](https://github.com/SchwarzIT/hypermatch) — High-performance rule matching ☆`33`
- [maxatome/go-vitotrol](https://github.com/maxatome/go-vitotrol) — golang client library to Viessmann Vitotrol web service ☆`23`
### Webhooks

- [adnanh/webhook](https://github.com/adnanh/webhook) — webhook is a lightweight incoming webhook server to run shell commands ☆`11,442`
- [webhookx-io/webhookx](https://github.com/webhookx-io/webhookx) — The Next-Generation Webhooks Gateway. ☆`267`
- [42atomys/webhooked](https://github.com/42atomys/webhooked) — A webhook receiver on steroids. ☆`41`
## Networking

### Consensus

- [hashicorp/raft](https://github.com/hashicorp/raft) — Golang implementation of the Raft consensus protocol ☆`8,874`
- [lni/dragonboat](https://github.com/lni/dragonboat) — A feature complete and high performance multi-group Raft library in Go. ☆`5,285`
- [etcd-io/raft](https://github.com/etcd-io/raft) — Raft library for maintaining a replicated state machine ☆`962`
- [vadiminshakov/committer](https://github.com/vadiminshakov/committer) — 2PC and 3PC protocols for Go ☆`41`
### DNS

- [miekg/dns](https://github.com/miekg/dns) — DNS library in Go ☆`8,598`
- [hashicorp/mdns](https://github.com/hashicorp/mdns) — Simple mDNS client/server library in Golang ☆`1,319`
- [semihalev/sdns](https://github.com/semihalev/sdns) — A high-performance, recursive DNS resolver server with DNSSEC support, focused on preserving privacy. ☆`1,021`
- [mosajjal/dnsmonster](https://github.com/mosajjal/dnsmonster) — Passive DNS Capture and Monitoring Toolkit ☆`348`
- [joeig/go-powerdns](https://github.com/joeig/go-powerdns) — PowerDNS API client for Go (community project) ☆`103`
### Distributed Utilities

- [luraproject/lura](https://github.com/luraproject/lura) — Ultra performant API Gateway with middlewares. A project hosted at The Linux Foundation ☆`6,704`
- [chrislusf/gleam](https://github.com/chrislusf/gleam) — Fast, efficient, and scalable distributed map/reduce system, DAG execution, in memory or on disk, written in pure Go, runs standalone or distributedly. ☆`3,551`
- [bsm/redislock](https://github.com/bsm/redislock) — Simplified distributed locking implementation using Redis ☆`1,725`
- [k8gb-io/k8gb](https://github.com/k8gb-io/k8gb) — A cloud native Kubernetes Global Balancer ☆`1,131`
- [temporalio/sdk-go](https://github.com/temporalio/sdk-go) — Temporal Go SDK ☆`790`
- [AppsFlyer/go-sundheit](https://github.com/AppsFlyer/go-sundheit) — A library built to provide support for defining service health for golang services. It allows you to register async health checks for your dependencies and the service itself, provides a health endpoint that exposes their status, and health metrics. ☆`560`
- [tarmac-project/tarmac](https://github.com/tarmac-project/tarmac) — Write as Functions, Deploy as a Monolith or Microservice with WebAssembly ☆`339`
- [italolelis/outboxer](https://github.com/italolelis/outboxer) — A library that implements the outboxer pattern in go ☆`164`
- [capillariesio/capillaries](https://github.com/capillariesio/capillaries) — Distributed batch data processing framework ☆`69`
- [svcavallar/celeriac.v1](https://github.com/svcavallar/celeriac.v1) — Golang client library for adding support for interacting and monitoring Celery workers, tasks and events. ☆`76`
- [sanketplus/go-mysql-lock](https://github.com/sanketplus/go-mysql-lock) — MySQL Backed Locking Primitive ☆`66`
- [pdupub/go-pdu](https://github.com/pdupub/go-pdu) — An PDU implementation in Go ☆`49`
- [mbrostami/consistenthash](https://github.com/mbrostami/consistenthash) — Consistent hashing implementation ☆`30`
### HTTP & Proxy

- [valyala/fasthttp](https://github.com/valyala/fasthttp) — Fast HTTP package for Go. Tuned for high performance. Zero memory allocations in hot paths. Up to 10x faster than net/http ☆`23,159`
- [elazarl/goproxy](https://github.com/elazarl/goproxy) — An HTTP proxy library for Go ☆`6,553`
- [eduardonunesp/sslb](https://github.com/eduardonunesp/sslb) — Simple load balancer ☆`151`
- [wzshiming/httpproxy](https://github.com/wzshiming/httpproxy) — HTTP proxy handler and dialer ☆`31`
### HTTP Clients

- [go-resty/resty](https://github.com/go-resty/resty) — Simple HTTP, REST, and SSE client library for Go ☆`11,429`
- [imroc/req](https://github.com/imroc/req) — Simple Go HTTP client with Black Magic ☆`4,710`
- [gojek/heimdall](https://github.com/gojek/heimdall) — An enhanced HTTP client for Go ☆`2,701`
- [hashicorp/go-retryablehttp](https://github.com/hashicorp/go-retryablehttp) — Retryable HTTP client in Go ☆`2,247`
- [levigross/grequests](https://github.com/levigross/grequests) — A Go "clone" of the great and famous Requests library ☆`2,183`
- [dghubble/sling](https://github.com/dghubble/sling) — A Go HTTP client library for creating and sending API requests ☆`1,717`
- [earthboundkid/requests](https://github.com/earthboundkid/requests) — HTTP requests for Gophers ☆`1,658`
- [bogdanfinn/tls-client](https://github.com/bogdanfinn/tls-client) — HTTP client with TLS fingerprint spoofing ☆`1,374`
- [Noooste/azuretls-client](https://github.com/Noooste/azuretls-client) — HTTP client to spoof TLS/JA3 fingerprint ☆`398`
- [monaco-io/request](https://github.com/monaco-io/request) — go request, go http client ☆`294`
- [NdoleStudio/go-otelroundtripper](https://github.com/NdoleStudio/go-otelroundtripper) — OpenTelemetry metrics for HTTP clients ☆`84`
- [opus-domini/fast-shot](https://github.com/opus-domini/fast-shot) — Hit your API targets with rapid-fire precision using Go's fastest and simple HTTP Client. ☆`94`
- [go-zoox/fetch](https://github.com/go-zoox/fetch) — Go Fetch - A Powerful, Lightweight, Easy Http Client, inspired by Web Fetch API ☆`88`
- [rezmoss/axios4go](https://github.com/rezmoss/axios4go) — A Go HTTP client library inspired by Axios, providing a simple and intuitive API for making HTTP requests with features like interceptors, JSON handling, configurable instances, and automatic retries ☆`30`
### Message Brokers

- [nats-io/nats-server](https://github.com/nats-io/nats-server) — High-performance NATS message server ☆`18,853`
- [emitter-io/emitter](https://github.com/emitter-io/emitter) — High performance, distributed and low latency publish-subscribe platform. ☆`3,996`
- [mochi-mqtt/server](https://github.com/mochi-mqtt/server) — The fully compliant, embeddable high-performance Go MQTT v5 server for IoT, smarthome, and pubsub ☆`1,746`
### Microservices

- [zeromicro/go-zero](https://github.com/zeromicro/go-zero) — A cloud-native Go microservices framework with cli tool for productivity. ☆`32,330`
- [go-kit/kit](https://github.com/go-kit/kit) — A standard library for microservices. ☆`27,572`
- [go-kratos/kratos](https://github.com/go-kratos/kratos) — Your ultimate Go microservices framework for the cloud-native era. ☆`25,258`
- [micro/go-micro](https://github.com/micro/go-micro) — A Go microservices framework ☆`22,643`
- [smallnest/rpcx](https://github.com/smallnest/rpcx) — Best microservices framework in Go, like alibaba Dubbo, but with more features, Scale easily ☆`8,270`
- [cloudwego/kitex](https://github.com/cloudwego/kitex) — Go RPC framework with high-performance and strong-extensibility for building micro-services. ☆`7,788`
- [go-dev-frame/sponge](https://github.com/go-dev-frame/sponge) — A powerful and easy-to-use Go development framework that enables you to effortlessly build stable, reliable, and high-performance backend services with a "low-code" approach. ☆`2,735`
- [go-eagle/eagle](https://github.com/go-eagle/eagle) — A Go framework for the API or Microservice ☆`2,407`
- [unionj-cloud/go-doudou](https://github.com/unionj-cloud/go-doudou) — OpenAPI 3 and gRPC microservices framework ☆`1,208`
- [trpc-group/trpc-go](https://github.com/trpc-group/trpc-go) — A pluggable, high-performance RPC framework written in golang ☆`1,090`
- [gmsec/micro](https://github.com/gmsec/micro) — A Go distributed systems development framework ☆`25`
### Network Utilities

- [fortio/fortio](https://github.com/fortio/fortio) — Load testing and echo server ☆`3,651`
- [hashicorp/go-getter](https://github.com/hashicorp/go-getter) — Package for downloading things from a string URL using a variety of protocols. ☆`1,787`
- [TimothyYe/godns](https://github.com/TimothyYe/godns) — A dynamic DNS client tool that supports AliDNS, Cloudflare, Google Domains, DNSPod, HE.net & DuckDNS & DreamHost, etc, written in Go. ☆`1,721`
- [cavaliergopher/grab](https://github.com/cavaliergopher/grab) — Download manager package ☆`1,465`
- [schollz/peerdiscovery](https://github.com/schollz/peerdiscovery) — Pure-Go library for cross-platform local peer discovery using UDP multicast ☆`667`
- [fclairamb/ftpserverlib](https://github.com/fclairamb/ftpserverlib) — FTP server library for Go ☆`460`
- [skibish/ddns](https://github.com/skibish/ddns) — Personal DDNS client with Digital Ocean Networking DNS as backend. ☆`267`
- [c-robinson/iplib](https://github.com/c-robinson/iplib) — A library for working with IP addresses and networks in Go ☆`151`
- [gaissmai/bart](https://github.com/gaissmai/bart) — The Balanced Routing Table is an adaptation of D. Knuth's ART algorithm and requires significantly less memory and has an even better lookup speed. ☆`109`
- [alegrey91/fwdctl](https://github.com/alegrey91/fwdctl) — Manage IPTables forwards via CLI ☆`73`
### P2P & Torrent

- [anacrolix/torrent](https://github.com/anacrolix/torrent) — Full-featured BitTorrent client package and utilities ☆`5,921`
- [dragonflyoss/dragonfly](https://github.com/dragonflyoss/dragonfly) — P2P-based container image distribution ☆`2,943`
- [cenkalti/rain](https://github.com/cenkalti/rain) — BitTorrent client and library in Go ☆`1,101`
- [anacrolix/dht](https://github.com/anacrolix/dht) — dht is used by anacrolix/torrent, and is intended for use as a library in other projects both torrent related and otherwise ☆`346`
### Protocols

- [pion/webrtc](https://github.com/pion/webrtc) — Pure Go implementation of the WebRTC API ☆`15,837`
- [quic-go/quic-go](https://github.com/quic-go/quic-go) — A production-ready QUIC implementation in pure Go ☆`11,272`
- [google/gopacket](https://github.com/google/gopacket) — Provides packet processing capabilities for Go ☆`6,704`
- [osrg/gobgp](https://github.com/osrg/gobgp) — BGP implemented in the Go Programming Language ☆`3,942`
- [lxzan/gws](https://github.com/lxzan/gws) — simple, fast, reliable websocket server & client, supports running over tcp/kcp/unix domain socket. keywords: ws, proxy, chat, go, golang... ☆`1,683`
- [gosnmp/gosnmp](https://github.com/gosnmp/gosnmp) — An SNMP library written in Go ☆`1,234`
- [ccding/go-stun](https://github.com/ccding/go-stun) — A go implementation of the STUN client (RFC 3489 and RFC 5389) ☆`713`
- [google/gnxi](https://github.com/google/gnxi) — gNXI Tools - gRPC Network Management/Operations Interface Tools ☆`282`
- [jeroenrinzema/psql-wire](https://github.com/jeroenrinzema/psql-wire) — PostgreSQL wire protocol for Go ☆`207`
- [jimlambrt/gldap](https://github.com/jimlambrt/gldap) — Build LDAP services w/ Go ☆`118`
- [soypat/natiu-mqtt](https://github.com/soypat/natiu-mqtt) — A dead-simple, extensible MQTT implementation well suited for embedded systems. ☆`101`
### RPC

- [grpc/grpc-go](https://github.com/grpc/grpc-go) — The Go language implementation of gRPC. HTTP/2 based RPC ☆`22,677`
- [hprose/hprose-golang](https://github.com/hprose/hprose-golang) — Cross-language RPC for Go ☆`1,263`
- [lesismal/arpc](https://github.com/lesismal/arpc) — Two-way RPC with broadcast support ☆`1,085`
- [ybbus/jsonrpc](https://github.com/ybbus/jsonrpc) — A simple go implementation of json rpc 2.0 client over http ☆`366`
- [osamingo/jsonrpc](https://github.com/osamingo/jsonrpc) — The jsonrpc package helps implement of JSON-RPC 2.0 ☆`192`
### SSH & SFTP

- [gliderlabs/ssh](https://github.com/gliderlabs/ssh) — Easy SSH servers in Golang ☆`4,046`
- [pkg/sftp](https://github.com/pkg/sftp) — SFTP support for the go.crypto/ssh package ☆`1,627`
- [masterzen/winrm](https://github.com/masterzen/winrm) — Command-line tool and library for Windows remote command execution in Go ☆`456`
### Server Applications

- [caddyserver/caddy](https://github.com/caddyserver/caddy) — Fast and extensible multi-platform HTTP/1-2-3 web server with automatic HTTPS ☆`68,756`
- [minio/minio](https://github.com/minio/minio) — MinIO is a high-performance, S3 compatible object store, open sourced under GNU AGPLv3 license. ☆`59,420`
- [pocketbase/pocketbase](https://github.com/pocketbase/pocketbase) — Open Source realtime backend in 1 file ☆`54,605`
- [etcd-io/etcd](https://github.com/etcd-io/etcd) — Distributed reliable key-value store for the most critical data of a distributed system ☆`51,146`
- [drakkan/sftpgo](https://github.com/drakkan/sftpgo) — Full-featured and highly configurable SFTP, HTTP/S, FTP/S and WebDAV server - S3, Google Cloud Storage, Azure Blob ☆`11,503`
- [roadrunner-server/roadrunner](https://github.com/roadrunner-server/roadrunner) — High-performance PHP application server ☆`8,358`
- [easegress-io/easegress](https://github.com/easegress-io/easegress) — A Cloud Native traffic orchestration system ☆`5,869`
- [flipt-io/flipt](https://github.com/flipt-io/flipt) — Enterprise-ready, Git native feature management solution ☆`4,668`
- [charmbracelet/wish](https://github.com/charmbracelet/wish) — Make SSH apps, just like that! ☆`4,646`
- [getfider/fider](https://github.com/getfider/fider) — Open platform to collect and prioritize feedback ☆`3,928`
- [xyproto/algernon](https://github.com/xyproto/algernon) — Small self-contained pure-Go web server with Lua, Teal, Markdown, Ollama, HTTP/2, QUIC, Redis, SQLite and PostgreSQL support ++ ☆`2,971`
- [openflagr/flagr](https://github.com/openflagr/flagr) — Flagr is a feature flagging, A/B testing and dynamic configuration microservice ☆`2,562`
- [thomaspoignant/go-feature-flag](https://github.com/thomaspoignant/go-feature-flag) — Open source feature flag solution ☆`1,877`
- [openrundev/openrun](https://github.com/openrundev/openrun) — Open source alternative to Google Cloud Run and AWS App Runner. Easily deploy web apps declaratively. ☆`713`
- [blind-oracle/cortex-tenant](https://github.com/blind-oracle/cortex-tenant) — Prometheus proxy with tenant ID injection ☆`129`
- [baalimago/wd-41](https://github.com/baalimago/wd-41) — Web-Development 41, a static web server with live-reload ☆`150`
- [rekby/lets-proxy2](https://github.com/rekby/lets-proxy2) — Reverse proxy with automatically obtains TLS certificates from Let's Encrypt ☆`101`
### TCP/UDP Frameworks

- [xtaci/kcptun](https://github.com/xtaci/kcptun) — A Quantum-Safe Secure Tunnel based on QPP, KCP, FEC, and N:M multiplexing. ☆`14,319`
- [panjf2000/gnet](https://github.com/panjf2000/gnet) — gnet is a high-performance, lightweight, non-blocking, event-driven networking framework written in pure Go. ☆`10,981`
- [cloudwego/netpoll](https://github.com/cloudwego/netpoll) — A high-performance non-blocking I/O networking framework focusing on RPC scenarios. ☆`4,494`
- [xtaci/kcp-go](https://github.com/xtaci/kcp-go) — A Crypto-Secure Reliable-UDP Library for golang with FEC ☆`4,367`
- [lesismal/nbio](https://github.com/lesismal/nbio) — Pure Go 1000k+ connections solution, support tls/http1.x/websocket and basically compatible with net/http, with high-performance and low memory cost, non-blocking, event-driven, easy-to-use. ☆`2,682`
- [Allenxuxu/gev](https://github.com/Allenxuxu/gev) — Gev is a lightweight, fast non-blocking TCP network library / websocket server based on Reactor mode. Support custom protocols to quickly and easily build high-performance servers. ☆`1,771`
- [xtaci/gaio](https://github.com/xtaci/gaio) — High performance minimalism async-io(proactor) networking for Golang. ☆`799`
- [cheng-zhongliang/event](https://github.com/cheng-zhongliang/event) — Simple I/O event notification library wirtten in Golang ☆`119`
- [fish-tennis/gnet](https://github.com/fish-tennis/gnet) — high performance net library for game server ☆`26`
### VPN & Tunneling

- [cloudflare/cloudflared](https://github.com/cloudflare/cloudflared) — Cloudflare Tunnel client ☆`12,441`
- [xjasonlyu/tun2socks](https://github.com/xjasonlyu/tun2socks) — TUN to SOCKS proxy ☆`4,753`
- [songgao/water](https://github.com/songgao/water) — A simple TUN/TAP library written in native Go. ☆`2,110`
- [yosebyte/nodepass](https://github.com/yosebyte/nodepass) — Secure TCP/UDP tunneling with TLS ☆`1,573`
## Other

### Other Software

- [schollz/croc](https://github.com/schollz/croc) — Easily and securely send things from one computer to another ☆`33,500`
- [restic/restic](https://github.com/restic/restic) — Fast, secure backup program ☆`31,393`
- [seaweedfs/seaweedfs](https://github.com/seaweedfs/seaweedfs) — Fast distributed storage for blobs ☆`29,085`
- [juicedata/juicefs](https://github.com/juicedata/juicefs) — Distributed POSIX filesystem ☆`12,576`
- [Shopify/toxiproxy](https://github.com/Shopify/toxiproxy) — A TCP proxy to simulate network and system conditions for chaos and resiliency testing ☆`11,753`
- [0xERR0R/blocky](https://github.com/0xERR0R/blocky) — Fast and lightweight DNS proxy as ad-blocker for local network with many features ☆`5,834`
- [fogleman/nes](https://github.com/fogleman/nes) — NES emulator written in Go. ☆`5,631`
- [gilbertchen/duplicacy](https://github.com/gilbertchen/duplicacy) — Cloud backup tool ☆`5,593`
- [Forceu/Gokapi](https://github.com/Forceu/Gokapi) — Lightweight selfhosted Firefox Send alternative without public upload. AWS S3 supported. ☆`2,470`
- [documize/community](https://github.com/documize/community) — Modern Confluence alternative ☆`2,347`
- [go-sonic/sonic](https://github.com/go-sonic/sonic) — Blogging platform in Go ☆`2,118`
- [wabarc/wayback](https://github.com/wabarc/wayback) — Web archiving tool with IM interface ☆`2,115`
- [root-gg/plik](https://github.com/root-gg/plik) — Temporary file upload system ☆`1,679`
- [SpatiumPortae/portal](https://github.com/SpatiumPortae/portal) — Command-line file transfer utility ☆`1,717`
- [msoap/shell2http](https://github.com/msoap/shell2http) — Executing shell commands via HTTP server ☆`1,463`
- [pointlander/peg](https://github.com/pointlander/peg) — Peg, Parsing Expression Grammar, is an implementation of a Packrat parser generator. ☆`1,094`
- [janpfeifer/gonb](https://github.com/janpfeifer/gonb) — Go notebook kernel for Jupyter ☆`968`
- [alajmo/sake](https://github.com/alajmo/sake) — Task runner for local and remote hosts ☆`740`
- [chapar-rest/chapar](https://github.com/chapar-rest/chapar) — API testing for HTTP and gRPC ☆`674`
- [goccmack/gocc](https://github.com/goccmack/gocc) — Parser and scanner generator ☆`652`
- [moshebe/gebug](https://github.com/moshebe/gebug) — Debug Dockerized Go apps ☆`634`
- [edwingeng/hotswap](https://github.com/edwingeng/hotswap) — Hot reload Go code without restart ☆`415`
- [marwanhawari/stew](https://github.com/marwanhawari/stew) — An independent package manager for compiled binaries. ☆`312`
- [assafmo/joincap](https://github.com/assafmo/joincap) — Merge pcap files ☆`219`
- [lingrino/vaku](https://github.com/lingrino/vaku) — Extended Vault API and CLI ☆`158`
- [DMcP89/tinycare-tui](https://github.com/DMcP89/tinycare-tui) — TUI application written in GO inspired by tiny-care-terminal ☆`16`
## Science & Geography

### Geographic

- [tidwall/tile38](https://github.com/tidwall/tile38) — Real-time Geospatial and Geofencing ☆`9,544`
- [golang/geo](https://github.com/golang/geo) — S2 geometry library in Go ☆`1,810`
- [consbio/mbtileserver](https://github.com/consbio/mbtileserver) — MBTiles server in Go ☆`766`
- [spatial-go/geoos](https://github.com/spatial-go/geoos) — Spatial data and geometric algorithms ☆`526`
- [paulmach/osm](https://github.com/paulmach/osm) — OpenStreetMap data library ☆`436`
- [uber/h3-go](https://github.com/uber/h3-go) — H3 hexagonal geospatial indexing ☆`384`
- [airbusgeo/godal](https://github.com/airbusgeo/godal) — GDAL wrapper for Go ☆`173`
- [peterstace/simplefeatures](https://github.com/peterstace/simplefeatures) — OpenGIS Simple Feature implementation ☆`164`
- [wroge/wgs84](https://github.com/wroge/wgs84) — Zero-dep coordinate transformations ☆`140`
- [pantrif/s2-geojson](https://github.com/pantrif/s2-geojson) — Visualize S2 cells on a map ☆`36`
### Science

- [gonum/gonum](https://github.com/gonum/gonum) — Numeric libraries for Go ☆`8,269`
- [gonum/plot](https://github.com/gonum/plot) — Plotting and visualization ☆`2,932`
- [paulmach/orb](https://github.com/paulmach/orb) — 2D geometry types and utilities ☆`1,071`
- [bebop/poly](https://github.com/bebop/poly) — Synthetic biology library for Go ☆`716`
- [hmdsefi/gograph](https://github.com/hmdsefi/gograph) — Generic graph algorithms library ☆`102`
- [nikolaydubina/jsonl-graph](https://github.com/nikolaydubina/jsonl-graph) — JSONL Graph Tools ☆`77`
- [claygod/PiHex](https://github.com/claygod/PiHex) — PiHex Library, written in Go, generates a hexadecimal number sequence in the number Pi in the range from 0 to 10,000,000. ☆`20`
## Scripting

### Embeddable Languages

- [php/frankenphp](https://github.com/php/frankenphp) — The modern PHP app server ☆`10,577`
- [expr-lang/expr](https://github.com/expr-lang/expr) — Expression evaluation for Go ☆`7,549`
- [yuin/gopher-lua](https://github.com/yuin/gopher-lua) — Lua VM and compiler in Go ☆`6,811`
- [dop251/goja](https://github.com/dop251/goja) — ECMAScript engine in pure Go ☆`6,648`
- [d5/tengo](https://github.com/d5/tengo) — Fast script language for Go ☆`3,754`
- [Shopify/go-lua](https://github.com/Shopify/go-lua) — Lua VM in Go ☆`3,384`
- [google/cel-go](https://github.com/google/cel-go) — Common Expression Language for Go ☆`2,803`
- [google/starlark-go](https://github.com/google/starlark-go) — Starlark config language in Go ☆`2,591`
- [metacall/core](https://github.com/metacall/core) — Polyglot programming runtime ☆`1,747`
- [wa-lang/wa](https://github.com/wa-lang/wa) — The Wa Programming Language ☆`1,741`
- [mattn/anko](https://github.com/mattn/anko) — Scriptable interpreter in Go ☆`1,550`
- [PaesslerAG/gval](https://github.com/PaesslerAG/gval) — Expression evaluation in Go ☆`809`
- [ichiban/prolog](https://github.com/ichiban/prolog) — Prolog scripting engine for Go ☆`702`
- [aarzilli/golua](https://github.com/aarzilli/golua) — Lua C API bindings for Go ☆`687`
- [1set/starlet](https://github.com/1set/starlet) — Starlark wrapper with batteries ☆`40`
### Generators

- [oapi-codegen/oapi-codegen](https://github.com/oapi-codegen/oapi-codegen) — Generate Go code from OpenAPI 3 specs ☆`7,917`
- [dave/jennifer](https://github.com/dave/jennifer) — Code generator for Go ☆`3,587`
- [hexdigest/gowrap](https://github.com/hexdigest/gowrap) — Generate interface decorators ☆`1,296`
- [awalterschulze/goderive](https://github.com/awalterschulze/goderive) — Generate mundane Go functions ☆`1,271`
- [abice/go-enum](https://github.com/abice/go-enum) — Enum generator for Go ☆`907`
- [jmattheis/goverter](https://github.com/jmattheis/goverter) — Generate type-safe converters ☆`796`
- [rjeczalik/interfaces](https://github.com/rjeczalik/interfaces) — Code generation tools for Go ☆`432`
- [switchupcb/copygen](https://github.com/switchupcb/copygen) — Copy values between types ☆`399`
- [reedom/convergen](https://github.com/reedom/convergen) — Type-to-type copy code generator ☆`48`
## Testing & Quality

### Benchmarks

- [smallnest/go-web-framework-benchmark](https://github.com/smallnest/go-web-framework-benchmark) — Web framework benchmarks ☆`2,137`
- [alecthomas/go_serialization_benchmarks](https://github.com/alecthomas/go_serialization_benchmarks) — Serialization benchmarks for Go ☆`1,620`
- [SimonWaldherr/golang-benchmarks](https://github.com/SimonWaldherr/golang-benchmarks) — Go(lang) benchmarks - (measure the speed of golang) ☆`141`
- [feyeleanor/gospeed](https://github.com/feyeleanor/gospeed) — Go micro-benchmarks for calculating the speed of language constructs ☆`126`
- [nikolaydubina/go-ml-benchmarks](https://github.com/nikolaydubina/go-ml-benchmarks) — Benchmarks of machine learning inference for Go ☆`32`
### Code Analysis

- [golangci/golangci-lint](https://github.com/golangci/golangci-lint) — Fast linters runner for Go ☆`18,201`
- [boyter/scc](https://github.com/boyter/scc) — Sloc, Cloc and Code: scc is a very fast accurate code counter with complexity calculations and COCOMO estimates written in pure Go ☆`7,895`
- [mgechev/revive](https://github.com/mgechev/revive) — Fast, extensible Go linter ☆`5,367`
- [kisielk/errcheck](https://github.com/kisielk/errcheck) — errcheck checks that you checked errors. ☆`2,458`
- [go-critic/go-critic](https://github.com/go-critic/go-critic) — The most opinionated Go source code linter for code audit. ☆`2,026`
- [daveshanley/vacuum](https://github.com/daveshanley/vacuum) — Fast OpenAPI linter ☆`969`
- [presmihaylov/todocheck](https://github.com/presmihaylov/todocheck) — Analyser for TODO comments ☆`436`
- [mdempsky/unconvert](https://github.com/mdempsky/unconvert) — Remove unnecessary type conversions ☆`386`
- [tomarrell/wrapcheck](https://github.com/tomarrell/wrapcheck) — Check errors are wrapped ☆`354`
- [mibk/dupl](https://github.com/mibk/dupl) — Code clone detection tool ☆`360`
- [shurcooL/gostatus](https://github.com/shurcooL/gostatus) — Show status of Go repositories ☆`245`
- [Antonboom/testifylint](https://github.com/Antonboom/testifylint) — Linter for testify usage ☆`162`
- [Crocmagnon/fatcontext](https://github.com/Crocmagnon/fatcontext) — Detect nested contexts in loops ☆`63`
- [antham/ghokin](https://github.com/antham/ghokin) — Parallelized formatter with no external dependencies for gherkin (cucumber, behat...) ☆`49`
- [asticode/go-astitodo](https://github.com/asticode/go-astitodo) — Parse TODOs in your GO code ☆`66`
- [sashamelentyev/usestdlibvars](https://github.com/sashamelentyev/usestdlibvars) — Linter for stdlib variables usage ☆`46`
- [borovikovd/gomsort](https://github.com/borovikovd/gomsort) — Go msort - linter that sorts methods ☆`26`
### Mock

- [vektra/mockery](https://github.com/vektra/mockery) — Mock code autogenerator for Go ☆`6,921`
- [DATA-DOG/go-sqlmock](https://github.com/DATA-DOG/go-sqlmock) — SQL mock driver for testing ☆`6,498`
- [brianvoe/gofakeit](https://github.com/brianvoe/gofakeit) — Random fake data generator written in go ☆`5,268`
- [uber-go/mock](https://github.com/uber-go/mock) — GoMock is a mocking framework for the Go programming language. ☆`3,214`
- [SpectoLabs/hoverfly](https://github.com/SpectoLabs/hoverfly) — API simulation and virtualization ☆`2,455`
- [matryer/moq](https://github.com/matryer/moq) — Interface mocking via go generate ☆`2,170`
- [jarcoal/httpmock](https://github.com/jarcoal/httpmock) — HTTP mocking for Go ☆`2,075`
- [maxbrunsfeld/counterfeiter](https://github.com/maxbrunsfeld/counterfeiter) — Generate type-safe test doubles ☆`1,109`
- [gojuno/minimock](https://github.com/gojuno/minimock) — Powerful mock generator ☆`744`
- [DATA-DOG/go-txdb](https://github.com/DATA-DOG/go-txdb) — Transaction-isolated SQL driver ☆`739`
- [pashagolub/pgxmock](https://github.com/pashagolub/pgxmock) — pgx mock driver for testing ☆`545`
- [xhd2015/xgo](https://github.com/xhd2015/xgo) — All-in-one Go testing library ☆`428`
- [seborama/govcr](https://github.com/seborama/govcr) — Record and replay HTTP interactions ☆`197`
- [elgohr/go-localstack](https://github.com/elgohr/go-localstack) — Go wrapper for LocalStack ☆`85`
### Performance

- [jaegertracing/jaeger](https://github.com/jaegertracing/jaeger) — Distributed tracing platform ☆`22,268`
- [pixie-io/pixie](https://github.com/pixie-io/pixie) — Kubernetes-native observability ☆`6,295`
- [arl/statsviz](https://github.com/arl/statsviz) — Visualize Go runtime metrics ☆`3,606`
- [nikolaydubina/go-instrument](https://github.com/nikolaydubina/go-instrument) — Add trace spans to Go functions ☆`287`
- [joetifa2003/mm-go](https://github.com/joetifa2003/mm-go) — Manual memory management for Go ☆`191`
### Selenium and browser control tools

- [chromedp/chromedp](https://github.com/chromedp/chromedp) — Chrome DevTools Protocol driver ☆`12,594`
- [go-rod/rod](https://github.com/go-rod/rod) — Chrome DevTools driver for scraping ☆`6,506`
- [sensepost/gowitness](https://github.com/sensepost/gowitness) — Web screenshot utility with Chrome ☆`4,097`
- [playwright-community/playwright-go](https://github.com/playwright-community/playwright-go) — Browser automation for Chromium, Firefox, WebKit ☆`3,084`
- [mafredri/cdp](https://github.com/mafredri/cdp) — Package cdp provides type-safe bindings for the Chrome DevTools Protocol (CDP), written in the Go programming language. ☆`770`
### Testing Frameworks

- [stretchr/testify](https://github.com/stretchr/testify) — A toolkit with common assertions and mocks that plays nicely with the standard library ☆`25,561`
- [keploy/keploy](https://github.com/keploy/keploy) — API, Integration, E2E Testing Agent for Developers that actually work. Generate tests, mocks/stubs for your APIs! ☆`13,648`
- [testcontainers/testcontainers-go](https://github.com/testcontainers/testcontainers-go) — Docker containers for integration tests ☆`4,559`
- [google/go-cmp](https://github.com/google/go-cmp) — Package for comparing Go values in tests ☆`4,568`
- [gavv/httpexpect](https://github.com/gavv/httpexpect) — End-to-end HTTP and REST API testing for Go. ☆`2,697`
- [cucumber/godog](https://github.com/cucumber/godog) — Cucumber for golang ☆`2,569`
- [orlangure/gnomock](https://github.com/orlangure/gnomock) — Test your code without writing mocks with ephemeral Docker containers Setup popular services with just a couple lines of code No bash, no yaml, only code ☆`1,473`
- [dnaeon/go-vcr](https://github.com/dnaeon/go-vcr) — Record and replay your HTTP interactions for fast, deterministic and accurate tests ☆`1,345`
- [go-testfixtures/testfixtures](https://github.com/go-testfixtures/testfixtures) — Rails-like test fixtures for Go ☆`1,207`
- [fergusstrange/embedded-postgres](https://github.com/fergusstrange/embedded-postgres) — Embedded PostgreSQL for testing ☆`1,098`
- [gotestyourself/gotest.tools](https://github.com/gotestyourself/gotest.tools) — Testing utilities for Go ☆`574`
- [maxatome/go-testdeep](https://github.com/maxatome/go-testdeep) — Extremely flexible golang deep comparison, extends the go testing package, tests HTTP APIs and provides tests suite ☆`456`
- [appleboy/gofight](https://github.com/appleboy/gofight) — Testing API Handler written in Golang. ☆`445`
- [viant/endly](https://github.com/viant/endly) — End to end functional test and automation framework ☆`267`
- [ysmood/got](https://github.com/ysmood/got) — An enjoyable golang test framework. ☆`269`
- [kinbiko/jsonassert](https://github.com/kinbiko/jsonassert) — A Go test assertion library for verifying that two representations of JSON are semantically equal ☆`140`
- [adamluzsi/testcase](https://github.com/adamluzsi/testcase) — testcase is an opinionated testing framework to support test driven design. ☆`127`
- [earthboundkid/be](https://github.com/earthboundkid/be) — The Go test helper for minimalists ☆`125`
- [corbym/gocrest](https://github.com/corbym/gocrest) — GoCrest - Hamcrest-like matchers for Go ☆`106`
- [hedhyw/gherkingen](https://github.com/hedhyw/gherkingen) — Behaviour Driven Development tests generator for Golang ☆`91`
- [madflojo/testcerts](https://github.com/madflojo/testcerts) — Dynamically generate self-signed certificates and certificate authorities for Go tests ☆`83`
- [go-restit/restit](https://github.com/go-restit/restit) — A Go library help testing your RESTful API application ☆`55`
- [rekby/fixenv](https://github.com/rekby/fixenv) —  ☆`33`
- [viant/dsunit](https://github.com/viant/dsunit) — Datastore Testibility ☆`45`
- [abecodes/dft](https://github.com/abecodes/dft) — Docker For Testing is a zero dependency wrapper around the `docker` command. ☆`19`
### Testing Utilities

- [dvyukov/go-fuzz](https://github.com/dvyukov/go-fuzz) — Randomized testing for Go ☆`4,841`
- [pingcap/failpoint](https://github.com/pingcap/failpoint) — Failpoint implementation for Go ☆`870`
### Validation

- [go-playground/validator](https://github.com/go-playground/validator) — Struct and field validation for Go ☆`19,498`
- [gookit/validate](https://github.com/gookit/validate) — Struct and data validation ☆`1,122`
- [Oudwins/zog](https://github.com/Oudwins/zog) — Zod-inspired schema validation ☆`1,059`
- [twharmon/govalid](https://github.com/twharmon/govalid) — Struct validation using tags ☆`110`
- [faceair/jio](https://github.com/faceair/jio) — JSON schema validator like Joi ☆`124`
- [osamingo/checkdigit](https://github.com/osamingo/checkdigit) — Check digit algorithms ☆`114`
- [marrow16/valix](https://github.com/marrow16/valix) — Request validation package ☆`31`
- [tiendc/go-validator](https://github.com/tiendc/go-validator) — Intuitive validation library ☆`32`
## Text & NLP

### Formatters

- [dustin/go-humanize](https://github.com/dustin/go-humanize) — Human-friendly unit formatting ☆`4,750`
- [neilotoole/sq](https://github.com/neilotoole/sq) — SQL data wrangler ☆`2,407`
- [ianlopshire/go-fixedwidth](https://github.com/ianlopshire/go-fixedwidth) — Fixed-width data encoding ☆`87`
- [bojanz/address](https://github.com/bojanz/address) — Address handling for Go ☆`81`
### Markup Languages

- [BurntSushi/toml](https://github.com/BurntSushi/toml) — TOML parser with reflection ☆`4,866`
- [yuin/goldmark](https://github.com/yuin/goldmark) — Markdown parser for Go ☆`4,470`
- [JohannesKaufmann/html-to-markdown](https://github.com/JohannesKaufmann/html-to-markdown) — Convert HTML to Markdown ☆`3,285`
- [pelletier/go-toml](https://github.com/pelletier/go-toml) — TOML library for Go ☆`1,890`
- [antchfx/htmlquery](https://github.com/antchfx/htmlquery) — XPath for HTML queries ☆`774`
- [clbanning/mxj](https://github.com/clbanning/mxj) — XML to/from map conversion ☆`632`
- [mmalcek/bafi](https://github.com/mmalcek/bafi) — Universal format converter ☆`110`
- [drewstinnett/gout](https://github.com/drewstinnett/gout) — Output Go objects in YAML, JSON ☆`18`
### Morphological Analyzers

- [nlpodyssey/spago](https://github.com/nlpodyssey/spago) — ML and NLP library for Go ☆`1,838`
- [ikawaha/kagome](https://github.com/ikawaha/kagome) — Japanese morphological analyzer ☆`927`
- [afjoseph/RAKE.Go](https://github.com/afjoseph/RAKE.Go) — Rapid Keyword Extraction in Go ☆`122`
- [jonreiter/govader](https://github.com/jonreiter/govader) — VADER sentiment analysis ☆`52`
### Parsers/Encoders/Decoders

- [mvdan/sh](https://github.com/mvdan/sh) — Shell parser and formatter ☆`8,334`
- [mmcdole/gofeed](https://github.com/mmcdole/gofeed) — Parse RSS, Atom, JSON feeds ☆`2,785`
- [google/go-querystring](https://github.com/google/go-querystring) — Encode structs to URL query strings ☆`2,123`
- [olebedev/when](https://github.com/olebedev/when) — Natural language date parser ☆`1,453`
- [adrianmo/go-nmea](https://github.com/adrianmo/go-nmea) — NMEA sentence parser ☆`253`
- [yassinebenaid/godump](https://github.com/yassinebenaid/godump) — Dump any Go variable ☆`222`
- [editorconfig/editorconfig-core-go](https://github.com/editorconfig/editorconfig-core-go) — EditorConfig core in Go ☆`150`
- [bzick/tokenizer](https://github.com/bzick/tokenizer) — Tokenizer/lexer for Go ☆`138`
- [emersion/go-vcard](https://github.com/emersion/go-vcard) — vCard parser and formatter ☆`123`
- [polera/gonameparts](https://github.com/polera/gonameparts) — Takes a full name and splits it into individual name parts ☆`43`
### Scrapers

- [gocolly/colly](https://github.com/gocolly/colly) — Web scraping framework for Go ☆`24,945`
- [PuerkitoBio/goquery](https://github.com/PuerkitoBio/goquery) — jQuery-like HTML manipulation ☆`14,851`
- [mvdan/xurls](https://github.com/mvdan/xurls) — Extract URLs from text ☆`1,239`
- [s0rg/crawley](https://github.com/s0rg/crawley) — The unix-way web crawler ☆`321`
- [zoomio/tagify](https://github.com/zoomio/tagify) — Extract tags from HTML/Markdown/text ☆`39`
### Tokenizers

- [go-ego/gse](https://github.com/go-ego/gse) — Multilingual text segmentation ☆`2,763`
- [pebbe/textcat](https://github.com/pebbe/textcat) — N-gram text categorization ☆`73`
### Translation

- [nicksnyder/go-i18n](https://github.com/nicksnyder/go-i18n) — Translate Go programs ☆`3,429`
- [leonelquinteros/gotext](https://github.com/leonelquinteros/gotext) — GNU gettext for Go ☆`487`
- [vorlif/spreak](https://github.com/vorlif/spreak) — Gettext-based translation library ☆`89`
- [invopop/ctxi18n](https://github.com/invopop/ctxi18n) — Context-based i18n for Go ☆`89`
- [mehanizm/iuliia-go](https://github.com/mehanizm/iuliia-go) — Cyrillic to Latin transliteration ☆`55`
- [youthlin/t](https://github.com/youthlin/t) — Translation util using gettext ☆`20`
### Utility/Miscellaneous

- [microcosm-cc/bluemonday](https://github.com/microcosm-cc/bluemonday) — Fast HTML sanitizer for Go ☆`3,585`
- [pemistahl/lingua-go](https://github.com/pemistahl/lingua-go) — Natural language detection ☆`1,307`
- [gosimple/slug](https://github.com/gosimple/slug) — URL-friendly slugify ☆`1,303`
- [arunsupe/semantic-grep](https://github.com/arunsupe/semantic-grep) — Grep for similar words ☆`1,193`
- [mattn/go-runewidth](https://github.com/mattn/go-runewidth) — Rune width for terminals ☆`672`
- [hedhyw/rex](https://github.com/hedhyw/rex) — Flexible regex constructor ☆`210`
- [IGLOU-EU/go-wildcard](https://github.com/IGLOU-EU/go-wildcard) — Fast wildcard matching ☆`99`
- [JoshuaDoes/gofuckyourself](https://github.com/JoshuaDoes/gofuckyourself) — Swear filter for Go ☆`68`
- [alexsergivan/transliterator](https://github.com/alexsergivan/transliterator) — Text transliterator ☆`46`
- [Dynom/TySug](https://github.com/Dynom/TySug) — Typo suggestions with keyboard layout ☆`19`
## Utilities

### Build & Release

- [goreleaser/goreleaser](https://github.com/goreleaser/goreleaser) — Release engineering simplified ☆`15,400`
- [create-go-app/cli](https://github.com/create-go-app/cli) — Create production-ready Go projects ☆`2,733`
- [miniscruff/changie](https://github.com/miniscruff/changie) — Automated changelog tool ☆`844`
- [jaschaephraim/lrserver](https://github.com/jaschaephraim/lrserver) — LiveReload server for Go [golang] ☆`129`
- [karl-cardenas-coding/go-lambda-cleanup](https://github.com/karl-cardenas-coding/go-lambda-cleanup) — Remove old AWS Lambda versions ☆`96`
### CLI Tools

- [junegunn/fzf](https://github.com/junegunn/fzf) — Command-line fuzzy finder ☆`76,227`
- [wagoodman/dive](https://github.com/wagoodman/dive) — Explore Docker image layers ☆`52,966`
- [xo/usql](https://github.com/xo/usql) — Universal SQL CLI ☆`9,718`
- [minio/mc](https://github.com/minio/mc) — Unix utilities for object stores ☆`3,318`
- [joshmedeski/sesh](https://github.com/joshmedeski/sesh) — Terminal session manager ☆`1,504`
- [itchyny/bed](https://github.com/itchyny/bed) — Binary editor in Go ☆`1,343`
- [owenthereal/upterm](https://github.com/owenthereal/upterm) — Instant terminal sharing ☆`1,074`
- [Unrud/remote-touchpad](https://github.com/Unrud/remote-touchpad) — Control mouse/keyboard remotely ☆`638`
- [alajmo/mani](https://github.com/alajmo/mani) — CLI for managing repositories ☆`636`
- [chenquan/diskusage](https://github.com/chenquan/diskusage) — Fast disk usage analyzer ☆`297`
- [reugn/wifiqr](https://github.com/reugn/wifiqr) — Generate Wi-Fi QR codes ☆`280`
- [hedhyw/json-log-viewer](https://github.com/hedhyw/json-log-viewer) — Interactive JSON log viewer ☆`197`
- [knbr13/gitcs](https://github.com/knbr13/gitcs) — Git contributions graph generator ☆`127`
- [antham/yogo](https://github.com/antham/yogo) — Check yopmail from CLI ☆`46`
### Data Conversion

- [samber/lo](https://github.com/samber/lo) — Lodash-style utilities for Go ☆`20,791`
- [duke-git/lancet](https://github.com/duke-git/lancet) — Comprehensive util library ☆`5,241`
- [darccio/mergo](https://github.com/darccio/mergo) — Merge Go structs and maps ☆`3,078`
- [goforj/godump](https://github.com/goforj/godump) — Pretty-printer for Go structs ☆`1,476`
- [gookit/filter](https://github.com/gookit/filter) — Data filtering and conversion ☆`150`
- [tiendc/gofn](https://github.com/tiendc/gofn) — High-performance generic functions ☆`52`
- [xorcare/pointer](https://github.com/xorcare/pointer) — Create optional field pointers ☆`48`
- [shockerli/cvt](https://github.com/shockerli/cvt) — Safe type conversion ☆`53`
### Database Extensions

- [jmoiron/sqlx](https://github.com/jmoiron/sqlx) — Extensions for database/sql ☆`17,431`
- [georgysavva/scany](https://github.com/georgysavva/scany) — Scan database rows to structs ☆`1,491`
- [blockloop/scan](https://github.com/blockloop/scan) — Scan SQL rows to structs ☆`606`
- [wroge/scan](https://github.com/wroge/scan) — Generic SQL row scanner ☆`68`
### Date and Time

- [dromara/carbon](https://github.com/dromara/carbon) — Developer-friendly time package ☆`5,191`
- [araddon/dateparse](https://github.com/araddon/dateparse) — Parse dates without format ☆`2,130`
- [yaa110/go-persian-calendar](https://github.com/yaa110/go-persian-calendar) — Persian calendar for Go ☆`237`
- [bykof/gostradamus](https://github.com/bykof/gostradamus) — Better DateTimes for Go ☆`210`
- [nathan-osman/go-sunrise](https://github.com/nathan-osman/go-sunrise) — Calculate sunrise and sunset times ☆`171`
- [rickb777/date](https://github.com/rickb777/date) — Date handling package ☆`140`
- [relvacode/iso8601](https://github.com/relvacode/iso8601) — Fast ISO8601 date parser ☆`156`
### Dependency Injection

- [uber-go/fx](https://github.com/uber-go/fx) — DI-based application framework ☆`7,154`
- [uber-go/dig](https://github.com/uber-go/dig) — Reflection-based DI toolkit ☆`4,409`
- [goioc/di](https://github.com/goioc/di) — Simple DI for Go ☆`375`
- [go-kod/kod](https://github.com/go-kod/kod) — DI with aspect-oriented support ☆`197`
- [i-love-flamingo/dingo](https://github.com/i-love-flamingo/dingo) — DI framework for Go ☆`186`
- [NVIDIA/gontainer](https://github.com/NVIDIA/gontainer) — Simple DI container ☆`62`
- [junioryono/godi](https://github.com/junioryono/godi) — DI with service lifetimes ☆`62`
- [matzefriedrich/parsley](https://github.com/matzefriedrich/parsley) — Reflection-based DI package ☆`31`
- [muir/nject](https://github.com/muir/nject) — Type-safe DI for Go ☆`30`
- [logrange/linker](https://github.com/logrange/linker) — DI and IoC package ☆`35`
- [firasdarwish/ore](https://github.com/firasdarwish/ore) — Advanced DI solution ☆`24`
- [componego/componego](https://github.com/componego/componego) — Component-oriented framework ☆`28`
- [gontainer/gontainer](https://github.com/gontainer/gontainer) — YAML-based DI container ☆`16`
### Error Handling

- [hashicorp/go-multierror](https://github.com/hashicorp/go-multierror) — Represent multiple errors as one ☆`2,537`
- [cockroachdb/errors](https://github.com/cockroachdb/errors) — Error library with portability ☆`2,331`
- [rotisserie/eris](https://github.com/rotisserie/eris) — Errors with readable stack traces ☆`1,746`
- [joomcode/errorx](https://github.com/joomcode/errorx) — Comprehensive error handling ☆`1,268`
- [ztrue/tracerr](https://github.com/ztrue/tracerr) — Errors with stack trace ☆`1,101`
- [samber/oops](https://github.com/samber/oops) — Structured error handling ☆`823`
- [Southclaws/fault](https://github.com/Southclaws/fault) — Composable error wrapping ☆`302`
### File Handling

- [pdfcpu/pdfcpu](https://github.com/pdfcpu/pdfcpu) — PDF processor in Go ☆`8,320`
- [spf13/afero](https://github.com/spf13/afero) — Filesystem abstraction for Go ☆`6,500`
- [dundee/gdu](https://github.com/dundee/gdu) — Fast disk usage analyzer ☆`5,113`
- [SebastiaanKlippert/go-wkhtmltopdf](https://github.com/SebastiaanKlippert/go-wkhtmltopdf) — HTML to PDF wrapper ☆`1,170`
- [otiai10/copy](https://github.com/otiai10/copy) — Copy directories recursively ☆`769`
- [ulikunitz/xz](https://github.com/ulikunitz/xz) — Pure golang package for reading and writing xz-compressed files ☆`544`
- [no-src/gofs](https://github.com/no-src/gofs) — Cross-platform file sync ☆`523`
- [viant/afs](https://github.com/viant/afs) — Abstract file storage ☆`367`
- [C2FO/vfs](https://github.com/C2FO/vfs) — Virtual file system for Go ☆`356`
- [mholt/archives](https://github.com/mholt/archives) — Cross-platform library to create & extract archives, compress & decompress files, and walk virtual file systems across various formats ☆`355`
- [barasher/go-exiftool](https://github.com/barasher/go-exiftool) — Exiftool wrapper for metadata ☆`289`
- [gen2brain/go-unarr](https://github.com/gen2brain/go-unarr) — Go bindings for unarr (decompression library for RAR, TAR, ZIP and 7z archives) ☆`299`
- [kdomanski/iso9660](https://github.com/kdomanski/iso9660) — ISO9660 image library ☆`282`
- [artonge/go-csv-tag](https://github.com/artonge/go-csv-tag) — CSV reading with tags ☆`128`
- [charlievieth/fastwalk](https://github.com/charlievieth/fastwalk) — Fast directory traversal ☆`112`
- [parsyl/parquet](https://github.com/parsyl/parquet) — Parquet file library ☆`127`
- [adelowo/gulter](https://github.com/adelowo/gulter) — Multipart form handling ☆`66`
### Forms

- [justinas/nosurf](https://github.com/justinas/nosurf) — CSRF protection middleware ☆`1,714`
- [gorilla/csrf](https://github.com/gorilla/csrf) — CSRF prevention middleware ☆`1,166`
- [go-playground/form](https://github.com/go-playground/form) — URL values to structs ☆`895`
- [ggicci/httpin](https://github.com/ggicci/httpin) — HTTP request to struct binding ☆`380`
- [sonh/qs](https://github.com/sonh/qs) — Encode structs to query params ☆`79`
- [cinar/checker](https://github.com/cinar/checker) — Input validation with struct tags ☆`47`
### Functional

- [samber/mo](https://github.com/samber/mo) — Monads and FP for Go ☆`3,251`
- [BooleanCat/go-functional](https://github.com/BooleanCat/go-functional) — Iterator library for Go ☆`524`
- [seborama/fuego](https://github.com/seborama/fuego) — Functional programming in Go ☆`146`
- [rjNemo/underscore](https://github.com/rjNemo/underscore) — Functional helpers for Go ☆`118`
### General

- [gabriel-vasile/mimetype](https://github.com/gabriel-vasile/mimetype) — MIME type detection by magic numbers ☆`1,916`
- [qmuntal/stateless](https://github.com/qmuntal/stateless) — Go library for creating finite state machines ☆`1,147`
- [jonboulle/clockwork](https://github.com/jonboulle/clockwork) — a fake clock for golang ☆`722`
- [Boeing/config-file-validator](https://github.com/Boeing/config-file-validator) — Cross Platform tool to validate configuration files ☆`484`
- [ungerik/go-dry](https://github.com/ungerik/go-dry) — DRY (don't repeat yourself) package for Go ☆`488`
- [biter777/countries](https://github.com/biter777/countries) — Countries - ISO-639, ISO-3166 countries codes with subdivisions and names, ISO-4217 currency designators, ITU-T E.164 IDD phone codes, countries capitals, UN M.49 codes, IANA ccTLD countries domains, FIPS, IOC/NOC and FIFA codes, VERY VERY FAST, compatible with Databases/JSON/BSON/GOB/XML/CSV, Emoji countries flags and currencies, Unicode CLDR. ☆`493`
- [subosito/gotenv](https://github.com/subosito/gotenv) — Load environment variables from `.env` or `io.Reader` in Go. ☆`306`
- [ikeikeikeike/go-sitemap-generator](https://github.com/ikeikeikeike/go-sitemap-generator) — Generate XML sitemaps ☆`228`
- [viant/toolbox](https://github.com/viant/toolbox) — Toolbox - go utility library ☆`227`
- [maja42/goval](https://github.com/maja42/goval) — Expression evaluation in golang ☆`173`
- [commander-cli/cmd](https://github.com/commander-cli/cmd) — A simple package to execute shell commands on linux, windows and osx ☆`160`
- [jfcg/sorty](https://github.com/jfcg/sorty) — Fast Concurrent / Parallel Sorting in Go ☆`142`
- [tiendc/go-deepcopy](https://github.com/tiendc/go-deepcopy) — Fast deep-copy library for Go ☆`121`
- [syntaqx/cookie](https://github.com/syntaqx/cookie) — Cookies, but with structs, for happiness. ☆`110`
- [pioz/countries](https://github.com/pioz/countries) — All you need when you are working with countries in Go. ☆`93`
- [arthurkushman/pgo](https://github.com/arthurkushman/pgo) — Go library for PHP community with convenient functions ☆`88`
- [wzshiming/gotype](https://github.com/wzshiming/gotype) — Golang source code parsing, usage like reflect package ☆`64`
- [rkoesters/xdg](https://github.com/rkoesters/xdg) — FreeDesktop.org (xdg) Specs implemented in Go ☆`48`
- [icza/backscanner](https://github.com/icza/backscanner) — A scanner similar to bufio.Scanner, but it reads and returns lines in reverse order, starting at a given position and going backward. ☆`69`
- [ik5/gostrutils](https://github.com/ik5/gostrutils) — Collections of string utils I have created over the years ☆`48`
- [kazhuravlev/just](https://github.com/kazhuravlev/just) — Collection of useful functions. Complete simple tasks faster! ☆`37`
- [osamingo/gosh](https://github.com/osamingo/gosh) — Provide Go Statistics Handler, Struct, Measure Method ☆`35`
- [floatdrop/debounce](https://github.com/floatdrop/debounce) — A zero-allocation debouncer ☆`34`
- [lrita/numa](https://github.com/lrita/numa) — NUMA is a utility library, which is written in go. It help us to write some NUMA-AWARED code. ☆`37`
- [skovtunenko/graterm](https://github.com/skovtunenko/graterm) — Provides primitives to perform ordered GRAceful TERmination for Golang applications ☆`30`
- [mikekonan/go-types](https://github.com/mikekonan/go-types) — Library providing opanapi3 and Go types for store/validation and transfer of ISO-4217, ISO-3166, and other types. ☆`22`
- [nikolaydubina/watchhttp](https://github.com/nikolaydubina/watchhttp) — Expose command output via HTTP ☆`34`
### Logging

- [sirupsen/logrus](https://github.com/sirupsen/logrus) — Structured, pluggable logging for Go. ☆`25,636`
- [uber-go/zap](https://github.com/uber-go/zap) — Fast structured logging ☆`24,065`
- [rs/zerolog](https://github.com/rs/zerolog) — Zero allocation JSON logger ☆`12,063`
- [davecgh/go-spew](https://github.com/davecgh/go-spew) — Deep pretty printer for debugging ☆`6,363`
- [golang/glog](https://github.com/golang/glog) — Leveled execution logs ☆`3,620`
- [k0kubun/pp](https://github.com/k0kubun/pp) — Colored pretty printer for Go ☆`2,021`
- [lmittmann/tint](https://github.com/lmittmann/tint) — Colorized slog handler ☆`1,189`
- [getsentry/sentry-go](https://github.com/getsentry/sentry-go) — Official Sentry SDK for Go ☆`1,028`
- [Lifailon/lazyjournal](https://github.com/Lifailon/lazyjournal) — TUI for journald, Docker, K8s logs ☆`1,028`
- [phuslu/log](https://github.com/phuslu/log) — Fastest structured logging ☆`827`
- [samber/slog-multi](https://github.com/samber/slog-multi) — Workflow design for slog handlers ☆`592`
- [gookit/slog](https://github.com/gookit/slog) — Configurable logging library ☆`523`
- [henvic/httpretty](https://github.com/henvic/httpretty) — Pretty-print HTTP requests ☆`413`
- [simukti/sqldb-logger](https://github.com/simukti/sqldb-logger) — SQL database logger ☆`383`
- [hashicorp/logutils](https://github.com/hashicorp/logutils) — Logging utilities for Go ☆`371`
- [samber/slog-formatter](https://github.com/samber/slog-formatter) — Slog attribute formatting ☆`204`
- [rs/xlog](https://github.com/rs/xlog) — Context-aware HTTP logger ☆`140`
- [DeRuina/timberjack](https://github.com/DeRuina/timberjack) — Log rolling library ☆`107`
- [yuseferi/zax](https://github.com/yuseferi/zax) — Zap logger with context ☆`31`
- [clok/kemba](https://github.com/clok/kemba) — Tiny debug logging tool ☆`17`
### Networking Utils

- [cristianoliveira/ergo](https://github.com/cristianoliveira/ergo) — Manage apps on different ports ☆`643`
- [htcat/htcat](https://github.com/htcat/htcat) — Parallel HTTP download ☆`557`
- [ferama/rospo](https://github.com/ferama/rospo) — Persistent SSH tunnels ☆`350`
### Project Layout

- [golang-standards/project-layout](https://github.com/golang-standards/project-layout) — Standard Go project layout ☆`54,820`
- [Melkeydev/go-blueprint](https://github.com/Melkeydev/go-blueprint) — Spin up Go projects with popular frameworks ☆`8,515`
- [ardanlabs/service](https://github.com/ardanlabs/service) — K8s service starter kit ☆`3,919`
- [Shpota/goxygen](https://github.com/Shpota/goxygen) — Generate a modern Web project with Go and Angular, React, or Vue in seconds ☆`3,605`
- [mikestefanello/pagoda](https://github.com/mikestefanello/pagoda) — Full-stack web development starter kit ☆`2,882`
- [go-nunu/nunu](https://github.com/go-nunu/nunu) — CLI for building Go apps ☆`2,520`
- [sagikazarmark/modern-go-application](https://github.com/sagikazarmark/modern-go-application) — Modern Go app example ☆`1,939`
- [naughtygopher/goapp](https://github.com/naughtygopher/goapp) — Opinionated web app structure ☆`1,040`
- [lacion/cookiecutter-golang](https://github.com/lacion/cookiecutter-golang) — Go project template ☆`733`
- [allaboutapps/go-starter](https://github.com/allaboutapps/go-starter) — Production-ready RESTful API template ☆`587`
- [golang-templates/seed](https://github.com/golang-templates/seed) — Go app GitHub template ☆`549`
- [raeperd/kickstart.go](https://github.com/raeperd/kickstart.go) — Minimal HTTP server template ☆`101`
- [wangyoucao577/go-project-layout](https://github.com/wangyoucao577/go-project-layout) — Go project structure guide ☆`26`
### Resilience & Retry

- [avast/retry-go](https://github.com/avast/retry-go) — Simple retry mechanism ☆`2,861`
- [eapache/go-resiliency](https://github.com/eapache/go-resiliency) — Resiliency patterns for golang ☆`2,340`
- [failsafe-go/failsafe-go](https://github.com/failsafe-go/failsafe-go) — Fault tolerance patterns ☆`2,040`
- [rubyist/circuitbreaker](https://github.com/rubyist/circuitbreaker) — Circuit breakers in Go ☆`1,164`
- [cep21/circuit](https://github.com/cep21/circuit) — Hystrix-like circuit breaker ☆`794`
- [mennanov/limiters](https://github.com/mennanov/limiters) — Distributed rate limiters ☆`610`
- [kamilsk/retry](https://github.com/kamilsk/retry) — Advanced retry mechanism ☆`345`
- [webriots/rate](https://github.com/webriots/rate) — High-performance rate limiter ☆`163`
- [reugn/equalizer](https://github.com/reugn/equalizer) — Performant rate limiters ☆`91`
### Strings

- [huandu/xstrings](https://github.com/huandu/xstrings) — String functions from other langs ☆`1,417`
- [abhimanyu003/sttr](https://github.com/abhimanyu003/sttr) — CLI string operations ☆`1,235`
- [gobeam/stringy](https://github.com/gobeam/stringy) — Convert string to camel case, snake case, kebab case / slugify, custom delimiter, pad string, tease string and many other functionalities with help of by Stringy package. ☆`251`
- [ozgio/strutil](https://github.com/ozgio/strutil) — String utilities for Go ☆`207`
### System & Process

- [cilium/ebpf](https://github.com/cilium/ebpf) — eBPF library for Go ☆`7,387`
- [maruel/panicparse](https://github.com/maruel/panicparse) — Crash your app in style ☆`3,715`
- [immortal/immortal](https://github.com/immortal/immortal) — Cross-platform supervisor ☆`830`
- [derekparker/delve](https://github.com/derekparker/delve) — Delve is a debugger for the Go programming language. ☆`663`
- [gotranspile/cxgo](https://github.com/gotranspile/cxgo) — Transpile C to Go ☆`377`
### UUID

- [google/uuid](https://github.com/google/uuid) — UUID generation and parsing ☆`5,937`
- [oklog/ulid](https://github.com/oklog/ulid) — ULID implementation ☆`4,946`
- [gofrs/uuid](https://github.com/gofrs/uuid) — UUID library for Go ☆`1,753`
- [edwingeng/wuid](https://github.com/edwingeng/wuid) — An extremely fast globally unique number generator. ☆`545`
- [osamingo/indigo](https://github.com/osamingo/indigo) — A distributed unique ID generator of using Sonyflake and encoded by Base58 ☆`112`
- [sdrapkin/guid](https://github.com/sdrapkin/guid) — Fast cryptographically safe Guid generator for Go ☆`73`
- [twharmon/gouid](https://github.com/twharmon/gouid) — Fast, dependable universally unique ids ☆`26`
## Version Control & Packages

### Package Management

- [anchore/syft](https://github.com/anchore/syft) — CLI tool and library for generating a Software Bill of Materials from container images and filesystems ☆`8,155`
- [nao1215/gup](https://github.com/nao1215/gup) — gup - Update binaries installed by "go install" with goroutines. ☆`516`
- [chaindead/modup](https://github.com/chaindead/modup) — Terminal UI for Go dependency updates with outdated module detection and selective upgrading. ☆`61`
### Version Control

- [go-git/go-git](https://github.com/go-git/go-git) — Pure Go Git implementation ☆`7,085`
- [antham/chyle](https://github.com/antham/chyle) — Changelog generator : use a git repository and various data sources and publish the result on external services ☆`159`
- [gabyx/Githooks](https://github.com/gabyx/Githooks) — Githooks: per-repo and shared Git hooks with version control and auto update. [✩Star] if you're using it! ☆`115`
- [antham/gommit](https://github.com/antham/gommit) — Enforce git message commit consistency ☆`115`
- [jfrog/froggit-go](https://github.com/jfrog/froggit-go) — Froggit-Go is a universal Go library, allowing to perform actions on VCS providers. ☆`49`
- [kazhuravlev/git-tools](https://github.com/kazhuravlev/git-tools) — Useful set of tools which helps to manage git tags ☆`33`
## Web Development

### Middlewares

- [urfave/negroni](https://github.com/urfave/negroni) — Idiomatic HTTP Middleware for Golang ☆`7,540`
- [tdewolff/minify](https://github.com/tdewolff/minify) — Go minifiers for web formats ☆`4,036`
- [justinas/alice](https://github.com/justinas/alice) — Painless middleware chaining for Go ☆`3,342`
- [rs/cors](https://github.com/rs/cors) — Go net/http configurable handler to handle CORS requests ☆`2,845`
- [didip/tollbooth](https://github.com/didip/tollbooth) — Simple middleware to rate-limit HTTP requests. ☆`2,846`
- [unrolled/render](https://github.com/unrolled/render) — Go package for easily rendering JSON, XML, binary data, and HTML templates responses. ☆`1,990`
- [lingrino/go-fault](https://github.com/lingrino/go-fault) — go fault injection library ☆`510`
- [jub0bs/cors](https://github.com/jub0bs/cors) — perhaps the best CORS middleware library for Go ☆`163`
- [rookie-ninja/rk-gin](https://github.com/rookie-ninja/rk-gin) — Start gin microservice from YAML, plugin of rk-boot ☆`51`
- [faabiosr/echo-middleware](https://github.com/faabiosr/echo-middleware) — Middlewares for Echo framework ☆`16`
### Routers

- [gorilla/mux](https://github.com/gorilla/mux) — Package gorilla/mux is a powerful HTTP router and URL matcher for building Go web servers with ☆`21,750`
- [go-chi/chi](https://github.com/go-chi/chi) — lightweight, idiomatic and composable router for building Go HTTP services ☆`21,209`
- [gernest/alien](https://github.com/gernest/alien) — A lightweight and fast http router from outer space ☆`134`
- [ngamux/ngamux](https://github.com/ngamux/ngamux) — Simple HTTP router for Go ☆`70`
- [bmf-san/goblin](https://github.com/bmf-san/goblin) — A golang http router based on trie tree. ☆`81`
- [muir/nchi](https://github.com/muir/nchi) — golang http router with elegance, speed, and flexibility ☆`18`
### Template Engines

- [a-h/templ](https://github.com/a-h/templ) — A language for writing HTML user interfaces in Go. ☆`9,919`
- [valyala/quicktemplate](https://github.com/valyala/quicktemplate) — Fast template engine for Go ☆`3,289`
- [johnfercher/maroto](https://github.com/johnfercher/maroto) — A maroto way to create PDFs. Maroto is inspired in Bootstrap and uses gofpdf. Fast and simple. ☆`2,602`
- [CloudyKit/jet](https://github.com/CloudyKit/jet) — Jet template engine ☆`1,373`
- [osteele/liquid](https://github.com/osteele/liquid) — A Liquid template engine in Go ☆`332`
- [go-sprout/sprout](https://github.com/go-sprout/sprout) — From sprig to sprout - Useful template functions for Go templates with steroids ☆`197`
- [robfig/soy](https://github.com/robfig/soy) — Go implementation for Soy templates (Google Closure templates) ☆`177`
- [goradd/got](https://github.com/goradd/got) — GoT is a template engine that turns templates into Go code to compile into your app. ☆`38`
### Web Frameworks

- [gin-gonic/gin](https://github.com/gin-gonic/gin) — Gin is a high-performance HTTP web framework written in Go. It provides a Martini-like API but with significantly better performance—up to 40 times faster—thanks to httprouter. Gin is designed for building REST APIs, web applications, and microservices. ☆`87,472`
- [gofiber/fiber](https://github.com/gofiber/fiber) — Express inspired web framework written in Go ☆`38,815`
- [beego/beego](https://github.com/beego/beego) — beego is an open-source, high-performance web framework for the Go programming language. ☆`32,382`
- [labstack/echo](https://github.com/labstack/echo) — High performance, minimalist Go web framework ☆`31,950`
- [gofr-dev/gofr](https://github.com/gofr-dev/gofr) — An opinionated GoLang framework for accelerated microservice development. Built in support for databases and observability. ☆`15,433`
- [gogf/gf](https://github.com/gogf/gf) — A powerful framework for faster, easier, and more efficient project development. ☆`12,962`
- [cloudwego/hertz](https://github.com/cloudwego/hertz) — Go HTTP framework with high-performance and strong-extensibility for building micro-services. ☆`6,978`
- [goadesign/goa](https://github.com/goadesign/goa) — Design-first Go framework that generates API code, documentation, and clients. Define once in an elegant DSL, deploy as HTTP and gRPC services with zero drift between code and docs. ☆`6,022`
- [apache/dubbo-go](https://github.com/apache/dubbo-go) — Go Implementation For Apache Dubbo . ☆`4,866`
- [goravel/goravel](https://github.com/goravel/goravel) — The full-featured Golang Development Framework skeleton ☆`4,346`
- [danielgtaylor/huma](https://github.com/danielgtaylor/huma) — Huma REST/HTTP API Framework for Golang with OpenAPI 3.1 ☆`3,682`
- [go-goyave/goyave](https://github.com/go-goyave/goyave) — The enterprise REST API framework ☆`1,757`
- [go-fuego/fuego](https://github.com/go-fuego/fuego) — Golang Fuego - Web framework generating OpenAPI 3 spec from source code - Pluggable to existing Gin & Echo APIs ☆`1,620`
- [savsgio/atreugo](https://github.com/savsgio/atreugo) — High performance and extensible micro web framework. Zero memory allocations in hot paths. ☆`1,298`
- [templui/templui](https://github.com/templui/templui) — A growing collection of beautifully designed UI components for Go and templ. Install via CLI. Customize everything. Own your code. ☆`1,166`
- [ankorstore/yokai](https://github.com/ankorstore/yokai) — Simple, modular, and observable Go framework for backend applications. ☆`805`
- [indeedeng/iwf](https://github.com/indeedeng/iwf) — iWF is a Workflow-As-Code microservice orchestration platform offering an orchestration coding framework and service for building resilient, fault-tolerant, scalable long-running processes ☆`627`
- [i-love-flamingo/flamingo-commerce](https://github.com/i-love-flamingo/flamingo-commerce) — Flexible Go web framework ☆`585`
- [i-love-flamingo/flamingo](https://github.com/i-love-flamingo/flamingo) — Flexible Go web framework ☆`552`
- [rookie-ninja/rk-boot](https://github.com/rookie-ninja/rk-boot) — Build microservice with rk-boot and let the team take over clean and tidy code. ☆`575`
- [fastschema/fastschema](https://github.com/fastschema/fastschema) — All-in-One Backend as a Service with Headless CMS Power ☆`525`
- [uadmin/uadmin](https://github.com/uadmin/uadmin) — The web framework for Golang ☆`354`
- [xxjwxc/ginrpc](https://github.com/xxjwxc/ginrpc) — gin auto binding, grpc and annotated route ☆`300`
- [hidevopsio/hiboot](https://github.com/hidevopsio/hiboot) — hiboot is a high performance web and cli application framework with dependency injection support ☆`182`
- [beatlabs/patron](https://github.com/beatlabs/patron) — Microservice framework following best cloud practices with a focus on productivity. ☆`126`
- [gone-io/gone](https://github.com/gone-io/gone) — Gone - A Lightweight Dependency Injection Framework for Go | Tag-based Auto Injection | Supports Config Center/Lifecycle Management | Provides Rich Ecosystem Components and Scaffolding Tool ☆`132`
- [claygod/microservice](https://github.com/claygod/microservice) — This library provides a simple microservice framework based on clean architecture principles with a working example implemented. ☆`122`
- [gookit/rux](https://github.com/gookit/rux) — Rux is an simple and fast web framework. Support route group, param route binding, middleware, compatible http.Handler interface ☆`98`
- [yaitoo/xun](https://github.com/yaitoo/xun) — Xun is a web framework built on Go's built-in html/template and net/http package’s router (1.22). ☆`91`
- [go-spring/spring-core](https://github.com/go-spring/spring-core) — [released] Go-Spring is a high-performance Go framework inspired by Spring Boot, offering DI, auto-configuration, and lifecycle management while maintaining Go's simplicity and efficiency. ☆`75`
- [napsy/go-css](https://github.com/napsy/go-css) — A very simple CSS parser, written in Go ☆`87`
- [abemedia/go-don](https://github.com/abemedia/go-don) — API framework written in Golang. ☆`57`
- [JiveGroup/gFly](https://github.com/JiveGroup/gFly) — Laravel inspired web framework written in Go ☆`49`
- [SaiNageswarS/go-api-boot](https://github.com/SaiNageswarS/go-api-boot) — gRPC + HTTP/2 production framework ☆`35`
- [clubpay/ronykit](https://github.com/clubpay/ronykit) — API Framework supporting REST and RPC. ☆`34`
- [jvcoutinho/lit](https://github.com/jvcoutinho/lit) — A simple, fast and expressive HTTP framework for Go. ☆`30`
### WebAssembly

- [tinygo-org/tinygo](https://github.com/tinygo-org/tinygo) — Go compiler for small places. Microcontrollers, WebAssembly (WASM/WASI), and command-line tools. Based on LLVM. ☆`16,988`
- [agnivade/wasmbrowsertest](https://github.com/agnivade/wasmbrowsertest) — Run WASM tests inside your browser ☆`206`
- [extism/go-sdk](https://github.com/extism/go-sdk) — Extism Go SDK - easily run WebAssembly modules in your Go applications ☆`161`
## Workflow & Scheduling

### Job Scheduler

- [go-co-op/gocron](https://github.com/go-co-op/gocron) — Easy and fluent Go cron scheduling ☆`6,816`
- [hatchet-dev/hatchet](https://github.com/hatchet-dev/hatchet) — Run Background Tasks at Scale ☆`6,375`
- [reugn/go-quartz](https://github.com/reugn/go-quartz) — Minimalist and zero-dependency scheduling library for Go ☆`1,989`
- [adhocore/gronx](https://github.com/adhocore/gronx) — Lightweight, fast and dependency-free Cron expression parser (due checker, next/prev due date finder), task runner, job scheduler and/or daemon for Golang (tested on v1.13+) and standalone usage. If you are bold, use it to replace crontab entirely. ☆`482`
- [fieldryand/goflow](https://github.com/fieldryand/goflow) — Simple but powerful DAG scheduler and dashboard ☆`468`
- [madflojo/tasks](https://github.com/madflojo/tasks) — Package tasks is an easy to use in-process scheduler for recurring tasks in Go ☆`321`
- [bart6114/cheek](https://github.com/bart6114/cheek) — cheek: a pico-sized declarative job scheduler ☆`197`
- [onatm/clockwerk](https://github.com/onatm/clockwerk) — Job Scheduling Library ☆`182`
- [deepaksinghvi/cdule](https://github.com/deepaksinghvi/cdule) — cdule (pronounce as Schedule) Golang based scheduler library with database support. ☆`59`
- [pardnchiu/go-scheduler](https://github.com/pardnchiu/go-scheduler) — Scheduler with standard cron and task dependencies ☆`31`
- [romshark/sched](https://github.com/romshark/sched) — A job scheduler for Go with the ability to fast-forward time. ☆`28`
### Workflow Frameworks

- [redpanda-data/connect](https://github.com/redpanda-data/connect) — Fancy stream processing made operationally mundane ☆`8,538`
- [dagu-org/dagu](https://github.com/dagu-org/dagu) — A lightweight workflow engine with builtin Web UI. No code, self-contained, and portable. execute them anywhere with a single binary, compose complex pipelines from reusable sub-workflows, and distribute tasks across workers. Just work without requiring databases, message brokers, or code changes. ☆`2,938`
- [jf-tech/omniparser](https://github.com/jf-tech/omniparser) — omniparser: a native Golang ETL streaming parser and transform library for CSV, JSON, XML, EDI, text, etc. ☆`1,074`
- [noneback/go-taskflow](https://github.com/noneback/go-taskflow) — A pure go General-purpose Task-parallel Programming Framework with integrated visualizer and profiler ☆`605`
- [cadence-workflow/cadence-go-client](https://github.com/cadence-workflow/cadence-go-client) — Cadence workflow client for Go ☆`375`
- [luno/workflow](https://github.com/luno/workflow) — The type-safe, event-driven workflow orchestration library that scales with your business. Build robust, distributed workflows in Go with compile-time safety, automatic retries, and horizontal scaling out of the box. Integrate with your existing tech stack using adapters ☆`211`
- [rhosocial/go-dag](https://github.com/rhosocial/go-dag) — A Go-based framework has been developed to oversee the execution of workflows delineated by directed acyclic graphs (DAGs). ☆`35`


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