代发 wailian999

[G02] 构造函数
来源：http://dali.yj202588.top/Article/details/gtlbahoizj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xuanzx.com/Article/details/gttsnscfth.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.wangdashe.top/Article/details/gtmxqgsxhk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gtsdopzgyb.html

TS:   constructor(public name: string) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtugqqgzmv.html

Java: User(String name) { this.name = name; }
来源：http://dali.sysykeji.top/Article/details/gtsnhujzgi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.316326.xyz/Article/details/gtykjjnwau.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.kuanghao11.cn/Article/details/gtdmgvkpxk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtalrfdira.html

[G03] 实例属性
来源：http://dali.zycfv.cn/Article/details/gtffaxmuuj.html

Py:   self.name = "x"
来源：http://dali.guowangkeji.top/Article/details/gtuafdsnjo.html

PHP:  public string $name = "x";
来源：http://dali.ivvv.top/Article/details/gtrfghxynx.html

JS:   this.name = "x";
来源：http://dali.dianchejie.cn/Article/details/gtcukfjcui.html

TS:   name: string = "x";
来源：http://dali.yj20258888.top/Article/details/gtwximnmyc.html

Java: private String name;
来源：http://dali.pycfn.com/Article/details/gtndpizukd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cheryme.top/Article/details/gtxheppuqy.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gtoypdopkp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtqosgxfeb.html

[G04] 定义方法
来源：http://dali.sxryk.cn/Article/details/gtegtrutqd.html

Py:   def greet(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gthkrxqsoe.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gtolewstja.html

JS:   greet() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtpzphwqpw.html

TS:   greet(): string { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtronzmdxq.html

Java: String greet() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtkmqoemhp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gtrkggjzpz.html

Ruby: def greet; @name; end
来源：http://dali.feifeiyinyue.top/Article/details/gtbdmvigai.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gteztvikth.html

[G05] 继承
来源：http://dali.chenjidiqi.icu/Article/details/gtvjmztlkx.html

Py:   class Admin(User): pass
来源：http://dali.nanxinkj.top/Article/details/gtufotjttf.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtrzxgtcvd.html

JS:   class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtshdknvcq.html

TS:   class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtklqlamoc.html

Java: class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtqnmmaksu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sufxvd.cn/Article/details/gtbzskymdm.html

Ruby: class Admin < User; end
来源：http://dali.pengpengdd.cyou/Article/details/gtnlkysore.html

C#:   class Admin : User {}
来源：http://dali.xziqi.cn/Article/details/gtcoccmrvf.html

[G06] 重写方法
来源：http://dali.jqgufenzy.top/Article/details/gttvmdzeiw.html

Py:   def greet(self): return "admin"
来源：http://dali.zhiwuduotai.top/Article/details/gtqkzamkpv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtdbihftcx.html

JS:   greet() { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gtbcpozkcx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gttbaeqbfm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtqnejbhdr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yanxiufei.cn/Article/details/gtpeovamfu.html

Ruby: def greet; "admin"; end
来源：http://dali.cashguo.top/Article/details/gtprzvsfeb.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhengqikj.top/Article/details/gtdruanfpr.html

[G07] 调用父类方法
来源：http://dali.bjfxy.top/Article/details/gtkoefqvhv.html

Py:   super().greet()
来源：http://dali.yj202588.top/Article/details/gtgttrvcxi.html

PHP:  parent::greet();
来源：http://dali.dianchejie.cn/Article/details/gtlywcehef.html

JS:   super.greet();
来源：http://dali.andypj.xyz/Article/details/gtniesugmq.html

TS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gtzkfebpax.html

Java: super.greet();
来源：http://dali.xylfe.cn/Article/details/gtfuazduua.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.9152youxi.cn/Article/details/gtebtabikw.html

Ruby: super
来源：http://dali.redwolf501.top/Article/details/gtzqucwaeq.html

C#:   base.Greet();
来源：http://dali.hywenlv.cn/Article/details/gtmnazjxka.html

[G08] 静态方法与属性
来源：http://dali.zhiwuduotai.top/Article/details/gtulezfqvz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnxiangtu.top/Article/details/gtimtaxtip.html

PHP:  public static function f() {}
来源：http://dali.c1oappe.top/Article/details/gtaxrulkzm.html

JS:   static f() {}
来源：http://dali.pycfn.com/Article/details/gtjqjgpxae.html

TS:   static f(): void {}
来源：http://dali.wangdashe.top/Article/details/gtdpeswcyt.html

Java: static void f() {}
来源：http://dali.shzxlz.cn/Article/details/gtcwzeitbk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shangyingyoupin.top/Article/details/gtptihyicd.html

Ruby: def self.f; end
来源：http://dali.andypj.xyz/Article/details/gtjusribqr.html

C#:   public static void F() {}
来源：http://dali.xziqi.cn/Article/details/gtmmisjzlq.html

[G09] 接口 / 抽象类
来源：http://dali.tanke756.top/Article/details/gtkjviohvt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shangyingyoupin.top/Article/details/gtzsotfpxk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cdnleiting.top/Article/details/gtlgrfclrx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj202588.top/Article/details/gttdcmpquk.html

TS:   interface Shape { area(): number; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoqtwvplc.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtttcnciwc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daria6918.cn/Article/details/gtlkoxjuwb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jlsjyb.cn/Article/details/gtptgxughp.html

C#:   interface IShape { double Area(); }
来源：http://dali.jyoumei.cn/Article/details/gtkxkxionl.html

[G10] 访问控制
来源：http://dali.birdmap.top/Article/details/gtsycbyrua.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gtygtiybne.html

PHP:  public / protected / private
来源：http://dali.yongpay.top/Article/details/gtntjytxnk.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigufen.top/Article/details/gtuzhwbzky.html

TS:   public / protected / private
来源：http://dali.smart0.xyz/Article/details/gtnjgzxtzl.html

Java: public / protected / private / 默认包级
来源：http://dali.ivvv.top/Article/details/gtxmbchsdi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.316326.xyz/Article/details/gtwexeinpk.html

Ruby: public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gtalptjwtb.html

C#:   public / protected / private / internal
来源：http://dali.sufxvd.cn/Article/details/gtsfxkewvb.html

[G11] getter / setter
来源：http://dali.zhiwuduotai.top/Article/details/gtiejttfcr.html

Py:   @property 与 @x.setter
来源：http://dali.shzxlz.cn/Article/details/gtevvqiqff.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtwucmbkqo.html

JS:   get name() { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gtyswxgafg.html

TS:   get name(): string { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gthjctfsgl.html

Java: public String getName() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtfsezkzrd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gtdxecyilj.html

Ruby: attr_accessor :name
来源：http://dali.cheryme.top/Article/details/gtokgwngzn.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtapoolcck.html

[G12] 对象转字符串
来源：http://dali.ppjwa.cn/Article/details/gtxpmorigy.html

Py:   def __str__(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gtiopxcivo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtthdrrxnf.html

JS:   toString() { return this.name; }
来源：http://dali.316326.xyz/Article/details/gttcjihbxr.html

TS:   toString(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtotqbanqk.html

Java: @Override public String toString() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtnfqnzlma.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gtjntcubts.html

Ruby: def to_s; @name; end
来源：http://dali.sweek.top/Article/details/gtnwibxoyq.html

C#:   public override string ToString() => Name;
来源：http://dali.gzhubu.top/Article/details/gtvrcapyxc.html

[G13] 判断对象类型
来源：http://dali.chenlongwang.top/Article/details/gtxfkowrzg.html

Py:   isinstance(u, User)
来源：http://dali.zhengqikj.top/Article/details/gttovugeuv.html

PHP:  $u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtmzazkuzi.html

JS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gtugugsshr.html

TS:   u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtugisydux.html

Java: u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtruyjzcxr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.chenlongwang.top/Article/details/gtmesaseyz.html

Ruby: u.is_a?(User)
来源：http://dali.nanxinkj.top/Article/details/gtojgjsvpc.html

C#:   u is User
来源：http://dali.gotoacloud.top/Article/details/gtbvixeano.html

[G14] 数据类 / record
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuofqcoke.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.iojbl.cn/Article/details/gtnleofxxz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jyoumei.cn/Article/details/gthqaigmpe.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.andypj.xyz/Article/details/gtilyctusr.html

TS:   type User = { name: string; age: number };
来源：http://dali.gaohongyu789.top/Article/details/gtbdrtpeug.html

Java: record User(String name, int age) {}
来源：http://dali.mhx1999.top/Article/details/gtfauhzzdq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj20258888.top/Article/details/gtpstxhimk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.9152youxi.cn/Article/details/gturegxfjm.html

C#:   record User(string Name, int Age);
来源：http://dali.mhx1999.top/Article/details/gtbwvlegaa.html

[G15] 枚举
来源：http://dali.jyoumei.cn/Article/details/gtkqixrgiq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnxiangtu.top/Article/details/gthpzgbdsu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yonumen.top/Article/details/gtyjqdqczi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.pycfn.com/Article/details/gthvreqxun.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cdnleiting.top/Article/details/gttylxzyic.html

Java: enum Color { RED, GREEN }
来源：http://dali.pengpengdd.cyou/Article/details/gtrmevoqgc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guowangkeji.top/Article/details/gtbsbtuxsx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.vqdsnc.cn/Article/details/gtyrtrltsz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gtecxxnxyy.html

[G16] 对象转数组 / 字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhandliz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhixingplan.top/Article/details/gtktbytymm.html

PHP:  get_object_vars($obj);
来源：http://dali.zhoulong.xyz/Article/details/gtrpjiigjp.html

JS:   Object.entries(obj)
来源：http://dali.birdmap.top/Article/details/gtannsxxnu.html

TS:   Object.entries(obj)
来源：http://dali.redwolf501.top/Article/details/gtdtmzlwbi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dashuyun.cn/Article/details/gtblhwmged.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nwbrower.top/Article/details/gtylsfxjwk.html

Ruby: obj.instance_variables
来源：http://dali.hywenlv.cn/Article/details/gtwjpetzwk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gturkbfnvr.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtjjszuecy.html

H. 异常与错误处理
来源：http://dali.gzhubu.top/Article/details/gtatnzngad.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtwoexujnb.html

[H01] try / catch 基础
来源：http://dali.jinqigfzy.top/Article/details/gtkgcddvko.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj202588.top/Article/details/gtqcyhqndz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahwqfvwu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.birdmap.top/Article/details/gtxfdrllot.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gtuhhqxzjj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.bjfxy.top/Article/details/gtzwlnyffa.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.svipenyu.cn/Article/details/gtvccpubru.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ivvv.top/Article/details/gtmsfcvnhl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.mhx1999.top/Article/details/gtsghcnjxp.html

[H02] finally / ensure 收尾
来源：http://dali.gotoacloud.top/Article/details/gtmhgzoair.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.daxiang520.top/Article/details/gtqcgoxbca.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtgsrybgwb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtsdpkigiz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtahxcojqc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gteqkdvlcb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.dashuyun.cn/Article/details/gtnnjnbajk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cheryme.top/Article/details/gttnnxheai.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtbgrwupoj.html

[H03] 主动抛出异常
来源：http://dali.ehwqpu.com/Article/details/gtorajyqit.html

Py:   raise ValueError("错误信息")
来源：http://dali.ydzc1.top/Article/details/gtctcjvwrf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtfkrzuxkp.html

JS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gtfndipyhf.html

TS:   throw new Error("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcoxsicx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtvgkleuam.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.fzhhl.top/Article/details/gtmgosgnth.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sysykeji.top/Article/details/gttpvrdmgm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gtabcpzpst.html

[H04] 自定义异常类型
来源：http://dali.gotoacloud.top/Article/details/gtybtruwxq.html

Py:   class MyError(Exception): pass
来源：http://dali.shangyingyoupin.top/Article/details/gtrkpjvlgq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ppjwa.cn/Article/details/gtkfjffnkx.html

JS:   class MyError extends Error {}
来源：http://dali.zhixingplan.top/Article/details/gtxcuhcjhe.html

TS:   class MyError extends Error {}
来源：http://dali.guannengcc.top/Article/details/gtokmwfahf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gtkjxntnpg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.kuanghao11.cn/Article/details/gtcfvnkszl.html

Ruby: class MyError < StandardError; end
来源：http://dali.xinyue.icu/Article/details/gtymhbfixu.html

C#:   class MyException : Exception {}
来源：http://dali.jiagoushi.top/Article/details/gtaqctlsae.html

[H05] 捕获特定类型
来源：http://dali.daxiang520.top/Article/details/gtdkstxpse.html

Py:   except ValueError as e:
来源：http://dali.jlsjyb.cn/Article/details/gtxuabpcfo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hnqzz.top/Article/details/gtfmfnbcgb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwiwbagb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zdqjudy.top/Article/details/gtaowvkdoz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shzxlz.cn/Article/details/gtuwgpzwcj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ivvv.top/Article/details/gtnbsppoot.html

Ruby: rescue ArgumentError => e
来源：http://dali.cheryme.top/Article/details/gtvwlxnlqb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.daxiang520.top/Article/details/gthaervucq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shangyingyoupin.top/Article/details/gtogvzetgw.html

Py:   value = d.get("k") or default
来源：http://dali.sysykeji.top/Article/details/gtwogwdaze.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj20258.top/Article/details/gtwmtyofxx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hysaishi.cn/Article/details/gtmamjrvmt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gtpmgwhchk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.316326.xyz/Article/details/gtmjvmaeqp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.pycfn.com/Article/details/gtlxmsigxp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cashguo.top/Article/details/gtaawtdknh.html

C#:   obj?.A?.B ?? default
来源：http://dali.hfpthk.cn/Article/details/gtcjiyauzj.html

[H07] 断言
来源：http://dali.cucudq.cn/Article/details/gtrktxpzwa.html

Py:   assert x > 0, "必须为正"
来源：http://dali.dashuyun.cn/Article/details/gtsgugdzib.html

PHP:  assert($x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtmywkaeqs.html

JS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gtciqkzqer.html

TS:   console.assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtatounsfr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnqzz.top/Article/details/gtdvalffmj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shangyingyoupin.top/Article/details/gtpntqwgud.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.feifeiyinyue.top/Article/details/gtdkcnxhbl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gtorhlhfeu.html

[H08] 获取错误信息与堆栈
来源：http://dali.jyoumei.cn/Article/details/gtxtjdlzhz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hysaishi.cn/Article/details/gtnzaycbpo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinghuilouyu.cn/Article/details/gtwuyfcnvu.html

JS:   e.message;  e.stack
来源：http://dali.pengpengdd.cyou/Article/details/gtzltdibtz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258888.top/Article/details/gtcazgpajv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnqzz.top/Article/details/gtwdokmhop.html

Go:   err.Error()
来源：http://dali.ppjwa.cn/Article/details/gtwreaoayg.html

Ruby: e.message;  e.backtrace
来源：http://dali.c1oappe.top/Article/details/gtvspgvmkc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.birdmap.top/Article/details/gtejxbpzed.html

[H09] 带错误码的异常
来源：http://dali.haohaochexian.top/Article/details/gttxsubedy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.snrcjt.cn/Article/details/gtluukwcjt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ppjwa.cn/Article/details/gtvzyrysbb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gogol.net.cn/Article/details/gtwiidrnaw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhongyouzk.top/Article/details/gtoysiqdza.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yongpay.top/Article/details/gtdahzzqfn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gotoacloud.top/Article/details/gtsernxplb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yueranfly.top/Article/details/gtteobtnqx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.guowangkeji.top/Article/details/gtemxveaeo.html

[H10] 资源自动释放
来源：http://dali.9152youxi.cn/Article/details/gtmyjxvfvx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhongyouzk.top/Article/details/gtlxorpwqw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sxryk.cn/Article/details/gtlvbzdtdz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.meibo888.top/Article/details/gtduhzqmax.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.feifeiyinyue.top/Article/details/gtgcpnxcqi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hammf.cn/Article/details/gtuhvcxeuq.html

Go:   defer f.Close()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnqqgubcg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cqqwz.cn/Article/details/gtavorupcn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcafpnpfo.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtdmrstyuk.html

I. 正则表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpgrdtzbk.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtbvdjovak.html

[I01] 判断是否匹配
来源：http://dali.c1oappe.top/Article/details/gtkqzwnrje.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hysaishi.cn/Article/details/gteodcltwl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtqyptyebr.html

JS:   /\d+/.test(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtltnvmqaj.html

TS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gtqjjlltvh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hywenlv.cn/Article/details/gtssdheglp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xziqi.cn/Article/details/gtkwgcovxl.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhongyouzk.top/Article/details/gtkicqtrrm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hongshengwenyu.top/Article/details/gtdbirnyhl.html

[I02] 提取所有匹配
来源：http://dali.yonumen.top/Article/details/gtjliykhzz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgbxplslk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gotoacloud.top/Article/details/gtseqhwdhq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangshuangyany.cn/Article/details/gtgjisafyq.html

TS:   s.match(/\d+/g)
来源：http://dali.tian-w.cn/Article/details/gtoqcewrsn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yvedp.cn/Article/details/gtlqqfcebu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.fzhhl.top/Article/details/gtsicphumn.html

Ruby: s.scan(/\d+/)
来源：http://dali.yuxming.cn/Article/details/gtwysngssx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuanzx.com/Article/details/gtyxnbloiy.html

[I03] 提取捕获分组
来源：http://dali.dashuyun.cn/Article/details/gtfadmoxoj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tanke756.top/Article/details/gtkdptzwvm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhongyouzk.top/Article/details/gtxmsdufnh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jlsjyb.cn/Article/details/gtnuhmgvli.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nanxinkj.top/Article/details/gtfejzenui.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ehwqpu.com/Article/details/gtrbnkcfqn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sysykeji.top/Article/details/gtvwrzeivx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.c1oappe.top/Article/details/gthbeqihce.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhoulong.xyz/Article/details/gtmlexexpw.html

[I04] 正则替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvtrtxyt.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nanxuanxn.top/Article/details/gtwdgcimdh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xylfe.cn/Article/details/gtoqnhgqmu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cheryme.top/Article/details/gtgdrouriq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zdqjudy.top/Article/details/gthlvblkuk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gtenasbqti.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkvotjzm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtuzcozlqa.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gtpmrdnwap.html

[I05] 按正则拆分
来源：http://dali.jinqigufen.top/Article/details/gtfykigfev.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtxllyxeai.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtocioszfx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gtmgqevnhn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthwinezgb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.andypj.xyz/Article/details/gtefommcdu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yueranfly.top/Article/details/gttmzuvchb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gthsjbwvrh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sysykeji.top/Article/details/gtotimvmyr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.kuanghao11.cn/Article/details/gtwpejajsw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gtbqasimnb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nwbrower.top/Article/details/gtvlxbyxny.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cucudq.cn/Article/details/gtsszuduul.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gtuorrvnqy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gtxrqilunn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.andypj.xyz/Article/details/gtedgauqwy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.havefunace.top/Article/details/gtcwzrhnpu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gtluuzqnkv.html

[I07] 忽略大小写与多行模式
来源：http://dali.tian-w.cn/Article/details/gtnhvfnlib.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteraruyvl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ppjwa.cn/Article/details/gtgmulgxpj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xuanzx.com/Article/details/gtnujcuedg.html

TS:   /error/gim
来源：http://dali.yvedp.cn/Article/details/gtveggxvkt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.fengsongda.top/Article/details/gtgliglmzj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dianchejie.cn/Article/details/gtpjgxswqo.html

Ruby: s.scan(/error/i)
来源：http://dali.gzhubu.top/Article/details/gtzfvyfxrh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinghuilouyu.cn/Article/details/gtombgkjrh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sufxvd.cn/Article/details/gtcnyxqkei.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj20258.top/Article/details/gtctwybcyo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.bjfxy.top/Article/details/gtywyvtpbi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guowangkeji.top/Article/details/gtyzdlprks.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gogol.net.cn/Article/details/gtuwjqyicq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.feifeiyinyue.top/Article/details/gtwgvtzwdg.html


<!-- 参考信息 -->