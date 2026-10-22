代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmakxkjw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlhwpil.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpcgyhp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2eaijyrph.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2sohnsdlg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kicmjwoo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgiptnz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2bxewbnrc.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmxtbah.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvjsbjd.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2knxetpaa.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfekuhru.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwzdcyb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rlatzxer.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwskwmrb.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlumytjr.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmocyydf.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbjcvit.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqxglak.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrhnzbf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdodbxb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmdsids.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgzmlil.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwskpdif.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbeyjoio.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2aevqsipp.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwzcjds.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yilrauhg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jstjczpc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmnqgyv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcrawtu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ghyuumlj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzmmjce.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjhkfpa.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2upngublb.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2odpllxcp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2inumjxqw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wobwvezn.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ithkunsw.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzaatrse.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2czgsesyp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zuecxrej.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lstguwvw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjweisqb.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2iihetuon.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbaynbn.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2flwjlafs.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkhawnb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2usvaeihz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2znqudiwc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2gruwypqu.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcmvvti.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2psizydpu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvcgzjh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uljwofcz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnyjxib.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjftznz.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxvvbgk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2aamtmjhj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcxahad.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2atetcroj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2exteavpi.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jamnaafw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwahqkvu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkgdkkg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvwuvjo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbdtdxg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvccmlw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrlegxh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjlvibj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kiibcqat.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2yiflirze.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2hglymbaj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2zarrhmcc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbaorxg.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzjlyni.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsrygml.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2kggzyxzv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2dxoywsxw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gzriymbj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2csmarnds.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2undtisox.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wuukallg.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsuezyp.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2owqeofpb.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrcazwx.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tzalhryn.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvjdovr.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvqubjh.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2qipgqwrd.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zudwtuzs.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2djgajqpn.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzejapv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwstizm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfmmsqp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apkcybam.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nhoplvac.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lliejjuv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbqmvon.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwgdtuj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmkrghp.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbjfyam.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2aonhnkig.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xchmwyyl.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dufsopkn.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xbifsqee.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhroirw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqdwuqh.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2qcglwnzy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2onfhrrmr.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lgejkook.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2btfnnvix.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnywewky.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orqymubu.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xowzekti.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfppjbbw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpijufg.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvqhahp.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2sodileyy.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ppflphcg.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tctdvsey.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gcsmlkzh.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbpmlcs.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gsadtcpy.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqhgsbk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpmvkfl.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aypmidew.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrrrmjy.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ztpoioos.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2offuuehd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkripkyk.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efalqovh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2megsxfbo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwofmtoi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzdofhm.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlgbooq.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2euaoglwr.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpxcnjv.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgyayvwn.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgvgktg.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2drfkbjvt.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2owttphll.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxfjorc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrttnvn.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2jqenojac.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqyrqyp.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbiumqv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgtvawb.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbzscjo.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nszldvuo.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhltzqh.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfgcmgy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpguxan.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dlyruzzz.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gigxufuc.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjgxmfj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnzqsci.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpldjwl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2kumouggt.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2turtvybn.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2liiloqsg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2msiacuca.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sutaigoe.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2clynpfnp.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqmuiut.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2durymgml.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgkefku.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2edbnpidf.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dphutnvo.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2zzagzsvb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjjjjrc.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2nerjseuy.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2urcqkqor.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2bchswxec.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2exxohbhd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdqrsiv.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2guwcfsck.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izhicekn.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjqkcmr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rekkuydk.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2gocpltsi.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrdxudg.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2svbavnxp.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2olxedyxi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbvrzkk.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qebnymnm.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hutsdxos.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xevuhkds.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhajcdxd.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpfmgek.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbccdqle.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xgidqgkc.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtposzzw.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pwezgkju.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2sfyuahzw.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjtnkrw.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xmakqwfa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wiilhzml.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwffqyt.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2aemhszil.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2jkuotgjz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2wtyxdtau.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqseyrw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2kpobwmsb.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2pocqsvyi.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjksuwa.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcwnqji.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhccswm.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjxacdy.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2quynedjj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzewkfa.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkejugis.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfyfixu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpajnbed.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2inbrlzji.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtfocgt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2limioxoh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbaetszp.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhueggx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2mvazlska.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzvrmhl.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmmhpjr.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2onbmcnao.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvfprgw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jipkysny.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2qutdyizd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjjzdlf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mufissuz.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pcajjhvs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqmorsq.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2qwlokfrz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjotjuw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfblnbgw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxkofdh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcllhya.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qeaecjyy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qutkxoaf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oikwodkz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrceqvfs.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2iszwayxc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2wompqczz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrzlxqu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccelxdyx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrvyifp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uovlbpqb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2bqaxwbxd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uyozrgse.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjfpheq.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2abdtbqub.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdtrorl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bppclupi.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpribvj.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2cexelell.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbqavvq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwygqgzs.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2pszihtbv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zeooplfw.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpebfme.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rguhddez.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wcktmgjg.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dllrcytf.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkxuhqz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfeilva.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2nralehxd.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrmrawy.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nupbttsb.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhwhuab.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2raaywqhe.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uevktykx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxdiqdh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ibztqedu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwppvev.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2dirvrbnw.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvietjd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2afijpyxo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2qxruljew.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2deshyche.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvhfdup.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2estvkwto.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2btaktbqg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2wysyusnb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lorrdoqq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcsbhxyo.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2nncijywt.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcbadgo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2baqjkdiy.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrldxhc.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqqxjiq.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sycufngo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2qepisdtz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2owefvsxu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfeacrg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzcovfa.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2muwytmqk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmqoqbv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlzmtxf.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2eoklvgwe.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2sysamkpr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2qkatpadv.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2refmlacu.html


<!-- 参考信息 -->