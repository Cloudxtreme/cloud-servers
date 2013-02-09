# Cloud Servers

A package for simulating cloud-like URLs.

### Usage

Directories are relative to the `cloud-servers` workspace directory (`process.cwd()`), so you can reference other directories on your local machine.

To run a local instance, copy the `conf-sample.js` file into your project directory, rename it to `conf.js,` and add as many instances of servers as needed.

All directories (the `dir` variable in `conf.js`) are relative to the project directory, so to access anything below the project root, use '../' (Mac/Linux) or '..\' (Windows).

Alternately, just dump your cloud files into the CDN folder, and start it up. No configuration necessary. (All contents in the CDN folder are ignored.)