代发 wailian999

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2klkgssap.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2idlzwkbs.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zebjkjou.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgozytk.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwudbzh.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgysivew.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2wamkglda.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2onvcthbw.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqndlkx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmftobv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmsdolz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfzdtmu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdfpbqq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bmydhuvc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqxjdui.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2niqxfvak.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2oqowqfki.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2oertwkkb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yseezjwz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2dudvhxbx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbzdbaz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuylfgqr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2kykkbapk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdasxwl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzuqkrjs.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmovqbf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcygitxe.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwxnsza.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwhvsjg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mouzwnkv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhkvxbq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvmkoga.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrvxhokt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpklryx.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcofhkr.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kishhvkd.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtncwsig.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlegupdm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmagozo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvrbwnm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgqwdpt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqsqput.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zavmzzqj.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbqfluh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2enjfnxli.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2etzkircy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkcmodfk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bryysudo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyecnazz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2locawoou.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2ampnaqjr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2sjojlqjs.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jyglfvun.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2modalxtj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2aybcqkzu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbgtxbo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcgltcv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gejufweu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulekbvxx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ekviebbz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jnddnqza.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpiumub.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2ajezqmwh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nizzobye.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvrhxez.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2totjwkpa.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gptoysnb.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2lscacxxc.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlzxnil.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2jksxskrf.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2tthhptnm.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfmwuqk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcedgyo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2isfkllam.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2whzbklzu.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kycrnlkg.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnnljbs.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbefqax.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2biosgcqy.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpezirm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtfrgud.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2qjiebhag.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2khhfkykt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2zbomdtey.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpbhiux.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbmtptc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtzanlg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbgpgxd.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lghvqlhw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kogiahkp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2qblzlfpj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwpekra.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2phlgqrfx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsciangp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmebbka.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2anvxxrpu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2nfioxeaf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lepbodbw.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkkxmrb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eklbxvvi.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2thzoxtln.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2benjfzot.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxgjpne.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2wobmqtfs.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxodgszr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqxzeor.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2hkyvbqnz.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhaqwmxk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbummjm.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tiokbmfr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvjonkc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziemgekj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdmvczy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2savtwudf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxvsnpi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2iltotads.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrkezro.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbrvvdx.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcnlxxy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2bujmyqph.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2skigbzbv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2erxdfasu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2antphyzj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2szoawhub.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgshpxzk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2taiqeubq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zzouhvzo.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2phltjfmg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjouewdx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2degomeas.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmsfmvd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbdxzen.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfexpxof.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2aapvhpfj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdajcatw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtnggeg.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jpagosxi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2jitymghw.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgaflfd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgluhjn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtrnyjd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2llpgbdcr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqtgfkd.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2coihcjkm.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpsvuqo.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjuinmq.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dyatfwcy.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpdxtxk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zapkjfkh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ouidbdjx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmiknrc.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpftxme.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnerbfkl.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkpzqel.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdwmdzz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbamoycu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzeofswu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2aumkqeow.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2apevcccw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjbgmgx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2wedbnwso.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2putdzmdh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpxxxuz.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcvphjn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhshcrpq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sipbruki.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bksljypy.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2trilqdcy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqirxbuj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzouafm.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbykpech.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2resiyekp.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ufaxxwig.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cldrhrvq.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwgsvgj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2alhggrwt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjewotn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eklfnavs.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvevqkyz.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pprmtnfz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2yoldmrwn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2figesekq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdeckxhc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2siyawzdt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2idkscixv.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwwzzrp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2rcawqsre.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhahzusj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2azflgkil.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfrfskb.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwpsybk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2livknvpl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ksakqhzt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmptvzsm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtbamnf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqduesk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2amhcxjgx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpezsrr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2beluvypf.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgacjdo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntacsgcy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2iprlnknf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmqfiil.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvshhny.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpuvpfe.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nxywtsla.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjovmiw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2umbeaeoo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jixjvcib.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbvqukq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmaisqu.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2snazkxox.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpahpll.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jidjqxkc.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjrecjz.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vatczljg.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvqnakz.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbvjfqy.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2slosvdre.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2blqswyct.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2flbudmnt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2biidfobo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oawhxtkt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqroxngc.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2orpnygel.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjnxxkd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxciwvuf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxzpohp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2doqclrbh.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyfnvwm.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqabizt.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwvxecz.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rtaqpqji.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdlzoex.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ludiyvqd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jaselyvl.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2bajghgyz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rikjwema.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrsklrm.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2hliqrbie.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wevfenlz.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlywxxjl.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvreexke.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsivycsj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaekjjup.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kunsgivh.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2opzgcukr.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2cboeehsd.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwnufnm.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xpuuovlx.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwpqnfl.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkoijbr.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tubzeugv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfzifxf.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxxhcux.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfhyokm.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfifoeb.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2jsiwyfov.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whrszmct.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsqfuwl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkfqttc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2osdiduhf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkesubu.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhofruy.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtzxljq.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2usuwzjxp.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2xslubwut.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpkvyav.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vgaemael.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2atyxawrm.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uasfgudo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fzykhbcd.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwemsvs.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hticyoas.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dujdpmmi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ijytnvkk.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxbkkte.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2azfnzaaa.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2asxmhalm.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fhohkdmg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2dwruojhj.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxsafwp.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcbtede.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwozjsj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwkjqkj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qknvpoza.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2ezffxxop.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahuzepvz.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iycxdafg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgewtbg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2acteuluc.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2clhkiify.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2aexwokwx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2esgnhkzi.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cinhqgvz.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnpjmrd.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2odyulwik.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzxzonw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2uuiuoles.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2egskudjz.html


<!-- 参考信息 -->