代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfopeky.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2vveluzae.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjuolzd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2difjiexo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbztgep.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2huxcmapo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbwdico.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvtnvga.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2paehsscm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdcjsid.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxmkllo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbazmoa.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2evjdgvoh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbbtoil.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2uymdvzot.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwmzfmg.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tedjyxmk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2fulmcmfx.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdbduke.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2soleftqo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gayeeydw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjtlgtj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2kydhbkiv.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ayihyodn.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfqkndk.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bssavmrf.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsjykeg.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tcilubrk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmjudde.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyjfbuu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2oiobxnmp.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wcttwity.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpunecvv.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkpxyaj.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2saeqsnxf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mseztaxo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2phalwgqv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2nzblamgx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2hczheuuo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxnpjzp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqpymau.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvsrvwf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2srveagag.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2izyrplef.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tblooxel.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuyjgotx.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnowoicj.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqlvumw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsunjmew.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzgszzp.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwtcegg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkeryhxk.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2toyjibvx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkasdwix.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vgrdvsfn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2scljadka.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2mslrrkhh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2prhjwxfb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2pruuxwsu.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vulhyvcm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2kivhdyts.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxqemgb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcccgug.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2huwxuadv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tixkuaco.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpboeoja.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2muzjthvy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpuuqrx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcukwddu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lugoopew.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdjzmtt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2khuhtfgk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2keisqxen.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrohplc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2castcfqo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhajbkku.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2zotmoxme.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bndakfbh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhklsswa.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2coeebhpa.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkajcis.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2szpimfae.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2puohvjrf.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2altriyej.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ezphbiyw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyfecui.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2scxektdd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcvfzmr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fdapqbis.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2errgizsq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tijzsskt.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2tpiqggtb.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tywnahua.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwmixin.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwdilfe.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmuezfau.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gwduxnwg.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnsgnrc.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2btvsievi.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eiounwhh.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvxgsuc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2equxlorh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxamcta.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahyvvhlk.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpdcian.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mligpelf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2deskuzaq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dibjobjo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfauhzea.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqibkfs.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlfbzqg.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2flchrpvb.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mduadfkq.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cfobjztk.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfukgnny.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vewgjxcv.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2tsuqatzo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2snvfrrju.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2oehbvbcq.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsxxzjv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvefmsok.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpadpvam.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfhpuah.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frnuqgws.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnvvtbm.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ducjlskj.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwufleu.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2htnzyvup.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjnycwy.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kozawexh.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdfllct.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tukfbazw.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zdticmwn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcnsbsd.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrxiwuz.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ojyfjxnj.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2talbfukh.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2yepwnubc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfedqfh.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdhrqui.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhsmvum.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzacllai.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgnwjvn.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fycffetd.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlvitpr.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kjodygle.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjfauak.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qcsfjydt.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvsgqly.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbopvdh.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2buhqwfgd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2eanpfwsx.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2elppwfsc.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uygjdkrt.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2umkgdytb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2nunxvijh.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmrttdk.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzdnslu.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqntobb.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2boxiubkj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2uzowclmw.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzbdycq.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sojubxfe.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2exowdfhf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfdcgia.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlvawrc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvazlgf.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzyrswsg.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbiyyci.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxrgctk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sylolxqu.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sorkdzpn.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqjbtas.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2aexbtkdl.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2eockldja.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2asuemeiv.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmhdslm.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtqjprk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2kyygllmr.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwxudgi.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2gmazonhk.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbbogwo.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2cuiyngvv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eeumaixb.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evpoayhs.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvyxbxh.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2idwukswa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hstvqhlg.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2vsctmsbz.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdhvpsv.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdhluwh.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdktdqk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2csfbvqbq.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqwfonr.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbgycaw.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqmrtpj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylearrfl.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mjejkscz.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhmswnz.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbrldps.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrczyjj.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2aegerdwb.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwylmsv.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2plbpucvq.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmvbrhc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyuujnp.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgifaql.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqvlvue.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzqjocx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzxnnng.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2kpndgbxo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzxemfn.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2mafenjkq.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwpxzlp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2miusmubr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2egmksttk.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2haeqwher.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2svtqosol.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2oiehkfoe.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2crfqdrvg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzabnbt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdeylwno.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgxfrio.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtyiizw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2pthnffxu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2akusdide.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pyempcxd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxcjlhu.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2amnugyhf.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdwfayd.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkqkwzb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxnfloxu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrdpgtc.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2acjkwecr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2segrxnyx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgaookd.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqnpfdy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fasvcjvw.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvymyzz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2yphlatqo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2khuuovxj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwhdvac.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrleuwkv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkingvd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jykptkdw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tiujebhk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwpxvno.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxdgdww.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwznrle.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mstfnmcp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhrtspy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfnxvzx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhtdscu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2wirrlfei.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rpftktph.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yigcojrk.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbwcuxf.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdjpkbj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hyydekgf.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pwegrhrs.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbxczoc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lhinfgel.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2omwpsyau.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkaedbe.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ibuwbxfw.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gcathutq.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrdwgtv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2auqdhgcn.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2idobbovx.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wopdgigb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dtefseyf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2cotgzafu.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqtktaw.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tdffzyig.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2twvueqfa.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2eifydtxy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rdyqszuh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aowozkll.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvpkbvs.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bmonagyu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2muocyddp.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2rotgbeta.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2doqzydqp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2sajwmigu.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2oklsrkor.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2llzgrwto.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2svxgfumy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2abgfbdcj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnfavjl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtzjahy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbtxdmt.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdwzhmb.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqskrvi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrkuzds.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvefwrwy.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbsqmqi.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxhxnki.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2barikwjc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxwktbm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwsjljc.html


<!-- 参考信息 -->