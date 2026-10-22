代发 wailian999

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcevebk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgogkxa.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgjwywv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2temfvouu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sratydjv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcffwitt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbfhqlb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zybxclzk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmyxlmku.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfeummc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbuxbfm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qibupzsy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwedkmb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzfqwpr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzywowq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfhithk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2txlnlyym.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmcrmva.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgaqcim.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dtaczjph.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljukarxe.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkhcpyf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfydeok.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2oznafonl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvekbap.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2yybespnt.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2unauuwsl.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2othibzea.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2xfebqhwa.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2eymrvcme.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oanfrlam.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ythyboba.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbocwylu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzwaygp.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzlhnui.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsfylci.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fzaieomx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2byonqonh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgapleug.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2aonpevxx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2iygtcyke.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2byowwpdu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvygfsro.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rtuvevnz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2elyiofxa.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2koxoncuj.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyhvilf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbedvbfw.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzmceco.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsybbxkb.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbkevir.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2orlzzfin.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2vaalryyk.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2eysunwbq.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzkdwav.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmbwenc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfzhune.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gqytvxyz.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oxuxhmce.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwkwbtb.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbnynig.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2gljsaigy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgusqxy.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2hykfytkt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2mjyhoynm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2acfugnpv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2czdyygxh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2anvyyjay.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2uupbzjqr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxyjiea.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfeepqf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2tfndniqw.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gidmektq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtaoylg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hikipewm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jxoercon.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2umcpmtxy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2xhutdobx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2uazeuwlv.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2btmmjlby.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2zsuuenfl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qdluyufs.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2iharkjsv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mxstogcc.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhrxbdq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqcrrns.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ltatjfwq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2bibbnltk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmcbump.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtiyxzp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2amijwown.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhiiarle.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mxumshvk.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iechzpct.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzipnsm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnpcscy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2akntcjto.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eqglarcb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqnxjze.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkkjlbl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlyiysfo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jztkyinr.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2bryguppq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2swmslyog.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2koeibkkf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqaqtye.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfyqzji.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqvgeac.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcyrvsr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofblulcg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2etffpjbg.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rpiubfbx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbwmgfs.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwaimnor.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrytqsaz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2aazsmbuz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2slfsiuib.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2spdcuwja.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nomnyxll.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfdnium.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xveqlwac.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2yppvwavk.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2clfunrtj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hisocaeo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbjtxrh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgpyufe.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcbkyvy.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2svjnbcgt.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2epqlvnau.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpuhxls.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxscglrl.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fftlcorj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjwubyz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvwkgaf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvnyuwj.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnsbfqf.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhjuryl.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtltuww.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfywuek.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoullxmd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbhfvwa.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlnlbfw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2krzivnqh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrhyalw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztiajfpe.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlixlgpf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2bndvzvxt.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rvufmcvv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgsfdah.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwtqbky.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwgccig.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2genyxrom.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptthjpha.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdcwvte.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2frwsuers.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpracnr.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpkdajp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbcctuk.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dfppaneh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2mykckoim.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2yajfeypy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2koguuhgx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2bcznshng.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yurjobpy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ythrddby.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2kladlwyp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrnymkm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkgwkzu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jcivwrgz.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2otzkbwyq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwbhrjm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2elgokqvq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjtengv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2towuhznx.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfapyag.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bveeoyab.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnmelqe.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrrgsxp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2efhbnoys.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yohmmmiv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2hagieldj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rpineooz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzhmlpg.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2rljxxzlr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2copkectm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2yddmqvrm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vuukdcmt.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrkyytw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2lavuswdr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2toxavxfm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2siwginyy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ralrlrbn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2thyiagff.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2hdotfmeo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgghvrd.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2nquwtsao.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhvahne.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2crctpdcz.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzoyqpb.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tifekgan.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gevphxdw.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2uidbbkvt.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2winsvaqu.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ridurgjo.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nhysujxu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2tiymskjo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qphlunjz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlvumfj.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rcppjfam.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qouzhtbp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkofjacw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xqsahcnt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2virdnsoh.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2akfaafuk.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwbhmsi.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pezfsgii.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2slkjuybd.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfjbyey.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvajfey.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqpyhoo.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnbzlon.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkedqcl.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvdelhw.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqkyrva.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2szzqezag.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxehgutb.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avnyjedq.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fighsaci.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrzqtwn.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgqwuiq.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyyauobr.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xodljwdx.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2deudygmk.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ndktmlop.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rqluvxfj.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kduagjke.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ftohvert.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzdzkrj.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aibfxyij.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfkddvf.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wcijvwlx.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2hetvhumt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzewkijy.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvsxuae.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhawbul.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcaqnci.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjkwaln.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmhnibi.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2reikqhnp.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2icapjmtl.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbbewfh.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcvzuuv.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvianme.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxzjwmm.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rswljatc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2obghdnkg.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2wokamwld.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2txnqtrye.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhdfzug.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdeudmr.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxwngnn.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgwxfiu.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zaewjylu.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhfhvxr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjlwtoc.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zsctvwwh.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ankgotin.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2xmocrrai.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2oylnvscp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gslxusbv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxlyefe.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrzobbx.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvyeewzs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhwdpkh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2akmpktqw.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sitnwyhw.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2lcuukrme.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2oenuweiz.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2swlkzlir.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2muahoect.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2knwpnaly.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2xzufkfsw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjvxbdr.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2iadwmpzs.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ewurbldu.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ldidtqgk.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxwcskj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwnolqp.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yptelrfj.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emmwnaeu.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkbuomq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cingxqdd.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2wmeicgra.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jppvduzs.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2peuaackg.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2stdnvdmf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cicoxeym.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afkibzty.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whmufymf.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iergsmed.html


<!-- 参考信息 -->