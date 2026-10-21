代发 wailian999

Ruby: s.reverse
来源：http://dali.tianlin.xyz/Article/details/gtjyykyhtg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.fengsongda.top/Article/details/gtdyphsqzz.html

[E12] 统计某字符出现次数
来源：http://dali.sysykeji.top/Article/details/gtqjishdpw.html

Py:   s.count("a")
来源：http://dali.jyoumei.cn/Article/details/gtlsihdbwl.html

PHP:  substr_count($s, "a");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvkappju.html

JS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gtvfprnmjn.html

TS:   s.split("a").length - 1
来源：http://dali.xylfe.cn/Article/details/gtshvwaptu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yangfankeji.com/Article/details/gtbrldbhfa.html

Go:   strings.Count(s, "a")
来源：http://dali.pycfn.com/Article/details/gteoiltxkh.html

Ruby: s.count("a")
来源：http://dali.daxiang520.top/Article/details/gtfdhxulnx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xziqi.cn/Article/details/gtndpnscjy.html

[E13] 逐字符遍历
来源：http://dali.ivvv.top/Article/details/gtkrxyhibz.html

Py:   for ch in s: print(ch)
来源：http://dali.chenjidiqi.icu/Article/details/gtdiuakyut.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ybcxt.top/Article/details/gtdyheubnp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gtwvdvwzvn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtlygdpxqk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.9152youxi.cn/Article/details/gtzdxgqbwg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xziqi.cn/Article/details/gtxnwemsqi.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.guowangkeji.top/Article/details/gtjkbsoxxc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xylfe.cn/Article/details/gtlccdqbjg.html

[E14] URL 编码与 Base64
来源：http://dali.mhx1999.top/Article/details/gtmntuogyk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.guowangkeji.top/Article/details/gtyxejvtpp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhengqikj.top/Article/details/gtueajvnit.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jiagoushi.top/Article/details/gtpkgenmok.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yuanzhike.top/Article/details/gtdvxhpeku.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gtnayadjil.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ydzc1.top/Article/details/gtqrweqjuq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jlsjyb.cn/Article/details/gtyuyxtbfk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gtcumzryoy.html

[E15] HTML 转义 / 反转义
来源：http://dali.nwbrower.top/Article/details/gtgmemljrl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.svipenyu.cn/Article/details/gthqoyqgbs.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.dashuyun.cn/Article/details/gtvskdednw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenzaomai.com/Article/details/gtnhothygo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hnqzz.top/Article/details/gtxyevylmp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhoulong.xyz/Article/details/gtioxznjnk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.nanxuanxn.top/Article/details/gtsibptxut.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cqqwz.cn/Article/details/gtpmgijwhg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenzaomai.com/Article/details/gtrnsrygwr.html

[E16] 数字千分位
来源：http://dali.316326.xyz/Article/details/gtpoevbbig.html

Py:   f"{1234567:,}"
来源：http://dali.daxiang520.top/Article/details/gtjixxpapl.html

PHP:  number_format(1234567);
来源：http://dali.kuanghao11.cn/Article/details/gtugzxgqlf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhixingplan.top/Article/details/gtzfgktkgj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ydzc1.top/Article/details/gtzmkjzeyl.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.daxiang520.top/Article/details/gtsijkzgpg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jqgfzy.top/Article/details/gtclrdnsbr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhiwuduotai.top/Article/details/gtlitleede.html

C#:   1234567.ToString("N0")
来源：http://dali.yongpay.top/Article/details/gtxbzeziif.html

[E17] 首字母大写
来源：http://dali.xinyue.icu/Article/details/gtmoxvfltm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.dianchejie.cn/Article/details/gttfvbllip.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj20258.top/Article/details/gtkbluhfuq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gtnzwinrik.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.redwolf501.top/Article/details/gtchygdswn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.mhx1999.top/Article/details/gtlrklhtgn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtbrqlwvai.html

Ruby: s.capitalize
来源：http://dali.gogol.net.cn/Article/details/gtpjywknhb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xinyue.icu/Article/details/gtnmdjjcis.html

[E18] 模板占位符替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtoscailhu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jianghu66.top/Article/details/gtlekkognk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xylfe.cn/Article/details/gtlnpnnetd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtsadjlmvw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gthjwbdnhl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.birdmap.top/Article/details/gtjtonnsar.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gtpqbktjen.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.snrcjt.cn/Article/details/gtxvhsfrmo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.tanke756.top/Article/details/gtgpdkflbc.html

[E19] 多行文本按行拆分
来源：http://dali.gogol.net.cn/Article/details/gtsgzvclhw.html

Py:   s.splitlines()
来源：http://dali.gogol.net.cn/Article/details/gtfebtvxjo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.guannengcc.top/Article/details/gtenkwqqxj.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gtyjnrxtpv.html

TS:   s.split(/\r?\n/)
来源：http://dali.nwbrower.top/Article/details/gthipberhf.html

Java: s.lines().toList()
来源：http://dali.birdmap.top/Article/details/gtetvxnumn.html

Go:   strings.Split(s, "\n")
来源：http://dali.snrcjt.cn/Article/details/gtwqpdoytf.html

Ruby: s.lines
来源：http://dali.ydzc1.top/Article/details/gteyxcjjlk.html

C#:   s.Split('\n')
来源：http://dali.yj202588.top/Article/details/gtrsbbkrvx.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gtvohlhbzh.html

Py:   if not s:
来源：http://dali.hywenlv.cn/Article/details/gtsnktfrso.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hammf.cn/Article/details/gtccxrkhhk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.birdmap.top/Article/details/gtndzfrlxb.html

TS:   if (s === "") {}
来源：http://dali.zhongyouzk.top/Article/details/gtawzfkoes.html

Java: if (s.isEmpty()) {}
来源：http://dali.tianlin.xyz/Article/details/gtqmnxnfjx.html

Go:   if s == "" {}
来源：http://dali.jinqigufen.top/Article/details/gtrmttyunr.html

Ruby: if s.empty?
来源：http://dali.jinghuilouyu.cn/Article/details/gtyinklrxr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yanxiufei.cn/Article/details/gtjsgsaabu.html

[E21] 超长截断加省略号
来源：http://dali.svipenyu.cn/Article/details/gtqspdsljn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenlongwang.top/Article/details/gtgweltkjw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gtsjelhqca.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gtvkawxojy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtzflwltgv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtdgmkjoov.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.andypj.xyz/Article/details/gthacblnfz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtrrtxksxj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtbguxfztp.html

[E22] 字节长度与字符长度
来源：http://dali.jinqigfzy.top/Article/details/gtkuiwpigt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtiywyicwt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gtwsyxzcqu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gtejkocbnw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gtqlpdzphx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tanke756.top/Article/details/gtihhyswzq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gzhubu.top/Article/details/gtzhrukzga.html

Ruby: s.bytesize;  s.length
来源：http://dali.hysaishi.cn/Article/details/gtojkubtit.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.andypj.xyz/Article/details/gtygrwpods.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtbbvbsvud.html

F. 文件与目录
来源：http://dali.shangyingyoupin.top/Article/details/gtvbciqrku.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtfqfwfsle.html

[F01] 读取整个文件
来源：http://dali.guowangkeji.top/Article/details/gtazxivydz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gaohongyu789.top/Article/details/gtngezsxvv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtiubipvim.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xuetiantiany.cn/Article/details/gtpandtldi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gtaoejsrwd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtxmgiovpt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nanxinkj.top/Article/details/gttqxedsmw.html

Ruby: File.read("a.txt")
来源：http://dali.tanke756.top/Article/details/gtfpgfatwp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jianghu66.top/Article/details/gthetyqmoh.html

[F02] 逐行读取文件
来源：http://dali.daxiang520.top/Article/details/gtxfxymwoj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xinyue.icu/Article/details/gtczkobsvx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmyjgwhiz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dashuyun.cn/Article/details/gtkwwsfaih.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yonumen.top/Article/details/gtkdhnfcsq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.vqdsnc.cn/Article/details/gtmtbyoiiu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yanxiufei.cn/Article/details/gtdzorjyjk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pengpengdd.cyou/Article/details/gtlchqjdjk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daria6918.cn/Article/details/gtgagakwvx.html

[F03] 写入文件（覆盖）
来源：http://dali.wangdashe.top/Article/details/gtjfpqyfax.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhoulong.xyz/Article/details/gtbylqjejz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.fzhhl.top/Article/details/gthrsnnkjc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpcizzlyx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gthlauqcyu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jiagoushi.top/Article/details/gtncmlttju.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.fengsongda.top/Article/details/gtikkpgwke.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yvedp.cn/Article/details/gtcysuvope.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shuidangran.top/Article/details/gtirapvxoo.html

[F04] 追加写入文件
来源：http://dali.9152youxi.cn/Article/details/gtmaqadgsy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtmndmjmfc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ybcxt.top/Article/details/gtqxjecpzi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sufxvd.cn/Article/details/gtpgxubadw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.smart0.xyz/Article/details/gtkxjsvfpt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hammf.cn/Article/details/gtjwqnuwrq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenzaomai.com/Article/details/gttmptpauy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.daria6918.cn/Article/details/gtvlfnpjiu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.meibo888.top/Article/details/gtyzdsztlj.html

[F05] 判断文件或目录是否存在
来源：http://dali.tianlin.xyz/Article/details/gtqbfsjnni.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yongpay.top/Article/details/gttfkpsdhl.html

PHP:  file_exists("a.txt");
来源：http://dali.pycfn.com/Article/details/gtbrssbedy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtofurxgjl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtojfwvctd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gtkrhqhhvw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sufxvd.cn/Article/details/gtveucvdvu.html

Ruby: File.exist?("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtbsdyfgtm.html

C#:   File.Exists("a.txt")
来源：http://dali.mhx1999.top/Article/details/gterryuwma.html

[F06] 删除文件
来源：http://dali.cheryme.top/Article/details/gtmrtdrzut.html

Py:   os.remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gtpelxvhxb.html

PHP:  unlink("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtqxmarcrb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtkpqobpdi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gthrfhrhla.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gtjujqmbzk.html

Go:   os.Remove("a.txt")
来源：http://dali.hammf.cn/Article/details/gtkkhkhrkj.html

Ruby: File.delete("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtfzrebpjn.html

C#:   File.Delete("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtthgttgwb.html

[F07] 创建目录（含多级）
来源：http://dali.snrcjt.cn/Article/details/gtqaozcasf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nanxuanxn.top/Article/details/gttuybjkrz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jqgfzy.top/Article/details/gtbtpdcknk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gtlqcnognq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jyoumei.cn/Article/details/gtzkypsuvc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ppjwa.cn/Article/details/gthqqyuvnn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jlsjyb.cn/Article/details/gtpcphcpee.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.svipenyu.cn/Article/details/gtojdjovsx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cashguo.top/Article/details/gtemxbjkzg.html

[F08] 遍历目录
来源：http://dali.ivvv.top/Article/details/gtwmmfeqnl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.meibo888.top/Article/details/gtuzftvnjg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj20258888.top/Article/details/gtuthioyfi.html

JS:   fs.readdirSync("dir")
来源：http://dali.yonumen.top/Article/details/gteljghkev.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvohaxzmt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gtwqavrrfo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hfpthk.cn/Article/details/gtikhbhpjr.html

Ruby: Dir.children("dir")
来源：http://dali.zdqjudy.top/Article/details/gtnxypyhty.html

C#:   Directory.GetFiles("dir")
来源：http://dali.dashuyun.cn/Article/details/gteohgyaer.html

[F09] 获取文件大小
来源：http://dali.zhiwuduotai.top/Article/details/gtmrolddav.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtyagikcme.html

PHP:  filesize("a.txt");
来源：http://dali.cheryme.top/Article/details/gtdfximwcc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xziqi.cn/Article/details/gtjvybplgt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhoulong.xyz/Article/details/gtzhiceusp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtoubmlemd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hongshengwenyu.top/Article/details/gtiehtpqkx.html

Ruby: File.size("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtlgowdvrd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jiagoushi.top/Article/details/gtycmufqfc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxuanxn.top/Article/details/gtczggatom.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtgpkouqzx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yuxming.cn/Article/details/gtqhavakfc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtntmetgki.html

TS:   path.extname("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrgebnhyr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigufen.top/Article/details/gtnxyzlqsf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtvhgocgez.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtfahgueue.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtcmwupklj.html

[F11] 复制与移动文件
来源：http://dali.hfpthk.cn/Article/details/gtdqdnohgf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtkbcbuwfo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yongpay.top/Article/details/gtfgwonxzu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyeuokwtn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtnrfdmkwg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gtkxskosbs.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shzxlz.cn/Article/details/gtapasbwbv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtyjzqivwi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guowangkeji.top/Article/details/gtfagiebzw.html

[F12] CSV 读写
来源：http://dali.jinqigfzy.top/Article/details/gtohcfbamg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj202588.top/Article/details/gtrrnjfunw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jianghu66.top/Article/details/gtvxqhibea.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxinkj.top/Article/details/gtbrzoekjb.html

TS:   // 同上
来源：http://dali.nanxinkj.top/Article/details/gtvctcutqc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.wangshuangyany.cn/Article/details/gtmfcrlimp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nwbrower.top/Article/details/gtitzbfhyr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hongshengwenyu.top/Article/details/gtavvnqkhs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.mhx1999.top/Article/details/gtpywqgrpy.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtldjdpjdi.html

G. 面向对象
来源：http://dali.sxryk.cn/Article/details/gtfxuxeqll.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtpmvhxiiu.html

[G01] 定义类
来源：http://dali.pengpengdd.cyou/Article/details/gtquphuufk.html

Py:   class User: pass
来源：http://dali.cheryme.top/Article/details/gtbvtyxptv.html

PHP:  class User {}
来源：http://dali.fengsongda.top/Article/details/gtbvqeyisp.html

JS:   class User {}
来源：http://dali.nwbrower.top/Article/details/gtfvzuvtby.html

TS:   class User { name: string = ""; }
来源：http://dali.smart0.xyz/Article/details/gtbdokljiv.html

Java: class User {}
来源：http://dali.316326.xyz/Article/details/gtyiyixfll.html

Go:   type User struct { Name string }
来源：http://dali.cdnleiting.top/Article/details/gtooqlpcbm.html

Ruby: class User; end
来源：http://dali.hongshengwenyu.top/Article/details/gtiyrdqdor.html

C#:   class User {}
来源：http://dali.birdmap.top/Article/details/gtshlgdqql.html

[G02] 构造函数
来源：http://dali.ybcxt.top/Article/details/gtzpblhdkc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhixingplan.top/Article/details/gtxwzexocg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.0kj1m.cn/Article/details/gttcjdrtkb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sweek.top/Article/details/gtkwvhjkuk.html

TS:   constructor(public name: string) {}
来源：http://dali.sxryk.cn/Article/details/gtvfwfjtlb.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinqigufen.top/Article/details/gtztgvupqp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.kuanghao11.cn/Article/details/gtxzlcqdlj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenzaomai.com/Article/details/gtakjdowin.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gttjjijpms.html

[G03] 实例属性
来源：http://dali.jlsjyb.cn/Article/details/gtqxfohpkk.html

Py:   self.name = "x"
来源：http://dali.vqdsnc.cn/Article/details/gtmgakgdex.html

PHP:  public string $name = "x";
来源：http://dali.xziqi.cn/Article/details/gtuzgbfxst.html

JS:   this.name = "x";
来源：http://dali.daria6918.cn/Article/details/gtjfvxjvrc.html

TS:   name: string = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtqstbiidp.html

Java: private String name;
来源：http://dali.bjfxy.top/Article/details/gtkvysutpi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj202588.top/Article/details/gtlfhkvnlz.html

Ruby: @name = "x"
来源：http://dali.jiagoushi.top/Article/details/gtjarsrrvd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xuanzx.com/Article/details/gtielvjssb.html

[G04] 定义方法
来源：http://dali.zhongyouzk.top/Article/details/gtgtblrnoe.html

Py:   def greet(self): return self.name
来源：http://dali.ehwqpu.com/Article/details/gtyvbnntaj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gtoutjttjd.html

JS:   greet() { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gthynvlwrc.html

TS:   greet(): string { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gttwwypbmp.html

Java: String greet() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gteuuwbvmf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtkgdacwto.html

Ruby: def greet; @name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxndmryh.html

C#:   public string Greet() => Name;
来源：http://dali.jinqigfzy.top/Article/details/gtopzglujx.html

[G05] 继承
来源：http://dali.iojbl.cn/Article/details/gtaudgfdrz.html

Py:   class Admin(User): pass
来源：http://dali.ehwqpu.com/Article/details/gtxpvmbkii.html

PHP:  class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtlntgefer.html

JS:   class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtrblyzejc.html

TS:   class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtoldcgxby.html

Java: class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtpstdvdge.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ehwqpu.com/Article/details/gtexrmlrhl.html

Ruby: class Admin < User; end
来源：http://dali.cashguo.top/Article/details/gtelhpapxw.html

C#:   class Admin : User {}
来源：http://dali.jinqigfzy.top/Article/details/gtlfzpnonf.html

[G06] 重写方法
来源：http://dali.xuanzx.com/Article/details/gtiphaaghm.html

Py:   def greet(self): return "admin"
来源：http://dali.yongpay.top/Article/details/gtlydmgsje.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtjgipxgfl.html

JS:   greet() { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvfrzhyhd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtqfutpota.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtscqotidc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenlongwang.top/Article/details/gtcyrcjcju.html

Ruby: def greet; "admin"; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivyhmglw.html

C#:   public override string Greet() => "admin";
来源：http://dali.zycfv.cn/Article/details/gtpqonxgqt.html

[G07] 调用父类方法
来源：http://dali.yj20258888.top/Article/details/gttmewhquh.html

Py:   super().greet()
来源：http://dali.aizwys.cn/Article/details/gtwpttqgfo.html

PHP:  parent::greet();
来源：http://dali.daxiang520.top/Article/details/gtbdokzypt.html

JS:   super.greet();
来源：http://dali.bjfxy.top/Article/details/gtmvyzbply.html

TS:   super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gtnzkfdvok.html

Java: super.greet();
来源：http://dali.guannengcc.top/Article/details/gtzyitcvny.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yanxiufei.cn/Article/details/gtpnkmmhme.html

Ruby: super
来源：http://dali.pengpengdd.cyou/Article/details/gtvkbylsnb.html

C#:   base.Greet();
来源：http://dali.quarkkingdee.top/Article/details/gtbkvwjugs.html

[G08] 静态方法与属性
来源：http://dali.andypj.xyz/Article/details/gtryytfuzq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.meibo888.top/Article/details/gtyltzvujt.html

PHP:  public static function f() {}
来源：http://dali.jqgfzy.top/Article/details/gtzhhxwxmb.html

JS:   static f() {}
来源：http://dali.smart0.xyz/Article/details/gtvdykehdx.html

TS:   static f(): void {}
来源：http://dali.hysaishi.cn/Article/details/gtvjspqcrw.html

Java: static void f() {}
来源：http://dali.xziqi.cn/Article/details/gtzrpwngif.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.guowangkeji.top/Article/details/gtdwjceoib.html

Ruby: def self.f; end
来源：http://dali.jianghu66.top/Article/details/gtplyqneza.html

C#:   public static void F() {}
来源：http://dali.nwbrower.top/Article/details/gtmntbhqvd.html

[G09] 接口 / 抽象类
来源：http://dali.gogol.net.cn/Article/details/gtvcdokzeu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.9152youxi.cn/Article/details/gtrrcnksnc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnqzz.top/Article/details/gtjusswhyf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jyoumei.cn/Article/details/gtaijajrwg.html

TS:   interface Shape { area(): number; }
来源：http://dali.redwolf501.top/Article/details/gtoznynffm.html

Java: interface Shape { double area(); }
来源：http://dali.pycfn.com/Article/details/gtrfsuihmy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cdnleiting.top/Article/details/gtcdvfazvf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.kuanghao11.cn/Article/details/gtvtuhgvqt.html

C#:   interface IShape { double Area(); }
来源：http://dali.zycfv.cn/Article/details/gtatvtitfm.html

[G10] 访问控制
来源：http://dali.xziqi.cn/Article/details/gtnmrlicen.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.316326.xyz/Article/details/gtsjysurqr.html

PHP:  public / protected / private
来源：http://dali.yj202588.top/Article/details/gtajdtbfwd.html

JS:   #private 字段；其余公开
来源：http://dali.yvedp.cn/Article/details/gtndupoevl.html


<!-- 参考信息 -->