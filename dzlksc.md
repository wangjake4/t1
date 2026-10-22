代发 wailian999

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cheryme.top/Article/details/gteslagkfh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.quarkkingdee.top/Article/details/gtujtphkcg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yangfankeji.com/Article/details/gtdarlvhdl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zycfv.cn/Article/details/gtsymwoyfg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hammf.cn/Article/details/gtnbqarsgu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxinkj.top/Article/details/gtzhbyfkyc.html

[F03] 写入文件（覆盖）
来源：http://dali.316326.xyz/Article/details/gtwswddeeg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hammf.cn/Article/details/gttyowrywb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.haohaochexian.top/Article/details/gtsnlbfekw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gtpifnwymj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfenidrdg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj20258888.top/Article/details/gtziphcnwj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cdnleiting.top/Article/details/gtllgndxph.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jlsjyb.cn/Article/details/gtlhkwcgyd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtqheoyywf.html

[F04] 追加写入文件
来源：http://dali.daxiang520.top/Article/details/gtyhvvvcfz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.iojbl.cn/Article/details/gtsllbffgr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yonumen.top/Article/details/gtfxdiolct.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yangfankeji.com/Article/details/gtgujjtlfb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtohezkmpl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.dianchejie.cn/Article/details/gtylcrbsut.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gotoacloud.top/Article/details/gtjdipdbno.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zdqjudy.top/Article/details/gtrsehkfsv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtefxlnuml.html

[F05] 判断文件或目录是否存在
来源：http://dali.kuanghao11.cn/Article/details/gtzytljcsv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sweek.top/Article/details/gtynzygjcs.html

PHP:  file_exists("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtipkeabbz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtbpzklrbq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtmabxmadg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gtbhhjvhim.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gotoacloud.top/Article/details/gtnpecxpnz.html

Ruby: File.exist?("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtctpystxh.html

C#:   File.Exists("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gthbabudiq.html

[F06] 删除文件
来源：http://dali.sysykeji.top/Article/details/gtcoqjmobo.html

Py:   os.remove("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtyboosgnp.html

PHP:  unlink("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtocfivctw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtmnfieohg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtsmvjziga.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtkbyywqxy.html

Go:   os.Remove("a.txt")
来源：http://dali.316326.xyz/Article/details/gtfwauynnj.html

Ruby: File.delete("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtiffbznco.html

C#:   File.Delete("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtkawdobgp.html

[F07] 创建目录（含多级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlecdgpxo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.316326.xyz/Article/details/gtdhuhvqpi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cdnleiting.top/Article/details/gtafafbzha.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yonumen.top/Article/details/gtwbsdjqbr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gtoulmowem.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.guannengcc.top/Article/details/gtlskhqpmb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tian-w.cn/Article/details/gtcnjppykx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinghuilouyu.cn/Article/details/gtndrdkahc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.fengsongda.top/Article/details/gtrrclkmmg.html

[F08] 遍历目录
来源：http://dali.iojbl.cn/Article/details/gtdcbmwlqu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hongshengwenyu.top/Article/details/gttwfxxpzr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhoulong.xyz/Article/details/gtwjcaihve.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gtbcohyatu.html

TS:   fs.readdirSync("dir")
来源：http://dali.svipenyu.cn/Article/details/gtliofqtvt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gtcmnyhdko.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xuanzx.com/Article/details/gtovwlmivj.html

Ruby: Dir.children("dir")
来源：http://dali.ybcxt.top/Article/details/gtybhefxyv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ppjwa.cn/Article/details/gtfavvpvcc.html

[F09] 获取文件大小
来源：http://dali.yuanzhike.top/Article/details/gtbscjkjcg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtzpxybqvb.html

PHP:  filesize("a.txt");
来源：http://dali.pycfn.com/Article/details/gtmkghwmxq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gteudrgnxm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenlongwang.top/Article/details/gtsuncnjzm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtoztkxwil.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yuanzhike.top/Article/details/gtfacgelcy.html

Ruby: File.size("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtlnifbrgd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.mhx1999.top/Article/details/gtkmqbdcme.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jianghu66.top/Article/details/gtpmajmhrg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtzxobjhib.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtksgfobiw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtemnbpllo.html

TS:   path.extname("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtukaxsljb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yongpay.top/Article/details/gtgzvhtwbc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtnezfazbf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gterwdvksj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtvzyxeszw.html

[F11] 复制与移动文件
来源：http://dali.cheryme.top/Article/details/gtnqkbmsnj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtalisneld.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zycfv.cn/Article/details/gtqirwjgod.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtzhrzsaxi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtwjpdqcon.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hnqzz.top/Article/details/gtympblvsn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shanyushiyangtech.top/Article/details/gtdzqegldl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtlmbxaxss.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.havefunace.top/Article/details/gthdkjapyi.html

[F12] CSV 读写
来源：http://dali.sxryk.cn/Article/details/gtqfznklgn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.snrcjt.cn/Article/details/gtvpuxydvo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.birdmap.top/Article/details/gtuyxbfoyq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sufxvd.cn/Article/details/gthaptzzag.html

TS:   // 同上
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbaeeaxy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.iojbl.cn/Article/details/gtlscrjsfq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zdqjudy.top/Article/details/gtgwijxavn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shuidangran.top/Article/details/gtpjfjgloo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jqgufenzy.top/Article/details/gtdpyrejlz.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtseggdndv.html

G. 面向对象
来源：http://dali.dashuyun.cn/Article/details/gtrnlyxcfk.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtgkemzrsu.html

[G01] 定义类
来源：http://dali.yonumen.top/Article/details/gtxdoacbhr.html

Py:   class User: pass
来源：http://dali.daria6918.cn/Article/details/gtyguokhll.html

PHP:  class User {}
来源：http://dali.9152youxi.cn/Article/details/gtcjomlnge.html

JS:   class User {}
来源：http://dali.yj20258.top/Article/details/gttusivnwm.html

TS:   class User { name: string = ""; }
来源：http://dali.hysaishi.cn/Article/details/gtegpyipdy.html

Java: class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtalevbygg.html

Go:   type User struct { Name string }
来源：http://dali.kuanghao11.cn/Article/details/gtizriwbws.html

Ruby: class User; end
来源：http://dali.wangshuangyany.cn/Article/details/gtfdrxawki.html

C#:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtddztiuoh.html

[G02] 构造函数
来源：http://dali.zdqjudy.top/Article/details/gtuovvpjot.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yuanzhike.top/Article/details/gtiybumxgb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.havefunace.top/Article/details/gtbdeakyhp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gticcshtch.html

TS:   constructor(public name: string) {}
来源：http://dali.snrcjt.cn/Article/details/gtmgwpahzc.html

Java: User(String name) { this.name = name; }
来源：http://dali.mhx1999.top/Article/details/gtyjtcawgq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cqqwz.cn/Article/details/gthpfipdwd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hfpthk.cn/Article/details/gtiuabhxua.html

C#:   public User(string name) { Name = name; }
来源：http://dali.havefunace.top/Article/details/gtbgsheevo.html

[G03] 实例属性
来源：http://dali.tianlin.xyz/Article/details/gtghrrutqq.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gtjwihqgnu.html

PHP:  public string $name = "x";
来源：http://dali.dashuyun.cn/Article/details/gtogwkibqf.html

JS:   this.name = "x";
来源：http://dali.mhx1999.top/Article/details/gtdwodatis.html

TS:   name: string = "x";
来源：http://dali.fengsongda.top/Article/details/gtobfkwucc.html

Java: private String name;
来源：http://dali.hnqzz.top/Article/details/gtbmrmirjf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jianghu66.top/Article/details/gtjftjqqsb.html

Ruby: @name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gtmcyfcceo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.havefunace.top/Article/details/gtgjddcmdn.html

[G04] 定义方法
来源：http://dali.pengpengdd.cyou/Article/details/gtuccweqch.html

Py:   def greet(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gtiyhkbijl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gtulqcxilq.html

JS:   greet() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gttmxtkqnq.html

TS:   greet(): string { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtbeemhgba.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtylajpbys.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gtvxguiooj.html

Ruby: def greet; @name; end
来源：http://dali.zdqjudy.top/Article/details/gtkfyvfrck.html

C#:   public string Greet() => Name;
来源：http://dali.ybcxt.top/Article/details/gteakeopev.html

[G05] 继承
来源：http://dali.aizwys.cn/Article/details/gtrnsztxvu.html

Py:   class Admin(User): pass
来源：http://dali.zycfv.cn/Article/details/gtyztplmva.html

PHP:  class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtzybowxky.html

JS:   class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtlredgsuv.html

TS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtsfloqcvw.html

Java: class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gtfblwkjcj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.316326.xyz/Article/details/gtzkybjojx.html

Ruby: class Admin < User; end
来源：http://dali.jyoumei.cn/Article/details/gtmrtzekso.html

C#:   class Admin : User {}
来源：http://dali.cucudq.cn/Article/details/gtdaddibiq.html

[G06] 重写方法
来源：http://dali.guannengcc.top/Article/details/gtgvafnhwf.html

Py:   def greet(self): return "admin"
来源：http://dali.hammf.cn/Article/details/gtlyvheilh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtmmurjojq.html

JS:   greet() { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtvvbpypsp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtlvubrciu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtzbzgwgcf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gtygsbbwmt.html

Ruby: def greet; "admin"; end
来源：http://dali.xuanzx.com/Article/details/gtfqeaduju.html

C#:   public override string Greet() => "admin";
来源：http://dali.ppjwa.cn/Article/details/gtjcjwrljt.html

[G07] 调用父类方法
来源：http://dali.gaohongyu789.top/Article/details/gtdfjdbrla.html

Py:   super().greet()
来源：http://dali.tian-w.cn/Article/details/gttxylzgic.html

PHP:  parent::greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtheuqbyiq.html

JS:   super.greet();
来源：http://dali.yangfankeji.com/Article/details/gtkqzjvmoc.html

TS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtpxixhvud.html

Java: super.greet();
来源：http://dali.yuxming.cn/Article/details/gtxreztkqm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tanke756.top/Article/details/gtfadbkhlz.html

Ruby: super
来源：http://dali.shangyingyoupin.top/Article/details/gtnpagmpzr.html

C#:   base.Greet();
来源：http://dali.zhoulong.xyz/Article/details/gtuwljfeig.html

[G08] 静态方法与属性
来源：http://dali.havefunace.top/Article/details/gtaipuydva.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xziqi.cn/Article/details/gtarjcqfrr.html

PHP:  public static function f() {}
来源：http://dali.sxryk.cn/Article/details/gtbvddwrrq.html

JS:   static f() {}
来源：http://dali.hysaishi.cn/Article/details/gtzaxlkgyj.html

TS:   static f(): void {}
来源：http://dali.ehwqpu.com/Article/details/gtqzkrwgnr.html

Java: static void f() {}
来源：http://dali.nanxuanxn.top/Article/details/gtjyiyjyze.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hammf.cn/Article/details/gtlcopgtxi.html

Ruby: def self.f; end
来源：http://dali.daxiang520.top/Article/details/gtsqiijbvq.html

C#:   public static void F() {}
来源：http://dali.yongpay.top/Article/details/gtgoqgyqij.html

[G09] 接口 / 抽象类
来源：http://dali.yvedp.cn/Article/details/gtfaatmjfe.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.smart0.xyz/Article/details/gtifokdoja.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tian-w.cn/Article/details/gtjracbhwn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ehwqpu.com/Article/details/gtfkhseklv.html

TS:   interface Shape { area(): number; }
来源：http://dali.vqdsnc.cn/Article/details/gtmahuucqw.html

Java: interface Shape { double area(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtfeujljlm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.wangdashe.top/Article/details/gtqmfghhtf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinqigufen.top/Article/details/gtcuughdtj.html

C#:   interface IShape { double Area(); }
来源：http://dali.smart0.xyz/Article/details/gtltcceydb.html

[G10] 访问控制
来源：http://dali.yuxming.cn/Article/details/gtdrplecya.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hywenlv.cn/Article/details/gtzovikrbi.html

PHP:  public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gtwsazlneu.html

JS:   #private 字段；其余公开
来源：http://dali.gaohongyu789.top/Article/details/gtjcgfvhrj.html

TS:   public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gtjilittgy.html

Java: public / protected / private / 默认包级
来源：http://dali.guowangkeji.top/Article/details/gtepcelrmj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinghuilouyu.cn/Article/details/gtqhqbmufs.html

Ruby: public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbimqgpxr.html

C#:   public / protected / private / internal
来源：http://dali.birdmap.top/Article/details/gtkoeautxa.html

[G11] getter / setter
来源：http://dali.xylfe.cn/Article/details/gtsloinmzp.html

Py:   @property 与 @x.setter
来源：http://dali.daxiang520.top/Article/details/gtsprmzrui.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtirmxxubw.html

JS:   get name() { return this._name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjtzjmbmh.html

TS:   get name(): string { return this._name; }
来源：http://dali.cqqwz.cn/Article/details/gtenrzatrd.html

Java: public String getName() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtcdjdnica.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gtrsuzsvbg.html

Ruby: attr_accessor :name
来源：http://dali.daria6918.cn/Article/details/gtstocdmwx.html

C#:   public string Name { get; set; }
来源：http://dali.yj20258888.top/Article/details/gtmrhlvjcn.html

[G12] 对象转字符串
来源：http://dali.jiagoushi.top/Article/details/gtrbvxuynl.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gtkdymmkeg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gtzoloosdf.html

JS:   toString() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjsrzprz.html

TS:   toString(): string { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofubeabq.html

Java: @Override public String toString() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtznmzwgoe.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gtgswgsvol.html

Ruby: def to_s; @name; end
来源：http://dali.hongshengwenyu.top/Article/details/gtbgubvawp.html

C#:   public override string ToString() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gtcccazfsy.html

[G13] 判断对象类型
来源：http://dali.birdmap.top/Article/details/gtwooftgth.html

Py:   isinstance(u, User)
来源：http://dali.svipenyu.cn/Article/details/gtpgdothrq.html

PHP:  $u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gtyyvgxchv.html

JS:   u instanceof User
来源：http://dali.yj20258.top/Article/details/gtvsqteqoe.html

TS:   u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gthjidxtjd.html

Java: u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtnruwrrsp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.0kj1m.cn/Article/details/gtutmcecdw.html

Ruby: u.is_a?(User)
来源：http://dali.yvedp.cn/Article/details/gtxersjjfp.html

C#:   u is User
来源：http://dali.shanyushiyangkeji.top/Article/details/gthvmvigjm.html

[G14] 数据类 / record
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqqkasnq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gzhubu.top/Article/details/gtawwlmjcm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.fengsongda.top/Article/details/gtcuybjxap.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cqqwz.cn/Article/details/gtyvgnffev.html

TS:   type User = { name: string; age: number };
来源：http://dali.gaohongyu789.top/Article/details/gtcxtiqaho.html

Java: record User(String name, int age) {}
来源：http://dali.andypj.xyz/Article/details/gtcydusckj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yonumen.top/Article/details/gtacxzthaz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cheryme.top/Article/details/gtyuqghjwc.html

C#:   record User(string Name, int Age);
来源：http://dali.chenlongwang.top/Article/details/gtwjykawce.html

[G15] 枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gtivtvimfy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ybcxt.top/Article/details/gtijmduqsc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.daxiang520.top/Article/details/gtjuizkrrv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.aizwys.cn/Article/details/gtybbcuhcf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yonumen.top/Article/details/gtpeqjarjv.html

Java: enum Color { RED, GREEN }
来源：http://dali.hfpthk.cn/Article/details/gtqlafoelk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xylfe.cn/Article/details/gtiatsxaru.html

Ruby: Color = %i[red green].freeze
来源：http://dali.fzhhl.top/Article/details/gtvufuzsmo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gthuhxnkaq.html

[G16] 对象转数组 / 字典
来源：http://dali.316326.xyz/Article/details/gtguujtudn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.feifeiyinyue.top/Article/details/gtnbytpeuc.html

PHP:  get_object_vars($obj);
来源：http://dali.tanke756.top/Article/details/gtwklalxwl.html

JS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gtnqhzlumh.html

TS:   Object.entries(obj)
来源：http://dali.yonumen.top/Article/details/gtnhfsfssf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.havefunace.top/Article/details/gtdtazadip.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jyoumei.cn/Article/details/gtzefhgdfq.html

Ruby: obj.instance_variables
来源：http://dali.yanxiufei.cn/Article/details/gtrrttqhmu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gtzrbqgytx.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjxgjuvsq.html

H. 异常与错误处理
来源：http://dali.xuanzx.com/Article/details/gtjpokzlgw.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtufynxjcw.html

[H01] try / catch 基础
来源：http://dali.ppjwa.cn/Article/details/gtkbfxffkv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenlongwang.top/Article/details/gtighfsygv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tanke756.top/Article/details/gtbdymgyqx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gtqsnghocx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gtrahgceyj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.guannengcc.top/Article/details/gtbcunhskn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhongyouzk.top/Article/details/gtgntksccq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.mhx1999.top/Article/details/gtuoucmpfk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.dianchejie.cn/Article/details/gtfpvxgxtb.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258.top/Article/details/gtyfipmoyo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dashuyun.cn/Article/details/gttabrubub.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gthuorfbac.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtjekpgccx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gttppsgvtm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtyhqnqsge.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xinyue.icu/Article/details/gtaijthjhr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.fengsongda.top/Article/details/gtdehijdkt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtqeklugll.html

[H03] 主动抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gtsusicyay.html

Py:   raise ValueError("错误信息")
来源：http://dali.cashguo.top/Article/details/gtspedefbh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtrufdiogf.html

JS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtbqbnmdbl.html

TS:   throw new Error("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtsmtxscqv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtfbjjfbhr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.0kj1m.cn/Article/details/gtprgbbzpp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yvedp.cn/Article/details/gtfdpiqzwt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtnrlehzqf.html

[H04] 自定义异常类型
来源：http://dali.ivvv.top/Article/details/gtgmflwrjq.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgfzy.top/Article/details/gtowkwfohk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gzhubu.top/Article/details/gtqsdgndqw.html

JS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gtpeddfoaa.html

TS:   class MyError extends Error {}
来源：http://dali.nanxinkj.top/Article/details/gtugxmtawg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.pycfn.com/Article/details/gtzmyhoxpp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jqgufenzy.top/Article/details/gtnqokwcyq.html

Ruby: class MyError < StandardError; end
来源：http://dali.gogol.net.cn/Article/details/gtddldgsir.html

C#:   class MyException : Exception {}
来源：http://dali.gogol.net.cn/Article/details/gtyfkmgyac.html

[H05] 捕获特定类型
来源：http://dali.ydzc1.top/Article/details/gtfbhrxtar.html

Py:   except ValueError as e:
来源：http://dali.jianghu66.top/Article/details/gtexqgzqru.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gtmmhkwwfe.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigfzy.top/Article/details/gtsnsuqccq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhoulong.xyz/Article/details/gtpxwxkonr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cheryme.top/Article/details/gtvykbqbxb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdrhsxua.html

Ruby: rescue ArgumentError => e
来源：http://dali.cqqwz.cn/Article/details/gtsazveiss.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtclbqxtay.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuanzx.com/Article/details/gtgbyvexkq.html

Py:   value = d.get("k") or default
来源：http://dali.fzhhl.top/Article/details/gtnchxdpmf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sweek.top/Article/details/gtoplabmxa.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuxming.cn/Article/details/gtxsnmfxoz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cheryme.top/Article/details/gtfuhuabdz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yonumen.top/Article/details/gtdxmparmx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.fengsongda.top/Article/details/gtqgvzdblt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cqqwz.cn/Article/details/gtxrizfvlz.html

C#:   obj?.A?.B ?? default
来源：http://dali.hywenlv.cn/Article/details/gtvigxnioe.html


<!-- 参考信息 -->