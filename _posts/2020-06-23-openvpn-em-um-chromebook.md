---
layout: post
title: OpenVPN em um Chromebook
categories: [tecnologia, chromebook, openvpn]
published: true
---

![OpenVPN no Chromebook](https://4.bp.blogspot.com/-w3658lha2Os/Wh_8xL10KkI/AAAAAAAABQ4/VPYRriMdhbghlc-V0qL5qLG5xI22llg_gCEwYBhgL/s1600/Screenshot%2B2017-11-30%2Bat%2B10.40.06.png)

O suporte a OpenVPN em Chromebooks sempre foi inexplicavelmente péssimo e incompleto. Quem como eu adquiriu um atraído pelo preço, peso leve e longa duração de bateria,porém precisava desta funcionalidade, se deparou com um oceano de problemas e frustração.

As possíveis soluções para este tipo de conexão espalhadas pela web variam entre criações de arquivos ONC que na maioria dos casos é ineficaz por não oferecer várias das funcionalidades comuns a outras gambiarras que atendem raríssimos casos. No final das contas, nada definitivo ou sequer minimamente adequado.

Pois bem! Eis que surge o suporte a Android Apps para nos resgatar! Vários dos modelos de Chromebooks já oferecem suporte a Play Store no *stable* ou *beta channel*. Com esta atualização salvadora de vidas, todos os meus problemas relacionados foram resolvidos instalando um cliente OpenVPN de Android, o [JuiceSSH](https://juicessh.com/) para administrar meus servidores e o [Opera Mini](https://www.opera.com/mobile/) para os poucos serviços web que precisar acessar via VPN. A única limitação, com a qual consigo conviver tranquilamente, é que somente apps de Android acessam as rotas criadas pela VPN deste modo já que todos executam em uma sandbox.

Este texto foi originalmente publicado em um dos meus antigos blogs.