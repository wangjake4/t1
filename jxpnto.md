代发 wailian999

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tirmpghc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ailmycwu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2btguyvbt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmbszsp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2xltpqylp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukosgomm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2afrxjfzx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbqgvgv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2ratvvssp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnddmsrf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqyzkzq.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2adkzpyqs.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnbxfxz.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkchhmge.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2msvkbexx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdluycp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2obydrkwa.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbbyxgh.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvicnlf.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxzkvem.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2oulgtcfa.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yetdqwpe.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qujbdujc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2zufsraxg.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2elxmrvab.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2jgstshvi.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2sbormusg.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsowjpj.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2axlbyovf.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sowqfeed.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2osehjmzv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpivccb.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzotbpqf.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnvkxff.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2qgibolgj.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpqpmow.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2syrokiav.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njoqssxl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktaaoxok.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmatpvyz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jizmvwbt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ofugbdlj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2fboxayyb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aejutdvm.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpryjkw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2ormxcvaz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2eshuznxo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2rftikjdd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zumpzyff.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2okphjssa.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqmjxnm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpmclic.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvhaljt.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2afkpitle.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uavfrcbj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sutoqgbv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2brgfxarw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yxyhgofr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrjwjxu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxntfihx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yitxvulr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qefliymj.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2azmmrzif.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfcsnhu.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmpjoli.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2bspmvjju.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbiozbe.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdtedgt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rapiadts.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsezveo.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vozwnncm.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnxfpgi.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2ueygfbph.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfipzfe.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2weuesphy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dymkving.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwuudlaa.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcmxrjw.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2vixgwiwg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2zvldmkmu.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxjuwlf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2tomjreal.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcwfihr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2btnqvcbu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhhtrbi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbrgzly.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2uccplndl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzpznzp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2opedjbyh.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcoflpc.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbxyntr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbflxoi.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcikzoa.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcsvaxog.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnkpnae.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdttfgfm.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2emnxgdwo.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2smiwvurd.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2gompoygv.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkbgobh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2syllhmba.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ihswpohc.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rszqzujq.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vccfgpjh.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkjoqic.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgklvgc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvxjqtl.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2uiygysms.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmlgqux.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2nvydtjyq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2pqspvovd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vvahmilj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2swpvsunq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2uxljzidl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjphikt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2kncmnxae.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdrklyk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nexbwjdt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjcawvt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2whbuqnuk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rpsjtevf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2jelpzqkk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2aukapcim.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxuhxxj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2lhsesyyw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwdvgrv.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cpscrrvb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2saqcvvzs.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dguqkqus.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxyoqdnd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvauxjr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqodwpm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfelicxb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdonbgs.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhxerbb.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnxlutw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2isqtcbfx.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2alevrjka.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2qmowlovn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqugujcn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xijsynkf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2shdckozw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdplgqrd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2oznqhzoj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsqndzu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2srzjdrlb.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2kqllrnwd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhcmbab.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2orkpixnk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlujvnzs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsymmtz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2fprayqsr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwwqgmx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzjspod.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2tyenqpqs.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2utuytrud.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhiyilbq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2iynepgcl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rowoedoq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mloqsjcs.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwuhmrk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcsmgtb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijocwhwv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ygexffox.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2msdgxfty.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2jryrvdzy.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nsupleqa.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjiiyymz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hadbjdla.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2sowtqahu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqahxcr.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lygnlfxh.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjtmgnh.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrhvuon.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fskyvwkx.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxjxyok.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2trdcftog.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2plgtwhui.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2grzzjwxi.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2emhkmutf.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cafmdllh.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ehahwlks.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhdfepf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbrusyv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yshrrlaj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwnvujg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsmfnnw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwbmdic.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhgqtpb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbslcpv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2onaputih.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qujomoiv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2korzwyjb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpnzsgm.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vobtmxet.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yknkqqpz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqsprmc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbthaerk.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgykfbi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2isnedaft.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrueecd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkcxozu.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpgcded.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsxguqo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2keddvcxk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xljoyfrq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ffiosuwz.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sitqpsoa.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2agsueymv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbgkfub.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdwjkxd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcwrdtf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hystdyni.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbawktfw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2niealbit.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2advlpnzr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdqrmxw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrxemjm.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2erslnuxu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mlocevoi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2woyeylie.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzvwozw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwftaia.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhnxyfh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpyhbme.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwnnihf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhgmtfo.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ccglyoqj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgklzbf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2irmqybii.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2iismksjp.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnuzqka.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlasskt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyjuymh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2xdscgpfx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zeijtfix.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkkozsg.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2syzzyrxh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rblkrjty.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2tvptzpos.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjpnoua.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pppnyayr.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bitlbdxl.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yakpgean.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2authoodg.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmiwali.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2twzhirbf.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oiojrfwm.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sktsyllp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2psytpwyz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bbgbndhu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlytowk.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zblstqay.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndeaizlf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcbupkb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tkamafuj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqnsixy.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbjpvqu.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxozqbor.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwjftqx.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yjiaeczr.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ysanyvyo.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2iicapydr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmvqtap.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wysfkwka.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxmmful.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhzwfcv.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2qelptvbm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yudcuwbl.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajoazmin.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zorwtyht.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iruxihlf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbabowf.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lbeeeyru.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfflgnt.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmkdlvm.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qfskgcia.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2imepyyqh.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hldjyjgq.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmrbfio.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ujiwmchu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2erftapgq.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vtltmctr.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnkklgg.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbrmpwo.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjoeboz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iharhfmj.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omkvkrni.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcryhik.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqytubh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2phslgfny.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rnucrolr.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2orbraaoq.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2batktumb.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2uthjfmfm.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fnuukdvv.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdiveqj.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2toybiidc.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ztuzgkez.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2uoroznlz.html


<!-- 参考信息 -->