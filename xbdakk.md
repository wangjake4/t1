代发 wailian999

Go:   strings.Join(items, ",")
来源：http://dali.c1oappe.top/Article/details/gtatuqtqoj.html

Ruby: items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtvrithqsf.html

C#:   string.Join(",", items)
来源：http://dali.jianghu66.top/Article/details/gtqlcnaogd.html

[E09] 去除所有空白字符
来源：http://dali.nwbrower.top/Article/details/gtnkjfcyhl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj202588.top/Article/details/gtjyfusnbg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtutneapss.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cucudq.cn/Article/details/gtchcaropk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.mhx1999.top/Article/details/gtviagcxni.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yongpay.top/Article/details/gtaiovmnmr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ppjwa.cn/Article/details/gtqsjgtxop.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cucudq.cn/Article/details/gtlrkxrhnn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.pengpengdd.cyou/Article/details/gtjnogzfdv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hongshengwenyu.top/Article/details/gtzaitekxp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yvedp.cn/Article/details/gtjazqlrjs.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cucudq.cn/Article/details/gtptlkvwbq.html

JS:   "7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gtikdbglhw.html

TS:   "7".padStart(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gtkfjgbzeq.html

Java: String.format("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gtplpqfqxl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtuwojxiey.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gtsqgfqaip.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.dashuyun.cn/Article/details/gtyfrhsqul.html

[E11] 反转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtxprzjxzw.html

Py:   s[::-1]
来源：http://dali.pycfn.com/Article/details/gtntywqdow.html

PHP:  strrev($s);
来源：http://dali.yj20258888.top/Article/details/gthmpthxsc.html

JS:   [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gtpsumffbk.html

TS:   [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gtjtzrcdcj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.dianchejie.cn/Article/details/gtjlywdbfh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gtvcwiccza.html

Ruby: s.reverse
来源：http://dali.cdnleiting.top/Article/details/gtbdettgql.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.guannengcc.top/Article/details/gtobfftiam.html

[E12] 统计某字符出现次数
来源：http://dali.xylfe.cn/Article/details/gtmyeqhmbz.html

Py:   s.count("a")
来源：http://dali.wangdashe.top/Article/details/gtayoagbff.html

PHP:  substr_count($s, "a");
来源：http://dali.jlsjyb.cn/Article/details/gtltigdcxc.html

JS:   s.split("a").length - 1
来源：http://dali.gotoacloud.top/Article/details/gtgermlsyz.html

TS:   s.split("a").length - 1
来源：http://dali.yueranfly.top/Article/details/gtvpwpbyzm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhengqikj.top/Article/details/gtpilkdcjy.html

Go:   strings.Count(s, "a")
来源：http://dali.gogol.net.cn/Article/details/gtedsnsway.html

Ruby: s.count("a")
来源：http://dali.zhixingplan.top/Article/details/gtcbivyepx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xylfe.cn/Article/details/gtsksnjaxp.html

[E13] 逐字符遍历
来源：http://dali.ehwqpu.com/Article/details/gtcbegqnck.html

Py:   for ch in s: print(ch)
来源：http://dali.gzhubu.top/Article/details/gtzograanz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhoulong.xyz/Article/details/gtyxuuitfy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gthycxctte.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gtentspfnq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtavutgkyr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jqgufenzy.top/Article/details/gtgxqxnmqp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sufxvd.cn/Article/details/gtrzeublbc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cheryme.top/Article/details/gtyxflpbgl.html

[E14] URL 编码与 Base64
来源：http://dali.yj20258.top/Article/details/gtphjtgjdo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jlsjyb.cn/Article/details/gtifcwvkik.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gzhubu.top/Article/details/gtkuogdszj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.bjfxy.top/Article/details/gtwmvrdcsb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hammf.cn/Article/details/gtwdhlfhva.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhixingplan.top/Article/details/gtvoemjhrp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.daxiang520.top/Article/details/gtcghrezow.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.fzhhl.top/Article/details/gtlmuqdcvb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenzaomai.com/Article/details/gtnxbqndnc.html

[E15] HTML 转义 / 反转义
来源：http://dali.ybcxt.top/Article/details/gthwpiocqh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.meibo888.top/Article/details/gtharitsqm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.svipenyu.cn/Article/details/gtlfajbpry.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.kuanghao11.cn/Article/details/gtzgbayopj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nanxuanxn.top/Article/details/gthvwvflal.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenlongwang.top/Article/details/gtyaceeqju.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ivvv.top/Article/details/gtbngasdmm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.fengsongda.top/Article/details/gtjnxdtxjv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnqzz.top/Article/details/gtkvvvlrli.html

[E16] 数字千分位
来源：http://dali.fengsongda.top/Article/details/gtmrnhmhzb.html

Py:   f"{1234567:,}"
来源：http://dali.zhoulong.xyz/Article/details/gtgwjnckkx.html

PHP:  number_format(1234567);
来源：http://dali.sysykeji.top/Article/details/gtykfwayvc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tianlin.xyz/Article/details/gtpushygfb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.9152youxi.cn/Article/details/gtwgmbvhvl.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tianlin.xyz/Article/details/gtsleduwbu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xylfe.cn/Article/details/gtacvcmqun.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenlongwang.top/Article/details/gtgcjcujak.html

C#:   1234567.ToString("N0")
来源：http://dali.chenzaomai.com/Article/details/gtegzjqxlp.html

[E17] 首字母大写
来源：http://dali.zycfv.cn/Article/details/gtppteriiw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.redwolf501.top/Article/details/gtjipzqaqt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tanke756.top/Article/details/gtapqxauch.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gzhubu.top/Article/details/gtzqzlndcy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yueranfly.top/Article/details/gtizggwmoi.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cucudq.cn/Article/details/gtvsqmovrm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.dashuyun.cn/Article/details/gtqqehkjqu.html

Ruby: s.capitalize
来源：http://dali.xziqi.cn/Article/details/gttxxjnrvt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.guannengcc.top/Article/details/gtldputkui.html

[E18] 模板占位符替换
来源：http://dali.zdqjudy.top/Article/details/gtgjamjpkv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xuetiantiany.cn/Article/details/gtifsnpwgo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cdnleiting.top/Article/details/gtsizzreuo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gtacnfcmgx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gthgxnlsok.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtqdkveksb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gtjgshvmeg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fzhhl.top/Article/details/gthgordadu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.iojbl.cn/Article/details/gtggrnwtol.html

[E19] 多行文本按行拆分
来源：http://dali.shangyingyoupin.top/Article/details/gtlqixkkni.html

Py:   s.splitlines()
来源：http://dali.jyoumei.cn/Article/details/gtinlrkbrv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yangfankeji.com/Article/details/gtdaqdlwiq.html

JS:   s.split(/\r?\n/)
来源：http://dali.ivvv.top/Article/details/gteilvjjlt.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gtgctlozan.html

Java: s.lines().toList()
来源：http://dali.ivvv.top/Article/details/gtbgvufjgc.html

Go:   strings.Split(s, "\n")
来源：http://dali.hfpthk.cn/Article/details/gtrywmfdif.html

Ruby: s.lines
来源：http://dali.quarkkingdee.top/Article/details/gtsvbrmtcx.html

C#:   s.Split('\n')
来源：http://dali.tian-w.cn/Article/details/gtlsdckoon.html

[E20] 判断字符串是否为空
来源：http://dali.quarkkingdee.top/Article/details/gtuownxvvb.html

Py:   if not s:
来源：http://dali.xuetiantiany.cn/Article/details/gtoyinubti.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpucywzgl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.birdmap.top/Article/details/gtfyddyycj.html

TS:   if (s === "") {}
来源：http://dali.daria6918.cn/Article/details/gtkdnfnxeg.html

Java: if (s.isEmpty()) {}
来源：http://dali.nwbrower.top/Article/details/gtruqcnxpg.html

Go:   if s == "" {}
来源：http://dali.c1oappe.top/Article/details/gtgjtzicfn.html

Ruby: if s.empty?
来源：http://dali.yueranfly.top/Article/details/gtrgbnjkps.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtjrvpjyag.html

[E21] 超长截断加省略号
来源：http://dali.cheryme.top/Article/details/gthluabrcc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.haohaochexian.top/Article/details/gtddeixtmp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gtowtymmaq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtrmcvqiec.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtkhrkkbtr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteuuwflgy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.fzhhl.top/Article/details/gtzedawdwd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gttpkvshxk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtyefuuomd.html

[E22] 字节长度与字符长度
来源：http://dali.cqqwz.cn/Article/details/gtnwmksvcv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenzaomai.com/Article/details/gtfmxtylih.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gtyzezxyrb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ehwqpu.com/Article/details/gtiqferrfi.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gttyifwwnk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hnqzz.top/Article/details/gtjukirhom.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.andypj.xyz/Article/details/gtbqahowzo.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gtvmcnogqa.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.svipenyu.cn/Article/details/gtejwczlpa.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtxkmabtkw.html

F. 文件与目录
来源：http://dali.fzhhl.top/Article/details/gtmrxxtdbp.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtvxbsneol.html

[F01] 读取整个文件
来源：http://dali.dianchejie.cn/Article/details/gtedujcybq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.quarkkingdee.top/Article/details/gtgelpagml.html

PHP:  file_get_contents("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtvhsohvkl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.9152youxi.cn/Article/details/gtqmpewhws.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gtnxisglfd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtqajklpgp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.316326.xyz/Article/details/gtwkrhqvud.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpqgiiqfk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtuieeilck.html

[F02] 逐行读取文件
来源：http://dali.haohaochexian.top/Article/details/gtwtcpilzy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.smart0.xyz/Article/details/gtaobhzpzf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenlongwang.top/Article/details/gtcdeziunx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.smart0.xyz/Article/details/gtcbleytcw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtgoyotuaz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gtjnnvpxjb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ivvv.top/Article/details/gtoaaiskjf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hammf.cn/Article/details/gtnmjvgbiy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sufxvd.cn/Article/details/gtogtfymlg.html

[F03] 写入文件（覆盖）
来源：http://dali.chenjidiqi.icu/Article/details/gtxdiutbuz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.havefunace.top/Article/details/gtmukbseng.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zycfv.cn/Article/details/gtwunqnygq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gtauxmtsfr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jianghu66.top/Article/details/gttpxzmwop.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.wangshuangyany.cn/Article/details/gtlutwygzo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xziqi.cn/Article/details/gtiehnuubj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gtkmgnsrry.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hnxiangtu.top/Article/details/gtisxjzagh.html

[F04] 追加写入文件
来源：http://dali.guowangkeji.top/Article/details/gthvoevytl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.birdmap.top/Article/details/gtibruziju.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthyovltvy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.mhx1999.top/Article/details/gtjlvxurmp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gtzdwyyfno.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.guowangkeji.top/Article/details/gtsufkkhvy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhongyouzk.top/Article/details/gtguyxemff.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hnqzz.top/Article/details/gtkrlsjlfa.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jiagoushi.top/Article/details/gtwwaujdxe.html

[F05] 判断文件或目录是否存在
来源：http://dali.nanxuanxn.top/Article/details/gtcnwbfwle.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.pengpengdd.cyou/Article/details/gtrwelspat.html

PHP:  file_exists("a.txt");
来源：http://dali.yonumen.top/Article/details/gtiwzjexwo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtsfftewrh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtptedjfhh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtjxduxids.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xuanzx.com/Article/details/gteneuztxz.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqnsifehi.html

C#:   File.Exists("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtwskdyeke.html

[F06] 删除文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtlshtjaui.html

Py:   os.remove("a.txt")
来源：http://dali.meibo888.top/Article/details/gtwmgyxvga.html

PHP:  unlink("a.txt");
来源：http://dali.cashguo.top/Article/details/gtfhcpixfe.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtfwdrveax.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtzksbbiyl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtvzfuriau.html

Go:   os.Remove("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtdcphnkdz.html

Ruby: File.delete("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtnxanqipn.html

C#:   File.Delete("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtrttjrvyh.html

[F07] 创建目录（含多级）
来源：http://dali.jyoumei.cn/Article/details/gtffeesmob.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cucudq.cn/Article/details/gtloueswey.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.fzhhl.top/Article/details/gtrscwdzuj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cheryme.top/Article/details/gtspxizsss.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shangyingyoupin.top/Article/details/gtqkqxnubh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.0kj1m.cn/Article/details/gtsfcxyrgs.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.iojbl.cn/Article/details/gtsrlmgdkb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zdqjudy.top/Article/details/gtbflsqgpb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhoulong.xyz/Article/details/gtsfxvwalf.html

[F08] 遍历目录
来源：http://dali.ppjwa.cn/Article/details/gtgjtbhacm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.c1oappe.top/Article/details/gtjgvyunob.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gtutiegchu.html

JS:   fs.readdirSync("dir")
来源：http://dali.ehwqpu.com/Article/details/gtankrellx.html

TS:   fs.readdirSync("dir")
来源：http://dali.yueranfly.top/Article/details/gtoxgqumov.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.feifeiyinyue.top/Article/details/gtpgcuyonc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtcgysstmq.html

Ruby: Dir.children("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtkaynrbju.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtmixuwpfd.html

[F09] 获取文件大小
来源：http://dali.gogol.net.cn/Article/details/gtlsbibcsy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtusbacwow.html

PHP:  filesize("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtowqwbdxc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hysaishi.cn/Article/details/gtqgdztkix.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jlsjyb.cn/Article/details/gtazfctrvp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtpeajdink.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ivvv.top/Article/details/gtztjjyfsu.html

Ruby: File.size("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtgzowcqvh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhoulong.xyz/Article/details/gtiijvolvo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.guannengcc.top/Article/details/gtlkjpuhhj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtsumvzbpd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtuiohrjpn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzbqluthh.html

TS:   path.extname("a.txt")
来源：http://dali.meibo888.top/Article/details/gtqwtumxyn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gotoacloud.top/Article/details/gtgjoeiejj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtgfnpmpwi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtjbuchuzp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gteusmuwjm.html

[F11] 复制与移动文件
来源：http://dali.redwolf501.top/Article/details/gtokoerojq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gthpwriyjp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.birdmap.top/Article/details/gtzxyotvtt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtccmhhsis.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gtmsdtahnd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtjyatikft.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cdnleiting.top/Article/details/gtwnxrhcjm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtegztfutf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pengpengdd.cyou/Article/details/gtghysfwqu.html

[F12] CSV 读写
来源：http://dali.sweek.top/Article/details/gthyeyzpdm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.dashuyun.cn/Article/details/gtvpqbgwpv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.meibo888.top/Article/details/gtxotrvdww.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenjidiqi.icu/Article/details/gtouykbxtk.html

TS:   // 同上
来源：http://dali.chenlongwang.top/Article/details/gtugzfaddn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnxiangtu.top/Article/details/gtqletkims.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.pengpengdd.cyou/Article/details/gtymdhkmis.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.iojbl.cn/Article/details/gtkexvjpyp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jqgfzy.top/Article/details/gtgodatfem.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtqavnrmjc.html

G. 面向对象
来源：http://dali.yuxming.cn/Article/details/gtjrzjahdw.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtkpqzukvm.html

[G01] 定义类
来源：http://dali.gogol.net.cn/Article/details/gtazkvimpp.html

Py:   class User: pass
来源：http://dali.cucudq.cn/Article/details/gtpvyhawmv.html

PHP:  class User {}
来源：http://dali.cashguo.top/Article/details/gtmmfuvmhf.html

JS:   class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmpsjpzmg.html

TS:   class User { name: string = ""; }
来源：http://dali.svipenyu.cn/Article/details/gtqpnbcssq.html

Java: class User {}
来源：http://dali.meibo888.top/Article/details/gtrfjfvzth.html

Go:   type User struct { Name string }
来源：http://dali.bjfxy.top/Article/details/gtrcjghopt.html

Ruby: class User; end
来源：http://dali.jiagoushi.top/Article/details/gtasvrvepc.html

C#:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gtvtmfvhsu.html

[G02] 构造函数
来源：http://dali.gogol.net.cn/Article/details/gtaubehszl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.316326.xyz/Article/details/gtjfuazxpj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xinyue.icu/Article/details/gtzbcskcvj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gtaazplmle.html

TS:   constructor(public name: string) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtlrxprfod.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gtioitspbl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspvcifqe.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.svipenyu.cn/Article/details/gtegcodbgf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfyxanhsu.html

[G03] 实例属性
来源：http://dali.birdmap.top/Article/details/gtqtbqkzar.html

Py:   self.name = "x"
来源：http://dali.yj20258.top/Article/details/gtzweovhyx.html

PHP:  public string $name = "x";
来源：http://dali.guannengcc.top/Article/details/gtzqtvmefr.html

JS:   this.name = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfiosdrrt.html

TS:   name: string = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtznlfpbqv.html

Java: private String name;
来源：http://dali.iojbl.cn/Article/details/gtacpvutma.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.smart0.xyz/Article/details/gtxpsbmbsb.html

Ruby: @name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gtvqvtukvg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.andypj.xyz/Article/details/gtohmgkzwt.html

[G04] 定义方法
来源：http://dali.wangdashe.top/Article/details/gtyvqeyryz.html

Py:   def greet(self): return self.name
来源：http://dali.sysykeji.top/Article/details/gtaetlhros.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gttgphwbmx.html

JS:   greet() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtraarervs.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtfdbwneyn.html

Java: String greet() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtenyqgxgn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gtubgdqmat.html

Ruby: def greet; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gtxawztwob.html

C#:   public string Greet() => Name;
来源：http://dali.sufxvd.cn/Article/details/gtldwlshko.html

[G05] 继承
来源：http://dali.hongshengwenyu.top/Article/details/gtjkwvdfbc.html

Py:   class Admin(User): pass
来源：http://dali.hnqzz.top/Article/details/gtvvyxxhuc.html

PHP:  class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtlrtzmdpo.html

JS:   class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtekspkfgx.html

TS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtoojholqq.html

Java: class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gteteddwbs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hongshengwenyu.top/Article/details/gtgfoifouh.html

Ruby: class Admin < User; end
来源：http://dali.cqqwz.cn/Article/details/gtcqdllsol.html

C#:   class Admin : User {}
来源：http://dali.xuanzx.com/Article/details/gtrgyptqta.html

[G06] 重写方法
来源：http://dali.fzhhl.top/Article/details/gtikrjlnal.html

Py:   def greet(self): return "admin"
来源：http://dali.9152youxi.cn/Article/details/gtrbtuchgu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtnjopgerr.html

JS:   greet() { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtxmddtjui.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtajguyfcs.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtazqgqcch.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.fengsongda.top/Article/details/gtfdkwbznq.html

Ruby: def greet; "admin"; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxqvbwnfw.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnxiangtu.top/Article/details/gtyrvatggc.html

[G07] 调用父类方法
来源：http://dali.dashuyun.cn/Article/details/gtiusobsyn.html

Py:   super().greet()
来源：http://dali.jqgufenzy.top/Article/details/gthvsijkss.html

PHP:  parent::greet();
来源：http://dali.hnxiangtu.top/Article/details/gtyegrweic.html


<!-- 参考信息 -->