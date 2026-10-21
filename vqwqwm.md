代发 wailian999

Py:   class User: pass
来源：http://dali.daria6918.cn/Article/details/gthyrngfwq.html

PHP:  class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtflpkswaa.html

JS:   class User {}
来源：http://dali.jqgfzy.top/Article/details/gtbfuslmiy.html

TS:   class User { name: string = ""; }
来源：http://dali.xuanzx.com/Article/details/gtrjoxdaeh.html

Java: class User {}
来源：http://dali.hnxiangtu.top/Article/details/gthhsuaqec.html

Go:   type User struct { Name string }
来源：http://dali.fengsongda.top/Article/details/gtcyllejhp.html

Ruby: class User; end
来源：http://dali.jqgfzy.top/Article/details/gtutbgufef.html

C#:   class User {}
来源：http://dali.jqgufenzy.top/Article/details/gthpoglvsr.html

[G02] 构造函数
来源：http://dali.vqdsnc.cn/Article/details/gtyoztjjcm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gzhubu.top/Article/details/gtcedfrajx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258.top/Article/details/gtigsulgui.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hfpthk.cn/Article/details/gtqzphidew.html

TS:   constructor(public name: string) {}
来源：http://dali.tanke756.top/Article/details/gtbojmzqon.html

Java: User(String name) { this.name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtcszlwcge.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gtaywlibkv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cucudq.cn/Article/details/gtxvpzebvp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gtpvfldqce.html

[G03] 实例属性
来源：http://dali.xuanzx.com/Article/details/gtrudqojzt.html

Py:   self.name = "x"
来源：http://dali.hongshengwenyu.top/Article/details/gtzlsexkuz.html

PHP:  public string $name = "x";
来源：http://dali.birdmap.top/Article/details/gtweaewqzc.html

JS:   this.name = "x";
来源：http://dali.tanke756.top/Article/details/gtorblqxho.html

TS:   name: string = "x";
来源：http://dali.guannengcc.top/Article/details/gtxqimyuxb.html

Java: private String name;
来源：http://dali.yj20258.top/Article/details/gtbbfpqqje.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenzaomai.com/Article/details/gtdxceapci.html

Ruby: @name = "x"
来源：http://dali.andypj.xyz/Article/details/gtqwfrsyaf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhixingplan.top/Article/details/gtlbhgrhii.html

[G04] 定义方法
来源：http://dali.xuetiantiany.cn/Article/details/gtmqiqlmsa.html

Py:   def greet(self): return self.name
来源：http://dali.hammf.cn/Article/details/gtpbsjfryw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gtjbanvars.html

JS:   greet() { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtcptqeytu.html

TS:   greet(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gthlavafgb.html

Java: String greet() { return name; }
来源：http://dali.wangdashe.top/Article/details/gtfcjafgwy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gtgzzlorru.html

Ruby: def greet; @name; end
来源：http://dali.shzxlz.cn/Article/details/gtlmsfvncs.html

C#:   public string Greet() => Name;
来源：http://dali.yvedp.cn/Article/details/gtidbdtika.html

[G05] 继承
来源：http://dali.sxryk.cn/Article/details/gthjnrsttl.html

Py:   class Admin(User): pass
来源：http://dali.xuanzx.com/Article/details/gttcamprfs.html

PHP:  class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gtsqycrjvh.html

JS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjoudcngj.html

TS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gthxobbhfp.html

Java: class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtujjenbbm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hnqzz.top/Article/details/gtrfackhcb.html

Ruby: class Admin < User; end
来源：http://dali.redwolf501.top/Article/details/gtrljjtcnn.html

C#:   class Admin : User {}
来源：http://dali.dianchejie.cn/Article/details/gtddkgzenm.html

[G06] 重写方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmeqwnldb.html

Py:   def greet(self): return "admin"
来源：http://dali.hfpthk.cn/Article/details/gtqvszaqtp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gtabaoxcoo.html

JS:   greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtccvgghbz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtcmadnbex.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtyiedduzn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.kuanghao11.cn/Article/details/gtryycrqmm.html

Ruby: def greet; "admin"; end
来源：http://dali.havefunace.top/Article/details/gtfgytyzmx.html

C#:   public override string Greet() => "admin";
来源：http://dali.zdqjudy.top/Article/details/gtdczqlbly.html

[G07] 调用父类方法
来源：http://dali.cqqwz.cn/Article/details/gtpdefxawr.html

Py:   super().greet()
来源：http://dali.ydzc1.top/Article/details/gtalnbcmef.html

PHP:  parent::greet();
来源：http://dali.cashguo.top/Article/details/gtlpublanq.html

JS:   super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtztonnxjc.html

TS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtzvwnuiyr.html

Java: super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtkobjhqab.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sweek.top/Article/details/gtqywsbgpy.html

Ruby: super
来源：http://dali.xuanzx.com/Article/details/gttqfqowhj.html

C#:   base.Greet();
来源：http://dali.bjfxy.top/Article/details/gtneuvqaov.html

[G08] 静态方法与属性
来源：http://dali.aizwys.cn/Article/details/gtynwbtmxx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj202588.top/Article/details/gtxovfduvc.html

PHP:  public static function f() {}
来源：http://dali.cashguo.top/Article/details/gtozpmjcuy.html

JS:   static f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtwxzfcvow.html

TS:   static f(): void {}
来源：http://dali.c1oappe.top/Article/details/gtyuhnqpmr.html

Java: static void f() {}
来源：http://dali.aibaodan.cn/Article/details/gtymtgnqil.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.bjfxy.top/Article/details/gtxvdujilo.html

Ruby: def self.f; end
来源：http://dali.zhongyouzk.top/Article/details/gticbpwqev.html

C#:   public static void F() {}
来源：http://dali.zhengqikj.top/Article/details/gtwepfabbr.html

[G09] 接口 / 抽象类
来源：http://dali.gogol.net.cn/Article/details/gtibifnqcx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoghouuxv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenjidiqi.icu/Article/details/gtgazhzzoj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jianghu66.top/Article/details/gtalsxmrve.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangdashe.top/Article/details/gtauukahfo.html

Java: interface Shape { double area(); }
来源：http://dali.zhoulong.xyz/Article/details/gtzbjunchh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zdqjudy.top/Article/details/gtbscffjxj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yongpay.top/Article/details/gtcxtfbnen.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdaemsthh.html

[G10] 访问控制
来源：http://dali.ehwqpu.com/Article/details/gtsyjqskjf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yongpay.top/Article/details/gtoouotiuk.html

PHP:  public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gtxnxjwdrw.html

JS:   #private 字段；其余公开
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpgfphvnr.html

TS:   public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtbfujzsbi.html

Java: public / protected / private / 默认包级
来源：http://dali.snrcjt.cn/Article/details/gtppbbznjn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.kuanghao11.cn/Article/details/gtuakfikzc.html

Ruby: public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtybzohybf.html

C#:   public / protected / private / internal
来源：http://dali.nwbrower.top/Article/details/gtszehegfv.html

[G11] getter / setter
来源：http://dali.chenlongwang.top/Article/details/gtvnnkupbk.html

Py:   @property 与 @x.setter
来源：http://dali.sufxvd.cn/Article/details/gtesadltaj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gthulfmwlt.html

JS:   get name() { return this._name; }
来源：http://dali.fzhhl.top/Article/details/gtvxtgeysy.html

TS:   get name(): string { return this._name; }
来源：http://dali.jqgfzy.top/Article/details/gtecawixed.html

Java: public String getName() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtsfqpeciv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gtdlncuvhv.html

Ruby: attr_accessor :name
来源：http://dali.zdqjudy.top/Article/details/gtuffrsbel.html

C#:   public string Name { get; set; }
来源：http://dali.smart0.xyz/Article/details/gtmylbvdgr.html

[G12] 对象转字符串
来源：http://dali.vqdsnc.cn/Article/details/gtvfxqkkzi.html

Py:   def __str__(self): return self.name
来源：http://dali.shuidangran.top/Article/details/gtfvwwgzbo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gtdheprdyw.html

JS:   toString() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gttgjecloi.html

TS:   toString(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtxtnoyfbs.html

Java: @Override public String toString() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtvlcbsdoa.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtolmudaax.html

Ruby: def to_s; @name; end
来源：http://dali.cucudq.cn/Article/details/gtirxkpkly.html

C#:   public override string ToString() => Name;
来源：http://dali.hywenlv.cn/Article/details/gtgsopgcfs.html

[G13] 判断对象类型
来源：http://dali.zhiwuduotai.top/Article/details/gtruslbflg.html

Py:   isinstance(u, User)
来源：http://dali.feifeiyinyue.top/Article/details/gtziqfjyay.html

PHP:  $u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtknclprzm.html

JS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtcvsnpklb.html

TS:   u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtfmtwukph.html

Java: u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtyklbqglf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj202588.top/Article/details/gtifzbptyz.html

Ruby: u.is_a?(User)
来源：http://dali.xinyue.icu/Article/details/gtubtbbjcx.html

C#:   u is User
来源：http://dali.snrcjt.cn/Article/details/gtzkwpmqdu.html

[G14] 数据类 / record
来源：http://dali.ivvv.top/Article/details/gtfvzaftlb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhongyouzk.top/Article/details/gtczghnybn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yangfankeji.com/Article/details/gtoogqmstw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ehwqpu.com/Article/details/gtsfnxfkua.html

TS:   type User = { name: string; age: number };
来源：http://dali.feifeiyinyue.top/Article/details/gtfedcurpw.html

Java: record User(String name, int age) {}
来源：http://dali.chenlongwang.top/Article/details/gtlqahfcwe.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ydzc1.top/Article/details/gtfynqzfbb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.vqdsnc.cn/Article/details/gtbmamlunm.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigufen.top/Article/details/gtjslzcssn.html

[G15] 枚举
来源：http://dali.cdnleiting.top/Article/details/gtjdfuttpg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.kuanghao11.cn/Article/details/gtsxmzptgo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.kuanghao11.cn/Article/details/gtzzqsmoga.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xinyue.icu/Article/details/gtahkimqzr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gtiqukqbkr.html

Java: enum Color { RED, GREEN }
来源：http://dali.jianghu66.top/Article/details/gttlowcpop.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hysaishi.cn/Article/details/gtnrjiwbqa.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hongshengwenyu.top/Article/details/gtcisnagwi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gtnuobykiw.html

[G16] 对象转数组 / 字典
来源：http://dali.tianlin.xyz/Article/details/gtwruyvxcs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hnxiangtu.top/Article/details/gtytgdotst.html

PHP:  get_object_vars($obj);
来源：http://dali.yanxiufei.cn/Article/details/gtikzccgoe.html

JS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gtwftcadoh.html

TS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gtzrnlfyuz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnqzz.top/Article/details/gtxdrsgheh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.pengpengdd.cyou/Article/details/gtpzpugdwz.html

Ruby: obj.instance_variables
来源：http://dali.vqdsnc.cn/Article/details/gtgbtwnufi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gtztvkwbdi.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtuxmqrhsb.html

H. 异常与错误处理
来源：http://dali.yj20258.top/Article/details/gteldhomxt.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtkkcxfjnh.html

[H01] try / catch 基础
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteadawfqu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gogol.net.cn/Article/details/gtvkczmtut.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.316326.xyz/Article/details/gtifzbppgv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gtcecofgkg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gtitdetuka.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqcvdunv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj202588.top/Article/details/gtjichsslk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj202588.top/Article/details/gtjajzxvlm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jlsjyb.cn/Article/details/gtplljvlob.html

[H02] finally / ensure 收尾
来源：http://dali.zhoulong.xyz/Article/details/gtfvmdrrtn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.redwolf501.top/Article/details/gtbaqmuozy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtrpdetcnm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjettgym.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtqrpnnuft.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtuxiqwzpj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnxiangtu.top/Article/details/gtyklwcsel.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.0kj1m.cn/Article/details/gtddcvvgbl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtxnjghzwz.html

[H03] 主动抛出异常
来源：http://dali.sxryk.cn/Article/details/gtolemrkfw.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258888.top/Article/details/gtoboozmqh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gttreflayp.html

JS:   throw new Error("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gttvmwnfpz.html

TS:   throw new Error("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtctefclaa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtdwmfbxuj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jyoumei.cn/Article/details/gtzgfqoqqb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nanxinkj.top/Article/details/gtqgqgrgch.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtijkkotyr.html

[H04] 自定义异常类型
来源：http://dali.hammf.cn/Article/details/gtcojfhyay.html

Py:   class MyError(Exception): pass
来源：http://dali.ivvv.top/Article/details/gtzmmysnyj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gtckfaeyhd.html

JS:   class MyError extends Error {}
来源：http://dali.chenzaomai.com/Article/details/gtkhychgxc.html

TS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gtoiboponb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhoulong.xyz/Article/details/gthkswrywi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.meibo888.top/Article/details/gtxntyzghd.html

Ruby: class MyError < StandardError; end
来源：http://dali.tian-w.cn/Article/details/gtqitlrvkh.html

C#:   class MyException : Exception {}
来源：http://dali.zhengqikj.top/Article/details/gtzosthifz.html

[H05] 捕获特定类型
来源：http://dali.snrcjt.cn/Article/details/gthfanrulz.html

Py:   except ValueError as e:
来源：http://dali.sysykeji.top/Article/details/gtcroaaeot.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.snrcjt.cn/Article/details/gtgolyqxom.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ppjwa.cn/Article/details/gtfkgsuekp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.wangdashe.top/Article/details/gtebullqkc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuanzhike.top/Article/details/gtjgfgdnhf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigufen.top/Article/details/gtszxtxnrn.html

Ruby: rescue ArgumentError => e
来源：http://dali.tanke756.top/Article/details/gtkonmsydz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj20258888.top/Article/details/gthlysntoq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zdqjudy.top/Article/details/gtndiompxm.html

Py:   value = d.get("k") or default
来源：http://dali.daxiang520.top/Article/details/gtchnjrnpr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmlbnhagu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxinkj.top/Article/details/gtszbthrye.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.pycfn.com/Article/details/gttasvpmjw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hfpthk.cn/Article/details/gtkscyofgq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jianghu66.top/Article/details/gtdhnreewq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnctuvdr.html

C#:   obj?.A?.B ?? default
来源：http://dali.hammf.cn/Article/details/gtfytfgmhz.html

[H07] 断言
来源：http://dali.aibaodan.cn/Article/details/gtmosggofq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.svipenyu.cn/Article/details/gtaerxahny.html

PHP:  assert($x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtwaukxpnv.html

JS:   console.assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gtuuzlmegk.html

TS:   console.assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gtbljkcaik.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shzxlz.cn/Article/details/gtchurrets.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.vqdsnc.cn/Article/details/gtffjcrnso.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenzaomai.com/Article/details/gtkyhgbfhs.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gtbxodydka.html

[H08] 获取错误信息与堆栈
来源：http://dali.ydzc1.top/Article/details/gtfrhxptlw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nwbrower.top/Article/details/gtizzxejib.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigufen.top/Article/details/gtwkoqxztm.html

JS:   e.message;  e.stack
来源：http://dali.birdmap.top/Article/details/gteznvvues.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxuanxn.top/Article/details/gtlcnqpsgw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpmnvwmtj.html

Go:   err.Error()
来源：http://dali.yongpay.top/Article/details/gtwopswqso.html

Ruby: e.message;  e.backtrace
来源：http://dali.jianghu66.top/Article/details/gtxahkksff.html

C#:   e.Message;  e.StackTrace
来源：http://dali.daxiang520.top/Article/details/gtwhuzkztz.html

[H09] 带错误码的异常
来源：http://dali.ppjwa.cn/Article/details/gtfshhlxhl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xuetiantiany.cn/Article/details/gtsqwvyvqg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.guowangkeji.top/Article/details/gtdacwwxth.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.c1oappe.top/Article/details/gtwvqfizcd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xuetiantiany.cn/Article/details/gtshzgglxn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ydzc1.top/Article/details/gtvplafhhk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtawkiksbx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jqgfzy.top/Article/details/gtxfuaekjx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.svipenyu.cn/Article/details/gtswdnrxge.html

[H10] 资源自动释放
来源：http://dali.xziqi.cn/Article/details/gticurmpwf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinqigfzy.top/Article/details/gtvzfijpja.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zdqjudy.top/Article/details/gtlxxzdelb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gtagdqgwpd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gtswjefxog.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gogol.net.cn/Article/details/gtjdeivbin.html

Go:   defer f.Close()
来源：http://dali.yangfankeji.com/Article/details/gtlvgiwxyi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.daxiang520.top/Article/details/gtjexzqqtj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sweek.top/Article/details/gtllypnhnp.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtzwxadyuq.html

I. 正则表达式
来源：http://dali.hammf.cn/Article/details/gtjfhlhugr.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtjelxeekg.html

[I01] 判断是否匹配
来源：http://dali.gogol.net.cn/Article/details/gthdufszyh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jyoumei.cn/Article/details/gtfzbxzfqs.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.haohaochexian.top/Article/details/gtfiutjjws.html

JS:   /\d+/.test(s)
来源：http://dali.cqqwz.cn/Article/details/gtiztheslw.html

TS:   /\d+/.test(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtzxtqgfmz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ybcxt.top/Article/details/gtelufpoww.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ppjwa.cn/Article/details/gtbzqjftss.html

Ruby: s.match?(/\d+/)
来源：http://dali.yueranfly.top/Article/details/gtmpabqjcq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hywenlv.cn/Article/details/gtvwqenyrz.html

[I02] 提取所有匹配
来源：http://dali.tanke756.top/Article/details/gtlbvwanzn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hfpthk.cn/Article/details/gtrolxdbbi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenlongwang.top/Article/details/gtpkzqteei.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shuidangran.top/Article/details/gtrdrryrik.html

TS:   s.match(/\d+/g)
来源：http://dali.bjfxy.top/Article/details/gtyprcvbrp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenzaomai.com/Article/details/gtojqpwgpq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhengqikj.top/Article/details/gtatzbqoey.html

Ruby: s.scan(/\d+/)
来源：http://dali.xuetiantiany.cn/Article/details/gtmzlnlgef.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zycfv.cn/Article/details/gtbhsdwbyx.html

[I03] 提取捕获分组
来源：http://dali.yvedp.cn/Article/details/gtotkvlrql.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtbfdnjazy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiiutugnd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.aibaodan.cn/Article/details/gtsizvmvvn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shangyingyoupin.top/Article/details/gteblrgcts.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hywenlv.cn/Article/details/gtnvecvhcb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.9152youxi.cn/Article/details/gtqwwzokoq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jiagoushi.top/Article/details/gtrrcuxmad.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yuxming.cn/Article/details/gtutowowdw.html

[I04] 正则替换
来源：http://dali.kuanghao11.cn/Article/details/gtgtecavkv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cqqwz.cn/Article/details/gtvdqssicd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xylfe.cn/Article/details/gtolqnchvb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yuxming.cn/Article/details/gtylskcbiv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.0kj1m.cn/Article/details/gtxvwqzbzc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gtwouhozdd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtzoaqdtmx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.pycfn.com/Article/details/gtdrycrfgr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhongyouzk.top/Article/details/gtglvarfyh.html

[I05] 按正则拆分
来源：http://dali.jyoumei.cn/Article/details/gtvurbsdki.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.andypj.xyz/Article/details/gtvleyojcw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtkcgrbbvu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zycfv.cn/Article/details/gtsvwbjebl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gtqpvcujzy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinqigufen.top/Article/details/gtgpkhonmb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlupcmuje.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zycfv.cn/Article/details/gtdxahdnom.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.0kj1m.cn/Article/details/gtpvsxdsoj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigfzy.top/Article/details/gtplfuzkis.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gtdyxjcdhi.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.feifeiyinyue.top/Article/details/gtpdccoflv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yueranfly.top/Article/details/gtpggymzqu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangdashe.top/Article/details/gteidghvug.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gtdscyudbi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.daxiang520.top/Article/details/gtarudyguq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.meibo888.top/Article/details/gtxiqthkae.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gtkqqqkhmi.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj20258888.top/Article/details/gtekgbyvts.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.andypj.xyz/Article/details/gtfsrzicah.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yanxiufei.cn/Article/details/gtzwdqkais.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.quarkkingdee.top/Article/details/gtsjkyvwmv.html

TS:   /error/gim
来源：http://dali.yonumen.top/Article/details/gtgvxgnvaf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.iojbl.cn/Article/details/gtujzceprt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gzhubu.top/Article/details/gtehuckrie.html


<!-- 参考信息 -->