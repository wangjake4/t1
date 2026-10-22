代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ixywwqwn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2gahzbphy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2sishtscp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfucppo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtszcju.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtoradf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbiphya.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2klylrxcy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cejggfah.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmmyzuo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2tezwghzb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wofybtdm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2lutpndwr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjgypix.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfzbihg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2qtydiwwq.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tgprlmix.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2guiemlzn.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwxtjgz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrajiks.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2swkiwqcw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2oxymxtpc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuefkydq.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijaxiaud.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwndfqq.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2otcqgieu.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqoulre.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2htraqiwi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztpmarmn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcesdqcj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfnjkax.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyypnzr.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2owarhnil.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ckizzcoj.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qafnwzpo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjdtaqa.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2orpjbcwm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzzponz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ughlsskf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfpudvl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdofvodx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2lovbigtx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhtvjdo.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ijivehmj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2odvajrdx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzrabqc.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlwlzah.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2reoywcrc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2vimmiopn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrekwpec.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgvlobq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhslrdvt.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzzcnup.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2scqabgkl.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zejvmxxq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2kdivcbpy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsiatrd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bkezhkbu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzcjfxt.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcozgmv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2yqniyath.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2jnyjifkh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdsophkf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxenypb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfphgfzz.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxauzafe.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2vkyzuflp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gskfmxhe.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfedkanw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aevhapab.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwhufti.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nntwnvkw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyekjfk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tpncanhe.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjivwwjt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2thdgibcj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtrdfmm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxohdjw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpysbbcg.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2tfykagzw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtvkzvr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2bxknmxqr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmapxsj.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2todoofhm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2gvoyfrta.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2yekqopvc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzevdqf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2sychdhnm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjqgbpe.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwnenaj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iajobgox.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjkzozn.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtkeahj.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fketysxm.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bybtckzm.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcyfoqvf.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cufgupnz.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhskjlf.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fqykgqla.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwcelmy.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2txzfifzf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2wbordnxg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hibqlffw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxwajql.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zqayzpmw.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajeneryj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bletkobe.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kubquauy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hparmjwt.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnfueil.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcrslnw.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2sutzujcj.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtedehe.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzgqydd.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhphwdcs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxkjbur.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ormloncq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ohizvwjl.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hptebhan.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2smquccnn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpmypnz.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mphgggaq.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xolvatul.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xunknbyr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fogzxtgt.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mndqkzke.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2sojbwmir.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2chtchnui.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2muqcdeed.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmnkbah.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2guuhczbp.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fbcngszk.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lswbfduh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcxvnen.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uwasfizz.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eijbvtfl.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpxlhml.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkgzfrn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vucxaola.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kisuzjhn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvyruelb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2essgwfvp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2aszfqhvl.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ksuwgqri.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2heqixjkf.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2trldqzyk.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2cijgozws.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bklwpetl.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sjuqdzjp.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fszivnwo.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xtucszbm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyqqmbb.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2cstakica.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2muntrruh.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rwymjuso.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2clshwhov.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrwemwb.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2viuzlgpa.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hksjnqgv.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2btxmlxmb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2upyawfvw.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yikbpahv.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtkrbfw.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2jccwxods.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2jzidgmnb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2trzbkqmh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgsjaej.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yflecneu.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmqbcff.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kslgxamy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2itktivjp.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsutrolx.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrevcai.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2wqicwdil.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zeygyhom.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbzuddu.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkvxmll.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2unyggtzy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ganiaqsh.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lultrtbq.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgwyart.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2kmuqkujy.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcumwqs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2denuumrl.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvgwkad.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhykuojm.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afqydjzg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2krxxwzka.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2oxghpsfx.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkggmjml.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jpiqmrol.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfchrod.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmprqay.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fihlxqxu.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgffaorr.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igvzjvul.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2loslgqlk.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2slqxzfyk.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ragvivbu.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2epqxbdrb.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2gswkkbij.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2paiwuuvd.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zeonmxpg.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jeynwfev.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2uswzycxl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpdxynq.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckygmlzw.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ritimbfw.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqhgiug.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqkpaha.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmgqznm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqrsbiw.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2jnesojzc.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jazhowoy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmzferb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgfqcki.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgppmlpr.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkenuke.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2feiqukho.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdlmjqr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2qzuxxthw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uowpmyyb.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkdxnlh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ughiakry.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2teiuygop.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2njrtcxyp.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wtuljwkf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2vggtvcqy.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgeykfhx.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmuunxa.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2snbgzlze.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2jdimbqpb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzrtoqr.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2wydbzeop.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfvpnkz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpckcyo.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jyscgnbq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhrrraz.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqjlarl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2uymamdtj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzbmpif.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xucitivg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgyqvoy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcectpvn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtawzwe.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfjpsfs.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yifvaker.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qkffqtkt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsbpfaf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqyjshp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cezwtyjp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxxwdru.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pelmldef.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2roesjteu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2riptokxy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cblpjmeh.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwnwqem.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2sncyklxg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2drcrprhb.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyyhmzu.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmzyshv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kglpcvgd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwiizhg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwucpbx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vegaiucf.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2riqrzcqt.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ffirbtmu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbmdpyh.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkewbhf.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlvsswp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2awftrcst.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxkloyl.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvhxtid.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsotnwb.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbvmufi.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2uabufemn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cqeakibp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2drycvzcj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2amhpvgxp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ymldufsf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcghdzx.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2avbdwoik.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fywvahzr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqadaoe.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2meicqars.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2yugaoetd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2akwoeryr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2uidzzhyi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwporgt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqappxe.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pchmxwmp.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkecciw.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rptejbmm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2xeamhsfh.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bndzahoh.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dueunpgx.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2oelmxjsk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2avklusvk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqnsmsk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2tamlutwo.html


<!-- 参考信息 -->