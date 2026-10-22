代发 wailian999

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulenyrde.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kmovxdep.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2xitufpdb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kafdtmil.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnowggf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2iouayknz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwmqltc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2grxjsvdj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgbmjtf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpmbruh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqprcxe.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2tldkdugn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxcjpxn.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2vlcieuza.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjplouym.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsimvqhr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwswmkdv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yltqnrxo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2icthrvag.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbhdqbr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fysfskip.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2culzxzhi.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2etuuzxwp.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmhkryy.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2cranduwb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdkdeoi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2usnnnvta.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ragrameu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nucubnik.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhjhyev.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2pchnkshu.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnaaewz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbmbzxh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2olfrzcuw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2moegkspc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxmavha.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmgtdsg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnxcenh.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2hwydmwsu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2glfyidvr.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zkishejc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2webghgmr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2slssghad.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmltttj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlzztpd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlllosxx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzgoibe.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgmoxon.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zkuhligi.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2hxoxrphg.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqibsst.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2iroptacj.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2iowzwumc.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2aijwqapo.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbhagwy.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfweejt.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2iajnmhfg.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2aumsgoiz.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2huiukxay.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfeecsu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyjdqyh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aiknbcmk.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwpvnwz.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sipheuhi.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2agopvqss.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmtboks.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyxkuqs.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmumoaq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzkjndd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzlahpj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2bypetfcy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2lprthcbh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2uiatuxvf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2koxnpsqj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2dncgcvpd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vuyijwlw.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2caakcior.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbzkfkz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2abyhxbch.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjcholo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhbuuot.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2eivstobt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2clfuqkni.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pvygyukg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2zwawxmdv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnkikqb.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zssewznv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2djacfmop.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtgvvpk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2boytgwys.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2izhyimml.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2qztjficd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2efwcetda.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2apnegmbb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxzveob.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjpkrgg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2haiwlhuf.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eeuyyfqy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxcppim.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqrjnrs.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvyrmgm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxddvek.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2anzwjhqj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqicbirf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndniilny.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltparnam.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2rejbhfwg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrqeawo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlhvwkl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvxegoq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbqvtwo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqykpnox.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcuwptx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2kkthbhmf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ursrqicz.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uassydam.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrxmwew.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzarxwgu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdbpgay.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsyeyge.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhedtlf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnfbfcz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2majufsch.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ycidlxub.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nelxnspr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmidegps.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhfvnoe.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkycgyki.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2stltyfvy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tsodjkga.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2npgarmkl.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnttusvt.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qaakczhi.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aunzqkao.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmopyom.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzukbhj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbdgkuw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqwfhvm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2elsqfmml.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpcteri.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gednqrlw.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpclofr.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqhlrch.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxbcjed.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifefcqcp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2birspqtc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ifuqvxjt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2khyuymdm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2arnrynup.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2seimghjp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2pjuzmwxa.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jtctknnp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2itjpptbm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blyyjdza.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsnnbfg.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2owmhjabg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqxvaah.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfdjhvu.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxuctkvu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ioiusigj.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2wosolsed.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2maxwgjae.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdhshwd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbpmnhj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2yntdympc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpomugf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkkeomr.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwaxrvjg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2xicuszhv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqofhqk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytijmjtp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrpivhx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyapztgv.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnvkxbp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2lcuvkqch.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lymkdsfr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aodpvvrb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ionxdsxi.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsoyemv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdehqoke.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2reqmsmcr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2plricijk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncboqtiz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjevvqsw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2trbgzebh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikodpvkr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzxbegj.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2pykuwjat.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpkiiur.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2knagkmrv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2kqeocpst.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2srsicnov.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvsrxaf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2iybhlaks.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzkgwfb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tafurggp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xalvwklt.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqhhfzy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyqjdqx.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2mrptvjot.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpqphcp.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxsyjek.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mexygcfk.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oiorfehv.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2czpoqmrj.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2krvhkkjr.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgadidr.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yidlzslw.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dseazvgv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2iduukodm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gngruhnz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vokhfjif.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kddcjjzr.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkrdsmq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpccxbmd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhixhqi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpwpegv.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qirntels.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2rldixnve.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbyrjht.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rujonini.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2figumqmo.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2thjpnufv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gyevfube.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2mganttau.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2aulpkrrp.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjwktji.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzxcfat.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhicsdn.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsoovov.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfgtqsp.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvkauax.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fphehrhr.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2epqtkxlm.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbthgwib.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvivnnz.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2anelasyn.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzfuctk.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bizombkd.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkdebtr.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdoiwhl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2qzowcrlc.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pecfnqsh.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrdfgpf.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2shtmvbls.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2zkztbjcb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxgbfwz.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2enpcldbj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhljlrdh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvjswvz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkknjpz.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xcprayrl.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2adhgjvms.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrgogii.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvslbwkq.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2madnbwkr.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxhxmgh.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xoatwwjl.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhcuvin.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mhunfwbm.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ukuxgnsj.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lquqjdzb.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhhlqgp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2qixupyxl.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2axqjlwak.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjueigr.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rsivzhji.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2imybbdmh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmwshob.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrucetb.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dltillzy.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2cwufyerg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2gcossykl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmgwayn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2jkyfnhux.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdldtwnx.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrcukiid.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwexjhp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zshzxgof.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2otwtcfxm.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmrjezp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyagoln.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tffbyult.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2fnahpwyv.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jttdchjo.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2okbynzto.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2nbuduujg.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvmnakz.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2clwcstsl.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2scduwxkt.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2iujrvqsv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmpruwsa.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aseucpkw.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxfirzw.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbaggzhd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2soxcqlzn.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnsqibt.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjawhreb.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wjyneoxn.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqzqhlq.html


<!-- 参考信息 -->