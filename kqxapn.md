代发 wailian999

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.kuanghao11.cn/Article/details/gtrmozyyuu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ppjwa.cn/Article/details/gtcfpvsvwl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.fengsongda.top/Article/details/gtyaznqmqs.html

TS:   // 同上
来源：http://dali.kuanghao11.cn/Article/details/gtgduwqfoo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgfzy.top/Article/details/gtmmwjjtwn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj20258.top/Article/details/gtezpobuei.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gzhubu.top/Article/details/gttnrpbuti.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hammf.cn/Article/details/gtxytrskto.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtygjfsgzq.html

G. 面向对象
来源：http://dali.snrcjt.cn/Article/details/gtiqxvzlxn.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtkyltfvro.html

[G01] 定义类
来源：http://dali.jqgufenzy.top/Article/details/gtpiwzjpfg.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gtcgfhkwoc.html

PHP:  class User {}
来源：http://dali.fzhhl.top/Article/details/gtqdpynrha.html

JS:   class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtnimseyeu.html

TS:   class User { name: string = ""; }
来源：http://dali.shuidangran.top/Article/details/gtuxasdeqq.html

Java: class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtjqzofiea.html

Go:   type User struct { Name string }
来源：http://dali.ehwqpu.com/Article/details/gtjrxaiqri.html

Ruby: class User; end
来源：http://dali.daxiang520.top/Article/details/gtvbrcizmu.html

C#:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gtqwtglzhu.html

[G02] 构造函数
来源：http://dali.hysaishi.cn/Article/details/gtpbntnznf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jqgufenzy.top/Article/details/gtrhqzclyl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ydzc1.top/Article/details/gtlcmmpaei.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtgrzmyokn.html

TS:   constructor(public name: string) {}
来源：http://dali.nanxinkj.top/Article/details/gtaitxdiwi.html

Java: User(String name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtdyiodcvr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.andypj.xyz/Article/details/gtbsugeuug.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenlongwang.top/Article/details/gtjdoonqhr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhixingplan.top/Article/details/gtikyvvbja.html

[G03] 实例属性
来源：http://dali.nanxuanxn.top/Article/details/gtmlwkqcem.html

Py:   self.name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gtkvkboguz.html

PHP:  public string $name = "x";
来源：http://dali.cashguo.top/Article/details/gtrzzvesmr.html

JS:   this.name = "x";
来源：http://dali.zycfv.cn/Article/details/gtvlfvrdzr.html

TS:   name: string = "x";
来源：http://dali.zdqjudy.top/Article/details/gtowhbztia.html

Java: private String name;
来源：http://dali.sysykeji.top/Article/details/gtgreckxoa.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yvedp.cn/Article/details/gthqvmqidn.html

Ruby: @name = "x"
来源：http://dali.jqgfzy.top/Article/details/gtutrwgpos.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sufxvd.cn/Article/details/gttlehnlmd.html

[G04] 定义方法
来源：http://dali.xziqi.cn/Article/details/gtqfonzaww.html

Py:   def greet(self): return self.name
来源：http://dali.pengpengdd.cyou/Article/details/gtkmfegtri.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gtbuiqbwlk.html

JS:   greet() { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtvslbfuyp.html

TS:   greet(): string { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtodnglstt.html

Java: String greet() { return name; }
来源：http://dali.gzhubu.top/Article/details/gtpjkrnnps.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtapwqzumt.html

Ruby: def greet; @name; end
来源：http://dali.svipenyu.cn/Article/details/gtrbwfbrbo.html

C#:   public string Greet() => Name;
来源：http://dali.jyoumei.cn/Article/details/gtngxebwds.html

[G05] 继承
来源：http://dali.birdmap.top/Article/details/gtjqptvbtm.html

Py:   class Admin(User): pass
来源：http://dali.xuanzx.com/Article/details/gtuepxjthr.html

PHP:  class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtjrdtbkre.html

JS:   class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtxtolvxoa.html

TS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtjiahtdhj.html

Java: class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtqhlwawcn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shzxlz.cn/Article/details/gtevggpfoy.html

Ruby: class Admin < User; end
来源：http://dali.wangshuangyany.cn/Article/details/gtcqqxhgte.html

C#:   class Admin : User {}
来源：http://dali.kuanghao11.cn/Article/details/gtcjfyjypd.html

[G06] 重写方法
来源：http://dali.feifeiyinyue.top/Article/details/gtvqeraeow.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258888.top/Article/details/gtjojlduqw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtknljacrk.html

JS:   greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtxanyytii.html

TS:   greet(): string { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtlhovjroh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gtzpilynap.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hongshengwenyu.top/Article/details/gtkyyimgli.html

Ruby: def greet; "admin"; end
来源：http://dali.zhengqikj.top/Article/details/gtzpnhgcnj.html

C#:   public override string Greet() => "admin";
来源：http://dali.cheryme.top/Article/details/gtauxoykjy.html

[G07] 调用父类方法
来源：http://dali.aizwys.cn/Article/details/gtjvtkobyt.html

Py:   super().greet()
来源：http://dali.zhengqikj.top/Article/details/gtdudfedkw.html

PHP:  parent::greet();
来源：http://dali.ybcxt.top/Article/details/gtfpdrrhna.html

JS:   super.greet();
来源：http://dali.fengsongda.top/Article/details/gtzpdhmhzo.html

TS:   super.greet();
来源：http://dali.hfpthk.cn/Article/details/gtwnqglwrx.html

Java: super.greet();
来源：http://dali.xylfe.cn/Article/details/gtorxsjmng.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ydzc1.top/Article/details/gtdqsdivvt.html

Ruby: super
来源：http://dali.aizwys.cn/Article/details/gtcuhdlysv.html

C#:   base.Greet();
来源：http://dali.xylfe.cn/Article/details/gtinalbdhu.html

[G08] 静态方法与属性
来源：http://dali.pengpengdd.cyou/Article/details/gtqsskfogv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cqqwz.cn/Article/details/gtndtxfskz.html

PHP:  public static function f() {}
来源：http://dali.c1oappe.top/Article/details/gtylcqruea.html

JS:   static f() {}
来源：http://dali.ehwqpu.com/Article/details/gtiqsyjbjt.html

TS:   static f(): void {}
来源：http://dali.wangshuangyany.cn/Article/details/gtjbrtebca.html

Java: static void f() {}
来源：http://dali.hammf.cn/Article/details/gtsdtmkrvb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sufxvd.cn/Article/details/gtgzekfqkk.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gtcpkkrjih.html

C#:   public static void F() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtrijbtivp.html

[G09] 接口 / 抽象类
来源：http://dali.snrcjt.cn/Article/details/gtaibbmqsm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.bjfxy.top/Article/details/gtxgrgakyh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.quarkkingdee.top/Article/details/gtqjkllcvr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgfzy.top/Article/details/gtyzrammch.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gtyqqwnlfq.html

Java: interface Shape { double area(); }
来源：http://dali.fengsongda.top/Article/details/gthowdhsef.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xylfe.cn/Article/details/gtvlouhdmv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtqauvunwr.html

C#:   interface IShape { double Area(); }
来源：http://dali.cdnleiting.top/Article/details/gtqekapvil.html

[G10] 访问控制
来源：http://dali.cdnleiting.top/Article/details/gtehxnfhjb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinqigfzy.top/Article/details/gtisyitqpd.html

PHP:  public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gtfantwrtj.html

JS:   #private 字段；其余公开
来源：http://dali.nanxuanxn.top/Article/details/gtzblfolmh.html

TS:   public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gtxvklgiil.html

Java: public / protected / private / 默认包级
来源：http://dali.svipenyu.cn/Article/details/gtbbmcwvuq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zycfv.cn/Article/details/gtaqffkqpo.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gttbksuzll.html

C#:   public / protected / private / internal
来源：http://dali.jiagoushi.top/Article/details/gtnosggias.html

[G11] getter / setter
来源：http://dali.cqqwz.cn/Article/details/gtzsynxmsd.html

Py:   @property 与 @x.setter
来源：http://dali.zycfv.cn/Article/details/gtnifheokl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ybcxt.top/Article/details/gtkddeoywd.html

JS:   get name() { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gtrpnnfxkd.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gtqiqdsulp.html

Java: public String getName() { return name; }
来源：http://dali.xziqi.cn/Article/details/gtsiporsog.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gtycqcrofo.html

Ruby: attr_accessor :name
来源：http://dali.c1oappe.top/Article/details/gtfkoqazqp.html

C#:   public string Name { get; set; }
来源：http://dali.yonumen.top/Article/details/gtoqowjntv.html

[G12] 对象转字符串
来源：http://dali.bjfxy.top/Article/details/gtglbjbxap.html

Py:   def __str__(self): return self.name
来源：http://dali.vqdsnc.cn/Article/details/gtquyxnvrq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gtgwyujaky.html

JS:   toString() { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtrijrozhd.html

TS:   toString(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtbqqmhbcb.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtksxyaben.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gtrmvhtqhl.html

Ruby: def to_s; @name; end
来源：http://dali.dianchejie.cn/Article/details/gtyrgcowkb.html

C#:   public override string ToString() => Name;
来源：http://dali.aizwys.cn/Article/details/gttqvzsuss.html

[G13] 判断对象类型
来源：http://dali.aizwys.cn/Article/details/gtprogmoyv.html

Py:   isinstance(u, User)
来源：http://dali.yj20258.top/Article/details/gtbegccohd.html

PHP:  $u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gteabpsygh.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gtjdrumbsj.html

TS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtheyjyeou.html

Java: u instanceof User
来源：http://dali.ivvv.top/Article/details/gtksgdfnvc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ydzc1.top/Article/details/gtwsudlygi.html

Ruby: u.is_a?(User)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbltewou.html

C#:   u is User
来源：http://dali.shuidangran.top/Article/details/gtrxnzhiks.html

[G14] 数据类 / record
来源：http://dali.yj20258888.top/Article/details/gtmxrpjjfh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ydzc1.top/Article/details/gtxnztpdem.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gotoacloud.top/Article/details/gtkavefilz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zdqjudy.top/Article/details/gtsaxpvkzf.html

TS:   type User = { name: string; age: number };
来源：http://dali.smart0.xyz/Article/details/gtzoojtvzk.html

Java: record User(String name, int age) {}
来源：http://dali.jinqigfzy.top/Article/details/gtwxclrlsd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hysaishi.cn/Article/details/gturroxmay.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hfpthk.cn/Article/details/gttfkuuqno.html

C#:   record User(string Name, int Age);
来源：http://dali.jyoumei.cn/Article/details/gtbeyacnrj.html

[G15] 枚举
来源：http://dali.birdmap.top/Article/details/gtptvnvizz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yanxiufei.cn/Article/details/gtprryiskb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hywenlv.cn/Article/details/gtigrvxnrb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hammf.cn/Article/details/gtqtkfnacr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtevkuyxfj.html

Java: enum Color { RED, GREEN }
来源：http://dali.shzxlz.cn/Article/details/gtgbgqospk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gzhubu.top/Article/details/gthswevnlr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shuidangran.top/Article/details/gtjwchvriq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsiizsikj.html

[G16] 对象转数组 / 字典
来源：http://dali.fzhhl.top/Article/details/gtneqenmcy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqldtnuew.html

PHP:  get_object_vars($obj);
来源：http://dali.xylfe.cn/Article/details/gtlykqaabu.html

JS:   Object.entries(obj)
来源：http://dali.zycfv.cn/Article/details/gttgzsqgru.html

TS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtqyisgevu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cdnleiting.top/Article/details/gtkvhsxlea.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.meibo888.top/Article/details/gtcdsutyzp.html

Ruby: obj.instance_variables
来源：http://dali.jinqigfzy.top/Article/details/gttwpzcinu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yangfankeji.com/Article/details/gttszwfafq.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtbriovucn.html

H. 异常与错误处理
来源：http://dali.gotoacloud.top/Article/details/gtmcbhtwqj.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtjubgooqk.html

[H01] try / catch 基础
来源：http://dali.nwbrower.top/Article/details/gtiuczzfxb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.birdmap.top/Article/details/gtfissxvhk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yangfankeji.com/Article/details/gtenucszhj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxrmeyltu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gtujquizar.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daxiang520.top/Article/details/gtwrtakkyp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.snrcjt.cn/Article/details/gtrrzdqgzd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xuetiantiany.cn/Article/details/gtmknuzwvm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuxming.cn/Article/details/gtvfpkicol.html

[H02] finally / ensure 收尾
来源：http://dali.hfpthk.cn/Article/details/gthssggcne.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cqqwz.cn/Article/details/gtyyiwrgku.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtlqhlsfhl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtnbmznnms.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtxhxxxlsu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtxkhzpqih.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258888.top/Article/details/gtcnbbqofk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cdnleiting.top/Article/details/gtfsbudqry.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtxmzxzvwl.html

[H03] 主动抛出异常
来源：http://dali.bjfxy.top/Article/details/gtjmpuplpo.html

Py:   raise ValueError("错误信息")
来源：http://dali.birdmap.top/Article/details/gtrckrciht.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtylzxqqcu.html

JS:   throw new Error("错误信息");
来源：http://dali.sweek.top/Article/details/gtvxezylgh.html

TS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gtmzkiyvcn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtyxxdjcub.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.9152youxi.cn/Article/details/gtzsjdavur.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.smart0.xyz/Article/details/gtwyepbikq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtqpixqubb.html

[H04] 自定义异常类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbimrgivv.html

Py:   class MyError(Exception): pass
来源：http://dali.hongshengwenyu.top/Article/details/gtlrknuuzb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gtjyjgmgkf.html

JS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gtdwminwqi.html

TS:   class MyError extends Error {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdwshkjid.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpkhgdjoe.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenlongwang.top/Article/details/gtmlaxkucf.html

Ruby: class MyError < StandardError; end
来源：http://dali.gogol.net.cn/Article/details/gtpetlauui.html

C#:   class MyException : Exception {}
来源：http://dali.xuanzx.com/Article/details/gtmhzxrooy.html

[H05] 捕获特定类型
来源：http://dali.c1oappe.top/Article/details/gtskhyvrsh.html

Py:   except ValueError as e:
来源：http://dali.iojbl.cn/Article/details/gtmsuccaar.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.9152youxi.cn/Article/details/gtgcauvhwi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ybcxt.top/Article/details/gtfsxxdbke.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gtheluiwyf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtbkrbbwbs.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ydzc1.top/Article/details/gtsshbtvks.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinqigfzy.top/Article/details/gtstgkuwsk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.svipenyu.cn/Article/details/gtzgubvbgx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yonumen.top/Article/details/gtdupgfumv.html

Py:   value = d.get("k") or default
来源：http://dali.guowangkeji.top/Article/details/gtligkokwy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yonumen.top/Article/details/gtonwcqenu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ybcxt.top/Article/details/gtozlvulab.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gtzpoibaky.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ybcxt.top/Article/details/gtkjisflck.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.pycfn.com/Article/details/gtyunknksf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.redwolf501.top/Article/details/gtwowrihsr.html

C#:   obj?.A?.B ?? default
来源：http://dali.havefunace.top/Article/details/gtrkmrbxbh.html

[H07] 断言
来源：http://dali.redwolf501.top/Article/details/gtnyauxxbf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hammf.cn/Article/details/gtfuywwgwp.html

PHP:  assert($x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtkdwkkora.html

JS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gtvflqzipe.html

TS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gtztsodcwv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yueranfly.top/Article/details/gtoatpbdma.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cheryme.top/Article/details/gtzgsfgske.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkxpvwlsj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtqbxipxed.html

[H08] 获取错误信息与堆栈
来源：http://dali.shuidangran.top/Article/details/gtsxvjtyny.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhiwuduotai.top/Article/details/gtbmbzkryt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.wangdashe.top/Article/details/gtxvoywstr.html

JS:   e.message;  e.stack
来源：http://dali.hnxiangtu.top/Article/details/gtapwezwmd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.dianchejie.cn/Article/details/gtczufcxvd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.aibaodan.cn/Article/details/gtqgxqwjcr.html

Go:   err.Error()
来源：http://dali.zycfv.cn/Article/details/gtipwwirdk.html

Ruby: e.message;  e.backtrace
来源：http://dali.tian-w.cn/Article/details/gtehwfohbs.html

C#:   e.Message;  e.StackTrace
来源：http://dali.smart0.xyz/Article/details/gtktmppdos.html

[H09] 带错误码的异常
来源：http://dali.guowangkeji.top/Article/details/gtcwharoru.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shuidangran.top/Article/details/gtsacmleul.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gaohongyu789.top/Article/details/gtivpxoxws.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.iojbl.cn/Article/details/gtnlmyppgl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yuanzhike.top/Article/details/gtgyaivbiz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.kuanghao11.cn/Article/details/gtqfrbkbur.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yongpay.top/Article/details/gtizlsibuy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.snrcjt.cn/Article/details/gtqvjekjdh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjcshtlto.html

[H10] 资源自动释放
来源：http://dali.shzxlz.cn/Article/details/gteuxgnrce.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.vqdsnc.cn/Article/details/gtwrwwldou.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.chenjidiqi.icu/Article/details/gttcpayyvn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxinkj.top/Article/details/gtjskrqoqs.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sxryk.cn/Article/details/gtqgijrymk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.haohaochexian.top/Article/details/gtszixrnyh.html

Go:   defer f.Close()
来源：http://dali.nanxinkj.top/Article/details/gtpisafpzt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.feifeiyinyue.top/Article/details/gthnqavhpz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtcxeifsfx.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtoqpwcoqb.html

I. 正则表达式
来源：http://dali.bjfxy.top/Article/details/gtqfzztpqe.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtxgrenbxx.html

[I01] 判断是否匹配
来源：http://dali.meibo888.top/Article/details/gtvjrbykvf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gtjwesuzfr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cashguo.top/Article/details/gttrdlmlhc.html

JS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gtmvcwtrti.html

TS:   /\d+/.test(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfhfciaae.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhiwuduotai.top/Article/details/gtqtbpxoeo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtfijqgdqp.html

Ruby: s.match?(/\d+/)
来源：http://dali.hammf.cn/Article/details/gtyhmculne.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tian-w.cn/Article/details/gtztncjntu.html

[I02] 提取所有匹配
来源：http://dali.yuanzhike.top/Article/details/gtdzkwzaao.html

Py:   re.findall(r"\d+", s)
来源：http://dali.meibo888.top/Article/details/gtrqhrgzju.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jianghu66.top/Article/details/gtzexpttxr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ppjwa.cn/Article/details/gtxjghknvn.html

TS:   s.match(/\d+/g)
来源：http://dali.vqdsnc.cn/Article/details/gtxvuzlqla.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gtfugsewnm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.mhx1999.top/Article/details/gtvqdlblvc.html

Ruby: s.scan(/\d+/)
来源：http://dali.cashguo.top/Article/details/gtqooqmpyh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtdvcndsht.html

[I03] 提取捕获分组
来源：http://dali.vqdsnc.cn/Article/details/gtlbisgqir.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ybcxt.top/Article/details/gttkocnrcu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.0kj1m.cn/Article/details/gtxgmnzkvr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sweek.top/Article/details/gtacpckuxy.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ppjwa.cn/Article/details/gtmnswfvxh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jiagoushi.top/Article/details/gtmddtavas.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.bjfxy.top/Article/details/gtiwlksfzp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shuidangran.top/Article/details/gtjhbhfcaj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.guannengcc.top/Article/details/gtnhrvghjk.html

[I04] 正则替换
来源：http://dali.sufxvd.cn/Article/details/gtwefarjza.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nanxinkj.top/Article/details/gtafftejak.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.meibo888.top/Article/details/gtdtwyzbci.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.pycfn.com/Article/details/gtnhdsvowy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hysaishi.cn/Article/details/gtikhxqxfm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.0kj1m.cn/Article/details/gtoubczrmb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtszzygfmp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtkzyuwyxz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.dianchejie.cn/Article/details/gtiweczpzh.html

[I05] 按正则拆分
来源：http://dali.ybcxt.top/Article/details/gtmcwqwnpw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.aibaodan.cn/Article/details/gtnkqkspwo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yuxming.cn/Article/details/gtzuirszyl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gtfqzwcjof.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gtlbdjpxdk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nanxuanxn.top/Article/details/gtjkpvtqwd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gogol.net.cn/Article/details/gtnncpbkcq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdajpvko.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhixingplan.top/Article/details/gtxoitsfko.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhengqikj.top/Article/details/gtucyerssa.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gtqeiuyrpw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cqqwz.cn/Article/details/gtgyxpunjq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gotoacloud.top/Article/details/gtfqhqgmvi.html


<!-- 参考信息 -->