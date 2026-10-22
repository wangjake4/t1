代发 wailian999

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zawdpugo.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2pskosbby.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2civwapvw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2palqcnvg.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2yszgixhz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2tegmjvsp.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2emjdvvkt.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2lulfjlnb.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxycppe.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqlxwxo.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcojgzo.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2mulyilok.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2jazsnbfv.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2vusnwnxg.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2loxhelja.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnufees.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntizrhwr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtivbgqm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwaguidk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2errlptia.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqpfduo.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxpmcwy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2qarxklrh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwqnmdp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzhjmas.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywndngsd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2auukhgdq.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2rowqntig.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgxxftp.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtbnkur.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyyhmgts.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2efvybigw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2mktwimmp.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqzrhxe.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2yudrwiji.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhijtdxo.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrdlrxq.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vkoghjlv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2znldokdm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbicnfr.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2lgflcana.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2eisgcpra.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbvtwyf.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2krqstgog.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2oeftvtpc.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2winpbtlt.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmrvlra.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbccwcx.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwswfcv.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2snlmacyo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2crmeemou.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2llhfgdeq.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpupjtu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ordzibly.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjgksnc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwtqvxj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqdipxr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqfyiyx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsyxlvm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajguqxjm.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcbhyig.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkpeuxn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2buytojju.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwurivja.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2txylvdrc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2qazgzlqm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdzfznj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mitlezoh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2phdtfuap.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2glolsdga.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhjwkdv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzqhrgz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfyyvfu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2iedkpjnl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2skvpmxck.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvljvxs.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2akzymlvq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtmotzw.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2hegymzhs.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oaouxysf.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyksock.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2bicatemr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2pozlhxos.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkobcwyr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtquaek.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2knjcvrqm.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2aswuxcwq.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2gwebppfk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhiaoxur.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2okxfuawg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdfnvea.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cczoxbfo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbacsyqh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhjseuz.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2ulszmhqg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlfbweb.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fptuxarv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnqkhwj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2zedyremk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rluovmox.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbphofe.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhiarwql.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyuauzth.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjbsnig.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qexiolwc.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgdxvug.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2paauuwug.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpygzguj.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcebferu.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxapugu.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2adbydqbr.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2oivztops.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvmzwsb.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdzhjko.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2jprfsbze.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2qggrvsct.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2xtykxtek.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnytmcz.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2swlchjaz.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rxboxapd.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2faoavbzp.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkqvyre.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2itsetctt.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgmvqfc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2hywwfjfq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2lotljjos.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxhqyoq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2iaojuuiw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mlackqrw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2cyoiddpr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcjjibg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhdylbe.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2imuabgvv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2waagdtqb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2faxsskpa.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2svjqhahc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ytabyufb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvbqmpe.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2bznvwltb.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tbapvyzh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vljwwrgw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gupnjjoo.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qawlhzoz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pojvtmag.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjkmcxk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwqflpc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kztkljeg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2amymvdfh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2olkxvcqj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkkrrqj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcnryuq.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2namkozob.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yyejticm.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fzafmwhp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzmskeo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aszugfyb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ototgnbh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2prptqrrz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2odmiwyhy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2docchmtt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlmmxmd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmrpaki.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2cibyefvc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2hddshrtb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2sbuuijic.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdsyxnc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjaxjae.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebafwelo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjsvnxg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqjypjm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvgxwoj.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2idllccyn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxbcpoz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlvydrt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzguvua.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvnzvmx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdwxbge.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzjyrce.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2txyspdev.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkmxqpv.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqyahpc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2kstblniu.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqkcziq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmuivkqk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdicflec.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pisciexv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfnskjy.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zikjlkak.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xixtomoj.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nstjbvvs.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccofkuky.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwcluqi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pokuoevz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfeplaat.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gybbaakj.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfrjmjf.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvgtsfc.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2klejwngc.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2fechodwx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmjcskn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrjtkrd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2bntlsxlt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2attrjtbv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mwenvsoy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybywfqhu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2sonddevc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvwmagu.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ekaerlmk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxtjmgm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcurrstn.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjhacrp.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jckzvoju.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkterpf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbwrtkj.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2umbnhttj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2okqimlwb.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnryprz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnipbmon.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmazblx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2stpkvkjf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnxexdg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2plrdwesr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgznxgp.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtogwjmt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vihhrdcm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2hjenbrzl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2krvowvxv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2itbqogsj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2btqbxocr.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xerfngms.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjorxdm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfsxloq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtfqpws.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikblriip.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwracyf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kptonazm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2srwagyac.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rammgypm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqoyddxo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbezldhv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwpgpiu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iomgdiwd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzddstz.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2efcmvywh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2uaziwgcb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2zjujsxvv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cydiykpn.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2njndqvnm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2gczouuzh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcxbpod.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyvoghk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnslkgj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fthdgbwn.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnmnsts.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2unqfbjkn.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2duxcubex.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdxnqha.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfrgqkp.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yiigkiaz.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eklxvdpm.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2djlexwzb.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdunxft.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvycsst.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gfelwiwq.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vextxrkp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2jclxruca.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvobbjt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twhmeapr.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jjswdvnw.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrjkbav.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2onhwnavn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcocrxi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thlxybkc.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ervwzjpf.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxixbqu.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtdtxbi.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxaabwt.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2eijvcbhv.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zinmrtxx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2kcysnomk.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wiassxrd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vourrlqy.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2iaaaycmz.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2evzbyphg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpokslrm.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2syrrnype.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywiykrwt.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeluislb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyytujjw.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2inejknii.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2unfeipsm.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ijadwovu.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2pztgkipq.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrqutei.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vudkwnsd.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mkcwomqt.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxzjzmx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2tzeuunoz.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmvzglq.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dycfsraq.html


<!-- 参考信息 -->