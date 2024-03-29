Hi there 👋. You're probably interested in my open source work, so here is a quick summary. I've also added a bit of work history.

📫 Please open a GitHub issue if you want to discuss something related to an open source project of mine. 

Otherwise you can reach me at gh@felixge.de.

Last Update: 2022-09-19

## Open Source

### Go (2012-now)

- [traceutils](https://github.com/felixge/traceutils): Code for decoding and encoding runtime/trace files as well as useful functionality implemented on top.
- [fgtrace](https://github.com/felixge/fgtrace): An experimental profiler/tracer that is capturing wallclock timelines for each goroutine. It's very similar to the Chrome profiler.
- [cl](https://github.com/felixge/cl): Quickly clone git repositories into a nested folders like GOPATH.
- [pprofutils](https://github.com/felixge/pprofutils): Swiss army knife for pprof files. Implemented as a command line utility as well as free web service.
- [gostackparse](https://github.com/DataDog/gostackparse): A library that can parse Go stack traces at 300 MiB/s.
- [sprof](https://github.com/felixge/sprof): A Go profiler based on static analysis. Note the release date.
- [dd-trace-go/profiler](https://github.com/DataDog/dd-trace-go/tree/v1/profiler): Working on this as part of my job for Datadog right now.
- [go-profiler-notes](https://github.com/felixge/go-profiler-notes): In-depth research and writing on the various Go profilers.
- [sqlbench](https://github.com/felixge/sqlbench): A Go tool that measures and compares the execution time of one or more PostgreSQL queries
- [fgprof](https://github.com/felixge/fgprof): Experimental wall-clock profiler for Go.
- [httpsnoop](https://github.com/felixge/httpsnoop): Properly wraps the `http.ResponseWriter` interface in Go for monitoring.
- [go-xxd](https://github.com/felixge/go-xxd): High performance Go implementation of the xxd utility. I got nerd sniped into this.
- [godrone](https://github.com/felixge/godrone): Firmware for the Parrot AR Drone 2.0 written in Go, i.e. an experiment to physically visualize a garbage collector 😉
- [tcpkeepalive](https://github.com/felixge/tcpkeepalive): Exposes TCP keepalive knobs & dials. There are probably better alternatives now.

### PostgreSQL (2017-2020)

- [flame-explain](https://github.com/felixge/flame-explain): An [online](https://flame-explain.com/) PostgreSQL EXPLAIN visualizer written in React/TypeScript. I was very excited about this and scheduled to speak about it at various conferences. Then this pandemic thing happened and I burned out on the project : (.
- [state-machines](https://felixge.de/2017/07/27/implementing-state-machines-in-postgresql/): A blog post showing how to implement state machines in PostgreSQL using user-defined aggregate functions.

### Node.js (mostly 2009-2011)

Contributed [100+ patches](https://github.com/nodejs/node/commits?author=felixge) to the core involving promises, exception handling, fs, module system, UTF-8 (including a [patch for v8](https://codereview.chromium.org/121173009/)). Mea culpa for [process.on("uncaughtException")](https://github.com/nodejs/node/commit/2b252acea47af3ebeac3d7e68277f015667264cc) 🙈.

Additionally I wrote a lot of [NPM modules](https://www.npmjs.com/~felixge), most notably:

- [mysql](https://github.com/mysqljs/mysql): Pure JS implementation of the binary MySQL protocol.
- [formidable](https://github.com/node-formidable/formidable): A multipart/form-data parser that's pretty fast.
- [node-ar-drone](https://github.com/felixge/node-ar-drone): Implementation of the networking protocols used by the Parrot AR Drone 2.0. This one got a bit [out of control](http://www.nodecopter.com/).
- [node-style-guide](https://github.com/felixge/node-style-guide): Not a module, but maybe it helped some people write better modules?

### Misc

- [tus](https://tus.io/): A protocol for resumable file uploads on the web that I wrote the initial version for. It's seen wide industry adoption since.

### CakePHP (2007-2009)

Contributed [~150 patches](https://github.com/cakephp/cakephp/commits?author=felixge) to the core and made some good friends.

## Public Speaking

Here is a list of recent talks:

- [Go Profiling and Observability from Scratch](https://www.gophercon.com/agenda/session/596212) at [GopherCon 2021](https://www.gophercon.com/) ・ Dec 8, 2021
- [Continuous Go Profiling & Observability](https://www.p99conf.io/session/continuous-go-profiling-observability/) at [P99 Conf](https://www.p99conf.io/) ・ [Video](https://www.youtube.com/watch?v=KiMxhKIKd5c) ・ [Slides](https://docs.google.com/presentation/d/1edVkJemsUoShHpApD227SztJxojQh3fKH3fhAA8ASrk/edit?usp=sharing) ・ Oct 6, 2021

You can find an incomplete [list of previous talks](https://felixge.de/#speaking) on my website.

Going forward I'm actively looking for opportunities to present on Go profiling related topics.

## Blogging

I have an infrequently updated [blog](https://felixge.de/#blog) where I give [questionable advise](https://felixge.de/2013/03/11/the-pull-request-hack/) that ocassionally [compromises](https://gist.github.com/felixge/024827e7f09048d7bee2ad7c397e6ace) servers around the world.

## Work

My CV is available on request, but I'm not looking for a job right now.

- **2021-Now**: Datadog, working on Continious Go Profiling.
- **2014-2020**: Apple, working on secret manufacturing stuff using PostgreSQL and Go.
- **2013-2014**: Thomson Reuters, contracted to work on Eikon Messanger XMPP server in Go.
- **2009-2013**: Transloadit, co-founded the business and wrote lots of Node.js code until it was profitable.
- **2006-2008**: Freelancer, working for international clients while finishing high school.
