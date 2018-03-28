FROM localethereum/pyethapp

COPY data/config /root/.config/pyethapp
COPY start.sh /root/
COPY data/log /root/log
EXPOSE 30303
EXPOSE 30303/udp
EXPOSE 8545

ENTRYPOINT ["sh","/root/start.sh"]
