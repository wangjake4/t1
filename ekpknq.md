代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2aabysgef.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyquguwm.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2xalbftqk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtigpzlg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zduiqwfh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2iomixuzj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2csrvkldm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmragbmc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvvqykd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2yekscsyr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2teppwhwl.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzxmiqs.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2lyenpqiq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2fglebvvm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjyxdrn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmqagvw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuukhvdw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nanllcvg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjikvgbb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2tyccteja.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmshzal.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvwigle.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2otssgqwe.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rlszfigq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nneuoyhl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2owyjjkxy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpaqhwmp.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjkuoyr.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eiufuiuy.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxwlwlj.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eblgjqzy.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2aglhzerr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fugqqeht.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfzfqbu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhtkemw.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vkiryopj.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2swmbncha.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cjajlflh.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2avcvlyaj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhwrlqo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdpacur.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxrwvee.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2kuixcjoe.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ppltqfbd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2oiintcrw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ietphzkx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2kixhrheo.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdtijlx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pibcblmy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaryhqim.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2whjirhiw.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zywkwjpi.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbfmclk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbldosb.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwnwdkr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnflfef.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdxmald.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hytpttya.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpejhhr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2qaocaheq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2yeoiqqoa.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkloeec.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2radjoetp.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgtmayh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqlrffo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2mccunmed.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aexjrtbv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2deqdbddx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwdyviw.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2utzlklco.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqfqkuu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2flcrwata.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfigxbe.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2joiyqxap.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtjwvxg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sajcanuz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vltvehtx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljyjxifc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjoqcev.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfogumro.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwznofj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcriomh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgikwemo.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcfltmb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmtptur.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2zvihoupm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jidtxggm.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2lwyutowp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2dymeizud.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2upoizvoq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwfvdxf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2alfehxvw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxbevki.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bxasguxx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2odztmhlp.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2wulrwuuw.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2owgqqioz.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxxciur.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ryaelhph.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qixdrkca.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2msvmyico.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2tiglsjoo.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvsqgmb.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxwqkhl.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwmuczv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2mmuyhdik.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpnkplc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jowahvfa.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uoohtqfo.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhvyosn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2djilxdod.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2msdboxxh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avuqcqyg.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsycvdb.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2jilljqvz.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2onvmxufm.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhckazn.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2urmguedh.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdxdndg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zztnzndy.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2gehjdycz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yeekyzsr.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lbncwzas.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2gewvmfty.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtbtyno.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfiaukqj.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgaqbcin.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltepsxii.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrxtfcj.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2abpdbpei.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zudtjtgo.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2nctqbegb.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2slqxldov.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdzbqmq.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2spdywhza.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlqvphq.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rpyervmy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2zfysilnk.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlubrhl.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvtnjas.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfkzdme.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2hzeahuvz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjyyuvcx.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnmkfsi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2opdhkdcv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yptbwjso.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2agabzmxm.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lzktcnxf.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbvdzyd.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwkgbhz.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2mysogogc.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2upoijsch.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ritinjzs.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wldxnoef.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmaaiuc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2sejeytbu.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2qmddfnmk.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nthxgxbq.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2srmjadbb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2clcoycqg.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xjyixqyh.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cshexcno.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2avldsidc.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ydniihfz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tcreazxc.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfwgfby.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wzmbbhsa.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxaufyf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2nrexzynb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2duwheirk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhhoile.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udayidol.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuccuekr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyuwovlt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2atwsjjfp.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pclvgvlj.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfhffim.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2hxccyija.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2yeareugh.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2rwikqloh.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lixcjmbp.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzvvnfc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2uenhptxy.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvcfmzr.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjulldc.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jpiftgpr.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrlkunv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcsomep.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwbmtqs.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyyflxlr.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvuqgkvm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqnzsak.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwidwyo.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgmvohm.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkzdhgc.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ailckhgo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgxkiwy.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdicaqy.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phemmbqw.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjdemcq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmnzjve.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfmxxip.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wisbpabe.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tymjgvjv.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvinnod.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zgoaubgc.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ivukmaid.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2owxyjsrl.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tymtyifr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlxfzpn.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2oafloqvz.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2iooyzhxz.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2avodmlsz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmiyaod.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2batilzlb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2iqnjxyza.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2cijrwnvm.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2glsppzhf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtggkkew.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2sobdeesp.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2xalyqcel.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2iyybcvcx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnrqvle.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unadbizw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2cqefzofx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdslzaov.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2qeikiywx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrrckfo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2iruvulhl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oesjtnlt.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyjtwdg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2aqltbtzf.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2cctzakan.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfebhtsg.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpxlghq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2qquykhpj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ceolxbvd.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2umuctzcg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkgdwur.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkyzgje.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gxldwepd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2alxkunwx.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2fwntmgqr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2xszkwiiv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kufouwss.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccashhhv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2grchekzo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmabjxv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2iguccsri.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zxaznano.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjjqeus.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhsvgsp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2iihhbety.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hearmwbu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdfdfue.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iikuoedq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwyrgtif.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrojdac.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcvoifp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2admrsvth.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zperjrdj.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtwfmky.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtgfrlt.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2whrmgfld.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2klotrszk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqqibeb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnyhodv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwupaxv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kcighicq.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pnddivwu.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xdchqoev.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2evubnaws.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqmkfds.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvtlvgk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jbexkujl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2bigzqnvp.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2obdtqvea.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxchanhi.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jabuxlga.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2mazeshqh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2llqfgflw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtgrknd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dgujymet.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlujhus.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhlxejt.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdgeheh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wullozdt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkxymir.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2hmganevt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjntpig.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2zkevmbdo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2msuscayd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2oducufwy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2muthkoup.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhhzyiz.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpbtaka.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjuljaz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpvlkei.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkcxvuv.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwppquy.html


<!-- 参考信息 -->