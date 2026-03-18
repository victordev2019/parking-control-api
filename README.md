# parking-control-api
Tenho algumas dúvidas em relação ao projeto.

A primeira é sobre o formato de data, que não funcionou conforme esperado. Tem uma Vconfiguração global na pasta config, no arquivo DateConfig, mas aparentemente ela não está sendo aplicada corretamente. Gostaria de entender o que pode estar faltando ou se existe alguma etapa adicional para garantir que essa configuração funcione.

Também tenho dúvidas sobre o uso de Optional. Gostaria de compreender melhor em quais cenários ele é mais indicado e se existe alguma boa prática específica para utilizá-lo.

Observei que há regras de negócio implementadas diretamente no controller. O ideal seria centralizar essa lógica na camada de service?
