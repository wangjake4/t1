代发 wailian999

Java: class User {}
来源：http://dali.xziqi.cn/Article/details/gtfwxmdwcg.html

Go:   type User struct { Name string }
来源：http://dali.cucudq.cn/Article/details/gttuaetekk.html

Ruby: class User; end
来源：http://dali.cashguo.top/Article/details/gtbdhjvmsi.html

C#:   class User {}
来源：http://dali.cheryme.top/Article/details/gtphyvqbgv.html

[G02] 构造函数
来源：http://dali.xuanzx.com/Article/details/gtfnzytbpp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sxryk.cn/Article/details/gtwboetsoi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxwmlzrv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtfdmensvx.html

TS:   constructor(public name: string) {}
来源：http://dali.jiagoushi.top/Article/details/gtsaqhbuje.html

Java: User(String name) { this.name = name; }
来源：http://dali.xylfe.cn/Article/details/gtnhpozauu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aizwys.cn/Article/details/gtjrwaxiag.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nwbrower.top/Article/details/gtwuoxfdma.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdhweidiq.html

[G03] 实例属性
来源：http://dali.guowangkeji.top/Article/details/gtfsqbokni.html

Py:   self.name = "x"
来源：http://dali.zhixingplan.top/Article/details/gtttskrrqa.html

PHP:  public string $name = "x";
来源：http://dali.yangfankeji.com/Article/details/gtvadpivjc.html

JS:   this.name = "x";
来源：http://dali.tianlin.xyz/Article/details/gtfmgalfvf.html

TS:   name: string = "x";
来源：http://dali.chenlongwang.top/Article/details/gtfqmkbgkm.html

Java: private String name;
来源：http://dali.sufxvd.cn/Article/details/gtlstkbhdj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yvedp.cn/Article/details/gttzaissff.html

Ruby: @name = "x"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnsxeowcj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.redwolf501.top/Article/details/gtmmokcbdt.html

[G04] 定义方法
来源：http://dali.hfpthk.cn/Article/details/gtdtuxzciv.html

Py:   def greet(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtykvnzmjt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gtlsltenkr.html

JS:   greet() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtulmmtons.html

TS:   greet(): string { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtqriimncq.html

Java: String greet() { return name; }
来源：http://dali.sweek.top/Article/details/gtkkrucaaj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gtcjsitpud.html

Ruby: def greet; @name; end
来源：http://dali.smart0.xyz/Article/details/gtpjrvoanh.html

C#:   public string Greet() => Name;
来源：http://dali.jlsjyb.cn/Article/details/gtaugvabrt.html

[G05] 继承
来源：http://dali.hnxiangtu.top/Article/details/gtivtkcdsu.html

Py:   class Admin(User): pass
来源：http://dali.yj20258.top/Article/details/gtosgadudx.html

PHP:  class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtepeexhly.html

JS:   class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gtxhtdsxnl.html

TS:   class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtjthswejs.html

Java: class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtxxtppzwy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yonumen.top/Article/details/gtqdwlnnwl.html

Ruby: class Admin < User; end
来源：http://dali.daria6918.cn/Article/details/gtwkokdxma.html

C#:   class Admin : User {}
来源：http://dali.yj202588.top/Article/details/gtujkbnrkb.html

[G06] 重写方法
来源：http://dali.sxryk.cn/Article/details/gtdmpnabnn.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigufen.top/Article/details/gtpegwuekh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtybtwksro.html

JS:   greet() { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtkesamonf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gttkxwjfeg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gttkwkwffj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.pengpengdd.cyou/Article/details/gtajhyfrxf.html

Ruby: def greet; "admin"; end
来源：http://dali.yongpay.top/Article/details/gtkpjhciha.html

C#:   public override string Greet() => "admin";
来源：http://dali.snrcjt.cn/Article/details/gtncbvadvf.html

[G07] 调用父类方法
来源：http://dali.redwolf501.top/Article/details/gtvinfxugs.html

Py:   super().greet()
来源：http://dali.zhongyouzk.top/Article/details/gtrlzzpttb.html

PHP:  parent::greet();
来源：http://dali.ybcxt.top/Article/details/gtuehzbpbt.html

JS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gtmvaivkjd.html

TS:   super.greet();
来源：http://dali.zhengqikj.top/Article/details/gtkwawwzay.html

Java: super.greet();
来源：http://dali.zhixingplan.top/Article/details/gttkxxlofz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.havefunace.top/Article/details/gthtlpejow.html

Ruby: super
来源：http://dali.chenlongwang.top/Article/details/gtbrelname.html

C#:   base.Greet();
来源：http://dali.xinyue.icu/Article/details/gtnrqedywq.html

[G08] 静态方法与属性
来源：http://dali.fzhhl.top/Article/details/gtajgcpwco.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xziqi.cn/Article/details/gtyrdgnctg.html

PHP:  public static function f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtggtmaozh.html

JS:   static f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtffqwgoxa.html

TS:   static f(): void {}
来源：http://dali.gogol.net.cn/Article/details/gtwemulvpa.html

Java: static void f() {}
来源：http://dali.andypj.xyz/Article/details/gttwhafbue.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nanxuanxn.top/Article/details/gturqmfeos.html

Ruby: def self.f; end
来源：http://dali.cdnleiting.top/Article/details/gtkkpzueka.html

C#:   public static void F() {}
来源：http://dali.gogol.net.cn/Article/details/gthzztzvdj.html

[G09] 接口 / 抽象类
来源：http://dali.cucudq.cn/Article/details/gtxabpylue.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pengpengdd.cyou/Article/details/gtsxnueivc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.quarkkingdee.top/Article/details/gtxwcbwqff.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.redwolf501.top/Article/details/gtkokdmgcq.html

TS:   interface Shape { area(): number; }
来源：http://dali.sweek.top/Article/details/gtltvqwjil.html

Java: interface Shape { double area(); }
来源：http://dali.yvedp.cn/Article/details/gtruifogsh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shuidangran.top/Article/details/gtjvzvppnf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hongshengwenyu.top/Article/details/gthdaewkyg.html

C#:   interface IShape { double Area(); }
来源：http://dali.ybcxt.top/Article/details/gtescntprd.html

[G10] 访问控制
来源：http://dali.gaohongyu789.top/Article/details/gtdblkobox.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yongpay.top/Article/details/gtuxtfcpbm.html

PHP:  public / protected / private
来源：http://dali.cashguo.top/Article/details/gtzczmbrwu.html

JS:   #private 字段；其余公开
来源：http://dali.316326.xyz/Article/details/gtejiwzzql.html

TS:   public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gtsobwvaur.html

Java: public / protected / private / 默认包级
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlifxqgzk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.mhx1999.top/Article/details/gtquflsqst.html

Ruby: public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gtomicyxef.html

C#:   public / protected / private / internal
来源：http://dali.aibaodan.cn/Article/details/gtfangqbhx.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gtkaadlmtq.html

Py:   @property 与 @x.setter
来源：http://dali.ybcxt.top/Article/details/gtpdnnunzz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gtcrucslty.html

JS:   get name() { return this._name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtjqozwyfa.html

TS:   get name(): string { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gtzmwoorji.html

Java: public String getName() { return name; }
来源：http://dali.jianghu66.top/Article/details/gtpmljdhen.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gteefsxhuw.html

Ruby: attr_accessor :name
来源：http://dali.havefunace.top/Article/details/gtbxqxaszc.html

C#:   public string Name { get; set; }
来源：http://dali.zdqjudy.top/Article/details/gtlkqyxeii.html

[G12] 对象转字符串
来源：http://dali.ppjwa.cn/Article/details/gtlkepjnth.html

Py:   def __str__(self): return self.name
来源：http://dali.bjfxy.top/Article/details/gtdjrivawd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtwgcccqua.html

JS:   toString() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtlkyhqtol.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjsphgzsh.html

Java: @Override public String toString() { return name; }
来源：http://dali.cashguo.top/Article/details/gtxrdguwoc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gtuozvmetx.html

Ruby: def to_s; @name; end
来源：http://dali.aizwys.cn/Article/details/gtqtvplyhg.html

C#:   public override string ToString() => Name;
来源：http://dali.nanxinkj.top/Article/details/gthdegdsmh.html

[G13] 判断对象类型
来源：http://dali.andypj.xyz/Article/details/gtgqirinft.html

Py:   isinstance(u, User)
来源：http://dali.zhoulong.xyz/Article/details/gtdktykcfr.html

PHP:  $u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtfqalxwru.html

JS:   u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gtogixbtve.html

TS:   u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gtyioolwvh.html

Java: u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtawmgkbnh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.kuanghao11.cn/Article/details/gtfmoqhffr.html

Ruby: u.is_a?(User)
来源：http://dali.hywenlv.cn/Article/details/gtralmzziu.html

C#:   u is User
来源：http://dali.zycfv.cn/Article/details/gtinymbvbh.html

[G14] 数据类 / record
来源：http://dali.jinyuanbaomall.cn/Article/details/gtevqqbtcp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.havefunace.top/Article/details/gtowiklwdt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigfzy.top/Article/details/gtwouuxssz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shuidangran.top/Article/details/gtlgaauhkn.html

TS:   type User = { name: string; age: number };
来源：http://dali.sufxvd.cn/Article/details/gtvwstcvvr.html

Java: record User(String name, int age) {}
来源：http://dali.yongpay.top/Article/details/gthpxkdkju.html

Go:   type User struct { Name string; Age int }
来源：http://dali.svipenyu.cn/Article/details/gtpoygmvmd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ehwqpu.com/Article/details/gtuuzbzjph.html

C#:   record User(string Name, int Age);
来源：http://dali.yj202588.top/Article/details/gtxpzsyepv.html

[G15] 枚举
来源：http://dali.wangshuangyany.cn/Article/details/gthqebryay.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xylfe.cn/Article/details/gtuumzrlrq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258.top/Article/details/gtgbgkvfcm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cheryme.top/Article/details/gturfbbgga.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfokrobot.html

Java: enum Color { RED, GREEN }
来源：http://dali.pengpengdd.cyou/Article/details/gtzxgdssva.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhongyouzk.top/Article/details/gtwethljaq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.aibaodan.cn/Article/details/gtxthtaoec.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.0kj1m.cn/Article/details/gtcobdooqr.html

[G16] 对象转数组 / 字典
来源：http://dali.zhoulong.xyz/Article/details/gtuesgeqjg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jyoumei.cn/Article/details/gtffzxgdsv.html

PHP:  get_object_vars($obj);
来源：http://dali.tian-w.cn/Article/details/gtmyeiidxm.html

JS:   Object.entries(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtwbvxtjuy.html

TS:   Object.entries(obj)
来源：http://dali.iojbl.cn/Article/details/gtjgzgxlpi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.vqdsnc.cn/Article/details/gtjypyckjx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jianghu66.top/Article/details/gthqabojzx.html

Ruby: obj.instance_variables
来源：http://dali.jinqigfzy.top/Article/details/gtengoqlnp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xziqi.cn/Article/details/gtikmgzbsb.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtagkfktqg.html

H. 异常与错误处理
来源：http://dali.chenlongwang.top/Article/details/gtleebmiqm.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtevoglkkh.html

[H01] try / catch 基础
来源：http://dali.daria6918.cn/Article/details/gtluqtrctk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dashuyun.cn/Article/details/gtrlbooplx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daria6918.cn/Article/details/gtdjvtdasx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jiagoushi.top/Article/details/gtgccovsqf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gtmcizacyb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shzxlz.cn/Article/details/gtzungxkux.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shuidangran.top/Article/details/gtqdfoxmcn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sufxvd.cn/Article/details/gtamiobixx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ybcxt.top/Article/details/gtugevyhgf.html

[H02] finally / ensure 收尾
来源：http://dali.redwolf501.top/Article/details/gtsjhbpnkq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hfpthk.cn/Article/details/gtgkvuztbr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtdwtzrnaq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtevndezmy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtvoqxkule.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtflwpggjx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.birdmap.top/Article/details/gtrunltysx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sxryk.cn/Article/details/gtrhdjsjfk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtojuttbjq.html

[H03] 主动抛出异常
来源：http://dali.hammf.cn/Article/details/gtsjrzokru.html

Py:   raise ValueError("错误信息")
来源：http://dali.hammf.cn/Article/details/gtvmspwbct.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtzlktsjpm.html

JS:   throw new Error("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtxcrdojuj.html

TS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgtqoykve.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtdvhpukax.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gaohongyu789.top/Article/details/gtucowusvx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nanxuanxn.top/Article/details/gtlcsmvtzc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtbswdpwvy.html

[H04] 自定义异常类型
来源：http://dali.nwbrower.top/Article/details/gtrzmlbtsa.html

Py:   class MyError(Exception): pass
来源：http://dali.hammf.cn/Article/details/gtarpbsmfu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gtkhpjkrwl.html

JS:   class MyError extends Error {}
来源：http://dali.ehwqpu.com/Article/details/gtrnsygpfh.html

TS:   class MyError extends Error {}
来源：http://dali.jianghu66.top/Article/details/gtepqokudu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yuxming.cn/Article/details/gtglysbabi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cashguo.top/Article/details/gtonfztakq.html

Ruby: class MyError < StandardError; end
来源：http://dali.cdnleiting.top/Article/details/gttngcwjbu.html

C#:   class MyException : Exception {}
来源：http://dali.redwolf501.top/Article/details/gtgcbumzol.html

[H05] 捕获特定类型
来源：http://dali.jinqigfzy.top/Article/details/gtulngxagc.html

Py:   except ValueError as e:
来源：http://dali.sweek.top/Article/details/gtozxkcwlh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.quarkkingdee.top/Article/details/gtnkkhnzny.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtfcyrhkgz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yangfankeji.com/Article/details/gtamidceng.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj202588.top/Article/details/gtisgvhjid.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xylfe.cn/Article/details/gtyotbkrec.html

Ruby: rescue ArgumentError => e
来源：http://dali.quarkkingdee.top/Article/details/gtxsyrgdne.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yanxiufei.cn/Article/details/gtxfjzqlwc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhixingplan.top/Article/details/gtdgcapvlv.html

Py:   value = d.get("k") or default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtytzgnhtz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gaohongyu789.top/Article/details/gtzncrgmzf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cucudq.cn/Article/details/gteycqjmvi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.redwolf501.top/Article/details/gthdnkpwut.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.bjfxy.top/Article/details/gttccjrdej.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.birdmap.top/Article/details/gtgbsgwkfd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hywenlv.cn/Article/details/gtxelzfsrb.html

C#:   obj?.A?.B ?? default
来源：http://dali.yuxming.cn/Article/details/gtbvolgfos.html

[H07] 断言
来源：http://dali.shzxlz.cn/Article/details/gtvmpchbsl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.vqdsnc.cn/Article/details/gtswouiziz.html

PHP:  assert($x > 0);
来源：http://dali.xziqi.cn/Article/details/gtyegmoasx.html

JS:   console.assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtppqxaukn.html

TS:   console.assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtxgmdamcx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.dashuyun.cn/Article/details/gtmlszleky.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.daria6918.cn/Article/details/gtyflocrmf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.kuanghao11.cn/Article/details/gtipxdpooj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gtbdthazad.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj202588.top/Article/details/gtbaheysgg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj202588.top/Article/details/gtuzzfispe.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jiagoushi.top/Article/details/gtfwuhosih.html

JS:   e.message;  e.stack
来源：http://dali.zycfv.cn/Article/details/gtkoejrblb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.guannengcc.top/Article/details/gtnkznmrka.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hfpthk.cn/Article/details/gthbguynsp.html

Go:   err.Error()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmydrcrts.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigfzy.top/Article/details/gtpbhwyetd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinghuilouyu.cn/Article/details/gtssvmists.html

[H09] 带错误码的异常
来源：http://dali.sweek.top/Article/details/gtgstaknqe.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pycfn.com/Article/details/gtekbueifs.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.smart0.xyz/Article/details/gtvolsbwyr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbpgutslf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.dianchejie.cn/Article/details/gtkxzkihzk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hnxiangtu.top/Article/details/gtarnshycd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.wangshuangyany.cn/Article/details/gtytnthzxc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nwbrower.top/Article/details/gtnjaxaauf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtavoecysw.html

[H10] 资源自动释放
来源：http://dali.hywenlv.cn/Article/details/gtkwxspoph.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhongyouzk.top/Article/details/gtzdlpxbuo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.redwolf501.top/Article/details/gtanrhcdle.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhixingplan.top/Article/details/gtiasimlaf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhixingplan.top/Article/details/gtatxtcypu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sysykeji.top/Article/details/gtybyooryw.html

Go:   defer f.Close()
来源：http://dali.jqgufenzy.top/Article/details/gtmbmrwxyr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sweek.top/Article/details/gtylkdugoi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtujymxyxv.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtngpjpwta.html

I. 正则表达式
来源：http://dali.jqgufenzy.top/Article/details/gtcsagofgv.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtasojvdgj.html

[I01] 判断是否匹配
来源：http://dali.nwbrower.top/Article/details/gtgapxrajc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yanxiufei.cn/Article/details/gtvacfkduf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuxming.cn/Article/details/gtjxzpupso.html

JS:   /\d+/.test(s)
来源：http://dali.jqgufenzy.top/Article/details/gtlutrgotj.html

TS:   /\d+/.test(s)
来源：http://dali.jinqigufen.top/Article/details/gtniiycoky.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.9152youxi.cn/Article/details/gtjirqesod.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.haohaochexian.top/Article/details/gtcddpjxnp.html

Ruby: s.match?(/\d+/)
来源：http://dali.yanxiufei.cn/Article/details/gtocgpfykf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.aizwys.cn/Article/details/gtyfvydunt.html

[I02] 提取所有匹配
来源：http://dali.jqgufenzy.top/Article/details/gtsrjudocm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jlsjyb.cn/Article/details/gtwavswjbs.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.quarkkingdee.top/Article/details/gtvxffuzrw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinqigfzy.top/Article/details/gtwnlnknim.html

TS:   s.match(/\d+/g)
来源：http://dali.c1oappe.top/Article/details/gtpmcrwhjg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.pycfn.com/Article/details/gtefoyohhk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj20258888.top/Article/details/gtnhznevnh.html

Ruby: s.scan(/\d+/)
来源：http://dali.hnxiangtu.top/Article/details/gtbaiemvib.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtcmpxterv.html

[I03] 提取捕获分组
来源：http://dali.chenjidiqi.icu/Article/details/gtjooguebi.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ybcxt.top/Article/details/gtyyvzxmry.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sysykeji.top/Article/details/gtiaiereog.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtinmphtsw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.0kj1m.cn/Article/details/gtcueebswd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ydzc1.top/Article/details/gthdedwebl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.pengpengdd.cyou/Article/details/gtvekjtzmk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.quarkkingdee.top/Article/details/gttzaocbco.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jianghu66.top/Article/details/gtqrfxiwwk.html

[I04] 正则替换
来源：http://dali.hfpthk.cn/Article/details/gtftemddrm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhixingplan.top/Article/details/gtznagluti.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cqqwz.cn/Article/details/gtulqbkzbm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ppjwa.cn/Article/details/gtmhfsrdvo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigufen.top/Article/details/gtgfwejcqh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hammf.cn/Article/details/gtpclkxihg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhixingplan.top/Article/details/gtpgqfobdl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ppjwa.cn/Article/details/gthvrppana.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hywenlv.cn/Article/details/gtepscuyky.html

[I05] 按正则拆分
来源：http://dali.zhengqikj.top/Article/details/gtcromvphs.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.fengsongda.top/Article/details/gttmhoocta.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.daria6918.cn/Article/details/gthwbutthh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gtkdcnpjqc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gtggxiwoma.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gogol.net.cn/Article/details/gtmmtdyptw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jianghu66.top/Article/details/gtuipqspta.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gtcjthsnhp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.andypj.xyz/Article/details/gtdrofjply.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yvedp.cn/Article/details/gtrkemqyuf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gtdkcrqllx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nanxuanxn.top/Article/details/gtwdrxntxa.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tanke756.top/Article/details/gtoyruiwzk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgufenzy.top/Article/details/gtwsdbuujj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gtgvcyepyg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.haohaochexian.top/Article/details/gtuzrngslb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhoulong.xyz/Article/details/gtqcrunzyn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtraxcdvdk.html

[I07] 忽略大小写与多行模式
来源：http://dali.snrcjt.cn/Article/details/gtyaacaguz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj202588.top/Article/details/gtmeyaexwp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sxryk.cn/Article/details/gteaqchvzp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258888.top/Article/details/gtfeyapngd.html

TS:   /error/gim
来源：http://dali.zhengqikj.top/Article/details/gtvgvflqsz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gogol.net.cn/Article/details/gtttacdqko.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yuxming.cn/Article/details/gtrdptqnqe.html

Ruby: s.scan(/error/i)
来源：http://dali.hywenlv.cn/Article/details/gtumubtqhg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cashguo.top/Article/details/gtquxifeog.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gtxxbdaomr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ppjwa.cn/Article/details/gtlyrgdckf.html


<!-- 参考信息 -->