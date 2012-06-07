# Thorfile
require 'active_support/inflector'

class Default < Thor
  include Thor::Actions
  attr_reader :name

  source_root File.expand_path("../templates", __FILE__)

  desc "thing NAME", "Create a new thing"
  def thing(name)
    @name = name
    directory "thing", "."
  end
end