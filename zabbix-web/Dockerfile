FROM zabbix/zabbix-web-nginx-mysql:ubuntu-3.2-latest
RUN apt-get update -y && apt-get install -y fonts-ipafont
RUN ln -s /usr/share/fonts/opentype/ipafont-gothic/ipagp.ttf /usr/share/zabbix/fonts/ipagp.ttf
RUN sed -i -e 's/graphfont/ipagp/g' /usr/share/zabbix/include/defines.inc.php