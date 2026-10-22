代发 wailian999

Py:   class User: pass
来源：http://dali.jlsjyb.cn/Article/details/gt2znfhiubf.html

PHP:  class User {}
来源：http://dali.dianchejie.cn/Article/details/gt2ewaobzvx.html

JS:   class User {}
来源：http://dali.wangdashe.top/Article/details/gt2fufpkveh.html

TS:   class User { name: string = ""; }
来源：http://dali.guowangkeji.top/Article/details/gt2iyjjgmlf.html

Java: class User {}
来源：http://dali.fzhhl.top/Article/details/gt2hxxbvmlr.html

Go:   type User struct { Name string }
来源：http://dali.ybcxt.top/Article/details/gt2ftwclfyx.html

Ruby: class User; end
来源：http://dali.jianghu66.top/Article/details/gt2cwtbdcsh.html

C#:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gt2hwzlyaoz.html

[G02] 构造函数
来源：http://dali.jqgfzy.top/Article/details/gt2jkwowwma.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yonumen.top/Article/details/gt2bthemqsv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xinyue.icu/Article/details/gt2tscnuzpj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenlongwang.top/Article/details/gt2ezgochpa.html

TS:   constructor(public name: string) {}
来源：http://dali.dianchejie.cn/Article/details/gt2gjhorgdu.html

Java: User(String name) { this.name = name; }
来源：http://dali.sweek.top/Article/details/gt2xwqzddjn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhixingplan.top/Article/details/gt2tbvdhbmn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.birdmap.top/Article/details/gt2xfxlblna.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ydzc1.top/Article/details/gt2yavjzcwe.html

[G03] 实例属性
来源：http://dali.shuidangran.top/Article/details/gt2tkmkosyn.html

Py:   self.name = "x"
来源：http://dali.yonumen.top/Article/details/gt2barxsgxj.html

PHP:  public string $name = "x";
来源：http://dali.hysaishi.cn/Article/details/gt2kfkeqdqp.html

JS:   this.name = "x";
来源：http://dali.aibaodan.cn/Article/details/gt2jvrouvjg.html

TS:   name: string = "x";
来源：http://dali.sysykeji.top/Article/details/gt2aemkmkys.html

Java: private String name;
来源：http://dali.yueranfly.top/Article/details/gt2dctdaaxt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigfzy.top/Article/details/gt2jxjswull.html

Ruby: @name = "x"
来源：http://dali.birdmap.top/Article/details/gt2bpkppphp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yueranfly.top/Article/details/gt2ulkscnir.html

[G04] 定义方法
来源：http://dali.sysykeji.top/Article/details/gt2ngndkgvx.html

Py:   def greet(self): return self.name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2btdzispy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gt2vdeazkfd.html

JS:   greet() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2mjyobrxr.html

TS:   greet(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gt2vsiwbfsm.html

Java: String greet() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2mnnstmnf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gt2iujtveio.html

Ruby: def greet; @name; end
来源：http://dali.jqgufenzy.top/Article/details/gt2akzjuwoh.html

C#:   public string Greet() => Name;
来源：http://dali.xylfe.cn/Article/details/gt2obrqxioi.html

[G05] 继承
来源：http://dali.gogol.net.cn/Article/details/gt2inobjmyr.html

Py:   class Admin(User): pass
来源：http://dali.sxryk.cn/Article/details/gt2xofsmtsh.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2agmrvple.html

JS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gt2cjpawogt.html

TS:   class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gt2tkpzlqkd.html

Java: class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gt2znnaoxcx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.fengsongda.top/Article/details/gt2ldkhyqui.html

Ruby: class Admin < User; end
来源：http://dali.cheryme.top/Article/details/gt2vwbuanep.html

C#:   class Admin : User {}
来源：http://dali.redwolf501.top/Article/details/gt2uzugsljm.html

[G06] 重写方法
来源：http://dali.quarkkingdee.top/Article/details/gt2nsvljdcn.html

Py:   def greet(self): return "admin"
来源：http://dali.shzxlz.cn/Article/details/gt2jmzjsyjm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vvptbvny.html

JS:   greet() { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gt2uilmilgg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gt2hrohetof.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gt2ngpfexvo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gzhubu.top/Article/details/gt2vtpvfsiy.html

Ruby: def greet; "admin"; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2sbhcoxjv.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj202588.top/Article/details/gt2nrtrgwvo.html

[G07] 调用父类方法
来源：http://dali.hysaishi.cn/Article/details/gt2xvqdpkev.html

Py:   super().greet()
来源：http://dali.sxryk.cn/Article/details/gt2lhvgbhoo.html

PHP:  parent::greet();
来源：http://dali.yuanzhike.top/Article/details/gt2saaiunde.html

JS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gt2utficsut.html

TS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gt2zplwpeln.html

Java: super.greet();
来源：http://dali.yj202588.top/Article/details/gt2asqydxup.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj20258.top/Article/details/gt2hzinqqns.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2alfoveoi.html

C#:   base.Greet();
来源：http://dali.ybcxt.top/Article/details/gt2qocbwhbx.html

[G08] 静态方法与属性
来源：http://dali.jinghuilouyu.cn/Article/details/gt2djxeriaj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.smart0.xyz/Article/details/gt2wupwjckw.html

PHP:  public static function f() {}
来源：http://dali.iojbl.cn/Article/details/gt2zuzgzdkh.html

JS:   static f() {}
来源：http://dali.jlsjyb.cn/Article/details/gt2fkunfznu.html

TS:   static f(): void {}
来源：http://dali.yongpay.top/Article/details/gt2bvjtprcy.html

Java: static void f() {}
来源：http://dali.cheryme.top/Article/details/gt2irtcrxxt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.quarkkingdee.top/Article/details/gt2mtphxkua.html

Ruby: def self.f; end
来源：http://dali.shzxlz.cn/Article/details/gt2oywkgjwc.html

C#:   public static void F() {}
来源：http://dali.yj20258.top/Article/details/gt2adoexluf.html

[G09] 接口 / 抽象类
来源：http://dali.jqgfzy.top/Article/details/gt2krfdbvlt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tanke756.top/Article/details/gt2iwkzuqnl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yangfankeji.com/Article/details/gt2qjtbzumc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nwbrower.top/Article/details/gt2toznazjf.html

TS:   interface Shape { area(): number; }
来源：http://dali.c1oappe.top/Article/details/gt2hjfpawcg.html

Java: interface Shape { double area(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2owuolmir.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2elmextjp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnxiangtu.top/Article/details/gt2whvnwznp.html

C#:   interface IShape { double Area(); }
来源：http://dali.yangfankeji.com/Article/details/gt2yhdmxwjc.html

[G10] 访问控制
来源：http://dali.nanxuanxn.top/Article/details/gt2jqeylddj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.guowangkeji.top/Article/details/gt2kiggsdvq.html

PHP:  public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gt2hnsphbei.html

JS:   #private 字段；其余公开
来源：http://dali.birdmap.top/Article/details/gt2bhgjkvrn.html

TS:   public / protected / private
来源：http://dali.xylfe.cn/Article/details/gt2pcxzpzmy.html

Java: public / protected / private / 默认包级
来源：http://dali.ehwqpu.com/Article/details/gt2zktvvpia.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guowangkeji.top/Article/details/gt2bycgycyz.html

Ruby: public / protected / private
来源：http://dali.cashguo.top/Article/details/gt2rujzfmra.html

C#:   public / protected / private / internal
来源：http://dali.aibaodan.cn/Article/details/gt2ichnwylj.html

[G11] getter / setter
来源：http://dali.sysykeji.top/Article/details/gt2fervyypb.html

Py:   @property 与 @x.setter
来源：http://dali.aibaodan.cn/Article/details/gt2vnymhfqm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gt2vruzwmxy.html

JS:   get name() { return this._name; }
来源：http://dali.yangfankeji.com/Article/details/gt2nydrubfv.html

TS:   get name(): string { return this._name; }
来源：http://dali.fengsongda.top/Article/details/gt2xvetweyy.html

Java: public String getName() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2tuuomgwu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gt2ifvsfzkw.html

Ruby: attr_accessor :name
来源：http://dali.guannengcc.top/Article/details/gt2tzzfzbcd.html

C#:   public string Name { get; set; }
来源：http://dali.zdqjudy.top/Article/details/gt2dntbkjwo.html

[G12] 对象转字符串
来源：http://dali.hfpthk.cn/Article/details/gt2xahzfqez.html

Py:   def __str__(self): return self.name
来源：http://dali.chenzaomai.com/Article/details/gt2vkydqfyt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gt2iirkgdrm.html

JS:   toString() { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hayvzwqa.html

TS:   toString(): string { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gt2mfithdbr.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xctzqmsv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gt2ezgnqlzg.html

Ruby: def to_s; @name; end
来源：http://dali.jqgufenzy.top/Article/details/gt2jokesiiu.html

C#:   public override string ToString() => Name;
来源：http://dali.pycfn.com/Article/details/gt2madcywye.html

[G13] 判断对象类型
来源：http://dali.hysaishi.cn/Article/details/gt2uhxooisz.html

Py:   isinstance(u, User)
来源：http://dali.gogol.net.cn/Article/details/gt2sywvqusw.html

PHP:  $u instanceof User
来源：http://dali.c1oappe.top/Article/details/gt2sdfyccfo.html

JS:   u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gt2ajvwfnie.html

TS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gt2efvtonaj.html

Java: u instanceof User
来源：http://dali.tanke756.top/Article/details/gt2ywogzbxf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.redwolf501.top/Article/details/gt2pymtyszk.html

Ruby: u.is_a?(User)
来源：http://dali.yanxiufei.cn/Article/details/gt2siaxrvpu.html

C#:   u is User
来源：http://dali.hammf.cn/Article/details/gt2vdqhnnzx.html

[G14] 数据类 / record
来源：http://dali.tianlin.xyz/Article/details/gt2hjmmcvbi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mzubzuaq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jqgufenzy.top/Article/details/gt2elrniwvb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.fzhhl.top/Article/details/gt2fnalrroh.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2brlaaaex.html

Java: record User(String name, int age) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2kptrtgtx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aizwys.cn/Article/details/gt2yfwliksd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.0kj1m.cn/Article/details/gt2jdoahrrq.html

C#:   record User(string Name, int Age);
来源：http://dali.zdqjudy.top/Article/details/gt2jabevwcu.html

[G15] 枚举
来源：http://dali.xuanzx.com/Article/details/gt2otsxvzxk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yuanzhike.top/Article/details/gt2ujzyvczs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cashguo.top/Article/details/gt2lfdrdxkn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.meibo888.top/Article/details/gt2psowbmzl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gt2zcbhcoxz.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigfzy.top/Article/details/gt2obmrprib.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ybcxt.top/Article/details/gt2qfzycwps.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yonumen.top/Article/details/gt2sgoaftum.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zycfv.cn/Article/details/gt2zbueowhm.html

[G16] 对象转数组 / 字典
来源：http://dali.zhongyouzk.top/Article/details/gt2mqjdrdsr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jiagoushi.top/Article/details/gt2dgazhbkr.html

PHP:  get_object_vars($obj);
来源：http://dali.wangdashe.top/Article/details/gt2pvvhvbim.html

JS:   Object.entries(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2qbhnwswd.html

TS:   Object.entries(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2odlfrmkr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tianlin.xyz/Article/details/gt2pvbqfagt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gogol.net.cn/Article/details/gt2heykbrha.html

Ruby: obj.instance_variables
来源：http://dali.yongpay.top/Article/details/gt2tnrfpexn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zycfv.cn/Article/details/gt2lxvykxsn.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2polpevtm.html

H. 异常与错误处理
来源：http://dali.shzxlz.cn/Article/details/gt2ohpomjwk.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2togghlvj.html

[H01] try / catch 基础
来源：http://dali.kuanghao11.cn/Article/details/gt2mmlduzsf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.wangdashe.top/Article/details/gt2mkaufqpi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2zkkesrri.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gt2ulzshjks.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gt2vsmzgquh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aibaodan.cn/Article/details/gt2dwiabtrl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhoulong.xyz/Article/details/gt2tkcmfzih.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cheryme.top/Article/details/gt2rfmvlwln.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gogol.net.cn/Article/details/gt2ijcctqzp.html

[H02] finally / ensure 收尾
来源：http://dali.sysykeji.top/Article/details/gt2vphpvgwk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.fzhhl.top/Article/details/gt2lcynwijb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gt2tcxjdknf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gt2xqfhoywy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gt2egsvynja.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gt2nqszlppa.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pfbpkbtp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shuidangran.top/Article/details/gt2jakiojde.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gt2zuquxgei.html

[H03] 主动抛出异常
来源：http://dali.ppjwa.cn/Article/details/gt2olrmbslz.html

Py:   raise ValueError("错误信息")
来源：http://dali.hammf.cn/Article/details/gt2ejyevgbw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gt2bokgifhi.html

JS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gt2tsrranbr.html

TS:   throw new Error("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2mvsbktgg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uozayvlw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.haohaochexian.top/Article/details/gt2amfxhakq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhixingplan.top/Article/details/gt2xpuaieim.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gt2dkuwcsfj.html

[H04] 自定义异常类型
来源：http://dali.sweek.top/Article/details/gt2xjjzibkp.html

Py:   class MyError(Exception): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fifdnqrs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gt2pctftoud.html

JS:   class MyError extends Error {}
来源：http://dali.fzhhl.top/Article/details/gt2ewbshxlg.html

TS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gt2wxanayrb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xziqi.cn/Article/details/gt2ypnnlcyh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sufxvd.cn/Article/details/gt2oqkyfaei.html

Ruby: class MyError < StandardError; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2uspjvefl.html

C#:   class MyException : Exception {}
来源：http://dali.guowangkeji.top/Article/details/gt2llvamjtp.html

[H05] 捕获特定类型
来源：http://dali.xinyue.icu/Article/details/gt2igpfhpmi.html

Py:   except ValueError as e:
来源：http://dali.kuanghao11.cn/Article/details/gt2tusuddsk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigfzy.top/Article/details/gt2qaezhhcc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2zcbeoiki.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shuidangran.top/Article/details/gt2lvthvmja.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aibaodan.cn/Article/details/gt2pcdodaqm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.haohaochexian.top/Article/details/gt2zvnppldq.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenzaomai.com/Article/details/gt2mzwwtclh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hfpthk.cn/Article/details/gt2mqiendpj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ppjwa.cn/Article/details/gt2okvyocmt.html

Py:   value = d.get("k") or default
来源：http://dali.iojbl.cn/Article/details/gt2ywcomuhy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.guowangkeji.top/Article/details/gt2rygknder.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cashguo.top/Article/details/gt2pchrdqjk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gt2ipgdxtqj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.9152youxi.cn/Article/details/gt2cdwcdkvd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ydzc1.top/Article/details/gt2yibujuvx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.mhx1999.top/Article/details/gt2igzgvrgd.html

C#:   obj?.A?.B ?? default
来源：http://dali.andypj.xyz/Article/details/gt2qckfdgwl.html

[H07] 断言
来源：http://dali.gaohongyu789.top/Article/details/gt2qrmhlzca.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuanzx.com/Article/details/gt2kgvhbjum.html

PHP:  assert($x > 0);
来源：http://dali.9152youxi.cn/Article/details/gt2nmqzrawf.html

JS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gt2ohvebxes.html

TS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gt2zxfzpbpt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.fengsongda.top/Article/details/gt2bvcmisle.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xziqi.cn/Article/details/gt2syipvqjs.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.snrcjt.cn/Article/details/gt2ldmroxri.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2qlceiawp.html

[H08] 获取错误信息与堆栈
来源：http://dali.dianchejie.cn/Article/details/gt2zgccbhzc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxuanxn.top/Article/details/gt2jnxjycpl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sxryk.cn/Article/details/gt2joallbdd.html

JS:   e.message;  e.stack
来源：http://dali.9152youxi.cn/Article/details/gt2fhmrbfuy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.snrcjt.cn/Article/details/gt2mfavecjw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sufxvd.cn/Article/details/gt2mbewfkzr.html

Go:   err.Error()
来源：http://dali.fengsongda.top/Article/details/gt2feqqopui.html

Ruby: e.message;  e.backtrace
来源：http://dali.shangyingyoupin.top/Article/details/gt2dzovdjsn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sweek.top/Article/details/gt2kxefucbt.html

[H09] 带错误码的异常
来源：http://dali.yuxming.cn/Article/details/gt2mdnbjnnd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.daxiang520.top/Article/details/gt2kasvjqck.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hywenlv.cn/Article/details/gt2wjkisatv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj202588.top/Article/details/gt2ravcagvs.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gzhubu.top/Article/details/gt2igskvace.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zdqjudy.top/Article/details/gt2ohrmioqe.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tanke756.top/Article/details/gt2lvuvynqt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yueranfly.top/Article/details/gt2yyhgjpou.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.wangshuangyany.cn/Article/details/gt2qxsykobg.html

[H10] 资源自动释放
来源：http://dali.smart0.xyz/Article/details/gt2bplzfghj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gogol.net.cn/Article/details/gt2hvipviuu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigufen.top/Article/details/gt2fnkuddam.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2xxckjrfz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jlsjyb.cn/Article/details/gt2tmfecqdu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.quarkkingdee.top/Article/details/gt2xzohejuq.html

Go:   defer f.Close()
来源：http://dali.xuanzx.com/Article/details/gt2yhdrwuvu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.andypj.xyz/Article/details/gt2araydjuk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2vlvvrnnd.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2zcuwbbrs.html

I. 正则表达式
来源：http://dali.tianlin.xyz/Article/details/gt2tgpegunp.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2qxkbofif.html

[I01] 判断是否匹配
来源：http://dali.birdmap.top/Article/details/gt2whxgzqin.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.dashuyun.cn/Article/details/gt2opbkjush.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xinyue.icu/Article/details/gt2hmrrjaxz.html

JS:   /\d+/.test(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2yawmptck.html

TS:   /\d+/.test(s)
来源：http://dali.jinqigufen.top/Article/details/gt2usdfcyvs.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.mhx1999.top/Article/details/gt2cjqhhqpn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xylfe.cn/Article/details/gt2xiqkgjij.html

Ruby: s.match?(/\d+/)
来源：http://dali.sysykeji.top/Article/details/gt2vpezmsjf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.redwolf501.top/Article/details/gt2qqidcniw.html

[I02] 提取所有匹配
来源：http://dali.sufxvd.cn/Article/details/gt2namsvpln.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yvedp.cn/Article/details/gt2vzbsyqmv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj20258888.top/Article/details/gt2igjubkod.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wgjvtbib.html

TS:   s.match(/\d+/g)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ehnjrzcc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2sqddjeir.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenlongwang.top/Article/details/gt2eozhellp.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaazkaen.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.c1oappe.top/Article/details/gt2wmvxupem.html

[I03] 提取捕获分组
来源：http://dali.hammf.cn/Article/details/gt2paidmrai.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2usqggmld.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.svipenyu.cn/Article/details/gt2etbfnvwu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vyfqlvbn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gogol.net.cn/Article/details/gt2vrxzobds.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhixingplan.top/Article/details/gt2wtjpbzsf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ybcxt.top/Article/details/gt2vzihevtj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.daria6918.cn/Article/details/gt2mkkjkapd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fzhhl.top/Article/details/gt2fzvtatgc.html

[I04] 正则替换
来源：http://dali.hnxiangtu.top/Article/details/gt2vsnentnx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.havefunace.top/Article/details/gt2roitqsfv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.fengsongda.top/Article/details/gt2sokbksim.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cdnleiting.top/Article/details/gt2jdtztsvs.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gt2zkivdryt.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2oaxdrsxx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gt2hscvueuz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gt2wbhjevpb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gt2jnkrjbto.html

[I05] 按正则拆分
来源：http://dali.shzxlz.cn/Article/details/gt2hmwdlnvx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj20258888.top/Article/details/gt2cicueccl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shzxlz.cn/Article/details/gt2fxlrbghe.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gt2nqsgemiw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gt2coihmujj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.haohaochexian.top/Article/details/gt2uclnovot.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.mhx1999.top/Article/details/gt2zjxnoxty.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2phxetdba.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cdnleiting.top/Article/details/gt2vkhmhegz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigfzy.top/Article/details/gt2wbfwzziz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qsmtrimv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hnqzz.top/Article/details/gt2pvbfqoec.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gt2nmgteqwr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nwbrower.top/Article/details/gt2lshroziz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gt2egavgqgx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj20258.top/Article/details/gt2jrjctjmj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.iojbl.cn/Article/details/gt2eevjhapo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gt2ujoxsogb.html

[I07] 忽略大小写与多行模式
来源：http://dali.zdqjudy.top/Article/details/gt2izdovyfb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigfzy.top/Article/details/gt2rlxfnyvg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gt2nczrjqpr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jlsjyb.cn/Article/details/gt2zmzzsrhe.html

TS:   /error/gim
来源：http://dali.nanxuanxn.top/Article/details/gt2awkzlxlq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.haohaochexian.top/Article/details/gt2aovdndmm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jqgufenzy.top/Article/details/gt2lzpyyxhk.html


<!-- 参考信息 -->