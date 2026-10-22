代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlumfkb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdkrncy.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2mokzbfzq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2cudzbvgw.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wmquhvta.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2afcbnfud.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvropkjk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2eoutczlp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2iccypcgm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxrmsyw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsiahrpj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwfjvbe.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhjjync.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqxqqnl.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcebrnq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzijswk.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpaiopl.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxthngql.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjtlskj.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2znggfvvi.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2ukozygfo.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2cysedcbb.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfdcvau.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2itdcbbte.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2gsuiahla.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2csdbgecn.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2btmanqnq.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eftrpylk.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dbymfkoe.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwlbnfn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsqebas.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqrxobg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2ldukuhzk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhduyhb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2muzeesmc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2oddjswbq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2arvaojnb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbpprxb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhkojnw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzedsey.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2axmzveke.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qghktdty.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkyeprp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rkfizdxc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnasmku.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdismlv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2drzakjce.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdndeoz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnuihlg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmhxlnb.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2skinqpfz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rneeoayz.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfsgyiy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2myowvcvl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zpclznul.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsqilgi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbgimzq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjmfvgg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2ccaazttn.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfandfa.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzuygzy.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkgqpxu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2pnybfnmk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxozvqm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uielzmnl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lovwttir.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2twgzozwm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhvjilp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqyicffh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2upjqhwqr.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhivltl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlgkcvj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kanuczfo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwtagqm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2edsrbsiq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2atktkxmt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhuymii.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbehyvhj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxrnhko.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbjbhhw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xgoqxoox.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfbfvyj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nizkmizz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxdoppc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2pypaceoo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovabraqw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjuimlxn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2wgoktygx.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2skrkppxr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzlsvwm.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cofmwdck.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkjxpdq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgbsrjy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlkeoyu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2cetgrzhc.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfunmtc.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzitrdar.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjcojmc.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywljbxcd.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2knugmgpb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztguezso.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfurtrlp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hbuuygdc.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpxbnbw.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqdxxet.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2flsylasf.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2grdwsvbx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsczqnt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmgkrzz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjzupzl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhxieub.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xuommkwu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2otxqwzoq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxqdywc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcqqtel.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgypome.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2reatqhmy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cupdwdjw.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2puvdmxgf.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qemctcwj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2swmqskvm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyrdrkl.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkkrfno.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsszdbd.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2xysninqb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wuysehtn.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jnuvympi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2exllnmzi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrbakon.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vreyfgta.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2nprlojqh.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmnfqmj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2kedhvxld.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2nowlrwvq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubslrayd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2caposvci.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nikwdwrf.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjhfjno.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2gureoxjg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcdjyen.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhxsopcw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwpzvyh.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xznblcaz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rezzsiem.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gtiupknb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbntnfs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2urawzimt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2azhuqasp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2qrslpayf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcirqty.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xaugkjvu.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2fahbalqv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovuekeie.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2udowcnwh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvrovvj.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2hholayhl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqbfhmq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2gxquhbfk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2nimucxiw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2utnhgxlw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pzuymwut.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxqdari.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2komxlieq.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2gclxnusp.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyoxbef.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2trfqtjvp.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2swhwaqur.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrokcae.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xidsarwr.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmugvarz.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nugbxfkf.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2olkeocou.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tdiykgxs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfxgjov.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbkamsk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkrxrjk.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mjiflint.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvpfatl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfqfqbd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nblsgwoz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqmqwce.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2oknevbwk.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2jurxtusw.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgmxuxl.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ccphvvxb.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mqotvjsq.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gocjtrcb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zjlvulro.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsrtyoz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dpepbljh.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pfigbtcj.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxktwwz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chefwmdu.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2reifhswu.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oezzuwdl.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lafngpjc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxxitsg.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gnscgirc.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrhxaoz.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2btorpmxa.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhcmjoq.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nujoetrz.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvrpreo.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhacrwe.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbbdptn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2compqhka.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yulpowbb.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wuucrqwd.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxwimsp.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2sozgbrnh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lydpjuqc.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxykqelc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqujenlf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcogbxt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2slvaruky.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ixglnoqf.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvssnfy.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbaokim.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2rhttgdoq.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzqcfrs.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yhspqxzp.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qipdhcpy.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wdutqaoc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ouruqcro.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2scpqnfag.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcmjbnn.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kmyrymhj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkflula.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlxplvg.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lurnjoge.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxwgnlg.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrhmjib.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2quadlipx.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqdkgur.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2afkymdpg.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2qellqaxr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2avofttoz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjkhvgr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkjktls.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cirvfwnv.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2egqojynv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fallkxfe.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpdijpy.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xthuinwb.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2iulhvxfj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2zltldlxp.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zoazdjjd.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2zydjbpua.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxxvorc.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2woiotofw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ypamwuuf.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzuxssp.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2almnzqgm.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2rypbrrzw.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbuaudi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgfhhik.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqrcqzo.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnbrqkn.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpijjncw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnjhgvm.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2xnotwmgx.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrprapsb.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqbdqll.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2hihkcxnl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbmrnbq.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2samxtyai.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iumkxxsh.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnioyjs.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtcsbup.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hunsnmcg.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2svgmadqc.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlwqrbv.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2scrwmtuy.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2slbdapgy.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtlsdbe.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2suycebgf.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrzagyx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nezmpygt.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2urjfygbz.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2vuivrlpk.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2rowcohry.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2zenspxdv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbipfyh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpyrzzl.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzclxne.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgzefec.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vikomknw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmpluuh.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2cspvgklb.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdzpfcj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nocvfhnp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxqzkmg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2usjgwyum.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbsckyj.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2youkbzyk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgivnoo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnbierk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuufkqcq.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gavxxssl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzjcqeq.html


<!-- 参考信息 -->