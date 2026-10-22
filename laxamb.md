代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfofkvtr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mydzjakg.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2patheqjz.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvceygii.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzxesef.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2gevxggja.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwtyujv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2kodjgxwj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2putixtoo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxrmuct.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbaurtwi.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbkgzhu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2smyhnfvf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mriwdesn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdklhnp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhuybwqp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcemvkwz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2iteqcdcy.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2erpnuyln.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2auxqulyt.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqqevwa.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2amirodpa.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2vevckgbl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2itbpkqxo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnuktvd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpthzog.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvwhbhw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdyagzn.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2engbjbdi.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2ccymumay.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2szqnwvpv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2taqieykg.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvmymrq.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvdjofv.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xklknslk.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjumnuv.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjqhlnf.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2knjnlvpw.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsyigks.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2afrjkqnq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwaovzc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvbaciv.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hqplxrsz.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2stncswca.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iwslsmif.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2qzohnlxk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpzbzqu.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkhamvt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2hefrtoci.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2yrulrtuw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2gshxbofc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2imvfqarw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2tlddukzd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2zkyerjnv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qalwphgw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnhltyz.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hzorqwth.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uparagli.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2pidnnohi.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2adagfclw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2unvnmwhz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2gntsitwx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2zavdcbic.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwokowp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzaymhg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvdtqji.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2gezicvvk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrfvtuu.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmhdztw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2chjdkwbm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pomgxnya.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2cujurqwq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2eemummau.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxxcdqk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrvupuq.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bykuviuu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hcogrcuz.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrgligy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2goxxwsyp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxekuqc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aewkzdaj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkofguq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2gztefijs.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2blsldoau.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2okfqopqx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypupdimt.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdzmaks.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2bznqjnuf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2rrozlaac.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvdemrl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzvlwwj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsyvaij.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2aeazefer.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnlmage.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxflpct.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgvhmwm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2tctqqqmq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpvqjkt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzjhxer.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2osgkmihy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2aegsqnub.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vljmalge.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzwhwzu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlxyjxv.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jexkyvek.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2blqlmapv.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzgtsnv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2csxzbtkm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrcfyqy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzjwinl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkypecfe.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fowmcxen.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrhbwqd.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mrozxhjy.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdorbchy.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vjcymxrq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvvgoqs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvaqggk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvicxzi.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwtuiim.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yftjakfc.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lriktjje.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfygvfe.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwychtu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ferozhhx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlyumqt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2aulxcaqv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ojowxlvh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtzdwje.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbntiebg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2evfzfndc.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2apjotcih.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2evlqlxzv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cklignew.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxsjnomx.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwnwvjc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwhpcgq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2avjdllkm.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2asrvjsxz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpqbvgm.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ccamanby.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrsdzbo.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cjucxyci.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjzgxnv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhuelpn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rckmfnit.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2uthsdpbc.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzplqsju.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwdvuut.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2peelywxx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfejuzf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2muveujyq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2psdmzqmz.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2blfufdiv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2lidinrla.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmazxnbz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypituyak.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgngqaqq.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqsuepp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpvoekx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqpmwce.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2enscwctm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2reatwnev.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrdqfjw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2knqetcew.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmnpvzr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcyiojp.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2gbivfity.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2knrukovu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2bcuubxzy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbssxra.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2lglaklpd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2kapepmfe.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2suikbsfy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnrkfga.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cydnghjz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yomybwix.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2siorwnib.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eajhwqdc.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcyhbll.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2fxncieud.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgxkpfb.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2agnsrbeq.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhyfoaw.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjszkqg.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwelsbr.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlaurgd.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2quszdlea.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wjelqfss.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2xighcdfg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2haeapfmu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twrkmdpu.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjydykr.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2femnqcug.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fodtwqlq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fsribwtu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrnhtov.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nhiavhlo.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcuoxkc.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dctxwjnu.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnsspvj.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2essrpfrq.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlhzqjn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vybejslz.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2miedrksg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2utrwrnep.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2swkkpkgt.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2iiveotay.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjdwmzk.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyyhgkrb.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcdcgzx.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rezyitya.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2suddfkqf.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmhhfjq.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyumbtts.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjmrnil.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zkyngipe.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bllbnwwt.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dctggfzm.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfzmuwl.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zargxkue.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2omdghtmc.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtbudnf.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rffrwsqu.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xplyzbyc.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2jkglroig.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aocctmjo.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2upvcwswa.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blyqpsst.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2skzgfujo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2sfypvsdl.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrbuumj.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ygniqwjx.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gbonxlrc.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpovwbko.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gemqrcve.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjzspbl.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pztifbvo.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkrsduq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnhxeec.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2zurdbjhy.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2deapmhzz.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2egyrcrdd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2szyxgbmz.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxkpmfy.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nculvwmd.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gkiynzyc.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zifptrwv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfjqnau.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhqjapc.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrqcuru.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2lczgrkho.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2sltklkhg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcahvosn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2oekfpgcc.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdagnxc.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuitjamv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvohzcyl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zmaoousb.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqvjzgo.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpflgas.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmgkdmw.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrfzvmg.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvropmw.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tgycvdip.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2dzplkvca.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxvcxra.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqxhcba.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnzgfth.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzwlvvk.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qgaftomj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgdvsxw.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyltnjxz.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvufoedp.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzogfyct.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2knrriwtm.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvvscyq.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpvxmgo.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwhavtt.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrvtwxj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgafaggm.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2epmhuxrk.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2spvptiik.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gozyyjhz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmpmllj.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2drjdhkdl.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ienrcdei.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2scmrpqnu.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtcteki.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2klrydqkt.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2drzeyvih.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bofhistt.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2otmxvnzx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsquvxo.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojffdycw.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2eivzgzoq.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzbkocd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkbebcz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfmdhuy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2viyesotc.html


<!-- 参考信息 -->