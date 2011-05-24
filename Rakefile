require 'rake'

task :test do
  1.upto(500) do
    sleep(0.01)
    putc '.'
    $stdout.flush
  end
  raise 'Simulate error'
  exit 0
end

task :default => :test
