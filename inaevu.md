代发 wailian999

[F09] 获取文件大小
来源：http://dali.yj20258.top/Article/details/gtzimkpduf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtoapdulvi.html

PHP:  filesize("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtnbvicwwu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gtvvvdixnn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gthaourjfd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtnviovngv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gzhubu.top/Article/details/gtwkdtbilb.html

Ruby: File.size("a.txt")
来源：http://dali.tanke756.top/Article/details/gtexvfezaw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jiagoushi.top/Article/details/gtglgykvnq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxuanxn.top/Article/details/gtvnlmdnav.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtofbanjzj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.iojbl.cn/Article/details/gteoashegz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtfxoihvea.html

TS:   path.extname("a.txt")
来源：http://dali.daria6918.cn/Article/details/gthsnlhacd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258888.top/Article/details/gtghfzzclg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtjmkubluw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtcfsldywn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtrzfdxxex.html

[F11] 复制与移动文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqjhokmxz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gtnuoprvlu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gogol.net.cn/Article/details/gtxvoxxinf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gttpiinhjr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuahfczjn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuanzx.com/Article/details/gtvjbygmxc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhoulong.xyz/Article/details/gtvdabpurh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtcyhpofnq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tian-w.cn/Article/details/gtturuiklw.html

[F12] CSV 读写
来源：http://dali.yongpay.top/Article/details/gtymkyjvcr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.svipenyu.cn/Article/details/gthvsqyibu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhixingplan.top/Article/details/gtphiabfsu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ppjwa.cn/Article/details/gtmddsxdbp.html

TS:   // 同上
来源：http://dali.yj20258.top/Article/details/gtqbuyrrng.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.mhx1999.top/Article/details/gtbavukvvs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tanke756.top/Article/details/gtlkhkzewd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenlongwang.top/Article/details/gtsjularye.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yanxiufei.cn/Article/details/gtxpicmskk.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gthvefdxuk.html

G. 面向对象
来源：http://dali.feifeiyinyue.top/Article/details/gtospeifia.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtpvcluktm.html

[G01] 定义类
来源：http://dali.aibaodan.cn/Article/details/gtdeyccasz.html

Py:   class User: pass
来源：http://dali.tian-w.cn/Article/details/gtrdqtwwxj.html

PHP:  class User {}
来源：http://dali.smart0.xyz/Article/details/gtbuhczbky.html

JS:   class User {}
来源：http://dali.yj202588.top/Article/details/gtbseeiznv.html

TS:   class User { name: string = ""; }
来源：http://dali.yuxming.cn/Article/details/gtokicbifi.html

Java: class User {}
来源：http://dali.mhx1999.top/Article/details/gtjsfcaycw.html

Go:   type User struct { Name string }
来源：http://dali.ydzc1.top/Article/details/gtzxjwasto.html

Ruby: class User; end
来源：http://dali.nanxuanxn.top/Article/details/gtyaggzdee.html

C#:   class User {}
来源：http://dali.shuidangran.top/Article/details/gtrmrtokfn.html

[G02] 构造函数
来源：http://dali.guannengcc.top/Article/details/gtfrcxxbsg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ivvv.top/Article/details/gtellqwrlj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhixingplan.top/Article/details/gtpwkzyrij.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgfzy.top/Article/details/gtrjjdyvtd.html

TS:   constructor(public name: string) {}
来源：http://dali.vqdsnc.cn/Article/details/gtagsrehxl.html

Java: User(String name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gthpguwgvz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.meibo888.top/Article/details/gtlbpwjwlp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yongpay.top/Article/details/gtkbpxbuzf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtgjkyqzsk.html

[G03] 实例属性
来源：http://dali.meibo888.top/Article/details/gtvahrcyws.html

Py:   self.name = "x"
来源：http://dali.316326.xyz/Article/details/gtewwuntsl.html

PHP:  public string $name = "x";
来源：http://dali.ivvv.top/Article/details/gtfwvbialf.html

JS:   this.name = "x";
来源：http://dali.haohaochexian.top/Article/details/gtiswvgerz.html

TS:   name: string = "x";
来源：http://dali.zycfv.cn/Article/details/gtivkrpefy.html

Java: private String name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjgfnbhcg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrkeljtmu.html

Ruby: @name = "x"
来源：http://dali.hysaishi.cn/Article/details/gtyyxweqze.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxinkj.top/Article/details/gtdskspiwg.html

[G04] 定义方法
来源：http://dali.tianlin.xyz/Article/details/gtynqglonf.html

Py:   def greet(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gtabvdfadv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gtpjytrqim.html

JS:   greet() { return this.name; }
来源：http://dali.sweek.top/Article/details/gtcypprkby.html

TS:   greet(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtonhbfseo.html

Java: String greet() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtyyikctnv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtjrduqbdu.html

Ruby: def greet; @name; end
来源：http://dali.gotoacloud.top/Article/details/gtlkdxdpwn.html

C#:   public string Greet() => Name;
来源：http://dali.zhengqikj.top/Article/details/gtilvnvkoi.html

[G05] 继承
来源：http://dali.shangyingyoupin.top/Article/details/gtuvtkudkq.html

Py:   class Admin(User): pass
来源：http://dali.zhongyouzk.top/Article/details/gtcjggkjwj.html

PHP:  class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtwtdbstcs.html

JS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtulqyiihd.html

TS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gthutidxua.html

Java: class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtzrwggwmk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tanke756.top/Article/details/gtwupzyfmo.html

Ruby: class Admin < User; end
来源：http://dali.tian-w.cn/Article/details/gtokcpyjkv.html

C#:   class Admin : User {}
来源：http://dali.jiagoushi.top/Article/details/gtenqvuzog.html

[G06] 重写方法
来源：http://dali.wangdashe.top/Article/details/gtmpkfoktl.html

Py:   def greet(self): return "admin"
来源：http://dali.gotoacloud.top/Article/details/gtmpwnkwcu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gthoaadohg.html

JS:   greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtcrfhvjsx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtqhajmqjz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtexgapumn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ppjwa.cn/Article/details/gtatvbstid.html

Ruby: def greet; "admin"; end
来源：http://dali.jlsjyb.cn/Article/details/gtczrfomzk.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenlongwang.top/Article/details/gtotxkgzec.html

[G07] 调用父类方法
来源：http://dali.jinqigfzy.top/Article/details/gtfifyxyxp.html

Py:   super().greet()
来源：http://dali.kuanghao11.cn/Article/details/gtisezsliz.html

PHP:  parent::greet();
来源：http://dali.guowangkeji.top/Article/details/gtrehivdro.html

JS:   super.greet();
来源：http://dali.zhixingplan.top/Article/details/gtyxvweqfk.html

TS:   super.greet();
来源：http://dali.redwolf501.top/Article/details/gtzbtcdjqw.html

Java: super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gthabnndnn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sysykeji.top/Article/details/gtthdazyzy.html

Ruby: super
来源：http://dali.xuetiantiany.cn/Article/details/gtrsncfoht.html

C#:   base.Greet();
来源：http://dali.zhengqikj.top/Article/details/gtuldoqcbl.html

[G08] 静态方法与属性
来源：http://dali.fengsongda.top/Article/details/gtffuxycmz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnqzz.top/Article/details/gttbbbzmis.html

PHP:  public static function f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtqsawcoxj.html

JS:   static f() {}
来源：http://dali.yangfankeji.com/Article/details/gtsxcoktmw.html

TS:   static f(): void {}
来源：http://dali.gotoacloud.top/Article/details/gtskxhsisb.html

Java: static void f() {}
来源：http://dali.fzhhl.top/Article/details/gtnoukrsal.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.mhx1999.top/Article/details/gtcimevpeh.html

Ruby: def self.f; end
来源：http://dali.cheryme.top/Article/details/gttnhvvufy.html

C#:   public static void F() {}
来源：http://dali.chenzaomai.com/Article/details/gteikwncrx.html

[G09] 接口 / 抽象类
来源：http://dali.snrcjt.cn/Article/details/gtrwlhcpjh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zdqjudy.top/Article/details/gtcymuewpz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sxryk.cn/Article/details/gthqpjlucl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhoulong.xyz/Article/details/gtqvbjiydv.html

TS:   interface Shape { area(): number; }
来源：http://dali.shzxlz.cn/Article/details/gtwlxlvlts.html

Java: interface Shape { double area(); }
来源：http://dali.zhongyouzk.top/Article/details/gtdtwevwsv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ydzc1.top/Article/details/gtwapknwao.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ehwqpu.com/Article/details/gtbsukyfpj.html

C#:   interface IShape { double Area(); }
来源：http://dali.yuxming.cn/Article/details/gtkfcjtjep.html

[G10] 访问控制
来源：http://dali.hnqzz.top/Article/details/gtdgedovyk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hfpthk.cn/Article/details/gtcrmrstvt.html

PHP:  public / protected / private
来源：http://dali.birdmap.top/Article/details/gtcvrbxzjw.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigfzy.top/Article/details/gtfrqdjlxz.html

TS:   public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gtfdshvqse.html

Java: public / protected / private / 默认包级
来源：http://dali.zhongyouzk.top/Article/details/gtjuduzrai.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.wangdashe.top/Article/details/gtjrppjdjn.html

Ruby: public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtqzpyspgi.html

C#:   public / protected / private / internal
来源：http://dali.zhoulong.xyz/Article/details/gtdlhmazjb.html

[G11] getter / setter
来源：http://dali.dianchejie.cn/Article/details/gtkozfxdpn.html

Py:   @property 与 @x.setter
来源：http://dali.hfpthk.cn/Article/details/gtuidkbpnl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gtucjghano.html

JS:   get name() { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gtxzojhtjr.html

TS:   get name(): string { return this._name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtjqrfjrdy.html

Java: public String getName() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtwaflukms.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gtmdaikttr.html

Ruby: attr_accessor :name
来源：http://dali.svipenyu.cn/Article/details/gtbxmumlhd.html

C#:   public string Name { get; set; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttymvibuj.html

[G12] 对象转字符串
来源：http://dali.tian-w.cn/Article/details/gtqoxwyrmw.html

Py:   def __str__(self): return self.name
来源：http://dali.cashguo.top/Article/details/gtwxsffuyq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gthrqreeyx.html

JS:   toString() { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gtmnusjtce.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtsadwilfp.html

Java: @Override public String toString() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtoosarpqx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbknkhfgi.html

Ruby: def to_s; @name; end
来源：http://dali.tian-w.cn/Article/details/gtuvrsuwyh.html

C#:   public override string ToString() => Name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gthlqhsryv.html

[G13] 判断对象类型
来源：http://dali.yuxming.cn/Article/details/gtqcplfuuz.html

Py:   isinstance(u, User)
来源：http://dali.nanxuanxn.top/Article/details/gtvlvwhtfd.html

PHP:  $u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gtndzblkby.html

JS:   u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gttgzuzoul.html

TS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtchilaysf.html

Java: u instanceof User
来源：http://dali.tanke756.top/Article/details/gtpmubvgpe.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.iojbl.cn/Article/details/gttnulancp.html

Ruby: u.is_a?(User)
来源：http://dali.jiagoushi.top/Article/details/gtigwlbooo.html

C#:   u is User
来源：http://dali.kuanghao11.cn/Article/details/gtbsqwexhv.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxgpicjk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hywenlv.cn/Article/details/gtpybazolp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cheryme.top/Article/details/gtvvvldhvi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.aizwys.cn/Article/details/gtyfbnxelu.html

TS:   type User = { name: string; age: number };
来源：http://dali.gotoacloud.top/Article/details/gtbwlouirz.html

Java: record User(String name, int age) {}
来源：http://dali.0kj1m.cn/Article/details/gtbhrbfplz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydjneagn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.meibo888.top/Article/details/gtvilhjgrx.html

C#:   record User(string Name, int Age);
来源：http://dali.cashguo.top/Article/details/gtqsjavksy.html

[G15] 枚举
来源：http://dali.zhongyouzk.top/Article/details/gtudtyicqw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zdqjudy.top/Article/details/gtuscywzdc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhixingplan.top/Article/details/gtsvzxlxvx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhoulong.xyz/Article/details/gtegunrhtc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtaxzucdpa.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenjidiqi.icu/Article/details/gtwbdtfxxr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenlongwang.top/Article/details/gtnsminbrn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhiwuduotai.top/Article/details/gtdrkkiylm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hfpthk.cn/Article/details/gtzhbvwksw.html

[G16] 对象转数组 / 字典
来源：http://dali.dashuyun.cn/Article/details/gtmawkcyeg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zycfv.cn/Article/details/gtuwmhdvvx.html

PHP:  get_object_vars($obj);
来源：http://dali.dianchejie.cn/Article/details/gtcdloqqar.html

JS:   Object.entries(obj)
来源：http://dali.yonumen.top/Article/details/gtpmknzenr.html

TS:   Object.entries(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtldtdkbxw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yvedp.cn/Article/details/gtmpfjavac.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hnxiangtu.top/Article/details/gtpeuclvnn.html

Ruby: obj.instance_variables
来源：http://dali.hywenlv.cn/Article/details/gtjxjxeash.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyinrmtfu.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmddcsck.html

H. 异常与错误处理
来源：http://dali.tian-w.cn/Article/details/gtxlvhyxwj.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtlgusccbm.html

[H01] try / catch 基础
来源：http://dali.zhiwuduotai.top/Article/details/gtbrhiscsm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nanxinkj.top/Article/details/gteookgwcc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hnxiangtu.top/Article/details/gthagmqkxr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gtcdklnjdn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gtgcrxyyue.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sysykeji.top/Article/details/gtkxuppqkf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.redwolf501.top/Article/details/gtufoldxjc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangdashe.top/Article/details/gtphgesgkn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhixingplan.top/Article/details/gtztrgbqkw.html

[H02] finally / ensure 收尾
来源：http://dali.fzhhl.top/Article/details/gtdtzvufzx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.feifeiyinyue.top/Article/details/gtolgpmepj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtsyezdqpr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtrjwhxlty.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtybkmtpfn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtudohyldl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ydzc1.top/Article/details/gtpygqiqbx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.mhx1999.top/Article/details/gttokspims.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sweek.top/Article/details/gtfivsnyna.html

[H03] 主动抛出异常
来源：http://dali.hywenlv.cn/Article/details/gtqgkmlwpq.html

Py:   raise ValueError("错误信息")
来源：http://dali.mhx1999.top/Article/details/gtxrbgyrdy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtedkkcasl.html

JS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtnumynbuu.html

TS:   throw new Error("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtjvrkkdwd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtrmtlvhgs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.pengpengdd.cyou/Article/details/gtrnsfegeh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenzaomai.com/Article/details/gtdutoipng.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtgktlnxln.html

[H04] 自定义异常类型
来源：http://dali.gogol.net.cn/Article/details/gtvrgwwlji.html

Py:   class MyError(Exception): pass
来源：http://dali.c1oappe.top/Article/details/gtwdnubmhg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hywenlv.cn/Article/details/gtqpwcvxhb.html

JS:   class MyError extends Error {}
来源：http://dali.hnqzz.top/Article/details/gtmovmgkks.html

TS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvqkxnrha.html

Java: class MyException extends RuntimeException {}
来源：http://dali.pycfn.com/Article/details/gtfkikkgex.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.kuanghao11.cn/Article/details/gtdtmmthsv.html

Ruby: class MyError < StandardError; end
来源：http://dali.havefunace.top/Article/details/gtixajxjbu.html

C#:   class MyException : Exception {}
来源：http://dali.yongpay.top/Article/details/gthugqfcqt.html

[H05] 捕获特定类型
来源：http://dali.hnqzz.top/Article/details/gtsvfdayvt.html

Py:   except ValueError as e:
来源：http://dali.yuxming.cn/Article/details/gtotcvzjxe.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ehwqpu.com/Article/details/gtgmswxldy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hnqzz.top/Article/details/gtfgwbdrma.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258.top/Article/details/gtahbjprfi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tianlin.xyz/Article/details/gtzdthxpxo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.pengpengdd.cyou/Article/details/gtcnksmkum.html

Ruby: rescue ArgumentError => e
来源：http://dali.tianlin.xyz/Article/details/gtzuxnfymo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cdnleiting.top/Article/details/gtsejuyjfo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuanzx.com/Article/details/gtfecynewh.html

Py:   value = d.get("k") or default
来源：http://dali.ehwqpu.com/Article/details/gtyibltinc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.guannengcc.top/Article/details/gtndiciegk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.quarkkingdee.top/Article/details/gtwuyrefuz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gtcztwfzfa.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjucpffnm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gtvrzxggvl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadynmiuz.html

C#:   obj?.A?.B ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtmymbdncq.html

[H07] 断言
来源：http://dali.ydzc1.top/Article/details/gtqfftyaol.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yueranfly.top/Article/details/gtrprwaibw.html

PHP:  assert($x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtjwkjzwqi.html

JS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gtxcbpjmul.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gteieqipky.html

Java: assert x > 0 : "必须为正";
来源：http://dali.snrcjt.cn/Article/details/gtttztsvxe.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzyflbgv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuanzhike.top/Article/details/gthkzbjypw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtunswmrsk.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangdashe.top/Article/details/gtyxscqhoq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenzaomai.com/Article/details/gtafhkexlz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hnqzz.top/Article/details/gtkmyamttu.html

JS:   e.message;  e.stack
来源：http://dali.aizwys.cn/Article/details/gtrtvckrwp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.quarkkingdee.top/Article/details/gtulvqrcrx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj202588.top/Article/details/gtjstsaqxc.html

Go:   err.Error()
来源：http://dali.tian-w.cn/Article/details/gtpjanulog.html

Ruby: e.message;  e.backtrace
来源：http://dali.ppjwa.cn/Article/details/gteycthyjf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.bjfxy.top/Article/details/gtiahwrfvg.html

[H09] 带错误码的异常
来源：http://dali.meibo888.top/Article/details/gtugjewoak.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinqigfzy.top/Article/details/gtzhigohux.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jqgufenzy.top/Article/details/gtxwpoofrz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.mhx1999.top/Article/details/gtnedkuvzh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sxryk.cn/Article/details/gtqlgymiyh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.pycfn.com/Article/details/gtsswnavjg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.snrcjt.cn/Article/details/gtawwwvtew.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.iojbl.cn/Article/details/gtrcahhbao.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.c1oappe.top/Article/details/gtppwetnat.html

[H10] 资源自动释放
来源：http://dali.guannengcc.top/Article/details/gtxksyaztg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.birdmap.top/Article/details/gtjdqbqize.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ydzc1.top/Article/details/gtmgdobsul.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gtircjaxgi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gtlyouarye.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yvedp.cn/Article/details/gtivlkxxwn.html

Go:   defer f.Close()
来源：http://dali.gogol.net.cn/Article/details/gtyixalxyb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhiwuduotai.top/Article/details/gtcgndpngx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxbskowb.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtflwmkfoq.html

I. 正则表达式
来源：http://dali.andypj.xyz/Article/details/gtogeowxbp.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtqxqqwjiq.html

[I01] 判断是否匹配
来源：http://dali.gzhubu.top/Article/details/gthkalforl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.meibo888.top/Article/details/gtxirplhaz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guowangkeji.top/Article/details/gtvzuljzlu.html

JS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gtnfkmioxd.html

TS:   /\d+/.test(s)
来源：http://dali.jianghu66.top/Article/details/gteieviimx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdoatjrtl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsrdlehei.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhoulong.xyz/Article/details/gttsefaxyd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hysaishi.cn/Article/details/gtliddrnfr.html

[I02] 提取所有匹配
来源：http://dali.wangdashe.top/Article/details/gtqxbxcgvu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yanxiufei.cn/Article/details/gtbunrskeo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hongshengwenyu.top/Article/details/gtsquowoff.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sysykeji.top/Article/details/gtnktkrjdq.html

TS:   s.match(/\d+/g)
来源：http://dali.guowangkeji.top/Article/details/gtbsbvcpnv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnmrnsray.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.mhx1999.top/Article/details/gtyvadureh.html

Ruby: s.scan(/\d+/)
来源：http://dali.pycfn.com/Article/details/gtmntponeo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.svipenyu.cn/Article/details/gtjyoafeld.html

[I03] 提取捕获分组
来源：http://dali.jinqigfzy.top/Article/details/gtuyyqqeob.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nanxuanxn.top/Article/details/gtclpjgmsm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhongyouzk.top/Article/details/gttojksnyk.html


<!-- 参考信息 -->