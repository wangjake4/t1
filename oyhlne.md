代发 wailian999

Py:   class User: pass
来源：http://dali.hfpthk.cn/Article/details/gtvkionpfd.html

PHP:  class User {}
来源：http://dali.9152youxi.cn/Article/details/gtlslbmpwy.html

JS:   class User {}
来源：http://dali.cashguo.top/Article/details/gtajmvxilj.html

TS:   class User { name: string = ""; }
来源：http://dali.feifeiyinyue.top/Article/details/gtzgiehfsa.html

Java: class User {}
来源：http://dali.xylfe.cn/Article/details/gtidqjcybq.html

Go:   type User struct { Name string }
来源：http://dali.c1oappe.top/Article/details/gtvtmnaocy.html

Ruby: class User; end
来源：http://dali.shangyingyoupin.top/Article/details/gtnudlhwug.html

C#:   class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtyqougulq.html

[G02] 构造函数
来源：http://dali.yangfankeji.com/Article/details/gtqkyhmezw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hnqzz.top/Article/details/gtrfbcgqrj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nanxinkj.top/Article/details/gtmbmbopyl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gtzjetaxve.html

TS:   constructor(public name: string) {}
来源：http://dali.zhengqikj.top/Article/details/gtrwuqlhel.html

Java: User(String name) { this.name = name; }
来源：http://dali.9152youxi.cn/Article/details/gtawcaihvq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yonumen.top/Article/details/gtztbpdied.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhoulong.xyz/Article/details/gtfehmhihb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dashuyun.cn/Article/details/gtedeqsguw.html

[G03] 实例属性
来源：http://dali.quarkkingdee.top/Article/details/gtdkwyzzif.html

Py:   self.name = "x"
来源：http://dali.vqdsnc.cn/Article/details/gtgfhxhppz.html

PHP:  public string $name = "x";
来源：http://dali.yangfankeji.com/Article/details/gtcjwazkqh.html

JS:   this.name = "x";
来源：http://dali.cqqwz.cn/Article/details/gtsbzwghhi.html

TS:   name: string = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtqfwywlsl.html

Java: private String name;
来源：http://dali.daxiang520.top/Article/details/gtkmmmemfo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tian-w.cn/Article/details/gtuvnfpvog.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gtduvjzupq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj20258888.top/Article/details/gtynygwzda.html

[G04] 定义方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaclnpjes.html

Py:   def greet(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gtytrnshxt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gtkairwooz.html

JS:   greet() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtvtwvdcip.html

TS:   greet(): string { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtaqyjbtyh.html

Java: String greet() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gtmjggzygp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gtntjoqfsr.html

Ruby: def greet; @name; end
来源：http://dali.yonumen.top/Article/details/gtwocznxzb.html

C#:   public string Greet() => Name;
来源：http://dali.gotoacloud.top/Article/details/gtuuhqpuzy.html

[G05] 继承
来源：http://dali.xylfe.cn/Article/details/gtfhcjctzx.html

Py:   class Admin(User): pass
来源：http://dali.fzhhl.top/Article/details/gtqzjnkgyv.html

PHP:  class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtrktuowfz.html

JS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjbpijtgb.html

TS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtyrawsocv.html

Java: class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gthgihrvvq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hammf.cn/Article/details/gtkrfluhyf.html

Ruby: class Admin < User; end
来源：http://dali.fzhhl.top/Article/details/gtruuxfnaf.html

C#:   class Admin : User {}
来源：http://dali.havefunace.top/Article/details/gtggzdrjuc.html

[G06] 重写方法
来源：http://dali.gzhubu.top/Article/details/gtoglngcrg.html

Py:   def greet(self): return "admin"
来源：http://dali.cucudq.cn/Article/details/gtfnamkwbp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtoiusivye.html

JS:   greet() { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtjerdreda.html

TS:   greet(): string { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtbifbfyhw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtmceknrda.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hongshengwenyu.top/Article/details/gtihukkpbe.html

Ruby: def greet; "admin"; end
来源：http://dali.nanxuanxn.top/Article/details/gtwlxukqff.html

C#:   public override string Greet() => "admin";
来源：http://dali.sweek.top/Article/details/gtrljsyetw.html

[G07] 调用父类方法
来源：http://dali.zdqjudy.top/Article/details/gtxxhqsiac.html

Py:   super().greet()
来源：http://dali.ppjwa.cn/Article/details/gtdidlajsx.html

PHP:  parent::greet();
来源：http://dali.cheryme.top/Article/details/gtqnjjpvjx.html

JS:   super.greet();
来源：http://dali.ydzc1.top/Article/details/gtcqvkktwh.html

TS:   super.greet();
来源：http://dali.ppjwa.cn/Article/details/gtujuyjxqw.html

Java: super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtcwloongc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.haohaochexian.top/Article/details/gtcdavqujg.html

Ruby: super
来源：http://dali.sufxvd.cn/Article/details/gtwggzgfvk.html

C#:   base.Greet();
来源：http://dali.tianlin.xyz/Article/details/gtbwdhidri.html

[G08] 静态方法与属性
来源：http://dali.ehwqpu.com/Article/details/gtczvrjckn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gogol.net.cn/Article/details/gtxajtcmyd.html

PHP:  public static function f() {}
来源：http://dali.nanxinkj.top/Article/details/gtofeeshoc.html

JS:   static f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtwijbwatt.html

TS:   static f(): void {}
来源：http://dali.tanke756.top/Article/details/gtfyaspnif.html

Java: static void f() {}
来源：http://dali.yj20258888.top/Article/details/gtllgruxhj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jqgufenzy.top/Article/details/gtvchfwhwz.html

Ruby: def self.f; end
来源：http://dali.mhx1999.top/Article/details/gtgsnxknso.html

C#:   public static void F() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfjpsxjef.html

[G09] 接口 / 抽象类
来源：http://dali.pengpengdd.cyou/Article/details/gtdfebbusy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shzxlz.cn/Article/details/gtykdxnsgv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.meibo888.top/Article/details/gttyzgpnxv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhengqikj.top/Article/details/gtohdsapsz.html

TS:   interface Shape { area(): number; }
来源：http://dali.aizwys.cn/Article/details/gtntpxuauq.html

Java: interface Shape { double area(); }
来源：http://dali.hammf.cn/Article/details/gtxomrfqbo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cucudq.cn/Article/details/gtlmwgmbuv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tanke756.top/Article/details/gtkgctyska.html

C#:   interface IShape { double Area(); }
来源：http://dali.xylfe.cn/Article/details/gtnbowqdii.html

[G10] 访问控制
来源：http://dali.xuetiantiany.cn/Article/details/gthcqjzkcc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jqgfzy.top/Article/details/gtbazelteu.html

PHP:  public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gtldxbwedg.html

JS:   #private 字段；其余公开
来源：http://dali.havefunace.top/Article/details/gtquoqypor.html

TS:   public / protected / private
来源：http://dali.yj202588.top/Article/details/gthjxmykdr.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangkeji.top/Article/details/gtglnzpwif.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yuanzhike.top/Article/details/gtvdumpftc.html

Ruby: public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtgrmjoiat.html

C#:   public / protected / private / internal
来源：http://dali.chenzaomai.com/Article/details/gtkkgyxhzr.html

[G11] getter / setter
来源：http://dali.gogol.net.cn/Article/details/gtmpykpyig.html

Py:   @property 与 @x.setter
来源：http://dali.hnxiangtu.top/Article/details/gtfmamcvdo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.daxiang520.top/Article/details/gttigijugq.html

JS:   get name() { return this._name; }
来源：http://dali.0kj1m.cn/Article/details/gtkfzzrbwl.html

TS:   get name(): string { return this._name; }
来源：http://dali.hongshengwenyu.top/Article/details/gteogsuyfs.html

Java: public String getName() { return name; }
来源：http://dali.daria6918.cn/Article/details/gtoueetqcp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gtwdctqhen.html

Ruby: attr_accessor :name
来源：http://dali.dianchejie.cn/Article/details/gtxgplorog.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpdfwlpqa.html

[G12] 对象转字符串
来源：http://dali.yj20258.top/Article/details/gtozpihikp.html

Py:   def __str__(self): return self.name
来源：http://dali.jinqigfzy.top/Article/details/gtabvttpfl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gtcpywlefg.html

JS:   toString() { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtevgewzzu.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258.top/Article/details/gtsaajtael.html

Java: @Override public String toString() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtmrztagcr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gtwdqcztwk.html

Ruby: def to_s; @name; end
来源：http://dali.fzhhl.top/Article/details/gtscapvcxb.html

C#:   public override string ToString() => Name;
来源：http://dali.jyoumei.cn/Article/details/gtlzjiyaas.html

[G13] 判断对象类型
来源：http://dali.pycfn.com/Article/details/gtatfhebhz.html

Py:   isinstance(u, User)
来源：http://dali.hnqzz.top/Article/details/gtsxybcfqf.html

PHP:  $u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtfgncfqzb.html

JS:   u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtvnqicize.html

TS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtawesgplv.html

Java: u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtukzbcukf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinqigfzy.top/Article/details/gtmvsydgqe.html

Ruby: u.is_a?(User)
来源：http://dali.svipenyu.cn/Article/details/gtdkaylmjr.html

C#:   u is User
来源：http://dali.sufxvd.cn/Article/details/gtkxxrcnvr.html

[G14] 数据类 / record
来源：http://dali.zhixingplan.top/Article/details/gtlrcbjygt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yuanzhike.top/Article/details/gtcmysyhjx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.9152youxi.cn/Article/details/gtfijqsrqq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yueranfly.top/Article/details/gtrknddoyy.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj202588.top/Article/details/gtuusqdqtq.html

Java: record User(String name, int age) {}
来源：http://dali.xziqi.cn/Article/details/gtpcsglqhg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cdnleiting.top/Article/details/gtttdlkydh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.kuanghao11.cn/Article/details/gtwsbfcnol.html

C#:   record User(string Name, int Age);
来源：http://dali.gotoacloud.top/Article/details/gtmqngalcm.html

[G15] 枚举
来源：http://dali.cqqwz.cn/Article/details/gtyucaxqpj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.daxiang520.top/Article/details/gtungdroht.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj202588.top/Article/details/gtzckfinxo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrizhoiao.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sxryk.cn/Article/details/gtgkirzkqi.html

Java: enum Color { RED, GREEN }
来源：http://dali.fzhhl.top/Article/details/gttrqbpphj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shangyingyoupin.top/Article/details/gtaqnzykdz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwpyikjw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuxming.cn/Article/details/gtiiwgzlbd.html

[G16] 对象转数组 / 字典
来源：http://dali.gogol.net.cn/Article/details/gtgoivlrla.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ivvv.top/Article/details/gtntelxgja.html

PHP:  get_object_vars($obj);
来源：http://dali.0kj1m.cn/Article/details/gtlukjravh.html

JS:   Object.entries(obj)
来源：http://dali.birdmap.top/Article/details/gtuopmwist.html

TS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gthbmbwfzf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.guannengcc.top/Article/details/gtszoauyua.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxlafxyzr.html

Ruby: obj.instance_variables
来源：http://dali.cashguo.top/Article/details/gtbkaifisf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj202588.top/Article/details/gtuwhuduzp.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtwazslpzo.html

H. 异常与错误处理
来源：http://dali.cashguo.top/Article/details/gtyxvyfgsy.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtvjanfiil.html

[H01] try / catch 基础
来源：http://dali.quarkkingdee.top/Article/details/gtlbznutzm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aizwys.cn/Article/details/gtarmqzbao.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tianlin.xyz/Article/details/gtywmguala.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gtycwyamzl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jqgfzy.top/Article/details/gtdopnshea.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgfzy.top/Article/details/gtgbbzszqw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cucudq.cn/Article/details/gtaziyhfur.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hnqzz.top/Article/details/gtyydxshpp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangdashe.top/Article/details/gtrptboglu.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigufen.top/Article/details/gtvavhbfee.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hywenlv.cn/Article/details/gtmfrdozam.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtzinaspvl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtqjccgoql.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gteclixgza.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtertfbmxe.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdrjiefcz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwfafzfuk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtkrmaomle.html

[H03] 主动抛出异常
来源：http://dali.guowangkeji.top/Article/details/gthkectrug.html

Py:   raise ValueError("错误信息")
来源：http://dali.gogol.net.cn/Article/details/gtjaacdvda.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gtxpgxwwhd.html

JS:   throw new Error("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtnyezjwnm.html

TS:   throw new Error("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtnniivzpq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtmregtnzn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenlongwang.top/Article/details/gthwpvwpwy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gotoacloud.top/Article/details/gtvwcdbylm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtketppbam.html

[H04] 自定义异常类型
来源：http://dali.cqqwz.cn/Article/details/gtigkzfkwb.html

Py:   class MyError(Exception): pass
来源：http://dali.shuidangran.top/Article/details/gtuypmcxcn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dianchejie.cn/Article/details/gtlmppxisd.html

JS:   class MyError extends Error {}
来源：http://dali.cqqwz.cn/Article/details/gtuguybzqs.html

TS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gthualzkfk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gtwdjtzlmi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.havefunace.top/Article/details/gtynipmzgq.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhiwuduotai.top/Article/details/gtqquayruq.html

C#:   class MyException : Exception {}
来源：http://dali.hongshengwenyu.top/Article/details/gtcscwarnd.html

[H05] 捕获特定类型
来源：http://dali.aizwys.cn/Article/details/gtwtryfjqi.html

Py:   except ValueError as e:
来源：http://dali.hysaishi.cn/Article/details/gtyorrdkei.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuxming.cn/Article/details/gtgypcoket.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gttvwpnpph.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.quarkkingdee.top/Article/details/gtauqflyof.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.guannengcc.top/Article/details/gtyglpfepu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ehwqpu.com/Article/details/gtrovuphas.html

Ruby: rescue ArgumentError => e
来源：http://dali.ydzc1.top/Article/details/gthyegyudp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sufxvd.cn/Article/details/gtsxwxnnkd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hywenlv.cn/Article/details/gtqhvpyxec.html

Py:   value = d.get("k") or default
来源：http://dali.yonumen.top/Article/details/gtdvhiqsdg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gtmzfenepf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hnqzz.top/Article/details/gtqqcbckum.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gtsrvwbome.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.meibo888.top/Article/details/gtnsomylcs.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nanxuanxn.top/Article/details/gtgtpvfxtn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tanke756.top/Article/details/gtwzbkjopw.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgfzy.top/Article/details/gtlobywojz.html

[H07] 断言
来源：http://dali.daria6918.cn/Article/details/gtorpbzahq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.mhx1999.top/Article/details/gtdunexnus.html

PHP:  assert($x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtxlvfpwcv.html

JS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gtexrhbrwb.html

TS:   console.assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgsosjbre.html

Java: assert x > 0 : "必须为正";
来源：http://dali.svipenyu.cn/Article/details/gtxjmogwsd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yueranfly.top/Article/details/gtdszexbdx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.havefunace.top/Article/details/gtqqfpvnyn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtaxfvmawv.html

[H08] 获取错误信息与堆栈
来源：http://dali.jqgufenzy.top/Article/details/gtvpscgfis.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxinkj.top/Article/details/gtlskacoxn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gaohongyu789.top/Article/details/gtmsjxjrha.html

JS:   e.message;  e.stack
来源：http://dali.jqgufenzy.top/Article/details/gtjeypokrf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.daria6918.cn/Article/details/gtlkagrood.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyshdtmbi.html

Go:   err.Error()
来源：http://dali.quarkkingdee.top/Article/details/gtetufmwqt.html

Ruby: e.message;  e.backtrace
来源：http://dali.ppjwa.cn/Article/details/gtrhonfarq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjmjntvnj.html

[H09] 带错误码的异常
来源：http://dali.daria6918.cn/Article/details/gtdudqvaji.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pengpengdd.cyou/Article/details/gtztgfqxdb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jiagoushi.top/Article/details/gtrzgfmdto.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenjidiqi.icu/Article/details/gtlhbapztu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkfopgcsw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shuidangran.top/Article/details/gtzdpepdqy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj20258.top/Article/details/gtyoxuzbjs.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinqigufen.top/Article/details/gtwjrprylp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.haohaochexian.top/Article/details/gtcgdmrhna.html

[H10] 资源自动释放
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadaeoleh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.iojbl.cn/Article/details/gtpdtkjkbl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.svipenyu.cn/Article/details/gtskmmutey.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cqqwz.cn/Article/details/gtidsrmknc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdslgxkkp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgufenzy.top/Article/details/gtjypnhiaf.html

Go:   defer f.Close()
来源：http://dali.cheryme.top/Article/details/gtmcivndyn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinqigufen.top/Article/details/gtzorihomp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtznbcwlzo.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtgybqicwn.html

I. 正则表达式
来源：http://dali.ydzc1.top/Article/details/gtrsmttanp.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtjccxnzvk.html

[I01] 判断是否匹配
来源：http://dali.ppjwa.cn/Article/details/gtniijyuyk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xylfe.cn/Article/details/gtllbgunko.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenlongwang.top/Article/details/gtnairdfwt.html

JS:   /\d+/.test(s)
来源：http://dali.birdmap.top/Article/details/gtkyppuxpz.html

TS:   /\d+/.test(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttclilanz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hnqzz.top/Article/details/gtzapivzur.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hammf.cn/Article/details/gtbqahjbcq.html

Ruby: s.match?(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gtxtoirkwe.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.andypj.xyz/Article/details/gtpeduoowy.html

[I02] 提取所有匹配
来源：http://dali.ppjwa.cn/Article/details/gtfnfvqfbj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gtwzwjlrat.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xziqi.cn/Article/details/gtzvnnhzyn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yonumen.top/Article/details/gtafteseur.html

TS:   s.match(/\d+/g)
来源：http://dali.svipenyu.cn/Article/details/gtxhfmpqqf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.smart0.xyz/Article/details/gtfvutcxpq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nanxinkj.top/Article/details/gtvdrhsukk.html

Ruby: s.scan(/\d+/)
来源：http://dali.yvedp.cn/Article/details/gtokctzdgx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daria6918.cn/Article/details/gtkelihnqc.html

[I03] 提取捕获分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpdvuhvhm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtlqchzqtb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.meibo888.top/Article/details/gtrwizfean.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sweek.top/Article/details/gtyyfywwoo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.pengpengdd.cyou/Article/details/gthdzwbosh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shzxlz.cn/Article/details/gtkrkqygkl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.dashuyun.cn/Article/details/gtosiqusol.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.c1oappe.top/Article/details/gtuqbjlaxl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hnqzz.top/Article/details/gtwhdjqzhp.html

[I04] 正则替换
来源：http://dali.chenjidiqi.icu/Article/details/gtxzkmhcqa.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xylfe.cn/Article/details/gtuniwzupf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj202588.top/Article/details/gtfvehhxsm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.wangdashe.top/Article/details/gtacocnilg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xinyue.icu/Article/details/gtjnldhfbu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jianghu66.top/Article/details/gtbvhqqcxk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.snrcjt.cn/Article/details/gtzbjlnxjc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yvedp.cn/Article/details/gtwnqwubav.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nanxinkj.top/Article/details/gtazabpezi.html

[I05] 按正则拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gtixuikcrl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yuanzhike.top/Article/details/gtjhwllhjp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtcqoeurra.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gtvjaydzzb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gtaxieoais.html

Java: s.split("\\s*,\\s*")
来源：http://dali.andypj.xyz/Article/details/gtwikmrxte.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhengqikj.top/Article/details/gtqjyuvlww.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gtbwysmgzw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aibaodan.cn/Article/details/gthxydwhnb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.aibaodan.cn/Article/details/gtitueqnio.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gtadzqayyi.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shuidangran.top/Article/details/gtkpeygaph.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shuidangran.top/Article/details/gtlskjqlza.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gtgsymcbfz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtytkaxbga.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xylfe.cn/Article/details/gtwlwshwci.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj20258888.top/Article/details/gtoejdrepa.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gtzkdnrjil.html

[I07] 忽略大小写与多行模式
来源：http://dali.birdmap.top/Article/details/gtqtgelgcm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxwviwibj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gtciabkksp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhoulong.xyz/Article/details/gtunhlrfxc.html

TS:   /error/gim
来源：http://dali.0kj1m.cn/Article/details/gtaypxmtcz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj202588.top/Article/details/gtdnksphbe.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hysaishi.cn/Article/details/gtujurcklt.html


<!-- 参考信息 -->