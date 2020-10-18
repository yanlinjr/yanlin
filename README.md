
function HOME()
  MN = gg.choice({
"[[🇲🇲]]ᴀɴᴛɪʙᴀɴ [[ʟᴏʙʙʏ ]]",
"[[🇲🇲]]ᴡᴀʟʟʜᴀᴄᴋ ᴀʟʟ sᴅ[[ᴛʀᴀɪɴɢ]]",
"[[🇲🇲]]ᴄᴏʟᴏʀ ᴀʟʟ sᴅ[[ᴛʀᴀɪɴɢ]]",
"[[🇲🇲]]ʟᴇss ʀᴇᴄᴏɪʟ [[ɪɴɢᴀᴍᴇ]]",
"[[🇲🇲]]ʜᴇᴀᴅsʜᴏᴛ [[ɪɴɢᴀᴍᴇ]]",
"[[🇲🇲]]ᴀɴᴛᴇɴɴᴀ ʜᴀᴄᴋ [[ɪɴɢᴀᴍᴇ]]",
"[[🇲🇲]]ᴡɪᴅᴇ ᴠɪᴇᴡ [[ɪɴɢᴀᴍᴇ]]",
"[[🇲🇲]]ɢ𝟗𝟎ᴛ [[ɴᴏᴛᴇ ❽ ᴘʀᴏ]]",
"◦•●◉✿ᴇxɪᴛ✿◉●•◦"
      }, nil, (os.date("✭❈ʟᴛɴs☆ᴏɴʟɪɴᴇ☆sᴄʀɪᴘᴛ☆ᴠᴇʀsɪᴏɴ☆ɴᴀᴛsᴏᴇ")))
      
        if MN == 1 then
          BY()
        end
        if MN == 2 then
          WC()
        end
        if MN == 3 then
          CLR()
        end
        if MN == 4 then
          REC()
        end
        if MN == 5 then
          HS()
        end
        if MN == 6 then
          ANTENA()
          end
          if MN == 7 then
            WV()
            end
         if MN == 8 then
            g90t()
            end
        if MN == 9 then
         EXIT()
        end
      
      PENGKIKGM = -1
    end
    function g90t()
  ML = gg.multiChoice({
    "𝐕𝟭 𝐖𝐚𝐥𝐥 𝐀𝐧𝐝 𝐂𝐨𝐥𝐨𝐮𝐫",
    "𝐕𝟮 𝐖𝐚𝐥𝐥 𝐀𝐧𝐝 𝐂𝐨𝐥𝐨𝐮𝐫",
    "𝐕𝟯 𝐖𝐚𝐥𝐥 𝐀𝐧𝐝 𝐂𝐨𝐥𝐨𝐮𝐫",
"◦•●◉✿𝐁𝐚𝐜𝐤✿◉●•◦"
  }, nil, "🇲🇲sᴏᴍᴇ ᴛɪᴍᴇs ᴡᴀʟʟʜᴀᴄᴋ ɴᴏᴛ ᴡᴏʀᴋ🇲🇲")
  if ML == nil then
  else
   if ML[1] == true then
      G90TV1()
    end
    if ML[2] == true then
     G90TV2()
    end
    if ML[3] == true then
    G90TV3()
    end
    if ML[4] == true then
      HOME()
    end
  end
  PUBGMH = -1
end
function G90TV3()
DIE2 = gg.multiChoice({
"[[🇲🇲]]𝐖𝐀𝐋𝐋 𝐇𝐀𝐂𝐊 𝐆90𝐓",
"[[🇲🇲]]𝐂𝐎𝐋𝐎𝐑 𝐁𝐥𝐚𝐜𝐤 ",
"[[🇲🇲]]𝐂𝐨𝐥𝐨𝐮𝐫 𝐆𝐫𝐞𝐞𝐧",
"[[🇲🇲]]𝐂𝐨𝐥𝐨𝐮𝐫 𝐘𝐞𝐥𝐥𝐨𝐰",
"[[🇲🇲]]𝐂𝐨𝐥𝐨𝐮𝐫 𝐑𝐞𝐝",
"🔙𝐄𝐗𝐈𝐓"}, nil, "")
if DIE2 == nil then else
if DIE2[1] == true then G90T3() end
if DIE2[2] == true then Black() end
if DIE2[3] == true then Green() end
if DIE2[4] == true then Yellow() end
if DIE2[5] == true then Red() end
if DIE2[6] == true then close() end
end
DIE = -1
end
function G90T3()
  gg.clearResults()
  gg.searchNumber("\"1.793662e-43F;3.5873241e-43F;1.1210388e-44F;0.5F:512\"", gg.TYPE_FLOAT)
  gg.refineNumber("\"0.5\"", gg.TYPE_FLOAT)
  t = gg.getResults(100)
  for i, i in ipairs(t) do
    if i.flags == gg.TYPE_FLOAT then
      i.value = "2.0"
      i.freeze = true
    end
  end
  gg.addListItems(t)
  gg.clearResults ()
  gg.toast("WH Mediatek G90T")
end

function Black()
  gg.clearResults()
  gg.setRanges(gg.REGION_C_ALLOC)
  gg.searchNumber("40D;32D;16D;2D::37", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("39", gg.TYPE_DWORD)
  gg.toast("Black")
end

function Green()
  gg.clearResults()
  gg.setRanges(gg.REGION_C_ALLOC)
  gg.searchNumber("2;2;8;6;40:45", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.processResume()
  gg.refineNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10, nil, nil, nil, nil, nil, nil, nil, nil)
  gg.editAll("32", gg.TYPE_DWORD)
  gg.processResume()
  gg.toast("Green")
end

function Yellow()
  gg.clearResults()
  gg.setRanges(gg.REGION_C_ALLOC)
  gg.searchNumber("16;32;40;48;40:41", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("36", gg.TYPE_DWORD)
  gg.clearResults()
  gg.toast("YELLOW")
end

function Red()
  gg.clearResults()
  gg.setRanges(gg.REGION_C_ALLOC)
  gg.searchNumber("16;32;40;48;40:41", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("38", gg.TYPE_DWORD)
  gg.toast("LTNS")
end


function G90TV1()
DIE1 = gg.multiChoice({
"[[🇲🇲]]𝐖𝐀𝐋𝐋 𝐇𝐀𝐂𝐊 𝐆90𝐓",
"[[🇲🇲]]𝐂𝐎𝐋𝐎𝐑 𝐑𝐄𝐃 ",
"🔙EXIT"}, nil, "")
if DIE1 == nil then else
if DIE1[1] == true then WHG90T() end
if DIE1[2] == true then CHG90T() end
if DIE1[3] == true then close() end
end
DIE = -1
end

function WHG90T()
gg.clearResults()
  
  gg.clearResults()
  gg.setRanges(gg.REGION_C_ALLOC)
  gg.searchNumber("16;32;40;48;40:41", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("36", gg.TYPE_DWORD)
  gg.clearResults()
  gg.searchNumber("\"1.793662e-43F;3.5873241e-43F;1.1210388e-44F;0.5F:512\"", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("\"0.5\"", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  n = gg.getResultCount()
  jz = gg.getResults(n)
  do
    do
      for i = 1, n do
        gg.addListItems({
          [1] = {
            address = jz[i].address + 0,
            flags = 16,
            freeze = true,
            value = 2
          }
        })
      end--yanlinjr
    end--yanlinjr
  end--yanlinjr
  gg.clearResults()
  gg.alert("Wallhack G90t Activated")
end--yanlinjr

function CHG90T()

  gg.clearResults()
  gg.setRanges(gg.REGION_C_ALLOC)
  gg.searchNumber("8;16;32;48;40::169", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("38", gg.TYPE_DWORD)
  gg.clearResults()
  gg.alert("Color Red ")
end--yanlinjr
function G90TV2()
  ML = gg.multiChoice({
    "[[🇲🇲]]𝐖𝐚𝐥𝐥𝐡𝐚𝐜𝐤 ❶",
    "[[🇲🇲]]𝐖𝐚𝐥𝐥𝐡𝐚𝐜𝐤 ❷",
    "[[🇲🇲]]𝐖𝐚𝐥𝐥𝐡𝐚𝐜𝐤 ❸",
    "[[🇲🇲]]𝐂𝐨𝐥𝐨𝐮𝐫  ❶",
    "[[🇲🇲]]𝐂𝐨𝐥𝐨𝐮𝐫  ❷",
"◦•●◉✿𝐁𝐚𝐜𝐤✿◉●•◦"
  }, nil, "🇲🇲sᴏᴍᴇ ᴛɪᴍᴇs ᴡᴀʟʟʜᴀᴄᴋ ɴᴏᴛ ᴡᴏʀᴋ🇲🇲")
  if ML == nil then
  else
    if ML[1] == true then
      ML1()
    end
    if ML[2] == true then
      ML2()
    end
    if ML[3] == true then
      ML3()
    end
    if ML[4] == true then
      ML4()
    end
    if ML[5] == true then
      ML5()
    end
    if ML[6] == true then
      HOME()
    end--yanlinjr
  end--yanlinjr
  PUBGMH = -1
end

function ML1()
  gg.clearResults()
  gg.setRanges(gg.REGION_C_ALLOC)
  gg.searchNumber("1.793662e-43F;3.5873241e-43F;1.1210388e-44F;0.5F:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1, 0)
  gg.processResume()
  gg.refineNumber("0.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1, 0)
  gg.getResults(500, nil, nil, nil, nil, nil, nil, nil, nil)
  gg.getResults(500, nil, nil, nil, nil, nil, nil, nil, nil)
  jg = gg.getResults(500)
  sl = gg.getResultCount()
  if 500 < sl then
    sl = 500
  end
  do
    do
      for _FORV_3_ = 1, sl do
        dzy = jg[_FORV_3_].address
        gg.addListItems({
          [1] = {
            address = dzy,
            flags = gg.TYPE_FLOAT,
            freeze = true,
            value = 2
          }
        })
      end--yanlinjr
    end--yanlinjr
  end--yanlinjr
  gg.toast("Wallhack Activated")
end

function ML2()
  gg.alert("wall hack on HD/Medium/classic")
  gg.alert("ONLY FOR MEDITEK G90K HACKS")
  gg.setRanges(gg.REGION_C_ALLOC)
  gg.alert("Adjust Graphics Smooth /low /Classic")
  gg.searchNumber("0.5;-360.0;360.0;776.0;0.5;0.5:273", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1, 0)
  gg.refineNumber("0.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1, 0)
  gg.getResults(40, nil, nil, nil, nil, nil, nil, nil, nil)
  gg.getResults(40, nil, nil, nil, nil, nil, nil, nil, nil)
  jg = gg.getResults(40)
  sl = gg.getResultCount()
  if sl > 100 then
    sl = 40
  end--yanlinjr
  do
    do
      for _FORV_3_ = 1, sl do
        dzy = jg[_FORV_3_].address
        gg.addListItems({
          [1] = {
            address = dzy,
            flags = gg.TYPE_FLOAT,
            freeze = true,
            value = 2
          }
        })
      end--yanlinjr
    end--yanlinjr
  end--yanlinjr
  gg.toast("Wallhack Activated")
end

function ML3()
  gg.setRanges(gg.REGION_C_ALLOC)
  gg.searchNumber("360.0;776.0;0.5;2.80259693e-45;5.60519386e-45;4.17586942e-43;2.94272678e-44;1.26116862e-44;9.80908925e-45;8.40779079e-45;7.00649232e-45:2293", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1, 0)
  gg.refineNumber("0.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1, 0)
  revert = gg.getResults(500, nil, nil, nil, nil, nil, nil, nil, nil)
  local t = gg.getResults(500, nil, nil, nil, nil, nil, nil, nil, nil)
  do
    do
      for _FORV_4_, _FORV_5_ in ipairs(t) do
        if _FORV_5_.flags == gg.TYPE_FLOAT then
          _FORV_5_.value = "2"
          _FORV_5_.freeze = true
        end--yanlinjr
      end--yanlinjr
    end--yanlinjr
  end--yanlinjr
  gg.toast("Wallhavk Done")
end--yanlinjr

function ML4()
  gg.setRanges(gg.REGION_C_ALLOC)
  gg.searchNumber("\"40;734003200:5\"", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("\"40\"", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  revert = gg.getResults(600, nil, nil, nil, nil, nil, nil, nil, nil)
  gg.editAll("\"38\"", gg.TYPE_DWORD)
end

function ML5()
  gg.setRanges(gg.REGION_C_ALLOC)
  gg.searchNumber("935329792;40;734003200;32;801112064;48;801112064;16;801112064;2;2;2;64:85", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
  gg.processResume()
  gg.refineNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
  gg.getResults(30, nil, nil, nil, nil, nil, nil, nil, nil)
  gg.getResults(30, nil, nil, nil, nil, nil, nil, nil, nil)
  gg.editAll("\"28\"", gg.TYPE_DWORD)
  gg.toast("restart")
end


    function WC()
      MN1 = gg.choice({
        "[[🇲🇲]] 𝐖𝐇 𝐀𝐋𝐋 𝐒𝐍𝐀𝐏𝐃𝐑𝐀𝐆𝐎𝐍",
        "[[🇲🇲]]  𝐖𝐇 𝐀𝐋𝐋 𝐃𝐄𝐕𝐈𝐂𝐄",
        "[[🇲🇲]]  𝐖𝐇 𝐅𝐈𝐗 𝐁𝐋𝐈𝐍𝐊 [ 𝐈𝐍 𝐆𝐀𝐌𝐄 ]",
        "[[🇲🇲]]  𝐖𝐇 𝐅𝐈𝐗 𝐒𝐂𝐎𝐏𝐄",
        "[[🇲🇲]]  𝐖𝐇 𝐒𝐃 𝟒𝟎𝟎",
        "[[🇲🇲]]  𝐖𝐇 𝐒𝐃 𝟒𝟏𝟎",
        "[[🇲🇲]]  𝐖𝐇 𝐒𝐃 𝟒𝟏𝟓",
        "[[🇲🇲]]  𝐖𝐇 𝐒𝐃 𝟒𝟐𝟓",
        "[[🇲🇲]]  𝐖𝐇 𝐒𝐃 𝟒𝟑𝟎",
        "[[🇲🇲]]  𝐖𝐇 𝐒𝐃 𝟒𝟑𝟓",
        "[[🇲🇲]]  𝐖𝐇 𝐒𝐃 𝟒𝟑𝟗",
        "[[🇲🇲]]  𝐖𝐇 𝐒𝐃 𝟒𝟓𝟎",
        "[[🇲🇲]]  𝐖𝐇 𝐒𝐃 𝟔𝟎𝟎",
        "[[🇲🇲]]  𝐖𝐇 𝐒𝐃 𝟔𝟏𝟎",
        "[[🇲🇲]]  𝐖𝐇 𝐒𝐃 𝟔𝟏𝟓",
        "[[🇲🇲]]  𝐖𝐇 𝐒𝐃 𝟔𝟏𝟔",
        "[[🇲🇲]]  𝐖𝐇 𝐒𝐃 𝟔𝟐𝟓",
        "[[🇲🇲]]  𝐖𝐇 𝐒𝐃 𝟔𝟐𝟔",
        "[[🇲🇲]]  𝐖𝐇 𝐒𝐃 𝟔𝟑𝟎",
        "[[🇲🇲]]  𝐖𝐇 𝐒𝐃 𝟔𝟑𝟐",
        "[[🇲🇲]]  𝐖𝐇 𝐒𝐃 𝟔𝟑𝟔",
        "[[🇲🇲]]  𝐖𝐇 𝐒𝐃 𝟔𝟓𝟎",
        "[[🇲🇲]]  𝐖𝐇 𝐒𝐃 𝟔𝟓𝟑",
        "[[🇲🇲]]  𝐖𝐇 𝐒𝐃 𝟔𝟔𝟎",
        "[[🇲🇲]]  𝐖𝐇 𝐒𝐃 𝟔𝟔𝟓",
        "[[🇲🇲]]  𝐖𝐇 𝐒𝐃 𝟔𝟕𝟎",
        "[[🇲🇲]]  𝐖𝐇 𝐒𝐃 𝟔𝟕𝟓",
        "[[🇲🇲]]  𝐖𝐇 𝐒𝐃 𝟔𝟖𝟎",
        "[[🇲🇲]]  𝐖𝐇 𝐒𝐃 𝟕𝟏𝟎",
        "[[🇲🇲]]  𝐖𝐇 𝐒𝐃 𝟕𝟏𝟐",
        "[[🇲🇲]]  𝐖𝐇 𝐒𝐃 𝟕𝟏𝟓",
       " [[🇲🇲]] 𝐖𝐇 𝐒𝐃 𝟕𝟔𝟓",   
        "[[🇲🇲]]  𝐖𝐇 𝐒𝐃 𝟖𝟎𝟎",
        "[[🇲🇲]]  𝐖𝐇 𝐒𝐃 𝟖𝟎𝟏",
        "[[🇲🇲]]  𝐖𝐇 𝐒𝐃 𝟖𝟎𝟓",
        "[[🇲🇲]]  𝐖𝐇 𝐒𝐃 𝟖𝟎𝟖",
        "[[🇲🇲]]  𝐖𝐇 𝐒𝐃 𝟖𝟏𝟎",
        "[[🇲🇲]]  𝐖𝐇 𝐒𝐃 𝟖𝟏𝟓",
        "[[🇲🇲]]  𝐖𝐇 𝐒𝐃 𝟖𝟐𝟎",
        "[[🇲🇲]]  𝐖𝐇 𝐒𝐃 𝟖𝟐𝟏",
        "[[🇲🇲]]  𝐖𝐇 𝐒𝐃 𝟖𝟑𝟓",
        "[[🇲🇲]]  𝐖𝐇 𝐒𝐃 𝟖𝟒𝟓 ",
        "[[🇲🇲]]  𝐖𝐇 𝐒𝐃 𝟖𝟓𝟓",
        "◦•●◉✿𝐁𝐚𝐜𝐤✿◉●•◦"
      }, nil, "                        ✭❈ʟᴛɴs☆ᴏɴʟɪɴᴇ☆sᴄʀɪᴘᴛ☆ᴠᴇʀsɪᴏɴ☆ɴᴀᴛsᴏᴇ")
if MN1 == 1 then
          WHA()
        end
        if MN1 == 2 then
          WHAD()
        end
        if MN1 == 3 then
          WHFB()
        end
        if MN1 == 4 then
          WHFS()
        end
        if MN1 == 5 then
          WH400()
        end
        if MN1 == 6 then
          WH410()
        end
        if MN1 == 7 then
          WH415()
        end
        if MN1 == 8 then
          WH425()
        end
        if MN1 == 9 then
          WH430()
        end
        if MN1 == 10 then
          WH435()
        end
        if MN1 == 11 then
          WH439()
        end
        if MN1 == 12 then
          WH450()
        end
        if MN1  == 13 then
          WH600()
        end
        if MN1 == 14 then
          WH610()
        end
        if MN1 == 15 then
          WH615()
        end
        if MN1  == 16 then
          WH616()
        end
        if MN1 == 17 then
          WH625()
        end
        if MN1== 18 then
          WH626()
        end
        if MN1== 19 then
          WH630()
        end
        if MN1== 20 then
          WH632()
        end
        if MN1== 21 then
          WH636()
          Y636()
        end
        if MN1== 22 then
          WH650()
        end
        if MN1== 23 then
          WH653()
        end
        if MN1== 24 then
          WH660()
        end
        if MN1== 25 then
          WH665()
        end
        if MN1== 26 then
          WH670()
        end
        if MN1== 27 then
          WH675()
        end
        if MN1== 28 then
          WH680()
        end
        if MN1== 29 then
          WH710()
        end
        if MN1== 30 then
          WH712()
        end
        if MN1== 31 then
          WH715()
        end
        if MN1 == 32 then
          WH765()
          Y765()
          end
        if MN1== 33 then
          WH800()
        end
        if MN1== 34 then
          WH801()
        end
        if MN1== 35 then
          WH805()
        end
        if MN1== 36 then
          WH808()
        end
        if MN1== 37 then
          WH810()
        end
        if MN1== 38 then
          WH815()
        end
        if MN1== 39 then
          WH820()
        end
        if MN1== 40 then
          WH821()
        end
        if MN1== 41 then
          WH835()      
        end
        if MN1 == 42 then
          WH845()
        end
        if MN1 == 43 then
          WH855()
          Y855()
        end
        
        if MN1 == 44 then
          HOME()
        end
      PUBBGMH = -1
    end
    
   function CLR()
      MN2 = gg.choice({ 
        "[[🇲🇲]]  𝐂 𝐆𝐫𝐞𝐞𝐧",
        "[[🇲🇲]]  𝐂 𝐑𝐞𝐝 [[𝐎𝐧𝐥𝐲 𝐁𝐨𝐝𝐲]]",
        "[[🇲🇲]]  𝐂 𝐑𝐞𝐝 [ 𝐅𝐮𝐥𝐥 ]",
        "[[🇲🇲]]  𝐂 𝐘𝐞𝐥𝐥𝐨𝐰 [[𝐎𝐧𝐥𝐲 𝐁𝐨𝐝𝐲]]",
        "[[🇲🇲]]  𝐂 𝐘𝐞𝐥𝐥𝐨𝐰 [[𝐅𝐮𝐥𝐥]]",
        "[[🇲🇲]]  𝐂 𝐏𝐢𝐧𝐤",
        "[[🇲🇲]]  𝐂 𝐖𝐡𝐢𝐭𝐞 [[𝐎𝐧𝐥𝐲 𝐁𝐨𝐝𝐲]]",
        "[[🇲🇲]]  𝐂 𝐖𝐡𝐢𝐭𝐞 [[𝐅𝐮𝐥𝐥]]",
        "[[🇲🇲]]  𝐂 𝐒𝐃 𝟒𝟎𝟎 𝐘𝐞𝐥𝐥𝐨𝐰",
        "[[🇲🇲]]  𝐂 𝐒𝐃 𝟒𝟎𝟎//𝟒𝟏𝟎 𝐆𝐫𝐞𝐞𝐧",
        "[[🇲🇲]]  𝐂 𝐒𝐃 𝟒𝟏𝟓 𝐆𝐫𝐞𝐞𝐧",
        "[[🇲🇲]]  𝐂 𝐒𝐃 𝟒𝟐𝟓",
        "[[🇲🇲]]  𝐂 𝐒𝐃 𝟒𝟑𝟓",
        "[[🇲🇲]]  𝐂 𝐒𝐃 𝟒𝟓𝟎",
        "[[🇲🇲]]  𝐂 𝐒𝐃 𝟔𝟏𝟓",
        "[[🇲🇲]]  𝐂 𝐒𝐃 𝟔𝟑𝟔",
        "[[🇲🇲]]  𝐂 𝐒𝐃 𝟔𝟔𝟎",
        "[[🇲🇲]]  𝐂 𝐒𝐃 𝟔𝟔𝟓",
        "[[🇲🇲]]  𝐂 𝐒𝐃 𝟔𝟕𝟓",
        "[[🇲🇲]]  𝐂 𝐒𝐃 𝟕𝟏𝟎",
        "[[🇲🇲]]  𝐂 𝐒𝐃 𝟕𝟏𝟐",
        "[[🇲🇲]]  𝐂 𝐒𝐃 𝟖𝟒𝟓",
        "[[🇲🇲]]  𝐂 𝐒𝐃 𝟖𝟓𝟓",
"◦•●◉✿𝐁𝐚𝐜𝐤✿◉●•◦"
      }, nil, "                        ✭❈ʟᴛɴs☆ᴏɴʟɪɴᴇ☆sᴄʀɪᴘᴛ☆ᴠᴇʀsɪᴏɴ☆ɴᴀᴛsᴏᴇ")
    
      if MN2  == 1 then
          C1()
        end
        if MN2== 2 then
          C2()
        end
        if MN2== 3 then
          C3()
        end
        if MN2 == 4 then
          C4()
        end
        if MN2 == 5 then
          C5()
        end
        if MN2 == 6 then
          C6()
        end
        if MN2 == 7 then
          C7()
        end
        if MN2 == 8 then
          C8()
        end
        if MN2== 9 then
          C9()
        end
        if MN2 == 10 then
          C10()
        end
        if MN2== 11 then
          C11()
        end
        if MN2== 12 then
          C12()
        end
        if MN2 == 13 then
          C13()
        end
        if MN2 == 14 then
          C14()
        end
        if MN2 == 15 then
          C15()
        end
        if MN2 == 16 then
          C16()
        end
        if MN2 == 17 then
          C17()
        end
        if MN2 == 18 then
          C18()
        end
        if MN2== 19 then
          C19()
        end
        if MN2 == 20 then
          C20()
        end
        if MN2 == 21 then
          C21()
        end
        if MN2 == 22 then
          C22()
        end
        if MN2  == 23 then
          C23()
        end
        if MN2 == 24 then
          HOME()
        end
      
      PUBBGMH = -1
    end
    
    
    function WH765()

gg.clearResults()
 gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
gg.searchNumber('"1.7506772e-39F;4.7223772e21F;2.0F"', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
revert = gg.getResults(1000, nil, nil, nil, nil, nil, nil, nil, nil)
gg.editAll('"100"', gg.TYPE_FLOAT)
gg.processResume()
gg.processResume()

local t = gg.getResults(1000, nil, nil, nil, nil, nil, nil, nil, nil)
gg.addListItems(t)
t = nil

gg.processResume()
gg.refineNumber('"2.5223372e-44F;1.1202051e-19F;2.0F"', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('"2.5223372e-44F;1.1202051e-19F;2.0F"', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
revert = gg.getResults(1000, nil, nil, nil, nil, nil, nil, nil, nil)
gg.editAll('"100"', gg.TYPE_FLOAT)
gg.processResume()
gg.toast("WH765 ᴀᴄᴛɪᴠᴇ ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
end

function WH439()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("4,140D;4.7408166e21F;4.7223665e21;0D;0D;0D;0D;0D;0D;-0.0F;2.0F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(30)
      gg.editAll("120", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.setRanges(gg.REGION_BAD)
      gg.searchNumber("2.718519e-43;2.0F;-1.0F;1.0F;-127F;0.24022650719F;-0.0", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(30)
      gg.editAll("120", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.toast("WH439 ᴀᴄᴛɪᴠᴇ ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function WH450()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("135,215D;4,140D;3.7615819e-37;2::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(10)
      gg.editAll("130", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.setRanges(gg.REGION_BAD)
      gg.searchNumber("194D;3.7615819e-37;2;-1;1;-127::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(10)
      gg.editAll("130", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.toast("WH450 ᴀᴄᴛɪᴠᴇ ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function WHFS()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("2.718519e-43F;3.7615819e-37F;2.0F;-1.0F;1.0F;-127.0F;0.00999999978F::200", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber(2, gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(3)
      gg.editAll("2.001", gg.TYPE_FLOAT)
      gg.searchNumber(2, gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(10)
      gg.editAll("120", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.setRanges(gg.REGION_BAD)
      gg.searchNumber("5.8013756e-42F;-5.5695588e-40F;2.0F::100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(3)
      gg.editAll("2.001", gg.TYPE_FLOAT)
      gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(10)
      gg.editAll("120", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.toast("Wallhack Fix Scope ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function WH400()
      gg.clearResults()
      gg.setRanges(gg.REGION_C_ALLOC)
      gg.searchNumber("228;1,073,741,824;1,073,741,824;229;-1,082,130,432:29", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("1,073,741,824", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(30)
      gg.editAll("1,123,024,896", gg.TYPE_DWORD)
      gg.clearResults()
      gg.setRanges(gg.REGION_C_ALLOC)
      gg.searchNumber("3.3631163e-44;2.0;3.5032462e-44;-1.0;3.643376e-44;3.7835059e-44;-1.0;3.9236357e-44;4.0637655e-44;1.0;-127.0:129", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(100)
      gg.editAll("120", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.toast("WH400 ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function WH410()
      gg.clearResults()
      gg.setRanges(gg.REGION_C_HEAP)
      gg.searchNumber("3.3631163e-44;2.0;3.5032462e-44;-1.0;3.643376e-44;3.7835059e-44;-1.0;3.9236357e-44;4.0637655e-44;1.0;-127.0:129", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(100)
      gg.editAll("120", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.searchNumber("3.1809475e-43;3.1949605e-43;2.0;3.2089735e-43:53", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(100)
      gg.editAll("120", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.setRanges(gg.REGION_C_HEAP)
      gg.searchNumber("3.2229865e-43F;2.0F;-1.0F;-1.0F;2.0F:145", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(360)
      gg.editAll("150", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.toast("WH410 ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function WH415()
      gg.clearResults()
      gg.setRanges(gg.REGION_C_HEAP)
      gg.searchNumber("228;1,073,741,824;1,073,741,824;229;-1,082,130,432:29", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("1,073,741,824", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(30)
      gg.editAll("1,123,024,896", gg.TYPE_DWORD)
      gg.clearResults()
      gg.setRanges(gg.REGION_C_HEAP)
      gg.searchNumber("3.3631163e-44;2.0;3.5032462e-44;-1.0;3.643376e-44;3.7835059e-44;-1.0;3.9236357e-44;4.0637655e-44;1.0;-127.0:129", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(100)
      gg.editAll("120", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.searchNumber("3.1809475e-43;3.1949605e-43;2.0;3.2089735e-43:53", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(100)
      gg.editAll("120", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.toast("WH415 ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function WH665(...)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber('2.0F;1.66231134e-19F;0.0F;9.21942286e-41F;7.23035964e-15F;2.37549734116F;4.40284136e-29F;2.25000905991F;3.58159416e-39F;1.66433004e10F::37', 16, false, 536870912, 0, -1)
  gg.searchNumber('2', 16, false, 536870912, 0, -1)
  gg.refineAddress('200')
  gg.getResults(25)
  gg.editAll('120', 16)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber('2.0F;-1.0F;0.0F;1.0F;-127.0F;0.24022650719F;0.69314718246F;0.00999999978F;-0.0F;0.0F::37', 16, false, 536870912, 0, -1)
  gg.searchNumber('2', 16, false, 536870912, 0, -1)
  gg.refineAddress('930')
  gg.getResults(25)
  gg.editAll('120', 16)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber('2', 16, false, 536870912, 0, -1)
  gg.refineAddress('A8C')
  gg.getResults(25)
  gg.editAll('120', 16)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber('2', 16, false, 536870912, 0, -1)
  gg.refineAddress('B10')
  gg.getResults(25)
  gg.editAll('120', 16)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber('2', 16, false, 536870912, 0, -1)
  gg.refineAddress('588')
  gg.getResults(25)
  gg.editAll('999', 16)
  gg.clearResults()
  gg.toast('WALLHACK [SnapDragon 665] Activated')
  
end

function FIXWH(...)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber('5.2806111e-40;6.50000333786;3.7615819e-37;2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(20)
  gg.editAll('9999', gg.TYPE_FLOAT)
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber('1.1202011e-19;1.1202015e-19;3.7615819e-37;255.0;2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(20)
  gg.editAll('9999', gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast('🛠️ Fix Blink 430-835 🛠️')
end
function WH600()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("4,140D;4.7408166e21F;4.7223665e21;0D;0D;0D;0D;0D;0D;-0.0F;2.0F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(30)
      gg.editAll("120", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.setRanges(gg.REGION_BAD)
      gg.searchNumber("2.718519e-43;2.0F;-1.0F;1.0F;-127F;0.24022650719F;-0.0", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(30)
      gg.editAll("120", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.toast("WH600 ᴀᴄᴛɪᴠᴇ ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
function WH610()
      gg.clearResults()
      gg.setRanges(gg.REGION_BAD)
      gg.searchNumber("4,140D;4.7408166e21F;4.7223665e21;0D;0D;0D;0D;0D;0D;-0.0F;2.0F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(30)
      gg.editAll("120", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.setRanges(gg.REGION_BAD)
      gg.searchNumber("2.718519e-43;2.0F;-1.0F;1.0F;-127F;0.24022650719F;-0.0", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(30)
      gg.editAll("120", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.toast("WH610 ᴀᴄᴛɪᴠᴇ ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
function WH615()
      gg.clearResults()
      gg.setRanges(gg.REGION_C_HEAP)
      gg.searchNumber("3.2229865e-43;2.0;-1.0;-1.0;2.0:145", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(100)
      gg.editAll("122", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.setRanges(gg.REGION_C_HEAP)
      gg.searchNumber("3.3631163e-44;2.0;3.5032462e-44;-1.0;3.643376e-44;3.7835059e-44;-1.0;3.9236357e-44;4.0637655e-44;1.0;-127.0:129", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(100)
      gg.editAll("120", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.searchNumber("3.1809475e-43;3.1949605e-43;2.0;3.2089735e-43:53", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(100)
      gg.editAll("120", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.toast("WH615 ᴀᴄᴛɪᴠᴇ ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
function WH616()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("4,140D;4.7408166e21F;4.7223665e21;0D;0D;0D;0D;0D;0D;-0.0F;2.0F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(30)
      gg.editAll("120", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.setRanges(gg.REGION_BAD)
      gg.searchNumber("2.718519e-43;2.0F;-1.0F;1.0F;-127F;0.24022650719F;-0.0", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(30)
      gg.editAll("120", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.toast("WH616 ᴀᴄᴛɪᴠᴇ ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
function WH625()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("135,215D;4,140D;3.7615819e-37;2::", gg.POINTER_WRITABLE, false, gg.SIGN_FUZZY_EQUAL, 0, -1)
      gg.searchNumber("2", gg.POINTER_WRITABLE, false, gg.SIGN_FUZZY_EQUAL, 0, -1)
      gg.getResults(10)
      gg.editAll("130", gg.POINTER_WRITABLE)
      gg.clearResults()
      gg.setRanges(gg.REGION_BAD)
      gg.searchNumber("194D;3.7615819e-37;2;-1;1;-127::", gg.POINTER_WRITABLE, false, gg.SIGN_FUZZY_EQUAL, 0, -1)
      gg.searchNumber("2", gg.POINTER_WRITABLE, false, gg.SIGN_FUZZY_EQUAL, 0, -1)
      gg.getResults(10)
      gg.editAll("130", gg.POINTER_WRITABLE)
      gg.clearResults()
      gg.toast("WH625 ᴀᴄᴛɪᴠᴇ ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    
function FIXWH2(...)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber('5.2806111e-40;6.50000333786;3.7615819e-37;2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(20)
  gg.editAll('9999', gg.TYPE_FLOAT)
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber('1.1202011e-19;1.1202015e-19;3.7615819e-37;255.0;2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(20)
  gg.editAll('9999', gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast('🛠️ Fix Blink 845-855 🛠️')
end

function FIXSCOPE(...)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber('2.718519e-43F;3.7615819e-37F;2.0F;-1.0F;1.0F;-127.0F;0.00999999978F::200', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber(2, gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(3)
  gg.editAll('2.001', gg.TYPE_FLOAT)
  gg.searchNumber(2, gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll('120', gg.TYPE_FLOAT)
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber('5.8013756e-42F;-5.5695588e-40F;2.0F::100', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(3)
  gg.editAll('2.001', gg.TYPE_FLOAT)
  gg.searchNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll('120', gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast('🛠️ Fix Scope 🛠️')
end

function WH425(...)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber('2.9427268e-44;2.0;3.0828566e-44;-1.0;3.2229865e-44;3.3631163e-44;3.643376e-44:97', 16, false, 536870912, 0, -1)
  gg.searchNumber('2', 16, false, 536870912, 0, -1)
  gg.getResults(100)
  gg.editAll('120', 16)
  gg.clearResults()
  gg.searchNumber('3.1529215e-43;2.0F;3.1669345e-43F;3.1809475e-43:49', 16, false, 536870912, 0, -1)
  gg.searchNumber('2', 16, false, 536870912, 0, -1)
  gg.getResults(100)
  gg.editAll('120', 16)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber('227;1,073,741,824;1,073,741,824;-1,082,130,432;1,073,741,824:49', 4, false, 536870912, 0, -1)
  gg.searchNumber('1,073,741,824', 4, false, 536870912, 0, -1)
  gg.getResults(100)
  gg.editAll('1,123,024,896', 4)
  gg.clearResults()
  gg.toast('WALLHACK [SnapDragon 425] Activated')
  
end

function WH630()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("2;1.8947657e-40;5.8013756e-42", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.refineAddress("504")
      gg.getResults(20)
      gg.editAll("120", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.searchNumber("2.718519e-43;3.7615819e-37;2;-1;1;-127", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.refineAddress("900")
      gg.getResults(20)
      gg.editAll("120", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.toast("WH630 ᴀᴄᴛɪᴠᴇ ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
function WH632()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("2;1.8947657e-40;5.8013756e-42", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.refineAddress("504")
      gg.getResults(20)
      gg.editAll("120", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.searchNumber("2.718519e-43;3.7615819e-37;2;-1;1;-127", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.refineAddress("900")
      gg.getResults(20)
      gg.editAll("120", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.toast("WH632 ᴀᴄᴛɪᴠᴇ ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
function WH650()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("2.718519e-43F;3.7615819e-37F;2.0F;-1.0F;1.0F;-127.0F;0.00999999978F::200", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber(2, gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(30)
      gg.editAll("120", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.searchNumber("5.8013756e-42F;-5.5695588e-40F;2.0F::100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber(2, gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(30)
      gg.editAll("120", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.toast("WH650 ᴀᴄᴛɪᴠᴇ ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function WH653()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("2.718519e-43F;3.7615819e-37F;2.0F;-1.0F;1.0F;-127.0F;0.00999999978F::200", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber(2, gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(30)
      gg.editAll("120", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.searchNumber("5.8013756e-42F;-5.5695588e-40F;2.0F::100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber(2, gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(30)
      gg.editAll("120", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.toast("653 ᴀᴄᴛɪᴠᴇ ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
function WH821()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("135,215D;4,140D;3.7615819e-37;2::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(10)
      gg.editAll("130", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.setRanges(gg.REGION_BAD)
      gg.searchNumber("194D;3.7615819e-37;2;-1;1;-127::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(10)
      gg.editAll("130", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.toast("WH821 ᴀᴄᴛɪᴠᴇ ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
function WH715()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.refineAddress("200", -1, gg.TYPE_FLOAT, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(20)
      gg.editAll("120", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.refineAddress("930", -1, gg.TYPE_FLOAT, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(20)
      gg.editAll("120", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.toast("WH715 ᴀᴄᴛɪᴠᴇ ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
function WH712()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("274,677,779D;2.25000452995;2;1.6623054e-19", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(20)
      gg.editAll("130", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("218D;3.7615819e-37;2;-1;1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(10)
      gg.editAll("130", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.setRanges(gg.REGION_BAD)
      gg.searchNumber("95D;2;9.2194229e-41", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(15)
      gg.editAll("130", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.setRanges(gg.REGION_BAD)
      gg.searchNumber("206D;3.7615819e-37;2;-1;1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(10)
      gg.editAll("130", gg.TYPE_FLOAT)
      gg.toast("WH712 ᴀᴄᴛɪᴠᴇ ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
  function WH800()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("5.1097599e21;2.0;1.6623071e-19;3.6734297e-39;1.66433e10::17", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(30)
      gg.editAll("120", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.searchNumber("2.0;-1.0;0.0;1.0;-127.0::17", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(30)
      gg.editAll("120", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.toast("WH800 ᴀᴄᴛɪᴠᴇ ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
  function WH801()
      gg.clearResults()
      gg.setRanges(gg.REGION_C_ALLOC)
      gg.searchNumber("3.15292154e-43;2.0;2.0;3.1949605e-43:73", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      revert = gg.getResults(3000, nil, nil, nil, nil, nil, nil, nil, nil)
      gg.editAll("120", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.searchNumber("3.15292154e-43;2.0;2.0;3.1949605e-43;4.34402524e-44;2.0;4.62428493e-44;4.76441478e-44:241", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      revert = gg.getResults(3000, nil, nil, nil, nil, nil, nil, nil, nil)
      gg.editAll("120", gg.TYPE_FLOAT)
      gg.toast("WH801 ᴀᴄᴛɪᴠᴇ ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
   function WH805()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("4,140D;4.7408166e21F;4.7223665e21;0D;0D;0D;0D;0D;0D;-0.0F;2.0F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(30)
      gg.editAll("120", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.setRanges(gg.REGION_BAD)
      gg.searchNumber("2.718519e-43;2.0F;-1.0F;1.0F;-127F;0.24022650719F;-0.0", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(30)
      gg.editAll("120", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.toast("WH805 ᴀᴄᴛɪᴠᴇ ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function WH808()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("4,140D;4.7408166e21F;4.7223665e21;0D;0D;0D;0D;0D;0D;-0.0F;2.0F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(30)
      gg.editAll("120", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.setRanges(gg.REGION_BAD)
      gg.searchNumber("2.718519e-43;2.0F;-1.0F;1.0F;-127F;0.24022650719F;-0.0", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(30)
      gg.editAll("120", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.toast("WH808 ᴀᴄᴛɪᴠᴇ ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
function WH430(...)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber('2;1.8947657e-40;5.8013756e-42', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(999)
  gg.editAll('120', gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber('2.718519e-43;3.7615819e-37;2;-1;1;-127', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(999)
  gg.editAll('120', gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast('WALLHACK [SnapDragon 430] Activated')
  
end

function WH625(...)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber('135,215D;4,140D;3.7615819e-37;2::', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll('130', gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber('194D;3.7615819e-37;2;-1;1;-127::', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll('130', gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast('WALLHACK [SnapDragon 625] Activated')
  
end

function WH6252(...)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber('5.79227989e21;-5.56955884e-40;2.0;1.39125666e-19;2.0:9285', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(50)
  gg.editAll('120', gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast('WALLHACK [SnapDragon 625] Activated')
 
end

function WH636(...)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber('5.1097599e21;2.0;1.6623071e-19;3.6734297e-39;1.66433e10::17', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll('120', gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber('2.0;-1.0;0.0;1.0;-127.0::17', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll('120', gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast('WALLHACK [SnapDragon 636] Activated')
  
end

function WH660(...)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber('135,215D;4,140D;3.7615819e-37;2::', 16, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber('2', 16, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll('130', 16)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber('194D;3.7615819e-37;2;-1;1;-127::', 16, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber('2', 16, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll('130', 16)
  gg.clearResults()
  gg.toast('WALLHACK [SnapDragon 660] Activated')
 
end

function WH675(...)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber('274,677,779D;2.25000452995;2;1.6623054e-19', 16, false, 536870912, 0, -1)
  gg.searchNumber('2', 16, false, 536870912, 0, -1)
  gg.getResults(20)
  gg.editAll('130', 16)
  gg.toast('25%')
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber('218D;3.7615819e-37;2;-1;1', 16, false, 536870912, 0, -1)
  gg.searchNumber('2', 16, false, 536870912, 0, -1)
  gg.getResults(10)
  gg.editAll('130', 16)
  gg.toast('50%')
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber('95D;2;9.2194229e-41', 16, false, 536870912, 0, -1)
  gg.searchNumber('2', 16, false, 536870912, 0, -1)
  gg.getResults(15)
  gg.editAll('130', 16)
  gg.toast('75%')
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber('206D;3.7615819e-37;2;-1;1', 16, false, 536870912, 0, -1)
  gg.searchNumber('2', 16, false, 536870912, 0, -1)
  gg.getResults(10)
  gg.editAll('130', 16)
  gg.clearResults()
  gg.toast('WALLHACK [SnapDragon 675] Activated')
  
end

function WH6752(...)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineAddress('200')
  gg.getResults(999)
  gg.editAll('120', gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineAddress('930')
  gg.getResults(999)
  gg.editAll('120', gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast('WALLHACK [SnapDragon 675] Activated')
end

function WH710(...)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber('2;1.8947657e-40;5.8013756e-42', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll('120', gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber('2.718519e-43;3.7615819e-37;2;-1;1;-127', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll('120', gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast('WALLHACK [SnapDragon 710] Activated')

end

function WH810(...)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber('2;1.8947657e-40;5.8013756e-42', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll('120', gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber('2.718519e-43;3.7615819e-37;2;-1;1;-127', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll('120', gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast('WALLHACK [SnapDragon 810] Activated')
  gg.clearResults()

end

function WH820(...)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber('2;1.8947657e-40;5.8013756e-42', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll('120', gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber('2.718519e-43;3.7615819e-37;2;-1;1;-127', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll('120', gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast('WALLHACK [SnapDragon 820] Activated')

end

function WH835(...)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber('2;1.8947657e-40;5.8013756e-42', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll('120', gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber('2.718519e-43;3.7615819e-37;2;-1;1;-127', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll('120', gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast('WALLHACK [SnapDragon 835] Activated')
 
end

function WH845(...)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineAddress('200', -1, gg.TYPE_FLOAT, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(25)
  gg.editAll('120', gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineAddress('930', -1, gg.TYPE_FLOAT, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(25)
  gg.editAll('120', gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast('WALLHACK [SnapDragon 845] Activated')
  
end

function WH855()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber('95D;2;9.2194229e-41::100', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll('120', gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber('2;-1;0;1;-127;0.24022650719;0.69314718246;0.00999999978::30', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll('120', gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast('WALLHACK [SnapDragon 855]ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀr')
  
end
    
    function C1()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("32769;-2,134900724:21", gg.TYPE_DWORD, false)
      gg.searchNumber("32769", gg.TYPE_DWORD, false)
      revert = gg.getResults(10, nil, nil, nil, nil, nil, nil, nil, nil)
      for i, i in ipairs((gg.getResults(10, nil, nil, nil, nil, nil, nil, nil, nil))) do
        if i.flags == gg.TYPE_FLOAT then
          i.value = "SHAFUNC(STRFUNC(DATABLE[414]))"
          i.freeze = true
        end
      end
      gg.addListItems((gg.getResults(10, nil, nil, nil, nil, nil, nil, nil, nil)))
      gg.clearResults()
      gg.toast("C.Green ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function C2()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("256D;8,200D;13D", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResultsCount()
      gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(20)
      gg.editAll("8199", gg.TYPE_DWORD)
      gg.toast("C.Red ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ ")
    end
    
    function C3()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("8,196D;8,192D;8,200D::", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(10)
      gg.editAll("7", gg.TYPE_DWORD)
      gg.clearResults()
      gg.toast("C.Red V2 ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function C4()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("256D;8,200D;13D", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResultsCount()
      gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(20)
      gg.editAll("8198", gg.TYPE_DWORD)
      gg.toast("C.Yellow ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
function WHA()
      gg.setRanges(gg.REGION_BAD)
      gg.searchNumber("5.6447121e21;-8.3252823e-40;4.9252852e21::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("-8.3252823e-40", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(100)
      gg.editAll("6444", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.setRanges(gg.REGION_BAD)
      gg.searchNumber("4.9068373e21;-3.5875931e-39;4.8699618e21::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("-3.5875931e-39", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(100)
      gg.editAll("6444", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.setRanges(gg.REGION_BAD)
      gg.searchNumber("5.0544113e21;-3.4039221e-39;4.8699607e21::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("-3.4039221e-39", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(100)
      gg.editAll("6444", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.setRanges(gg.REGION_BAD)
      gg.searchNumber("5.6447206e21;-1.0161992e-39;4.9068396e21::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("-1.0161992e-39", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(100)
      gg.editAll("6444", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.setRanges(gg.REGION_BAD)
      gg.searchNumber("4.7223665e21;-8.3246237e-40;4.8330515e21::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("-8.3246237e-40", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(100)
      gg.editAll("6444", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.setRanges(gg.REGION_BAD)
      gg.searchNumber("4.7408149e21;-5.5695588e-40;4.814603e21::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("-5.5695588e-40", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(6)
      gg.editAll("6444", gg.TYPE_FLOAT)
      gg.toast("ᴀᴄᴛɪᴠᴇ ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function WHAD()
      gg.clearResults()
      gg.setRanges(gg.REGION_BAD)
      gg.searchNumber("135,215D;4,140D;3.7615819e-37;2::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(10)
      gg.editAll("130", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.setRanges(gg.REGION_BAD)
      gg.searchNumber("194D;3.7615819e-37;2;-1;1;-127::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(10)
      gg.editAll("130", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.toast("WH ᴀᴄᴛɪᴠᴇ ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function WHFB()
      gg.clearResults()
      gg.setRanges(gg.REGION_BAD)
      gg.searchNumber("1.3312335e-43;120;1.6623075e-19;9.2194229e-41", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("120", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(1)
      gg.editAll("2", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.setRanges(gg.REGION_BAD)
      gg.searchNumber("4.8146053e21;1.3912556e-19;1.5414283e-44;120;-1;1;-127", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("120", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(1)
      gg.editAll("2", gg.TYPE_FLOAT)
      gg.toast("Wallhack Fix Blink ᴀᴄᴛɪᴠᴇ ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function WHFS()
      gg.clearResults()
      gg.setRanges(gg.REGION_BAD)
      gg.searchNumber("2.718519e-43F;3.7615819e-37F;2.0F;-1.0F;1.0F;-127.0F;0.00999999978F::200", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber(2, gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(3)
      gg.editAll("2.001", gg.TYPE_FLOAT)
      gg.searchNumber(2, gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(10)
      gg.editAll("120", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.setRanges(gg.REGION_BAD)
      gg.searchNumber("5.8013756e-42F;-5.5695588e-40F;2.0F::100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(3)
      gg.editAll("2.001", gg.TYPE_FLOAT)
      gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(10)
      gg.editAll("120", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.toast("Wallhack Fix Scope ᴀᴄᴛɪᴠᴇ ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    
    function C5()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("8,196D;8,192D;8,200D::", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(10)
      gg.editAll("6", gg.TYPE_DWORD)
      gg.clearResults()
      gg.toast("C.Yellow V2 ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function C6()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("32768;-2134900726;32769;-2134900725;32770;-2134900724::", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("32768;32770::", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      revert = gg.getResults(100, nil, nil, nil, nil, nil, nil, nil, nil)
      for i, i in ipairs((gg.getResults(100, nil, nil, nil, nil, nil, nil, nil, nil))) do
        if i.flags == gg.TYPE_DWORD then
          i.value = "SHAFUNC(STRFUNC(DATABLE[434]))"
          i.freeze = true
        end
      end
      gg.addListItems((gg.getResults(100, nil, nil, nil, nil, nil, nil, nil, nil)))
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("32768", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("32768", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(100)
      gg.clearResults()
      gg.toast("C.Pink ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function C7()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("256D;8,200D;13D", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResultsCount()
      gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(20)
      gg.editAll("8197", gg.TYPE_DWORD)
      gg.toast("C.White ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function C8()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("8,196D;8,192D;8,200D::", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(10)
      gg.editAll("4", gg.TYPE_DWORD)
      gg.clearResults()
      gg.toast("C.White V2 ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function C9()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.setRanges(131072)
      gg.searchNumber("856128", 4, false, 536870912, 0, -1)
      gg.getResults(4)
      gg.editAll("856118", 4)
      gg.clearResults()
      gg.searchNumber("196610;1280;196608:25", 4, false, 536870912, 0, -1)
      gg.searchNumber("196608", 4, false)
      gg.getResults(10)
      gg.editAll("9999", 4)
      gg.clearResults()
      gg.toast("C.400 Yellow ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function C10()
      gg.clearResults()
      gg.setRanges(gg.REGION_BAD)
      gg.searchNumber("8,201;8,202;538,968,081:29", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("8202", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(1)
      gg.editAll("8", gg.REGION_VIDEO or gg.REGION_BAD)
      gg.clearResults()
      gg.toast("C.400/410 Green ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function C11()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("200761;92;8204;856124;108;196610:409", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.refineNumber("8204", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(1000)
      gg.editAll("8500", gg.TYPE_DWORD)
      gg.setRanges(gg.REGION_BAD)
      gg.searchNumber("856,128", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(3)
      gg.editAll("856093", gg.TYPE_DWORD)
      gg.clearResults()
      gg.searchNumber("196,610;1,280;196,608::25", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("196608", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(5)
      gg.editAll("9999", gg.TYPE_DWORD)
      gg.clearResults()
      gg.toast("C.415 Green ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function C12()
      C425 = gg.choice({
        "[[🇲🇲]]  𝐂 𝟒𝟐𝟓 𝐌𝐢𝐱",
        "[[🇲🇲]]  𝐂 𝟒𝟐𝟓 𝐑𝐞𝐝",
        "[[🇲🇲]]  𝐂 𝟒𝟐𝟓 𝐘𝐞𝐥𝐥𝐨𝐰",
        "[[🇲🇲]]  𝐂 𝟒𝟐𝟓 𝐆𝐫𝐞𝐞𝐧",
        "◦•●◉✿𝐁𝐚𝐜𝐤✿◉●•◦"
      }, nil, "✭❈ʟᴛɴs☆ᴏɴʟɪɴᴇ☆sᴄʀɪᴘᴛ☆ᴠᴇʀsɪᴏɴ☆ɴᴀᴛsᴏᴇ")
      
        if C425 == 1 then
          M425()
        end
        if C425 == 2 then
          R425()
        end
        if C425 == 3 then
          Y425()
        end
        if C425 == 4 then
          G425()
        end
        if C425 == 5 then
          WC()
        end
      
      PENGKIKGM = -1
    end
    
    function M425()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("856128", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(4)
      gg.editAll("99", gg.TYPE_DWORD)
      gg.clearResults()
      gg.searchNumber("200761;92;8204;856124;108;196610:409", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.refineNumber("8204", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      revert = gg.getResults(1000, nil, nil, nil, nil, nil, nil, nil, nil)
      gg.editAll("1", gg.TYPE_DWORD)
      gg.toast("C.425 Mix ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function R425()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("227;1,073,741,824;1,073,741,824;-1,082,130,432;1,073,741,824:49", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("1,073,741,824", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(100)
      gg.editAll("1,123,024,896", gg.TYPE_DWORD)
      gg.clearResults()
      gg.toast("50%")
      gg.setRanges(gg.REGION_BAD)
      gg.searchNumber("8204", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(30, nil, nil, nil, nil, nil, nil, nil, nil)
      gg.editAll("11", gg.TYPE_DWORD)
      gg.clearResults()
      gg.toast("C.425 Red ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function Y425()
      gg.clearResults()
      gg.setRanges(131072)
      gg.searchNumber("4060000BhA;0000200ChA", 4, false, 536870912, 0, -1)
      gg.refineNumber("8204", 4, false, 536870912, 0, -1)
      gg.getResults(1000, nil, nil, nil, nil, nil, nil, nil, nil)
      gg.editAll("75", 4)
      gg.clearResults()
      gg.toast("50%")
      gg.setRanges(4)
      gg.searchNumber("227;1,073,741,824;1,073,741,824;-1,082,130,432;1,073,741,824:49", 4, false, 536870912, 0, -1)
      gg.searchNumber("1,073,741,824", 4, false, 536870912, 0, -1)
      gg.getResults(100)
      gg.editAll("1,123,024,896", 4)
      gg.clearResults()
      gg.setRanges(131072)
      gg.searchNumber("8204", 4, false, 536870912, 0, -1)
      gg.getResults(500, nil, nil, nil, nil, nil, nil, nil, nil)
      gg.editAll("10", 4)
      gg.clearResults()
      gg.toast("C.425 Yellow ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function G425()
      gg.clearResults()
      gg.setRanges(131072)
      gg.searchNumber("4060000BhA;0000200ChA", 4, false, 536870912, 0, -1)
      gg.refineNumber("8204", 4, false, 536870912, 0, -1)
      gg.getResults(1000, nil, nil, nil, nil, nil, nil, nil, nil)
      gg.editAll("6666", 4)
      gg.clearResults()
      gg.toast("C.425 Green ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
      gg.clearResults()
    end
    
    function C13()
      C435 = gg.choice({
        "[[🇲🇲]]  𝐂 𝟒𝟑𝟓 𝐆𝐫𝐞𝐞𝐧",
        "[[🇲🇲]]  𝐂 𝟒𝟑𝟓 𝐑𝐞𝐝",
        "◦•●◉✿𝐁𝐚𝐜𝐤✿◉●•◦"
      }, nil, "✭❈ʟᴛɴs☆ᴏɴʟɪɴᴇ☆sᴄʀɪᴘᴛ☆ᴠᴇʀsɪᴏɴ☆ɴᴀᴛsᴏᴇ")
      
        if C435 == 1 then
          G435()
        end
        if C435 == 2 then
          R435()
        end
        if C435 == 3 then
          WC()
        end
      
      PENGKIKGM = -1
    end
    
    function G435()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("200761;92;8204;856124;108;196610:409", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.refineNumber("8204", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(1000, nil, nil, nil, nil, nil, nil, nil, nil)
      gg.editAll("99", gg.TYPE_DWORD)
      gg.clearResults()
      gg.toast("C.435 Green ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function R435()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("1,661,239,308;8,200;1,194,380,045:9", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(6)
      gg.editAll("7", gg.TYPE_DWORD)
      gg.toast("C.435 Red ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function C14()
      C450 = gg.choice({
        "[[🇲🇲]]  𝐂 𝟒𝟓𝟎 𝐑𝐞𝐝",
        "[[🇲🇲]]  𝐂 𝟒𝟓𝟎 𝐘𝐞𝐥𝐥𝐨𝐰",
        "◦•●◉✿𝐁𝐚𝐜𝐤✿◉●•◦"
      }, nil, "✭❈ʟᴛɴs☆ᴏɴʟɪɴᴇ☆sᴄʀɪᴘᴛ☆ᴠᴇʀsɪᴏɴ☆ɴᴀᴛsᴏᴇ")
      
        if C450 == 1 then
          R450()
        end
        if C450 == 2 then
          Y450()
        end
        if C450 == 3 then
          WC()
        end
      
      PENGKIKGM = -1
    end
    
    function R450()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("4060000BhA;0000200ChA", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.refineNumber("8204", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(1000, nil, nil, nil, nil, nil, nil, nil, nil)
      gg.editAll("75", gg.TYPE_DWORD)
      gg.clearResults()
      gg.toast("C.450 Red ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function Y450()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("1.3912525e-19F;8200;96", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(10)
      gg.editAll("6", gg.TYPE_DWORD)
      gg.toast("C.450 Yellow ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function C15()
      C615 = gg.choice({
        "[[🇲🇲]]  C 615 Cyan",
        "[[🇲🇲]]  C 615 Green",
        "[[🇲🇲]]  C 615 Yellow",
        "[ BACK ]"
      }, nil, "✭❈ʟᴛɴs☆ᴏɴʟɪɴᴇ☆sᴄʀɪᴘᴛ☆ᴠᴇʀsɪᴏɴ☆ɴᴀᴛsᴏᴇ")
      
        if C615 == 1 then
          CN615()
        end
        if C615 == 2 then
          G615()
        end
        if C615 == 3 then
          Y615()
        end
        if C615 == 4 then
          WC()
        end
     
      PENGKIKGM = -1
    end
    
    function CN615()
      gg.clearResults()
      gg.setRanges(gg.REGION_BAD)
      gg.searchNumber("196,608D;196,608D:409", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("196,608;196,608", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(25)
      gg.editAll("196619", gg.TYPE_DWORD)
      gg.toast("C.615 Cyan ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function G615()
      gg.clearResults()
      gg.setRanges(gg.REGION_BAD)
      gg.searchNumber("8.201D;8.202D;538.968.081D:29", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("8201;8202;538968081", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(5)
      gg.editAll("8", gg.TYPE_DWORD)
      gg.clearResults()
      gg.toast("C.615 Green ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function Y615()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("1D;2D;91D:25", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("1;2;91", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(5)
      gg.editAll("5", gg.TYPE_DWORD)
      gg.clearResults()
      gg.toast("C.615 Yellow ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function C16()
      C636 = gg.choice({
    "[[🇲🇲]]𝐂 636 𝐘𝐞𝐥𝐥𝐨𝐰",
    "[[🇲🇲]]𝐂 636 𝐑𝐞𝐝",
    "[[🇲🇲]]𝐂 636 𝐖𝐡𝐢𝐭𝐞",
        "◦•●◉✿𝐁𝐚𝐜𝐤✿◉●•◦"
      }, nil, "✭❈ʟᴛɴs☆ᴏɴʟɪɴᴇ☆sᴄʀɪᴘᴛ☆ᴠᴇʀsɪᴏɴ☆ɴᴀᴛsᴏᴇ")
      
        if C636 == 1 then
          Y636()
        end
        if C636 == 2 then
          R636()
        end
        if C636 == 3 then
          W636()
        end
        if C636 == 4 then
          WC()
        end
      
      PENGKIKGM = -1
    end
    
    function Y636()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("256D;8,200D;13D", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResultsCount()
      gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(20)
      gg.editAll("8198", gg.TYPE_DWORD)
      gg.toast("C.636 Yellow ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function R636()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("256D;8,200D;13D", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResultsCount()
      gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(20)
      gg.editAll("8199", gg.TYPE_DWORD)
      gg.toast("C.636 Red ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function W636()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("256D;8,200D;13D", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResultsCount()
      gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(20)
      gg.editAll("8197", gg.TYPE_DWORD)
      gg.toast("C.636 Red ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function C17()
      C660 = gg.choice({
        "[[🇲🇲]]  𝐂 660 𝐆𝐫𝐞𝐞𝐧",
        "[[🇲🇲]]  𝐂 660 𝐑𝐞𝐝",
        "[[🇲🇲]]  𝐂 660 𝐘𝐞𝐥𝐥𝐨𝐰",
        "◦•●◉✿𝐁𝐚𝐜𝐤✿◉●•◦"
      }, nil, "✭❈ʟᴛɴs☆ᴏɴʟɪɴᴇ☆sᴄʀɪᴘᴛ☆ᴠᴇʀsɪᴏɴ☆ɴᴀᴛsᴏᴇ")
      
        if C660 == 1 then
          G660()
        end
        if C660 == 2 then
          R660()
        end
        if C660 == 3 then
          Y660()
        end
        if C660 == 4 then
          WC()
        end
     
      PENGKIKGM = -1
    end
    
    function G660()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("32769", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.refineNumber("32769", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.refineAddress("518")
      gg.getResults(9999)
      gg.editAll("32772", gg.TYPE_DWORD)
      gg.clearResults()
      gg.toast("C.660 Green ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function R660()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("96D;8200;196,615", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(10)
      gg.editAll("7", gg.TYPE_DWORD)
      gg.toast("C.660 Red ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function Y660()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("536889616;8200;1194344458:9", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
      gg.refineNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
      revert = gg.getResults(2, nil, nil, nil, nil, nil, nil, nil, nil)
      gg.editAll("6", gg.TYPE_DWORD)
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("1669398530;8200;1194380045:9", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
      gg.refineNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
      revert = gg.getResults(2, nil, nil, nil, nil, nil, nil, nil, nil)
      gg.editAll("6", gg.TYPE_DWORD)
      gg.clearResults()
      gg.toast("C.660 Yellow ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function C18()
      C665 = gg.choice({
        "[[🇲🇲]]  𝐂 665 𝐑𝐞𝐝",
        "[[🇲🇲]]  𝐂 665 𝐘𝐞𝐥𝐥𝐨𝐰",
        "◦•●◉✿𝐁𝐚𝐜𝐤✿◉●•◦"
      }, nil, "✭❈ʟᴛɴs☆ᴏɴʟɪɴᴇ☆sᴄʀɪᴘᴛ☆ᴠᴇʀsɪᴏɴ☆ɴᴀᴛsᴏᴇ")
      
        if C665 == 1 then
          R665()
        end
        if C665 == 2 then
          Y665()
        end
        if C665 == 3 then
          WC()
        end
      
      PENGKIKGM = -1
    end
    
    function B665()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("32.773D;50.331.648D;1.039.516.303D;1.025.761.280D;1.123.024.896D;1.050.800.659D;1.065.353.216D;1.170.939.904D;1.050.222.592D;1.058.422.784D::177", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("32773", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(25)
      gg.editAll("7", gg.TYPE_DWORD)
      gg.clearResults()
      gg.toast("C.665 Blue ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function G665()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("69,897;147,457;69,739", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(10)
      gg.editAll("7", gg.TYPE_DWORD)
      gg.toast("C.665 Green ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function R665()
      gg.clearResults()
      gg.searchNumber("8,200;1,101,004,840;2,097,154;1,661,911,061;2,162,708;1,661,911,056:1109", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(100)
      gg.editAll("6", gg.TYPE_DWORD)
      gg.toast("C.665 Red ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function kambing()
      gg.clearResults()
      gg.setRanges(gg.REGION_C_DATA)
      gg.searchNumber("1.1754945e-37", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(1000)
      gg.editAll("0", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(1000)
      gg.editAll("0", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("0", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(1000)
      gg.editAll("1.1754945e-37", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.clearResults()
      gg.toast("ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function Y665()
      gg.clearResults()
      gg.searchNumber("8,200;1,194,344,477;8,201:9", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(100)
      gg.editAll("7", gg.TYPE_DWORD)
      gg.toast("C.665 Yellow ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
      gg.clearResults()
    end
    
    function C19()
      C675 = gg.choice({
        "[[🇲🇲]]  𝐂 675 𝐑𝐞𝐝",
        "[[🇲🇲]]  𝐂 675 𝐁𝐥𝐮𝐞",
        "[[🇲🇲]]  𝐂 675 𝐆𝐫𝐞𝐞𝐧",
        "[[🇲🇲]]  𝐂 675 𝐘𝐞𝐥𝐥𝐨𝐰",
        "◦•●◉✿𝐁𝐚𝐜𝐤✿◉●•◦"
      }, nil, "✭❈ʟᴛɴs☆ᴏɴʟɪɴᴇ☆sᴄʀɪᴘᴛ☆ᴠᴇʀsɪᴏɴ☆ɴᴀᴛsᴏᴇ")
      
        if C675 == 1 then
          R675()
        end
        if C675 == 2 then
          B675()
        end
        if C675 == 3 then
          G675()
        end
        if C675 == 4 then
          Y675()
        end
        if C675 == 5 then
          WC()
        end
     
      PENGKIKGM = -1
    end
    
    function R675()
      gg.clearResults()
      gg.searchNumber("8,200;1,101,004,840;2,097,154;1,661,911,061;2,162,708;1,661,911,056:1109", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(100)
      gg.editAll("6", gg.TYPE_DWORD)
      gg.toast("C.675 Red ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function B675()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("5,129,821,174,980,681,738", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.sleep(140)
      gg.refineNumber("5,129,821,174,980,681,738", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.sleep(140)
      gg.refineAddress("2D0", -1, gg.TYPE_QWORD, gg.SIGN_EQUAL, 0, -1)
      gg.refineNumber("5,129,821,174,980,681,738", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(1401)
      gg.editAll("5,129,821,174,980,673,543", gg.TYPE_QWORD)
      gg.clearResults()
      gg.toast("C.675 Blue ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function G675()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("5,129,822,240,132,571,145", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.sleep(140)
      gg.refineNumber("5,129,822,240,132,571,145", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.sleep(140)
      gg.refineAddress("0D8", -1, gg.TYPE_QWORD, gg.SIGN_EQUAL, 0, -1)
      gg.refineNumber("5,129,822,240,132,571,145", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(1)
      gg.editAll("5,129,822,240,132,564,055", gg.TYPE_QWORD)
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("5,129,822,240,132,571,145", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.sleep(140)
      gg.refineNumber("5,129,822,240,132,571,145", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.sleep(140)
      gg.refineAddress("0D8", -1, gg.TYPE_QWORD, gg.SIGN_EQUAL, 0, -1)
      gg.refineNumber("5,129,822,240,132,571,145", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(1)
      gg.editAll("5,129,822,240,132,564,055", gg.TYPE_QWORD)
      gg.toast("C.675 Green ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
      gg.clearResults()
    end
    
    function Y675()
      gg.clearResults()
      gg.searchNumber("8,200;1,194,344,477;8,201:9", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(100)
      gg.editAll("7", gg.TYPE_DWORD)
      gg.toast("C.675 Yellowᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
      gg.clearResults()
    end
    
    function C20()
      C710 = gg.choice({
     "[[🇲🇲]]  𝐂 𝟕𝟏𝟎 𝐑𝐞𝐝",
     "[[🇲🇲]]  𝐂 𝟕𝟏𝟎 𝐘𝐞𝐥𝐥𝐨𝐰",
     "[[🇲🇲]]  𝐂 𝟕𝟏𝟎 𝐆𝐫𝐞𝐞𝐧",
     "[[🇲🇲]]  𝐂 𝟕𝟏𝟎 𝐁𝐥𝐮𝐞 𝐒𝐞𝐚",
        "◦•●◉✿𝐁𝐚𝐜𝐤✿◉●•◦"
      }, nil, "✭❈ʟᴛɴs☆ᴏɴʟɪɴᴇ☆sᴄʀɪᴘᴛ☆ᴠᴇʀsɪᴏɴ☆ɴᴀᴛsᴏᴇ")
     
        if C710 == 1 then
          R710()
        end
        if C710 == 2 then
          Y710()
        end
        if C710 == 3 then
          G710()
        end
        if C710 == 4 then
          B710()
        end
        if C710 == 5 then
          WC()
        end
      
      PENGKIKGM = -1
    end
    
    function R710()
      gg.clearResults()
      gg.setRanges(gg.REGION_BAD)
      gg.searchNumber("1703959D;8200D;8201D:17", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.refineNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(10)
      gg.editAll("7", gg.TYPE_DWORD)
      gg.toast("C.710 Red ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function Y710()
      gg.clearResults()
      gg.setRanges(gg.REGION_BAD)
      gg.searchNumber("8201;8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(15)
      gg.editAll("7;7", gg.TYPE_DWORD)
      gg.toast("C.710 Yellow ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function BY()
      PG1 = gg.choice({
        "[[🇨🇰]][[🇨🇰]] 𝐁𝐘𝐏𝐀𝐒𝐒 𝐆𝐋𝐎𝐁𝐀𝐋",
        "[[🇰🇷]][[🇰🇷]] 𝐁𝐘𝐏𝐀𝐒𝐒 𝐊𝐎𝐑𝐄𝐀",
        "◦•●◉✿𝐁𝐚𝐜𝐤✿◉●•◦"
      }, nil, "  👉 [[ 𝟯𝟬 ]]စဣန့်✭စောင့်ပေးပါရန်✭")
      
        if PG1 == 1 then
          J1()
        end
        if PG1 == 2 then
          J2()
        end
        if PG1 == 3 then
          HOME()
        end
     
      PUBGMH = -1
    end
    
    function J1()
      gg.alert("ᴠɪᴘ ʙʏᴘᴀss ʙʏ ʟᴛɴs ᴛᴇᴀᴍ")
      gg.clearResults()
      gg.searchNumber("9|||||||||||||||||||||||||||||||||||||9|||||||||||||||||||9|||||||||||||||||||||||||||||||||||9|||||||||||||||||||||||||||||||||||9|||||||||||||||||||||||||||||||||||9|||||||||||||||||||||||||||||||||||9|||||||||||||||||||||||||||||||||||9", 4, false, 536870912, 0, -1)
      gg.getResults(1)
      gg.editAll("1|||||||||P||||||||||||9||||||||||||||||||||||||||||||||||||||||||||||||||G||||||||||||||7|||||||||||||||||||||||||||||||||||||||||||||||||||00|||||||||||||||||||||3|||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||70||||||||||||||||||||||||||||||||||||||||||||||||||||7||||||||||||||||||||||||||||||||||||||||||||||||||||8", 4)
      gg.clearResults()
      gg.setRanges(gg.REGION_C_ALLOC)
      gg.searchNumber("135682;144387", gg.TYPE_DWORD)
      gg.refineNumber("135682", gg.TYPE_DWORD)
      gg.getResults(50000)
      gg.editAll("0", gg.TYPE_DWORD)
      gg.clearResults()
      gg.setRanges(gg.REGION_C_ALLOC)
      gg.searchNumber("134658;131586", gg.TYPE_DWORD)
      gg.refineNumber("134658", gg.TYPE_DWORD)
      gg.getResults(50000)
      gg.editAll("0", gg.TYPE_DWORD)
      gg.clearResults()
      gg.setRanges(gg.REGION_C_ALLOC)
      gg.searchNumber("134914;262403", gg.TYPE_DWORD)
      gg.refineNumber("134914", gg.TYPE_DWORD)
      gg.getResults(50000)
      gg.editAll("0", gg.TYPE_DWORD)
      gg.clearResults()
      gg.setRanges(gg.REGION_C_ALLOC)
      gg.searchNumber("13||||||||||337|||||||||||||||||||||8;26||||||||||24|||||||||||||||||||||03", gg.TYPE_DWORD)
      gg.refineNumber("1||||||||||3||||||||||33||||||||||7|||||||||||8", gg.TYPE_DWORD)
      gg.getResults(50000)
      gg.editAll("0", gg.TYPE_DWORD)
      gg.clearResults()
      gg.setRanges(gg.REGION_C_ALLOC)
      gg.searchNumber("131330;133634", gg.TYPE_DWORD)
      gg.refineNumber("131330", gg.TYPE_DWORD)
      gg.getResults(50000)
      gg.editAll("0", gg.TYPE_DWORD)
      gg.clearResults()
      gg.setRanges(gg.REGION_C_ALLOC)
      gg.searchNumber("131842;132098", gg.TYPE_DWORD)
      gg.refineNumber("131842", gg.TYPE_DWORD)
      gg.getResults(50000)
      gg.editAll("0", gg.TYPE_DWORD)
      gg.clearResults()
      gg.setRanges(gg.REGION_C_ALLOC)
      gg.searchNumber("1|||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||3||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||2||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||0|||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||@PENGKIKGAMING||||||||||||||||||||||||||||||||||||||||9|||||||||||||||||||||||||||||||||||8", gg.TYPE_DWORD)
      gg.getResults(50000)
      gg.editAll("0", gg.TYPE_DWORD)
      gg.clearResults()
      resultsCount = gg.getResultCount()
      Zlet_6 = gg.getResults(resultsCount)
      for i = 1, resultsCount do
        gg.addListItems({
          [1] = {
            address = Zlet_6[i].address + 48,
            flags = 4,
            freeze = true,
            value = 70032
          }
        })
        gg.addListItems({
          [1] = {
            address = Zlet_6[i].address + 100,
            flags = 4,
            freeze = true,
            value = 4451
          }
        })
      end
      gg.clearResults()
      gg.setRanges(gg.REGION_ANONYMOUS)
      gg.searchNumber("16610;8388646;8388805", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(50)
      gg.editAll("30", gg.TYPE_DWORD)
      gg.clearResults()
      gg.searchNumber("2||||||||||||||||5||||||||||||||||7D;0~9||||||||||||||||||||||||999||||||||||||||9F;1D;0||||||||||||||||||||D::3|||||||||||||||||||||||||||00", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResultsCount()
      gg.searchNumber("0~9999", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(100)
      gg.clearResults()
      gg.addListItems((gg.getResults(100)))
      gg.clearResults()
      gg.alert("ᴠɪᴘ ʙʏᴘᴀss ʙʏ ʟᴛɴs ᴛᴇᴀᴍ")
      gg.alert("[[🇲🇲]] 𝐋𝐎𝐍𝐆✯︎𝐓𝐈𝐌𝐄✯︎𝐍𝐎✯︎𝐒𝐄𝐄 [[🇲🇲]]")
    end
    
    function J2()
      gg.alert("ᴠɪᴘ ʙʏᴘᴀss ʙʏ ʟᴛɴs ᴛᴇᴀᴍ")
      gg.clearResults()
      gg.searchNumber("9|||||||||||||||||||||||||||||||||||||9|||||||||||||||||||9|||||||||||||||||||||||||||||||||||9|||||||||||||||||||||||||||||||||||9|||||||||||||||||||||||||||||||||||9|||||||||||||||||||||||||||||||||||9|||||||||||||||||||||||||||||||||||9", 4, false, 536870912, 0, -1)
      gg.getResults(1)
      gg.editAll("1|||||||||P||||||||||||9||||||||||||||||||||||||||||||||||||||||||||||||||G||||||||||||||7|||||||||||||||||||||||||||||||||||||||||||||||||||00|||||||||||||||||||||3|||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||70||||||||||||||||||||||||||||||||||||||||||||||||||||7||||||||||||||||||||||||||||||||||||||||||||||||||||8", 4)
      gg.clearResults()
      gg.setRanges(gg.REGION_C_ALLOC)
      gg.searchNumber("135682;144387", gg.TYPE_DWORD)
      gg.refineNumber("135682", gg.TYPE_DWORD)
      gg.getResults(50000)
      gg.editAll("0", gg.TYPE_DWORD)
      gg.clearResults()
      gg.setRanges(gg.REGION_C_ALLOC)
      gg.searchNumber("134658;131586", gg.TYPE_DWORD)
      gg.refineNumber("134658", gg.TYPE_DWORD)
      gg.getResults(50000)
      gg.editAll("0", gg.TYPE_DWORD)
      gg.clearResults()
      gg.setRanges(gg.REGION_C_ALLOC)
      gg.searchNumber("134914;262403", gg.TYPE_DWORD)
      gg.refineNumber("134914", gg.TYPE_DWORD)
      gg.getResults(50000)
      gg.editAll("0", gg.TYPE_DWORD)
      gg.clearResults()
      gg.setRanges(gg.REGION_C_ALLOC)
      gg.searchNumber("13||||||||||337|||||||||||||||||||||8;26||||||||||24|||||||||||||||||||||03", gg.TYPE_DWORD)
      gg.refineNumber("1||||||||||3||||||||||33||||||||||7|||||||||||8", gg.TYPE_DWORD)
      gg.getResults(50000)
      gg.editAll("0", gg.TYPE_DWORD)
      gg.clearResults()
      gg.setRanges(gg.REGION_C_ALLOC)
      gg.searchNumber("131330;133634", gg.TYPE_DWORD)
      gg.refineNumber("131330", gg.TYPE_DWORD)
      gg.getResults(50000)
      gg.editAll("0", gg.TYPE_DWORD)
      gg.clearResults()
      gg.setRanges(gg.REGION_C_ALLOC)
      gg.searchNumber("131842;132098", gg.TYPE_DWORD)
      gg.refineNumber("131842", gg.TYPE_DWORD)
      gg.getResults(50000)
      gg.editAll("0", gg.TYPE_DWORD)
      gg.clearResults()
      gg.setRanges(gg.REGION_C_ALLOC)
      gg.searchNumber("1|||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||3||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||2||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||0|||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||@PENGKIKGAMING||||||||||||||||||||||||||||||||||||||||9|||||||||||||||||||||||||||||||||||8", gg.TYPE_DWORD)
      gg.getResults(50000)
      gg.editAll("0", gg.TYPE_DWORD)
      gg.clearResults()
      resultsCount = gg.getResultCount()
      Zlet_6 = gg.getResults(resultsCount)
      for i = 1, resultsCount do
        gg.addListItems({
          [1] = {
            address = Zlet_6[i].address + 48,
            flags = 4,
            freeze = true,
            value = 70032
          }
        })
        gg.addListItems({
          [1] = {
            address = Zlet_6[i].address + 100,
            flags = 4,
            freeze = true,
            value = 4452
          }
        })
      end
      gg.clearResults()
      gg.setRanges(gg.REGION_ANONYMOUS)
      gg.searchNumber("16610;8388646;8388805", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(50)
      gg.editAll("30", gg.TYPE_DWORD)
      gg.clearResults()
      gg.searchNumber("2||||||||||||||||5||||||||||||||||7D;0~9||||||||||||||||||||||||999||||||||||||||9F;1D;0||||||||||||||||||||D::3|||||||||||||||||||||||||||00", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResultsCount()
      gg.searchNumber("0~9999", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(100)
      gg.clearResults()
      gg.addListItems((gg.getResults(100)))
      gg.clearResults()
      gg.alert("ᴠɪᴘ ʙʏᴘᴀss ʙʏ ʟᴛɴs ᴛᴇᴀᴍ")
      gg.alert("[[🇲🇲]] 𝐋𝐎𝐍𝐆✯︎𝐓𝐈𝐌𝐄✯︎𝐍𝐎✯︎𝐒𝐄𝐄 [[🇲🇲]]")
    end
    
    
    
    function G710()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("1,194,344,475D;8,201D;1,194,379,806D:9", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("8201", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(10)
      gg.editAll("7", gg.TYPE_DWORD)
      gg.clearResults()
      gg.toast("C.710 Green ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function B710()
      gg.clearResults()
      gg.setRanges(gg.REGION_BAD)
      gg.searchNumber("8201", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(15)
      gg.editAll("6", gg.TYPE_DWORD)
      gg.toast("C.710 Blue ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function C21()
      C712 = gg.choice({
        "[[🇲🇲]]  𝐂 𝟕𝟏𝟐 𝐘𝐞𝐥𝐥𝐨𝐰",
        "[[🇲🇲]]  𝐂 𝟕𝟏𝟐 𝐆𝐫𝐞𝐞𝐧",
        "[[🇲🇲]]  𝐂 𝟕𝟏𝟐 𝐑𝐞𝐝",
        "◦•●◉✿𝐁𝐚𝐜𝐤✿◉●•◦"
      }, nil, "✭❈ʟᴛɴs☆ᴏɴʟɪɴᴇ☆sᴄʀɪᴘᴛ☆ᴠᴇʀsɪᴏɴ☆ɴᴀᴛsᴏᴇ")
     
        if C712== 1 then
          Y712()
        end
        if C712== 2 then
          G712()
        end
        if C712== 3 then
          R712()
        end
        if C712== 4 then
          WC()
        end
      
      PENGKIKGM = -1
    end
    
    function Y712()
      gg.clearResults()
      gg.setRanges(gg.REGION_BAD)
      gg.searchNumber("1703959D;8200D;8201D:17", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.refineNumber("1703959;8200;8201", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(10)
      gg.editAll("6;7;8199", gg.TYPE_DWORD)
      gg.toast("C. 712 Yellow ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function G712()
      gg.setRanges(gg.REGION_BAD)
      gg.searchNumber("8201", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(999)
      gg.editAll("8199", gg.TYPE_DWORD)
      gg.clearResults()
      gg.toast("C. 712 Green ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
function Y765()
      gg.clearResults()
gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
gg.searchNumber("8201;8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(15)
gg.editAll("7;7", gg.TYPE_DWORD)
gg.clearResults()
gg.searchNumber("8201", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(999)
gg.editAll("8199", gg.TYPE_DWORD)
gg.toast("ᴄᴏʟᴏᴜʀ 765 ʏᴇʟʟᴏᴡ ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function R712()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("1,081,081,875D;8,200D;1,194,344,485D:9", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(100)
      gg.editAll("13", gg.TYPE_DWORD)
      gg.clearResults()
      gg.toast("C. 712 Red ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function C22()
      C845 = gg.choice({
        "[[🇲🇲]]  𝐂 𝟖𝟒𝟓 𝐘𝐞𝐥𝐥𝐨𝐰",
        "[[🇲🇲]]  𝐂 𝟖𝟒𝟓 𝐑𝐞𝐝 𝐇𝐃𝐑",
        "[[🇲🇲]]  𝐂 𝟖𝟒𝟓 𝐆𝐫𝐞𝐞𝐧 𝐇𝐃𝐑",
        "[[🇲🇲]]  𝐂 𝟖𝟒𝟓 𝐁𝐥𝐮𝐞 𝐒𝐦𝐨𝐨𝐭𝐡",
        "[[🇲🇲]]  𝐂 𝟖𝟒𝟓 𝐆𝐫𝐞𝐞𝐧 𝐒𝐦𝐨𝐨𝐭𝐡",
        "◦•●◉✿𝐁𝐚𝐜𝐤✿◉●•◦"
      }, nil, "✭❈ʟᴛɴs☆ᴏɴʟɪɴᴇ☆sᴄʀɪᴘᴛ☆ᴠᴇʀsɪᴏɴ☆ɴᴀᴛsᴏᴇ")
      
        if C845 == 1 then
          Y845()
        end
        if C845 == 2 then
          R845()
        end
        if C845 == 3 then
          G8452()
        end
        if C845 == 4 then
          B845()
        end
        if C845 == 5 then
          G845()
        end
        if C845 == 6 then
          WC()
        end
      
      PENGKIKGM = -1
    end
    
    function Y845()
      gg.setRanges(gg.REGION_BAD)
      gg.searchNumber("536887312;539246610;-2128609280;8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(20)
      gg.editAll("6", gg.TYPE_DWORD)
      gg.clearResults()
      gg.toast("C.845 Yellow ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function R845()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("5129823416953610248", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(69)
      gg.editAll("5129823416953610247", gg.TYPE_QWORD)
      gg.clearResults()
      gg.toast("C.845 Red Hdr ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function G8452()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("5129823416953610248", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(69)
      gg.editAll("5129823416953610246", gg.TYPE_QWORD)
      gg.clearResults()
      gg.toast("C.845 Green Hdr ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function B845()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("5129822240132571145", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(69)
      gg.editAll("5129822240132571142", gg.TYPE_QWORD)
      gg.clearResults()
      gg.toast("C.845 Blue ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function G845()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("5129822240132571145", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(69)
      gg.editAll("5129822240132571143", gg.TYPE_QWORD)
      gg.clearResults()
      gg.toast("C.845 Greenᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function C23()
      C855 = gg.choice({
        "[[🇲🇲]]𝐂 𝟖𝟓𝟓 𝐑𝐞𝐝",
        "[[🇲🇲]]𝐂 𝟖𝟓𝟓 𝐘𝐞𝐥𝐥𝐨𝐰",
        "[[🇲🇲]]𝐂 𝟖𝟓𝟓 𝐆𝐫𝐞𝐞𝐧",
        "[[🇲🇲]]𝐂 𝟖𝟓𝟓 𝐁𝐥𝐮𝐞",
        "◦•●◉✿𝐁𝐚𝐜𝐤✿◉●•◦"
      }, nil, "✭❈ʟᴛɴs☆ᴏɴʟɪɴᴇ☆sᴄʀɪᴘᴛ☆ᴠᴇʀsɪᴏɴ☆ɴᴀᴛsᴏᴇ")
     
        if C855 == 1 then
          R855()
        end
        if C855 == 2 then
          Y855()
        end
        if C855 == 3 then
          G855()
        end
        if C855 == 4 then
          B855()
        end
        if C855 == 5 then
          WC()
        end
      
      PENGKIKGM = -1
    end
    
    function R855()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("8,196D;8,192D;8,200D::", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(10)
      gg.editAll("7", gg.TYPE_DWORD)
      gg.clearResults()
      gg.toast("C.855 Red ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function Y855()
      gg.clearResults()
gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
gg.searchNumber("8201;8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(15)
gg.editAll("7;7", gg.TYPE_DWORD)
gg.clearResults()
gg.searchNumber("8201", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(999)
gg.editAll("8199", gg.TYPE_DWORD)
gg.toast("ᴄᴏʟᴏᴜʀ 855 ʏᴇʟʟᴏᴡ")
end

    
    function G855()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("8201", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.refineAddress("0A0")
      gg.getResults(10)
      gg.editAll("8199", gg.TYPE_DWORD)
      gg.clearResults()
      gg.toast("C.855 Green ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function B855()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("8201", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.refineAddress("0A0")
      gg.getResults(10)
      gg.editAll("8198", gg.TYPE_DWORD)
      gg.clearResults()
      gg.toast("C.855 Blue ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function OS()
      gg.clearResults()
      gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
      gg.searchNumber("135,215D;4,140D;3.7615819e-37;2::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(10)
      gg.editAll("130", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.setRanges(gg.REGION_BAD)
      gg.searchNumber("194D;3.7615819e-37;2;-1;1;-127::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(10)
      gg.editAll("130", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.toast("Wallhack ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
      gg.clearResults()
      gg.setRanges(gg.REGION_BAD)
      gg.searchNumber("8,192D;256D;8200D", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(20)
      gg.editAll("6", gg.TYPE_DWORD)
      gg.toast("C.Yellow ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
      gg.clearResults()
    end
    
    
    function REC()
      gg.clearResults()
      gg.setRanges(32)
      gg.searchNumber("1,868,784,978;1,850,305,641;28,518;13,212::13", 4, false, 536870912, 0, -1)
      gg.searchNumber("1,850,305,641", 4, false, 536870912, 0, -1)
      gg.getResults(20)
      gg.editAll("0", 4)
      gg.clearResults()
      gg.setRanges(32)
      gg.searchNumber("1;0;0;1,028,443,341;1,090,519,040;1,036,831,949;1,057,803,469;1,092,091,904;1,097,859,072::33", 4, false, 536870912, 0, -1)
      gg.searchNumber("1", 4, false, 536870912, 0, -1)
      gg.getResults(50)
      gg.editAll("0", 4)
      gg.toast("LessRecoil ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    
    
    function WV()
      gg.setRanges(32)
      gg.clearResults()
      gg.searchNumber("220;178;15 ", 16, false, 536870912, 0, -1)
      gg.searchNumber("220", 16, false, 536870912, 0, -1)
      gg.getResults(300)
      gg.editAll("438", 16)
      gg.clearResults()
      gg.toast("Tab View ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    function ANTENA()
      gg.clearResults()
      gg.setRanges(gg.REGION_ANONYMOUS)
      gg.searchNumber("88.50576019287F;87.27782440186F;-100.91194152832F;1F::13", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("88.50576019287F;87.27782440186F;1F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(6)
      gg.editAll("1.96875;1.96875;999;1.96875;1.96875;999", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.toast("Antena ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
    
    
    function HS()
      gg.clearResults()
      gg.setRanges(gg.REGION_BAD)
      gg.searchNumber("-88.66608428955;26:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("26", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(2)
      gg.editAll("-460", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.searchNumber("-88.73961639404;28:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(2)
      gg.editAll("-560", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.setRanges(gg.REGION_ANONYMOUS)
      gg.searchNumber("9.201618;30.5;25", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.searchNumber("25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      gg.getResults(10)
      gg.editAll("160", gg.TYPE_FLOAT)
      gg.clearResults()
      gg.toast("HS75% ᴀᴄᴛɪᴠᴇ✔ʙʏ ᴀᴅᴍɪɴ ʏᴀɴʟɪɴᴊʀ")
    end
    
       
    
 function EXIT()
      print('✪ ᴄʀᴇᴀᴛᴏʀ ʙʏ ★𝐋𝐓𝐍𝐒★ ✪\n©2020 ɴᴇᴡ ɢɢ ᴄᴏᴅᴇs\n➢ Cᴏɴᴛᴀᴄᴛ Cʀᴇᴀᴛᴏʀ :★𝐋𝐓𝐍𝐒★ 𝐊𝐈𝐋𝐋𝐄𝐑\n⊚ ║★𝐋𝐓𝐍𝐒★[[🇲🇲]]̩ 𝐒𝐂𝐑𝐈𝐏𝐓[[🇲🇲]]║̩ ')
cs = "YOUR DEVICE ALWAYS ROOT"
print("========== ᴛʜᴀɴᴋs[[🇲🇲]]★𝐋𝐓𝐍𝐒★[[🇲🇲]]  ᴍᴇᴍʙᴇʀs ==========")
      os.exit()
    end
    
    while true do
      if gg.isVisible(true) then
        PENGKIKGM = 1
        gg.setVisible(false)
      end
      if PENGKIKGM == 1 then
        HOME()
      end
    end
