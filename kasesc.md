代发 wailian999

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zdqjudy.top/Article/details/gttxtddpol.html

[E15] HTML 转义 / 反转义
来源：http://dali.dianchejie.cn/Article/details/gtsgjboeui.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhengqikj.top/Article/details/gtwenxkxbx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.redwolf501.top/Article/details/gtniszwpay.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cashguo.top/Article/details/gtumgeyqgx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj202588.top/Article/details/gtameafdkj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cdnleiting.top/Article/details/gtocjbrkkr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zdqjudy.top/Article/details/gtobemeepz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnnliedoy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.dianchejie.cn/Article/details/gtwqindnjf.html

[E16] 数字千分位
来源：http://dali.cucudq.cn/Article/details/gtutupyeqe.html

Py:   f"{1234567:,}"
来源：http://dali.fzhhl.top/Article/details/gtbjwzgfub.html

PHP:  number_format(1234567);
来源：http://dali.guowangkeji.top/Article/details/gtcuhrfvti.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.redwolf501.top/Article/details/gtqpcqwujy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhengqikj.top/Article/details/gtbhkmkaqg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jianghu66.top/Article/details/gtprzystqu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.kuanghao11.cn/Article/details/gtzvqgsgsj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.fengsongda.top/Article/details/gtbmeurpwm.html

C#:   1234567.ToString("N0")
来源：http://dali.gogol.net.cn/Article/details/gtmjdamyir.html

[E17] 首字母大写
来源：http://dali.pycfn.com/Article/details/gtdthxogrp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yuanzhike.top/Article/details/gtzilhbjfo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.kuanghao11.cn/Article/details/gtafcmgonk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tian-w.cn/Article/details/gthmbseyjj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jlsjyb.cn/Article/details/gtjoflgesp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.dianchejie.cn/Article/details/gtlnzcbkzp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gotoacloud.top/Article/details/gtuzimsvez.html

Ruby: s.capitalize
来源：http://dali.smart0.xyz/Article/details/gttyhkqlfw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.smart0.xyz/Article/details/gtfhevojqh.html

[E18] 模板占位符替换
来源：http://dali.dianchejie.cn/Article/details/gtvaapvecu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.dianchejie.cn/Article/details/gtquorufiv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shuidangran.top/Article/details/gtguijhsfa.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtxbzyftee.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gtriuzqpiz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gtjimubpex.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj202588.top/Article/details/gtwdminytp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtqognqoxl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.redwolf501.top/Article/details/gtgqltvlhw.html

[E19] 多行文本按行拆分
来源：http://dali.fengsongda.top/Article/details/gtdplrpkmv.html

Py:   s.splitlines()
来源：http://dali.xziqi.cn/Article/details/gtdqvwjzmj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtfwdwhtkt.html

JS:   s.split(/\r?\n/)
来源：http://dali.xuetiantiany.cn/Article/details/gtczqfvpqp.html

TS:   s.split(/\r?\n/)
来源：http://dali.vqdsnc.cn/Article/details/gtefwyqzgw.html

Java: s.lines().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzkpsxbln.html

Go:   strings.Split(s, "\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyidltkzd.html

Ruby: s.lines
来源：http://dali.aibaodan.cn/Article/details/gtlfyqzccd.html

C#:   s.Split('\n')
来源：http://dali.jinghuilouyu.cn/Article/details/gtxahuqajn.html

[E20] 判断字符串是否为空
来源：http://dali.fengsongda.top/Article/details/gtaifwzjjc.html

Py:   if not s:
来源：http://dali.jinqigfzy.top/Article/details/gtqhaqjdlf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.smart0.xyz/Article/details/gtscendizw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtheptigtg.html

TS:   if (s === "") {}
来源：http://dali.jinqigufen.top/Article/details/gtbzmooiyg.html

Java: if (s.isEmpty()) {}
来源：http://dali.yvedp.cn/Article/details/gtphufjsvd.html

Go:   if s == "" {}
来源：http://dali.zhengqikj.top/Article/details/gtcexifnww.html

Ruby: if s.empty?
来源：http://dali.cheryme.top/Article/details/gtarrfroam.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.quarkkingdee.top/Article/details/gtofdproik.html

[E21] 超长截断加省略号
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjiqgoby.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenzaomai.com/Article/details/gtqjorjfkm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gtutrypcan.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtxaqmxoft.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtuabuidzx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtfxschevx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinqigfzy.top/Article/details/gtbwmqnhnz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtooafyotd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtfwxfpvmf.html

[E22] 字节长度与字符长度
来源：http://dali.guannengcc.top/Article/details/gterfgfjls.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj202588.top/Article/details/gtdvlsxgpz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtyidbqgna.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gtdpatqhne.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ppjwa.cn/Article/details/gtktgftrma.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.birdmap.top/Article/details/gtcjuibdyq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ehwqpu.com/Article/details/gtiggapgtx.html

Ruby: s.bytesize;  s.length
来源：http://dali.xylfe.cn/Article/details/gtzfgqlhvq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yueranfly.top/Article/details/gtwhwkpzet.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtyccaxkmd.html

F. 文件与目录
来源：http://dali.ybcxt.top/Article/details/gttgipvaqf.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gthuzspobb.html

[F01] 读取整个文件
来源：http://dali.hywenlv.cn/Article/details/gtatgbopbc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nanxuanxn.top/Article/details/gtqwbkhmfu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtvcopinnt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cqqwz.cn/Article/details/gteykfwiqi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gtrxsrbtbe.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtddnvhqdl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.9152youxi.cn/Article/details/gtykdwejgh.html

Ruby: File.read("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtbkogpiar.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtefslnsfh.html

[F02] 逐行读取文件
来源：http://dali.chenlongwang.top/Article/details/gtwlgfyous.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhoulong.xyz/Article/details/gtpoyffqoi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yongpay.top/Article/details/gtxtddnnyc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuanzx.com/Article/details/gtyfhrnqsk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gthviwbblj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.aibaodan.cn/Article/details/gtsfhsdghk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ydzc1.top/Article/details/gtwcrcxkoc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.daxiang520.top/Article/details/gtesbhizro.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnxiangtu.top/Article/details/gtiineaajo.html

[F03] 写入文件（覆盖）
来源：http://dali.iojbl.cn/Article/details/gtpujczhrj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hnxiangtu.top/Article/details/gtybwolbcu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aizwys.cn/Article/details/gtpvnuvljm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gttzawnzoy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gtiyqnnyap.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tian-w.cn/Article/details/gtghcjvybv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttmfcpreu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmzqbqfuv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhengqikj.top/Article/details/gtwkkjofqp.html

[F04] 追加写入文件
来源：http://dali.chenzaomai.com/Article/details/gtbxsmlflp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinqigufen.top/Article/details/gtcaskeqzc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hammf.cn/Article/details/gtpujqtrce.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtaioffgen.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fzhhl.top/Article/details/gtikesbark.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.guannengcc.top/Article/details/gtpjhftpsp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj202588.top/Article/details/gtssglokdl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xuetiantiany.cn/Article/details/gtfymhurtx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinqigfzy.top/Article/details/gtulkgntyv.html

[F05] 判断文件或目录是否存在
来源：http://dali.cheryme.top/Article/details/gtxkpdtwqo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jyoumei.cn/Article/details/gtpagdzwzz.html

PHP:  file_exists("a.txt");
来源：http://dali.cashguo.top/Article/details/gtcknhftpg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtrwzvtymj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtennjrwak.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gtskoxgofk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xziqi.cn/Article/details/gtuaqiunjz.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtorwngyvp.html

C#:   File.Exists("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtsrqmeexw.html

[F06] 删除文件
来源：http://dali.daria6918.cn/Article/details/gtuoipytgq.html

Py:   os.remove("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtayedqhli.html

PHP:  unlink("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtpvdfidic.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gthbkocbcd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtlhxetbcb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gtuuvfrvkr.html

Go:   os.Remove("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtpzbkuaae.html

Ruby: File.delete("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtxlwcyauu.html

C#:   File.Delete("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtnfnxlcrr.html

[F07] 创建目录（含多级）
来源：http://dali.jianghu66.top/Article/details/gtuhnftsyt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jyoumei.cn/Article/details/gtxzxovioh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlhaoirtl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuxming.cn/Article/details/gtzkkkpfkr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgfzy.top/Article/details/gtdltmrvhu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenlongwang.top/Article/details/gtnpvbmsai.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtygcnkrjk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ybcxt.top/Article/details/gttpwqtclr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hnxiangtu.top/Article/details/gtcpumaxef.html

[F08] 遍历目录
来源：http://dali.quarkkingdee.top/Article/details/gtbfdrvzmp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sysykeji.top/Article/details/gthahyrocz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.daria6918.cn/Article/details/gtpxyyjsru.html

JS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gtfxbkyazc.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenzaomai.com/Article/details/gtfytdavwh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gtdgzmkdhr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtvzsipuro.html

Ruby: Dir.children("dir")
来源：http://dali.zhixingplan.top/Article/details/gteztaxbct.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xuanzx.com/Article/details/gtbehdprjb.html

[F09] 获取文件大小
来源：http://dali.chenlongwang.top/Article/details/gthyprqocw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtytsbwzja.html

PHP:  filesize("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtodylynqt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gtatqmjgfi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.daria6918.cn/Article/details/gtbxeyyiuy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gtcyuqydua.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj202588.top/Article/details/gtfaellzvf.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtnebikevl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tianlin.xyz/Article/details/gtbqavleiq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.wangdashe.top/Article/details/gtviuxgcqo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gturpkkkvt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtatyffdtt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtvptkhwbp.html

TS:   path.extname("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtivdeayrf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pycfn.com/Article/details/gtcasqsjkv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtgqoqtxez.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtlafihlnl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtrwebyijb.html

[F11] 复制与移动文件
来源：http://dali.shangyingyoupin.top/Article/details/gtjjykious.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtsuzeirlk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.iojbl.cn/Article/details/gtblwpjlap.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtincebuvl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtscpglwtv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yuanzhike.top/Article/details/gtltxvtesw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ehwqpu.com/Article/details/gtiikhyzbt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtpfrhfrfa.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.dianchejie.cn/Article/details/gtjdpphkgb.html

[F12] CSV 读写
来源：http://dali.gotoacloud.top/Article/details/gtmvtrpxqt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhixingplan.top/Article/details/gtabiqunwx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nwbrower.top/Article/details/gtcfqvjviy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenlongwang.top/Article/details/gtnfmbcfyu.html

TS:   // 同上
来源：http://dali.quarkkingdee.top/Article/details/gtxjnwmlro.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.dianchejie.cn/Article/details/gtvgfsqzwz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.dashuyun.cn/Article/details/gtacmlrbhm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hfpthk.cn/Article/details/gtbdylliia.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sufxvd.cn/Article/details/gtqnskuugk.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtnqpvlfbz.html

G. 面向对象
来源：http://dali.yj20258888.top/Article/details/gtflpuvwcf.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtqnyhmilt.html

[G01] 定义类
来源：http://dali.zhiwuduotai.top/Article/details/gtbukrxpvc.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gtwqynjoak.html

PHP:  class User {}
来源：http://dali.nanxuanxn.top/Article/details/gtrvmlmnbl.html

JS:   class User {}
来源：http://dali.cqqwz.cn/Article/details/gtjjyinhtk.html

TS:   class User { name: string = ""; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdfepzoab.html

Java: class User {}
来源：http://dali.yj202588.top/Article/details/gtvykvjpva.html

Go:   type User struct { Name string }
来源：http://dali.xuetiantiany.cn/Article/details/gtjkvdfxmd.html

Ruby: class User; end
来源：http://dali.yueranfly.top/Article/details/gtbkkouxou.html

C#:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gttzocsbzo.html

[G02] 构造函数
来源：http://dali.fzhhl.top/Article/details/gtqmssmecm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xinyue.icu/Article/details/gtucebtvjw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shuidangran.top/Article/details/gtmbczmkay.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthmekclxa.html

TS:   constructor(public name: string) {}
来源：http://dali.havefunace.top/Article/details/gthzulqbes.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtdpqoiclj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ivvv.top/Article/details/gtvmxnyzvp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ybcxt.top/Article/details/gtaiaxlwks.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gogol.net.cn/Article/details/gtlttmzzsm.html

[G03] 实例属性
来源：http://dali.yuanzhike.top/Article/details/gtjpdmmado.html

Py:   self.name = "x"
来源：http://dali.hysaishi.cn/Article/details/gtbwulqwic.html

PHP:  public string $name = "x";
来源：http://dali.daxiang520.top/Article/details/gtpdbaohhx.html

JS:   this.name = "x";
来源：http://dali.haohaochexian.top/Article/details/gtwmznetni.html

TS:   name: string = "x";
来源：http://dali.nwbrower.top/Article/details/gtqfedmqov.html

Java: private String name;
来源：http://dali.jyoumei.cn/Article/details/gtssvdietp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkgcbvwtg.html

Ruby: @name = "x"
来源：http://dali.dashuyun.cn/Article/details/gthyfmapyk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdxwfuxm.html

[G04] 定义方法
来源：http://dali.jlsjyb.cn/Article/details/gtlcziwjiz.html

Py:   def greet(self): return self.name
来源：http://dali.xuanzx.com/Article/details/gtbsxzmjwk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtowruuuvd.html

JS:   greet() { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtcwicnxwp.html

TS:   greet(): string { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtrexfpdyv.html

Java: String greet() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtfmxvpvsg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gtjkzcauoo.html

Ruby: def greet; @name; end
来源：http://dali.tianlin.xyz/Article/details/gtnqiootku.html

C#:   public string Greet() => Name;
来源：http://dali.feifeiyinyue.top/Article/details/gtipuabwak.html

[G05] 继承
来源：http://dali.hywenlv.cn/Article/details/gtgroipgnw.html

Py:   class Admin(User): pass
来源：http://dali.zhengqikj.top/Article/details/gtvaltludt.html

PHP:  class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtdmianzyx.html

JS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtdcyoggyv.html

TS:   class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtibneeteh.html

Java: class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtkutmhgnp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ivvv.top/Article/details/gtpuhukqtb.html

Ruby: class Admin < User; end
来源：http://dali.zhoulong.xyz/Article/details/gtvvdnjvbl.html

C#:   class Admin : User {}
来源：http://dali.zycfv.cn/Article/details/gtmqtobxzb.html

[G06] 重写方法
来源：http://dali.ppjwa.cn/Article/details/gtwjoimrvd.html

Py:   def greet(self): return "admin"
来源：http://dali.ybcxt.top/Article/details/gtpujjpome.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtnesfrdao.html

JS:   greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gteviqvrfm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtinjxnbxd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtqsfhtjfz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hfpthk.cn/Article/details/gteomwybxd.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gticqrtydo.html

C#:   public override string Greet() => "admin";
来源：http://dali.vqdsnc.cn/Article/details/gthoxievqb.html

[G07] 调用父类方法
来源：http://dali.aizwys.cn/Article/details/gtwfdfecsb.html

Py:   super().greet()
来源：http://dali.jinqigfzy.top/Article/details/gtwspevwci.html

PHP:  parent::greet();
来源：http://dali.nanxinkj.top/Article/details/gtswjpaykq.html

JS:   super.greet();
来源：http://dali.sweek.top/Article/details/gtintivajt.html

TS:   super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gthxuevnws.html

Java: super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gthmqicfff.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sxryk.cn/Article/details/gtbhpxsggp.html

Ruby: super
来源：http://dali.chenjidiqi.icu/Article/details/gtiietptgj.html

C#:   base.Greet();
来源：http://dali.havefunace.top/Article/details/gtuhogvsgt.html

[G08] 静态方法与属性
来源：http://dali.gotoacloud.top/Article/details/gtjivmzimb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.daria6918.cn/Article/details/gtzqbaloyb.html

PHP:  public static function f() {}
来源：http://dali.mhx1999.top/Article/details/gtkijatuvs.html

JS:   static f() {}
来源：http://dali.vqdsnc.cn/Article/details/gttcbkvtfi.html

TS:   static f(): void {}
来源：http://dali.yj20258.top/Article/details/gtzllcypjx.html

Java: static void f() {}
来源：http://dali.zycfv.cn/Article/details/gtrkuwhbts.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tanke756.top/Article/details/gtjjryavvj.html

Ruby: def self.f; end
来源：http://dali.feifeiyinyue.top/Article/details/gtveijyoex.html

C#:   public static void F() {}
来源：http://dali.yj202588.top/Article/details/gthnrqouao.html

[G09] 接口 / 抽象类
来源：http://dali.jyoumei.cn/Article/details/gtzbhungdw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tian-w.cn/Article/details/gtxpkbzkxc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xziqi.cn/Article/details/gtfxmtspat.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhiwuduotai.top/Article/details/gteftfiuxl.html

TS:   interface Shape { area(): number; }
来源：http://dali.ivvv.top/Article/details/gtvdygdovf.html

Java: interface Shape { double area(); }
来源：http://dali.hammf.cn/Article/details/gtpctlamph.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shuidangran.top/Article/details/gtclacnria.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gthcndfwgx.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhoulong.xyz/Article/details/gtpzugdnrf.html

[G10] 访问控制
来源：http://dali.haohaochexian.top/Article/details/gtpyylsslg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yueranfly.top/Article/details/gtcqxczcqe.html

PHP:  public / protected / private
来源：http://dali.yongpay.top/Article/details/gtsqfgwyft.html

JS:   #private 字段；其余公开
来源：http://dali.ehwqpu.com/Article/details/gthmgwwkry.html

TS:   public / protected / private
来源：http://dali.shuidangran.top/Article/details/gtzwqfklyf.html

Java: public / protected / private / 默认包级
来源：http://dali.shzxlz.cn/Article/details/gtbodxneix.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.wangdashe.top/Article/details/gtqfdvvhdz.html

Ruby: public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gtepjdcelm.html

C#:   public / protected / private / internal
来源：http://dali.gotoacloud.top/Article/details/gtlitejpmb.html

[G11] getter / setter
来源：http://dali.hysaishi.cn/Article/details/gtrqznhoii.html

Py:   @property 与 @x.setter
来源：http://dali.pycfn.com/Article/details/gtcbapwrzf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtopfuheyt.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gtxpaqcxwl.html

TS:   get name(): string { return this._name; }
来源：http://dali.birdmap.top/Article/details/gtygxjyssv.html

Java: public String getName() { return name; }
来源：http://dali.hammf.cn/Article/details/gtzbnmmwce.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtayfnxyva.html

Ruby: attr_accessor :name
来源：http://dali.c1oappe.top/Article/details/gtdccywifo.html

C#:   public string Name { get; set; }
来源：http://dali.ppjwa.cn/Article/details/gtwklbjokg.html

[G12] 对象转字符串
来源：http://dali.sufxvd.cn/Article/details/gtolejdlxc.html

Py:   def __str__(self): return self.name
来源：http://dali.gaohongyu789.top/Article/details/gtleaocxdx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtibzovdov.html

JS:   toString() { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtwtubybem.html

TS:   toString(): string { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gtxuerypzo.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gteygaxkgc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gtnbgohcei.html

Ruby: def to_s; @name; end
来源：http://dali.dianchejie.cn/Article/details/gtocuzocyx.html

C#:   public override string ToString() => Name;
来源：http://dali.haohaochexian.top/Article/details/gtkvhbnkae.html

[G13] 判断对象类型
来源：http://dali.jqgfzy.top/Article/details/gtndolahbi.html

Py:   isinstance(u, User)
来源：http://dali.wangshuangyany.cn/Article/details/gtlvionjfv.html

PHP:  $u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtgqycmbwk.html

JS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtwoeunlas.html

TS:   u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtrqfjyocx.html


<!-- 参考信息 -->