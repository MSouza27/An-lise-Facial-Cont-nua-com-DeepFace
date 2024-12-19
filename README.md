# Análise Facial Contínua com DeepFace

## Funcionalidades

- **Streaming facial**: Permite a detecção e análise de rostos em tempo real.
- **Reconhecimento facial**: Identifica rostos com base em um banco de dados.
- **Análise de emoções**: Detecta as emoções predominantes de cada rosto.
- **Cálculo de idade**: Estima a idade dos rostos analisados.

## Tecnologias utilizadas

- **DeepFace**: Biblioteca para reconhecimento facial e análise de emoções.
- **OpenCV**: Para integração com dispositivos de câmera e manipulação de vídeos.

## Configuração

### Dependências

Certifique-se de que as seguintes bibliotecas estejam instaladas:

- `deepface`
- `opencv-python`

Para instalar, execute o comando:

```bash
pip install deepface opencv-python
```

### Banco de dados

O streaming facial utiliza um banco de dados de imagens para reconhecimento e análise. Configure o banco de dados adicionando imagens no formato suportado (ex.: `.jpg`, `.png`).

O caminho para o banco de dados deve ser especificado ao executar o script.

## Uso

1. Clone este repositório:

   ```bash
   [git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio](https://github.com/MSouza27/An-lise-Facial-Cont-nua-com-DeepFace)
   ```

2. Execute o seguinte script para iniciar o streaming:

   ```python
   from deepface import DeepFace
   DeepFace.stream("database")
   ```

   Substitua `"database"` pelo caminho para o banco de dados contendo as imagens a serem analisadas.

3. Visualize os resultados em tempo real na interface de análise.

## Estrutura do projeto

- **`streaming.py`**: Script principal para execução do streaming.
- **Banco de dados**: Diretório contendo imagens para referência e reconhecimento facial.

## Resultados esperados

- **Detecção em tempo real**: Reconhecimento e análise de rostos conectados ao banco de dados.
- **Análise de emoções**: Identifica emoções dominantes de cada rosto detectado.
- **Estatísticas**: Exibe idades estimadas e mapeamento emocional após o processamento.

## Contribuição

Sinta-se à vontade para abrir issues e pull requests para melhorias. Feedbacks são sempre bem-vindos!

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

Desenvolvido por Magno Santos.

