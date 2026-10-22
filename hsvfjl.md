代发 wailian999

Py:   class User: pass
来源：http://dali.tanke756.top/Article/details/gt2xopnkkcl.html

PHP:  class User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2hksfqsdk.html

JS:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2gdfnnrdw.html

TS:   class User { name: string = ""; }
来源：http://dali.cdnleiting.top/Article/details/gt2rfnzpcbk.html

Java: class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2kzgfhnne.html

Go:   type User struct { Name string }
来源：http://dali.yuxming.cn/Article/details/gt2ikgmnhxs.html

Ruby: class User; end
来源：http://dali.sweek.top/Article/details/gt2ymfepmeh.html

C#:   class User {}
来源：http://dali.xuanzx.com/Article/details/gt2gyhmylju.html

[G02] 构造函数
来源：http://dali.yueranfly.top/Article/details/gt2gpwacngb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sxryk.cn/Article/details/gt2knptqtok.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.0kj1m.cn/Article/details/gt2gguoiudj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gt2ywzorawm.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2ggqhaell.html

Java: User(String name) { this.name = name; }
来源：http://dali.9152youxi.cn/Article/details/gt2ragkvirm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jianghu66.top/Article/details/gt2dyrzfeel.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shzxlz.cn/Article/details/gt2sospvrgr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhixingplan.top/Article/details/gt2bknrgxxk.html

[G03] 实例属性
来源：http://dali.cqqwz.cn/Article/details/gt2wpqlqyup.html

Py:   self.name = "x"
来源：http://dali.quarkkingdee.top/Article/details/gt2pmwtppjr.html

PHP:  public string $name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gt2nqrfwlbf.html

JS:   this.name = "x";
来源：http://dali.chenzaomai.com/Article/details/gt2wyerumnx.html

TS:   name: string = "x";
来源：http://dali.xuanzx.com/Article/details/gt2hbjgudmj.html

Java: private String name;
来源：http://dali.yangfankeji.com/Article/details/gt2ythdvcal.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hjmzvbfm.html

Ruby: @name = "x"
来源：http://dali.sweek.top/Article/details/gt2szwjjmjl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ubtraghl.html

[G04] 定义方法
来源：http://dali.316326.xyz/Article/details/gt2hnfqoxvx.html

Py:   def greet(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gt2lyayiohh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gt2fasdcqkp.html

JS:   greet() { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gt2sfhrzovi.html

TS:   greet(): string { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gt2zbuzxfti.html

Java: String greet() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gt2yheumogh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gt2qdtldrxi.html

Ruby: def greet; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gt2pmwmrzqe.html

C#:   public string Greet() => Name;
来源：http://dali.xuanzx.com/Article/details/gt2etzooxqg.html

[G05] 继承
来源：http://dali.haohaochexian.top/Article/details/gt2gvwvzqpe.html

Py:   class Admin(User): pass
来源：http://dali.svipenyu.cn/Article/details/gt2rmlcoupu.html

PHP:  class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gt2njpwgksv.html

JS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gt2xseizbie.html

TS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gt2xvllsogm.html

Java: class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gt2qshnmgmq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhongyouzk.top/Article/details/gt2hgqoztpx.html

Ruby: class Admin < User; end
来源：http://dali.c1oappe.top/Article/details/gt2jvyjthfn.html

C#:   class Admin : User {}
来源：http://dali.yongpay.top/Article/details/gt2mlhdyuxh.html

[G06] 重写方法
来源：http://dali.316326.xyz/Article/details/gt2vqyyesfa.html

Py:   def greet(self): return "admin"
来源：http://dali.snrcjt.cn/Article/details/gt2tvhjinvx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gt2rnpfhziu.html

JS:   greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2gcyrjuya.html

TS:   greet(): string { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gt2hmxlzjml.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2phzvbxtf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xuanzx.com/Article/details/gt2tahpstrt.html

Ruby: def greet; "admin"; end
来源：http://dali.svipenyu.cn/Article/details/gt2lnzigtfv.html

C#:   public override string Greet() => "admin";
来源：http://dali.svipenyu.cn/Article/details/gt2qdhusxnr.html

[G07] 调用父类方法
来源：http://dali.wangdashe.top/Article/details/gt2qwdnrcfq.html

Py:   super().greet()
来源：http://dali.0kj1m.cn/Article/details/gt2nnplojwy.html

PHP:  parent::greet();
来源：http://dali.hysaishi.cn/Article/details/gt2daumzpni.html

JS:   super.greet();
来源：http://dali.ydzc1.top/Article/details/gt2nvasgcqk.html

TS:   super.greet();
来源：http://dali.yj20258.top/Article/details/gt2hbeitniq.html

Java: super.greet();
来源：http://dali.meibo888.top/Article/details/gt2dyfkqtjf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinqigfzy.top/Article/details/gt2ruqscaeu.html

Ruby: super
来源：http://dali.chenjidiqi.icu/Article/details/gt2hsifkquh.html

C#:   base.Greet();
来源：http://dali.chenlongwang.top/Article/details/gt2omkcuvtz.html

[G08] 静态方法与属性
来源：http://dali.yanxiufei.cn/Article/details/gt2aahrzwpj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tianlin.xyz/Article/details/gt2viulxdbt.html

PHP:  public static function f() {}
来源：http://dali.yongpay.top/Article/details/gt2xyfpntkz.html

JS:   static f() {}
来源：http://dali.gotoacloud.top/Article/details/gt2shexcxbz.html

TS:   static f(): void {}
来源：http://dali.gzhubu.top/Article/details/gt2puafhgki.html

Java: static void f() {}
来源：http://dali.snrcjt.cn/Article/details/gt2ckkhexls.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhongyouzk.top/Article/details/gt2kgzfcopa.html

Ruby: def self.f; end
来源：http://dali.jianghu66.top/Article/details/gt2hzpjzrzj.html

C#:   public static void F() {}
来源：http://dali.ehwqpu.com/Article/details/gt2wirjjtdz.html

[G09] 接口 / 抽象类
来源：http://dali.yuanzhike.top/Article/details/gt2bkirlrgm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.vqdsnc.cn/Article/details/gt2mjqmblpn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sxryk.cn/Article/details/gt2owiwqbeq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kmuwyzsk.html

TS:   interface Shape { area(): number; }
来源：http://dali.guannengcc.top/Article/details/gt2bukhoclq.html

Java: interface Shape { double area(); }
来源：http://dali.iojbl.cn/Article/details/gt2bixiekih.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yangfankeji.com/Article/details/gt2eiedkhbv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.redwolf501.top/Article/details/gt2vwnoggcm.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lupkniba.html

[G10] 访问控制
来源：http://dali.nwbrower.top/Article/details/gt2rpwpcaac.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fengsongda.top/Article/details/gt2ajmrgoen.html

PHP:  public / protected / private
来源：http://dali.tian-w.cn/Article/details/gt2qimyuzsc.html

JS:   #private 字段；其余公开
来源：http://dali.yuanzhike.top/Article/details/gt2xcbgjobw.html

TS:   public / protected / private
来源：http://dali.iojbl.cn/Article/details/gt2efvoehsy.html

Java: public / protected / private / 默认包级
来源：http://dali.dianchejie.cn/Article/details/gt2reicodqu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhoulong.xyz/Article/details/gt2uncxjfqj.html

Ruby: public / protected / private
来源：http://dali.yj20258888.top/Article/details/gt2apfsrcjo.html

C#:   public / protected / private / internal
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2scdfashw.html

[G11] getter / setter
来源：http://dali.andypj.xyz/Article/details/gt2oubnvjgp.html

Py:   @property 与 @x.setter
来源：http://dali.316326.xyz/Article/details/gt2nxzhwqks.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hewwhdnh.html

JS:   get name() { return this._name; }
来源：http://dali.yonumen.top/Article/details/gt2gqyojqgr.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gt2gklzkdsh.html

Java: public String getName() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gt2vhtslwwe.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yktvphcc.html

Ruby: attr_accessor :name
来源：http://dali.chenlongwang.top/Article/details/gt2kmtnuakw.html

C#:   public string Name { get; set; }
来源：http://dali.sweek.top/Article/details/gt2gnkfxhje.html

[G12] 对象转字符串
来源：http://dali.daria6918.cn/Article/details/gt2orwuxdme.html

Py:   def __str__(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gt2fvokdfio.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gt2akkmvdpy.html

JS:   toString() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2kdgdyynr.html

TS:   toString(): string { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gt2eojbmzad.html

Java: @Override public String toString() { return name; }
来源：http://dali.xziqi.cn/Article/details/gt2ktlzwtum.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gt2azouqpdl.html

Ruby: def to_s; @name; end
来源：http://dali.quarkkingdee.top/Article/details/gt2lhpqolyc.html

C#:   public override string ToString() => Name;
来源：http://dali.snrcjt.cn/Article/details/gt2smovxdkl.html

[G13] 判断对象类型
来源：http://dali.wangdashe.top/Article/details/gt2imqoqcfo.html

Py:   isinstance(u, User)
来源：http://dali.shzxlz.cn/Article/details/gt2acafsbnu.html

PHP:  $u instanceof User
来源：http://dali.bjfxy.top/Article/details/gt2bavchlhq.html

JS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gt2tccawiuq.html

TS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qvaawbzq.html

Java: u instanceof User
来源：http://dali.meibo888.top/Article/details/gt2jqzymaes.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yuanzhike.top/Article/details/gt2fprxzhci.html

Ruby: u.is_a?(User)
来源：http://dali.hnqzz.top/Article/details/gt2narttooc.html

C#:   u is User
来源：http://dali.quarkkingdee.top/Article/details/gt2xupxzviq.html

[G14] 数据类 / record
来源：http://dali.c1oappe.top/Article/details/gt2oynmhktg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gzhubu.top/Article/details/gt2lsadxqwx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhiwuduotai.top/Article/details/gt2nbqafcif.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gogol.net.cn/Article/details/gt2ofhgfvbv.html

TS:   type User = { name: string; age: number };
来源：http://dali.gaohongyu789.top/Article/details/gt2ntigfrfn.html

Java: record User(String name, int age) {}
来源：http://dali.yj202588.top/Article/details/gt2udmdnuay.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenlongwang.top/Article/details/gt2mezzkzuw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hnxiangtu.top/Article/details/gt2ixhfrbum.html

C#:   record User(string Name, int Age);
来源：http://dali.xziqi.cn/Article/details/gt2brtdsuxv.html

[G15] 枚举
来源：http://dali.zhengqikj.top/Article/details/gt2eycudhak.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2cbqrpwup.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.316326.xyz/Article/details/gt2kefdfgai.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.redwolf501.top/Article/details/gt2tslpmfqm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gt2zqwbnekr.html

Java: enum Color { RED, GREEN }
来源：http://dali.yvedp.cn/Article/details/gt2lfjdumim.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhongyouzk.top/Article/details/gt2ohsxqkqk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxinkj.top/Article/details/gt2qqfnyxpo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gt2todvmmba.html

[G16] 对象转数组 / 字典
来源：http://dali.zycfv.cn/Article/details/gt2nznnetyb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.pengpengdd.cyou/Article/details/gt2hfxemddh.html

PHP:  get_object_vars($obj);
来源：http://dali.zhixingplan.top/Article/details/gt2ffxrtnub.html

JS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2wdcwarjl.html

TS:   Object.entries(obj)
来源：http://dali.nwbrower.top/Article/details/gt2qglrchci.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhoulong.xyz/Article/details/gt2yularjpa.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.vqdsnc.cn/Article/details/gt2jjkfywup.html

Ruby: obj.instance_variables
来源：http://dali.fzhhl.top/Article/details/gt2jxngtyup.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gt2hhrtdczo.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2wrsznlep.html

H. 异常与错误处理
来源：http://dali.meibo888.top/Article/details/gt2qkrpjjug.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jhcvbbti.html

[H01] try / catch 基础
来源：http://dali.jlsjyb.cn/Article/details/gt2llyqxchx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yanxiufei.cn/Article/details/gt2lnzfcklm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xinyue.icu/Article/details/gt2cgpucbed.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.birdmap.top/Article/details/gt2zkvezipv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenlongwang.top/Article/details/gt2yocatjut.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenzaomai.com/Article/details/gt2giiedoee.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.kuanghao11.cn/Article/details/gt2haqogfxd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ppjwa.cn/Article/details/gt2yaspxfcb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uqjggrqw.html

[H02] finally / ensure 收尾
来源：http://dali.nanxuanxn.top/Article/details/gt2ylutgauz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.meibo888.top/Article/details/gt2cqhcuadr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2opfiaqts.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2azpzkwbx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gt2dqoesowo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gt2ieghvkcn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenzaomai.com/Article/details/gt2iuxsjeqj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jlsjyb.cn/Article/details/gt2nmykboiy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gt2qnfgmfma.html

[H03] 主动抛出异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ygkelloj.html

Py:   raise ValueError("错误信息")
来源：http://dali.shangyingyoupin.top/Article/details/gt2qdgmlilf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gt2qaaexnfl.html

JS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gt2vyywzvnr.html

TS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gt2yvpbshzu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gt2dszmxixq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wisvvsmr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cheryme.top/Article/details/gt2ddqftomh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gt2afsjmmyx.html

[H04] 自定义异常类型
来源：http://dali.aibaodan.cn/Article/details/gt2whtslqhl.html

Py:   class MyError(Exception): pass
来源：http://dali.hammf.cn/Article/details/gt2oiglaaqc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinqigufen.top/Article/details/gt2qxkhhhoh.html

JS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gt2xvwwswaf.html

TS:   class MyError extends Error {}
来源：http://dali.fengsongda.top/Article/details/gt2piusleht.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ehwqpu.com/Article/details/gt2uqgxsija.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.0kj1m.cn/Article/details/gt2uazwedpi.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2jhacmgft.html

C#:   class MyException : Exception {}
来源：http://dali.9152youxi.cn/Article/details/gt2cksbsgum.html

[H05] 捕获特定类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2vhiwwpvg.html

Py:   except ValueError as e:
来源：http://dali.daxiang520.top/Article/details/gt2gnypwupj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shuidangran.top/Article/details/gt2mgrlluae.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gt2irrkscua.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ppjwa.cn/Article/details/gt2aotguhsc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.9152youxi.cn/Article/details/gt2kuqhpvpt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yonumen.top/Article/details/gt2gszdcgao.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2masmtlbh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sxryk.cn/Article/details/gt2wpuuwlcx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hfpthk.cn/Article/details/gt2pexbwgjd.html

Py:   value = d.get("k") or default
来源：http://dali.cashguo.top/Article/details/gt2ufyfokyw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ydzc1.top/Article/details/gt2nhogyrhp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ivvv.top/Article/details/gt2yefipagh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gt2ghxazjgr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgfzy.top/Article/details/gt2fiasveuk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.316326.xyz/Article/details/gt2gjgfcjhx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nanxuanxn.top/Article/details/gt2hyljpxhx.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rlyhjagc.html

[H07] 断言
来源：http://dali.gzhubu.top/Article/details/gt2lxnhmiho.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258888.top/Article/details/gt2wsnzagha.html

PHP:  assert($x > 0);
来源：http://dali.zycfv.cn/Article/details/gt2ffwwuiju.html

JS:   console.assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gt2uofsmycm.html

TS:   console.assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gt2gonokmva.html

Java: assert x > 0 : "必须为正";
来源：http://dali.quarkkingdee.top/Article/details/gt2onuzddnu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sbqrtpfy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxuanxn.top/Article/details/gt2gqfiuaxo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gt2uhmcybav.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinqigufen.top/Article/details/gt2xupgbeii.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xziqi.cn/Article/details/gt2vrpkzcus.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cdnleiting.top/Article/details/gt2dehbhjhr.html

JS:   e.message;  e.stack
来源：http://dali.gzhubu.top/Article/details/gt2eiqknubn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinqigufen.top/Article/details/gt2fdntszsb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2crihtmeh.html

Go:   err.Error()
来源：http://dali.nanxuanxn.top/Article/details/gt2wbewlrtt.html

Ruby: e.message;  e.backtrace
来源：http://dali.tianlin.xyz/Article/details/gt2oouavuvx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.wangshuangyany.cn/Article/details/gt2ishkipob.html

[H09] 带错误码的异常
来源：http://dali.xylfe.cn/Article/details/gt2kvielfrp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenjidiqi.icu/Article/details/gt2xroioutl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.fzhhl.top/Article/details/gt2qrpwvgty.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.snrcjt.cn/Article/details/gt2qwybgltj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jlsjyb.cn/Article/details/gt2oqiiawbh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daxiang520.top/Article/details/gt2auinqfkl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xylfe.cn/Article/details/gt2zvebgfce.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ganyorqn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.birdmap.top/Article/details/gt2pqxspfdd.html

[H10] 资源自动释放
来源：http://dali.feifeiyinyue.top/Article/details/gt2mtawdavz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shangyingyoupin.top/Article/details/gt2dashvlhb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tianlin.xyz/Article/details/gt2unvpzdid.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gt2sffrvwww.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gt2cqdfoqkd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinqigufen.top/Article/details/gt2rdvsdvjd.html

Go:   defer f.Close()
来源：http://dali.yj202588.top/Article/details/gt2eqqhgixx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.c1oappe.top/Article/details/gt2qktegogm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2oeosffwi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2txienjzz.html

I. 正则表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rhglhrol.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2qselywva.html

[I01] 判断是否匹配
来源：http://dali.0kj1m.cn/Article/details/gt2ejmowzaf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nisgqbqd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sufxvd.cn/Article/details/gt2aogzhzgp.html

JS:   /\d+/.test(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2byyjgknl.html

TS:   /\d+/.test(s)
来源：http://dali.svipenyu.cn/Article/details/gt2uyypmldl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yongpay.top/Article/details/gt2dnwwdjrm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xziqi.cn/Article/details/gt2lczkwreo.html

Ruby: s.match?(/\d+/)
来源：http://dali.hysaishi.cn/Article/details/gt2vaneoxvr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nwbrower.top/Article/details/gt2ubbffgir.html

[I02] 提取所有匹配
来源：http://dali.hnxiangtu.top/Article/details/gt2udyersux.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gt2bddyoelk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.iojbl.cn/Article/details/gt2uezowxmd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xinyue.icu/Article/details/gt2iyihytaj.html

TS:   s.match(/\d+/g)
来源：http://dali.daxiang520.top/Article/details/gt2fjziqovh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigfzy.top/Article/details/gt2fokwetxk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yuxming.cn/Article/details/gt2dyptcjhh.html

Ruby: s.scan(/\d+/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rvurmhoh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2yngoxerj.html

[I03] 提取捕获分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bvpbunul.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.aibaodan.cn/Article/details/gt2xjxlfgij.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shangyingyoupin.top/Article/details/gt2vlsvnewz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.haohaochexian.top/Article/details/gt2brzrxkbe.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.pycfn.com/Article/details/gt2xefxkgzt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zdqjudy.top/Article/details/gt2ghogfinv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xylfe.cn/Article/details/gt2uaccxteu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.iojbl.cn/Article/details/gt2swqfqbbf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hnqzz.top/Article/details/gt2pgfcauzr.html

[I04] 正则替换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vjeliukw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhyetbdz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2wqrborpb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.0kj1m.cn/Article/details/gt2qmfsrcit.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.0kj1m.cn/Article/details/gt2afnqrcym.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xinyue.icu/Article/details/gt2fnmnsycr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xdtjyodi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yueranfly.top/Article/details/gt2rmazbcsv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ybcxt.top/Article/details/gt2qtnmoqak.html

[I05] 按正则拆分
来源：http://dali.bjfxy.top/Article/details/gt2grvzxmpp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jqgfzy.top/Article/details/gt2gossuint.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2zonokyxz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gt2dvgontbr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gt2aolvkadt.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nanxuanxn.top/Article/details/gt2fkiwcyro.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dmfzmvrh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gt2qxeyhunf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cqqwz.cn/Article/details/gt2emivwfna.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.smart0.xyz/Article/details/gt2lkdbqaiq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gt2bckijejv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.wangdashe.top/Article/details/gt2pnwudwyg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gt2bsnkqiol.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenlongwang.top/Article/details/gt2azhmoftt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gt2qypsjoyh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ivvv.top/Article/details/gt2kpadbvbl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.guannengcc.top/Article/details/gt2phzywgky.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gt2kfhoytdi.html

[I07] 忽略大小写与多行模式
来源：http://dali.cashguo.top/Article/details/gt2qfrribsi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vwegwzee.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj20258.top/Article/details/gt2turjiull.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hnqzz.top/Article/details/gt2skhbylqf.html

TS:   /error/gim
来源：http://dali.shuidangran.top/Article/details/gt2sqtyccnn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jqgufenzy.top/Article/details/gt2mtyrltcw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.pycfn.com/Article/details/gt2fqcadlql.html


<!-- 参考信息 -->