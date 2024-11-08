# Dev install/local
1. Install [Ruby](https://www.ruby-lang.org/en/documentation/installation/) (I use Ubuntu 22.04)
```bash
sudo apt-get install ruby-full
```
2. Add Jekyll gem
```bash
 gem install bundler jekyll
```
3. Download dependencies
```bash
cd ./DouglasKrouth.github.io
bundle install
```

## Fun potential additions, ideas
* Add a CI step to auto-update publication/edit dates to posts
* Add a CI step for checking whether the list of categories is "correct" based on some predefined list to avoid accidentally publishing under an incorrect/redundant category
