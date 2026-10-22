代发 wailian999

Py:   class User: pass
来源：http://dali.chenjidiqi.icu/Article/details/gt2nmhipcah.html

PHP:  class User {}
来源：http://dali.shuidangran.top/Article/details/gt2umdlsxbh.html

JS:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lamkgkzj.html

TS:   class User { name: string = ""; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rnynwdbc.html

Java: class User {}
来源：http://dali.ybcxt.top/Article/details/gt2qdsnxijy.html

Go:   type User struct { Name string }
来源：http://dali.gotoacloud.top/Article/details/gt2wkunxiqd.html

Ruby: class User; end
来源：http://dali.jinqigfzy.top/Article/details/gt2vnhqeywk.html

C#:   class User {}
来源：http://dali.jianghu66.top/Article/details/gt2yidofswo.html

[G02] 构造函数
来源：http://dali.snrcjt.cn/Article/details/gt2vptswyox.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jyoumei.cn/Article/details/gt2wbocibct.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtviflq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gt2dvvdebag.html

TS:   constructor(public name: string) {}
来源：http://dali.aibaodan.cn/Article/details/gt2jdowhnyg.html

Java: User(String name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lpprxufd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ppjwa.cn/Article/details/gt2cczsoioq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sysykeji.top/Article/details/gt2rhespfat.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xqwkqrsw.html

[G03] 实例属性
来源：http://dali.gaohongyu789.top/Article/details/gt2tdsprzbh.html

Py:   self.name = "x"
来源：http://dali.sweek.top/Article/details/gt2dtgbjson.html

PHP:  public string $name = "x";
来源：http://dali.yuxming.cn/Article/details/gt2rlpphgcj.html

JS:   this.name = "x";
来源：http://dali.bjfxy.top/Article/details/gt2eirwwfvu.html

TS:   name: string = "x";
来源：http://dali.yuxming.cn/Article/details/gt2pqrrnsbk.html

Java: private String name;
来源：http://dali.xziqi.cn/Article/details/gt2ivalcjpz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj202588.top/Article/details/gt2oqiebapu.html

Ruby: @name = "x"
来源：http://dali.xziqi.cn/Article/details/gt2bjwjbpcl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guowangkeji.top/Article/details/gt2ssvjrabe.html

[G04] 定义方法
来源：http://dali.jiagoushi.top/Article/details/gt2fcvhqdhp.html

Py:   def greet(self): return self.name
来源：http://dali.tanke756.top/Article/details/gt2wgogpvlg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2lorblvnz.html

JS:   greet() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gt2xiehmkgv.html

TS:   greet(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gt2sxnrutyf.html

Java: String greet() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2swpmrbss.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gt2uawoffyj.html

Ruby: def greet; @name; end
来源：http://dali.zhengqikj.top/Article/details/gt2zvrkiayv.html

C#:   public string Greet() => Name;
来源：http://dali.cheryme.top/Article/details/gt2xovcibkm.html

[G05] 继承
来源：http://dali.ydzc1.top/Article/details/gt2qenwvlhh.html

Py:   class Admin(User): pass
来源：http://dali.zhoulong.xyz/Article/details/gt2ripuvsgg.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gt2ecdfjkrv.html

JS:   class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gt2tytooncf.html

TS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gt2wjthrsno.html

Java: class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2fabdylfr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cucudq.cn/Article/details/gt2jzzfhpir.html

Ruby: class Admin < User; end
来源：http://dali.zycfv.cn/Article/details/gt2wcckriuk.html

C#:   class Admin : User {}
来源：http://dali.jianghu66.top/Article/details/gt2xiybixxp.html

[G06] 重写方法
来源：http://dali.pengpengdd.cyou/Article/details/gt2thkseral.html

Py:   def greet(self): return "admin"
来源：http://dali.wangshuangyany.cn/Article/details/gt2qkemjedg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ecroiezf.html

JS:   greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gt2nyxrgeis.html

TS:   greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2wnsshnhi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gt2drlhemcv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.meibo888.top/Article/details/gt2dytlonqf.html

Ruby: def greet; "admin"; end
来源：http://dali.andypj.xyz/Article/details/gt2iuuehnum.html

C#:   public override string Greet() => "admin";
来源：http://dali.jlsjyb.cn/Article/details/gt2orxcnvwv.html

[G07] 调用父类方法
来源：http://dali.yj202588.top/Article/details/gt2soupvugt.html

Py:   super().greet()
来源：http://dali.dianchejie.cn/Article/details/gt2ovqhomrd.html

PHP:  parent::greet();
来源：http://dali.shuidangran.top/Article/details/gt2gfnzhqaa.html

JS:   super.greet();
来源：http://dali.yj202588.top/Article/details/gt2iqsolqtu.html

TS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gt2vllcjefh.html

Java: super.greet();
来源：http://dali.sufxvd.cn/Article/details/gt2klmuiroh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zjptyswn.html

Ruby: super
来源：http://dali.cashguo.top/Article/details/gt2nxadtslv.html

C#:   base.Greet();
来源：http://dali.hysaishi.cn/Article/details/gt2bcbiaayn.html

[G08] 静态方法与属性
来源：http://dali.chenlongwang.top/Article/details/gt2qfsolijx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.fengsongda.top/Article/details/gt2yhzzoobn.html

PHP:  public static function f() {}
来源：http://dali.kuanghao11.cn/Article/details/gt2alawulqq.html

JS:   static f() {}
来源：http://dali.fzhhl.top/Article/details/gt2rgxyirqr.html

TS:   static f(): void {}
来源：http://dali.jqgufenzy.top/Article/details/gt2loqufnnn.html

Java: static void f() {}
来源：http://dali.zhengqikj.top/Article/details/gt2cjxpkuwc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cashguo.top/Article/details/gt2wddokgdd.html

Ruby: def self.f; end
来源：http://dali.yonumen.top/Article/details/gt2azzdikvd.html

C#:   public static void F() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rspdaqlt.html

[G09] 接口 / 抽象类
来源：http://dali.daxiang520.top/Article/details/gt2zagygxbx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj20258888.top/Article/details/gt2vbwwjskh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2brgqukll.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hfpthk.cn/Article/details/gt2hcqdkfut.html

TS:   interface Shape { area(): number; }
来源：http://dali.jlsjyb.cn/Article/details/gt2fuactchl.html

Java: interface Shape { double area(); }
来源：http://dali.svipenyu.cn/Article/details/gt2fsrxtxed.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gzhubu.top/Article/details/gt2mdxntktu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aibaodan.cn/Article/details/gt2wbjpzamd.html

C#:   interface IShape { double Area(); }
来源：http://dali.tian-w.cn/Article/details/gt2midsqyju.html

[G10] 访问控制
来源：http://dali.bjfxy.top/Article/details/gt2gwchuvvl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yangfankeji.com/Article/details/gt2pygvnsio.html

PHP:  public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gt2ailfqpfg.html

JS:   #private 字段；其余公开
来源：http://dali.chenjidiqi.icu/Article/details/gt2acoellzy.html

TS:   public / protected / private
来源：http://dali.tian-w.cn/Article/details/gt2ndirtznb.html

Java: public / protected / private / 默认包级
来源：http://dali.aibaodan.cn/Article/details/gt2aqeqnalq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sweek.top/Article/details/gt2oklnbiyo.html

Ruby: public / protected / private
来源：http://dali.xinyue.icu/Article/details/gt2dtydomtw.html

C#:   public / protected / private / internal
来源：http://dali.zhixingplan.top/Article/details/gt2tglpdsql.html

[G11] getter / setter
来源：http://dali.jinqigufen.top/Article/details/gt2thiovfsf.html

Py:   @property 与 @x.setter
来源：http://dali.shzxlz.cn/Article/details/gt2pcblifsy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gt2pqwzcjia.html

JS:   get name() { return this._name; }
来源：http://dali.xuanzx.com/Article/details/gt2acqljjnf.html

TS:   get name(): string { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2infgqhkn.html

Java: public String getName() { return name; }
来源：http://dali.daria6918.cn/Article/details/gt2bvjttnlz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gt2jhrbzzut.html

Ruby: attr_accessor :name
来源：http://dali.dianchejie.cn/Article/details/gt2bifhowry.html

C#:   public string Name { get; set; }
来源：http://dali.nwbrower.top/Article/details/gt2ocrhwccb.html

[G12] 对象转字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2ekckazcz.html

Py:   def __str__(self): return self.name
来源：http://dali.xuanzx.com/Article/details/gt2hnvmjahp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gt2tfbpcpaz.html

JS:   toString() { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gt2fgstoylq.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2idztjoea.html

Java: @Override public String toString() { return name; }
来源：http://dali.ivvv.top/Article/details/gt2lnyswlxi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gt2dgxvqeiz.html

Ruby: def to_s; @name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pqtdrtze.html

C#:   public override string ToString() => Name;
来源：http://dali.bjfxy.top/Article/details/gt2qmobudys.html

[G13] 判断对象类型
来源：http://dali.jyoumei.cn/Article/details/gt2gcirbtbi.html

Py:   isinstance(u, User)
来源：http://dali.haohaochexian.top/Article/details/gt2okaeeymg.html

PHP:  $u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gt2gxyllfwf.html

JS:   u instanceof User
来源：http://dali.ybcxt.top/Article/details/gt2oheruxnw.html

TS:   u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gt2scwclobc.html

Java: u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gt2yqufmxco.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.snrcjt.cn/Article/details/gt2aakeiiha.html

Ruby: u.is_a?(User)
来源：http://dali.nanxinkj.top/Article/details/gt2lfpvcjbv.html

C#:   u is User
来源：http://dali.zycfv.cn/Article/details/gt2ajyvshos.html

[G14] 数据类 / record
来源：http://dali.hywenlv.cn/Article/details/gt2yyseahbv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ybcxt.top/Article/details/gt2jhjfzosk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jqgfzy.top/Article/details/gt2gshipkfp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xylfe.cn/Article/details/gt2izltywjh.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jakoufgs.html

Java: record User(String name, int age) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2sqfwdjus.html

Go:   type User struct { Name string; Age int }
来源：http://dali.svipenyu.cn/Article/details/gt2fqgfwvcn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhoulong.xyz/Article/details/gt2xrxnolpz.html

C#:   record User(string Name, int Age);
来源：http://dali.sufxvd.cn/Article/details/gt2zkecidsi.html

[G15] 枚举
来源：http://dali.gogol.net.cn/Article/details/gt2ncjqtqst.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ppjwa.cn/Article/details/gt2iunorhhg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.havefunace.top/Article/details/gt2yowcabfm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nyqsafsw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ojgvhhlk.html

Java: enum Color { RED, GREEN }
来源：http://dali.shuidangran.top/Article/details/gt2rbhrujaa.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenlongwang.top/Article/details/gt2idfonnzq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cashguo.top/Article/details/gt2tvmyxkcp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.iojbl.cn/Article/details/gt2lparwcin.html

[G16] 对象转数组 / 字典
来源：http://dali.yuxming.cn/Article/details/gt2hwvwiflp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hnxiangtu.top/Article/details/gt2mglufdef.html

PHP:  get_object_vars($obj);
来源：http://dali.zhongyouzk.top/Article/details/gt2ekvzrmas.html

JS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gt2gexqgmmm.html

TS:   Object.entries(obj)
来源：http://dali.shuidangran.top/Article/details/gt2vvsxpwxm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wjsbldry.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rfoaydbt.html

Ruby: obj.instance_variables
来源：http://dali.bjfxy.top/Article/details/gt2ivugoasn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pevmjqbi.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2rrnyzfur.html

H. 异常与错误处理
来源：http://dali.shzxlz.cn/Article/details/gt2xodylanx.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2sfuhsoef.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhcxcpl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.pycfn.com/Article/details/gt2grfwdypo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hzggsjop.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2bpkxbljz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gt2eoiynlxr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ehwqpu.com/Article/details/gt2wzpsfxnf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.snrcjt.cn/Article/details/gt2cgmfsimr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.daxiang520.top/Article/details/gt2mfelaphr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sufxvd.cn/Article/details/gt2btkwixhf.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2alpuwxbm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xinyue.icu/Article/details/gt2hetxpady.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nucccshj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wupkjvjt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2mzzhubjm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pbyopyfo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.fengsongda.top/Article/details/gt2uzoznfae.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2ggcvoewt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gt2mspdeueh.html

[H03] 主动抛出异常
来源：http://dali.sysykeji.top/Article/details/gt2tzffnbwv.html

Py:   raise ValueError("错误信息")
来源：http://dali.ydzc1.top/Article/details/gt2smjvmhkg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gt2opixrxoz.html

JS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gt2qcvaycki.html

TS:   throw new Error("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gt2zwrtfcgb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gt2eywycsai.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cucudq.cn/Article/details/gt2wjkyxset.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.meibo888.top/Article/details/gt2otrbxlcb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gt2vwaxtekk.html

[H04] 自定义异常类型
来源：http://dali.andypj.xyz/Article/details/gt2vuyoksuo.html

Py:   class MyError(Exception): pass
来源：http://dali.meibo888.top/Article/details/gt2hdoxczvv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.aizwys.cn/Article/details/gt2pppoxbfx.html

JS:   class MyError extends Error {}
来源：http://dali.daria6918.cn/Article/details/gt2yiycpqvk.html

TS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gt2mrdsalao.html

Java: class MyException extends RuntimeException {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2knykbelx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sxryk.cn/Article/details/gt2lenduvxa.html

Ruby: class MyError < StandardError; end
来源：http://dali.shuidangran.top/Article/details/gt2qvrwqlcj.html

C#:   class MyException : Exception {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2axktqykx.html

[H05] 捕获特定类型
来源：http://dali.cheryme.top/Article/details/gt2zmvurggm.html

Py:   except ValueError as e:
来源：http://dali.cqqwz.cn/Article/details/gt2egdchria.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gotoacloud.top/Article/details/gt2zrjiqgyx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2lywgprys.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uysutavu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.pycfn.com/Article/details/gt2cltykoei.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhengqikj.top/Article/details/gt2frfychrx.html

Ruby: rescue ArgumentError => e
来源：http://dali.feifeiyinyue.top/Article/details/gt2opoosopt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.316326.xyz/Article/details/gt2hyqkrlld.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gogol.net.cn/Article/details/gt2ifervmwe.html

Py:   value = d.get("k") or default
来源：http://dali.tian-w.cn/Article/details/gt2rytiayjt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gotoacloud.top/Article/details/gt2lwbcftdt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gt2edfenqjt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guowangkeji.top/Article/details/gt2pmtzqkxr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yangfankeji.com/Article/details/gt2xdnsmgmk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ehwqpu.com/Article/details/gt2iuilbnvo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258888.top/Article/details/gt2fytalnkp.html

C#:   obj?.A?.B ?? default
来源：http://dali.xziqi.cn/Article/details/gt2zatezmlr.html

[H07] 断言
来源：http://dali.jinqigufen.top/Article/details/gt2eojhhnvc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuanzx.com/Article/details/gt2uhnsjvpp.html

PHP:  assert($x > 0);
来源：http://dali.jinqigufen.top/Article/details/gt2rluvabte.html

JS:   console.assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2psugyjuf.html

TS:   console.assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gt2amimkpjt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxinkj.top/Article/details/gt2jglelfaa.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xinyue.icu/Article/details/gt2ndqaumxr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.smart0.xyz/Article/details/gt2skijmlwl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gt2bgrovgvr.html

[H08] 获取错误信息与堆栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rhycsuro.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.feifeiyinyue.top/Article/details/gt2qeeiownw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tanke756.top/Article/details/gt2odrbfmwz.html

JS:   e.message;  e.stack
来源：http://dali.jinqigfzy.top/Article/details/gt2dpdvcrfc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rftjojty.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xylfe.cn/Article/details/gt2cgvljfdk.html

Go:   err.Error()
来源：http://dali.yangfankeji.com/Article/details/gt2dyzimnfo.html

Ruby: e.message;  e.backtrace
来源：http://dali.xziqi.cn/Article/details/gt2ppjeypdi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.andypj.xyz/Article/details/gt2byoyznia.html

[H09] 带错误码的异常
来源：http://dali.gotoacloud.top/Article/details/gt2doeujpmq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangdashe.top/Article/details/gt2xxjwkuiw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yonumen.top/Article/details/gt2rfcxegvu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jlsjyb.cn/Article/details/gt2aqwuziab.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.bjfxy.top/Article/details/gt2ptpozesh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yonumen.top/Article/details/gt2vipdyakn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zycfv.cn/Article/details/gt2tegrsjfu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinqigfzy.top/Article/details/gt2elbngokd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nanxuanxn.top/Article/details/gt2pguuohzh.html

[H10] 资源自动释放
来源：http://dali.daxiang520.top/Article/details/gt2xxgldzws.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zdqjudy.top/Article/details/gt2gosafval.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhiwuduotai.top/Article/details/gt2hiinauze.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pengpengdd.cyou/Article/details/gt2oruabxgo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.andypj.xyz/Article/details/gt2dcbsnrwx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.havefunace.top/Article/details/gt2sgykmaov.html

Go:   defer f.Close()
来源：http://dali.aizwys.cn/Article/details/gt2hwngwdxv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinqigfzy.top/Article/details/gt2hmqcsrzw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jdwcojyh.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2sjkfyuat.html

I. 正则表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xbzdtrqi.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2uhybftzy.html

[I01] 判断是否匹配
来源：http://dali.hnqzz.top/Article/details/gt2yhgyptrw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ivvv.top/Article/details/gt2uhahbsrj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2eznhgtfn.html

JS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2aqihzhob.html

TS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gt2jufcrhca.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.aibaodan.cn/Article/details/gt2adpzvwep.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgfzy.top/Article/details/gt2iwoobfxi.html

Ruby: s.match?(/\d+/)
来源：http://dali.yuxming.cn/Article/details/gt2aldqlfnl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ehwqpu.com/Article/details/gt2qizvewwk.html

[I02] 提取所有匹配
来源：http://dali.dashuyun.cn/Article/details/gt2xjlatwaz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tianlin.xyz/Article/details/gt2csimuruw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.316326.xyz/Article/details/gt2hqfyrrvj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangshuangyany.cn/Article/details/gt2oivplmog.html

TS:   s.match(/\d+/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lsojqtvq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2yxqtzlmz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zycfv.cn/Article/details/gt2lcolwevl.html

Ruby: s.scan(/\d+/)
来源：http://dali.daria6918.cn/Article/details/gt2rufwmurp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hcvqwoeq.html

[I03] 提取捕获分组
来源：http://dali.xinyue.icu/Article/details/gt2jkkvhejn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.c1oappe.top/Article/details/gt2ddffcidy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jiagoushi.top/Article/details/gt2jtglnjfw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xziqi.cn/Article/details/gt2sphcfjlg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.meibo888.top/Article/details/gt2siyihbcm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jianghu66.top/Article/details/gt2wtwgiihz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cdnleiting.top/Article/details/gt2tytabadf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jagknvyv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hammf.cn/Article/details/gt2uqetgacz.html

[I04] 正则替换
来源：http://dali.xuetiantiany.cn/Article/details/gt2zdwagttn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nanxinkj.top/Article/details/gt2prtpaqqo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.aizwys.cn/Article/details/gt2ftiopbmo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tidydazj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daria6918.cn/Article/details/gt2yopejmib.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.andypj.xyz/Article/details/gt2nvtggchx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ibsqnqki.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.haohaochexian.top/Article/details/gt2rjjohuuk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gt2vqhijgga.html

[I05] 按正则拆分
来源：http://dali.yj20258.top/Article/details/gt2rcebnrms.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yuanzhike.top/Article/details/gt2lmbktwmq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cashguo.top/Article/details/gt2ajjiovxx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gt2bbutjzvl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gt2hlkdczmy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.fzhhl.top/Article/details/gt2buffvwuf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zqsrwdwt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gt2wnrcvrvx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sadqftpo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jiagoushi.top/Article/details/gt2mhulgtzx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gt2uwcgvzjl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinqigufen.top/Article/details/gt2uenegjie.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hywenlv.cn/Article/details/gt2wlizqrvb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gt2tizkmegv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj202588.top/Article/details/gt2dfcdigtu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pdgazird.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nzfbmdug.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gt2unmjlpdf.html

[I07] 忽略大小写与多行模式
来源：http://dali.hongshengwenyu.top/Article/details/gt2nhhcsnmi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cuoprxlv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.fzhhl.top/Article/details/gt2mizqghjn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bcemipqx.html

TS:   /error/gim
来源：http://dali.ydzc1.top/Article/details/gt2wvghrypx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.mhx1999.top/Article/details/gt2qmhwtahm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pyaohbao.html


<!-- 参考信息 -->