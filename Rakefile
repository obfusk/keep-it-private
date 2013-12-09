desc 'README.md -> index.html'
file 'index.html' => 'README.md' do
  sh 'redcarpet --parse-autolink README.md > index.html'
end

file 'README.md'


# kp  = 'encryption/images/keypair.svg'
# kp_ = 'encryption/images/keypair_.svg'
#
# desc 'keypair_.svg -> keypair.svg'
# file kp => kp_ do
#   sh "sed -r 's!file:.*/(.*\.svg)!images/\\1!g' < #{kp_} > #{kp}"
# end
#
# file kp_
