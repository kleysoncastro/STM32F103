# STM32F103 Designer PCB para MCU stm32f103c8t

#### Na construção de uma pcb, existe basicamente 2 etapas muito importantes "sento muito simplista".
### 1º parte física/mecânica, essa etapa do processo é para simplismte definir qual será a forma fisica da pcb.
- para projetos simples, como: placas para teste, provas de conceito, a etapa 1 é suficiente.
- para projetos mais criteriosos, nessa etapa se define também meteriral de construção, número de faces pontos/furos de fixaçao e etc.


### 2º parte sensível, essa etapa é por onde se começa a construção do layout da pcb, `nao é regra absoluta`. 
  - quando se trata de mcu, umas das partes mais sensíveis é a de `clock`. logo é uma das primeiras a ser desenhada.
    * segundo o [AN2586](https://www.st.com/en/microcontrollers-microprocessors/stm32f103.html#documentation) há um distania física a ser respeitata, capacitores espécificos com suas particularidade de construção bem definidas.
    * Para o stm32f103c8t6 o AN2586 define clock interno e externo os `HSE e LSE `.
 - Parte de alimentação, essa etapa deve ser muito bem projetada, senda causado de ruidos e reset indesejados.
