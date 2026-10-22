代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrruduv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmlrouy.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvinrjc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2okleriuo.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmfvxjv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgewzhgs.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2tglidluv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghycueyo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpxffcn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeburhet.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnuuyar.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpsmvim.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjgxzqq.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjxemqq.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxaptfd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sisgawvf.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhkaree.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzfhddj.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgvhvvf.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlyfcuk.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2abztsdtu.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2lahesfrf.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqdasty.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2aacbdjrk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdgtflc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2liyvfrul.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcgbgbe.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbfdrca.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhrxokd.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2lzetmwim.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvnfvjt.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2njcuvgff.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2pcucpesi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2aqeykgjw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2epppjbzq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgpannb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2cxnatfss.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbdyvra.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2svwvegqm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2suxffbep.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vzcjbwvd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpxrncz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2dachkmie.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jxegksiv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2saadetnc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcgenbh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2offbtrlp.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2diqhbuwn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2umrniidn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwriiqe.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwcaywf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2raetjzax.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2exfdyaur.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnhijna.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lovcgclb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbmfsld.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2knbmhtle.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2viqrmoam.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqkrbnq.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgsjiqsr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cacayfhi.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gyptxisw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2lfncszlz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tefdrlji.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtgdgqw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2plwnyyub.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnegzvy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tavrhppt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2chsxwwnt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ximjrcua.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjvfnpm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvryctl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhdpzkk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxvhrpe.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2fajrcuob.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqctllq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhslhgh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhayyqeh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbhddii.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kfygrsrj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2aerqjewy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbcgsiv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vaiwhhfe.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2whxlfgwx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2uohvdoyz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnquceh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lafrcbwt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwvzkxi.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjfqmwc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrykpny.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cyuycbrw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyzgeop.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgqurua.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwfyzpt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnlcbwh.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyxfmmy.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uscqputz.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bkajzjoo.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtfhvip.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2byaarsjx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rphreval.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgotakf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvbywzc.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxhfogx.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxexliaf.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2etqkecqy.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvdyuud.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2auhcnnxd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2olyexhya.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2irfgwnqv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcdffaf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfucxgl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2zugqzakk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2utqycpgh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2gxssrwhf.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzyfskq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubuagpjh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oliorfmn.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgmpxbg.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujovboif.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2atsekhli.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gipupsox.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2typuoufp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wedokder.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2etaatadl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rojksztr.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gckswkaf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2qszxsorb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2iywyaoag.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgpetgm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvurchz.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2loziqdgc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfoffbv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2bcculhzp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2okfuivwe.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqvqqza.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eesjqllx.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfllcval.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjxburb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqqqbma.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vakgtcnz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkyzrexw.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpbmjni.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkokbhp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvqnaan.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bciaimtr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbywdvhq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iljzbimi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2kjswcayl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vcplpclz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvywfeuw.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2dijpysae.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbtekfp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2srztvuao.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmlaksz.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdhkbnp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrlhihd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbbtgsn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbdwooh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdbekwv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jmblocxr.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2idoehkjq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sahxmowx.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2aqeioges.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrqcldd.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2speklrri.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlysqco.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpslscs.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2myfcnuhn.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2opithzcn.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2amndkxbe.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtwwatq.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzmxljt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2hetxrmfj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pamfjvho.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxsgwzh.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qziofasi.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxqndas.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2obcyyuht.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2frinqfar.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqpljst.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxxwikt.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ievrxfte.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2znisstes.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwidcgh.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqaziqw.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzdmzxf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hcasnewz.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2swnvzmnv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2svouaoqb.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xcunqhwf.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcdejjj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmazloc.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpyqhfy.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrofgnl.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnogrck.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2obaovfkb.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qdakebtp.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdyllqs.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkwbvnt.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2uklyypak.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrullkv.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rervwptd.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wgewbvny.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqchkdp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2jahahsjv.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvsddse.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2smtpxitt.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cgnqnotn.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxhbibc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mumkxbtv.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qocazlnd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rutzjahh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2czingoff.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjouyce.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rqurqwva.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2yblfogfx.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtnfbuz.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2syjbexdn.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hsogttqx.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2prrselnc.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fiazohti.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2aakmmdpv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpofvrc.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpugudd.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfbtvyx.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpsmhxo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2uikbaoys.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wilauabf.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dhonaasr.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvruvvt.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjqebjx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2gufketzj.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdkvylv.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvmzczn.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2alwvadgn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2slyrytoq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xevjlkib.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgbyklw.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcptuar.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwvlntt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxiqqrj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sotxccvw.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2venhhwcg.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbladyl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2jogebdxb.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2iqiahjwy.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkokqna.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfsceel.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgiwjdu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbkpfob.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkukmnl.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqfcuvd.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jtuaqsqw.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2dwffbesu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuadjjco.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2monjxchx.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkljyutr.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxyhgay.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2djlvspks.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ziktbzer.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrwifcg.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdonwsb.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfbljkp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zecajdsl.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svfgnrso.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcngvxez.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekohepye.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hesxvrfg.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbzqjvg.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdpuwfx.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ujybeqyx.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2immmfcfr.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2txdghuvx.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wepkvjyy.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpqngst.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvlknno.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ayowhvuy.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2agudfvbm.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2dekxwafw.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2awutugrf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjdohvd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdzygse.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtzqszh.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2eqsmzrno.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2evirgmat.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsbtbxk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcorfxs.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfydtrzg.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ralwcmts.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zgcupuyt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkwlqqi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ginhyztd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbbeila.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrcindaw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtstsypz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhzhnfq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwfbqxr.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yitteiuj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcyhyqk.html


<!-- 参考信息 -->