# v1.1.4 (2022-11-11)
- Updates ruby/setup-ruby to v1 (which should automatically get fixes without
  having to manually update the tag); in this case, ruby 2.7 wasn't available
  to install on ubuntu 22.04 on the previous version of ruby/setup-ruby we were
  using

# v1.1.3 (2022-10-24)
- Adds bundler-version input
- Adds more system dependency logic for gems

# v1.1.2 (2022-10-19)
- Changes variable assignment to use environment variables again

# 1.1.1 (2022-10-19)
- Bumps ssh-agent to 0.7.0

# 1.1.0 (2022-10-13)
- Changes variable assignment to use environment variables

# 1.0.3 (2022-10-11)
- Adds support for ruby gems by allowing caller to pass in ruby version
