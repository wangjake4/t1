代发 wailian999

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkxgqih.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2agqfhgur.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtokxym.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlrgryh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrqwzwk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbncqep.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvbkjnq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uhahjjhj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmdwflp.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqcfphy.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2szktcjsz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajyyknlj.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2llbdhzqg.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2baauceiw.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvdvtpp.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2tiiptegm.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2nnucygrj.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkyvscq.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2ukluiryy.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcoonqj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2lwknikdi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfoxpqh.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmuoebx.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sideicez.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2efpvqycx.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2qefoxnpc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpnkidp.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2kexctzyi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2wggnqouj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2icfrjzyv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjmjicp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhlssvo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxrxklu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2xttywqdm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdbiige.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmcykvf.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wdiavtav.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdyvyzs.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjyrnts.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsrfyab.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nsekrduw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2awckbrhw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2sonfjfap.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqtszhq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnbelyb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfpapng.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mznyvjof.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rivgvtpt.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgffyzs.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsypwnr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fruzzflm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2atykpsgg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlzucum.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnsqruu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbvdgzc.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pkauzpky.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2afuahptk.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dsskvfma.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2ouksuhoe.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icgspjzz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2inrjgkgx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2diyxvadc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojexyoqv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsoycbfr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhluvui.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kelnrgsx.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlmvxxk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhminytu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wojpzrrp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqlbtiz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvhxgvv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2krnpuult.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzibdoa.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2yytukvee.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gacpgawp.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hucarltl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2htmtbyvq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjshrlmf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdhzcck.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfcgirm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbckgqph.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwwqytk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfiqhwef.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2lsakueyr.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kotajfqu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2owvkoyqu.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdmualy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fonfwdny.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxrohwx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsylwcg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgwicqo.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oaapmesy.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkyfclp.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxbqonk.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpcxpwf.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ndckjtjo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxestmxf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcqnovv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ldchznxz.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cneivqfa.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2voyhfcyg.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zvslzkse.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnworpj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcuklinp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrkufbv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2albmuazg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbvdics.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2okesrgvx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2yefhcazv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2wycmpfuc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2tcumsxoq.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ypthtmyd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2phdoehlv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqymopuw.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tsiyzynh.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofahfdyh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgyxkcm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfgeyzc.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qeefhids.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgdkjss.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2famzrean.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfqtrkv.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vydfpfbo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrsiwus.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2zitrslyf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nbttykud.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfjsvri.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhpasle.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfgsqwc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2senjgkgv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmunapv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zuynzyrv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxaryoiq.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvvzwlt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2qndowfdr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdmmrrx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxicaihq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvroqyby.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2biyfbsyk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oeymtxzc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkrplyu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2girftbcs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjiwivg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrjpifm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2eufdlvpt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxutgycz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2blpvisoz.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2scgwuxqe.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwujrgg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2vxoztjqp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fcocxmnc.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqxkkob.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2dahiwtxa.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2eaeoezgt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2dvsvlbag.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnwuevu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rubdvkzr.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2gsimqxim.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2catdoufd.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2etfywldt.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxvbojg.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvuipes.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ihsfxeul.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slnfavmd.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjaneyb.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2mimfszkm.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dxntvbcs.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iveivfjt.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2knhbwvjw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2unvvdnza.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lebptmfi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzxzwoa.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbycqrx.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vahvzzji.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjerzhc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfmtscq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwiswjje.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bvofugjq.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2cakeeipl.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzgejpj.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qabghfpn.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fwisiwwk.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsmlppg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvvkxcu.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2lorapecg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnvflcf.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fppkvjvq.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2fvsbpufh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2feiinupj.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kirhqrna.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwngbyy.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2osxjnorg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjypxcw.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqklwtf.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrzuijg.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcbvyyl.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ncisbnmh.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyyzmpr.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzqcbud.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhshcfn.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2facqoxjk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2tceabxnd.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cphkgxbl.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmjivwa.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsbznnz.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2csaqqxee.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njcwnxkv.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpvjtjn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlfxhyk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uiscwlgy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2suwercxj.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2atxoovtz.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2lmziktcb.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvabdfh.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsqrxlk.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwuetgv.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2seepobjd.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dzuctrsz.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wdawuuzm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2trddbgcd.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsswkjq.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgnrjmt.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fcccikge.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2yamvuguo.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gyroizck.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2umsazjsd.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqyowje.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nunczeeb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2oytomfdx.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxumxrr.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2loloqsgy.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2nlleatff.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2nuoeflro.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkxijft.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrajgkb.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqcfulbr.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnglktv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsttera.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qobeumri.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fysaxzhd.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkgitpd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbbonoy.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cijkskrr.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2rtahnhiv.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xavppuqu.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmhadat.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2adgqpaey.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2oshljrxc.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2apqupono.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlgqhkc.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzqydbk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwdtjbm.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djjrvbys.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2guxwqwqv.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgcxoqy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpffgqlt.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhymcke.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzspqbf.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqfeqmf.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpbivlb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2klzibflr.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhllhtx.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxtvvbs.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jevwhrag.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2avimbgxx.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2afbevmzs.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsptbqk.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xshlceek.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcthisjo.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xeumzbfy.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxftpcy.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kjelyyrq.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dphckpbe.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjsztes.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzecnmdz.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzfojri.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpvbswl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2wgiopgzu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2lodfbpqx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2khqtmjij.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqhsjkr.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qmsobnzn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2cachmfta.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2stvlpiur.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2reaxssit.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfuivop.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrceaek.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvwhivf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2xxoggnpi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iaramvri.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvwtspn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwbuxsp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrwodnh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkoltnku.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dippjsbv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqwcugp.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlyznukz.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwdlfim.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgqxjbt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwijafq.html


<!-- 参考信息 -->