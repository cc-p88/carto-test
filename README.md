# Prerequisites
Jekyll requires the following:
- [Ruby][rubyurl] version 2.4.0 or higher (check your Ruby version using `ruby -v`) 
- [RubyGems][rybygemurl] (check your Gems version using `gem -v`)
- [GCC][gccurl] and [Make][makeurl] (check versions using `gcc -v`,`g++ -v`, and `make -v`)

Check [Requirements][reqs] in Jekyll website for further information.  

[rubyurl]: https://www.ruby-lang.org/en/downloads/
[rybygemurl]: https://rubygems.org/pages/download  
[gccurl]: https://gcc.gnu.org/install/  
[makeurl]: https://www.gnu.org/software/make/  
[reqs]: https://jekyllrb.com/docs/installation/#requirements  


# Instructions
1. Install all prerequisites.
2. Install the jekyll and bundler gems.  
`gem install jekyll bundler`  
3. Move to the folder of the site and make it available on a local server.  
`bundle exec jekyll serve`  
4. Browse to http://localhost:4000
