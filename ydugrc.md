代发 wailian999

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsitsmotf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrrguyujd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hfpthk.cn/Article/details/gtypexvvvt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dashuyun.cn/Article/details/gtahbeyfzo.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtqzrftele.html

G. 面向对象
来源：http://dali.iojbl.cn/Article/details/gtfsuvuafi.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtmrrlbfso.html

[G01] 定义类
来源：http://dali.hammf.cn/Article/details/gtulekoysx.html

Py:   class User: pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmiwdwte.html

PHP:  class User {}
来源：http://dali.sufxvd.cn/Article/details/gtfeekpvgk.html

JS:   class User {}
来源：http://dali.jqgfzy.top/Article/details/gtknwblmng.html

TS:   class User { name: string = ""; }
来源：http://dali.sxryk.cn/Article/details/gtnugnkvix.html

Java: class User {}
来源：http://dali.nwbrower.top/Article/details/gttcwigtqx.html

Go:   type User struct { Name string }
来源：http://dali.aizwys.cn/Article/details/gtvdelblun.html

Ruby: class User; end
来源：http://dali.jianghu66.top/Article/details/gtpispqlsk.html

C#:   class User {}
来源：http://dali.yuanzhike.top/Article/details/gtmlsmzknb.html

[G02] 构造函数
来源：http://dali.0kj1m.cn/Article/details/gttmjgdtiv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenzaomai.com/Article/details/gtuhtlrhoc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jyoumei.cn/Article/details/gteewyjnoy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtevbkkvln.html

TS:   constructor(public name: string) {}
来源：http://dali.gotoacloud.top/Article/details/gtwrkwkaol.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gtejrkkepl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxuanxn.top/Article/details/gtyynatauc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gotoacloud.top/Article/details/gtpqxpgvcm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xuanzx.com/Article/details/gtyrtfxefe.html

[G03] 实例属性
来源：http://dali.shzxlz.cn/Article/details/gtuonrgogv.html

Py:   self.name = "x"
来源：http://dali.xinyue.icu/Article/details/gtnwwlooqv.html

PHP:  public string $name = "x";
来源：http://dali.fzhhl.top/Article/details/gtxrfcqsqh.html

JS:   this.name = "x";
来源：http://dali.9152youxi.cn/Article/details/gtqsevguod.html

TS:   name: string = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtrmnahjvp.html

Java: private String name;
来源：http://dali.yvedp.cn/Article/details/gtqtoqawfk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nanxuanxn.top/Article/details/gtrzqxvprn.html

Ruby: @name = "x"
来源：http://dali.aibaodan.cn/Article/details/gtierwdnuw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sweek.top/Article/details/gtyfoswark.html

[G04] 定义方法
来源：http://dali.iojbl.cn/Article/details/gtchrpgzuu.html

Py:   def greet(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gtlgwpzocj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gthcggdxrb.html

JS:   greet() { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtahtdchnj.html

TS:   greet(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtsqymlaja.html

Java: String greet() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gtkuqwkpvc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gtvbcgzvrl.html

Ruby: def greet; @name; end
来源：http://dali.yvedp.cn/Article/details/gtbwxfnhsm.html

C#:   public string Greet() => Name;
来源：http://dali.hammf.cn/Article/details/gtxfnzgqwi.html

[G05] 继承
来源：http://dali.zhiwuduotai.top/Article/details/gttgkefpdp.html

Py:   class Admin(User): pass
来源：http://dali.sxryk.cn/Article/details/gtfgprwqgn.html

PHP:  class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtyoaajcfl.html

JS:   class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gthupksmpf.html

TS:   class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtncolbhjh.html

Java: class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtnxglskcc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.meibo888.top/Article/details/gthtcomhai.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtocbghwhz.html

C#:   class Admin : User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtegdfsrpw.html

[G06] 重写方法
来源：http://dali.yuxming.cn/Article/details/gtnqundmhr.html

Py:   def greet(self): return "admin"
来源：http://dali.zhixingplan.top/Article/details/gtjgebclks.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gthdxnecbv.html

JS:   greet() { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtnlnwrhqd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtpxflvhwh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtnwxszlbs.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shangyingyoupin.top/Article/details/gtlaiajhqi.html

Ruby: def greet; "admin"; end
来源：http://dali.gaohongyu789.top/Article/details/gthmovfjpa.html

C#:   public override string Greet() => "admin";
来源：http://dali.c1oappe.top/Article/details/gtuwcyynel.html

[G07] 调用父类方法
来源：http://dali.zdqjudy.top/Article/details/gtweajdcnv.html

Py:   super().greet()
来源：http://dali.jinghuilouyu.cn/Article/details/gtywpuywji.html

PHP:  parent::greet();
来源：http://dali.sysykeji.top/Article/details/gtwahqeumc.html

JS:   super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzqdmubox.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtewqoweoh.html

Java: super.greet();
来源：http://dali.xinyue.icu/Article/details/gtlsisndtf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yvedp.cn/Article/details/gtqyalwhfc.html

Ruby: super
来源：http://dali.ppjwa.cn/Article/details/gtiswpsdpv.html

C#:   base.Greet();
来源：http://dali.aizwys.cn/Article/details/gtetjqlejs.html

[G08] 静态方法与属性
来源：http://dali.chenzaomai.com/Article/details/gthxphqqny.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shzxlz.cn/Article/details/gtvcxgnhmd.html

PHP:  public static function f() {}
来源：http://dali.fengsongda.top/Article/details/gtbpwdxevs.html

JS:   static f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtcqqenxpa.html

TS:   static f(): void {}
来源：http://dali.andypj.xyz/Article/details/gtgyujrjdi.html

Java: static void f() {}
来源：http://dali.ydzc1.top/Article/details/gtqviywcud.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinqigfzy.top/Article/details/gtuexnypty.html

Ruby: def self.f; end
来源：http://dali.jqgfzy.top/Article/details/gtdcwfqypu.html

C#:   public static void F() {}
来源：http://dali.xuanzx.com/Article/details/gtyobkcbhd.html

[G09] 接口 / 抽象类
来源：http://dali.quarkkingdee.top/Article/details/gtbayyrkno.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.0kj1m.cn/Article/details/gtqqskzzfq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cdnleiting.top/Article/details/gtkdsqkdqs.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hongshengwenyu.top/Article/details/gtiprfzgrl.html

TS:   interface Shape { area(): number; }
来源：http://dali.hfpthk.cn/Article/details/gtomyvgldy.html

Java: interface Shape { double area(); }
来源：http://dali.chenlongwang.top/Article/details/gtarzbfjiv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.svipenyu.cn/Article/details/gtathtmnan.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.316326.xyz/Article/details/gtrxhqxtxk.html

C#:   interface IShape { double Area(); }
来源：http://dali.c1oappe.top/Article/details/gttufywvnp.html

[G10] 访问控制
来源：http://dali.pycfn.com/Article/details/gttlxzikja.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhixingplan.top/Article/details/gtmjkqlaux.html

PHP:  public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gtqvlwupcs.html

JS:   #private 字段；其余公开
来源：http://dali.mhx1999.top/Article/details/gthedicgfc.html

TS:   public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gtkjyhkmvc.html

Java: public / protected / private / 默认包级
来源：http://dali.zhiwuduotai.top/Article/details/gtdqcwadmd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.snrcjt.cn/Article/details/gtgyjrqfyx.html

Ruby: public / protected / private
来源：http://dali.hnqzz.top/Article/details/gtlwhifqnb.html

C#:   public / protected / private / internal
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfahcioqe.html

[G11] getter / setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtitigsbbg.html

Py:   @property 与 @x.setter
来源：http://dali.xylfe.cn/Article/details/gtacyehymj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gtydyxkpeq.html

JS:   get name() { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gtbujmtryy.html

TS:   get name(): string { return this._name; }
来源：http://dali.fzhhl.top/Article/details/gtcrwmqpri.html

Java: public String getName() { return name; }
来源：http://dali.sxryk.cn/Article/details/gtizlpdmtf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gtzfiswjsw.html

Ruby: attr_accessor :name
来源：http://dali.nanxuanxn.top/Article/details/gtrhyxytmb.html

C#:   public string Name { get; set; }
来源：http://dali.yangfankeji.com/Article/details/gthxrkucgx.html

[G12] 对象转字符串
来源：http://dali.jyoumei.cn/Article/details/gtwknyyrnf.html

Py:   def __str__(self): return self.name
来源：http://dali.hammf.cn/Article/details/gtcuqrdrcr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gtdwahrren.html

JS:   toString() { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtcrgddenx.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gttksatokp.html

Java: @Override public String toString() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtayzjvwhq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtpbibxill.html

Ruby: def to_s; @name; end
来源：http://dali.nwbrower.top/Article/details/gtugmyummb.html

C#:   public override string ToString() => Name;
来源：http://dali.snrcjt.cn/Article/details/gtkmaaqkxh.html

[G13] 判断对象类型
来源：http://dali.havefunace.top/Article/details/gtfunifqsa.html

Py:   isinstance(u, User)
来源：http://dali.gaohongyu789.top/Article/details/gtfgrlpruv.html

PHP:  $u instanceof User
来源：http://dali.yueranfly.top/Article/details/gttmtegdqj.html

JS:   u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtvnepisfv.html

TS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtsmawbrlx.html

Java: u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gteehkfxtm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinqigufen.top/Article/details/gteykwdlco.html

Ruby: u.is_a?(User)
来源：http://dali.sufxvd.cn/Article/details/gtkqjxjrml.html

C#:   u is User
来源：http://dali.yj202588.top/Article/details/gtasmrjthv.html

[G14] 数据类 / record
来源：http://dali.jinqigfzy.top/Article/details/gtgkjteekz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xziqi.cn/Article/details/gtpryotwwk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmwvkuvdx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cqqwz.cn/Article/details/gtfmtlchzo.html

TS:   type User = { name: string; age: number };
来源：http://dali.birdmap.top/Article/details/gtlzlzhjda.html

Java: record User(String name, int age) {}
来源：http://dali.jlsjyb.cn/Article/details/gttrswikro.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnqzz.top/Article/details/gtzohycxkw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.aizwys.cn/Article/details/gtmxojhgst.html

C#:   record User(string Name, int Age);
来源：http://dali.chenjidiqi.icu/Article/details/gtkdesopfa.html

[G15] 枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtookchwbc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenlongwang.top/Article/details/gtbctzdiin.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nanxuanxn.top/Article/details/gtthookrug.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.316326.xyz/Article/details/gtsaegnvyh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hywenlv.cn/Article/details/gtqbhvbrbt.html

Java: enum Color { RED, GREEN }
来源：http://dali.dashuyun.cn/Article/details/gthvnmzesb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daxiang520.top/Article/details/gtragmsjyo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cucudq.cn/Article/details/gtojxtyihk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.andypj.xyz/Article/details/gtaeojcwvl.html

[G16] 对象转数组 / 字典
来源：http://dali.shangyingyoupin.top/Article/details/gtgubxludw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shangyingyoupin.top/Article/details/gtkhdaeujr.html

PHP:  get_object_vars($obj);
来源：http://dali.sysykeji.top/Article/details/gtttajfhrt.html

JS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gtstxabsnb.html

TS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gtejzsxkrj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnxiangtu.top/Article/details/gtufmbebdr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.redwolf501.top/Article/details/gtlnkfnlcr.html

Ruby: obj.instance_variables
来源：http://dali.gaohongyu789.top/Article/details/gtqxhwtuwh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.vqdsnc.cn/Article/details/gtfdcpresj.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtebiptasf.html

H. 异常与错误处理
来源：http://dali.zycfv.cn/Article/details/gtygnpiupl.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtkgcbhldt.html

[H01] try / catch 基础
来源：http://dali.meibo888.top/Article/details/gtzkahpnce.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.snrcjt.cn/Article/details/gtzjczppzb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shzxlz.cn/Article/details/gtgmokvpuj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gtongtizmr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gtlfsdhjxy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aizwys.cn/Article/details/gtkwbahncy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.aibaodan.cn/Article/details/gtoxhvddms.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sxryk.cn/Article/details/gtpiqnusll.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ybcxt.top/Article/details/gtgrzxjwwm.html

[H02] finally / ensure 收尾
来源：http://dali.kuanghao11.cn/Article/details/gtnatvbxkk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jianghu66.top/Article/details/gtzcuajfwy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtpnakkred.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtcqtozxyq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwdczwgbs.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtcnzsyiwg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tian-w.cn/Article/details/gtqjlvimxh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zdqjudy.top/Article/details/gtdymtlqvf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtmcvelzen.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtkfvfhcsa.html

Py:   raise ValueError("错误信息")
来源：http://dali.yvedp.cn/Article/details/gtwsilprjg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtrudingna.html

JS:   throw new Error("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtxfnkjyid.html

TS:   throw new Error("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtcingkrar.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtzkxhavfm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.fengsongda.top/Article/details/gtpkythbcd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hywenlv.cn/Article/details/gtgeoobvvh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtvdspperg.html

[H04] 自定义异常类型
来源：http://dali.hammf.cn/Article/details/gtxfkkwrrh.html

Py:   class MyError(Exception): pass
来源：http://dali.svipenyu.cn/Article/details/gtnlhwecwe.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fzhhl.top/Article/details/gtbzpxboup.html

JS:   class MyError extends Error {}
来源：http://dali.zhongyouzk.top/Article/details/gtsxypwjgh.html

TS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gtisardlsq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gtinddirmr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yongpay.top/Article/details/gtcsieizlv.html

Ruby: class MyError < StandardError; end
来源：http://dali.vqdsnc.cn/Article/details/gthzuuvqlh.html

C#:   class MyException : Exception {}
来源：http://dali.fengsongda.top/Article/details/gtedbioyec.html

[H05] 捕获特定类型
来源：http://dali.jinqigfzy.top/Article/details/gtwdopzwfv.html

Py:   except ValueError as e:
来源：http://dali.hysaishi.cn/Article/details/gtwpbywpwi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gttlgrtgqn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cqqwz.cn/Article/details/gtejvhqicu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zdqjudy.top/Article/details/gttqxgtkls.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ppjwa.cn/Article/details/gtnziowhsi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenlongwang.top/Article/details/gtgdjukzhb.html

Ruby: rescue ArgumentError => e
来源：http://dali.tanke756.top/Article/details/gtiipcvyto.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtkgzvtjfx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.aizwys.cn/Article/details/gtxhgeorsq.html

Py:   value = d.get("k") or default
来源：http://dali.hnxiangtu.top/Article/details/gtrxwtcqcn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cqqwz.cn/Article/details/gtqdirevvu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zycfv.cn/Article/details/gtpuqmjsua.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gtambroqbv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hammf.cn/Article/details/gtxwtrjefh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nanxinkj.top/Article/details/gtqczucgfi.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnxiangtu.top/Article/details/gtugwohviv.html

C#:   obj?.A?.B ?? default
来源：http://dali.ydzc1.top/Article/details/gtqbsffxpu.html

[H07] 断言
来源：http://dali.jyoumei.cn/Article/details/gtmcagwuue.html

Py:   assert x > 0, "必须为正"
来源：http://dali.daxiang520.top/Article/details/gtqcrccwnm.html

PHP:  assert($x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtjtfjsuyb.html

JS:   console.assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gtwineelda.html

TS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtlsvebjww.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yanxiufei.cn/Article/details/gtmcpnfwql.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hongshengwenyu.top/Article/details/gtgblozymn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zycfv.cn/Article/details/gtzmwuloxy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtogseoylt.html

[H08] 获取错误信息与堆栈
来源：http://dali.cheryme.top/Article/details/gtsixoaxrf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.guannengcc.top/Article/details/gtobstlxcc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigfzy.top/Article/details/gtnkwbxfcx.html

JS:   e.message;  e.stack
来源：http://dali.dashuyun.cn/Article/details/gtrltnnuop.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.dianchejie.cn/Article/details/gtdxdxuzbo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ehwqpu.com/Article/details/gtdonovgyp.html

Go:   err.Error()
来源：http://dali.iojbl.cn/Article/details/gtufoydsba.html

Ruby: e.message;  e.backtrace
来源：http://dali.yanxiufei.cn/Article/details/gtnsvhvkqp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.havefunace.top/Article/details/gtkvkzbqqm.html

[H09] 带错误码的异常
来源：http://dali.sufxvd.cn/Article/details/gtlgtjfhoo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hammf.cn/Article/details/gtesizgoik.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.haohaochexian.top/Article/details/gtnljzwmtl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.iojbl.cn/Article/details/gtfvkyvatd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenjidiqi.icu/Article/details/gtbfkbatoi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ivvv.top/Article/details/gthzcrmdej.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhixingplan.top/Article/details/gtdzokrsio.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zdqjudy.top/Article/details/gtjkpjtbin.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fzhhl.top/Article/details/gtmunlczom.html

[H10] 资源自动释放
来源：http://dali.vqdsnc.cn/Article/details/gtstmhwjah.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgumoaqvg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hysaishi.cn/Article/details/gtyxtbacnw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gtzacuftls.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gterdqkfhw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hnxiangtu.top/Article/details/gtdxjxkivz.html

Go:   defer f.Close()
来源：http://dali.yj20258888.top/Article/details/gtzgzasgez.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.quarkkingdee.top/Article/details/gtqjoeolek.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj202588.top/Article/details/gtppipkngq.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gthwovjnui.html

I. 正则表达式
来源：http://dali.hnqzz.top/Article/details/gtotynjzgh.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtzwaxxjez.html

[I01] 判断是否匹配
来源：http://dali.gaohongyu789.top/Article/details/gtggblxfuq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.dianchejie.cn/Article/details/gtwmixjyrj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtokxsaewu.html

JS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gtjlxqydvq.html

TS:   /\d+/.test(s)
来源：http://dali.smart0.xyz/Article/details/gtnmnedhlt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.andypj.xyz/Article/details/gtkpqnlxdm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gaohongyu789.top/Article/details/gtfjstoopx.html

Ruby: s.match?(/\d+/)
来源：http://dali.zdqjudy.top/Article/details/gtolbiiukw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnxiangtu.top/Article/details/gtutzuwdhw.html

[I02] 提取所有匹配
来源：http://dali.hammf.cn/Article/details/gtsnigknbh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xziqi.cn/Article/details/gtjltjsfbn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hfpthk.cn/Article/details/gtuzbcuozx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxinkj.top/Article/details/gtqupzbglj.html

TS:   s.match(/\d+/g)
来源：http://dali.dianchejie.cn/Article/details/gtjyolpdoh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hysaishi.cn/Article/details/gtdhvfacqo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yanxiufei.cn/Article/details/gtgjfjbgrl.html

Ruby: s.scan(/\d+/)
来源：http://dali.cucudq.cn/Article/details/gttkrpppoa.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtuafmlwuy.html

[I03] 提取捕获分组
来源：http://dali.jlsjyb.cn/Article/details/gtiecshstt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbgtmwwbj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxinkj.top/Article/details/gtfaskrbmt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gzhubu.top/Article/details/gtvzsmogpi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tanke756.top/Article/details/gthdsgkdww.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gtnbfeylrn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sxryk.cn/Article/details/gtwbyjgrsp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinqigufen.top/Article/details/gtxfaxvskb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinqigfzy.top/Article/details/gtnxfpmlvh.html

[I04] 正则替换
来源：http://dali.xuetiantiany.cn/Article/details/gtvaoepkdh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jqgufenzy.top/Article/details/gtcauztczn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.meibo888.top/Article/details/gtepngybfd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gtoiekadzj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shuidangran.top/Article/details/gtcfxlvqme.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.andypj.xyz/Article/details/gtuxphqkbn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenzaomai.com/Article/details/gtojmxzxse.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjchinlbk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.svipenyu.cn/Article/details/gtxfsicdis.html

[I05] 按正则拆分
来源：http://dali.daxiang520.top/Article/details/gtnwhyazes.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shzxlz.cn/Article/details/gthxjjrvqo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtikpuytbx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gtievhbmrn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gtiwzsffcp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.bjfxy.top/Article/details/gtlgimuvvq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenjidiqi.icu/Article/details/gtxfzfpeos.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gtlqsniukt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjjznltwu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xuetiantiany.cn/Article/details/gtkesrzdfb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cheryme.top/Article/details/gtcxetkvyp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhoulong.xyz/Article/details/gtaxoemmyi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cqqwz.cn/Article/details/gtyrmkknvh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shzxlz.cn/Article/details/gttjbsvuqq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.birdmap.top/Article/details/gtvvgdbqsx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xylfe.cn/Article/details/gteacpjrhe.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jlsjyb.cn/Article/details/gthivrfqqg.html


<!-- 参考信息 -->