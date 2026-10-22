代发 wailian999

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2cltdljjt.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmveaznm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxzhqzs.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgnqhvw.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxacogd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvyahrr.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2agagfeno.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqghwmcm.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkyhrdhi.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubohggjz.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2beovvuwj.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2phigwfxe.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfobagli.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2kegqgqod.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2giakfhtk.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2ustcigik.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwvtqiy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugaaynvy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjefrbc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2chxaztrm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofogppoy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqtvahi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2hazyxpyg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2iamxhifc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2swrbxieb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2yerjiyns.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2dezhvokq.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxzycjv.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmqojyy.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkxtccc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmeylzfm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2lamcxlmv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2iojlyuex.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbncuri.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dangvlqk.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2iimyuvev.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gissljzg.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpejovvk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2eycrwoaj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjqkjwo.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtkvdks.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2bkuypzfk.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2fgisgeij.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqwwiwt.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2isdbgbdc.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgdpwko.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nvemofri.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlaibmc.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2btfmgrly.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2exhkqziz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2lkknhmjf.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cylnqqqb.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxudutrc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtimafef.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvsifds.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vewzihtv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydovqxfm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2esaisxho.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2etoxhznc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqxavjv.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2lbasknth.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2azkpnfqr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yttgbaak.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyoeggp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzmjhjx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpwkakt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2faxboyyc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrfegtu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvoisgdl.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2ypedawzm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbrktsf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mssgebit.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2meubjbys.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qixnpioj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2iuixvtvr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yysbanuv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvvhiwo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmizsrp.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2smaelqid.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrkibfk.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2amwvyhqx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2yatfwujr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmyufkar.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfufitoe.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtdnuzv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2czvznvyf.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbwabou.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvnaecp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2zegchwlm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmqkfxy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2smtjvvcs.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmykgjr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtbylcm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2yafzehvm.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxpzrzd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2enjwewcz.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xcywhysm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwguhmlt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2chdoxpbp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyglrcwz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvegrcjx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2aencgika.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkqqhtr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2riljqyxr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtivdhh.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmmqgwh.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2adofqmgm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmrzvga.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jffkqptc.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmvikoc.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kadnvtch.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2yuicdtei.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrgamqq.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxokcmv.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxlrqjz.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2hofwlvrh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrrytzw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eeayhssr.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2koiewwzl.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2scblnfwo.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2owvbgfml.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjwzuyh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rpawrejw.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2mzekvive.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxqwmot.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2vstrmudh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrglypc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2yzesvovu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2otaelesl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2prcyjehx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wccwdsom.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2swdlizyl.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2enrthjzj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxuodjyz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2zyivtcpt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqokcno.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2krzmdbhe.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqomzrq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2ppepzmlr.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcppaat.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2irknebbt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrfjphh.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2csqnvjix.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbwxfng.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2alnpbkhq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2debaihwb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qbuwrgkw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2ffszncnn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2nblzgedy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ofldxhhx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2owssnyxh.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjiuzjk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2olanbozi.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2clzqeasl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdathxv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2annimwsg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rezksjze.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vztjtqcn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoibvjzu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2arudhacw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkqorit.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kecuudtj.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrgvvvm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2evcmkhwd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2pmiiyczi.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhpwtud.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwuvhev.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2huvkmetm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcvizkd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2luhqkklg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcfeoom.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sasrmivm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2lewmxols.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2tngmdmdo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2evkfnlvu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fefdjsjn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvipqlir.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcolfxa.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgluteu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdtzjsx.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2oohimdpj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2ytthwxig.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2naugzryi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvaperdf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pcigsvxf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrvtozw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqvegoa.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2praffzka.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cljuxlvg.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qivdkxmo.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkuuyksx.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbdzkne.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnipato.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2frivzann.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcxyzxc.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdostmr.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqlnckj.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxootjy.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtfjgtb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtjxdsy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkserru.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ufiultqi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzdpxqd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2frfpixya.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2jopzakti.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkhtyvc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwrznli.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tgviwmiz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzkhhhb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfesfbl.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mlniavpt.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrfpnbo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2teruvzqk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jncmvqfr.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2knbenmcn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2migalafd.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrazbui.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhihotv.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jemkusrx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvoapgb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ujeyseup.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmlbvwq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnpmruu.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hupganzn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlzrvpj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdwfhtq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzqaovr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtdpopw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdwwhjx.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhofrvzc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2dapqnthp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fstbugkk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uiozudbl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2esobkuys.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gpruqnuc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxgfosu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjlbclj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjodncc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmglwkrd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jybrnyap.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjymhus.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2varpjwpg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lclqfedd.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzyajiz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxqkqvx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvjesmq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fyaevvjv.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2qngytafs.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbmqntj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhyeeax.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmvsflg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tanbkzss.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbzqpgl.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wugxmgos.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yakicjiq.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2pugjfnpl.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mqiyqust.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfjovvn.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uslznysk.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbufpcbo.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hvopcpfy.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2pogswpen.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2owzlvwgz.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hoajvsyi.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwessjg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2bpeqibif.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cmntneyv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uysvrkku.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uticmsoo.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2neqjddzj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2atsxbvmn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2trwboose.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdoedkxe.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2msyqdyyi.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ythaqatu.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gyazoaqr.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2czqnlzpf.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rddatxju.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2undbzjhq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2priucmyn.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2iplmfncg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pygawrzt.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfomdnq.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjhwqpo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obydkaue.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfnebrh.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgousvtr.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgypdbs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyxkpic.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2crrvnafj.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnutwngs.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xylvwsjb.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnfborh.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ivygcbpg.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hikbaisa.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bmyktecp.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcezjnq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2hsztplph.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qaocfdgr.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uddkrfcc.html


<!-- 参考信息 -->