#1
var profile = document.querySelector('.profile-image')
=> undefined

profile
=> <img src=​"images/​self-portrait-grassbg.jpg" alt=​"Self Portrait" title=​"Self Portrait" class=​"profile-image">​

profile.src = 'images/self-portrait-snowbg.jpg'
=> "images/self-portrait-snowbg.jpg"
#2
var header = document.querySelector('h1')
header.innerText = "Jennie Li"
#3
var employment = document.querySelector('#employment .info-title')
employment.innerText = "Something Else"
#4
var body = document.body
body.style.backgroundColor = "Chartreuse"
#5
var highlights = document.querySelectorAll('.highlight')
highlights.forEach(function(item) {item.style.color = "purple"})
#6
header.style.fontFamily = "monospace"
#7
var circleIcons = document.querySelectorAll('aside a')
circleIcons.forEach(function(icon) {icon.style.backgroundColor = "cadetblue"})
#8
var nameField = document.querySelector('input[name="name"]')
nameField.placeholder = "Identify Youself"
#9
var messageField = document.querySelector('textarea[name="message"]')
messageField.placeholder = State you business"
#10
nameField.value = "Your nemesis"
#11
var emailField = document.querySelector('input[name="email"]')
emailField.value = "koalathebear@gmail.com"
