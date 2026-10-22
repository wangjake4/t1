代发 wailian999

Java: class User {}
来源：http://dali.dianchejie.cn/Article/details/gt2fbmmrzxo.html

Go:   type User struct { Name string }
来源：http://dali.pengpengdd.cyou/Article/details/gt2nlxradjf.html

Ruby: class User; end
来源：http://dali.aibaodan.cn/Article/details/gt2gytahtvu.html

C#:   class User {}
来源：http://dali.sysykeji.top/Article/details/gt2veczkzad.html

[G02] 构造函数
来源：http://dali.hysaishi.cn/Article/details/gt2jaqzgoby.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wvbwoyty.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yonumen.top/Article/details/gt2pzantple.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.pycfn.com/Article/details/gt2ifuxflir.html

TS:   constructor(public name: string) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zywwpbmq.html

Java: User(String name) { this.name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2bybbwols.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guowangkeji.top/Article/details/gt2vhnyurrm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jqgfzy.top/Article/details/gt2ocggfwlq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tianlin.xyz/Article/details/gt2bclrqywn.html

[G03] 实例属性
来源：http://dali.jyoumei.cn/Article/details/gt2gzflyccu.html

Py:   self.name = "x"
来源：http://dali.aizwys.cn/Article/details/gt2lbyubeqj.html

PHP:  public string $name = "x";
来源：http://dali.yonumen.top/Article/details/gt2slqpwhvu.html

JS:   this.name = "x";
来源：http://dali.bjfxy.top/Article/details/gt2uqiwodfj.html

TS:   name: string = "x";
来源：http://dali.gogol.net.cn/Article/details/gt2sobduvom.html

Java: private String name;
来源：http://dali.xylfe.cn/Article/details/gt2yvppdxgx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.9152youxi.cn/Article/details/gt2yqqfzgpz.html

Ruby: @name = "x"
来源：http://dali.xziqi.cn/Article/details/gt2sdruqvxp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xinyue.icu/Article/details/gt2fqjyzkzk.html

[G04] 定义方法
来源：http://dali.yj20258.top/Article/details/gt2zxsxsabz.html

Py:   def greet(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gt2zafsqekx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gt2xvvgbwvy.html

JS:   greet() { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gt2wlctiwqw.html

TS:   greet(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2cgdesexn.html

Java: String greet() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2acgcdcdh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gt2wkvyiyla.html

Ruby: def greet; @name; end
来源：http://dali.yonumen.top/Article/details/gt2gtuigcei.html

C#:   public string Greet() => Name;
来源：http://dali.zycfv.cn/Article/details/gt2nxyegxnj.html

[G05] 继承
来源：http://dali.hfpthk.cn/Article/details/gt2tynnfvvs.html

Py:   class Admin(User): pass
来源：http://dali.tianlin.xyz/Article/details/gt2mpemccky.html

PHP:  class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gt2qyiebuaw.html

JS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2bedokurg.html

TS:   class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gt2umluxbas.html

Java: class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gt2hvzkkjae.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shangyingyoupin.top/Article/details/gt2oysfyxhv.html

Ruby: class Admin < User; end
来源：http://dali.chenzaomai.com/Article/details/gt2mhcatmey.html

C#:   class Admin : User {}
来源：http://dali.cheryme.top/Article/details/gt2vrklvnvp.html

[G06] 重写方法
来源：http://dali.sweek.top/Article/details/gt2labkdlow.html

Py:   def greet(self): return "admin"
来源：http://dali.ehwqpu.com/Article/details/gt2svdozghc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gt2wwgrngeb.html

JS:   greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gt2ehvpgnup.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gt2azvepndv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2koxrfooc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cucudq.cn/Article/details/gt2ptekvgze.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigufen.top/Article/details/gt2sfmdbjaf.html

C#:   public override string Greet() => "admin";
来源：http://dali.jiagoushi.top/Article/details/gt2nenywono.html

[G07] 调用父类方法
来源：http://dali.bjfxy.top/Article/details/gt2eplshtwy.html

Py:   super().greet()
来源：http://dali.kuanghao11.cn/Article/details/gt2lstrrnhu.html

PHP:  parent::greet();
来源：http://dali.yuanzhike.top/Article/details/gt2jxumgtmv.html

JS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gt2jqahknel.html

TS:   super.greet();
来源：http://dali.yueranfly.top/Article/details/gt2bqfrnlsl.html

Java: super.greet();
来源：http://dali.mhx1999.top/Article/details/gt2ofsizqzt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shzxlz.cn/Article/details/gt2lcsnudey.html

Ruby: super
来源：http://dali.vqdsnc.cn/Article/details/gt2dmjtbxld.html

C#:   base.Greet();
来源：http://dali.yj20258.top/Article/details/gt2qhqlbksd.html

[G08] 静态方法与属性
来源：http://dali.jiagoushi.top/Article/details/gt2jpuocjcr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.andypj.xyz/Article/details/gt2hjciomhv.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xkengktp.html

JS:   static f() {}
来源：http://dali.chenlongwang.top/Article/details/gt2wzgdisqg.html

TS:   static f(): void {}
来源：http://dali.zhengqikj.top/Article/details/gt2qxhskejn.html

Java: static void f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2xiyertyc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yzjstfzq.html

Ruby: def self.f; end
来源：http://dali.pycfn.com/Article/details/gt2cbowfngx.html

C#:   public static void F() {}
来源：http://dali.zdqjudy.top/Article/details/gt2fynpfwsh.html

[G09] 接口 / 抽象类
来源：http://dali.cucudq.cn/Article/details/gt2aixrkjbq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hysaishi.cn/Article/details/gt2goocfdvq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxinkj.top/Article/details/gt2titeadhh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cucudq.cn/Article/details/gt2fobptkxy.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2dwrsczow.html

Java: interface Shape { double area(); }
来源：http://dali.hywenlv.cn/Article/details/gt2fgtzidqp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.c1oappe.top/Article/details/gt2kcwjhgob.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yvedp.cn/Article/details/gt2hbeiwumi.html

C#:   interface IShape { double Area(); }
来源：http://dali.mhx1999.top/Article/details/gt2nqdwbduz.html

[G10] 访问控制
来源：http://dali.xinyue.icu/Article/details/gt2chhksghq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.iojbl.cn/Article/details/gt2gdkoerue.html

PHP:  public / protected / private
来源：http://dali.hnqzz.top/Article/details/gt2fizahtce.html

JS:   #private 字段；其余公开
来源：http://dali.shuidangran.top/Article/details/gt2ggstweue.html

TS:   public / protected / private
来源：http://dali.yvedp.cn/Article/details/gt2phcmauvz.html

Java: public / protected / private / 默认包级
来源：http://dali.hysaishi.cn/Article/details/gt2lvmgsebh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.mhx1999.top/Article/details/gt2ormcigqi.html

Ruby: public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qggzfpuw.html

C#:   public / protected / private / internal
来源：http://dali.yangfankeji.com/Article/details/gt2snnzkjug.html

[G11] getter / setter
来源：http://dali.xuanzx.com/Article/details/gt2yzryxwlu.html

Py:   @property 与 @x.setter
来源：http://dali.snrcjt.cn/Article/details/gt2rnwduwny.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gt2tlxfrmip.html

JS:   get name() { return this._name; }
来源：http://dali.havefunace.top/Article/details/gt2saquxqod.html

TS:   get name(): string { return this._name; }
来源：http://dali.guannengcc.top/Article/details/gt2wpechcrb.html

Java: public String getName() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gt2gkwbayjo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gt2iwgivseg.html

Ruby: attr_accessor :name
来源：http://dali.yueranfly.top/Article/details/gt2vvfvywda.html

C#:   public string Name { get; set; }
来源：http://dali.andypj.xyz/Article/details/gt2vqaactop.html

[G12] 对象转字符串
来源：http://dali.sweek.top/Article/details/gt2sdttschl.html

Py:   def __str__(self): return self.name
来源：http://dali.zdqjudy.top/Article/details/gt2aazignrg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gt2gvseoztn.html

JS:   toString() { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2pclnswak.html

TS:   toString(): string { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hrttxnvq.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2yybkxlos.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gt2efhdgebb.html

Ruby: def to_s; @name; end
来源：http://dali.bjfxy.top/Article/details/gt2sfaskpis.html

C#:   public override string ToString() => Name;
来源：http://dali.vqdsnc.cn/Article/details/gt2ollqyjzz.html

[G13] 判断对象类型
来源：http://dali.tianlin.xyz/Article/details/gt2ifivygez.html

Py:   isinstance(u, User)
来源：http://dali.hysaishi.cn/Article/details/gt2jjzycsxb.html

PHP:  $u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gt2juqdejky.html

JS:   u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iqsmcsow.html

TS:   u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uswbrmql.html

Java: u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gt2sbsnyawq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.316326.xyz/Article/details/gt2nrzcdjbl.html

Ruby: u.is_a?(User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nleyawvc.html

C#:   u is User
来源：http://dali.cheryme.top/Article/details/gt2ktkyhuvy.html

[G14] 数据类 / record
来源：http://dali.zhiwuduotai.top/Article/details/gt2bdzlacuk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.guannengcc.top/Article/details/gt2tpjzgnja.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxuanxn.top/Article/details/gt2bqmfllwb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cdnleiting.top/Article/details/gt2vanohssm.html

TS:   type User = { name: string; age: number };
来源：http://dali.hongshengwenyu.top/Article/details/gt2fcyvelca.html

Java: record User(String name, int age) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2kisrvowm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dashuyun.cn/Article/details/gt2zumquirt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hongshengwenyu.top/Article/details/gt2cluvucfo.html

C#:   record User(string Name, int Age);
来源：http://dali.yongpay.top/Article/details/gt2rgrsopsv.html

[G15] 枚举
来源：http://dali.jinqigfzy.top/Article/details/gt2czutkkdm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.aibaodan.cn/Article/details/gt2dgfirxhz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guowangkeji.top/Article/details/gt2vajfehbf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hammf.cn/Article/details/gt2xdeibobj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gt2ffxudcqo.html

Java: enum Color { RED, GREEN }
来源：http://dali.xinyue.icu/Article/details/gt2ggmtzqdv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gogol.net.cn/Article/details/gt2plgpikfo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gotoacloud.top/Article/details/gt2zyackcyq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zycfv.cn/Article/details/gt2rohxwqjx.html

[G16] 对象转数组 / 字典
来源：http://dali.shangyingyoupin.top/Article/details/gt2xrjybckw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jiagoushi.top/Article/details/gt2wfrnumzy.html

PHP:  get_object_vars($obj);
来源：http://dali.sysykeji.top/Article/details/gt2lcekrkut.html

JS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gt2gbfpyokv.html

TS:   Object.entries(obj)
来源：http://dali.xziqi.cn/Article/details/gt2airwvjsg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.pengpengdd.cyou/Article/details/gt2arprsqgb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.0kj1m.cn/Article/details/gt2vaytgpby.html

Ruby: obj.instance_variables
来源：http://dali.gzhubu.top/Article/details/gt2ogyccjvy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gt2tpgsuuqc.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2qholfyyv.html

H. 异常与错误处理
来源：http://dali.cashguo.top/Article/details/gt2phwqrpzt.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2gwqrmxok.html

[H01] try / catch 基础
来源：http://dali.zdqjudy.top/Article/details/gt2gmibeigk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.pycfn.com/Article/details/gt2zlkvrdyd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.9152youxi.cn/Article/details/gt2toounext.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gt2lohfsofa.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gt2kytcptqh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhongyouzk.top/Article/details/gt2nikaidtr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cucudq.cn/Article/details/gt2ksobaorl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tanke756.top/Article/details/gt2zgvemkjs.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hysaishi.cn/Article/details/gt2yazfcdsg.html

[H02] finally / ensure 收尾
来源：http://dali.chenlongwang.top/Article/details/gt2bnqyyvul.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.kuanghao11.cn/Article/details/gt2mxsqwoat.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2neffiqtz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gt2kmruzzfk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2lhtmggep.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2miqlaskp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.feifeiyinyue.top/Article/details/gt2mmmdmluc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2kzaeelod.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gt2ajppjyjg.html

[H03] 主动抛出异常
来源：http://dali.jianghu66.top/Article/details/gt2gnlktmaj.html

Py:   raise ValueError("错误信息")
来源：http://dali.fengsongda.top/Article/details/gt2jltoheeq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2ztrvzpsk.html

JS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gt2msirzfdo.html

TS:   throw new Error("错误信息");
来源：http://dali.nwbrower.top/Article/details/gt2xqbeefqs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gt2uxqgvyys.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vpreeexk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnxiangtu.top/Article/details/gt2vuklrrrn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gt2ucrogezj.html

[H04] 自定义异常类型
来源：http://dali.wangdashe.top/Article/details/gt2tjtxsapj.html

Py:   class MyError(Exception): pass
来源：http://dali.cucudq.cn/Article/details/gt2cbergllv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gogol.net.cn/Article/details/gt2tnqbsbyo.html

JS:   class MyError extends Error {}
来源：http://dali.chenzaomai.com/Article/details/gt2namsbhqf.html

TS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gt2aujydups.html

Java: class MyException extends RuntimeException {}
来源：http://dali.c1oappe.top/Article/details/gt2sybioalw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jiagoushi.top/Article/details/gt2fcmnolfp.html

Ruby: class MyError < StandardError; end
来源：http://dali.ppjwa.cn/Article/details/gt2qurtmxct.html

C#:   class MyException : Exception {}
来源：http://dali.ydzc1.top/Article/details/gt2kdjupeji.html

[H05] 捕获特定类型
来源：http://dali.cqqwz.cn/Article/details/gt2iffztpur.html

Py:   except ValueError as e:
来源：http://dali.yuanzhike.top/Article/details/gt2mgybqamu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.iojbl.cn/Article/details/gt2tscpidfh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.haohaochexian.top/Article/details/gt2cokwomfp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gt2dnwwadfi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2cycvxdgw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yvedp.cn/Article/details/gt2saiecqtg.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgufenzy.top/Article/details/gt2soaongfa.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.svipenyu.cn/Article/details/gt2gdzvtwba.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jlsjyb.cn/Article/details/gt2bqpdxayh.html

Py:   value = d.get("k") or default
来源：http://dali.aizwys.cn/Article/details/gt2hpotsutc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2fltuymyv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gt2mtkubscj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ucbplcpr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xylfe.cn/Article/details/gt2bijerzvk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.smart0.xyz/Article/details/gt2bcovzymy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.svipenyu.cn/Article/details/gt2lfjiavxm.html

C#:   obj?.A?.B ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ghpnfejf.html

[H07] 断言
来源：http://dali.zhongyouzk.top/Article/details/gt2epagcjvg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenlongwang.top/Article/details/gt2qubhqtmy.html

PHP:  assert($x > 0);
来源：http://dali.xziqi.cn/Article/details/gt2noecdvrf.html

JS:   console.assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bwqlhglo.html

TS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gt2oqwgqqcr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.dashuyun.cn/Article/details/gt2tbtsckuq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.quarkkingdee.top/Article/details/gt2qqzumxdd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.aizwys.cn/Article/details/gt2cwkbfqrs.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gt2svlhbkax.html

[H08] 获取错误信息与堆栈
来源：http://dali.feifeiyinyue.top/Article/details/gt2rqvpvdff.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jianghu66.top/Article/details/gt2jgpqrpje.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xylfe.cn/Article/details/gt2vgcyptze.html

JS:   e.message;  e.stack
来源：http://dali.xuetiantiany.cn/Article/details/gt2edkknnjf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xafesgdq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ehwqpu.com/Article/details/gt2kufwhjwc.html

Go:   err.Error()
来源：http://dali.dashuyun.cn/Article/details/gt2mwbixutn.html

Ruby: e.message;  e.backtrace
来源：http://dali.316326.xyz/Article/details/gt2jtiamwed.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj20258888.top/Article/details/gt2mveehgaj.html

[H09] 带错误码的异常
来源：http://dali.zycfv.cn/Article/details/gt2luqhrees.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ppjwa.cn/Article/details/gt2estlzdur.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kyqesecg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.kuanghao11.cn/Article/details/gt2osdapjuf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2yumefnzx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yongpay.top/Article/details/gt2yruvbkwz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daxiang520.top/Article/details/gt2xgcarccq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cdnleiting.top/Article/details/gt2abozuwfm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shuidangran.top/Article/details/gt2scxlukbo.html

[H10] 资源自动释放
来源：http://dali.redwolf501.top/Article/details/gt2vupsgxic.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.andypj.xyz/Article/details/gt2vhkulqdd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hammf.cn/Article/details/gt2uvqygmje.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shangyingyoupin.top/Article/details/gt2tapdfpca.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.snrcjt.cn/Article/details/gt2eipnmywu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.daria6918.cn/Article/details/gt2fgfwpmfl.html

Go:   defer f.Close()
来源：http://dali.gaohongyu789.top/Article/details/gt2kdupmqsn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yangfankeji.com/Article/details/gt2qnasebyn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2kzbfwvhi.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2vdradnmc.html

I. 正则表达式
来源：http://dali.sxryk.cn/Article/details/gt2koyldyfe.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2sjkpbeya.html

[I01] 判断是否匹配
来源：http://dali.yueranfly.top/Article/details/gt2oozxketr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jianghu66.top/Article/details/gt2bdbhsvfy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sxryk.cn/Article/details/gt2tehaooci.html

JS:   /\d+/.test(s)
来源：http://dali.jinqigufen.top/Article/details/gt2jcjbnhgl.html

TS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2ptmkfusr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ydzc1.top/Article/details/gt2vpnoojbu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cqqwz.cn/Article/details/gt2qdnxnopf.html

Ruby: s.match?(/\d+/)
来源：http://dali.xylfe.cn/Article/details/gt2hievuilc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgfzy.top/Article/details/gt2ynnehhad.html

[I02] 提取所有匹配
来源：http://dali.dianchejie.cn/Article/details/gt2owrzgpec.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bzhlvjma.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.0kj1m.cn/Article/details/gt2podovhya.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ehwqpu.com/Article/details/gt2daheqkpq.html

TS:   s.match(/\d+/g)
来源：http://dali.daria6918.cn/Article/details/gt2txnmcpyp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yongpay.top/Article/details/gt2foiitosr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.aibaodan.cn/Article/details/gt2cukuuzry.html

Ruby: s.scan(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gt2kklldpnz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shzxlz.cn/Article/details/gt2jvcrnpkp.html

[I03] 提取捕获分组
来源：http://dali.mhx1999.top/Article/details/gt2nawynppk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2jncmvbxo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sxryk.cn/Article/details/gt2huhpzean.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangdashe.top/Article/details/gt2crtoxlsg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shzxlz.cn/Article/details/gt2omfllucd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.wangdashe.top/Article/details/gt2vjnocsic.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhengqikj.top/Article/details/gt2pcpophgx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zycfv.cn/Article/details/gt2xfkpnlve.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gaohongyu789.top/Article/details/gt2rrczdstn.html

[I04] 正则替换
来源：http://dali.aibaodan.cn/Article/details/gt2ezxoputp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jqgufenzy.top/Article/details/gt2wkzbtnor.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jianghu66.top/Article/details/gt2pfoigtkx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cheryme.top/Article/details/gt2gqookroo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sufxvd.cn/Article/details/gt2gdzovnnz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.fengsongda.top/Article/details/gt2kvhwwfot.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gotoacloud.top/Article/details/gt2pyykvpgs.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.haohaochexian.top/Article/details/gt2aqrudotc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.redwolf501.top/Article/details/gt2pkcfxjzr.html

[I05] 按正则拆分
来源：http://dali.guannengcc.top/Article/details/gt2bkqwaill.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj20258888.top/Article/details/gt2fuexemmn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2tywtavtz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gt2bkwypxld.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gt2mqueqqqy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.havefunace.top/Article/details/gt2hoqfxulw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.smart0.xyz/Article/details/gt2oqebztlc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gt2ktkomiij.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cheryme.top/Article/details/gt2bscxdvrf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ydzc1.top/Article/details/gt2hfsgiltg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gt2ijggcoat.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gzhubu.top/Article/details/gt2aisnjxjo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shzxlz.cn/Article/details/gt2fclfukgn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gt2dxxitpdi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gt2jxolqatp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.0kj1m.cn/Article/details/gt2skimanqh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.redwolf501.top/Article/details/gt2gbioogki.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenlongwang.top/Article/details/gt2ncagzyew.html

[I07] 忽略大小写与多行模式
来源：http://dali.hongshengwenyu.top/Article/details/gt2slwvikqt.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhengqikj.top/Article/details/gt2qbtdukee.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2vaktymav.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tian-w.cn/Article/details/gt2bjzlfbro.html

TS:   /error/gim
来源：http://dali.yonumen.top/Article/details/gt2zxoypnvz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gzhubu.top/Article/details/gt2tflrducm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj20258.top/Article/details/gt2lggxveky.html

Ruby: s.scan(/error/i)
来源：http://dali.jinqigfzy.top/Article/details/gt2kctahtxc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jianghu66.top/Article/details/gt2bbkxlmfy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gogol.net.cn/Article/details/gt2mrgejqxx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xziqi.cn/Article/details/gt2libqrdef.html


<!-- 参考信息 -->