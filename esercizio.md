| ID                    | Type                                                    | Attributes                         | Index       |
| --------------------- | ------------------------------------------------------- | ---------------------------------- | ----------- |
| ID                    | BIGINT                                                  | AUTO-INCREMENT, NOT-NULL, UNSIGNED | PRIMARY KEY |
| Marca                 | VARCHAR(10)                                             | NOT-NULL                           | INDEX       |
| Modello               | VARCHAR(50)                                             | NOT-NULL                           | INDEX       |
| Anno_immatricolazione | YEAR                                                    | NOT NULL                           |             |
| Cilindrata            | INT(in cc)                                              |                                    |             |
| Alimentazione         | ENUM("benzina", "diesel", "GPL", "ibrida", "elettrica") | NOT NULL                           |             |
| Colore                | VARCHAR(10)                                             |                                    |             |
| Prezzo                | DECIMAL(10, 2)                                          | NOT-NULL                           | INDEX       |
| Cambio                | ENUM("manuale", "automatico")                           | DEFAULT("manuale")                 |             |
