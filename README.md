# nezzixccc

<div align="center">
  <p><i>Hello World in asm?</i></p>

  ```asm
  section .data
      msg db 'Hello, World!', 0Ah
      len equ $ - msg

  section .text
      global _start

  _start:
      mov eax, 4      ; sys_write
      mov ebx, 1      ; stdout
      mov ecx, msg    ; message
      mov edx, len    ; length
      int 80h         ; syscall
      
      mov eax, 1      ; sys_exit
      xor ebx, ebx    ; return 0
      int 80h         ; syscall
  ```
</div>

## Skills

<div align="center">
  <img src="https://img.shields.io/badge/UI%2FUX%20Design-2d333b?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Cross--Platform%20Development-2d333b?style=for-the-badge&logoColor=white" />
</div>

## Technologies

<div align="center">
  <img src="https://img.shields.io/badge/NodeJS-1e4273?style=for-the-badge&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Electron-2b3a55?style=for-the-badge&logo=electron&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-44273c?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLite-3d2e40?style=for-the-badge&logo=sqlite&logoColor=white" />
</div>

## OS & Tools

<div align="center">
  <img src="https://img.shields.io/badge/Windows-2d333b?style=for-the-badge&logo=windows&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-2d333b?style=for-the-badge&logo=linux&logoColor=white" />
</div>

## Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=nezzixccc&show_icons=true&hide_title=true&hide_border=true&bg_color=22272e&text_color=adbac7&icon_color=909dab&title_color=539bf5&ring_color=c96198" alt="GitHub Stats" />
</div>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=nezzixccc&layout=compact&hide_border=true&bg_color=22272e&text_color=adbac7&title_color=539bf5" alt="Top Languages" />
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=nezzixccc&hide_border=true&background=22272E&stroke=539BF5&ring=C96198&fire=DD5C37&currStreakNum=ADBAC7&sideNums=ADBAC7&currStreakLabel=539BF5&sideLabels=539BF5&dates=768390" alt="GitHub Streak" />
</div>

<br>

<div align="center">
  
[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=14&duration=3000&color=539BF5&center=true&vCenter=true&repeat=false&width=435&lines=Thanks+for+visiting!)](https://git.io/typing-svg)

</div>
