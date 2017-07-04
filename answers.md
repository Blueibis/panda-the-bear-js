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
var highlights = document.querySelector('.highlight')
highlights.style.color = "purple"
#6
header.style.fontFamily = "monospace"
#7
var circleIcons = document.querySelectorAll('aside a')
circleIcons.forEach(function(icon) {icon.style.backgroundColor = "cadetblue"})
