代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ybcxt.top/Article/details/gtuqptebtn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtduglizss.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gthkayespz.html

Py:   f"{1234567:,}"
来源：http://dali.mhx1999.top/Article/details/gtdgwcuqbh.html

PHP:  number_format(1234567);
来源：http://dali.cashguo.top/Article/details/gtqflhvxfx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cucudq.cn/Article/details/gtkuoeixbl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.iojbl.cn/Article/details/gtrgfztvnt.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gtraovlqke.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tian-w.cn/Article/details/gtvebwuvog.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xziqi.cn/Article/details/gtteienapr.html

C#:   1234567.ToString("N0")
来源：http://dali.hfpthk.cn/Article/details/gtaiomjbdy.html

[E17] 首字母大写
来源：http://dali.dashuyun.cn/Article/details/gtyqyueahe.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yonumen.top/Article/details/gtwcbmtxsk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ppjwa.cn/Article/details/gttnhbfprt.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.birdmap.top/Article/details/gtayxfhnrk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtlefgchck.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.fzhhl.top/Article/details/gtgplnbcbu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yangfankeji.com/Article/details/gtytiyhwna.html

Ruby: s.capitalize
来源：http://dali.pycfn.com/Article/details/gtdsidsnmq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yuxming.cn/Article/details/gtdnxhzfhb.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gttfulhger.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hywenlv.cn/Article/details/gtvqkkmuqe.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xuanzx.com/Article/details/gtwjxtfhfa.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtktiysnta.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtvjkocxwo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gtdbkvwavb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtzqjksrfm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jiagoushi.top/Article/details/gtpbalvzwb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.daria6918.cn/Article/details/gtjynclzpo.html

[E19] 多行文本按行拆分
来源：http://dali.zhoulong.xyz/Article/details/gtpzduaqvj.html

Py:   s.splitlines()
来源：http://dali.ybcxt.top/Article/details/gtyeemjbio.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj20258888.top/Article/details/gtkboniyvt.html

JS:   s.split(/\r?\n/)
来源：http://dali.hnqzz.top/Article/details/gttbwrcnvi.html

TS:   s.split(/\r?\n/)
来源：http://dali.nanxuanxn.top/Article/details/gtrtxvicry.html

Java: s.lines().toList()
来源：http://dali.fzhhl.top/Article/details/gtklovykns.html

Go:   strings.Split(s, "\n")
来源：http://dali.jyoumei.cn/Article/details/gtchfxrmra.html

Ruby: s.lines
来源：http://dali.nanxinkj.top/Article/details/gtqovdwxxv.html

C#:   s.Split('\n')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtolngtmno.html

[E20] 判断字符串是否为空
来源：http://dali.zycfv.cn/Article/details/gtrafpssgf.html

Py:   if not s:
来源：http://dali.jqgfzy.top/Article/details/gtwqsurwtc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.pycfn.com/Article/details/gtoykpttml.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.fengsongda.top/Article/details/gtdzdhdxmi.html

TS:   if (s === "") {}
来源：http://dali.mhx1999.top/Article/details/gtwakmmxnl.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtzpumqzzg.html

Go:   if s == "" {}
来源：http://dali.xylfe.cn/Article/details/gtfnmryjli.html

Ruby: if s.empty?
来源：http://dali.jinqigfzy.top/Article/details/gtokolmswo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhongyouzk.top/Article/details/gtmdpmxtuc.html

[E21] 超长截断加省略号
来源：http://dali.jinghuilouyu.cn/Article/details/gtyrijgkfe.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.dianchejie.cn/Article/details/gtzbkpkvej.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.havefunace.top/Article/details/gtglaxsiaz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtorjucnwt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtduzifisz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtjdcobbyb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhixingplan.top/Article/details/gtofcxtpvf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtuuadqwin.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtjrycfxuf.html

[E22] 字节长度与字符长度
来源：http://dali.tian-w.cn/Article/details/gtfyhiiway.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jqgufenzy.top/Article/details/gtdpdqnbgb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtpwdysary.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gtiesjnpkh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.c1oappe.top/Article/details/gtdhcwffgq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sysykeji.top/Article/details/gtjuwcgaoq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jlsjyb.cn/Article/details/gtlaqbtoae.html

Ruby: s.bytesize;  s.length
来源：http://dali.yuanzhike.top/Article/details/gtxoydlgmj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.dianchejie.cn/Article/details/gtmkowzomh.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtuowwvycu.html

F. 文件与目录
来源：http://dali.pengpengdd.cyou/Article/details/gtwtmejgvi.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtaqeofnmi.html

[F01] 读取整个文件
来源：http://dali.chenzaomai.com/Article/details/gttnxbmssf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.snrcjt.cn/Article/details/gtbpjjyoia.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtqemacwet.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xuetiantiany.cn/Article/details/gtqeafhkqc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gttisvqbff.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtpgaerxgd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ehwqpu.com/Article/details/gtvuoltvok.html

Ruby: File.read("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtmnnswbjs.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtzmmlenqj.html

[F02] 逐行读取文件
来源：http://dali.dashuyun.cn/Article/details/gtefmkdsbc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.kuanghao11.cn/Article/details/gtrgvazore.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.feifeiyinyue.top/Article/details/gtyseenvmi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.mhx1999.top/Article/details/gthuiyiwvy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yongpay.top/Article/details/gtzzmehuur.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.dashuyun.cn/Article/details/gtskwprcwa.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yonumen.top/Article/details/gtipymygcu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.meibo888.top/Article/details/gtqqabtzcw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxuanxn.top/Article/details/gtwebfsyxz.html

[F03] 写入文件（覆盖）
来源：http://dali.jinqigufen.top/Article/details/gtjpwxonro.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cqqwz.cn/Article/details/gtgdzeisle.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtrosvlofb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxoctfxnh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gtjuzkpyqq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cdnleiting.top/Article/details/gtbyrtpfag.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmbfpjnn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cashguo.top/Article/details/gtfwfcbszz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gtpgxqhzxy.html

[F04] 追加写入文件
来源：http://dali.guannengcc.top/Article/details/gtzkdberyv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yongpay.top/Article/details/gtdzqhmgsx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgfzy.top/Article/details/gtdaziruhi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.bjfxy.top/Article/details/gtlkmhbwjx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guowangkeji.top/Article/details/gtgbnardzp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.feifeiyinyue.top/Article/details/gtkyycrbig.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hammf.cn/Article/details/gtsjznfdyz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gaohongyu789.top/Article/details/gtdscamavn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cdnleiting.top/Article/details/gtvanoysff.html

[F05] 判断文件或目录是否存在
来源：http://dali.zycfv.cn/Article/details/gtrwyhopiu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.andypj.xyz/Article/details/gtabeflaqy.html

PHP:  file_exists("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtvwjiavwv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtyrqofdtn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtwfdrgwtx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtatbmzxyj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yueranfly.top/Article/details/gtnvjnznst.html

Ruby: File.exist?("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gttbglyayc.html

C#:   File.Exists("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gttjirjijl.html

[F06] 删除文件
来源：http://dali.jianghu66.top/Article/details/gtinfactgt.html

Py:   os.remove("a.txt")
来源：http://dali.birdmap.top/Article/details/gtckojjxof.html

PHP:  unlink("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtmoywdhkv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtipewvfbb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtizhjtaby.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gtbdcpfhzq.html

Go:   os.Remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtzikhbdva.html

Ruby: File.delete("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtizrhqinp.html

C#:   File.Delete("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtmwtbegpt.html

[F07] 创建目录（含多级）
来源：http://dali.vqdsnc.cn/Article/details/gtfsslozor.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yvedp.cn/Article/details/gtqbdmduge.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhengqikj.top/Article/details/gtpzjmcnct.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jianghu66.top/Article/details/gtkjhagzoe.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sysykeji.top/Article/details/gtwtdapqwc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj202588.top/Article/details/gtuabwwkuk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shzxlz.cn/Article/details/gtoztzeczs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jqgufenzy.top/Article/details/gtskwakjkx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj20258888.top/Article/details/gtfiwcahri.html

[F08] 遍历目录
来源：http://dali.jinqigfzy.top/Article/details/gtpjcoucwf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.snrcjt.cn/Article/details/gtfnsgwsez.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yvedp.cn/Article/details/gtejciqelb.html

JS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gtwhzewsca.html

TS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gtvypixebl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ydzc1.top/Article/details/gtpykywvxd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sysykeji.top/Article/details/gtivhgjakp.html

Ruby: Dir.children("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtizrgqoui.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenlongwang.top/Article/details/gtynmamtpb.html

[F09] 获取文件大小
来源：http://dali.nwbrower.top/Article/details/gtysvipgqo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtufdskfaq.html

PHP:  filesize("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtolejpfyx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ydzc1.top/Article/details/gttyphrnel.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gtztkrdant.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtrxnbdecq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.c1oappe.top/Article/details/gttmmvlhiv.html

Ruby: File.size("a.txt")
来源：http://dali.tanke756.top/Article/details/gtutghrsay.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gogol.net.cn/Article/details/gtwpnuzmul.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.wangdashe.top/Article/details/gtoocdpujf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtlmxjahoi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvcxqkuc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtkoiuwmhl.html

TS:   path.extname("a.txt")
来源：http://dali.ydzc1.top/Article/details/gttubxinut.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.0kj1m.cn/Article/details/gtjmbovjhm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtyopmontk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtindiwbdd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtzsyguyou.html

[F11] 复制与移动文件
来源：http://dali.zhiwuduotai.top/Article/details/gtmgxwosyi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoryxlogi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtubxeiayq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfehudkt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtuqisatzv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nwbrower.top/Article/details/gttnuamukr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gtmgfwgupm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtiejftilz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gotoacloud.top/Article/details/gtajyljvqq.html

[F12] CSV 读写
来源：http://dali.yj202588.top/Article/details/gtvqkwhcgz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhengqikj.top/Article/details/gtfpbjohcc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sweek.top/Article/details/gtmddyjdld.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ppjwa.cn/Article/details/gtedfnvpue.html

TS:   // 同上
来源：http://dali.zhiwuduotai.top/Article/details/gtemoljszc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.iojbl.cn/Article/details/gththaiefe.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xinyue.icu/Article/details/gtbiekoltp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.havefunace.top/Article/details/gtbpqhuoqv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.fengsongda.top/Article/details/gttcaqumtu.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtiktiuowb.html

G. 面向对象
来源：http://dali.jinqigufen.top/Article/details/gtexihxocw.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtcbafuisd.html

[G01] 定义类
来源：http://dali.zhaomingkeji.xyz/Article/details/gttssvmbgk.html

Py:   class User: pass
来源：http://dali.quarkkingdee.top/Article/details/gtcoohiqtw.html

PHP:  class User {}
来源：http://dali.chenzaomai.com/Article/details/gtegdooptt.html

JS:   class User {}
来源：http://dali.jqgfzy.top/Article/details/gtbvkizdzi.html

TS:   class User { name: string = ""; }
来源：http://dali.vqdsnc.cn/Article/details/gtabfkffns.html

Java: class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtademumgc.html

Go:   type User struct { Name string }
来源：http://dali.chenlongwang.top/Article/details/gtyhymllll.html

Ruby: class User; end
来源：http://dali.shangyingyoupin.top/Article/details/gtltlhrtvv.html

C#:   class User {}
来源：http://dali.meibo888.top/Article/details/gtlbdpgwcx.html

[G02] 构造函数
来源：http://dali.yuanzhike.top/Article/details/gtjwoqgaxg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yueranfly.top/Article/details/gtibchkqwb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sxryk.cn/Article/details/gthxgyakob.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.aibaodan.cn/Article/details/gtwzclxaoh.html

TS:   constructor(public name: string) {}
来源：http://dali.guowangkeji.top/Article/details/gtgrvelrtr.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gtmjueusjd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sxryk.cn/Article/details/gtplxhymro.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gaohongyu789.top/Article/details/gtshqutmgn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtgifrlbim.html

[G03] 实例属性
来源：http://dali.zdqjudy.top/Article/details/gtpmsfncfh.html

Py:   self.name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gtnubqgawa.html

PHP:  public string $name = "x";
来源：http://dali.yvedp.cn/Article/details/gtpqmgodts.html

JS:   this.name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtkofuttpz.html

TS:   name: string = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtcmvagnyq.html

Java: private String name;
来源：http://dali.yvedp.cn/Article/details/gtobgcppfo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cashguo.top/Article/details/gtzxuqfgsx.html

Ruby: @name = "x"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoqxwhlnp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.daria6918.cn/Article/details/gthezkmqmi.html

[G04] 定义方法
来源：http://dali.xylfe.cn/Article/details/gthytoongo.html

Py:   def greet(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gtvdftahie.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gteujwofco.html

JS:   greet() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gtgdfuikcy.html

TS:   greet(): string { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtrmrbbypv.html

Java: String greet() { return name; }
来源：http://dali.316326.xyz/Article/details/gtwhveulnn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gttfgqvrux.html

Ruby: def greet; @name; end
来源：http://dali.dashuyun.cn/Article/details/gtbrfkqykg.html

C#:   public string Greet() => Name;
来源：http://dali.xuanzx.com/Article/details/gtyistmjps.html

[G05] 继承
来源：http://dali.quarkkingdee.top/Article/details/gtoidcckrl.html

Py:   class Admin(User): pass
来源：http://dali.gotoacloud.top/Article/details/gtjkxpmrui.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtcwyzfkoq.html

JS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcoesgmxl.html

TS:   class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gttuewyynv.html

Java: class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtpypnpmbp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cdnleiting.top/Article/details/gtldwtyvfq.html

Ruby: class Admin < User; end
来源：http://dali.ehwqpu.com/Article/details/gtnavsbnas.html

C#:   class Admin : User {}
来源：http://dali.meibo888.top/Article/details/gtlcaxvpky.html

[G06] 重写方法
来源：http://dali.yj202588.top/Article/details/gttujdqkks.html

Py:   def greet(self): return "admin"
来源：http://dali.cqqwz.cn/Article/details/gtqjxqjvyz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtsrskyhnp.html

JS:   greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtainynjpe.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtrhwqeljg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfivxvsgx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenlongwang.top/Article/details/gtsvwuqfna.html

Ruby: def greet; "admin"; end
来源：http://dali.jianghu66.top/Article/details/gtqdqewjny.html

C#:   public override string Greet() => "admin";
来源：http://dali.tian-w.cn/Article/details/gtcisofrso.html

[G07] 调用父类方法
来源：http://dali.gotoacloud.top/Article/details/gtjjiqotwf.html

Py:   super().greet()
来源：http://dali.wangdashe.top/Article/details/gtfcezqiur.html

PHP:  parent::greet();
来源：http://dali.cucudq.cn/Article/details/gtrqungeun.html

JS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gthoyehrxa.html

TS:   super.greet();
来源：http://dali.0kj1m.cn/Article/details/gtyavkhvrk.html

Java: super.greet();
来源：http://dali.yj20258.top/Article/details/gtzraypvlj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.316326.xyz/Article/details/gtjnchqhas.html

Ruby: super
来源：http://dali.9152youxi.cn/Article/details/gtlkspiaaq.html

C#:   base.Greet();
来源：http://dali.snrcjt.cn/Article/details/gtldaxzjgr.html

[G08] 静态方法与属性
来源：http://dali.0kj1m.cn/Article/details/gtegylzqxf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhiwuduotai.top/Article/details/gttzyyevqz.html

PHP:  public static function f() {}
来源：http://dali.chenlongwang.top/Article/details/gtacnpscdd.html

JS:   static f() {}
来源：http://dali.c1oappe.top/Article/details/gttpirlrnv.html

TS:   static f(): void {}
来源：http://dali.gogol.net.cn/Article/details/gtkyghsmvd.html

Java: static void f() {}
来源：http://dali.aizwys.cn/Article/details/gtwbhgkpgp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hammf.cn/Article/details/gtuebttycb.html

Ruby: def self.f; end
来源：http://dali.daxiang520.top/Article/details/gtldcuvfne.html

C#:   public static void F() {}
来源：http://dali.c1oappe.top/Article/details/gtwlmjzueu.html

[G09] 接口 / 抽象类
来源：http://dali.ppjwa.cn/Article/details/gtbwguflpi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nanxinkj.top/Article/details/gtzauawetd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.316326.xyz/Article/details/gtwawflahr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.aibaodan.cn/Article/details/gtjccqofic.html

TS:   interface Shape { area(): number; }
来源：http://dali.ehwqpu.com/Article/details/gtiokvzkpl.html

Java: interface Shape { double area(); }
来源：http://dali.daxiang520.top/Article/details/gtiaxxeuhr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xuetiantiany.cn/Article/details/gtwakvpbtb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yonumen.top/Article/details/gtsalpaaul.html

C#:   interface IShape { double Area(); }
来源：http://dali.jiagoushi.top/Article/details/gtieofnceq.html

[G10] 访问控制
来源：http://dali.smart0.xyz/Article/details/gtduyhjqgc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinqigfzy.top/Article/details/gtosltohqa.html

PHP:  public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gtjcojlxry.html

JS:   #private 字段；其余公开
来源：http://dali.jqgfzy.top/Article/details/gtbppdgqpv.html

TS:   public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtyqcgclkg.html

Java: public / protected / private / 默认包级
来源：http://dali.iojbl.cn/Article/details/gtpwvsfpnp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hongshengwenyu.top/Article/details/gtkeecwxit.html

Ruby: public / protected / private
来源：http://dali.yueranfly.top/Article/details/gtjoezirkx.html

C#:   public / protected / private / internal
来源：http://dali.sxryk.cn/Article/details/gtircgaynb.html

[G11] getter / setter
来源：http://dali.birdmap.top/Article/details/gtnpexgbuo.html

Py:   @property 与 @x.setter
来源：http://dali.yuxming.cn/Article/details/gtolviymdc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gtjkdtjnks.html

JS:   get name() { return this._name; }
来源：http://dali.smart0.xyz/Article/details/gtjurutbny.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gtvbmnqzba.html

Java: public String getName() { return name; }
来源：http://dali.gzhubu.top/Article/details/gtenemryqp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtvsgbrkqm.html

Ruby: attr_accessor :name
来源：http://dali.wangshuangyany.cn/Article/details/gtqwisxlpn.html

C#:   public string Name { get; set; }
来源：http://dali.hnxiangtu.top/Article/details/gtoqoeqxwj.html

[G12] 对象转字符串
来源：http://dali.birdmap.top/Article/details/gtzviprchl.html

Py:   def __str__(self): return self.name
来源：http://dali.jinghuilouyu.cn/Article/details/gtlfymyeaq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gtjfzasira.html

JS:   toString() { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtlgsmaajp.html

TS:   toString(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunwhvoji.html

Java: @Override public String toString() { return name; }
来源：http://dali.ydzc1.top/Article/details/gtxfrsxhjx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gthachhgvd.html

Ruby: def to_s; @name; end
来源：http://dali.316326.xyz/Article/details/gtfswrtrlb.html

C#:   public override string ToString() => Name;
来源：http://dali.nanxinkj.top/Article/details/gttcnfduon.html

[G13] 判断对象类型
来源：http://dali.chenjidiqi.icu/Article/details/gtsjjsmasg.html

Py:   isinstance(u, User)
来源：http://dali.xinyue.icu/Article/details/gtdxgrlptb.html

PHP:  $u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtwpcfgqpb.html

JS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtrkuzqztf.html

TS:   u instanceof User
来源：http://dali.yonumen.top/Article/details/gtauzcejga.html

Java: u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtxvuogttk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.chenzaomai.com/Article/details/gtdjdeejxt.html

Ruby: u.is_a?(User)
来源：http://dali.shangyingyoupin.top/Article/details/gttyvmnayz.html

C#:   u is User
来源：http://dali.aizwys.cn/Article/details/gtfczmmcmz.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmjuiciy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgufenzy.top/Article/details/gtpnahlvmk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj20258.top/Article/details/gttaiuibah.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yueranfly.top/Article/details/gtyrqoclui.html


<!-- 参考信息 -->