### Hi there 👋

<!--
**consacs/consacs** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
对于有垃圾回收机制的语言，最初指向一块物理地址的地址（指针）无法被替代，即无法直接将一块物理地址再赋值给其他地址（指针），只能使用二维地址（二维指针）指向该块物理地址的地址，以操作该块物理地址。
以上为个人猜想垃圾回收机制语言对于地址（指针）的使用限制。而不同于C这种没有垃圾回收机制的语言，可以将一块物理地址直接赋值给其他指针使用，只要你记得这块物理地址没用时将其释放掉。
