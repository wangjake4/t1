代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2viphwgbt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2jaegoigo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwszokuc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfnmobq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvjbogx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2dttetbcn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzqyrau.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2orcqaoma.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwsbednc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2arhhuaki.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmdmage.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2toyrurzc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkfdwxp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kalctkog.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2meflkgdu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjtrytd.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvbgqwg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2aahvqdxg.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vmeuquwf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bneuuenb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxthqqgj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqoxjxl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2vojtthac.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2edxkdveu.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncppbryx.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ucucgjuq.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2glozijjh.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2seygwgef.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2blxfdwkv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnjzusq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxyprkg.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kysoyagq.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzedoxqg.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nkihbbsz.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpllxxq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhfbvhh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nllkbtpe.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2obdzuwdd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbsakrh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nufilmpp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucybniyt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2phdbzvrs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2bggbkeqd.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfdjbwq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2yneljyxc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxewadzp.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvbbsbc.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqntgql.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzliwav.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpdjsui.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgajmod.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2obwnnmzy.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ieaxegaz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iiaurpdl.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2amdqbvfh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcgkfdg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2umclhdjv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtnhrsv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbetpub.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rlylardz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2dzaibtio.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjtrdmi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtzfisr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjqyedm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2prlnhpzv.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2okmwmvub.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2zllkgjvq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbllmdva.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzrfupu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmlajvwv.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gashbccd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjznqewo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ayaevlto.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fajgshae.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2scknfteb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxgvuru.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2eyguuhxl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2syfblmqn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpuyrza.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2usyzusbc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxaseil.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2uascbgbm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jddtqxer.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2bppipkvh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2avzvyfkk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgwwtgh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2clwgtbew.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdqhgha.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgvbiwg.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jilxbcpr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbnecph.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2yodrxhmq.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2stqafzdu.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2akwoaqiq.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqyowxj.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhitpztg.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbiwbap.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkspjar.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fuugjukz.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsjilha.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzvcyzh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlzdweg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bgydiqyi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttooiugh.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lldunplu.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgikurlm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhdqlws.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jbeqzjlk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvvxfsj.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrpdsmo.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2yzeizqsy.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2haqckyrs.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqbkbxn.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cskffqyv.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqotbja.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2lxskurkm.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2squhzsye.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxbbaap.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlhimnz.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2bapekwop.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2erjkuebf.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwejmlm.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2doylfvyk.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2noqnjqek.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvsdksg.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2upxqvgvi.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2swyqwqqx.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2avgrjgfi.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2drobmbmj.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjgdvkw.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2egriodap.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbcmurw.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oibkwcrn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwgyfpo.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wriscedi.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jafedqot.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbnaxoo.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2lvuxfqso.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdclybbm.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkoybmra.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsrsrnh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtbawza.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2riqiafcv.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcikebz.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtvjkyk.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mvacuslq.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2fomqahgo.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ospkydtz.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2udqcjcdu.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jibxpohu.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbulqpd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2czaiyhxl.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2psscelnd.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pcatyrxr.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lyoandsz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ivswdwvn.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2alwmwnmz.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2klnfvkfc.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mjyldbnl.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kkonysmr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwuqqmo.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrcnrws.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jvupfuvy.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzuxlqj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2dqoxqqxu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlrqbos.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdjaoim.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlerkozz.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrktrum.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdsyblp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcfnnlv.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2imlnmpul.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzabauh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2vcolsiqz.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vexvcrkc.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2smlilmoj.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdbxnbk.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdyhtwn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbodvch.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpthhvb.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhhwtcq.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzbuuqf.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbhawhx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbpujln.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xflmkdbo.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmjpwue.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjorpppw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qoyszlul.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvgvcte.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azacwtda.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tszqnyhq.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2aengkqko.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogplxkuk.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmdubhu.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkstczh.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzjqsnd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmjyfnk.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2boyijrab.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmiwnpp.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2heqdqcfh.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2euiwqjfb.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfhurgc.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbmqber.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2umfredoj.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zeiskcum.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhztoxp.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2iihffvqm.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxlydvf.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvzfcel.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2uavqlycw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2pntqzrrn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2omgnnzcb.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmxjztd.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wcyakebu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2flrqcgyb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmvweej.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2dosaldds.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrvlbsj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpklpvh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evtkqrmj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsjzuas.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mipmpkqi.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfvvphz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2uohstnpv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2fyboctyf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ceuvfchb.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgzzgos.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjsyhvm.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2psszofcj.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjiyyzx.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzitxxgf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxiawjq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdxujso.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqvivlz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2deqyoiyx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwzsymv.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2imkmlhlg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lbiavkhl.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpnfqoz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywiflrwu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2totxdpmw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2blyyiwya.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcyloan.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gubabxlv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kykembxn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tzahimqo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlojfmq.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2hzekxzzj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqmpedd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpspggm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjoevbw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuokudrw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzguvqb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2rqojirtn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jqefftzv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qivqhtdg.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hnyrpyyd.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwanixwc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zfikuxjl.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hdiwnnbx.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2txorrzmp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxgkjgf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmoxodas.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2uyiplbse.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ahuepffi.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ezuyscaq.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zvstsesc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oeogczcu.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgxxfcc.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnhdmys.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjooctk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2owjjzikq.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zloruhnr.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvzofbj.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bzffbcmg.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2jtulieke.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ghekjdao.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmurage.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2emxoinok.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jcghmtml.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqsaidzs.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2nchrwqfp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2odvaepdq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2jldgojgu.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2yebbcnfa.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgyagcq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2btcrjkun.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqebrth.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzknpic.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzjntyb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgnvcrdj.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkcdzih.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfahjss.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2ajobrjpf.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdkjxbd.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytssxxuu.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qecohlse.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2rwelnccv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzojimw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzrakdj.html


<!-- 参考信息 -->