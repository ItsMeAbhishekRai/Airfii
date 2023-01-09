# Airfii
Ideal tool to automate WiFi attacks (WPA/WPA2 - PSK) aimed at obtaining the password.
The Airfii tool has 2 attack modes. The first of these is the Handshake attack, where in an automated way, everything necessary is managed so that, through a classic attack of de-authentication and reconnection by a station, a valid Handshake is obtained with which to later be able to work to apply force. gross.
The second attack mode is the PKMID ClientLess Attack, which focuses its attention on wireless networks that do not have associated clients (Modern Method).
# How is the tool executed?
The tool has 2 parameters, on the one hand the parameter '-a' to specify the attack mode (Handshake|PKMID) and on the other hand the parameter -n to specify the name of the network card.
In any case, the tool has a help panel after its execution:

┌─[root@parrot]─[/home/Abhi/Desktop/Airfii]
└──╼ #./Airfii.sh 

[*] Uso: ./Airfii.sh

        a) attack mode
                Handshake
                PKMID
        n) Network card name
        h) Show this help panel
        
With these parameters already defined, depending on the selected attack mode... everything necessary will be displayed automatically
