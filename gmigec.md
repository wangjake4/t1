代发 wailian999

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhmcstf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdmnlco.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2sehkhsdh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfauhyg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxqgeli.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwgoome.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbitfwb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrphdhwg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvdyskw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2iyrlrjfq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2klaixkfx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmtpaag.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2txwueyhu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdssrpor.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvhwofi.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vcllqvbm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbiuhxd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcdxkvv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kucdskmz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhujlfac.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2fegfzokl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfiherih.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2udgpacsg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ttibvljt.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxzyrnr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2zprrwjwd.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dencefkm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2atwrjucp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkmfgyu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzvhbpd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmrrabq.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwaetva.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtapcycn.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2byeaowxi.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlqtqhh.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qcicawjn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsonoaoe.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2euzcxnfr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcrdpke.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2istzezqg.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpihtcs.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgrpqom.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2keqwknyx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqoojdno.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztyoqmdu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2whrswlbz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2jkveuesi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2irpiwyms.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsftjkar.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2abmcbrpy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmbspab.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfdjuvg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2epmpvuqk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgtvgwq.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxaobytz.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwokwtn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlbygzr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rezcsvcs.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwksmofr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlxqzxo.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqictdp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pcspiyro.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2peqtshti.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2iatcnkst.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhwkyxk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwbwfdv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcyfxhj.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2twehpnsz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjozgrf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdxjqgo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hendizwf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fxaqidli.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjfkikr.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lyivxesq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2sghazufq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrebthj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtzhjkv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhpzpks.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lruvfwku.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjtunlg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxbzfbr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcoypvs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqijtno.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfufgipy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2twuazxgs.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kuouobve.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqwjgyq.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgibwcz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxojrrpl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2zojjrzkp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vgboqjxa.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxqdnxn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2icnmwpiu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ikidurql.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2suymilkl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzkmxvh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbzsppk.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgedzxl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2udqqidfe.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2qsuhhldm.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvqxfyl.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwpzmde.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrqihun.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzazhwts.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqcbmiy.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2knbrhpcl.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zkyvwthl.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2etuxkikc.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iynakeej.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2hkoidfxo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jmcvuzsp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfsgvej.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfzhzqb.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qoonkbze.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2oiiwlrwt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvectkb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwcpyocw.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jptahkds.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2eethoyvn.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkahvpo.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yxefcjbp.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gevzllrs.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmipwdja.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2dueujcgt.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2suqwwkzq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcryghi.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhzqgqy.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmmspkm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhjfhpp.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvoyokiz.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2paufuryp.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykeaywwd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmnhkqr.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjdokzc.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwnhddr.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2lfojssqm.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2khlxgohw.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2murybcir.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmojwik.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2svilpaep.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kuahbodu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbgzaqr.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnvsgzk.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkxjmdz.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lngadfbe.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2apzgqshl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imdbeyuw.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sofxuoej.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtlwlhs.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayipvgwc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2tbewovoj.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfubaeg.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2swcecvms.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2izfldxoe.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqyncwqn.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sexbtrbj.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvcykvo.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2shhyaxch.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmycbxi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2efqtvjxg.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2hlddmixx.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxwymoz.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhjijzj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpfyong.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqtzumq.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpozsep.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uobtazir.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bnoxzycv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2dsemwgie.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bmryquve.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sgiqzagk.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2libgvmmh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2eoztgzoq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymagmmzn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2clbdlszv.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tytaywxn.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eunhfaqz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2csnzxevm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpeiwii.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmpcvdy.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2zsocxjsg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2irjihvku.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2igspeqsb.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2upflykjm.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2byrtruew.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2clvsiwqa.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2knuikwun.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ercgfqot.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2pktboege.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzbohki.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2aogxpwai.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkdfdil.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtlgxax.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkougzry.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkogrnn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjhenky.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ybplbhoj.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojoipswb.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcpdtjn.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2yecwmpcf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmextcx.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ambkjqab.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpezulyr.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znlswpyo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ropbabjh.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fgruqujr.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mndshdim.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbzghcy.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlttnehm.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpqjiiw.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjidmyw.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbolbzc.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mshetfwn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbisnsg.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilngxwlz.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2commutah.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2suqrjsxw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2eybeqaig.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvcuyhg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbdeiog.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdnjziw.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkvshss.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2tygqtjae.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2xepsgnls.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxjmdrn.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fspxdagu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzayvcd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqijjlaf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2iajqgvjk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qklyjlea.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmapkoz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckascsbg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2srecyium.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhojfnj.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzmduvn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2awnudiiq.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpyvlpl.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2knhkxgai.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrodfhq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2izfqpijg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmkmfto.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtsagsc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2utnbmxjn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjtxozc.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvaawbn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgnslhr.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrzafnf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvzpetm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnzvorb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2etdypyos.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ioynodff.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2snocbhat.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqcajrk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjzexwy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ythhgmpd.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dhzfzjgh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2vssdtkek.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnnoils.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sngzjncy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vodjyaja.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwecowjc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmprdul.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpdogsl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwoamqgz.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2utignsct.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2bubxtfvb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmdqnbr.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fzukqprm.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdnwfyu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rxihrkot.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2oupqhlaw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbbxtrw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdfnvlt.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2obgdrypd.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwrxxck.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsbhecr.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgapwqw.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ungjyzuq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrfmnbw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2welmmusx.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwvyjjb.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vyuhtblb.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrlstlu.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqfnwcx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cycmucim.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mntuvjym.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfuwyof.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2usbiijto.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyyzdacq.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2orjmkhlr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rbffeyqb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzblbcc.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzugtob.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2sehrtxkm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ehghqayy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2qenjsqts.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjzasvt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwigdnuf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbogxgut.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2khlrwklm.html


<!-- 参考信息 -->