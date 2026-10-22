代发 wailian999

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2axtiomia.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2mncrefql.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2pkadyzau.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrxorsv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhtetgj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbyzses.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qouyjgmd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2inunavyu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2aontfmwu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2abxgkhxi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcqqivs.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2iztfidvx.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2exwbymgs.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2xljpaxoh.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yoyrkazj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkyhdcfl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkapyqgi.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2erhruweb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2uijydcpq.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzlxyft.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gigbcoso.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxgnlva.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrfotok.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ndttggdq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzwuvvw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsdpgzu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2egqxltss.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwcytnk.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqulnbt.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lsspeynt.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrcvkjb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cedinvou.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mintfnmg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfdyror.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqyfheo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gylhqhqo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhcbczh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2fegjkqwv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2bykfpsmz.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvvovym.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gaguzbpz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcesxwm.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsrpham.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lntwuigc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuiexekd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrrvviq.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2boobxucq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2woyklkou.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgeoifl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnicwfl.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lytzmwyc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2eybqnrow.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2pccepbes.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzkodlu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohllehqr.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtogcbfp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhuvafi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2jhssvicq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfyeikn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ryekkbod.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnniuhu.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kyaidhdr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzcuuol.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmaciwo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbnbbwa.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddolvawq.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjoijjq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wghintxq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wlidbjaq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcpfbph.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxojqqv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fauofizr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmvzomf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xilipail.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2slhvaygu.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2upfvptcu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwbbzyh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2mahywifn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxnnjpf.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2viwfzkli.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzwiaax.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2iljfmnah.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpovszi.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2neenbqcs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yioemakm.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2pfegkvoe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tbolkipo.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2hdeyfuqs.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxlgezg.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2obvlutrr.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcsculz.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnsnvfk.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2otkhoqsq.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyehczwo.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gggotksb.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2orcxgwjw.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tezriknc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2onpgygsk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uovjliap.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgzrzcr.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtkjpwn.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjoebbnn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpzjmne.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pyclutml.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkngwyz.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ymejtpax.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpvauqg.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mliiuwnm.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wthmxuwj.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2duuiopqs.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgwiamv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2atiorgin.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2pxclgxlo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2iebrynqg.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwpqoxf.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2pamyvwci.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbuemlmz.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyaukygw.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qngpebas.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfyzztg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhsdkur.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtctfgo.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjgcafu.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2utijdfcx.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lnydwpgg.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkremhc.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxpyuoh.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwtvtln.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxlfolk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdznozl.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxnmuqu.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhupgix.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2uxporudz.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgpvkns.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyihhwrv.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdeckja.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyazctcv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkifrtga.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2onybbwuk.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vrncpvxp.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhqgohs.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpcndlz.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdcwten.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvtgwky.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ndiptbha.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dngjfknp.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwmramm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lpguyflj.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2zzudluah.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjvcyfm.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2adpihodr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2qyshcnpk.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gjujrvvv.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yipsgxjo.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2updlrofv.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlhwiyg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjrsotu.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2idljnphi.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxxwfqf.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlmoxmg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2cmaqaudl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnptddzk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2rmayolht.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwoahist.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzurnevh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgnvhnq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgrndxn.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqntcab.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlvwdwk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2owakzbvl.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmckjwa.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2zxabygfn.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2spqutbhn.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2cjexzpsr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2skxiadwg.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmgfsin.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvfhszk.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2oltgvgfv.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlyihpy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvztrgx.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfvdmmj.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnbhbmg.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruszsowo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2twdpjiwf.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2oughvmkr.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2liwvnaff.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbhexth.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2okeocsye.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkajhvtl.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlptqrw.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slgzknzr.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbeamvhk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnflmhro.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdwxazy.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqybozqp.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ljswzfkt.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2napivbrw.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dosqbsay.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zpktzeja.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkfaoqs.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvyosko.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2aznrqwed.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2jscnqsuq.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwvqmcv.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2dgoignke.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2fmogzbzp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyffrky.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzjbtbh.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmzicgu.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nukkcqoy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2heiauiqs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2waeawelt.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2aimtmrfa.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqixltr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2syasgnxn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvchimrp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2zecylvyx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2blnftkde.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgalsfht.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpctdcri.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgamahg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqcdegu.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpvmzhu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2icvxmgtx.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhpfyag.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxnmezu.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2puximivt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2giuknpof.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2combgoep.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2hgubuclq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcfeeza.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aucgyxpf.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqifdtl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rniufqrn.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpovkvp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwpjkva.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yiokhlyk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhazhki.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgennjo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2idgutknr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2owolptvm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvjblbi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dptuhbmh.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2quxcpwot.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2lduyopyn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdgxqkg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrravnck.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2admalgqw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sejzgayq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2zyombgal.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrxewhn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cafafshe.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmeghnh.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2vcncvxzi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fovcwngm.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwmdwji.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbnkgjs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2onutkvwd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkclumys.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2ivralfje.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjfyitv.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbwndaj.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxxcbde.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtdmhjt.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbazsvq.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fsocccxw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcmtyaw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwtzvne.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxjamwc.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsqvqng.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhnvfhx.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbyfpfu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgxrzmg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkwvhkx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wldckpri.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqnuude.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkaaljkm.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2cakwglzf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvsjceq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyaprrl.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2offthvbo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpayykwt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2skqljtaj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwszmet.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdigzpf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pterwkmd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xooirzux.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2sgreaavg.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2iczdjjsm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2umnmpziu.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2obdjdktq.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnjmhqb.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdyvvge.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnhtoat.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcsskad.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjxdwty.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvoxkdjm.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrelijq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtrnbiw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlnwwaw.html


<!-- 参考信息 -->