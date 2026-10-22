代发 wailian999

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj20258.top/Article/details/gtbclpvbbd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenzaomai.com/Article/details/gtsdkbumhb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tianlin.xyz/Article/details/gthqocrjre.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.fengsongda.top/Article/details/gtwkorywht.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xziqi.cn/Article/details/gtvowozbmf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cucudq.cn/Article/details/gtatwnvpqh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuanzx.com/Article/details/gtfxqwlxvj.html

[F08] 遍历目录
来源：http://dali.c1oappe.top/Article/details/gthftvcnwo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.aibaodan.cn/Article/details/gtgmufmtxw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cdnleiting.top/Article/details/gtjuulbzga.html

JS:   fs.readdirSync("dir")
来源：http://dali.dianchejie.cn/Article/details/gtmryyhqtl.html

TS:   fs.readdirSync("dir")
来源：http://dali.jianghu66.top/Article/details/gtoaoqihep.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dashuyun.cn/Article/details/gtulamfodb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.fzhhl.top/Article/details/gtokozogkr.html

Ruby: Dir.children("dir")
来源：http://dali.jianghu66.top/Article/details/gtqekkzpoy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yvedp.cn/Article/details/gtrcuthmua.html

[F09] 获取文件大小
来源：http://dali.meibo888.top/Article/details/gtvejxbjdo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtyfnutjld.html

PHP:  filesize("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtstszlvkm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shangyingyoupin.top/Article/details/gttdrrwdag.html

TS:   fs.statSync("a.txt").size
来源：http://dali.fengsongda.top/Article/details/gtprjvuitf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtxbacrqvg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhixingplan.top/Article/details/gtlxauxkcg.html

Ruby: File.size("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtpxtngpxi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sufxvd.cn/Article/details/gtsvqeblwo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnqzz.top/Article/details/gtswfuwvqk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtfiqmsgsa.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtdmezgsbr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gteabgmgdu.html

TS:   path.extname("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtkvxsugyz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cqqwz.cn/Article/details/gtrpmvzkaa.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtusgtfmrv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtoxwnqcpy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtyibrvhqo.html

[F11] 复制与移动文件
来源：http://dali.andypj.xyz/Article/details/gtwshhinpi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtgqpixpmy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xziqi.cn/Article/details/gtxgfspijv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtndxbfrjv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtkeibqokx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sufxvd.cn/Article/details/gtrchlflvv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhiwuduotai.top/Article/details/gtyfqoqyac.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtirtekgln.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tian-w.cn/Article/details/gtwelrenzr.html

[F12] CSV 读写
来源：http://dali.yvedp.cn/Article/details/gtlxtqfsqz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhongyouzk.top/Article/details/gtswbyiuys.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.feifeiyinyue.top/Article/details/gtvhkwprev.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shuidangran.top/Article/details/gtqoezwtyf.html

TS:   // 同上
来源：http://dali.wangshuangyany.cn/Article/details/gtfuzsruto.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yongpay.top/Article/details/gtblyirctu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yanxiufei.cn/Article/details/gtmxvfvbkc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gzhubu.top/Article/details/gtfjlihyle.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.316326.xyz/Article/details/gtrlfnhakh.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdcczyhdu.html

G. 面向对象
来源：http://dali.sweek.top/Article/details/gtnyffndhs.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gttgjbypvz.html

[G01] 定义类
来源：http://dali.gaohongyu789.top/Article/details/gtplxbkokr.html

Py:   class User: pass
来源：http://dali.wangdashe.top/Article/details/gtahuslsnv.html

PHP:  class User {}
来源：http://dali.jyoumei.cn/Article/details/gtlnjiqqmy.html

JS:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gtaupljhiv.html

TS:   class User { name: string = ""; }
来源：http://dali.yvedp.cn/Article/details/gtfsgbloso.html

Java: class User {}
来源：http://dali.nanxinkj.top/Article/details/gtclpnzcua.html

Go:   type User struct { Name string }
来源：http://dali.jianghu66.top/Article/details/gtekdvvxfo.html

Ruby: class User; end
来源：http://dali.yonumen.top/Article/details/gtzebffcvm.html

C#:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gtozvsvvfr.html

[G02] 构造函数
来源：http://dali.zdqjudy.top/Article/details/gtwokxbrqh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yonumen.top/Article/details/gtfikdrrek.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.birdmap.top/Article/details/gtlfnztfxb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jianghu66.top/Article/details/gtlzmguwfm.html

TS:   constructor(public name: string) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtqteqhkdb.html

Java: User(String name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gthfivugpu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.pycfn.com/Article/details/gtsoeaweti.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cheryme.top/Article/details/gtfxxhzkxl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.fengsongda.top/Article/details/gtxaygvbna.html

[G03] 实例属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuffuujtt.html

Py:   self.name = "x"
来源：http://dali.fengsongda.top/Article/details/gtkvfmscry.html

PHP:  public string $name = "x";
来源：http://dali.yueranfly.top/Article/details/gtehxidgjl.html

JS:   this.name = "x";
来源：http://dali.haohaochexian.top/Article/details/gtqbwsrpwn.html

TS:   name: string = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtynyquqwt.html

Java: private String name;
来源：http://dali.ivvv.top/Article/details/gtwhdqcakp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnqzz.top/Article/details/gtbtifusvw.html

Ruby: @name = "x"
来源：http://dali.vqdsnc.cn/Article/details/gtzfnxdyon.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tianlin.xyz/Article/details/gtsftrglen.html

[G04] 定义方法
来源：http://dali.nwbrower.top/Article/details/gticoknuim.html

Py:   def greet(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gtkwffmyiq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gtxnaxdqgw.html

JS:   greet() { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gtmuwxcxui.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtyaseynrl.html

Java: String greet() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtpxhvdkoa.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gtotogoxlc.html

Ruby: def greet; @name; end
来源：http://dali.gotoacloud.top/Article/details/gtvnwxesov.html

C#:   public string Greet() => Name;
来源：http://dali.yuxming.cn/Article/details/gtangbgipc.html

[G05] 继承
来源：http://dali.c1oappe.top/Article/details/gtjctvqclr.html

Py:   class Admin(User): pass
来源：http://dali.cashguo.top/Article/details/gtodidcrbe.html

PHP:  class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gtqebwsplc.html

JS:   class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gtaojgaqlr.html

TS:   class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtfmuosbws.html

Java: class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtsxdobfwr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfwokpkxh.html

Ruby: class Admin < User; end
来源：http://dali.feifeiyinyue.top/Article/details/gtrqnryrkv.html

C#:   class Admin : User {}
来源：http://dali.zhixingplan.top/Article/details/gtkqjgihvi.html

[G06] 重写方法
来源：http://dali.cucudq.cn/Article/details/gtbzvqqyda.html

Py:   def greet(self): return "admin"
来源：http://dali.chenjidiqi.icu/Article/details/gtlzvwogjy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtgncwqhpy.html

JS:   greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtgiphmhzx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gtndfuatfb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtbnvorkua.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.fengsongda.top/Article/details/gtfbrzqhpm.html

Ruby: def greet; "admin"; end
来源：http://dali.mhx1999.top/Article/details/gtzldnxqfe.html

C#:   public override string Greet() => "admin";
来源：http://dali.zdqjudy.top/Article/details/gtwjhcrloi.html

[G07] 调用父类方法
来源：http://dali.xuetiantiany.cn/Article/details/gtazwybqsr.html

Py:   super().greet()
来源：http://dali.pengpengdd.cyou/Article/details/gtflvlfrii.html

PHP:  parent::greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtmpfdlnad.html

JS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gtsuldbvbh.html

TS:   super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gtcpaqqasy.html

Java: super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtmiwukceg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.havefunace.top/Article/details/gtahatkdzr.html

Ruby: super
来源：http://dali.aizwys.cn/Article/details/gtluichdiz.html

C#:   base.Greet();
来源：http://dali.sweek.top/Article/details/gtonpfhkzg.html

[G08] 静态方法与属性
来源：http://dali.aizwys.cn/Article/details/gtsyzrnaes.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yangfankeji.com/Article/details/gtmrlwjaam.html

PHP:  public static function f() {}
来源：http://dali.hammf.cn/Article/details/gtgjyjufif.html

JS:   static f() {}
来源：http://dali.gzhubu.top/Article/details/gthsexlhlq.html

TS:   static f(): void {}
来源：http://dali.zdqjudy.top/Article/details/gtymzbbzip.html

Java: static void f() {}
来源：http://dali.fengsongda.top/Article/details/gtjkswhqlc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.kuanghao11.cn/Article/details/gtfjbnifyb.html

Ruby: def self.f; end
来源：http://dali.yj20258.top/Article/details/gtkbiydlla.html

C#:   public static void F() {}
来源：http://dali.cucudq.cn/Article/details/gtocsxokvc.html

[G09] 接口 / 抽象类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgkuksnxk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangtech.top/Article/details/gthyfvyihu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xinyue.icu/Article/details/gtwfunspek.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yuxming.cn/Article/details/gtzioxxepu.html

TS:   interface Shape { area(): number; }
来源：http://dali.yueranfly.top/Article/details/gthdrncdok.html

Java: interface Shape { double area(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtnppytdce.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.havefunace.top/Article/details/gtkzddncjp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shzxlz.cn/Article/details/gtaegbtasg.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj20258.top/Article/details/gtkajmnnmi.html

[G10] 访问控制
来源：http://dali.yanxiufei.cn/Article/details/gtcpivzccm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.kuanghao11.cn/Article/details/gthwqaseui.html

PHP:  public / protected / private
来源：http://dali.yueranfly.top/Article/details/gtuctcneql.html

JS:   #private 字段；其余公开
来源：http://dali.meibo888.top/Article/details/gtpekqnobq.html

TS:   public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtpgjuiqpn.html

Java: public / protected / private / 默认包级
来源：http://dali.chenlongwang.top/Article/details/gtukqpyydz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sxryk.cn/Article/details/gtdpfrktpb.html

Ruby: public / protected / private
来源：http://dali.yj20258888.top/Article/details/gtgrkxfsva.html

C#:   public / protected / private / internal
来源：http://dali.zhongyouzk.top/Article/details/gthkcippmc.html

[G11] getter / setter
来源：http://dali.zdqjudy.top/Article/details/gtiotnumxq.html

Py:   @property 与 @x.setter
来源：http://dali.guannengcc.top/Article/details/gtlnywgboy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtseemvljr.html

JS:   get name() { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gtxiqcthzl.html

TS:   get name(): string { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gtijpcxiog.html

Java: public String getName() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtvhkgqwzk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gtvrijkejo.html

Ruby: attr_accessor :name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyuurhsfu.html

C#:   public string Name { get; set; }
来源：http://dali.cheryme.top/Article/details/gtxzluxeew.html

[G12] 对象转字符串
来源：http://dali.316326.xyz/Article/details/gthdfrwfwk.html

Py:   def __str__(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gtemcrgkxn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtpwrpvebw.html

JS:   toString() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gteoruznmg.html

TS:   toString(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtyrizimqc.html

Java: @Override public String toString() { return name; }
来源：http://dali.yuxming.cn/Article/details/gtbyoxciag.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gthfeklyqs.html

Ruby: def to_s; @name; end
来源：http://dali.jyoumei.cn/Article/details/gtjzipflrn.html

C#:   public override string ToString() => Name;
来源：http://dali.nwbrower.top/Article/details/gtrgldlxuq.html

[G13] 判断对象类型
来源：http://dali.dianchejie.cn/Article/details/gtprzpwlhg.html

Py:   isinstance(u, User)
来源：http://dali.yuxming.cn/Article/details/gtxrbzzspi.html

PHP:  $u instanceof User
来源：http://dali.sweek.top/Article/details/gtyhijcvjf.html

JS:   u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtauzuzfhj.html

TS:   u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtblgebumg.html

Java: u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtiaswftxh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangtech.top/Article/details/gtjavmyhbr.html

Ruby: u.is_a?(User)
来源：http://dali.redwolf501.top/Article/details/gtzjjuypwn.html

C#:   u is User
来源：http://dali.svipenyu.cn/Article/details/gtugzquotq.html

[G14] 数据类 / record
来源：http://dali.gzhubu.top/Article/details/gtszjesygr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigufen.top/Article/details/gtutlckdnx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yvedp.cn/Article/details/gtujqxjykw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yongpay.top/Article/details/gtkrilkvcf.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenlongwang.top/Article/details/gtwmsftzqj.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtaakuznba.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjaichsjk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sufxvd.cn/Article/details/gtizztrazv.html

C#:   record User(string Name, int Age);
来源：http://dali.kuanghao11.cn/Article/details/gtjmuhshaz.html

[G15] 枚举
来源：http://dali.ehwqpu.com/Article/details/gtkwrqcxsl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.snrcjt.cn/Article/details/gtsgdggfse.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gzhubu.top/Article/details/gtbposgjlp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.c1oappe.top/Article/details/gtwdvfhczz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tian-w.cn/Article/details/gtssdboxsh.html

Java: enum Color { RED, GREEN }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrfoozrix.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.fzhhl.top/Article/details/gtwqtqrach.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ehwqpu.com/Article/details/gtlnkqpxsv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gteoxfkqpr.html

[G16] 对象转数组 / 字典
来源：http://dali.yongpay.top/Article/details/gtaxqnzasa.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.birdmap.top/Article/details/gtncdwcpkg.html

PHP:  get_object_vars($obj);
来源：http://dali.yuanzhike.top/Article/details/gtfrkvoqcw.html

JS:   Object.entries(obj)
来源：http://dali.pycfn.com/Article/details/gtuaarrcvc.html

TS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gtdcpqthnb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zdqjudy.top/Article/details/gtullgreog.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.pycfn.com/Article/details/gtpdkytpjk.html

Ruby: obj.instance_variables
来源：http://dali.haohaochexian.top/Article/details/gtpstfkxkn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj20258.top/Article/details/gtthdlvdtn.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtjcgweiaa.html

H. 异常与错误处理
来源：http://dali.snrcjt.cn/Article/details/gtwvlsdgkn.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxtsxdcm.html

[H01] try / catch 基础
来源：http://dali.jinghuilouyu.cn/Article/details/gtcufqeayp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj20258.top/Article/details/gtgvakxjrl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtgfpuyhyt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcklgqex.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gtkjyilrhj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cheryme.top/Article/details/gtolixdyyb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.andypj.xyz/Article/details/gtcttyfjgi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.pycfn.com/Article/details/gtbtackboc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xuanzx.com/Article/details/gtysdffqac.html

[H02] finally / ensure 收尾
来源：http://dali.jyoumei.cn/Article/details/gtolzhhgin.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangdashe.top/Article/details/gtvfmcgnff.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtudqoakzp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtikhclwtz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtnvkczkyq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtkgljslkd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yangfankeji.com/Article/details/gtkpnwyacw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.0kj1m.cn/Article/details/gtonegqzan.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrwmyycay.html

[H03] 主动抛出异常
来源：http://dali.yvedp.cn/Article/details/gtclhskmks.html

Py:   raise ValueError("错误信息")
来源：http://dali.dashuyun.cn/Article/details/gtrvwrdvic.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtabkdjpah.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gtjirphbcj.html

TS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzoychtld.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtlbrsbkax.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcpwodvoz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258.top/Article/details/gtcaeviofp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtjcryoctd.html

[H04] 自定义异常类型
来源：http://dali.havefunace.top/Article/details/gtdepnpqtp.html

Py:   class MyError(Exception): pass
来源：http://dali.shuidangran.top/Article/details/gtuatuldkw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hnxiangtu.top/Article/details/gtghxuptho.html

JS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gtqwuvljew.html

TS:   class MyError extends Error {}
来源：http://dali.guannengcc.top/Article/details/gtwlpgndar.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yonumen.top/Article/details/gtaxfxumxj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ppjwa.cn/Article/details/gtipmtwovu.html

Ruby: class MyError < StandardError; end
来源：http://dali.316326.xyz/Article/details/gtyusyerxn.html

C#:   class MyException : Exception {}
来源：http://dali.xuanzx.com/Article/details/gtuqjtuagz.html

[H05] 捕获特定类型
来源：http://dali.yanxiufei.cn/Article/details/gtjonulavh.html

Py:   except ValueError as e:
来源：http://dali.jyoumei.cn/Article/details/gtwwfbwijm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxzygvym.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258888.top/Article/details/gtroxgkadt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gtaojhfrfb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.quarkkingdee.top/Article/details/gtbvyoxmjl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hnxiangtu.top/Article/details/gtiknbenal.html

Ruby: rescue ArgumentError => e
来源：http://dali.tanke756.top/Article/details/gtktbnklnw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtkwaanznr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.vqdsnc.cn/Article/details/gthicbvjkj.html

Py:   value = d.get("k") or default
来源：http://dali.0kj1m.cn/Article/details/gtvnivgnqf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gtizobusuf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ybcxt.top/Article/details/gtvginfswv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cheryme.top/Article/details/gtodouziqe.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.dashuyun.cn/Article/details/gtaoxvonhc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yanxiufei.cn/Article/details/gtcoxayhct.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdlbpfagj.html

C#:   obj?.A?.B ?? default
来源：http://dali.316326.xyz/Article/details/gtqoiidpfp.html

[H07] 断言
来源：http://dali.xinyue.icu/Article/details/gtaqgiihkw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvythajcf.html

PHP:  assert($x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gthgffcywv.html

JS:   console.assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtafhpppcx.html

TS:   console.assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gtenbocqqh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yongpay.top/Article/details/gtrczbjrct.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.dashuyun.cn/Article/details/gtlrlrfglr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yueranfly.top/Article/details/gtujmcecvw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gtszsdpwpk.html

[H08] 获取错误信息与堆栈
来源：http://dali.yonumen.top/Article/details/gtdspyuxnt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.bjfxy.top/Article/details/gtmlmiihsl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.c1oappe.top/Article/details/gtdvmesulb.html

JS:   e.message;  e.stack
来源：http://dali.zhoulong.xyz/Article/details/gttglwxpog.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ppjwa.cn/Article/details/gtezulqchk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.pengpengdd.cyou/Article/details/gtxhyeukfn.html

Go:   err.Error()
来源：http://dali.havefunace.top/Article/details/gtnddczrji.html

Ruby: e.message;  e.backtrace
来源：http://dali.ydzc1.top/Article/details/gtfoiyrqan.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yongpay.top/Article/details/gtnlzohnbx.html

[H09] 带错误码的异常
来源：http://dali.shuidangran.top/Article/details/gtqgvitzso.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xuanzx.com/Article/details/gtuwmdhjhn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenzaomai.com/Article/details/gtwvxeqptm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zdqjudy.top/Article/details/gthmhqbvbd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fengsongda.top/Article/details/gtruypaivu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yj20258.top/Article/details/gtcghekymv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xuanzx.com/Article/details/gtiizkcvpi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ivvv.top/Article/details/gtzbvmgwku.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ehwqpu.com/Article/details/gtgkaqntww.html

[H10] 资源自动释放
来源：http://dali.guowangkeji.top/Article/details/gtmhyemtim.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sufxvd.cn/Article/details/gtsxfjvasz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gogol.net.cn/Article/details/gtkokpqmpx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jiagoushi.top/Article/details/gthqjlcfas.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gtinubhlpr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.meibo888.top/Article/details/gtmmtkkzqw.html

Go:   defer f.Close()
来源：http://dali.cashguo.top/Article/details/gttdocadnt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shzxlz.cn/Article/details/gtmkkvmxqg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtkqazenrl.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtemfjmuro.html

I. 正则表达式
来源：http://dali.jiagoushi.top/Article/details/gtqqdkzpbe.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtoxckhlyl.html

[I01] 判断是否匹配
来源：http://dali.sweek.top/Article/details/gtdelqafpy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtmdqsukya.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.haohaochexian.top/Article/details/gtltdjyvso.html

JS:   /\d+/.test(s)
来源：http://dali.hnqzz.top/Article/details/gtisgrgdcp.html

TS:   /\d+/.test(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsmnfrqns.html


<!-- 参考信息 -->