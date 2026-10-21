代发 wailian999

Java: class User {}
来源：http://dali.birdmap.top/Article/details/gtoslaukdp.html

Go:   type User struct { Name string }
来源：http://dali.chenlongwang.top/Article/details/gtehgokwly.html

Ruby: class User; end
来源：http://dali.hnqzz.top/Article/details/gtxhwhiidb.html

C#:   class User {}
来源：http://dali.daxiang520.top/Article/details/gtnsjzwlxf.html

[G02] 构造函数
来源：http://dali.jlsjyb.cn/Article/details/gtcsjvnjuc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinqigfzy.top/Article/details/gtyztqwste.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tian-w.cn/Article/details/gtfknsrjwr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tanke756.top/Article/details/gtdowtweuy.html

TS:   constructor(public name: string) {}
来源：http://dali.ybcxt.top/Article/details/gtkiocuvqo.html

Java: User(String name) { this.name = name; }
来源：http://dali.hfpthk.cn/Article/details/gtyszcplvq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfdtjqxfc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sysykeji.top/Article/details/gtlgfdihup.html

C#:   public User(string name) { Name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtmtgmuznz.html

[G03] 实例属性
来源：http://dali.yuanzhike.top/Article/details/gtldybjzzi.html

Py:   self.name = "x"
来源：http://dali.yuanzhike.top/Article/details/gtyhqokplm.html

PHP:  public string $name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtwqvtyffs.html

JS:   this.name = "x";
来源：http://dali.guannengcc.top/Article/details/gtkiivvvts.html

TS:   name: string = "x";
来源：http://dali.jqgufenzy.top/Article/details/gthcmhxguz.html

Java: private String name;
来源：http://dali.nwbrower.top/Article/details/gtvyhtunbe.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgfzy.top/Article/details/gtckpbpdkm.html

Ruby: @name = "x"
来源：http://dali.hywenlv.cn/Article/details/gtpdhfhdiq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigufen.top/Article/details/gtjdhlgwqb.html

[G04] 定义方法
来源：http://dali.quarkkingdee.top/Article/details/gtpdotbfee.html

Py:   def greet(self): return self.name
来源：http://dali.haohaochexian.top/Article/details/gtelqexvou.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gtansxdobi.html

JS:   greet() { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtknkddlcc.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gttrlplqdn.html

Java: String greet() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtcecqoaom.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gtwxzhrxvb.html

Ruby: def greet; @name; end
来源：http://dali.zdqjudy.top/Article/details/gtxwydgjfc.html

C#:   public string Greet() => Name;
来源：http://dali.bjfxy.top/Article/details/gtcwfadith.html

[G05] 继承
来源：http://dali.zhengqikj.top/Article/details/gthoeqofpa.html

Py:   class Admin(User): pass
来源：http://dali.nanxuanxn.top/Article/details/gtabfiouto.html

PHP:  class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtsmaorjyt.html

JS:   class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gtxqkabgov.html

TS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtosladnbr.html

Java: class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtldsznkum.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xziqi.cn/Article/details/gtihuxtszl.html

Ruby: class Admin < User; end
来源：http://dali.hnqzz.top/Article/details/gtlpaodubf.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gtrsapaxzq.html

[G06] 重写方法
来源：http://dali.smart0.xyz/Article/details/gtxbahvalo.html

Py:   def greet(self): return "admin"
来源：http://dali.mhx1999.top/Article/details/gtdbfrrzgi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtjbclcypq.html

JS:   greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtfvfmaoqq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtppyrnmuo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkfycgegk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nwbrower.top/Article/details/gtcndxbqae.html

Ruby: def greet; "admin"; end
来源：http://dali.jiagoushi.top/Article/details/gtququhmwu.html

C#:   public override string Greet() => "admin";
来源：http://dali.tian-w.cn/Article/details/gtybrxihsl.html

[G07] 调用父类方法
来源：http://dali.jinqigfzy.top/Article/details/gtgymfubwk.html

Py:   super().greet()
来源：http://dali.shuidangran.top/Article/details/gtiwmomopl.html

PHP:  parent::greet();
来源：http://dali.pycfn.com/Article/details/gtkrhrantq.html

JS:   super.greet();
来源：http://dali.c1oappe.top/Article/details/gtpblzmkfz.html

TS:   super.greet();
来源：http://dali.yuxming.cn/Article/details/gtcxtslxmw.html

Java: super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtequuapno.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenlongwang.top/Article/details/gtaelpfrvx.html

Ruby: super
来源：http://dali.yangfankeji.com/Article/details/gtdymfcwld.html

C#:   base.Greet();
来源：http://dali.ydzc1.top/Article/details/gtgzumejox.html

[G08] 静态方法与属性
来源：http://dali.zhongyouzk.top/Article/details/gtvgwzopxk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.redwolf501.top/Article/details/gtllozkomq.html

PHP:  public static function f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtfhmokrbc.html

JS:   static f() {}
来源：http://dali.yj20258.top/Article/details/gtlvpecvom.html

TS:   static f(): void {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzllnjjn.html

Java: static void f() {}
来源：http://dali.aibaodan.cn/Article/details/gtgsjthzba.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gogol.net.cn/Article/details/gteysltgyy.html

Ruby: def self.f; end
来源：http://dali.svipenyu.cn/Article/details/gtruiwzzpx.html

C#:   public static void F() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtkclczfwp.html

[G09] 接口 / 抽象类
来源：http://dali.wangdashe.top/Article/details/gtavhaskyc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sysykeji.top/Article/details/gtzvfghrvb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.svipenyu.cn/Article/details/gttrwldeoi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yueranfly.top/Article/details/gtjgtubjez.html

TS:   interface Shape { area(): number; }
来源：http://dali.yuanzhike.top/Article/details/gtpuxmboyk.html

Java: interface Shape { double area(); }
来源：http://dali.shzxlz.cn/Article/details/gtmaywedlv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.kuanghao11.cn/Article/details/gtqnwhdjsk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.smart0.xyz/Article/details/gtdgzwpomj.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhixingplan.top/Article/details/gtoygexsce.html

[G10] 访问控制
来源：http://dali.c1oappe.top/Article/details/gtkcadcaap.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nwbrower.top/Article/details/gttlnxxqry.html

PHP:  public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjsxyrcsz.html

JS:   #private 字段；其余公开
来源：http://dali.tian-w.cn/Article/details/gtkrhhmntm.html

TS:   public / protected / private
来源：http://dali.daxiang520.top/Article/details/gtrfcxepbg.html

Java: public / protected / private / 默认包级
来源：http://dali.shangyingyoupin.top/Article/details/gtxjyjjnol.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhongyouzk.top/Article/details/gtcwllbvzs.html

Ruby: public / protected / private
来源：http://dali.smart0.xyz/Article/details/gthygybfyo.html

C#:   public / protected / private / internal
来源：http://dali.chenzaomai.com/Article/details/gthvrnbaod.html

[G11] getter / setter
来源：http://dali.ywan-chungtsiang.top/Article/details/gtciodwlxb.html

Py:   @property 与 @x.setter
来源：http://dali.hysaishi.cn/Article/details/gtvulypxrf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gtwocwncbg.html

JS:   get name() { return this._name; }
来源：http://dali.gotoacloud.top/Article/details/gtbdghnxdx.html

TS:   get name(): string { return this._name; }
来源：http://dali.ehwqpu.com/Article/details/gtepxgxsgf.html

Java: public String getName() { return name; }
来源：http://dali.xylfe.cn/Article/details/gtumsesezo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gtsfjicqae.html

Ruby: attr_accessor :name
来源：http://dali.jlsjyb.cn/Article/details/gtnfnqlzuy.html

C#:   public string Name { get; set; }
来源：http://dali.c1oappe.top/Article/details/gtmajcochc.html

[G12] 对象转字符串
来源：http://dali.tian-w.cn/Article/details/gtorhxrxvx.html

Py:   def __str__(self): return self.name
来源：http://dali.meibo888.top/Article/details/gtlpvglait.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtkginemlx.html

JS:   toString() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtsxasqjsi.html

TS:   toString(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtxtvtwuat.html

Java: @Override public String toString() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtfoafmpzt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gtxpcztabs.html

Ruby: def to_s; @name; end
来源：http://dali.chenlongwang.top/Article/details/gthwxldfpp.html

C#:   public override string ToString() => Name;
来源：http://dali.tianlin.xyz/Article/details/gtzqiajofg.html

[G13] 判断对象类型
来源：http://dali.aibaodan.cn/Article/details/gtbtqrtbuu.html

Py:   isinstance(u, User)
来源：http://dali.smart0.xyz/Article/details/gtwbsqpmgh.html

PHP:  $u instanceof User
来源：http://dali.birdmap.top/Article/details/gtwtnhzocv.html

JS:   u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtksfbvciq.html

TS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtuzgbynmh.html

Java: u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gttxbqeebl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.kuanghao11.cn/Article/details/gtfhcrrcbd.html

Ruby: u.is_a?(User)
来源：http://dali.hammf.cn/Article/details/gtyrawbrbj.html

C#:   u is User
来源：http://dali.jyoumei.cn/Article/details/gtqlcvpzzi.html

[G14] 数据类 / record
来源：http://dali.xziqi.cn/Article/details/gtwgrqrutw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gzhubu.top/Article/details/gtwgiybvuv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tianlin.xyz/Article/details/gtgtozwkec.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhiwuduotai.top/Article/details/gtzmlxzigk.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycdgpntg.html

Java: record User(String name, int age) {}
来源：http://dali.yanxiufei.cn/Article/details/gtchxxtebd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dianchejie.cn/Article/details/gtnqybsqcx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ppjwa.cn/Article/details/gtnvozdkis.html

C#:   record User(string Name, int Age);
来源：http://dali.feifeiyinyue.top/Article/details/gtanprmjhx.html

[G15] 枚举
来源：http://dali.sxryk.cn/Article/details/gtzureqntz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gotoacloud.top/Article/details/gtummdptgc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.birdmap.top/Article/details/gtmbjqsuki.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jqgufenzy.top/Article/details/gtdrcwhtvx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtwyvazyas.html

Java: enum Color { RED, GREEN }
来源：http://dali.feifeiyinyue.top/Article/details/gttwuzeysy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenlongwang.top/Article/details/gtqtlreohu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.bjfxy.top/Article/details/gtxdpiqfry.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtxbrtfykm.html

[G16] 对象转数组 / 字典
来源：http://dali.zycfv.cn/Article/details/gtefsoriyp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sweek.top/Article/details/gtxccejzmv.html

PHP:  get_object_vars($obj);
来源：http://dali.gaohongyu789.top/Article/details/gtnighrylq.html

JS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnfrvaivj.html

TS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gttxxyubpr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.guowangkeji.top/Article/details/gtrcxubvti.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.bjfxy.top/Article/details/gtkhubshlf.html

Ruby: obj.instance_variables
来源：http://dali.dianchejie.cn/Article/details/gtjksgmnzq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zdqjudy.top/Article/details/gtqbzlqwvo.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtagsetmvt.html

H. 异常与错误处理
来源：http://dali.jiagoushi.top/Article/details/gtmiwvxgjc.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtygdccljg.html

[H01] try / catch 基础
来源：http://dali.smart0.xyz/Article/details/gtcxhmeoxz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnduhibel.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.quarkkingdee.top/Article/details/gtqcyliocn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gtzvmawhyn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gtyqszrett.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.0kj1m.cn/Article/details/gthwclibcy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.quarkkingdee.top/Article/details/gtxkfysucj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zdqjudy.top/Article/details/gtbiabzevb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hywenlv.cn/Article/details/gtbclbumas.html

[H02] finally / ensure 收尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrvlxxrtu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhengqikj.top/Article/details/gtteorsnus.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gtjqmwhdan.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtjzelvoal.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtlvdqsrvn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkjaeirtx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sweek.top/Article/details/gtheecwprr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aizwys.cn/Article/details/gtppunkeyo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtndaaotje.html

[H03] 主动抛出异常
来源：http://dali.daria6918.cn/Article/details/gtmccfqfrb.html

Py:   raise ValueError("错误信息")
来源：http://dali.zdqjudy.top/Article/details/gtapemyrav.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpyivppfc.html

JS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtyxggxsxm.html

TS:   throw new Error("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtyhfsbubs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gtlbpgjrxo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yongpay.top/Article/details/gtlfpeqcxw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinghuilouyu.cn/Article/details/gtewuemvqw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtdpupltsk.html

[H04] 自定义异常类型
来源：http://dali.chenlongwang.top/Article/details/gtkvmwwfer.html

Py:   class MyError(Exception): pass
来源：http://dali.aibaodan.cn/Article/details/gtsqzbhhip.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gtettpnadx.html

JS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gtqzgyrgip.html

TS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gtmvollgor.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenzaomai.com/Article/details/gtptcgjffb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pycfn.com/Article/details/gtrqmrcypu.html

Ruby: class MyError < StandardError; end
来源：http://dali.quarkkingdee.top/Article/details/gteuxgbzpz.html

C#:   class MyException : Exception {}
来源：http://dali.yvedp.cn/Article/details/gtkwkxpmen.html

[H05] 捕获特定类型
来源：http://dali.aizwys.cn/Article/details/gtizsiaoqb.html

Py:   except ValueError as e:
来源：http://dali.tanke756.top/Article/details/gtcyxqbjbz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tanke756.top/Article/details/gtkvpvumzb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtafpknueq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.0kj1m.cn/Article/details/gtfryzodmy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tanke756.top/Article/details/gtcjektkkx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxinkj.top/Article/details/gtjryqvzcw.html

Ruby: rescue ArgumentError => e
来源：http://dali.hywenlv.cn/Article/details/gtqwhwvwfs.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tian-w.cn/Article/details/gtixjehclb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinghuilouyu.cn/Article/details/gthuyksbfr.html

Py:   value = d.get("k") or default
来源：http://dali.ppjwa.cn/Article/details/gtufchoktw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tian-w.cn/Article/details/gtfdpkjwhm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gtwqkbbejd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfyoxepd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhiwuduotai.top/Article/details/gtclgesxyo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nwbrower.top/Article/details/gtydrlhwtd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.haohaochexian.top/Article/details/gtuqvubxjn.html

C#:   obj?.A?.B ?? default
来源：http://dali.xylfe.cn/Article/details/gtdjdvnbja.html

[H07] 断言
来源：http://dali.jinqigfzy.top/Article/details/gtcxuqnylu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yanxiufei.cn/Article/details/gtkffxsemi.html

PHP:  assert($x > 0);
来源：http://dali.tian-w.cn/Article/details/gtgtidgqhv.html

JS:   console.assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcztzqjnc.html

TS:   console.assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gtpnamqmea.html

Java: assert x > 0 : "必须为正";
来源：http://dali.fengsongda.top/Article/details/gtynikiaex.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jqgufenzy.top/Article/details/gtpltbbuwu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinghuilouyu.cn/Article/details/gtpfgxcnxq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtpcbralaf.html

[H08] 获取错误信息与堆栈
来源：http://dali.yueranfly.top/Article/details/gtbxdnxvat.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cheryme.top/Article/details/gtwllysyrc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nanxuanxn.top/Article/details/gtectmhcjy.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgazqack.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnzzgjthv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.guowangkeji.top/Article/details/gtomylaizx.html

Go:   err.Error()
来源：http://dali.shangyingyoupin.top/Article/details/gtlgmufcpq.html

Ruby: e.message;  e.backtrace
来源：http://dali.zycfv.cn/Article/details/gthhiwjrvk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenlongwang.top/Article/details/gtrjuxloew.html

[H09] 带错误码的异常
来源：http://dali.pengpengdd.cyou/Article/details/gtyatesrgj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinqigufen.top/Article/details/gtllsjqcmy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dianchejie.cn/Article/details/gtcosoukpz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.dashuyun.cn/Article/details/gtogsrzvvi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zdqjudy.top/Article/details/gtgzovlllt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpeujvxvx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xuanzx.com/Article/details/gtxjhfdciu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.aibaodan.cn/Article/details/gtahfbtnig.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.daria6918.cn/Article/details/gtlqdinebh.html

[H10] 资源自动释放
来源：http://dali.ydzc1.top/Article/details/gtnjefvuih.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yuanzhike.top/Article/details/gtgicboqie.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jqgufenzy.top/Article/details/gtprunwgcl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.havefunace.top/Article/details/gtjgctagwr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.c1oappe.top/Article/details/gtqreifcvz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.meibo888.top/Article/details/gtvsgfunch.html

Go:   defer f.Close()
来源：http://dali.yj202588.top/Article/details/gtyfuunyvo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.andypj.xyz/Article/details/gttuerfqcu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtjbjsndxy.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtzjhodhbe.html

I. 正则表达式
来源：http://dali.andypj.xyz/Article/details/gtzggvpjai.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gttjjmysia.html

[I01] 判断是否匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtfmapeayj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.guowangkeji.top/Article/details/gtslqwxcva.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cheryme.top/Article/details/gtbrfcpadr.html

JS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gtwtrcunzf.html

TS:   /\d+/.test(s)
来源：http://dali.yangfankeji.com/Article/details/gtxveinqlz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yanxiufei.cn/Article/details/gtinammhbr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nanxuanxn.top/Article/details/gtqjekguoh.html

Ruby: s.match?(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gtwdczawbg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmainmdyk.html

[I02] 提取所有匹配
来源：http://dali.wangshuangyany.cn/Article/details/gteenpdzbv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jianghu66.top/Article/details/gtctkagima.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.birdmap.top/Article/details/gtnqmbrqxb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xinyue.icu/Article/details/gttcsmgoiz.html

TS:   s.match(/\d+/g)
来源：http://dali.tanke756.top/Article/details/gtxkkjdzsu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yongpay.top/Article/details/gtkfvktfoo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jianghu66.top/Article/details/gtubidekjp.html

Ruby: s.scan(/\d+/)
来源：http://dali.hammf.cn/Article/details/gtyyrprzei.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gotoacloud.top/Article/details/gtffxzbgeu.html

[I03] 提取捕获分组
来源：http://dali.cucudq.cn/Article/details/gtalqakyms.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shzxlz.cn/Article/details/gtehldoqbw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtvlclkqmz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hfpthk.cn/Article/details/gtvopfdspv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.smart0.xyz/Article/details/gtwclnzgjx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zdqjudy.top/Article/details/gtocrrxval.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.iojbl.cn/Article/details/gteuvzcyfb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.birdmap.top/Article/details/gtibvqgseg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fzhhl.top/Article/details/gtpknxphyz.html

[I04] 正则替换
来源：http://dali.jlsjyb.cn/Article/details/gtyvukufbu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinqigfzy.top/Article/details/gtnjxiduci.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtyeknncok.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sxryk.cn/Article/details/gtmwviliwh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.pycfn.com/Article/details/gtjkalqcbz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gotoacloud.top/Article/details/gtgyuqmfju.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinqigufen.top/Article/details/gthaguitnz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtfrnmxocd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hammf.cn/Article/details/gtgbjxukul.html

[I05] 按正则拆分
来源：http://dali.cqqwz.cn/Article/details/gtvokceadt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhixingplan.top/Article/details/gtdvnyqeqt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gogol.net.cn/Article/details/gtgmhbgmsm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gtuytlfptl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gtzrmalvqe.html

Java: s.split("\\s*,\\s*")
来源：http://dali.c1oappe.top/Article/details/gtobyffqpb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhiwuduotai.top/Article/details/gtvziqluvm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gtdpolisda.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yuxming.cn/Article/details/gtenmgqkzx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hfpthk.cn/Article/details/gtbpjorvpc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gtjrgsydbr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.dashuyun.cn/Article/details/gtykpiizzx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ppjwa.cn/Article/details/gtjffagyjm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gtvgcghtqy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gthoiggchr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.daxiang520.top/Article/details/gtgxluenhb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gtzzvhvsdw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gtwkhubhqr.html

[I07] 忽略大小写与多行模式
来源：http://dali.guannengcc.top/Article/details/gtpeznaodb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yuxming.cn/Article/details/gtdinnnymd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ppjwa.cn/Article/details/gtvzunrmqm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gogol.net.cn/Article/details/gtlfpwjvvc.html

TS:   /error/gim
来源：http://dali.zhongyouzk.top/Article/details/gtqhqroddq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xuanzx.com/Article/details/gtmpvfifku.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hfpthk.cn/Article/details/gtqqsmsnaw.html

Ruby: s.scan(/error/i)
来源：http://dali.sweek.top/Article/details/gtnnqrhgkg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shanyushiyangtech.top/Article/details/gtoftitefi.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.feifeiyinyue.top/Article/details/gthbcvxozi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cdnleiting.top/Article/details/gtwstnjpvr.html


<!-- 参考信息 -->