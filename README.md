# Redes II - Universidade do Algarve - Néstor Cataño

## Conhecimentos Prévios recomendados

Redes de Computadores I


## Objetivos de aprendizagem (conhecimentos, aptidões e competências)

a. Compreender as diferenças e o funcionamento das arquitecturas de rede
ao nível da camada de aplicação.

b. Compreender o endereçamento de rede no âmbito público e
privado.

c. Compreender o endereçamento IPv6.

d. Compreender os serviços das várias camadas protocolares para a
implementação de redes sem fios.

e. Compreender as características e os principais constrangimentos
da transmissão multimédia.

f. Conhecer as principais vertentes da segurança em redes informáticas, e
identificar as principais vulnerabilidades e tipos de ameaças.

## Metodologias de ensino (avaliação incluída)
Os conteúdos programáticos serão ministrados por exposição teórica tendo como
suporte um conjunto de slides e vídeos, e pela leitura/discussão de alguns
artigos. A compreensão dos conteúdos será consolidada através da realização
de trabalhos práticos que permitem perceber com mais detalhe o funcionamento
dos protocolos subjacentes ao funcionamento das redes.

A avaliação tem duas componentes: **prática** e **teória**. A componente
**prática** é avaliada por **tarefa de casa**, tem incidência nos trabalhos práticos
realizados durante o semestre e vale **40%** da nota final.

A componente **teórica** é avaliada por **exame**, tem incidência na matéria
teórica e vale **60%** da nota final. Para admissão a exame (em qualquer das
épocas previstas) será necessário entregar todos os trabalhos práticos dentro
do prazo, obter a sua validação e obter uma nota mínima >= **8** (sobre
**10**) valores nas **tarefas de casa**.


# Week 1 - introduction to computer networks

1. The four-layer model

2. Overview of packets

3. Overview of network protocols security

	1. CIA (Confidentiality, Integrity, Availability)

	1. Dolev-Yao threat model for network protocols

	2. attacks: package dropping, message forgery, message delay


## Readings

1. K&R (Chapters 1.0-1.8)



# Week 2 - the link (ethernet) Layer


1. The Ethernet protocol

2. MAC addresses

3. Switching

4. Switching security

	1. attacks: poisoning, flooding

## Readings

1. K&R (Chapter 6.1, 6.4.1, 6.4.2)



# Week 3 - the internetwork layer


1. The Internet Protocol (IP)

2. IP addresses

3. Reserved IP addresses

4. IP packet structure

5. Routing

6. IP packet safety and security

	1. Eavesdropping on the Internet

7. ICMP

8. **ping** and **traceroute**


## Readings

1. K&R (Chapters 4.3.1-4.3.3)



# Week 4 - Introduction to Security

1. Basics on security

2. Safety and security in the IP layer

3. NAT and IP addresses

4. Man-in-the-middle (MITM) attacks.


## Readings

1. K&R (Chapters 8.1)



# Week 5 - ARP and DHCP

1. Introduction to ARP and DHCP

2. MAC addressing and ARP

3. DHCE

4. ARP security

5. DHCP security


### Readings

1. K&R (Chapters 4.3.3, 6.4.1, 6.7.1-6.7.2)


# Week 6 - UDP


1. UDP segment

2. UDP protocol

3. UDP security

	1. Reflection attack

	2. Amplification attack


## Readings

1. K&R (Chapters 4.3.3, 6.4.1, 6.7.1-6.7.2)



# Week 7 - DNS


1. DNS introduction

2. DNS record types

3. Recursive name resolutions

4. Traffic filtering

5. Security considerations

	1. DNS poisoning

	2. DNS sinkholing

	3. DNS amplification attacks

## Readings

1. K&R (Chapters 2.4, 6.7.3-6.7.4)



# Week 8 - TCP


1. Transport Control Protocol (TCP)

2. TCP packet

	1. Connection establishing and closing

	2. Sequence numbers

	3. Reliability

	4. IP spoofing

	5. SYN flooding


## Readings

1. K&R (Chapters 3.4-3.4.1, 3.5)


# Week 9 - networking outlook


1. Application layer protocols

2. HTTP 

3. Web sockets 

4. WiFi and WiFi security 

5. Bluetooth 

6. security by locality

7. Mobile internet

8. Long-term security

## Readings

1. K&R (Chapters 7.1,7.3,7.6)



# Week 10 - wireless and mobile networks 

1. Introduction

2. Wireless links 

3. IEE 802.11 wireless LANs

4. Cellular internet access 

5. Mobility: principles of addressing and routing to mobile users

6. Mobile IP

7. Handling mobility in cellular networks 

8. Mobility and higher-layer protocols

## Readings

1. K&R (Chapter 7)



# Week 11 - security

1. Security in Computer Networks

2. Principles of Cryptography 

	1. Symmetric key cryptography

	2. Public key encryption

	3. Message integrity and Digital signatures

			1. Cryptographic hash functions

			2. Message authentication code

			3. Digital signatures

## Readings

1. K&R (Chapters 8.1-8.3) 



# Week 12 - TLS

1. TLS introduction

2. Internet PKI

3. Trust model issues

	1. CA

	2. Certification issuance and maintenance

	3. Certificate revocation

	4. Users

## Readings

1. K&R (Chapters 3.4-3.4.1,3.5,8.6)

2. G&T (Chapters 7.1.2,8.3)

# Week 13 - network defense

1. network defense overview

2. firewalls

3. intrusion-detection systems

4. networking testing

5. zero-trust architecture

## Readings

1. K&R (Chapters 8.9)

2. G&T (Chapters 5-5.4, 6.2, 6.3, intro, 6.3.3, 6.4) 


# Week 14 - Summary

1. Revision

2. Typ exam resolution


# Bibliography

1. Computer Networking: A Top-Down Approach, 7th Edition, by Kurose
   and Ross (K&R).

2. Introduction to Computer Security, 1st Edition, by Goodrich, and
   Tamassia (G&T).


# Inquiries

For any questions or issues contact Néstor Cataño
[nestor.catano@gmail.com](mailto:nestor.catano@gmail.com).
