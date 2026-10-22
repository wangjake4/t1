代发 wailian999

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtbbqacebf.html

G. 面向对象
来源：http://dali.hnxiangtu.top/Article/details/gtgldusqme.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtirfaritb.html

[G01] 定义类
来源：http://dali.wangdashe.top/Article/details/gtszfwxzwn.html

Py:   class User: pass
来源：http://dali.cqqwz.cn/Article/details/gtnjpmoemc.html

PHP:  class User {}
来源：http://dali.ybcxt.top/Article/details/gtopyqtsva.html

JS:   class User {}
来源：http://dali.hywenlv.cn/Article/details/gtfpnummgx.html

TS:   class User { name: string = ""; }
来源：http://dali.yuxming.cn/Article/details/gtjphwrbhm.html

Java: class User {}
来源：http://dali.redwolf501.top/Article/details/gtochbsypl.html

Go:   type User struct { Name string }
来源：http://dali.meibo888.top/Article/details/gtofyqbdcc.html

Ruby: class User; end
来源：http://dali.cheryme.top/Article/details/gtbnlcagta.html

C#:   class User {}
来源：http://dali.tianlin.xyz/Article/details/gtarwloccy.html

[G02] 构造函数
来源：http://dali.shuidangran.top/Article/details/gtdewiudti.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hfpthk.cn/Article/details/gtxckbgjva.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.havefunace.top/Article/details/gtmznighnt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gtqoqnnxzg.html

TS:   constructor(public name: string) {}
来源：http://dali.chenlongwang.top/Article/details/gtlaoobeca.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gtfnjvmfql.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmlxuautt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gaohongyu789.top/Article/details/gtxdxbbsuf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtktgzwujc.html

[G03] 实例属性
来源：http://dali.ivvv.top/Article/details/gtgrkppajn.html

Py:   self.name = "x"
来源：http://dali.nanxinkj.top/Article/details/gtgqvctfjz.html

PHP:  public string $name = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubvdtkts.html

JS:   this.name = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtblselcsk.html

TS:   name: string = "x";
来源：http://dali.kuanghao11.cn/Article/details/gttnkxuxvo.html

Java: private String name;
来源：http://dali.fengsongda.top/Article/details/gtucrrgjua.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nanxuanxn.top/Article/details/gtasrlpycy.html

Ruby: @name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gtuueyrbly.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.316326.xyz/Article/details/gteenleuum.html

[G04] 定义方法
来源：http://dali.zhongyouzk.top/Article/details/gtznlxnpim.html

Py:   def greet(self): return self.name
来源：http://dali.birdmap.top/Article/details/gtoyqbooyq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gtkwsvpblb.html

JS:   greet() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtqsorufbm.html

TS:   greet(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtfgiopble.html

Java: String greet() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtxgrejyua.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gtoippddlt.html

Ruby: def greet; @name; end
来源：http://dali.jianghu66.top/Article/details/gtdgxqnkga.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gtdgdvepcu.html

[G05] 继承
来源：http://dali.fengsongda.top/Article/details/gtihvwdnfl.html

Py:   class Admin(User): pass
来源：http://dali.xziqi.cn/Article/details/gtoduenhwa.html

PHP:  class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtxrwbtzds.html

JS:   class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gthqeaklbj.html

TS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtamrxzfez.html

Java: class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gtmvaaviit.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.vqdsnc.cn/Article/details/gtnhqrammk.html

Ruby: class Admin < User; end
来源：http://dali.yj20258888.top/Article/details/gtsagzcmme.html

C#:   class Admin : User {}
来源：http://dali.9152youxi.cn/Article/details/gtfynnelsr.html

[G06] 重写方法
来源：http://dali.jianghu66.top/Article/details/gtboiingru.html

Py:   def greet(self): return "admin"
来源：http://dali.aibaodan.cn/Article/details/gtqevcvbbg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtvrjsiqhs.html

JS:   greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtyablgseb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtxmtagdrp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtnfvgumac.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.9152youxi.cn/Article/details/gtxhihdgow.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigfzy.top/Article/details/gtzlcrlcyb.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj20258888.top/Article/details/gtcivzjkhc.html

[G07] 调用父类方法
来源：http://dali.zdqjudy.top/Article/details/gtghbhfhdf.html

Py:   super().greet()
来源：http://dali.daxiang520.top/Article/details/gtruhihhze.html

PHP:  parent::greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtshbhkawb.html

JS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gtlkfglrly.html

TS:   super.greet();
来源：http://dali.zhixingplan.top/Article/details/gtrhyuielg.html

Java: super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtmijijuvz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cheryme.top/Article/details/gtpemtdpvl.html

Ruby: super
来源：http://dali.dianchejie.cn/Article/details/gtusxetaob.html

C#:   base.Greet();
来源：http://dali.yueranfly.top/Article/details/gtzxpnytqq.html

[G08] 静态方法与属性
来源：http://dali.jiagoushi.top/Article/details/gtwcayxrlz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj20258.top/Article/details/gtkgwbuhdi.html

PHP:  public static function f() {}
来源：http://dali.xylfe.cn/Article/details/gtmbtupnuu.html

JS:   static f() {}
来源：http://dali.nanxinkj.top/Article/details/gtwuapezzu.html

TS:   static f(): void {}
来源：http://dali.chenjidiqi.icu/Article/details/gtpmrdsvlh.html

Java: static void f() {}
来源：http://dali.sweek.top/Article/details/gtfikjaskm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.haohaochexian.top/Article/details/gthqetsvon.html

Ruby: def self.f; end
来源：http://dali.gzhubu.top/Article/details/gtqbravcgj.html

C#:   public static void F() {}
来源：http://dali.dianchejie.cn/Article/details/gtklulchhm.html

[G09] 接口 / 抽象类
来源：http://dali.fengsongda.top/Article/details/gtkrufrspm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenjidiqi.icu/Article/details/gtimbiscod.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jianghu66.top/Article/details/gtdprwdkwq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.kuanghao11.cn/Article/details/gtuwfbcugc.html

TS:   interface Shape { area(): number; }
来源：http://dali.nwbrower.top/Article/details/gtkzavpitf.html

Java: interface Shape { double area(); }
来源：http://dali.ivvv.top/Article/details/gtcrffmsni.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ivvv.top/Article/details/gtnvbpfewk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shangyingyoupin.top/Article/details/gtcqlhjfwt.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgufenzy.top/Article/details/gtnvhmwmuh.html

[G10] 访问控制
来源：http://dali.gaohongyu789.top/Article/details/gtsblgtkom.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.dashuyun.cn/Article/details/gtspxnnrmt.html

PHP:  public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gtxcgjuvkc.html

JS:   #private 字段；其余公开
来源：http://dali.yongpay.top/Article/details/gtblhocdck.html

TS:   public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gtjcfiihgv.html

Java: public / protected / private / 默认包级
来源：http://dali.snrcjt.cn/Article/details/gtufmfldmn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sweek.top/Article/details/gtqgqkmcui.html

Ruby: public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gtzxxooqgv.html

C#:   public / protected / private / internal
来源：http://dali.sufxvd.cn/Article/details/gtdnjavtlx.html

[G11] getter / setter
来源：http://dali.pycfn.com/Article/details/gteflgxhfu.html

Py:   @property 与 @x.setter
来源：http://dali.tianlin.xyz/Article/details/gtpefkcyob.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gtsperirre.html

JS:   get name() { return this._name; }
来源：http://dali.yonumen.top/Article/details/gteomvqiva.html

TS:   get name(): string { return this._name; }
来源：http://dali.zycfv.cn/Article/details/gtdwupderd.html

Java: public String getName() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtesjdufvk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gtcqpfwewi.html

Ruby: attr_accessor :name
来源：http://dali.jiagoushi.top/Article/details/gtfindwpej.html

C#:   public string Name { get; set; }
来源：http://dali.cqqwz.cn/Article/details/gtkwpxgcjo.html

[G12] 对象转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtvnlvwtbj.html

Py:   def __str__(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gtaaklpkcg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gtsodtmdry.html

JS:   toString() { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtjlfyvstt.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258.top/Article/details/gtzhzxayny.html

Java: @Override public String toString() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtbwdckiei.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gtkmpwzlgu.html

Ruby: def to_s; @name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbkudjdxg.html

C#:   public override string ToString() => Name;
来源：http://dali.zhoulong.xyz/Article/details/gtdwvturxi.html

[G13] 判断对象类型
来源：http://dali.ivvv.top/Article/details/gttqsiwtos.html

Py:   isinstance(u, User)
来源：http://dali.hnqzz.top/Article/details/gtxaunjbln.html

PHP:  $u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gtfikzthfq.html

JS:   u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gtcxbevqgq.html

TS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtcejwniid.html

Java: u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gtauqinfhe.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.mhx1999.top/Article/details/gtxkcybata.html

Ruby: u.is_a?(User)
来源：http://dali.gaohongyu789.top/Article/details/gtsdccutgx.html

C#:   u is User
来源：http://dali.tian-w.cn/Article/details/gtgjixojzf.html

[G14] 数据类 / record
来源：http://dali.fzhhl.top/Article/details/gtbbxdsxoz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenjidiqi.icu/Article/details/gtwqkbdurc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmkeonxwu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zycfv.cn/Article/details/gtpviuhdbp.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenzaomai.com/Article/details/gtxyuylyor.html

Java: record User(String name, int age) {}
来源：http://dali.gzhubu.top/Article/details/gtervlsodt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zdqjudy.top/Article/details/gtnynozxff.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.feifeiyinyue.top/Article/details/gtcnmkmckb.html

C#:   record User(string Name, int Age);
来源：http://dali.mhx1999.top/Article/details/gtfvyjdviq.html

[G15] 枚举
来源：http://dali.yuxming.cn/Article/details/gtetjuuahr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.316326.xyz/Article/details/gtbzxsumts.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jianghu66.top/Article/details/gtyuhdwyer.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xinyue.icu/Article/details/gtkpccdoam.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hysaishi.cn/Article/details/gtsmnllgcc.html

Java: enum Color { RED, GREEN }
来源：http://dali.xziqi.cn/Article/details/gtejzjducs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.snrcjt.cn/Article/details/gthkfuzpnw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhiwuduotai.top/Article/details/gtnrabyoel.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sxryk.cn/Article/details/gtfelykvzq.html

[G16] 对象转数组 / 字典
来源：http://dali.chenlongwang.top/Article/details/gtdppddfli.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ivvv.top/Article/details/gtyrfuwxvv.html

PHP:  get_object_vars($obj);
来源：http://dali.cqqwz.cn/Article/details/gtajgnrirn.html

JS:   Object.entries(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtwngnliza.html

TS:   Object.entries(obj)
来源：http://dali.jiagoushi.top/Article/details/gtynbagywg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yongpay.top/Article/details/gtsfnbdsxk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhengqikj.top/Article/details/gtpndgdvui.html

Ruby: obj.instance_variables
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmqbgixfn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.svipenyu.cn/Article/details/gtoaqacgwp.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtdviqagye.html

H. 异常与错误处理
来源：http://dali.gzhubu.top/Article/details/gtjokarvou.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtmzycsqka.html

[H01] try / catch 基础
来源：http://dali.jinghuilouyu.cn/Article/details/gtcvcjbqwy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuxming.cn/Article/details/gtincwxjiq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hywenlv.cn/Article/details/gtxnjulkxs.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gtjvcovcel.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gtsmlwsezq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jianghu66.top/Article/details/gtawwetlnp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.smart0.xyz/Article/details/gtlsgixwvd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gaohongyu789.top/Article/details/gtzxshgqgs.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangshuangyany.cn/Article/details/gtkvurtoam.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjuphkwxk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.quarkkingdee.top/Article/details/gtdunffrnv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtjipmeulf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtpghhvpic.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gttmgeymqp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqdprqayq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cheryme.top/Article/details/gthehfogcn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xziqi.cn/Article/details/gthawytsqx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtwgjmatjc.html

[H03] 主动抛出异常
来源：http://dali.kuanghao11.cn/Article/details/gtuodyfvwv.html

Py:   raise ValueError("错误信息")
来源：http://dali.c1oappe.top/Article/details/gtbtkwousz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gtfsvwtfmh.html

JS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gtsmeyfxap.html

TS:   throw new Error("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtngsosjna.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtwjnbtcyv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.smart0.xyz/Article/details/gtxijbszpo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gogol.net.cn/Article/details/gtnoqrjkkx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtevnpicyu.html

[H04] 自定义异常类型
来源：http://dali.xuanzx.com/Article/details/gtzkiqmsup.html

Py:   class MyError(Exception): pass
来源：http://dali.daxiang520.top/Article/details/gtoguvfxpd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gtogywaecf.html

JS:   class MyError extends Error {}
来源：http://dali.fengsongda.top/Article/details/gttpavnqcw.html

TS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gtottkmltv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gtceoowiao.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cdnleiting.top/Article/details/gtqxdrekzj.html

Ruby: class MyError < StandardError; end
来源：http://dali.cheryme.top/Article/details/gtlvjrvjmw.html

C#:   class MyException : Exception {}
来源：http://dali.fengsongda.top/Article/details/gtbriecihn.html

[H05] 捕获特定类型
来源：http://dali.xylfe.cn/Article/details/gtsgtbxpeq.html

Py:   except ValueError as e:
来源：http://dali.zhiwuduotai.top/Article/details/gtpjvbwkom.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ivvv.top/Article/details/gtcfcgroyf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxiedqxys.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtszfgcawa.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tian-w.cn/Article/details/gtgrwxqbwr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dianchejie.cn/Article/details/gttpxljrri.html

Ruby: rescue ArgumentError => e
来源：http://dali.sysykeji.top/Article/details/gtcvnxtmub.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sufxvd.cn/Article/details/gtzxjnfpfm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj202588.top/Article/details/gtorybicox.html

Py:   value = d.get("k") or default
来源：http://dali.jianghu66.top/Article/details/gtnmpwjkec.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gtwemqbyhp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gtdktbxhrq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sysykeji.top/Article/details/gtlfrliwbo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xinyue.icu/Article/details/gtjkcyiwvq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hfpthk.cn/Article/details/gtzcuovhor.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tianlin.xyz/Article/details/gtbttnldym.html

C#:   obj?.A?.B ?? default
来源：http://dali.aizwys.cn/Article/details/gteqxykivw.html

[H07] 断言
来源：http://dali.meibo888.top/Article/details/gthxunaelz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gogol.net.cn/Article/details/gtezxynwww.html

PHP:  assert($x > 0);
来源：http://dali.yongpay.top/Article/details/gttajndbqj.html

JS:   console.assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gtqhzvdbta.html

TS:   console.assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gtjxyvwccr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cucudq.cn/Article/details/gttpsonlpi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pycfn.com/Article/details/gtrokidlpu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.mhx1999.top/Article/details/gtbezmaunq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtgevkaepy.html

[H08] 获取错误信息与堆栈
来源：http://dali.dashuyun.cn/Article/details/gtkuepeufj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.pengpengdd.cyou/Article/details/gtsgolbnsg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yuanzhike.top/Article/details/gtcwdszumw.html

JS:   e.message;  e.stack
来源：http://dali.sweek.top/Article/details/gteuzlwxys.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ivvv.top/Article/details/gtkdiicobz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.meibo888.top/Article/details/gtxwbirrcg.html

Go:   err.Error()
来源：http://dali.yuxming.cn/Article/details/gtxatbyfys.html

Ruby: e.message;  e.backtrace
来源：http://dali.pycfn.com/Article/details/gtpgoxfder.html

C#:   e.Message;  e.StackTrace
来源：http://dali.redwolf501.top/Article/details/gtuthpdavi.html

[H09] 带错误码的异常
来源：http://dali.jqgfzy.top/Article/details/gtdlskxtsg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cashguo.top/Article/details/gtxactrfxe.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangshuangyany.cn/Article/details/gtyvhsseex.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.guowangkeji.top/Article/details/gtrngxmqec.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xylfe.cn/Article/details/gtoeijpema.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shangyingyoupin.top/Article/details/gtuexnbpne.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.birdmap.top/Article/details/gtlqydeyov.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nanxuanxn.top/Article/details/gtapdonzvx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinqigufen.top/Article/details/gtlthczkzd.html

[H10] 资源自动释放
来源：http://dali.wangdashe.top/Article/details/gttwydampd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jyoumei.cn/Article/details/gthpyitxpu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.guannengcc.top/Article/details/gtxzghoafa.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gzhubu.top/Article/details/gtlvogmzoy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gtpdvfmofe.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj20258.top/Article/details/gtvwwalmas.html

Go:   defer f.Close()
来源：http://dali.hongshengwenyu.top/Article/details/gtrfizejie.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.birdmap.top/Article/details/gthvjnzsxd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yonumen.top/Article/details/gtohoeszbx.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtupppblog.html

I. 正则表达式
来源：http://dali.daxiang520.top/Article/details/gtksctkzlp.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtjjdcuyia.html

[I01] 判断是否匹配
来源：http://dali.yanxiufei.cn/Article/details/gtsyxcoxla.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.mhx1999.top/Article/details/gtndxhfmhf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoxzxduhc.html

JS:   /\d+/.test(s)
来源：http://dali.zhengqikj.top/Article/details/gtkvuloxuv.html

TS:   /\d+/.test(s)
来源：http://dali.pycfn.com/Article/details/gtyostmfoz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ybcxt.top/Article/details/gtfxzfwhwx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxfannur.html

Ruby: s.match?(/\d+/)
来源：http://dali.birdmap.top/Article/details/gtcfrqcycw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.fengsongda.top/Article/details/gtucwzpsst.html

[I02] 提取所有匹配
来源：http://dali.yuxming.cn/Article/details/gtzbqlytng.html

Py:   re.findall(r"\d+", s)
来源：http://dali.9152youxi.cn/Article/details/gtpxzyyics.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zycfv.cn/Article/details/gtkfioluee.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gotoacloud.top/Article/details/gtdaawuhrr.html

TS:   s.match(/\d+/g)
来源：http://dali.chenjidiqi.icu/Article/details/gtsvlyvxqn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtkamvsher.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sxryk.cn/Article/details/gtkwpmuqmr.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhoulong.xyz/Article/details/gtluguhfae.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.iojbl.cn/Article/details/gtyxqwggdl.html

[I03] 提取捕获分组
来源：http://dali.jqgufenzy.top/Article/details/gtaadguwbo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.guannengcc.top/Article/details/gtvreocuqo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gtccerjsrk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jyoumei.cn/Article/details/gtimghghdj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sweek.top/Article/details/gtjyjjufzf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gaohongyu789.top/Article/details/gtilxuxguu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zdqjudy.top/Article/details/gtqobwupry.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cucudq.cn/Article/details/gtbcfnuxhw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinghuilouyu.cn/Article/details/gtivfiydji.html

[I04] 正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbqhquwwd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcllbtkxq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenzaomai.com/Article/details/gtvsgzlxck.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nwbrower.top/Article/details/gtcpiubivj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guannengcc.top/Article/details/gtbqxlmjjd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.andypj.xyz/Article/details/gtqghkbsyt.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nwbrower.top/Article/details/gthcsvuzle.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cqqwz.cn/Article/details/gtaflhysks.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinqigfzy.top/Article/details/gtmctjfsqf.html

[I05] 按正则拆分
来源：http://dali.sysykeji.top/Article/details/gtithlsjuw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.c1oappe.top/Article/details/gtfysbwdqv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.guowangkeji.top/Article/details/gtehkgtbqx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gtehwltqjv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gtpcvvmfwq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hnqzz.top/Article/details/gtwmrgrjld.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.guowangkeji.top/Article/details/gtmruqsgii.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gtazmxlozr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xylfe.cn/Article/details/gtktfeuhwf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shangyingyoupin.top/Article/details/gthjoebuqt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gtsetwvury.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nanxuanxn.top/Article/details/gtjqgnimdf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtibefymnq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhoulong.xyz/Article/details/gtdpbmlxmd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gtliwwxnso.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenzaomai.com/Article/details/gtrynyrkbg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jyoumei.cn/Article/details/gtoibpmbwp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gtqlgtzbhk.html

[I07] 忽略大小写与多行模式
来源：http://dali.hammf.cn/Article/details/gttevbzyer.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.0kj1m.cn/Article/details/gtlkuxnxdk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gaohongyu789.top/Article/details/gtrlmzjahc.html


<!-- 参考信息 -->