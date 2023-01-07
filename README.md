### Hi there 👋
section .data
  msg db "Hello World"

section .text
  global_start

_start:
	mov rax, 1
	mov rdi, 1
	mov rsi, msg
	mov rdx, 12
	syscall
	mov rax, 60
	mov rdi, 0
	syscall
<!--
**rootiris/rootiris** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
