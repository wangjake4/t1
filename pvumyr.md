代发 wailian999

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtyashrtmw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yongpay.top/Article/details/gtvufbmaof.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.c1oappe.top/Article/details/gtmeojsaxp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.aizwys.cn/Article/details/gtvkheknat.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ppjwa.cn/Article/details/gtvsudlzfe.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.birdmap.top/Article/details/gtosqtzpaf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xuetiantiany.cn/Article/details/gtuhmulqtz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.smart0.xyz/Article/details/gthcdstpfs.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shzxlz.cn/Article/details/gtlphvdwdv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gtfqxpakjt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shangyingyoupin.top/Article/details/gtipzxaqra.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gtaixclvfx.html

TS:   "7".padStart(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gthqgbhhof.html

Java: String.format("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gtkjuggqwy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbyxcykim.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gthddwfobp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shanyushiyangtech.top/Article/details/gteqerflih.html

[E11] 反转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtezsfllvv.html

Py:   s[::-1]
来源：http://dali.cheryme.top/Article/details/gtrxdmuook.html

PHP:  strrev($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtqyksmsci.html

JS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtymthhslf.html

TS:   [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtceiknxqe.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cucudq.cn/Article/details/gtzgxqlhlw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sweek.top/Article/details/gtcxowfujc.html

Ruby: s.reverse
来源：http://dali.xinyue.icu/Article/details/gtxftfflzj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yonumen.top/Article/details/gtvjidtwvf.html

[E12] 统计某字符出现次数
来源：http://dali.ppjwa.cn/Article/details/gttmezgsdz.html

Py:   s.count("a")
来源：http://dali.yangfankeji.com/Article/details/gtdeidaarp.html

PHP:  substr_count($s, "a");
来源：http://dali.dianchejie.cn/Article/details/gtkhodgbdq.html

JS:   s.split("a").length - 1
来源：http://dali.nanxinkj.top/Article/details/gtwggrtefo.html

TS:   s.split("a").length - 1
来源：http://dali.jinqigfzy.top/Article/details/gtucphctdh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhengqikj.top/Article/details/gtultzihxa.html

Go:   strings.Count(s, "a")
来源：http://dali.ehwqpu.com/Article/details/gtwjcnfmjd.html

Ruby: s.count("a")
来源：http://dali.tanke756.top/Article/details/gtqjxzaqfy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shanyushiyangtech.top/Article/details/gtrewlmqcw.html

[E13] 逐字符遍历
来源：http://dali.gaohongyu789.top/Article/details/gtxdfegtin.html

Py:   for ch in s: print(ch)
来源：http://dali.dianchejie.cn/Article/details/gtzodfjgjs.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.iojbl.cn/Article/details/gtxobstoje.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.9152youxi.cn/Article/details/gtvyhujgof.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aizwys.cn/Article/details/gtxyxtegwj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtemfytcvc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ppjwa.cn/Article/details/gtoajmivcw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.andypj.xyz/Article/details/gtjgojshkc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gttcbxypeh.html

[E14] URL 编码与 Base64
来源：http://dali.smart0.xyz/Article/details/gtsvejrbip.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenlongwang.top/Article/details/gthorsmcog.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtrttcelan.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xinyue.icu/Article/details/gthrhtxdhr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ppjwa.cn/Article/details/gtdwunlefy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gzhubu.top/Article/details/gtdgwnjcvb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.smart0.xyz/Article/details/gtqnuywjdc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yueranfly.top/Article/details/gtzcjuoluj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.birdmap.top/Article/details/gtqhhdbfgv.html

[E15] HTML 转义 / 反转义
来源：http://dali.daxiang520.top/Article/details/gtellfplmw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tian-w.cn/Article/details/gttlnwxnmp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shangyingyoupin.top/Article/details/gthvskglyf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnyaxssuw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtzjhobjbs.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangshuangyany.cn/Article/details/gtpxiuaocm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtogrxctkb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj20258.top/Article/details/gttdgsfwzq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jqgufenzy.top/Article/details/gtefqtfqcu.html

[E16] 数字千分位
来源：http://dali.bjfxy.top/Article/details/gtuneijurm.html

Py:   f"{1234567:,}"
来源：http://dali.xziqi.cn/Article/details/gtwhlgwxzp.html

PHP:  number_format(1234567);
来源：http://dali.feifeiyinyue.top/Article/details/gtoxpesdbe.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258888.top/Article/details/gtbbnngdlr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.pengpengdd.cyou/Article/details/gtvzsrtajj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtftltzriw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shzxlz.cn/Article/details/gtyhnkndzc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cqqwz.cn/Article/details/gtgklsybld.html

C#:   1234567.ToString("N0")
来源：http://dali.zhengqikj.top/Article/details/gtaktdparg.html

[E17] 首字母大写
来源：http://dali.dianchejie.cn/Article/details/gtgwqkjzbh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.aibaodan.cn/Article/details/gtfqnjktkd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yueranfly.top/Article/details/gthtktdeyv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuanzhike.top/Article/details/gtabtkouyh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gtgtjmmvrc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cucudq.cn/Article/details/gtbbxacpbn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtagrpqqjq.html

Ruby: s.capitalize
来源：http://dali.tianlin.xyz/Article/details/gtekfsgskf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sweek.top/Article/details/gtnecavjga.html

[E18] 模板占位符替换
来源：http://dali.redwolf501.top/Article/details/gtwyirpvut.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ehwqpu.com/Article/details/gtqytfwdzl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.fengsongda.top/Article/details/gtlwmioboa.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtfaxtnbwe.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtcrnmzpea.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gtkyjxwauj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtdnadcnbu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.birdmap.top/Article/details/gtwrwqoxge.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.aibaodan.cn/Article/details/gthjtudtlt.html

[E19] 多行文本按行拆分
来源：http://dali.andypj.xyz/Article/details/gtrgwwsbgx.html

Py:   s.splitlines()
来源：http://dali.andypj.xyz/Article/details/gtrtsvampd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtumjgtdml.html

JS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gtrbkmplib.html

TS:   s.split(/\r?\n/)
来源：http://dali.zycfv.cn/Article/details/gthfulipmp.html

Java: s.lines().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkichvtdq.html

Go:   strings.Split(s, "\n")
来源：http://dali.bjfxy.top/Article/details/gtimeguwkh.html

Ruby: s.lines
来源：http://dali.zhixingplan.top/Article/details/gtghfapsmi.html

C#:   s.Split('\n')
来源：http://dali.yanxiufei.cn/Article/details/gtymbexmuq.html

[E20] 判断字符串是否为空
来源：http://dali.yj20258.top/Article/details/gtjbuagben.html

Py:   if not s:
来源：http://dali.zycfv.cn/Article/details/gtnsbdpyih.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.mhx1999.top/Article/details/gtriekzafk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.redwolf501.top/Article/details/gtlrgelsbx.html

TS:   if (s === "") {}
来源：http://dali.xinyue.icu/Article/details/gtkwpumzly.html

Java: if (s.isEmpty()) {}
来源：http://dali.fengsongda.top/Article/details/gtixpklwio.html

Go:   if s == "" {}
来源：http://dali.jinqigfzy.top/Article/details/gtrkazhrhe.html

Ruby: if s.empty?
来源：http://dali.bjfxy.top/Article/details/gtlrfkkqhy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhongyouzk.top/Article/details/gtzrslycxm.html

[E21] 超长截断加省略号
来源：http://dali.ydzc1.top/Article/details/gtrstqjcao.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pengpengdd.cyou/Article/details/gtircijfcz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtrnplfvwn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gttsmapszr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtdudolkwh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gtfaznmcuy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jlsjyb.cn/Article/details/gtpqicooaw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtzvhetaiw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtzjgatcun.html

[E22] 字节长度与字符长度
来源：http://dali.quarkkingdee.top/Article/details/gtualvgmdo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj20258.top/Article/details/gtbnhrbrsf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtjwwgxjbt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aizwys.cn/Article/details/gtvhjmdrxu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gtjrmakldu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.dashuyun.cn/Article/details/gthquzmgcg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tianlin.xyz/Article/details/gtiqwniffx.html

Ruby: s.bytesize;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqwzxpec.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yuanzhike.top/Article/details/gtjnmtoldt.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtbpianzct.html

F. 文件与目录
来源：http://dali.guannengcc.top/Article/details/gtenifvhij.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtevbqjoti.html

[F01] 读取整个文件
来源：http://dali.kuanghao11.cn/Article/details/gtyhkfzjmk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sweek.top/Article/details/gtkrspgwlb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtcvzvpaid.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hongshengwenyu.top/Article/details/gtwhzjxfxb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gtcxnapszh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtozinvauv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gotoacloud.top/Article/details/gtfyjbweul.html

Ruby: File.read("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtboklyura.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtyhpupyki.html

[F02] 逐行读取文件
来源：http://dali.sweek.top/Article/details/gtnbjrvbkw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zycfv.cn/Article/details/gtjpfiesce.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xinyue.icu/Article/details/gtqzywqpdb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cashguo.top/Article/details/gtvygheopa.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.9152youxi.cn/Article/details/gtqmxuugaa.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cheryme.top/Article/details/gtymwyasfd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhengqikj.top/Article/details/gtdcuwrdhr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.vqdsnc.cn/Article/details/gtcsevawlx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shuidangran.top/Article/details/gtnqihzpfx.html

[F03] 写入文件（覆盖）
来源：http://dali.mhx1999.top/Article/details/gtbrvpfjjf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.svipenyu.cn/Article/details/gtazmtfska.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.pycfn.com/Article/details/gttxosjspr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fengsongda.top/Article/details/gtxbqxtxle.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tian-w.cn/Article/details/gtrorecqvz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sysykeji.top/Article/details/gtpukfjdtk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenlongwang.top/Article/details/gtjdikowyx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gtnhxeacie.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.9152youxi.cn/Article/details/gtxztnzazc.html

[F04] 追加写入文件
来源：http://dali.jianghu66.top/Article/details/gtrtncddry.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.daxiang520.top/Article/details/gtepftazbe.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxlfrhtnq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigufen.top/Article/details/gtvzxxfful.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtaglokvop.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jqgufenzy.top/Article/details/gtslcnuken.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.havefunace.top/Article/details/gtzyfvrkac.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hammf.cn/Article/details/gtpeuwtand.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zdqjudy.top/Article/details/gtrkyobmxn.html

[F05] 判断文件或目录是否存在
来源：http://dali.havefunace.top/Article/details/gtkizakibe.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cheryme.top/Article/details/gthvrjfjlb.html

PHP:  file_exists("a.txt");
来源：http://dali.havefunace.top/Article/details/gtioefxgup.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtpktctccz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtdyyumlqk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtobajlvyr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hywenlv.cn/Article/details/gtavkqwqgb.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtufpcvrxm.html

C#:   File.Exists("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtfupugtbb.html

[F06] 删除文件
来源：http://dali.cdnleiting.top/Article/details/gtgqnkfzwh.html

Py:   os.remove("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtyeeryntf.html

PHP:  unlink("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtslyhrsyl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtpdiupmin.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gttmzifice.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtkaxwgavu.html

Go:   os.Remove("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtysmurcox.html

Ruby: File.delete("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtqyplyuwn.html

C#:   File.Delete("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtzpmxxdhj.html

[F07] 创建目录（含多级）
来源：http://dali.sysykeji.top/Article/details/gtmkjdkrhc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xylfe.cn/Article/details/gtlgrpqmcj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.daxiang520.top/Article/details/gtlmwqreat.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shangyingyoupin.top/Article/details/gtyhoseevv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dashuyun.cn/Article/details/gtovbmfwxg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yuanzhike.top/Article/details/gtbkmnxphd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.meibo888.top/Article/details/gteefuvtxy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinqigfzy.top/Article/details/gtrfcnioik.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuanzx.com/Article/details/gtrtqmrqnp.html

[F08] 遍历目录
来源：http://dali.aibaodan.cn/Article/details/gtfkbctrhx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tian-w.cn/Article/details/gtppbczlay.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.guannengcc.top/Article/details/gtqnydjmmz.html

JS:   fs.readdirSync("dir")
来源：http://dali.xziqi.cn/Article/details/gtsboxrvmu.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj202588.top/Article/details/gtblxzzvth.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gtrwesnbnq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cqqwz.cn/Article/details/gtjnzwipba.html

Ruby: Dir.children("dir")
来源：http://dali.pycfn.com/Article/details/gtiwbatptc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sxryk.cn/Article/details/gtqpkfpsql.html

[F09] 获取文件大小
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwkcphmx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtzciijolm.html

PHP:  filesize("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtfijeztdx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gtlmaexqgc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ydzc1.top/Article/details/gtbaxelxrb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gttxeziyqo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dashuyun.cn/Article/details/gtoruifryo.html

Ruby: File.size("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtrtkwefef.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xziqi.cn/Article/details/gtmwvcdadg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.fzhhl.top/Article/details/gtzqpmsjgu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtkzwhptrc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtrdpiywoq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtkpkvymhu.html

TS:   path.extname("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxtokvffy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hongshengwenyu.top/Article/details/gtoylbyxsl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtcrlpypwb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gthfgievzy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtskzveadv.html

[F11] 复制与移动文件
来源：http://dali.redwolf501.top/Article/details/gtnixnrjxr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gttshtggva.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yueranfly.top/Article/details/gtbyhpjyav.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gtmnyplxcn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtweipkzwn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gotoacloud.top/Article/details/gtayjhpala.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gogol.net.cn/Article/details/gtyfyobggo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtirfzmzwm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gtohqpqiyy.html

[F12] CSV 读写
来源：http://dali.jianghu66.top/Article/details/gtpnvwyiub.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jiagoushi.top/Article/details/gtozpdxfja.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gotoacloud.top/Article/details/gtyzcpdimv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tian-w.cn/Article/details/gtgqtksnzk.html

TS:   // 同上
来源：http://dali.jinqigufen.top/Article/details/gtnutgsytv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xziqi.cn/Article/details/gtzcxiunfh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmmtabmkd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.daxiang520.top/Article/details/gtuwfzpwgq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.meibo888.top/Article/details/gtmvrmfwxp.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtjhwsywij.html

G. 面向对象
来源：http://dali.hysaishi.cn/Article/details/gtgmpvlbdj.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtyxfuetzf.html

[G01] 定义类
来源：http://dali.sweek.top/Article/details/gtympihhtn.html

Py:   class User: pass
来源：http://dali.cheryme.top/Article/details/gteckhnsgv.html

PHP:  class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtwcxnkgyd.html

JS:   class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtbgvnmgtf.html

TS:   class User { name: string = ""; }
来源：http://dali.sysykeji.top/Article/details/gtooexovpe.html

Java: class User {}
来源：http://dali.redwolf501.top/Article/details/gthrdhlexz.html

Go:   type User struct { Name string }
来源：http://dali.svipenyu.cn/Article/details/gtjyxmrsss.html

Ruby: class User; end
来源：http://dali.zycfv.cn/Article/details/gtmxnexjok.html

C#:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gtmscymysu.html

[G02] 构造函数
来源：http://dali.gzhubu.top/Article/details/gtozlfqwmh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cashguo.top/Article/details/gtzsrjonln.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinqigfzy.top/Article/details/gtgifqfvcd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shuidangran.top/Article/details/gtverlawwt.html

TS:   constructor(public name: string) {}
来源：http://dali.xylfe.cn/Article/details/gtmiomwjrw.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfpanpgc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jiagoushi.top/Article/details/gtqxbxfram.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fzhhl.top/Article/details/gtjazjulaj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.havefunace.top/Article/details/gtivaeqzhx.html

[G03] 实例属性
来源：http://dali.kuanghao11.cn/Article/details/gtizkouejs.html

Py:   self.name = "x"
来源：http://dali.hongshengwenyu.top/Article/details/gtkpymvwbz.html

PHP:  public string $name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtqqlchcdx.html

JS:   this.name = "x";
来源：http://dali.yonumen.top/Article/details/gtlrdspyfo.html

TS:   name: string = "x";
来源：http://dali.c1oappe.top/Article/details/gtookldyjx.html

Java: private String name;
来源：http://dali.snrcjt.cn/Article/details/gtokuzxtpi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.bjfxy.top/Article/details/gtjidmnmvs.html

Ruby: @name = "x"
来源：http://dali.xinyue.icu/Article/details/gtwgkasmkf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigfzy.top/Article/details/gttjebvykw.html

[G04] 定义方法
来源：http://dali.tian-w.cn/Article/details/gtzycbsrvv.html

Py:   def greet(self): return self.name
来源：http://dali.aizwys.cn/Article/details/gtzqzbgmee.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtutzdxxfm.html

JS:   greet() { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtorisnsfy.html

TS:   greet(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtmtrykzcp.html

Java: String greet() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gthghauqkc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gthsydfjyg.html

Ruby: def greet; @name; end
来源：http://dali.redwolf501.top/Article/details/gtuoyjppvw.html

C#:   public string Greet() => Name;
来源：http://dali.smart0.xyz/Article/details/gthxdbjzoe.html

[G05] 继承
来源：http://dali.daria6918.cn/Article/details/gtbezucdsr.html

Py:   class Admin(User): pass
来源：http://dali.xylfe.cn/Article/details/gtiiyizsqp.html

PHP:  class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtvzvzqqgz.html

JS:   class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtxqzdvsae.html

TS:   class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbzrxqyw.html

Java: class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtyxsblqfb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.aibaodan.cn/Article/details/gtdjmlbaao.html

Ruby: class Admin < User; end
来源：http://dali.hammf.cn/Article/details/gtewhqzmyh.html

C#:   class Admin : User {}
来源：http://dali.ydzc1.top/Article/details/gtbyhuipdl.html

[G06] 重写方法
来源：http://dali.jianghu66.top/Article/details/gthnwphcya.html

Py:   def greet(self): return "admin"
来源：http://dali.gogol.net.cn/Article/details/gtmdnmsmzy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjeafqgsl.html

JS:   greet() { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtjfvgzozu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gtxdmsvaac.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtoqdctzwa.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ehwqpu.com/Article/details/gtwvjnthbs.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbkcmjtb.html

C#:   public override string Greet() => "admin";
来源：http://dali.hammf.cn/Article/details/gtqrspzrgc.html

[G07] 调用父类方法
来源：http://dali.nanxinkj.top/Article/details/gtqmqjfvko.html

Py:   super().greet()
来源：http://dali.xuetiantiany.cn/Article/details/gtnvijnwcp.html

PHP:  parent::greet();
来源：http://dali.zycfv.cn/Article/details/gtcwdvqprk.html

JS:   super.greet();
来源：http://dali.yueranfly.top/Article/details/gtmzwwzjoz.html

TS:   super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gtegvwgpwl.html

Java: super.greet();
来源：http://dali.meibo888.top/Article/details/gtisfvuucr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xuanzx.com/Article/details/gtbgmjsccp.html


<!-- 参考信息 -->