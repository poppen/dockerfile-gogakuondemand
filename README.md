# poppen/gogakuondemand

Dockerfile for gogakuondemand.rb

# How to

    docker run --rm -v $(pwd)/data poppen/gogakuondemand

or

    docker run --rm -v -v pref.rb:/gogaku/pref.rb $(pwd)/data poppen/gogakuondemand

# Build

    docker build -t poppen/gogakuondemand .

# References

* [gogakuondemand.rb](http://d.hatena.ne.jp/riocampos+tech/20130731/p1)
