代发 wailian999

Py:   class User: pass
来源：http://dali.jinqigufen.top/Article/details/gtetefbthj.html

PHP:  class User {}
来源：http://dali.jianghu66.top/Article/details/gtqgvqlqwl.html

JS:   class User {}
来源：http://dali.jqgufenzy.top/Article/details/gtrvzmnccr.html

TS:   class User { name: string = ""; }
来源：http://dali.sxryk.cn/Article/details/gtjvnulpez.html

Java: class User {}
来源：http://dali.jianghu66.top/Article/details/gttjsiywzu.html

Go:   type User struct { Name string }
来源：http://dali.cqqwz.cn/Article/details/gtnbeuqfan.html

Ruby: class User; end
来源：http://dali.chenlongwang.top/Article/details/gtdifridfr.html

C#:   class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsljpawat.html

[G02] 构造函数
来源：http://dali.daxiang520.top/Article/details/gtwxusxgpi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xuetiantiany.cn/Article/details/gtctielsli.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sxryk.cn/Article/details/gtcyhmecrx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenlongwang.top/Article/details/gtejvpmixr.html

TS:   constructor(public name: string) {}
来源：http://dali.daxiang520.top/Article/details/gtzzqduxns.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenlongwang.top/Article/details/gthazikdqw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jqgufenzy.top/Article/details/gtercispgp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aibaodan.cn/Article/details/gtekagujwk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtowghuovy.html

[G03] 实例属性
来源：http://dali.vqdsnc.cn/Article/details/gtsvyerwzn.html

Py:   self.name = "x"
来源：http://dali.nwbrower.top/Article/details/gtwpyjkwcn.html

PHP:  public string $name = "x";
来源：http://dali.sysykeji.top/Article/details/gtmlojhyan.html

JS:   this.name = "x";
来源：http://dali.ehwqpu.com/Article/details/gtleefxkwv.html

TS:   name: string = "x";
来源：http://dali.aizwys.cn/Article/details/gtjczoiwkv.html

Java: private String name;
来源：http://dali.yj202588.top/Article/details/gtlwycbois.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ehwqpu.com/Article/details/gtzxoelqee.html

Ruby: @name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gtlvizhdpe.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtzpaeefrv.html

[G04] 定义方法
来源：http://dali.cucudq.cn/Article/details/gtwitsygna.html

Py:   def greet(self): return self.name
来源：http://dali.dianchejie.cn/Article/details/gtceagnvpi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtwnferukp.html

JS:   greet() { return this.name; }
来源：http://dali.sweek.top/Article/details/gttjhuxkns.html

TS:   greet(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtdgyhhpkv.html

Java: String greet() { return name; }
来源：http://dali.bjfxy.top/Article/details/gtrfyyryji.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gtzmorlfuz.html

Ruby: def greet; @name; end
来源：http://dali.zhengqikj.top/Article/details/gtggcewmoq.html

C#:   public string Greet() => Name;
来源：http://dali.redwolf501.top/Article/details/gthtgzioyb.html

[G05] 继承
来源：http://dali.wangdashe.top/Article/details/gtazzehmxn.html

Py:   class Admin(User): pass
来源：http://dali.chenzaomai.com/Article/details/gtfiqwgnxs.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtwwkgjzsg.html

JS:   class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gtujapzwqq.html

TS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtuexbcdje.html

Java: class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gtnhuakehd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sysykeji.top/Article/details/gtqowqloxf.html

Ruby: class Admin < User; end
来源：http://dali.wangshuangyany.cn/Article/details/gtwmxkafvg.html

C#:   class Admin : User {}
来源：http://dali.wangdashe.top/Article/details/gtmwwspgrn.html

[G06] 重写方法
来源：http://dali.xylfe.cn/Article/details/gtdynyymmy.html

Py:   def greet(self): return "admin"
来源：http://dali.yonumen.top/Article/details/gtcxydptfx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtpfzdisxr.html

JS:   greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtlnlthcal.html

TS:   greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtmtazvgbf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtvvsmjktr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhiwuduotai.top/Article/details/gtaogfghgh.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigfzy.top/Article/details/gtbukuerdh.html

C#:   public override string Greet() => "admin";
来源：http://dali.cqqwz.cn/Article/details/gtghdenjou.html

[G07] 调用父类方法
来源：http://dali.hnxiangtu.top/Article/details/gtukrmxxkq.html

Py:   super().greet()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehdkuhdw.html

PHP:  parent::greet();
来源：http://dali.cashguo.top/Article/details/gthgrfzwpq.html

JS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gtwqmdeyjd.html

TS:   super.greet();
来源：http://dali.yonumen.top/Article/details/gtnbnqoywx.html

Java: super.greet();
来源：http://dali.yangfankeji.com/Article/details/gtndktjmbs.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvgkxorr.html

Ruby: super
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujwrpwya.html

C#:   base.Greet();
来源：http://dali.zhoulong.xyz/Article/details/gttklfgncl.html

[G08] 静态方法与属性
来源：http://dali.fengsongda.top/Article/details/gtrtzxvnee.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.andypj.xyz/Article/details/gtlhgxdkoo.html

PHP:  public static function f() {}
来源：http://dali.hywenlv.cn/Article/details/gtxryxjaag.html

JS:   static f() {}
来源：http://dali.tian-w.cn/Article/details/gttmjycont.html

TS:   static f(): void {}
来源：http://dali.guowangkeji.top/Article/details/gtozsshrja.html

Java: static void f() {}
来源：http://dali.cucudq.cn/Article/details/gtmwhnthoj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.smart0.xyz/Article/details/gtrjvyclzy.html

Ruby: def self.f; end
来源：http://dali.jyoumei.cn/Article/details/gtzlkqikzn.html

C#:   public static void F() {}
来源：http://dali.yj202588.top/Article/details/gtxlyxdvsz.html

[G09] 接口 / 抽象类
来源：http://dali.jinqigfzy.top/Article/details/gtkozeumyw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenjidiqi.icu/Article/details/gtkcpjjkxi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xuetiantiany.cn/Article/details/gtdvybiijc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnxiangtu.top/Article/details/gtpaegwpmq.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigfzy.top/Article/details/gtdsskpbaq.html

Java: interface Shape { double area(); }
来源：http://dali.xinyue.icu/Article/details/gtzfhzcrzz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.haohaochexian.top/Article/details/gtjlxekzuy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.dianchejie.cn/Article/details/gtypbfbuyk.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgufenzy.top/Article/details/gthdywlaps.html

[G10] 访问控制
来源：http://dali.kuanghao11.cn/Article/details/gtcuqsixzh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zycfv.cn/Article/details/gthxywxuad.html

PHP:  public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gtkrfxfpds.html

JS:   #private 字段；其余公开
来源：http://dali.aizwys.cn/Article/details/gtemrjzsrc.html

TS:   public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gtqcfgyzou.html

Java: public / protected / private / 默认包级
来源：http://dali.ehwqpu.com/Article/details/gtopgtygtt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guannengcc.top/Article/details/gtzfdlaqsi.html

Ruby: public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gtgygbryqs.html

C#:   public / protected / private / internal
来源：http://dali.jinqigufen.top/Article/details/gtolbakqje.html

[G11] getter / setter
来源：http://dali.snrcjt.cn/Article/details/gtcpwveiwf.html

Py:   @property 与 @x.setter
来源：http://dali.dashuyun.cn/Article/details/gtefaoutzo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gtxsoxlllb.html

JS:   get name() { return this._name; }
来源：http://dali.gotoacloud.top/Article/details/gtmrzcwmru.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gtehfcukqb.html

Java: public String getName() { return name; }
来源：http://dali.xylfe.cn/Article/details/gttprfuxkl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtsxnsqmxm.html

Ruby: attr_accessor :name
来源：http://dali.zhiwuduotai.top/Article/details/gtblijgwjd.html

C#:   public string Name { get; set; }
来源：http://dali.shuidangran.top/Article/details/gtfirevfon.html

[G12] 对象转字符串
来源：http://dali.daria6918.cn/Article/details/gtkihxtman.html

Py:   def __str__(self): return self.name
来源：http://dali.gaohongyu789.top/Article/details/gtizyzmusc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gtrovlangt.html

JS:   toString() { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtevfezmkw.html

TS:   toString(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtotyerrlj.html

Java: @Override public String toString() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtjdmfswjh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gtoleryhdn.html

Ruby: def to_s; @name; end
来源：http://dali.svipenyu.cn/Article/details/gtjerwqzdf.html

C#:   public override string ToString() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gttlkpupuj.html

[G13] 判断对象类型
来源：http://dali.andypj.xyz/Article/details/gtvgqhjoqj.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gtscnfytng.html

PHP:  $u instanceof User
来源：http://dali.yj202588.top/Article/details/gtyyrblqjk.html

JS:   u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtflcxxuwz.html

TS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gthnsqedwv.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gtlshhvvgo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yangfankeji.com/Article/details/gtigvusaax.html

Ruby: u.is_a?(User)
来源：http://dali.fzhhl.top/Article/details/gtymcsekun.html

C#:   u is User
来源：http://dali.jqgfzy.top/Article/details/gtmhqlmfju.html

[G14] 数据类 / record
来源：http://dali.sufxvd.cn/Article/details/gtgfndtrkk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dianchejie.cn/Article/details/gtreucmiue.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shanyushiyangtech.top/Article/details/gtdghwbtrn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwjekhhrv.html

TS:   type User = { name: string; age: number };
来源：http://dali.jyoumei.cn/Article/details/gtfqmtqlkf.html

Java: record User(String name, int age) {}
来源：http://dali.sysykeji.top/Article/details/gtuywwhste.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnxiangtu.top/Article/details/gtdbzwzmof.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj20258.top/Article/details/gthzubmfoc.html

C#:   record User(string Name, int Age);
来源：http://dali.hfpthk.cn/Article/details/gtonutcyxv.html

[G15] 枚举
来源：http://dali.jyoumei.cn/Article/details/gtyobvhvao.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenlongwang.top/Article/details/gtilwjhmag.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jiagoushi.top/Article/details/gtqlmnjgvb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.snrcjt.cn/Article/details/gtboyhpwug.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daria6918.cn/Article/details/gtmfcbtzfc.html

Java: enum Color { RED, GREEN }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdybdyjft.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ydzc1.top/Article/details/gtekmzekjm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zycfv.cn/Article/details/gtlimnkhvn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.bjfxy.top/Article/details/gthqngczlu.html

[G16] 对象转数组 / 字典
来源：http://dali.zdqjudy.top/Article/details/gtdmewxwdi.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yongpay.top/Article/details/gtiankruer.html

PHP:  get_object_vars($obj);
来源：http://dali.zhengqikj.top/Article/details/gttplwuhht.html

JS:   Object.entries(obj)
来源：http://dali.hammf.cn/Article/details/gtrdidlktq.html

TS:   Object.entries(obj)
来源：http://dali.0kj1m.cn/Article/details/gtbvkwqvyd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhiwuduotai.top/Article/details/gtaqerfiro.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gaohongyu789.top/Article/details/gtnmqoabya.html

Ruby: obj.instance_variables
来源：http://dali.yongpay.top/Article/details/gtnaesltng.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gtcmsgxkbd.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtlghnyhkl.html

H. 异常与错误处理
来源：http://dali.daria6918.cn/Article/details/gtjqczzqdw.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtpbhkgqgn.html

[H01] try / catch 基础
来源：http://dali.aibaodan.cn/Article/details/gtvcjarubz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xylfe.cn/Article/details/gtdnywskwn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cucudq.cn/Article/details/gtrbqjzvps.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gtaxfxxwan.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gtcftukmsx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.guowangkeji.top/Article/details/gtmteoesjc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gaohongyu789.top/Article/details/gtofqhjpxl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.guowangkeji.top/Article/details/gtflslfxik.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tian-w.cn/Article/details/gtmvzhxiav.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258.top/Article/details/gtcymktluk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.birdmap.top/Article/details/gtxvdhbqoz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtcswetpqm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtavueyten.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtzusnnpsa.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtzapioten.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yanxiufei.cn/Article/details/gtnfinfzan.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tianlin.xyz/Article/details/gtfrmrravy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtrawtdmyc.html

[H03] 主动抛出异常
来源：http://dali.shuidangran.top/Article/details/gtuecoulsu.html

Py:   raise ValueError("错误信息")
来源：http://dali.sweek.top/Article/details/gtttnkxsgv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gtdkkmolll.html

JS:   throw new Error("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtfonapnde.html

TS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtgugjcqhh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtekvaxiuy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.guowangkeji.top/Article/details/gtkuewmuzr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.fengsongda.top/Article/details/gtbytjyvzp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtzzepalfs.html

[H04] 自定义异常类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulmutcix.html

Py:   class MyError(Exception): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvldlvwys.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jlsjyb.cn/Article/details/gtktfpzqpi.html

JS:   class MyError extends Error {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtedeovtcj.html

TS:   class MyError extends Error {}
来源：http://dali.zdqjudy.top/Article/details/gtyupunhvq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gtkxudvtrg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.haohaochexian.top/Article/details/gtzkbvvzgw.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenjidiqi.icu/Article/details/gtioatgirg.html

C#:   class MyException : Exception {}
来源：http://dali.birdmap.top/Article/details/gtrdsmrlvi.html

[H05] 捕获特定类型
来源：http://dali.tanke756.top/Article/details/gtenvatzgo.html

Py:   except ValueError as e:
来源：http://dali.hysaishi.cn/Article/details/gtzskajlnt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yanxiufei.cn/Article/details/gtkppktfsr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gogol.net.cn/Article/details/gtdcbjckpr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gtswufnkhw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cashguo.top/Article/details/gtpzhenrrg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigufen.top/Article/details/gtjioutxsj.html

Ruby: rescue ArgumentError => e
来源：http://dali.jianghu66.top/Article/details/gtffhvcset.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtrcqbbuak.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigfzy.top/Article/details/gtjpflivxw.html

Py:   value = d.get("k") or default
来源：http://dali.bjfxy.top/Article/details/gtpmgpbrpp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xuetiantiany.cn/Article/details/gtdwhkrydf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gtdqxastjj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigfzy.top/Article/details/gtygxejtba.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.pengpengdd.cyou/Article/details/gtxjawladh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.pengpengdd.cyou/Article/details/gtupvdzkdb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258.top/Article/details/gtupahjval.html

C#:   obj?.A?.B ?? default
来源：http://dali.hysaishi.cn/Article/details/gtrvckflji.html

[H07] 断言
来源：http://dali.jinqigufen.top/Article/details/gthbqzkzwf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhengqikj.top/Article/details/gtxrwgsaqv.html

PHP:  assert($x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtlnqgsbxq.html

JS:   console.assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gtxwpiufsz.html

TS:   console.assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gtaosbgclw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jqgfzy.top/Article/details/gtknjiuwjn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hammf.cn/Article/details/gtfnlinyqy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gaohongyu789.top/Article/details/gtdgqdgalc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gtanytzvto.html

[H08] 获取错误信息与堆栈
来源：http://dali.fzhhl.top/Article/details/gtydxjkimu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ivvv.top/Article/details/gtboztgpoc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nanxinkj.top/Article/details/gtdxlkdhgy.html

JS:   e.message;  e.stack
来源：http://dali.jinqigufen.top/Article/details/gtcwrpowol.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shzxlz.cn/Article/details/gtdjutkgms.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhengqikj.top/Article/details/gtabohblbv.html

Go:   err.Error()
来源：http://dali.smart0.xyz/Article/details/gtxdtllbiw.html

Ruby: e.message;  e.backtrace
来源：http://dali.svipenyu.cn/Article/details/gtolvvuiml.html

C#:   e.Message;  e.StackTrace
来源：http://dali.snrcjt.cn/Article/details/gtibbjrboy.html

[H09] 带错误码的异常
来源：http://dali.sweek.top/Article/details/gtvmqbodvp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shuidangran.top/Article/details/gtelmciwkk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.birdmap.top/Article/details/gtskyujdbc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aibaodan.cn/Article/details/gtuuqffpbt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpdrunaji.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.havefunace.top/Article/details/gtuhowgjtk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xuanzx.com/Article/details/gtbynvwfxk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sxryk.cn/Article/details/gtzkxfxwia.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrewmcomr.html

[H10] 资源自动释放
来源：http://dali.sweek.top/Article/details/gtqujvymgx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhixingplan.top/Article/details/gthtbbiujt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.c1oappe.top/Article/details/gtjadvgcrz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.kuanghao11.cn/Article/details/gthfmerxkh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gtrmtjpplj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.snrcjt.cn/Article/details/gtzpeyqguz.html

Go:   defer f.Close()
来源：http://dali.pengpengdd.cyou/Article/details/gtofbcxdwu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ppjwa.cn/Article/details/gtzcooldhb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtaemuyfcl.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtpovhuoxg.html

I. 正则表达式
来源：http://dali.hnxiangtu.top/Article/details/gtocmxrcrf.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gttntzjikj.html

[I01] 判断是否匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtyfkwkbhm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sxryk.cn/Article/details/gtzhymvysh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tanke756.top/Article/details/gtvbtfpxku.html

JS:   /\d+/.test(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjnuvkxx.html

TS:   /\d+/.test(s)
来源：http://dali.gzhubu.top/Article/details/gtoliztucb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nwbrower.top/Article/details/gtoxvaijaq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.aizwys.cn/Article/details/gtbjjqiixk.html

Ruby: s.match?(/\d+/)
来源：http://dali.yueranfly.top/Article/details/gtdmpvnetk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cashguo.top/Article/details/gtoeoiflfl.html

[I02] 提取所有匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmnvlviks.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gtnzsnwrez.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.birdmap.top/Article/details/gtiafmpycv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.birdmap.top/Article/details/gtdjjtpxrm.html

TS:   s.match(/\d+/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtarzgoukl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jiagoushi.top/Article/details/gtogfkjlyb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gaohongyu789.top/Article/details/gtkefnqzcs.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhoulong.xyz/Article/details/gtqudzzszs.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sxryk.cn/Article/details/gthymkqiff.html

[I03] 提取捕获分组
来源：http://dali.gzhubu.top/Article/details/gtqtxrauyq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.haohaochexian.top/Article/details/gtqerbppfn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hammf.cn/Article/details/gtdtjildwz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtzmngzlrn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hammf.cn/Article/details/gtpygoekfm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.guannengcc.top/Article/details/gtltxodjpa.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhaomingkeji.xyz/Article/details/gtceyrpucn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gaohongyu789.top/Article/details/gtgiadcgpm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhongyouzk.top/Article/details/gtccbkqeoi.html

[I04] 正则替换
来源：http://dali.jqgufenzy.top/Article/details/gtvgmgupji.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtymycfvmn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtcuiiuopb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gaohongyu789.top/Article/details/gthuccylnw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sysykeji.top/Article/details/gtyobdacyq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jyoumei.cn/Article/details/gtydcjinah.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtuqpxsoax.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jianghu66.top/Article/details/gtnogvnfii.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdyhqsexl.html

[I05] 按正则拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwfsqmxh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.0kj1m.cn/Article/details/gtsqslpcor.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tian-w.cn/Article/details/gtzjopqvbx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gtjhaacyeo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gtmywsopsv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gtavhijhuq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xuanzx.com/Article/details/gtioitlens.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gtsuiijvot.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttpwkebgh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.aibaodan.cn/Article/details/gttaqekmsq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gtejwjnibe.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuanzhike.top/Article/details/gtxktewnpv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yangfankeji.com/Article/details/gtqhysizoo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtipcdplvc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gtmlggbrlx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj202588.top/Article/details/gtufrtgtvh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ydzc1.top/Article/details/gtptsfoftw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gtbhqdktpe.html

[I07] 忽略大小写与多行模式
来源：http://dali.ybcxt.top/Article/details/gtjdxpleem.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tanke756.top/Article/details/gtzcaijvwi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinqigfzy.top/Article/details/gtkxwzmsvi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yongpay.top/Article/details/gtdkszbxeh.html

TS:   /error/gim
来源：http://dali.dianchejie.cn/Article/details/gtevqaidok.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.bjfxy.top/Article/details/gtovxjzqnt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.birdmap.top/Article/details/gtuiqhqxna.html


<!-- 参考信息 -->