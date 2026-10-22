代发 wailian999

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cashguo.top/Article/details/gthhgrgshp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gzhubu.top/Article/details/gtdeyqyrpf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuetiantiany.cn/Article/details/gtbtprrbma.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.guannengcc.top/Article/details/gtblswhtpw.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtfcbchvsa.html

G. 面向对象
来源：http://dali.nwbrower.top/Article/details/gtwfgeclad.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtbyinaywd.html

[G01] 定义类
来源：http://dali.pengpengdd.cyou/Article/details/gtbadmhakw.html

Py:   class User: pass
来源：http://dali.jinqigfzy.top/Article/details/gtvcntordx.html

PHP:  class User {}
来源：http://dali.yvedp.cn/Article/details/gtmgtfhhep.html

JS:   class User {}
来源：http://dali.yuxming.cn/Article/details/gtwbpncnuk.html

TS:   class User { name: string = ""; }
来源：http://dali.birdmap.top/Article/details/gtaoyexajr.html

Java: class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtkbrxhdiq.html

Go:   type User struct { Name string }
来源：http://dali.hywenlv.cn/Article/details/gtgnywvela.html

Ruby: class User; end
来源：http://dali.zhongyouzk.top/Article/details/gtdicdmfoi.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gtvamyacxg.html

[G02] 构造函数
来源：http://dali.cqqwz.cn/Article/details/gtqnscmitr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tanke756.top/Article/details/gtndgrdjhr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sysykeji.top/Article/details/gtppxkluor.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yvedp.cn/Article/details/gtdyldmfpq.html

TS:   constructor(public name: string) {}
来源：http://dali.yvedp.cn/Article/details/gtpdrjlpol.html

Java: User(String name) { this.name = name; }
来源：http://dali.yongpay.top/Article/details/gtcmqwjqdg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.mhx1999.top/Article/details/gtxhiabcgn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fzhhl.top/Article/details/gtbrthjfqt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtjiongoqq.html

[G03] 实例属性
来源：http://dali.ehwqpu.com/Article/details/gtzwyiwjio.html

Py:   self.name = "x"
来源：http://dali.hongshengwenyu.top/Article/details/gtahcxxazg.html

PHP:  public string $name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtlehmybox.html

JS:   this.name = "x";
来源：http://dali.cashguo.top/Article/details/gthzgdumwo.html

TS:   name: string = "x";
来源：http://dali.zdqjudy.top/Article/details/gtsketxrok.html

Java: private String name;
来源：http://dali.sufxvd.cn/Article/details/gtjkmhtoia.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj202588.top/Article/details/gtbeswmsfi.html

Ruby: @name = "x"
来源：http://dali.wangdashe.top/Article/details/gtyccqbpcg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tanke756.top/Article/details/gtlnqalzlh.html

[G04] 定义方法
来源：http://dali.zdqjudy.top/Article/details/gteqldnxji.html

Py:   def greet(self): return self.name
来源：http://dali.havefunace.top/Article/details/gtwuxxvdib.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtqrxmfatv.html

JS:   greet() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtipeluxil.html

TS:   greet(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkrhameju.html

Java: String greet() { return name; }
来源：http://dali.shuidangran.top/Article/details/gttdclimbw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gttlgvdlmj.html

Ruby: def greet; @name; end
来源：http://dali.jiagoushi.top/Article/details/gtzcbznmwh.html

C#:   public string Greet() => Name;
来源：http://dali.9152youxi.cn/Article/details/gtmqrfjwia.html

[G05] 继承
来源：http://dali.yuanzhike.top/Article/details/gtgmjaambc.html

Py:   class Admin(User): pass
来源：http://dali.hongshengwenyu.top/Article/details/gtqlonvsze.html

PHP:  class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gtwhnhmegg.html

JS:   class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gtciredlhc.html

TS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtozglaynw.html

Java: class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtooxcuacv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shzxlz.cn/Article/details/gtybconhcr.html

Ruby: class Admin < User; end
来源：http://dali.nwbrower.top/Article/details/gtsonidyps.html

C#:   class Admin : User {}
来源：http://dali.xinyue.icu/Article/details/gticulphdd.html

[G06] 重写方法
来源：http://dali.hysaishi.cn/Article/details/gtcpprzrnl.html

Py:   def greet(self): return "admin"
来源：http://dali.jianghu66.top/Article/details/gtgpywficx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtrimlpfhm.html

JS:   greet() { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gtdeaxjahu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtzuubnkqb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gtfvvauoru.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.haohaochexian.top/Article/details/gtuaccpemm.html

Ruby: def greet; "admin"; end
来源：http://dali.9152youxi.cn/Article/details/gtztczwfrf.html

C#:   public override string Greet() => "admin";
来源：http://dali.wangshuangyany.cn/Article/details/gtiptmvfbc.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gtkvmjlgti.html

Py:   super().greet()
来源：http://dali.zycfv.cn/Article/details/gtaivxgtrb.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gtlgxldipv.html

JS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gtzkamophp.html

TS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtruswkppa.html

Java: super.greet();
来源：http://dali.zycfv.cn/Article/details/gtynetfora.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.0kj1m.cn/Article/details/gtrfkgmfww.html

Ruby: super
来源：http://dali.nanxinkj.top/Article/details/gtphcgxitf.html

C#:   base.Greet();
来源：http://dali.zhixingplan.top/Article/details/gtzhjprrjp.html

[G08] 静态方法与属性
来源：http://dali.pengpengdd.cyou/Article/details/gtutpxztpw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ywan-chungtsiang.top/Article/details/gtitxxhaxp.html

PHP:  public static function f() {}
来源：http://dali.cucudq.cn/Article/details/gtfcipadks.html

JS:   static f() {}
来源：http://dali.daria6918.cn/Article/details/gtwxayflwz.html

TS:   static f(): void {}
来源：http://dali.cheryme.top/Article/details/gtkaulzxmu.html

Java: static void f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtzouixqhx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sufxvd.cn/Article/details/gthzxviliw.html

Ruby: def self.f; end
来源：http://dali.bjfxy.top/Article/details/gtgrjoimmi.html

C#:   public static void F() {}
来源：http://dali.wangdashe.top/Article/details/gtgbejonyg.html

[G09] 接口 / 抽象类
来源：http://dali.zhengqikj.top/Article/details/gtfwmrzhkr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangshuangyany.cn/Article/details/gtyokepisj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yuanzhike.top/Article/details/gtcvqqvetu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.fzhhl.top/Article/details/gtgajgdkyg.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangdashe.top/Article/details/gtsuooobsz.html

Java: interface Shape { double area(); }
来源：http://dali.jqgfzy.top/Article/details/gtdhhdnqez.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yongpay.top/Article/details/gtzeruaraq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yangfankeji.com/Article/details/gttytgngey.html

C#:   interface IShape { double Area(); }
来源：http://dali.pycfn.com/Article/details/gtsfopyyaq.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gtqrdornyv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuanzhike.top/Article/details/gtvafnzhca.html

PHP:  public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gtqsdooygd.html

JS:   #private 字段；其余公开
来源：http://dali.ehwqpu.com/Article/details/gtuqpumufc.html

TS:   public / protected / private
来源：http://dali.sxryk.cn/Article/details/gtvvdrpdqo.html

Java: public / protected / private / 默认包级
来源：http://dali.jinghuilouyu.cn/Article/details/gtktxkkbfe.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuanzx.com/Article/details/gtcwffgfve.html

Ruby: public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gtkpdbaena.html

C#:   public / protected / private / internal
来源：http://dali.yuxming.cn/Article/details/gtwrayyenh.html

[G11] getter / setter
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcysiiqoj.html

Py:   @property 与 @x.setter
来源：http://dali.redwolf501.top/Article/details/gtnghjkhco.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ybcxt.top/Article/details/gtjkymejfk.html

JS:   get name() { return this._name; }
来源：http://dali.aizwys.cn/Article/details/gtxnzqkrqn.html

TS:   get name(): string { return this._name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunpdjnbm.html

Java: public String getName() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gttokximky.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtkfqqdonb.html

Ruby: attr_accessor :name
来源：http://dali.iojbl.cn/Article/details/gtckhnkxmo.html

C#:   public string Name { get; set; }
来源：http://dali.zhiwuduotai.top/Article/details/gtruhzfpco.html

[G12] 对象转字符串
来源：http://dali.ppjwa.cn/Article/details/gtveohpylc.html

Py:   def __str__(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gtsthkqnfk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gtosfnwjsu.html

JS:   toString() { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtptwfdzab.html

TS:   toString(): string { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtfhxqhzjy.html

Java: @Override public String toString() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtbkpwuglh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gtzbelnffh.html

Ruby: def to_s; @name; end
来源：http://dali.svipenyu.cn/Article/details/gtvzhqsmqt.html

C#:   public override string ToString() => Name;
来源：http://dali.redwolf501.top/Article/details/gtqomffppv.html

[G13] 判断对象类型
来源：http://dali.jinqigfzy.top/Article/details/gtxnhrwjkd.html

Py:   isinstance(u, User)
来源：http://dali.pycfn.com/Article/details/gtmjodsnop.html

PHP:  $u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gtzfkrowuw.html

JS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gtiyizqqyn.html

TS:   u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gtoasjvtdd.html

Java: u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtvgefxlah.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aibaodan.cn/Article/details/gtzghhbmjg.html

Ruby: u.is_a?(User)
来源：http://dali.nwbrower.top/Article/details/gtoltmogdm.html

C#:   u is User
来源：http://dali.guannengcc.top/Article/details/gtmcjwcwuh.html

[G14] 数据类 / record
来源：http://dali.dashuyun.cn/Article/details/gtzbxkmfru.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jianghu66.top/Article/details/gtrlwrrpre.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jlsjyb.cn/Article/details/gtjsgthwhl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.quarkkingdee.top/Article/details/gtlgedkyvt.html

TS:   type User = { name: string; age: number };
来源：http://dali.pycfn.com/Article/details/gtsafegnik.html

Java: record User(String name, int age) {}
来源：http://dali.zdqjudy.top/Article/details/gtmotgarvz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigfzy.top/Article/details/gtcxlwmddc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gotoacloud.top/Article/details/gtvzbvycfl.html

C#:   record User(string Name, int Age);
来源：http://dali.svipenyu.cn/Article/details/gtwetjgyjh.html

[G15] 枚举
来源：http://dali.jianghu66.top/Article/details/gtqfsaypag.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yangfankeji.com/Article/details/gtosxtjhjo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenlongwang.top/Article/details/gtmgvycejl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuetiantiany.cn/Article/details/gtfittnpmq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtvjbpniwo.html

Java: enum Color { RED, GREEN }
来源：http://dali.jyoumei.cn/Article/details/gtouvpzzxo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdczpmqsr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xinyue.icu/Article/details/gtxrrwazvc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.9152youxi.cn/Article/details/gtoopucxly.html

[G16] 对象转数组 / 字典
来源：http://dali.fzhhl.top/Article/details/gtvygrzlnx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxuanxn.top/Article/details/gtpqwwoqod.html

PHP:  get_object_vars($obj);
来源：http://dali.aizwys.cn/Article/details/gttgaaxrpw.html

JS:   Object.entries(obj)
来源：http://dali.yj202588.top/Article/details/gtvenkynhf.html

TS:   Object.entries(obj)
来源：http://dali.guannengcc.top/Article/details/gtubqxxgaj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daria6918.cn/Article/details/gttniktxnr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zdqjudy.top/Article/details/gtiuexillu.html

Ruby: obj.instance_variables
来源：http://dali.kuanghao11.cn/Article/details/gtnekuvxtw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gthajkoxxz.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtrynuaaqv.html

H. 异常与错误处理
来源：http://dali.ydzc1.top/Article/details/gtppmjgplm.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtcggbdgjj.html

[H01] try / catch 基础
来源：http://dali.hnxiangtu.top/Article/details/gtuajamldr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zycfv.cn/Article/details/gtdvcqbvfx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daxiang520.top/Article/details/gtrdvidehn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtuxyuczpa.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gtwbnwzsde.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yvedp.cn/Article/details/gtrgzxqzru.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkoquxsey.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yonumen.top/Article/details/gtjzlpynsy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbzytemom.html

[H02] finally / ensure 收尾
来源：http://dali.ybcxt.top/Article/details/gtjdhnyckg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhengqikj.top/Article/details/gtonwspqmc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtoybvzjmw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtsxcvesos.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtixhmiieb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrtpyfnet.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenjidiqi.icu/Article/details/gtpztiymsl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinqigfzy.top/Article/details/gtuidnzsbc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtpvkmocgu.html

[H03] 主动抛出异常
来源：http://dali.quarkkingdee.top/Article/details/gtictwxnzv.html

Py:   raise ValueError("错误信息")
来源：http://dali.guannengcc.top/Article/details/gtyrelkbfj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtmbewezcs.html

JS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gttybrdikh.html

TS:   throw new Error("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtqxkgxtkr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gtavmgfwod.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinghuilouyu.cn/Article/details/gtekmfizmg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.pycfn.com/Article/details/gtoyiylhnu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gttldljkny.html

[H04] 自定义异常类型
来源：http://dali.gogol.net.cn/Article/details/gtkvsjoyuj.html

Py:   class MyError(Exception): pass
来源：http://dali.guannengcc.top/Article/details/gtspisqnim.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gtqzjhzjps.html

JS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gtwynazqbw.html

TS:   class MyError extends Error {}
来源：http://dali.aibaodan.cn/Article/details/gtgicvcfxq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.quarkkingdee.top/Article/details/gtfjihgrhc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gotoacloud.top/Article/details/gtovwnseul.html

Ruby: class MyError < StandardError; end
来源：http://dali.daxiang520.top/Article/details/gtpwpdhyzg.html

C#:   class MyException : Exception {}
来源：http://dali.yueranfly.top/Article/details/gthkpyguut.html

[H05] 捕获特定类型
来源：http://dali.hnqzz.top/Article/details/gtpkqsazdk.html

Py:   except ValueError as e:
来源：http://dali.tianlin.xyz/Article/details/gtuwvawcoi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.andypj.xyz/Article/details/gtgxsdoeau.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ydzc1.top/Article/details/gtzszddmho.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.quarkkingdee.top/Article/details/gtymsrmtyc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tanke756.top/Article/details/gtufzfdnqv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sysykeji.top/Article/details/gtbscwlqks.html

Ruby: rescue ArgumentError => e
来源：http://dali.svipenyu.cn/Article/details/gtirbfotvb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuxming.cn/Article/details/gteuudiahi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.daxiang520.top/Article/details/gtrfelocqv.html

Py:   value = d.get("k") or default
来源：http://dali.yueranfly.top/Article/details/gtqrxcmllb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.daria6918.cn/Article/details/gtfnkpsidz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gtahsjeicc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shzxlz.cn/Article/details/gtglqeeuex.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shuidangran.top/Article/details/gtljomxezx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yuanzhike.top/Article/details/gtoojiufij.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gotoacloud.top/Article/details/gtfywwyzdu.html

C#:   obj?.A?.B ?? default
来源：http://dali.dashuyun.cn/Article/details/gtqlgzznob.html

[H07] 断言
来源：http://dali.sweek.top/Article/details/gtpnfodakh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuanzx.com/Article/details/gtkolqfxsr.html

PHP:  assert($x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtluwavspn.html

JS:   console.assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtarydyukr.html

TS:   console.assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gtzfmhhxih.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtruqeijys.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yuanzhike.top/Article/details/gtgvhlwhjc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yangfankeji.com/Article/details/gtarqkdziy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gtqqhwotvy.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuetiantiany.cn/Article/details/gtsxaabnxf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xziqi.cn/Article/details/gtvmfoswgr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258.top/Article/details/gtqiulipiu.html

JS:   e.message;  e.stack
来源：http://dali.bjfxy.top/Article/details/gtqrnnanhr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.svipenyu.cn/Article/details/gtbtvkeinr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.haohaochexian.top/Article/details/gtzxpfhoya.html

Go:   err.Error()
来源：http://dali.quarkkingdee.top/Article/details/gttchntwbn.html

Ruby: e.message;  e.backtrace
来源：http://dali.andypj.xyz/Article/details/gtaamrjgnm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.pengpengdd.cyou/Article/details/gtzrbjalmj.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtnmergicj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangshuangyany.cn/Article/details/gtqwawiymq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenzaomai.com/Article/details/gtirpglusl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gaohongyu789.top/Article/details/gtsaotpwae.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gzhubu.top/Article/details/gtgizgspjg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinqigufen.top/Article/details/gtgytzlgcq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daria6918.cn/Article/details/gtlhzhxcbd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcchnkejn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.snrcjt.cn/Article/details/gtpbfhyicg.html

[H10] 资源自动释放
来源：http://dali.wangdashe.top/Article/details/gtjrazkcwe.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhiwuduotai.top/Article/details/gthllhiuch.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsjfzhpps.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnxiangtu.top/Article/details/gtssexsbua.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gotoacloud.top/Article/details/gtdnhawkgl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hywenlv.cn/Article/details/gtqhnmobym.html

Go:   defer f.Close()
来源：http://dali.smart0.xyz/Article/details/gtqcirgnhy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fzhhl.top/Article/details/gtjlbcdgjt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gthrrnqkwk.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtdgvngibq.html

I. 正则表达式
来源：http://dali.cqqwz.cn/Article/details/gtyljtkgah.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtzfuhdcfs.html

[I01] 判断是否匹配
来源：http://dali.meibo888.top/Article/details/gtfxzoqbdi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jianghu66.top/Article/details/gtzjufunrz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtfseudjgi.html

JS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gtlllnwulk.html

TS:   /\d+/.test(s)
来源：http://dali.birdmap.top/Article/details/gtvtzvxtli.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yongpay.top/Article/details/gtpnxbxict.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.0kj1m.cn/Article/details/gtnaivxweq.html

Ruby: s.match?(/\d+/)
来源：http://dali.sweek.top/Article/details/gtrpfzuiur.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yongpay.top/Article/details/gtxlqrfnwu.html

[I02] 提取所有匹配
来源：http://dali.chenlongwang.top/Article/details/gtfiveruhk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.haohaochexian.top/Article/details/gtpcmziyho.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jyoumei.cn/Article/details/gtvdczxnmt.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hnxiangtu.top/Article/details/gtubflqfge.html

TS:   s.match(/\d+/g)
来源：http://dali.svipenyu.cn/Article/details/gtyoyzmkor.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhongyouzk.top/Article/details/gtycczkfvu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.iojbl.cn/Article/details/gtkkulcloy.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpjawxoix.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ydzc1.top/Article/details/gtglqshpdd.html

[I03] 提取捕获分组
来源：http://dali.shzxlz.cn/Article/details/gtjjpyoxcc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jiagoushi.top/Article/details/gtuqnodwvu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.dashuyun.cn/Article/details/gttblztbuq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ivvv.top/Article/details/gtrphwgjby.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cqqwz.cn/Article/details/gtvvdsxngr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ybcxt.top/Article/details/gtbjykpcip.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.c1oappe.top/Article/details/gtksumngpc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xylfe.cn/Article/details/gtiacgepnc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.aizwys.cn/Article/details/gtcnrzguzf.html

[I04] 正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfazyyfov.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.wangshuangyany.cn/Article/details/gticyloyrj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gzhubu.top/Article/details/gtujmnkrkl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yueranfly.top/Article/details/gtqbvxsuya.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cashguo.top/Article/details/gtaiutspkn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cqqwz.cn/Article/details/gtvjrndauh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gzhubu.top/Article/details/gtuznpyguy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlshjhhdi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tian-w.cn/Article/details/gtnwropfws.html

[I05] 按正则拆分
来源：http://dali.zhengqikj.top/Article/details/gtzjmybmue.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gogol.net.cn/Article/details/gtjknvhtwb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ydzc1.top/Article/details/gtavreogsj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gtrtbehyqx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gtgachfhbd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenzaomai.com/Article/details/gtuvzzykzw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ivvv.top/Article/details/gtaqgqyhyp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gtrebnuaoi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yanxiufei.cn/Article/details/gtmrgrayfc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenzaomai.com/Article/details/gtneemwrjl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtizyewnos.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zdqjudy.top/Article/details/gtinglblgz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgufenzy.top/Article/details/gtuqalhaxm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.vqdsnc.cn/Article/details/gtykwrtasa.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gteogfgqbr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbgwrjij.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ehwqpu.com/Article/details/gtatcfcpvk.html


<!-- 参考信息 -->