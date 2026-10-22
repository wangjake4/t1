代发 wailian999

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhslsbte.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2rihrldod.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqhlqzi.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2noqokzth.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2wucqcxrl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2agybxdou.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hzttxsnk.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukanpwsg.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2roorgzpd.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2dojlmkzy.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmzzkbs.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2garsiboc.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdrkflh.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrsuism.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnrpuil.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2exncfsrs.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oceeorby.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfvyare.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxwaxoz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhblcoxo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2scvqdfuy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqabsjqd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzbvbbr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2gykmbnua.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2fnorwszj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhigzyii.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovaccnwc.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcikdfk.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpoohamw.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2fykuoiwk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2vteelhxm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwiqbfaq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhpjzlo.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eeengjja.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2wasozeiz.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssebiqls.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrmotit.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2okptspnk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2orzhsptd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfobjrq.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2nytibgsr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2hrymlflh.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2ldacrwem.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2jajxarzg.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrozmzc.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmnetqc.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rpemmuwa.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdwhcgf.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2lteuqpss.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhshezjb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2imptsbvv.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbcugud.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpnqywg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzezbjiv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfqyoji.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wczeguib.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkcdyht.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xjljjeiv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkymdhn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2egohders.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2afiigklf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2coomdjzy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjqvfhu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2evooucnp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfthnwl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2slvgcved.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2epoadpax.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzxofux.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrerufb.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbvhust.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gamrrcta.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfymawo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oynbtmnw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxhmvyh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwncfms.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2judqrsfm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uubbbzrn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhntjsmy.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2xblajocd.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tweglavw.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjxbyuo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2apmntzsa.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2aulfrqbo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcuqldc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2porpolct.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtndmqh.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2chegczzz.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2lehlqakd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjnijul.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjyjvzv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhnjrwo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsgsyxy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sffgkwsw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2znmhyejg.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuahczo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfbvkbu.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtjnwhh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpqdnwl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyribow.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqbetqm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmwkroj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2iebxmzim.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvxcdaf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wcecounq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gwptcqyc.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2vivixenx.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzmmbsg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbphhpy.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxtqusl.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvydpzm.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwufpofn.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvbqfza.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfgzqxj.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrtcvjf.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnnrikj.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2urohngae.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2ydilcslv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdntmrv.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2obgsnvvt.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2stwjoath.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpnljwg.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjrechy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjgiyvz.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2lkokxgkb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2jvcfusdd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2nqelaalz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdqvusk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2uljiyfrp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlegixw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqirdar.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2zaniohcf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmqjngx.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjudfpf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eykyenlx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2yddmyllv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jystlalh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vgivqyfi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkulsec.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcnojyg.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ilcazthl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2momznuen.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zywjdifp.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjeodqy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyshbcm.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtyrxqb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2blldhwcm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqiqqcg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2fhriimaq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2huzgttrj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpkdexa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvfgpgj.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpiqvldn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ddylasrj.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qizxdice.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2imudrfrp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uemkfuig.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzvjnul.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlwlgsz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmxctdf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvaairxx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhivlgkw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhabpiof.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyfamta.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2bilnhrac.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ucptqvib.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2shajwuex.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpmkzfn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsimlvf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2eknyzhmr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpmpwgv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vyujzulm.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2upsvvsnd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2umyjqwxs.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2nakbgvtf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwzyeza.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2tclhwsum.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdbozjg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2myqgibsr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2iaozxduv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2uehdyihg.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2umcajgnp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2hvazvkzz.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmrvxfa.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yptrscsn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2icwoqjuz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hozhtflo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2phtvtxdd.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2louwcsmi.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rofmpsar.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xzexuuol.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsivknwr.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sesleoii.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhyxeasz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjoeqfeu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtbloux.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2btetgpcf.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eswbecnd.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cftgckqd.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hghurjwh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwrjgpe.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2slkqvgru.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqhgxmv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2rqylorcy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2trtdlpol.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2uthjsihz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjuwcom.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2dmngobuf.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2pduryudi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vebwbpmx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbfrcsd.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dccnfrdf.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytycznkz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqfnjpm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yglpctzd.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2eobuogri.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgfsaaw.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2nturhali.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2peufjxvi.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2aprhpwkn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmttsyu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2zldtoxgs.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvvlsjo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2sabkkdoe.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rczglybd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2kkthdazx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfeshjc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qegsljpx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnkvqvs.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qychkjso.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhllkwn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2eamliskl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcakgit.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fomumwpx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyrsgro.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbxisvp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qoopekmb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwtfjzo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnbmjta.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2itzsdmbi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aojzpxap.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2xoagdycn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlvlznu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqoozkn.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvcelwk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2pszbfwmg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2eoinfmjx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2chooxytw.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbgkpwc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2zjlhuvaf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dpctprix.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzrdmzg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ltudbgpm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcvuawv.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdfrbsl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2imxpnqwn.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2crxlozlm.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2adurknud.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzauvry.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wngduwbx.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eygmujwt.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqftcni.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2eedyroqn.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rdymqtua.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbopowy.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvdtinl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2nwybrcpm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bevlmocw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpudwpfm.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2thctqjae.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fthbqmry.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2afgnusfi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xetjqsgc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdyzkkp.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jfuazsrx.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2covlwowz.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vogqxkzb.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vvohhvyd.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2npjttegl.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmrxhvk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkqdfsj.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhdrmnl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxjlyvq.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmtmnqe.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvxlgyz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxknpnj.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvbauxn.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eigybscn.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bybmghkq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzpckyt.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aglvpdjh.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyepwuyd.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2pweitlnc.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrqfxbs.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnvrsjh.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rqijpgkl.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwwqsjq.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvmyojc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2eudgllzm.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyjuvdz.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjrvoah.html


<!-- 参考信息 -->