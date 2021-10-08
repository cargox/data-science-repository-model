# data-science-repository-model

Repositório de exemplo demonstrando a estrutura de pastas referência para projetos de ciência de dados.

### Layout de diretório proposto
    .
    ├── 0_funcoes_base                    # Funções que serao utilizadas em vários notebooks (.py ou .r)
    ├── 1_analises                        # Pasta base onde as análises serão organizadas
    |   ├── nome_elucidativo_da_analise    # Pasta dedicada a uma análise especifica (macro)
    |   |    ├── intermediarios             # Pasta onde os arquivos intermediarios origuindos de processamento (exe: *.csv) serão armazenados (não versionar)
    |   |    ├── out                        # Pasta onde artefatos gerados (imagens, modelos, etc) serão armazenados (versionar)
    |   |    ├── relatorios                 # Pasta onde os arquivos necessários para relatórios serão armazenados
    |   ├── nome_elucidativo_de_outra_analise
    |       (...)
    ├── 2_deployment                      # Pasta onde os serão armazenadas os dados e scripts para deployment dos modelos oriundos das analises     
    |   ├── nome_elucidativo_da_analise    # Pasta dedicada a uma análise especifica (macro), contendo os scripts de validação e API
    |   |    ├── dataset_treino_sampled     # Pata para armazenar sample de dataset utilizado no treinamento (para detecção de concept drift em prod)



