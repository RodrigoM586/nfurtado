*********************
Gestão de Equipamentos
*********************

Esta secção pretende documentar o processo de gestão de equipamentos e respetiva sala de equipamentos.

Workflow Sala Equipamentos
==============================

Todo o movimento de material na Sala de Equipamentos, deverá seguir o seguinte workflow procedimental, sendo registado através da base de dados.

.. image:: img/Diagrama_SalaEquipamentos.jpeg	


Base de Dados
==============================

A seguinte secção pretende documentar o registo e gestão de equipamentos na base de dados. 

Registo novo equipamento
---------------------------

Para registar um novo equipamento deverá aceder ao separador :guilabel:`Equipamentos`, na base de dados de suporte, e clicar em :guilabel:`Adic. Novo Equip.` sendo necessário o preenchimento do seguinte formulário:

.. image:: img/novoEquipamento.PNG

.. Note:: Os equipamentos são classicados através de dois tipos, ``EMM`` ou ``ESEG``. 

		``EMM``: Equipamentos de Medição e Monitorização.

		``ESEG``: Equipamentos Controlador pela sua afetação.

Movimentação
---------------------------

Qualquer saída ou entrada de um equipamento, na Sala de Equipamentos, deverá ter um registo na base de dados. Para tal, deverá ser preenchida a tabela de ``Atribuições`` do respetivo equipamento, conforme exemplificado na imagem em anexo.

.. image:: img/movimentoEquip.PNG	

.. Note:: A primeira linha corresponde sempre ao último movimento do equipamento. 

			As colunas :guilabel:`Entrada` e :guilabel:`Saída` deverão estar sempre preenchidas, quando o registo daquele movimento está concluído.




