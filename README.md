# HeliosSecureBinder

**Versão:** 1.0.0  
**E-mail:** devhansoft@gmail.com  
**Licença:** [MIT]

---

## Descrição

O **Helios Secure Binder** combina dois arquivos em um só, anexando um arquivo criptografado ao final do arquivo base.  
Ele oferece mecanismos avançados de proteção de dados, utilizando técnicas modernas de segurança e criptografia em múltiplas camadas para ocultar arquivos dentro de outros arquivos base.

Com ele, é possível combinar dois arquivos em um único, preservando a integridade do arquivo base, enquanto o arquivo oculto permanece protegido por camadas robustas de criptografia.

### Recursos principais:
- Verificação de integridade  
- Cascading encryption utilizando AES e ChaCha20  
- Autenticação HMAC-SHA256  
- Ofuscação de dados  
- Particionamento de constantes para dificultar engenharia reversa  
- Inserção de bytes aleatórios para mascarar padrões  
- Codificação customizada para reforçar a segurança do conteúdo  

Essas técnicas garantem uma solução confiável para ocultação e proteção de informações sensíveis em diversos cenários.

---

## Como Funciona

### 1. Arquivo Base
É o arquivo visível após a junção.  

**Formatos 100% seguros para uso como base:**
- Imagens: PNG, JPG, JPEG, SVG, TIFF  
- Vídeos: MP4, AVI, MOV, WMV  
- Áudio: MP3, WAV, FLAC  
- Documentos: PDF  

**Atenção:**  
Evite formatos que validam estrutura interna, pois eles serão corrompidos ao receber dados extras, como:
- ZIP, RAR, 7Z, DOCX, XLSX

---

### 2. Arquivo Oculto
É o arquivo que será criptografado e anexado ao final do arquivo base.  
Não há restrição de extensão, ele pode ser de qualquer tipo.

**Exemplos:**
- DOCX, XLSX, PDF, TXT, ZIP, RAR, 7Z, JPG, PNG, MP3...

---

## Aviso de Responsabilidade

- Use senhas fortes com pelo menos 12 caracteres;  
- Combine letras maiúsculas, minúsculas, números e símbolos;  
- Teste a decriptografia logo após a criptografia;  
- Tenha cuidado com envio e armazenamento dos arquivos;  
- Mantenha sempre backups dos arquivos originais;  
- Erros podem ocorrer devido a falhas do sistema;  
- Não nos responsabilizamos por perda ou acesso não autorizado aos seus dados.

> Ao utilizar este programa, você reconhece e aceita os termos descritos acima.

---

## Aviso Legal

Este aplicativo é gratuito e fornecido "no estado em que se encontra" (*"as is"*), sem garantias de qualquer tipo, expressas ou implícitas.  

O desenvolvedor não se responsabiliza por quaisquer danos, perdas de dados ou outros problemas decorrentes do uso deste software.

---

## Licença

Este projeto está licenciado sob a Licença MIT.  
Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
