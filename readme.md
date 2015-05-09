# DevTools

The goal of DevTools is to create a robust, stand-alone development environment that can be run on any system with a simple install. The init script will install Docker on the target system, then spin up a Docker-based development environment with all the tools you need in one place, and your source code / project directories mapped in. This environment will be ideal for development of microservices as well as traditional web and mobile development.

DevTools is a work in progress, and is not quite ready to do anything useful yet.

To get up & running with DevTools, simply:

1. You will need a GitHub account. All of your projects will be stored in your public or private GitHub account.
2. Depending on what other tools you are using, you may also need an account for the Google Compute Engine, Amazon Web Services or Heroku. (eventually...)
3. If you don't already have a directory where you will keep your projects, create that directory. Example:

        md ~/esol-dev

4. Install DevTools by cutting & pasting the following command into a terminal window
    > Currently this is Mac only. Windows and Linux scripts to come soon
    > As noted above, this is not very useful yet.

        curl -sSL https://goo.gl/PqgD5j > init && . ./init && rm init

5. Start your DevTools environment with the command
        . ~/mydev-home/devtools/start
