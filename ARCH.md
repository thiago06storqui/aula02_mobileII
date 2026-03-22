# ARCH — Preencha após refatoração

## Estrutura final

lib/
  core/
  features/
    todos/
      data/
      domain/
      presentation/

## Fluxo de dependências
UI -> ViewModel -> Repository -> (RemoteDataSource, LocalDataSource)

## Decisões
- Onde ficou a validação?
    ficara dentro de domain com validações expecificas para sua tela.
- Onde ficou o parsing JSON?
    Ficara em Data.
- Como você tratou erros?
    é apresentado apenas uma caixa com erro.
