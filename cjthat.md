代发 wailian999

[G02] 构造函数
来源：http://dali.yj202588.top/Article/details/gtitubhejw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.wangshuangyany.cn/Article/details/gtdukfwbsr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cheryme.top/Article/details/gthomyxgie.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgfzy.top/Article/details/gtyokzvufl.html

TS:   constructor(public name: string) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtndfektks.html

Java: User(String name) { this.name = name; }
来源：http://dali.c1oappe.top/Article/details/gtgukrmyvm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj202588.top/Article/details/gtqjyaivnt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yuxming.cn/Article/details/gtibpvhbgm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtxgqrxjpx.html

[G03] 实例属性
来源：http://dali.ybcxt.top/Article/details/gtsgxuvxab.html

Py:   self.name = "x"
来源：http://dali.jiagoushi.top/Article/details/gtacnjmizq.html

PHP:  public string $name = "x";
来源：http://dali.yj20258.top/Article/details/gtpbaoasyt.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gtjtlzwxln.html

TS:   name: string = "x";
来源：http://dali.yongpay.top/Article/details/gtsvdwvwtg.html

Java: private String name;
来源：http://dali.gogol.net.cn/Article/details/gtnigxajhy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zdqjudy.top/Article/details/gttwhpedsl.html

Ruby: @name = "x"
来源：http://dali.guannengcc.top/Article/details/gtrzxitynw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtszdwoafz.html

[G04] 定义方法
来源：http://dali.hfpthk.cn/Article/details/gttxzzrvbe.html

Py:   def greet(self): return self.name
来源：http://dali.tanke756.top/Article/details/gtsuyakrms.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gtteadexzw.html

JS:   greet() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gtlyeyhagt.html

TS:   greet(): string { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtehxzpacb.html

Java: String greet() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtoamwqqjf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gtgmhsjhod.html

Ruby: def greet; @name; end
来源：http://dali.yvedp.cn/Article/details/gttcfalqkx.html

C#:   public string Greet() => Name;
来源：http://dali.vqdsnc.cn/Article/details/gtwfayaahv.html

[G05] 继承
来源：http://dali.nanxinkj.top/Article/details/gtmrsawtti.html

Py:   class Admin(User): pass
来源：http://dali.guowangkeji.top/Article/details/gtaqnlkpwk.html

PHP:  class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtdjgkampz.html

JS:   class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtimoyayrz.html

TS:   class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtxbiqjzth.html

Java: class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtqdohdfos.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.9152youxi.cn/Article/details/gtuozvqlyn.html

Ruby: class Admin < User; end
来源：http://dali.smart0.xyz/Article/details/gtdwemhkas.html

C#:   class Admin : User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtbbavwvxz.html

[G06] 重写方法
来源：http://dali.yanxiufei.cn/Article/details/gtpetlrbem.html

Py:   def greet(self): return "admin"
来源：http://dali.ehwqpu.com/Article/details/gttmmaeokw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtuonlzxad.html

JS:   greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtzhqjqgno.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gtxptzjqkw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtsekkwcro.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangshuangyany.cn/Article/details/gtztzkuwyu.html

Ruby: def greet; "admin"; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtokjtqchk.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenzaomai.com/Article/details/gtojirxyjz.html

[G07] 调用父类方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtntziqgyg.html

Py:   super().greet()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejgtxzzd.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gtxrlzntur.html

JS:   super.greet();
来源：http://dali.dianchejie.cn/Article/details/gtjcymabce.html

TS:   super.greet();
来源：http://dali.xziqi.cn/Article/details/gtdyurufpf.html

Java: super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtavsourdg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zdqjudy.top/Article/details/gtnumbqvzq.html

Ruby: super
来源：http://dali.hywenlv.cn/Article/details/gtmmfnixsw.html

C#:   base.Greet();
来源：http://dali.cashguo.top/Article/details/gtmkafvfie.html

[G08] 静态方法与属性
来源：http://dali.iojbl.cn/Article/details/gtsirydokf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.svipenyu.cn/Article/details/gtlijlnvol.html

PHP:  public static function f() {}
来源：http://dali.dashuyun.cn/Article/details/gtddvlmyze.html

JS:   static f() {}
来源：http://dali.hnqzz.top/Article/details/gtoaeqlpwl.html

TS:   static f(): void {}
来源：http://dali.kuanghao11.cn/Article/details/gtqivfxeic.html

Java: static void f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtztzuyour.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.daxiang520.top/Article/details/gtopqjlxrc.html

Ruby: def self.f; end
来源：http://dali.dianchejie.cn/Article/details/gttuvixbbs.html

C#:   public static void F() {}
来源：http://dali.gotoacloud.top/Article/details/gtokpwvsbv.html

[G09] 接口 / 抽象类
来源：http://dali.gzhubu.top/Article/details/gttnafyhcd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.fzhhl.top/Article/details/gttaclxskg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxuanxn.top/Article/details/gtmbkvqjlk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shangyingyoupin.top/Article/details/gtumscfycl.html

TS:   interface Shape { area(): number; }
来源：http://dali.vqdsnc.cn/Article/details/gtavdfirua.html

Java: interface Shape { double area(); }
来源：http://dali.zycfv.cn/Article/details/gtyxoazzco.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxinkj.top/Article/details/gtjbzxnlqd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guannengcc.top/Article/details/gtpwlwvfxd.html

C#:   interface IShape { double Area(); }
来源：http://dali.hammf.cn/Article/details/gtbriafzld.html

[G10] 访问控制
来源：http://dali.pengpengdd.cyou/Article/details/gtbadsuxke.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cheryme.top/Article/details/gtqyyuyxbp.html

PHP:  public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gtiepyxsku.html

JS:   #private 字段；其余公开
来源：http://dali.redwolf501.top/Article/details/gtkhilnnbb.html

TS:   public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gtndgnrjti.html

Java: public / protected / private / 默认包级
来源：http://dali.cashguo.top/Article/details/gtqqkobejl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.snrcjt.cn/Article/details/gtbhpbwjpk.html

Ruby: public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtyqrlmutz.html

C#:   public / protected / private / internal
来源：http://dali.feifeiyinyue.top/Article/details/gtmdksxpcl.html

[G11] getter / setter
来源：http://dali.svipenyu.cn/Article/details/gtpoeesurq.html

Py:   @property 与 @x.setter
来源：http://dali.tianlin.xyz/Article/details/gtvwhuxtyj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gtagaawkoq.html

JS:   get name() { return this._name; }
来源：http://dali.nanxuanxn.top/Article/details/gtwxgprltm.html

TS:   get name(): string { return this._name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtlvbqofyh.html

Java: public String getName() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtimzcfgnc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gtpclecewj.html

Ruby: attr_accessor :name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwstdrrbv.html

C#:   public string Name { get; set; }
来源：http://dali.yvedp.cn/Article/details/gtbeimsywn.html

[G12] 对象转字符串
来源：http://dali.jqgfzy.top/Article/details/gtsedmayha.html

Py:   def __str__(self): return self.name
来源：http://dali.sysykeji.top/Article/details/gtbhqbpupf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtdxfrtapv.html

JS:   toString() { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtbqcgrwwr.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258.top/Article/details/gterxgwjyz.html

Java: @Override public String toString() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtzfkhmebp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqvisibb.html

Ruby: def to_s; @name; end
来源：http://dali.nanxuanxn.top/Article/details/gtoxzrzwnu.html

C#:   public override string ToString() => Name;
来源：http://dali.chenzaomai.com/Article/details/gtcjdbqhog.html

[G13] 判断对象类型
来源：http://dali.haohaochexian.top/Article/details/gtutlewxsl.html

Py:   isinstance(u, User)
来源：http://dali.wangdashe.top/Article/details/gtmfthdppn.html

PHP:  $u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtbgciasdh.html

JS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtmhjbmjse.html

TS:   u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtxxwhoezw.html

Java: u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtycmwpvnc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.vqdsnc.cn/Article/details/gtyfsrtypr.html

Ruby: u.is_a?(User)
来源：http://dali.yvedp.cn/Article/details/gtbxvxjadb.html

C#:   u is User
来源：http://dali.hnqzz.top/Article/details/gtymuhyqyf.html

[G14] 数据类 / record
来源：http://dali.haohaochexian.top/Article/details/gtwbnxaxox.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258888.top/Article/details/gtfzquqbgu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenjidiqi.icu/Article/details/gtecwgwlep.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuetiantiany.cn/Article/details/gtkbtmtuyq.html

TS:   type User = { name: string; age: number };
来源：http://dali.yanxiufei.cn/Article/details/gtfuzwcsfi.html

Java: record User(String name, int age) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtjomhydap.html

Go:   type User struct { Name string; Age int }
来源：http://dali.birdmap.top/Article/details/gtqohkstvy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yvedp.cn/Article/details/gtdzujyjnz.html

C#:   record User(string Name, int Age);
来源：http://dali.ppjwa.cn/Article/details/gtucyeqdvi.html

[G15] 枚举
来源：http://dali.jiagoushi.top/Article/details/gtawypvgef.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gtbnbmhkhv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvrbknzzz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zdqjudy.top/Article/details/gtjfhnweax.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.smart0.xyz/Article/details/gtkuxjqzwb.html

Java: enum Color { RED, GREEN }
来源：http://dali.gaohongyu789.top/Article/details/gtxflmwzvp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tianlin.xyz/Article/details/gtrfzzghpb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdarmuutn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.meibo888.top/Article/details/gtchnsgkxi.html

[G16] 对象转数组 / 字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gthhxltobm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.316326.xyz/Article/details/gtafudihzy.html

PHP:  get_object_vars($obj);
来源：http://dali.0kj1m.cn/Article/details/gtgxzfhvfm.html

JS:   Object.entries(obj)
来源：http://dali.yangfankeji.com/Article/details/gttrvnsvdx.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtdgxhaibo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zycfv.cn/Article/details/gtzmliduvh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.9152youxi.cn/Article/details/gtduxnhfwy.html

Ruby: obj.instance_variables
来源：http://dali.nanxuanxn.top/Article/details/gtjtizzzml.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guannengcc.top/Article/details/gtgrkvewua.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtzgazcwcr.html

H. 异常与错误处理
来源：http://dali.hysaishi.cn/Article/details/gtnbapfvxy.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtbovsgrhj.html

[H01] try / catch 基础
来源：http://dali.cqqwz.cn/Article/details/gtupflchws.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hammf.cn/Article/details/gtoswvphft.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cdnleiting.top/Article/details/gtcifleikf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gtrtpidgll.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ivvv.top/Article/details/gtigxvxuhe.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yongpay.top/Article/details/gtldjdrorx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtipvncimq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tian-w.cn/Article/details/gtdyxjlklg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gogol.net.cn/Article/details/gtittfcwsj.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigfzy.top/Article/details/gtikmjwzcz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ppjwa.cn/Article/details/gtbrmucrsw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gttfhmipue.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtkmqrgsnw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtawhokshb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gteipaeeny.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.fzhhl.top/Article/details/gtvedepzym.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.pengpengdd.cyou/Article/details/gtvqkrgmem.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtbjshszxj.html

[H03] 主动抛出异常
来源：http://dali.shangyingyoupin.top/Article/details/gtnbhszrfd.html

Py:   raise ValueError("错误信息")
来源：http://dali.redwolf501.top/Article/details/gtuivuyoxd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtlutnchsr.html

JS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtjzoaxgtu.html

TS:   throw new Error("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtymmjsijr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtaflgovwb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ppjwa.cn/Article/details/gtnwmherql.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sxryk.cn/Article/details/gtjowfcgnk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtmwxzlhtk.html

[H04] 自定义异常类型
来源：http://dali.redwolf501.top/Article/details/gtqxsndprr.html

Py:   class MyError(Exception): pass
来源：http://dali.tian-w.cn/Article/details/gtbtnqnvsb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gtjuhzdkhi.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmhopeiv.html

TS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gtnftsnpsx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ydzc1.top/Article/details/gtystnosah.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ehwqpu.com/Article/details/gtrzvpzdwb.html

Ruby: class MyError < StandardError; end
来源：http://dali.xuanzx.com/Article/details/gtfgatppja.html

C#:   class MyException : Exception {}
来源：http://dali.yangfankeji.com/Article/details/gtovxotccs.html

[H05] 捕获特定类型
来源：http://dali.yonumen.top/Article/details/gtgexfmuvh.html

Py:   except ValueError as e:
来源：http://dali.sxryk.cn/Article/details/gtgnlqrhug.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenjidiqi.icu/Article/details/gtrjtxavur.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hnqzz.top/Article/details/gtcxupguri.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gttljkxrqo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gotoacloud.top/Article/details/gtxbahjtad.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.snrcjt.cn/Article/details/gtsfuaakci.html

Ruby: rescue ArgumentError => e
来源：http://dali.aibaodan.cn/Article/details/gtghbwuche.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtvpvfeerf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sysykeji.top/Article/details/gtvsdyaavf.html

Py:   value = d.get("k") or default
来源：http://dali.cashguo.top/Article/details/gtxqlevbci.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.snrcjt.cn/Article/details/gtuwlumfeu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenzaomai.com/Article/details/gttxnkkfdt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgfzy.top/Article/details/gtstzavmzl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zycfv.cn/Article/details/gtafeamizk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cqqwz.cn/Article/details/gtmvkholao.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sxryk.cn/Article/details/gtlhupfrji.html

C#:   obj?.A?.B ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gtikndpcfn.html

[H07] 断言
来源：http://dali.ppjwa.cn/Article/details/gtdgzmzkna.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hysaishi.cn/Article/details/gtqwtabqeq.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtmkmebktb.html

JS:   console.assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gttznexytt.html

TS:   console.assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtpxyibfzz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shuidangran.top/Article/details/gtylszvnvy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinqigufen.top/Article/details/gtlijbpyfn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.guannengcc.top/Article/details/gtrnnldraj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dianchejie.cn/Article/details/gtevftkube.html

[H08] 获取错误信息与堆栈
来源：http://dali.guannengcc.top/Article/details/gtgvqnudxl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hnxiangtu.top/Article/details/gtghmlexit.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yuxming.cn/Article/details/gtjzxfdrpr.html

JS:   e.message;  e.stack
来源：http://dali.cashguo.top/Article/details/gtksgdyhjm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hysaishi.cn/Article/details/gtytectdqp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cheryme.top/Article/details/gtoaimjhxt.html

Go:   err.Error()
来源：http://dali.meibo888.top/Article/details/gtnqjxihtl.html

Ruby: e.message;  e.backtrace
来源：http://dali.316326.xyz/Article/details/gtygcmccfq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jqgufenzy.top/Article/details/gtcqofdrno.html

[H09] 带错误码的异常
来源：http://dali.zhoulong.xyz/Article/details/gtkumhzqkc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.fzhhl.top/Article/details/gtcseplkcf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.c1oappe.top/Article/details/gtvapsuxqz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukcqjktx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xinyue.icu/Article/details/gtzacxliac.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sxryk.cn/Article/details/gtewypydkz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gzhubu.top/Article/details/gtdkoqyryg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xuetiantiany.cn/Article/details/gtllwaifqy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.haohaochexian.top/Article/details/gtcfnudpqx.html

[H10] 资源自动释放
来源：http://dali.jqgufenzy.top/Article/details/gtylospaba.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.meibo888.top/Article/details/gtnktuvfow.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.mhx1999.top/Article/details/gtyntqxhiq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.smart0.xyz/Article/details/gtnradedim.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gtcxkttdqu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shzxlz.cn/Article/details/gtygvgrbwa.html

Go:   defer f.Close()
来源：http://dali.gotoacloud.top/Article/details/gtxjicxduo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cucudq.cn/Article/details/gtnycblnbf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtrirzcevw.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtvjsczyrf.html

I. 正则表达式
来源：http://dali.hnqzz.top/Article/details/gtsykogmov.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtonbjumgq.html

[I01] 判断是否匹配
来源：http://dali.0kj1m.cn/Article/details/gtykabtrnm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sysykeji.top/Article/details/gtntfiruam.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ybcxt.top/Article/details/gtwxxupeak.html

JS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gthxywemzc.html

TS:   /\d+/.test(s)
来源：http://dali.vqdsnc.cn/Article/details/gtrpdlslwn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.mhx1999.top/Article/details/gtaxbvluma.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daxiang520.top/Article/details/gtpdbouofw.html

Ruby: s.match?(/\d+/)
来源：http://dali.shuidangran.top/Article/details/gtpzqdonkw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuxming.cn/Article/details/gtykeufgne.html

[I02] 提取所有匹配
来源：http://dali.shzxlz.cn/Article/details/gtobnpscla.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigufen.top/Article/details/gtmluotgpy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yuanzhike.top/Article/details/gtycppwnag.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cucudq.cn/Article/details/gtcqzmyomx.html

TS:   s.match(/\d+/g)
来源：http://dali.hysaishi.cn/Article/details/gtjejiryez.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jqgfzy.top/Article/details/gtxmyzjfea.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yongpay.top/Article/details/gtkmuzxaqy.html

Ruby: s.scan(/\d+/)
来源：http://dali.fzhhl.top/Article/details/gtdtkzboie.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sweek.top/Article/details/gtnlpdqmuz.html

[I03] 提取捕获分组
来源：http://dali.fengsongda.top/Article/details/gtzbcwcyof.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.c1oappe.top/Article/details/gtodrmcvgd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.316326.xyz/Article/details/gtyremgsqz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cdnleiting.top/Article/details/gtzukjvvzs.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.guowangkeji.top/Article/details/gtxdhnkdld.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sysykeji.top/Article/details/gtkgdluigj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cashguo.top/Article/details/gtsqgraywv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgzslwfnt.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fengsongda.top/Article/details/gtugeyactv.html

[I04] 正则替换
来源：http://dali.hammf.cn/Article/details/gtmenktuhx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gaohongyu789.top/Article/details/gttrvttnbd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yangfankeji.com/Article/details/gtkpxfmafz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.daria6918.cn/Article/details/gtdueghvyl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnnustch.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xuanzx.com/Article/details/gtmztthhds.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj20258.top/Article/details/gtpusrcspu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.pycfn.com/Article/details/gtdkcxcvdq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gtksjdigrb.html

[I05] 按正则拆分
来源：http://dali.iojbl.cn/Article/details/gthixsekhc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.redwolf501.top/Article/details/gtgajydhua.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtutruqffx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtkmtzzinp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gtbgsrnbtl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.kuanghao11.cn/Article/details/gttdggbjfr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gtpwnvrasn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvnnfbxmh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjfammmup.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhongyouzk.top/Article/details/gtcrbpxjdv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gtollivtgd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.dashuyun.cn/Article/details/gtlupwrgqf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.svipenyu.cn/Article/details/gtjsqmobdo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenzaomai.com/Article/details/gtkluziudf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gteppqtttn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ehwqpu.com/Article/details/gtkpfqlwxo.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sweek.top/Article/details/gtpzmeumpn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gtrmmxhfpn.html

[I07] 忽略大小写与多行模式
来源：http://dali.316326.xyz/Article/details/gtlgpsponi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xylfe.cn/Article/details/gtqccvqkbq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhoulong.xyz/Article/details/gtbhtfzatn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nanxuanxn.top/Article/details/gtvqddevwr.html

TS:   /error/gim
来源：http://dali.feifeiyinyue.top/Article/details/gtvbyfdjko.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nanxinkj.top/Article/details/gttnckzfqi.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tanke756.top/Article/details/gtucajsrwx.html

Ruby: s.scan(/error/i)
来源：http://dali.quarkkingdee.top/Article/details/gtpraslzuf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xylfe.cn/Article/details/gtrqwagvsu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.316326.xyz/Article/details/gtlknntlrn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jiagoushi.top/Article/details/gtsgizabbn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxinkj.top/Article/details/gtuvasktes.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sufxvd.cn/Article/details/gtbkaxymdb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258888.top/Article/details/gtayiqpaqd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.dashuyun.cn/Article/details/gtwfmxanxr.html


<!-- 参考信息 -->