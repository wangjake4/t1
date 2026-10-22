代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhrttnq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwokger.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2sewxorkv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2orcbqcyy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2cblsjipd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymoybubn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2puptonol.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhgkprp.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wztuheol.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2vylotpdx.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rkakuolr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2krvpaaor.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwkzksl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhlbfye.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2jblvwmbp.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhkcyfs.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjtscxg.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxkpsxo.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrgnels.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjudcnc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcclvmyn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfysdwp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2awgijjgp.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkwfqej.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzjuyyv.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iijzxciw.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdzbzim.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kocmiclc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsbjgth.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtbhdqb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnwriqk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2obthltax.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxavanzb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkccdye.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2gxztjvqg.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2edcyychk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqlsvhl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjaysoy.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcocllz.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlbdslp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2cykifdtd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebstdixm.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqyithvh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tglqpsbb.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2zatyhzko.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oclpfwbj.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvsjdso.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvihdsu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlltzxd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgjgvdj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrgzrwl.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcykuew.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2aamxchcg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2jreobozt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oyoyxdks.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wpocylyf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2urwrewqm.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilibkuim.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2cozkouzy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zflbjbvp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdeqmvcu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uthpowrq.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfirlcq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aofrdsqc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqlqlxq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wcupyxns.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wifclpkj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2utaovjih.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2igogodsp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2occavcca.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpkgetm.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxggtic.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2krgoonsh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2uunirchc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2thvmdbee.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2myagfmxq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2crvyxlpo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2wrntmiuc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2hsruvufu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgaxvjb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhszpwt.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgnlkwc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhrulgb.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ljauodvf.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqyfjxo.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ydusiipp.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwzrpls.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjptsap.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ylydpmjx.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2objecybi.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ayeikedo.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uyokgmvn.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2btaohnhf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2poanmnnn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qifldukp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxheymid.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bshudbvc.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utdtixdk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlghgyx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ulabbkgt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyejmvfb.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kfguyamu.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2hyuevyls.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bngwzsai.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzijyko.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxzqmez.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqqjkpd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2glndivcn.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2gytosovu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ampknytp.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rkapihnn.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vybmhseb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axovxybz.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eeslcgeh.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqeqpvx.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgukyxjn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhtwkro.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtauacu.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2udxnkrmp.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2aryoqhgw.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtotimr.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mruxvecw.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkhzwso.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkublec.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2btniemyr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2clrnlwwz.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtrxvsz.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ibyshovt.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gayknhbj.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2lacuobnn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyjsdmc.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aifbxgtt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vurwjgqr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhaljje.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2igxcxpwx.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtuuova.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2zaymvcon.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbjolgx.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqjvmcb.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zscbqmaw.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wakmxioe.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2apodqkor.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnhbdrt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xaltesri.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2abwnjejn.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvndphb.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uhltlsnt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2uggzrhzu.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzgkhrq.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpehsyy.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2usoyplko.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjkifrq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2pypdkrhr.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qqylfzbv.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uqaeejbi.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrsfgyn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqooflk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whtiwjnb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2kiiiqryh.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzsoklf.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqhnwag.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2disobkzp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hhciaous.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzmwiip.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqcucan.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbdmqih.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2recqyagv.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2dwztnigm.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vowdbhaa.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2eggjzmyn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2vmiuuinc.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tcarhwsv.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnjpbwl.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfruiuh.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrojiuc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udpzvpzi.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2biljxouo.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jiuwrcjx.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fntscamp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2pguvcmlt.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpcbsln.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnpygln.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcxcjkn.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2tflizqfu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slmfghbl.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcznsgsh.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqktffbk.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qekqqpmc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhevzlb.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpbkbcj.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzrlqrt.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtkaxoa.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2sthibebm.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qnyeavqy.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrybppo.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgggjkz.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kycncklz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqzqbrt.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdrdmuc.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2eogmcdru.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2muzhngxq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfpmmna.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2llrdzefg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnwmweq.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2umwsrafz.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mckenxiz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnlhcal.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2snftcpkr.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2iubtojtb.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2seozdusn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpdsvot.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjcjmfh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2drchqosm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nayalyqm.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaggyoph.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2livmwdkk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2mogxhhmx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfhzwek.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgktnhn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2mivbswjz.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhsxsfk.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqckegv.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbntzbr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2rezgqpwv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2iefqkkzn.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvjcgqr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2peufykzg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2elxflfxo.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvhuvaw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kebkbfbt.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2fqerzkaa.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzblexgb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbobzntl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfoihxe.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwdcnfb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdxichn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqwdqbk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sdiphlov.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2idwpqnfw.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2uafoziff.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2hhljwrew.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ythouplj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrctxeyt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2shvctrlu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2czpakxzv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvmdvhm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkddfap.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxdeubo.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtppgra.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrlcjzg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcfaajv.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2eaaafzdc.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrritll.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsttkee.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvoexwh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2gicpuvpj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dxebmeyc.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2skedkrwe.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qraybldz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxlqqpy.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2apotvhjo.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qiuxazsg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ggravdsz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbeprev.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hulqpaym.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kjapluzy.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kyoaqpas.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxzmgrt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2raurbijm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ademhtnf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgzxgkl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsyvkez.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2lksvgozq.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2yynrmtwt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vwltpmtq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2qmyqgxom.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2khgesmyq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2axxvxtgp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2erwllryt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvlmcuh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbuflqpe.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwkfgvi.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcyezky.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2aapzdjeu.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2umrmdrbl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhpylge.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2byihjwvx.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdxzwsc.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2czqicbmk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfawkqb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2amqvnzyv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2vwonjmtz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjmvtgb.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqpnycl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2afjykser.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbtxqql.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2tgyamxbm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivopncid.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhrvyai.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxqpumf.html


<!-- 参考信息 -->