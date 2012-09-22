Edge Rails Playground

git clone git://github.com/johnson/edge_rails_playground.git

bundle install

cp config/database.yml.sample config/database.yml
bundle rake db:setup
bundle rake db:migrate

bundle exec rails s thin