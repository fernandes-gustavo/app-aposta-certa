# 🎲 Aposta Certa

Aplicativo Android nativo desenvolvido em **Kotlin** que gera apostas para a Mega Sena com base na quantidade de números desejada pelo usuário (entre 6 e 15).

---

## 💡 Funcionalidades

* **Geração Aleatória Única:**
    * Gera a quantidade exata de números aleatórios no intervalo de 1 a 60.
    * Garante que **não haja repetição**, utilizando a estrutura de dados **`Set` em Kotlin**.
* **Validação de Entrada:**
    * Valida se o número informado está entre 6 e 15.
    * Retorna *feedback* ao usuário via `Toast`.
* **Persistência de Dados:**
    * Utiliza **`SharedPreferences`** para salvar automaticamente a última aposta gerada.
    * Exibe a última aposta na tela ao iniciar o aplicativo.

---

## ⬇️ Baixe para Testar!

Você pode baixar o arquivo APK (Android Package) diretamente e instalar no seu celular.

* **Arquivo APK:** [app-debug.apk](<https://github.com/fernandes-gustavo/app-aposta-certa/releases/download/v1.0.0/app-debug.apk>)
* **Instruções de Instalação:** Lembre-se de permitir a instalação de aplicativos de "fontes desconhecidas" nas configurações do seu celular.
