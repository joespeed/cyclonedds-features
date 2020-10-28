# cyclonedds-features

| Standard                              | Conformance Point                                               | Conformance Reference            |                           |
|---------------------------------------|-----------------------------------------------------------------|----------------------------------|---------------------------|
| **DDS (1.4)**                             |                                                                 |                                  |                           |
| Minimum Profile                       |                                                                 | Annex A                          | ---                       |
|   --- Qos Support:                    |                                                                 | Section 2.2.3                    | ---                       |
|                                       | *USER_DATA, TOPIC_DATA, GROUP_DATA                              | Section 2.2.3.1,2.2.3.2, 2.2.3.3 |                           |
|                                       | *DURABILITY                                                     | Section 2.2.3.4                  | Volatile, Transient Local |
|                                       | *PRESENTATION                                                   | Section 2.2.3.6                  |                           |
|                                       | *DEADLINE, LATENCY_BUDGET                                       | Section 2.2.3.7, 2.2.3.8         | feature implemented       |
|                                       | *OWNERSHIP, OWNERSHIP_STRENGHT                                  | Section 2.2.3.9, 2.2.3.10        | feature implemented       |
|                                       | *LIVELINESS                                                     | Section 2.2.3.11                 | feature implemented       |
|                                       | *TIME_BASED_FILTER                                              | Section 2.2.3.12                 | feature implemented       |
|                                       | *PARTITION                                                      | Section 2.2.3.13                 | feature implemented       |
|                                       | *RELIABILITY                                                    | Section 2.2.3.14                 | feature implemented       |
|                                       | *TRASPORT_PRIORITY                                              | Section 2.2.3.15                 | feature implemented       |
|                                       | *LIFESPAN                                                       | Section 2.2.3.16                 | feature implemented       |
|                                       | *DESTINATION_ORDER                                              | Section 2.2.3.17                 | feature implemented       |
|                                       | *HISTORY, RESOURCE_LIMITS                                       | Section 2.2.3.18, 2.2.3.19       | feature implemented       |
|                                       | *ENTITY_FACTORY                                                 | Section 2.2.3.20                 | feature implemented       |
|                                       | *WRITER_DATA_LIFECYCLE, READER_DATA_LIFECYCLE                   |                                  | feature implemented       |
| --- Conditions                        |                                                                 |                                  | ---                       |
|                                       | *GuardCondition                                                 | Section 2.2.2.1.8                | feature implemented       |
|                                       | *StatusCondition                                                | Section 2.2.2.1.8                | feature implemented       |
|                                       | *ReadCondition                                                  | Section 2.2.2.5.8                | feature implemented       |
| -- Data Access                        |                                                                 |                                  | ---                       |
|                                       | *read, take                                                     |                                  | feature implemented       |
|                                       | *read_instance, take_instance                                   |                                  | feature implemented       |
|                                       | *read_next_sample, take_next_sample                             |                                  | feature implemented       |
|                                       | *read_next_instance, take_next_instance                         |                                  | feature implemented       |
|                                       | *read_w_condition, take_w_condition                             |                                  | feature implemented       |
|                                       | *read_next_instance_w_condition, take_next_instance_w_condition |                                  | feature implemented       |
| Content-Subscription Profile          |                                                                 | Annex A                          | ---                       |
| --- Conditions                        | *QueryCondition                                                 |                                  |                           |
| --- Data Access                       | * create_query_condition                                        | Section 2.2.2.5.9                |                           |
| Persistence Profile                   |                                                                 | Annex A                          | ---                       |
| --- Qos Support                       | * DURABILITY, DURABILITY_SERVICE                                | Section 2.2.3.4, 2.2.3.5         |                           |
| Ownership Profile                     |                                                                 | Annex A                          | feature implemented       |
|   ----- Qos Support:                  | OWNERSHIP, OWNERSHIP_STRENGHT                                   | Section 2.2.3.9, 2.2.3.10        | feature implemented       |
| Group Access Profile                  |                                                                 | Annex A                          | ---                       |
| --- Qos Support                       | *PRESENTATION                                                   | Section 2.2.3.6                  |                           |
| --- Conditions                        | * QueryCondition                                                |                                  |                           |
| --- Data Access                       | * create_query_condition                                        |                                  |                           |
| **DDS-SECURITY (1.1)**                    |                                                                 |                                  |                           |
| Builtin plugin                        |                                                                 | Section 2.2                      | feature implemented       |
| * RSA 2048                            |                                                                 | Section 9.3, 9.4                 | feature implemented       |
| * ECDSA 256                           |                                                                 | Section 9.3, 9.4                 | feature implemented       |
| * Auth URI file                       |                                                                 | Section 9.3.1                    | feature implemented       |
| * Auth URI data                       |                                                                 | Section 9.3.1                    | feature implemented       |
| * Auth URI pkcs11                     |                                                                 | Section 9.3.1                    | feature implemented       |
| * Auth CRL / OCSP                     |                                                                 | Section 9.3.3                    | feature implemented       |
| * Crypto AES 128                      |                                                                 | Section 9.5                      | feature implemented       |
| * Crypto AES 256                      |                                                                 | Section 9.5                      | feature implemented       |
| Plugin framework                      |                                                                 | Section 2.3                      | feature implemented       |
| Plugin language APIs                  |                                                                 | Section 2.4                      | feature implemented       |
| * C Plugin APIs                       |                                                                 | Section 10.3                     | feature implemented       |
| * C++ classic Plugin APIs             |                                                                 | Section 10.4                     | feature implemented       |
| * Java classic Plugin APIs            |                                                                 | Section 10.5                     | feature implemented       |
| * C++11 Plugin APIs                   |                                                                 | Section 10.6                     | feature implemented       |
| * Java5+ Plugin APIs                  |                                                                 | Section 10.7                     | feature implemented       |
| Logging and Tagging                   |                                                                 | Section 2.5                      | feature implemented       |
| * Logging Plugin                      |                                                                 | Section 8.6, 9.6                 | feature implemented       |
| * Data Tagging                        |                                                                 | Section 8.7                      | feature implemented       |
| C (from IDL for C mapping)            |                                                                 |                                  |                           |
| DCPS Programming API                  |                                                                 |                                  | feature implemented       |
| IDL mapping                           |                                                                 |                                  | feature implemented       |
| **DDS-PSM-Cxx (1.0)**                     |                                                                 |                                  |                           |
| DCPS Programming API                  |                                                                 |                                  | feature implemented       |
| IDL mapping                           |                                                                 |                                  | feature implemented       |
| **DDS-DLRL (1.4)**                        |                                                                 |                                  |                           |
| **DDSI-RTPS (2.3)**                       |                                                                 |                                  |                           |
| Large Data Support                    |                                                                 | Section 8.4.14.1                 | feature implemented       |
| Writer-side content filtering support |                                                                 | Section 8.2.9.1                  | feature implemented       |
| Group Order Access support            |                                                                 | Section 8.7.5                    |                           |
| Coherent Set support                  |                                                                 | Section 8.7.6                    | feature implemented       |
| **DDS-XTYPES (1.3)**                      |                                                                 |                                  |                           |
| Minimal Conformance                   |                                                                 | Section 2                        | feature implemented       |
| Basic Conformance                     |                                                                 | Section 2                        | feature implemented       |
| Complete Conformance                  |                                                                 | Section 2                        | feature implemented       |
| Programming Interface                 |                                                                 | Section 2.1                      | feature implemented       |
| Plain Language Binding                |                                                                 | Section 7.5.1                    | feature implemented       |
| Dynamic Language Binding              |                                                                 | Section 7.5.2                    |                           |
| Minimal Network Interoperability      |                                                                 | Section 2.2.1                    | feature implemented       |
| Basic Network Interoperability        |                                                                 | Section 2.2.2                    | feature implemented       |
| XTYPES 1.1 Interoperability           |                                                                 | Section 2.3                      | feature implemented       |
| XML Data Representation               |                                                                 | Section 2.4                      | feature implemented       |
| **IDL (4.2)**                             |                                                                 |                                  |                           |
| Core Data Types                       |                                                                 | Section 7.4.1                    | feature implemented       |
| Any                                   |                                                                 | Section 7.4.2                    |                           |
| Extended Data Types                   |                                                                 | Section 7.4.13                   | feature implemented       |
| Anonymous Types                       |                                                                 | Section 7.4.14                   |                           |
| Interfaces - Basic                    |                                                                 | Section 7.4.3                    |                           |
| Annotations                           |                                                                 | Section 7.4.15                   | feature implemented       |
| * General Purpose Group               |                                                                 | Section 8.3.1                    |                           |
| * Data Modeling Group                 |                                                                 | Section 8.3.2                    |                           |
| * Units and Ranges Group              |                                                                 | Section 8.3.3                    |                           |
| * Data Implementation Group           |                                                                 | Section 8.3.4                    |                           |
| * Code Generation Group               |                                                                 | Section 8.3.5                    |                           |
| * Interfaces Group                    |                                                                 | Section 8.3.6                    |                           |
| Plain DDS Profile                     |                                                                 | Section 9.3.1                    | feature implemented       |
| Extensible DDS Profile                |                                                                 | Section 9.3.2                    | feature implemented       |
| RPC over DDS Profile                  |                                                                 | Section 9.3.3                    |                           |
