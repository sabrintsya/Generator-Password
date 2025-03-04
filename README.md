# Password Generator 🔐

## 📌 Overview
Password Generator adalah aplikasi berbasis web yang memungkinkan pengguna untuk membuat password yang kuat secara otomatis dengan panjang yang dapat disesuaikan. Aplikasi ini menggunakan **JavaScript** untuk menghasilkan password acak dan memberikan opsi untuk menyimpannya dalam file teks.

## 🚀 Features
✅ **Generate Password** - Buat password acak dengan kombinasi huruf, angka, dan simbol.
✅ **Customizable Length** - Tentukan panjang password sesuai kebutuhan.
✅ **Save Password** - Simpan password dalam file teks dengan sekali klik.
✅ **Responsive UI** - Dibangun dengan **Bootstrap 5** untuk tampilan yang modern dan responsif.

## 🛠️ Technologies Used
- **HTML5** - Struktur halaman
- **CSS3 & Bootstrap 5** - Styling dan layout responsif
- **JavaScript (ES6)** - Logika password generator

## 🎨 UI Preview
![Password Generator UI](https://via.placeholder.com/800x400?text=Password+Generator+Preview)

## 📂 Project Structure
```
Password-Generator/
├── index.html      # Main HTML file
├── index.js        # JavaScript logic
├── README.md       # Documentation

```

## 🔧 Installation & Usage
1. **Clone Repository**
   ```sh
   git clone https://github.com/sabrintsya/Generator-Password.git
   cd password-generator
   ```
2. **Open `index.html` in Browser**
3. Masukkan panjang password dan klik **Generate Password**
4. Klik **Save Password** untuk menyimpan hasilnya

## 📜 Code Snippet
```js
const generatePassword = (len) => {
  const data = "abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789!@#$%^&*()_+=-{}[]';:/?.,<>~`";
  let generator = '';
  for (let i = 0; i < len; i++) {
    generator += data[Math.floor(Math.random() * data.length)];
  }
  return generator;
};
```

## 📌 Live Demo
🔗 [Try it Online](#)

## 📞 Contact
📧 Email: sabrinatasya170306@gmail.com
🌐 GitHub: [sabrintsya](https://github.com/sabrintsya)

