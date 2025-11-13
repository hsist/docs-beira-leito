[guia_acompanhamento_enfermagem.md](https://github.com/user-attachments/files/23530641/guia_acompanhamento_enfermagem.md)
# SIGS — Acompanhamento Enfermagem (Guia Rápido)

**Endereço de acesso:**  
[http://sigs.hsist.com.br:8081/beira-leito](http://sigs.hsist.com.br:8081/beira-leito)

Este documento descreve como acessar e utilizar o módulo **Acompanhamento Enfermagem** do SIGS via navegador.

---

## 1. Acesso e menu

**Caminho no menu:**

```
Gestão Hospitalar → Acompanhamento Clínico → Internação → Acompanhamento Enfermagem
```

> **Observação:** o usuário precisa ter setores configurados para visualizar pacientes.

---

## 2. Tela 1 — Lista de Pacientes

Exibe pacientes em atendimento (sem alta), filtrados pelos setores associados ao usuário.

- **Configuração de setores do usuário:**  
  *Gestão Hospitalar → Utilidades → Configuração de Usuários → Setores*
- **Atividade do setor:**  
  *Gestão Hospitalar → Arquivos e Tabelas → Setores*  
  O setor deve conter a atividade **51 Enfermagem**.

### Pesquisa

O campo de pesquisa busca em qualquer coluna exibida — nome do paciente, convênio, etc.  
Digite o termo e os resultados serão filtrados.

Para abrir a Tela 2, clique na seta no canto direito da linha do paciente.

---

## 3. Tela 2 — Prescrições de Enfermagem

Mostra prescrições das últimas 24 horas que **não estejam canceladas**.

- **Botão Incluir:**  
  Se o setor estiver parametrizado com *Preencher responsável ao incluir*, o campo *Responsável pela Inclusão* será preenchido automaticamente.  
  Caso contrário, apenas data/hora e usuário serão preenchidos.
- **Botão Sinais Vitais:** abre a Tela 3.
- **Botão Voltar:** retorna à Tela 1.

> **Atenção:** não utilize os botões do navegador (voltar/avançar) para navegar entre telas — use os botões da aplicação.

---

## 4. Tela 3 — Sinais Vitais

Permite a inclusão de sinais vitais.  
A visualização e edição dos sinais existentes devem ser feitas no SIGS (desktop) pelo menu indicado abaixo:

```
Gestão Hospitalar → Acompanhamento Clínico → Internação → Acompanhamento Enfermagem
```

Nenhum campo é obrigatório.  
Ao finalizar, escolha:

- **Salvar** — grava os dados e volta para a Tela 2.  
- **Cancelar** — descarta a inclusão e volta para a Tela 2.

---

## 5. Observações e boas práticas

- Verifique se o usuário tem os setores configurados corretamente antes de abrir o módulo.  
- Use sempre os botões da aplicação para navegar entre telas.  
- Para treinamento, indique ao time que os sinais vitais são inseridos aqui, mas gerenciados/visualizados no sistema principal quando necessário.

---
