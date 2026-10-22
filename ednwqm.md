代发 wailian999

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jianghu66.top/Article/details/gt2ymldcapc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hysaishi.cn/Article/details/gt2zpbcdfln.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.birdmap.top/Article/details/gt2jwhasnuf.html

TS:   // 同上
来源：http://dali.yj20258888.top/Article/details/gt2sfbaagyu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.316326.xyz/Article/details/gt2xzjeutge.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hongshengwenyu.top/Article/details/gt2znzbgfar.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2guxdikbz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jianghu66.top/Article/details/gt2wtqalrgb.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2vagwuokc.html

G. 面向对象
来源：http://dali.iojbl.cn/Article/details/gt2iztkzgfg.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2utpvguyy.html

[G01] 定义类
来源：http://dali.zhixingplan.top/Article/details/gt2mlmwcfwc.html

Py:   class User: pass
来源：http://dali.jianghu66.top/Article/details/gt2cpyobpwh.html

PHP:  class User {}
来源：http://dali.ppjwa.cn/Article/details/gt2iaqwgrhz.html

JS:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rjvsfkjs.html

TS:   class User { name: string = ""; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gsygvinv.html

Java: class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2wzmomysj.html

Go:   type User struct { Name string }
来源：http://dali.guowangkeji.top/Article/details/gt2cmbcrtpo.html

Ruby: class User; end
来源：http://dali.c1oappe.top/Article/details/gt2urnxphwx.html

C#:   class User {}
来源：http://dali.smart0.xyz/Article/details/gt2bitazion.html

[G02] 构造函数
来源：http://dali.vqdsnc.cn/Article/details/gt2kguyghtt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hfpthk.cn/Article/details/gt2qhlnqgnq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gogol.net.cn/Article/details/gt2kxriurrd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2twpszogp.html

TS:   constructor(public name: string) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2aonvuign.html

Java: User(String name) { this.name = name; }
来源：http://dali.yuanzhike.top/Article/details/gt2fjxhmiuj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.fengsongda.top/Article/details/gt2hmvtcxhu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nxyfmjof.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fjuyntay.html

[G03] 实例属性
来源：http://dali.aibaodan.cn/Article/details/gt2oeurvsos.html

Py:   self.name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gt2xvyktdru.html

PHP:  public string $name = "x";
来源：http://dali.sysykeji.top/Article/details/gt2qtgydtqb.html

JS:   this.name = "x";
来源：http://dali.zhoulong.xyz/Article/details/gt2uzzndnam.html

TS:   name: string = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2wckciobf.html

Java: private String name;
来源：http://dali.guannengcc.top/Article/details/gt2rltjspga.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.smart0.xyz/Article/details/gt2xsfyypvm.html

Ruby: @name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gt2ethlxhun.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gt2bgrfdpyr.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2sosgagfm.html

Py:   def greet(self): return self.name
来源：http://dali.sweek.top/Article/details/gt2ekjdzfyk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gt2potulged.html

JS:   greet() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gt2tjepwith.html

TS:   greet(): string { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gt2vsknrwdf.html

Java: String greet() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gt2jwanmfdm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gt2jydqzvoc.html

Ruby: def greet; @name; end
来源：http://dali.fzhhl.top/Article/details/gt2qtaemgtk.html

C#:   public string Greet() => Name;
来源：http://dali.sxryk.cn/Article/details/gt2clcxvaxq.html

[G05] 继承
来源：http://dali.gaohongyu789.top/Article/details/gt2utfmakdp.html

Py:   class Admin(User): pass
来源：http://dali.shuidangran.top/Article/details/gt2izjlidnh.html

PHP:  class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gt2tmzcjblw.html

JS:   class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gt2lvedgavu.html

TS:   class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gt2tdidbczz.html

Java: class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gt2kfnrnwqh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.havefunace.top/Article/details/gt2rdunoihv.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mklbsaig.html

C#:   class Admin : User {}
来源：http://dali.chenlongwang.top/Article/details/gt2vlpsowgk.html

[G06] 重写方法
来源：http://dali.jiagoushi.top/Article/details/gt2smwubpez.html

Py:   def greet(self): return "admin"
来源：http://dali.hysaishi.cn/Article/details/gt2kkyibunx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gt2qxqtdiav.html

JS:   greet() { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gt2lutkijgl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gt2lfxiughp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gt2ynfawpdk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigufen.top/Article/details/gt2abxidwyz.html

Ruby: def greet; "admin"; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2xxfwuagq.html

C#:   public override string Greet() => "admin";
来源：http://dali.tianlin.xyz/Article/details/gt2bvkoonvw.html

[G07] 调用父类方法
来源：http://dali.haohaochexian.top/Article/details/gt2scjiyewr.html

Py:   super().greet()
来源：http://dali.cucudq.cn/Article/details/gt2gmwvdwij.html

PHP:  parent::greet();
来源：http://dali.yj202588.top/Article/details/gt2ccdvajpz.html

JS:   super.greet();
来源：http://dali.dashuyun.cn/Article/details/gt2spvvxyvo.html

TS:   super.greet();
来源：http://dali.c1oappe.top/Article/details/gt2alrleelj.html

Java: super.greet();
来源：http://dali.zhengqikj.top/Article/details/gt2xfqsorrb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xylfe.cn/Article/details/gt2zwwhaiaf.html

Ruby: super
来源：http://dali.jqgfzy.top/Article/details/gt2vqfmcofa.html

C#:   base.Greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jsthqnfv.html

[G08] 静态方法与属性
来源：http://dali.hongshengwenyu.top/Article/details/gt2egydezju.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xylfe.cn/Article/details/gt2gzhetbbr.html

PHP:  public static function f() {}
来源：http://dali.vqdsnc.cn/Article/details/gt2ogyncjzv.html

JS:   static f() {}
来源：http://dali.guowangkeji.top/Article/details/gt2pfmdmtov.html

TS:   static f(): void {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2utorcxpw.html

Java: static void f() {}
来源：http://dali.xinyue.icu/Article/details/gt2eftdektg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zdqjudy.top/Article/details/gt2qmqgotyg.html

Ruby: def self.f; end
来源：http://dali.chenlongwang.top/Article/details/gt2kdfweyiu.html

C#:   public static void F() {}
来源：http://dali.kuanghao11.cn/Article/details/gt2qvtvyqkq.html

[G09] 接口 / 抽象类
来源：http://dali.jqgufenzy.top/Article/details/gt2keaxvuvy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cheryme.top/Article/details/gt2clxjiuxc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sufxvd.cn/Article/details/gt2bbanacps.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guowangkeji.top/Article/details/gt2bziacipe.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sqmstbzw.html

Java: interface Shape { double area(); }
来源：http://dali.pycfn.com/Article/details/gt2khmnglaq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2mszrangw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cqqwz.cn/Article/details/gt2nwwvieeg.html

C#:   interface IShape { double Area(); }
来源：http://dali.bjfxy.top/Article/details/gt2vliqcuyh.html

[G10] 访问控制
来源：http://dali.zhongyouzk.top/Article/details/gt2uvzxumgk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nanxinkj.top/Article/details/gt2fgdpwqqn.html

PHP:  public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gt2pguvxftw.html

JS:   #private 字段；其余公开
来源：http://dali.ppjwa.cn/Article/details/gt2pbqnbxis.html

TS:   public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gt2netrnjme.html

Java: public / protected / private / 默认包级
来源：http://dali.kuanghao11.cn/Article/details/gt2wucyulqi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.c1oappe.top/Article/details/gt2ljgtgkde.html

Ruby: public / protected / private
来源：http://dali.bjfxy.top/Article/details/gt2dzxbibos.html

C#:   public / protected / private / internal
来源：http://dali.quarkkingdee.top/Article/details/gt2nnhxexbc.html

[G11] getter / setter
来源：http://dali.sweek.top/Article/details/gt2drcyqjgq.html

Py:   @property 与 @x.setter
来源：http://dali.chenjidiqi.icu/Article/details/gt2lnbcycoz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gt2qxuwkvdj.html

JS:   get name() { return this._name; }
来源：http://dali.birdmap.top/Article/details/gt2iendsjiy.html

TS:   get name(): string { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gt2ejwppvxl.html

Java: public String getName() { return name; }
来源：http://dali.shuidangran.top/Article/details/gt2lwprenaa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gt2qxjrvkme.html

Ruby: attr_accessor :name
来源：http://dali.gaohongyu789.top/Article/details/gt2asmfpvmr.html

C#:   public string Name { get; set; }
来源：http://dali.tianlin.xyz/Article/details/gt2llxtelll.html

[G12] 对象转字符串
来源：http://dali.sufxvd.cn/Article/details/gt2yynbzwhu.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258.top/Article/details/gt2zfnkcgai.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gt2rbmmcwxu.html

JS:   toString() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gt2fxdmxqsz.html

TS:   toString(): string { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2bwxyaulo.html

Java: @Override public String toString() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2pdoyamca.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gt2nvwtnrds.html

Ruby: def to_s; @name; end
来源：http://dali.chenlongwang.top/Article/details/gt2pbgtawec.html

C#:   public override string ToString() => Name;
来源：http://dali.jinqigufen.top/Article/details/gt2peckmmbd.html

[G13] 判断对象类型
来源：http://dali.guowangkeji.top/Article/details/gt2qqhahthj.html

Py:   isinstance(u, User)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wemzgueu.html

PHP:  $u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gt2atbtkaxe.html

JS:   u instanceof User
来源：http://dali.xuanzx.com/Article/details/gt2ztaswlmp.html

TS:   u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gt2mhxbefko.html

Java: u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gt2wvgrqjnz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.daria6918.cn/Article/details/gt2fmvrccya.html

Ruby: u.is_a?(User)
来源：http://dali.zhixingplan.top/Article/details/gt2duhtpflg.html

C#:   u is User
来源：http://dali.shuidangran.top/Article/details/gt2bxeccrrj.html

[G14] 数据类 / record
来源：http://dali.sweek.top/Article/details/gt2rjmfbknx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcnzeeh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jyoumei.cn/Article/details/gt2tcbeoovs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fbrrgoaj.html

TS:   type User = { name: string; age: number };
来源：http://dali.shangyingyoupin.top/Article/details/gt2omrztupn.html

Java: record User(String name, int age) {}
来源：http://dali.aizwys.cn/Article/details/gt2gqdslhww.html

Go:   type User struct { Name string; Age int }
来源：http://dali.pycfn.com/Article/details/gt2htpoxlhn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.dianchejie.cn/Article/details/gt2myjbngdx.html

C#:   record User(string Name, int Age);
来源：http://dali.zhongyouzk.top/Article/details/gt2rykkwvte.html

[G15] 枚举
来源：http://dali.yueranfly.top/Article/details/gt2rrctqoxa.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tocgpkix.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jianghu66.top/Article/details/gt2peikqpdj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yanxiufei.cn/Article/details/gt2kkowqfym.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.0kj1m.cn/Article/details/gt2dblwidsa.html

Java: enum Color { RED, GREEN }
来源：http://dali.cheryme.top/Article/details/gt2zxhauqgd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hysaishi.cn/Article/details/gt2hpvnrshk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.feifeiyinyue.top/Article/details/gt2uthybwsj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wbkeorzp.html

[G16] 对象转数组 / 字典
来源：http://dali.daria6918.cn/Article/details/gt2byarryiz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xuanzx.com/Article/details/gt2kxfwbmfr.html

PHP:  get_object_vars($obj);
来源：http://dali.fengsongda.top/Article/details/gt2nfeotgir.html

JS:   Object.entries(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2pvzfxflr.html

TS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2hnxpqqtw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hammf.cn/Article/details/gt2atvatlpt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.kuanghao11.cn/Article/details/gt2kprvbkzh.html

Ruby: obj.instance_variables
来源：http://dali.tianlin.xyz/Article/details/gt2wnqwkowd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.aibaodan.cn/Article/details/gt2rjaumqnq.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2kmtqbibn.html

H. 异常与错误处理
来源：http://dali.316326.xyz/Article/details/gt2qnxehzxs.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2mtonilcb.html

[H01] try / catch 基础
来源：http://dali.yuanzhike.top/Article/details/gt2sroiqnll.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yvedp.cn/Article/details/gt2htjuxeat.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cdnleiting.top/Article/details/gt2shkzmaok.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2onthcdsf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gt2lhgzzwyl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gzhubu.top/Article/details/gt2mgahmoke.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jyoumei.cn/Article/details/gt2rsyynhxd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.guannengcc.top/Article/details/gt2zpmpjfph.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cheryme.top/Article/details/gt2kynicaqt.html

[H02] finally / ensure 收尾
来源：http://dali.daxiang520.top/Article/details/gt2hzylkojx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sysykeji.top/Article/details/gt2ehlubyuj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gt2ebpnopqk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2agyjpxvu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2rizbqtli.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2bhmduwmk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ppjwa.cn/Article/details/gt2dfokcejh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tanke756.top/Article/details/gt2ndllcjum.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gt2ttbvoveg.html

[H03] 主动抛出异常
来源：http://dali.gotoacloud.top/Article/details/gt2fraxiekx.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhengqikj.top/Article/details/gt2sexdqhba.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gt2kvokrtpj.html

JS:   throw new Error("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gt2svmrrlrs.html

TS:   throw new Error("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gt2qgjftmao.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gt2vrdonwgs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.snrcjt.cn/Article/details/gt2xpljagfo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.havefunace.top/Article/details/gt2nyzmfwqq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gt2sltaccjy.html

[H04] 自定义异常类型
来源：http://dali.dianchejie.cn/Article/details/gt2nlnabijf.html

Py:   class MyError(Exception): pass
来源：http://dali.c1oappe.top/Article/details/gt2wmksbybx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gt2dvozpbwl.html

JS:   class MyError extends Error {}
来源：http://dali.yuxming.cn/Article/details/gt2mpvetobt.html

TS:   class MyError extends Error {}
来源：http://dali.yvedp.cn/Article/details/gt2gdwoylde.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jlsjyb.cn/Article/details/gt2attgthfb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.iojbl.cn/Article/details/gt2qreburgm.html

Ruby: class MyError < StandardError; end
来源：http://dali.hnxiangtu.top/Article/details/gt2rlswapgz.html

C#:   class MyException : Exception {}
来源：http://dali.ybcxt.top/Article/details/gt2jtzcqegl.html

[H05] 捕获特定类型
来源：http://dali.jlsjyb.cn/Article/details/gt2xejfvjby.html

Py:   except ValueError as e:
来源：http://dali.chenjidiqi.icu/Article/details/gt2okjnbhar.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.daxiang520.top/Article/details/gt2cwvijqtt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gt2aknxqxzd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2fncnttfw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yueranfly.top/Article/details/gt2gzphxely.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tanke756.top/Article/details/gt2ojmchdwy.html

Ruby: rescue ArgumentError => e
来源：http://dali.snrcjt.cn/Article/details/gt2vpnnneti.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yangfankeji.com/Article/details/gt2dzlfbxpw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ceahtzuv.html

Py:   value = d.get("k") or default
来源：http://dali.zhengqikj.top/Article/details/gt2agvfccnd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.9152youxi.cn/Article/details/gt2huzjlpcu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gt2rjaqutxs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gt2jrxehryw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuxming.cn/Article/details/gt2qnsunqre.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.daria6918.cn/Article/details/gt2aucifhbo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yuxming.cn/Article/details/gt2opizawxq.html

C#:   obj?.A?.B ?? default
来源：http://dali.ehwqpu.com/Article/details/gt2dqbxjhsn.html

[H07] 断言
来源：http://dali.yuanzhike.top/Article/details/gt2ifdoabxu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yueranfly.top/Article/details/gt2csrapllt.html

PHP:  assert($x > 0);
来源：http://dali.pycfn.com/Article/details/gt2kvkilxnu.html

JS:   console.assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gt2mtsgefsg.html

TS:   console.assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bvsmjsin.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jlsjyb.cn/Article/details/gt2cqxtykgp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aizwys.cn/Article/details/gt2rrvjmrbi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cheryme.top/Article/details/gt2fjcymwbu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gt2ttcbmbxz.html

[H08] 获取错误信息与堆栈
来源：http://dali.kuanghao11.cn/Article/details/gt2stflygra.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.pycfn.com/Article/details/gt2qcgrsdfa.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tian-w.cn/Article/details/gt2btdhmqrn.html

JS:   e.message;  e.stack
来源：http://dali.tanke756.top/Article/details/gt2fyacezqz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qkhjwuxa.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.quarkkingdee.top/Article/details/gt2wzvqdurt.html

Go:   err.Error()
来源：http://dali.guannengcc.top/Article/details/gt2fisvyrqo.html

Ruby: e.message;  e.backtrace
来源：http://dali.jianghu66.top/Article/details/gt2ahshulog.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yongpay.top/Article/details/gt2wzunpxvu.html

[H09] 带错误码的异常
来源：http://dali.xziqi.cn/Article/details/gt2dfucluhw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xuanzx.com/Article/details/gt2mgaskywt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hongshengwenyu.top/Article/details/gt2apkxddia.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hammf.cn/Article/details/gt2vrgmzjuf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2kgdurcvx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ydzc1.top/Article/details/gt2gcdohbbq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gaohongyu789.top/Article/details/gt2przeongr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.aizwys.cn/Article/details/gt2hdkljlet.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nwbrower.top/Article/details/gt2jtnencnd.html

[H10] 资源自动释放
来源：http://dali.jinqigfzy.top/Article/details/gt2ibaywsik.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tanke756.top/Article/details/gt2wxitajwc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yvedp.cn/Article/details/gt2szsdmtda.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.meibo888.top/Article/details/gt2ecbdnqua.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.smart0.xyz/Article/details/gt2ogqovjpo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hongshengwenyu.top/Article/details/gt2kourjuev.html

Go:   defer f.Close()
来源：http://dali.fengsongda.top/Article/details/gt2ymorbtol.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hfkmqqee.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2kklrluia.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2mqocpwgf.html

I. 正则表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dwpiouai.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2clnrumwl.html

[I01] 判断是否匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jnntgbaz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.birdmap.top/Article/details/gt2dfofnojp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2xojnxglg.html

JS:   /\d+/.test(s)
来源：http://dali.daria6918.cn/Article/details/gt2kfiiltsg.html

TS:   /\d+/.test(s)
来源：http://dali.andypj.xyz/Article/details/gt2ddtlbpej.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jlsjyb.cn/Article/details/gt2kapmrnbr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.316326.xyz/Article/details/gt2tsxudzaf.html

Ruby: s.match?(/\d+/)
来源：http://dali.yongpay.top/Article/details/gt2csiwyiuk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shuidangran.top/Article/details/gt2tapprbbk.html

[I02] 提取所有匹配
来源：http://dali.9152youxi.cn/Article/details/gt2gslwoyyr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tanke756.top/Article/details/gt2fduyewxv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dianchejie.cn/Article/details/gt2zjpreeaq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258888.top/Article/details/gt2vtafescg.html

TS:   s.match(/\d+/g)
来源：http://dali.ehwqpu.com/Article/details/gt2lmyvpivv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2qootuhfx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nwbrower.top/Article/details/gt2ptauvqdk.html

Ruby: s.scan(/\d+/)
来源：http://dali.hammf.cn/Article/details/gt2oylpeael.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhengqikj.top/Article/details/gt2xjoksguu.html

[I03] 提取捕获分组
来源：http://dali.xuetiantiany.cn/Article/details/gt2fanlbspn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nwbrower.top/Article/details/gt2geqddzzk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.daria6918.cn/Article/details/gt2lbzjcedk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangshuangyany.cn/Article/details/gt2eddpqrtu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cheryme.top/Article/details/gt2ukfzjnsj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.birdmap.top/Article/details/gt2ilraqghj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xuanzx.com/Article/details/gt2wsnclwer.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qyngdrgo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tian-w.cn/Article/details/gt2zwmlbzkh.html

[I04] 正则替换
来源：http://dali.hywenlv.cn/Article/details/gt2hveaghfg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hfpthk.cn/Article/details/gt2idgedwts.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nwbrower.top/Article/details/gt2oryfzzek.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgfzy.top/Article/details/gt2ipundjru.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gzhubu.top/Article/details/gt2xtalbkas.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.quarkkingdee.top/Article/details/gt2wyhpxpbl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.wangdashe.top/Article/details/gt2lvxuwfic.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.svipenyu.cn/Article/details/gt2cejibvvu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tanke756.top/Article/details/gt2aykergoc.html

[I05] 按正则拆分
来源：http://dali.jqgufenzy.top/Article/details/gt2kcsfpawk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kzpazqew.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cucudq.cn/Article/details/gt2jbhppkdc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gt2ckskvzyg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gt2geacgnwi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.wangshuangyany.cn/Article/details/gt2rjyoprvw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2odloknvk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gt2uajyptjo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aizwys.cn/Article/details/gt2qlxfrygw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yanxiufei.cn/Article/details/gt2cqbwzjkm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gt2ofvewkvk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hysaishi.cn/Article/details/gt2yoinfgka.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxinkj.top/Article/details/gt2mkpjuhfb.html


<!-- 参考信息 -->