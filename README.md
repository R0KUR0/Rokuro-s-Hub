
--[[
AztupBrew(Fork of IronBrew2): obfuscation; Version 2.7.2
]]
return(function(IlllIlllIlIlII,lIlIIIIIIIIl,lIlIIIIIIIIl)local llIlllllIlIIlIIIIll=string.char;local lIlIIllIlIIIlIllIlIIIII=string.sub;local lIllIlIIlllIIIlllllIlIl=table.concat;local lIIIIIlIIlIIIIlIlII=math.ldexp;local llIIIIIlI=getfenv or function()return _ENV end;local IlIIlIll=select;local llIlIlllIIIlIIIIlIll=unpack or table.unpack;local IlllllllIlIll=tonumber;local function IllIllIIll(IIlIlllIIIIlIlIIl)local llIlIllIIllllIIIlIIIIIlII,llllllllllIIIIlllIIll,llIlIlllIIIlIIIIlIll="","",{}local llIlIIlIlIIIlIl=256;local IIIlIlIllllllll={}for lIlIIIIIIIIl=0,llIlIIlIlIIIlIl-1 do IIIlIlIllllllll[lIlIIIIIIIIl]=llIlllllIlIIlIIIIll(lIlIIIIIIIIl)end;local lIlIIIIIIIIl=1;local function IlllIlllIlIlII()local llIlIllIIllllIIIlIIIIIlII=IlllllllIlIll(lIlIIllIlIIIlIllIlIIIII(IIlIlllIIIIlIlIIl,lIlIIIIIIIIl,lIlIIIIIIIIl),36)lIlIIIIIIIIl=lIlIIIIIIIIl+1;local llllllllllIIIIlllIIll=IlllllllIlIll(lIlIIllIlIIIlIllIlIIIII(IIlIlllIIIIlIlIIl,lIlIIIIIIIIl,lIlIIIIIIIIl+llIlIllIIllllIIIlIIIIIlII-1),36)lIlIIIIIIIIl=lIlIIIIIIIIl+llIlIllIIllllIIIlIIIIIlII;return llllllllllIIIIlllIIll end;llIlIllIIllllIIIlIIIIIlII=llIlllllIlIIlIIIIll(IlllIlllIlIlII())llIlIlllIIIlIIIIlIll[1]=llIlIllIIllllIIIlIIIIIlII;while lIlIIIIIIIIl<#IIlIlllIIIIlIlIIl do local lIlIIIIIIIIl=IlllIlllIlIlII()if IIIlIlIllllllll[lIlIIIIIIIIl]then llllllllllIIIIlllIIll=IIIlIlIllllllll[lIlIIIIIIIIl]else llllllllllIIIIlllIIll=llIlIllIIllllIIIlIIIIIlII..lIlIIllIlIIIlIllIlIIIII(llIlIllIIllllIIIlIIIIIlII,1,1)end;IIIlIlIllllllll[llIlIIlIlIIIlIl]=llIlIllIIllllIIIlIIIIIlII..lIlIIllIlIIIlIllIlIIIII(llllllllllIIIIlllIIll,1,1)llIlIlllIIIlIIIIlIll[#llIlIlllIIIlIIIIlIll+1],llIlIllIIllllIIIlIIIIIlII,llIlIIlIlIIIlIl=llllllllllIIIIlllIIll,llllllllllIIIIlllIIll,llIlIIlIlIIIlIl+1 end;return table.concat(llIlIlllIIIlIIIIlIll)end;local IlllllllIlIll=IllIllIIll('25524U27524S24K27524U25E25D25R25M26526226425J25C25L24S24Q27925L25R25F25N24S24P27926E26226226626H25N26224S23Z27925I27W26626524423L23L26625R27F25N25O27I23K25P25D25F23L26425R26123L26G26526C25R25H24826N26Y24S24I27926L26425N25R26225N26X27I25M25D26128Z27927025D25H26326425D23T26523Y26E26325O29D27529229429626G25D25E25M25N26429R24U26A25D25P25R25E23N27225E25R25Z2A027S2792AA2AC2A026524S24L2792A42A625E2AH2AD2A124N29125I25R28N25P2962A124M27U26325F25R25C25D25J25M2AF29S29325M25J2622AK2B22BC25N2BE2BG24424S24O27926K26327W25D25C24S2AU27526F25C26025J29M26L27P2BO27927125E2B92AE2BX24U26X2A725H27126625N2BK24V27927924E26M2CL2CM26M25T26M2BW27926C2B426627229B2AE24R2AN25R25O25N25E24S24527926926125C2A024526Y25I25N25Z2C425E25E26B25N29F29H29J23Y29T2BL28823Y2CE2DM25Z2DH25N26K25J26425M26M26W24D27026B23N23N26T29W26423Y26Z26F26R24U24E27925827M2752CQ24U2582EQ24U24S27923Y2EU2CL24T2ES2752F12EP2CM2F02CM2F82EV2F92CL2EW2EY24U2ER2D32ET24U2F12BP2F82F72FD2FC2FF24U27T25824X24U27M2BI2CM2EW27M2EW2FI2F12EW2752FE2F12F12AU2G62FJ24U2782GA2F12AM2FE27M2CL2FS2752BP2902F827M2BP2FD2752D32GS2ES2502FR24U24J2CM25724U2D327T2GR24U2BP2H32F224U2B224G2F92BP2B22H52H424U24H2H92AU25A27924S24Z2GC2F923Q2GX2782CL2FE27T27M25B2HK2H92H92782592EN2752AM2562F92902ER2HO2GY2FQ2792HS27T2GZ2HV2752HX24U2HZ2FI2AU2H12752FI2I32I524U2I72I92IE2EV2HP2GZ2G42752902IH2FQ2HW2H624U2542I02742F827T2AU2ER2792ER2F12GU2762F527O27Q2BB24U2AR2AJ2AL2AN2A52A72JR2A12JA27526I25N2602C427Q28N26925P25P25E26326525J2BU26B25D29Z2CV2BY2C02C225J2A625F2H22EN2JC2IY2FE2FY24U2KT2792F12EM27927M2GT2F62F92GX2JL27926125R2BF27L27N27P27R27T2752JX2AK2AM2752AO2JW2AB2AS2KI24U26L2AW2AY2B024S2FX29O2B52B72B92LP2DY2CG2CI2CK2782IR23T2FQ2JG2D32CL2MC2H92FP2G52EZ2GB2FE2MD27M2MJ2FQ2D32MM2CL2BP2HM2FQ2LF2FV2FB2752I42EU2F92MU2LB2752L82LA2JM2LD2JP2LH2JT2LK2JV2AQ2LN2CB2AV2AX25R2AZ2AE2LW2B42B62B82BA2CC2CX25F2CZ2D126424V2M62ES2M82MD2792MB2M92ME2FA2MG2O32F12MP2MV2O92MO2MH2MR2EU2MU2F52JH2MX2OI2F9');local lIlIIIIIIIIl=(bit or bit32);local IIIlIlIllllllll=lIlIIIIIIIIl and lIlIIIIIIIIl.bxor or function(lIlIIIIIIIIl,llIlIllIIllllIIIlIIIIIlII)local llllllllllIIIIlllIIll,IIIlIlIllllllll,lIlIIllIlIIIlIllIlIIIII=1,0,10 while lIlIIIIIIIIl>0 and llIlIllIIllllIIIlIIIIIlII>0 do local llIlIlllIIIlIIIIlIll,lIlIIllIlIIIlIllIlIIIII=lIlIIIIIIIIl%2,llIlIllIIllllIIIlIIIIIlII%2 if llIlIlllIIIlIIIIlIll~=lIlIIllIlIIIlIllIlIIIII then IIIlIlIllllllll=IIIlIlIllllllll+llllllllllIIIIlllIIll end lIlIIIIIIIIl,llIlIllIIllllIIIlIIIIIlII,llllllllllIIIIlllIIll=(lIlIIIIIIIIl-llIlIlllIIIlIIIIlIll)/2,(llIlIllIIllllIIIlIIIIIlII-lIlIIllIlIIIlIllIlIIIII)/2,llllllllllIIIIlllIIll*2 end if lIlIIIIIIIIl<llIlIllIIllllIIIlIIIIIlII then lIlIIIIIIIIl=llIlIllIIllllIIIlIIIIIlII end while lIlIIIIIIIIl>0 do local llIlIllIIllllIIIlIIIIIlII=lIlIIIIIIIIl%2 if llIlIllIIllllIIIlIIIIIlII>0 then IIIlIlIllllllll=IIIlIlIllllllll+llllllllllIIIIlllIIll end lIlIIIIIIIIl,llllllllllIIIIlllIIll=(lIlIIIIIIIIl-llIlIllIIllllIIIlIIIIIlII)/2,llllllllllIIIIlllIIll*2 end return IIIlIlIllllllll end local function llllllllllIIIIlllIIll(llIlIllIIllllIIIlIIIIIlII,lIlIIIIIIIIl,llllllllllIIIIlllIIll)if llllllllllIIIIlllIIll then local lIlIIIIIIIIl=(llIlIllIIllllIIIlIIIIIlII/2^(lIlIIIIIIIIl-1))%2^((llllllllllIIIIlllIIll-1)-(lIlIIIIIIIIl-1)+1);return lIlIIIIIIIIl-lIlIIIIIIIIl%1;else local lIlIIIIIIIIl=2^(lIlIIIIIIIIl-1);return(llIlIllIIllllIIIlIIIIIlII%(lIlIIIIIIIIl+lIlIIIIIIIIl)>=lIlIIIIIIIIl)and 1 or 0;end;end;local lIlIIIIIIIIl=1;local function llIlIllIIllllIIIlIIIIIlII()local llIlIllIIllllIIIlIIIIIlII,llllllllllIIIIlllIIll,llIlIlllIIIlIIIIlIll,lIlIIllIlIIIlIllIlIIIII=IlllIlllIlIlII(IlllllllIlIll,lIlIIIIIIIIl,lIlIIIIIIIIl+3);llIlIllIIllllIIIlIIIIIlII=IIIlIlIllllllll(llIlIllIIllllIIIlIIIIIlII,174)llllllllllIIIIlllIIll=IIIlIlIllllllll(llllllllllIIIIlllIIll,174)llIlIlllIIIlIIIIlIll=IIIlIlIllllllll(llIlIlllIIIlIIIIlIll,174)lIlIIllIlIIIlIllIlIIIII=IIIlIlIllllllll(lIlIIllIlIIIlIllIlIIIII,174)lIlIIIIIIIIl=lIlIIIIIIIIl+4;return(lIlIIllIlIIIlIllIlIIIII*16777216)+(llIlIlllIIIlIIIIlIll*65536)+(llllllllllIIIIlllIIll*256)+llIlIllIIllllIIIlIIIIIlII;end;local function IIlIlllIIIIlIlIIl()local llIlIllIIllllIIIlIIIIIlII=IIIlIlIllllllll(IlllIlllIlIlII(IlllllllIlIll,lIlIIIIIIIIl,lIlIIIIIIIIl),174);lIlIIIIIIIIl=lIlIIIIIIIIl+1;return llIlIllIIllllIIIlIIIIIlII;end;local function llIlIIlIlIIIlIl()local llIlIllIIllllIIIlIIIIIlII,llllllllllIIIIlllIIll=IlllIlllIlIlII(IlllllllIlIll,lIlIIIIIIIIl,lIlIIIIIIIIl+2);llIlIllIIllllIIIlIIIIIlII=IIIlIlIllllllll(llIlIllIIllllIIIlIIIIIlII,174)llllllllllIIIIlllIIll=IIIlIlIllllllll(llllllllllIIIIlllIIll,174)lIlIIIIIIIIl=lIlIIIIIIIIl+2;return(llllllllllIIIIlllIIll*256)+llIlIllIIllllIIIlIIIIIlII;end;local function lIlIlIIIllIlIlll()local lIlIIIIIIIIl=llIlIllIIllllIIIlIIIIIlII();local llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII();local lIlIIllIlIIIlIllIlIIIII=1;local IIIlIlIllllllll=(llllllllllIIIIlllIIll(llIlIllIIllllIIIlIIIIIlII,1,20)*(2^32))+lIlIIIIIIIIl;local lIlIIIIIIIIl=llllllllllIIIIlllIIll(llIlIllIIllllIIIlIIIIIlII,21,31);local llIlIllIIllllIIIlIIIIIlII=((-1)^llllllllllIIIIlllIIll(llIlIllIIllllIIIlIIIIIlII,32));if(lIlIIIIIIIIl==0)then if(IIIlIlIllllllll==0)then return llIlIllIIllllIIIlIIIIIlII*0;else lIlIIIIIIIIl=1;lIlIIllIlIIIlIllIlIIIII=0;end;elseif(lIlIIIIIIIIl==2047)then return(IIIlIlIllllllll==0)and(llIlIllIIllllIIIlIIIIIlII*(1/0))or(llIlIllIIllllIIIlIIIIIlII*(0/0));end;return lIIIIIlIIlIIIIlIlII(llIlIllIIllllIIIlIIIIIlII,lIlIIIIIIIIl-1023)*(lIlIIllIlIIIlIllIlIIIII+(IIIlIlIllllllll/(2^52)));end;local lIIIIIlIIlIIIIlIlII=llIlIllIIllllIIIlIIIIIlII;local function IllIllIIll(llIlIllIIllllIIIlIIIIIlII)local llllllllllIIIIlllIIll;if(not llIlIllIIllllIIIlIIIIIlII)then llIlIllIIllllIIIlIIIIIlII=lIIIIIlIIlIIIIlIlII();if(llIlIllIIllllIIIlIIIIIlII==0)then return'';end;end;llllllllllIIIIlllIIll=lIlIIllIlIIIlIllIlIIIII(IlllllllIlIll,lIlIIIIIIIIl,lIlIIIIIIIIl+llIlIllIIllllIIIlIIIIIlII-1);lIlIIIIIIIIl=lIlIIIIIIIIl+llIlIllIIllllIIIlIIIIIlII;local llIlIllIIllllIIIlIIIIIlII={}for lIlIIIIIIIIl=1,#llllllllllIIIIlllIIll do llIlIllIIllllIIIlIIIIIlII[lIlIIIIIIIIl]=llIlllllIlIIlIIIIll(IIIlIlIllllllll(IlllIlllIlIlII(lIlIIllIlIIIlIllIlIIIII(llllllllllIIIIlllIIll,lIlIIIIIIIIl,lIlIIIIIIIIl)),174))end return lIllIlIIlllIIIlllllIlIl(llIlIllIIllllIIIlIIIIIlII);end;local lIlIIIIIIIIl=llIlIllIIllllIIIlIIIIIlII;local function lIllIlIIlllIIIlllllIlIl(...)return{...},IlIIlIll('#',...)end local function lIIIIIlIIlIIIIlIlII()local IlllllllIlIll={};local IlllIlllIlIlII={};local lIlIIIIIIIIl={};local llIlllllIlIIlIIIIll={[#{{604;642;72;18};{819;360;497;542};}]=IlllIlllIlIlII,[#{{112;489;478;24};{365;387;278;473};"1 + 1 = 111";}]=nil,[#{"1 + 1 = 111";{31;404;409;967};"1 + 1 = 111";"1 + 1 = 111";}]=lIlIIIIIIIIl,[#{{371;292;428;722};}]=IlllllllIlIll,};local lIlIIIIIIIIl=llIlIllIIllllIIIlIIIIIlII()local lIlIIllIlIIIlIllIlIIIII={}for llllllllllIIIIlllIIll=1,lIlIIIIIIIIl do local llIlIllIIllllIIIlIIIIIlII=IIlIlllIIIIlIlIIl();local lIlIIIIIIIIl;if(llIlIllIIllllIIIlIIIIIlII==0)then lIlIIIIIIIIl=(IIlIlllIIIIlIlIIl()~=0);elseif(llIlIllIIllllIIIlIIIIIlII==1)then lIlIIIIIIIIl=lIlIlIIIllIlIlll();elseif(llIlIllIIllllIIIlIIIIIlII==2)then lIlIIIIIIIIl=IllIllIIll();end;lIlIIllIlIIIlIllIlIIIII[llllllllllIIIIlllIIll]=lIlIIIIIIIIl;end;llIlllllIlIIlIIIIll[3]=IIlIlllIIIIlIlIIl();for IlllIlllIlIlII=1,llIlIllIIllllIIIlIIIIIlII()do local lIlIIIIIIIIl=IIlIlllIIIIlIlIIl();if(llllllllllIIIIlllIIll(lIlIIIIIIIIl,1,1)==0)then local IIIlIlIllllllll=llllllllllIIIIlllIIll(lIlIIIIIIIIl,2,3);local llIlIlllIIIlIIIIlIll=llllllllllIIIIlllIIll(lIlIIIIIIIIl,4,6);local lIlIIIIIIIIl={llIlIIlIlIIIlIl(),llIlIIlIlIIIlIl(),nil,nil};if(IIIlIlIllllllll==0)then lIlIIIIIIIIl[3]=llIlIIlIlIIIlIl();lIlIIIIIIIIl[4]=llIlIIlIlIIIlIl();elseif(IIIlIlIllllllll==1)then lIlIIIIIIIIl[3]=llIlIllIIllllIIIlIIIIIlII();elseif(IIIlIlIllllllll==2)then lIlIIIIIIIIl[3]=llIlIllIIllllIIIlIIIIIlII()-(2^16)elseif(IIIlIlIllllllll==3)then lIlIIIIIIIIl[3]=llIlIllIIllllIIIlIIIIIlII()-(2^16)lIlIIIIIIIIl[4]=llIlIIlIlIIIlIl();end;if(llllllllllIIIIlllIIll(llIlIlllIIIlIIIIlIll,1,1)==1)then lIlIIIIIIIIl[2]=lIlIIllIlIIIlIllIlIIIII[lIlIIIIIIIIl[2]]end if(llllllllllIIIIlllIIll(llIlIlllIIIlIIIIlIll,2,2)==1)then lIlIIIIIIIIl[3]=lIlIIllIlIIIlIllIlIIIII[lIlIIIIIIIIl[3]]end if(llllllllllIIIIlllIIll(llIlIlllIIIlIIIIlIll,3,3)==1)then lIlIIIIIIIIl[4]=lIlIIllIlIIIlIllIlIIIII[lIlIIIIIIIIl[4]]end IlllllllIlIll[IlllIlllIlIlII]=lIlIIIIIIIIl;end end;for lIlIIIIIIIIl=1,llIlIllIIllllIIIlIIIIIlII()do IlllIlllIlIlII[lIlIIIIIIIIl-1]=lIIIIIlIIlIIIIlIlII();end;return llIlllllIlIIlIIIIll;end;local function llIlllllIlIIlIIIIll(lIlIIIIIIIIl,llIlIllIIllllIIIlIIIIIlII,llIlIIlIlIIIlIl)lIlIIIIIIIIl=(lIlIIIIIIIIl==true and lIIIIIlIIlIIIIlIlII())or lIlIIIIIIIIl;return(function(...)local IIIlIlIllllllll=lIlIIIIIIIIl[1];local lIlIIllIlIIIlIllIlIIIII=lIlIIIIIIIIl[3];local IllIllIIll=lIlIIIIIIIIl[2];local lIIIIIlIIlIIIIlIlII=lIllIlIIlllIIIlllllIlIl local llIlIllIIllllIIIlIIIIIlII=1;local IIlIlllIIIIlIlIIl=-1;local llIIIIIlI={};local IlllllllIlIll={...};local IlllIlllIlIlII=IlIIlIll('#',...)-1;local lIlIIIIIIIIl={};local llllllllllIIIIlllIIll={};for lIlIIIIIIIIl=0,IlllIlllIlIlII do if(lIlIIIIIIIIl>=lIlIIllIlIIIlIllIlIIIII)then llIIIIIlI[lIlIIIIIIIIl-lIlIIllIlIIIlIllIlIIIII]=IlllllllIlIll[lIlIIIIIIIIl+1];else llllllllllIIIIlllIIll[lIlIIIIIIIIl]=IlllllllIlIll[lIlIIIIIIIIl+#{{239;43;845;785};}];end;end;local lIlIIIIIIIIl=IlllIlllIlIlII-lIlIIllIlIIIlIllIlIIIII+1 local lIlIIIIIIIIl;local lIlIIllIlIIIlIllIlIIIII;while true do lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];lIlIIllIlIIIlIllIlIIIII=lIlIIIIIIIIl[1];if lIlIIllIlIIIlIllIlIIIII<=19 then if lIlIIllIlIIIlIllIlIIIII<=9 then if lIlIIllIlIIIlIllIlIIIII<=4 then if lIlIIllIlIIIlIllIlIIIII<=1 then if lIlIIllIlIIIlIllIlIIIII>0 then local llIlIllIIllllIIIlIIIIIlII=lIlIIIIIIIIl[2];local IIIlIlIllllllll=llllllllllIIIIlllIIll[lIlIIIIIIIIl[3]];llllllllllIIIIlllIIll[llIlIllIIllllIIIlIIIIIlII+1]=IIIlIlIllllllll;llllllllllIIIIlllIIll[llIlIllIIllllIIIlIIIIIlII]=IIIlIlIllllllll[lIlIIIIIIIIl[4]];else local llIlIllIIllllIIIlIIIIIlII=lIlIIIIIIIIl[2];local IIIlIlIllllllll=llllllllllIIIIlllIIll[lIlIIIIIIIIl[3]];llllllllllIIIIlllIIll[llIlIllIIllllIIIlIIIIIlII+1]=IIIlIlIllllllll;llllllllllIIIIlllIIll[llIlIllIIllllIIIlIIIIIlII]=IIIlIlIllllllll[lIlIIIIIIIIl[4]];end;elseif lIlIIllIlIIIlIllIlIIIII<=2 then local llIlIllIIllllIIIlIIIIIlII=lIlIIIIIIIIl[2]local IIIlIlIllllllll,lIlIIIIIIIIl=lIIIIIlIIlIIIIlIlII(llllllllllIIIIlllIIll[llIlIllIIllllIIIlIIIIIlII](llIlIlllIIIlIIIIlIll(llllllllllIIIIlllIIll,llIlIllIIllllIIIlIIIIIlII+1,lIlIIIIIIIIl[3])))IIlIlllIIIIlIlIIl=lIlIIIIIIIIl+llIlIllIIllllIIIlIIIIIlII-1 local lIlIIIIIIIIl=0;for llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII,IIlIlllIIIIlIlIIl do lIlIIIIIIIIl=lIlIIIIIIIIl+1;llllllllllIIIIlllIIll[llIlIllIIllllIIIlIIIIIlII]=IIIlIlIllllllll[lIlIIIIIIIIl];end;elseif lIlIIllIlIIIlIllIlIIIII>3 then local IlllllllIlIll;local IlIIlIll,llIlllllIlIIlIIIIll;local IlllIlllIlIlII;local lIlIIllIlIIIlIllIlIIIII;llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=llIlIIlIlIIIlIl[lIlIIIIIIIIl[3]];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=llIlIIlIlIIIlIl[lIlIIIIIIIIl[3]];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];lIlIIllIlIIIlIllIlIIIII=lIlIIIIIIIIl[2];IlllIlllIlIlII=llllllllllIIIIlllIIll[lIlIIIIIIIIl[3]];llllllllllIIIIlllIIll[lIlIIllIlIIIlIllIlIIIII+1]=IlllIlllIlIlII;llllllllllIIIIlllIIll[lIlIIllIlIIIlIllIlIIIII]=IlllIlllIlIlII[lIlIIIIIIIIl[4]];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=lIlIIIIIIIIl[3];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];lIlIIllIlIIIlIllIlIIIII=lIlIIIIIIIIl[2]IlIIlIll,llIlllllIlIIlIIIIll=lIIIIIlIIlIIIIlIlII(llllllllllIIIIlllIIll[lIlIIllIlIIIlIllIlIIIII](llIlIlllIIIlIIIIlIll(llllllllllIIIIlllIIll,lIlIIllIlIIIlIllIlIIIII+1,lIlIIIIIIIIl[3])))IIlIlllIIIIlIlIIl=llIlllllIlIIlIIIIll+lIlIIllIlIIIlIllIlIIIII-1 IlllllllIlIll=0;for lIlIIIIIIIIl=lIlIIllIlIIIlIllIlIIIII,IIlIlllIIIIlIlIIl do IlllllllIlIll=IlllllllIlIll+1;llllllllllIIIIlllIIll[lIlIIIIIIIIl]=IlIIlIll[IlllllllIlIll];end;llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];lIlIIllIlIIIlIllIlIIIII=lIlIIIIIIIIl[2]llllllllllIIIIlllIIll[lIlIIllIlIIIlIllIlIIIII]=llllllllllIIIIlllIIll[lIlIIllIlIIIlIllIlIIIII](llIlIlllIIIlIIIIlIll(llllllllllIIIIlllIIll,lIlIIllIlIIIlIllIlIIIII+1,IIlIlllIIIIlIlIIl))llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];lIlIIllIlIIIlIllIlIIIII=lIlIIIIIIIIl[2]llllllllllIIIIlllIIll[lIlIIllIlIIIlIllIlIIIII]=llllllllllIIIIlllIIll[lIlIIllIlIIIlIllIlIIIII]()llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];lIlIIllIlIIIlIllIlIIIII=lIlIIIIIIIIl[2];IlllIlllIlIlII=llllllllllIIIIlllIIll[lIlIIIIIIIIl[3]];llllllllllIIIIlllIIll[lIlIIllIlIIIlIllIlIIIII+1]=IlllIlllIlIlII;llllllllllIIIIlllIIll[lIlIIllIlIIIlIllIlIIIII]=IlllIlllIlIlII[lIlIIIIIIIIl[4]];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=lIlIIIIIIIIl[3];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];lIlIIllIlIIIlIllIlIIIII=lIlIIIIIIIIl[2]llllllllllIIIIlllIIll[lIlIIllIlIIIlIllIlIIIII]=llllllllllIIIIlllIIll[lIlIIllIlIIIlIllIlIIIII](llIlIlllIIIlIIIIlIll(llllllllllIIIIlllIIll,lIlIIllIlIIIlIllIlIIIII+1,lIlIIIIIIIIl[3]))else local lIlIIIIIIIIl=lIlIIIIIIIIl[2]llllllllllIIIIlllIIll[lIlIIIIIIIIl]=llllllllllIIIIlllIIll[lIlIIIIIIIIl]()end;elseif lIlIIllIlIIIlIllIlIIIII<=6 then if lIlIIllIlIIIlIllIlIIIII>5 then do return end;else llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]();llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=llIlIIlIlIIIlIl[lIlIIIIIIIIl[3]];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=llllllllllIIIIlllIIll[lIlIIIIIIIIl[3]][lIlIIIIIIIIl[4]];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=llllllllllIIIIlllIIll[lIlIIIIIIIIl[3]][lIlIIIIIIIIl[4]];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=llllllllllIIIIlllIIll[lIlIIIIIIIIl[3]][lIlIIIIIIIIl[4]];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=llllllllllIIIIlllIIll[lIlIIIIIIIIl[3]][lIlIIIIIIIIl[4]];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]][lIlIIIIIIIIl[3]]=llllllllllIIIIlllIIll[lIlIIIIIIIIl[4]];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];llIlIllIIllllIIIlIIIIIlII=lIlIIIIIIIIl[3];end;elseif lIlIIllIlIIIlIllIlIIIII<=7 then llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]();llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=llIlIIlIlIIIlIl[lIlIIIIIIIIl[3]];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=llllllllllIIIIlllIIll[lIlIIIIIIIIl[3]][lIlIIIIIIIIl[4]];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=llllllllllIIIIlllIIll[lIlIIIIIIIIl[3]][lIlIIIIIIIIl[4]];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=llllllllllIIIIlllIIll[lIlIIIIIIIIl[3]][lIlIIIIIIIIl[4]];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=llllllllllIIIIlllIIll[lIlIIIIIIIIl[3]][lIlIIIIIIIIl[4]];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]][lIlIIIIIIIIl[3]]=llllllllllIIIIlllIIll[lIlIIIIIIIIl[4]];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];llIlIllIIllllIIIlIIIIIlII=lIlIIIIIIIIl[3];elseif lIlIIllIlIIIlIllIlIIIII==8 then local llIlIIlIlIIIlIl;local lIlIIllIlIIIlIllIlIIIII;lIlIIllIlIIIlIllIlIIIII=lIlIIIIIIIIl[2]llllllllllIIIIlllIIll[lIlIIllIlIIIlIllIlIIIII](llIlIlllIIIlIIIIlIll(llllllllllIIIIlllIIll,lIlIIllIlIIIlIllIlIIIII+1,lIlIIIIIIIIl[3]))llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];lIlIIllIlIIIlIllIlIIIII=lIlIIIIIIIIl[2];llIlIIlIlIIIlIl=llllllllllIIIIlllIIll[lIlIIIIIIIIl[3]];llllllllllIIIIlllIIll[lIlIIllIlIIIlIllIlIIIII+1]=llIlIIlIlIIIlIl;llllllllllIIIIlllIIll[lIlIIllIlIIIlIllIlIIIII]=llIlIIlIlIIIlIl[lIlIIIIIIIIl[4]];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=lIlIIIIIIIIl[3];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=lIlIIIIIIIIl[3];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=lIlIIIIIIIIl[3];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=(lIlIIIIIIIIl[3]~=0);else llIlIllIIllllIIIlIIIIIlII=lIlIIIIIIIIl[3];end;elseif lIlIIllIlIIIlIllIlIIIII<=14 then if lIlIIllIlIIIlIllIlIIIII<=11 then if lIlIIllIlIIIlIllIlIIIII>10 then local lIlIIIIIIIIl=lIlIIIIIIIIl[2]llllllllllIIIIlllIIll[lIlIIIIIIIIl]=llllllllllIIIIlllIIll[lIlIIIIIIIIl](llIlIlllIIIlIIIIlIll(llllllllllIIIIlllIIll,lIlIIIIIIIIl+1,IIlIlllIIIIlIlIIl))else llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]][lIlIIIIIIIIl[3]]=lIlIIIIIIIIl[4];end;elseif lIlIIllIlIIIlIllIlIIIII<=12 then local llIlIIlIlIIIlIl;local lIlIIllIlIIIlIllIlIIIII;lIlIIllIlIIIlIllIlIIIII=lIlIIIIIIIIl[2]llllllllllIIIIlllIIll[lIlIIllIlIIIlIllIlIIIII](llIlIlllIIIlIIIIlIll(llllllllllIIIIlllIIll,lIlIIllIlIIIlIllIlIIIII+1,lIlIIIIIIIIl[3]))llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];lIlIIllIlIIIlIllIlIIIII=lIlIIIIIIIIl[2];llIlIIlIlIIIlIl=llllllllllIIIIlllIIll[lIlIIIIIIIIl[3]];llllllllllIIIIlllIIll[lIlIIllIlIIIlIllIlIIIII+1]=llIlIIlIlIIIlIl;llllllllllIIIIlllIIll[lIlIIllIlIIIlIllIlIIIII]=llIlIIlIlIIIlIl[lIlIIIIIIIIl[4]];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=lIlIIIIIIIIl[3];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];lIlIIllIlIIIlIllIlIIIII=lIlIIIIIIIIl[2]llllllllllIIIIlllIIll[lIlIIllIlIIIlIllIlIIIII](llIlIlllIIIlIIIIlIll(llllllllllIIIIlllIIll,lIlIIllIlIIIlIllIlIIIII+1,lIlIIIIIIIIl[3]))llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];do return end;elseif lIlIIllIlIIIlIllIlIIIII==13 then local llIlIllIIllllIIIlIIIIIlII=lIlIIIIIIIIl[2]local IIIlIlIllllllll,lIlIIIIIIIIl=lIIIIIlIIlIIIIlIlII(llllllllllIIIIlllIIll[llIlIllIIllllIIIlIIIIIlII](llIlIlllIIIlIIIIlIll(llllllllllIIIIlllIIll,llIlIllIIllllIIIlIIIIIlII+1,lIlIIIIIIIIl[3])))IIlIlllIIIIlIlIIl=lIlIIIIIIIIl+llIlIllIIllllIIIlIIIIIlII-1 local lIlIIIIIIIIl=0;for llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII,IIlIlllIIIIlIlIIl do lIlIIIIIIIIl=lIlIIIIIIIIl+1;llllllllllIIIIlllIIll[llIlIllIIllllIIIlIIIIIlII]=IIIlIlIllllllll[lIlIIIIIIIIl];end;else llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]();end;elseif lIlIIllIlIIIlIllIlIIIII<=16 then if lIlIIllIlIIIlIllIlIIIII>15 then llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=llIlIIlIlIIIlIl[lIlIIIIIIIIl[3]];else local llIlIllIIllllIIIlIIIIIlII=lIlIIIIIIIIl[2]llllllllllIIIIlllIIll[llIlIllIIllllIIIlIIIIIlII](llIlIlllIIIlIIIIlIll(llllllllllIIIIlllIIll,llIlIllIIllllIIIlIIIIIlII+1,lIlIIIIIIIIl[3]))end;elseif lIlIIllIlIIIlIllIlIIIII<=17 then llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]][lIlIIIIIIIIl[3]]=lIlIIIIIIIIl[4];elseif lIlIIllIlIIIlIllIlIIIII>18 then do return end;else local llIlIllIIllllIIIlIIIIIlII=lIlIIIIIIIIl[2]llllllllllIIIIlllIIll[llIlIllIIllllIIIlIIIIIlII](llIlIlllIIIlIIIIlIll(llllllllllIIIIlllIIll,llIlIllIIllllIIIlIIIIIlII+1,lIlIIIIIIIIl[3]))end;elseif lIlIIllIlIIIlIllIlIIIII<=29 then if lIlIIllIlIIIlIllIlIIIII<=24 then if lIlIIllIlIIIlIllIlIIIII<=21 then if lIlIIllIlIIIlIllIlIIIII==20 then llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=lIlIIIIIIIIl[3];else local llIlIIlIlIIIlIl;local lIlIIllIlIIIlIllIlIIIII;lIlIIllIlIIIlIllIlIIIII=lIlIIIIIIIIl[2]llllllllllIIIIlllIIll[lIlIIllIlIIIlIllIlIIIII]=llllllllllIIIIlllIIll[lIlIIllIlIIIlIllIlIIIII](llIlIlllIIIlIIIIlIll(llllllllllIIIIlllIIll,lIlIIllIlIIIlIllIlIIIII+1,lIlIIIIIIIIl[3]))llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];lIlIIllIlIIIlIllIlIIIII=lIlIIIIIIIIl[2];llIlIIlIlIIIlIl=llllllllllIIIIlllIIll[lIlIIIIIIIIl[3]];llllllllllIIIIlllIIll[lIlIIllIlIIIlIllIlIIIII+1]=llIlIIlIlIIIlIl;llllllllllIIIIlllIIll[lIlIIllIlIIIlIllIlIIIII]=llIlIIlIlIIIlIl[lIlIIIIIIIIl[4]];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=lIlIIIIIIIIl[3];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];lIlIIllIlIIIlIllIlIIIII=lIlIIIIIIIIl[2]llllllllllIIIIlllIIll[lIlIIllIlIIIlIllIlIIIII]=llllllllllIIIIlllIIll[lIlIIllIlIIIlIllIlIIIII](llIlIlllIIIlIIIIlIll(llllllllllIIIIlllIIll,lIlIIllIlIIIlIllIlIIIII+1,lIlIIIIIIIIl[3]))llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];lIlIIllIlIIIlIllIlIIIII=lIlIIIIIIIIl[2];llIlIIlIlIIIlIl=llllllllllIIIIlllIIll[lIlIIIIIIIIl[3]];llllllllllIIIIlllIIll[lIlIIllIlIIIlIllIlIIIII+1]=llIlIIlIlIIIlIl;llllllllllIIIIlllIIll[lIlIIllIlIIIlIllIlIIIII]=llIlIIlIlIIIlIl[lIlIIIIIIIIl[4]];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=lIlIIIIIIIIl[3];end;elseif lIlIIllIlIIIlIllIlIIIII<=22 then llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=(lIlIIIIIIIIl[3]~=0);elseif lIlIIllIlIIIlIllIlIIIII>23 then llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]][lIlIIIIIIIIl[3]]=llllllllllIIIIlllIIll[lIlIIIIIIIIl[4]];else llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=llIlIIlIlIIIlIl[lIlIIIIIIIIl[3]];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=llllllllllIIIIlllIIll[lIlIIIIIIIIl[3]][lIlIIIIIIIIl[4]];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=llllllllllIIIIlllIIll[lIlIIIIIIIIl[3]][lIlIIIIIIIIl[4]];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]][lIlIIIIIIIIl[3]]=lIlIIIIIIIIl[4];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];do return end;end;elseif lIlIIllIlIIIlIllIlIIIII<=26 then if lIlIIllIlIIIlIllIlIIIII==25 then local lIlIIIIIIIIl=lIlIIIIIIIIl[2]llllllllllIIIIlllIIll[lIlIIIIIIIIl]=llllllllllIIIIlllIIll[lIlIIIIIIIIl](llIlIlllIIIlIIIIlIll(llllllllllIIIIlllIIll,lIlIIIIIIIIl+1,IIlIlllIIIIlIlIIl))else llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=lIlIIIIIIIIl[3];end;elseif lIlIIllIlIIIlIllIlIIIII<=27 then llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=llllllllllIIIIlllIIll[lIlIIIIIIIIl[3]][lIlIIIIIIIIl[4]];elseif lIlIIllIlIIIlIllIlIIIII==28 then llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]][lIlIIIIIIIIl[3]]=llllllllllIIIIlllIIll[lIlIIIIIIIIl[4]];else llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=llIlllllIlIIlIIIIll(IllIllIIll[lIlIIIIIIIIl[3]],nil,llIlIIlIlIIIlIl);end;elseif lIlIIllIlIIIlIllIlIIIII<=34 then if lIlIIllIlIIIlIllIlIIIII<=31 then if lIlIIllIlIIIlIllIlIIIII==30 then local llIlIllIIllllIIIlIIIIIlII=lIlIIIIIIIIl[2]llllllllllIIIIlllIIll[llIlIllIIllllIIIlIIIIIlII]=llllllllllIIIIlllIIll[llIlIllIIllllIIIlIIIIIlII](llIlIlllIIIlIIIIlIll(llllllllllIIIIlllIIll,llIlIllIIllllIIIlIIIIIlII+1,lIlIIIIIIIIl[3]))else local IIlIlllIIIIlIlIIl;local lIlIIllIlIIIlIllIlIIIII;llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=lIlIIIIIIIIl[3];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];lIlIIllIlIIIlIllIlIIIII=lIlIIIIIIIIl[2]llllllllllIIIIlllIIll[lIlIIllIlIIIlIllIlIIIII]=llllllllllIIIIlllIIll[lIlIIllIlIIIlIllIlIIIII](llIlIlllIIIlIIIIlIll(llllllllllIIIIlllIIll,lIlIIllIlIIIlIllIlIIIII+1,lIlIIIIIIIIl[3]))llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=llIlIIlIlIIIlIl[lIlIIIIIIIIl[3]];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=llllllllllIIIIlllIIll[lIlIIIIIIIIl[3]][lIlIIIIIIIIl[4]];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=llllllllllIIIIlllIIll[lIlIIIIIIIIl[3]][lIlIIIIIIIIl[4]];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=llllllllllIIIIlllIIll[lIlIIIIIIIIl[3]][lIlIIIIIIIIl[4]];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];lIlIIllIlIIIlIllIlIIIII=lIlIIIIIIIIl[2];IIlIlllIIIIlIlIIl=llllllllllIIIIlllIIll[lIlIIIIIIIIl[3]];llllllllllIIIIlllIIll[lIlIIllIlIIIlIllIlIIIII+1]=IIlIlllIIIIlIlIIl;llllllllllIIIIlllIIll[lIlIIllIlIIIlIllIlIIIII]=IIlIlllIIIIlIlIIl[lIlIIIIIIIIl[4]];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=lIlIIIIIIIIl[3];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];lIlIIllIlIIIlIllIlIIIII=lIlIIIIIIIIl[2]llllllllllIIIIlllIIll[lIlIIllIlIIIlIllIlIIIII]=llllllllllIIIIlllIIll[lIlIIllIlIIIlIllIlIIIII](llIlIlllIIIlIIIIlIll(llllllllllIIIIlllIIll,lIlIIllIlIIIlIllIlIIIII+1,lIlIIIIIIIIl[3]))llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];lIlIIllIlIIIlIllIlIIIII=lIlIIIIIIIIl[2];IIlIlllIIIIlIlIIl=llllllllllIIIIlllIIll[lIlIIIIIIIIl[3]];llllllllllIIIIlllIIll[lIlIIllIlIIIlIllIlIIIII+1]=IIlIlllIIIIlIlIIl;llllllllllIIIIlllIIll[lIlIIllIlIIIlIllIlIIIII]=IIlIlllIIIIlIlIIl[lIlIIIIIIIIl[4]];end;elseif lIlIIllIlIIIlIllIlIIIII<=32 then llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]();elseif lIlIIllIlIIIlIllIlIIIII==33 then llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=llIlllllIlIIlIIIIll(IllIllIIll[lIlIIIIIIIIl[3]],nil,llIlIIlIlIIIlIl);else local llIlIllIIllllIIIlIIIIIlII=lIlIIIIIIIIl[2]llllllllllIIIIlllIIll[llIlIllIIllllIIIlIIIIIlII]=llllllllllIIIIlllIIll[llIlIllIIllllIIIlIIIIIlII](llIlIlllIIIlIIIIlIll(llllllllllIIIIlllIIll,llIlIllIIllllIIIlIIIIIlII+1,lIlIIIIIIIIl[3]))end;elseif lIlIIllIlIIIlIllIlIIIII<=37 then if lIlIIllIlIIIlIllIlIIIII<=35 then llIlIllIIllllIIIlIIIIIlII=lIlIIIIIIIIl[3];elseif lIlIIllIlIIIlIllIlIIIII>36 then llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=(lIlIIIIIIIIl[3]~=0);else local lIlIIIIIIIIl=lIlIIIIIIIIl[2]llllllllllIIIIlllIIll[lIlIIIIIIIIl]=llllllllllIIIIlllIIll[lIlIIIIIIIIl]()end;elseif lIlIIllIlIIIlIllIlIIIII<=38 then llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=llllllllllIIIIlllIIll[lIlIIIIIIIIl[3]][lIlIIIIIIIIl[4]];elseif lIlIIllIlIIIlIllIlIIIII>39 then local llIlIIlIlIIIlIl;local lIlIIllIlIIIlIllIlIIIII;lIlIIllIlIIIlIllIlIIIII=lIlIIIIIIIIl[2]llllllllllIIIIlllIIll[lIlIIllIlIIIlIllIlIIIII](llIlIlllIIIlIIIIlIll(llllllllllIIIIlllIIll,lIlIIllIlIIIlIllIlIIIII+1,lIlIIIIIIIIl[3]))llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];lIlIIllIlIIIlIllIlIIIII=lIlIIIIIIIIl[2];llIlIIlIlIIIlIl=llllllllllIIIIlllIIll[lIlIIIIIIIIl[3]];llllllllllIIIIlllIIll[lIlIIllIlIIIlIllIlIIIII+1]=llIlIIlIlIIIlIl;llllllllllIIIIlllIIll[lIlIIllIlIIIlIllIlIIIII]=llIlIIlIlIIIlIl[lIlIIIIIIIIl[4]];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=lIlIIIIIIIIl[3];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=lIlIIIIIIIIl[3];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=lIlIIIIIIIIl[3];llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;lIlIIIIIIIIl=IIIlIlIllllllll[llIlIllIIllllIIIlIIIIIlII];llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=(lIlIIIIIIIIl[3]~=0);else llllllllllIIIIlllIIll[lIlIIIIIIIIl[2]]=llIlIIlIlIIIlIl[lIlIIIIIIIIl[3]];end;llIlIllIIllllIIIlIIIIIlII=llIlIllIIllllIIIlIIIIIlII+1;end;end);end;return llIlllllIlIIlIIIIll(true,{},llIIIIIlI())();end)(string.byte,table.insert,setmetatable);
