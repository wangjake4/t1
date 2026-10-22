代发 wailian999

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2djfudzci.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cufjlaqn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxzogrs.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxybipyf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjmgcol.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxyfdzr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwetwqc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmgukjy.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2uueglgla.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2swbjqwuq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qokpkfna.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkdtwhr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqzippn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzfoefg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2zhsdjibl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2snwlvmfa.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfjjdbw.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlegzzs.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2asbyzupe.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhnvaet.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdpgnki.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfdpwwl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2vjaqrmce.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtpnfbr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgapsssm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2estriltg.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnxaljl.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzvynla.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2szexlykd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkvhllg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvsepqbp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2aryyzumf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmsimve.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2zajscjvn.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2anhdhchi.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvljozx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2avgfkyci.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2preqrhwf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcweovmq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqfsddc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqeaqmo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2umiodnhe.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2okdoehmp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2dupkkjpq.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2snblwfab.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2arkxrnov.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzzgrgn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufalxkfb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xynjuhnr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkzkqwt.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxylkxv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xliiwejb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yfyevpkf.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhmugng.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqqxtzv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hokblklc.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxwuhqm.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzovtqiq.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ygleymqc.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2clpoabil.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2casdixqk.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2omxpxwta.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2xyuuujrd.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2jpudmmkm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhxxtwi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2swsfjezr.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmlwowd.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pevjmcur.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eomyjohq.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2xujjueic.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qoguhlmj.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbhvtoo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlpbcmj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhsemdb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2liudtdtn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2pezexghl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qzapsntp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2wuupzoiy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vokuwizb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2idzeswcg.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tclwgvrw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldposdtc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsbeiko.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2eowxzfdh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ebomplgq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2icofwdza.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbouhvz.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhfpykb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2gcoybvrb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qkodroru.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2whrfqqke.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxheqta.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ejznqmek.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnixmmv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhtvrhp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtgcrcy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2reppofgz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kesaojae.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2awankbgy.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2puxunebi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2prwnckwo.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kluxdfdr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfljimw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glbpjshv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdbkihl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnudmor.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmavouh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2shjnghix.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2hktioemp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgahdjc.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlmphcu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjdrozl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfynuus.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjdvkrd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpypmxju.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2jitgsccf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2aneyccsq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2lytateqb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvorcrh.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfxxlyi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsbkuaf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2rljhigsq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfjyjcp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogykxvmr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbsrilz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmybhvb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsweafji.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfbiukh.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2biywxpvo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjoloho.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fhafoyns.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsladcgs.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzbqytk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mehrdtls.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydaauzmb.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfpazsh.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtyctei.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gajcprbn.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2picrkryn.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jnroaowz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrvmmrv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtsgyvi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2upmpdpho.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bszmegsi.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ysyifsuq.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqogygw.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2svvgcyfk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwaitbat.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpspmum.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2cjaaftnr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxvhhjz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ulthhbii.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnjbems.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2zliabzln.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2eucdtpab.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwcqgro.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ametjtay.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqmmshz.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmnfxvv.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zynnuitz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqejnfp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsyhrje.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2futafhta.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvyweum.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhotijs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yukuylpf.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdyvpib.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2szczezkp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjbwzlh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vayqtyir.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhzrpaf.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwankzt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbqndfk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2mxftrhhf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwfilpq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qazbxojd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytssujuc.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rsuerxsj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2dwriojno.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhjgslh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrnosje.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjezwdel.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfzqmgo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikioljif.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqftdsw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2benyilwz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfwabzu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzaeptfb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvifuzy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2viuqjpyn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mczelyqv.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2uninvjum.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkccqdh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfrbcaz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qddrthea.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2jazhbvxz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2akhlhaoy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpltvcu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2plqfoloq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtzcagm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kchnxlst.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2faugcyau.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kitpyrjv.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2kupjacok.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2osbzdidl.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhamlvs.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmpuhfr.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqidauqc.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxxfwmk.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtzbdhb.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2acnnfzbv.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2laybpejj.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfuajfi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2vafdnzjx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxcvzvj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxgylmp.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrkkkvd.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2opudlzjf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2llhourcl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrmaaln.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2deqzsqfe.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwbsfyq.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2iulktqji.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rtoipzel.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kcolqpzy.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyrpvjz.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkdpmpo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2coijpslh.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2twuptivi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2poskrnxv.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wadbmynm.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2igboqtpb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkltftx.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqjmcwd.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pflkxscv.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hareloth.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2khamadmr.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xhshdkjf.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkywnjo.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2qvabzbnv.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rgummbjb.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdyoubj.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwgehif.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkqbfdl.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2quirlbje.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2kmogutzb.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkrktky.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kadljugi.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dltjvrvb.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2zbetuixn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zooxsadn.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgksogzr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okcudves.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sejxrteb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2tjplnfcu.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xdixiqpj.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2hsizmxke.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2swjgpxch.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjsakzo.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zqycvkfw.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2htjvbmbu.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxyfizg.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bcoiysac.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjavzge.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrzkpzg.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pbaafbuf.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xzunashq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2mtltaupu.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdnrcag.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lblsexse.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vshhguos.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mddbvcet.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfeklra.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bhewpqop.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jydiwirk.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2cglgrikt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2tdytxucy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrerfpni.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2riwpzpzg.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdbysez.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjziqzu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrixvwq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqtjpxt.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukokvtsi.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2cofqrjht.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlvporo.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmgmhft.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdjulzb.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cycxkjts.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2gspbtihq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdqtxue.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzdsnwj.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgygxbe.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2sbncypjw.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jvropode.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atxgqdfv.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjfozyi.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxotxvrd.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwztrpkw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2snwsfkjf.html


<!-- 参考信息 -->