代发 wailian999

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbdjeec.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrvrnqs.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqrglfj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtjjfaz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2zjllotnx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqlpdtx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmurpmdl.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcxjlyn.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2cinjpofo.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2sncmxvga.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvgyxsf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqnhezu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhhmzbr.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aungvqqz.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqgzkss.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2crykuexf.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fipnwrgg.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycyjmjge.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlpjftu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2fpegwydt.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2lirwzuxw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2aglyfsmu.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2trjbmcwu.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2flqgygya.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2zvyyyank.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzvvrvk.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdqxfri.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2zebuideu.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvaoayk.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2chrrxlay.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2qinztozd.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wiyagmtl.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdsruhd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldyzmvut.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2saqoyark.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbdzilm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jldqncja.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2owqmtosn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvyqdkdo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwovfnij.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2utzxkelp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2adwqwguj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuchxkzl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsyyvaq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dedhgqzl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2dealygkp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2hofdaoch.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdojpdrj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2itrixnki.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2wuuhyspz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kaicammu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnbanef.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eahkbnwv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2frvpepom.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2exyyhreu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtziqem.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwcrhav.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvdoaoi.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2dorkjlpk.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jheydpbq.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwpqdie.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqkqror.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvwlwiu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlgptzi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhichgw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzcjkuh.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zyiigqlv.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2tkewjjsf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkiduglh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkzpexu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvevjksh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dstmeoku.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2khzigavc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2laskscdf.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2faoeedsb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2ryelqoqv.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2meqhfkmm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlruwji.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2smxzsrfo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2khqeytrz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2umttrsfc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzugnkqd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2envgkysv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzjsbzq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2veltqhgx.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzvbveo.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhbnfrd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdovnue.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2sackzmqi.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnujwuy.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jkokwbly.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpysqig.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2xduferds.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2aihvlkla.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2trxgfzzt.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgtsdwq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhcmkxz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2znrghxfv.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fovipypf.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdxpzrb.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwplemg.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqahvce.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ibszggeb.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2rkaelmoe.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpogmlz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2htkpiyif.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2attgfjrs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2txkaevrh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhscijy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2nunsahsr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2olrbjmxt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzjxsqw.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdqwtbl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sifmfgpl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2gykhugof.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tukoiecx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2awjbvgsj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2wugbajhc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2bdifmhup.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnuxope.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2wgddpppg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uslbanxj.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tkepeqbt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2syisnspo.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2slgolcve.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2myfondeb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bzidukst.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2zbsmeicf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwhjurf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgscuai.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrxnwuv.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcdnsec.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2grtxkdgn.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sfazoejg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2ssncasos.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vddasjqt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcthhnr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgsrwyg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqilccfn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtaevjfo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbxjzrp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2peiinduv.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbnjqhf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwwvhox.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2iwngpakm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2oekyiouo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2quibcmzd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsvkmee.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvmizxa.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2spxejtfa.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2afledtlk.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdtcpac.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2viuoxvrp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2ioadmbcl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2oynjiblb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdygxpg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhkdnwi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2npfbkpzr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nleoppad.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2enwsnkeo.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhnyori.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2fazexrps.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwbllip.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfjxvfv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsppkzr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvasgqe.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2naebmozq.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgiwvxng.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfgimhk.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2odwddgqc.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxmulib.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkbxinz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxajloyk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xylxturs.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2sldgdexs.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2apmwlrpi.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kclnduea.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfnzail.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbluvsg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wafccekr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzbjrhc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2wqyteexx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2pejvhmvn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjpgfgb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyrpbgy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2osccxice.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjfcctn.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bmioiqmo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsygipsx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xitzblpq.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwmdixo.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtnbwjn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2xipdskte.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkmmhks.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogovwkjp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2whjdjitz.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2soiqaegc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvyzbgd.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zihwajsh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrsesaw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2tklokqhq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxqmxgb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2eijazegj.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmowudps.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrllknw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2bhaznwtw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyuplua.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2aoussxvv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rendfbnl.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xflnyihj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnqcgvv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfvfhkf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2elfpyxwq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrfbanl.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvznvrr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhpurte.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkogooc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwwbbss.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbffatp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfwgbxk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2vksfwujl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yljuejhf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwzsbbg.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ozckslnt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdfcvsd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2ledebxah.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2wlziqrcf.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2utssdqwc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfuntlh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcfjrum.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2wclamiad.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrirbnl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xcubwlid.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhirzua.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtgdhfh.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2rrizvzow.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwucpih.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvokttl.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdrjbni.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkswkfog.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qvikljan.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbsmdcp.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2comqndix.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oopakuqp.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zhotaexl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmznebu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2knmsaiub.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmhwcbb.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kegrfctm.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvmmtex.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2truffptm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xntqlagt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tozwwhre.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxdglqy.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2kdyvflhk.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhihwpv.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2opyojdng.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yihacrpa.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2aunyvfjg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrxkflq.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2itikivla.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zmehatss.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hwikixlh.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2elbmudza.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acbvjcfe.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqutfmcf.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2admaozzu.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bygqbdbo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndflpksp.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ozslzbkl.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqqgyyx.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2msertyzr.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnzpvqu.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhwgygr.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtxuvyr.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtkknbc.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oqphmhdn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlhlbty.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkwvsnf.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqddzkq.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2garsyypw.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2hwritaqt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzkjzry.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvneonos.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzpujsk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rldfctof.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2vxchzduy.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcvmavh.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2etzjamgq.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2anpwtdwf.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2djavqkvy.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gibqonbo.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdlqoad.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mptqwioq.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlsyhfg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqlgdgc.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2emnozpje.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkkxiuc.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lfuyfbin.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmimblw.html


<!-- 参考信息 -->