## Installing Maelstrom

Homebrew instructions:

```
brew install openjdk graphviz gnuplot

# make sure to symlink if it says to do so
# ==> Caveats
# ==> openjdk
# For the system Java wrappers to find this JDK, symlink it with
#   sudo ln -sfn /opt/homebrew/opt/openjdk/libexec/openjdk.jdk /Library/Java/JavaVirtualMachines/openjdk.jdk
sudo ln -sfn /opt/homebrew/opt/openjdk/libexec/openjdk.jdk /Library/Java/JavaVirtualMachines/openjdk.jdk
```

Running the binary:

```bash
wget https://github.com/jepsen-io/maelstrom/releases/download/v0.2.3/maelstrom.tar.bz2 -O - | tar -xz
```

Then run `maelstrom/maelstrom ...`
