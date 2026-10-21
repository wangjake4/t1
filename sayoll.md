代发 wailian999

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtmiemihlo.html

G. 面向对象
来源：http://dali.zycfv.cn/Article/details/gtwpnirnuu.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtnmcdxqgl.html

[G01] 定义类
来源：http://dali.chenlongwang.top/Article/details/gtijbuposp.html

Py:   class User: pass
来源：http://dali.sweek.top/Article/details/gtdhyfbafd.html

PHP:  class User {}
来源：http://dali.hywenlv.cn/Article/details/gtnprcewrx.html

JS:   class User {}
来源：http://dali.yj20258888.top/Article/details/gtbuxdruhf.html

TS:   class User { name: string = ""; }
来源：http://dali.chenlongwang.top/Article/details/gtaetltttg.html

Java: class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtwasswinu.html

Go:   type User struct { Name string }
来源：http://dali.jiagoushi.top/Article/details/gtkvfbxqqo.html

Ruby: class User; end
来源：http://dali.ybcxt.top/Article/details/gtimwejeli.html

C#:   class User {}
来源：http://dali.pycfn.com/Article/details/gtgewxfgok.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gttrvhupuy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenzaomai.com/Article/details/gtiamxwnjz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gaohongyu789.top/Article/details/gtkhokqobb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gtsykehatn.html

TS:   constructor(public name: string) {}
来源：http://dali.zhongyouzk.top/Article/details/gtkzxprmrj.html

Java: User(String name) { this.name = name; }
来源：http://dali.cdnleiting.top/Article/details/gtrmcxwzwp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ydzc1.top/Article/details/gtsqnqbwdn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.0kj1m.cn/Article/details/gtjwkculpp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dashuyun.cn/Article/details/gtyqjfpqdd.html

[G03] 实例属性
来源：http://dali.dianchejie.cn/Article/details/gtustgggjw.html

Py:   self.name = "x"
来源：http://dali.iojbl.cn/Article/details/gtamfsrzyq.html

PHP:  public string $name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtwpxxpvtc.html

JS:   this.name = "x";
来源：http://dali.gotoacloud.top/Article/details/gtkgdivabt.html

TS:   name: string = "x";
来源：http://dali.sxryk.cn/Article/details/gtdwckyjah.html

Java: private String name;
来源：http://dali.haohaochexian.top/Article/details/gtpfwsgptq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yangfankeji.com/Article/details/gtktwdldmz.html

Ruby: @name = "x"
来源：http://dali.jinqigufen.top/Article/details/gtbgpwrdvu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenlongwang.top/Article/details/gtibqyoqmn.html

[G04] 定义方法
来源：http://dali.yangfankeji.com/Article/details/gtmgcpodda.html

Py:   def greet(self): return self.name
来源：http://dali.tanke756.top/Article/details/gtithatnwh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtagdszljg.html

JS:   greet() { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gtlbbygtko.html

TS:   greet(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtkwimcofh.html

Java: String greet() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtnsukxsbi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gtkwwtswze.html

Ruby: def greet; @name; end
来源：http://dali.xuetiantiany.cn/Article/details/gtpqeydibt.html

C#:   public string Greet() => Name;
来源：http://dali.jqgufenzy.top/Article/details/gtznxdvubk.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gtpbbfdgro.html

Py:   class Admin(User): pass
来源：http://dali.cheryme.top/Article/details/gtskvptofg.html

PHP:  class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtxmppiryn.html

JS:   class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtdptogjkc.html

TS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gttxjkfibd.html

Java: class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtcxgwynmo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigfzy.top/Article/details/gthmefbyzf.html

Ruby: class Admin < User; end
来源：http://dali.dashuyun.cn/Article/details/gtlehprhij.html

C#:   class Admin : User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtfaxtkjwh.html

[G06] 重写方法
来源：http://dali.ydzc1.top/Article/details/gtmylzgygs.html

Py:   def greet(self): return "admin"
来源：http://dali.316326.xyz/Article/details/gtiligkkfu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtqtycqdhu.html

JS:   greet() { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gtpqfbhdkr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtsffkbpem.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtroutbsys.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.fengsongda.top/Article/details/gtxqywexzp.html

Ruby: def greet; "admin"; end
来源：http://dali.sufxvd.cn/Article/details/gtnfismqfg.html

C#:   public override string Greet() => "admin";
来源：http://dali.cqqwz.cn/Article/details/gtdtlnudfm.html

[G07] 调用父类方法
来源：http://dali.shuidangran.top/Article/details/gttuyiuhjn.html

Py:   super().greet()
来源：http://dali.nanxinkj.top/Article/details/gtbskhjlrg.html

PHP:  parent::greet();
来源：http://dali.yuxming.cn/Article/details/gtcakxeven.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtabnxsfet.html

TS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gtmzdzfshv.html

Java: super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gthnuuwudn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.0kj1m.cn/Article/details/gtvhmoyjfv.html

Ruby: super
来源：http://dali.jinqigfzy.top/Article/details/gtbiayvofb.html

C#:   base.Greet();
来源：http://dali.iojbl.cn/Article/details/gtsiibptug.html

[G08] 静态方法与属性
来源：http://dali.gzhubu.top/Article/details/gthgguzlgb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgufenzy.top/Article/details/gtizovmnch.html

PHP:  public static function f() {}
来源：http://dali.yanxiufei.cn/Article/details/gtdsdoibge.html

JS:   static f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtixlewxdt.html

TS:   static f(): void {}
来源：http://dali.gzhubu.top/Article/details/gtuavpzpyt.html

Java: static void f() {}
来源：http://dali.havefunace.top/Article/details/gtnoaskupf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhengqikj.top/Article/details/gtvqipqlpp.html

Ruby: def self.f; end
来源：http://dali.xylfe.cn/Article/details/gtnpigntjv.html

C#:   public static void F() {}
来源：http://dali.iojbl.cn/Article/details/gtjeyaogwm.html

[G09] 接口 / 抽象类
来源：http://dali.yj20258.top/Article/details/gtnudgvgxu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xylfe.cn/Article/details/gtpwcqpyna.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.aizwys.cn/Article/details/gtbcoqgptt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guannengcc.top/Article/details/gtqxgohdqb.html

TS:   interface Shape { area(): number; }
来源：http://dali.nwbrower.top/Article/details/gtvcxhhgqk.html

Java: interface Shape { double area(); }
来源：http://dali.jianghu66.top/Article/details/gtmzjtosfu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hongshengwenyu.top/Article/details/gtkogesomw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.snrcjt.cn/Article/details/gttgznmubm.html

C#:   interface IShape { double Area(); }
来源：http://dali.svipenyu.cn/Article/details/gtmbgufpty.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gtsjrisuol.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.andypj.xyz/Article/details/gterrwfuoi.html

PHP:  public / protected / private
来源：http://dali.wangdashe.top/Article/details/gtrrmatxlt.html

JS:   #private 字段；其余公开
来源：http://dali.meibo888.top/Article/details/gthrispbny.html

TS:   public / protected / private
来源：http://dali.smart0.xyz/Article/details/gtdcbhzhrw.html

Java: public / protected / private / 默认包级
来源：http://dali.jyoumei.cn/Article/details/gtcjvohksi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258888.top/Article/details/gtojidtbum.html

Ruby: public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gtoxbbjnkn.html

C#:   public / protected / private / internal
来源：http://dali.zhoulong.xyz/Article/details/gtmbmmzpyb.html

[G11] getter / setter
来源：http://dali.tanke756.top/Article/details/gthgpvnqcj.html

Py:   @property 与 @x.setter
来源：http://dali.cdnleiting.top/Article/details/gtaugfnbsq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gtuceyszki.html

JS:   get name() { return this._name; }
来源：http://dali.cheryme.top/Article/details/gtmnllwhju.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtlpwunenw.html

Java: public String getName() { return name; }
来源：http://dali.sweek.top/Article/details/gtjrhivsqu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gtjjreeknh.html

Ruby: attr_accessor :name
来源：http://dali.tianlin.xyz/Article/details/gtsogjcuka.html

C#:   public string Name { get; set; }
来源：http://dali.hysaishi.cn/Article/details/gthgxldudb.html

[G12] 对象转字符串
来源：http://dali.fzhhl.top/Article/details/gtwfksqwon.html

Py:   def __str__(self): return self.name
来源：http://dali.aibaodan.cn/Article/details/gtpdzpevsp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gttjmpjzga.html

JS:   toString() { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtgejxduut.html

TS:   toString(): string { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtpjlulzll.html

Java: @Override public String toString() { return name; }
来源：http://dali.hammf.cn/Article/details/gtkigpoydl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtlrsiyimx.html

Ruby: def to_s; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gtxxvukvql.html

C#:   public override string ToString() => Name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgxbiostp.html

[G13] 判断对象类型
来源：http://dali.9152youxi.cn/Article/details/gthorgeqnk.html

Py:   isinstance(u, User)
来源：http://dali.yanxiufei.cn/Article/details/gtwnkyzqja.html

PHP:  $u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtkxtzmmlw.html

JS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtvbxrwhek.html

TS:   u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtajfowzaz.html

Java: u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtvmthalwu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hongshengwenyu.top/Article/details/gtqkexsdld.html

Ruby: u.is_a?(User)
来源：http://dali.yueranfly.top/Article/details/gtkvgaazra.html

C#:   u is User
来源：http://dali.wangdashe.top/Article/details/gtcngpizmf.html

[G14] 数据类 / record
来源：http://dali.jqgfzy.top/Article/details/gtqidfxrqx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tanke756.top/Article/details/gtuvbpcotq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dashuyun.cn/Article/details/gtoojyvxxs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgufenzy.top/Article/details/gttwwnkutq.html

TS:   type User = { name: string; age: number };
来源：http://dali.gogol.net.cn/Article/details/gtjjgloxsj.html

Java: record User(String name, int age) {}
来源：http://dali.redwolf501.top/Article/details/gtugeaucmj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.daria6918.cn/Article/details/gtqdwxjypm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xylfe.cn/Article/details/gtqazeagap.html

C#:   record User(string Name, int Age);
来源：http://dali.yuanzhike.top/Article/details/gtresufrao.html

[G15] 枚举
来源：http://dali.haohaochexian.top/Article/details/gtbszhrwsr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.mhx1999.top/Article/details/gtufavrhth.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinqigfzy.top/Article/details/gteaezdiya.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yueranfly.top/Article/details/gtvldarudf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenzaomai.com/Article/details/gtyckhxvdw.html

Java: enum Color { RED, GREEN }
来源：http://dali.hongshengwenyu.top/Article/details/gtkyldbjzb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daria6918.cn/Article/details/gtlqhjomxc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgufenzy.top/Article/details/gtrcmqwwyt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gotoacloud.top/Article/details/gtkkgacrod.html

[G16] 对象转数组 / 字典
来源：http://dali.ppjwa.cn/Article/details/gtdlhjzfae.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhixingplan.top/Article/details/gtlzxmreib.html

PHP:  get_object_vars($obj);
来源：http://dali.smart0.xyz/Article/details/gtnnwparnd.html

JS:   Object.entries(obj)
来源：http://dali.ivvv.top/Article/details/gtacxpytuu.html

TS:   Object.entries(obj)
来源：http://dali.ivvv.top/Article/details/gtoeuwkqop.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhoulong.xyz/Article/details/gtvyvrsrlx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ydzc1.top/Article/details/gtcierftsa.html

Ruby: obj.instance_variables
来源：http://dali.svipenyu.cn/Article/details/gtmbrbvirk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gthmmrbmty.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtmkicpehx.html

H. 异常与错误处理
来源：http://dali.0kj1m.cn/Article/details/gtiseredst.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtowkgkvbf.html

[H01] try / catch 基础
来源：http://dali.ivvv.top/Article/details/gtkegbbmfl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jianghu66.top/Article/details/gtdzymuxed.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cashguo.top/Article/details/gtnzxkcmob.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gtuqbhhcpk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gtwxfxgadw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gaohongyu789.top/Article/details/gtsubztubt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.feifeiyinyue.top/Article/details/gtagylmhqd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jqgufenzy.top/Article/details/gtisqducpr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.quarkkingdee.top/Article/details/gtkhpxwoho.html

[H02] finally / ensure 收尾
来源：http://dali.nanxuanxn.top/Article/details/gtoqykamiv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangkeji.top/Article/details/gthgpunhwl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtpnugsjjq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtkuvjvccm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtziyndbkq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtraoiptbo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgfzy.top/Article/details/gtffvzffcg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhongyouzk.top/Article/details/gtroaepgyd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtfhvmqxyd.html

[H03] 主动抛出异常
来源：http://dali.ppjwa.cn/Article/details/gtitatscdv.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258888.top/Article/details/gtzjwhxbzr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtrsijibab.html

JS:   throw new Error("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtclnpgzfj.html

TS:   throw new Error("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtbrhmfxgh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtyuqvyyvf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xziqi.cn/Article/details/gtylfdlrdu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gtxjsdxhve.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtrdlyqsrp.html

[H04] 自定义异常类型
来源：http://dali.ppjwa.cn/Article/details/gtafjpwczq.html

Py:   class MyError(Exception): pass
来源：http://dali.gogol.net.cn/Article/details/gtxrreyahu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shzxlz.cn/Article/details/gtoiaevzyw.html

JS:   class MyError extends Error {}
来源：http://dali.fengsongda.top/Article/details/gtavdoubtv.html

TS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gtljrrqxde.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gtmiswrcai.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpvtxmmjw.html

Ruby: class MyError < StandardError; end
来源：http://dali.gzhubu.top/Article/details/gteixwpavn.html

C#:   class MyException : Exception {}
来源：http://dali.0kj1m.cn/Article/details/gtzrhzddyy.html

[H05] 捕获特定类型
来源：http://dali.ydzc1.top/Article/details/gtyihhuoth.html

Py:   except ValueError as e:
来源：http://dali.tian-w.cn/Article/details/gtphwpjrho.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shuidangran.top/Article/details/gtrgxawinu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yuanzhike.top/Article/details/gtvrqwyzwu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ydzc1.top/Article/details/gtftjkicgf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gaohongyu789.top/Article/details/gtjnbfmrfd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hysaishi.cn/Article/details/gtjemjvmtn.html

Ruby: rescue ArgumentError => e
来源：http://dali.bjfxy.top/Article/details/gtfmuxhred.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yanxiufei.cn/Article/details/gtwepcvhwl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guowangkeji.top/Article/details/gtralpjuwq.html

Py:   value = d.get("k") or default
来源：http://dali.yongpay.top/Article/details/gtvzrbknuz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yonumen.top/Article/details/gtsiwlfjjx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gtdmdriawl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenlongwang.top/Article/details/gtjmfuvrpn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.pycfn.com/Article/details/gtutdrfgda.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yongpay.top/Article/details/gtftlchydo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shzxlz.cn/Article/details/gtimhjkuui.html

C#:   obj?.A?.B ?? default
来源：http://dali.nanxuanxn.top/Article/details/gtpiuvqqes.html

[H07] 断言
来源：http://dali.iojbl.cn/Article/details/gtyxerwzxc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nanxuanxn.top/Article/details/gtaukfaywq.html

PHP:  assert($x > 0);
来源：http://dali.pycfn.com/Article/details/gtvtfchqle.html

JS:   console.assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gtkkljovtf.html

TS:   console.assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthccxvgga.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hywenlv.cn/Article/details/gtfziesxhn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shuidangran.top/Article/details/gtoytktjdk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zdqjudy.top/Article/details/gtbyfrhbpn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gtjimilcih.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrcqqewm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ivvv.top/Article/details/gtnkyeelag.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ydzc1.top/Article/details/gtmdoezudg.html

JS:   e.message;  e.stack
来源：http://dali.gzhubu.top/Article/details/gtxdkxraro.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhongyouzk.top/Article/details/gtqgqtwdnh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ybcxt.top/Article/details/gtcofrsqps.html

Go:   err.Error()
来源：http://dali.hfpthk.cn/Article/details/gtfwmcilgw.html

Ruby: e.message;  e.backtrace
来源：http://dali.tanke756.top/Article/details/gtjildcvxv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.snrcjt.cn/Article/details/gtnaahpchf.html

[H09] 带错误码的异常
来源：http://dali.jinqigufen.top/Article/details/gtlrjagpeq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.meibo888.top/Article/details/gtofnpkcyg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jlsjyb.cn/Article/details/gtymkamtmt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jqgufenzy.top/Article/details/gttismmmyv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cqqwz.cn/Article/details/gtlwgstkaj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xziqi.cn/Article/details/gtftlobhwm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.havefunace.top/Article/details/gtdazjunrc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xziqi.cn/Article/details/gtgvxvnkwv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhongyouzk.top/Article/details/gtxrfxyhfy.html

[H10] 资源自动释放
来源：http://dali.jyoumei.cn/Article/details/gtkrxdstnu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tianlin.xyz/Article/details/gtdnopiwdr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.wangshuangyany.cn/Article/details/gtflzrrgwd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuanzx.com/Article/details/gtsbzwovxq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsksdrlge.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.svipenyu.cn/Article/details/gtwxwoyoyr.html

Go:   defer f.Close()
来源：http://dali.shzxlz.cn/Article/details/gtacfrdmcq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.guowangkeji.top/Article/details/gtddvecrlb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sxryk.cn/Article/details/gttpasqbpo.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gttuasgfky.html

I. 正则表达式
来源：http://dali.shuidangran.top/Article/details/gtsdyqpyns.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtilqtitaw.html

[I01] 判断是否匹配
来源：http://dali.yongpay.top/Article/details/gtfhcaigxm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj20258888.top/Article/details/gtqctzqhsf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gogol.net.cn/Article/details/gtfacnwswv.html

JS:   /\d+/.test(s)
来源：http://dali.xziqi.cn/Article/details/gtjqfaddfp.html

TS:   /\d+/.test(s)
来源：http://dali.hammf.cn/Article/details/gtdqsnjfqj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.wangdashe.top/Article/details/gthpxfberu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tanke756.top/Article/details/gteimkxlhq.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvbkweire.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nanxinkj.top/Article/details/gtwkvntttz.html

[I02] 提取所有匹配
来源：http://dali.redwolf501.top/Article/details/gtgwjcwywb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrtnuuqxh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.9152youxi.cn/Article/details/gtlhrxjuap.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj202588.top/Article/details/gtgvgjpvsr.html

TS:   s.match(/\d+/g)
来源：http://dali.ydzc1.top/Article/details/gtyvcchahz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.aizwys.cn/Article/details/gtcgfhtwnm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yuxming.cn/Article/details/gttceudgnr.html

Ruby: s.scan(/\d+/)
来源：http://dali.chenzaomai.com/Article/details/gtonfjzblb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtbdzczdrv.html

[I03] 提取捕获分组
来源：http://dali.bjfxy.top/Article/details/gtnkgzzslb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.daxiang520.top/Article/details/gtichsxmyc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.dianchejie.cn/Article/details/gtlomwkjjo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.haohaochexian.top/Article/details/gtffnmylza.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jqgfzy.top/Article/details/gtacdynwlk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.c1oappe.top/Article/details/gtdnwlgyic.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zdqjudy.top/Article/details/gtnrwiarvs.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cdnleiting.top/Article/details/gtfslkahpz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jianghu66.top/Article/details/gtylqgnqli.html

[I04] 正则替换
来源：http://dali.ivvv.top/Article/details/gtwibnstll.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hnqzz.top/Article/details/gtiddffvxp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gzhubu.top/Article/details/gtjrmnylfi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gtzgnwqzds.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hywenlv.cn/Article/details/gtcamdrbnr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hammf.cn/Article/details/gttwrpmank.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtkynsfgry.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yanxiufei.cn/Article/details/gtmwzquuzg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.fzhhl.top/Article/details/gtbybmbpgb.html

[I05] 按正则拆分
来源：http://dali.gogol.net.cn/Article/details/gtvdmzgfnw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.c1oappe.top/Article/details/gttjwwmaxp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yonumen.top/Article/details/gtyoscxflb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gtyubnhnaa.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvsjbelsy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hfpthk.cn/Article/details/gtlqipiabv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gtcnsvozhx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gtnjhhghxn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinqigfzy.top/Article/details/gtbgbfjeww.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hnxiangtu.top/Article/details/gtkkpcincu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtmsbjxkev.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.kuanghao11.cn/Article/details/gtuafqhjlx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cucudq.cn/Article/details/gtfokvbooj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.birdmap.top/Article/details/gtrwmkjxzj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.tanke756.top/Article/details/gthxlfzkre.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.dashuyun.cn/Article/details/gtijnammad.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuxming.cn/Article/details/gthpjgdezy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gtlrsydvpv.html

[I07] 忽略大小写与多行模式
来源：http://dali.sxryk.cn/Article/details/gtzhbfzqrv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.chenlongwang.top/Article/details/gtzihfkfkf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gtdrbxggvh.html


<!-- 参考信息 -->