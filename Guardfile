guard 'sass', :input => 'assets/sass', :output => 'assets/css', :style => :compressed

guard :concat, type: "js", files: %w(respond), input_dir: "assets/js/includes", output: "assets/js/site"

guard 'livereload' do
  watch(%r{.+\.(html|liquid)$})
  watch(%r{styles/sass/.+\.scss})
  watch(%r{js/includes/.+\.js})
end