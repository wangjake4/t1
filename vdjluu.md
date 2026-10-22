代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwuodiau.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwfcfip.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iawxhgjb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2idfdisuv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzghbxz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2plgzbvow.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdjuhrq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcfazfg.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fyelgade.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2enrizdbh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2oiiciekp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmtlpwx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzajpev.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zetnqdpq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozylnwwd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2knvjknnf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rmciztrq.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2jregqiod.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2anowrbyc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhubsmt.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2efmolmip.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2eshxfxaa.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgsjqpeb.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvykwgo.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqutytg.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2bbclbmmd.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqdopaj.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2usslmuqh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2rxiljrxn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2krgbdjof.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yejckuyw.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvqflpg.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdlziqc.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvxozki.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dtorzlxb.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbsjrlz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2yasknzpp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnabcvn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ludtpeje.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgpgswj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2umwnfchi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqxltye.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpynqgg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmgscot.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sazlwzih.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqyducr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwairnb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwdnokq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lktpjchp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2klzfsztk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2qfopmdns.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtrvxhq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2kigcogfz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vcycwsbw.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2odathcix.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqhdlcj.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rpyvwjrq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2cgazzjtn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpvammq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2ytldolwf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2abdlhtpn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2biiqzjqd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2rjixidiv.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aeramtfc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qorjwmvc.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rghmjpwl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2mevrdmuh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjompse.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2feuxcsdp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vunqrdlr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2htyxrzbf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgvjcyy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2tclztdpc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkqcive.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2mrpvlxhx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsvzluj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnywywf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2pctpmjdq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2qunelejv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmqhzob.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmebzwgb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2gergvmjq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2rezyguhw.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2izwoeako.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2imzuhzuk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvuaupgs.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qedlygni.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjdijrk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2wugpvfrs.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjagbvp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmewmpht.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2qdeeeope.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hswuwlni.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvgqscy.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dvecivtj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2plygcoco.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ruaopcsf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ktywdrqu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2udmirijw.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjayfxf.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpiigvzf.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbletvd.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbaszhii.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2shunpwym.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2evbandbv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfgboeh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtjdrbu.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2awfimvoa.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2immolhka.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2knstfraq.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ynywvynt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dudprded.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkdbknn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2kicesnkk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgauffv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2syhqbsie.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2umcrvxzt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrnjfgs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqlzxyk.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxpasoo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzrhohc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgymbfi.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwapnzf.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbznajcw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdthtry.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2utnyehpv.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxghegxk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsefrxpt.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2oclennoc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpwwktq.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zalgfvkr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpwdskf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2izgjomzn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgpwqse.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxpghhs.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2arllawnu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ixscgoft.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2afzbptes.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmixoxrn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbsppzn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2upsvxzpo.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hodvrvzn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnxblxh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2foxercfb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmllcmoa.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsnadjd.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mebgffpb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2murbkomy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlscvfr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfduooz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnsjzxt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjfsvcl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2alokhapt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2griuiizg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqgkppy.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdimvbj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxbubxz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhyqppp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2nbotvevz.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2sltincvj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrdbwau.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2adshruuj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2qnneksrq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnoxwlx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhenhgp.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvdcotl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lgltstex.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzickja.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2axckpgbn.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwgaovq.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xozkmocu.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfryatuh.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsaitrw.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2sotyosnh.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxtiyza.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnsuyfe.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qiljowic.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbcdrri.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmdcbco.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dybjunuq.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhmnwyq.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlfiyvk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqnpzdp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zetpmjss.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hahacyot.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cqekngke.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvmrhvt.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ridskxul.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvmfajk.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxfugwf.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mspttczi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2takozigw.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2sgyjrgdq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgxugvo.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ayldszcr.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwgelzs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wirareit.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfoybid.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmsaxue.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnwebvb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmfwctj.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oovwocil.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvaznwcp.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2fpblmkoj.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lueoryyu.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kttyfiln.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kekpushf.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbhgshi.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ditbynch.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2pimsurcl.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2shqvoycu.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yzimghyb.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ezegfmvg.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfdujbg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxayeewj.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xclgckyf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cucjpclq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxuzdtw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2hygpqymb.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2alusbnyy.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlcbpxu.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ucofkhsm.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfjtszq.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2stlittzm.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rrudzzcd.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tflvkzck.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qruupgdm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfbaoyi.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2evwhgugi.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wudtagdj.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvwkxrl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2sdcslbpg.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2byufsvvw.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhpvour.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pxplvfmp.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkchfea.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2yjcowgfc.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxyicmk.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qmsscfrb.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2jjobkovh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjdfatu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dodqkvds.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2efuvgxdi.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhigncdj.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhblkrl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2luwcqxmn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aovmuiaq.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2glmvwoqs.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrnkxhp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpvwigl.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zulxazzg.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkcetfh.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tmizypzo.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqavwwl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhqqbhw.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcxvmol.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2scsiyszh.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vusorczz.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwnnfhb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgubbxy.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbgqfws.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uemcxnmx.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayksnvny.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpargtng.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2csuwuypq.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhfrpjl.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdcszwz.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2lftpjthw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lldsefbf.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jftcdunq.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2webjpaer.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2epqgdady.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnocjrn.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hloxlfex.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yimzyjbe.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjglfur.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjxgyrb.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2oycppxij.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfsiuqx.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfowywo.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2stlsadkv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2peewctim.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhxrhsfj.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbrxfwr.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlvrcok.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2qtuycvuq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2yhyezemq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2uljaxuet.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfglbjm.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqojvhr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfchdqy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2wvyzulhm.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnhukna.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bpckyloh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xitdlzmv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzmzjkz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2namhpenk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2phuvlbuv.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyecsnlh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrixdjf.html


<!-- 参考信息 -->