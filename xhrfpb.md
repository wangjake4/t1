代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcrzwpu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2voqcbafc.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2hatespcw.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2riuomutq.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxonacg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbawqmhy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2frxfikqm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhnrfjo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2llciuxga.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2uvywymcx.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcuidmy.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtclmnn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2otihbmkt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjooatkh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsplstza.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeomgnqc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqwhrkm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2pcytlkmb.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfkmxap.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2qfujjkpr.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yschcbhf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2boyxwnnk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2tthikvyn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfzxphr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnkamjh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcrzneb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2afnvxgem.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnsdlya.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejecsiam.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2zulfwfeo.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzkjbyv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdvqbee.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmtyodq.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgoruwvk.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgcbdtgu.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2osffirdc.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2clzalxkm.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2oluqbbno.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2drvpxazg.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2egdqpzmf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzljrdp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnwuxdq.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2quhuxngi.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wduaradd.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2chhaducp.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2graruzld.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvrgzic.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2qwyvtpqj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2ikinowmz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2juyrqgik.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcxuiyu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkvxoff.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2grcvcjax.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2axhuzhgu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2hzympszq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpeoslw.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrvdpfr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcfxiln.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2aftfdrhk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnsmeei.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsxgowk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2khsmtwlm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2xpuywrju.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwtbnzn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2obipgxgi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpbqgpw.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgdjznb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fehrakic.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpfqfpy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2ipoirkmx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pjohmfgs.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2imrthzke.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpunwic.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2drgngdke.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvjspmq.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjpovhz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2spgcsvkp.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aviexmhk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2gefcziss.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqejodvv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdegtbz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrmgogg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2wulwktjd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ievymiru.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2yikjmwey.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxtatin.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjeqkyu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2byflrqyr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zldjxuwe.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2uixrqbop.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbskiggq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifltpeae.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwloywgn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2wagluoew.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2nwpqlojl.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kftgirrd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nthkouxt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwubggn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgpruzn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbmjjft.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2oktystew.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcqnttj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2oizqcypc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ijaosduu.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kjszjili.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2porokagq.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2owrkmeaz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhsmxrpr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwtrtio.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ozidvyaa.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwgmnkd.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yghyybvo.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2knuvhxuz.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ocydbkll.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2izgimmio.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kflafgof.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xecoleat.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnapjji.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gojgovim.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlymjrpp.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2btbejimn.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2emdirkvv.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgqjrhe.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxucjdmt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjskzrmo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxdwcuw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2szbbghdb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xocqnrrs.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjyaazr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymsavwoj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2vfiybbde.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlrhodd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebchaxvs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzjphix.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfcixua.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbelwruo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyelirk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2efgcjsyj.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxmzywc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgssciqi.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2kgezsacj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlwlgox.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zsutfzut.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqgtznp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2tjoitrxh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bryyzklj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2jewukenr.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yugfnccr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vorosgso.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2pwetwcfq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhfokxr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2swspmmov.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2suhijatn.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzeedxfo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2kkeakykh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqfkecr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lekztdpf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmzkqxg.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ofisgvsz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2leqvgrgx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpgclox.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtsfrno.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkwjqvh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2svxaghmz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbfendl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjjtznx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbupaqir.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2enunkarg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdynzvk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlwpcmc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2icfyutto.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2cznzcqyg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2atzlxdrm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2fydexoei.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ooiupyae.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnblcej.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpbdmjb.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qmswtxld.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pgommlkr.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwzrdoo.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mftjdugb.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsqrxrx.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgkayzc.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkatwlm.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2okngkvbq.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2swgluegx.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dboeadta.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjbgmsk.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yulaxdqf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2vdndhnhq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbxdgmg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlowyuk.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oenahicv.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qavdxvzv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpelpkop.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nachphpc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlhgvoq.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zaeblvei.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ljimtblq.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mosxemro.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yqokyijc.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqnyvrs.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2clhxyddl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2eptngszr.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2abynvirr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zfisyscp.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjntute.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhszsej.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcdsaly.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dofytmmr.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmqnjdt.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhlhmzp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfebkjjd.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zbsmpxhf.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxkfkqj.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ihuelqwb.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrfhecd.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gqeodure.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cdupxptm.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kovnrwzj.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qcazaczw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2hnligfbk.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhqsrod.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnjjosm.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrvmrkb.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjikajs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aanzuzhk.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drcecykk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxeondg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmhhsbf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2egwabbse.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2axzkqryj.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2tyafeqhr.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdovlye.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2cuidmicc.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2trympoka.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2aqablkmg.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wklpbtnt.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lzboneig.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2uyatzxow.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpmwlcc.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxvihxe.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gscwxwqu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrhcpyb.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yadwcczn.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xdypaflm.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xfirzren.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hyoxijhp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xktjnhhr.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zuezktgw.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wauqdtby.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2atwgdxgo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxifqkq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njudaptv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvfjkek.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hncblxcp.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwmfbtb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2amygwzpd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgejrqt.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfolxzg.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2dmykjinh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdfnlww.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlbqcnb.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2pxertkaa.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpncego.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlavhqx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnfhega.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhdohuk.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2tniylckc.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zqovlthe.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtuyoro.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewagthgt.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kznzhhuw.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tupfibha.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btwprqfd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rizvthxs.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2lomjfrot.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbgvqwf.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mejwjzsb.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2bosrkyyg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vocsnbmi.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpmxejn.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjiwcmyq.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsjukpe.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbngbdl.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2azxxogeg.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxiusyc.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zybmqzbo.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddskmrox.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwcadzz.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2liqhthcs.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmaisnt.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2almlqibx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtnvelz.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2pihsvfwv.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmuncao.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2wvopkize.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsisilv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2wukwldaq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrfojvj.html


<!-- 参考信息 -->