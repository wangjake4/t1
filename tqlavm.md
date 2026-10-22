代发 wailian999

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aznlwtta.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2czlkiskz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2avcaxsmn.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgpmfbj.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wznzqlna.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmonirp.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpurvjsy.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qlumgryy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkamjymp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uskzbqbv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vggdukzv.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzffwnkc.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2npqyiqpt.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ktezqpvv.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2thdqcqjp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2giedrnvd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2uohuytvf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2jhopkcek.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2caivwwww.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2phpwnhiw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrglsozz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxkfvta.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2xsoffngf.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2blkrcqmw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxddgjm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cafxktss.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2iryprdua.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgosunja.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgzvuno.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2alknyztz.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmlkzun.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ianjwnuu.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2wsiyszgc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnacpja.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqlonar.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqallxw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqfnsmo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lsnxondu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2eysbqqlz.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgyuivp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrnolqj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ghyueeny.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnrikjp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jaldfqmj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xsssrppv.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcjvrrg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2vbllbebv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xshycydg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqoajvxo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgdmdix.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jsprdjaz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwuzafl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnflkit.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlmprsi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dizfjmlg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkhdgcy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxdirth.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvonfgfh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfyxqzv.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2rzusthcx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxakkmql.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2ckixbfpp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2buuhelrh.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2xpizggmq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvmsvlp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2emdrbmnz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdgaygr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2kywkkuaq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jndtfeku.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfhblpq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnoynuz.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2dujuhznl.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2epzfkgat.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2keuvvzos.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2csuxfwxf.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twauivik.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eyudkgxr.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqfsumw.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xopbffmy.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2timzaowe.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2icaxwttb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2embcmpcz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qdacwivm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llodgfsi.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jwatqknj.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bncehqis.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpothcru.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vczxnmjh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjsmesja.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2swjgdosq.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2efaxmswh.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfyckxh.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjmegrd.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uljqhtno.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2enzldshn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcompjc.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2yjszkcln.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ldknubgs.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmtzwjn.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2whjzvcbn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efiwjmno.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnejolyu.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqopetk.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2diirgxvl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgltysgy.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rudvjxuj.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2loqmucio.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfoseys.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpufdwm.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwtvwuq.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wfppfhig.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzdgsfr.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tifjjfyf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2tsipaztr.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sywljzcs.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxzlnwv.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2clvqtbug.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2tflnmbwm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hovjcryc.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjmrkgs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvanmtaj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2trljjozj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2hgckzxkr.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkqumft.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwgpeyj.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cwllgmdk.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwddwqwu.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ithssbmj.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzrpsfa.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xebjimhb.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tnddtkbc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xwsbbaxg.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2omqehifw.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpsqelw.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fungwsss.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2cfaryfxt.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjkajmf.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjmbcwx.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwxandi.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zgagmkaq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ycraqztz.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uexlwvoz.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcdwzqp.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2guzlqfor.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2znneveow.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvzjdmj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbhdvro.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpllggd.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nofkrwiu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzkuige.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gieucpjn.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcaljkm.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjwahgg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfpopvr.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jusbgbed.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2aidkgvys.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcguzhs.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2oorqntgu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2loqfgoae.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnkmius.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtejrep.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2mipukmml.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2iukgapcc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aojyiwep.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcttihil.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbhsbdw.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lapmhpot.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqiwbnjb.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2eszdmvhz.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sokufbbs.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2itdgtagx.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjxagbs.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efhcbnqg.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irevcrzp.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmaaagko.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcusmqb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqanqikc.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tychuwkd.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkecjqrk.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ppyrctib.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwczmlny.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2iigsgpof.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2entaflsq.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvvffuj.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kypainaa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qiufxsye.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgztwsa.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2xornemmj.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2tktcxaup.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgtmdit.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlwzifu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2luhyksqm.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqyruez.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iuiusovr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2evlzbuuj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsxdziu.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ralyftoz.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdinemd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ortpbovq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmwwlxb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjgruwh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgehkrq.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2grpjzani.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaypjibk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvltvpe.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yusklymb.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uaybdxgs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2jugjhhgr.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfpjqmc.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqclnvo.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2etpmeqpv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvwrxrc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpqbyqq.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkgyths.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdqvizs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bditpdyf.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2khfivdrw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdevbuv.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2wgysdpxd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2olsqfbds.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdeomoj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2obqgezhf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2klldvkvx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2flvmvwul.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjuplwl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrzdsjp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aftssilw.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkgcfuu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrkkykz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cemugwlt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2efgsercj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2piqujzlh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehefpatq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2hzywtkqd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxkawsx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ioyquyyb.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2umjizkhf.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwdarvl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcmyluq.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ikisnfwq.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pemosryj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qrewlkko.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2jankgqmf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2myoxqlrw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwigzqn.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwrpbna.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2foeueqss.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzupgpt.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2prclmhso.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxftxye.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2klmhlscy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdohhxt.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aojdqoyd.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhujixs.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhinfkn.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqpyhxn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bymtwoyy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdgbwcw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gstbyrqk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkwgqeh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2fikhzkfq.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2djxknhaj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2roskzals.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2bhslexfr.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2gyiimpua.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2vomrfycw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzeffjt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2deuzxfcx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmepnhe.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rttjgpvs.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqceefe.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxwflyz.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2asswrclx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2acxkofha.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfinasph.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcllechv.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uewrlwep.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnzyxoe.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmrpwls.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvnaivc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cangebzw.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2uyucfriz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2umhslskb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhvdtkg.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2fpihljem.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2prkkpmfr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvvijrj.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsfcatj.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmqwrie.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ggczkdui.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xudpqjjq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwnqlay.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhyfnao.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmoujqe.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2eaoobkzp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnlfmgn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzlrwyi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgytbkhu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kixxajzl.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcgdyry.html


<!-- 参考信息 -->