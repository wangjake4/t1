代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpebohkc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nctrsmlv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2qdklpnrz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfignrz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2frqegwof.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfnegtt.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcunoap.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvplzyn.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtlmffq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2djtpncdy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2exafzryp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2shsremrw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yqasyhho.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ggudcmqd.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdggsytz.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvknert.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2twdwmyae.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvrwats.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pamrdmyc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjamxim.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiieoamm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2qmepckeg.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2iowvkuho.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxtyxpo.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhtootc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2fyaufcjx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2mheyxhsd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrotlbo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnuvnnol.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fccaussh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2itdnxkqi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxztsjw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gjecgxzf.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2msymueql.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2vduwkedl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrlydlb.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2fboncwvs.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlpqfsf.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jztxwfyz.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2irlyvjmb.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2sybobxoo.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2qesiiggy.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2rquhhvdl.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmowvsp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyaeylb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrycxmz.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtwnzsr.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjbffrw.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvikrza.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2wdccpfni.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2loorwqnb.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2eqixiqvx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrodbgd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpnhuwg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2yqucpghe.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfekulp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvpaqyw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvmchkv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnppvlv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2rvptxeqg.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgsqbzj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pukzckuh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhgppeq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cbziiezu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjafzbj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2smgybgxq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpgzckj.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rmcuxuhm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2pjcvqodc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsbhhnb.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2aeitraks.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yccuejkg.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrnkqjy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2drgeofxn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlolasa.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2hbufrslm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqxfdhy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wutcmayn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2cinzbswi.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmurmer.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dnembscx.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcfacjp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgkfqic.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyecqatg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2anbqfarx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrgmeeu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2zaarrffy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bodzwzgm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuikhvzq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrqkypm.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2ykroxcfw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzttiya.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvtvopv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxequzrq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2qugacxnp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfurxms.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjnddjo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2inthwqsh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzurxte.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2byrpgcte.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2sefztdtc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2eoaebabx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnoglpkw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2iznyouxf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqbpiog.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmifvdvh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nspajkpb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwwnpcr.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdeqwho.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpuwpgs.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qoksulol.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gudzhafo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2coskynyj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzjkrlg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2giiafrlq.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpuhzcj.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wouuodej.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqkqvzi.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ioawxluz.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdnpmxv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpdemch.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcyqygup.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ukltyveg.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vubkzweh.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdyzsimm.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lpetgumq.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqiauyj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2upssmbeh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjdaocw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkmqitu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2djtfpdiu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbsrrfh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqsoaoq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2oigswvmi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2fuseodmn.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lyoopoll.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2renzthpg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tblyvrqe.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzbwvyt.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2aoiopagl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbswdaza.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2oruktysu.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2upktadas.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgdszkl.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvxjywo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvbsawk.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pazpafnn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbrjizu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2oakavejz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nebuitou.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2akrshbzh.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkzbwae.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsrducu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbcprnm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sichizzv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qordiqtl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcegzqbf.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgfynfl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcpnwcw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jemawjrz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2edbkygsd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpmmnts.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ausugeiz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rovsmjjb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwfzjpu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2txuxiipm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2emstkdih.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpodzovj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2tyaypmgr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wakkefmq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjazncd.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2uoyjbxiz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzjopmo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2ctayycmf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ecglmzoy.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2lmasdsqh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2iarqchur.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxmanbm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2baevfrdx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2orljkgkf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2isomuopq.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbcnqyx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nprmvkgm.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrfikic.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xzeneyjf.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nblubqun.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cpyavzya.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sihvdenq.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wtclrheu.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxwricz.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmgyjsw.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2evycvuns.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2joqhxdbn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtlsumr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqyihcm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxibbrcu.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ajyhvyjr.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvqgoik.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2edaepdhc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwtfsty.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2effmubaw.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2upunnsge.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvzvvmo.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbzvxjr.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2epzkearx.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2djqwaano.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qeukahqf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcuxvlh.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcrtvls.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfabkko.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvplghh.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlmjpta.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmhwmgv.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yswgvkkw.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyicczld.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnikjkg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyzddho.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pktoryjk.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zupfplco.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2cznuhesl.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvecyjx.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cnwbirev.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqvxtvn.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2drrlktvs.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qagiwkns.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2capcveyw.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oztsucmg.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgxejjd.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rwijnryj.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuiyphj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkvarum.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zggjfuqi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2juvgeibh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iefxlrhx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2khklipdh.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgiqmgf.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtksapz.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cdivqzfa.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmcyjzc.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ckyefoep.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ygphzkmq.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gecsvueu.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwaclvv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfbliwp.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmtntke.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ughxlbuq.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqbcess.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrokwgc.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbabogm.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sasprykp.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aaaukgmx.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2evynakxq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbuzkej.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqjlage.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvzyjpl.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2eepshsvd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2djleriqd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkekalad.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2fkyflqnr.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbeikbwr.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dprmnwox.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sihaivkf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nmriifgj.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnvwjbo.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdwgsiw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2plyabhgp.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2uydnqgke.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2hpakhvfn.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrswuju.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzljrqy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2bbltrywq.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fxefmuyp.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxolkzs.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzfzyfa.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zryzxfde.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzqbffm.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eneeimyq.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2muetpvng.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbfbdyi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuoploeq.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2xngkrxly.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxejqapf.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mdllusln.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2pbakmdka.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwylzvmv.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcqidnc.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2doclzcno.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2elagxkhp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nljckics.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqmogzj.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2idqetjqa.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxvvdmy.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxjwmkn.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqhjlgw.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2awhyekcg.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2krpdaidx.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsvmfjr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qttmexix.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyggmbdc.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2glwwbybe.html


<!-- 参考信息 -->