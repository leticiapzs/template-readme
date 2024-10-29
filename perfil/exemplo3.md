# Seu nome

<h2 align="center">Sobre mim </h2>

```golang
package main

import (
	"fmt"
)

type Bio map[string]string

func main() {
	for k, v := range GetBio() {
		fmt.Printf("%+v: %+v\n", k, v)
	}
}

func GetBio() Bio {
	return Bio{

- ⚡ **Bio:** "Fale um pouco sobre você",
- 🌱 **Atualmente aprendendo:** "Linguagens que você está aprendendo no atual momento",
- 👯 **Buscando colaborar em:** "Insira em quais projetos você gostaria de colaborar e com quais linguagens",
- 🤔 **Preciso de ajuda com:** "Qualquer coisa relacionada ao que estou aprendendo atualmente 😅",
- 💬 **Pergunte-me sobre:** "Insira aqui as linguagens que você domina",
- 📫 **Como me contatar:** "https://github.com/seuusername",
	}
}
```

<h2 align="center">Você pode me achar em: </h2>

<p align="center">

  <a href="https://www.linkedin.com/in/">
    <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white">
  </a>

  <a href="https://www.github.com/">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white">
  </a>  

  <a href="mailto:seuemail@exemplo.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white">
  </a>
</p>