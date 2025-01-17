# Setoolkit (Social Engineer Toolkit)

O **Setoolkit** é uma ferramenta versátil usada para Coleta de Informações, oferecendo uma ampla gama de recursos voltados para ataques de engenharia social, testes de penetração (Fast-Track) e módulos de diversas ferramentas. Entre as funcionalidades, destacam-se:
- Ataques de Spear-Phishing
- Comprometimento de websites
- Criação de mídia maliciosa
- Geração de payloads e listeners
- Ataques de e-mail em massa
- Exploits com Arduino
- Ataques a redes sem fio
- Criação de QR Codes maliciosos
- Ataques baseados em PowerShell  

## Website Cloner

O módulo **Website Cloner** permite capturar informações inseridas em formulários de sites falsos, replicando o layout de páginas legítimas. No exemplo a seguir, foi clonada a página de login do Facebook.  
**Nota:** Insira o número da opção no programa seguido de `Enter` para navegar. Use "99" para voltar ou cancelar.

No teste abaixo, foi usado:  
- E-mail fictício: `teste123@gmail.com`  
- Senha fictícia: `123teste`

### Passo a Passo:
1. Como root no terminal digite **setoolkit**.
2. Opção (1) **Social-Engineering Attacks**.
3. Opção (2) **Website Attack Vectors**.
4. Opção (3) **Credential Harvester Attack Method**.
5. Opção (2) **Site Cloner**.
6. Insira a URL do site que deseja clonar (ex.: `https://github.com/login`).
7. Localmente, acesse pelo navegador o **IP do dispositivo na porta 80** para visualizar o site clonado:  
   Exemplo: `http://localhost:80`.

---

### Dicas Adicionais
- Certifique-se de configurar corretamente o ambiente de rede antes de executar.
- Use o módulo exclusivamente para **testes de segurança autorizados**.

