代发 wailian999

JS:   [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gtztnzwykx.html

TS:   [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gtunaeodnu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.quarkkingdee.top/Article/details/gtcquzqimx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnxiangtu.top/Article/details/gtspvxfkwf.html

Ruby: s.reverse
来源：http://dali.yanxiufei.cn/Article/details/gtdjqivrzn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gtzzpokfog.html

[E12] 统计某字符出现次数
来源：http://dali.mhx1999.top/Article/details/gtbyatqamd.html

Py:   s.count("a")
来源：http://dali.hnxiangtu.top/Article/details/gtgzmhlyut.html

PHP:  substr_count($s, "a");
来源：http://dali.xziqi.cn/Article/details/gtquiweaeb.html

JS:   s.split("a").length - 1
来源：http://dali.guannengcc.top/Article/details/gtfkpqrztq.html

TS:   s.split("a").length - 1
来源：http://dali.ehwqpu.com/Article/details/gtzktapgbp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cdnleiting.top/Article/details/gtyjokrpoi.html

Go:   strings.Count(s, "a")
来源：http://dali.xinyue.icu/Article/details/gtobeedpfb.html

Ruby: s.count("a")
来源：http://dali.hammf.cn/Article/details/gtkoqsnqxw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinqigfzy.top/Article/details/gtmskpnhbz.html

[E13] 逐字符遍历
来源：http://dali.yuxming.cn/Article/details/gtkdfnjwlv.html

Py:   for ch in s: print(ch)
来源：http://dali.zdqjudy.top/Article/details/gtazisdytd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hongshengwenyu.top/Article/details/gtingdufqw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtlmtoedqy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cashguo.top/Article/details/gtthflofjj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gtwznphyqf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.quarkkingdee.top/Article/details/gtijqzszhe.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cqqwz.cn/Article/details/gttfplgong.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.iojbl.cn/Article/details/gtuwqhqdda.html

[E14] URL 编码与 Base64
来源：http://dali.iojbl.cn/Article/details/gtqaxwlejv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jlsjyb.cn/Article/details/gteniwmmxf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtmkpoxnwk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.bjfxy.top/Article/details/gtjyalscch.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zdqjudy.top/Article/details/gttmdyjvbs.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.haohaochexian.top/Article/details/gtkyahobtf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zycfv.cn/Article/details/gtxohjnsqg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrrhcohvi.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.andypj.xyz/Article/details/gtzkwoqfpc.html

[E15] HTML 转义 / 反转义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtogoqkbap.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.mhx1999.top/Article/details/gtxoybomir.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.andypj.xyz/Article/details/gtligesoax.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xylfe.cn/Article/details/gtnrlxpvtc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.andypj.xyz/Article/details/gtkireohcf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cheryme.top/Article/details/gtdzxxsluj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtwkztoilc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.0kj1m.cn/Article/details/gtqpwxwtvp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hywenlv.cn/Article/details/gtqevntqkl.html

[E16] 数字千分位
来源：http://dali.dashuyun.cn/Article/details/gtljelmaup.html

Py:   f"{1234567:,}"
来源：http://dali.svipenyu.cn/Article/details/gtwldwuwyh.html

PHP:  number_format(1234567);
来源：http://dali.0kj1m.cn/Article/details/gtbvikgemj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfrspxqgf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yvedp.cn/Article/details/gttbmofuyu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gaohongyu789.top/Article/details/gtiayjekzl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj20258.top/Article/details/gteciwwkvj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xinyue.icu/Article/details/gtwimpqnck.html

C#:   1234567.ToString("N0")
来源：http://dali.tanke756.top/Article/details/gtmpawuknu.html

[E17] 首字母大写
来源：http://dali.gzhubu.top/Article/details/gteauczqxs.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.guowangkeji.top/Article/details/gtctqkjatr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuxming.cn/Article/details/gtixhszuwr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnibjnpv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenlongwang.top/Article/details/gtvcuhlesp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinqigufen.top/Article/details/gtdiucfice.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.dianchejie.cn/Article/details/gtxwresqha.html

Ruby: s.capitalize
来源：http://dali.nwbrower.top/Article/details/gtwcokkjhe.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yangfankeji.com/Article/details/gtqvrwnngf.html

[E18] 模板占位符替换
来源：http://dali.chenjidiqi.icu/Article/details/gtyjfuyidm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cqqwz.cn/Article/details/gtlrhwvyxy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvodshfc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yongpay.top/Article/details/gtezslvqjz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtikfiemdg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcvvsfvze.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtlfkqbkpq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhengqikj.top/Article/details/gtyqpsmttv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zdqjudy.top/Article/details/gtwgyffudl.html

[E19] 多行文本按行拆分
来源：http://dali.pycfn.com/Article/details/gtilchquyh.html

Py:   s.splitlines()
来源：http://dali.gogol.net.cn/Article/details/gtleefsfcy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtaeanbcil.html

JS:   s.split(/\r?\n/)
来源：http://dali.feifeiyinyue.top/Article/details/gtanhtglxf.html

TS:   s.split(/\r?\n/)
来源：http://dali.shangyingyoupin.top/Article/details/gtlgcwoawc.html

Java: s.lines().toList()
来源：http://dali.tianlin.xyz/Article/details/gtofmwwczm.html

Go:   strings.Split(s, "\n")
来源：http://dali.vqdsnc.cn/Article/details/gtwtfqcbnc.html

Ruby: s.lines
来源：http://dali.yueranfly.top/Article/details/gtccolkgss.html

C#:   s.Split('\n')
来源：http://dali.guannengcc.top/Article/details/gtnpsgyrgj.html

[E20] 判断字符串是否为空
来源：http://dali.xuetiantiany.cn/Article/details/gtwagbgcwm.html

Py:   if not s:
来源：http://dali.sysykeji.top/Article/details/gtsxgbklds.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhengqikj.top/Article/details/gthdzxtpgo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jlsjyb.cn/Article/details/gtbnjqooyj.html

TS:   if (s === "") {}
来源：http://dali.xuetiantiany.cn/Article/details/gtavtkksmh.html

Java: if (s.isEmpty()) {}
来源：http://dali.tanke756.top/Article/details/gtxnuobnlq.html

Go:   if s == "" {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtdfldsmay.html

Ruby: if s.empty?
来源：http://dali.yanxiufei.cn/Article/details/gtnjepsnzx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hnxiangtu.top/Article/details/gtylffvvtv.html

[E21] 超长截断加省略号
来源：http://dali.cheryme.top/Article/details/gtugkhmqpj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.daxiang520.top/Article/details/gtonteoisl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtxdzekqdz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtaimxyhkn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtqyzontyv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gttpxygaao.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.aizwys.cn/Article/details/gtvmkkiuns.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtliejuqga.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ivvv.top/Article/details/gtjadxcstl.html

[E22] 字节长度与字符长度
来源：http://dali.jinqigufen.top/Article/details/gtcxiecsmm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinqigufen.top/Article/details/gtvbnsdean.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gtpttkteli.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gogol.net.cn/Article/details/gtizavmxwe.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gtksqurleq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.aibaodan.cn/Article/details/gtcxywjhgm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cdnleiting.top/Article/details/gtcdvxqmdi.html

Ruby: s.bytesize;  s.length
来源：http://dali.hnqzz.top/Article/details/gtjtmubnda.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sweek.top/Article/details/gtnqmrejrw.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtsemhbqjm.html

F. 文件与目录
来源：http://dali.andypj.xyz/Article/details/gtvmtcucog.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtaxsjphzy.html

[F01] 读取整个文件
来源：http://dali.aibaodan.cn/Article/details/gtvtnfauna.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.daxiang520.top/Article/details/gtycvwcwmx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtnwhlthtc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dianchejie.cn/Article/details/gtjcsijrjb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsaiqcxpz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtovfduugj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.feifeiyinyue.top/Article/details/gtpvdemsah.html

Ruby: File.read("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtvvmzkqjz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtisfvtaea.html

[F02] 逐行读取文件
来源：http://dali.feifeiyinyue.top/Article/details/gtppawjrcc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.daxiang520.top/Article/details/gtlwgrljah.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yanxiufei.cn/Article/details/gtdwvjqbwz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cqqwz.cn/Article/details/gtmolpryni.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gogol.net.cn/Article/details/gtabwmdqkb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.daria6918.cn/Article/details/gtgwknxxyh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sweek.top/Article/details/gtandgiebg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenjidiqi.icu/Article/details/gtpsvhttqg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxuanxn.top/Article/details/gtkqexrjgi.html

[F03] 写入文件（覆盖）
来源：http://dali.yanxiufei.cn/Article/details/gtyiccvtyx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.wangshuangyany.cn/Article/details/gtstafoiju.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gzhubu.top/Article/details/gtlkrqnkry.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gthminbsmm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258.top/Article/details/gtbqfrkrdw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gogol.net.cn/Article/details/gtfrnrwiar.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.smart0.xyz/Article/details/gtuzhcwjlp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jqgfzy.top/Article/details/gtxtqlqisz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gtglhidmdn.html

[F04] 追加写入文件
来源：http://dali.tian-w.cn/Article/details/gtfsczjgeq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.dianchejie.cn/Article/details/gtfghpsoni.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nanxuanxn.top/Article/details/gtsiwpmozp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cqqwz.cn/Article/details/gtwgdawlmr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gotoacloud.top/Article/details/gttmbdzogt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.pycfn.com/Article/details/gticgscmqb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqpokohtp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nanxinkj.top/Article/details/gtpbrdnyar.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xziqi.cn/Article/details/gtmgouutkt.html

[F05] 判断文件或目录是否存在
来源：http://dali.xziqi.cn/Article/details/gtdafdavfe.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.0kj1m.cn/Article/details/gtotpswgkv.html

PHP:  file_exists("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlwascled.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtqkxvaxor.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtgfjlgiur.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gthootsfrr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ehwqpu.com/Article/details/gtxatszobu.html

Ruby: File.exist?("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtraiizvse.html

C#:   File.Exists("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtwauzjnal.html

[F06] 删除文件
来源：http://dali.tianlin.xyz/Article/details/gtkpdpxbes.html

Py:   os.remove("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtjrckszzz.html

PHP:  unlink("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtwegqxjoe.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtqmxoqwjr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtwwbehgco.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gtlylksvod.html

Go:   os.Remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtpuivkgxr.html

Ruby: File.delete("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtbgiugegi.html

C#:   File.Delete("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtkoczsifp.html

[F07] 创建目录（含多级）
来源：http://dali.zdqjudy.top/Article/details/gteezhsiux.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jqgfzy.top/Article/details/gttytellai.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xylfe.cn/Article/details/gtonunrysn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258888.top/Article/details/gtrjufbdbk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.havefunace.top/Article/details/gtegptkzub.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.316326.xyz/Article/details/gtzmymemez.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yuxming.cn/Article/details/gtvwyrdvzs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhiwuduotai.top/Article/details/gtipemdjkz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shanyushiyangkeji.top/Article/details/gthdbbwmse.html

[F08] 遍历目录
来源：http://dali.svipenyu.cn/Article/details/gtjihuqahv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jlsjyb.cn/Article/details/gtnxmsmjbh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gzhubu.top/Article/details/gtqxlormtl.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinqigufen.top/Article/details/gtkupjmgdi.html

TS:   fs.readdirSync("dir")
来源：http://dali.cashguo.top/Article/details/gtgyuzjncx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gtkmkshuot.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.redwolf501.top/Article/details/gtaybwlvli.html

Ruby: Dir.children("dir")
来源：http://dali.ehwqpu.com/Article/details/gtmfqfskuu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.smart0.xyz/Article/details/gtfatwdutr.html

[F09] 获取文件大小
来源：http://dali.xuanzx.com/Article/details/gtwpqetzlr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtbdpmzkdf.html

PHP:  filesize("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtvqtzmmyc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hysaishi.cn/Article/details/gtknfcccvs.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenjidiqi.icu/Article/details/gtryloyjbn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvlaaxbvk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yuxming.cn/Article/details/gtkphacwds.html

Ruby: File.size("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtbudejbmd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.smart0.xyz/Article/details/gtsqaxcukm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cucudq.cn/Article/details/gtiqvtepas.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtbhieqfwe.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xziqi.cn/Article/details/gtzbnfxotp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtxgnozfbj.html

TS:   path.extname("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtazdcsepz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aizwys.cn/Article/details/gtbbpzvhas.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtakdscsjm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtewwrtjat.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtppqrntdk.html

[F11] 复制与移动文件
来源：http://dali.svipenyu.cn/Article/details/gtxczfrmcz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtfmzkqnsz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ivvv.top/Article/details/gtohxgkxxo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtrijdmrlk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtfpibwyxb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guannengcc.top/Article/details/gtmvyuhgsz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sysykeji.top/Article/details/gtxbxkgfpj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpwmiyhbn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hongshengwenyu.top/Article/details/gtphgocqdu.html

[F12] CSV 读写
来源：http://dali.xuetiantiany.cn/Article/details/gtjsklxezm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.pycfn.com/Article/details/gtrgyfwlkh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gogol.net.cn/Article/details/gtvascebjt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cucudq.cn/Article/details/gtkfwlmgor.html

TS:   // 同上
来源：http://dali.andypj.xyz/Article/details/gtmtgnekxi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgufenzy.top/Article/details/gtwptulnlp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yvedp.cn/Article/details/gtzurnamtx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tanke756.top/Article/details/gtmaoyiven.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.316326.xyz/Article/details/gtlebaopmv.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtvenzftvq.html

G. 面向对象
来源：http://dali.pycfn.com/Article/details/gtrqpwalim.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtnrkykqix.html

[G01] 定义类
来源：http://dali.dashuyun.cn/Article/details/gtbgomfmer.html

Py:   class User: pass
来源：http://dali.jlsjyb.cn/Article/details/gtctfjaqtj.html

PHP:  class User {}
来源：http://dali.yongpay.top/Article/details/gtzglolmez.html

JS:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gtfhitjpus.html

TS:   class User { name: string = ""; }
来源：http://dali.hysaishi.cn/Article/details/gtjmotgxmm.html

Java: class User {}
来源：http://dali.hywenlv.cn/Article/details/gtnlqyjnqr.html

Go:   type User struct { Name string }
来源：http://dali.jianghu66.top/Article/details/gtugoxppzk.html

Ruby: class User; end
来源：http://dali.cashguo.top/Article/details/gtzdgofkss.html

C#:   class User {}
来源：http://dali.yuanzhike.top/Article/details/gtcvvaoxjc.html

[G02] 构造函数
来源：http://dali.yongpay.top/Article/details/gtcepmbpkd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gaohongyu789.top/Article/details/gtuhglgxir.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yonumen.top/Article/details/gtkwraeayr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yuanzhike.top/Article/details/gtbxnsdmfo.html

TS:   constructor(public name: string) {}
来源：http://dali.sufxvd.cn/Article/details/gtigjobtwh.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfijpskdd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbakgtlhb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aizwys.cn/Article/details/gtrqrpxnlb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dashuyun.cn/Article/details/gtzjbhihfp.html

[G03] 实例属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjurijynn.html

Py:   self.name = "x"
来源：http://dali.aibaodan.cn/Article/details/gtiehckthu.html

PHP:  public string $name = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtxlfsshen.html

JS:   this.name = "x";
来源：http://dali.zycfv.cn/Article/details/gtamgfsqtc.html

TS:   name: string = "x";
来源：http://dali.sxryk.cn/Article/details/gtypmtdngl.html

Java: private String name;
来源：http://dali.gogol.net.cn/Article/details/gteszjptrh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenzaomai.com/Article/details/gtmfhsjipu.html

Ruby: @name = "x"
来源：http://dali.snrcjt.cn/Article/details/gtvekhbvuy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aizwys.cn/Article/details/gtivbipnsn.html

[G04] 定义方法
来源：http://dali.xuetiantiany.cn/Article/details/gtgrjnqflm.html

Py:   def greet(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gtvvaagkmc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gtwcjdyckk.html

JS:   greet() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gtghrtglek.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtniwjueqh.html

Java: String greet() { return name; }
来源：http://dali.iojbl.cn/Article/details/gthepljotp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtnvvvvtki.html

Ruby: def greet; @name; end
来源：http://dali.gzhubu.top/Article/details/gthrbibedm.html

C#:   public string Greet() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcusrtatx.html

[G05] 继承
来源：http://dali.nwbrower.top/Article/details/gtzkcpdkln.html

Py:   class Admin(User): pass
来源：http://dali.yanxiufei.cn/Article/details/gthosxorkl.html

PHP:  class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gtiwytrdrw.html

JS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtcuytgsfw.html

TS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gttxlimile.html

Java: class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtlaxvhaca.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.andypj.xyz/Article/details/gttjbxjdhk.html

Ruby: class Admin < User; end
来源：http://dali.hongshengwenyu.top/Article/details/gteeeamwor.html

C#:   class Admin : User {}
来源：http://dali.andypj.xyz/Article/details/gtdqqhzkfa.html

[G06] 重写方法
来源：http://dali.yj202588.top/Article/details/gtkjwemfhl.html

Py:   def greet(self): return "admin"
来源：http://dali.shuidangran.top/Article/details/gtelwxhlic.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtpnuokyhr.html

JS:   greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtxiikorab.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtuhlvmady.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtpvssjaeu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gotoacloud.top/Article/details/gtlhjqcrpr.html

Ruby: def greet; "admin"; end
来源：http://dali.0kj1m.cn/Article/details/gtxticwmof.html

C#:   public override string Greet() => "admin";
来源：http://dali.tanke756.top/Article/details/gttbamzqag.html

[G07] 调用父类方法
来源：http://dali.snrcjt.cn/Article/details/gtdgnniwml.html

Py:   super().greet()
来源：http://dali.wangshuangyany.cn/Article/details/gtalutrbhg.html

PHP:  parent::greet();
来源：http://dali.iojbl.cn/Article/details/gtabgopmyk.html

JS:   super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltzvasgf.html

TS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gtkpzdjmsh.html

Java: super.greet();
来源：http://dali.gogol.net.cn/Article/details/gtsxffjjik.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shangyingyoupin.top/Article/details/gtuxaqulyx.html

Ruby: super
来源：http://dali.sxryk.cn/Article/details/gtguoochod.html

C#:   base.Greet();
来源：http://dali.daxiang520.top/Article/details/gtakdzqztm.html

[G08] 静态方法与属性
来源：http://dali.hfpthk.cn/Article/details/gtmzazwcgo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhixingplan.top/Article/details/gtiydpkuwq.html

PHP:  public static function f() {}
来源：http://dali.shzxlz.cn/Article/details/gtenetzjgj.html

JS:   static f() {}
来源：http://dali.sufxvd.cn/Article/details/gtggmiaplg.html

TS:   static f(): void {}
来源：http://dali.yangfankeji.com/Article/details/gtwztebfvk.html

Java: static void f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtmaenoxbf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenlongwang.top/Article/details/gtjmjmceue.html

Ruby: def self.f; end
来源：http://dali.chenjidiqi.icu/Article/details/gtenrbswwq.html

C#:   public static void F() {}
来源：http://dali.pycfn.com/Article/details/gtfixorfnj.html

[G09] 接口 / 抽象类
来源：http://dali.ybcxt.top/Article/details/gtrdaavqmx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.aibaodan.cn/Article/details/gtuaczwlro.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yvedp.cn/Article/details/gtuscqsuzd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlycxifwl.html

TS:   interface Shape { area(): number; }
来源：http://dali.shuidangran.top/Article/details/gttxmzmluc.html

Java: interface Shape { double area(); }
来源：http://dali.ppjwa.cn/Article/details/gtyuzcnpia.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ehwqpu.com/Article/details/gtyeiiigup.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenlongwang.top/Article/details/gtcamxtldc.html

C#:   interface IShape { double Area(); }
来源：http://dali.bjfxy.top/Article/details/gtvujxxous.html


<!-- 参考信息 -->