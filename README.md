# Strawberry Perl - Principais Comandos

## Verificar instalação

``` bash
perl -v
```

## Executar um arquivo Perl

``` bash
perl arquivo.pl
```

## Executar código direto no terminal

``` bash
perl -e "print 'Olá mundo\n';"
```

## Instalar módulos (CPAN)

``` bash
cpan NomeDoModulo
```

## Listar módulos instalados

``` bash
perldoc perllocal
```

------------------------------------------------------------------------

# Programa Exemplo em Perl

Salve como `exemplo.pl`:

``` perl
#!/usr/bin/perl
use strict;
use warnings;

print "Hello, World!\n";

my $nome = "Eric";
print "Olá, $nome!\n";
```

Para executar:

``` bash
perl exemplo.pl
```
