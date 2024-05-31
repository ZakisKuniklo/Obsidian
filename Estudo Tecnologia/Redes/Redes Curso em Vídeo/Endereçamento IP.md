IPV4 - 192.168.1.10

###### Classes IP
- A - 0 a 127  -> 2^24
- B - 128 a 191 -> 2^16
- C - 192 a 223 -> 2^8
- D - 224 a 239 -> Multicast
- E - 240 a 255 -> Teste de novas tecnologias


###### IPs Restritos e Privados
10.0.0.0 /8
172.16.0.0/12
192.168.0.0/16

127.0.0.0 -> Auto IP
169.254.0.0 -> Apipa
	Quando o dispositivo não recebe um IP

###### Máscara padrão
- A - 255.0.0.0
- B - 255.255.0.0
- C - 255.255.255.0

###### Dentro da rede ([[Calculo de Sub-redes|Sub-redes]])

| Rede             | Host                                         | [[Tipos de Transmissão\|Broadcast]] |
| ---------------- | -------------------------------------------- | ----------------------------------- |
| Endereço da rede | Endereços dos equipamentos conectados a rede | endereço do broadcast               |
| 192.168.1.0      | 192.168.1.1 *até* 192.168.1.254              | 192.168.1.255                       |
