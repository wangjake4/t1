代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofophzhh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2iankcxux.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxekzgw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2kipwmrkh.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2biojsvnk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvkbthj.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2slwxzigh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2apsdennl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2evnhcamn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hhoacumo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyprycfm.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqwewfh.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2putrnthk.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kajvlgyw.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2blflyuon.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mklrlfmt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmznxvh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2exdajssq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2debryrzs.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvtimvv.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwcwoht.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtegjxj.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpauzdl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qitxhljn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yadqvsyb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2tivutore.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2hfteihfr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vncvwdhm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2jaugxqxm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfuvraob.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2annbxoyg.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2pghmtsqf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjycnawa.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iexjxnim.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wuehzjrr.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xgozonbh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvyhfdbt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnutjma.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yffxjgqm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmsrrsv.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2uuphdujg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmhxagy.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcymuzj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsbgznq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkgrxsh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2igvynyyl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgsqzudw.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcsnhnbp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvceuoq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcobuaz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkinwpcy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpgoeud.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2foxppwaj.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zilcsjqb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ltoalaqb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uscipxkj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2czgqnnhn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrvvxal.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvxhkxh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xyamygmz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxjuyqk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2herrnsgv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqoioiin.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uypqcfez.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2gchnaajv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2arqxanuw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryahfzny.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2geoxfonp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyyzjaj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2irreslfr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2plgprahy.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzmcstk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjmeaae.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2aseczpom.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2cekzqmhx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tktuihvm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjxkwtv.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqcljva.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ngahwmqc.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2euumfxrp.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbpxjnx.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyroslb.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ynuebgig.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bywhvczl.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhzmqiy.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgfhkwp.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjxnmky.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cbshxbur.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cozgqtgq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgrvfum.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ohocsbiz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2muokgyjn.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2micpwwft.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxoxzga.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkevowif.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdqpbsa.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnzrbhv.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zdujdwco.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqztumse.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bzftdmvd.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2auncnjma.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wchcqnqu.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvjeljq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zhizejyl.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrlxase.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjlrydn.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsjpxms.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvkzdzi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlripaen.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lphogjfp.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arboftvm.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbrhfbw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2udbdtwco.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2psbmiggg.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebddxiky.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxmdcqh.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxmwynk.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2apnjszjc.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jiueizez.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nivvfsup.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rutujjjx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtzunxz.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2djozjugt.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsucdhk.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yudpvjky.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2jlemosig.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brklzebk.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgufzbe.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnglhxyu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcxmkja.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrflfgi.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrofras.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ntibvngm.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdzakqp.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2glreqbzk.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gofoiorq.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmxicus.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nergkrct.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxouksv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zeobebud.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpaupoo.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2aojhuyxz.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pverzcjq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ywuewnqy.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzxlyai.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvpfgnv.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfducph.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwqkqzq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hperyaku.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxdyicj.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlfcone.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjpcppn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2naghhdpo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kngfkloc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2ovuzbhhj.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sumbvhkf.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zabusqrg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpriqwp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjddfbd.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbsczqo.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwqynsw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ovetrodv.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxieyvq.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2opixnauk.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2yznxqxel.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxsozwr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzsetqi.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbllyhg.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2bbloeaue.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vyefkmik.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrqevnh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2maufqzzc.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yblxzidu.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odasfqko.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyaltrnt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvaldze.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2rhebcrvx.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvwwprx.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yupddfvp.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdpvuyc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rennmjut.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgazrvr.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfleacvd.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayubgcch.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhknyar.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nciwclrp.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2eytvokci.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqsohng.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdqqzjj.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhblcwf.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbpfpno.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fyddyugn.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ebuityna.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbzsvgi.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvsejkp.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2zoeumzir.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2rppreqob.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlzftut.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2uacatkfx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ypiskkrd.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2axkepwej.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oqiclqdo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocepejjq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2qpspkvvh.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgjscpy.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rklstspo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yavdkrqy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlyuahk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ihoivwdj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkhcmks.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxaiwngl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofervxbq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ayoslcxf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dftecdcj.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwlyauv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrxdajm.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmiqcmjm.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2potrjxae.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzyaaci.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2wryuddyr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hyogmvtq.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2atesntzr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkbsryd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oplzfiju.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vmghgark.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjuurrq.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2llayffvd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkonlqau.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgcslvfv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbslhdn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oeycivdg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2crpzcupo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ugoezaso.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vurjlcya.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2afabtwyo.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wqynatvt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcgxvda.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2htypscea.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqonrwjl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhprtna.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdiajjs.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2mzlixheg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpzfboe.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iporibzi.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nmomrwaq.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2wekcyzbm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdpfkyc.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fumwyeip.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bortbyqh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhukxsu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrxiaxm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2uzegfjlb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqcsvyn.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2axchmhev.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2murcrkie.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnkmbrw.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2acdhigkk.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgwivfk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fitewmua.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwqwmdw.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ejuxnxot.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mevuerph.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfjtagk.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2skasjisw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ztazgsvl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vetnjrot.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vezqhsvt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vshkkngb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqqloxj.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfrrkyv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxrxghi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2vjedhydx.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2egxsjfzm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2eviftkca.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2fivnlqpu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2gurjnjqb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2bybvfigc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqsntbto.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdllrbp.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hopgufil.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfizbps.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2yfczkexz.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqeursoz.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnpgijpi.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqiyphz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvpupqe.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfnqcqq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkihzas.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbfuagv.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdnhjri.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2xegvauma.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtrdyrn.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2orctcdug.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2clufqvck.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2hyyimwwo.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhpsrcu.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnsgwtn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdzqmef.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2grqxhbtz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2pyidalxl.html


<!-- 参考信息 -->