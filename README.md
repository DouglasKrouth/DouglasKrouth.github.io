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

## Articles, resources used
[Add syntax highlighting to your Jekyll site with Rouge](https://bnhr.xyz/2017/03/25/add-syntax-highlighting-to-your-jekyll-site-with-rouge.html)
* To apply *rouge* styling : `rougify style <STYLE_NAME> > /path/to/css/file.css`
* For code syntax highlighting, use 3x tilde<LANGUAGE> 3x tilde format.

## Fun potential additions, ideas
* Add a CI step to auto-update publication/edit dates to posts
* Add a CI step for checking whether the list of categories is "correct" based on some predefined list to avoid accidentally publishing under an incorrect/redundant category
