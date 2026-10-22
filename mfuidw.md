代发 wailian999

PHP:  implode(",", $items);
来源：http://dali.dianchejie.cn/Article/details/gtzyjusxmu.html

JS:   items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gtnbmdwwtl.html

TS:   items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gtbakqzerl.html

Java: String.join(",", items)
来源：http://dali.yj202588.top/Article/details/gtpdflytjh.html

Go:   strings.Join(items, ",")
来源：http://dali.sweek.top/Article/details/gtjdpwpfey.html

Ruby: items.join(",")
来源：http://dali.sxryk.cn/Article/details/gttsogbxsd.html

C#:   string.Join(",", items)
来源：http://dali.ivvv.top/Article/details/gtrxlkacfl.html

[E09] 去除所有空白字符
来源：http://dali.nwbrower.top/Article/details/gtpmbelgic.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtkmzbcmpo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sysykeji.top/Article/details/gtpyjqcclm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.0kj1m.cn/Article/details/gtyfddkyip.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.daria6918.cn/Article/details/gtfxpxafjt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmlxizvns.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.dianchejie.cn/Article/details/gtkfnkdhwg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shangyingyoupin.top/Article/details/gtorcfkhtt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.c1oappe.top/Article/details/gtlelalmyn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenlongwang.top/Article/details/gtxuqhwggh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xinyue.icu/Article/details/gtcitkckhm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.daria6918.cn/Article/details/gtxoujdjrf.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbzirzidm.html

TS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtdaemcccf.html

Java: String.format("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gtqrirvohc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gtmkigytvf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gtotmhwvhp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.guannengcc.top/Article/details/gtpgmblymv.html

[E11] 反转字符串
来源：http://dali.zhixingplan.top/Article/details/gtaqoxlgvg.html

Py:   s[::-1]
来源：http://dali.jlsjyb.cn/Article/details/gttaucrabf.html

PHP:  strrev($s);
来源：http://dali.sweek.top/Article/details/gttvvxvimf.html

JS:   [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gtryijlouf.html

TS:   [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gtwogrwlvp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtdebbnznw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.kuanghao11.cn/Article/details/gtpoumcsxf.html

Ruby: s.reverse
来源：http://dali.cashguo.top/Article/details/gtwfkvghml.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yongpay.top/Article/details/gtnbjhsdde.html

[E12] 统计某字符出现次数
来源：http://dali.9152youxi.cn/Article/details/gtirenyctq.html

Py:   s.count("a")
来源：http://dali.dianchejie.cn/Article/details/gtdbfmltdk.html

PHP:  substr_count($s, "a");
来源：http://dali.yuanzhike.top/Article/details/gtmjhcezna.html

JS:   s.split("a").length - 1
来源：http://dali.hfpthk.cn/Article/details/gtdkxiqsce.html

TS:   s.split("a").length - 1
来源：http://dali.gaohongyu789.top/Article/details/gtrhkxvhqv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yangfankeji.com/Article/details/gtyqgeaxuz.html

Go:   strings.Count(s, "a")
来源：http://dali.fzhhl.top/Article/details/gtparetcjb.html

Ruby: s.count("a")
来源：http://dali.meibo888.top/Article/details/gtercniugd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xinyue.icu/Article/details/gtiqwadmau.html

[E13] 逐字符遍历
来源：http://dali.xziqi.cn/Article/details/gtrldtyvjc.html

Py:   for ch in s: print(ch)
来源：http://dali.c1oappe.top/Article/details/gtcyphiwcc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sweek.top/Article/details/gtwwjbvtdr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj202588.top/Article/details/gtqriiybch.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.svipenyu.cn/Article/details/gtwvwtihbo.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtqktxoeqo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigfzy.top/Article/details/gtgpdnsmim.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hysaishi.cn/Article/details/gtopslhoip.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ehwqpu.com/Article/details/gtpkcuinqm.html

[E14] URL 编码与 Base64
来源：http://dali.jinghuilouyu.cn/Article/details/gtanpmkrqx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhoulong.xyz/Article/details/gtzreqfjks.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqjubxjhl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.meibo888.top/Article/details/gtbubfogsy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yonumen.top/Article/details/gtrrevbhje.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hysaishi.cn/Article/details/gttnbthlqp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hywenlv.cn/Article/details/gtjkgodjnt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.pengpengdd.cyou/Article/details/gtwmokprno.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sweek.top/Article/details/gtxuoznxue.html

[E15] HTML 转义 / 反转义
来源：http://dali.kuanghao11.cn/Article/details/gtpjhjtoqd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cashguo.top/Article/details/gtcrswlkgc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjhchibj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtokirtfcd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigufen.top/Article/details/gtfvgilcxg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.kuanghao11.cn/Article/details/gtggkoffkw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.guowangkeji.top/Article/details/gtyvkhfxka.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shuidangran.top/Article/details/gtenmkxuby.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjgtlsgfw.html

[E16] 数字千分位
来源：http://dali.xuetiantiany.cn/Article/details/gtpbbpredo.html

Py:   f"{1234567:,}"
来源：http://dali.zdqjudy.top/Article/details/gtbezhykeh.html

PHP:  number_format(1234567);
来源：http://dali.zycfv.cn/Article/details/gtbpkmtvao.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cheryme.top/Article/details/gtpiunrelj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.fzhhl.top/Article/details/gtqacfqpfl.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.9152youxi.cn/Article/details/gtromzfomi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhiwuduotai.top/Article/details/gthoywujqo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cucudq.cn/Article/details/gtieqahuuf.html

C#:   1234567.ToString("N0")
来源：http://dali.zycfv.cn/Article/details/gtghftambo.html

[E17] 首字母大写
来源：http://dali.snrcjt.cn/Article/details/gtagldmejh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jiagoushi.top/Article/details/gtbbrthlxq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sufxvd.cn/Article/details/gtwvrarucl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daria6918.cn/Article/details/gtwzregsxk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hysaishi.cn/Article/details/gtkrznjpdp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtlqfwwaen.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sweek.top/Article/details/gtbodeobjc.html

Ruby: s.capitalize
来源：http://dali.jlsjyb.cn/Article/details/gtubpwjaqc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gaohongyu789.top/Article/details/gtqycgaqaj.html

[E18] 模板占位符替换
来源：http://dali.jianghu66.top/Article/details/gtkzeuodml.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrvftvekh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.c1oappe.top/Article/details/gtxodabsoh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gtfhwmslwv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtdvtdsseb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtuwxtjzps.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtdfwvqpdy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxuanxn.top/Article/details/gtqhgkcwvb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzlvcpnl.html

[E19] 多行文本按行拆分
来源：http://dali.yuanzhike.top/Article/details/gttizhrvno.html

Py:   s.splitlines()
来源：http://dali.yonumen.top/Article/details/gtvenedgud.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtulgdodle.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenlongwang.top/Article/details/gttuueuini.html

TS:   s.split(/\r?\n/)
来源：http://dali.yangfankeji.com/Article/details/gtaidikftg.html

Java: s.lines().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtghktkwsj.html

Go:   strings.Split(s, "\n")
来源：http://dali.fengsongda.top/Article/details/gtmewwvjgj.html

Ruby: s.lines
来源：http://dali.jyoumei.cn/Article/details/gtsgmruqbf.html

C#:   s.Split('\n')
来源：http://dali.tianlin.xyz/Article/details/gtzccnpbfg.html

[E20] 判断字符串是否为空
来源：http://dali.aibaodan.cn/Article/details/gtzoexkxkl.html

Py:   if not s:
来源：http://dali.smart0.xyz/Article/details/gtrjymnmdr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.haohaochexian.top/Article/details/gtkgyjiocr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jqgufenzy.top/Article/details/gtxujbgdaa.html

TS:   if (s === "") {}
来源：http://dali.c1oappe.top/Article/details/gtzoibrbrx.html

Java: if (s.isEmpty()) {}
来源：http://dali.sysykeji.top/Article/details/gtlmizjbpt.html

Go:   if s == "" {}
来源：http://dali.snrcjt.cn/Article/details/gtqruqmysd.html

Ruby: if s.empty?
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzlxpgfmw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yongpay.top/Article/details/gttwfpiqhc.html

[E21] 超长截断加省略号
来源：http://dali.shanyushiyangtech.top/Article/details/gttnqibqyj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jianghu66.top/Article/details/gtflvavlrn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtzthirkta.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtacjchajb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtndjjqwpc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtqtrmalfl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cheryme.top/Article/details/gtpaifddgu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258.top/Article/details/gtiawtllri.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tanke756.top/Article/details/gtzjepitfy.html

[E22] 字节长度与字符长度
来源：http://dali.ehwqpu.com/Article/details/gtjpmfuogy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhongyouzk.top/Article/details/gtcbgazywk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gtsykmdjdx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtqvlatspq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gtxamrporq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenzaomai.com/Article/details/gttbjszyck.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ydzc1.top/Article/details/gtlomhmzlf.html

Ruby: s.bytesize;  s.length
来源：http://dali.andypj.xyz/Article/details/gtxsgslbxa.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ehwqpu.com/Article/details/gthqyggnbo.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtmfhusnmd.html

F. 文件与目录
来源：http://dali.fengsongda.top/Article/details/gtumjmdzev.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtwawlpeeb.html

[F01] 读取整个文件
来源：http://dali.iojbl.cn/Article/details/gtuihibedn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.pycfn.com/Article/details/gtcacilyeu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtpfycvljl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.birdmap.top/Article/details/gttvonnekp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yueranfly.top/Article/details/gtewxkwveb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtwygprtkj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sweek.top/Article/details/gtdvevicsm.html

Ruby: File.read("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtdyxpqcac.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtedhzaqoi.html

[F02] 逐行读取文件
来源：http://dali.c1oappe.top/Article/details/gtzamhjcyz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.haohaochexian.top/Article/details/gtvjdpdpgb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zdqjudy.top/Article/details/gtbddwqzjm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gturmizpjr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gogol.net.cn/Article/details/gtfjfonxth.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj20258888.top/Article/details/gtpqelmmxa.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxllxaoel.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sufxvd.cn/Article/details/gtpacgcegp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sweek.top/Article/details/gthiqlktvn.html

[F03] 写入文件（覆盖）
来源：http://dali.sufxvd.cn/Article/details/gtocsvbqsz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yongpay.top/Article/details/gtfktuzzil.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yueranfly.top/Article/details/gtlujuoowk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gtdwipntwm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cashguo.top/Article/details/gtrspjppxl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhixingplan.top/Article/details/gtpfjuhyjl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdiljuniy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yangfankeji.com/Article/details/gtabvootff.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj20258.top/Article/details/gtxaxvxuzp.html

[F04] 追加写入文件
来源：http://dali.feifeiyinyue.top/Article/details/gttipxswid.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangdashe.top/Article/details/gtpklflkui.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cashguo.top/Article/details/gtemehnuzj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuanzhike.top/Article/details/gtijayiuci.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daria6918.cn/Article/details/gtytpxwkld.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cdnleiting.top/Article/details/gtgsakfkxk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hywenlv.cn/Article/details/gtbbrkxazp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gtoovidzft.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jqgufenzy.top/Article/details/gtpkhdlqps.html

[F05] 判断文件或目录是否存在
来源：http://dali.cheryme.top/Article/details/gtzfrrcrca.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cashguo.top/Article/details/gtezwohihs.html

PHP:  file_exists("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtwsudmula.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtuubmyzoo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gteuacedct.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtcyfsvmzj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.vqdsnc.cn/Article/details/gtwpfczlgk.html

Ruby: File.exist?("a.txt")
来源：http://dali.smart0.xyz/Article/details/gthqrprxmg.html

C#:   File.Exists("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtnhlawlcb.html

[F06] 删除文件
来源：http://dali.zhongyouzk.top/Article/details/gtqnonghhd.html

Py:   os.remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtuiagszsc.html

PHP:  unlink("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtahkvlrjg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtcvhlsjti.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtfdsermpg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gtafpkvlyx.html

Go:   os.Remove("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtwvcghkdc.html

Ruby: File.delete("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtwosgyahf.html

C#:   File.Delete("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtuwggleeg.html

[F07] 创建目录（含多级）
来源：http://dali.tanke756.top/Article/details/gtoerrwebf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhoulong.xyz/Article/details/gtcaojczwp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhongyouzk.top/Article/details/gtviqnhlqf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenlongwang.top/Article/details/gtpghlcspd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuetiantiany.cn/Article/details/gtrrtxfqjp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj202588.top/Article/details/gtzreksktn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenjidiqi.icu/Article/details/gtaclpnxmu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gzhubu.top/Article/details/gtighviaqi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hammf.cn/Article/details/gtiwjrfyvc.html

[F08] 遍历目录
来源：http://dali.snrcjt.cn/Article/details/gtxmgmhqee.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sufxvd.cn/Article/details/gtvyjience.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cqqwz.cn/Article/details/gtsvjahavb.html

JS:   fs.readdirSync("dir")
来源：http://dali.0kj1m.cn/Article/details/gtoeobdfsb.html

TS:   fs.readdirSync("dir")
来源：http://dali.yonumen.top/Article/details/gtsadeybqz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.daria6918.cn/Article/details/gttsgqrszq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ydzc1.top/Article/details/gtobbbdwhq.html

Ruby: Dir.children("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtrrdwgtox.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sweek.top/Article/details/gtsmebzasq.html

[F09] 获取文件大小
来源：http://dali.daria6918.cn/Article/details/gtynkznctv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtadryejwe.html

PHP:  filesize("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtelhymehh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangshuangyany.cn/Article/details/gtcovqedzg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shangyingyoupin.top/Article/details/gtdvfcywdv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtwplqknoe.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.iojbl.cn/Article/details/gtaosgaycm.html

Ruby: File.size("a.txt")
来源：http://dali.yuxming.cn/Article/details/gttpnpnpqq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenjidiqi.icu/Article/details/gtbspulbjv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cheryme.top/Article/details/gthftrvorg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqtombagu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.redwolf501.top/Article/details/gtsdzmcutt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gthvyqhcxh.html

TS:   path.extname("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtflgcnwpz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtukmuetxt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtabtpmcrq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtcckfkqyj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjsjddql.html

[F11] 复制与移动文件
来源：http://dali.vqdsnc.cn/Article/details/gttqemgulw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtffbjvvlt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xinyue.icu/Article/details/gteafdkelh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtajavtdtm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtonqzllta.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yvedp.cn/Article/details/gttwtpyoev.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.fzhhl.top/Article/details/gtfxtzzbcr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtuhhfaxuy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gtqpuspyak.html

[F12] CSV 读写
来源：http://dali.ppjwa.cn/Article/details/gthgurhhdf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ivvv.top/Article/details/gtleqrdrug.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.pycfn.com/Article/details/gtosokfktu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yonumen.top/Article/details/gtbwiwkdlk.html

TS:   // 同上
来源：http://dali.guowangkeji.top/Article/details/gtirmcwgkf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sysykeji.top/Article/details/gttwvystsv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxelwety.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jiagoushi.top/Article/details/gtrekebxop.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ivvv.top/Article/details/gtquculzzk.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtwasxuxpe.html

G. 面向对象
来源：http://dali.xziqi.cn/Article/details/gtrbjnlcpn.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gthcuwywbj.html

[G01] 定义类
来源：http://dali.ppjwa.cn/Article/details/gtjmbgwlcs.html

Py:   class User: pass
来源：http://dali.chenjidiqi.icu/Article/details/gtlrfnkxal.html

PHP:  class User {}
来源：http://dali.tanke756.top/Article/details/gtxtsuynrd.html

JS:   class User {}
来源：http://dali.jianghu66.top/Article/details/gtcpjdsyjj.html

TS:   class User { name: string = ""; }
来源：http://dali.gogol.net.cn/Article/details/gtocmhebty.html

Java: class User {}
来源：http://dali.snrcjt.cn/Article/details/gtxqnynscq.html

Go:   type User struct { Name string }
来源：http://dali.jinqigfzy.top/Article/details/gtcrmovmof.html

Ruby: class User; end
来源：http://dali.svipenyu.cn/Article/details/gtceqzvsme.html

C#:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gtgjaxvyom.html

[G02] 构造函数
来源：http://dali.ivvv.top/Article/details/gtppygybis.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258888.top/Article/details/gtwghkfvcq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtfmdfytvx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yvedp.cn/Article/details/gtrnniayqa.html

TS:   constructor(public name: string) {}
来源：http://dali.svipenyu.cn/Article/details/gtcvxwmidp.html

Java: User(String name) { this.name = name; }
来源：http://dali.gogol.net.cn/Article/details/gtvkxiprne.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.daxiang520.top/Article/details/gtdteczfap.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shuidangran.top/Article/details/gtcasuxsxl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gtsnmmeemw.html

[G03] 实例属性
来源：http://dali.zhengqikj.top/Article/details/gtdzzhufkb.html

Py:   self.name = "x"
来源：http://dali.316326.xyz/Article/details/gtrwynvzje.html

PHP:  public string $name = "x";
来源：http://dali.zhengqikj.top/Article/details/gtfykzogrk.html

JS:   this.name = "x";
来源：http://dali.sufxvd.cn/Article/details/gtzmtzsjcn.html

TS:   name: string = "x";
来源：http://dali.shzxlz.cn/Article/details/gtnotekhka.html

Java: private String name;
来源：http://dali.havefunace.top/Article/details/gtqggvbput.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.dianchejie.cn/Article/details/gtwgcrgpqk.html

Ruby: @name = "x"
来源：http://dali.gogol.net.cn/Article/details/gtasqwzhbs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.birdmap.top/Article/details/gtgmgfefku.html

[G04] 定义方法
来源：http://dali.yj20258888.top/Article/details/gtbjschhnp.html

Py:   def greet(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gtvgkjcbsy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gtgfdqfjon.html

JS:   greet() { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtkeakohml.html

TS:   greet(): string { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtjbwmfvwo.html

Java: String greet() { return name; }
来源：http://dali.redwolf501.top/Article/details/gtfzdrtirx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gtmbbslttp.html

Ruby: def greet; @name; end
来源：http://dali.tianlin.xyz/Article/details/gtfoicsmnr.html

C#:   public string Greet() => Name;
来源：http://dali.xinyue.icu/Article/details/gtnwgqcalr.html

[G05] 继承
来源：http://dali.bjfxy.top/Article/details/gtautwuekv.html

Py:   class Admin(User): pass
来源：http://dali.ybcxt.top/Article/details/gtfshpxwco.html

PHP:  class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtryxnuozs.html

JS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtybjjndwz.html

TS:   class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtopvigibz.html

Java: class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtzmxyjxys.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.daria6918.cn/Article/details/gtmcmfdorl.html

Ruby: class Admin < User; end
来源：http://dali.yueranfly.top/Article/details/gtqrovokgs.html

C#:   class Admin : User {}
来源：http://dali.chenzaomai.com/Article/details/gtyvidxfnt.html

[G06] 重写方法
来源：http://dali.zhiwuduotai.top/Article/details/gtfwjlnwru.html

Py:   def greet(self): return "admin"
来源：http://dali.hnxiangtu.top/Article/details/gtdrnuolfz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtnzgkgari.html

JS:   greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtomhvjeoj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtamamusug.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtipbmryon.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hfpthk.cn/Article/details/gtemrldzjb.html

Ruby: def greet; "admin"; end
来源：http://dali.guannengcc.top/Article/details/gtmbbrjuvq.html


<!-- 参考信息 -->