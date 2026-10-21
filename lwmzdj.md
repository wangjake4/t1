代发 wailian999

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shangyingyoupin.top/Article/details/gtrxyrlkgd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenzaomai.com/Article/details/gtjbsyreza.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cdnleiting.top/Article/details/gtzzoonuvo.html

TS:   // 同上
来源：http://dali.hysaishi.cn/Article/details/gttwoheuob.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gtzoaveekq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj202588.top/Article/details/gtogllcnhc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dianchejie.cn/Article/details/gtvukblnkg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.aizwys.cn/Article/details/gtxxpmkymg.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtolngxbrc.html

G. 面向对象
来源：http://dali.ehwqpu.com/Article/details/gtapvuyhsg.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtmjagmwmj.html

[G01] 定义类
来源：http://dali.ppjwa.cn/Article/details/gtahqqjuxe.html

Py:   class User: pass
来源：http://dali.0kj1m.cn/Article/details/gtwoidrpmj.html

PHP:  class User {}
来源：http://dali.daxiang520.top/Article/details/gtfhdappws.html

JS:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtjdwfycri.html

TS:   class User { name: string = ""; }
来源：http://dali.pycfn.com/Article/details/gtnzbngida.html

Java: class User {}
来源：http://dali.daxiang520.top/Article/details/gtogbsezmb.html

Go:   type User struct { Name string }
来源：http://dali.wangshuangyany.cn/Article/details/gtipfpwbax.html

Ruby: class User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmcyvpkwz.html

C#:   class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtiqdlvgas.html

[G02] 构造函数
来源：http://dali.gaohongyu789.top/Article/details/gtkkehwlqk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xinyue.icu/Article/details/gtyvttrmoo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.mhx1999.top/Article/details/gtzmosvsgk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlcljudov.html

TS:   constructor(public name: string) {}
来源：http://dali.guannengcc.top/Article/details/gtufcdetrs.html

Java: User(String name) { this.name = name; }
来源：http://dali.nwbrower.top/Article/details/gtmnwhzxbw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxinkj.top/Article/details/gtygraafjm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tanke756.top/Article/details/gtyhmuustq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yueranfly.top/Article/details/gtxumipxch.html

[G03] 实例属性
来源：http://dali.guannengcc.top/Article/details/gtkzqxzdgt.html

Py:   self.name = "x"
来源：http://dali.hfpthk.cn/Article/details/gtnnwdobyq.html

PHP:  public string $name = "x";
来源：http://dali.zhengqikj.top/Article/details/gtfwgjazoe.html

JS:   this.name = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtanyzaiyn.html

TS:   name: string = "x";
来源：http://dali.svipenyu.cn/Article/details/gtlchjxcoj.html

Java: private String name;
来源：http://dali.hnxiangtu.top/Article/details/gtjzbeopnu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.quarkkingdee.top/Article/details/gtlmrtglrz.html

Ruby: @name = "x"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqaxslmi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.meibo888.top/Article/details/gtczzbbagx.html

[G04] 定义方法
来源：http://dali.cucudq.cn/Article/details/gtickmdvdk.html

Py:   def greet(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gtjzhvxyfl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gtdgcqmiyv.html

JS:   greet() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtaxipoumf.html

TS:   greet(): string { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtndgfldqm.html

Java: String greet() { return name; }
来源：http://dali.hnqzz.top/Article/details/gtasinduxm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gthpfdpilu.html

Ruby: def greet; @name; end
来源：http://dali.fengsongda.top/Article/details/gtrmkfybwj.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gtdpotovsd.html

[G05] 继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotiytmmk.html

Py:   class Admin(User): pass
来源：http://dali.chenlongwang.top/Article/details/gtdhicqvpy.html

PHP:  class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtedzblkdd.html

JS:   class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gtdzsyoquf.html

TS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gtyeepkuwz.html

Java: class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtzzbokaak.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gttylxfgvx.html

Ruby: class Admin < User; end
来源：http://dali.316326.xyz/Article/details/gtstitsssb.html

C#:   class Admin : User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtvefwklnb.html

[G06] 重写方法
来源：http://dali.hnqzz.top/Article/details/gtntpqpljh.html

Py:   def greet(self): return "admin"
来源：http://dali.zhiwuduotai.top/Article/details/gtlzbvhnog.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtvsaljpvd.html

JS:   greet() { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtygsioegq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtmlevrzte.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtoqliqami.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.aizwys.cn/Article/details/gtxstyzrqt.html

Ruby: def greet; "admin"; end
来源：http://dali.yuanzhike.top/Article/details/gtzbhlnxpz.html

C#:   public override string Greet() => "admin";
来源：http://dali.dashuyun.cn/Article/details/gtwnndrmcp.html

[G07] 调用父类方法
来源：http://dali.cashguo.top/Article/details/gtjqhijliu.html

Py:   super().greet()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlczmuhwd.html

PHP:  parent::greet();
来源：http://dali.jiagoushi.top/Article/details/gtmdhpzoee.html

JS:   super.greet();
来源：http://dali.daxiang520.top/Article/details/gtpxfdpqpy.html

TS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gtkxvjaars.html

Java: super.greet();
来源：http://dali.haohaochexian.top/Article/details/gtsrvrdggh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hfpthk.cn/Article/details/gtwfvgbfpe.html

Ruby: super
来源：http://dali.gzhubu.top/Article/details/gtcyxfdxxk.html

C#:   base.Greet();
来源：http://dali.yonumen.top/Article/details/gtjdqrxclo.html

[G08] 静态方法与属性
来源：http://dali.tian-w.cn/Article/details/gtalwixmlw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenjidiqi.icu/Article/details/gtwefetkud.html

PHP:  public static function f() {}
来源：http://dali.pycfn.com/Article/details/gtzgbugqqe.html

JS:   static f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtbvubqlwl.html

TS:   static f(): void {}
来源：http://dali.hfpthk.cn/Article/details/gtopyxeqxf.html

Java: static void f() {}
来源：http://dali.tanke756.top/Article/details/gtnsfaaaux.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.wangdashe.top/Article/details/gthsudfmkz.html

Ruby: def self.f; end
来源：http://dali.shzxlz.cn/Article/details/gteigumxcj.html

C#:   public static void F() {}
来源：http://dali.cheryme.top/Article/details/gtvyjnqurg.html

[G09] 接口 / 抽象类
来源：http://dali.chenzaomai.com/Article/details/gtrqfguzqf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hammf.cn/Article/details/gtcymoiyjm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zdqjudy.top/Article/details/gtbxgvbfeg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daxiang520.top/Article/details/gtuzkktoay.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhongyouzk.top/Article/details/gtvpwuqjad.html

Java: interface Shape { double area(); }
来源：http://dali.andypj.xyz/Article/details/gtdvixuhto.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gaohongyu789.top/Article/details/gtzrprbfje.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhoulong.xyz/Article/details/gtxdoltlyd.html

C#:   interface IShape { double Area(); }
来源：http://dali.jlsjyb.cn/Article/details/gtvkycmnlg.html

[G10] 访问控制
来源：http://dali.sxryk.cn/Article/details/gtkidaurvf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.guowangkeji.top/Article/details/gtdanvbvth.html

PHP:  public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gtqacigxoe.html

JS:   #private 字段；其余公开
来源：http://dali.chenzaomai.com/Article/details/gtpnyczyuz.html

TS:   public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtgafpksjx.html

Java: public / protected / private / 默认包级
来源：http://dali.daria6918.cn/Article/details/gtpekrrfxp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.fengsongda.top/Article/details/gtqxoejuhi.html

Ruby: public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gttmvwbfmf.html

C#:   public / protected / private / internal
来源：http://dali.xuetiantiany.cn/Article/details/gtebzxnhlu.html

[G11] getter / setter
来源：http://dali.feifeiyinyue.top/Article/details/gtywelzjaw.html

Py:   @property 与 @x.setter
来源：http://dali.chenjidiqi.icu/Article/details/gtxycxxamk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtbitjzsap.html

JS:   get name() { return this._name; }
来源：http://dali.tian-w.cn/Article/details/gtzsmojhiu.html

TS:   get name(): string { return this._name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtduczvsjd.html

Java: public String getName() { return name; }
来源：http://dali.havefunace.top/Article/details/gtynkywqou.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gtujouoaah.html

Ruby: attr_accessor :name
来源：http://dali.sxryk.cn/Article/details/gtrtpmaoem.html

C#:   public string Name { get; set; }
来源：http://dali.0kj1m.cn/Article/details/gtxpmzlkup.html

[G12] 对象转字符串
来源：http://dali.cqqwz.cn/Article/details/gtsjqoycnh.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258888.top/Article/details/gtqjbdsikc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gtldwwqnrl.html

JS:   toString() { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtdolmpzjr.html

TS:   toString(): string { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gtdhqdtnse.html

Java: @Override public String toString() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtmwplklzy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gtcfxtdckq.html

Ruby: def to_s; @name; end
来源：http://dali.yangfankeji.com/Article/details/gthbnxrndy.html

C#:   public override string ToString() => Name;
来源：http://dali.zhiwuduotai.top/Article/details/gtwjvansgh.html

[G13] 判断对象类型
来源：http://dali.wangdashe.top/Article/details/gtctxegohf.html

Py:   isinstance(u, User)
来源：http://dali.shuidangran.top/Article/details/gtalpidfny.html

PHP:  $u instanceof User
来源：http://dali.smart0.xyz/Article/details/gttpwthquq.html

JS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gtvvtefchr.html

TS:   u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gtjofutwqn.html

Java: u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtyatjqowp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.wangdashe.top/Article/details/gtzfngzegm.html

Ruby: u.is_a?(User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmsvvsphg.html

C#:   u is User
来源：http://dali.andypj.xyz/Article/details/gtvjzetrsw.html

[G14] 数据类 / record
来源：http://dali.gaohongyu789.top/Article/details/gtjrbnbbvv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cheryme.top/Article/details/gtmcegngpw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aibaodan.cn/Article/details/gtisvmastm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hysaishi.cn/Article/details/gtgrqpwjwz.html

TS:   type User = { name: string; age: number };
来源：http://dali.cucudq.cn/Article/details/gtsymuifxr.html

Java: record User(String name, int age) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtnzunyyec.html

Go:   type User struct { Name string; Age int }
来源：http://dali.snrcjt.cn/Article/details/gtxyidruol.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinghuilouyu.cn/Article/details/gtraksbpmp.html

C#:   record User(string Name, int Age);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukrundsi.html

[G15] 枚举
来源：http://dali.svipenyu.cn/Article/details/gtoagenhxu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangdashe.top/Article/details/gtgzujbqpc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yangfankeji.com/Article/details/gttqeoyztv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangdashe.top/Article/details/gtsjmjjuui.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gteydsepkw.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigfzy.top/Article/details/gthpfzdece.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nanxuanxn.top/Article/details/gtyexonzqp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cdnleiting.top/Article/details/gtobxwxpor.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzikoqtuy.html

[G16] 对象转数组 / 字典
来源：http://dali.redwolf501.top/Article/details/gtwimfoqdz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yanxiufei.cn/Article/details/gtikgdiutn.html

PHP:  get_object_vars($obj);
来源：http://dali.havefunace.top/Article/details/gtnfckzeqy.html

JS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gtnuqjgvnb.html

TS:   Object.entries(obj)
来源：http://dali.yuanzhike.top/Article/details/gtckrmgkkq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxpmdwkh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hammf.cn/Article/details/gtcgjsxxeh.html

Ruby: obj.instance_variables
来源：http://dali.redwolf501.top/Article/details/gtaaqifaaq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gtslsbzajg.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjunwclh.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gtceovhqwl.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtdhijxztq.html

[H01] try / catch 基础
来源：http://dali.0kj1m.cn/Article/details/gtrtqjnzpg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yangfankeji.com/Article/details/gtllnpocmx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtcgvjfbyl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gtsdgedshl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gttwlxwjqb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.wangdashe.top/Article/details/gtgitejllr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenjidiqi.icu/Article/details/gtflwykozk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hongshengwenyu.top/Article/details/gtidtasazd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tian-w.cn/Article/details/gtyzrqqkyj.html

[H02] finally / ensure 收尾
来源：http://dali.sufxvd.cn/Article/details/gtjiefgfzl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigfzy.top/Article/details/gtfhfrxgpo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtumwcihuo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtlmrijetr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtmsmrcipv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtlqeycmyq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jiagoushi.top/Article/details/gtyxqkrjks.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jyoumei.cn/Article/details/gtoflxznne.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtfcyzheqk.html

[H03] 主动抛出异常
来源：http://dali.cucudq.cn/Article/details/gtfrlrxllk.html

Py:   raise ValueError("错误信息")
来源：http://dali.zycfv.cn/Article/details/gtmfgnpads.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtwwqclejo.html

JS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gtedxxxxud.html

TS:   throw new Error("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtynwxfawi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtsmavnkej.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgfzy.top/Article/details/gtptmtrbhk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nanxuanxn.top/Article/details/gtujrjmicr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtxbinoebi.html

[H04] 自定义异常类型
来源：http://dali.gotoacloud.top/Article/details/gtmjbcsrhp.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxuanxn.top/Article/details/gtvtajgujn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.quarkkingdee.top/Article/details/gtzcisovjg.html

JS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gtmyjtsorp.html

TS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gtbxdmvsgd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gtmtcyfhoy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.snrcjt.cn/Article/details/gtnkuntvei.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtspuvaqwt.html

C#:   class MyException : Exception {}
来源：http://dali.kuanghao11.cn/Article/details/gtlxrubqlt.html

[H05] 捕获特定类型
来源：http://dali.yangfankeji.com/Article/details/gtdhlmzeqv.html

Py:   except ValueError as e:
来源：http://dali.zhiwuduotai.top/Article/details/gtbplqdnpd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tian-w.cn/Article/details/gtntyapbsv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gogol.net.cn/Article/details/gtabdfsevr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zdqjudy.top/Article/details/gtymhsvryu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jyoumei.cn/Article/details/gtokxuzahg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jiagoushi.top/Article/details/gttvzevaci.html

Ruby: rescue ArgumentError => e
来源：http://dali.sysykeji.top/Article/details/gtxgacdwql.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.andypj.xyz/Article/details/gtklsihrxu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ydzc1.top/Article/details/gtteynqvnj.html

Py:   value = d.get("k") or default
来源：http://dali.tian-w.cn/Article/details/gtrobnkyig.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gtcocldihy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gtvjwkazty.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gtraetowlg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuxming.cn/Article/details/gtireeebnp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.andypj.xyz/Article/details/gtueaptmxr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yonumen.top/Article/details/gteicsolds.html

C#:   obj?.A?.B ?? default
来源：http://dali.sweek.top/Article/details/gtukksstxu.html

[H07] 断言
来源：http://dali.jqgfzy.top/Article/details/gtizgyzxkx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.0kj1m.cn/Article/details/gtfxsvuojo.html

PHP:  assert($x > 0);
来源：http://dali.xuanzx.com/Article/details/gtcqwekjdo.html

JS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gtbgcpawuh.html

TS:   console.assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtmshogkvn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqnryurxa.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aibaodan.cn/Article/details/gtrxnawunv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cashguo.top/Article/details/gtkyyyndhy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtbpsbndta.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangdashe.top/Article/details/gtvbgrcaiu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cucudq.cn/Article/details/gtjmxcgcrm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nanxuanxn.top/Article/details/gtnyqfuuzn.html

JS:   e.message;  e.stack
来源：http://dali.pycfn.com/Article/details/gtlivprdnm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pengpengdd.cyou/Article/details/gtadbcmmsb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jqgufenzy.top/Article/details/gtzcfrytfc.html

Go:   err.Error()
来源：http://dali.snrcjt.cn/Article/details/gtsgwkalnr.html

Ruby: e.message;  e.backtrace
来源：http://dali.haohaochexian.top/Article/details/gtuhdrhnbm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtirwkilmf.html

[H09] 带错误码的异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdznslqko.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jiagoushi.top/Article/details/gtirqjdiyi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangdashe.top/Article/details/gtffacaxmb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tianlin.xyz/Article/details/gtbpbjmozj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ppjwa.cn/Article/details/gtmexhchhk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cdnleiting.top/Article/details/gtbfqhesvt.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.guannengcc.top/Article/details/gtovkimmow.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sxryk.cn/Article/details/gtprazskyq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gaohongyu789.top/Article/details/gtezwveisu.html

[H10] 资源自动释放
来源：http://dali.cheryme.top/Article/details/gtqjaxzqfl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hongshengwenyu.top/Article/details/gtmugzmfft.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhixingplan.top/Article/details/gtsbxyvuvh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhixingplan.top/Article/details/gtnpekyxdh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nwbrower.top/Article/details/gtswbfdanc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.pengpengdd.cyou/Article/details/gtbaznghrz.html

Go:   defer f.Close()
来源：http://dali.feifeiyinyue.top/Article/details/gtfkubhgow.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fengsongda.top/Article/details/gtnhxeyvkq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtmnslhndo.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtwervhjkn.html

I. 正则表达式
来源：http://dali.chenzaomai.com/Article/details/gtwktbuate.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gthaihqbpi.html

[I01] 判断是否匹配
来源：http://dali.yanxiufei.cn/Article/details/gtbujtznas.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ppjwa.cn/Article/details/gtjdnulnbk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtqmlthocx.html

JS:   /\d+/.test(s)
来源：http://dali.yueranfly.top/Article/details/gttpwpjmlu.html

TS:   /\d+/.test(s)
来源：http://dali.daria6918.cn/Article/details/gtzyrubjlj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj20258.top/Article/details/gtbqlmfsfy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgufenzy.top/Article/details/gtgdywednu.html

Ruby: s.match?(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gtbshyzfiy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.havefunace.top/Article/details/gtcxqivaug.html

[I02] 提取所有匹配
来源：http://dali.guowangkeji.top/Article/details/gtmwqgvabe.html

Py:   re.findall(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gtknffbomv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj20258888.top/Article/details/gtagyngybi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenjidiqi.icu/Article/details/gteewqyfuk.html

TS:   s.match(/\d+/g)
来源：http://dali.smart0.xyz/Article/details/gtcimdqunm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shzxlz.cn/Article/details/gtkvakhvwx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.aibaodan.cn/Article/details/gtzluxlxtn.html

Ruby: s.scan(/\d+/)
来源：http://dali.dianchejie.cn/Article/details/gtzvaqflrk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sweek.top/Article/details/gtnhlajnmx.html

[I03] 提取捕获分组
来源：http://dali.cheryme.top/Article/details/gtneofuzhv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hammf.cn/Article/details/gtjvazfubb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.iojbl.cn/Article/details/gtxsvckmei.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.c1oappe.top/Article/details/gtmhrmjbks.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.aibaodan.cn/Article/details/gtbsmhnkrd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuetiantiany.cn/Article/details/gthyzoylws.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yuxming.cn/Article/details/gtmflavqix.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shzxlz.cn/Article/details/gtrlutdnfb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nwbrower.top/Article/details/gtjtbuyttz.html

[I04] 正则替换
来源：http://dali.ehwqpu.com/Article/details/gtinbulydj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtuzkccbqe.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtleqwpbjj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtjnfelnsr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gtmakecfhh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.aibaodan.cn/Article/details/gthegfnxfj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj20258888.top/Article/details/gtrfkcwufd.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ehwqpu.com/Article/details/gtvvvcpcdb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gzhubu.top/Article/details/gtuhjxryfs.html

[I05] 按正则拆分
来源：http://dali.cdnleiting.top/Article/details/gtsyblsekj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yonumen.top/Article/details/gtqwxcyycb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ivvv.top/Article/details/gtmbrztnce.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gtwzzeiauw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gtkudwnaco.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tian-w.cn/Article/details/gtspluncdl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.smart0.xyz/Article/details/gtgceaafcg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gtkqqtlzkb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhongyouzk.top/Article/details/gtjrcohvaj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.svipenyu.cn/Article/details/gtquygddip.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gtinxivvxd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yueranfly.top/Article/details/gtkzmccnoj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.bjfxy.top/Article/details/gtnwsqrurg.html


<!-- 参考信息 -->