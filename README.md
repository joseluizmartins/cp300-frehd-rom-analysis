# cp300-frehd-rom-patch

Documentação técnica e observacional do patch de ROM do **FreHD** para o **CP-300**.

Este repositório contém documentação técnica sobre o patch de ROM que permite o uso do dispositivo FreHD no microcomputador CP-300.

O CP-300 foi originalmente projetado para operar exclusivamente com armazenamento em fita cassete e não possuía qualquer suporte nativo a disco, BIOS de armazenamento ou sistema operacional residente em mídia removível. O patch de ROM documentado aqui introduz um novo fluxo de inicialização e um subsistema de acesso a armazenamento em bloco, tornando possível a utilização do FreHD nesse ambiente.

A documentação apresentada neste repositório foi construída a partir de **observação prática, testes diretos e engenharia reversa**, sem acesso à documentação técnica original do autor do patch. Por esse motivo, o conteúdo adota uma postura descritiva e cautelosa, limitando-se ao que pode ser tecnicamente verificado.

## Escopo do repositório

Este repositório tem como objetivo:

- Documentar o funcionamento observado do patch de ROM do FreHD no CP-300
- Registrar o comportamento do processo de inicialização e acesso ao armazenamento
- Preservar tecnicamente um trabalho relevante para a história da computação nacional
- Servir como base para estudos futuros e análises mais aprofundadas

Este repositório **não tem como objetivo**:

- Reconstituir intenções ou decisões de projeto do autor original
- Fornecer um guia de instalação passo a passo
- Afirmar compatibilidade total com sistemas operacionais específicos sem validação técnica

## Conteúdo

A documentação principal encontra-se em:

- `frehd-cp300-rom-patch.md` — Documento técnico detalhando o funcionamento observado do patch

Outros arquivos poderão ser adicionados no futuro para complementar a análise, como estudos de mapa de memória, engenharia reversa detalhada da ROM ou validações de compatibilidade de software.

## Nota de reconhecimento

O patch de ROM aqui documentado foi desenvolvido por **Fábio Belavenuto**, que infelizmente faleceu e não deixou documentação técnica pública sobre seu funcionamento interno.

Este repositório existe com o propósito exclusivo de **preservação, estudo e continuidade técnica**, respeitando o trabalho original e evitando qualquer tipo de apropriação ou reinterpretação autoral.

## Status

A documentação encontra-se em **estado descritivo**, refletindo o nível atual de conhecimento obtido por meio de observação e análise prática. Pontos ainda não verificados ou dependentes de investigação adicional são explicitamente indicados nos documentos.

Contribuições técnicas, correções e informações adicionais são bem-vindas, desde que mantenham o mesmo rigor técnico e postura respeitosa adotados neste repositório.
