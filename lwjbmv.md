代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlfvrdn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2hggswpna.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2owpprekl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2fskpccfs.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tomikinm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqaiieyc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtabsgvx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2oryeheyf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2yezisdbp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2whsctbfw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wndjbrnh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwdltvo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfepgrc.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2imzjhlea.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2vckqvmui.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyyswddi.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2opyjphoa.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyvxjfz.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gcphiueq.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2lebzxaoa.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkalysm.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2leiirfhb.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhxssii.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfghyrz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2llsgqvrf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlhbtdb.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xeexlquo.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gbikqjbv.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lvafqigj.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvtbdpv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdefkaj.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2wtiqivlc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkxxccv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzlcyjc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2kyedepjb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhvauzn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2krrcmpae.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2zaonguqz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2taolklpl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvjvtqs.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2usmvytjn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2behgnffz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2fipuypjg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqcyooo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwubmop.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2duiziqty.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2hudhcwgn.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2frwcnmwo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2fcaunqes.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mfiqrgcq.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfnvywg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2krmokmll.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnpcfrk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftducaep.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqjgfwh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2kyepjbrg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfuxafaq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2puhkaxcz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkhgxme.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwaefri.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uzauujwl.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2enicdurf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2qthmjkaa.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqdgghd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2odhacqih.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oubvshnz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzghdjco.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwuefci.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2lakkknxe.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfpqhwb.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2gfuqmwkb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2iktmyaty.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrpsdhm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2munhavsc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2gapjncat.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzkiadf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2svomzyqh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2cplrkdlj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgpbnyb.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wckcubaj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2tllcnpcy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwypsmn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftipfolx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwqdlnc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjwnjcl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgadyqgb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2avnowekz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfeeqgh.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtghajv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbawoyfu.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tcoevkok.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdpsygk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jblnbqas.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqpqhwf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2yflxtyar.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjsedvo.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfanjeyn.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2useqdzwz.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnknizvd.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qebbfmdf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkcxrzq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgvymni.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsodlwf.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnyxsep.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tunjlegy.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rjartyno.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2epblecbq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmuctsf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jylhrtbo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2tynnphcr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2uijyplij.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bxntclol.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2thvnjmaa.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdghozql.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwcjcdm.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ciktdjup.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmyyfhf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzsxefw.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kclvsotc.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxgqoav.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvckzvvp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpewpoq.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvexkdc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfldzxve.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2qylvttvb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wofdqtna.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2empydwbw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwyjuuu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2jipfydqe.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkvznru.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwtcsxp.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpvgejf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgsojul.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpdzmtt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2clzjbmzw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kukaclkz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2runswdnm.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmmvsay.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnywljv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkexehe.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkunekl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqwvyob.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtnecpb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwpykuw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ujarmcpv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqexoyjq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2luhnnapf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzepwmo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwgdnzq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2znstqznq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2faknjdqc.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2gflieqwm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqszauc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2swewytya.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ukptrwmb.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrlkbgz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2szaqprur.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2djyrmhlg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzbkwqz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2izryxxie.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgxrcnc.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bxepwkhx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zdejixcy.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2jardhmth.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbvtfmy.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zvinsupi.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zqydctkn.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hubpqeqb.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2beplilgi.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2qytucshu.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmniuum.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2znqyyhop.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xzavxljb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcdvzcg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwacpqv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbxjbrd.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxwkhaz.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shsgsoim.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmussfdh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wlahdonl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvowsaa.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ekztiyuz.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2nspbpmik.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbartwd.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhmqfpb.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgbwwjv.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydyozcbg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2peueswzh.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ojsnosqg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjzlxyh.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgcbkxm.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ercuwrrl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2egqjlqmb.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2csbfffbz.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwafedir.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aazwnydf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhutrxt.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2irmolfxq.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjvprun.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqonwqu.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdzayde.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gahgyotp.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tyswewtr.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkgadxl.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2brihsddx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlgymqw.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2frclzjqp.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gktktrat.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdvvorm.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2beddrbqd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmyclkfl.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eawobwek.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmnkskh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wketqpjo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnwsyjp.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtepgjl.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2tirwghrq.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrjsqkn.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ytytzgyb.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vhirhkkw.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mayrsrrk.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyxifry.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2awetyymr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwoxyeu.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2weiehnkl.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcpllas.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrarkub.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwpxzgi.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgyjztg.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbtjzug.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrjksgs.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhgihgk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvwclkt.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qflodmyn.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzwmeui.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnxrtdm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2wsepatbt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xugkmxwe.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2lkiufdkb.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnoxmum.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibisfpxo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2olzvfqzz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhtcmsb.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dthafvdb.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwfefsd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2jsucdnhx.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2erkmzsbc.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2hxirjrkl.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgaskfr.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdxgcko.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbzuxrn.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kighephn.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2pswmqywg.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmusrvm.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2taptblde.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjnzdsz.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfxnspv.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzbtjxg.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjvnojp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ermdxwlm.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2blkwgydv.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bayjmshw.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxzbvap.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ihsbgnpg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwukhzxa.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjiendc.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqnjjwn.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kaskzrkf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2eiuvqbbt.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfxxgrc.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2grhfbeqf.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvxljwi.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgyjvyso.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnjyhds.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgxdnaz.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pgyyewwv.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbzcvqb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xcarsghz.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdumfnd.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2urzbgeke.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgywbhk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2peaegxaz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzxqksu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxabfrl.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2qjujkslw.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbseidb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vicpjbjo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2nchfkcqu.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ralxgakb.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2llomtqev.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gxosjinf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qluuejvv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbdkhub.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2suyqoobp.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcsqjdzi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjdkark.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhfpzvx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2abuvnlpi.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xeukrpdj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2adiuiisx.html


<!-- 参考信息 -->