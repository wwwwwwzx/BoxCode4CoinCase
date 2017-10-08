Box names for coin case gliches.  
Note: _ = Space

# Guide
https://www.reddit.com/r/pokemon/comments/4a6abq/guide_getting_any_pokémon_you_want_in_gold_silver/

# Mew
- DA2A97 !/RZ?r   % Dex num to Mew
- DA2C01 !/TZAB   % Move1 to Pound
- DA3059 !/XZza   % TID to 22796
- DA310C !/YZAM
- DB4A86 ./rZ?a   % OT to GF
- DB4B85 ./sZ?] 
- DB4C50 ./tZxZ   % clear trash bytes in OT
- DB4D50 ./uZxZ
- DB4E50 ./vZxZ   
- DB4F50 ./wZxZ
- DB5050 ./xZxZ

If the length of current OT is `N`, do the clear procedure `N - 2` times.

# Shiny for roamers
## Raikou
- DD1FFA é/GZ59
- DD20AA é/HZ9l
## Entei
- DD26FA é/NZ59
- DD27AA é/OZ9l
## Suicune
- DD2DFA é/UZ59
- DD2EAA é/VZ9l

# GameShark
% Write GameShark Code to EVs and IVs first, starting from following addresses
- Slot 2: 0xDA65
- Slot 5: 0xDAF5
- Slot 6: 0xDB25

% Example Codes
- Keep enemy 0 HP: ea 00 d1 c9
- Keep enemy shiny: 3e fa ea f5 d0 3e aa ea f6 d0 c9
- Keep enemy being Celebi: 3e fb ea ed d0 c9
- No wall: 21 a3 ce 22 22 22 22 c9

% You can use the pk2 files given (All legit)  

% direct to slot 2 EVs/IVs  
- FF8A65 _A?ezm
- FF8BDA _A?f!/
- FF89C3 _A?d's♂

% direct to slot 5 EVs/IVs  
- FF8AF5 _A?e09
- FF8BDA _A?f!/
- FF89C3 _A?d's♂ 

% direct to slot 6 EVs/IVs   
- FF8A25 _A?eMZ
- FF8BDB _A?f./
- FF89C3 _A?d's♂

% Turn off
- FF89C9 _A?d'd3

# NTR Client Note (Personal use)
This part has nothing to do with Coin Case Glitch  
Assume process id of `trl` is 0x33
- Modify Slot 2 EVs: Write(0x8A2406C+0xDA35,(0x21,0xa3,0xce,0x22,0x22,0x22,0x22,0xc9),0x33)
- Enable Code: Write(0x8A3C1C5,(0xC3,0x35,0xDA),0x33)
