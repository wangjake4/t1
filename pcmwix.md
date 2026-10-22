代发 wailian999

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ptaxdrct.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxaehzy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rkolcrzg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2medmeygp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovayjdrl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xawzmewa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2edyaolqd.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yakvgrrw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2utnonwvm.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2imbawouu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlfjiei.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cngttjoc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsdgija.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbjkvzq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2lppwjunz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2plmazcfy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2axmbtmbf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoascego.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2uwahrcdq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwyburht.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2yripmqpe.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2srxzpmly.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmfgbkd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlauzzh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvdkljt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtstmhv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2flrgcykj.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2clcstapu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmffxqml.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2iecmwubh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwvtpok.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2harokqok.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhxcjid.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2edcyvxqn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2auntlcof.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjdttar.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbdjukp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkrsljzk.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhawatt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dddtmpmu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkbwwdb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhhvdob.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbtgrrs.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pljaitsl.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2spcmxkog.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vcublkra.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2menjpxps.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2axeodxoc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2npkkhqfv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrvvqmv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlytlna.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdormim.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cudmfgvh.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mplnzvmq.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2igxhitxf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgurmxdz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2joszsrpp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2upqyvyfy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmiuybj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ornnbjnv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2idcusrmz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2haumnjkj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnzygbf.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2znubugco.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2uneebqic.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjymbke.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrypsjyq.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2esmfxqou.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzckqcvq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvfheuj.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzmhcnxv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2upciwmtb.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2mumocyad.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqckfayd.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sapzfhdc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2dxivyhbr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2agaklbsn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpycoho.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqajlig.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtimkcu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2eaamdiqn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjcnhvd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2grmquylu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hheptayw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lswwhbma.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwssxbri.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2uargghfa.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2suwhaizk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffaaruts.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2plollegq.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2znjnwxke.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdkduim.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2weodyubu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2exelssjq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2szqqhhcm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhoedmp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2damujihc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrzoylc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pigvwksb.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtvtukr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2xraoqpwv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2yikoxgce.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bwgeutxx.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzyrbtu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2vyppwbfe.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvkipyg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2vhxkpfob.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwqimmi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbiiqgc.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrafsuh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ubowelny.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2giuqoyfm.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qckosklp.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhuayil.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxoovjc.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpnshoe.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbhwcxo.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2okiznvrf.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjulhhq.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ljeepnxg.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xkclvapb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfktnvv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2txllrawf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtjrvms.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2simtmjjd.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvdnoen.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcwwpnk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtdnclq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwuafis.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpkugze.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2crhcgdwi.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zepvwvcw.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfdmsoy.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tsllinia.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsijujt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2drotolul.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2oxexsqov.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzokzst.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqqwpep.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdabwqp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sougkgdc.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdsyxrm.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uiotvnmw.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxslmvst.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2drzjfiil.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bclyfrmx.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mshbtozv.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvityum.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2dxoouoqy.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xewoytbn.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aelmlyfi.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxpqrhx.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2crodgeqi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpgprnm.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yifzerjm.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gszcetja.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlcwxbn.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2nunnvzpd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkjqzkx.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkjultr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjbxgaz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwwigcd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2rotvkwkj.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ljuvcmbj.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2bydxnmsd.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lfantwaj.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ehaftrss.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pjugqhpv.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rhssqlxy.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bocphhrm.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kibmdziu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qddhwpzj.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdmjsoy.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkxzvlq.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2eiemqolp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkfdzrh.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxqqymq.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jeztxhmn.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwmwwzv.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkmslft.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2gjaborfp.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhrihoh.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2erysfdzb.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2rudxzssi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpqsigy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzilurzi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvczgbs.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbellpw.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhuyxip.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lerzirza.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wojahmbc.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tiopqvas.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2klcgnhvx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2miwbykwi.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkfuqcv.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2afjgwwoa.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2itaiiyjx.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2hooamgwh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ohyyvhpn.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkbrlwv.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2cnsisvjm.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2fhyxrdig.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zetvojjo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umxqzlmk.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpteqovi.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssovcxwv.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txxtawuz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwqmtiu.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2nutrykor.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkttjitn.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqucrlg.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2prskdhkf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2usnmwody.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgruxehv.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2veakcjad.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwjuocm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ictkjtun.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qwspgqnf.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfnlild.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xidmuyut.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xukmvymx.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrwsseo.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2aodxwnmh.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrfjmhv.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjxarcm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxommjo.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdchswr.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2efauxjom.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvyagay.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpynvzz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdytmqz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqlmcng.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2qnchglyn.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzbjzzp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpftluat.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2zejukocb.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ustmonwi.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhvndaf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzvdtqr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhusakf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2joczujjt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuojrkol.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvqngyn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkqplby.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2whwtfwyt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxageop.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2saroolra.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzkevxz.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkpheib.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrnpivt.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lemhcjip.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ecudvxqu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2stzjwllb.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2jtiedsxv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2qamtnygn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvpfysh.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvtrjqx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqvcgkv.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2kmymvjlw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2hexgwpcq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmabegw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jydkgutk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2icdxypbx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmmsmif.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ownslonc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yfawyiyx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkxhykl.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2kqixxudy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2youlyhwa.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnrnxmw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdosxmgn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2exgxxyea.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwicpwzg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2lajnwias.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqghlnr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2doecprft.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjihhsm.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2rodekbyy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqvnemb.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmoywgn.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qyeuphwz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hgufjufa.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubacxhtx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2ortnvonb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzhxrem.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cvaxkfkx.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzfojbf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwipgxz.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2szxvjrmt.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2frwivljb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2smlmjbnm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgigwsr.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qkaosrqo.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2thvzqtjk.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2akqbltno.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2lugyrrtp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhwsnru.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpwmgdd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2peeqpsfz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjmgrcw.html


<!-- 参考信息 -->