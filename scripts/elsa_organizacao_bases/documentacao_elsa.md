*BASES DE DADOS - ELSA*

em cada pasta referente a uma base há varios documentos, como diferentes formatos
da base de dados referida, além do livro de variáveis corresppondente àquela base,
o dicionário de variáveis da base e o databook de variáveis.

- arquivo .XLSX     - refere-se a arquivos Excel
- arquivo .DTA      - refere-se a arquivos do software Stata
- arquivo .SAV      - refere-se a arquivos do software SPSS
- arquivo .SAS7BDTA - refere-se a arquivos de tipo binário dos software SAS

folder_base __
             |___ databook da base
             |
             |___ dicionário da base
             |
             |___ base de dados (.SAV, .DTA , .SAS7BDTA ou .XLSX)

dicionário ___
             |___ atividade
             |
             |___ variável
             |
             |___ label
             |
             |___ valores

base_dados ____________________
            |idelsa| variaveis| ... 
            |______|__________|
            |______|__________|
            |______|__________|

            * idelsa corresponde ao ID do paciente

            * ao realizar uma extração, a base deve ser ordenada de forma ASCENDENTE com base na COLUNA IDELSA

            * após o ID, cada coluna seguinte corresponde a uma variável

========================================================================    

comandos básicos para abrir base com Python

    - arquivo .DTA      - pd.read_stata()
    - arquivo .SAV      - pd.read_spss()
    - arquivo .SAS7BDTA - pd.read_sas()
    - arquivo .XLSX     - pd.read_excel()
    - arquivo .CSV      - pd.read_csv()

========================================================================

* ONDA 1 - (A)

'   - base completa nova                    | nVariáveis_na_base :        | Atividades:
    - base ancestralidade                   | nVariáveis_na_base : 3      | Atividades: EUR, AFR, AMR 
    - base dieta                            | nVariáveis_na_base : 701    | Atividades: DIE, DER
    - base georeferenciamento               | nVariáveis_na_base : 11     | Atividades: GEO
    - base hemograma                        | nVariáveis_na_base : 25     | Atividades: LAB
    - base laboratório                      | nVariáveis_na_base : 62     | Atividades: LAB
    - base laboratório SI                   | nVariáveis_na_base : 30     | Atividades: LAB
    - base medicamentos uso contínuo        | nVariáveis_na_base : 14376  | Atividades (bases)
    :                                                                                  'base_med_o1_c_pa_150619',
                                                                                       'base_med_o1_c_150619_parte1',
                                                                                       'base_med_o1_c_150619_parte2',
                                                                                       'base_med_o1_c_150619_parte3'
    - base medicamentos uso esporádico      | nVariáveis_na_base : 627    | Atividades: MDG
    - base ocupação                         | nVariáveis_na_base : 3      | Atividades: DER
    - base segregação econômica             | nVariáveis_na_base : 10     | Atividades: GEO
    - base ECG                              | nVariáveis_na_base : 61     | Atividades: ECG
    - base exames complementares            | nVariáveis_na_base : 426    | Atividades: EXA
    - base ultraprocessados                 | nVariáveis_na_base : 6      | Atividades: DER
    - base derivadas - síndrome metabólica  | nVariáveis_na_base : 296    | Atividades: DER



* ONDA 2 - (B)

    - base bioimpedância             | nVariaveis_na_base : 
    - base laboratório               | nVariaveis_na_base :
    - base laboratório SI            | nVariaveis_na_base :
    - base completa                  | nVariaveis_na_base :
    - base hemograma                 | nVariaveis_na_base :
    - base medicamentos classes      | nVariaveis_na_base :
    - base medicamentos concentração | nVariaveis_na_base :
    - base PCR                       | nVariaveis_na_base :
    - base recusa ou óbito           | nVariaveis_na_base :
    - base RETCL                     | nVariaveis_na_base :
    - base derivadas                 | nVariaveis_na_base :


* ONDA 3 - (C)

    - base bioimpedância
    - base derivadas
    - base completa
    - base hemograma
    - base laboratório
    - base medicamentos
    - base ultraprocessados
    - base derivadas da dieta
    - base ECG CL
    - base IMT


* ONDA 4 - (D) em construção ainda 

    - base elsa 04 - maio de 2024


* MULTÍPLAS ONDAS

    - base datas - onda 01 e 02
    - base derivadas de diabetes - onda 01 e 02
    - base IVAN - onda 01 e 02
    - base variável perdas - onda 01 e 02
    - base variável perdas - onda 01 e 03
    - base derivada DCV autorreferida - onda 02 e 03
    - base CAC - onda 01, 02 e 03


* BASES AVULSAS

    - base autoavaliação de saúde - abril 2021
    - base elsa covid - junho 2021
    - base obitos - até abril 2021
    - base variáveis VFC 5min
