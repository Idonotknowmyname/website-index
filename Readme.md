# The static part of Matteo Maggiolo's website
Built with Jekyll and the [Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/).

# Notes when running locally
If you are on a Mac (intel), and you are getting nokogiri file not found error, update the nokogiri entry in the Gemfile.lock, replacing `nokogiri-X.XX.X-arm64-darwin` with `nokogiri-X.XX.X-x86_64-darwin`