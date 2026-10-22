代发 wailian999

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2usdgpvyv.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlegtgnu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhogzldp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhlmtlj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcktrbv.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxsvfkx.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2humakfgg.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgiszfjn.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2epeurujr.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcmttid.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkqujcp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2crnnptcm.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2wetsvnfa.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2wztpdlto.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmrkdmx.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2kyexyten.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2opbuscoo.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wmndzxbu.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yryvsnba.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2ryazfytu.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2jolfhdrl.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2yemzsolp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2xsntbffj.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cizacefb.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmonbzbk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qytrsvne.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2saesvwkd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdttnbn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvcbfnk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gvezcmvm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxavdqr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwpuzfd.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2tkffuktv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcpgqeu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcitwwe.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2oeljxxrh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwakhiv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcgmahw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2faotyfwe.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2lznbaldh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgqleik.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2uontgtgf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vncgoptg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wblvzjew.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrbyfmp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnepfwg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbpacmh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pblnmaim.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2onixnrip.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvfxweq.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcyzxop.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2upxpxxxp.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgqxqsy.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpflsne.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2xffrgwvr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2gaowcwab.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcmtvfq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgahkxj.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2pomqmvhs.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzfmyvx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2nttwfxkb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxgalki.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pihhuqfl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2atuaikke.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgzhjjl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2tewkpvld.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpajkxb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2pikmutzj.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfnuwgb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdoeqhdo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2epqqornj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2evbjbskq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lohwgvnt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahydwfze.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfklgxl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2crlcrmnx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vdruarnf.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkiptzu.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjobihj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uiscduoo.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2tatwvyuy.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2uszoiihs.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlitmql.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2raktfjmj.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjmrxpq.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2ijseibzs.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2uafehrbc.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2fohvskln.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2emtucuwq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2slbzdfhq.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2axwntwuu.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2loqdyfyf.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2olonpzip.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjggawq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqzqefn.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2cccpjqul.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtqdalh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwkqnux.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqwnyzc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2znyyhftn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2efevfelp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2soddjysg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qshundja.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnnnpcr.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqpmign.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2swtmtagb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhzcuje.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsgygzg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2twnndlvb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzsvjmh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2xjtlekhi.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxzziek.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2sanfcawx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpwtsek.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fqllrhwd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpiyuvq.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2idvcfizb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2cellduwu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqcvxpo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2diquhflv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmmilue.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgutzoo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkigmbm.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2juousmqd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qaceuhai.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yiikqrtc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgvnkyc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlcrjou.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2epgsqzqn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xofcwtwj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnrnfwi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2venwrlia.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsycquqd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhsdxyib.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2eznepczz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2szemwkgy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkcjxnc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2yehysopi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2llnaneuq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdgihcx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2brcrvibl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrunmiqw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrywrnp.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2krqzatzt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqcfgar.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqeucfvh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwodhfs.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvbrdom.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2voyzcqjs.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2shxvexnl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2edcptxgm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2dokojsdn.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zjaimtko.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2tydtbivn.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqwzone.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpyebmm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxesxhat.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmpdyqu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2bysvudzi.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aeifajjw.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zocrzbsu.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbbetmk.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzxwrhf.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bovvhmrl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eywnhipm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pddnnhhj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fubrqeaq.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2brmrbtau.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgzoanu.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkswjvn.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2axtkeeua.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbuwioj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwjmwvz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2tpeuwbln.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2owjwrlnu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2keyzvbwg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2apyxouco.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogozoifc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2hxivnlgy.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2maixfgcd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrptujn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlixwjv.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpyvbay.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzloedx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhlwlvr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2afmovpah.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hexvgwtj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttoavbfw.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdtdefw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iodappob.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bejbnctq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbyqxtx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2zclatvnb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2panluxuj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2loytvktp.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2omjtpfej.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2gsymocls.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2pilubckb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wlalhinq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2adinqmad.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrvemfk.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvluxxci.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2cilehxzw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfcrqdy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xugkjijn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqfaasn.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bzltzevv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjnbxkj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsiuier.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2brgkkahv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybajrukw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2trfmkrmo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrcvmti.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcpyzft.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvludeg.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyxeyei.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgivvory.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2naktmqpq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2yybtwcov.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2oiuokbda.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2lphkbyhw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkebjed.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2jluzrvbg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2eremfriy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkcpoem.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhdmqww.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgircnt.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2nmktpenc.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrtxeum.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hrykinex.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kpowpcxq.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmmakkh.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ikidktsj.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2xppnflqz.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhwjaye.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mywvorel.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhacvlv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2vvviwsbh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2umoscjhp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bowadvzc.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyaikes.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btbbfppu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2esgkijqs.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsfkbni.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kucqnbvr.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuqibmo.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vffujkoi.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkuczwt.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wtocjctb.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgdyuuv.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdwpfjp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2epuadpam.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2msdwsize.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwzxfon.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ctnmflzg.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ukibiuie.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdlknek.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfighnjt.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2disbycuz.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obljkonb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhmbxjg.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdccrpd.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dexqymxa.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2bqccxojw.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ncurpvsc.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgtluuz.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2olnbwdci.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvwbdpl.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kndslwae.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ufasonnj.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjonita.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgwtnrp.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2udvdgigj.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnfzshh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yncmavqt.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlgamey.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lroklain.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkighws.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2lgylmqxd.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvuiqbu.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpfpdyg.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqlqsqf.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2aavfqexn.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmutrqr.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zckpvmyu.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gkaxrzci.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdurbof.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bphckbjv.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2tyseqnqg.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2marvbfjo.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vzadbvst.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzbocqq.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rojhnrlc.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xozmqvqk.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2foholrvt.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmvigja.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2itcalbjq.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lciltqgw.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wcluktcy.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2woronyvm.html


<!-- 参考信息 -->