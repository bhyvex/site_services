# Load DSL and set up stages
require 'capistrano/setup'

# Include default deployment tasks
require 'capistrano/deploy'

# Cap3 Unicorn gem
require 'capistrano3/unicorn'

# Bundler support
require 'capistrano/bundler'

# Bring in migration support from cap-rails
require 'capistrano/rails/migrations'

# Load custom tasks from `lib/capistrano/tasks` if you have any defined
Dir.glob('lib/capistrano/tasks/*.rake').each { |r| import r }
