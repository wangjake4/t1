代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yuanzhike.top/Article/details/gtwnmnbjau.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtvhstibid.html

Ruby: Dir.children("dir")
来源：http://dali.ehwqpu.com/Article/details/gtpyreiczt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtdpxowquo.html

[F09] 获取文件大小
来源：http://dali.pengpengdd.cyou/Article/details/gtpluehaee.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtfbjzpsbq.html

PHP:  filesize("a.txt");
来源：http://dali.ydzc1.top/Article/details/gthiwwzknp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gturkzxjuk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwxrcefok.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gttvuvcjhj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dashuyun.cn/Article/details/gtjvodhjpk.html

Ruby: File.size("a.txt")
来源：http://dali.yongpay.top/Article/details/gtsnuvsctl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenjidiqi.icu/Article/details/gtbbxaemxv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.havefunace.top/Article/details/gtdlbqxdcz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtsizxkafv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gttunfbnne.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtyywsrcpn.html

TS:   path.extname("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtxdzurixv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ehwqpu.com/Article/details/gtiifayzdk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtcsrbmdgl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtmewjeqeo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtsegtbfpw.html

[F11] 复制与移动文件
来源：http://dali.fengsongda.top/Article/details/gthyapjtpu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtdiitnogp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjobneac.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtobveugyv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtxigxuuie.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tianlin.xyz/Article/details/gtnrmrjsfk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shuidangran.top/Article/details/gtpwmtxpbd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtdwqwczbl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.aizwys.cn/Article/details/gtzbvfrkwa.html

[F12] CSV 读写
来源：http://dali.sufxvd.cn/Article/details/gtovlnqbgh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.dashuyun.cn/Article/details/gtdqfbvbbg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj20258888.top/Article/details/gtgfpaajbz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gtbxrmrxoa.html

TS:   // 同上
来源：http://dali.kuanghao11.cn/Article/details/gtpkyiyskz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmtotekz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gttsllcdkx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tanke756.top/Article/details/gtvvregyvm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xylfe.cn/Article/details/gtokvprdfg.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtbifxixuz.html

G. 面向对象
来源：http://dali.gzhubu.top/Article/details/gtodiqjznt.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gttrpkuxap.html

[G01] 定义类
来源：http://dali.aizwys.cn/Article/details/gtgkfmukmp.html

Py:   class User: pass
来源：http://dali.yuxming.cn/Article/details/gtqdvwtiqf.html

PHP:  class User {}
来源：http://dali.xylfe.cn/Article/details/gtfpkkdrcw.html

JS:   class User {}
来源：http://dali.cheryme.top/Article/details/gtsqpyaibz.html

TS:   class User { name: string = ""; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrornhrwm.html

Java: class User {}
来源：http://dali.jiagoushi.top/Article/details/gtpervhebf.html

Go:   type User struct { Name string }
来源：http://dali.zdqjudy.top/Article/details/gtqbpcfrlo.html

Ruby: class User; end
来源：http://dali.jlsjyb.cn/Article/details/gtfvvjpqmn.html

C#:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtxiofcoid.html

[G02] 构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtlvlwnlth.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.redwolf501.top/Article/details/gtzgkrluec.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgufenzy.top/Article/details/gtacsgjsqy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shuidangran.top/Article/details/gtjqdlpmzk.html

TS:   constructor(public name: string) {}
来源：http://dali.hammf.cn/Article/details/gtlyfmvhyq.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gtdmxtsclz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yangfankeji.com/Article/details/gtwululyjt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenjidiqi.icu/Article/details/gttzgvfmqi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmxdrzpvq.html

[G03] 实例属性
来源：http://dali.jianghu66.top/Article/details/gtkswlbuqz.html

Py:   self.name = "x"
来源：http://dali.birdmap.top/Article/details/gtuqjpayyf.html

PHP:  public string $name = "x";
来源：http://dali.zhixingplan.top/Article/details/gtrohbrgir.html

JS:   this.name = "x";
来源：http://dali.sufxvd.cn/Article/details/gtofqapdgk.html

TS:   name: string = "x";
来源：http://dali.gotoacloud.top/Article/details/gtqhywheqd.html

Java: private String name;
来源：http://dali.cqqwz.cn/Article/details/gtaalsnvyj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cqqwz.cn/Article/details/gtzgouqnvo.html

Ruby: @name = "x"
来源：http://dali.daxiang520.top/Article/details/gtlbfzuryk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtwzjntuma.html

[G04] 定义方法
来源：http://dali.zhiwuduotai.top/Article/details/gtulojlyiv.html

Py:   def greet(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gtzasnbfls.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbogqwlnm.html

JS:   greet() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtxgnzzxym.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqgydynnf.html

Java: String greet() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtgwjrdvih.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzyuuyxwv.html

Ruby: def greet; @name; end
来源：http://dali.havefunace.top/Article/details/gttjwfvnel.html

C#:   public string Greet() => Name;
来源：http://dali.nwbrower.top/Article/details/gtwzanmmlg.html

[G05] 继承
来源：http://dali.jinqigufen.top/Article/details/gtvnvngmqe.html

Py:   class Admin(User): pass
来源：http://dali.tianlin.xyz/Article/details/gtwrfpfqja.html

PHP:  class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtavdceflv.html

JS:   class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtggvhawop.html

TS:   class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gtmypudirf.html

Java: class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gteamdczpb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shuidangran.top/Article/details/gtwuszllgn.html

Ruby: class Admin < User; end
来源：http://dali.guannengcc.top/Article/details/gtpgfennfe.html

C#:   class Admin : User {}
来源：http://dali.gogol.net.cn/Article/details/gtvfjumnea.html

[G06] 重写方法
来源：http://dali.shuidangran.top/Article/details/gtdlnuaiaf.html

Py:   def greet(self): return "admin"
来源：http://dali.chenlongwang.top/Article/details/gttbibnfgb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gttmywradi.html

JS:   greet() { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gttiprdxiq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtrcybxrrp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gtqxrsvpgj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangdashe.top/Article/details/gtrmdveecs.html

Ruby: def greet; "admin"; end
来源：http://dali.meibo888.top/Article/details/gteccgtbir.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuanzx.com/Article/details/gtxuihuowf.html

[G07] 调用父类方法
来源：http://dali.jiagoushi.top/Article/details/gtydxvttzg.html

Py:   super().greet()
来源：http://dali.wangdashe.top/Article/details/gtgjkyysru.html

PHP:  parent::greet();
来源：http://dali.zhoulong.xyz/Article/details/gtxjbpfhbg.html

JS:   super.greet();
来源：http://dali.hfpthk.cn/Article/details/gtseqnwbcj.html

TS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gtfokpbpdd.html

Java: super.greet();
来源：http://dali.sysykeji.top/Article/details/gtwmzegfdg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ivvv.top/Article/details/gttoxeeizt.html

Ruby: super
来源：http://dali.guannengcc.top/Article/details/gtjvybdkgr.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gtgtmxhaab.html

[G08] 静态方法与属性
来源：http://dali.jinqigufen.top/Article/details/gtdmucferb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.andypj.xyz/Article/details/gtpoukzeuu.html

PHP:  public static function f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtnoomybdh.html

JS:   static f() {}
来源：http://dali.fzhhl.top/Article/details/gtevfoaoyn.html

TS:   static f(): void {}
来源：http://dali.redwolf501.top/Article/details/gtbnxwlhge.html

Java: static void f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtgjpjlzlx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shzxlz.cn/Article/details/gtivlvkewc.html

Ruby: def self.f; end
来源：http://dali.fzhhl.top/Article/details/gtllajmhjk.html

C#:   public static void F() {}
来源：http://dali.mhx1999.top/Article/details/gtluqskpah.html

[G09] 接口 / 抽象类
来源：http://dali.redwolf501.top/Article/details/gtulbnpkdw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yuxming.cn/Article/details/gtptwfgyge.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhoulong.xyz/Article/details/gtztrqzazi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.meibo888.top/Article/details/gtdgqmvgpe.html

TS:   interface Shape { area(): number; }
来源：http://dali.316326.xyz/Article/details/gtmcmacznt.html

Java: interface Shape { double area(); }
来源：http://dali.nanxinkj.top/Article/details/gtxvnrejco.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.redwolf501.top/Article/details/gthdgxqhqy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fzhhl.top/Article/details/gtoydjaevc.html

C#:   interface IShape { double Area(); }
来源：http://dali.guowangkeji.top/Article/details/gthaspkobn.html

[G10] 访问控制
来源：http://dali.ehwqpu.com/Article/details/gtknuwogpc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.aizwys.cn/Article/details/gtrjuozdbi.html

PHP:  public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gtltxfozpd.html

JS:   #private 字段；其余公开
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipwbjjfz.html

TS:   public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gtxkqniytg.html

Java: public / protected / private / 默认包级
来源：http://dali.ybcxt.top/Article/details/gtbeqsbegf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.birdmap.top/Article/details/gtjmtjnowh.html

Ruby: public / protected / private
来源：http://dali.aizwys.cn/Article/details/gtwbxlmhzf.html

C#:   public / protected / private / internal
来源：http://dali.birdmap.top/Article/details/gtjyrxowpv.html

[G11] getter / setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gtziqnrrws.html

Py:   @property 与 @x.setter
来源：http://dali.guowangkeji.top/Article/details/gtkvprdczh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gtlxsbifii.html

JS:   get name() { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gtrrgimhpx.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gtkamaaklj.html

Java: public String getName() { return name; }
来源：http://dali.xylfe.cn/Article/details/gtmciqmuox.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gtngdupdsf.html

Ruby: attr_accessor :name
来源：http://dali.zhoulong.xyz/Article/details/gtnvhzerha.html

C#:   public string Name { get; set; }
来源：http://dali.xuetiantiany.cn/Article/details/gtyritrbwm.html

[G12] 对象转字符串
来源：http://dali.cdnleiting.top/Article/details/gtzwqsrlqs.html

Py:   def __str__(self): return self.name
来源：http://dali.gaohongyu789.top/Article/details/gtidsmvknd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gtdaudmmpb.html

JS:   toString() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtggegglve.html

TS:   toString(): string { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtnrgrkuyt.html

Java: @Override public String toString() { return name; }
来源：http://dali.cheryme.top/Article/details/gtyaowsvmd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gtyhubuaei.html

Ruby: def to_s; @name; end
来源：http://dali.jiagoushi.top/Article/details/gtfkylxxyi.html

C#:   public override string ToString() => Name;
来源：http://dali.aibaodan.cn/Article/details/gtjizvyhvq.html

[G13] 判断对象类型
来源：http://dali.jqgfzy.top/Article/details/gtgaemxbqv.html

Py:   isinstance(u, User)
来源：http://dali.hongshengwenyu.top/Article/details/gtzmlksini.html

PHP:  $u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtqlngdxno.html

JS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyaanyotu.html

TS:   u instanceof User
来源：http://dali.pycfn.com/Article/details/gtvjkuwslm.html

Java: u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtqvexsjte.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuetiantiany.cn/Article/details/gtbplpzhsk.html

Ruby: u.is_a?(User)
来源：http://dali.nanxuanxn.top/Article/details/gthhoysiwt.html

C#:   u is User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvvnfwrz.html

[G14] 数据类 / record
来源：http://dali.ybcxt.top/Article/details/gtihcwujsu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gaohongyu789.top/Article/details/gtpklnvrpf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hywenlv.cn/Article/details/gtpdgmipgv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yueranfly.top/Article/details/gtovaornsj.html

TS:   type User = { name: string; age: number };
来源：http://dali.hfpthk.cn/Article/details/gtgcbihhzz.html

Java: record User(String name, int age) {}
来源：http://dali.hysaishi.cn/Article/details/gtupwmecxq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xinyue.icu/Article/details/gthbdzlcrn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xuetiantiany.cn/Article/details/gtfuljjrpc.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gtckuvavnn.html

[G15] 枚举
来源：http://dali.jqgufenzy.top/Article/details/gtxmgbukgd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuetiantiany.cn/Article/details/gtzwrnjkfw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shuidangran.top/Article/details/gtaiorbqpc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.mhx1999.top/Article/details/gtsgmdiaza.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtcjihgses.html

Java: enum Color { RED, GREEN }
来源：http://dali.sufxvd.cn/Article/details/gtflxlxqbb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yvedp.cn/Article/details/gtvsyhpfpx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zycfv.cn/Article/details/gtwwevysvu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gtfknxwvob.html

[G16] 对象转数组 / 字典
来源：http://dali.zycfv.cn/Article/details/gtxhaacgrq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jlsjyb.cn/Article/details/gtkqwafnqd.html

PHP:  get_object_vars($obj);
来源：http://dali.chenlongwang.top/Article/details/gtfhtmkxnd.html

JS:   Object.entries(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtwwgemtmh.html

TS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gtglxfjvcg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.feifeiyinyue.top/Article/details/gtnqmwxpfl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ivvv.top/Article/details/gtgpkfduyv.html

Ruby: obj.instance_variables
来源：http://dali.hfpthk.cn/Article/details/gtdtiqltii.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cdnleiting.top/Article/details/gtxqoawpbc.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjcldpuz.html

H. 异常与错误处理
来源：http://dali.shangyingyoupin.top/Article/details/gtkrkkxisr.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtopuexoec.html

[H01] try / catch 基础
来源：http://dali.sufxvd.cn/Article/details/gtieugqvnp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xuetiantiany.cn/Article/details/gtzioiucre.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sysykeji.top/Article/details/gtjrgaxout.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenjidiqi.icu/Article/details/gtduefyryj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gtuzmvtkjy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xylfe.cn/Article/details/gtgvlhtorc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gtsxtqssih.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtyspwgtjd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gzhubu.top/Article/details/gteprztlxb.html

[H02] finally / ensure 收尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfhgcpbi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenjidiqi.icu/Article/details/gtjjyzuizl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtpjyowkxr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbigejkty.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gtvbnrwcmp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtnbdenkgy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hongshengwenyu.top/Article/details/gtbnvpquiy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hywenlv.cn/Article/details/gthtbcicej.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtfzgegdgy.html

[H03] 主动抛出异常
来源：http://dali.smart0.xyz/Article/details/gthjqpbdba.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhengqikj.top/Article/details/gtbktgoskj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtpfkqsdll.html

JS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtkrlrhbvz.html

TS:   throw new Error("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtmrindwai.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gttrjauzwc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.mhx1999.top/Article/details/gtduflyhqq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.feifeiyinyue.top/Article/details/gtpprzbmdb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtxwasebel.html

[H04] 自定义异常类型
来源：http://dali.haohaochexian.top/Article/details/gtxurfzrhv.html

Py:   class MyError(Exception): pass
来源：http://dali.yuxming.cn/Article/details/gtohnrfwgv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gttgmeaedy.html

JS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gtdzdapilr.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggpmesnk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xylfe.cn/Article/details/gtbajroufx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yangfankeji.com/Article/details/gtymmpnoal.html

Ruby: class MyError < StandardError; end
来源：http://dali.bjfxy.top/Article/details/gtezhuftur.html

C#:   class MyException : Exception {}
来源：http://dali.birdmap.top/Article/details/gtfksknote.html

[H05] 捕获特定类型
来源：http://dali.yj202588.top/Article/details/gtwwkbteds.html

Py:   except ValueError as e:
来源：http://dali.cdnleiting.top/Article/details/gtiiwwmuhe.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jqgufenzy.top/Article/details/gtcvprhxik.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cqqwz.cn/Article/details/gtzpcylbqo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.iojbl.cn/Article/details/gtbjsfezeh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cdnleiting.top/Article/details/gthcrchqwj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hammf.cn/Article/details/gtkgupeiwu.html

Ruby: rescue ArgumentError => e
来源：http://dali.jlsjyb.cn/Article/details/gtocsagwne.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtfafzmkza.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgrzydtss.html

Py:   value = d.get("k") or default
来源：http://dali.316326.xyz/Article/details/gtzmdznsyz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gtyikrulmg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.9152youxi.cn/Article/details/gtyikalqmb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gtnrgqtqax.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ppjwa.cn/Article/details/gtinpwqmdi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.9152youxi.cn/Article/details/gtecmdodyp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zycfv.cn/Article/details/gthazjprsh.html

C#:   obj?.A?.B ?? default
来源：http://dali.aibaodan.cn/Article/details/gtxhfxsmkv.html

[H07] 断言
来源：http://dali.jinqigufen.top/Article/details/gttocuvfya.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhoulong.xyz/Article/details/gtsxzsuxjq.html

PHP:  assert($x > 0);
来源：http://dali.jianghu66.top/Article/details/gtjbwganhn.html

JS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtdmofqudf.html

TS:   console.assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gtpghufmly.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ybcxt.top/Article/details/gtsytcrvzw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gogol.net.cn/Article/details/gtakdywpji.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinyuanbaomall.cn/Article/details/gtssbmumyx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gtgxoaqfus.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangshuangyany.cn/Article/details/gtvugsvaah.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hammf.cn/Article/details/gtksdmgkiv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtubexfbji.html

JS:   e.message;  e.stack
来源：http://dali.zhixingplan.top/Article/details/gtvhoqciyy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhoulong.xyz/Article/details/gtlchpflaf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gaohongyu789.top/Article/details/gtmrffvcci.html

Go:   err.Error()
来源：http://dali.quarkkingdee.top/Article/details/gtbfudxbhr.html

Ruby: e.message;  e.backtrace
来源：http://dali.yueranfly.top/Article/details/gtlnvccafn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cqqwz.cn/Article/details/gtslwsewew.html

[H09] 带错误码的异常
来源：http://dali.wangdashe.top/Article/details/gtepwtdypo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tian-w.cn/Article/details/gtqbqvbydy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yonumen.top/Article/details/gtrvbtfkfl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sxryk.cn/Article/details/gteokbzawr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sxryk.cn/Article/details/gtgznjtobt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yangfankeji.com/Article/details/gtpgikbomw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlljkdnyt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ehwqpu.com/Article/details/gtyybjonqw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hnqzz.top/Article/details/gtobwfzmdz.html

[H10] 资源自动释放
来源：http://dali.316326.xyz/Article/details/gtxziayhur.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yueranfly.top/Article/details/gttkskiprr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zdqjudy.top/Article/details/gtxuhwqqxe.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yueranfly.top/Article/details/gtmtwohikm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gtxqgdamgu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvpifpxn.html

Go:   defer f.Close()
来源：http://dali.nwbrower.top/Article/details/gtabsdlkhl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xuanzx.com/Article/details/gtjmhridrm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtxpgpnwhc.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtnbhwlfbd.html

I. 正则表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthpyvvjf.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtcdolgavu.html

[I01] 判断是否匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gttotfjloh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yanxiufei.cn/Article/details/gtogbsltxy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.c1oappe.top/Article/details/gtgyknolky.html

JS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gtbovbdauh.html

TS:   /\d+/.test(s)
来源：http://dali.ppjwa.cn/Article/details/gtzpkdpkik.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.dianchejie.cn/Article/details/gtefvwhgwk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jiagoushi.top/Article/details/gtjqlogjwl.html

Ruby: s.match?(/\d+/)
来源：http://dali.sysykeji.top/Article/details/gtmtzxsbhx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgufenzy.top/Article/details/gtizsehhal.html

[I02] 提取所有匹配
来源：http://dali.yvedp.cn/Article/details/gthptobxob.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zdqjudy.top/Article/details/gtnqeaibcq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ivvv.top/Article/details/gtoobamhbo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sweek.top/Article/details/gtwweknnja.html

TS:   s.match(/\d+/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpuzkguoq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shuidangran.top/Article/details/gtzgmfaviw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxjedbfqw.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhongyouzk.top/Article/details/gtecutzova.html


<!-- 参考信息 -->