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
#12
var submit = document.querySelector('input[type="submit"]')
submit.value = "En Garde!"
#13
submit.disabled = true
#14
var profileInfo = document.querySelectorAll('.bio-info-value')
profileInfo.forEach(field) {field.innerText = ""})
#Part 2 - Removing elements from the DOM
var fake = document.querySelector('#time-travel')
fake.parentElement.remove()
#Part 3 - Adding elements to the DOM
#1
var portfolio-container = document.querySelector('.portfolio-container')
var pikachu = document.querySelector('#right-image img')
portfolio-container.appendChild(pikachu.cloneNode())
#2
for (var index = 10; index > 0; index--) {
    portfolio-container.appendChild(pikachu.cloneNode())
  }
#3
var listItem = document.createElement('li')
var leftSpan = document.createElement('span')
var rightSpan = document.createElement('span')
var lastUpdated = document.createTextNode('Page last updated on')
var dateText = document.createTextNode(Date())
var list = document.querySelector('.bio-info')

leftSpan.appendChild(lastUpdated)
rightSpan.appendChild(dateText)
listItem.appendChild(leftSpan)
list.appendChild(listItem)
listItem.appendChild(rightSpan)

listItem.className = "bio-info-item"
leftSpan.className = "bio-info-title"
rightSpan.className = "bio-info-value bio-info-last-updated"
