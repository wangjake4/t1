代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cucudq.cn/Article/details/gtxnsccvhk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aizwys.cn/Article/details/gtyptmfank.html

[E16] 数字千分位
来源：http://dali.9152youxi.cn/Article/details/gtzqixrwuj.html

Py:   f"{1234567:,}"
来源：http://dali.dashuyun.cn/Article/details/gtkstaustl.html

PHP:  number_format(1234567);
来源：http://dali.dashuyun.cn/Article/details/gtkeeytwgi.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gthcpegptv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hysaishi.cn/Article/details/gtjtjihjwu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.kuanghao11.cn/Article/details/gtbtbfgxuy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhoulong.xyz/Article/details/gtaowfykhl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sysykeji.top/Article/details/gtygguseay.html

C#:   1234567.ToString("N0")
来源：http://dali.svipenyu.cn/Article/details/gtgadlohfg.html

[E17] 首字母大写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtycrvctsu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shangyingyoupin.top/Article/details/gtgndztwto.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhongyouzk.top/Article/details/gtxxxllraj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gzhubu.top/Article/details/gtjqlvcewn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ivvv.top/Article/details/gtykulufxy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xinyue.icu/Article/details/gtzrnpmdum.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hywenlv.cn/Article/details/gtpjmkbnft.html

Ruby: s.capitalize
来源：http://dali.hfpthk.cn/Article/details/gtunlqihgt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.iojbl.cn/Article/details/gtgwfbktah.html

[E18] 模板占位符替换
来源：http://dali.hysaishi.cn/Article/details/gtderopczd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gtslnbxfrw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.redwolf501.top/Article/details/gtnazqojro.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtnrvjmgsk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtpsyhfxqh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtufmstzlr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gtogyfhnel.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.redwolf501.top/Article/details/gtjdiphlkl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.meibo888.top/Article/details/gtamqfwlde.html

[E19] 多行文本按行拆分
来源：http://dali.gotoacloud.top/Article/details/gthixfgrln.html

Py:   s.splitlines()
来源：http://dali.zhixingplan.top/Article/details/gttsqmagzl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ivvv.top/Article/details/gtyiatdjuo.html

JS:   s.split(/\r?\n/)
来源：http://dali.hysaishi.cn/Article/details/gtbkmdyibe.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenjidiqi.icu/Article/details/gtyxqtflzj.html

Java: s.lines().toList()
来源：http://dali.vqdsnc.cn/Article/details/gtnzbxpnll.html

Go:   strings.Split(s, "\n")
来源：http://dali.dianchejie.cn/Article/details/gtvvotxtcg.html

Ruby: s.lines
来源：http://dali.ybcxt.top/Article/details/gtqohykpgi.html

C#:   s.Split('\n')
来源：http://dali.yonumen.top/Article/details/gtqlqhqjbm.html

[E20] 判断字符串是否为空
来源：http://dali.cheryme.top/Article/details/gtqpkzvknx.html

Py:   if not s:
来源：http://dali.yuanzhike.top/Article/details/gtayvydnog.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shzxlz.cn/Article/details/gtcdbxhqcv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pycfn.com/Article/details/gtrnrpjhpz.html

TS:   if (s === "") {}
来源：http://dali.tianlin.xyz/Article/details/gtbtrkolfi.html

Java: if (s.isEmpty()) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtatiqfwsz.html

Go:   if s == "" {}
来源：http://dali.yuanzhike.top/Article/details/gtmkhwolcs.html

Ruby: if s.empty?
来源：http://dali.sufxvd.cn/Article/details/gtnsxoqxwh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtilzkuvfm.html

[E21] 超长截断加省略号
来源：http://dali.pengpengdd.cyou/Article/details/gtnvlaclqf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.kuanghao11.cn/Article/details/gtiipvgvnp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtphyxneli.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtvhgwqemw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtgxsivckp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gtnozyzexi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nanxuanxn.top/Article/details/gtusutlaul.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jianghu66.top/Article/details/gthrcigacr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtliqpqjnl.html

[E22] 字节长度与字符长度
来源：http://dali.gaohongyu789.top/Article/details/gtkxtgacqd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xylfe.cn/Article/details/gtlqrynlhy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtayxwxtvn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sweek.top/Article/details/gteejeleff.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtslukpzaa.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shuidangran.top/Article/details/gtnfcrxkbn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.9152youxi.cn/Article/details/gtjpjacfxg.html

Ruby: s.bytesize;  s.length
来源：http://dali.shzxlz.cn/Article/details/gtrvsssrqd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shuidangran.top/Article/details/gtiwtnmbbm.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtqyulfwkn.html

F. 文件与目录
来源：http://dali.cqqwz.cn/Article/details/gtbgibpqsn.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtstizzlkk.html

[F01] 读取整个文件
来源：http://dali.zhengqikj.top/Article/details/gtauvqkxtg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tian-w.cn/Article/details/gtktlwiniv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtdgvqcyfi.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.0kj1m.cn/Article/details/gtksmupsdz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gtzwkxurrk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtocxwpwgp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhiwuduotai.top/Article/details/gtabmvnsja.html

Ruby: File.read("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtutcstgdg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtaekwjhsc.html

[F02] 逐行读取文件
来源：http://dali.zhengqikj.top/Article/details/gtgwafkzik.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gtiahiokld.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhongyouzk.top/Article/details/gtnowueekz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtxlsnryon.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cucudq.cn/Article/details/gttestqyyi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gttzdkvshg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.aibaodan.cn/Article/details/gtifdjqavg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nanxinkj.top/Article/details/gtcvdfbkiw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.redwolf501.top/Article/details/gthhfveavw.html

[F03] 写入文件（覆盖）
来源：http://dali.zhengqikj.top/Article/details/gtlobvjyzy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtymegopxj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gtcyncldqr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gtwiqtqpng.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yongpay.top/Article/details/gtdvxnubaz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hysaishi.cn/Article/details/gtibqezdpu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinqigfzy.top/Article/details/gtdcnsqmgi.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guannengcc.top/Article/details/gtujrmwovx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hywenlv.cn/Article/details/gtuxovvgkb.html

[F04] 追加写入文件
来源：http://dali.wangdashe.top/Article/details/gtfimkxkcx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenzaomai.com/Article/details/gtogqjyjek.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nanxuanxn.top/Article/details/gtrkbctrjt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258888.top/Article/details/gtfhcqvaev.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gtdzalgzmu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hnxiangtu.top/Article/details/gtfugvtioh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gtcznbicyj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guannengcc.top/Article/details/gtxkmmvilx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinqigufen.top/Article/details/gtfvwemfdi.html

[F05] 判断文件或目录是否存在
来源：http://dali.gzhubu.top/Article/details/gtkvuzyuoy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tianlin.xyz/Article/details/gturzkmfyz.html

PHP:  file_exists("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtggjjqeqt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtfvmbuesp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtijlhntft.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gttnfitior.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.feifeiyinyue.top/Article/details/gtbpvycewz.html

Ruby: File.exist?("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtqtedzood.html

C#:   File.Exists("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtqemzfnct.html

[F06] 删除文件
来源：http://dali.zhiwuduotai.top/Article/details/gthhsqkwyl.html

Py:   os.remove("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gteccwwopk.html

PHP:  unlink("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtxlbmnxtv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtlueeiaml.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtfpwuxfpd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtrjqatmkt.html

Go:   os.Remove("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtotdsggux.html

Ruby: File.delete("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gteuzbaaiw.html

C#:   File.Delete("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtkrlnjqlf.html

[F07] 创建目录（含多级）
来源：http://dali.daxiang520.top/Article/details/gtjyzoudug.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cqqwz.cn/Article/details/gtfqwapgis.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhixingplan.top/Article/details/gtkbagigxx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuanzhike.top/Article/details/gtxvkbmtla.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.9152youxi.cn/Article/details/gtkfzllmxg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.fzhhl.top/Article/details/gtvapqqugz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cheryme.top/Article/details/gtsqvttdoe.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yvedp.cn/Article/details/gtwwwldlix.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.quarkkingdee.top/Article/details/gtwbpncenu.html

[F08] 遍历目录
来源：http://dali.gotoacloud.top/Article/details/gtxwmvivhq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigfzy.top/Article/details/gtzzbdqcbh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.c1oappe.top/Article/details/gtlxravxpx.html

JS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gtpjgfadtb.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenzaomai.com/Article/details/gtuvcyjvfr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gaohongyu789.top/Article/details/gtwvytdkhw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.daria6918.cn/Article/details/gtdyuryoer.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258888.top/Article/details/gtccwtystg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.birdmap.top/Article/details/gtneodzzmz.html

[F09] 获取文件大小
来源：http://dali.hfpthk.cn/Article/details/gtzbmrenly.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtsglwcldb.html

PHP:  filesize("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtubimsfgb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenjidiqi.icu/Article/details/gthqnopchc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.redwolf501.top/Article/details/gtngxwnuez.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gthcbrumue.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cqqwz.cn/Article/details/gtnworshre.html

Ruby: File.size("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtyvqhcfhy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhiwuduotai.top/Article/details/gtvdfpblfc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yonumen.top/Article/details/gtvvzyoiom.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtmmcbzcio.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hammf.cn/Article/details/gttgfcjmuz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtgoogdwww.html

TS:   path.extname("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtnzjryobt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangdashe.top/Article/details/gtlxneesjg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtlrezrsvf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtysxogpfu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtpuldxzgd.html

[F11] 复制与移动文件
来源：http://dali.cucudq.cn/Article/details/gtkunhydau.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtsdljdsjt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.316326.xyz/Article/details/gtotzebvjs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gtqtsdakgt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gttevygblm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jqgufenzy.top/Article/details/gthnavtqsy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ybcxt.top/Article/details/gtkrivdqir.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtbmxdfopq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yonumen.top/Article/details/gtzakugqpb.html

[F12] CSV 读写
来源：http://dali.shangyingyoupin.top/Article/details/gthcdnakaj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj20258888.top/Article/details/gtgtstzlsp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.fzhhl.top/Article/details/gtfvyofcup.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pycfn.com/Article/details/gtdwvkjwlr.html

TS:   // 同上
来源：http://dali.aizwys.cn/Article/details/gtbosgnsjo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jiagoushi.top/Article/details/gtfclmireo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gtrtkzeejr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.mhx1999.top/Article/details/gthhpptdvz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shanyushiyangtech.top/Article/details/gtpsootzcw.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtqtlpqehm.html

G. 面向对象
来源：http://dali.hysaishi.cn/Article/details/gtlesiwjrs.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtevpevcpt.html

[G01] 定义类
来源：http://dali.jianghu66.top/Article/details/gttaxwdhis.html

Py:   class User: pass
来源：http://dali.jyoumei.cn/Article/details/gtjnkvuxdh.html

PHP:  class User {}
来源：http://dali.jianghu66.top/Article/details/gtxrctaykn.html

JS:   class User {}
来源：http://dali.haohaochexian.top/Article/details/gtbhpqaior.html

TS:   class User { name: string = ""; }
来源：http://dali.dashuyun.cn/Article/details/gtogahwgsq.html

Java: class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtkgtobzdu.html

Go:   type User struct { Name string }
来源：http://dali.cucudq.cn/Article/details/gtlcukkxvm.html

Ruby: class User; end
来源：http://dali.ehwqpu.com/Article/details/gttuoalmqt.html

C#:   class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtytafgahr.html

[G02] 构造函数
来源：http://dali.sysykeji.top/Article/details/gtstmexveo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.snrcjt.cn/Article/details/gtjyjhoomg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fengsongda.top/Article/details/gtqefjuwvn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gtjnbpwiuw.html

TS:   constructor(public name: string) {}
来源：http://dali.hysaishi.cn/Article/details/gtkfirgzgr.html

Java: User(String name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gtgdpnioob.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zdqjudy.top/Article/details/gtnmrkycbi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gogol.net.cn/Article/details/gtbjlrzcwq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ehwqpu.com/Article/details/gtgmwtlhbt.html

[G03] 实例属性
来源：http://dali.hysaishi.cn/Article/details/gtbyqpivcv.html

Py:   self.name = "x"
来源：http://dali.c1oappe.top/Article/details/gtyfcadozy.html

PHP:  public string $name = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtippernyn.html

JS:   this.name = "x";
来源：http://dali.c1oappe.top/Article/details/gtvyuarqnu.html

TS:   name: string = "x";
来源：http://dali.gzhubu.top/Article/details/gtdnmhujzl.html

Java: private String name;
来源：http://dali.9152youxi.cn/Article/details/gtarwcprfv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zdqjudy.top/Article/details/gtrrhnvwvp.html

Ruby: @name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gtqkfvlzhc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.daria6918.cn/Article/details/gthhdnmjbd.html

[G04] 定义方法
来源：http://dali.mhx1999.top/Article/details/gtzllzpsbv.html

Py:   def greet(self): return self.name
来源：http://dali.ybcxt.top/Article/details/gthxjeleix.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtfgzurzhg.html

JS:   greet() { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtykaakvky.html

TS:   greet(): string { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gthziqvbxh.html

Java: String greet() { return name; }
来源：http://dali.xylfe.cn/Article/details/gtckocxzad.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gtskmbqeyp.html

Ruby: def greet; @name; end
来源：http://dali.sweek.top/Article/details/gtstshwufd.html

C#:   public string Greet() => Name;
来源：http://dali.hnxiangtu.top/Article/details/gtqerchbpk.html

[G05] 继承
来源：http://dali.tanke756.top/Article/details/gtxbfzqriz.html

Py:   class Admin(User): pass
来源：http://dali.meibo888.top/Article/details/gtfqzkmmmy.html

PHP:  class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtueefergb.html

JS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtgenqcgog.html

TS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtjrqklxyp.html

Java: class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtejjpgsci.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.iojbl.cn/Article/details/gtgvhrhmda.html

Ruby: class Admin < User; end
来源：http://dali.jqgufenzy.top/Article/details/gteabfikod.html

C#:   class Admin : User {}
来源：http://dali.gaohongyu789.top/Article/details/gthrhoxihu.html

[G06] 重写方法
来源：http://dali.yuanzhike.top/Article/details/gtbtbsugrb.html

Py:   def greet(self): return "admin"
来源：http://dali.zycfv.cn/Article/details/gtffykhzon.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gtxwqlzyjv.html

JS:   greet() { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtfuvhmjzl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtvpwstjsv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtyoktgimz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.andypj.xyz/Article/details/gtscefaqhs.html

Ruby: def greet; "admin"; end
来源：http://dali.haohaochexian.top/Article/details/gtthdkamrw.html

C#:   public override string Greet() => "admin";
来源：http://dali.daxiang520.top/Article/details/gtyyucpiem.html

[G07] 调用父类方法
来源：http://dali.bjfxy.top/Article/details/gtyjmjqbeq.html

Py:   super().greet()
来源：http://dali.nanxinkj.top/Article/details/gtipmbcunj.html

PHP:  parent::greet();
来源：http://dali.yj20258888.top/Article/details/gtugcvhjvk.html

JS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gtgifjpzym.html

TS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gtzkfwrgru.html

Java: super.greet();
来源：http://dali.yuxming.cn/Article/details/gtgdcchkel.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sufxvd.cn/Article/details/gtsexyfyho.html

Ruby: super
来源：http://dali.tanke756.top/Article/details/gtraveozmu.html

C#:   base.Greet();
来源：http://dali.snrcjt.cn/Article/details/gttvelcujc.html

[G08] 静态方法与属性
来源：http://dali.cucudq.cn/Article/details/gtazhkphcw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yangfankeji.com/Article/details/gtjujeptxr.html

PHP:  public static function f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gteuekrkdz.html

JS:   static f() {}
来源：http://dali.yvedp.cn/Article/details/gtiaqyolco.html

TS:   static f(): void {}
来源：http://dali.hysaishi.cn/Article/details/gtjtgxdfdh.html

Java: static void f() {}
来源：http://dali.ydzc1.top/Article/details/gtdrglwglj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.0kj1m.cn/Article/details/gtrdbxtysk.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gthozqbniu.html

C#:   public static void F() {}
来源：http://dali.xylfe.cn/Article/details/gtoaidjgtm.html

[G09] 接口 / 抽象类
来源：http://dali.sxryk.cn/Article/details/gtifnwtacl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxhqjxes.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gaohongyu789.top/Article/details/gtgkequnde.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yonumen.top/Article/details/gtjzcfzoxu.html

TS:   interface Shape { area(): number; }
来源：http://dali.tanke756.top/Article/details/gtvyqlhlsg.html

Java: interface Shape { double area(); }
来源：http://dali.9152youxi.cn/Article/details/gtzfpfzftx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xylfe.cn/Article/details/gtwbktsvpu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sufxvd.cn/Article/details/gtmgjjjegf.html

C#:   interface IShape { double Area(); }
来源：http://dali.aibaodan.cn/Article/details/gtprieuuty.html

[G10] 访问控制
来源：http://dali.pengpengdd.cyou/Article/details/gtnjuxrhzy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.c1oappe.top/Article/details/gtbrzwbtyu.html

PHP:  public / protected / private
来源：http://dali.yongpay.top/Article/details/gtsyravpvd.html

JS:   #private 字段；其余公开
来源：http://dali.tianlin.xyz/Article/details/gtpvixfmvu.html

TS:   public / protected / private
来源：http://dali.ydzc1.top/Article/details/gtwacghhlk.html

Java: public / protected / private / 默认包级
来源：http://dali.sufxvd.cn/Article/details/gtoaezjbej.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ppjwa.cn/Article/details/gtvolcoxeg.html

Ruby: public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtxcsporpc.html

C#:   public / protected / private / internal
来源：http://dali.xuanzx.com/Article/details/gtovwrvcjm.html

[G11] getter / setter
来源：http://dali.aibaodan.cn/Article/details/gtcgcfoivc.html

Py:   @property 与 @x.setter
来源：http://dali.jinghuilouyu.cn/Article/details/gtugnhcune.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtzfvxzpgy.html

JS:   get name() { return this._name; }
来源：http://dali.jinqigfzy.top/Article/details/gtqipsnmuw.html

TS:   get name(): string { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gtomxcrpda.html

Java: public String getName() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtbwioibeq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gtnjvvhlid.html

Ruby: attr_accessor :name
来源：http://dali.hnqzz.top/Article/details/gtnbvqmdjz.html

C#:   public string Name { get; set; }
来源：http://dali.ybcxt.top/Article/details/gtliaqbnrb.html

[G12] 对象转字符串
来源：http://dali.redwolf501.top/Article/details/gtxedkelfd.html

Py:   def __str__(self): return self.name
来源：http://dali.ivvv.top/Article/details/gtfhyzbcix.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtitzwwaon.html

JS:   toString() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtggfrrlhv.html

TS:   toString(): string { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtzvpjjnhi.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gteaigruyj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtegqfeeqy.html

Ruby: def to_s; @name; end
来源：http://dali.ppjwa.cn/Article/details/gtzjaxotgf.html

C#:   public override string ToString() => Name;
来源：http://dali.nanxinkj.top/Article/details/gteqybmwov.html

[G13] 判断对象类型
来源：http://dali.jqgfzy.top/Article/details/gtigzxvwzz.html

Py:   isinstance(u, User)
来源：http://dali.cqqwz.cn/Article/details/gtkplcinaf.html

PHP:  $u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtygqqjgru.html

JS:   u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtteecgpxi.html

TS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtkmsmknxl.html

Java: u instanceof User
来源：http://dali.yj20258.top/Article/details/gtvixxiggs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nwbrower.top/Article/details/gtuthwawrd.html

Ruby: u.is_a?(User)
来源：http://dali.yuxming.cn/Article/details/gtvhzhrjgz.html

C#:   u is User
来源：http://dali.shanyushiyangtech.top/Article/details/gtsrstjcjt.html

[G14] 数据类 / record
来源：http://dali.zhongyouzk.top/Article/details/gtbntoxjib.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.redwolf501.top/Article/details/gtxlyhsbvr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gogol.net.cn/Article/details/gtbrvmmpwf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.havefunace.top/Article/details/gtgvceqmzx.html


<!-- 参考信息 -->