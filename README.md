# Dijkstra Visualizer

**Número da Lista**: Não se aplica<br>
**Conteúdo da Disciplina**: Grafos2<br>

## Alunos
| Matrícula  | Aluno                         |
| ---------- | ----------------------------- |
| 19/0124997 | Amanda Jeniffer Pereira Nobre |
| 15/0129866 | Igor Araujo de Sousa          |

## Sobre 
Esse projeto tem como objetivo demonstrar visualmente o algoritmo de Dijkstra funcionando ao mostrar o menor caminho entre dois pontos, sendo possível criar obstáculos entre eles. 

## Screenshots
![image](https://user-images.githubusercontent.com/44625056/178384635-eac0dd3a-fc19-4ba4-b287-4338c542fd19.png)

![image](https://user-images.githubusercontent.com/44625056/178384715-18dfde68-98df-4bfd-ac80-8dbb9d6585ec.png)

![image](https://user-images.githubusercontent.com/44625056/178384739-f46fe0f5-4887-4bd4-9919-6de2d3137f57.png)

## Instalação 
**Linguagem**: JavaScript<br>
**Framework**: React<br>

## Uso 
Tudo que é necessário para executar esse projeto é ter em sua máquina instalado o [docker](https://docs.docker.com/engine/install/ubuntu/).

Após a intalação é necessário executar os seguintes comandos na raiz desse projeto:

```
docker build -t dijkstra .

```

```
docker run -p 3000:3000 dijkstra

```