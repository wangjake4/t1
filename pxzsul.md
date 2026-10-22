代发 wailian999

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gazvfdla.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwnengr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxkwveo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ustgrxcq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2eggbpkrv.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2ewimjmks.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqvvuci.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lubbkknp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2klkgamwv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwxafmo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbrssog.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyshypmq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kubhbxbc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvheime.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2mitwfeai.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jldkqlpf.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2afwdwxkq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmxpalb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2blmtehjx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkerwram.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdvwqlw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmdtwov.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfnoiyp.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2brguxoef.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcnwljj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2grqfkgve.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsohlbd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2afiuaxct.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhonjzw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwzatsi.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvmlajx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2wxueopps.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2txfcvrvg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubryavdm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxlmntwg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmoygoy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlyofdm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxjcblv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kijharfy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2crdqtdbe.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcpdhkb.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2cuthqgdc.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtsoecu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cifprnzh.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfecqkz.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jomyhxlp.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uibnrakl.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpyooba.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnzxhcl.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkfyony.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2reoqiobf.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmoaijq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2uapwoiwn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rpucteyt.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvwwduh.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tafgzjvc.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbumctp.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2rziiyngp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jlykhyod.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjxfexd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmdasjq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2whakfaey.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ulueqgrs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcwqjvs.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2tckhfzun.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2gmukaphf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2huycikmg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ldytagew.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2byfrwaem.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2stacwuwi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2gopppjko.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwbqexy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qjchfjyw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvgrtns.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfwrcrt.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzpsbeq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vebkgzgv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzxjske.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ccffmbcl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lxuzzdck.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpghsbv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxebufi.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ahoqncuh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2snuahdbq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxblsvbe.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgthxjb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2mqyqxcfh.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpfqypm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrfivyz.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nnuiwcew.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgbojhz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2analhlqo.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2azxubigg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sdglthad.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2gskfhcji.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxwguoz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgvfyem.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubzgthxo.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2hibozbhz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2wndhhedw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2smpnhiyn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwniayah.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2adxqloxx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2jiexreuj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfgbvfk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzkeqwj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2skgowlge.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lkczakzw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2dusiwore.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhrwehe.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugzuvjts.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqgfpsb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2plunoior.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfqzxjp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2okhyddpm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2nnghzjjv.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2putsgyas.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2akcirflj.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxqaymt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnoegst.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lttjftqo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jogitucf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzghmrpc.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gimicpup.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnuprek.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbhpxuq.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2txuvdlum.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjrkusw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2emncbduq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcxmcgq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2iuuwrsuc.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2slpcxjua.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2apnrsjem.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmzcwik.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2kvobndui.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lstwvsbg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtbilce.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2moklzvxh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2iyrktwsb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmgrwia.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2bympwhql.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2kttztnoe.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2sqiddsnq.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2itzthhvl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwleslh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhdvonk.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfssbbl.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2puzgwuxj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2bflctgpr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwamfpfj.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2llbiltft.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvlplbk.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2jstdeiwn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcudpsxs.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnykfjw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2udnueysc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2tijbwvgs.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzctwct.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpupumkb.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sghponxg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgkckri.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2kaihbnsq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhkrbti.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxqxgzx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sgthmoqh.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqltnhbv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2snwpmfuq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vobolwsu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hupumztt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvosroc.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yeectroq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jiecduhz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zbderitb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kduiwdoc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmctnaau.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtomfev.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2gswtkomn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtamqpk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wotahhgz.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnnvmvp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfrqnga.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmslzou.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2nhehjkok.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgqlcuc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2micuplal.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2shsmuszr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2abhdtrjs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpyitoe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzssvku.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtbffwn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnittgn.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkusggl.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2afqepxok.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ydifemgw.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2unfdzvpp.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omrrffek.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ldengscu.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2imfgsfku.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdtadmh.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jctkbkgv.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pcupbkxy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2fpiifdfq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcggjcl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frddfoqs.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkwgqjy.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjgpueg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2itrpylgu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdsuwoe.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzfydto.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2reteobwr.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjvxqbn.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2okmboivf.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nuuhwywl.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2larsevft.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpfcmfe.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2pdeydytx.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2hiorqwfa.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkggjvs.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbdorsx.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vgklbcpw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxxrlaz.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlyvyipg.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvezwaen.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgvcqfg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tryubeom.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hecvjsdv.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwebblrc.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqbwraw.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlfqfzk.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2trctsqmw.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2banojeze.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvqivul.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2emdulvjg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2nrglmsdj.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxnnyqj.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjrdwph.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lgaqilrs.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjnfvee.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2naizggky.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kravwbbh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkjxvmb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyameomf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2buflvyxb.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2apsqnknw.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjbvadx.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2sscgtnzl.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2curlwhqa.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pptlfvsk.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjdwxol.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iliervzd.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2atnaokcn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2elqzcrlx.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2szqzaiwt.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlrusfm.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrtmkxk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2fzurdpfr.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aowaokql.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwgllih.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yulcdvoh.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2acyngcow.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mwofsiwm.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvbkknz.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mvknebdh.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2notkpvsh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtvxlmc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awvihiyg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2omjjmkiw.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tavbjcfs.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2chddsqyg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2puubvmfu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kccmkksc.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqlyodh.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsxoqxc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2tntscxvn.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwdpkhq.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ldyggpdu.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjjwlxp.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ightnszt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxghvcf.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vfikugnm.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2odybwpwn.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2prplddhb.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfpohpk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emjadggc.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grnyhrwt.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chvxlthd.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wumujdnm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukphjhyq.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2hapzsykh.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cljrkxnd.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbqymco.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2tpauxhus.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbfszny.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmfdzhq.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbhzatx.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itkilfzj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvcwxfs.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2khlffvrb.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyofyfle.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhymqjz.html


<!-- 参考信息 -->