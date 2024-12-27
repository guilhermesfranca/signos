In english bellow

# Encontrador de Signo Astrológico

Esta aplicação em JavaScript determina o signo astrológico com base na data fornecida. Ela compara a data fornecida com as datas de início e fim definidas para cada signo do zodíaco, retornando o signo correspondente.

## Índice
- [Visão Geral](#visão-geral)
- [Funcionalidades](#funcionalidades)
- [Como Usar](#como-usar)
- [Explicação do Código](#explicação-do-código)
- [Licença](#licença)

## Visão Geral
Este script calcula o signo astrológico para uma data específica, verificando se a data cai dentro do intervalo de datas de início e fim de cada signo. O script inclui uma lógica para lidar com o caso especial de Capricórnio, que atravessa a fronteira do ano (de 22 de dezembro a 19 de janeiro). Ele suporta qualquer data de entrada e determina o signo astrológico apropriado com base nos intervalos de datas definidos.

## Funcionalidades
- **Cálculo de Signo**: A aplicação determina o signo astrológico para qualquer data fornecida.
- **Tratamento Personalizado de Datas**: Lida com o signo de Capricórnio, que vai do final de um ano até o início do próximo.
- **Lógica Comparativa**: Utiliza a lógica de comparação `and`/`or` para identificar corretamente o signo astrológico para datas no final do ano.

## Como Usar
1. **Defina a Data**: Você pode alterar a variável `data_app` para a data que deseja verificar. Exemplo:
   ```js
   let data_app = new Date("2023-02-07"); // Substitua por qualquer data






# Astrological Sign Finder

This JavaScript application determines the astrological sign based on the given date. It compares the provided date with the defined start and end dates of each zodiac sign, returning the corresponding sign.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [How to Use](#how-to-use)
- [Code Explanation](#code-explanation)
- [License](#license)

## Overview
This script calculates the zodiac sign for a specific date by checking if the date falls within a given range of start and end dates for each sign. The script includes a logic for handling the special case of Capricorn, which spans across the year boundary (from December 22 to January 19). It supports any input date and determines the appropriate zodiac sign based on the defined date ranges.

## Features
- **Zodiac Calculation**: The application determines the zodiac sign for any given date.
- **Custom Date Handling**: Handles the Capricorn sign, which spans from the end of one year to the beginning of the next.
- **Comparative Logic**: Uses the `and`/`or` comparison logic to correctly identify the zodiac sign for dates around the year's end.

## How to Use
1. **Set the Date**: You can change the `data_app` variable to the date you want to check. For example:
   ```js
   let data_app = new Date("2023-02-07"); // Replace with any date
