# Website source for [boekhoudkoppelingen.nl](https://boekhoudkoppelingen.nl)

### Setup


Download and Install a Ruby+Devkit version from RubyInstaller Downloads (https://rubyinstaller.org/downloads/). Use default options for installation.
Run the ridk install step on the last stage of the installation wizard. This is needed for installing gems with native extensions. You can find additional information regarding this in the RubyInstaller Documentation
Open a new command prompt window from the start menu, so that changes to the PATH environment variable becomes effective. Install Jekyll and Bundler via: gem install jekyll bundler
Check if Jekyll installed properly: jekyll -v


```bash
gem install jekyll-paginate
gem install jekyll-sitemap
```


### Development
This command will generate the static site in `_site`:

```bash
jekyll serve --watch
```

Open [localhost:4000](http://127.0.0.1:4000/) and simply refresh the page after changing a source file.

### Publish
Just commit & push to the repo.
