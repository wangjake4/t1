代发 wailian999

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2etggjpor.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqutzlc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsduiyly.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhiuwmgi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2icwthpht.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhdfgzi.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfgsstl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eselvvax.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyxsnct.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyijsosk.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhilutb.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgkjukb.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmihnly.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2etxtbexw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucymaknv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2xafqpsdf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmzyhtd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2nfsddvtt.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqeiqqe.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2focgiszq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwcvgwh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmpohsd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pofmvxla.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjltzvmb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfxekan.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdzhzfo.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzhftfv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2jygcqtmd.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpxdabf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2lixkqncw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2pamjcvyh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqbxauc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbtoimg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkajktrl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvetazm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kydeovwp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvbwflc.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjvhkgt.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdbrnfg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhrodfo.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqyirdg.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2osrnbzfz.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfskxmrd.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjxvffz.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2lmexvgle.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2lxoksise.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2alfigyrv.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlxbnbr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2znlitqmr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvzkxmm.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2izukxfgl.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2szfbjpiu.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnlkxvu.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxklppp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xhriuqck.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqkfsyy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtkbsfl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2rrakfopm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2efwguhfb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxoxaym.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkvoaws.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2vehzhlky.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2bijuzprg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2tjiyjkbw.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdxwegx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkmmhlh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2crhtjipp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2evuuywkf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zthndgvw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfkjhfo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2htfibyls.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2smvxetrn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxpjpxk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxrovxr.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2gdksohop.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aneoyhms.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jncqtyqq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2ebydyzqc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fieeixdo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2jraidaja.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwmrhfl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ycquvqsi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcxpmkd.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2avsidbsp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvwiead.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lddgtiuj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2xmprdllm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkzuhvd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnxjkjf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tirtokgz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsrfwbm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jptgxpds.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbogxpj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jijmplch.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2mppayksx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjncehn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcbhufg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2srjrfqov.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhqnslw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbbpisk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2yaajuvjw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2dksmzapm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hutliort.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mjeswvyk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbfchov.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqginds.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2uagwbngk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzlvkqf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2qidqziea.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2crjawtha.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkrzqbm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdkfuqq.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2akevzkxz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2fkafnrcz.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzgdlxv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmbqncd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2opvsjmhp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hxohwypz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsshtysi.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2olgkxsvm.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqbabih.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gcglttdm.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2izozvzsq.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2idxwmjil.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylztersm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xykvttwx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjzbkdh.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fovfsqlt.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmiabkcs.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ehiciypo.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxlseey.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmfqjyj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnxgtpq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqjfzis.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtbqspe.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wxatndtf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2xptzhzra.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqdufyd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2zhinyrrf.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmtvbpj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsrnomh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iptiestk.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuwtpge.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2skvktavm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcdsiik.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2iugelhfr.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2npguxbzs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xgelncdc.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ojebtnhu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2smjnvzeq.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbggqtn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2jahowysr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvdoevf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bzesgyok.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2limmjtjh.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlyfctc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvdqqzw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwzkcdn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvvpzdq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2csyxpvib.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hinapzlu.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kveiihcg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2elomcdhy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpmwovs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcquisle.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnlwzig.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnycrvt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxofxevy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rfaifnfc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkqtdvu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2swspbmeq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdxugqe.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2elhjdvbu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxaqfnu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2roxxwvar.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2gehnvehs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpavrkak.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2flvnqzhn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2kusehgjr.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2iclrmywp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2vmcyoepk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhiaukg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvsldfv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhpydid.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fcejipiu.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtkspxq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ginsiaxm.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2fbysexwe.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqimguc.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2myjyqgoz.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2muyskmcd.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjaliik.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmsopva.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgihxzr.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtfyjfi.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2alkeuwsn.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nietdijw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2kktvluqo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tebkmtty.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqykskx.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbxjhtl.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzewsnf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2azevgsol.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxxlygn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpvisol.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2udatrsqk.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2izpfmvbd.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxhzoha.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bzltzvou.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zzugdofa.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmyylbu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2pffwkwhy.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2lijiozrs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2geajyjov.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dvyxhxpw.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvwtfaj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpoiubwd.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqeetpsx.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vibhsgpd.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtdvaiq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2obbeqcuu.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2evlbmcgb.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvmwelu.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2glyjexlw.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2dsipbeuy.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pitvzhcg.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpbkxxw.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxptlth.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hquxttea.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2txqmiwdm.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iendjblz.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsewcri.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmcwysx.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkbggfv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etaxqlmn.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljolabtu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qczeuode.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2deyjuiad.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbfkgjv.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdmymng.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ehevutue.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dusnuzud.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvjltxw.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dfukjcqm.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvcuean.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lojvtaqr.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ljlxhatp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2noglbcwl.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhjmgki.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmlqmsd.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhdhioe.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqyxzhs.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2weczfqvo.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xjawlvlr.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yyptcwqi.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aakjwnfu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmanyli.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmqlprj.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bvefwczu.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrrspht.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2nocpgptx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzoxbdo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2ktadrhie.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxkruyt.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgjjuvc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bizgtlai.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gpsqlfmj.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzsyyoax.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2zccjawgs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdluphz.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdbyimo.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqpzczs.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvecbkn.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfozike.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2hkedmdot.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2usnmvzun.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2zsouflek.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2kgofjtke.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrkscmc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyntjxqo.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuobpqqi.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khwakstv.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnzkabc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkccmgeh.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2aznahzps.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xntigwxe.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bijyqugq.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2eeryvshh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcrszhd.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdteqvug.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efepgwyw.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwwthsl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2spxkirdy.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mamcnykj.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jounfapf.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vamtvxui.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2iudxrnsa.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2twglqfrt.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpapaep.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcupkck.html


<!-- 参考信息 -->