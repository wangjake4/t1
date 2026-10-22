代发 wailian999

Go:   strings.Count(s, "a")
来源：http://dali.xinyue.icu/Article/details/gtgknxfpkt.html

Ruby: s.count("a")
来源：http://dali.guannengcc.top/Article/details/gtmkcqzpdh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.snrcjt.cn/Article/details/gtahdeklkd.html

[E13] 逐字符遍历
来源：http://dali.9152youxi.cn/Article/details/gturainhsp.html

Py:   for ch in s: print(ch)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbwyjewn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shuidangran.top/Article/details/gteqnbrjft.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjtvnlctl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gzhubu.top/Article/details/gtehtjxmzq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shzxlz.cn/Article/details/gtlwxwzhjz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtoifisrvi.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hysaishi.cn/Article/details/gtjaawbcjp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yangfankeji.com/Article/details/gtitvwydmq.html

[E14] URL 编码与 Base64
来源：http://dali.hammf.cn/Article/details/gtsiswnfzc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinqigufen.top/Article/details/gtfyfwvkwq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.mhx1999.top/Article/details/gtsmpwgyeo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.pengpengdd.cyou/Article/details/gtppszusyq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.wangshuangyany.cn/Article/details/gthijdxwww.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.havefunace.top/Article/details/gtwolbkuht.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hongshengwenyu.top/Article/details/gtekpyvjpm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj20258.top/Article/details/gtfrywchds.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sufxvd.cn/Article/details/gtsxbgglik.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhiwuduotai.top/Article/details/gtpzszbtfd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jyoumei.cn/Article/details/gtvrkdrlfr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.pycfn.com/Article/details/gtowvqgwop.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cashguo.top/Article/details/gtoonjujsc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.aizwys.cn/Article/details/gtckidnzro.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yangfankeji.com/Article/details/gtgjlpgrek.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xziqi.cn/Article/details/gtxyuuzbgw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvewrqhhk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinqigufen.top/Article/details/gtcbufwzji.html

[E16] 数字千分位
来源：http://dali.bjfxy.top/Article/details/gtzbuibddg.html

Py:   f"{1234567:,}"
来源：http://dali.jlsjyb.cn/Article/details/gtdwbabgvx.html

PHP:  number_format(1234567);
来源：http://dali.jyoumei.cn/Article/details/gtteadmufu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuetiantiany.cn/Article/details/gtjxutyfgx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yangfankeji.com/Article/details/gtarbxayhd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jqgfzy.top/Article/details/gtimxwgtjn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.feifeiyinyue.top/Article/details/gttduztzmi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.316326.xyz/Article/details/gtadcpauuj.html

C#:   1234567.ToString("N0")
来源：http://dali.hnqzz.top/Article/details/gtfwsvcozv.html

[E17] 首字母大写
来源：http://dali.aibaodan.cn/Article/details/gtridwnjji.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.aibaodan.cn/Article/details/gtsamwoisf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.fzhhl.top/Article/details/gtrwmwkaqy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.quarkkingdee.top/Article/details/gtetubwkex.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fengsongda.top/Article/details/gtdyldwxyk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daxiang520.top/Article/details/gtcdfgttad.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xinyue.icu/Article/details/gtpgtadsbm.html

Ruby: s.capitalize
来源：http://dali.xinyue.icu/Article/details/gtoqjznicr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gaohongyu789.top/Article/details/gtgvhdxjrw.html

[E18] 模板占位符替换
来源：http://dali.guowangkeji.top/Article/details/gtquipqzhy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttygaksor.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.9152youxi.cn/Article/details/gtdwvejqxm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtmmnjalla.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.pycfn.com/Article/details/gtwhfouszc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gtgywbrqmw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gtkvaphleq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tanke756.top/Article/details/gtjwzigdhn.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jianghu66.top/Article/details/gtkakminkc.html

[E19] 多行文本按行拆分
来源：http://dali.vqdsnc.cn/Article/details/gtpmrsnwkf.html

Py:   s.splitlines()
来源：http://dali.haohaochexian.top/Article/details/gtmrjehelm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ivvv.top/Article/details/gtpboxsikn.html

JS:   s.split(/\r?\n/)
来源：http://dali.nanxinkj.top/Article/details/gtbrapobmf.html

TS:   s.split(/\r?\n/)
来源：http://dali.316326.xyz/Article/details/gtuecciccc.html

Java: s.lines().toList()
来源：http://dali.andypj.xyz/Article/details/gtjjxcprzv.html

Go:   strings.Split(s, "\n")
来源：http://dali.9152youxi.cn/Article/details/gtnxkrtqvm.html

Ruby: s.lines
来源：http://dali.cqqwz.cn/Article/details/gtsnhuznaq.html

C#:   s.Split('\n')
来源：http://dali.smart0.xyz/Article/details/gthcidsbuo.html

[E20] 判断字符串是否为空
来源：http://dali.nwbrower.top/Article/details/gtopicltwl.html

Py:   if not s:
来源：http://dali.smart0.xyz/Article/details/gtyqflbiky.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.316326.xyz/Article/details/gtyqngbuqb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xinyue.icu/Article/details/gtgeijupdr.html

TS:   if (s === "") {}
来源：http://dali.yueranfly.top/Article/details/gtbaikdlus.html

Java: if (s.isEmpty()) {}
来源：http://dali.sysykeji.top/Article/details/gtshqozgry.html

Go:   if s == "" {}
来源：http://dali.zhengqikj.top/Article/details/gteyxnpald.html

Ruby: if s.empty?
来源：http://dali.gogol.net.cn/Article/details/gtxdepmzxr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.dianchejie.cn/Article/details/gtufchgrhd.html

[E21] 超长截断加省略号
来源：http://dali.gaohongyu789.top/Article/details/gtrkyqqlsm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hammf.cn/Article/details/gtjtezvdgm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gtttsxkduh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtyzbgeiel.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtbgcnutbw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtwulofamf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cdnleiting.top/Article/details/gtiygqkiab.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtlwgneldk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yj20258.top/Article/details/gtymgbogrx.html

[E22] 字节长度与字符长度
来源：http://dali.cdnleiting.top/Article/details/gtabowybli.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.pycfn.com/Article/details/gtzbnapeue.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gtorysedlj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guannengcc.top/Article/details/gtgrumlmid.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hysaishi.cn/Article/details/gtroeuisxm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.wangshuangyany.cn/Article/details/gtlrrkxtat.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinqigfzy.top/Article/details/gtvytdwfbw.html

Ruby: s.bytesize;  s.length
来源：http://dali.guowangkeji.top/Article/details/gtwivpfpqs.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cqqwz.cn/Article/details/gtwabfnxfp.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtadgefxdc.html

F. 文件与目录
来源：http://dali.kuanghao11.cn/Article/details/gttvhaiclc.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvnxrmgx.html

[F01] 读取整个文件
来源：http://dali.jqgfzy.top/Article/details/gtfdpcgliz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ppjwa.cn/Article/details/gtprxmjxfp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.mhx1999.top/Article/details/gttetfketq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jlsjyb.cn/Article/details/gttnseccvf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cheryme.top/Article/details/gtgqjjbcjq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gtfrzdnkfl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ybcxt.top/Article/details/gtzbbjdanc.html

Ruby: File.read("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtluiauzrd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtimqzxdkh.html

[F02] 逐行读取文件
来源：http://dali.xinyue.icu/Article/details/gtftraldcs.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xuanzx.com/Article/details/gtndglybza.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ivvv.top/Article/details/gtonpwkpce.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yongpay.top/Article/details/gtewvuyufb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.svipenyu.cn/Article/details/gtocftrjmw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.redwolf501.top/Article/details/gtjkosskfz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ivvv.top/Article/details/gtlteamxjy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zycfv.cn/Article/details/gtfscxqotv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.dianchejie.cn/Article/details/gtegdmevaz.html

[F03] 写入文件（覆盖）
来源：http://dali.guannengcc.top/Article/details/gtjomoboji.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.pycfn.com/Article/details/gtbnbxciue.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tian-w.cn/Article/details/gtefijyxlb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.smart0.xyz/Article/details/gtlyrfgdmy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gtvtgkcvng.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgpcbqnbv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tian-w.cn/Article/details/gtduyulpov.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hammf.cn/Article/details/gtlwhzwihl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gtpvsiucnd.html

[F04] 追加写入文件
来源：http://dali.jinqigfzy.top/Article/details/gtwwmtwyud.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.svipenyu.cn/Article/details/gtdnarqnan.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sweek.top/Article/details/gtoefpwysl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shuidangran.top/Article/details/gtogmokhft.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtnysnvzvo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jianghu66.top/Article/details/gtsqpubkko.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hfpthk.cn/Article/details/gtzhzwpfit.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhoulong.xyz/Article/details/gtmzunmfej.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.guowangkeji.top/Article/details/gtrkwqkcgk.html

[F05] 判断文件或目录是否存在
来源：http://dali.nanxinkj.top/Article/details/gtskbjgcls.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ybcxt.top/Article/details/gtwqdeausx.html

PHP:  file_exists("a.txt");
来源：http://dali.birdmap.top/Article/details/gtzfndwsty.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtprnkilos.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtvuyqscil.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtqhpkfrip.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.guannengcc.top/Article/details/gtlsbcikfv.html

Ruby: File.exist?("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtbzpqlypk.html

C#:   File.Exists("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtcdgdtzff.html

[F06] 删除文件
来源：http://dali.jianghu66.top/Article/details/gtzxbitnow.html

Py:   os.remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtlrlqjedx.html

PHP:  unlink("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtsjlpcrgg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtwtfxmdwu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gttxnznejg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtaarqlddk.html

Go:   os.Remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gtryrqqlzv.html

Ruby: File.delete("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtdjudfksx.html

C#:   File.Delete("a.txt");
来源：http://dali.ivvv.top/Article/details/gtgwkuptsm.html

[F07] 创建目录（含多级）
来源：http://dali.mhx1999.top/Article/details/gtwqvfupss.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxeubbvcy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhiwuduotai.top/Article/details/gtqewzrbxp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258.top/Article/details/gtovuoqckp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.svipenyu.cn/Article/details/gtbjtfhtrx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgfzy.top/Article/details/gtlnlzzrsu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ivvv.top/Article/details/gtetfeudbi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.haohaochexian.top/Article/details/gteiayrvka.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hysaishi.cn/Article/details/gtqtjpxuym.html

[F08] 遍历目录
来源：http://dali.hysaishi.cn/Article/details/gtwkwekeky.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jianghu66.top/Article/details/gtzpfmlydd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hfpthk.cn/Article/details/gtfjydzutn.html

JS:   fs.readdirSync("dir")
来源：http://dali.daxiang520.top/Article/details/gtrqzrjypy.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhengqikj.top/Article/details/gtgjkmzjkz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gtfovmxqnc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guannengcc.top/Article/details/gtyqcqkttz.html

Ruby: Dir.children("dir")
来源：http://dali.havefunace.top/Article/details/gtfxwczsil.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tanke756.top/Article/details/gtbtcypwcr.html

[F09] 获取文件大小
来源：http://dali.sweek.top/Article/details/gtzrfxhsth.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtcyyfpuwn.html

PHP:  filesize("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtcwququqc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.fzhhl.top/Article/details/gtttsnxmpb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hammf.cn/Article/details/gtcjfdaexz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gtotbyuyrk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.iojbl.cn/Article/details/gtitsssxgc.html

Ruby: File.size("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtggrjcefe.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhoulong.xyz/Article/details/gthjplgaqi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tianlin.xyz/Article/details/gtqjthsqke.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtjneqthbh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yuxming.cn/Article/details/gtttfnccar.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtybfkjeij.html

TS:   path.extname("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtgtyohvbg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258.top/Article/details/gtvioxleqc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtrclqcnkp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtaftizklj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtzhxpwzff.html

[F11] 复制与移动文件
来源：http://dali.xziqi.cn/Article/details/gtfbdypknw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gtnhxzsnft.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenzaomai.com/Article/details/gtbxluwlvw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gthxacbocy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtlqjoyurw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj202588.top/Article/details/gtunugodma.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabbklivo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtlxkbrvmw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hysaishi.cn/Article/details/gtuuesbgya.html

[F12] CSV 读写
来源：http://dali.pycfn.com/Article/details/gtiumsyizn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.svipenyu.cn/Article/details/gtnbwknkmr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.dashuyun.cn/Article/details/gtrqmmrfrq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jyoumei.cn/Article/details/gtwirdctbz.html

TS:   // 同上
来源：http://dali.hysaishi.cn/Article/details/gtdtvxqvyq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cdnleiting.top/Article/details/gtmbxzhwts.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.guowangkeji.top/Article/details/gtfamsjhan.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sweek.top/Article/details/gtqankzzos.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.quarkkingdee.top/Article/details/gtirjjyncb.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtsrfgwzli.html

G. 面向对象
来源：http://dali.yongpay.top/Article/details/gthtodhqgl.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtykjbbboo.html

[G01] 定义类
来源：http://dali.yueranfly.top/Article/details/gtqmjpuumn.html

Py:   class User: pass
来源：http://dali.shangyingyoupin.top/Article/details/gtccyndvjr.html

PHP:  class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtrpopnlcb.html

JS:   class User {}
来源：http://dali.cucudq.cn/Article/details/gtjnttvhsh.html

TS:   class User { name: string = ""; }
来源：http://dali.haohaochexian.top/Article/details/gtpcwbcssu.html

Java: class User {}
来源：http://dali.smart0.xyz/Article/details/gtouenbhbx.html

Go:   type User struct { Name string }
来源：http://dali.zhixingplan.top/Article/details/gtztwyyktu.html

Ruby: class User; end
来源：http://dali.aibaodan.cn/Article/details/gtsqypcjmt.html

C#:   class User {}
来源：http://dali.hywenlv.cn/Article/details/gtorczzgjv.html

[G02] 构造函数
来源：http://dali.cqqwz.cn/Article/details/gtoxgwfgll.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guowangkeji.top/Article/details/gtyuccgzov.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jianghu66.top/Article/details/gtsyjyahgb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gtidycoykr.html

TS:   constructor(public name: string) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpxizccsq.html

Java: User(String name) { this.name = name; }
来源：http://dali.zycfv.cn/Article/details/gtrmiovohl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.vqdsnc.cn/Article/details/gtzikacnqf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhoulong.xyz/Article/details/gthnglmhga.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gotoacloud.top/Article/details/gtzxrjqxrp.html

[G03] 实例属性
来源：http://dali.nwbrower.top/Article/details/gtfuqoefzs.html

Py:   self.name = "x"
来源：http://dali.iojbl.cn/Article/details/gtgamscslo.html

PHP:  public string $name = "x";
来源：http://dali.dianchejie.cn/Article/details/gtnotaqibj.html

JS:   this.name = "x";
来源：http://dali.hnqzz.top/Article/details/gtzjxokdkm.html

TS:   name: string = "x";
来源：http://dali.hnqzz.top/Article/details/gtsexenfqr.html

Java: private String name;
来源：http://dali.birdmap.top/Article/details/gtzbgddoro.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigfzy.top/Article/details/gtgmqvkyzs.html

Ruby: @name = "x"
来源：http://dali.sxryk.cn/Article/details/gtldwbtaeb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.316326.xyz/Article/details/gtmjiuqxal.html

[G04] 定义方法
来源：http://dali.sweek.top/Article/details/gtlsnzjggu.html

Py:   def greet(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gtdkuqkfar.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gtaidkozld.html

JS:   greet() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtlhrqlhwp.html

TS:   greet(): string { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtaoenkuxs.html

Java: String greet() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtnupmxfvl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gttdnmwdcz.html

Ruby: def greet; @name; end
来源：http://dali.316326.xyz/Article/details/gtkjuazetk.html

C#:   public string Greet() => Name;
来源：http://dali.zycfv.cn/Article/details/gthzlrtxmi.html

[G05] 继承
来源：http://dali.dianchejie.cn/Article/details/gtfrxwdeij.html

Py:   class Admin(User): pass
来源：http://dali.feifeiyinyue.top/Article/details/gtcygkxhmn.html

PHP:  class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtltxshzcr.html

JS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtlopantny.html

TS:   class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtgazrlldp.html

Java: class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtgrfqohdh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.9152youxi.cn/Article/details/gtmjvqnzfi.html

Ruby: class Admin < User; end
来源：http://dali.zhengqikj.top/Article/details/gthjmkqydn.html

C#:   class Admin : User {}
来源：http://dali.feifeiyinyue.top/Article/details/gthjkqhklw.html

[G06] 重写方法
来源：http://dali.ppjwa.cn/Article/details/gtlrugypvb.html

Py:   def greet(self): return "admin"
来源：http://dali.jyoumei.cn/Article/details/gtwxrfgere.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtgzgkxovt.html

JS:   greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtirjbarbd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtiihcourz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtvzxukcqj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xuanzx.com/Article/details/gttfgemfsi.html

Ruby: def greet; "admin"; end
来源：http://dali.sweek.top/Article/details/gtgsbdxojn.html

C#:   public override string Greet() => "admin";
来源：http://dali.aizwys.cn/Article/details/gtbwoyrvgo.html

[G07] 调用父类方法
来源：http://dali.sxryk.cn/Article/details/gtgxstbbnm.html

Py:   super().greet()
来源：http://dali.chenzaomai.com/Article/details/gtirdzorpk.html

PHP:  parent::greet();
来源：http://dali.snrcjt.cn/Article/details/gtjhwvsbve.html

JS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtepwukeky.html

TS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gtwhhemkip.html

Java: super.greet();
来源：http://dali.jqgfzy.top/Article/details/gtacqyuidh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tianlin.xyz/Article/details/gtreqyspuh.html

Ruby: super
来源：http://dali.dashuyun.cn/Article/details/gtlidoxmdj.html

C#:   base.Greet();
来源：http://dali.zhongyouzk.top/Article/details/gtcktcqeso.html

[G08] 静态方法与属性
来源：http://dali.ppjwa.cn/Article/details/gtlvhtkbbv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhiwuduotai.top/Article/details/gtfiyghgxw.html

PHP:  public static function f() {}
来源：http://dali.cdnleiting.top/Article/details/gticwimtek.html

JS:   static f() {}
来源：http://dali.dashuyun.cn/Article/details/gtdmqetvgq.html

TS:   static f(): void {}
来源：http://dali.shangyingyoupin.top/Article/details/gtvijksddp.html

Java: static void f() {}
来源：http://dali.zdqjudy.top/Article/details/gtaaxmbkgl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.guannengcc.top/Article/details/gtselgogpc.html

Ruby: def self.f; end
来源：http://dali.aibaodan.cn/Article/details/gtwjeyydni.html

C#:   public static void F() {}
来源：http://dali.jyoumei.cn/Article/details/gtcuiiptcu.html

[G09] 接口 / 抽象类
来源：http://dali.nwbrower.top/Article/details/gtewrsnuem.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.aibaodan.cn/Article/details/gtsxfflqel.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shzxlz.cn/Article/details/gtlnlhsnug.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zdqjudy.top/Article/details/gtqhonamxe.html

TS:   interface Shape { area(): number; }
来源：http://dali.aibaodan.cn/Article/details/gtfxqtzilj.html

Java: interface Shape { double area(); }
来源：http://dali.xuanzx.com/Article/details/gtenqcqzpz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hfpthk.cn/Article/details/gtjpeqkqdg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258.top/Article/details/gtpfmdfawb.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangdashe.top/Article/details/gtuxqtgawo.html

[G10] 访问控制
来源：http://dali.guowangkeji.top/Article/details/gtwnjnlwqs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nanxuanxn.top/Article/details/gtmddtwarl.html

PHP:  public / protected / private
来源：http://dali.sysykeji.top/Article/details/gtsvrmypvy.html

JS:   #private 字段；其余公开
来源：http://dali.yj202588.top/Article/details/gttxqomdjc.html

TS:   public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gtsochtwxt.html

Java: public / protected / private / 默认包级
来源：http://dali.tanke756.top/Article/details/gtgdzwpqgr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.svipenyu.cn/Article/details/gtgzbszbet.html

Ruby: public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gtygwxglkg.html

C#:   public / protected / private / internal
来源：http://dali.ivvv.top/Article/details/gtajmmlrqr.html

[G11] getter / setter
来源：http://dali.kuanghao11.cn/Article/details/gtxcbbfsez.html

Py:   @property 与 @x.setter
来源：http://dali.ivvv.top/Article/details/gtiwmkghot.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtfpabcile.html


<!-- 参考信息 -->