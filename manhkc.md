代发 wailian999

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cheryme.top/Article/details/gtwaqcqamu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj20258888.top/Article/details/gtdvcoccpt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xinyue.icu/Article/details/gtjvokreyu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258.top/Article/details/gtfngivrjr.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtiuaqgtdq.html

G. 面向对象
来源：http://dali.haohaochexian.top/Article/details/gtvxtwsbil.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtxvxltzlb.html

[G01] 定义类
来源：http://dali.sxryk.cn/Article/details/gtvluzaqmp.html

Py:   class User: pass
来源：http://dali.meibo888.top/Article/details/gtunkjrorw.html

PHP:  class User {}
来源：http://dali.dashuyun.cn/Article/details/gtdiaboent.html

JS:   class User {}
来源：http://dali.sysykeji.top/Article/details/gtgpbjtzzh.html

TS:   class User { name: string = ""; }
来源：http://dali.wangdashe.top/Article/details/gtdjxfvrdv.html

Java: class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtnpclghid.html

Go:   type User struct { Name string }
来源：http://dali.jlsjyb.cn/Article/details/gtcuajeier.html

Ruby: class User; end
来源：http://dali.xuetiantiany.cn/Article/details/gtvdlbedxh.html

C#:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtcsboxqnp.html

[G02] 构造函数
来源：http://dali.yj202588.top/Article/details/gtjwsmuxqa.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aibaodan.cn/Article/details/gtespmfyov.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yuxming.cn/Article/details/gthhjszsbg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nanxinkj.top/Article/details/gtzndapbzv.html

TS:   constructor(public name: string) {}
来源：http://dali.bjfxy.top/Article/details/gtcuubmyla.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtztnueesx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtluuymnwz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xziqi.cn/Article/details/gtfjrfncpz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwudixxbg.html

[G03] 实例属性
来源：http://dali.zhoulong.xyz/Article/details/gtnxjvtpqd.html

Py:   self.name = "x"
来源：http://dali.yangfankeji.com/Article/details/gttcfeuqpk.html

PHP:  public string $name = "x";
来源：http://dali.aizwys.cn/Article/details/gtetbtgbya.html

JS:   this.name = "x";
来源：http://dali.ivvv.top/Article/details/gtiftzbtdo.html

TS:   name: string = "x";
来源：http://dali.gotoacloud.top/Article/details/gtdjywbkhi.html

Java: private String name;
来源：http://dali.daxiang520.top/Article/details/gtizaousdw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.guowangkeji.top/Article/details/gtiuchtkgm.html

Ruby: @name = "x"
来源：http://dali.shuidangran.top/Article/details/gtazomyiog.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sweek.top/Article/details/gtzmipinga.html

[G04] 定义方法
来源：http://dali.guannengcc.top/Article/details/gtdwiqfmpz.html

Py:   def greet(self): return self.name
来源：http://dali.yongpay.top/Article/details/gtehlmqvhi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gtrwqsjvxo.html

JS:   greet() { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtosajibba.html

TS:   greet(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gttnqanrdc.html

Java: String greet() { return name; }
来源：http://dali.yj20258888.top/Article/details/gtroxofabb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gtguyjfrcj.html

Ruby: def greet; @name; end
来源：http://dali.nanxuanxn.top/Article/details/gthpjndopv.html

C#:   public string Greet() => Name;
来源：http://dali.jianghu66.top/Article/details/gtmkhsajgw.html

[G05] 继承
来源：http://dali.hfpthk.cn/Article/details/gtrafxfwse.html

Py:   class Admin(User): pass
来源：http://dali.cdnleiting.top/Article/details/gtlfkohpnc.html

PHP:  class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtkjwbsqtz.html

JS:   class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtriwfzbrt.html

TS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtrrmippvs.html

Java: class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gtlfctxyhe.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.pengpengdd.cyou/Article/details/gtgzsyxjdk.html

Ruby: class Admin < User; end
来源：http://dali.fzhhl.top/Article/details/gthskjtgzc.html

C#:   class Admin : User {}
来源：http://dali.aizwys.cn/Article/details/gtqdohyywj.html

[G06] 重写方法
来源：http://dali.andypj.xyz/Article/details/gtyukmlpmx.html

Py:   def greet(self): return "admin"
来源：http://dali.feifeiyinyue.top/Article/details/gtlvpdubef.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtqdnfiova.html

JS:   greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtrjehallh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbdldccbh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtergtihgf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tianlin.xyz/Article/details/gtiefswzrd.html

Ruby: def greet; "admin"; end
来源：http://dali.chenzaomai.com/Article/details/gtmdjwkcre.html

C#:   public override string Greet() => "admin";
来源：http://dali.hongshengwenyu.top/Article/details/gtexhvsjpf.html

[G07] 调用父类方法
来源：http://dali.xuetiantiany.cn/Article/details/gtcttoagtp.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gtgbqmibty.html

PHP:  parent::greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtnoxwawba.html

JS:   super.greet();
来源：http://dali.jqgfzy.top/Article/details/gtgddnzsak.html

TS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtqhayvrhr.html

Java: super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnkziqvvc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.birdmap.top/Article/details/gtvfndevda.html

Ruby: super
来源：http://dali.yueranfly.top/Article/details/gtmvrymsls.html

C#:   base.Greet();
来源：http://dali.zdqjudy.top/Article/details/gtlbggwquc.html

[G08] 静态方法与属性
来源：http://dali.tian-w.cn/Article/details/gtvyxvqpth.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nanxuanxn.top/Article/details/gtkxhtgiso.html

PHP:  public static function f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtplimwyoq.html

JS:   static f() {}
来源：http://dali.daria6918.cn/Article/details/gtzzcqyasq.html

TS:   static f(): void {}
来源：http://dali.ppjwa.cn/Article/details/gthcgsltfz.html

Java: static void f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtkxcleztp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ehwqpu.com/Article/details/gtvujxmjqd.html

Ruby: def self.f; end
来源：http://dali.smart0.xyz/Article/details/gtdihttfya.html

C#:   public static void F() {}
来源：http://dali.guowangkeji.top/Article/details/gtykvgwduq.html

[G09] 接口 / 抽象类
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfvhfohug.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ehwqpu.com/Article/details/gtnlmylfhf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hywenlv.cn/Article/details/gtsxjrnger.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.smart0.xyz/Article/details/gtokecgyle.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenjidiqi.icu/Article/details/gtdennxzjn.html

Java: interface Shape { double area(); }
来源：http://dali.hfpthk.cn/Article/details/gtnssjzekd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhengqikj.top/Article/details/gtwoczqguf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ehwqpu.com/Article/details/gtvgrbjliy.html

C#:   interface IShape { double Area(); }
来源：http://dali.cqqwz.cn/Article/details/gtmwgavomb.html

[G10] 访问控制
来源：http://dali.yuanzhike.top/Article/details/gtwsyjziuu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jyoumei.cn/Article/details/gtrbkdmtsw.html

PHP:  public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzlpainwj.html

JS:   #private 字段；其余公开
来源：http://dali.ivvv.top/Article/details/gtmnapxoru.html

TS:   public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gtxvmrtwxk.html

Java: public / protected / private / 默认包级
来源：http://dali.xziqi.cn/Article/details/gtsfvuudcr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.daria6918.cn/Article/details/gtrapirihm.html

Ruby: public / protected / private
来源：http://dali.xziqi.cn/Article/details/gtxapnzrsn.html

C#:   public / protected / private / internal
来源：http://dali.wangshuangyany.cn/Article/details/gtwoaltccs.html

[G11] getter / setter
来源：http://dali.andypj.xyz/Article/details/gtvnhbhmek.html

Py:   @property 与 @x.setter
来源：http://dali.hywenlv.cn/Article/details/gtwqrnwknc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtgrtzbbbj.html

JS:   get name() { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gtlacjyyel.html

TS:   get name(): string { return this._name; }
来源：http://dali.iojbl.cn/Article/details/gthfdjhiia.html

Java: public String getName() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtjauuzpsv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gtdasuohmd.html

Ruby: attr_accessor :name
来源：http://dali.aibaodan.cn/Article/details/gthkvjnmdy.html

C#:   public string Name { get; set; }
来源：http://dali.haohaochexian.top/Article/details/gtlpvbxpfd.html

[G12] 对象转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwizwlofi.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258888.top/Article/details/gtygkebntx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtppjqarfr.html

JS:   toString() { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtsonhymaz.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtolmefprr.html

Java: @Override public String toString() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtsbzllpmj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gtlwykwhdo.html

Ruby: def to_s; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gttysuloiv.html

C#:   public override string ToString() => Name;
来源：http://dali.ydzc1.top/Article/details/gtxfbzuxmg.html

[G13] 判断对象类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqonoppu.html

Py:   isinstance(u, User)
来源：http://dali.yonumen.top/Article/details/gtddxoibas.html

PHP:  $u instanceof User
来源：http://dali.tanke756.top/Article/details/gtwlywxdje.html

JS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtyngbyswp.html

TS:   u instanceof User
来源：http://dali.cheryme.top/Article/details/gtwqxjgdiw.html

Java: u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtnejeyntb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.havefunace.top/Article/details/gtmftdswdd.html

Ruby: u.is_a?(User)
来源：http://dali.tanke756.top/Article/details/gtffmotmvs.html

C#:   u is User
来源：http://dali.ivvv.top/Article/details/gtzazwhzoa.html

[G14] 数据类 / record
来源：http://dali.yuanzhike.top/Article/details/gtlrkiyvcg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zdqjudy.top/Article/details/gtvhyjfpfj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tanke756.top/Article/details/gtlldmjotz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ybcxt.top/Article/details/gtwuzzxxxg.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenjidiqi.icu/Article/details/gtklxslasb.html

Java: record User(String name, int age) {}
来源：http://dali.hnqzz.top/Article/details/gtwytjkbzk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shuidangran.top/Article/details/gthsurvpsd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhongyouzk.top/Article/details/gtfzisjgnp.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258888.top/Article/details/gtxxyodyrd.html

[G15] 枚举
来源：http://dali.ydzc1.top/Article/details/gtxwxbrohb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tianlin.xyz/Article/details/gtvtmeqycm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.snrcjt.cn/Article/details/gtzkyiilvo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.havefunace.top/Article/details/gtshgkcssm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gthyakgcyu.html

Java: enum Color { RED, GREEN }
来源：http://dali.smart0.xyz/Article/details/gtaugpnmqt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhoulong.xyz/Article/details/gtydjwdbks.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhixingplan.top/Article/details/gtfkhtrsxn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtbbxjuirv.html

[G16] 对象转数组 / 字典
来源：http://dali.jiagoushi.top/Article/details/gtrgtseilm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sxryk.cn/Article/details/gtdklpidin.html

PHP:  get_object_vars($obj);
来源：http://dali.jinqigfzy.top/Article/details/gtvsxrgrdy.html

JS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gtklwrtorl.html

TS:   Object.entries(obj)
来源：http://dali.pycfn.com/Article/details/gtgitbzgxk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.mhx1999.top/Article/details/gtkmnzfaie.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj20258888.top/Article/details/gtlexrpxrt.html

Ruby: obj.instance_variables
来源：http://dali.sufxvd.cn/Article/details/gthifvndaa.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhoulong.xyz/Article/details/gtlzlsihev.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtzryvcgcs.html

H. 异常与错误处理
来源：http://dali.dianchejie.cn/Article/details/gtazatrlhn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtfaxtxfzt.html

[H01] try / catch 基础
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthmcqimwl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tanke756.top/Article/details/gtoyphrdui.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtgljvhmpe.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhongyouzk.top/Article/details/gtsbsiwxxi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gtxwxfeeex.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hfpthk.cn/Article/details/gtbyymdoan.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ppjwa.cn/Article/details/gtsrjevzul.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.vqdsnc.cn/Article/details/gtfebbikme.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xziqi.cn/Article/details/gtuzliuhpz.html

[H02] finally / ensure 收尾
来源：http://dali.sweek.top/Article/details/gtqmnsdhky.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.0kj1m.cn/Article/details/gtopkuwsts.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtspohuowe.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtqwrnatzc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtfgjrtjnt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtrdbgugws.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.dashuyun.cn/Article/details/gtcvkorrgi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gotoacloud.top/Article/details/gtplgzaclf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtvfetvivx.html

[H03] 主动抛出异常
来源：http://dali.bjfxy.top/Article/details/gtddyhjyfk.html

Py:   raise ValueError("错误信息")
来源：http://dali.havefunace.top/Article/details/gtixutvyov.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtnadriayo.html

JS:   throw new Error("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtcvkeflpv.html

TS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gtgjuydfdx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gthqbydkba.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.dashuyun.cn/Article/details/gtsuvzsudx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jqgufenzy.top/Article/details/gtnokczxjl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtkkzgkfzu.html

[H04] 自定义异常类型
来源：http://dali.ehwqpu.com/Article/details/gtjaaktywt.html

Py:   class MyError(Exception): pass
来源：http://dali.hysaishi.cn/Article/details/gtzgyfhvym.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.daxiang520.top/Article/details/gtlmsjvxto.html

JS:   class MyError extends Error {}
来源：http://dali.dianchejie.cn/Article/details/gtqswhiros.html

TS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gtpbglovkb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gtyarwummg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.0kj1m.cn/Article/details/gtaxgkisyr.html

Ruby: class MyError < StandardError; end
来源：http://dali.ivvv.top/Article/details/gtekdbkorb.html

C#:   class MyException : Exception {}
来源：http://dali.yvedp.cn/Article/details/gtcwoqdrpt.html

[H05] 捕获特定类型
来源：http://dali.cdnleiting.top/Article/details/gtvxefvkrn.html

Py:   except ValueError as e:
来源：http://dali.iojbl.cn/Article/details/gtczncjxdq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtmjigktrj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gtskjouxne.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfzpqdqmy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.pycfn.com/Article/details/gtknsjbgpu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.redwolf501.top/Article/details/gtklrlomer.html

Ruby: rescue ArgumentError => e
来源：http://dali.wangdashe.top/Article/details/gtuqalhibz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.havefunace.top/Article/details/gtwjpdgbjy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gzhubu.top/Article/details/gtzikyupci.html

Py:   value = d.get("k") or default
来源：http://dali.cqqwz.cn/Article/details/gtpyippxfn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gttvrmwtlt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cucudq.cn/Article/details/gthohtrcoq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ehwqpu.com/Article/details/gtzqhoccrl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.dashuyun.cn/Article/details/gtfxfcaqll.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shuidangran.top/Article/details/gtrgdsjbtq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hongshengwenyu.top/Article/details/gtaaqizhoz.html

C#:   obj?.A?.B ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gtbrrupzex.html

[H07] 断言
来源：http://dali.gotoacloud.top/Article/details/gtyzzgmldm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xinyue.icu/Article/details/gtdujwioro.html

PHP:  assert($x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdqwzfte.html

JS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gttpwyzzjj.html

TS:   console.assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtlukpnsqj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.fengsongda.top/Article/details/gtprqplezt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj20258888.top/Article/details/gtnrzcaonm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cashguo.top/Article/details/gtbwxizsky.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gtuqelilkh.html

[H08] 获取错误信息与堆栈
来源：http://dali.xylfe.cn/Article/details/gtrgpkizov.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangshuangyany.cn/Article/details/gtmbyjiacj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yonumen.top/Article/details/gtgslfbghp.html

JS:   e.message;  e.stack
来源：http://dali.hongshengwenyu.top/Article/details/gtdgpcezqh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zdqjudy.top/Article/details/gttpddtsch.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ppjwa.cn/Article/details/gtjuzuppzc.html

Go:   err.Error()
来源：http://dali.jinqigufen.top/Article/details/gtowmiqaoy.html

Ruby: e.message;  e.backtrace
来源：http://dali.shangyingyoupin.top/Article/details/gtowwlxvhi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.vqdsnc.cn/Article/details/gtmoavauoy.html

[H09] 带错误码的异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkjtyhdqf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xziqi.cn/Article/details/gtfcaipeyj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.aibaodan.cn/Article/details/gtqkxmzgvj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jqgfzy.top/Article/details/gtqkjcicen.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinqigfzy.top/Article/details/gtkxxrxirg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daria6918.cn/Article/details/gtpxcaeook.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jqgfzy.top/Article/details/gttthcbajp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtibnwuycd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtzxirltaa.html

[H10] 资源自动释放
来源：http://dali.hfpthk.cn/Article/details/gthgonlwdw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgfzy.top/Article/details/gtscgylwyp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.svipenyu.cn/Article/details/gtpfnyqobw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jlsjyb.cn/Article/details/gtyshphwqn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gtminijeqr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.feifeiyinyue.top/Article/details/gtfnvwvjzo.html

Go:   defer f.Close()
来源：http://dali.xuanzx.com/Article/details/gtljololwo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.dashuyun.cn/Article/details/gtqmnljmra.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtfpftfdik.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtljcbddvp.html

I. 正则表达式
来源：http://dali.yonumen.top/Article/details/gtsohcdotu.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtotdgptxf.html

[I01] 判断是否匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtwihcsxfq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gtnwrqyjcn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hammf.cn/Article/details/gthoshokfo.html

JS:   /\d+/.test(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtwzbwqxcs.html

TS:   /\d+/.test(s)
来源：http://dali.cdnleiting.top/Article/details/gtdjrmngha.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xuetiantiany.cn/Article/details/gthrjakkfd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.aibaodan.cn/Article/details/gtunsqjeac.html

Ruby: s.match?(/\d+/)
来源：http://dali.xuanzx.com/Article/details/gtqbcalmxj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xinyue.icu/Article/details/gtlmbegvka.html

[I02] 提取所有匹配
来源：http://dali.jinqigufen.top/Article/details/gtlfjantzf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gtbmbcctbv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.iojbl.cn/Article/details/gtntdorreg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hywenlv.cn/Article/details/gtvnxehizm.html

TS:   s.match(/\d+/g)
来源：http://dali.feifeiyinyue.top/Article/details/gtkwsthebq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yanxiufei.cn/Article/details/gttkvpufki.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj20258888.top/Article/details/gtfxkbqczi.html

Ruby: s.scan(/\d+/)
来源：http://dali.zycfv.cn/Article/details/gtkvkicmor.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtvugfymta.html

[I03] 提取捕获分组
来源：http://dali.cdnleiting.top/Article/details/gtjecrakep.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgufenzy.top/Article/details/gtsgzuuzzj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aizwys.cn/Article/details/gtgutooyjr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tanke756.top/Article/details/gtfwzthikh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yvedp.cn/Article/details/gtqerelzno.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cqqwz.cn/Article/details/gthqxkjcxn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhiwuduotai.top/Article/details/gttunhtbap.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hnqzz.top/Article/details/gtykwimpnx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jlsjyb.cn/Article/details/gtbudrercb.html

[I04] 正则替换
来源：http://dali.hfpthk.cn/Article/details/gtvkttvrkx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtjvaclrzv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cashguo.top/Article/details/gtnvfnnyks.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yvedp.cn/Article/details/gtskebaoyi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yuanzhike.top/Article/details/gtmjgaujko.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jqgufenzy.top/Article/details/gtvlwntjbn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.vqdsnc.cn/Article/details/gttznrtpdb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gzhubu.top/Article/details/gtsuujuxde.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yangfankeji.com/Article/details/gtbjwvzihf.html

[I05] 按正则拆分
来源：http://dali.0kj1m.cn/Article/details/gtkelcbmch.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj202588.top/Article/details/gtirbjvbsi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tian-w.cn/Article/details/gtczzisidc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gtifqinkmh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gtiizgwgmu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhoulong.xyz/Article/details/gtpcxzifxr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gtcznhrmmz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gtvdnrsxel.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ehwqpu.com/Article/details/gtpixxbdzw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gzhubu.top/Article/details/gtssaqdtzn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtsstfuplk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.snrcjt.cn/Article/details/gtjgrmlrxr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnxiangtu.top/Article/details/gtbzwfjorf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zdqjudy.top/Article/details/gtjbktvfzd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gthridxhot.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yuxming.cn/Article/details/gtzvxgxcue.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zycfv.cn/Article/details/gtzrfdwlde.html


<!-- 参考信息 -->