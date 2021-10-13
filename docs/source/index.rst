.. BEAM VM Wisdoms documentation master file

Bem-vindo(a), aventureiro(a)!
====================

Esta é uma coleção de artigos de fácil leitura bem como artigos de conteúdo em profundidade
sobre o funcionamento interno da VM, layout de memória, opcodes e etc.
Este projeto é um trabalho em andamento, volte em breve.

Repositório do Github para as páginas em português https://github.com/Pedneri1/beam-wisdoms.git

Repositório do Github com conteúdo original, em inglês https://github.com/kvakvs/beam-wisdoms

Atualizações
``````

*   2019-03-03  Binary match opcodes added to the instruction list
*   2018-12-30  Try/catch opcodes added to the instruction list

Seção ELI5 (Explain Me Like I'm Five / Explique-me como se tivesse cinco)
---------------------------------------

.. toctree::
    :maxdepth: 1

    eli5-vm
    eli5-atoms
    eli5-processes
    eli5-process-heap
    eli5-io
    eli5-tracing
    eli5-bif-nif
    eli5-types
    eli5-etf
    eli5-property-based
    eli5-efficiency
    eli5-efficiency-memory-perf


Seção de conteúdo aprofundado
------------------------

.. toctree::
    :maxdepth: 2

    definitions
    indepth-memory-layout
    indepth-data-sizes
    indepth-heap-layout
    interfacing
    indepth-beam-file
    indepth-beam-instructions
    indepth-io

.. todo::
    More details from ELI5 articles;
    IO and ports;
    Links and monitors;
    ETS?;
    BIFs, traps;
    Process: Exceptions;
    Ext term format

Pequenas coisas que você não teria notado se não estivessem aqui. Relacionado à fonte OTP C

:doc:`otp-c-style-guide`, :doc:`otp-cpp-ramblings`, :doc:`otp-c-refactor-todo`
