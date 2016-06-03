# Spotify-Electron
A simple Electron wrapper for Spotify.

## Prerequisites
Spotify-Electron comes with a build script to compile the code for you.
In order for the script to run, `nodejs` and `electron-packager` must first be installed.

Installing `nodejs` is different depending on the platform you are running. On Ubuntu, the following should work:

```bash
sudo apt-get install npm
```

Install `electron-packager` with the following command:

```bash
npm install -g electron-packager
```

Then, run the build script with the following command:

```bash
./build.sh
OR
bash build.sh
```

If you want to build with a version of Electron that is different from what is
in the latest commit, open `build.sh` with your favorite text editor and change
the value of `VERSION=` to the build you want.
