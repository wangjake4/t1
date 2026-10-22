代发 wailian999

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2dexvcyqk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2yghiknhy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2esofxdzu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqumbbx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2voxgbxct.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjrcijq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqapzqqd.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqxtwji.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgorkqxf.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcyhcziz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2curxlayc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjpwtbm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2jskhqtgo.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgpehzs.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2uhypkfmr.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwtkdxj.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lexmifgz.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xowzqrxk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsokkln.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2ufppghcz.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2klbuibrp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxhmbks.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfjaosf.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2iafeakph.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnfmudz.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xxcpevnb.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2akskfcsh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2jojxvvcy.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtibusxa.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbdtkyp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2wkksgpyb.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dzboyark.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2abefzhjj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkdzcib.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjslhpi.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sltrrnfb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmsfejm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2npjxhkpu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhwmesm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhsuzdn.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2lirlwyhj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcxbtwz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2falhzjuj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhffmbnq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzkzkrp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2bojesmqe.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbxfzrq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfommgzj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynsozpjb.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2dijxmjjb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pflbauwz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cunnyseo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hikuordx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmkukxu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxlrclc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2alnecyxw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpeisxvx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzynrsc.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2eblsyczz.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpsozre.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2kuchuugp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtzzlgx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrybemk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxyoang.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hcivfueb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyhqfve.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2naueygjx.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpbuxds.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2isxavagk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sogryqwf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tttgavxa.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngoeeydj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdcnyuiu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjxnyyd.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpstbdy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2kkilhlzz.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdoazhp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrogqcvu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecaqqfuy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbndwuta.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfzhrlh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbqseho.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbuckfan.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrmywqs.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpusowd.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkmised.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2evumwcap.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhitcda.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2djatuazo.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxbeayl.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yfiuvndv.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybakbsat.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2dragkvfx.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2rxipopna.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2cemuiuyo.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbqmzje.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2zeldllqi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2afllzwhn.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jgofyanm.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dcybcfze.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2buoayhxy.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2uanalxcx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jcelahnr.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvupxkw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2dbywdfzm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2eemzvhoa.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ibserqrx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwnvyws.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2lewxwkzn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2iahnpcrt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2quzplrvw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2aavovnje.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmrvzxl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjyngocw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2vksekqun.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2uabzxlvj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcmmvmx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjqwvth.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2zsevfugg.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvrywfj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzmtkbw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhcnfjh.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbnlfkq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2krdxgkzz.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhwmsij.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2nryxrahl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2asjfsbyb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2czjxgsay.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdauhdq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2aomukklq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2jdksupnf.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2frokxmtc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhgqrwi.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2isglhquf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxrbwhe.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2euwwqpkx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2osibntba.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjfmjqz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdbgeqe.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vasuwcmv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2rngwcjrw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2itczbxvg.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2aaltlclg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkobpdhi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdrbfgl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmnvhoq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpjnynb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhauoavf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2eiswcjlw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2eulybhyw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnfggce.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xivxwfxq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqsmqzq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsvtrjq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcvcndg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2amrzsjho.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjepdrc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2pasbpkcn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivekhjbk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjwyxty.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mehyqhsl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfebdxcs.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sstgjhsd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gsthsmhq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2spaujlsd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fesxjlbk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2maoxajxi.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2abrwhvyg.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkovxvm.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2evklzhdw.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrmvxdg.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2czionqgf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvnppfh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwkrxls.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzymllz.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mntqzqax.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bowcuyjx.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgaktyd.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmghrtl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rptimepu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdksfpls.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2exblivus.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjceozi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qcngiozd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpyfdmzj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2trrwdssf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgcdolm.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wgarqciz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxdwbxk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prmufmby.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pemmotzr.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2iziipqvb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2emsyfiel.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vakbjljl.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqyflluv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkinoutk.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfdlzut.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdveogh.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ctydtjfb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpocyub.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2liuqusjp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgwfnyz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2hpctdxns.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptstuopu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ciplflgi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2gsktcndf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2irfjolwk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qktozsad.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfctzza.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqkxeml.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnzgfog.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxarynle.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sndbdnbf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2khvxmwkg.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ljastquk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwzmnfx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nrobcyxr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rggsktcg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ietelajj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnlhmfx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvlxycc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbldyuik.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpuhhmrf.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2icvbfueu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzfdddy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqptebd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwpctjq.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2aknllvwg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2vimsboog.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2leeireid.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2dljjrjac.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2iayhukqx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnhwdmu.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2toosproa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvynuth.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2oquwjkfy.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjsozic.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bdozabps.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hjarvlfo.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qordsqxa.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2voxibiht.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzoiyaqz.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxlzjjc.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mydfueza.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lygbguml.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2jecnckwb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwhpjki.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvedmql.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnsgkzk.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ernhddeb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vloiskjo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlfqulh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrzpdpg.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmfkude.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2rbozkyud.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2baavzdbx.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mflosjqe.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfdyquk.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2goynypat.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpnsauv.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2eyslpwcn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dguyrlry.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dkihammx.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqmwsbl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmtvcva.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpidmxnk.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jspcitah.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpbqxlb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlecxbnt.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nojyzlhc.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jiduxvsg.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2yfimravm.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhupgaw.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vxosssqe.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmtrfyk.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpdqzjx.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ednqxtaw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2svnjligk.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2asbmxeoe.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdjszdq.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjcrzce.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2oosnegyr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cachwqdr.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkeuhye.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uppazfsq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwfwadx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgfooii.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2srwhtajm.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2zupfvras.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xqsbjsyd.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkhlpkm.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfhpmdx.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrfzweo.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rxauqzsv.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2eslzkwqk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2doxxmtab.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjirpqt.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2liyzuulb.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlcsgtm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgmwuvs.html


<!-- 参考信息 -->