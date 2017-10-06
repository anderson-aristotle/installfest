# Installfest

## Atom

The text editor we'll be using in this course is called **Atom**; it was
developed by the GitHub team, and is highly extensible.

**Note: From this point forward you will open Atom from the command line** with `atom <path_of_file_or_dir_to_open>`

### macOS ONLY

```bash
# macOS ONLY
brew cask install atom
```

### Linux ONLY

Download the `.deb` file from [Atom.io](https://atom.io/)
Once finished run the following command:

```bash
# LINUX ONLY
sudo dpkg -i atom-amd64.deb
```

### Atom Add-Ons

We're going to use Atom's package manager, `apm`, to add a number of helpful
extensions to your Atom installation.

```bash
scripts/atom.sh
```

If you get a `command not found` response in your terminal, you have not
installed shell commands correctly. In the top menu, select `Atom -> Install Shell Commands`. Then, rerun the above script.

Part of being a good developer is using tools that help you make fewer mistakes.
To that end, let's configure a useful feature in Atom: autosave! The script you just ran should have enabled this for you, but we will check in Atom just to be sure.

Once Atom is open, in the top menu, go to `Packages -> Settings View -> Manage Packages`, and search for autosave.
Then open the "Settings" panel for the autosave plugin.

![Atom Settings > Packages](https://cloud.githubusercontent.com/assets/388761/21697829/41986714-d362-11e6-87ac-f0c42eac72e0.png)

Lastly, ensure the "Enabled" option is checked.

![Autosave Settings](https://cloud.githubusercontent.com/assets/388761/21697838/47338b72-d362-11e6-9106-4a5f476945ca.png)