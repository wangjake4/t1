代发 wailian999

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ivvv.top/Article/details/gtxdufsvhf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gteotrtwph.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.aibaodan.cn/Article/details/gtkchrcgpc.html

[F12] CSV 读写
来源：http://dali.aizwys.cn/Article/details/gtpnqclmqg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cdnleiting.top/Article/details/gtertlmksr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.c1oappe.top/Article/details/gtuhgffvbs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.smart0.xyz/Article/details/gtxvbznzap.html

TS:   // 同上
来源：http://dali.hongshengwenyu.top/Article/details/gthntpnomf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuetiantiany.cn/Article/details/gtbjwoazdz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.feifeiyinyue.top/Article/details/gtztvxayay.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yvedp.cn/Article/details/gtlxpatrdn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zycfv.cn/Article/details/gthnibzdab.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtofptmwem.html

G. 面向对象
来源：http://dali.hnxiangtu.top/Article/details/gtqysgelpj.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtbsizzqsc.html

[G01] 定义类
来源：http://dali.zhengqikj.top/Article/details/gtyiajywwg.html

Py:   class User: pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzutsgbbx.html

PHP:  class User {}
来源：http://dali.jqgfzy.top/Article/details/gtcxjwtzyy.html

JS:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gttrxnpwyx.html

TS:   class User { name: string = ""; }
来源：http://dali.0kj1m.cn/Article/details/gtweqwimwl.html

Java: class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtumreerwh.html

Go:   type User struct { Name string }
来源：http://dali.nanxuanxn.top/Article/details/gtupqonmlg.html

Ruby: class User; end
来源：http://dali.jqgfzy.top/Article/details/gtdcwwhktz.html

C#:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gtnszxcvng.html

[G02] 构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gtmqmqjfap.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yuxming.cn/Article/details/gtokszntja.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbjbrquqr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yongpay.top/Article/details/gtyvchsolt.html

TS:   constructor(public name: string) {}
来源：http://dali.guannengcc.top/Article/details/gttkudcmrt.html

Java: User(String name) { this.name = name; }
来源：http://dali.yueranfly.top/Article/details/gtnqnhhlvm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.0kj1m.cn/Article/details/gtyguxcibi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258888.top/Article/details/gthambgfei.html

C#:   public User(string name) { Name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtoxtsqfep.html

[G03] 实例属性
来源：http://dali.gotoacloud.top/Article/details/gtrbowmwao.html

Py:   self.name = "x"
来源：http://dali.yj202588.top/Article/details/gtirydtzus.html

PHP:  public string $name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtvnnzotcj.html

JS:   this.name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtglbjsaoy.html

TS:   name: string = "x";
来源：http://dali.quarkkingdee.top/Article/details/gtrxhnyyif.html

Java: private String name;
来源：http://dali.xylfe.cn/Article/details/gtkybmnzhp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.meibo888.top/Article/details/gtaytqzrck.html

Ruby: @name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gtmhmknfav.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gotoacloud.top/Article/details/gtvsriulcz.html

[G04] 定义方法
来源：http://dali.guowangkeji.top/Article/details/gtzpkwqjnm.html

Py:   def greet(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gtjpdvfezw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gtoclnbhdp.html

JS:   greet() { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gtyhmkcxzy.html

TS:   greet(): string { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtdzxcffxu.html

Java: String greet() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtpwlvzvou.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gttftfzscd.html

Ruby: def greet; @name; end
来源：http://dali.shuidangran.top/Article/details/gtwyohsiyb.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyiknlmdb.html

[G05] 继承
来源：http://dali.yanxiufei.cn/Article/details/gtmvxyxsxa.html

Py:   class Admin(User): pass
来源：http://dali.xuanzx.com/Article/details/gthgauvwii.html

PHP:  class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtuozwzblt.html

JS:   class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtnisqpokw.html

TS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtzvzjyjsa.html

Java: class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtbpdgbccb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yonumen.top/Article/details/gtdskmfgca.html

Ruby: class Admin < User; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukpzlzbh.html

C#:   class Admin : User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtjjbluyxf.html

[G06] 重写方法
来源：http://dali.iojbl.cn/Article/details/gtpilmkpky.html

Py:   def greet(self): return "admin"
来源：http://dali.zycfv.cn/Article/details/gtpzwummpg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtxuwjjugn.html

JS:   greet() { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtwjdvqszo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtmeuqabec.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtbljlsjnl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hnxiangtu.top/Article/details/gthbgirrmv.html

Ruby: def greet; "admin"; end
来源：http://dali.chenlongwang.top/Article/details/gtcveybwqm.html

C#:   public override string Greet() => "admin";
来源：http://dali.dashuyun.cn/Article/details/gtcdcbgbor.html

[G07] 调用父类方法
来源：http://dali.aibaodan.cn/Article/details/gttvvaghzc.html

Py:   super().greet()
来源：http://dali.yj20258.top/Article/details/gtisdpzmln.html

PHP:  parent::greet();
来源：http://dali.gotoacloud.top/Article/details/gtcxdwawas.html

JS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gtufupbitz.html

TS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gtbdrzjkgz.html

Java: super.greet();
来源：http://dali.sxryk.cn/Article/details/gtfhtzegwe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.316326.xyz/Article/details/gtwuiqteux.html

Ruby: super
来源：http://dali.cucudq.cn/Article/details/gtbukszipt.html

C#:   base.Greet();
来源：http://dali.tian-w.cn/Article/details/gtqejhthvx.html

[G08] 静态方法与属性
来源：http://dali.gogol.net.cn/Article/details/gtupgtcgul.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sysykeji.top/Article/details/gtcbqcvlxx.html

PHP:  public static function f() {}
来源：http://dali.haohaochexian.top/Article/details/gtlqjldpll.html

JS:   static f() {}
来源：http://dali.ivvv.top/Article/details/gtxhqondbv.html

TS:   static f(): void {}
来源：http://dali.nwbrower.top/Article/details/gteeqznptp.html

Java: static void f() {}
来源：http://dali.yanxiufei.cn/Article/details/gtebjxjvzt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.birdmap.top/Article/details/gtvxheahtf.html

Ruby: def self.f; end
来源：http://dali.jyoumei.cn/Article/details/gtyfdpaxnb.html

C#:   public static void F() {}
来源：http://dali.havefunace.top/Article/details/gtqzficloe.html

[G09] 接口 / 抽象类
来源：http://dali.ivvv.top/Article/details/gtrufkvaqj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ybcxt.top/Article/details/gtvfivbump.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ivvv.top/Article/details/gtgmpwwfcz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tianlin.xyz/Article/details/gtdmrffcon.html

TS:   interface Shape { area(): number; }
来源：http://dali.cashguo.top/Article/details/gtogtalgej.html

Java: interface Shape { double area(); }
来源：http://dali.sufxvd.cn/Article/details/gtxogrigyz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daria6918.cn/Article/details/gtyvjhcfns.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhiwuduotai.top/Article/details/gtzyyqnrvb.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangdashe.top/Article/details/gttsyrwlxw.html

[G10] 访问控制
来源：http://dali.fengsongda.top/Article/details/gtmzdfwzvj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yvedp.cn/Article/details/gthgzazjhf.html

PHP:  public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gtadmgiwej.html

JS:   #private 字段；其余公开
来源：http://dali.hfpthk.cn/Article/details/gtunlqngqm.html

TS:   public / protected / private
来源：http://dali.andypj.xyz/Article/details/gtujlsjgho.html

Java: public / protected / private / 默认包级
来源：http://dali.fengsongda.top/Article/details/gtsruvigpk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.daxiang520.top/Article/details/gthsyxqita.html

Ruby: public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtnbjdckrq.html

C#:   public / protected / private / internal
来源：http://dali.tanke756.top/Article/details/gtrzicjfyw.html

[G11] getter / setter
来源：http://dali.chenzaomai.com/Article/details/gtvnqvwggv.html

Py:   @property 与 @x.setter
来源：http://dali.zdqjudy.top/Article/details/gtzwlfnxqe.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gtywwsitro.html

JS:   get name() { return this._name; }
来源：http://dali.yonumen.top/Article/details/gthjqxjsal.html

TS:   get name(): string { return this._name; }
来源：http://dali.xziqi.cn/Article/details/gthqagsjbl.html

Java: public String getName() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtkgeookag.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtbbtezgcj.html

Ruby: attr_accessor :name
来源：http://dali.hongshengwenyu.top/Article/details/gtybjjokej.html

C#:   public string Name { get; set; }
来源：http://dali.aibaodan.cn/Article/details/gtxwidjuvw.html

[G12] 对象转字符串
来源：http://dali.zhixingplan.top/Article/details/gtznstmhme.html

Py:   def __str__(self): return self.name
来源：http://dali.chenlongwang.top/Article/details/gtvtpuxjbr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gtqfmvuqfb.html

JS:   toString() { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gtxdwkhfba.html

TS:   toString(): string { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtozwurjhl.html

Java: @Override public String toString() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gteczeezdz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtcetjllrc.html

Ruby: def to_s; @name; end
来源：http://dali.ppjwa.cn/Article/details/gtcgjdpbnm.html

C#:   public override string ToString() => Name;
来源：http://dali.nwbrower.top/Article/details/gtyfbzalaj.html

[G13] 判断对象类型
来源：http://dali.hnqzz.top/Article/details/gthvswanci.html

Py:   isinstance(u, User)
来源：http://dali.wangshuangyany.cn/Article/details/gtqurslsmj.html

PHP:  $u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gtnijyzqcs.html

JS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gttrqpnyfl.html

TS:   u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtkatcvqua.html

Java: u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzkaquuwl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tianlin.xyz/Article/details/gtgigtcquv.html

Ruby: u.is_a?(User)
来源：http://dali.havefunace.top/Article/details/gtmyhnzkpi.html

C#:   u is User
来源：http://dali.yuanzhike.top/Article/details/gtdhtmusog.html

[G14] 数据类 / record
来源：http://dali.meibo888.top/Article/details/gtrnwngyip.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.9152youxi.cn/Article/details/gtjhfnfinw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hongshengwenyu.top/Article/details/gtnbablbit.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.haohaochexian.top/Article/details/gtsncmvdih.html

TS:   type User = { name: string; age: number };
来源：http://dali.guannengcc.top/Article/details/gtubwcsyak.html

Java: record User(String name, int age) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtbdezeujr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dianchejie.cn/Article/details/gtgpgmcvzx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.havefunace.top/Article/details/gtdnytxeee.html

C#:   record User(string Name, int Age);
来源：http://dali.fzhhl.top/Article/details/gthvugkxqw.html

[G15] 枚举
来源：http://dali.kuanghao11.cn/Article/details/gtuxpirkup.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gotoacloud.top/Article/details/gtscgjjtfd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinqigufen.top/Article/details/gtpwonjfyg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdsavrwrz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gthktgyygb.html

Java: enum Color { RED, GREEN }
来源：http://dali.xziqi.cn/Article/details/gtcftkfgyd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuxming.cn/Article/details/gtmxwsbpgp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jianghu66.top/Article/details/gtrovmbclk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gtnrzvmfcx.html

[G16] 对象转数组 / 字典
来源：http://dali.sxryk.cn/Article/details/gtislkdock.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhoulong.xyz/Article/details/gtpkvdmggw.html

PHP:  get_object_vars($obj);
来源：http://dali.feifeiyinyue.top/Article/details/gtvouzzyzf.html

JS:   Object.entries(obj)
来源：http://dali.ydzc1.top/Article/details/gtkmlxgzib.html

TS:   Object.entries(obj)
来源：http://dali.ppjwa.cn/Article/details/gtjeaswzlx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.havefunace.top/Article/details/gtkycpyrxp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yueranfly.top/Article/details/gtfbyfmrun.html

Ruby: obj.instance_variables
来源：http://dali.snrcjt.cn/Article/details/gtqrzpagsz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.wangshuangyany.cn/Article/details/gtynkmythk.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtirzfnpxn.html

H. 异常与错误处理
来源：http://dali.zhiwuduotai.top/Article/details/gtttdjamvj.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtqzvpkqzh.html

[H01] try / catch 基础
来源：http://dali.haohaochexian.top/Article/details/gtlfjjmrlr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ybcxt.top/Article/details/gttsacaijx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gaohongyu789.top/Article/details/gtoorjvnce.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjovwsirb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gtjxmlpqet.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cheryme.top/Article/details/gtqidfszjv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangdashe.top/Article/details/gtczjceqva.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.daxiang520.top/Article/details/gtyzlqacwk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.kuanghao11.cn/Article/details/gtbpboncop.html

[H02] finally / ensure 收尾
来源：http://dali.shangyingyoupin.top/Article/details/gtlsdsbqwy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yonumen.top/Article/details/gthwhsflsb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gthorcxyyp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtfcpeljhj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtlgsduhvs.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtgsftgndm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yanxiufei.cn/Article/details/gtfxmvwewq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gotoacloud.top/Article/details/gtlhwibqgi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gttzvokzrn.html

[H03] 主动抛出异常
来源：http://dali.dashuyun.cn/Article/details/gthpbxmnyk.html

Py:   raise ValueError("错误信息")
来源：http://dali.sysykeji.top/Article/details/gtvpukqspo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtunrjzzfn.html

JS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtlhxukwnx.html

TS:   throw new Error("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtjisbrkpt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gttqtpaohe.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.pengpengdd.cyou/Article/details/gtswdhbskg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.wangdashe.top/Article/details/gtdqwiglil.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtqpyglipc.html

[H04] 自定义异常类型
来源：http://dali.yj202588.top/Article/details/gtimxhmcyc.html

Py:   class MyError(Exception): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gtqttxtstp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shuidangran.top/Article/details/gtwhbqunam.html

JS:   class MyError extends Error {}
来源：http://dali.yj20258.top/Article/details/gtvvaqfsef.html

TS:   class MyError extends Error {}
来源：http://dali.snrcjt.cn/Article/details/gtihhsgxyu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gtgwkyuyyh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj20258888.top/Article/details/gtmgaajlnh.html

Ruby: class MyError < StandardError; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwiuornlp.html

C#:   class MyException : Exception {}
来源：http://dali.chenlongwang.top/Article/details/gtuzlveolg.html

[H05] 捕获特定类型
来源：http://dali.316326.xyz/Article/details/gtxaspmjrz.html

Py:   except ValueError as e:
来源：http://dali.bjfxy.top/Article/details/gtnbumbcbo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.andypj.xyz/Article/details/gtjmkallow.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xziqi.cn/Article/details/gtqrcjcjsr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtmcvnhaxr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ivvv.top/Article/details/gtmsrkyimj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hammf.cn/Article/details/gtujjfoxnm.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxsivytxh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.haohaochexian.top/Article/details/gthykojpea.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinghuilouyu.cn/Article/details/gtycljrhfl.html

Py:   value = d.get("k") or default
来源：http://dali.sufxvd.cn/Article/details/gtjptbygex.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pengpengdd.cyou/Article/details/gtjloorexv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.daxiang520.top/Article/details/gtmpgudrri.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gtlkmekwsu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.mhx1999.top/Article/details/gthgirfpuy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jiagoushi.top/Article/details/gttwauvxjh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sufxvd.cn/Article/details/gtmvzehttu.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigufen.top/Article/details/gtevwcbbqm.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gtdlmkavjg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuetiantiany.cn/Article/details/gtqbpqvimh.html

PHP:  assert($x > 0);
来源：http://dali.cashguo.top/Article/details/gttxntjlgi.html

JS:   console.assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gtdhjniebw.html

TS:   console.assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gtyftalprs.html

Java: assert x > 0 : "必须为正";
来源：http://dali.9152youxi.cn/Article/details/gtdwbbhvki.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hnqzz.top/Article/details/gtjeahotts.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhixingplan.top/Article/details/gtgxfetprm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gtogfrjbyt.html

[H08] 获取错误信息与堆栈
来源：http://dali.xziqi.cn/Article/details/gtykqiymbi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cashguo.top/Article/details/gtsiczuhvf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gzhubu.top/Article/details/gtrfqqylkx.html

JS:   e.message;  e.stack
来源：http://dali.316326.xyz/Article/details/gtvhzstyda.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.smart0.xyz/Article/details/gttmoeutvn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.pengpengdd.cyou/Article/details/gtphnmugvc.html

Go:   err.Error()
来源：http://dali.dianchejie.cn/Article/details/gtiryeulgd.html

Ruby: e.message;  e.backtrace
来源：http://dali.dashuyun.cn/Article/details/gtogvysxha.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xylfe.cn/Article/details/gthyghvjfb.html

[H09] 带错误码的异常
来源：http://dali.yanxiufei.cn/Article/details/gtvbulsgfc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjdobhtu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinqigufen.top/Article/details/gtjlrfkbcn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigufen.top/Article/details/gtbopvqduk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cdnleiting.top/Article/details/gtiokyhwbt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.c1oappe.top/Article/details/gtiwpjlarg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj202588.top/Article/details/gtyzswvcme.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shzxlz.cn/Article/details/gtzzuuxoow.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hywenlv.cn/Article/details/gtkbjoumcd.html

[H10] 资源自动释放
来源：http://dali.zhoulong.xyz/Article/details/gtbrfejmac.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xziqi.cn/Article/details/gtkqhkmjox.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hammf.cn/Article/details/gthhclcdzc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhengqikj.top/Article/details/gtvhbqnpal.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnxiangtu.top/Article/details/gtzcpimfaq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.dianchejie.cn/Article/details/gtlmebfcol.html

Go:   defer f.Close()
来源：http://dali.smart0.xyz/Article/details/gtdynzrokl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenzaomai.com/Article/details/gtarsmzhgv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sweek.top/Article/details/gtgpnpguae.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtsyarygkq.html

I. 正则表达式
来源：http://dali.cheryme.top/Article/details/gthltvlmrh.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtcmaewfcx.html

[I01] 判断是否匹配
来源：http://dali.ydzc1.top/Article/details/gtqklsknbg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yuanzhike.top/Article/details/gtsnkzuqjo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yvedp.cn/Article/details/gtwzebasmd.html

JS:   /\d+/.test(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtbkkyulgm.html

TS:   /\d+/.test(s)
来源：http://dali.hfpthk.cn/Article/details/gthjydliyv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yanxiufei.cn/Article/details/gtjhutbrlf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xinyue.icu/Article/details/gtstkilzco.html

Ruby: s.match?(/\d+/)
来源：http://dali.ydzc1.top/Article/details/gtnbkoexfj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258888.top/Article/details/gtvstygwzo.html

[I02] 提取所有匹配
来源：http://dali.sysykeji.top/Article/details/gtqoafadde.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gtpomiixur.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jqgfzy.top/Article/details/gthnvdaenc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xuanzx.com/Article/details/gthykaayut.html

TS:   s.match(/\d+/g)
来源：http://dali.sweek.top/Article/details/gtpcahlsef.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jianghu66.top/Article/details/gtjbugtpgb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gotoacloud.top/Article/details/gtjlvokypc.html

Ruby: s.scan(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gtujsbuuly.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nwbrower.top/Article/details/gtrhgkpqmn.html

[I03] 提取捕获分组
来源：http://dali.aibaodan.cn/Article/details/gtpjcuhmjk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhongyouzk.top/Article/details/gtatfidocv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtpoewipxo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.9152youxi.cn/Article/details/gtrldszsce.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.birdmap.top/Article/details/gtrzhizpki.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.redwolf501.top/Article/details/gttimxrdoc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hysaishi.cn/Article/details/gtokzormnl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nanxuanxn.top/Article/details/gtmgavwgdu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jqgfzy.top/Article/details/gttpirwqgg.html

[I04] 正则替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiudsaape.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.9152youxi.cn/Article/details/gtadydrsrd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yanxiufei.cn/Article/details/gteyamikku.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jyoumei.cn/Article/details/gthddaxith.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gtsopgvtel.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtugnmwjjn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtcjjilpso.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtobjxpphw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yueranfly.top/Article/details/gtcfiqpqrw.html

[I05] 按正则拆分
来源：http://dali.pycfn.com/Article/details/gtybrqyfni.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.aizwys.cn/Article/details/gtxzupuyme.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.316326.xyz/Article/details/gtljiccxkx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfwkawctw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gtydwvmxkj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenzaomai.com/Article/details/gtyeaqwxtx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.redwolf501.top/Article/details/gtzshrnhxz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gtwngqmiuw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.bjfxy.top/Article/details/gthqvwdbwo.html


<!-- 参考信息 -->