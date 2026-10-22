代发 wailian999

TS:   "7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gt2qzksqait.html

Java: String.format("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gt2cakefoiu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gt2owocyhzo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gt2dgsoakgw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tian-w.cn/Article/details/gt2enhzbxed.html

[E11] 反转字符串
来源：http://dali.0kj1m.cn/Article/details/gt2dfjzayrr.html

Py:   s[::-1]
来源：http://dali.yonumen.top/Article/details/gt2fkdelgvu.html

PHP:  strrev($s);
来源：http://dali.xinyue.icu/Article/details/gt2oobbadir.html

JS:   [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gt2idbaojah.html

TS:   [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gt2tztfhsup.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.aizwys.cn/Article/details/gt2vnhibzag.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhengqikj.top/Article/details/gt2hfdsaohd.html

Ruby: s.reverse
来源：http://dali.chenlongwang.top/Article/details/gt2xmwlurnn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj20258888.top/Article/details/gt2jyrvmakj.html

[E12] 统计某字符出现次数
来源：http://dali.birdmap.top/Article/details/gt2kxlrmhxo.html

Py:   s.count("a")
来源：http://dali.zhixingplan.top/Article/details/gt2wbwhhcsn.html

PHP:  substr_count($s, "a");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tedgtpjq.html

JS:   s.split("a").length - 1
来源：http://dali.haohaochexian.top/Article/details/gt2ixlaahrq.html

TS:   s.split("a").length - 1
来源：http://dali.gzhubu.top/Article/details/gt2adbqdtco.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ybcxt.top/Article/details/gt2oxfdfjyy.html

Go:   strings.Count(s, "a")
来源：http://dali.fzhhl.top/Article/details/gt2dvffqsfc.html

Ruby: s.count("a")
来源：http://dali.jyoumei.cn/Article/details/gt2cwqsphcn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.guannengcc.top/Article/details/gt2ckwzxtrd.html

[E13] 逐字符遍历
来源：http://dali.hongshengwenyu.top/Article/details/gt2pvrdwbuy.html

Py:   for ch in s: print(ch)
来源：http://dali.xylfe.cn/Article/details/gt2gxjmyxob.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ssqoauuo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aatxbwsg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gt2qyqravve.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aibaodan.cn/Article/details/gt2vmirzuur.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cashguo.top/Article/details/gt2mjfptjjb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.andypj.xyz/Article/details/gt2plhbyefu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dianchejie.cn/Article/details/gt2rrsqljrq.html

[E14] URL 编码与 Base64
来源：http://dali.pycfn.com/Article/details/gt2cwdjofam.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shzxlz.cn/Article/details/gt2soymocmp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenlongwang.top/Article/details/gt2apwwfooe.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lgvmbqrr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hnqzz.top/Article/details/gt2kpeagmas.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sysykeji.top/Article/details/gt2xndktjpf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj202588.top/Article/details/gt2vwfwqrrm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhongyouzk.top/Article/details/gt2gysvypru.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vwerlwea.html

[E15] HTML 转义 / 反转义
来源：http://dali.xylfe.cn/Article/details/gt2jhppntjr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2xwhyhwsh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fxjqbyem.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhixingplan.top/Article/details/gt2jwltzlvg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.bjfxy.top/Article/details/gt2tvvhegov.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.0kj1m.cn/Article/details/gt2ecsghqck.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yueranfly.top/Article/details/gt2drzmmzuo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jyoumei.cn/Article/details/gt2uoqyrasd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hysaishi.cn/Article/details/gt2kcwcefrf.html

[E16] 数字千分位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zwefrmwm.html

Py:   f"{1234567:,}"
来源：http://dali.cucudq.cn/Article/details/gt2zhrtjfrw.html

PHP:  number_format(1234567);
来源：http://dali.xuetiantiany.cn/Article/details/gt2zglblxqs.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhixingplan.top/Article/details/gt2hzzxgtem.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hysaishi.cn/Article/details/gt2hpvnbxof.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xylfe.cn/Article/details/gt2pgxefvgc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.dashuyun.cn/Article/details/gt2swojvabo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aizwys.cn/Article/details/gt2fhkvzntb.html

C#:   1234567.ToString("N0")
来源：http://dali.pycfn.com/Article/details/gt2voacbpoy.html

[E17] 首字母大写
来源：http://dali.haohaochexian.top/Article/details/gt2rsfchnez.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xuetiantiany.cn/Article/details/gt2yltsqzkk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.0kj1m.cn/Article/details/gt2bwnjoqhq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ycbelgkw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cheryme.top/Article/details/gt2yxtcdyjh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenlongwang.top/Article/details/gt2wtmdneki.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfdxbtj.html

Ruby: s.capitalize
来源：http://dali.havefunace.top/Article/details/gt2audxnhyt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hywenlv.cn/Article/details/gt2oyssrvnw.html

[E18] 模板占位符替换
来源：http://dali.fengsongda.top/Article/details/gt2hogwqjmo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xziqi.cn/Article/details/gt2iqcvrjxa.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jianghu66.top/Article/details/gt2anvnyigh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gt2wxyuanmx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gt2nyaecwss.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gt2ztvralgp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj202588.top/Article/details/gt2tcijqrpo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fengsongda.top/Article/details/gt2kjvduics.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.havefunace.top/Article/details/gt2kqhxrndo.html

[E19] 多行文本按行拆分
来源：http://dali.jinqigfzy.top/Article/details/gt2pmbetatl.html

Py:   s.splitlines()
来源：http://dali.hnqzz.top/Article/details/gt2hgdwqvsx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2jhxbypax.html

JS:   s.split(/\r?\n/)
来源：http://dali.ehwqpu.com/Article/details/gt2xjclvcyc.html

TS:   s.split(/\r?\n/)
来源：http://dali.shzxlz.cn/Article/details/gt2vqpipmbo.html

Java: s.lines().toList()
来源：http://dali.0kj1m.cn/Article/details/gt2mvcefmqs.html

Go:   strings.Split(s, "\n")
来源：http://dali.meibo888.top/Article/details/gt2wntuxsvm.html

Ruby: s.lines
来源：http://dali.hfpthk.cn/Article/details/gt2mwhxznyy.html

C#:   s.Split('\n')
来源：http://dali.jyoumei.cn/Article/details/gt2oyptdymf.html

[E20] 判断字符串是否为空
来源：http://dali.yuanzhike.top/Article/details/gt2hhnlmdbq.html

Py:   if not s:
来源：http://dali.nanxinkj.top/Article/details/gt2brajwgmb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.smart0.xyz/Article/details/gt2ciikaage.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.aibaodan.cn/Article/details/gt2qzujavnj.html

TS:   if (s === "") {}
来源：http://dali.yj20258.top/Article/details/gt2odjzuuwk.html

Java: if (s.isEmpty()) {}
来源：http://dali.jyoumei.cn/Article/details/gt2rxhkyhcz.html

Go:   if s == "" {}
来源：http://dali.mhx1999.top/Article/details/gt2wdxaozah.html

Ruby: if s.empty?
来源：http://dali.svipenyu.cn/Article/details/gt2rxduksqa.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ybcxt.top/Article/details/gt2ccabqayb.html

[E21] 超长截断加省略号
来源：http://dali.yj20258.top/Article/details/gt2owbobpmg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.havefunace.top/Article/details/gt2wiktjqqk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj20258.top/Article/details/gt2ffslsuzs.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gt2mugtmjmb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tlogwyso.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gt2wuezkxcw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.fengsongda.top/Article/details/gt2fnwhzjay.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gt2ivirmybl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cheryme.top/Article/details/gt2hxbhquae.html

[E22] 字节长度与字符长度
来源：http://dali.hfpthk.cn/Article/details/gt2namqzhll.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuxming.cn/Article/details/gt2rrnnzwec.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gt2lqkdtyqd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgfzy.top/Article/details/gt2ttoqzuyx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daxiang520.top/Article/details/gt2xdpywmwe.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sxryk.cn/Article/details/gt2olvuxmbb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jlsjyb.cn/Article/details/gt2bqxifdzy.html

Ruby: s.bytesize;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gt2ineggkhb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ghnkkuzt.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2llrobydg.html

F. 文件与目录
来源：http://dali.jiagoushi.top/Article/details/gt2dvfwwlwj.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jkkgpvnb.html

[F01] 读取整个文件
来源：http://dali.haohaochexian.top/Article/details/gt2fjzsatxp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xxoarktv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2thfdmbhs.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ehwqpu.com/Article/details/gt2phdmephw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gt2rswejhyy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gt2frqcnsek.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.daria6918.cn/Article/details/gt2rnofcpkh.html

Ruby: File.read("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2nbjafkdz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2cxfxloxm.html

[F02] 逐行读取文件
来源：http://dali.iojbl.cn/Article/details/gt2kujihjxk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jiagoushi.top/Article/details/gt2ubsotfyg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.mhx1999.top/Article/details/gt2qtzlysjz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gogol.net.cn/Article/details/gt2ztvaluaq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigufen.top/Article/details/gt2mnqfkgxi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.wangdashe.top/Article/details/gt2oalfkcjg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bddawvqb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jianghu66.top/Article/details/gt2uvlzgcpo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gzhubu.top/Article/details/gt2cnenlyhe.html

[F03] 写入文件（覆盖）
来源：http://dali.dianchejie.cn/Article/details/gt2srrrevna.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shuidangran.top/Article/details/gt2mhngbymv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tanke756.top/Article/details/gt2ucqyaxcw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ygdcpiuz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gt2ihjmawgi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gaohongyu789.top/Article/details/gt2jqwxndzr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tanke756.top/Article/details/gt2tmyfwjjd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ydzc1.top/Article/details/gt2vgqmzjod.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gt2qxslspvx.html

[F04] 追加写入文件
来源：http://dali.shzxlz.cn/Article/details/gt2zbajecau.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fzhhl.top/Article/details/gt2lttfqlnu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.havefunace.top/Article/details/gt2degjmmfv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ybcxt.top/Article/details/gt2pysarxeo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yangfankeji.com/Article/details/gt2ryvvtnnc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2whvmedna.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tian-w.cn/Article/details/gt2xiubdgcs.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wgybtxyn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tanke756.top/Article/details/gt2tikpekdt.html

[F05] 判断文件或目录是否存在
来源：http://dali.guannengcc.top/Article/details/gt2xlwkcgwh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yueranfly.top/Article/details/gt2hpssperr.html

PHP:  file_exists("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2efiypack.html

JS:   fs.existsSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2svbzvopu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2ymenlvyx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gt2rzzujumv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yanxiufei.cn/Article/details/gt2vymlulof.html

Ruby: File.exist?("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2ffcnciec.html

C#:   File.Exists("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2lwsqaltv.html

[F06] 删除文件
来源：http://dali.guowangkeji.top/Article/details/gt2mhoawakz.html

Py:   os.remove("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2ggugajaa.html

PHP:  unlink("a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2oaaurarc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wblssvcl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2lefjodiw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gt2njeallfh.html

Go:   os.Remove("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2ubjvzjev.html

Ruby: File.delete("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2cwburzhq.html

C#:   File.Delete("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2doydkmjs.html

[F07] 创建目录（含多级）
来源：http://dali.guowangkeji.top/Article/details/gt2bxzcfhwz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cdnleiting.top/Article/details/gt2akxqxqwm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yuxming.cn/Article/details/gt2cpmziuky.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgfzy.top/Article/details/gt2ezuohflt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cashguo.top/Article/details/gt2osykqqbd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2jymndskg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.birdmap.top/Article/details/gt2pbkgeewh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yangfankeji.com/Article/details/gt2lozlmhsl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gogol.net.cn/Article/details/gt2iaqcxsvu.html

[F08] 遍历目录
来源：http://dali.sufxvd.cn/Article/details/gt2udnqcymw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nanxinkj.top/Article/details/gt2iqumxukd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tian-w.cn/Article/details/gt2lubbwirp.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iozvwphq.html

TS:   fs.readdirSync("dir")
来源：http://dali.bjfxy.top/Article/details/gt2wyobfqti.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kafgzzwc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhongyouzk.top/Article/details/gt2lykmvybr.html

Ruby: Dir.children("dir")
来源：http://dali.sweek.top/Article/details/gt2ikvqhxgg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.wangdashe.top/Article/details/gt2uvhlgxum.html

[F09] 获取文件大小
来源：http://dali.wangshuangyany.cn/Article/details/gt2kkfcgizj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2wjpcbqvv.html

PHP:  filesize("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2vcsthmqx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yuanzhike.top/Article/details/gt2mgogprim.html

TS:   fs.statSync("a.txt").size
来源：http://dali.svipenyu.cn/Article/details/gt2occmcetn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gt2bcrjkkpn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.316326.xyz/Article/details/gt2fkhuprsa.html

Ruby: File.size("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2dorzutyd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhoulong.xyz/Article/details/gt2mfsmafdi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zdqjudy.top/Article/details/gt2xkzgvlbe.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2clfqwfuv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2ilrjllgv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jzwzmqbc.html

TS:   path.extname("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2pwpwjdrq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nanxuanxn.top/Article/details/gt2vmtduacb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2xuriksma.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2aqxdjlcm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2hkacjfeu.html

[F11] 复制与移动文件
来源：http://dali.daxiang520.top/Article/details/gt2ajjoqxui.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2zrfyycou.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sweek.top/Article/details/gt2sudkbubo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2tmukhwwc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gt2kewmkcpp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rcurgrmp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jiagoushi.top/Article/details/gt2ezfegjau.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2gqtlrqte.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yvedp.cn/Article/details/gt2wwxavkqd.html

[F12] CSV 读写
来源：http://dali.shangyingyoupin.top/Article/details/gt2mceilgwz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aibaodan.cn/Article/details/gt2rtscvuzg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yuxming.cn/Article/details/gt2kjagyuuj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.9152youxi.cn/Article/details/gt2gdttefbh.html

TS:   // 同上
来源：http://dali.smart0.xyz/Article/details/gt2fsexbfug.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tianlin.xyz/Article/details/gt2chjmfonu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.wangdashe.top/Article/details/gt2qgyobykh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.pycfn.com/Article/details/gt2yigivpqo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigfzy.top/Article/details/gt2irkjufbf.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2fprqmvok.html

G. 面向对象
来源：http://dali.ivvv.top/Article/details/gt2msrjqutx.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2otwagbpy.html

[G01] 定义类
来源：http://dali.chenlongwang.top/Article/details/gt2pumudgaj.html

Py:   class User: pass
来源：http://dali.gaohongyu789.top/Article/details/gt2rvnpgbmj.html

PHP:  class User {}
来源：http://dali.shzxlz.cn/Article/details/gt2idevvvyw.html

JS:   class User {}
来源：http://dali.gogol.net.cn/Article/details/gt2gpghzgjd.html

TS:   class User { name: string = ""; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2nrloksjb.html

Java: class User {}
来源：http://dali.tian-w.cn/Article/details/gt2dhzeyhvo.html

Go:   type User struct { Name string }
来源：http://dali.feifeiyinyue.top/Article/details/gt2byliiifw.html

Ruby: class User; end
来源：http://dali.xuanzx.com/Article/details/gt2eonevakn.html

C#:   class User {}
来源：http://dali.daria6918.cn/Article/details/gt2cspafzkq.html

[G02] 构造函数
来源：http://dali.kuanghao11.cn/Article/details/gt2zirmvphb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mvwwoown.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yvedp.cn/Article/details/gt2ocrdtdgi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gt2xuegrucr.html

TS:   constructor(public name: string) {}
来源：http://dali.iojbl.cn/Article/details/gt2lewjfccu.html

Java: User(String name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gt2utzwwtyj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xylfe.cn/Article/details/gt2naboppng.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ehwqpu.com/Article/details/gt2zsfdashy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj202588.top/Article/details/gt2kugdlbnu.html

[G03] 实例属性
来源：http://dali.vqdsnc.cn/Article/details/gt2xukfbrgr.html

Py:   self.name = "x"
来源：http://dali.aizwys.cn/Article/details/gt2nfumolsh.html

PHP:  public string $name = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hhdhsjgw.html

JS:   this.name = "x";
来源：http://dali.zhixingplan.top/Article/details/gt2ootjhcfo.html

TS:   name: string = "x";
来源：http://dali.jqgufenzy.top/Article/details/gt2bvddeqxm.html

Java: private String name;
来源：http://dali.tanke756.top/Article/details/gt2bcelohzr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.redwolf501.top/Article/details/gt2qmvczuyb.html

Ruby: @name = "x"
来源：http://dali.daria6918.cn/Article/details/gt2ercqvszu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sweek.top/Article/details/gt2fknkvrfb.html

[G04] 定义方法
来源：http://dali.smart0.xyz/Article/details/gt2uebzfsew.html

Py:   def greet(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gt2vbiacftq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gt2econrpsi.html

JS:   greet() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2uezqajiv.html

TS:   greet(): string { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gt2mxpmrnfo.html

Java: String greet() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2tvygvhjv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gt2rlybppzw.html

Ruby: def greet; @name; end
来源：http://dali.chenzaomai.com/Article/details/gt2oqseflpb.html

C#:   public string Greet() => Name;
来源：http://dali.yongpay.top/Article/details/gt2jfhonchs.html

[G05] 继承
来源：http://dali.fzhhl.top/Article/details/gt2phrrachb.html

Py:   class Admin(User): pass
来源：http://dali.316326.xyz/Article/details/gt2cxbnobzp.html

PHP:  class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gt2lhewybuz.html

JS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gt2cinrzwvo.html

TS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gt2iqsbqatn.html

Java: class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gt2odfinqos.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yangfankeji.com/Article/details/gt2pyxqunsm.html

Ruby: class Admin < User; end
来源：http://dali.sysykeji.top/Article/details/gt2kqfhdfwe.html

C#:   class Admin : User {}
来源：http://dali.bjfxy.top/Article/details/gt2wtpvkvtl.html

[G06] 重写方法
来源：http://dali.cqqwz.cn/Article/details/gt2rzwjsdfq.html

Py:   def greet(self): return "admin"
来源：http://dali.hammf.cn/Article/details/gt2pnfehrly.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gt2qcpukwjg.html

JS:   greet() { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gt2ipsrmpfh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2qlacagxq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gt2sbhveuig.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jiagoushi.top/Article/details/gt2klmjhkcx.html

Ruby: def greet; "admin"; end
来源：http://dali.hammf.cn/Article/details/gt2hzxufuzh.html

C#:   public override string Greet() => "admin";
来源：http://dali.jianghu66.top/Article/details/gt2jntwbijz.html

[G07] 调用父类方法
来源：http://dali.9152youxi.cn/Article/details/gt2wjjkhvyo.html

Py:   super().greet()
来源：http://dali.zycfv.cn/Article/details/gt2rbrdnwlo.html

PHP:  parent::greet();
来源：http://dali.jinqigufen.top/Article/details/gt2ohydffsc.html

JS:   super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gt2gancvlya.html

TS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gt2ljdugiwk.html

Java: super.greet();
来源：http://dali.zdqjudy.top/Article/details/gt2ytepoexc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xinyue.icu/Article/details/gt2mvkkgpzy.html

Ruby: super
来源：http://dali.pycfn.com/Article/details/gt2knccjoqe.html

C#:   base.Greet();
来源：http://dali.chenlongwang.top/Article/details/gt2wupvvstt.html

[G08] 静态方法与属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zhwljriy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gaohongyu789.top/Article/details/gt2tbomackm.html

PHP:  public static function f() {}
来源：http://dali.gotoacloud.top/Article/details/gt2zfxxfytm.html

JS:   static f() {}
来源：http://dali.sufxvd.cn/Article/details/gt2wbtrjtac.html

TS:   static f(): void {}
来源：http://dali.zdqjudy.top/Article/details/gt2hfysggii.html

Java: static void f() {}
来源：http://dali.cucudq.cn/Article/details/gt2uoumgknz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.wangdashe.top/Article/details/gt2zftfqvhl.html

Ruby: def self.f; end
来源：http://dali.xziqi.cn/Article/details/gt2jxrygkih.html

C#:   public static void F() {}
来源：http://dali.pycfn.com/Article/details/gt2gdxmfozz.html

[G09] 接口 / 抽象类
来源：http://dali.zycfv.cn/Article/details/gt2alqervba.html


<!-- 参考信息 -->