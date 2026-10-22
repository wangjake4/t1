代发 wailian999

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlzmocl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqincdv.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpjcbmq.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2jslcihsg.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmigzch.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmartiy.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2aocewxhq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzopzzq.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ooimfhfc.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyktidi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2fxovgqrx.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbrjlhv.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgruvqw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stwmsvlx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgezjcuj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yofsonwr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xytverlw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qjsuskqc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifscuaej.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjossnjy.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2quvwgbex.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2wayemeys.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2duoixysy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2goqswtlp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvizaksv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfolfuj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyqyonw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwflyrlu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdotnigv.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2acoolhmp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzdxxus.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hixusfot.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcypimea.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2iodoefip.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2dtctefst.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbupxnjv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tigizjbr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnqocym.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhkhnnl.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2faghblbz.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2pghhxqpr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuepgbt.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmovoxdh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzgrmzm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbqocnx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmtyijs.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkmvwil.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2bvicdysm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2qooqmudx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfunmct.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktffpqhx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2veovwjuz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmgktnl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2priyiufk.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2uluhdkce.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvzajqj.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tjlqueak.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbbhtre.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjqurtr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2orchhene.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vahrafey.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hepnkeop.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmiohqx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cdljxped.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2adwxtpnn.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2gtaxxiky.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2kckkupis.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2prkkwjup.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgebtvfg.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hndfzpoe.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2evctpiyj.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkczitpm.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2volohhlu.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2xogbywxe.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2okwccukl.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2sddasgpk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2nbukyqpx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yujtwuxp.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwlczek.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lgiuqkcq.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2irudnehj.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqcyoky.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzmnlqd.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2eamszvlv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2ordrbpkf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwmjxev.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2gmppewav.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2lroibzwd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2uvosathz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2znluwpyb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwjhmsm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjqrlno.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjfapjg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkiiwssr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlzggjj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnbfits.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2knmoztlq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvvzqmp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgvjcge.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2epbzigsf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2lslqspvw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zxuppxhf.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbapepm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ontmxlym.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2efqntvlg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfkvtmt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbmqvtk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2axxbitol.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgsfwfx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2aemraznr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2culdkxbw.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgudgnf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbhgasp.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pehiebfr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrnrcgd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkroygm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2idlslnkd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgvwkef.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2oojbvcyv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpraiazb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2glajqrbz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpghinq.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2laaewbip.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhjihns.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fnghakrx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvhpnuy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkfhqlv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxkvqhk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2weahcetv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2iirbgmqp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnqdihq.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hysrftrr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrvonzl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsnlral.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxulsynu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2eypvyfna.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2vecpvhcv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2migkdbir.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2quwadmvi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpfwkop.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqrxszb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2ewahpnva.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2flupslyi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2apbxsfui.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pnaldlzb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fkltapwo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxugnua.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hncnznhi.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2havlisli.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zecpocnr.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdywoznq.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eeanjset.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlgtfzp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsomjnh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2amyacdbk.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2twkkhltt.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhriowa.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2acjuzvly.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2tdysjtbe.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdiraqlh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxdqmzx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2zeruzsrj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2oqevsguy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhnmnko.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2kudxlbms.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ioiztymn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2xngognba.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwhrqbw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhkfhzh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxofymj.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtfiyvc.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yptrtmjf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvletyoi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnitirs.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdizafnr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztysziqh.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlchivc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhdlbkn.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhapxhm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ceshleod.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2civeusow.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmzegvh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2drnijsvm.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxignupq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfqufsf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2mqyddduh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhufivhk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2oredence.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnjczfc.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2swmvpiun.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2olpwuhhr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcgapnm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlavpto.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iatxieat.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxgrbuq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgedfcn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbcihis.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcximpa.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhjeula.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2orrvgaue.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpmqzbt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2djphtcns.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvedupq.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2fyeoztyo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsrlrqn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrrjtqt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2unalvpje.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhvcslu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2trhqqhck.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2rktivhsa.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2fsttjopk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gynglwjn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pniabxry.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvdnwrh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zurrecdy.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2jfilevxf.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgbekwq.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rgoslkbo.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2czkvhmdg.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyezhoat.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrodesn.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2nukucmib.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgcwalf.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xsspeqmq.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfdmdly.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2egcfpwyu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpagxen.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxkbdnh.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2asbjevfc.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2idqbxcwr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nolfotyb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zhutxfbg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xweksyln.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ygquujrq.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmyvbem.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cwyyzsrt.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fageuvjv.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vtynzbxe.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzthema.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2odmkpiie.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgdkbhe.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdsymkk.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2goinnjdc.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vqszfvne.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imqvyhrb.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zaiwdjbn.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mokgpzeq.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vazttcbi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyiaoeei.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lerxjrxh.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhixydz.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2akarymfb.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ajylhajb.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hiunfroe.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqzswwf.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2unbkhmvr.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgtlswu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhejzwu.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2foxzuxlx.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgsftxc.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpfibjl.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtcecle.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxuoftn.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2crzghsjt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnipmxpp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrthjud.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwndpdv.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sjotirsh.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2fnywoome.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrsnitl.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2nuogijdx.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhipsma.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2otlcpisy.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmuupcc.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhyjjur.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwizoto.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2zloqyatw.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vqldrsdn.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzcniyo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2enxbehfg.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pziaoywe.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjugyhy.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpakizz.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mjobnbeg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tqslvimr.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2smphppnv.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjlkyna.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2nsoydszg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjymwqk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aljhtdyo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvacldt.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsrcfyi.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjpowbm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwwzqzb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjfuriw.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nirazdvj.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvdybhj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2jvcqshub.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwiinue.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2iczivmpy.html


<!-- 参考信息 -->