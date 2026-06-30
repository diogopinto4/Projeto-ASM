# Projeto ASM — Assistente Universitário Multiagente

Projeto em grupo desenvolvido para a unidade curricular de **Agentes e Sistemas Multiagente**, do perfil de especialização **Sistemas Inteligentes** (Mestrado em Engenharia Informática, Universidade do Minho).

## Descrição

Sistema multiagente que funciona como um assistente universitário conversacional. Um agente assistente interpreta os pedidos do utilizador, com apoio de um LLM, e encaminha-os para agentes especializados que respondem sobre informação académica, horários, finanças e regulamentos.

## Agentes

- **Assistente** — orquestra a conversa e encaminha as intenções do utilizador.
- **Académico** — cursos, disciplinas e estudantes.
- **Horários** — horários e salas.
- **Financeiro** — informação financeira.
- **Regulamentos** — consulta de regulamentos.
- **User** — interface com o utilizador.

## Tecnologias

`Python` · `SPADE` · `XMPP (Openfire)` · `Ollama (LLM)` · `Docker` · `jsonpickle`

## Como correr

1. Cria e ativa um ambiente virtual Python.
2. Instala as dependências: `pip install -r requirements.txt`.
3. Corre `sh run.sh` para arrancar o Openfire e o Ollama (via Docker) e iniciar os agentes.
4. Na primeira utilização, configura o Openfire em `localhost:9090`.
