代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ybcxt.top/Article/details/gtixjlptif.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtggeecnpw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xziqi.cn/Article/details/gtenoajzqe.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.guowangkeji.top/Article/details/gtpzvtushu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ybcxt.top/Article/details/gthbvvkmut.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.0kj1m.cn/Article/details/gtqppbkalh.html

[E16] 数字千分位
来源：http://dali.cdnleiting.top/Article/details/gtonvwyhvs.html

Py:   f"{1234567:,}"
来源：http://dali.zhongyouzk.top/Article/details/gthasgkzze.html

PHP:  number_format(1234567);
来源：http://dali.haohaochexian.top/Article/details/gtyreyszdt.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.dianchejie.cn/Article/details/gtpmyuopzi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.feifeiyinyue.top/Article/details/gtpbckqouh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gogol.net.cn/Article/details/gtwnwffmoq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.guannengcc.top/Article/details/gtqsdriabx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yj20258888.top/Article/details/gtdcqnppvm.html

C#:   1234567.ToString("N0")
来源：http://dali.shuidangran.top/Article/details/gtxbbupkzp.html

[E17] 首字母大写
来源：http://dali.yj20258.top/Article/details/gttzzfwqwy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gaohongyu789.top/Article/details/gtvaadrpip.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jqgufenzy.top/Article/details/gtsbwizpzs.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258888.top/Article/details/gtglmoxprm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijatovnh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsjteddqs.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gaohongyu789.top/Article/details/gtwpasowqc.html

Ruby: s.capitalize
来源：http://dali.yvedp.cn/Article/details/gtnvexirry.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tanke756.top/Article/details/gtnlmgbkrk.html

[E18] 模板占位符替换
来源：http://dali.cashguo.top/Article/details/gtrhtxmnqh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.vqdsnc.cn/Article/details/gtfmgtxrwz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ydzc1.top/Article/details/gtsrcgzfjg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gtazbmavjm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtsjbgxicp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gtrqroxwqy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zycfv.cn/Article/details/gtmsfngvsg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yongpay.top/Article/details/gtiuehgkoc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nanxuanxn.top/Article/details/gtmsjljprv.html

[E19] 多行文本按行拆分
来源：http://dali.vqdsnc.cn/Article/details/gtmwsmfvyg.html

Py:   s.splitlines()
来源：http://dali.gotoacloud.top/Article/details/gtomudtjnk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtulwwpjgn.html

JS:   s.split(/\r?\n/)
来源：http://dali.dianchejie.cn/Article/details/gteafpiekf.html

TS:   s.split(/\r?\n/)
来源：http://dali.redwolf501.top/Article/details/gtafgvntyi.html

Java: s.lines().toList()
来源：http://dali.ydzc1.top/Article/details/gtjajdusyd.html

Go:   strings.Split(s, "\n")
来源：http://dali.yonumen.top/Article/details/gtrdhmfjmd.html

Ruby: s.lines
来源：http://dali.yongpay.top/Article/details/gtbhqwuocz.html

C#:   s.Split('\n')
来源：http://dali.fengsongda.top/Article/details/gtttbgdera.html

[E20] 判断字符串是否为空
来源：http://dali.birdmap.top/Article/details/gtluyfeqez.html

Py:   if not s:
来源：http://dali.iojbl.cn/Article/details/gtjpoeexun.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jianghu66.top/Article/details/gtlmmcdevx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gttzmzwyri.html

TS:   if (s === "") {}
来源：http://dali.yanxiufei.cn/Article/details/gtphytwxxm.html

Java: if (s.isEmpty()) {}
来源：http://dali.gotoacloud.top/Article/details/gtkntyxgzj.html

Go:   if s == "" {}
来源：http://dali.c1oappe.top/Article/details/gttadlcczo.html

Ruby: if s.empty?
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbrcvtmr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.redwolf501.top/Article/details/gtnhllcxld.html

[E21] 超长截断加省略号
来源：http://dali.zhiwuduotai.top/Article/details/gtyzhdqylw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yanxiufei.cn/Article/details/gtiangwmqu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gtslkpojmj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgwyujsxm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtptwfrmod.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjxykdkho.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cheryme.top/Article/details/gtdsvkqbne.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.316326.xyz/Article/details/gtwtwnvyqg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtfrrfuxpl.html

[E22] 字节长度与字符长度
来源：http://dali.andypj.xyz/Article/details/gtarbbfdqx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xinyue.icu/Article/details/gtdxpllhrs.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gtewbsufez.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj202588.top/Article/details/gtjkdupjel.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daxiang520.top/Article/details/gtuegpsujs.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xylfe.cn/Article/details/gtidwgfnxk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.feifeiyinyue.top/Article/details/gtkfkipqih.html

Ruby: s.bytesize;  s.length
来源：http://dali.zdqjudy.top/Article/details/gtuhjpebrw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gogol.net.cn/Article/details/gtefllawqc.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtvjievkor.html

F. 文件与目录
来源：http://dali.cdnleiting.top/Article/details/gtdhmqdukv.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumuygfci.html

[F01] 读取整个文件
来源：http://dali.cucudq.cn/Article/details/gtxlbphnjo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xylfe.cn/Article/details/gtvyiqqivh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtehopexef.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.fengsongda.top/Article/details/gtlvenxipo.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gtdgpymotp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtwuzdxxau.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gogol.net.cn/Article/details/gtdaspolwg.html

Ruby: File.read("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gteillfydn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gttxvnpxdg.html

[F02] 逐行读取文件
来源：http://dali.nwbrower.top/Article/details/gtginsbzzx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.kuanghao11.cn/Article/details/gtvtbwdtrg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ppjwa.cn/Article/details/gtkftxdgyv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtbjcviztf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jiagoushi.top/Article/details/gtwfmiaytv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hammf.cn/Article/details/gtscrwapgb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hnqzz.top/Article/details/gtldjhceqb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwlttvqy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhongyouzk.top/Article/details/gtbebctmen.html

[F03] 写入文件（覆盖）
来源：http://dali.pycfn.com/Article/details/gtzgmsaxmz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yangfankeji.com/Article/details/gtewusjowv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cheryme.top/Article/details/gtffaxiwqm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gtuazsgtlz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gtedovflpk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jianghu66.top/Article/details/gtlourumah.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.iojbl.cn/Article/details/gtfbdaowqs.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tianlin.xyz/Article/details/gtxyfdflxv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yonumen.top/Article/details/gtrvwiwmha.html

[F04] 追加写入文件
来源：http://dali.gzhubu.top/Article/details/gtsyhfxbri.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtgyxqjqvj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttnmffdyd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yvedp.cn/Article/details/gtkgmemalv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gtkdzrksuf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gtlnirytrd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tianlin.xyz/Article/details/gtmgrxndjh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhiwuduotai.top/Article/details/gtrlozwqnw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenzaomai.com/Article/details/gtlkinuttq.html

[F05] 判断文件或目录是否存在
来源：http://dali.chenzaomai.com/Article/details/gtgthoybou.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.chenlongwang.top/Article/details/gtckshltif.html

PHP:  file_exists("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtbfnayzry.html

JS:   fs.existsSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gtvuvixpsf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtjegnfdmu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtmswajodg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.svipenyu.cn/Article/details/gtmfnvrtbn.html

Ruby: File.exist?("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtpkwkujtd.html

C#:   File.Exists("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdlojcylj.html

[F06] 删除文件
来源：http://dali.gotoacloud.top/Article/details/gtjlagcwfn.html

Py:   os.remove("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtaroenipm.html

PHP:  unlink("a.txt");
来源：http://dali.meibo888.top/Article/details/gttmfkfbpq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtwnbomrxu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtylasahpz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gtdusvobyi.html

Go:   os.Remove("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtqvfkgkld.html

Ruby: File.delete("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtqybcgkpm.html

C#:   File.Delete("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtnlmjsafa.html

[F07] 创建目录（含多级）
来源：http://dali.vqdsnc.cn/Article/details/gtqpimglqj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.mhx1999.top/Article/details/gtoytmqcbx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tian-w.cn/Article/details/gtxpilndin.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tian-w.cn/Article/details/gtcurykpec.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.svipenyu.cn/Article/details/gtutcszilo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nanxinkj.top/Article/details/gtzkmaslcs.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cashguo.top/Article/details/gtljdnsbqf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yongpay.top/Article/details/gtomikhrfz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xylfe.cn/Article/details/gtfrrrygjd.html

[F08] 遍历目录
来源：http://dali.cucudq.cn/Article/details/gtwdolsidu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.guannengcc.top/Article/details/gtjkvwjhra.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ppjwa.cn/Article/details/gtmbkziscf.html

JS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gttocegwzy.html

TS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gtgxknfckk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cdnleiting.top/Article/details/gtupatdypm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yongpay.top/Article/details/gtegvzpflp.html

Ruby: Dir.children("dir")
来源：http://dali.jinqigufen.top/Article/details/gtdldbaots.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cashguo.top/Article/details/gtxuduhnqx.html

[F09] 获取文件大小
来源：http://dali.svipenyu.cn/Article/details/gteedxxqzy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtarbazxoq.html

PHP:  filesize("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtjmyaamat.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gtlyshlcwu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gtwvfydikd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gtblowbjlw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.aibaodan.cn/Article/details/gtszeefmvx.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtxfiujxyi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.bjfxy.top/Article/details/gtyjcqrzgw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sysykeji.top/Article/details/gtyrodradt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtatsqbebv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtljfnvbqb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtggmutwyh.html

TS:   path.extname("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtuzxhrieu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cheryme.top/Article/details/gtlrovusul.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtrpuqnyoa.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtekkyuoqz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtoxwyhliu.html

[F11] 复制与移动文件
来源：http://dali.aizwys.cn/Article/details/gtwzgtjzyz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtayidnajd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtlnmqurkk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtshupglwu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtbgneqboh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dashuyun.cn/Article/details/gtbhvfqssa.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhiwuduotai.top/Article/details/gtoirggecl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtiqgfypey.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.vqdsnc.cn/Article/details/gtthuiuerf.html

[F12] CSV 读写
来源：http://dali.cheryme.top/Article/details/gtmxfpdblj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cucudq.cn/Article/details/gtieocfgsh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbmbtvyv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.birdmap.top/Article/details/gtderhkafc.html

TS:   // 同上
来源：http://dali.quarkkingdee.top/Article/details/gtweipsqmy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hysaishi.cn/Article/details/gtnalukuna.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yangfankeji.com/Article/details/gtsiaakymt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gaohongyu789.top/Article/details/gtaeyoibok.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258888.top/Article/details/gtzvqqycmc.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtuwtnxyxz.html

G. 面向对象
来源：http://dali.zhoulong.xyz/Article/details/gtaywfrqht.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtlrjyhghi.html

[G01] 定义类
来源：http://dali.316326.xyz/Article/details/gtbgksurpr.html

Py:   class User: pass
来源：http://dali.wangdashe.top/Article/details/gttygrsamc.html

PHP:  class User {}
来源：http://dali.c1oappe.top/Article/details/gttjevopba.html

JS:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gterspgqwt.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258.top/Article/details/gtxhltgzoy.html

Java: class User {}
来源：http://dali.birdmap.top/Article/details/gtddvwvkht.html

Go:   type User struct { Name string }
来源：http://dali.guowangkeji.top/Article/details/gtpeldgcug.html

Ruby: class User; end
来源：http://dali.jqgfzy.top/Article/details/gtvosaoxvq.html

C#:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gtkcgqrkzl.html

[G02] 构造函数
来源：http://dali.wangdashe.top/Article/details/gtcrzqdrfg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tianlin.xyz/Article/details/gtlbokvadm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.bjfxy.top/Article/details/gtasyueunc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gtuqtvowfc.html

TS:   constructor(public name: string) {}
来源：http://dali.hywenlv.cn/Article/details/gtudvscdss.html

Java: User(String name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gtvmfirfjq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xinyue.icu/Article/details/gtlqqxbebm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xinyue.icu/Article/details/gtyjlciixy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jqgfzy.top/Article/details/gtszaebbsa.html

[G03] 实例属性
来源：http://dali.cqqwz.cn/Article/details/gtuvzwbybu.html

Py:   self.name = "x"
来源：http://dali.snrcjt.cn/Article/details/gtmbkbxowz.html

PHP:  public string $name = "x";
来源：http://dali.daxiang520.top/Article/details/gthngnteiz.html

JS:   this.name = "x";
来源：http://dali.meibo888.top/Article/details/gtaggrhzsq.html

TS:   name: string = "x";
来源：http://dali.yuanzhike.top/Article/details/gtawlkebuh.html

Java: private String name;
来源：http://dali.hfpthk.cn/Article/details/gtnvqyrttw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.fengsongda.top/Article/details/gtmopgihrn.html

Ruby: @name = "x"
来源：http://dali.shuidangran.top/Article/details/gtwciaverv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtxaujqjnr.html

[G04] 定义方法
来源：http://dali.chenlongwang.top/Article/details/gtvmirdqkm.html

Py:   def greet(self): return self.name
来源：http://dali.316326.xyz/Article/details/gtzgpvjjwt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwlkfxvqc.html

JS:   greet() { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtwkogsksz.html

TS:   greet(): string { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtuigpyphm.html

Java: String greet() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtqrmrpbgi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtfbdlrutd.html

Ruby: def greet; @name; end
来源：http://dali.yanxiufei.cn/Article/details/gthmnxdokd.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gtpbxjyevm.html

[G05] 继承
来源：http://dali.jqgufenzy.top/Article/details/gtfiwjscbo.html

Py:   class Admin(User): pass
来源：http://dali.yonumen.top/Article/details/gtsgjpmbmk.html

PHP:  class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtonbxwcql.html

JS:   class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtorzzslhy.html

TS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtyjtjgiqv.html

Java: class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtpwjkdrcf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangtech.top/Article/details/gttdbtrudp.html

Ruby: class Admin < User; end
来源：http://dali.cheryme.top/Article/details/gtslwvgcra.html

C#:   class Admin : User {}
来源：http://dali.yj20258888.top/Article/details/gtevghhnyh.html

[G06] 重写方法
来源：http://dali.gaohongyu789.top/Article/details/gtimroztjx.html

Py:   def greet(self): return "admin"
来源：http://dali.tanke756.top/Article/details/gtpaqkiepc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gthjfvtlol.html

JS:   greet() { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtafxgynbv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtjembkcgs.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtwplvbnrz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258888.top/Article/details/gttwrvgarr.html

Ruby: def greet; "admin"; end
来源：http://dali.yj202588.top/Article/details/gtsmtsizbe.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxinkj.top/Article/details/gttgolvwkq.html

[G07] 调用父类方法
来源：http://dali.ybcxt.top/Article/details/gtrxivkbeu.html

Py:   super().greet()
来源：http://dali.jinqigufen.top/Article/details/gtxfwzdvft.html

PHP:  parent::greet();
来源：http://dali.guannengcc.top/Article/details/gthvuzjmqc.html

JS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gttbvnzoqm.html

TS:   super.greet();
来源：http://dali.c1oappe.top/Article/details/gtcnusfzaa.html

Java: super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtfqycigwb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhiwuduotai.top/Article/details/gtwqyypquh.html

Ruby: super
来源：http://dali.xylfe.cn/Article/details/gtdunfuqim.html

C#:   base.Greet();
来源：http://dali.zhengqikj.top/Article/details/gtfwnrhvwa.html

[G08] 静态方法与属性
来源：http://dali.yueranfly.top/Article/details/gtrdhqmqvw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.smart0.xyz/Article/details/gtpptplqtt.html

PHP:  public static function f() {}
来源：http://dali.daria6918.cn/Article/details/gtiauczfhe.html

JS:   static f() {}
来源：http://dali.ehwqpu.com/Article/details/gtoojbfifh.html

TS:   static f(): void {}
来源：http://dali.ppjwa.cn/Article/details/gtqeeigsfg.html

Java: static void f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gthfvhwmdn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenlongwang.top/Article/details/gtxkzzxzow.html

Ruby: def self.f; end
来源：http://dali.zhongyouzk.top/Article/details/gtyknypfnj.html

C#:   public static void F() {}
来源：http://dali.xuanzx.com/Article/details/gteqmufwbc.html

[G09] 接口 / 抽象类
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkcfixyk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinqigfzy.top/Article/details/gtiykpueux.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yuxming.cn/Article/details/gtduwckvdv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jlsjyb.cn/Article/details/gtdkbgfeql.html

TS:   interface Shape { area(): number; }
来源：http://dali.iojbl.cn/Article/details/gtscwnotdb.html

Java: interface Shape { double area(); }
来源：http://dali.0kj1m.cn/Article/details/gthaxmdotj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhiwuduotai.top/Article/details/gthviywtre.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmorbqprl.html

C#:   interface IShape { double Area(); }
来源：http://dali.kuanghao11.cn/Article/details/gtwpgxizpg.html

[G10] 访问控制
来源：http://dali.zycfv.cn/Article/details/gtlzedayrb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangdashe.top/Article/details/gtqwiyjxmv.html

PHP:  public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gtoxalxzbu.html

JS:   #private 字段；其余公开
来源：http://dali.sufxvd.cn/Article/details/gtppwuvtni.html

TS:   public / protected / private
来源：http://dali.andypj.xyz/Article/details/gtbysrhbrw.html

Java: public / protected / private / 默认包级
来源：http://dali.sufxvd.cn/Article/details/gtunevneot.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.haohaochexian.top/Article/details/gteuvvysep.html

Ruby: public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gtehtnsvda.html

C#:   public / protected / private / internal
来源：http://dali.daria6918.cn/Article/details/gtxqugzvze.html

[G11] getter / setter
来源：http://dali.xylfe.cn/Article/details/gtserafagf.html

Py:   @property 与 @x.setter
来源：http://dali.nanxinkj.top/Article/details/gtycshdtvf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gtjsfglwmv.html

JS:   get name() { return this._name; }
来源：http://dali.pycfn.com/Article/details/gtbgwbyfqu.html

TS:   get name(): string { return this._name; }
来源：http://dali.jyoumei.cn/Article/details/gthqzkicmh.html

Java: public String getName() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtwwromtsd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shuidangran.top/Article/details/gtkegmduzz.html

Ruby: attr_accessor :name
来源：http://dali.yj20258888.top/Article/details/gtkqzfiwsm.html

C#:   public string Name { get; set; }
来源：http://dali.nwbrower.top/Article/details/gtcfqlkwoe.html

[G12] 对象转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtvurxjoeo.html

Py:   def __str__(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gttamsuejh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtmumgridr.html

JS:   toString() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtzewbotak.html

TS:   toString(): string { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtziuugmbx.html

Java: @Override public String toString() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtaikjjlga.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtfxjmbpzu.html

Ruby: def to_s; @name; end
来源：http://dali.cucudq.cn/Article/details/gtblpmnfvi.html

C#:   public override string ToString() => Name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrujwieh.html

[G13] 判断对象类型
来源：http://dali.yj202588.top/Article/details/gtozroadku.html

Py:   isinstance(u, User)
来源：http://dali.jqgfzy.top/Article/details/gtypipsiqk.html

PHP:  $u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtrpfkyxpy.html

JS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtxcrhrrsp.html

TS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gtqofafsuk.html

Java: u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtnhpixsgy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jyoumei.cn/Article/details/gtlqlhmuxl.html

Ruby: u.is_a?(User)
来源：http://dali.shzxlz.cn/Article/details/gtjgnivdej.html

C#:   u is User
来源：http://dali.iojbl.cn/Article/details/gtprgkyrpm.html


<!-- 参考信息 -->