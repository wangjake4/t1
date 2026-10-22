代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2webwcqqy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzbgpxj.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ghyrvjol.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2biqujorf.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkntycl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2uifmevej.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cssgsgec.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2movfdlju.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkpadhj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdbyfkt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhfkkyx.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsocykt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fivaybkq.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2squbexez.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzpqgrz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhlohrh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdtxcrr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2calezfbv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2gprmkoef.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqqqeqv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpqsmau.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2muykuujw.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2fepvmwvx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwclcgod.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2bitrtgnw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbweaef.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2tutdnwal.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2uafzopep.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2uunkppvp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbcovyy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmwatww.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ruymfnnc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cozcigqn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtjqnkk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2oabellyg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwbsppl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvyosxgl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2scfufxbr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2aihgsokc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2uemmsmbo.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2npwudfgb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkeypbmv.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ydiuyspl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhvfppk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2boqbpwho.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kiyoqptv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzznhems.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtqkgvi.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkmbzsc.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdonudd.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uamimklw.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kbeobouq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpnbtppy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2plazcdmk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwegmve.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqijzoa.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwlcich.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yywtgwfq.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvjaxcl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeuugnqy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbsptpf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2lxttlhoo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2enrwhnyi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dovoeyiv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmacyzab.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgcguhs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxybtml.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpulwkf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlmiuui.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkfcxyh.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lchkgowk.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2heapppju.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvfytzi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzqzdew.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktuwnaez.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgljsbo.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2imjhswmt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zocvqsqy.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iedfuyzp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2hpllumog.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2trijfaxp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qiudfmxp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ktntavyw.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qalnxuqw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnxfdxn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2blreprkf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sogvoghv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fofkupvs.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtssrvuy.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2icswsoix.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfusrep.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zeozrfuo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrwslbo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxsijqu.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bnyaaxfm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgofxjvx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbgkvtt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2esyuhvip.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xofwatgj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lowivtjg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2szpoqame.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqpwdhq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkouwkc.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2deyekhjc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfvbsst.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkeztzf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bndhxufu.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxutjrg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2aejlujre.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2goxtjapx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgrusvw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwfzsmc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ndentsii.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fltsnlrk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zwcasqqc.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2kdinbdob.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ueyjqgvr.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nptplmxd.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yyssqgwz.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdkdxck.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mucfsskw.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2akttogwn.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtmmwjh.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2onoxeotf.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcgrzfk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2qahwfnzr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qteppqzz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snjmllok.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bynkigph.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgelyvt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhmosik.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aqufnlfx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzuphwek.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgrvlja.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ifniulql.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpidthq.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yktnboic.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qsoadrpp.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2idzdrcsn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkaslkn.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2frsunmug.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpbbciq.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnekzfr.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2djunqgrz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iluuaeec.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhurswig.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcxfhhi.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpymvmnj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2epinzlxw.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvzudcy.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhtjrip.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhcimgg.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xdilclqq.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kubknstf.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqjxcyi.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqbetxi.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kowxcmye.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ougnjfsn.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uihobmry.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rusaelqu.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2koqaloew.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2pigecihd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqyfevi.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvahkugy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxmdeme.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grkfjhpw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2aljntedz.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2utmlmqtf.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2meniqtwe.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lidlnxzb.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2wchiymdq.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtzqspq.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2clclbgzc.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkjacph.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iujjbtku.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bknnsrot.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2cfeyhuwc.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdkfrek.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhocraa.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2xystkdio.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvsqcfe.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tiepnobf.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lejwvlpr.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwevixf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2eywhikco.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tzsqrgcq.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdlcrqx.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2bxaflntd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2kndfagvc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2macvdtrm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2kzuxdygk.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jskkjmyz.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqqqraz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsyteacm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2asbrpwdf.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqaatcnl.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkpxsnk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2sbabtaxl.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zifhmfkq.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2cehmazpx.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfyilet.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2iyeivjzp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxpsnid.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2extjqqha.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ooiguegl.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2rtezcvnu.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtghesq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arojobud.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkzdqks.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhqcikb.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drgfawqs.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzptxfcp.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2oznioftd.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njmgchzw.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2illtjrpu.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2shhuopfu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwsczzh.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhbxiut.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kubbafox.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwxwrov.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2aukgchrc.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ujasmugv.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2riqevwbm.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqatapw.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2abtudzye.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2iphhcwex.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwzokfy.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2armwpdax.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvvyopt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xretlcot.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ioandlrv.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2txlnzcvd.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqzaqzp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrdpipu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2skewdoqd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnsqemo.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2cvijeasu.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmlcsmo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpijtnlj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2qmisdrvb.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfhdzsq.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gggehwqz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhexadm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxehqxqn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwxbbmn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xstsfndt.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2iytiweqf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2verkmxwg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2braimqdf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzspxsgy.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjujdcd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2floqppro.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcgwtap.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxkjyqz.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzccflrx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2iclsbfqg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpnoyvl.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2bdblnfhm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2fsludnvl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2thswopzu.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mllpuoth.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ogoigykl.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2jztpkdoh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhewgnw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxfzrqg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2koelefjr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cebyursz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpggjlc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2okjqqhbo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fowtifbo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlmrens.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2duispuoa.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbcpauz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pckfoymb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2btdwalsj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtjedwk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnztldqw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpzbqky.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmwejsi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqiytpi.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qquelsef.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvisdrm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgopbmj.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zktrrykr.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbacidt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hyftyqcb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2maavezcj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqeekkz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jwibvpad.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2twaecqjq.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2homjjvqg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zqatqiqc.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mldgroip.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkqcyaq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkqsaxj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmjvyez.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjeaizf.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cxywpezx.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfuzixa.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbufxrq.html


<!-- 参考信息 -->