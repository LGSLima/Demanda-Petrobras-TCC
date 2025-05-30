# Unity Plus

**Projeto de Conclusão de Curso (TCC)  
Curso Técnico em Informática para Internet**

---

## 1. Apresentação

O **Unity Plus** é uma plataforma web desenvolvida como Trabalho de Conclusão de Curso (TCC) para o Curso Técnico em Informática para Internet. Seu objetivo principal é coletar, processar, visualizar e analisar dados socioeconômicos de comunidades locais, promovendo maior engajamento cidadão e fornecendo subsídios para tomada de decisão de gestores públicos e organizações não governamentais.

---

## 2. Justificativa

- **Demanda Social**: Muitas comunidades carecem de informações confiáveis em tempo real sobre indicadores de saúde, educação, infraestrutura e segurança.  
- **Empoderamento**: Ao facilitar a coleta colaborativa de dados, o sistema incentiva a participação ativa dos moradores.  
- **Tomada de Decisão**: Gestores públicos e ONGs passam a dispor de relatórios e gráficos dinâmicos, fundamentando políticas mais efetivas.

---

## 3. Objetivos

### 3.1 Objetivo Geral  
Desenvolver uma plataforma web acessível e responsiva para registro e análise de dados comunitários, adotando boas práticas de usabilidade e acessibilidade.

### 3.2 Objetivos Específicos  
- Implementar formulários dinâmicos para coleta de diferentes categorias de dados.  
- Permitir upload de mídia (imagens, vídeos e áudios) para documentação in loco.  
- Gerar dashboards interativos com gráficos e mapas de calor.  
- Oferecer relatórios automatizados exportáveis (PDF, CSV).  
- Garantir cumprimento das diretrizes de acessibilidade (WCAG 2.1).  
- Validar dados de entrada (máscaras para CPF, telefone, validações de formulário).

---

## 4. Escopo do Projeto

- **Módulo de Coleta de Dados**:  
  - Formulários de prioridades (Urgência, Alta, Média, Baixa).  
  - Classificação de incidentes por categoria (saúde, infraestrutura, meio ambiente etc.).  
- **Módulo de Mídia**:  
  - Upload de imagens, vídeos e áudios, com limite configurável de tamanho.  
- **Módulo de Geolocalização**:  
  - Captura automática da localização do usuário via API do navegador.  
- **Módulo de Análise**:  
  - Dashboards com gráficos interativos (barras, linhas, pizza) e mapas de calor.  
  - Exportação de relatórios.  
- **Módulo de Autenticação**:  
  - Login via CPF (integração Gov.br), Google e LinkedIn.  
- **Acessibilidade**:  
  - Uso de roles e atributos ARIA, contraste adequado, navegação por teclado.

---

## 5. Funcionalidades Principais

1. **Cadastro e Autenticação**  
2. **Formulários de Relato**  
   - Seletor de prioridade e categoria  
   - Campos obrigatórios e validações  
3. **Envio de Mídia**  
   - Pré-visualização e compressão simples no front-end  
4. **Localização**  
   - Botão para obter coordenadas geográficas  
5. **Dashboard Interativo**  
   - Gráficos em tempo real  
   - Filtros por data, categoria e prioridade  
6. **Relatórios**  
   - Download em PDF / CSV  
7. **Fórum de Discussão**  
   - Espaço para trocas entre comunidade, empresa e poder público  

---

## 6. Tecnologias Utilizadas

- **Frontend**  
  - HTML5, CSS3, JavaScript (ES6+)  
  - Bootstrap 5  
  - Chart.js / D3.js  
- **Backend**  
  - Node.js (Express) ou PHP (Laravel)  
  - Banco de Dados relacional (MySQL / PostgreSQL)  
- **APIs e Serviços**  
  - API de autenticação Gov.br  
  - Google OAuth  
  - API de geolocalização do navegador  
- **Ferramentas de Desenvolvimento**  
  - Git / GitHub  
  - Webpack / Vite  
  - ESLint / Prettier  

---

## 7. Instalação e Configuração

1. **Pré-requisitos**  
   - Node.js (versão ≥14.x) ou PHP (versão ≥8.x)  
   - MySQL ou PostgreSQL  
   - Git  
2. **Clonar o repositório**  
   ```
   git clone [TCC - Demanda Petrobras](https://github.com/LGSLima/Demanda-Petrobras-TCC)
   cd Demanda-Petrobras-TCC
   ```

## 8. Acessibilidade

- Conformidade com WCAG 2.1 (nível AA)
- Uso de atributos aria-* em botões e formulários
- Navegação por teclado e foco visível
- Contraste mínimo de 4.5:1 entre texto e fundo
- Labels e placeholders descritivos

## 9. Como Contribuir

1. **Faça um fork deste repositório**
2. **Crie uma branch com sua feature ou correção:**
   ```
   git checkout -b feature/nome-da-feature
   ```
3. **Faça commits pequenos e descritivos:**
   ```
   git checkout -b feature/nome-da-feature
   ```
4. **Sincronize seu fork com o repositório original:**
   ```
   git fetch upstream
   git merge upstream/main
   ```
5. **Abra um Pull Request detalhando as alterações e motivação.**

## 10. Licença

Este projeto está licenciado sob a MIT License.
Consulte o arquivo LICENSE para mais detalhes.

## 11. Autores e Contato

1. Evelyn Duarte - Aluna de Técnico em Informática para Internet - [Github](https://github.com/evelynduarte02) | E-mail: lgslima@proton.me
2. Expedita Nogueira - Aluna de Técnico em Informática para Internet - [Github](https://github.com/ExpeditaNogueira) | E-mail:
3. Igor Lucas - Professor/Orientador - Github - | Email: 
4. Jonnattan Silva - Aluno de Técnico em Informática para Internet - [Github](https://github.com/JonnattanSS) | E-mail:
5. Lucas Goebel - Aluno de Técnico em Informática para Internet - [Github](https://github.com/lgoebel) | E-mail:
6. Luís Lima - Aluno de Técnico em Informática para Internet - [Github](https://github.com/MatheusShuctzo) | E-mail:
7. Matheus Marzagão - Aluno de Técnico em Informática para Internet - [Github](https://github.com/LGSLima) | E-mail:
