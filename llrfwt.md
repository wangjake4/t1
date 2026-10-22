代发 wailian999

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xinyue.icu/Article/details/gt2gzmiekid.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.dashuyun.cn/Article/details/gt2yhrqmkgg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sxryk.cn/Article/details/gt2fhnrekqa.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hnxiangtu.top/Article/details/gt2roojqgyg.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2aidwdidn.html

G. 面向对象
来源：http://dali.iojbl.cn/Article/details/gt2ctlsdesa.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2njfnhsgo.html

[G01] 定义类
来源：http://dali.tanke756.top/Article/details/gt2rjbeeyye.html

Py:   class User: pass
来源：http://dali.pycfn.com/Article/details/gt2eiahioav.html

PHP:  class User {}
来源：http://dali.yongpay.top/Article/details/gt2uznfuwzn.html

JS:   class User {}
来源：http://dali.yj20258888.top/Article/details/gt2uebpmqnk.html

TS:   class User { name: string = ""; }
来源：http://dali.tanke756.top/Article/details/gt2jrslpdbl.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nguhzwtk.html

Go:   type User struct { Name string }
来源：http://dali.zycfv.cn/Article/details/gt2nswsdhax.html

Ruby: class User; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2epipjedt.html

C#:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gt2obyrlidg.html

[G02] 构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wqywpyic.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.svipenyu.cn/Article/details/gt2cbcwwpib.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hammf.cn/Article/details/gt2sobvuwps.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gt2fjmewugu.html

TS:   constructor(public name: string) {}
来源：http://dali.yonumen.top/Article/details/gt2bvhzhtso.html

Java: User(String name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gt2edmrpsjw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yonumen.top/Article/details/gt2vipzahdu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cucudq.cn/Article/details/gt2cutqjydi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2coiqglut.html

[G03] 实例属性
来源：http://dali.jinqigfzy.top/Article/details/gt2fphnaiyq.html

Py:   self.name = "x"
来源：http://dali.sweek.top/Article/details/gt2hlcoreve.html

PHP:  public string $name = "x";
来源：http://dali.mhx1999.top/Article/details/gt2rkykpxbz.html

JS:   this.name = "x";
来源：http://dali.ppjwa.cn/Article/details/gt2hrtwmsef.html

TS:   name: string = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gt2oayqlycx.html

Java: private String name;
来源：http://dali.tian-w.cn/Article/details/gt2blpowgmw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shzxlz.cn/Article/details/gt2iiwihypk.html

Ruby: @name = "x"
来源：http://dali.sxryk.cn/Article/details/gt2aclzsbcb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hammf.cn/Article/details/gt2iqrkfjdk.html

[G04] 定义方法
来源：http://dali.wangdashe.top/Article/details/gt2wdpqnzzd.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2dzonuckz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gt2rfmmwfwh.html

JS:   greet() { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gt2ualwgdlj.html

TS:   greet(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2pqpsfcdx.html

Java: String greet() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2vkgcbyik.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gt2ecsbwqpu.html

Ruby: def greet; @name; end
来源：http://dali.xylfe.cn/Article/details/gt2qhxolgzp.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nerzrnfa.html

[G05] 继承
来源：http://dali.ydzc1.top/Article/details/gt2lhxlxhub.html

Py:   class Admin(User): pass
来源：http://dali.pycfn.com/Article/details/gt2umyzykbm.html

PHP:  class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gt2llmdhwqk.html

JS:   class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gt2prrlwpcl.html

TS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gt2vozxbqmw.html

Java: class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gt2mgsgxaow.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.9152youxi.cn/Article/details/gt2kahtisoa.html

Ruby: class Admin < User; end
来源：http://dali.jqgfzy.top/Article/details/gt2uvzdmzzx.html

C#:   class Admin : User {}
来源：http://dali.nanxinkj.top/Article/details/gt2xmmuzkmt.html

[G06] 重写方法
来源：http://dali.andypj.xyz/Article/details/gt2pkcosfml.html

Py:   def greet(self): return "admin"
来源：http://dali.aibaodan.cn/Article/details/gt2hbojjvaw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gt2xnnhdcbk.html

JS:   greet() { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gt2zmxdwxgn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gt2dgznzigo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gt2dfxivelt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tian-w.cn/Article/details/gt2kdypsiay.html

Ruby: def greet; "admin"; end
来源：http://dali.guannengcc.top/Article/details/gt2umrftrfe.html

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vfykumvd.html

[G07] 调用父类方法
来源：http://dali.snrcjt.cn/Article/details/gt2wazwryxz.html

Py:   super().greet()
来源：http://dali.jlsjyb.cn/Article/details/gt2vkaprizw.html

PHP:  parent::greet();
来源：http://dali.meibo888.top/Article/details/gt2mmksovvk.html

JS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gt2yfexdsay.html

TS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gt2woiynphp.html

Java: super.greet();
来源：http://dali.yuxming.cn/Article/details/gt2pfqbtlso.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cashguo.top/Article/details/gt2vejfnvtf.html

Ruby: super
来源：http://dali.xziqi.cn/Article/details/gt2tigugkdd.html

C#:   base.Greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kaxbdzvq.html

[G08] 静态方法与属性
来源：http://dali.chenjidiqi.icu/Article/details/gt2euifbeza.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.dianchejie.cn/Article/details/gt2taguegba.html

PHP:  public static function f() {}
来源：http://dali.ppjwa.cn/Article/details/gt2iszvtnzv.html

JS:   static f() {}
来源：http://dali.316326.xyz/Article/details/gt2erpiovjw.html

TS:   static f(): void {}
来源：http://dali.pycfn.com/Article/details/gt2xpqesnva.html

Java: static void f() {}
来源：http://dali.xinyue.icu/Article/details/gt2npsrguot.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zycfv.cn/Article/details/gt2jyzkajzr.html

Ruby: def self.f; end
来源：http://dali.zycfv.cn/Article/details/gt2kocjcrzz.html

C#:   public static void F() {}
来源：http://dali.fengsongda.top/Article/details/gt2kixqpesj.html

[G09] 接口 / 抽象类
来源：http://dali.snrcjt.cn/Article/details/gt2eeymgoqc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pycfn.com/Article/details/gt2oeemxxab.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tianlin.xyz/Article/details/gt2aqgmgvfl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhoulong.xyz/Article/details/gt2fjiipipe.html

TS:   interface Shape { area(): number; }
来源：http://dali.ehwqpu.com/Article/details/gt2hoxuylus.html

Java: interface Shape { double area(); }
来源：http://dali.xinyue.icu/Article/details/gt2nfzyprvb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhongyouzk.top/Article/details/gt2jidhemni.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sxryk.cn/Article/details/gt2lonnjtis.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2poldnmym.html

[G10] 访问控制
来源：http://dali.jinqigufen.top/Article/details/gt2ctzwguvo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nanxinkj.top/Article/details/gt2edzkygiv.html

PHP:  public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gt2orkraxty.html

JS:   #private 字段；其余公开
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xebxfdpm.html

TS:   public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gt2ytznkrwk.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigfzy.top/Article/details/gt2nzcohtkf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guowangkeji.top/Article/details/gt2cgcihtku.html

Ruby: public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pfweungo.html

C#:   public / protected / private / internal
来源：http://dali.jiagoushi.top/Article/details/gt2nqexbgrn.html

[G11] getter / setter
来源：http://dali.vqdsnc.cn/Article/details/gt2drgfgydc.html

Py:   @property 与 @x.setter
来源：http://dali.xuetiantiany.cn/Article/details/gt2puirahnf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gt2outfmfvr.html

JS:   get name() { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2asfntlaz.html

TS:   get name(): string { return this._name; }
来源：http://dali.dianchejie.cn/Article/details/gt2kozonawx.html

Java: public String getName() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gt2ujddvziw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gt2zjybwzbh.html

Ruby: attr_accessor :name
来源：http://dali.guowangkeji.top/Article/details/gt2bxhkjlyr.html

C#:   public string Name { get; set; }
来源：http://dali.sweek.top/Article/details/gt2nmxjulrk.html

[G12] 对象转字符串
来源：http://dali.daria6918.cn/Article/details/gt2uzyhasoe.html

Py:   def __str__(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gt2hqolqsxx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sayizmxq.html

JS:   toString() { return this.name; }
来源：http://dali.yj20258.top/Article/details/gt2jazzzyby.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gt2smxasyfi.html

Java: @Override public String toString() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gt2livsimnp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gt2wxjpdqpo.html

Ruby: def to_s; @name; end
来源：http://dali.xuanzx.com/Article/details/gt2rmccnlja.html

C#:   public override string ToString() => Name;
来源：http://dali.jqgfzy.top/Article/details/gt2dsurtzyj.html

[G13] 判断对象类型
来源：http://dali.yuxming.cn/Article/details/gt2hkzigywm.html

Py:   isinstance(u, User)
来源：http://dali.sufxvd.cn/Article/details/gt2linfcwap.html

PHP:  $u instanceof User
来源：http://dali.yonumen.top/Article/details/gt2dcbxmlcl.html

JS:   u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gt2lghtoekl.html

TS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gt2nfwxnnyq.html

Java: u instanceof User
来源：http://dali.ydzc1.top/Article/details/gt2nsnkkpkx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.snrcjt.cn/Article/details/gt2exfuubpo.html

Ruby: u.is_a?(User)
来源：http://dali.hysaishi.cn/Article/details/gt2eygfznoq.html

C#:   u is User
来源：http://dali.gaohongyu789.top/Article/details/gt2tztuvexb.html

[G14] 数据类 / record
来源：http://dali.zhengqikj.top/Article/details/gt2alcmotnl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxinkj.top/Article/details/gt2kaaxzrkd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jcbwcawp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yj20258.top/Article/details/gt2ljhnjqgm.html

TS:   type User = { name: string; age: number };
来源：http://dali.yongpay.top/Article/details/gt2equjbqii.html

Java: record User(String name, int age) {}
来源：http://dali.hfpthk.cn/Article/details/gt2eqynedwy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cheryme.top/Article/details/gt2psololyc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yanxiufei.cn/Article/details/gt2ibwbzjrf.html

C#:   record User(string Name, int Age);
来源：http://dali.andypj.xyz/Article/details/gt2pzeqcfrx.html

[G15] 枚举
来源：http://dali.shuidangran.top/Article/details/gt2ceotvtwb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tianlin.xyz/Article/details/gt2epbytdkl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hysaishi.cn/Article/details/gt2qnbcggha.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yuanzhike.top/Article/details/gt2flyrotim.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhongyouzk.top/Article/details/gt2kkeoaahx.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2huutslzu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yueranfly.top/Article/details/gt2gkoqkifx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.c1oappe.top/Article/details/gt2hmkqbuhc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xinyue.icu/Article/details/gt2cjifflwj.html

[G16] 对象转数组 / 字典
来源：http://dali.sufxvd.cn/Article/details/gt2ttkgbhmf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.c1oappe.top/Article/details/gt2tolryirh.html

PHP:  get_object_vars($obj);
来源：http://dali.tianlin.xyz/Article/details/gt2klfiipgz.html

JS:   Object.entries(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2pygkwltw.html

TS:   Object.entries(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2gntqmqlq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.iojbl.cn/Article/details/gt2kywjkdgw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ehwqpu.com/Article/details/gt2fxlobmox.html

Ruby: obj.instance_variables
来源：http://dali.ehwqpu.com/Article/details/gt2zvnwzrxu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jiagoushi.top/Article/details/gt2wstngxwj.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2oxmbuhvi.html

H. 异常与错误处理
来源：http://dali.yangfankeji.com/Article/details/gt2wgnqywuo.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2ecpaunjb.html

[H01] try / catch 基础
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yxfnttbv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tian-w.cn/Article/details/gt2axvkqfqu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.c1oappe.top/Article/details/gt2nxznwxup.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gt2knnrwdkl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.daria6918.cn/Article/details/gt2rjkhxfet.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gaohongyu789.top/Article/details/gt2vbagslec.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.mhx1999.top/Article/details/gt2fmhslbha.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhoulong.xyz/Article/details/gt2opvoqpqo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ivvv.top/Article/details/gt2rnkfrvhl.html

[H02] finally / ensure 收尾
来源：http://dali.nanxinkj.top/Article/details/gt2kblrvypl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gogol.net.cn/Article/details/gt2hdgqpfwv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gt2nljzdtje.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2gkwyptgu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gt2zpqnjrbh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gt2zkrmfhyv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yueranfly.top/Article/details/gt2swfsaozz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gogol.net.cn/Article/details/gt2mrpmfmyt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gt2qeamruxq.html

[H03] 主动抛出异常
来源：http://dali.yanxiufei.cn/Article/details/gt2onowxvmh.html

Py:   raise ValueError("错误信息")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zijmzvqf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gt2utacgrhr.html

JS:   throw new Error("错误信息");
来源：http://dali.316326.xyz/Article/details/gt2rniwktsr.html

TS:   throw new Error("错误信息");
来源：http://dali.hnqzz.top/Article/details/gt2fxvfxmtf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gt2jsvugyem.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shzxlz.cn/Article/details/gt2ghyufmvx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jyoumei.cn/Article/details/gt2rfgvjixv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gt2xtvklegk.html

[H04] 自定义异常类型
来源：http://dali.gotoacloud.top/Article/details/gt2jmvuiyat.html

Py:   class MyError(Exception): pass
来源：http://dali.cdnleiting.top/Article/details/gt2fjfcawha.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gt2dvsundei.html

JS:   class MyError extends Error {}
来源：http://dali.jinqigufen.top/Article/details/gt2apyqzfmn.html

TS:   class MyError extends Error {}
来源：http://dali.redwolf501.top/Article/details/gt2ofluamxq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gt2plgwqpbu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.wangshuangyany.cn/Article/details/gt2mwedfrwv.html

Ruby: class MyError < StandardError; end
来源：http://dali.aizwys.cn/Article/details/gt2xdftqgdm.html

C#:   class MyException : Exception {}
来源：http://dali.tanke756.top/Article/details/gt2lgadloei.html

[H05] 捕获特定类型
来源：http://dali.yueranfly.top/Article/details/gt2vhoukapj.html

Py:   except ValueError as e:
来源：http://dali.jqgufenzy.top/Article/details/gt2sfnfnema.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhixingplan.top/Article/details/gt2ulmpwyxs.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2nftalfvm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ivvv.top/Article/details/gt2lvaqlpix.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.meibo888.top/Article/details/gt2dwfozlua.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.bjfxy.top/Article/details/gt2ltvpdmot.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhengqikj.top/Article/details/gt2mbskenlg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2hbjmzxsq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj202588.top/Article/details/gt2jxnrrfxp.html

Py:   value = d.get("k") or default
来源：http://dali.quarkkingdee.top/Article/details/gt2uhimmsbi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pycfn.com/Article/details/gt2geixmdru.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gt2ulqkdvzo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hywenlv.cn/Article/details/gt2lwewajnc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xylfe.cn/Article/details/gt2zwncaelw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.andypj.xyz/Article/details/gt2ojdnxklu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hywenlv.cn/Article/details/gt2rrzxcees.html

C#:   obj?.A?.B ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rnnosivm.html

[H07] 断言
来源：http://dali.wangdashe.top/Article/details/gt2pvygnypj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cucudq.cn/Article/details/gt2pveidbvc.html

PHP:  assert($x > 0);
来源：http://dali.fzhhl.top/Article/details/gt2ghsbvpnb.html

JS:   console.assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gt2qkqnnpfu.html

TS:   console.assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gt2vmdewocd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cqqwz.cn/Article/details/gt2odipyogm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qgzeotkl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.wangdashe.top/Article/details/gt2ydcqrykf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gt2pngmuqeu.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhixingplan.top/Article/details/gt2grnjzlfq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.vqdsnc.cn/Article/details/gt2zpzdcicl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yongpay.top/Article/details/gt2zcijwyku.html

JS:   e.message;  e.stack
来源：http://dali.cucudq.cn/Article/details/gt2pgylcyhl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sweek.top/Article/details/gt2bumozezh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnqzz.top/Article/details/gt2ujoscvbd.html

Go:   err.Error()
来源：http://dali.hnxiangtu.top/Article/details/gt2bukcliwm.html

Ruby: e.message;  e.backtrace
来源：http://dali.c1oappe.top/Article/details/gt2cbwzfcwo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vsloblob.html

[H09] 带错误码的异常
来源：http://dali.xuetiantiany.cn/Article/details/gt2cphryjqd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aibaodan.cn/Article/details/gt2uuqfycyf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.snrcjt.cn/Article/details/gt2tyfrbclt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bgroytam.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sxryk.cn/Article/details/gt2rffiwqnn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jyoumei.cn/Article/details/gt2nytdrrlq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ehwqpu.com/Article/details/gt2iesrfngp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnxiangtu.top/Article/details/gt2dhkvydvx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.snrcjt.cn/Article/details/gt2sldqbwro.html

[H10] 资源自动释放
来源：http://dali.xziqi.cn/Article/details/gt2smowymhk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenjidiqi.icu/Article/details/gt2avcifkvb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pycfn.com/Article/details/gt2tjektqqk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gt2nsuvabuq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gt2ajiwjkin.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.smart0.xyz/Article/details/gt2iozmoyyv.html

Go:   defer f.Close()
来源：http://dali.c1oappe.top/Article/details/gt2srzjeeny.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tanke756.top/Article/details/gt2zrfyaurm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2ywcpodrv.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2xotrgkoz.html

I. 正则表达式
来源：http://dali.daria6918.cn/Article/details/gt2tsgvrhrx.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2beednqwh.html

[I01] 判断是否匹配
来源：http://dali.zdqjudy.top/Article/details/gt2azeldkvb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.dianchejie.cn/Article/details/gt2jtllorhw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj20258.top/Article/details/gt2uuackofo.html

JS:   /\d+/.test(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jkpqbuzs.html

TS:   /\d+/.test(s)
来源：http://dali.guannengcc.top/Article/details/gt2qgzdylwj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gogol.net.cn/Article/details/gt2whduglxj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zftwetwq.html

Ruby: s.match?(/\d+/)
来源：http://dali.gzhubu.top/Article/details/gt2dztqpudn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tian-w.cn/Article/details/gt2jbkhodeh.html

[I02] 提取所有匹配
来源：http://dali.hywenlv.cn/Article/details/gt2rojkczmw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jyoumei.cn/Article/details/gt2egzmhnkw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.316326.xyz/Article/details/gt2ezgvkzmg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ydzc1.top/Article/details/gt2nboiviov.html

TS:   s.match(/\d+/g)
来源：http://dali.gzhubu.top/Article/details/gt2ybhwbuoo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hywenlv.cn/Article/details/gt2nhjygsqp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.haohaochexian.top/Article/details/gt2loqdttfo.html

Ruby: s.scan(/\d+/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2yngagjwx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.0kj1m.cn/Article/details/gt2onenbmng.html

[I03] 提取捕获分组
来源：http://dali.zhiwuduotai.top/Article/details/gt2zzzumsxl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2qfkyrukm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cashguo.top/Article/details/gt2rutgdudv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nwbrower.top/Article/details/gt2hkibcmeq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhoulong.xyz/Article/details/gt2ernhwriq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nanxinkj.top/Article/details/gt2bufmqxeq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.fzhhl.top/Article/details/gt2rmouakzo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xylfe.cn/Article/details/gt2ljmgajkc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cashguo.top/Article/details/gt2dgevlcco.html

[I04] 正则替换
来源：http://dali.nwbrower.top/Article/details/gt2czhwsolz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.havefunace.top/Article/details/gt2cadjjcox.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258888.top/Article/details/gt2zsvvpcpx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gt2ruoyztjr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xylfe.cn/Article/details/gt2jbjiaboe.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xziqi.cn/Article/details/gt2rqhqxwnz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yanxiufei.cn/Article/details/gt2yqbmqqjm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gaohongyu789.top/Article/details/gt2jzzthewm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhengqikj.top/Article/details/gt2eeammeqa.html

[I05] 按正则拆分
来源：http://dali.zdqjudy.top/Article/details/gt2jxitalss.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hysaishi.cn/Article/details/gt2pqaeyzqu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cashguo.top/Article/details/gt2hivfmelq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gt2zvxtytdy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gt2zzycwikm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinqigfzy.top/Article/details/gt2nrrczbxk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.svipenyu.cn/Article/details/gt2pffkrtnn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gt2ljuyexch.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cqqwz.cn/Article/details/gt2dvlxzjrc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fxdmyqgx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gt2bbtcpgux.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinqigfzy.top/Article/details/gt2mlneqoup.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cqqwz.cn/Article/details/gt2dkgkmefx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tian-w.cn/Article/details/gt2tafvzcvj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shuidangran.top/Article/details/gt2ymosbkin.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dzpzkgwx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sxryk.cn/Article/details/gt2taavnzhh.html


<!-- 参考信息 -->