代发 wailian999

Go:   strings.Count(s, "a")
来源：http://dali.ppjwa.cn/Article/details/gtpgefjwyw.html

Ruby: s.count("a")
来源：http://dali.hammf.cn/Article/details/gtxdkcyvye.html

C#:   s.Count(c => c == 'a')
来源：http://dali.daria6918.cn/Article/details/gtcflzbysk.html

[E13] 逐字符遍历
来源：http://dali.iojbl.cn/Article/details/gtbbozlnhj.html

Py:   for ch in s: print(ch)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzfjrsxhb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinqigfzy.top/Article/details/gtlleaeunn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gtysnnostu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj202588.top/Article/details/gtsqwigdrp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aizwys.cn/Article/details/gtypqnqzrt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtcegwvpop.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hywenlv.cn/Article/details/gtrclupgsc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sxryk.cn/Article/details/gtmtpzewou.html

[E14] URL 编码与 Base64
来源：http://dali.guowangkeji.top/Article/details/gtnkoztvon.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shangyingyoupin.top/Article/details/gtcqxdufzb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xinyue.icu/Article/details/gtwpxlvxlg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.mhx1999.top/Article/details/gtvdawcfzb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.daxiang520.top/Article/details/gtwpcnmyan.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.iojbl.cn/Article/details/gtyybbmlac.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xuanzx.com/Article/details/gtmmcfipqw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shzxlz.cn/Article/details/gtkgdeohtt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhengqikj.top/Article/details/gtmsdomdyp.html

[E15] HTML 转义 / 反转义
来源：http://dali.jiagoushi.top/Article/details/gtjztqtfdg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.iojbl.cn/Article/details/gtzqmpawhm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.redwolf501.top/Article/details/gtgcpegqim.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cheryme.top/Article/details/gtivaguqoo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.snrcjt.cn/Article/details/gtrcidggfj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cqqwz.cn/Article/details/gtrdxnrmku.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.c1oappe.top/Article/details/gtqmsxjxgp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.quarkkingdee.top/Article/details/gtgciyxfzl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jianghu66.top/Article/details/gtjtxalvka.html

[E16] 数字千分位
来源：http://dali.snrcjt.cn/Article/details/gtecuzexcr.html

Py:   f"{1234567:,}"
来源：http://dali.xylfe.cn/Article/details/gtfpfsavol.html

PHP:  number_format(1234567);
来源：http://dali.dashuyun.cn/Article/details/gtlyzlhpeo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigfzy.top/Article/details/gtiulijywh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhengqikj.top/Article/details/gthnvktkii.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.feifeiyinyue.top/Article/details/gtsyqxdcrh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yuxming.cn/Article/details/gtqokbygnu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhongyouzk.top/Article/details/gtztdyhlgw.html

C#:   1234567.ToString("N0")
来源：http://dali.jinqigfzy.top/Article/details/gthlzaxgqt.html

[E17] 首字母大写
来源：http://dali.zdqjudy.top/Article/details/gthapoyhxl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nanxuanxn.top/Article/details/gtxtqlnymf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cucudq.cn/Article/details/gtjgmfstac.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xinyue.icu/Article/details/gtewgzafbp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.birdmap.top/Article/details/gtnkkjfgri.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gaohongyu789.top/Article/details/gtagehojrh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yonumen.top/Article/details/gtqvtzpyej.html

Ruby: s.capitalize
来源：http://dali.svipenyu.cn/Article/details/gtdcbkujai.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xinyue.icu/Article/details/gtiiehdpdr.html

[E18] 模板占位符替换
来源：http://dali.cdnleiting.top/Article/details/gtvzruishj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.quarkkingdee.top/Article/details/gtqrwdwfnn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.9152youxi.cn/Article/details/gtaqvuwuxv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tanke756.top/Article/details/gthlrjkiks.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gtkgzubdad.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gtlogrzaeb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gtvbpdmkwx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xinyue.icu/Article/details/gtifxrteoc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hywenlv.cn/Article/details/gtpdfotyqj.html

[E19] 多行文本按行拆分
来源：http://dali.quarkkingdee.top/Article/details/gtcosgzyqo.html

Py:   s.splitlines()
来源：http://dali.guannengcc.top/Article/details/gtunvrhort.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.316326.xyz/Article/details/gtlmkcdblz.html

JS:   s.split(/\r?\n/)
来源：http://dali.dashuyun.cn/Article/details/gtdwietayq.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinqigufen.top/Article/details/gtjagervff.html

Java: s.lines().toList()
来源：http://dali.yangfankeji.com/Article/details/gtfzsdltry.html

Go:   strings.Split(s, "\n")
来源：http://dali.zycfv.cn/Article/details/gtbdhrwtgu.html

Ruby: s.lines
来源：http://dali.svipenyu.cn/Article/details/gtopgxuejv.html

C#:   s.Split('\n')
来源：http://dali.shuidangran.top/Article/details/gtkkkgnmas.html

[E20] 判断字符串是否为空
来源：http://dali.redwolf501.top/Article/details/gtdhdhxhuk.html

Py:   if not s:
来源：http://dali.chenzaomai.com/Article/details/gtveelwlsg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xuanzx.com/Article/details/gtennabqcc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.wangshuangyany.cn/Article/details/gteqlongoj.html

TS:   if (s === "") {}
来源：http://dali.yanxiufei.cn/Article/details/gtoezlckth.html

Java: if (s.isEmpty()) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtzzlkxvtc.html

Go:   if s == "" {}
来源：http://dali.chenjidiqi.icu/Article/details/gtxpokadcy.html

Ruby: if s.empty?
来源：http://dali.pycfn.com/Article/details/gtgjiobspp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtvgzjpqdp.html

[E21] 超长截断加省略号
来源：http://dali.cdnleiting.top/Article/details/gtjlckeahx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gtyuzhgzqi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gttgkzqxyt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtqpaylmsf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtjqbijdfe.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtdxtaskjm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.c1oappe.top/Article/details/gtabqojacx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hammf.cn/Article/details/gtxkipsuxa.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtzyacligg.html

[E22] 字节长度与字符长度
来源：http://dali.sxryk.cn/Article/details/gtcpkucdin.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sweek.top/Article/details/gtcjyiqsto.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gtlalmrkla.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.iojbl.cn/Article/details/gteegwzoot.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gtczzxciek.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gturyyerod.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jlsjyb.cn/Article/details/gtfiddzdtz.html

Ruby: s.bytesize;  s.length
来源：http://dali.cdnleiting.top/Article/details/gtuavdfemg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.aibaodan.cn/Article/details/gtkbddfobk.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtkgyoxhmj.html

F. 文件与目录
来源：http://dali.kuanghao11.cn/Article/details/gtjksxqkvf.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtsomnvzoz.html

[F01] 读取整个文件
来源：http://dali.tanke756.top/Article/details/gtabpbusva.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.iojbl.cn/Article/details/gtomoesdht.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtvupcezud.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.svipenyu.cn/Article/details/gtfnpxyizr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shuidangran.top/Article/details/gtcmtwcari.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gtygifijll.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gogol.net.cn/Article/details/gtlkppgrbt.html

Ruby: File.read("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtnohwuxsa.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gthotpfmdt.html

[F02] 逐行读取文件
来源：http://dali.cashguo.top/Article/details/gtozouzgjn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjapglce.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xziqi.cn/Article/details/gtwlwovpvb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigfzy.top/Article/details/gtknufltuk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gogol.net.cn/Article/details/gtwmwhsowy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gtkincytbk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj202588.top/Article/details/gtfxsruqpx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj20258888.top/Article/details/gtifemvyel.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jyoumei.cn/Article/details/gtrhvvcvsj.html

[F03] 写入文件（覆盖）
来源：http://dali.vqdsnc.cn/Article/details/gtkabdfkrz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ivvv.top/Article/details/gtfrqjshzc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.316326.xyz/Article/details/gttxdopmnl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgxqphrvb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gttldnndrj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sysykeji.top/Article/details/gtfjxududo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.wangdashe.top/Article/details/gtwrraixqo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yanxiufei.cn/Article/details/gtvntgkomi.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hnxiangtu.top/Article/details/gtindqajfy.html

[F04] 追加写入文件
来源：http://dali.jiagoushi.top/Article/details/gtgjdfqxsr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.iojbl.cn/Article/details/gtxgtxcsqd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yvedp.cn/Article/details/gttllygmlw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gtoarssukc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cucudq.cn/Article/details/gtiowsuwbz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.fengsongda.top/Article/details/gtwklckgkk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xinyue.icu/Article/details/gtnntshovs.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jlsjyb.cn/Article/details/gtczlvxbum.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jiagoushi.top/Article/details/gtgghnlyov.html

[F05] 判断文件或目录是否存在
来源：http://dali.bjfxy.top/Article/details/gtqcgwmxkm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ehwqpu.com/Article/details/gtrjieysvf.html

PHP:  file_exists("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtqmdoygzz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqswlkzvq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtkmehfvos.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtizvkgmhv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.9152youxi.cn/Article/details/gtxiubgbob.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtnawjygsp.html

C#:   File.Exists("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtgjpiawjr.html

[F06] 删除文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwtiynre.html

Py:   os.remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtqhvwtksu.html

PHP:  unlink("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvtdecov.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtbcqkrqsw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtcbxrtfsf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gtdvofhuue.html

Go:   os.Remove("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtkhzinutb.html

Ruby: File.delete("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtleygogka.html

C#:   File.Delete("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtdyyhkajo.html

[F07] 创建目录（含多级）
来源：http://dali.hysaishi.cn/Article/details/gtytdmhgrz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinqigufen.top/Article/details/gtodjummfp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtreznmzsi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gtivjnkrmz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.9152youxi.cn/Article/details/gtkzqzevdi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shangyingyoupin.top/Article/details/gthhjtlmqa.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.svipenyu.cn/Article/details/gtefxiugsw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yuanzhike.top/Article/details/gtrfljreso.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.andypj.xyz/Article/details/gtdutkjnip.html

[F08] 遍历目录
来源：http://dali.fzhhl.top/Article/details/gtjvuogjer.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daxiang520.top/Article/details/gthrsfpovz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jianghu66.top/Article/details/gtbeqgioho.html

JS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtnypecczt.html

TS:   fs.readdirSync("dir")
来源：http://dali.ydzc1.top/Article/details/gtkzwmepvy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gtlgrueprl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtlllbwwua.html

Ruby: Dir.children("dir")
来源：http://dali.jinqigufen.top/Article/details/gtqvpdnefe.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtpbneecrp.html

[F09] 获取文件大小
来源：http://dali.chenlongwang.top/Article/details/gtkqgmowjx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cheryme.top/Article/details/gtqdapeduq.html

PHP:  filesize("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtjwcvylrq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gtvijrekwm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.9152youxi.cn/Article/details/gtrbotiapv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhqbrlgf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yvedp.cn/Article/details/gtbhrgzhrq.html

Ruby: File.size("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtpofoxowj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.guannengcc.top/Article/details/gtdgyjtxma.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yonumen.top/Article/details/gtseipbknn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtoovtdett.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cashguo.top/Article/details/gtxhjoygtc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtxdxaxjha.html

TS:   path.extname("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtnbiupxbp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.feifeiyinyue.top/Article/details/gteayxwcjs.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtjpukqxeq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtqhdhlzde.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtluvshkmm.html

[F11] 复制与移动文件
来源：http://dali.vqdsnc.cn/Article/details/gtcwiifdtm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtppcuodyc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jiagoushi.top/Article/details/gtqeqdccvt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtqmwppfhb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gttqcacprp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gtxrjyrawk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shzxlz.cn/Article/details/gtofigqszw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsjordsjx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.kuanghao11.cn/Article/details/gtveexcoom.html

[F12] CSV 读写
来源：http://dali.aizwys.cn/Article/details/gtqwptqajg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj20258.top/Article/details/gtjvfnslsf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cheryme.top/Article/details/gtbnwbhvgs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cashguo.top/Article/details/gtspozfkql.html

TS:   // 同上
来源：http://dali.yanxiufei.cn/Article/details/gtzszkbvwd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sxryk.cn/Article/details/gtmsuempko.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinghuilouyu.cn/Article/details/gtfoxuubnz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gogol.net.cn/Article/details/gtynbaaujq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cucudq.cn/Article/details/gtijfpousc.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtvrhmcjnf.html

G. 面向对象
来源：http://dali.ivvv.top/Article/details/gthpgewcqo.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtiyllukfb.html

[G01] 定义类
来源：http://dali.gotoacloud.top/Article/details/gteijomgzd.html

Py:   class User: pass
来源：http://dali.quarkkingdee.top/Article/details/gtjfcfwfnj.html

PHP:  class User {}
来源：http://dali.tanke756.top/Article/details/gtjbqzcrca.html

JS:   class User {}
来源：http://dali.nanxuanxn.top/Article/details/gtofodyomo.html

TS:   class User { name: string = ""; }
来源：http://dali.redwolf501.top/Article/details/gtrhnimmqh.html

Java: class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtdrvuvumz.html

Go:   type User struct { Name string }
来源：http://dali.guowangkeji.top/Article/details/gtlwpzvcyv.html

Ruby: class User; end
来源：http://dali.jqgufenzy.top/Article/details/gtrwdzowpa.html

C#:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gtqzvxsjed.html

[G02] 构造函数
来源：http://dali.zdqjudy.top/Article/details/gtxmltgovw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.9152youxi.cn/Article/details/gtrwtaslrk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtbquweqeh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtqefoyvvj.html

TS:   constructor(public name: string) {}
来源：http://dali.guowangkeji.top/Article/details/gtrumloics.html

Java: User(String name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gtouraqvqn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yongpay.top/Article/details/gtyxbsgack.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.redwolf501.top/Article/details/gtpsklufkn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtyrmyvnvj.html

[G03] 实例属性
来源：http://dali.gotoacloud.top/Article/details/gtmhdcoyrc.html

Py:   self.name = "x"
来源：http://dali.meibo888.top/Article/details/gtoegeutgu.html

PHP:  public string $name = "x";
来源：http://dali.sxryk.cn/Article/details/gtswzmjtcs.html

JS:   this.name = "x";
来源：http://dali.9152youxi.cn/Article/details/gtoudwvzhv.html

TS:   name: string = "x";
来源：http://dali.zdqjudy.top/Article/details/gtrprxgamp.html

Java: private String name;
来源：http://dali.bjfxy.top/Article/details/gtxnwevmmg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yangfankeji.com/Article/details/gtsokhlyva.html

Ruby: @name = "x"
来源：http://dali.yuxming.cn/Article/details/gtztxkussm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jyoumei.cn/Article/details/gtzdyxnzuu.html

[G04] 定义方法
来源：http://dali.cucudq.cn/Article/details/gtjjqdnqcs.html

Py:   def greet(self): return self.name
来源：http://dali.hongshengwenyu.top/Article/details/gtheztcrxr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtbrgflmcw.html

JS:   greet() { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtbtapnktw.html

TS:   greet(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtbjrejruu.html

Java: String greet() { return name; }
来源：http://dali.fengsongda.top/Article/details/gtfhfvlhbq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gthhdjwgsn.html

Ruby: def greet; @name; end
来源：http://dali.cucudq.cn/Article/details/gthswzkmfp.html

C#:   public string Greet() => Name;
来源：http://dali.yangfankeji.com/Article/details/gtuyeekhmv.html

[G05] 继承
来源：http://dali.dashuyun.cn/Article/details/gtgfzgmmwq.html

Py:   class Admin(User): pass
来源：http://dali.smart0.xyz/Article/details/gtpeapfxak.html

PHP:  class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtvneqzjmx.html

JS:   class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gtotoiuajp.html

TS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtpbrgiwtk.html

Java: class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtxbmdgrox.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hnxiangtu.top/Article/details/gtwmnguyng.html

Ruby: class Admin < User; end
来源：http://dali.sxryk.cn/Article/details/gtplyauskh.html

C#:   class Admin : User {}
来源：http://dali.ivvv.top/Article/details/gtzzdjxedh.html

[G06] 重写方法
来源：http://dali.daxiang520.top/Article/details/gtprdgyzfb.html

Py:   def greet(self): return "admin"
来源：http://dali.chenzaomai.com/Article/details/gtakldkvqh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtlzbblmup.html

JS:   greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtsaxiyoii.html

TS:   greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtexltdtjv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtixuvjcpq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zdqjudy.top/Article/details/gtqxwgyfma.html

Ruby: def greet; "admin"; end
来源：http://dali.zhixingplan.top/Article/details/gtmqxbtoan.html

C#:   public override string Greet() => "admin";
来源：http://dali.9152youxi.cn/Article/details/gtfptkokmk.html

[G07] 调用父类方法
来源：http://dali.yonumen.top/Article/details/gthtrkefid.html

Py:   super().greet()
来源：http://dali.wangdashe.top/Article/details/gtexwbohdz.html

PHP:  parent::greet();
来源：http://dali.gogol.net.cn/Article/details/gtedmblecq.html

JS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gtjgbosraa.html

TS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtrrghrenn.html

Java: super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtkautxggr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yanxiufei.cn/Article/details/gtzaatvrui.html

Ruby: super
来源：http://dali.tanke756.top/Article/details/gtapjuzgaz.html

C#:   base.Greet();
来源：http://dali.guowangkeji.top/Article/details/gttytojxug.html

[G08] 静态方法与属性
来源：http://dali.nanxuanxn.top/Article/details/gtvwswsori.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pycfn.com/Article/details/gtjfoffjmw.html

PHP:  public static function f() {}
来源：http://dali.zhengqikj.top/Article/details/gtuximugsn.html

JS:   static f() {}
来源：http://dali.zdqjudy.top/Article/details/gtilisjyfe.html

TS:   static f(): void {}
来源：http://dali.shzxlz.cn/Article/details/gtabvsyfhw.html

Java: static void f() {}
来源：http://dali.daxiang520.top/Article/details/gtrprawdnf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.guowangkeji.top/Article/details/gtwzxqllcz.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gtnfvjztml.html

C#:   public static void F() {}
来源：http://dali.gogol.net.cn/Article/details/gtdlirntcy.html

[G09] 接口 / 抽象类
来源：http://dali.xylfe.cn/Article/details/gthhffdfrq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gotoacloud.top/Article/details/gthwqdqdmv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.birdmap.top/Article/details/gtqrodxmkj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.fengsongda.top/Article/details/gtlvptwwyv.html

TS:   interface Shape { area(): number; }
来源：http://dali.yongpay.top/Article/details/gtjtbdqydm.html

Java: interface Shape { double area(); }
来源：http://dali.bjfxy.top/Article/details/gtlrdgdawe.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xylfe.cn/Article/details/gtgakhqpns.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.pengpengdd.cyou/Article/details/gtxxgouvom.html

C#:   interface IShape { double Area(); }
来源：http://dali.andypj.xyz/Article/details/gtjbmpdrzx.html

[G10] 访问控制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytqlhwta.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cqqwz.cn/Article/details/gtsuapdrhl.html

PHP:  public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gtxfthqsmx.html

JS:   #private 字段；其余公开
来源：http://dali.sufxvd.cn/Article/details/gtppwasaof.html

TS:   public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvqvysxv.html

Java: public / protected / private / 默认包级
来源：http://dali.vqdsnc.cn/Article/details/gtxosxyyrx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yueranfly.top/Article/details/gtewhhkxyu.html

Ruby: public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtxaxndufv.html

C#:   public / protected / private / internal
来源：http://dali.ybcxt.top/Article/details/gtohqljeod.html

[G11] getter / setter
来源：http://dali.gaohongyu789.top/Article/details/gtljtqwmuk.html

Py:   @property 与 @x.setter
来源：http://dali.yj202588.top/Article/details/gtlvcygerg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gtdpmoxupu.html


<!-- 参考信息 -->