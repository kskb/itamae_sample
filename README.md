# Getting failed（失敗の仕方）

http://www.vagrantbox.es/

この辺からubuntu14.04でvagrant up している状態で動作確認しています。

    $ git clone git@github.com:kskb/itamae_sample.git

    $ cd itamae_sample

    $ bundle install --path vendor/bundle

    $ bundle exec itamae ssh -h <<host_name>> -u vagrant -j nodes/vagrant.json recipe.rb

rbenv入れる辺りで見事に失敗します＼(^o^)／
