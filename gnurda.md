代发 wailian999

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2xigiyrqz.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2qcepnele.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvtsvdm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhjehja.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkthycg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2trkkfsdm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2xmldyepb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hptrjhcp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbiwtzp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2udjggwuw.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2beihbegd.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dvavecuo.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujygzxyo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2btevlxqh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcunpbjh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjeonrqi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zekgxerg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2shfmivdj.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxydobbg.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2wggmmung.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxdupfi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqqtibz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2euiwagyv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbatqxuw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uspjpxov.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqjsksj.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2aabpzeeo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2truxmwgo.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oabpvvuc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjvwyud.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2sopmrxoc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbierrpy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldyejdhm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwwooom.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnrtvqp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjbrkye.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rqlihpeh.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2qsaplrxr.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2eekafjuz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhvidki.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpodgmm.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvbinqj.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzqwudh.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfbuyby.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2nikmrkqz.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2dceaadtc.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmynihg.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbvjbmr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2mucvyrhw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qbiedqfi.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xafcudgv.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kcslvkci.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rytlajnn.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlnyvzz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dpauopmt.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2ptszzkas.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwtomxt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2iednypbg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfxnmjj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2execkugz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2raexqntj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsmpwrq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2zudagiqa.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfjorgd.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmyiuty.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpiegpvg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2pkyiihpp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2abxprssq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xohgdbte.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2bscqaoxd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2dxktovxf.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lqamkcla.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbcwygs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2slxjoggw.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wcodrhyr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mimevmgb.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2exuevurb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2jktgnbez.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jasfezeq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2eosbbcug.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbhxusa.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2aflawtcb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbfkgir.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tygyqubg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgilanq.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpejulh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxrsqca.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbxdajz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfqmhrg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lakoyqwc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2hanpesyy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hivxvaoi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2arizbwmh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmohekcs.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2jpncwmul.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqtejsj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dusjpdhn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2umykbfci.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2nskundpd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2pghzcbwg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpipjbop.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2kphfosdc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdemwmw.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2prfhtudm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwsqjqo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqontqh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2szmhfaub.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kspguuok.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzckzic.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2efnoblrn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2spvaxzit.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ellhlkww.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwowled.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2qntvuqwo.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrnudmu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpuyegc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fuenuiza.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjzvejw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvrprlt.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqowtuzh.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kztztchy.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xwngwmzv.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpngrno.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ajsgzeox.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezheehjf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fycxfmol.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvqxdxk.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hopzodgu.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2chacbafl.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2aleglhfo.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2moqebvwi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2izynlpdz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrafsgv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdbkhud.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwguijb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zoysucew.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2imhrumrg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdwfuyw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpdunio.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2waacrflx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fusbgjbr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzwwzld.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cahewtyo.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cebaikha.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqeilqzz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsccyprj.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkcnqiyv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2psdwuudz.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2rynagnnv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwstdusk.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rsptkazs.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlfbkob.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfqtdng.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vagqzxyg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzvlgcf.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwatvhj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvqiokv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2klnxyhfk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwapmrfq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vhsfhtwc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgaiqxow.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2piffbbqx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdvrraj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwqdlrr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtttmjk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2akfyyrvo.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrofeef.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tpecohso.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vkaqgoup.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwcbsgao.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfozznjp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqnltun.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqfqmpz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yycdawwo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2okzwrmxz.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzprfml.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2slazrrhn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrairxk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rpilyckv.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcnkdfp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2gevkexup.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vqytqeep.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2iunmktkk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwqienn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bwyouymz.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zxaavgaw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wwyvijhb.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2dayxpbhl.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gurvhafp.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pdynejfq.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2poqormiw.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igyepibx.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqbndir.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmfffci.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzyijdj.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbmbqko.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ualvpjyk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2fffpwnby.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjrifgb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqftpsm.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fkixydrc.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izcezfpg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohajibjj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgzjkqu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlowtsu.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjbjnpl.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzknoil.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pleiuupi.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvhyuyj.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2veeqplbw.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2risacqac.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrrmlfy.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmyhcnw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qkyqspfa.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wylwrmjw.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2mzoqtpyg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdlymyo.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhftyxpo.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mclmjvgy.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znyinpsh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qauepomc.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxsitqe.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2taikyrsm.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2emfgdhhv.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zusnbhvr.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vufawbxl.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vuifsinz.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ngftncyl.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fwicuctq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2jievvwnt.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvxcxzc.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzjtjri.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ciplhxme.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2yonfoftv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snxadqxr.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntachayy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzkhsju.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxoiyote.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqwxbxh.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmdkcef.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnmnogm.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqhjsff.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ipatzhlf.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmuyjuc.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wytwnqok.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnykqmr.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2krdalbks.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2oiawdqwb.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtswrav.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2shbrzole.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rgczgdqk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrazfkh.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjzhasf.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdfpcxu.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdilyag.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2swgwammh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2kwipstly.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbcyemf.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nksqlemb.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2vbftnonw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyhsvrs.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqkoiwc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2vdljuyji.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eykuikmm.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2otzqmqfc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbarthh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhxlrdq.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnbiwfe.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdhfhik.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqcumkl.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2loexyeeo.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2kmuxzqrs.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxvpxbt.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ajefatic.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2mzznasbw.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jnulflqe.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2chdtxvvy.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ztupijdp.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrtoilw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwdkpmc.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbltjnh.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfharsez.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zirksvrj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvgijnt.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2qpeqwdja.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlkskfu.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvtgdhy.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2lfisrwwh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmditce.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfruocke.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgeelzpt.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbcjykv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2twfxodag.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2snyjwdwh.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbeyqiol.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjobcop.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2chttcwrp.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2izudwevb.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pufjglvq.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2sevoegyf.html


<!-- 参考信息 -->