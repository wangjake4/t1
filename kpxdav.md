代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlzxfld.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2ridkanuj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrnfxzi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jextdqmy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2eecjibxy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2inxpvfsy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2razrlrbq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2egkujjax.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lnarysfg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2cujnpkcv.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qqofqbrt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqabkbhz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdkyshi.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfsbemf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtuxqpli.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfbengt.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2suuadrqo.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrjigij.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcyjaejz.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgqgnah.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvizpaib.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vluttqop.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2aoioglvz.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzuuwbi.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcaqdtx.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ostkgwwr.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2epvubdtt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvfifrf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwwitok.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvcwmvh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2htnggidp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqykcer.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2lufxntaf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2vanvfynw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2prvcqkzx.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwyvldl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2igktzaof.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdraokqd.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2duwdhibc.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2obnwicce.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2idobcufj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kiouqxdu.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjeoweh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2snbnplgx.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnvcyfv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxevbkpu.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mascdyam.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ukufnunp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2acrqwien.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dfngvpjv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2twtjucpv.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wltvvwlr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2eghblfxz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmybyge.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgqgfvg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kybcolkv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhkvnhn.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxdhfuu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2thmmlpco.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2smfacgid.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2czejfvay.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjrlmlu.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dpyxcvym.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sorstfat.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqdnqwx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2khmwpevv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjphawi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqykmfzq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2thygwxwe.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2deauerbj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofodmxvn.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwlcacr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpuicecp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwbehzv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zzoxdtxx.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2kiooyzpj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2mhuymhmp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2okranrpt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2qckcnjff.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzylxhc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2urgzrlvl.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkeyyrw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2clnlrggk.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmjyhkz.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlfsqwa.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fccnbzyu.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tewenbib.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmiaqdtp.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpfbekg.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdrbhoi.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrghhwe.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wekvtcyo.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lumundjq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzjnbdp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nnopcwjq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olqirotw.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxmbolg.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xirfiarl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjwzfgw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gtoszcob.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhismwrw.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlshbzm.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsqkeef.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkbuori.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mwujgyny.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsswzzt.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fidrvfgc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2fewtzfup.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnqffvr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fowwatam.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjsaxjm.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2uijqcxyx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swkhidlb.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xngbarue.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwhfmgb.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oiggacvi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvenqby.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdkmwyb.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjwuxpu.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2cnsqkeaa.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsyryro.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqwwmsi.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnslgou.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zejsegsi.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2flctkaxa.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2etlcnurk.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpvtslk.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjmhhgo.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqqgssp.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdcbedd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvjrsbw.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzlbnih.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2porxeehz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2voqfglwe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlduotr.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2emjkvget.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsoafzh.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmmuvbs.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2blmpjyyy.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dsuzlleq.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qdyoxmga.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2oeirscis.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bfymjzji.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2carzlamf.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmytgxi.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxcdrfe.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ojblozac.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbzcafp.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmdumbu.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sqstfqfy.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsfiksh.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhzhzvn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcrglfg.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ockgcfyr.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2heeqvwub.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2ceikhftr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzeymhr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xosivygj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtlgcyf.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnkstvt.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtayovxd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkcckjb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnujdzt.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpmebdj.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgfqjto.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqlfids.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcippgw.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkhyrau.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qtyujddn.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjvyjun.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2muwgghes.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfryxsi.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhtqmsx.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgemtaz.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xvyulhdb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxmpmmh.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqeughe.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oynvghxb.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvkezjq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dswjohki.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2rfszkouu.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhestlvn.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwtxjhk.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2nvsmhalv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdastsn.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbpxfwu.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llpkxeht.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2myojgnac.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nelhwcaa.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmvkwee.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2utwelthu.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wogciqkz.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmchyvu.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwjxanf.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pditfmnf.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zftfitav.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrgulcd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dkltyvlp.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2vloaibra.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2oxywzsbl.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2aateuzms.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2tloykehu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2jncydklq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2rktakuyb.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzhanco.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmmafwd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvmoayj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2bfztxhed.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2qggnsjas.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxspcgh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ovboexzp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnawwqcz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ympkqohq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iaclzjci.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2tomdxxve.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2dukctyav.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2mysspafi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2byfjbteh.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ajuayrwx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2cwexzugu.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtzkeeg.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zarbtmvm.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cubutuur.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcygfqj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmlyyse.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfyskgr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdgjxap.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kkilasyr.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfxeqft.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2skadmudk.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2fnadruza.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfmivwa.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcsovsa.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgbkcpm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nctidbkg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydataein.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpgiion.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvdjlxe.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vehxtssw.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvrtiwo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2prodpofr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxphpdy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpxxwkc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfggmmdn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqzrink.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrffgvb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqodkyu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yeaxshgn.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2oxevybrz.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2lixhbbcl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2uuyioksg.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlrbszy.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wouqqhqm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsqujvp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2wddaezoh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2kjuvjvst.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjcyrud.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjkrbbj.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpaxlwf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2chjlvplj.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gnftmzmb.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzuynqh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxjafpi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2cizwcmbr.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvqsazs.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzljklr.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2piernhjg.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxxxqei.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdibeew.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2crjsentj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzvftnh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmludgf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrvtvnu.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2ccaulomh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pekmmejl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2sibmbemc.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2jujscksi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2fposodbm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnopxla.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2gdskvnmo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdmwdkq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkfspga.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpzoteh.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqgkgrk.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kerpidfo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2ylifdpdr.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uilsyviu.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxcjeryw.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbqqqat.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjlytvp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fhamgkkb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2iglgdoiu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifuyqpyx.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2kawnpiov.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2selvqvgd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsjfwkv.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2beyjrefe.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2krwlhzec.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2trzfevby.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2waxlayeg.html


<!-- 参考信息 -->