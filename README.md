# 🍓 Strawberry Perl --- Guia Rápido de Comandos

Strawberry Perl é uma distribuição completa do **Perl para Windows**,
incluindo interpretador, compilador e gerenciador de módulos.

------------------------------------------------------------------------

## 📌 1. Verificar Instalação

Verifica se o Perl está instalado e mostra a versão:

``` bash
perl -v
```

------------------------------------------------------------------------

## 📌 2. Executar um Arquivo Perl

Executa um script salvo com extensão `.pl`:

``` bash
perl arquivo.pl
```

------------------------------------------------------------------------

## 📌 3. Executar Código Diretamente no Terminal

Permite rodar um comando rápido sem criar arquivo:

``` bash
perl -e "print 'Olá mundo\n';"
```

------------------------------------------------------------------------

## 📌 4. Instalar Módulos (CPAN)

Instala bibliotecas adicionais:

``` bash
cpan NomeDoModulo
```

**Exemplo:**

``` bash
cpan DBI
```

------------------------------------------------------------------------

## 📌 5. Listar Módulos Instalados

Mostra os módulos já instalados no sistema:

``` bash
perldoc perllocal
```

# 💻 Programa Exemplo em Perl

Salve o arquivo como:

    exemplo.pl

## Código:

``` perl
#!/usr/bin/perl
use strict;
use warnings;

print "Hello, World!\n";

my $nome = "Eric";
print "Olá, $nome!\n";
```

------------------------------------------------------------------------

## ▶️ Como Executar

No terminal, navegue até a pasta do arquivo e execute:

``` bash
perl exemplo.pl
```

------------------------------------------------------------------------

# ✅ O que o programa faz?

-   Ativa boas práticas com `use strict` e `use warnings`
-   Exibe uma mensagem na tela
-   Declara uma variável
-   Mostra interpolação de variável dentro de string

------------------------------------------------------------------------

📚 **Resumo:**\
O Strawberry Perl permite criar scripts rápidos, automatizar tarefas e
manipular textos com eficiência no Windows.
