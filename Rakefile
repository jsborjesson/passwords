SOURCE_FILES = FileList['source/**/*.md']

file 'paper.md' => SOURCE_FILES do |task|
  concatenated = SOURCE_FILES.reduce('') do |result, path|
    result << File.read(path) + "\n"
  end

  File.open('paper.md', 'w') { |file| file.write(concatenated) }
end

task default: 'paper.md'
