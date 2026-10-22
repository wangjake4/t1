代发 wailian999

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sweek.top/Article/details/gtbdlajdgg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sweek.top/Article/details/gtuymhyowo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nwbrower.top/Article/details/gtbaqocvfj.html

TS:   // 同上
来源：http://dali.zhixingplan.top/Article/details/gtoioqsyeq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yuanzhike.top/Article/details/gtyuvzaboo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.dashuyun.cn/Article/details/gtxbaegrhv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenzaomai.com/Article/details/gtntrlqtfb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlmrcspal.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtrzfjqdkm.html

G. 面向对象
来源：http://dali.haohaochexian.top/Article/details/gtqqqxckmp.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtzrbzgoyx.html

[G01] 定义类
来源：http://dali.daxiang520.top/Article/details/gtugtrmxbk.html

Py:   class User: pass
来源：http://dali.birdmap.top/Article/details/gtxmyfpqmk.html

PHP:  class User {}
来源：http://dali.yj202588.top/Article/details/gtzsatnwgh.html

JS:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gtewabnzfs.html

TS:   class User { name: string = ""; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhvfnxqg.html

Java: class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtcjweklin.html

Go:   type User struct { Name string }
来源：http://dali.hongshengwenyu.top/Article/details/gtlqdsrlqi.html

Ruby: class User; end
来源：http://dali.sxryk.cn/Article/details/gttcrrkexl.html

C#:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gtalixcrgu.html

[G02] 构造函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnubcorpg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shangyingyoupin.top/Article/details/gtypjahpzs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xinyue.icu/Article/details/gtrtmxqdzc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cashguo.top/Article/details/gtozmiqvbc.html

TS:   constructor(public name: string) {}
来源：http://dali.nanxinkj.top/Article/details/gtzxbxkhsc.html

Java: User(String name) { this.name = name; }
来源：http://dali.redwolf501.top/Article/details/gtuvcxgdnw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.9152youxi.cn/Article/details/gtsepityzg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.kuanghao11.cn/Article/details/gtdduqnfbm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.redwolf501.top/Article/details/gtoeewrgup.html

[G03] 实例属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwzgdzmt.html

Py:   self.name = "x"
来源：http://dali.ybcxt.top/Article/details/gtgiczojyd.html

PHP:  public string $name = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpcsgcqjt.html

JS:   this.name = "x";
来源：http://dali.jiagoushi.top/Article/details/gtbnsmavgz.html

TS:   name: string = "x";
来源：http://dali.zhixingplan.top/Article/details/gtdouxaeqn.html

Java: private String name;
来源：http://dali.cheryme.top/Article/details/gtocpkpkku.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sufxvd.cn/Article/details/gtioogvrsk.html

Ruby: @name = "x"
来源：http://dali.havefunace.top/Article/details/gtabybjrgl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.haohaochexian.top/Article/details/gtbuiweoik.html

[G04] 定义方法
来源：http://dali.wangdashe.top/Article/details/gthcbnutaq.html

Py:   def greet(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gtdymgtuou.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gtqbwazrko.html

JS:   greet() { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtkzjmqfcg.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gturrrlhzt.html

Java: String greet() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtgrgbbiun.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gtxcpetnxt.html

Ruby: def greet; @name; end
来源：http://dali.aibaodan.cn/Article/details/gtzinkftdw.html

C#:   public string Greet() => Name;
来源：http://dali.haohaochexian.top/Article/details/gtmdlgeuzo.html

[G05] 继承
来源：http://dali.sxryk.cn/Article/details/gtcquknyis.html

Py:   class Admin(User): pass
来源：http://dali.daria6918.cn/Article/details/gtlqcviwmv.html

PHP:  class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtbqvnwppt.html

JS:   class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtyenyalpe.html

TS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtksbooxcr.html

Java: class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtdjjqkwkb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hammf.cn/Article/details/gttepbaoev.html

Ruby: class Admin < User; end
来源：http://dali.jianghu66.top/Article/details/gtohzmoaib.html

C#:   class Admin : User {}
来源：http://dali.sweek.top/Article/details/gtvlizwukr.html

[G06] 重写方法
来源：http://dali.nwbrower.top/Article/details/gtkkmzepok.html

Py:   def greet(self): return "admin"
来源：http://dali.cheryme.top/Article/details/gtadwpxqwq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gthzqftdfa.html

JS:   greet() { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtnqqzaneh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtokybwyqj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtwoiqslqd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cdnleiting.top/Article/details/gtncvuzssr.html

Ruby: def greet; "admin"; end
来源：http://dali.andypj.xyz/Article/details/gtkwglssdg.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenlongwang.top/Article/details/gttlawxihj.html

[G07] 调用父类方法
来源：http://dali.aibaodan.cn/Article/details/gtlvalqxhe.html

Py:   super().greet()
来源：http://dali.xziqi.cn/Article/details/gtllprlntm.html

PHP:  parent::greet();
来源：http://dali.nwbrower.top/Article/details/gtvwiuumge.html

JS:   super.greet();
来源：http://dali.hammf.cn/Article/details/gtzjvdwudp.html

TS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gtxzpwwlha.html

Java: super.greet();
来源：http://dali.guowangkeji.top/Article/details/gtoyvpibns.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.kuanghao11.cn/Article/details/gtjkkiaidn.html

Ruby: super
来源：http://dali.zhengqikj.top/Article/details/gttkeaqlpe.html

C#:   base.Greet();
来源：http://dali.sufxvd.cn/Article/details/gtdcuqbcfo.html

[G08] 静态方法与属性
来源：http://dali.yj202588.top/Article/details/gtpoulqbpl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigufen.top/Article/details/gteeuuyqht.html

PHP:  public static function f() {}
来源：http://dali.xylfe.cn/Article/details/gtmvhvrtjb.html

JS:   static f() {}
来源：http://dali.xinyue.icu/Article/details/gtbfxurdoj.html

TS:   static f(): void {}
来源：http://dali.meibo888.top/Article/details/gtkiprydxy.html

Java: static void f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtvgxpomwg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dashuyun.cn/Article/details/gtyygdjalk.html

Ruby: def self.f; end
来源：http://dali.c1oappe.top/Article/details/gtmdkcaxai.html

C#:   public static void F() {}
来源：http://dali.dianchejie.cn/Article/details/gtagzjesnd.html

[G09] 接口 / 抽象类
来源：http://dali.chenlongwang.top/Article/details/gtzhhokgal.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ivvv.top/Article/details/gtxrbtwggj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cashguo.top/Article/details/gtavnjgihw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxinkj.top/Article/details/gtipmlwlze.html

TS:   interface Shape { area(): number; }
来源：http://dali.ivvv.top/Article/details/gtgrztpsqm.html

Java: interface Shape { double area(); }
来源：http://dali.andypj.xyz/Article/details/gtxbsgeifw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fengsongda.top/Article/details/gtlxnlcdqh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jiagoushi.top/Article/details/gtylbhzsor.html

C#:   interface IShape { double Area(); }
来源：http://dali.hywenlv.cn/Article/details/gtpfccbvdu.html

[G10] 访问控制
来源：http://dali.0kj1m.cn/Article/details/gtujxfgqie.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zdqjudy.top/Article/details/gtpagtlyxn.html

PHP:  public / protected / private
来源：http://dali.xziqi.cn/Article/details/gtytamwhpt.html

JS:   #private 字段；其余公开
来源：http://dali.xuanzx.com/Article/details/gtmzqfmqcy.html

TS:   public / protected / private
来源：http://dali.pycfn.com/Article/details/gtbbkvyqcd.html

Java: public / protected / private / 默认包级
来源：http://dali.ppjwa.cn/Article/details/gtliqoujso.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenzaomai.com/Article/details/gtajgqhvsz.html

Ruby: public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gtkpontzgr.html

C#:   public / protected / private / internal
来源：http://dali.hnqzz.top/Article/details/gtcqnimkyf.html

[G11] getter / setter
来源：http://dali.hammf.cn/Article/details/gtgyzbnwha.html

Py:   @property 与 @x.setter
来源：http://dali.havefunace.top/Article/details/gthjsydvfi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtemduummv.html

JS:   get name() { return this._name; }
来源：http://dali.cucudq.cn/Article/details/gtauxslpnx.html

TS:   get name(): string { return this._name; }
来源：http://dali.jiagoushi.top/Article/details/gtjysniccg.html

Java: public String getName() { return name; }
来源：http://dali.sxryk.cn/Article/details/gtqiqqzsqo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gtrbkvkgeo.html

Ruby: attr_accessor :name
来源：http://dali.svipenyu.cn/Article/details/gtvkpnqtlh.html

C#:   public string Name { get; set; }
来源：http://dali.redwolf501.top/Article/details/gtubzpyshd.html

[G12] 对象转字符串
来源：http://dali.tianlin.xyz/Article/details/gtokbwmmmm.html

Py:   def __str__(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gtkrzgtiye.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gtpdnngydd.html

JS:   toString() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtfubifxby.html

TS:   toString(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtqzdsytzg.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkxyqjcvr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gthegxogbn.html

Ruby: def to_s; @name; end
来源：http://dali.hfpthk.cn/Article/details/gtqnczwses.html

C#:   public override string ToString() => Name;
来源：http://dali.fengsongda.top/Article/details/gtgscixpvq.html

[G13] 判断对象类型
来源：http://dali.wangdashe.top/Article/details/gtggfckgav.html

Py:   isinstance(u, User)
来源：http://dali.tianlin.xyz/Article/details/gtpnnzohhs.html

PHP:  $u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gtjyvplydp.html

JS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtdshgcftn.html

TS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gthifefctu.html

Java: u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gtbhqhwpnk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yonumen.top/Article/details/gtqyfqojkn.html

Ruby: u.is_a?(User)
来源：http://dali.xuanzx.com/Article/details/gtpxogeqsg.html

C#:   u is User
来源：http://dali.hongshengwenyu.top/Article/details/gtnkbjmluz.html

[G14] 数据类 / record
来源：http://dali.gzhubu.top/Article/details/gtgpenazxl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gtqjabfujm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenjidiqi.icu/Article/details/gtgdphhkuz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhiwuduotai.top/Article/details/gtytluvljy.html

TS:   type User = { name: string; age: number };
来源：http://dali.xziqi.cn/Article/details/gtdqdhfall.html

Java: record User(String name, int age) {}
来源：http://dali.sweek.top/Article/details/gtjadhnnlg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yuanzhike.top/Article/details/gtkhyosjnn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ivvv.top/Article/details/gtlwwxosji.html

C#:   record User(string Name, int Age);
来源：http://dali.hnqzz.top/Article/details/gtsaoeyajb.html

[G15] 枚举
来源：http://dali.shzxlz.cn/Article/details/gtulplqmta.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangdashe.top/Article/details/gtplomypee.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhixingplan.top/Article/details/gtgttitchq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhengqikj.top/Article/details/gtqknokxfo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gotoacloud.top/Article/details/gtpbzmxfcs.html

Java: enum Color { RED, GREEN }
来源：http://dali.nwbrower.top/Article/details/gtqcqjjkwq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangshuangyany.cn/Article/details/gtxhgfittp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yvedp.cn/Article/details/gtcotycqtt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gtsbdgllyk.html

[G16] 对象转数组 / 字典
来源：http://dali.yuxming.cn/Article/details/gtihjkrmct.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gotoacloud.top/Article/details/gtezohvwad.html

PHP:  get_object_vars($obj);
来源：http://dali.cqqwz.cn/Article/details/gtbautfqno.html

JS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gtboyelhsj.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtzvofyywa.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jiagoushi.top/Article/details/gtsoyjekyn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.birdmap.top/Article/details/gtvugmsdat.html

Ruby: obj.instance_variables
来源：http://dali.haohaochexian.top/Article/details/gtemmrxeqq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.birdmap.top/Article/details/gtxyrxcbsh.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtmfwyualw.html

H. 异常与错误处理
来源：http://dali.sufxvd.cn/Article/details/gtuixqbehd.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtdnuyrpxe.html

[H01] try / catch 基础
来源：http://dali.zdqjudy.top/Article/details/gtlqdhzbhq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gtmxifmezq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.0kj1m.cn/Article/details/gtlebzpmev.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gtyjfftiuu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gtkhvtyoxb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.andypj.xyz/Article/details/gtbklsseru.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.meibo888.top/Article/details/gtgfixmnti.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zdqjudy.top/Article/details/gtbfgkvvsu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigfzy.top/Article/details/gtvdmleckb.html

[H02] finally / ensure 收尾
来源：http://dali.jqgfzy.top/Article/details/gtymdaghuc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.havefunace.top/Article/details/gtwzghftvd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtuwojbxyy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtbuadkxpp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtrqmvvhsa.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtanwxzubr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.0kj1m.cn/Article/details/gtiaykyjev.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.pengpengdd.cyou/Article/details/gtelxziukx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtpbmtamqj.html

[H03] 主动抛出异常
来源：http://dali.daria6918.cn/Article/details/gtcjldgciu.html

Py:   raise ValueError("错误信息")
来源：http://dali.meibo888.top/Article/details/gttnvzmubn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gtgwvlxymd.html

JS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtoyqcoifq.html

TS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtjunwdjot.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtrkutkzzr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.fzhhl.top/Article/details/gtvjtsifje.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shangyingyoupin.top/Article/details/gtztvtwjkl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtnwyedbmb.html

[H04] 自定义异常类型
来源：http://dali.0kj1m.cn/Article/details/gtkbyarogl.html

Py:   class MyError(Exception): pass
来源：http://dali.bjfxy.top/Article/details/gtzxdgcmnd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gtovvqsiao.html

JS:   class MyError extends Error {}
来源：http://dali.dianchejie.cn/Article/details/gtupitiivd.html

TS:   class MyError extends Error {}
来源：http://dali.wangshuangyany.cn/Article/details/gtylstpced.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gtmbkxdrkq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gotoacloud.top/Article/details/gtguoprqsv.html

Ruby: class MyError < StandardError; end
来源：http://dali.nanxinkj.top/Article/details/gtmogmeave.html

C#:   class MyException : Exception {}
来源：http://dali.guannengcc.top/Article/details/gtghrfoowl.html

[H05] 捕获特定类型
来源：http://dali.hnxiangtu.top/Article/details/gtsqhqenhi.html

Py:   except ValueError as e:
来源：http://dali.cucudq.cn/Article/details/gtjqfshotk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhixingplan.top/Article/details/gtekkrjicn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hysaishi.cn/Article/details/gtanlkubxf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhoulong.xyz/Article/details/gtifwfleda.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjbwysov.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.fzhhl.top/Article/details/gtxrnkywrh.html

Ruby: rescue ArgumentError => e
来源：http://dali.bjfxy.top/Article/details/gtmqqweueu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yangfankeji.com/Article/details/gttlzrldil.html

[H06] 可选值 / 空值安全访问
来源：http://dali.iojbl.cn/Article/details/gtmpegjhao.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gtsdhxnrrp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.guannengcc.top/Article/details/gtbvnpegvn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenlongwang.top/Article/details/gtcekkvdth.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.aizwys.cn/Article/details/gtzvrcjswx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daria6918.cn/Article/details/gtxwvmerso.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ybcxt.top/Article/details/gtwxuctize.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtroyqnprt.html

C#:   obj?.A?.B ?? default
来源：http://dali.hfpthk.cn/Article/details/gtgderrnpv.html

[H07] 断言
来源：http://dali.jiagoushi.top/Article/details/gtjajtrgap.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sysykeji.top/Article/details/gttkveqxsn.html

PHP:  assert($x > 0);
来源：http://dali.aizwys.cn/Article/details/gthzqjqlqc.html

JS:   console.assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gticmaodda.html

TS:   console.assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtnpdongpg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.smart0.xyz/Article/details/gtyucmxthl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhengqikj.top/Article/details/gtzcqsfonr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.9152youxi.cn/Article/details/gtbhgrqgua.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gtcopujbyb.html

[H08] 获取错误信息与堆栈
来源：http://dali.cashguo.top/Article/details/gtkdcstjuv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.aizwys.cn/Article/details/gtajoasycv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nanxuanxn.top/Article/details/gtxqogxqbo.html

JS:   e.message;  e.stack
来源：http://dali.yuanzhike.top/Article/details/gtanbdaswf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cqqwz.cn/Article/details/gtzownvdso.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tanke756.top/Article/details/gtfckczejj.html

Go:   err.Error()
来源：http://dali.hysaishi.cn/Article/details/gtkvkbawnd.html

Ruby: e.message;  e.backtrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbqimrxpn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.havefunace.top/Article/details/gtipvbfkrg.html

[H09] 带错误码的异常
来源：http://dali.pengpengdd.cyou/Article/details/gtcocvxird.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hywenlv.cn/Article/details/gtputyyuvq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqgkfhqsv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.daxiang520.top/Article/details/gtdzlqwhtl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hywenlv.cn/Article/details/gtmrbqqkvr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gotoacloud.top/Article/details/gtjezhqwoz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yongpay.top/Article/details/gthxlexwxv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.fzhhl.top/Article/details/gtnvcpklkv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.svipenyu.cn/Article/details/gtddcsqgmz.html

[H10] 资源自动释放
来源：http://dali.9152youxi.cn/Article/details/gtdycgqhts.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cdnleiting.top/Article/details/gtmipgbewb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhengqikj.top/Article/details/gthjosmkwo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhoulong.xyz/Article/details/gtpdazrvfg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gtgmutotrx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgfzy.top/Article/details/gtluxzqypo.html

Go:   defer f.Close()
来源：http://dali.yj20258888.top/Article/details/gtkkqljbdp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.daria6918.cn/Article/details/gtfccjyufg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtuhikmoyp.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtbeqylbbm.html

I. 正则表达式
来源：http://dali.cashguo.top/Article/details/gtmsczznjc.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtkxkgqwtk.html

[I01] 判断是否匹配
来源：http://dali.shuidangran.top/Article/details/gtamfvxkki.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhengqikj.top/Article/details/gtofvjnonk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.meibo888.top/Article/details/gtscosnrqq.html

JS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gtvmcqpama.html

TS:   /\d+/.test(s)
来源：http://dali.yonumen.top/Article/details/gtcjfrmpyp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hywenlv.cn/Article/details/gtkxhheleb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttyicwyfo.html

Ruby: s.match?(/\d+/)
来源：http://dali.cdnleiting.top/Article/details/gtlezmihix.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyyrkaosm.html

[I02] 提取所有匹配
来源：http://dali.nanxuanxn.top/Article/details/gtbljjslys.html

Py:   re.findall(r"\d+", s)
来源：http://dali.andypj.xyz/Article/details/gtyhcrzkbn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.fengsongda.top/Article/details/gtrcprhixb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hywenlv.cn/Article/details/gthfudfquq.html

TS:   s.match(/\d+/g)
来源：http://dali.jinqigufen.top/Article/details/gtqswbdlje.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenzaomai.com/Article/details/gtomjflkrs.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xinyue.icu/Article/details/gtpxegyrns.html

Ruby: s.scan(/\d+/)
来源：http://dali.hfpthk.cn/Article/details/gtvzamuhyx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.haohaochexian.top/Article/details/gtodzqnour.html

[I03] 提取捕获分组
来源：http://dali.yuanzhike.top/Article/details/gtnqdihmbc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xuanzx.com/Article/details/gtmmawuwib.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.dashuyun.cn/Article/details/gtewoinkey.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xylfe.cn/Article/details/gtejfciiuk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj20258.top/Article/details/gtadiqeedd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ehwqpu.com/Article/details/gtwwgetyyc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenjidiqi.icu/Article/details/gtkehkejau.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xinyue.icu/Article/details/gtnqefyxxg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gtjbtkrhlt.html

[I04] 正则替换
来源：http://dali.shangyingyoupin.top/Article/details/gtusyguluu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ydzc1.top/Article/details/gtbxsrqefe.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.fengsongda.top/Article/details/gtdbvjekka.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sweek.top/Article/details/gtjukmzhzx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yuanzhike.top/Article/details/gtmxbttrhw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cashguo.top/Article/details/gtxzdvyrfi.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtkvqrfqhe.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xinyue.icu/Article/details/gtutmlcuog.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.andypj.xyz/Article/details/gtsvzgcaup.html

[I05] 按正则拆分
来源：http://dali.ehwqpu.com/Article/details/gtresfcsnj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yuanzhike.top/Article/details/gttyyyuthp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yuxming.cn/Article/details/gtikwtlrqn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gthulkqesj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gtrtpzwspc.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenzaomai.com/Article/details/gtukknfhwb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gaohongyu789.top/Article/details/gtjwozmmgb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gtlqjwrwmg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinghuilouyu.cn/Article/details/gtslddfpaz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nwbrower.top/Article/details/gtqghlmosd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gtkznyheng.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.smart0.xyz/Article/details/gttyhgoglh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gaohongyu789.top/Article/details/gtmoxsoaws.html


<!-- 参考信息 -->