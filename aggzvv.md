代发 wailian999

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2lafrjsyv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2moqztzey.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdxbrrx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzuvurp.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbcpydg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qswccfrf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdevfig.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvxrran.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbkpklp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2raximoxu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrjbbkk.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ktyawqde.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdyeuhk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnifovs.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wharugiv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqsoenc.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ifshxbdh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2fypdtrcq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxmjatr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2daredmhi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvnqpum.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mjyljpnn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2dikjvzjv.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qaftfanx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vlftuspq.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qoiubkur.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2bqalijwb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxoxzbx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bulncydq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbqoqsw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwiibxl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sghzjama.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpajqlv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtmokow.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2adwotyih.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2muobqncl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2yzyzygab.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2iucwwcjj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2suwtsekv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2mujglwug.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2stvmikiy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2kketcven.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2veohiqzv.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtnwcro.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2liilmglt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2enmvfqcu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qffmdwtq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wojbqflv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnjonoh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nliewerx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjpqaru.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2zczwsfqb.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqrmyjt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmdlmyv.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jiosdjci.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xladraxg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfoozxi.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tmixvatg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqfbfkw.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgycjvbw.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdqfizm.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aeuzxwyb.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bringwbj.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ustfmmir.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oryjklhy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbyxpqc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzmcjim.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmbyary.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2reboebhk.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ombawxie.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dpngwhgs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ingbiwyy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwzsgug.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnddixr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2clxabpmy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xairozys.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2agetpndg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2dexwixfi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzyrrlg.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmcpxqb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlliqlb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zucquydn.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2thuxulpg.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnuloarg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2eubadsdz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2svphgbsk.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqtkoeh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbskyyf.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2woqmhpwk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbkvjpp.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cawwwheo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2omgupxop.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhplffm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wmshbwki.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2mygsmoqy.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2disicnpq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqprsko.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2kmeoxzwm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqpwejx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ljgsiryv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgphasdv.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oevdwaqr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2bszarhuo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lshqlxbu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2biexfsyi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2woelxzky.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhkesvx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2janhtnry.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jffujays.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uiitrabg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uderqxtz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2boycgwzp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbvnyle.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2seulhzny.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kahpkuzh.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2assavxny.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgpxihj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2zavlebrj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2uidlngjz.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvkksee.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2rvyqiuew.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jicmybzl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghduaxdv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ypivhxrc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dtowckep.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2grkyxdma.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qckqixht.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2rnurjxxs.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2cjyavzso.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnwaabt.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2glxrmtvr.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdelifxj.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2millyjng.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2exvjepvp.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yblffyoz.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iecqxikl.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2auhqozvo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbdhscd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmiuvdif.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgummam.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpeefmp.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozochiov.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2noqibzfb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmjbtqf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2deksjqoa.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpqvfsr.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzkmucz.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqxvoyh.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bbylcnvv.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbafuuz.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2keqboijx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxgupmx.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvozrgl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvxsfdj.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2phhzjfeq.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxuwmsu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmhiisw.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnesblkw.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2auzdmdon.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtkcxyp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nisjjfuq.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2npwzuyok.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jeghsurl.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqxqmdh.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrysxox.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdnlhja.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2auatnkku.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwjjejw.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtcbcja.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhubxvr.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbtjvaf.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdzwwii.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ddffsiuf.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhvkxrc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aviznzcl.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frhyvyzt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdrzegw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tblrqprg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2lboibcsi.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hztvomjt.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2fjsagppw.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrcyfzl.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqfizmu.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2faztcdda.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mifpxccm.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2saifhxrc.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2myqjvcad.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlzhikp.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhqvwgb.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cjiwbmsg.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2axpijzmc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2pqhkilee.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rdenvyhg.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjmdxcm.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gagtaiov.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jlknxsac.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hckwwoen.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdpjzwz.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gftljkvy.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2pldlcscn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2uodfnjtf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pysbgujj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2skcztery.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgvjuph.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ascaasbh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nexjkvdc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2onrejqja.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqzwnum.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2jzblbbes.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2kqnajwxx.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cgotfhpp.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2agkyatwm.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fddflrpo.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ttyggzxr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ryitgmkd.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fueibtce.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlbmzsz.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2smeplkab.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ndsknlql.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yptzhadg.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhrobpo.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eabvsvvv.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yirpzyny.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkfgwlz.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2obbgookk.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcsither.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2skdotktj.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2caiowrbj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqxsvwd.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imipiotf.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrfrgtr.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyadwcou.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwurqasf.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gtavfadr.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2horlbhwx.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yuiuqoga.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdrvvci.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfspeir.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ijewfuiv.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzarmwg.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2uoeozssl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2voninwqc.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2epniytyr.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2lamnmyxe.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2eayfxemf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhgnsxi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxorpix.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2bejkflhp.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkfbzcm.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bemzhkbn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2mabigvls.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2etmxrzqy.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwzlfqc.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dgaznvra.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uupksfzr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bitgxnfy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2euvpijhq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcitybyl.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbuhrcso.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcurogdh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnbtwcy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxtnwbq.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2twsajpyg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2krvwzpwm.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2hffahtro.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdqwtpa.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rspnrqhv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2lscvlrun.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xwulnimd.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2hlntsssu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2xshtpxve.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbjhcrh.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2urvhlskf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnenfls.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgqyhqd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbngpiyj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2trkdsdmu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jonmsvlg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vywruqbh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtlhnem.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2iywscday.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jdyupwde.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmqhjgy.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2sahoznmc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvooitx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjacvxy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrsqizr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2asctredw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dglwzplt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvgnkge.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2peigonpe.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnfkgvn.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yxiwwepy.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkatout.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzbdigs.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjucwse.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fuknqjez.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2znlfgftx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzejojuh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2eovcsebv.html


<!-- 参考信息 -->