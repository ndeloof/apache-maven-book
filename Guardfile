require 'asciidoctor'
require 'erb'

guard 'shell' do
  watch(/^(.*)\.adoc$/) {|m|
    Asciidoctor.render_file(m[0], :in_place => true)
  }
end
