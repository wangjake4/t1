代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2znsqsdab.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpsuras.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmkbwvr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwtrsmt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwmeftf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxixmka.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbqxmwa.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2ciheemfj.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iytdeowh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2zimlyouw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhrxozo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruldynjl.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvzaocg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2sueqivzi.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwesynvi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvozvreb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lexoyoae.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2jadnbuix.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2tibhijjn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zaviqbdm.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlsibrdj.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlvwemr.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xavbcnev.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvthmnpe.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2bespkjlh.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2xiadpjwe.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2pnngwbky.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrszpth.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2arokriqr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nahjndhs.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sdujqthm.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bancjjgf.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qzyahywv.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2qbyiegtt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oilbhpbk.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxbzero.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjhthhl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2dczojyjg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmyrmjp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2zekovizm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2psmevsou.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjcvitn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlziewg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2hlghywpt.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyfuotd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rysbzgqo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbpvggt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpxoxiy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2glzrzaby.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgazocve.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnkrtvz.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ohyosvxg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmquwzi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vjaidvuf.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzrvfwk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbdqfrq.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2csjjvrgc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxoqakd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vkemmzog.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2glbbjene.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbegbno.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbdxmrg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2yybhfhxr.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2heikiimt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fsczktyn.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iipyyrzi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2fxlhlcuk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2taprlgqw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yaeheklh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2losldmuw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgvvmmp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2umhuznbg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2veqbccqx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzolarwg.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvyaoar.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2hntvotlz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2sakuitls.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2apmchhom.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvszofc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqifoqc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptuthvov.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzptvnq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqvboak.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yyefdrgi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohduagym.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2adpudcsr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2effzijrs.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwmhmgb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvwpiul.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2imjoygve.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxusyfp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2xffpqroo.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvmnzeb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2itdfmykh.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2abqxbwyy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmlderx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjcfxtuh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgnhrwl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjhroyh.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbigaoo.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2whoskdnb.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcwrrei.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhseqwpw.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsysluk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uymfkadc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2knafxjao.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgfyhgv.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcbdfnb.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kixjuajb.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdxddej.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxoblau.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzodlbk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmvupgv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqqnktm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2gldvixmz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wprdeard.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvoswjlk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfuvgujn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2huzecttd.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrxmhar.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2glintbxa.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbtsiwd.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2efntzqhh.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2iultgkof.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlyyush.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zakduhyr.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fazlzvlz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2almcjcpp.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvpxeig.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnjfvdu.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iezlnyrd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2axxqyrnp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfddbzy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2etcapbiw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsxdvgg.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lypqwfss.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ttosckff.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2isxobdkc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnghsbmg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvwxaxp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2prfxywfw.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqorentv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2rspsfskt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkngmsb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpyqpfob.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xezkaeum.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ihaxymto.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmtbvco.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnicsnf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjakapi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgjgsmb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqxzkrq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrgzpgn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eevnjqfa.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2idkfkzks.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2xeljnflv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2okzzmmcb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpgpjmn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjhqmrj.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2sgyroong.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2wijqwiyp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jncgueri.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2udjforot.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgeeuei.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjjwowk.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjkpdmh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzncsgo.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsbxvei.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2uqocyudq.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2coxsgajr.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2onssgcmd.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuytdrcr.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhzzghd.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwmpoeg.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hfftkhrf.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2itwpkthv.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcldggt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2xnabjcip.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcmoywt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgwqphg.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fdcvwsrr.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smucbtrj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhxdcqz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjyyume.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hiozlaam.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjsxqwj.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2thnoaqmg.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wddfuizm.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpebyrg.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lqoyegpn.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfqxetu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jercrxyq.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2zaagsiyw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lkguwgfo.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfpcghv.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2tdaksmld.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iibvmaub.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwivsvij.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tepvpvdk.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kddrxayj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqaxphfv.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqtfwys.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmhswuk.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxjavwg.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsitjdo.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pnoxcksb.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wifowcht.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pldvftkt.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2olzbpqlc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzqljcg.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2igroxaac.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrnpqab.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ujaxjfii.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfhdeng.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvoeeuj.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojoirqui.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhyfkipf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fixsqakq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2vcszaefc.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vniyiqyo.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ymydkbgf.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnnxcxo.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqezndy.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcppvjg.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqmfyzp.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgejbiv.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jlaxpedo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2muaswgli.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfbjswb.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwwetzb.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lskezkdo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrtbesl.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eclrckiy.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdbdzyg.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tkebuubv.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fylvaqhy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2spxsdfer.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvergwy.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kjizdjqz.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2qouhldpr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2skfnqjvu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2upwamxlt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2hnodwckb.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwojrozb.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsiduxu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkguldda.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nykostmo.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbbhqeh.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlapknu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2nlakgegl.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2esmehxoq.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjvqnap.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpbbzvf.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2omneiukt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtpjzhp.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2azvnnmtk.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2whkmdzqs.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2utknayti.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2yufhwebi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwctruv.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qymstwes.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvlgdrf.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lguzyaul.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqavqrq.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2pjeimhug.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrsjsko.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sitnxydl.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsjrmul.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbryditg.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irnoecbn.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnutmhik.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzssouey.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgpzlnp.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlibgma.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdrvnlh.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcxsovg.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2zroijixg.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lavhczik.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2biftwohz.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hoaklgsb.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2oraszebm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqtbudt.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdntjxjz.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwtehat.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2hqyflsot.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkhsndd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2kiywhufs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2uekxaazt.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2kschtxlm.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bijbfevo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdznmxs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxagnjj.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhsgdht.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2otqgisqx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhfmuth.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imvaeolt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ouudjfze.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhechph.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnskfqqb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2stsqnbhw.html


<!-- 参考信息 -->