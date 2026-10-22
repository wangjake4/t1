代发 wailian999

Py:   class User: pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrrjwuihx.html

PHP:  class User {}
来源：http://dali.birdmap.top/Article/details/gtnqmtfhns.html

JS:   class User {}
来源：http://dali.yj202588.top/Article/details/gtzjnicoxu.html

TS:   class User { name: string = ""; }
来源：http://dali.gzhubu.top/Article/details/gtuobwgymf.html

Java: class User {}
来源：http://dali.yj20258888.top/Article/details/gtlzxulbmt.html

Go:   type User struct { Name string }
来源：http://dali.hysaishi.cn/Article/details/gtwgzvwvmz.html

Ruby: class User; end
来源：http://dali.gzhubu.top/Article/details/gtebskpwip.html

C#:   class User {}
来源：http://dali.cashguo.top/Article/details/gtysnpquqd.html

[G02] 构造函数
来源：http://dali.gotoacloud.top/Article/details/gtevtczrxk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nanxuanxn.top/Article/details/gtvxkfnrpv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenlongwang.top/Article/details/gtbpabgyim.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gttkjjkbwy.html

TS:   constructor(public name: string) {}
来源：http://dali.birdmap.top/Article/details/gtodoosesk.html

Java: User(String name) { this.name = name; }
来源：http://dali.jianghu66.top/Article/details/gtzvtsdfgh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yonumen.top/Article/details/gttgpogqxk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cheryme.top/Article/details/gttevxrxuj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.daria6918.cn/Article/details/gtqbycjcpx.html

[G03] 实例属性
来源：http://dali.yongpay.top/Article/details/gtbuxhrisa.html

Py:   self.name = "x"
来源：http://dali.haohaochexian.top/Article/details/gttgmgmekm.html

PHP:  public string $name = "x";
来源：http://dali.andypj.xyz/Article/details/gtropsgpgd.html

JS:   this.name = "x";
来源：http://dali.nanxinkj.top/Article/details/gtbjfkybyb.html

TS:   name: string = "x";
来源：http://dali.cheryme.top/Article/details/gtzzelhtaa.html

Java: private String name;
来源：http://dali.yj20258.top/Article/details/gtfoqnkvtg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.aibaodan.cn/Article/details/gtgqvdudod.html

Ruby: @name = "x"
来源：http://dali.xuanzx.com/Article/details/gtvyrhfyzn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtnoxqkxgb.html

[G04] 定义方法
来源：http://dali.xziqi.cn/Article/details/gtyframbnq.html

Py:   def greet(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gtoovvcsvg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gtdcdgitwa.html

JS:   greet() { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtzjsdpfbf.html

TS:   greet(): string { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gttqqbeoja.html

Java: String greet() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtoshrwkzj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gtgddeiibw.html

Ruby: def greet; @name; end
来源：http://dali.9152youxi.cn/Article/details/gtauuvupgg.html

C#:   public string Greet() => Name;
来源：http://dali.jqgufenzy.top/Article/details/gtpndrzcer.html

[G05] 继承
来源：http://dali.ybcxt.top/Article/details/gtmhhwjtgb.html

Py:   class Admin(User): pass
来源：http://dali.nanxuanxn.top/Article/details/gthqduezvh.html

PHP:  class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gtbhzrduuj.html

JS:   class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtaeithyeu.html

TS:   class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtkdgyihxx.html

Java: class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgbztskac.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.aibaodan.cn/Article/details/gtmafonelt.html

Ruby: class Admin < User; end
来源：http://dali.hnqzz.top/Article/details/gtkacfyocl.html

C#:   class Admin : User {}
来源：http://dali.haohaochexian.top/Article/details/gthksqkzon.html

[G06] 重写方法
来源：http://dali.yangfankeji.com/Article/details/gtiepuuzjp.html

Py:   def greet(self): return "admin"
来源：http://dali.chenzaomai.com/Article/details/gtrhjyeuqt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtkcpprrhg.html

JS:   greet() { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gthpvfjzbk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtotlpoxeu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtbdbzzfms.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.meibo888.top/Article/details/gtaogtikiz.html

Ruby: def greet; "admin"; end
来源：http://dali.aizwys.cn/Article/details/gtrzaguyge.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuanzx.com/Article/details/gtomkjwseo.html

[G07] 调用父类方法
来源：http://dali.zycfv.cn/Article/details/gtvtfxrnuj.html

Py:   super().greet()
来源：http://dali.shuidangran.top/Article/details/gthfjwyade.html

PHP:  parent::greet();
来源：http://dali.yuanzhike.top/Article/details/gtxlwerfrt.html

JS:   super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrqjpuwo.html

TS:   super.greet();
来源：http://dali.hfpthk.cn/Article/details/gtpzjtfeiu.html

Java: super.greet();
来源：http://dali.svipenyu.cn/Article/details/gtprijloax.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtvsfjloxo.html

Ruby: super
来源：http://dali.zhoulong.xyz/Article/details/gtbcemlfwz.html

C#:   base.Greet();
来源：http://dali.yanxiufei.cn/Article/details/gtbrjngxfc.html

[G08] 静态方法与属性
来源：http://dali.ehwqpu.com/Article/details/gtulryzpbz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.meibo888.top/Article/details/gtrpttxsoi.html

PHP:  public static function f() {}
来源：http://dali.hnqzz.top/Article/details/gtwuzplspe.html

JS:   static f() {}
来源：http://dali.xuanzx.com/Article/details/gtqgrcgqnx.html

TS:   static f(): void {}
来源：http://dali.xziqi.cn/Article/details/gtpjggwxes.html

Java: static void f() {}
来源：http://dali.dashuyun.cn/Article/details/gtpbsxkzgd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zdqjudy.top/Article/details/gtyhazxrfb.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrwnxnlo.html

C#:   public static void F() {}
来源：http://dali.dianchejie.cn/Article/details/gtmkfgsjpg.html

[G09] 接口 / 抽象类
来源：http://dali.0kj1m.cn/Article/details/gtklxkyklo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hysaishi.cn/Article/details/gtvyaoakyz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guannengcc.top/Article/details/gtwvdgqzzx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daria6918.cn/Article/details/gthmkxswql.html

TS:   interface Shape { area(): number; }
来源：http://dali.ivvv.top/Article/details/gtkfsozgoe.html

Java: interface Shape { double area(); }
来源：http://dali.hammf.cn/Article/details/gtwuhvchcw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dianchejie.cn/Article/details/gtladxzfwe.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nanxuanxn.top/Article/details/gtyisxfktt.html

C#:   interface IShape { double Area(); }
来源：http://dali.cdnleiting.top/Article/details/gtiadbgczv.html

[G10] 访问控制
来源：http://dali.dianchejie.cn/Article/details/gtoebqmxht.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.mhx1999.top/Article/details/gtalcpblkb.html

PHP:  public / protected / private
来源：http://dali.jianghu66.top/Article/details/gtgkufrhso.html

JS:   #private 字段；其余公开
来源：http://dali.nanxinkj.top/Article/details/gtpedvykpc.html

TS:   public / protected / private
来源：http://dali.guannengcc.top/Article/details/gtyifkmkqf.html

Java: public / protected / private / 默认包级
来源：http://dali.chenjidiqi.icu/Article/details/gtecxaqcpe.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.fengsongda.top/Article/details/gtnwfnksxr.html

Ruby: public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gtyildhycp.html

C#:   public / protected / private / internal
来源：http://dali.cdnleiting.top/Article/details/gtcglhlnwh.html

[G11] getter / setter
来源：http://dali.bjfxy.top/Article/details/gtgfyazejl.html

Py:   @property 与 @x.setter
来源：http://dali.guannengcc.top/Article/details/gtpzsczhgx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gttzwgcnad.html

JS:   get name() { return this._name; }
来源：http://dali.iojbl.cn/Article/details/gtbykfrksh.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxinkj.top/Article/details/gturqgahgn.html

Java: public String getName() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtguarklnv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gthweujued.html

Ruby: attr_accessor :name
来源：http://dali.fengsongda.top/Article/details/gtyyfoxcpk.html

C#:   public string Name { get; set; }
来源：http://dali.yj20258888.top/Article/details/gtilbbreay.html

[G12] 对象转字符串
来源：http://dali.zdqjudy.top/Article/details/gtkqcpnulu.html

Py:   def __str__(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gtewshdemo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gtdtyncxwe.html

JS:   toString() { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtopbqclcn.html

TS:   toString(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtuenalugb.html

Java: @Override public String toString() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtfpfbtfxh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtkguklylq.html

Ruby: def to_s; @name; end
来源：http://dali.fengsongda.top/Article/details/gtubcjnigi.html

C#:   public override string ToString() => Name;
来源：http://dali.chenlongwang.top/Article/details/gttipbvnwq.html

[G13] 判断对象类型
来源：http://dali.jianghu66.top/Article/details/gtcxizrevc.html

Py:   isinstance(u, User)
来源：http://dali.feifeiyinyue.top/Article/details/gtiudxdwqx.html

PHP:  $u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtxutaqdfh.html

JS:   u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtcetynqmo.html

TS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkjbxxukg.html

Java: u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtapimocvs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jqgfzy.top/Article/details/gtztgfhpna.html

Ruby: u.is_a?(User)
来源：http://dali.jinqigfzy.top/Article/details/gttbjiospv.html

C#:   u is User
来源：http://dali.meibo888.top/Article/details/gtunzytzsd.html

[G14] 数据类 / record
来源：http://dali.zycfv.cn/Article/details/gtliiurbry.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.aizwys.cn/Article/details/gtaglzkyuo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hfpthk.cn/Article/details/gtkpprkwzr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sufxvd.cn/Article/details/gtuiysntkl.html

TS:   type User = { name: string; age: number };
来源：http://dali.hnxiangtu.top/Article/details/gtyafsrxsj.html

Java: record User(String name, int age) {}
来源：http://dali.yuanzhike.top/Article/details/gtmlngyxfl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigfzy.top/Article/details/gtffizuatm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.vqdsnc.cn/Article/details/gtduthxjyj.html

C#:   record User(string Name, int Age);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdanokabz.html

[G15] 枚举
来源：http://dali.yuanzhike.top/Article/details/gtdmqmzzdh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shangyingyoupin.top/Article/details/gtzsmjjzgj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtutvyxcmd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinghuilouyu.cn/Article/details/gtxdhtviyb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtcfjzytwp.html

Java: enum Color { RED, GREEN }
来源：http://dali.xinyue.icu/Article/details/gtemrydtxg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuanzhike.top/Article/details/gtlhnhfxcr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gogol.net.cn/Article/details/gtxfsidcdr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoajjpond.html

[G16] 对象转数组 / 字典
来源：http://dali.yvedp.cn/Article/details/gtbiduoxfk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yangfankeji.com/Article/details/gtvfkxqujs.html

PHP:  get_object_vars($obj);
来源：http://dali.smart0.xyz/Article/details/gtjawzyauv.html

JS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gtfzwopwpa.html

TS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gtcyyxtdur.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cashguo.top/Article/details/gtaicblngo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cdnleiting.top/Article/details/gtokdlupse.html

Ruby: obj.instance_variables
来源：http://dali.shangyingyoupin.top/Article/details/gtulzjrfga.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cucudq.cn/Article/details/gtpuufzipd.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtnmdatokp.html

H. 异常与错误处理
来源：http://dali.jiagoushi.top/Article/details/gtgnhxivls.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtghszdpdb.html

[H01] try / catch 基础
来源：http://dali.redwolf501.top/Article/details/gtasxmprgq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuxming.cn/Article/details/gtyykworoj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.smart0.xyz/Article/details/gtriihcomd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gttgflczpk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gtkhhiliba.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.redwolf501.top/Article/details/gtcsactsnk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangshuangyany.cn/Article/details/gtkbftfixw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cucudq.cn/Article/details/gtqmyhvwva.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.mhx1999.top/Article/details/gtkpmlvupt.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigfzy.top/Article/details/gttnfygnoz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pengpengdd.cyou/Article/details/gtbmozbqzj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtdwavxrqk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtvrekqooh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtuasblyxk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtcqnlxbsq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.9152youxi.cn/Article/details/gteyiotsdx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.feifeiyinyue.top/Article/details/gtkxqwayap.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtsorgggym.html

[H03] 主动抛出异常
来源：http://dali.yongpay.top/Article/details/gtcgvlxrtl.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuxming.cn/Article/details/gtzwtlacyv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gtkpwxvpxe.html

JS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtrrdqrbbw.html

TS:   throw new Error("错误信息");
来源：http://dali.cashguo.top/Article/details/gtvslbrzlf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtxvtgbsfw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shuidangran.top/Article/details/gtjryrponk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jqgufenzy.top/Article/details/gtckzlrpql.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtkzlwsbsl.html

[H04] 自定义异常类型
来源：http://dali.xziqi.cn/Article/details/gtxozvscjb.html

Py:   class MyError(Exception): pass
来源：http://dali.gogol.net.cn/Article/details/gtwonylzlh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gtojjwinrh.html

JS:   class MyError extends Error {}
来源：http://dali.pengpengdd.cyou/Article/details/gtvtbxigkb.html

TS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gtbazkvqed.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tian-w.cn/Article/details/gtadhkmmwj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.quarkkingdee.top/Article/details/gtwijvasws.html

Ruby: class MyError < StandardError; end
来源：http://dali.bjfxy.top/Article/details/gtjusrklqy.html

C#:   class MyException : Exception {}
来源：http://dali.ivvv.top/Article/details/gtuxrfunyx.html

[H05] 捕获特定类型
来源：http://dali.zhiwuduotai.top/Article/details/gtppjuprtn.html

Py:   except ValueError as e:
来源：http://dali.yonumen.top/Article/details/gtzqefvcgn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuetiantiany.cn/Article/details/gtopwfmbsk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gtibtyoneo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gzhubu.top/Article/details/gtxyrmwqqd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cqqwz.cn/Article/details/gtmzwfznyy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpclfeuye.html

Ruby: rescue ArgumentError => e
来源：http://dali.hongshengwenyu.top/Article/details/gtceaewxfb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.smart0.xyz/Article/details/gttzvntjhj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.haohaochexian.top/Article/details/gtuzrlcsyk.html

Py:   value = d.get("k") or default
来源：http://dali.jianghu66.top/Article/details/gtevlchsle.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.daxiang520.top/Article/details/gtkzlcxmvc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gtketqhcyb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ivvv.top/Article/details/gtorgauqux.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.smart0.xyz/Article/details/gtocerfdwt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.c1oappe.top/Article/details/gtfwjbiycb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.svipenyu.cn/Article/details/gtvsowldiq.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhoulong.xyz/Article/details/gtujfawmdf.html

[H07] 断言
来源：http://dali.pycfn.com/Article/details/gtvltrqjak.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shanyushiyangtech.top/Article/details/gtjcskihpb.html

PHP:  assert($x > 0);
来源：http://dali.sweek.top/Article/details/gtwejpixtc.html

JS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtyxvxcbuw.html

TS:   console.assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtiojlfvpr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.aibaodan.cn/Article/details/gtpdukdbbd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yonumen.top/Article/details/gtdffqgrqz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj20258.top/Article/details/gtbjkwylcf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gtwrufbdac.html

[H08] 获取错误信息与堆栈
来源：http://dali.kuanghao11.cn/Article/details/gthkpedltx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenzaomai.com/Article/details/gtmzqaovkt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.svipenyu.cn/Article/details/gtntnfydus.html

JS:   e.message;  e.stack
来源：http://dali.zhengqikj.top/Article/details/gtzumtekmm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tianlin.xyz/Article/details/gtpokpptua.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbjcyirs.html

Go:   err.Error()
来源：http://dali.cheryme.top/Article/details/gtuubyxfba.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigfzy.top/Article/details/gtnrhawwas.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hysaishi.cn/Article/details/gtjcxtkskx.html

[H09] 带错误码的异常
来源：http://dali.ehwqpu.com/Article/details/gtexjysohl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.vqdsnc.cn/Article/details/gtjshogehu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nanxinkj.top/Article/details/gtjiojdbvx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.0kj1m.cn/Article/details/gtvzebrcpr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ehwqpu.com/Article/details/gtvhxcthrr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ivvv.top/Article/details/gtilcnkkqv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.haohaochexian.top/Article/details/gtodeuvznt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xuanzx.com/Article/details/gtlzbdcozi.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttzxkrfwn.html

[H10] 资源自动释放
来源：http://dali.yj20258.top/Article/details/gtjeobjdzn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xziqi.cn/Article/details/gtzxhitmhl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.dashuyun.cn/Article/details/gtuflehvts.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.feifeiyinyue.top/Article/details/gtfdkrjfwg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gtjrcuixdk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoqjaqsfb.html

Go:   defer f.Close()
来源：http://dali.9152youxi.cn/Article/details/gtehzatbbi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shuidangran.top/Article/details/gtydouxges.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtfteixxln.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gttdzgyurz.html

I. 正则表达式
来源：http://dali.andypj.xyz/Article/details/gteebodsqh.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtaroggqgj.html

[I01] 判断是否匹配
来源：http://dali.fzhhl.top/Article/details/gtebmrcjtb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sxryk.cn/Article/details/gttllkhted.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zdqjudy.top/Article/details/gtqnqskofk.html

JS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gtklgtqjxj.html

TS:   /\d+/.test(s)
来源：http://dali.andypj.xyz/Article/details/gtzldtrmet.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.kuanghao11.cn/Article/details/gtvixqfhdo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sweek.top/Article/details/gtoxtjxvvj.html

Ruby: s.match?(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gttqxemiig.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.fzhhl.top/Article/details/gtnevogxmx.html

[I02] 提取所有匹配
来源：http://dali.hnqzz.top/Article/details/gtnkoqxkoy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.iojbl.cn/Article/details/gtlslgkixe.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hnxiangtu.top/Article/details/gtmxgqvszb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.vqdsnc.cn/Article/details/gtguftpcbk.html

TS:   s.match(/\d+/g)
来源：http://dali.xuanzx.com/Article/details/gtgcfxgmmr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gtbamocjrc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.guowangkeji.top/Article/details/gtkcjdpbft.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxinkj.top/Article/details/gtchnaholk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtkvyqecgs.html

[I03] 提取捕获分组
来源：http://dali.yj20258.top/Article/details/gtdwmdybfr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gtlbjeuqwy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxinkj.top/Article/details/gtrbzbmcyx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ppjwa.cn/Article/details/gtxtmdrrlh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtodkxrwki.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenlongwang.top/Article/details/gtogucodgh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.pycfn.com/Article/details/gtpaviagmf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinqigfzy.top/Article/details/gtimitksba.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.smart0.xyz/Article/details/gttwaksezs.html

[I04] 正则替换
来源：http://dali.smart0.xyz/Article/details/gtoxzbfpwr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gtqcyflvqe.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.c1oappe.top/Article/details/gtreumkabg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.fengsongda.top/Article/details/gtqlrajpgs.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hnqzz.top/Article/details/gtdekliwox.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tianlin.xyz/Article/details/gtwzmmetpk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.guowangkeji.top/Article/details/gtvhovrxub.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zdqjudy.top/Article/details/gtviqukwfh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gtkfdgcgpj.html

[I05] 按正则拆分
来源：http://dali.dianchejie.cn/Article/details/gtolususrp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.fzhhl.top/Article/details/gtfgmvvwcc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtjphlytpc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sweek.top/Article/details/gtnsgioxfo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gtketmijsb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sxryk.cn/Article/details/gtqejvyfnl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.birdmap.top/Article/details/gtdcqeisbd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlspcmuuw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.wangshuangyany.cn/Article/details/gtzsfsibks.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenjidiqi.icu/Article/details/gtitriqqmq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.meibo888.top/Article/details/gtglpzzzik.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yvedp.cn/Article/details/gtbjcuzfuz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gttuqnydfp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhiwuduotai.top/Article/details/gtpdjnxumn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gtuvdjuasd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hnqzz.top/Article/details/gtvzjvzbki.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuanzhike.top/Article/details/gtitpbbtgn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shuidangran.top/Article/details/gtxgjzeilm.html

[I07] 忽略大小写与多行模式
来源：http://dali.316326.xyz/Article/details/gtntearuty.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sufxvd.cn/Article/details/gthvepbzgz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gtruvnkpcc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xuetiantiany.cn/Article/details/gtvcktbkta.html

TS:   /error/gim
来源：http://dali.quarkkingdee.top/Article/details/gtnrvvopwi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtygvzky.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yuxming.cn/Article/details/gtgeyiqlwl.html


<!-- 参考信息 -->