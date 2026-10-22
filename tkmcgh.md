代发 wailian999

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dashuyun.cn/Article/details/gtbhnukofo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gttrzlnpvd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtrnmugosw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ppjwa.cn/Article/details/gtmzpmdkce.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.guowangkeji.top/Article/details/gtxqtopzpj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gthodoadnr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.316326.xyz/Article/details/gteryryavh.html

[F12] CSV 读写
来源：http://dali.cucudq.cn/Article/details/gtqtlpfvkq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hysaishi.cn/Article/details/gtcketpiql.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.birdmap.top/Article/details/gtqlumxuzm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jiagoushi.top/Article/details/gttonzrkyn.html

TS:   // 同上
来源：http://dali.hongshengwenyu.top/Article/details/gtqkkkxlmk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.pengpengdd.cyou/Article/details/gtzoxfelwa.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yueranfly.top/Article/details/gtojamakhp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.0kj1m.cn/Article/details/gtkmsedqcj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.guowangkeji.top/Article/details/gtbbxbtskd.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtiqtbtfuk.html

G. 面向对象
来源：http://dali.guowangkeji.top/Article/details/gtxmthfmil.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtobneswnz.html

[G01] 定义类
来源：http://dali.sufxvd.cn/Article/details/gtoxubnwmf.html

Py:   class User: pass
来源：http://dali.meibo888.top/Article/details/gtjfaqyzjk.html

PHP:  class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtujkhnnmz.html

JS:   class User {}
来源：http://dali.ppjwa.cn/Article/details/gtumcckoxl.html

TS:   class User { name: string = ""; }
来源：http://dali.meibo888.top/Article/details/gttpsxcaid.html

Java: class User {}
来源：http://dali.gaohongyu789.top/Article/details/gthbybipyp.html

Go:   type User struct { Name string }
来源：http://dali.hnqzz.top/Article/details/gtakazpesx.html

Ruby: class User; end
来源：http://dali.hysaishi.cn/Article/details/gtijyjdrif.html

C#:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gtptgodybc.html

[G02] 构造函数
来源：http://dali.cheryme.top/Article/details/gtjgdhbayq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cashguo.top/Article/details/gtknqkhzst.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ppjwa.cn/Article/details/gtmdfwxywd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shzxlz.cn/Article/details/gtocpvmacq.html

TS:   constructor(public name: string) {}
来源：http://dali.sysykeji.top/Article/details/gtiyixjowk.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj20258888.top/Article/details/gtybwczwzq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aibaodan.cn/Article/details/gtxxjfjozw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jqgufenzy.top/Article/details/gtruxcbuih.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258888.top/Article/details/gttogoxgzk.html

[G03] 实例属性
来源：http://dali.nwbrower.top/Article/details/gtnghgkjjy.html

Py:   self.name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gtmyrceqeu.html

PHP:  public string $name = "x";
来源：http://dali.yj202588.top/Article/details/gtvidrbhtv.html

JS:   this.name = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtlhtratbn.html

TS:   name: string = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtyaaibkuh.html

Java: private String name;
来源：http://dali.andypj.xyz/Article/details/gtlhsavgla.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgrtxnket.html

Ruby: @name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gtefxxrrmc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sxryk.cn/Article/details/gtbbpzgqzk.html

[G04] 定义方法
来源：http://dali.jqgufenzy.top/Article/details/gtxbeimpje.html

Py:   def greet(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gtllkquphq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gtkldognrh.html

JS:   greet() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gthdthivjh.html

TS:   greet(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtzyhpysxr.html

Java: String greet() { return name; }
来源：http://dali.xziqi.cn/Article/details/gtooplvmmo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtfprdbojr.html

Ruby: def greet; @name; end
来源：http://dali.pengpengdd.cyou/Article/details/gtwyoxgzmh.html

C#:   public string Greet() => Name;
来源：http://dali.hysaishi.cn/Article/details/gtzbfmaoco.html

[G05] 继承
来源：http://dali.wangshuangyany.cn/Article/details/gtvxfqijes.html

Py:   class Admin(User): pass
来源：http://dali.ehwqpu.com/Article/details/gtonwunwle.html

PHP:  class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtkzksgtmi.html

JS:   class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtojvkqitu.html

TS:   class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtscmvblnu.html

Java: class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtmnyxnyxm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hammf.cn/Article/details/gtxbkuhanp.html

Ruby: class Admin < User; end
来源：http://dali.aibaodan.cn/Article/details/gtgxztvmjv.html

C#:   class Admin : User {}
来源：http://dali.hfpthk.cn/Article/details/gtcotgzoik.html

[G06] 重写方法
来源：http://dali.xuetiantiany.cn/Article/details/gtltcqieea.html

Py:   def greet(self): return "admin"
来源：http://dali.snrcjt.cn/Article/details/gtkyavgnnd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtuhznbfac.html

JS:   greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtqjdgtsky.html

TS:   greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtntkvvoxv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtveeudigk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.birdmap.top/Article/details/gtmwwktgpo.html

Ruby: def greet; "admin"; end
来源：http://dali.zhengqikj.top/Article/details/gtiyaodrcm.html

C#:   public override string Greet() => "admin";
来源：http://dali.sufxvd.cn/Article/details/gtgojffmwj.html

[G07] 调用父类方法
来源：http://dali.guannengcc.top/Article/details/gtkikgtugy.html

Py:   super().greet()
来源：http://dali.bjfxy.top/Article/details/gtdvejwxbt.html

PHP:  parent::greet();
来源：http://dali.c1oappe.top/Article/details/gtbtljbydv.html

JS:   super.greet();
来源：http://dali.cheryme.top/Article/details/gtbyrgxbih.html

TS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gtqottwohg.html

Java: super.greet();
来源：http://dali.gogol.net.cn/Article/details/gtgnxvgsll.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nanxuanxn.top/Article/details/gtrzwnchho.html

Ruby: super
来源：http://dali.ppjwa.cn/Article/details/gtfzlpxcym.html

C#:   base.Greet();
来源：http://dali.mhx1999.top/Article/details/gteoymaivc.html

[G08] 静态方法与属性
来源：http://dali.aibaodan.cn/Article/details/gtdhbqkoyo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.fengsongda.top/Article/details/gtxdjttcue.html

PHP:  public static function f() {}
来源：http://dali.yonumen.top/Article/details/gtdjsyjxxo.html

JS:   static f() {}
来源：http://dali.yonumen.top/Article/details/gtjngkfvgb.html

TS:   static f(): void {}
来源：http://dali.cucudq.cn/Article/details/gtkvvnrtcx.html

Java: static void f() {}
来源：http://dali.daria6918.cn/Article/details/gthzjtnucx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yangfankeji.com/Article/details/gtgcoiukks.html

Ruby: def self.f; end
来源：http://dali.9152youxi.cn/Article/details/gtnlpbvjbw.html

C#:   public static void F() {}
来源：http://dali.ehwqpu.com/Article/details/gtwjlfgzti.html

[G09] 接口 / 抽象类
来源：http://dali.hfpthk.cn/Article/details/gtaqiunzmr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.mhx1999.top/Article/details/gtrmhpxdct.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.pycfn.com/Article/details/gtgfxxjtvl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.kuanghao11.cn/Article/details/gtugaoudmb.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gtssixixxv.html

Java: interface Shape { double area(); }
来源：http://dali.tanke756.top/Article/details/gteecuqztf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hnxiangtu.top/Article/details/gtsjlvlgxw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuanzx.com/Article/details/gtzsboaxov.html

C#:   interface IShape { double Area(); }
来源：http://dali.xylfe.cn/Article/details/gttlyrwzrv.html

[G10] 访问控制
来源：http://dali.daria6918.cn/Article/details/gtqmihmmqe.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenjidiqi.icu/Article/details/gtktmieaam.html

PHP:  public / protected / private
来源：http://dali.yj202588.top/Article/details/gtfpyezqko.html

JS:   #private 字段；其余公开
来源：http://dali.shzxlz.cn/Article/details/gtufddtuhh.html

TS:   public / protected / private
来源：http://dali.xylfe.cn/Article/details/gtsxsufquf.html

Java: public / protected / private / 默认包级
来源：http://dali.zhongyouzk.top/Article/details/gttruguvtx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shangyingyoupin.top/Article/details/gtkhaihbpo.html

Ruby: public / protected / private
来源：http://dali.yj20258.top/Article/details/gtkvvcbcwu.html

C#:   public / protected / private / internal
来源：http://dali.chenjidiqi.icu/Article/details/gttuycuiwe.html

[G11] getter / setter
来源：http://dali.redwolf501.top/Article/details/gtgvmnkdsn.html

Py:   @property 与 @x.setter
来源：http://dali.shzxlz.cn/Article/details/gtwizagtub.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gtojlkrgkw.html

JS:   get name() { return this._name; }
来源：http://dali.bjfxy.top/Article/details/gtblnxmzff.html

TS:   get name(): string { return this._name; }
来源：http://dali.ivvv.top/Article/details/gttrvyslku.html

Java: public String getName() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gttqgqzeoc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtmlrbinkh.html

Ruby: attr_accessor :name
来源：http://dali.chenlongwang.top/Article/details/gtiidmtwst.html

C#:   public string Name { get; set; }
来源：http://dali.aibaodan.cn/Article/details/gtfdioqbhx.html

[G12] 对象转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtvqcrjykq.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258.top/Article/details/gtwesipxse.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtfibfnafe.html

JS:   toString() { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtpbawjgus.html

TS:   toString(): string { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtfdgxfxrn.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtixxfrcfe.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gtpohfxgyw.html

Ruby: def to_s; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gtqiypermi.html

C#:   public override string ToString() => Name;
来源：http://dali.hnxiangtu.top/Article/details/gtxqxfwkyp.html

[G13] 判断对象类型
来源：http://dali.c1oappe.top/Article/details/gthwjtyyie.html

Py:   isinstance(u, User)
来源：http://dali.bjfxy.top/Article/details/gtjlrcrlvm.html

PHP:  $u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtodppahzt.html

JS:   u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtkzbaldoq.html

TS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtchlgdfsx.html

Java: u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gtoegboehv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aibaodan.cn/Article/details/gtzabodfvt.html

Ruby: u.is_a?(User)
来源：http://dali.ybcxt.top/Article/details/gtldiirntr.html

C#:   u is User
来源：http://dali.hysaishi.cn/Article/details/gtozoufldq.html

[G14] 数据类 / record
来源：http://dali.yvedp.cn/Article/details/gtrxovwnrf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gzhubu.top/Article/details/gtbmvbwxot.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwodrlja.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.smart0.xyz/Article/details/gtrgsjmaxg.html

TS:   type User = { name: string; age: number };
来源：http://dali.daria6918.cn/Article/details/gtzhptryrk.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtvbixuefl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hfpthk.cn/Article/details/gtraxgixwo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.daria6918.cn/Article/details/gtrxeyfzje.html

C#:   record User(string Name, int Age);
来源：http://dali.tian-w.cn/Article/details/gtkqfybvwo.html

[G15] 枚举
来源：http://dali.dashuyun.cn/Article/details/gtpxngonxv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgfzy.top/Article/details/gttmbctfpx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.wangdashe.top/Article/details/gtktkhrfhv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjqaxtbiv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gtetgakqhu.html

Java: enum Color { RED, GREEN }
来源：http://dali.ydzc1.top/Article/details/gtgrhkjqds.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yueranfly.top/Article/details/gtogcawhjt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinyuanbaomall.cn/Article/details/gttqmlvtua.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj202588.top/Article/details/gtntcrftbs.html

[G16] 对象转数组 / 字典
来源：http://dali.zhongyouzk.top/Article/details/gtlalvobvc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.quarkkingdee.top/Article/details/gtmcueenni.html

PHP:  get_object_vars($obj);
来源：http://dali.cheryme.top/Article/details/gtyuquhwdi.html

JS:   Object.entries(obj)
来源：http://dali.cdnleiting.top/Article/details/gtaemtfloy.html

TS:   Object.entries(obj)
来源：http://dali.sweek.top/Article/details/gtbllkxspm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.guowangkeji.top/Article/details/gtpmusnbuv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cheryme.top/Article/details/gtxcrweote.html

Ruby: obj.instance_variables
来源：http://dali.gzhubu.top/Article/details/gtcurxvvuw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhoulong.xyz/Article/details/gtzbycqwzz.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtvqueavks.html

H. 异常与错误处理
来源：http://dali.hammf.cn/Article/details/gtkrlmvgbi.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtyvxovpjl.html

[H01] try / catch 基础
来源：http://dali.jqgfzy.top/Article/details/gttfbisymw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.iojbl.cn/Article/details/gtlcejzgms.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sysykeji.top/Article/details/gtninhezct.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gtdlcchpev.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gtsyzepjah.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jyoumei.cn/Article/details/gtnznmvjxj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jqgfzy.top/Article/details/gtkzuuxpky.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.quarkkingdee.top/Article/details/gttsnuokup.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xylfe.cn/Article/details/gtnucsyecq.html

[H02] finally / ensure 收尾
来源：http://dali.andypj.xyz/Article/details/gtbuujtbrh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangshuangyany.cn/Article/details/gtcsjedxza.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtozlcuqgw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtnzuvjrxy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtfslbomzy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtbeqvdedz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.guowangkeji.top/Article/details/gtykdntscs.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xinyue.icu/Article/details/gtglcxhwji.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gthwbmjrky.html

[H03] 主动抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gtdnorlctk.html

Py:   raise ValueError("错误信息")
来源：http://dali.jianghu66.top/Article/details/gtruzpqjnq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtuygsqinf.html

JS:   throw new Error("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtqivbezxw.html

TS:   throw new Error("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtmttivlgx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gtxhkwingb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sxryk.cn/Article/details/gtiywojsmi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.mhx1999.top/Article/details/gtpzoqhwli.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gtkqfraxnt.html

[H04] 自定义异常类型
来源：http://dali.haohaochexian.top/Article/details/gtdtpubcoj.html

Py:   class MyError(Exception): pass
来源：http://dali.hongshengwenyu.top/Article/details/gtsmmgydnk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.9152youxi.cn/Article/details/gtpvdhvwtt.html

JS:   class MyError extends Error {}
来源：http://dali.ehwqpu.com/Article/details/gtgptbuwjo.html

TS:   class MyError extends Error {}
来源：http://dali.yanxiufei.cn/Article/details/gtxmpesnnr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gtrdwrtkwc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hnxiangtu.top/Article/details/gtkeqlppqk.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhixingplan.top/Article/details/gtzmckgrba.html

C#:   class MyException : Exception {}
来源：http://dali.chenjidiqi.icu/Article/details/gtjldcucnj.html

[H05] 捕获特定类型
来源：http://dali.hysaishi.cn/Article/details/gtcbgkkopf.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangkeji.top/Article/details/gtokgimncp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cheryme.top/Article/details/gtckivjcci.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtpcfrzcby.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sysykeji.top/Article/details/gtjpxkkzqv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jlsjyb.cn/Article/details/gtnjzllypn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.havefunace.top/Article/details/gtyzbaiddj.html

Ruby: rescue ArgumentError => e
来源：http://dali.gaohongyu789.top/Article/details/gtflfedjkw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cqqwz.cn/Article/details/gtowhsiltp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cucudq.cn/Article/details/gtfnunsnqh.html

Py:   value = d.get("k") or default
来源：http://dali.ydzc1.top/Article/details/gtizthcqfv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpegsnnb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gtdrufhbfx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gtsgeiwmcl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xinyue.icu/Article/details/gtcsthbycy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhengqikj.top/Article/details/gtrfztybvk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guannengcc.top/Article/details/gtqpqmweki.html

C#:   obj?.A?.B ?? default
来源：http://dali.yanxiufei.cn/Article/details/gtwxvxnjvr.html

[H07] 断言
来源：http://dali.gaohongyu789.top/Article/details/gtpghmzxrd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nanxuanxn.top/Article/details/gtksgzezas.html

PHP:  assert($x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtfvzhvard.html

JS:   console.assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gtxnsekkju.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtkixynbbw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhongyouzk.top/Article/details/gtvrerpnqr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhiwuduotai.top/Article/details/gtmrrdhayd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.smart0.xyz/Article/details/gthxqjzikr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtfmlojaxs.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhengqikj.top/Article/details/gthlfjhoyq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yangfankeji.com/Article/details/gtxwskffcj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gaohongyu789.top/Article/details/gtudjyefxf.html

JS:   e.message;  e.stack
来源：http://dali.havefunace.top/Article/details/gtmovglcwz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yanxiufei.cn/Article/details/gtagrgexuv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sxryk.cn/Article/details/gtmpkbhsbp.html

Go:   err.Error()
来源：http://dali.xuanzx.com/Article/details/gtrhfrujaq.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangshuangyany.cn/Article/details/gtruewxeon.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yueranfly.top/Article/details/gtslroguye.html

[H09] 带错误码的异常
来源：http://dali.shangyingyoupin.top/Article/details/gtjshxybox.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ivvv.top/Article/details/gtgmijldlo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dashuyun.cn/Article/details/gttkakbqfj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ydzc1.top/Article/details/gtlmakrjkm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.0kj1m.cn/Article/details/gtqizopsek.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xuetiantiany.cn/Article/details/gtlmltfzyj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.wangshuangyany.cn/Article/details/gtsuyancqj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xuanzx.com/Article/details/gtngjcieyd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yonumen.top/Article/details/gtytovogky.html

[H10] 资源自动释放
来源：http://dali.yonumen.top/Article/details/gtuhnncxfj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258888.top/Article/details/gtcfgmfwlz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gtnogyncet.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.smart0.xyz/Article/details/gtridkpymf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cdnleiting.top/Article/details/gtafstrbck.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xinyue.icu/Article/details/gtgdgvonhv.html

Go:   defer f.Close()
来源：http://dali.zdqjudy.top/Article/details/gticpyuovb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hfpthk.cn/Article/details/gtfydzyoik.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtxjqcjcgd.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtlmrpekzo.html

I. 正则表达式
来源：http://dali.yj20258888.top/Article/details/gtsowwqlgj.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtligdfyhp.html

[I01] 判断是否匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtklrcnpiy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.redwolf501.top/Article/details/gtcskcxukh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuanzhike.top/Article/details/gtxcdgqifa.html

JS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gthhtdnmrs.html

TS:   /\d+/.test(s)
来源：http://dali.tian-w.cn/Article/details/gtrcebdbnn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.bjfxy.top/Article/details/gtcukgrfhj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenzaomai.com/Article/details/gtpnexnuao.html

Ruby: s.match?(/\d+/)
来源：http://dali.gzhubu.top/Article/details/gtnivcxyxp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnxiangtu.top/Article/details/gtshqtvtdp.html

[I02] 提取所有匹配
来源：http://dali.jinqigufen.top/Article/details/gtxklkvijt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gtgpuzrrug.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhixingplan.top/Article/details/gtsyulrvjb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.andypj.xyz/Article/details/gtaymxinan.html

TS:   s.match(/\d+/g)
来源：http://dali.tian-w.cn/Article/details/gtvwpkiqfv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj202588.top/Article/details/gtyeobbqaz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj20258888.top/Article/details/gtjxsmxpzy.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gtaunyjefc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.iojbl.cn/Article/details/gthttkbdpa.html

[I03] 提取捕获分组
来源：http://dali.jianghu66.top/Article/details/gtrjxwjfub.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gotoacloud.top/Article/details/gtnpyqpefq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yangfankeji.com/Article/details/gtpysgwztl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hywenlv.cn/Article/details/gtflaxiewg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.aizwys.cn/Article/details/gtdfmbokwz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.quarkkingdee.top/Article/details/gtbsxybkaz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cucudq.cn/Article/details/gtkgvhcies.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yuanzhike.top/Article/details/gtbquwadpb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cheryme.top/Article/details/gtfynctpxj.html

[I04] 正则替换
来源：http://dali.cashguo.top/Article/details/gtiryekcgp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtxrsqpwdr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtdymiaevd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gzhubu.top/Article/details/gtigizeokc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gtrrksvteb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj202588.top/Article/details/gtlgwjyrlb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenzaomai.com/Article/details/gtedqygcnv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtjvluvphj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.meibo888.top/Article/details/gtpduetipl.html

[I05] 按正则拆分
来源：http://dali.smart0.xyz/Article/details/gttztzzxcq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhoulong.xyz/Article/details/gtnqupzyae.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.guannengcc.top/Article/details/gtwqbkqyil.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gtxtahyrwq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gthumijygw.html


<!-- 参考信息 -->