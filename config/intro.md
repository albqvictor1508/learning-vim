# Vim Config Intro

### Init.lua

Arquivo principal para configuração do neovim, onde vamo configurar em lua 

  require("config.lazy")
  vim.opt.expandtab = 2 
  vim.opt.shiftwidth = 2 
  vim.opt.softtabstop = 2 
  vim.opt.tabstop = 2

Config inicial do neovim, o require pegando configurações do lazy vim e o resto config é personalizada setando o tamanho de tabs do neovim

- Executando **`source %`** as configs são adicionadas no neovim
