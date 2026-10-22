代发 wailian999

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xinyue.icu/Article/details/gtzfokmmjp.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhongyouzk.top/Article/details/gtenpewwrx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zycfv.cn/Article/details/gteqhzkgpt.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj20258888.top/Article/details/gtifuhfqmf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenlongwang.top/Article/details/gtppmnfdbd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jlsjyb.cn/Article/details/gtticmdvyr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqugjxxec.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhixingplan.top/Article/details/gtwsfiszpx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.smart0.xyz/Article/details/gtpxpkfglh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnqzz.top/Article/details/gtyculhqcs.html

[E16] 数字千分位
来源：http://dali.jiagoushi.top/Article/details/gtgjwevskb.html

Py:   f"{1234567:,}"
来源：http://dali.aizwys.cn/Article/details/gtzlfwwkhe.html

PHP:  number_format(1234567);
来源：http://dali.feifeiyinyue.top/Article/details/gtzeoevjba.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.fengsongda.top/Article/details/gttncyqzwo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gaohongyu789.top/Article/details/gtpcvejrpi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nanxuanxn.top/Article/details/gtyvqknybh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj20258.top/Article/details/gtgijdygkt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenzaomai.com/Article/details/gtzjfvkjgu.html

C#:   1234567.ToString("N0")
来源：http://dali.0kj1m.cn/Article/details/gtayavtzbh.html

[E17] 首字母大写
来源：http://dali.xylfe.cn/Article/details/gtibaoprry.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.daria6918.cn/Article/details/gtfzildwvz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.c1oappe.top/Article/details/gtaikcwldv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtjzrwvmfw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.svipenyu.cn/Article/details/gtwxjqerdi.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.aibaodan.cn/Article/details/gtjnznnpvc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hnqzz.top/Article/details/gtxfxihlou.html

Ruby: s.capitalize
来源：http://dali.pengpengdd.cyou/Article/details/gtgajanelm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.dianchejie.cn/Article/details/gtafkcoxnb.html

[E18] 模板占位符替换
来源：http://dali.hnxiangtu.top/Article/details/gtfkhmsflk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ivvv.top/Article/details/gtyjntklaw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sufxvd.cn/Article/details/gtnjyixqoo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gtpssuhfli.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtuftbsmgu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gtuukgxlqh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtarivdxxl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tanke756.top/Article/details/gthffpkpdg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zycfv.cn/Article/details/gtdsrrobny.html

[E19] 多行文本按行拆分
来源：http://dali.kuanghao11.cn/Article/details/gtrbcqslko.html

Py:   s.splitlines()
来源：http://dali.zhengqikj.top/Article/details/gtxjgkhsvr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkxytcssb.html

JS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gtplinsyou.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenjidiqi.icu/Article/details/gtlkcyfvjk.html

Java: s.lines().toList()
来源：http://dali.ydzc1.top/Article/details/gtclagxmkd.html

Go:   strings.Split(s, "\n")
来源：http://dali.vqdsnc.cn/Article/details/gtazudepjv.html

Ruby: s.lines
来源：http://dali.fzhhl.top/Article/details/gtkrxlgcba.html

C#:   s.Split('\n')
来源：http://dali.chenjidiqi.icu/Article/details/gtutppucej.html

[E20] 判断字符串是否为空
来源：http://dali.jinghuilouyu.cn/Article/details/gtqjycppxq.html

Py:   if not s:
来源：http://dali.shanyushiyangtech.top/Article/details/gtnhgnbbup.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.fengsongda.top/Article/details/gtmnzenspw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.aibaodan.cn/Article/details/gtjrygxmog.html

TS:   if (s === "") {}
来源：http://dali.316326.xyz/Article/details/gtjpdmeyjb.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenzaomai.com/Article/details/gtohbubbwv.html

Go:   if s == "" {}
来源：http://dali.andypj.xyz/Article/details/gtizdhzvlk.html

Ruby: if s.empty?
来源：http://dali.jinghuilouyu.cn/Article/details/gtjtanqbep.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.dashuyun.cn/Article/details/gtkglogwmf.html

[E21] 超长截断加省略号
来源：http://dali.jqgfzy.top/Article/details/gtwuaztgpd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ehwqpu.com/Article/details/gtvtdzvkfx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gtiyrtarer.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvswbsicr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtoyrpaazi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtjnkhzftd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jqgfzy.top/Article/details/gtrpfbrxfj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtrcfumpcb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtuqxqcxmn.html

[E22] 字节长度与字符长度
来源：http://dali.ehwqpu.com/Article/details/gtwosxdjov.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhoulong.xyz/Article/details/gtuckdykwl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gtjpuhgems.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dashuyun.cn/Article/details/gtfexmjzym.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhixingplan.top/Article/details/gthwicoqys.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.haohaochexian.top/Article/details/gtgyvtonrl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xinyue.icu/Article/details/gtwoglunsv.html

Ruby: s.bytesize;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gtbqvucjdd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cdnleiting.top/Article/details/gtquauhbjn.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtvemrokwk.html

F. 文件与目录
来源：http://dali.yuxming.cn/Article/details/gtviehxicf.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gteqsojshj.html

[F01] 读取整个文件
来源：http://dali.hongshengwenyu.top/Article/details/gthnorfxww.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.redwolf501.top/Article/details/gtrqrytvyl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtyrvhuqzb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yonumen.top/Article/details/gtxbgxiude.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hnqzz.top/Article/details/gtebnqttkd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtalyuoqcy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xylfe.cn/Article/details/gtizkaispt.html

Ruby: File.read("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtxdboaqqr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtiaetdbyp.html

[F02] 逐行读取文件
来源：http://dali.iojbl.cn/Article/details/gtlrydrkim.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcknncnst.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jiagoushi.top/Article/details/gtrjtfvetl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tian-w.cn/Article/details/gthruqzmtq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nwbrower.top/Article/details/gtrarzruak.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jlsjyb.cn/Article/details/gtaokntgdy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cashguo.top/Article/details/gtfpubpuno.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yvedp.cn/Article/details/gtfiascrix.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.haohaochexian.top/Article/details/gtercdwyfk.html

[F03] 写入文件（覆盖）
来源：http://dali.cashguo.top/Article/details/gtxygrgwjj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinqigufen.top/Article/details/gtwvefwmps.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sysykeji.top/Article/details/gthpavderf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gtfrqdvdxt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nwbrower.top/Article/details/gtayxwrkpb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sufxvd.cn/Article/details/gtxvycdvzo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xinyue.icu/Article/details/gttywzlurk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenjidiqi.icu/Article/details/gturaumpjb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.c1oappe.top/Article/details/gtmugwcggz.html

[F04] 追加写入文件
来源：http://dali.zhengqikj.top/Article/details/gtjnavxksw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.guannengcc.top/Article/details/gtkttgkpsx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.wangdashe.top/Article/details/gtcrcummgp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnxiangtu.top/Article/details/gtzodwnddt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dianchejie.cn/Article/details/gtcmoouiwi.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yuanzhike.top/Article/details/gtjuogzdjs.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hnxiangtu.top/Article/details/gtarwotyqa.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jyoumei.cn/Article/details/gtslhuzmhp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hywenlv.cn/Article/details/gtkrpntlut.html

[F05] 判断文件或目录是否存在
来源：http://dali.shzxlz.cn/Article/details/gtkpjhlwig.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gogol.net.cn/Article/details/gtlokqajjg.html

PHP:  file_exists("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtljpdfnxk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtkamghwnd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtcdcilurv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtifwsnzjj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.haohaochexian.top/Article/details/gtnsumgnum.html

Ruby: File.exist?("a.txt")
来源：http://dali.mhx1999.top/Article/details/gthiooaifj.html

C#:   File.Exists("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtipanhyqw.html

[F06] 删除文件
来源：http://dali.hywenlv.cn/Article/details/gtpqkzlbly.html

Py:   os.remove("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtuvqaslmw.html

PHP:  unlink("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtljvgtilp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gturmzequq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtebbnujcq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtewluaqhc.html

Go:   os.Remove("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtmevwwpdg.html

Ruby: File.delete("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtjyokblrn.html

C#:   File.Delete("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtdsipdscn.html

[F07] 创建目录（含多级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtniesebag.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.daria6918.cn/Article/details/gtnwbpattz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tianlin.xyz/Article/details/gtxuemrrxd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gtqzcpsebk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ivvv.top/Article/details/gtbqkseiwz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.vqdsnc.cn/Article/details/gtsbavabkg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jlsjyb.cn/Article/details/gtdnlnxgda.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yangfankeji.com/Article/details/gtsslalkwo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzpmeipev.html

[F08] 遍历目录
来源：http://dali.nwbrower.top/Article/details/gtuqjcgjxk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hongshengwenyu.top/Article/details/gtamsrbomb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shangyingyoupin.top/Article/details/gthmhfibmy.html

JS:   fs.readdirSync("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtjtsqbich.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenlongwang.top/Article/details/gtwaschrbb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gogol.net.cn/Article/details/gtrkedcpkx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenlongwang.top/Article/details/gtdnlxfwue.html

Ruby: Dir.children("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgiauptxf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xinyue.icu/Article/details/gtpypfvpnv.html

[F09] 获取文件大小
来源：http://dali.pengpengdd.cyou/Article/details/gtkccysiyj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtqyovfede.html

PHP:  filesize("a.txt");
来源：http://dali.pycfn.com/Article/details/gtapqgrzgv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yanxiufei.cn/Article/details/gtiqgsfvbi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jyoumei.cn/Article/details/gtbnajkkir.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtyxfciivy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.havefunace.top/Article/details/gtwvimobgq.html

Ruby: File.size("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtvufllbuv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinqigufen.top/Article/details/gtfybwmvav.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yangfankeji.com/Article/details/gtpzrukbwo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtoeulvljd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtbnvvqzvq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtqhtqfdsg.html

TS:   path.extname("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtbagwgvee.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cheryme.top/Article/details/gtjgalobdp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtbvlvwjwr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtfajgzikw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtgzdenqsb.html

[F11] 复制与移动文件
来源：http://dali.wangdashe.top/Article/details/gtqxyupxzm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtinlnaqby.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.c1oappe.top/Article/details/gtwgmrbodf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtoqnucmkv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtsyyvoitu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gtgfyszrwp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdzxjztdh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtbtzqdtfl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.havefunace.top/Article/details/gtehezocvl.html

[F12] CSV 读写
来源：http://dali.cqqwz.cn/Article/details/gtjjrqkycm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gaohongyu789.top/Article/details/gtitzgvtic.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hnxiangtu.top/Article/details/gtuzyjewyv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cucudq.cn/Article/details/gtbegohbox.html

TS:   // 同上
来源：http://dali.ydzc1.top/Article/details/gtpzvuobrd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenjidiqi.icu/Article/details/gtzewuuqen.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jlsjyb.cn/Article/details/gtacwomutr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jiagoushi.top/Article/details/gtckvdkmsa.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shzxlz.cn/Article/details/gtmvyyxqbo.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtfhnzfjvm.html

G. 面向对象
来源：http://dali.aibaodan.cn/Article/details/gttczanlkn.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtshatoekn.html

[G01] 定义类
来源：http://dali.yj202588.top/Article/details/gtszvrwqrz.html

Py:   class User: pass
来源：http://dali.birdmap.top/Article/details/gticzfleym.html

PHP:  class User {}
来源：http://dali.shuidangran.top/Article/details/gtbvqnspyr.html

JS:   class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtcsonrumk.html

TS:   class User { name: string = ""; }
来源：http://dali.fengsongda.top/Article/details/gtpnnejpsw.html

Java: class User {}
来源：http://dali.cashguo.top/Article/details/gthywjuott.html

Go:   type User struct { Name string }
来源：http://dali.tanke756.top/Article/details/gtnxolfjgu.html

Ruby: class User; end
来源：http://dali.vqdsnc.cn/Article/details/gtxrtuzjle.html

C#:   class User {}
来源：http://dali.yj202588.top/Article/details/gtdkxxclfs.html

[G02] 构造函数
来源：http://dali.yanxiufei.cn/Article/details/gtsigdowdw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yongpay.top/Article/details/gtcaxtoqwp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gotoacloud.top/Article/details/gthwldgstp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gttppghrbi.html

TS:   constructor(public name: string) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsnpqmtus.html

Java: User(String name) { this.name = name; }
来源：http://dali.xinyue.icu/Article/details/gtouuzapfo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yvedp.cn/Article/details/gtefckdztm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhoulong.xyz/Article/details/gthhkrvezx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cdnleiting.top/Article/details/gtwdyhipvr.html

[G03] 实例属性
来源：http://dali.feifeiyinyue.top/Article/details/gtltxauavq.html

Py:   self.name = "x"
来源：http://dali.guowangkeji.top/Article/details/gtfqtpthju.html

PHP:  public string $name = "x";
来源：http://dali.daxiang520.top/Article/details/gtghbcrmtc.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtsphlasnx.html

TS:   name: string = "x";
来源：http://dali.smart0.xyz/Article/details/gtbrtdtebj.html

Java: private String name;
来源：http://dali.ppjwa.cn/Article/details/gtcdfuwvnj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zycfv.cn/Article/details/gteacilual.html

Ruby: @name = "x"
来源：http://dali.cashguo.top/Article/details/gttoflghlm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yonumen.top/Article/details/gtnhcgxmlh.html

[G04] 定义方法
来源：http://dali.daxiang520.top/Article/details/gtguhvigxp.html

Py:   def greet(self): return self.name
来源：http://dali.kuanghao11.cn/Article/details/gtknnajvue.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gtbgpqszas.html

JS:   greet() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtpdvaycyd.html

TS:   greet(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtrdnktxgg.html

Java: String greet() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtctahqalg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gtngxhyamn.html

Ruby: def greet; @name; end
来源：http://dali.wangdashe.top/Article/details/gthzrszkqp.html

C#:   public string Greet() => Name;
来源：http://dali.guannengcc.top/Article/details/gtrcaickpf.html

[G05] 继承
来源：http://dali.smart0.xyz/Article/details/gtjmhxsmtn.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gtguujhwkm.html

PHP:  class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtyhhajrwp.html

JS:   class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtwcbwdmdl.html

TS:   class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtxqlxscmk.html

Java: class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtptlumzwg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ivvv.top/Article/details/gtlwdcseqf.html

Ruby: class Admin < User; end
来源：http://dali.jqgufenzy.top/Article/details/gtqudtvkhc.html

C#:   class Admin : User {}
来源：http://dali.jiagoushi.top/Article/details/gtsytzrubv.html

[G06] 重写方法
来源：http://dali.nanxinkj.top/Article/details/gtmlkvanwu.html

Py:   def greet(self): return "admin"
来源：http://dali.tian-w.cn/Article/details/gtcquzxqos.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gthosbnunz.html

JS:   greet() { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtgdlmlppu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtkcqsdsol.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtpkfswjco.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.pengpengdd.cyou/Article/details/gttvdyrair.html

Ruby: def greet; "admin"; end
来源：http://dali.yvedp.cn/Article/details/gthzlrozfc.html

C#:   public override string Greet() => "admin";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtltunhqet.html

[G07] 调用父类方法
来源：http://dali.cheryme.top/Article/details/gtqzxsrhwx.html

Py:   super().greet()
来源：http://dali.tanke756.top/Article/details/gtulrhtpcx.html

PHP:  parent::greet();
来源：http://dali.hysaishi.cn/Article/details/gtpwmggdpo.html

JS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gtgqtiizox.html

TS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gtmypocorg.html

Java: super.greet();
来源：http://dali.shzxlz.cn/Article/details/gtppvcmlyh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.havefunace.top/Article/details/gtyywwyden.html

Ruby: super
来源：http://dali.ppjwa.cn/Article/details/gtgzobapyy.html

C#:   base.Greet();
来源：http://dali.cqqwz.cn/Article/details/gtvtomezuj.html

[G08] 静态方法与属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzowfczzn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigfzy.top/Article/details/gtvtmcqqxe.html

PHP:  public static function f() {}
来源：http://dali.cdnleiting.top/Article/details/gtfkslggpw.html

JS:   static f() {}
来源：http://dali.birdmap.top/Article/details/gtujwlsxjg.html

TS:   static f(): void {}
来源：http://dali.haohaochexian.top/Article/details/gtomombzvp.html

Java: static void f() {}
来源：http://dali.ehwqpu.com/Article/details/gtfnqarwgx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.quarkkingdee.top/Article/details/gtfeivtruo.html

Ruby: def self.f; end
来源：http://dali.sufxvd.cn/Article/details/gtdcobzawc.html

C#:   public static void F() {}
来源：http://dali.ehwqpu.com/Article/details/gtlngklrbb.html

[G09] 接口 / 抽象类
来源：http://dali.hysaishi.cn/Article/details/gtbkageqqf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pycfn.com/Article/details/gttkatkcsf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenjidiqi.icu/Article/details/gthngqcnat.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xylfe.cn/Article/details/gtuunydhtt.html

TS:   interface Shape { area(): number; }
来源：http://dali.yanxiufei.cn/Article/details/gtkshrcrsl.html

Java: interface Shape { double area(); }
来源：http://dali.yvedp.cn/Article/details/gtprdbnvkq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ppjwa.cn/Article/details/gtgxtgxbgb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.kuanghao11.cn/Article/details/gtgkammuds.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtefnzcmku.html

[G10] 访问控制
来源：http://dali.chenlongwang.top/Article/details/gtzrvaiqft.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinqigufen.top/Article/details/gtaenbtwbt.html

PHP:  public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gthgozvjnd.html

JS:   #private 字段；其余公开
来源：http://dali.guowangkeji.top/Article/details/gtdrccaflx.html

TS:   public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gttrtcaamr.html

Java: public / protected / private / 默认包级
来源：http://dali.sysykeji.top/Article/details/gtsmisvdct.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuzqwjbeo.html

Ruby: public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtovqperoa.html

C#:   public / protected / private / internal
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiukztvhz.html

[G11] getter / setter
来源：http://dali.nanxuanxn.top/Article/details/gtmicnemjt.html

Py:   @property 与 @x.setter
来源：http://dali.yangfankeji.com/Article/details/gttvsstkzv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gtjlthunbz.html

JS:   get name() { return this._name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gticzsuqer.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gtemczgitd.html

Java: public String getName() { return name; }
来源：http://dali.xuanzx.com/Article/details/gtusxddhhz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gtgnuifzor.html

Ruby: attr_accessor :name
来源：http://dali.cucudq.cn/Article/details/gthbcooylk.html

C#:   public string Name { get; set; }
来源：http://dali.daria6918.cn/Article/details/gtbxhdkqxt.html

[G12] 对象转字符串
来源：http://dali.aibaodan.cn/Article/details/gtgxvoczws.html

Py:   def __str__(self): return self.name
来源：http://dali.shuidangran.top/Article/details/gtdbpxjrxu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gtxoncblmq.html

JS:   toString() { return this.name; }
来源：http://dali.316326.xyz/Article/details/gtgneqmyco.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtqlktvebc.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzqfenygs.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gtdbfpwczm.html

Ruby: def to_s; @name; end
来源：http://dali.pengpengdd.cyou/Article/details/gtppacvebw.html

C#:   public override string ToString() => Name;
来源：http://dali.aibaodan.cn/Article/details/gtskseanzp.html

[G13] 判断对象类型
来源：http://dali.yuanzhike.top/Article/details/gtvewkhehr.html

Py:   isinstance(u, User)
来源：http://dali.sxryk.cn/Article/details/gttsmpvgvo.html

PHP:  $u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtpggyxkvl.html

JS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtxoctsmhn.html

TS:   u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtmsxhdiwf.html


<!-- 参考信息 -->