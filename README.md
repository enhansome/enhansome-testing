![](https://github.com/TheJambo/awesome-testing/blob/master/AwesomeTesting.jpg?raw=true)

# Awesome Testing with stars

> A curated list of testing software, extensions and resources

## Foreword

This is intended to be a curation of resources for the new among the software testing community. It is not tailored to a specific area (Usability/Performance) or role (Automation/Management). The idea is that you could hand this list to a CS graduate and it would greatly improve their testing skills, efficiency and overall breadth of knowledge. Note that this is for all areas of software testing after the code in question is written (no unit tests/static analysis!).

Finally, I'm sure everyone who reads this list has one thing they want to add. Please read the [How to Contribute](https://github.com/TheJambo/awesome-testing/blob/master/CONTRIBUTING.md) ⭐ 2,358 | 🐛 8 | 📅 2026-08-25 page and add to the list. :)

## Contents

* [Software](#software)
* [Books](#books)
* [Training](#training-includes-developer-training-for-automation-testers)
* [Blogs](#blogs)
* [Newsletters](#newsletters)
* [Suggested Awesome Lists](#suggested-awesome-lists)
* [QA & Testing Road Map](#qa-and-testing-road-map)
* [Others](#others)
* [Contributing](#contributing)
* [Code of Conduct](#code-of-conduct)
* [License](#license)

## Software

### API Testing

* [Bruno](https://github.com/usebruno/bruno) ⭐ 46,609 | 🐛 1,827 | 🌐 JavaScript | 📅 2026-08-28 - Open-source API client for exploring and testing APIs.
* [Keploy](https://github.com/keploy/keploy) ⭐ 18,435 | 🐛 716 | 🌐 Go | 📅 2026-08-28 - API Testing Platform that automatically generates unit test cases along with dependency mocks.
* [RestQA](https://github.com/restqa/restqa) ⭐ 93 | 🐛 18 | 🌐 JavaScript | 📅 2024-09-13 - REST API testing framework based on Gherkin.
* [Swagger Coverage Tool](https://github.com/Nikita-Filonov/swagger-coverage-tool) ⭐ 26 | 🐛 0 | 🌐 HTML | 📅 2026-06-09 - The Swagger Coverage Tool is designed to measure API test coverage based on Swagger documentation. It provides automated tracking and reporting of test coverage for APIs, helping ensure that your endpoints and services are well-tested.
* [SpecTest](https://github.com/justiceo/spectest) ⭐ 21 | 🐛 3 | 🌐 TypeScript | 📅 2026-07-11 - Truly declarative API testing framework in Js, or plain JSON.
* [postman2pytest](https://github.com/golikovichev/postman2pytest) ⭐ 18 | 🐛 1 | 🌐 Python | 📅 2026-08-24 - Convert a Postman Collection v2.1 JSON file into a ready-to-run pytest test suite.
* [Webhook Debugger](https://github.com/brancogao/webhook-debugger) ⭐ 13 | 🐛 1 | 🌐 JavaScript | 📅 2026-02-17 - Open-source, self-hosted webhook inspector with signature verification support.
* [Tests Coverage Tool](https://github.com/Nikita-Filonov/tests-coverage-tool) ⭐ 10 | 🐛 0 | 🌐 HTML | 📅 2026-07-27 - Ultimate tool to measure gRPC service coverage from tests.
* [API Status Check](https://apistatuscheck.com) - Real-time status monitoring dashboard for 188+ third-party APIs (OpenAI, Stripe, AWS, GitHub, etc.) with response time tracking and free alert tiers.
* [Polarity](https://www.polarity.so) - The First AI QA Engineer that does full E2E, API, UI testing. Understands your entire codebase and ensures all relavent tests are conducted with our long running agent setup.
* [BitDive](https://bitdive.io/) - Zero-code API testing platform for Java/Kotlin. Captures deep runtime context (HTTP, SQL, methods), auto-generates mocks from real traffic, and enables Live Context Replay for E2E testing and debugging.
* [CORS Tester](https://cors-error.dev/cors-tester/) - A tool for developers and API testers to check if an API is CORS-enabled for a given domain and identify gaps.
* [HttpMaster](https://www.httpmaster.net) - Professional software tool for HTTP testing and debugging.
* [Webhook Debugger & Logger](https://apify.com/ar27111994/webhook-debugger-logger) - Enterprise-grade tool for testing, debugging, and logging incoming webhooks in real-time.
* [Spiderhash](https://spiderhash.io/) - Webhook debugging and request inspection tool for testing callback payloads, headers, and delivery behavior.
* [KushoAI](https://kusho.ai/) - AI-native platform for API contract testing, end-to-end testing, UI testing, and continuous security scanning, with self-healing tests that automatically adapt to code changes in CI/CD.
* \[funapi] (<https://funapi.dev>) - A free mock REST API service designed for practicing API testing, automation, and integration with realistic scenarios and endpoints.

### Security Testing

* [Nuclei Scanner](https://github.com/projectdiscovery/nuclei) ⭐ 30,890 | 🐛 106 | 🌐 Go | 📅 2026-08-26 - nuclie is automated scanner for common vulnerbilty finding on site.
* [OWASP ZAP](https://github.com/zaproxy/zaproxy) ⭐ 15,696 | 🐛 858 | 🌐 Java | 📅 2026-08-27 - Intercepting proxy for HTTP traffic manipulation, security scanning, and exploitation.
* [BeEF](http://beefproject.com/) - Manipulate the browser by exploiting any XSS vulnerabilities you find.
* [BurpSuite](https://portswigger.net/burp/communitydownload) - Intercept API and Reply with changes in realtime with according api manipulations.

### AI & LLM Testing

* [promptfoo](https://github.com/promptfoo/promptfoo) ⭐ 24,640 | 🐛 534 | 🌐 TypeScript | 📅 2026-08-28 - Open-source framework for testing and red teaming LLM applications. Compare prompts, test RAG architectures, run multi-turn adversarial attacks, and catch security vulnerabilities with CI/CD integration.
* [nika](https://github.com/supernovae-st/nika) ⭐ 58 | 🐛 45 | 🌐 Rust | 📅 2026-08-28 - Workflow engine for AI with testing built in: `nika test` pins a workflow's offline behavior as a golden snapshot (deterministic mock provider, zero keys) and replays it in CI; every run also leaves a hash-chained trace for post-hoc verification.
* [voicetest](https://github.com/voicetestdev/voicetest) ⭐ 32 | 🐛 8 | 🌐 Python | 📅 2026-07-20 - Open-source test harness for voice AI agents supporting Retell, VAPI, LiveKit, and Bland with autonomous simulations and LLM-based evaluation.
* [Evaliphy](https://github.com/evaliphy/evaliphy) ⭐ 18 | 🐛 12 | 🌐 TypeScript | 📅 2026-05-07 - Test your AI system end-to-end with Evaliphy. It uses a Playwright-style testing approach and generates HTML reports.
* [Tenro](https://github.com/tenro-ai/tenro-python) ⭐ 7 | 🐛 1 | 🌐 Python | 📅 2026-06-09 - Open-source testing framework for AI agents. Simulate LLM and tool calls to test edge cases, failure paths, and agent logic without live API calls.
* [AgentSkeptic](https://github.com/jwekavanagh/agentskeptic) ⭐ 0 | 🐛 6 | 🌐 TypeScript | 📅 2026-08-03 - Verifies AI/agent workflows by checking database state after execution, comparing expected vs observed outcomes with read-only SQL.
* [QASkills.sh](https://qaskills.sh) - Open registry of 400+ QA and testing skills (Playwright, API, LLM evaluation, accessibility, performance) that AI coding agents install and follow via the qaskills CLI. Works with Claude Code, Cursor, and 30+ other agents.

### Service Virtualization

* [WireMock](https://github.com/wiremock/wiremock) ⭐ 7,350 | 🐛 495 | 🌐 Java | 📅 2026-08-28 - Open source HTTP mock engine written in Java. Embed in your test code, run as a standalone process, or deploy via Docker.
* [MockServer](https://github.com/mock-server/mockserver-monorepo) ⭐ 4,956 | 🐛 2 | 🌐 Java | 📅 2026-08-28 - Mocking, debugging proxy and chaos engineering tool for multiple protocols (HTTP, gRPC, GraphQL, LLM, MCP, Kafka, TCP and more); mock any dependency, record/replay and inspect traffic, verify requests, and inject faults. Docker, JAR, Helm, multi-language clients.
* [fakecloud](https://github.com/faiscadev/fakecloud) ⭐ 535 | 🐛 5 | 🌐 Rust | 📅 2026-08-24 - Free, open-source local AWS cloud emulator for integration tests, with 23 services at 100% conformance and first-party test-assertion SDKs in 6 languages.
* [DeepfakeHTTP](https://github.com/xnbox/DeepfakeHTTP) ⭐ 526 | 🐛 8 | 🌐 Java | 📅 2022-08-05 - Web server using HTTP dumps as a response source for API simulation.
* [mockd](https://github.com/getmockd/mockd) ⭐ 144 | 🐛 11 | 🌐 Go | 📅 2026-08-18 - Open-source multi-protocol mock server supporting HTTP, gRPC, GraphQL, WebSocket, MQTT, and SOAP with chaos engineering and proxy recording.
* [Beeceptor](https://beeceptor.com/) - Easy to use no-code mock servers for service virtualization. Rest, SOAP, GraphQL supported. Create an API mock server from OpenAPI Specification or Postman collection.
* [ApiNotes](https://apinotes.io/mock-server) - Drop your OpenAPI spec and get a fully functional mock API server instantly. Export to Bruno API client or test directly.

### Visual Testing

* [recheck-web](https://github.com/retest/recheck-web) ⭐ 269 | 🐛 30 | 🌐 HTML | 📅 2023-02-27 - Change comparison tool with Golden Masters and "unbreakable Selenium" tests.
* [Sherlo](https://github.com/sherlo-io/sherlo) ⭐ 83 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-27 - Visual testing platform for React Native Storybook. Captures screenshots on iOS and Android simulators in the cloud and detects visual changes automatically.
* [GoodLooks](https://github.com/dashcamio/goodlooks) ⭐ 52 | 🐛 0 | 🌐 JavaScript | 📅 2025-01-09 - AI-powered visual validation for Playwright tests.
* [Frostbyte Screenshot Action](https://github.com/OzorOwn/frostbyte-screenshot-action) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-03-04 - GitHub Action for automated website screenshots in CI/CD pipelines. Supports multiple viewports, full-page capture, and dark mode emulation.
* [Fluxguard](https://fluxguard.com) - Screenshot pixel and DOM change comparisons.
* [Happo](https://happo.io) - Cross-browser screenshot and visual regression testing service, integrates with tools like Storybook, Playwright, and Cypress.
* [Image Diff](https://nutilz.com/image-diff) - Free, browser-based pixel diff tool for comparing two images and highlighting exactly what changed, with an adjustable sensitivity threshold. No upload, no sign-up.
* [Lastest](https://lastest.cloud) - Visual regression testing for Playwright with AI flake triage and baseline review.
* [TestingBot](https://testingbot.com) - Supports automated, manual, and visual testing.
* [wopee.io](https://wopee.io/) - Autonomous visual regression testing platform.
* [SmartUI by TestMu AI (formerly LambdaTest)](https://www.testmuai.com/visual-testing-tool/)- AI-Native Visual Testing Tool for Flawless UIs across browsers, apps, websites, and PDFs.

### UI & End-to-End Testing

* [QA Wolf](https://github.com/qawolf/qawolf) ⭐ 3,443 | 🐛 5 | 🌐 TypeScript | 📅 2026-08-28 - Node.js library for creating browser tests faster.
* [Ferrum](https://github.com/rubycdp/ferrum) ⭐ 2,038 | 🐛 14 | 🌐 Ruby | 📅 2026-08-28 - Chrome automation via CDP with a high-level Ruby API.
* [Hercules](https://github.com/test-zeus-ai/testzeus-hercules) ⭐ 1,134 | 🐛 37 | 🌐 Python | 📅 2026-08-04 - Open-source end-to-end testing agent.
* [agent-qa](https://github.com/vostride/agent-qa) ⭐ 888 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-03 - Open-source Agentic QA Harness with Memory. Write tests in natural language. agent-qa runs them across web and mobile with execution memory, catching regressions before release.
* [playwright-bdd](https://github.com/vitalets/playwright-bdd) ⭐ 769 | 🐛 31 | 🌐 TypeScript | 📅 2026-08-27 - BDD-style Playwright testing.
* [tapflow](https://github.com/jo-duchan/tapflow) ⭐ 531 | 🐛 78 | 🌐 TypeScript | 📅 2026-08-28 - Self-hosted mobile QA tool that streams iOS simulators and Android emulators to the browser for team-wide testing without local setup.
* [flutter-skill](https://github.com/ai-dashboad/flutter-skill) ⭐ 360 | 🐛 7 | 🌐 Dart | 📅 2026-08-21 - AI-powered E2E testing via MCP for Flutter, React Native, iOS, Android, Electron, Tauri, KMP, and .NET MAUI. Zero test code.
* [UI Coverage Tool](https://github.com/Nikita-Filonov/ui-coverage-scenario-tool) ⭐ 8 | 🐛 0 | 🌐 HTML | 📅 2025-05-20 - UI Coverage Tool is an innovative, no-overhead solution for tracking and visualizing UI test coverage — directly on your actual application, not static snapshots.
* [Polarity](https://www.polarity.so) - Full visual and desktop environments showcasing complete E2E testsing for all UI/UX features. Generated you Playwrite, Cypress, and other code for you as the test runs.
* [BugBug](https://bugbug.io) - No-code test automation tool for web applications.
* [Courgette](https://courgette-testing.com) - Declarative BDD UI testing with Gherkin.
* [DevAssure](https://app.devassure.io) - Agentic testing for E2E web UI on real browsers. Agent can be added to Github Actions to test only the flows that have changed in a PR.
* [DeviceLab](https://devicelab.dev) - Private device lab infrastructure for mobile testing. Connect your own iOS/Android devices and run Appium, Maestro, or XCUITest remotely via WebRTC. Zero-trust architecture keeps test data on your network.
* [Hyperbrowser](https://hyperbrowser.ai) - Scalable headless browser testing with built-in session recording.
* [Kane CLI](https://www.testmuai.com/kane-cli/) - Natural-language browser testing from the terminal, locally or in CI, with export to Playwright and shareable run evidence.
* [Keploy](https://keploy.io) – Open-source AI-powered end-to-end testing tool for APIs and microservices that auto-generates test cases and mocks from real traffic.
* [TestMu AI (formerly LambdaTest)](https://www.testmuai.com) - Full-Stack Agentic AI Quality Engineering platform that empowers teams to test intelligently and ship faster.
* [Mocky Balboa](https://docs.mockybalboa.com/) - Mock server side network requests in your fullstack apps declaratively at runtime
* [Octomind](https://github.com/OctoMind-dev) - AI-powered test case discovery and maintenance.

### Test Management

* [TestLink](https://github.com/TestLinkOpenSourceTRMS/testlink-code) ⭐ 1,614 | 🐛 51 | 🌐 PHP | 📅 2025-12-08 - Open-source test case management system.
* [Kiwi TCMS](https://github.com/kiwitcms/Kiwi) ⭐ 1,248 | 🐛 138 | 🌐 Python | 📅 2026-08-28 - Open-source test case management.
* [skipper](https://github.com/get-skipper/skipper) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-01 - Real-time test execution control via Google Spreadsheet, enabling instant toggle without code changes.
* [Testomatio](https://testomat.io/) - Modern TCMS allowing sync of manual and automated tests.

### Test Data Management

* [Synth](https://github.com/getsynth/synth) ⭐ 1,484 | 🐛 98 | 🌐 Rust | 📅 2024-09-27 - Open-source test data generator.
* [Touca](https://github.com/trytouca/trytouca) ⭐ 509 | 🐛 6 | 🌐 TypeScript | 📅 2024-08-04 - Continuous regression testing for behavioral and performance comparisons.
* [test-each](https://github.com/ehmicky/test-each) ⭐ 118 | 🐛 0 | 🌐 JavaScript | 📅 2025-05-25 - Data-driven testing framework.
* [DATAMIMIC CE](https://github.com/rapiddweller/datamimic) ⭐ 37 | 🐛 1 | 🌐 Python | 📅 2026-07-17 - Open-source, deterministic engine for model-driven synthetic test data and PII pseudonymization. Pin a seed and get byte-identical output with a provenance hash on every run. Python, MIT.
* [MockJutsu](https://github.com/altansayan/mock-jutsu-api) ⭐ 11 | 🐛 7 | 🌐 HTML | 📅 2026-08-05 - Algorithmic open-source mock data engine generating 390+ format-valid types (IBAN, TCKN, Luhn, VIN, NHS, SWIFT, MRZ and more). CLI + REST API + Python package + JMeter
  plugin. 6 locales.
* [JSON Validation Test Cases](https://github.com/UtilHatch/json-validation-test-cases) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-14 - Reusable valid, invalid, and edge-case JSON fixtures for testing parsers, validators, APIs, editors, and error handling.
* [Temp Mail 24](https://temp-mail24.com/) - Browser-based receive-only temporary inbox for permitted manual signup-flow testing.
* [sms-florin](https://flo-voice1.com) - Rent a real UK phone number to receive SMS/OTP codes for testing verification flows (WhatsApp, Telegram, Google, and others). Ships a JS/TS SDK for CI/QA automation.
* [MockHero](https://mockhero.dev) - REST API for generating synthetic test data. 156 field types, 22 locales, relational data, sub-50ms. Free tier available.
* [Fake Data Generator](https://singhajit.com/tools/fake-data-generator/) - Browser-based generator for realistic mock/test data. Custom schema or presets, export as JSON, CSV, or SQL INSERT.
* [Sample Files](https://mzeeshan.me/tools/sample-files) - Free downloadable test file variants across video, audio, document, and archive formats (MP4, MOV, RTF, ZIP, PPTX, etc.), covering codecs, encodings, and edge cases for parser and import testing.
* [FakeNamely](https://fakenamely.com) - Free web generator and keyless JSON API for fictional identities, addresses and names across 38 countries. Seeded requests return byte-identical records, so a fixture can be committed; addresses pair a real city and a genuinely valid postal code with an invented street.

### Browser Extensions & Utilities

* [Anchor Browser](https://anchorbrowser.io) - Cloud browser infrastructure with built-in stealth and proxy rotation for automated testing at scale
* [Bug Magnet](https://chrome.google.com/webstore/detail/bug-magnet/efhedldbjahpgjcneebmbolkalbhckfi) - Field-based value suggestions for form testing.
* [BugShot](https://chromewebstore.google.com/detail/bugshot/ohakhekagkodklkickemonmifdcbhmig) - Capture a bug as a screenshot, a screen or tab recording, or a 30-second replay, with console, network, and user action logs collected automatically. Reports go straight from the browser to Jira, GitHub, Linear, Notion, GitLab, Asana, ClickUp, or Slack, with no third-party server in between. Open source, MIT.
* [Check All](https://chrispederick.com/work/web-developer/) - Provides a "Select All" function where missing.
* [Full Page Screenshot](https://chrome.google.com/webstore/detail/full-page-screen-capture/fdpohaocaechififmbbbbbknoalclacl) - Capture full-page screenshots.
* [Form Filler](https://chrome.google.com/webstore/detail/form-filler/bnjjngeaknajbdcgpfkgnonkmififhfo) - Auto-fill large forms with dummy data.
* [ProxySwitcher](https://chrome.google.com/webstore/detail/proxy-switcher-manager/onnfghpihccifgojkpnnncpagjcdbjod) - Easy proxy switching for test/prod environments.
* [Requestly](https://requestly.io/) - A lightweight proxy to intercept and modify network requests.

### Accessibility & Usability Testing

* [VertaaUX CLI](https://github.com/VertaaUX/cli) ⭐ 0 | 🐛 0 | 📅 2026-06-17 - UX, accessibility, and conversion audits from the terminal and CI, with score-based quality gates and PR regression detection.
* [Colour Blindness Simulator](https://altreus.github.io/colourblind/) - Simulate different types of color blindness.
* [RatedWithAI](https://ratedwithai.com) - AI-powered website accessibility scanner that checks for ADA and WCAG 2.2 compliance with instant actionable audits.
* [squirrelscan](https://squirrelscan.com) - Audits websites for accessibility, SEO, performance, and security with 260+ rules and returns exact fixes for your coding agent, from the CLI, cloud, or MCP.
* [WAVE](https://wave.webaim.org/) - Suite of evaluation tools that helps authors make their web content more accessible to individuals with disabilities.

### Performance & Load Testing

* [Load Testing Hub Panel](https://github.com/Nikita-Filonov/load-testing-hub-panel) ⭐ 23 | 🐛 0 | 🌐 TypeScript | 📅 2025-08-16 - Ultimate web UI for visualizing load test results
* [Yslow](http://yslow.org/) - Analyze web page performance based on Yahoo!'s rules.

### Web3 & Blockchain Testing

* [Foundry](https://github.com/foundry-rs/foundry) ⭐ 10,570 | 🐛 281 | 🌐 Rust | 📅 2026-08-28 - Fast, modular toolkit for Ethereum development.
* [Robot Framework Solidity Testing Toolkit](https://github.com/jg8481/Robot-Framework-Solidity-Testing-Toolkit) ⭐ 13 | 🐛 14 | 🌐 HTML | 📅 2026-08-10 - Robot Framework integration for Solidity testing.
* [Cannon](https://usecannon.com/) - Continuous configuration automation for Ethereum.
* [Dapp.tools](https://dapp.tools/) - Command-line tools and smart contract libraries for Ethereum.
* [Ganache](https://trufflesuite.com/ganache/) - Personal Ethereum blockchain for running tests.
* [Hardhat](https://hardhat.org/) - Ethereum development and testing environment.
* [Truffle Suite](https://trufflesuite.com/) - Comprehensive smart contract development suite.

### Test Automation Frameworks

* [Bats](https://github.com/bats-core/bats-core) ⭐ 6,236 | 🐛 127 | 🌐 Shell | 📅 2026-07-26 - Bash Automated Testing System.
* [Jumpstarter](https://github.com/jumpstarter-dev/jumpstarter) ⭐ 213 | 🐛 163 | 🌐 Python | 📅 2026-08-28 - Open source hardware-in-the-loop testing framework for automated testing on real and virtual hardware with CI/CD integration.
* [OpenTester](https://github.com/kznr02/OpenTester) ⭐ 28 | 🐛 0 | 🌐 Python | 📅 2026-03-23 - MCP-First Testing Framwork: AI Agents Can Now Test Like Humans
* [ai-natural-language-tests](https://github.com/aiqualitylab/ai-natural-language-tests) ⭐ 23 | 🐛 7 | 🌐 Python | 📅 2026-08-27 - Generates Cypress and Playwright E2E tests from natural language requirements using LangGraph, ChromaDB, and multi-provider LLM support.
* [optics-framework](https://github.com/mozarkai/optics-framework) ⭐ 10 | 🐛 61 | 🌐 Python | 📅 2026-08-26 - Self-healing test automation for mobile, web and Smart TV. Keyword-driven CSV/YAML tests run on Appium, Selenium and Playwright; when a locator breaks it falls back across XPath, text, OCR and image strategies, with optional AI-powered self-healing.
* [Robot Framework](https://robotframework.org/) - Generic open-source automation framework for testing and RPA.
* [Selenium Boot](https://seleniumboot.com) - Java framework layered on Selenium WebDriver and TestNG. One Maven dependency and one YAML file replace the usual driver-lifecycle, wait, retry and reporting boilerplate, and the raw WebDriver stays accessible.

### Screen Recording & Session Replays

* [rrweb](https://github.com/rrweb-io/rrweb) ⭐ 20,087 | 🐛 423 | 🌐 TypeScript | 📅 2026-08-24 - Records the DOM and user interactions as a typed JSON event stream and replays them pixel-perfect.
* [Captura](https://github.com/MathewSachin/Captura) ⭐ 10,807 | 🐛 116 | 🌐 C# | 📅 2026-05-25 - Open-source video recording tool.
* [PR Preview](https://www.pr-preview.com/) - MCP for Claude Code that drives your web app in a headed browser and records before/after demo videos of a pull request as MP4 or GIF.

### Mind Mapping & Documentation

* [Xmind](http://www.xmind.net/) - Mind mapping tool for documenting test cases and strategies.

### A/B Testing

* [Kirro](https://kirro.io) - A/B testing tool with visual editor, Bayesian statistics, and GA4 conversion tracking.

## Books

* [The Scrum Field Guide, Agile advice for your first year and beyond](https://amzn.to/2OERKEm) - Why you might want to move your company to Agile and great practical advice on how to do it.
* [Fifty quick ideas to improve your Tests](https://amzn.to/2AzMUF7) - Great illustrative examples on how to improve tests and why you should do them. Great as evidence for winning arguments!
* [Agile Testing: A Practical Guide](https://amzn.to/2n1K2aG) - A how to guide for those looking to transition to an Agile as a tester and also how the authors work on their Agile teams.
* [Explore It!: Reduce Risk and Increase Confidence with Exploratory Testing](https://amzn.to/2n8axLn) - A very good book on structuring Exploratory Testing and designing tests.
* [The Domain Testing Workbook](https://amzn.to/2Az4l90) - An in-depth look at the most common test technique, Domain Testing (also called Boundary Analysis and Equivalence Class partitioning) in use today with lots of examples to become better.
* [Don't Make Me Think: A Common Sense Approach to Web Usability](https://amzn.to/2naYmhf) - An incredibly useful book for usability testing.
* [Lessons Learned in Software Testing](https://amzn.to/2LTjM01) - One of the best books on Software Testing, broken into bite size lessons that are as applicable now as when it was published.
* [UI is Communication](https://amzn.to/2vbiALY) - How to make intuitive User Interfaces (UI and Usability Testing).
* [Thinking, Fast and Slow](https://amzn.to/2vcjasX) - About how we make decisions and how to run experiments (experiments == tests).
* [Chaos Engineering: Crash test your applications](https://www.manning.com/books/chaos-engineering) - A book on how to design and execute controlled software failure experiments.
* [Testing JavaScript Applications](https://www.manning.com/books/testing-javascript-applications) - A book about JavaScript testing tools and techniques for developers.
* [Chaos Engineering](https://www.manning.com/books/chaos-engineering) - A book that teaches you to design and execute controlled experiments that uncover hidden problems.
* [The Art of Unit Testing, Third Edition](https://www.manning.com/books/the-art-of-unit-testing-third-edition) - A book that guides you step by step from your first simple unit tests to building complete test sets that are maintainable, readable, and trustworthy.
* [Testing Web APIs](https://www.manning.com/books/testing-web-apis) - Guarantee the quality and consistency of your web APIs by implementing an automated testing process.
* [Effective Software Testing](https://www.manning.com/books/effective-software-testing) - A hands-on guide for developers on how to create high quality tests in a systematic and effective way.

## Training (Includes developer training for automation testers)

* [Learn to Code](https://github.com/karlhorky/learn-to-program) ⭐ 4,905 | 🐛 24 | 📅 2025-05-10 - Another awesome list for developer training
* [FrontRow](https://github.com/majdukovic/frontrow) ⭐ 7 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-12 - Open source React Native mobile app built as a hands on training surface for QA automation. Cross platform testIDs work across Maestro, Appium, Espresso and XCUITest, and a deep QA Debug Menu lets trainees force the failure modes that actually bite in production (4xx, 5xx, timeouts, offline, denied permissions, declined IAP, expired tokens) without flaky backends.
* [The Dojo](https://dojo.ministryoftesting.com/) - Courses and talks directly from the testing community.
* [Coursera](https://www.coursera.org/) - Online courses from top universities.
* [Cybrary](https://www.cybrary.it/) - Online free security training.
* [BBST Testing Courses](https://bbst.courses/bbst-testingeducation-materials/) - The famous Black Box Software Testing (BBST) courses are university level courses on Software Test Foundations, Bug Reporting and Test Design. These materials have been creative commons licensed for use by anyone. Includes articles, slides and video lectures.

## Blogs

* [James Bach](http://www.satisfice.com/blog/)
* [Michael Bolton](http://www.developsense.com/blog/)
* [Janet Gregory](http://janetgregory.ca/blog/)
* [Nikita Sobolev](https://sobolevn.me/)
* [Softwaretester Blog](https://www.softwaretester.blog/)
* [Automation Panda](https://automationpanda.com/)
* [And others](https://github.com/ChristoWolf/awesome-testing-blogs) ⭐ 117 | 🐛 6 | 🌐 Markdown | 📅 2026-04-14

## Newsletters

* [Coding Jag](https://www.testmuai.com/newsletter) - Your weekly dose of the latest in AI, Testing, Development, CI/CD, and Automation—keeping you ahead of the curve.
* [Software Testing Weekly](https://softwaretestingweekly.com/) - A curated round-up of the best software testing news and tools published every Friday.

## Suggested Awesome Lists

### Must Read

* [Naughty Strings](https://github.com/minimaxir/big-list-of-naughty-strings) ⭐ 47,711 | 🐛 108 | 🌐 Python | 📅 2024-04-18 - This is the famous list of Naughty Strings. If you're doing some field validation, look no further for inspiration.
* [Falsehoods](https://github.com/kdeldycke/awesome-falsehood) ⭐ 27,652 | 🐛 4 | 📅 2026-08-14 - A funny and educational list of why nothing in Software Development is ever easy. Think you can store a marriage in a DB?
* [Unicode](https://github.com/jagracey/Awesome-Unicode) ⭐ 982 | 🐛 10 | 🌐 JavaScript | 📅 2022-07-01 - A great resource for learning how unicode works and the issues it can cause.

### Useful References

* [The Original](https://github.com/sindresorhus/awesome) ⭐ 500,739 | 🐛 105 | 📅 2026-08-21 - The awesome list of awesome lists.
* [Security](https://github.com/sbilly/awesome-security) ⭐ 14,802 | 🐛 314 | 📅 2026-01-11 - This is mostly focused on Infrastructure, but if you're testing a series of systems, this is very useful.
* [Application Security](https://github.com/paragonie/awesome-appsec) ⭐ 7,046 | 🐛 40 | 🌐 PHP | 📅 2025-02-22 - Incredibly extensive, but you'll find something to fit the bill.
* [How They Test](https://github.com/abhivaikar/howtheytest) ⭐ 6,866 | 🐛 3 | 🌐 TypeScript | 📅 2026-08-22 - A curated collection of public resources from tech companies on how they test their software and build a quality culture
* [Learn to Code](https://github.com/karlhorky/learn-to-program) ⭐ 4,905 | 🐛 24 | 📅 2025-05-10 - Learning to code, for those looking to make the move to automation
* [Awesome Software Quality](https://github.com/ligurio/awesome-software-quality) ⭐ 2,320 | 🐛 0 | 📅 2023-02-01 - A list of free software testing and verification resources.
* [Selenium](https://github.com/christian-bromann/awesome-selenium) ⭐ 1,130 | 🐛 6 | 📅 2026-03-17 - Better than searching Google if you know what you want.
* [Awesome JMeter](https://github.com/aliesbelik/awesome-jmeter) ⭐ 807 | 🐛 4 | 🌐 HTML | 📅 2026-08-01 - A curated collection of resources around Apache JMeter.
* [Awesome AI Testing](https://github.com/tugkanboz/awesome-ai-testing) ⭐ 80 | 🐛 65 | 📅 2026-08-28 - A curated list of AI-powered testing tools, frameworks, and resources for QA engineers, covering test generation, self-healing automation, MCP-based testing, and LLM-as-judge evaluation.
* [Awesome Cucumber](https://github.com/virajkulkarni14/awesome-cucumber) ⭐ 45 | 🐛 3 | 📅 2021-09-22 - A (relatively-newer) curated list of awesome Cucumber and Gherkin-related resources.
* [Awesome Performance Engineering](https://github.com/be-next/awesome-performance-engineering) ⭐ 36 | 🐛 1 | 📅 2026-08-06 - A curated collection of tools and resources for performance engineering, covering observability and performance testing.
* [Awesome Behave](https://github.com/MathiasPaulenko/awesome-behave#readme) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2026-08-14 - A curated list of Behave resources, tools, and libraries for Python BDD.

## QA and Testing Road Map

* [How to start QA and Testing career](https://github.com/fityanos/Quality-Assurance-Road-Map) ⭐ 2,170 | 🐛 9 | 📅 2026-06-04 - A wide and rich list of strategies, topics, and skills that you need to start a career in software testing and automation.
* [QALadder](https://qaladder.org) - A free, sequenced roadmap from manual QA to SDET, with a 150-question interview bank, browser-based practice labs, and QA tools.

## Others

* [Software Testing Interview Tool](https://github.com/TheJambo/ToDoInterviewTest) ⭐ 52 | 🐛 0 | 🌐 JavaScript | 📅 2020-10-04 - A very buggy To Do List to facilitate face to face interviews.
* [Testers Rage Playlist](https://play.spotify.com/user/sanchezni/playlist/5yzT0HrymwEeO8ckqgkPiW) - A collaborative playlist from testers for when the red mist descends.
* [Software Testing Conferences](http://testingconferences.org/) - A list of software testing conferences and workshops.

## Contributing

See the *Awesome Testing* [contribution guide](CONTRIBUTING.md) for details on how to contribute.

## Code of Conduct

See the [Code of Conduct](CODE-OF-CONDUCT.md) for details. Basically it comes down to:

> In the interest of fostering an open and welcoming environment, we as
> contributors and maintainers pledge to making participation in our project and
> our community a harassment-free experience for everyone, regardless of age, body
> size, disability, ethnicity, gender identity and expression, level of experience,
> nationality, personal appearance, race, religion, or sexual identity and orientation.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [the
contributors](https://github.com/TheJambo/awesome-testing/graphs/contributors) ⭐ 2,358 | 🐛 8 | 📅 2026-08-25
have waived all copyright and related or neighboring rights to this work. See the
[license file](LICENSE) for details.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-28._
