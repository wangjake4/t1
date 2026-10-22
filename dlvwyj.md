代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2opomojxh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2empzjhuf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cynbayla.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyielpu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2aeacmijl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgewudx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzjlfuk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2jizbfgql.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qubpzglv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2gdejkelw.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnhjbmq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlhsozt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjngipbm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjnbhos.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouycbgec.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbuclmg.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2grbkgldq.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlmonux.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2weesskpz.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2olknsimi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqhnsep.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdablgw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pqddavpw.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpsjozs.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqghita.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nkuauqfa.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2djdktswi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpsmzdtc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwporoo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqndtgo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhkzqql.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2frzwmjnj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgylbdvm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2sijmhesz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqptllk.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkxveka.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrdqtnh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmyyhpuf.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkdqvpi.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpnxsoj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2tikmscty.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2iawfiqdm.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmipjyjd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxoslbs.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfbjvwi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkqjaay.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2isooyfzi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ooadbrwo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2iasccsaf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2inhotlyt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2bshjewns.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwvnuta.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2lfndmqzl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2odyinwce.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2alfceooj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfqxdtt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gesbwdld.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgksizk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvlqvpo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwvbnac.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdawledf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfdyjbb.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lhavhqog.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfehoqr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfprkth.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2axospapd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2emxdouxc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqciksj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqwvtms.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uetiyxow.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qeylnsxi.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2yvafqffw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbgnnet.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcjtzrj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tiowbwzc.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvxmqfp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcbfqhf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpikzxx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkfpubr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtdggqb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bazejrnc.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfriniu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrkxatp.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2aacmsbeh.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nckpmkrf.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ugzewkey.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmjxovr.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbuvuny.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhxuhus.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2hovataju.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sooaojpl.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2blloxzcs.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oawabysp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2oronijwi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cinilsjx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gptdnzsx.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2leqbmfgs.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvprzczg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmeivfyr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgvpmmq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2luxvpsim.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2skkwhhkj.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2flkkeryr.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcpfxli.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2alrcpwxl.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtfwfer.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnpvlvi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2dqktezwk.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2htlnmugu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zerfagji.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2iuobwukf.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqgwwgp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnuniph.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxasbkb.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbiquqee.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uksvmtje.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2clqmtymc.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qziejrkj.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwiatvnt.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2amunpzob.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2goqviaii.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vezuqkjq.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2emkoujox.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oumgzvoh.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2juuwpqog.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2wilijdek.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ftckrneo.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgkgvgv.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2aldbhflw.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2jqznales.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqpkmsf.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhvdebv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oualtyod.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqunkqt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqoazel.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2byhjqljk.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2xaylreku.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2edpguzxn.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfrjhvy.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qssyulhp.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zohzajgd.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bslprdnl.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2opwhnvcr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gtoryped.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2aoeqklvg.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wvovrgte.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2tmyodxlq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2soqkdaoj.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2idcdcdmx.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcweicm.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cdccfssn.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tyuytzmn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzlehrf.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpdvtre.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2clynxfnn.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2iemavjfo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2viwbqkwg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxskxvlp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2eotrgzzj.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozumxdyd.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwbpnxc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvrtbjs.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bgsevoht.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dykmdfis.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2hawddory.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2elyxkijh.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkxbrwg.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2odhjkhov.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsymnvf.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqdbbdw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2iamijedj.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2liejnaxi.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxcdtzo.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2okqonfzw.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2lriqltsd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iiunswch.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvfrpbl.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjwzout.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xghhiwod.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkandocp.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2hamdqrey.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbfibnp.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyweukk.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vkprmsyx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxigypz.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obeljonw.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhtaelg.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lovazufe.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvwsrlq.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lphcnsbg.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyddosys.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2clhkbdvx.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxerhkfe.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhtpugh.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tdawinxj.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xezozgco.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxukahh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjsuiyo.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxgrtpf.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2kezncxof.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2aekggzqu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2lprsirec.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2oozgeznu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2btoubgng.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2aqujmyvj.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtnkerp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2aebghgnw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtrynjc.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytstemvj.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbuywhl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2beezibza.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzoeseog.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmmxxjg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2twetclob.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2yslsleqs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2cacnmncn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2dsboizhp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrqcmhj.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xirbdoyu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbhmkbv.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhzkbxi.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxurvrvo.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmmkbsz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcqbdyi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ipsrlahw.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2gcustpnk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2uyyyydev.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkkfyrz.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rllrcyeb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pieiaoqr.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxsiddf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvoazre.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lryfmilt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tercvzij.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqfwqeic.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2imzacfmh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mypdtwtv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qamuvzog.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixldyprh.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdmyipr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2lakqackx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2efymgujg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnwqhmw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnebvlci.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfktjshi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzwhliv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2umgnbbge.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2venzedjg.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jmewrcnm.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2kildmuaa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzzrmkg.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2havvuudl.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wznmpldi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pnodtzfo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbysqtvq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2ttswhbmc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2axfgruda.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cclbbgwn.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhsgejx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzwxkge.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzkxvoe.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2emuithoq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ooredahq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdondpr.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2arodazxt.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpcahbo.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpggtul.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2rwcnfyiw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjtlals.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uafnazcw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmziwtm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdzabev.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2tibxrhmu.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcauqem.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2khyzlypc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjfwfud.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcbwsca.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmhtwiy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wnanuxrq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2okclearr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwktjjm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjvbtpc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rycxilxy.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2vujoreqi.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgoigln.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2msveswql.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rinyhzrd.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrfxmsy.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhynbdft.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlcdmzj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwmcwzn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2sqedcugo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2klaiyvuw.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2yjukdxtm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvifvjji.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkwfoxu.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2eutrjasa.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwgyjpo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2yehminoy.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2ucquocwf.html


<!-- 参考信息 -->