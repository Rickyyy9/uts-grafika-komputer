# UTS Grafika Komputer — OpenGL

Kumpulan materi belajar & latihan untuk UTS mata kuliah **Grafika Komputer** (OpenGL, GLSL, Buffer, Texture).

## 📂 Isi

| File | Deskripsi |
|------|-----------|
| [`rangkuman-materi.html`](rangkuman-materi.html) | Slide rangkuman materi (37 slide) — konsep, pipeline, dan implementasi OpenGL dengan diagram + Chart.js |
| [`latihan-soal-uts.html`](latihan-soal-uts.html) | 72 latihan soal interaktif — pilihan ganda, benar/salah, dan esai (dengan kolom jawaban + penilaian mandiri) |

## 🚀 Cara Pakai

Cukup buka file `.html` di browser (tidak perlu instalasi):

- **Rangkuman**: navigasi dengan `←` `→`, klik, atau `Home`/`End`
- **Latihan soal**:
  - Pilihan ganda & benar/salah → skor otomatis
  - Esai → tulis jawaban di kolom, klik **Lihat Kunci Jawaban**, lalu **nilai sendiri** (Benar/Salah)
  - Jawaban esai **tersimpan otomatis** di browser (localStorage)
  - Filter: Semua / Pilihan Ganda / Benar-Salah / Isian
  - Tombol **Reset** untuk mengulang

## 📚 Topik yang Dicakup

1. OpenGL Dasar & Komponen (GLFW, GLAD, GLSL, context)
2. Koordinat & Viewport (NDC, tangan kanan, `glViewport`)
3. Graphics Pipeline (7 tahap)
4. Vertex, VBO, VAO, EBO
5. `glDrawArrays` vs `glDrawElements`
6. Rectangle & Index
7. Struktur Array Vertex (stride, offset, location)
8. Shader & GLSL (`in`/`out`, `gl_Position`, `FragColor`)
9. Compile & Link Shader
10. Uniform
11. ShaderManager
12–16. Texture (UV mapping, wrapping, filtering, mipmap, stb_image)
17–18. Fungsi wajib & pasangan yang sering tertukar
20. Urutan wajib ingat (hafalan kilat)

## 📖 Sumber

- [learnopengl.com](https://learnopengl.com/)
- [khronos.org/opengl](https://www.khronos.org/opengl/wiki)
- [antongerdelan.net/opengl](https://antongerdelan.net/opengl/vertexbuffers.html)
- V. Scott Gordon & John Clevenger (2019), *Computer Graphics Programming in OpenGL with C++*
- Rankumar Narayanan, *Demystifying Augmented Reality*
