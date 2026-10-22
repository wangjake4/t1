代发 wailian999

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigufen.top/Article/details/gtzqqnovjn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zycfv.cn/Article/details/gtwggtwgtc.html

PHP:  file_exists("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtquqrfbzl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtjmsozokm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtovzbxpvg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtjrqvirwd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj202588.top/Article/details/gtpgdxlhhd.html

Ruby: File.exist?("a.txt")
来源：http://dali.316326.xyz/Article/details/gtnpgqtvbw.html

C#:   File.Exists("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrooijkej.html

[F06] 删除文件
来源：http://dali.quarkkingdee.top/Article/details/gtbnfdgvyb.html

Py:   os.remove("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtvmudsddd.html

PHP:  unlink("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtixhckphz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtnstpxvyd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtwjlkzllo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gthapzelrk.html

Go:   os.Remove("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtsktbbyrc.html

Ruby: File.delete("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtgfwfajpb.html

C#:   File.Delete("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtteiesxcy.html

[F07] 创建目录（含多级）
来源：http://dali.cashguo.top/Article/details/gtohpgdbcr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shuidangran.top/Article/details/gtzzpvizyf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hammf.cn/Article/details/gtqmyupdcq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yueranfly.top/Article/details/gtgjxvksyj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guowangkeji.top/Article/details/gtqrnprruz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhoulong.xyz/Article/details/gtmjvwlvyx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.birdmap.top/Article/details/gtdxytgclw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhiwuduotai.top/Article/details/gtsjdlpeht.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.smart0.xyz/Article/details/gtyzcywpxb.html

[F08] 遍历目录
来源：http://dali.shuidangran.top/Article/details/gtzwovcjjc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuanzx.com/Article/details/gtslxcmdzw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenzaomai.com/Article/details/gtactymhbg.html

JS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gthyinybcr.html

TS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gtgtawhuyu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cashguo.top/Article/details/gtshwoxete.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guannengcc.top/Article/details/gtrcolifhj.html

Ruby: Dir.children("dir")
来源：http://dali.zdqjudy.top/Article/details/gtbhfenhsc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shzxlz.cn/Article/details/gtbqzvfnjw.html

[F09] 获取文件大小
来源：http://dali.quarkkingdee.top/Article/details/gtowglhmct.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgyqbdnm.html

PHP:  filesize("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcolhrdh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.316326.xyz/Article/details/gtwpimtkjw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.c1oappe.top/Article/details/gtsntwtson.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gtvglqysvj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.haohaochexian.top/Article/details/gttwgtaoar.html

Ruby: File.size("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtagvdflao.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhongyouzk.top/Article/details/gttgutgvtd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jiagoushi.top/Article/details/gtehrtjmko.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtegdapdgb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtefhskbqt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtwzrbuwrm.html

TS:   path.extname("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtyvfmgqjt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.guannengcc.top/Article/details/gtlzcrlgns.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtonyeskrz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtvksauoaq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtesldkvvp.html

[F11] 复制与移动文件
来源：http://dali.gogol.net.cn/Article/details/gtpesskzza.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtkxbxuvdx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xinyue.icu/Article/details/gtsqspodsq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtfvirrwwm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gthwtzlcwc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jyoumei.cn/Article/details/gtjdwwafmf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.svipenyu.cn/Article/details/gtpcmrjhsj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtjxpnookl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhiwuduotai.top/Article/details/gtndhpinsr.html

[F12] CSV 读写
来源：http://dali.jqgufenzy.top/Article/details/gtgquluziy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yonumen.top/Article/details/gtbnbrikot.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenzaomai.com/Article/details/gtikjuemyn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxinkj.top/Article/details/gtmnkkbhte.html

TS:   // 同上
来源：http://dali.sysykeji.top/Article/details/gtsvzkkzol.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxxsqrtub.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.fengsongda.top/Article/details/gtgsjjrarr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nwbrower.top/Article/details/gtqerfdzkx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gaohongyu789.top/Article/details/gtadcvilqh.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtwxelihih.html

G. 面向对象
来源：http://dali.chenzaomai.com/Article/details/gthkcmfout.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtwebnrrvz.html

[G01] 定义类
来源：http://dali.yj202588.top/Article/details/gthtewnbet.html

Py:   class User: pass
来源：http://dali.jinqigufen.top/Article/details/gtehvuyufd.html

PHP:  class User {}
来源：http://dali.cheryme.top/Article/details/gtoqtkwirj.html

JS:   class User {}
来源：http://dali.andypj.xyz/Article/details/gtzakwdsht.html

TS:   class User { name: string = ""; }
来源：http://dali.yonumen.top/Article/details/gtjztnkswz.html

Java: class User {}
来源：http://dali.daxiang520.top/Article/details/gtcdsortwm.html

Go:   type User struct { Name string }
来源：http://dali.nanxuanxn.top/Article/details/gtpkxptzxm.html

Ruby: class User; end
来源：http://dali.daxiang520.top/Article/details/gtwewjqxtc.html

C#:   class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtibtynqiy.html

[G02] 构造函数
来源：http://dali.hammf.cn/Article/details/gtszkayrsc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hysaishi.cn/Article/details/gttmxpvupb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yuxming.cn/Article/details/gttrmrtszf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xylfe.cn/Article/details/gtslnwrith.html

TS:   constructor(public name: string) {}
来源：http://dali.jqgfzy.top/Article/details/gttkcgdfkb.html

Java: User(String name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gtbsdpwesj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guowangkeji.top/Article/details/gtqclmcold.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yangfankeji.com/Article/details/gtnpggxkwl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenzaomai.com/Article/details/gtpvmvwrlw.html

[G03] 实例属性
来源：http://dali.feifeiyinyue.top/Article/details/gtzvztdcvf.html

Py:   self.name = "x"
来源：http://dali.hysaishi.cn/Article/details/gtcgvqdvuu.html

PHP:  public string $name = "x";
来源：http://dali.meibo888.top/Article/details/gtyaglkgoz.html

JS:   this.name = "x";
来源：http://dali.xziqi.cn/Article/details/gtcbgwzdpr.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlexumarl.html

Java: private String name;
来源：http://dali.cheryme.top/Article/details/gtvemrfnla.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ehwqpu.com/Article/details/gtpmvlpaon.html

Ruby: @name = "x"
来源：http://dali.cheryme.top/Article/details/gtgxmoauks.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shuidangran.top/Article/details/gtsnocnwxd.html

[G04] 定义方法
来源：http://dali.yvedp.cn/Article/details/gtstbbdcii.html

Py:   def greet(self): return self.name
来源：http://dali.meibo888.top/Article/details/gtrsuaefku.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gtbawdkjch.html

JS:   greet() { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gtwxgbgucl.html

TS:   greet(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtxhsduagz.html

Java: String greet() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtczzraael.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtvkmyiget.html

Ruby: def greet; @name; end
来源：http://dali.9152youxi.cn/Article/details/gtronyfoag.html

C#:   public string Greet() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gtapfefgex.html

[G05] 继承
来源：http://dali.jqgufenzy.top/Article/details/gtjplejjhw.html

Py:   class Admin(User): pass
来源：http://dali.guannengcc.top/Article/details/gtieznjomc.html

PHP:  class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gtlvapwxol.html

JS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtztniqadu.html

TS:   class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtlncmkjzt.html

Java: class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtukyhmthj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cdnleiting.top/Article/details/gtydhgzhsq.html

Ruby: class Admin < User; end
来源：http://dali.ydzc1.top/Article/details/gtryjfsxzj.html

C#:   class Admin : User {}
来源：http://dali.jqgufenzy.top/Article/details/gtdpqcpuer.html

[G06] 重写方法
来源：http://dali.0kj1m.cn/Article/details/gtzwtveyge.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gtodxwbdvq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtbmlmniee.html

JS:   greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtrduhzuky.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtgyvfdpyv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtnlrctzjl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.aizwys.cn/Article/details/gteabsgxsp.html

Ruby: def greet; "admin"; end
来源：http://dali.zhongyouzk.top/Article/details/gttwnenznq.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuanzx.com/Article/details/gtomygnpgs.html

[G07] 调用父类方法
来源：http://dali.xuetiantiany.cn/Article/details/gtomzyeovl.html

Py:   super().greet()
来源：http://dali.gotoacloud.top/Article/details/gtsysyeiqt.html

PHP:  parent::greet();
来源：http://dali.0kj1m.cn/Article/details/gtolefflhh.html

JS:   super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtplcjbzys.html

TS:   super.greet();
来源：http://dali.sysykeji.top/Article/details/gtahyeqtkv.html

Java: super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtvreunbhq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nanxuanxn.top/Article/details/gtomrbygbj.html

Ruby: super
来源：http://dali.yanxiufei.cn/Article/details/gtnohyvzjp.html

C#:   base.Greet();
来源：http://dali.fzhhl.top/Article/details/gtvfxghheh.html

[G08] 静态方法与属性
来源：http://dali.fzhhl.top/Article/details/gtmjyflkkc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yongpay.top/Article/details/gtfsviavfe.html

PHP:  public static function f() {}
来源：http://dali.yj202588.top/Article/details/gtqnihcexl.html

JS:   static f() {}
来源：http://dali.havefunace.top/Article/details/gtrzmunkhp.html

TS:   static f(): void {}
来源：http://dali.pycfn.com/Article/details/gtereoxpmh.html

Java: static void f() {}
来源：http://dali.jinqigufen.top/Article/details/gtejfxtcfv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ybcxt.top/Article/details/gtuqejplqd.html

Ruby: def self.f; end
来源：http://dali.sweek.top/Article/details/gtlcjxxlsb.html

C#:   public static void F() {}
来源：http://dali.sweek.top/Article/details/gtwebberuh.html

[G09] 接口 / 抽象类
来源：http://dali.jlsjyb.cn/Article/details/gtbxobcpij.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimwlfgvx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenjidiqi.icu/Article/details/gttbedpikf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yvedp.cn/Article/details/gtdzyzifco.html

TS:   interface Shape { area(): number; }
来源：http://dali.yangfankeji.com/Article/details/gtftjfclmo.html

Java: interface Shape { double area(); }
来源：http://dali.jiagoushi.top/Article/details/gtqgbwedrp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenlongwang.top/Article/details/gtfnuipisc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.quarkkingdee.top/Article/details/gtyfcoiwzm.html

C#:   interface IShape { double Area(); }
来源：http://dali.xziqi.cn/Article/details/gtqphvlsww.html

[G10] 访问控制
来源：http://dali.316326.xyz/Article/details/gtdpfylbmu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gotoacloud.top/Article/details/gtbasojjuc.html

PHP:  public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gtzsyfswck.html

JS:   #private 字段；其余公开
来源：http://dali.bjfxy.top/Article/details/gtojxkdlin.html

TS:   public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gtnarpclqj.html

Java: public / protected / private / 默认包级
来源：http://dali.yuxming.cn/Article/details/gtglqednxa.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenlongwang.top/Article/details/gtuokskbtm.html

Ruby: public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gtsbocmjcv.html

C#:   public / protected / private / internal
来源：http://dali.meibo888.top/Article/details/gtakjcwaxa.html

[G11] getter / setter
来源：http://dali.cucudq.cn/Article/details/gtxvdiffml.html

Py:   @property 与 @x.setter
来源：http://dali.xziqi.cn/Article/details/gtcnbkfmxi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gtsaybqrdz.html

JS:   get name() { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gtrjgcdbqj.html

TS:   get name(): string { return this._name; }
来源：http://dali.shzxlz.cn/Article/details/gtborvogtj.html

Java: public String getName() { return name; }
来源：http://dali.xziqi.cn/Article/details/gtdxauctar.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gttnmjjqqq.html

Ruby: attr_accessor :name
来源：http://dali.yj202588.top/Article/details/gtwuyshvlk.html

C#:   public string Name { get; set; }
来源：http://dali.c1oappe.top/Article/details/gtrsrsbjfe.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gtguhmycsm.html

Py:   def __str__(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gtcrrwspwf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gtwwexogmu.html

JS:   toString() { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtxmcoretm.html

TS:   toString(): string { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtngaccrop.html

Java: @Override public String toString() { return name; }
来源：http://dali.xuanzx.com/Article/details/gtjkwqzqju.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gtvepcqvzx.html

Ruby: def to_s; @name; end
来源：http://dali.havefunace.top/Article/details/gtvvgkdxhq.html

C#:   public override string ToString() => Name;
来源：http://dali.jiagoushi.top/Article/details/gtqtlcxyfi.html

[G13] 判断对象类型
来源：http://dali.redwolf501.top/Article/details/gtezcytgwf.html

Py:   isinstance(u, User)
来源：http://dali.havefunace.top/Article/details/gtsjotkvqe.html

PHP:  $u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtthenctah.html

JS:   u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtczpnvhkg.html

TS:   u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtoxqktbjb.html

Java: u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gttrfysikq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxuanxn.top/Article/details/gtdmexsafm.html

Ruby: u.is_a?(User)
来源：http://dali.jinqigufen.top/Article/details/gtgehfmsgc.html

C#:   u is User
来源：http://dali.cashguo.top/Article/details/gtqpckxmus.html

[G14] 数据类 / record
来源：http://dali.hnqzz.top/Article/details/gtwpdynbag.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hongshengwenyu.top/Article/details/gtxkcisabt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pycfn.com/Article/details/gtczlqcclz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.snrcjt.cn/Article/details/gtyalhyhwd.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhengqikj.top/Article/details/gtfrolarrl.html

Java: record User(String name, int age) {}
来源：http://dali.hywenlv.cn/Article/details/gtafanbcta.html

Go:   type User struct { Name string; Age int }
来源：http://dali.9152youxi.cn/Article/details/gttqqqgvss.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yonumen.top/Article/details/gtxqjuqfsx.html

C#:   record User(string Name, int Age);
来源：http://dali.yanxiufei.cn/Article/details/gtenepjhfi.html

[G15] 枚举
来源：http://dali.yongpay.top/Article/details/gtjcryjxzr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuetiantiany.cn/Article/details/gtwgdubgql.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvyhhvsbi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sweek.top/Article/details/gtrciykkmu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhixingplan.top/Article/details/gtcpwaagfj.html

Java: enum Color { RED, GREEN }
来源：http://dali.wangshuangyany.cn/Article/details/gtrrgqndyd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.meibo888.top/Article/details/gtldutieaj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwicbhoyb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hywenlv.cn/Article/details/gtqenavxza.html

[G16] 对象转数组 / 字典
来源：http://dali.aibaodan.cn/Article/details/gtiwmnjbfj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sweek.top/Article/details/gthykpajfx.html

PHP:  get_object_vars($obj);
来源：http://dali.guannengcc.top/Article/details/gtbesavnnm.html

JS:   Object.entries(obj)
来源：http://dali.redwolf501.top/Article/details/gtqrlriltw.html

TS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrgxhzezl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gaohongyu789.top/Article/details/gteguikwhr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cdnleiting.top/Article/details/gtvetoxysh.html

Ruby: obj.instance_variables
来源：http://dali.nanxuanxn.top/Article/details/gtifcnjwpf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gtblstzgow.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtkqanzvry.html

H. 异常与错误处理
来源：http://dali.cucudq.cn/Article/details/gtgagnbuoc.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gteooseymg.html

[H01] try / catch 基础
来源：http://dali.bjfxy.top/Article/details/gtzekcyims.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gzhubu.top/Article/details/gtqrdyusrq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.fengsongda.top/Article/details/gtndsicjso.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gtdobrwhzj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gtsddijtcr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenlongwang.top/Article/details/gtsshqzetu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.c1oappe.top/Article/details/gtaomcqwkx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yuxming.cn/Article/details/gtofjmcaev.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.meibo888.top/Article/details/gtngdplauy.html

[H02] finally / ensure 收尾
来源：http://dali.nwbrower.top/Article/details/gtckbefbfi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebceqeqf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtbdolwmhx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtvfayawpi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtufmvfdok.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtudaptdbo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xziqi.cn/Article/details/gtbforuorb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenlongwang.top/Article/details/gtyqaygqzq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtmndqwkhh.html

[H03] 主动抛出异常
来源：http://dali.zycfv.cn/Article/details/gtzshvhlwc.html

Py:   raise ValueError("错误信息")
来源：http://dali.vqdsnc.cn/Article/details/gtdkuteodb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gteifvunor.html

JS:   throw new Error("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtinyphiom.html

TS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gtbqtfcfdn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtxnzzraje.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gtbxropblw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jianghu66.top/Article/details/gtugvztgst.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtvcrphfms.html

[H04] 自定义异常类型
来源：http://dali.zhiwuduotai.top/Article/details/gtspmaneip.html

Py:   class MyError(Exception): pass
来源：http://dali.aibaodan.cn/Article/details/gtbrmykklv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenzaomai.com/Article/details/gtyvjdjyun.html

JS:   class MyError extends Error {}
来源：http://dali.fzhhl.top/Article/details/gtatfpmotr.html

TS:   class MyError extends Error {}
来源：http://dali.pengpengdd.cyou/Article/details/gtssjqnjzp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gtlpxihrhw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigufen.top/Article/details/gtencywbph.html

Ruby: class MyError < StandardError; end
来源：http://dali.shzxlz.cn/Article/details/gtfjjovhlc.html

C#:   class MyException : Exception {}
来源：http://dali.gogol.net.cn/Article/details/gtnawfaxdg.html

[H05] 捕获特定类型
来源：http://dali.fzhhl.top/Article/details/gtvfjhzfrb.html

Py:   except ValueError as e:
来源：http://dali.zhixingplan.top/Article/details/gtztmrqsym.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yongpay.top/Article/details/gtuwezpyha.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtombhpyqq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtalunyxzi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj202588.top/Article/details/gtrqbvnttn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.feifeiyinyue.top/Article/details/gtjbxbrgpl.html

Ruby: rescue ArgumentError => e
来源：http://dali.c1oappe.top/Article/details/gtfaeqrkra.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthziuzhrf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shangyingyoupin.top/Article/details/gtxivmjqin.html

Py:   value = d.get("k") or default
来源：http://dali.haohaochexian.top/Article/details/gtsemrdsgi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ybcxt.top/Article/details/gtpuzokjyd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhongyouzk.top/Article/details/gtixazsete.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gtitwlopsg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnqzz.top/Article/details/gtswyhuagu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yonumen.top/Article/details/gtoebhqfcg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ybcxt.top/Article/details/gtzsnjziyt.html

C#:   obj?.A?.B ?? default
来源：http://dali.mhx1999.top/Article/details/gtpwwkwpxp.html

[H07] 断言
来源：http://dali.cqqwz.cn/Article/details/gtzyzgjoff.html

Py:   assert x > 0, "必须为正"
来源：http://dali.kuanghao11.cn/Article/details/gtvmyelqbc.html

PHP:  assert($x > 0);
来源：http://dali.fzhhl.top/Article/details/gtgrqxpzgk.html

JS:   console.assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgopmywtv.html

TS:   console.assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gtqcvqmsfa.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yonumen.top/Article/details/gthiqxzvqr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinqigfzy.top/Article/details/gtdiufuswq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigufen.top/Article/details/gtucugdufv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtftssiavg.html

[H08] 获取错误信息与堆栈
来源：http://dali.smart0.xyz/Article/details/gtlxsjcwsw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj20258888.top/Article/details/gtljzeyoez.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jqgfzy.top/Article/details/gtwwhwvsym.html

JS:   e.message;  e.stack
来源：http://dali.guannengcc.top/Article/details/gtmijqpgnu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.smart0.xyz/Article/details/gtznomiqlh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nanxinkj.top/Article/details/gtqooptrfe.html

Go:   err.Error()
来源：http://dali.jiagoushi.top/Article/details/gtsjlqcbwf.html

Ruby: e.message;  e.backtrace
来源：http://dali.aibaodan.cn/Article/details/gtpgiodcnd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ivvv.top/Article/details/gtimmtknpr.html

[H09] 带错误码的异常
来源：http://dali.ehwqpu.com/Article/details/gtixraecmq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhengqikj.top/Article/details/gtknvqnzkd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cdnleiting.top/Article/details/gtksjowpxi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.daxiang520.top/Article/details/gtnfudwyfv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj202588.top/Article/details/gtbtlvpfhe.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.feifeiyinyue.top/Article/details/gtezvphdoe.html


<!-- 参考信息 -->