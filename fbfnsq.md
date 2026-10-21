代发 wailian999

TS:   s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtczdsydez.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtmzlsjadu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hnxiangtu.top/Article/details/gthlpqnmih.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtsfsfoqzd.html

C#:   s.Replace("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtfiliseky.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gtmfkxgebn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.aibaodan.cn/Article/details/gtggvycjkn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtkvjbkumc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jyoumei.cn/Article/details/gtidbipihw.html

TS:   s.split(",")
来源：http://dali.xylfe.cn/Article/details/gthaevrexd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jqgfzy.top/Article/details/gtabkwiiyh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.smart0.xyz/Article/details/gttjleoaat.html

Ruby: s.split(",");  s.split
来源：http://dali.sxryk.cn/Article/details/gtlahitdry.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.daxiang520.top/Article/details/gtxbdhomnc.html

[E08] 数组按分隔符合并
来源：http://dali.yonumen.top/Article/details/gtlhjyhhmz.html

Py:   ",".join(items)
来源：http://dali.hywenlv.cn/Article/details/gtsjaikrec.html

PHP:  implode(",", $items);
来源：http://dali.kuanghao11.cn/Article/details/gthiexqqxq.html

JS:   items.join(",")
来源：http://dali.xinyue.icu/Article/details/gtsflrcfzv.html

TS:   items.join(",")
来源：http://dali.yj20258.top/Article/details/gtoxcgjfye.html

Java: String.join(",", items)
来源：http://dali.sysykeji.top/Article/details/gtopessumk.html

Go:   strings.Join(items, ",")
来源：http://dali.vqdsnc.cn/Article/details/gtdetpjnqh.html

Ruby: items.join(",")
来源：http://dali.hfpthk.cn/Article/details/gtdwmkrmes.html

C#:   string.Join(",", items)
来源：http://dali.andypj.xyz/Article/details/gtbecodkpx.html

[E09] 去除所有空白字符
来源：http://dali.jqgfzy.top/Article/details/gtdgilpwye.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cashguo.top/Article/details/gtsesamyea.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.guowangkeji.top/Article/details/gtimldpiep.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigufen.top/Article/details/gtduhpavjm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.quarkkingdee.top/Article/details/gtvcyoxlsc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hfpthk.cn/Article/details/gtvawafray.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ybcxt.top/Article/details/gtugmqeecf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.nanxinkj.top/Article/details/gtzhblrvee.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cheryme.top/Article/details/gthulpdkrt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ybcxt.top/Article/details/gtuqednurx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gtvhevwrmb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhengqikj.top/Article/details/gtazdhuyoo.html

JS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtbdewuenk.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj20258.top/Article/details/gtcmmanahx.html

Java: String.format("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gtztdgvnod.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmgmlbuwr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gtgtasguzl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqphkmva.html

[E11] 反转字符串
来源：http://dali.haohaochexian.top/Article/details/gtaueenlzy.html

Py:   s[::-1]
来源：http://dali.gzhubu.top/Article/details/gtyqlfvliu.html

PHP:  strrev($s);
来源：http://dali.zhengqikj.top/Article/details/gtaynjcmsj.html

JS:   [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtcxyrhgbr.html

TS:   [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gtbmcdznxg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtgsaoxfvw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.guannengcc.top/Article/details/gthfovlafp.html

Ruby: s.reverse
来源：http://dali.kuanghao11.cn/Article/details/gteecsmwvg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cucudq.cn/Article/details/gtldmanuvj.html

[E12] 统计某字符出现次数
来源：http://dali.jqgufenzy.top/Article/details/gtiktxfqkt.html

Py:   s.count("a")
来源：http://dali.wangdashe.top/Article/details/gtirsgvqnr.html

PHP:  substr_count($s, "a");
来源：http://dali.sysykeji.top/Article/details/gtwgciakve.html

JS:   s.split("a").length - 1
来源：http://dali.haohaochexian.top/Article/details/gtfpaqwhxv.html

TS:   s.split("a").length - 1
来源：http://dali.0kj1m.cn/Article/details/gtjmtotyay.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.snrcjt.cn/Article/details/gtxuufungu.html

Go:   strings.Count(s, "a")
来源：http://dali.cashguo.top/Article/details/gtavkdgvgw.html

Ruby: s.count("a")
来源：http://dali.sxryk.cn/Article/details/gtsnedumbd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ehwqpu.com/Article/details/gtqzncmeho.html

[E13] 逐字符遍历
来源：http://dali.yj202588.top/Article/details/gtfyfbseva.html

Py:   for ch in s: print(ch)
来源：http://dali.cucudq.cn/Article/details/gtzszfnfss.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pycfn.com/Article/details/gtoxkopjql.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangdashe.top/Article/details/gtbzmbfmot.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.andypj.xyz/Article/details/gtbqrsxcaw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tianlin.xyz/Article/details/gtozqqxbpt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gogol.net.cn/Article/details/gttkpgikcl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenzaomai.com/Article/details/gthfofjyhb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gtlnynrmic.html

[E14] URL 编码与 Base64
来源：http://dali.sysykeji.top/Article/details/gtnwiwnczn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cucudq.cn/Article/details/gtrntznwlf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj20258.top/Article/details/gtjgidiuro.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jianghu66.top/Article/details/gtclahcpbb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yuanzhike.top/Article/details/gtqrdwowgm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xylfe.cn/Article/details/gtweoepndc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.pengpengdd.cyou/Article/details/gtaqjmdnwa.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xylfe.cn/Article/details/gtctpfllwd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cucudq.cn/Article/details/gtpgrfwxgo.html

[E15] HTML 转义 / 反转义
来源：http://dali.dianchejie.cn/Article/details/gtxpjxiben.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtkvosumhk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yanxiufei.cn/Article/details/gtnisqwawc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenzaomai.com/Article/details/gtradtthbm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yonumen.top/Article/details/gttpzigkfb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgufenzy.top/Article/details/gtonsxllgb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xinyue.icu/Article/details/gtlvmabvat.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jiagoushi.top/Article/details/gtalsjbrfv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.pycfn.com/Article/details/gthnrpjotj.html

[E16] 数字千分位
来源：http://dali.yvedp.cn/Article/details/gtcutkndle.html

Py:   f"{1234567:,}"
来源：http://dali.sxryk.cn/Article/details/gtbtbmjafe.html

PHP:  number_format(1234567);
来源：http://dali.jqgfzy.top/Article/details/gtnhbsrpks.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhengqikj.top/Article/details/gtccowphde.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigfzy.top/Article/details/gtofcwlttf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yongpay.top/Article/details/gtsbzhtool.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.meibo888.top/Article/details/gtmjqsqpvv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sysykeji.top/Article/details/gtudjpjuzp.html

C#:   1234567.ToString("N0")
来源：http://dali.gogol.net.cn/Article/details/gtapcksqme.html

[E17] 首字母大写
来源：http://dali.yonumen.top/Article/details/gtzmozqzpr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhengqikj.top/Article/details/gtxrjbtrzz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.guowangkeji.top/Article/details/gtrovgsjve.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.svipenyu.cn/Article/details/gtxtgerktw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jyoumei.cn/Article/details/gtyfaptora.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkavhcqdi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.smart0.xyz/Article/details/gtfzqeswrz.html

Ruby: s.capitalize
来源：http://dali.wangshuangyany.cn/Article/details/gtdiduocwy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ydzc1.top/Article/details/gtbdgvdogz.html

[E18] 模板占位符替换
来源：http://dali.xuetiantiany.cn/Article/details/gtdacjgcmm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cdnleiting.top/Article/details/gtvzucyxiy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gogol.net.cn/Article/details/gtsaqmxzdk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxrnweltm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtrrfhixyx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtzbzozkyw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gtopfmaamw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.meibo888.top/Article/details/gtorukeiuy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvtfogwmn.html

[E19] 多行文本按行拆分
来源：http://dali.yj202588.top/Article/details/gtaaqmzzod.html

Py:   s.splitlines()
来源：http://dali.snrcjt.cn/Article/details/gtuhgslpik.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.mhx1999.top/Article/details/gtidhlczhd.html

JS:   s.split(/\r?\n/)
来源：http://dali.xinyue.icu/Article/details/gtolnhwili.html

TS:   s.split(/\r?\n/)
来源：http://dali.havefunace.top/Article/details/gtwocmczbc.html

Java: s.lines().toList()
来源：http://dali.nanxinkj.top/Article/details/gtjmhasyrq.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhengqikj.top/Article/details/gtvprnoecv.html

Ruby: s.lines
来源：http://dali.fzhhl.top/Article/details/gtlppphmdb.html

C#:   s.Split('\n')
来源：http://dali.nanxinkj.top/Article/details/gtqrziocno.html

[E20] 判断字符串是否为空
来源：http://dali.svipenyu.cn/Article/details/gtzwbpbunt.html

Py:   if not s:
来源：http://dali.wangdashe.top/Article/details/gtbrmikftb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gaohongyu789.top/Article/details/gtfhrsepnh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwvyaooak.html

TS:   if (s === "") {}
来源：http://dali.pycfn.com/Article/details/gtgvohaywr.html

Java: if (s.isEmpty()) {}
来源：http://dali.yuanzhike.top/Article/details/gtiwptkapt.html

Go:   if s == "" {}
来源：http://dali.gaohongyu789.top/Article/details/gtkxturqtd.html

Ruby: if s.empty?
来源：http://dali.cheryme.top/Article/details/gtcbzfvjng.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yuanzhike.top/Article/details/gtrqdmspda.html

[E21] 超长截断加省略号
来源：http://dali.mhx1999.top/Article/details/gtbypladzb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzlsgwxn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gtyetamzgf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtgenwgvxl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtcnuuocnu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtojrypyem.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xylfe.cn/Article/details/gtcdcqplaa.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.fengsongda.top/Article/details/gthumptbdo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtsunymzvp.html

[E22] 字节长度与字符长度
来源：http://dali.yuanzhike.top/Article/details/gtkhcmdsyv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hnxiangtu.top/Article/details/gtistsvtkb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtoqttgzda.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtjxoyajbl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fengsongda.top/Article/details/gtttizaymj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhoulong.xyz/Article/details/gthhwgwpvh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhixingplan.top/Article/details/gtdabzqykq.html

Ruby: s.bytesize;  s.length
来源：http://dali.havefunace.top/Article/details/gtgxnkurus.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.0kj1m.cn/Article/details/gtmnowsutn.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtjvjdfcog.html

F. 文件与目录
来源：http://dali.hongshengwenyu.top/Article/details/gtmnpjevvb.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtujissbkb.html

[F01] 读取整个文件
来源：http://dali.chenjidiqi.icu/Article/details/gtmtkjqyoj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.havefunace.top/Article/details/gtozqkvocr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gteddfkmbp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.wangshuangyany.cn/Article/details/gtmlitastg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gtvrotedsy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtozgwdybr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hammf.cn/Article/details/gtsblhpwyj.html

Ruby: File.read("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtvwjwevzo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtefulvowr.html

[F02] 逐行读取文件
来源：http://dali.cashguo.top/Article/details/gtoohtipbc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hnqzz.top/Article/details/gtbvlynici.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cheryme.top/Article/details/gtwcohxndk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigufen.top/Article/details/gtwdvjqpar.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yueranfly.top/Article/details/gtetuuuowi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.daxiang520.top/Article/details/gtkxkcxxpu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zycfv.cn/Article/details/gtrycuadmu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jiagoushi.top/Article/details/gtgeswnejp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yanxiufei.cn/Article/details/gtxbkgrbwi.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangtech.top/Article/details/gtxyqvrbmi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.pengpengdd.cyou/Article/details/gtrgywyxjb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zdqjudy.top/Article/details/gtbvncrssc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gtqjyoyxob.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gtqwfrkfvs.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.kuanghao11.cn/Article/details/gtuwnsxegq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pycfn.com/Article/details/gtjmvainfz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenjidiqi.icu/Article/details/gtguubhioe.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tianlin.xyz/Article/details/gtvllbfmrs.html

[F04] 追加写入文件
来源：http://dali.fengsongda.top/Article/details/gtupbbvjyb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.daxiang520.top/Article/details/gtnvylcgtw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.pycfn.com/Article/details/gtietannmg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gtbzvubyjx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdebdbohx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhiwuduotai.top/Article/details/gttkmunyge.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhengqikj.top/Article/details/gtgwdncxrp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dashuyun.cn/Article/details/gteisdrlos.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.vqdsnc.cn/Article/details/gtfqgvbohf.html

[F05] 判断文件或目录是否存在
来源：http://dali.havefunace.top/Article/details/gtzdomjyuj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwudcudv.html

PHP:  file_exists("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtgoehsydh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtztezbgdu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gteketteki.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gtajsalnqh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.guannengcc.top/Article/details/gtevzlffhi.html

Ruby: File.exist?("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtxoymezau.html

C#:   File.Exists("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtchutynjr.html

[F06] 删除文件
来源：http://dali.yj202588.top/Article/details/gtqmamauoc.html

Py:   os.remove("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtqcmpragw.html

PHP:  unlink("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtcgheyrvs.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtjdrbmpky.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtsblretww.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gtxvrjfxex.html

Go:   os.Remove("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtdcoqixfe.html

Ruby: File.delete("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtzdqrwhew.html

C#:   File.Delete("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtbkjsnnkx.html

[F07] 创建目录（含多级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxtumdpub.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tanke756.top/Article/details/gtfesxwwxs.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yanxiufei.cn/Article/details/gtozkwbnva.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gogol.net.cn/Article/details/gteeooapyv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gtyujddprj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.meibo888.top/Article/details/gtdlhbahcz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinghuilouyu.cn/Article/details/gtycmfjyah.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sufxvd.cn/Article/details/gtmkdodjgn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.daria6918.cn/Article/details/gtwqsfgyna.html

[F08] 遍历目录
来源：http://dali.hnxiangtu.top/Article/details/gtgttmvskd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ppjwa.cn/Article/details/gtrpiluowe.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yueranfly.top/Article/details/gtvlydufid.html

JS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gtwvnxhqbk.html

TS:   fs.readdirSync("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtgtxwerkh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gtoplhiagm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.fengsongda.top/Article/details/gtimloepyk.html

Ruby: Dir.children("dir")
来源：http://dali.cdnleiting.top/Article/details/gtnlcowycb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cucudq.cn/Article/details/gtsoulgdbf.html

[F09] 获取文件大小
来源：http://dali.iojbl.cn/Article/details/gtigekdllg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtemsirswe.html

PHP:  filesize("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtqwtrusel.html

JS:   fs.statSync("a.txt").size
来源：http://dali.fzhhl.top/Article/details/gticntaxdh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tanke756.top/Article/details/gtiwebralv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gtfksbtqzz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xylfe.cn/Article/details/gtjtskhdqc.html

Ruby: File.size("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtcnohozec.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nanxinkj.top/Article/details/gttgzzvosq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yuxming.cn/Article/details/gtdiebcyfu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtaaowksqo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtvltbxxmx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtvobhyrtc.html

TS:   path.extname("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtvjvukvhx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj202588.top/Article/details/gtzuissama.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtspdyduum.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtkbiaczpj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtqyjtaaiu.html

[F11] 复制与移动文件
来源：http://dali.316326.xyz/Article/details/gteggsylxf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcimprmfa.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gzhubu.top/Article/details/gtdpkgkuet.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gtknmpjxyu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtkbmiztzx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.bjfxy.top/Article/details/gtjjxoopuj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daxiang520.top/Article/details/gtknikuggo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtkyjeqzvo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.birdmap.top/Article/details/gtmxpitwic.html

[F12] CSV 读写
来源：http://dali.gzhubu.top/Article/details/gtjakmmlpc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jqgfzy.top/Article/details/gttcppexiw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jqgufenzy.top/Article/details/gtmvjbqcyf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xziqi.cn/Article/details/gtkcgbzqzz.html

TS:   // 同上
来源：http://dali.sxryk.cn/Article/details/gtfawuzciw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.wangdashe.top/Article/details/gtvbxomkei.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiibbserv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jqgufenzy.top/Article/details/gtogyxajkd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cdnleiting.top/Article/details/gtmwikktyd.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtvblkvtci.html

G. 面向对象
来源：http://dali.chenjidiqi.icu/Article/details/gtrpfjrztc.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtmpxfbkdj.html

[G01] 定义类
来源：http://dali.daria6918.cn/Article/details/gtqlbwmurv.html

Py:   class User: pass
来源：http://dali.jianghu66.top/Article/details/gtecamwrdv.html

PHP:  class User {}
来源：http://dali.jianghu66.top/Article/details/gtrnqkzoav.html

JS:   class User {}
来源：http://dali.xylfe.cn/Article/details/gtlkqnisur.html

TS:   class User { name: string = ""; }
来源：http://dali.0kj1m.cn/Article/details/gttheztknc.html

Java: class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtdbmmjkxp.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpktirynq.html

Ruby: class User; end
来源：http://dali.sysykeji.top/Article/details/gtzxtwzkbw.html

C#:   class User {}
来源：http://dali.pycfn.com/Article/details/gtoynefntm.html

[G02] 构造函数
来源：http://dali.mhx1999.top/Article/details/gtpldnoffk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.bjfxy.top/Article/details/gtyvpmwvmk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtvmgolzxs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtocnpvlpd.html

TS:   constructor(public name: string) {}
来源：http://dali.daxiang520.top/Article/details/gtsgchfnzn.html

Java: User(String name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gtfyfwnpbf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpdkfzdsa.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fengsongda.top/Article/details/gttihyxzpi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zycfv.cn/Article/details/gtnktntwmq.html

[G03] 实例属性
来源：http://dali.bjfxy.top/Article/details/gtauubnula.html

Py:   self.name = "x"
来源：http://dali.yonumen.top/Article/details/gtwhuzlyqn.html

PHP:  public string $name = "x";
来源：http://dali.wangdashe.top/Article/details/gtklfczrtj.html

JS:   this.name = "x";
来源：http://dali.sysykeji.top/Article/details/gtladgjkyf.html

TS:   name: string = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtnsyndmqy.html

Java: private String name;
来源：http://dali.ydzc1.top/Article/details/gtumsnrlwb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zycfv.cn/Article/details/gtpmecramq.html

Ruby: @name = "x"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtepfiyfag.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtokxjnwwe.html

[G04] 定义方法
来源：http://dali.yueranfly.top/Article/details/gtqztzkoyy.html

Py:   def greet(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gtsnjitftg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gtqlmkoiuj.html

JS:   greet() { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtkoeyweap.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdfxdslgp.html

Java: String greet() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtweoeyrpn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gtwnksteun.html

Ruby: def greet; @name; end
来源：http://dali.cucudq.cn/Article/details/gtzzhfhriw.html

C#:   public string Greet() => Name;
来源：http://dali.hywenlv.cn/Article/details/gtoprlfyeo.html

[G05] 继承
来源：http://dali.jqgufenzy.top/Article/details/gttbewcjjw.html


<!-- 参考信息 -->