### Customize Music player

## Task:

# Html,css,js

# task:

# 1. Render songs

-> Get elements
-> Render songs

# 2. Scroll

-> Scroll -> hidden thumb cd
-> Get opacity -

# 3. Play / pause / update tiem progress

-> Tính thời gian: (currentTime / duration ) \* 100
-> xử lý sự kiện tua thanh progress
-> Use Methods: pause / play audio DOM js
-> Use Methods: timeupdate() -> Kích hoạt khi vị trí phát lại hiện tại đã thay đổi
-> Use Methods: currentTime() -> trả về thời gian tính bằng giây (s)
-> Use Methods: duration() ->Trả về độ dài của âm thanh/video hiện tại (tính bằng giây)

# 4. Rotate CD

-> Get animate in js (animate API)
-> Khi stop rotate cd -> stop ở đâu thì phải dừng đúng đoạn music đang phát
-> khi start apps -> default: pause()

# 5. Next song / Prev song

-> Xử lý sự kiện click vào button next -> render bài hát trong list songs
-> Xử lý sự kiện click vào button prev -> render bài hát trong list songs

# 6. Random song

-> Random ngẫu nhiên bài phải khác bài đang active

# 7. Next / Repeat when ended

-> Khi click repeat -> repeat bài hát trong list

# 8. Active song

-> bổ sung css active
-> Khi next thì active

# 9. Scroll active song to view

-> add scrollIntoView()

# 10. Play when user clicks

-> add class "active"
-> sử dụng HTML DOM Element closest() Method

# Task Expend

# 11. Input search list music

# 12. On / off mute music

# 13. Show list music when user clicks add music

# 14. Custom dark mode theme

# 15. Import / export modules music

# 16. LocalStorage

### Research

# animate api

-> https://developer.mozilla.org/en-US/docs/Web/API/Web_Animations_API

# box-shadow

-> https://getcssscan.com/css-box-shadow-examples

# methods for audio

-> https://www.w3schools.com/tags/ref_av_dom.asp

# scroll into view

-> https://developer.mozilla.org/en-US/docs/Web/API/Element/scrollIntoView

# HTML DOM Element closest() Method

-> https://www.w3schools.com/jsref/met_element_closest.asp

# Gradien

-> https://cssgradient.io/gradient-backgrounds/
