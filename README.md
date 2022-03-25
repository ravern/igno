# Igno

Generate gitignore files with ease.

Igno uses the gitignore templates found on [this repository](https://github.com/toptal/gitignore).

## Installation

You need to have [Cargo](https://doc.rust-lang.org/cargo/getting-started/installation.html) installed. Run the following command to install Igno.

```bash
cargo install igno
```

## Usage

You can use Igno to generate .gitignore files.

```bash
igno generate macOS Rust > .gitignore
```

To search for the exact keywords to use, run the `search` command with your search query.

```bash
igno search No                       
JupyterNotebooks
MonoDevelop
Nanoc
Node
NodeChakraTimeTravelDebug
Nohup
NotepadPP
Synology
SynopsysVCS
nova
now
```
