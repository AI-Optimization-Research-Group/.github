<div align="center">

# Contributing to AI Optimization Research Group

[🇺🇸 English Version](#-english-version) | [🇹🇷 Türkçe Versiyon](#-türkçe-versiyon)

</div>

---

<a name="english-version"></a>
## 🇺🇸 English Version

First off, thank you for considering contributing to the **AI Optimization Research Group**! We are a community dedicated to optimizing AI systems and democratizing AutoML tools. People like you make this group such a great place to learn, inspire, and create.

### 📍 Table of Contents
1. [Code of Conduct](#code-of-conduct)
2. [How to Contribute](#how-to-contribute)
3. [Development Guidelines](#development-guidelines-automl--ai-specifics)
4. [Pull Request Process](#pull-request-process)

---

### Code of Conduct
By participating in this project, you are expected to uphold our Code of Conduct. We prioritize a harassment-free experience for everyone. Please be respectful and professional in issues and pull requests.

### How to Contribute

#### 🐞 Reporting Bugs
If you find a bug in our optimization algorithms or AutoML pipelines:
1. **Search existing issues** to see if it has already been reported.
2. Open a new issue with a clear title.
3. Include relevant details:
   - OS, Python version, and library versions (PyTorch/TensorFlow etc.).
   - A minimal reproducible code snippet.
   - Stack trace of the error.

#### 💡 Suggesting Enhancements
We welcome ideas for new optimization techniques (pruning, quantization) or AutoML features!
- Open an issue tagged as `enhancement`.
- Describe the feature clearly and why it would benefit the project.
- If possible, reference academic papers or articles supporting the technique.

### Development Guidelines (AutoML & AI Specifics)

To maintain the quality of our research and tools, please follow these standards:

* **Code Style:** We follow [PEP 8](https://www.python.org/dev/peps/pep-0008/) for Python code.
* **Type Hinting:** Please use type hints in function definitions to ensure code clarity.
* **Documentation:** All new functions and classes must have docstrings (Google or NumPy style).
* **Reproducibility:** Since we deal with AI:
    - Ensure random seeds can be fixed.
    - Do not hardcode paths to local datasets.
* **Testing:** Add unit tests for your code. If you are adding a new optimization algorithm, provide a small benchmark script proving it works.

### Pull Request Process

1.  **Fork** the repository and clone it locally.
2.  Create a branch for your edit: `git checkout -b feature/amazing-optimization` or `git checkout -b fix/annoying-bug`.
3.  Make your changes and ensure tests pass.
4.  Commit your changes using **Conventional Commits** format (e.g., `feat: add quantization module`, `fix: resolve gradient explosion`).
5.  Push to your fork and submit a **Pull Request**.
6.  Core members (**Muhammet Özdemir** or **Melek Altun**) will review your PR.

---
[⬆️ Back to Top](#contributing-to-ai-optimization-research-group)

<br><br><br>

---

<a name="türkçe-versiyon"></a>
## 🇹🇷 Türkçe Versiyon

Öncelikle **AI Optimization Research Group**'a katkıda bulunmayı düşündüğünüz için teşekkür ederiz! Yapay zeka sistemlerini optimize etmeye ve AutoML araçlarını geliştirmeye odaklanmış bir topluluğuz. Sizin gibi geliştiriciler ve araştırmacılar sayesinde büyüyoruz.

### 📍 İçindekiler
1. [Davranış Kuralları](#davranış-kuralları)
2. [Nasıl Katkıda Bulunurum?](#nasıl-katkıda-bulunurum)
3. [Geliştirme Standartları](#geliştirme-standartları-automl-ve-ai-özelinde)
4. [Pull Request (Çekme İsteği) Süreci](#pull-request-çekme-isteği-süreci)

---

### Davranış Kuralları
Bu projeye katılarak Davranış Kurallarımıza uymayı kabul etmiş olursunuz. Herkes için saygılı ve profesyonel bir ortam sağlamayı hedefliyoruz. Lütfen yorumlarda ve tartışmalarda yapıcı olmaya özen gösterin.

### Nasıl Katkıda Bulunurum?

#### 🐞 Hata Bildirimi (Bug Report)
Optimizasyon algoritmalarımızda veya AutoML boru hatlarında bir hata fark ederseniz:
1. Önce **mevcut konuları (issues)** arayarak hatanın daha önce bildirilip bildirilmediğini kontrol edin.
2. Anlaşılır bir başlık ile yeni bir "Issue" açın.
3. Şunları eklediğinizden emin olun:
   - İşletim sistemi, Python sürümü ve kütüphane sürümleri (PyTorch/TensorFlow vb.).
   - Hatayı tekrar etmemizi sağlayacak minimal bir kod örneği.
   - Hata mesajının tamamı (Stack trace).

#### 💡 Geliştirme Önerileri
Yeni optimizasyon teknikleri (pruning, quantization vb.) veya AutoML özellikleri için fikirlerinize açığız!
- `enhancement` etiketiyle bir konu (issue) açın.
- Özelliği ve projeye sağlayacağı faydayı net bir şekilde açıklayın.
- Mümkünse ilgili akademik makaleleri veya kaynakları referans gösterin.

### Geliştirme Standartları (AutoML ve AI Özelinde)

Araştırmalarımızın ve araçlarımızın kalitesini korumak için lütfen şu standartlara uyun:

* **Kod Stili:** Python kodu için [PEP 8](https://www.python.org/dev/peps/pep-0008/) standartlarını takip ediyoruz.
* **Tip Belirleme (Type Hinting):** Kodun okunabilirliği için fonksiyonlarda tip ipuçlarını kullanın.
* **Dokümantasyon:** Eklediğiniz tüm fonksiyon ve sınıflar için docstring (Google veya NumPy stili) yazın.
* **Tekrarlanabilirlik:** Yapay zeka ile çalıştığımız için:
    - Rastgelelik içeren işlemlerde `seed` parametresi kullanılabilir olmalıdır.
    - Yerel veri setlerine giden sabit dosya yolları (hardcoded paths) kullanmayın.
* **Test:** Kodunuz için birim testleri (unit tests) ekleyin. Yeni bir algoritma ekliyorsanız, çalıştığını kanıtlayan küçük bir benchmark betiği sağlayın.

### Pull Request (Çekme İsteği) Süreci

1.  Depoyu (Repository) **Fork** edin ve yerel makinenize klonlayın.
2.  Değişikliğiniz için yeni bir dal (branch) oluşturun: `git checkout -b feature/yeni-ozellik` veya `git checkout -b fix/hata-duzeltme`.
3.  Değişikliklerinizi yapın ve testlerin geçtiğinden emin olun.
4.  Commit mesajlarınızı **Conventional Commits** formatında yazın (Örn: `feat: yeni budama algoritması eklendi`, `fix: bellek sızıntısı giderildi`).
5.  Kendi fork'unuza push yapın ve ana depoya bir **Pull Request** gönderin.
6.  Çekirdek üyelerimiz (**Muhammet Özdemir** veya **Melek Altun**) PR'ınızı inceleyecektir.

---
[⬆️ Yukarı Dön](#contributing-to-ai-optimization-research-group)
