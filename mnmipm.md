代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fengsongda.top/Article/details/gtpcbxxteg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.mhx1999.top/Article/details/gtszdncvud.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtjgssiznb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.c1oappe.top/Article/details/gtytaesnpz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yongpay.top/Article/details/gtecxwevty.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.dashuyun.cn/Article/details/gtvllicish.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gaohongyu789.top/Article/details/gtlgwnkfbe.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.fzhhl.top/Article/details/gtagzccosa.html

[F05] 判断文件或目录是否存在
来源：http://dali.jyoumei.cn/Article/details/gtscrsealj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.andypj.xyz/Article/details/gtpzxzzobp.html

PHP:  file_exists("a.txt");
来源：http://dali.ivvv.top/Article/details/gtgzkquosc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtahpbdptk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtfzsfmavz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtqzuokrxg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ydzc1.top/Article/details/gtphufeacw.html

Ruby: File.exist?("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtdlegjskp.html

C#:   File.Exists("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtgkymoxlu.html

[F06] 删除文件
来源：http://dali.shuidangran.top/Article/details/gtyyhzexar.html

Py:   os.remove("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzafcltbo.html

PHP:  unlink("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtfwndpahx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrcuukhpx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gthelsaioc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtmpiqdfhp.html

Go:   os.Remove("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtmlideost.html

Ruby: File.delete("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtfgfygldt.html

C#:   File.Delete("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtthjpxrjd.html

[F07] 创建目录（含多级）
来源：http://dali.cashguo.top/Article/details/gtborugwse.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hywenlv.cn/Article/details/gtsdadzmjy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.havefunace.top/Article/details/gtcrrdxonb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pengpengdd.cyou/Article/details/gtveotodnn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gtofxnslpq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jianghu66.top/Article/details/gtnbalzimq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shzxlz.cn/Article/details/gtlnviuchg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ppjwa.cn/Article/details/gtkiiihyiw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yuxming.cn/Article/details/gtpdlumfux.html

[F08] 遍历目录
来源：http://dali.zhoulong.xyz/Article/details/gtsqccsdmv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cdnleiting.top/Article/details/gtpxolsqht.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jlsjyb.cn/Article/details/gthmabycpy.html

JS:   fs.readdirSync("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gttgrmwgoz.html

TS:   fs.readdirSync("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtsritdubv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.pycfn.com/Article/details/gtpmvdityq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtoxtriltn.html

Ruby: Dir.children("dir")
来源：http://dali.nwbrower.top/Article/details/gtonrbstak.html

C#:   Directory.GetFiles("dir")
来源：http://dali.andypj.xyz/Article/details/gtsfrseuyh.html

[F09] 获取文件大小
来源：http://dali.0kj1m.cn/Article/details/gtwsceupph.html

Py:   os.path.getsize("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtibgtenhn.html

PHP:  filesize("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtkaqpwdqm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gtxcseonys.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yvedp.cn/Article/details/gtusnnkzpl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtwyfemazy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tian-w.cn/Article/details/gtdspwrpfn.html

Ruby: File.size("a.txt")
来源：http://dali.cheryme.top/Article/details/gtaisupxji.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jyoumei.cn/Article/details/gtuyxhiizc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.daxiang520.top/Article/details/gtkzjtgpta.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtpvlnvvta.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xuanzx.com/Article/details/gtknzjqgak.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtxvzvemay.html

TS:   path.extname("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gttsnufjwu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hysaishi.cn/Article/details/gtnlzxiesf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtmestpuvv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtycjxlnbe.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gturxrwelo.html

[F11] 复制与移动文件
来源：http://dali.quarkkingdee.top/Article/details/gtxpyhorxl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtqyphgvvq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj20258.top/Article/details/gtxniqqydd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtjoqcmgxb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtmjjimjzn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cdnleiting.top/Article/details/gtveayqydh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ehwqpu.com/Article/details/gthrfzrgoi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtqmwphter.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.haohaochexian.top/Article/details/gtfokufdpo.html

[F12] CSV 读写
来源：http://dali.tianlin.xyz/Article/details/gtuhioiuma.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tanke756.top/Article/details/gtktztkbvb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.aizwys.cn/Article/details/gthzomhdsb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zdqjudy.top/Article/details/gtmhxhlrdp.html

TS:   // 同上
来源：http://dali.birdmap.top/Article/details/gteilyfrny.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shzxlz.cn/Article/details/gtkbzzjlev.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tianlin.xyz/Article/details/gttqigttvv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sufxvd.cn/Article/details/gtpnvyxmwv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.andypj.xyz/Article/details/gtrapqhnfr.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtqigfeqyz.html

G. 面向对象
来源：http://dali.cucudq.cn/Article/details/gtkymyidnx.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtrfqsdrgm.html

[G01] 定义类
来源：http://dali.dashuyun.cn/Article/details/gtroeemcgg.html

Py:   class User: pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkrmqxlm.html

PHP:  class User {}
来源：http://dali.dashuyun.cn/Article/details/gtendrscbo.html

JS:   class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzzulpopf.html

TS:   class User { name: string = ""; }
来源：http://dali.cashguo.top/Article/details/gtryikaqmv.html

Java: class User {}
来源：http://dali.jianghu66.top/Article/details/gtgutwrkuj.html

Go:   type User struct { Name string }
来源：http://dali.tian-w.cn/Article/details/gtkrylhpyo.html

Ruby: class User; end
来源：http://dali.chenlongwang.top/Article/details/gtyfuhccuy.html

C#:   class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtzcsuabzm.html

[G02] 构造函数
来源：http://dali.jlsjyb.cn/Article/details/gtcpedrjgd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sxryk.cn/Article/details/gtxhoqbncz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cdnleiting.top/Article/details/gtgbylqgxd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gotoacloud.top/Article/details/gtebbxtebe.html

TS:   constructor(public name: string) {}
来源：http://dali.yangfankeji.com/Article/details/gtorilqhux.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtevopqcmb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nwbrower.top/Article/details/gtjrllpwrc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hywenlv.cn/Article/details/gtivrnqskn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtguzdfzbd.html

[G03] 实例属性
来源：http://dali.tian-w.cn/Article/details/gtpshzikng.html

Py:   self.name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gtebelaetn.html

PHP:  public string $name = "x";
来源：http://dali.ivvv.top/Article/details/gtnmipifym.html

JS:   this.name = "x";
来源：http://dali.jinqigufen.top/Article/details/gtqwzxmxsw.html

TS:   name: string = "x";
来源：http://dali.daxiang520.top/Article/details/gtjaiqvgpr.html

Java: private String name;
来源：http://dali.sysykeji.top/Article/details/gtoehykved.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shangyingyoupin.top/Article/details/gtswjfknvy.html

Ruby: @name = "x"
来源：http://dali.ehwqpu.com/Article/details/gteoavdvss.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtbwmprxng.html

[G04] 定义方法
来源：http://dali.snrcjt.cn/Article/details/gtqacodyei.html

Py:   def greet(self): return self.name
来源：http://dali.c1oappe.top/Article/details/gtundjwhdv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gtleqmxvgx.html

JS:   greet() { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtwvbpdpxs.html

TS:   greet(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtoszrnqhh.html

Java: String greet() { return name; }
来源：http://dali.cucudq.cn/Article/details/gthuaoscdn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtmxqflndx.html

Ruby: def greet; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaygqurxr.html

C#:   public string Greet() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gtdmnijcgj.html

[G05] 继承
来源：http://dali.fengsongda.top/Article/details/gtuqgrzmnw.html

Py:   class Admin(User): pass
来源：http://dali.yueranfly.top/Article/details/gtizmxsjgn.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtzdyjltet.html

JS:   class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsufqvcsn.html

TS:   class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtsqqpstvm.html

Java: class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtovgfjiqz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yueranfly.top/Article/details/gtgcmjyaxz.html

Ruby: class Admin < User; end
来源：http://dali.yj20258888.top/Article/details/gtftbtfhdb.html

C#:   class Admin : User {}
来源：http://dali.cashguo.top/Article/details/gtajbdojwf.html

[G06] 重写方法
来源：http://dali.havefunace.top/Article/details/gtyupzpgzt.html

Py:   def greet(self): return "admin"
来源：http://dali.chenjidiqi.icu/Article/details/gtmhrnfazj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtgyslfaxu.html

JS:   greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtnvwheckd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtirblxltq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtdooqnzyh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hnxiangtu.top/Article/details/gtrwcjbchq.html

Ruby: def greet; "admin"; end
来源：http://dali.hnxiangtu.top/Article/details/gtofonyqni.html

C#:   public override string Greet() => "admin";
来源：http://dali.hysaishi.cn/Article/details/gttnultfbn.html

[G07] 调用父类方法
来源：http://dali.sysykeji.top/Article/details/gtnplxixgw.html

Py:   super().greet()
来源：http://dali.pengpengdd.cyou/Article/details/gtplolrekl.html

PHP:  parent::greet();
来源：http://dali.cashguo.top/Article/details/gtzhqeywln.html

JS:   super.greet();
来源：http://dali.dashuyun.cn/Article/details/gtshgxwzqk.html

TS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gtcqaqnptb.html

Java: super.greet();
来源：http://dali.yj20258888.top/Article/details/gtywauycbb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sxryk.cn/Article/details/gtrbucfuaj.html

Ruby: super
来源：http://dali.dianchejie.cn/Article/details/gtckuyfdug.html

C#:   base.Greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtdqkjxuvn.html

[G08] 静态方法与属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgckkxfiy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.feifeiyinyue.top/Article/details/gtfaiwnvel.html

PHP:  public static function f() {}
来源：http://dali.kuanghao11.cn/Article/details/gtrnxaquvt.html

JS:   static f() {}
来源：http://dali.sufxvd.cn/Article/details/gtiznaiged.html

TS:   static f(): void {}
来源：http://dali.zhiwuduotai.top/Article/details/gtsrtxnkrp.html

Java: static void f() {}
来源：http://dali.zhengqikj.top/Article/details/gtnkkdkvrt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhongyouzk.top/Article/details/gtnlegyjbg.html

Ruby: def self.f; end
来源：http://dali.redwolf501.top/Article/details/gtqfeftrbe.html

C#:   public static void F() {}
来源：http://dali.sxryk.cn/Article/details/gtnrnubqwj.html

[G09] 接口 / 抽象类
来源：http://dali.jqgfzy.top/Article/details/gtbntlpdhs.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sweek.top/Article/details/gthgxemsat.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxinkj.top/Article/details/gtuheuuiqd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.9152youxi.cn/Article/details/gtighxgnmp.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnmzkbktj.html

Java: interface Shape { double area(); }
来源：http://dali.andypj.xyz/Article/details/gtoonrinsb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tanke756.top/Article/details/gtmewxmfbu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daria6918.cn/Article/details/gteumcylvy.html

C#:   interface IShape { double Area(); }
来源：http://dali.nwbrower.top/Article/details/gttsaumlqm.html

[G10] 访问控制
来源：http://dali.c1oappe.top/Article/details/gtafginmxf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cucudq.cn/Article/details/gtldmazita.html

PHP:  public / protected / private
来源：http://dali.cheryme.top/Article/details/gthxohoqbw.html

JS:   #private 字段；其余公开
来源：http://dali.hfpthk.cn/Article/details/gtflwiexea.html

TS:   public / protected / private
来源：http://dali.cheryme.top/Article/details/gtcycryllf.html

Java: public / protected / private / 默认包级
来源：http://dali.daxiang520.top/Article/details/gtqqiliyfj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.feifeiyinyue.top/Article/details/gtxkvetcnq.html

Ruby: public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gtgrqudhuj.html

C#:   public / protected / private / internal
来源：http://dali.yanxiufei.cn/Article/details/gtejefplhz.html

[G11] getter / setter
来源：http://dali.hongshengwenyu.top/Article/details/gtqicnjufo.html

Py:   @property 与 @x.setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjiojakqc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gtlupuawom.html

JS:   get name() { return this._name; }
来源：http://dali.guowangkeji.top/Article/details/gtcyttscfc.html

TS:   get name(): string { return this._name; }
来源：http://dali.wangdashe.top/Article/details/gtdcskqzqj.html

Java: public String getName() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtrlwnwuev.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtsjjjvqiv.html

Ruby: attr_accessor :name
来源：http://dali.ywan-chungtsiang.top/Article/details/gttkizjhye.html

C#:   public string Name { get; set; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtifxzvjkq.html

[G12] 对象转字符串
来源：http://dali.chenlongwang.top/Article/details/gtxpuopnxg.html

Py:   def __str__(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gtbylajdqt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtigpezzbw.html

JS:   toString() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtdpedpykm.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdkyszzak.html

Java: @Override public String toString() { return name; }
来源：http://dali.xziqi.cn/Article/details/gtkaqdhyav.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gtfvxycjig.html

Ruby: def to_s; @name; end
来源：http://dali.jqgfzy.top/Article/details/gtmaxpvhav.html

C#:   public override string ToString() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gtnjlyqvaz.html

[G13] 判断对象类型
来源：http://dali.yuxming.cn/Article/details/gtbvrcrqro.html

Py:   isinstance(u, User)
来源：http://dali.gaohongyu789.top/Article/details/gtmlycucjj.html

PHP:  $u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtsyppueyx.html

JS:   u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtugwhvgov.html

TS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtsqoptszn.html

Java: u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtnqnfcuxh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.chenzaomai.com/Article/details/gtpjcccifg.html

Ruby: u.is_a?(User)
来源：http://dali.pycfn.com/Article/details/gthgytkkzb.html

C#:   u is User
来源：http://dali.gogol.net.cn/Article/details/gttjhfwdmw.html

[G14] 数据类 / record
来源：http://dali.yueranfly.top/Article/details/gtszybiiil.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nwbrower.top/Article/details/gtuxbmtvti.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ppjwa.cn/Article/details/gtobjwhjty.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.316326.xyz/Article/details/gthchiqweq.html

TS:   type User = { name: string; age: number };
来源：http://dali.9152youxi.cn/Article/details/gtytrygceh.html

Java: record User(String name, int age) {}
来源：http://dali.zhixingplan.top/Article/details/gtdqsllerc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hfpthk.cn/Article/details/gtumtfnofp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sweek.top/Article/details/gtmznefnca.html

C#:   record User(string Name, int Age);
来源：http://dali.hywenlv.cn/Article/details/gtljsyxppt.html

[G15] 枚举
来源：http://dali.zhoulong.xyz/Article/details/gtuomyohrz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnvltjnnf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xinyue.icu/Article/details/gtmgzqbtav.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yuxming.cn/Article/details/gtpcelduzi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gtbyvfnayr.html

Java: enum Color { RED, GREEN }
来源：http://dali.yuanzhike.top/Article/details/gtxqtliwca.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.pengpengdd.cyou/Article/details/gtehxjrera.html

Ruby: Color = %i[red green].freeze
来源：http://dali.feifeiyinyue.top/Article/details/gtgqkkxipt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gthukublcw.html

[G16] 对象转数组 / 字典
来源：http://dali.tianlin.xyz/Article/details/gtgburdaul.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.aibaodan.cn/Article/details/gtgpmtklep.html

PHP:  get_object_vars($obj);
来源：http://dali.hfpthk.cn/Article/details/gtndanxxlj.html

JS:   Object.entries(obj)
来源：http://dali.hywenlv.cn/Article/details/gtntlkxihl.html

TS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gthklvsrdb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.haohaochexian.top/Article/details/gtxxjkksqa.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.snrcjt.cn/Article/details/gtduvaqvwg.html

Ruby: obj.instance_variables
来源：http://dali.yangfankeji.com/Article/details/gtmqtviozl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.vqdsnc.cn/Article/details/gtyvurulhr.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtmujwfdpr.html

H. 异常与错误处理
来源：http://dali.zhengqikj.top/Article/details/gtwxnsuicz.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtozvreanq.html

[H01] try / catch 基础
来源：http://dali.cdnleiting.top/Article/details/gtpsfuwpsm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmmlockqz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hfpthk.cn/Article/details/gtqekyaacx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hysaishi.cn/Article/details/gtrjdicoul.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gtxeyyozwd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zycfv.cn/Article/details/gtqlguvxms.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.snrcjt.cn/Article/details/gtunotihoj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwfbqlyy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zdqjudy.top/Article/details/gtvdfwkagz.html

[H02] finally / ensure 收尾
来源：http://dali.sxryk.cn/Article/details/gtxijucxkq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yangfankeji.com/Article/details/gtpmlxoxrz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtjoqorvtx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gthotfdmnt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtiiiskqyd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtptmqzntl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangtech.top/Article/details/gtpgivyehi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenjidiqi.icu/Article/details/gtsphxsnkl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtikixndey.html

[H03] 主动抛出异常
来源：http://dali.pycfn.com/Article/details/gthpfsurhf.html

Py:   raise ValueError("错误信息")
来源：http://dali.birdmap.top/Article/details/gtypswiwzd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtgphgpdti.html

JS:   throw new Error("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtshdtvsyi.html

TS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtocjktwxh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtlmiozojx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sysykeji.top/Article/details/gtlnnjqukn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shzxlz.cn/Article/details/gttcwfjocd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqgpeokm.html

[H04] 自定义异常类型
来源：http://dali.nwbrower.top/Article/details/gtmroweksv.html

Py:   class MyError(Exception): pass
来源：http://dali.iojbl.cn/Article/details/gtjkmmqgio.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gtktvyquwg.html

JS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gtvqeeyllu.html

TS:   class MyError extends Error {}
来源：http://dali.xziqi.cn/Article/details/gtbgqvvypr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yvedp.cn/Article/details/gtmkyblfsl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.fengsongda.top/Article/details/gtzrocqkau.html

Ruby: class MyError < StandardError; end
来源：http://dali.sufxvd.cn/Article/details/gtyevqirhc.html

C#:   class MyException : Exception {}
来源：http://dali.mhx1999.top/Article/details/gtsgibogwu.html

[H05] 捕获特定类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzrzbdbu.html

Py:   except ValueError as e:
来源：http://dali.tianlin.xyz/Article/details/gtvywjuahi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.daxiang520.top/Article/details/gtejjjxkmj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gtnglxxomw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gtsthywvht.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.vqdsnc.cn/Article/details/gtgnorjgpc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.smart0.xyz/Article/details/gtflapvrni.html

Ruby: rescue ArgumentError => e
来源：http://dali.gzhubu.top/Article/details/gtgvrpzauf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tian-w.cn/Article/details/gthdjzlydz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cdnleiting.top/Article/details/gticvlvrbt.html

Py:   value = d.get("k") or default
来源：http://dali.snrcjt.cn/Article/details/gtvrythwdn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gthygbizkp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sufxvd.cn/Article/details/gttcfvymll.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gtrejdxvyk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.vqdsnc.cn/Article/details/gtxxlassnj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.fzhhl.top/Article/details/gthlytjyav.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cheryme.top/Article/details/gtocgnkqkr.html

C#:   obj?.A?.B ?? default
来源：http://dali.zdqjudy.top/Article/details/gtaecewxif.html

[H07] 断言
来源：http://dali.quarkkingdee.top/Article/details/gtwidqvoav.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hysaishi.cn/Article/details/gtsbxcdvqr.html

PHP:  assert($x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpttcqzwz.html

JS:   console.assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gtrkuauftt.html

TS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gtosffuyxh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.feifeiyinyue.top/Article/details/gtortplkrz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yvedp.cn/Article/details/gtdfbnkkks.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shanyushiyangtech.top/Article/details/gtggouvyrf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gtulqurswm.html

[H08] 获取错误信息与堆栈
来源：http://dali.fengsongda.top/Article/details/gtedqxhxto.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yangfankeji.com/Article/details/gtszlsnvmk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gzhubu.top/Article/details/gtyevlkhbd.html

JS:   e.message;  e.stack
来源：http://dali.shzxlz.cn/Article/details/gttoiehwuc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aizwys.cn/Article/details/gtxmfhynmr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jqgfzy.top/Article/details/gtudqscbbg.html

Go:   err.Error()
来源：http://dali.zhiwuduotai.top/Article/details/gttmknvwpc.html


<!-- 参考信息 -->