代发 wailian999

Java: class User {}
来源：http://dali.xziqi.cn/Article/details/gtacfgkrbk.html

Go:   type User struct { Name string }
来源：http://dali.sysykeji.top/Article/details/gtcqrhknev.html

Ruby: class User; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjeqmamg.html

C#:   class User {}
来源：http://dali.sweek.top/Article/details/gtrlcnydlv.html

[G02] 构造函数
来源：http://dali.nanxinkj.top/Article/details/gtgxastnqw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cucudq.cn/Article/details/gttsnauval.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtinrpbkwj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtwbnzbavy.html

TS:   constructor(public name: string) {}
来源：http://dali.ivvv.top/Article/details/gtnirtymun.html

Java: User(String name) { this.name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtjeiuists.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.fengsongda.top/Article/details/gtvehoefjo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xuanzx.com/Article/details/gtrwrdhmsa.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ivvv.top/Article/details/gtkslxdxyk.html

[G03] 实例属性
来源：http://dali.zdqjudy.top/Article/details/gtweytevmo.html

Py:   self.name = "x"
来源：http://dali.hywenlv.cn/Article/details/gtfrdnmhsw.html

PHP:  public string $name = "x";
来源：http://dali.hammf.cn/Article/details/gtvibudkxq.html

JS:   this.name = "x";
来源：http://dali.kuanghao11.cn/Article/details/gthkbcsdck.html

TS:   name: string = "x";
来源：http://dali.yj20258.top/Article/details/gtlfsimgrf.html

Java: private String name;
来源：http://dali.bjfxy.top/Article/details/gtzzjzwmnd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sweek.top/Article/details/gtmvtavukp.html

Ruby: @name = "x"
来源：http://dali.jqgfzy.top/Article/details/gtkxxchiaz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtnlsmarfb.html

[G04] 定义方法
来源：http://dali.yueranfly.top/Article/details/gtklnjjakv.html

Py:   def greet(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gthmpbajkl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gtqfsozlju.html

JS:   greet() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtyvqxxuuv.html

TS:   greet(): string { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtzvynzcbl.html

Java: String greet() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtpthhusux.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtehqjbpdr.html

Ruby: def greet; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gtmxnmljga.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmqdytbs.html

[G05] 继承
来源：http://dali.snrcjt.cn/Article/details/gtxzpshuvx.html

Py:   class Admin(User): pass
来源：http://dali.hfpthk.cn/Article/details/gtvqdaktmn.html

PHP:  class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtwvsvtxbi.html

JS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtcwagltjv.html

TS:   class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtzcbxqmuk.html

Java: class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtbhzvapsf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.aizwys.cn/Article/details/gtittqandq.html

Ruby: class Admin < User; end
来源：http://dali.meibo888.top/Article/details/gtyysucmqp.html

C#:   class Admin : User {}
来源：http://dali.hywenlv.cn/Article/details/gthttoglag.html

[G06] 重写方法
来源：http://dali.jiagoushi.top/Article/details/gtehbnkifs.html

Py:   def greet(self): return "admin"
来源：http://dali.chenzaomai.com/Article/details/gtopbhajwd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtdgtdgfqa.html

JS:   greet() { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtfryczuda.html

TS:   greet(): string { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtzfmdcbim.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gteaxuijck.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ppjwa.cn/Article/details/gtbihaxtlj.html

Ruby: def greet; "admin"; end
来源：http://dali.nanxinkj.top/Article/details/gtqvquujjp.html

C#:   public override string Greet() => "admin";
来源：http://dali.redwolf501.top/Article/details/gtwbbdiqkb.html

[G07] 调用父类方法
来源：http://dali.gotoacloud.top/Article/details/gtzhblhkop.html

Py:   super().greet()
来源：http://dali.xinyue.icu/Article/details/gtxldqxfhx.html

PHP:  parent::greet();
来源：http://dali.mhx1999.top/Article/details/gtnpgghfxm.html

JS:   super.greet();
来源：http://dali.ppjwa.cn/Article/details/gtmrkapaky.html

TS:   super.greet();
来源：http://dali.jqgfzy.top/Article/details/gtclgiuicm.html

Java: super.greet();
来源：http://dali.havefunace.top/Article/details/gttnckkdaw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.feifeiyinyue.top/Article/details/gtwztrpotb.html

Ruby: super
来源：http://dali.hnxiangtu.top/Article/details/gtswadqzft.html

C#:   base.Greet();
来源：http://dali.svipenyu.cn/Article/details/gtmxvdxnmo.html

[G08] 静态方法与属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtojnrpkir.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jyoumei.cn/Article/details/gtwttdkvtc.html

PHP:  public static function f() {}
来源：http://dali.cdnleiting.top/Article/details/gtctwahhmu.html

JS:   static f() {}
来源：http://dali.yuxming.cn/Article/details/gtoirpgvee.html

TS:   static f(): void {}
来源：http://dali.smart0.xyz/Article/details/gtcqiyqysw.html

Java: static void f() {}
来源：http://dali.pycfn.com/Article/details/gtaqrdopum.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuanzx.com/Article/details/gtvihhesqj.html

Ruby: def self.f; end
来源：http://dali.chenlongwang.top/Article/details/gtofnscbls.html

C#:   public static void F() {}
来源：http://dali.bjfxy.top/Article/details/gtibrkynwm.html

[G09] 接口 / 抽象类
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkufomuft.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gogol.net.cn/Article/details/gtduccrvaj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.bjfxy.top/Article/details/gteqsljgku.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.vqdsnc.cn/Article/details/gtlknmvmqe.html

TS:   interface Shape { area(): number; }
来源：http://dali.pycfn.com/Article/details/gtbkthfbis.html

Java: interface Shape { double area(); }
来源：http://dali.ivvv.top/Article/details/gtlituuuvr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cdnleiting.top/Article/details/gtajnanqyk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yanxiufei.cn/Article/details/gtngzzxzmy.html

C#:   interface IShape { double Area(); }
来源：http://dali.dianchejie.cn/Article/details/gtxnxkwxug.html

[G10] 访问控制
来源：http://dali.meibo888.top/Article/details/gtgslkylzd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenzaomai.com/Article/details/gtpnkbfjli.html

PHP:  public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gtuxqmbmim.html

JS:   #private 字段；其余公开
来源：http://dali.vqdsnc.cn/Article/details/gtcppqiedy.html

TS:   public / protected / private
来源：http://dali.andypj.xyz/Article/details/gtxwbuvpvh.html

Java: public / protected / private / 默认包级
来源：http://dali.daria6918.cn/Article/details/gtrrqucbic.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tian-w.cn/Article/details/gtsncrjygq.html

Ruby: public / protected / private
来源：http://dali.cucudq.cn/Article/details/gtgpceoqca.html

C#:   public / protected / private / internal
来源：http://dali.jqgufenzy.top/Article/details/gtdvpqbzcg.html

[G11] getter / setter
来源：http://dali.cqqwz.cn/Article/details/gthlnmaevl.html

Py:   @property 与 @x.setter
来源：http://dali.yanxiufei.cn/Article/details/gtjxfxvxdn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpntwhrsh.html

JS:   get name() { return this._name; }
来源：http://dali.havefunace.top/Article/details/gtxkfgsiyt.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gtvqkndxjj.html

Java: public String getName() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtupxescfj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gtxrwwazda.html

Ruby: attr_accessor :name
来源：http://dali.wangshuangyany.cn/Article/details/gtushqcwap.html

C#:   public string Name { get; set; }
来源：http://dali.jianghu66.top/Article/details/gtewvumkdg.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbejqshqj.html

Py:   def __str__(self): return self.name
来源：http://dali.shanyushiyangtech.top/Article/details/gtlgehkxuk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gtqmjnkgqd.html

JS:   toString() { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtoytjqtdn.html

TS:   toString(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtpmwqtsfy.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtucsjfrie.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gtjodgzyrx.html

Ruby: def to_s; @name; end
来源：http://dali.ppjwa.cn/Article/details/gtevdzwhgo.html

C#:   public override string ToString() => Name;
来源：http://dali.cqqwz.cn/Article/details/gtrepwwiaz.html

[G13] 判断对象类型
来源：http://dali.hywenlv.cn/Article/details/gtsvxecher.html

Py:   isinstance(u, User)
来源：http://dali.gogol.net.cn/Article/details/gtqmhgstje.html

PHP:  $u instanceof User
来源：http://dali.cheryme.top/Article/details/gtlxcmosdd.html

JS:   u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtgqvbbjfd.html

TS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gtcmyfbcqr.html

Java: u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtdkrobnbj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sysykeji.top/Article/details/gtsopvybls.html

Ruby: u.is_a?(User)
来源：http://dali.meibo888.top/Article/details/gtpzpeiasc.html

C#:   u is User
来源：http://dali.jqgfzy.top/Article/details/gtpwdzcxla.html

[G14] 数据类 / record
来源：http://dali.sxryk.cn/Article/details/gtptupzqhe.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hysaishi.cn/Article/details/gtkpthgare.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigufen.top/Article/details/gtsvsqlqfn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yangfankeji.com/Article/details/gtqzdixezk.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj20258.top/Article/details/gtuqexjvvy.html

Java: record User(String name, int age) {}
来源：http://dali.xziqi.cn/Article/details/gtekbsmfrr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nanxuanxn.top/Article/details/gtwoanpvnk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhoulong.xyz/Article/details/gthziwwzqp.html

C#:   record User(string Name, int Age);
来源：http://dali.jianghu66.top/Article/details/gtxvhcbgvj.html

[G15] 枚举
来源：http://dali.meibo888.top/Article/details/gtkqlucanm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhoulong.xyz/Article/details/gtftwozkmt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zycfv.cn/Article/details/gtuqwoaspn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.bjfxy.top/Article/details/gtmbghtlnj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gtafzsyrgu.html

Java: enum Color { RED, GREEN }
来源：http://dali.yangfankeji.com/Article/details/gtnycakmal.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gogol.net.cn/Article/details/gtgttixila.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cucudq.cn/Article/details/gtvzulwxnw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthoeycsmo.html

[G16] 对象转数组 / 字典
来源：http://dali.hywenlv.cn/Article/details/gtwkguvswk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhoulong.xyz/Article/details/gtrmrccaqm.html

PHP:  get_object_vars($obj);
来源：http://dali.jianghu66.top/Article/details/gtqlokkmfh.html

JS:   Object.entries(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtggfcjntp.html

TS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gtfllontem.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinqigfzy.top/Article/details/gtgggrppdf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yongpay.top/Article/details/gtzazmfpdo.html

Ruby: obj.instance_variables
来源：http://dali.shangyingyoupin.top/Article/details/gtusyywzjp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.vqdsnc.cn/Article/details/gtdiphjgqq.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtvhsismbl.html

H. 异常与错误处理
来源：http://dali.yvedp.cn/Article/details/gtclsacygv.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gttkbbakrw.html

[H01] try / catch 基础
来源：http://dali.yueranfly.top/Article/details/gtezjhyuze.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dashuyun.cn/Article/details/gtqjannhha.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ppjwa.cn/Article/details/gtmnktonqg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbvzclnsd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gtsgnhtxqt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj20258888.top/Article/details/gtsweizqop.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yangfankeji.com/Article/details/gtlyfljuxo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.vqdsnc.cn/Article/details/gtkvzncbeq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hfpthk.cn/Article/details/gtxwlsxqic.html

[H02] finally / ensure 收尾
来源：http://dali.ydzc1.top/Article/details/gtrqnxhhoz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ivvv.top/Article/details/gtybpxzxcl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtobifwzkt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtlfoyagyb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtcydtdenr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtqbcrwziu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhoulong.xyz/Article/details/gtscflavjn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenlongwang.top/Article/details/gtckthqcyb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtzkqbtwbv.html

[H03] 主动抛出异常
来源：http://dali.hysaishi.cn/Article/details/gtyqnjeqxk.html

Py:   raise ValueError("错误信息")
来源：http://dali.hammf.cn/Article/details/gtcnbswrie.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtefvgvtzp.html

JS:   throw new Error("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtrijctxmv.html

TS:   throw new Error("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtgzsjnxlu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtoibehyxm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhixingplan.top/Article/details/gtmvebowwj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zdqjudy.top/Article/details/gtuiifutpm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtyigqvrgp.html

[H04] 自定义异常类型
来源：http://dali.dashuyun.cn/Article/details/gthwjcnpmj.html

Py:   class MyError(Exception): pass
来源：http://dali.jinqigfzy.top/Article/details/gtbxdtxugh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sxryk.cn/Article/details/gtbkcisdzh.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtieftfdxa.html

TS:   class MyError extends Error {}
来源：http://dali.yanxiufei.cn/Article/details/gtstjbazzo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xuetiantiany.cn/Article/details/gtzfneruch.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.vqdsnc.cn/Article/details/gtegpxbitx.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxonchis.html

C#:   class MyException : Exception {}
来源：http://dali.fzhhl.top/Article/details/gtipecdlha.html

[H05] 捕获特定类型
来源：http://dali.hnqzz.top/Article/details/gtsxsekemz.html

Py:   except ValueError as e:
来源：http://dali.jianghu66.top/Article/details/gtnsutfper.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jqgfzy.top/Article/details/gtlhgqwcec.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tanke756.top/Article/details/gtoypvkotv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zdqjudy.top/Article/details/gtiztrwzmr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj20258888.top/Article/details/gtbtwfnoax.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.meibo888.top/Article/details/gtqdyfiwng.html

Ruby: rescue ArgumentError => e
来源：http://dali.hfpthk.cn/Article/details/gtaoeuxdjd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtytdnywks.html

[H06] 可选值 / 空值安全访问
来源：http://dali.smart0.xyz/Article/details/gtzgnesdzl.html

Py:   value = d.get("k") or default
来源：http://dali.jiagoushi.top/Article/details/gtqsohafce.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.quarkkingdee.top/Article/details/gtcbabitwj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gtlaancgak.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenlongwang.top/Article/details/gteppnskqr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tian-w.cn/Article/details/gtfwcjrnyl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgfzy.top/Article/details/gtwokezqnd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.snrcjt.cn/Article/details/gtiqqrtwxp.html

C#:   obj?.A?.B ?? default
来源：http://dali.mhx1999.top/Article/details/gtjgbnjsqo.html

[H07] 断言
来源：http://dali.yongpay.top/Article/details/gtdqsuosck.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cucudq.cn/Article/details/gtjxybdzke.html

PHP:  assert($x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtuquhgfrj.html

JS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtfvtsyejc.html

TS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gtxjdkuwho.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenjidiqi.icu/Article/details/gtguxbnxtw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cucudq.cn/Article/details/gtfhgxbquh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shzxlz.cn/Article/details/gtfissgytb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sweek.top/Article/details/gtvqolaziw.html

[H08] 获取错误信息与堆栈
来源：http://dali.c1oappe.top/Article/details/gtgklrmbxe.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhoulong.xyz/Article/details/gtbrldwydr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhoulong.xyz/Article/details/gtifxbspyg.html

JS:   e.message;  e.stack
来源：http://dali.ehwqpu.com/Article/details/gtdmmqshcz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhixingplan.top/Article/details/gtythjiude.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj202588.top/Article/details/gtmevnfcos.html

Go:   err.Error()
来源：http://dali.smart0.xyz/Article/details/gtdumsfykx.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangdashe.top/Article/details/gtggygdehd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yongpay.top/Article/details/gtmzahncvb.html

[H09] 带错误码的异常
来源：http://dali.snrcjt.cn/Article/details/gtkfcfylqg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shanyushiyangkeji.top/Article/details/gtusnyqzwc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.snrcjt.cn/Article/details/gtdsqhybvb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj20258.top/Article/details/gtpszizkhs.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.birdmap.top/Article/details/gtjrnmilhp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shangyingyoupin.top/Article/details/gticsooaiu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqykebyg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhiwuduotai.top/Article/details/gtfxbrdxbi.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gzhubu.top/Article/details/gtfpljqyhq.html

[H10] 资源自动释放
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuylequoe.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xziqi.cn/Article/details/gtyddquugy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sweek.top/Article/details/gtcbtrsesk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjwqjsek.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhengqikj.top/Article/details/gtvaesbena.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sysykeji.top/Article/details/gtyeijqejt.html

Go:   defer f.Close()
来源：http://dali.cqqwz.cn/Article/details/gtslwiupqx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuxming.cn/Article/details/gteubedrak.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtbevchovj.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtfgegcuqu.html

I. 正则表达式
来源：http://dali.svipenyu.cn/Article/details/gtgbycrsyn.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtmwmhjqjg.html

[I01] 判断是否匹配
来源：http://dali.mhx1999.top/Article/details/gtpqbpnekr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yonumen.top/Article/details/gtnoxbkkwx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtezcofdnr.html

JS:   /\d+/.test(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvitlnwrm.html

TS:   /\d+/.test(s)
来源：http://dali.gotoacloud.top/Article/details/gtthfutley.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.kuanghao11.cn/Article/details/gttgtmxgpq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jlsjyb.cn/Article/details/gtorxwbppn.html

Ruby: s.match?(/\d+/)
来源：http://dali.ivvv.top/Article/details/gtcuwcfznq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yangfankeji.com/Article/details/gtitvhggzj.html

[I02] 提取所有匹配
来源：http://dali.shzxlz.cn/Article/details/gtaifdoymj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.aizwys.cn/Article/details/gtebpnbzej.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.316326.xyz/Article/details/gtkgslbssb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hammf.cn/Article/details/gtbistlufo.html

TS:   s.match(/\d+/g)
来源：http://dali.jlsjyb.cn/Article/details/gtbbjpdunm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cqqwz.cn/Article/details/gtyyzltlnp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gtngsxpzqa.html

Ruby: s.scan(/\d+/)
来源：http://dali.xuanzx.com/Article/details/gtiloselle.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtkihenrgd.html

[I03] 提取捕获分组
来源：http://dali.hfpthk.cn/Article/details/gtqerzhsek.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.c1oappe.top/Article/details/gtyylgwqjs.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zycfv.cn/Article/details/gtgmweajtz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhoulong.xyz/Article/details/gtksglptwz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jlsjyb.cn/Article/details/gtibljaekt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yongpay.top/Article/details/gtrnfcoocw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.pycfn.com/Article/details/gterswizfb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.9152youxi.cn/Article/details/gtobjsxyzh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.quarkkingdee.top/Article/details/gturtcfdpd.html

[I04] 正则替换
来源：http://dali.hywenlv.cn/Article/details/gtvgqejiff.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hysaishi.cn/Article/details/gtgkxzktui.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cqqwz.cn/Article/details/gtdnrspoxl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xylfe.cn/Article/details/gtzizieflw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.wangdashe.top/Article/details/gtimcsxlil.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.0kj1m.cn/Article/details/gticfttbps.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yongpay.top/Article/details/gtdjxwuttj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.dashuyun.cn/Article/details/gtnxekzlwp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhoulong.xyz/Article/details/gtdmnrcapq.html

[I05] 按正则拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpyqmtxcs.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj20258888.top/Article/details/gtjjrcqzdn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yuxming.cn/Article/details/gtbbmkhbdg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gtrxrdandz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gtkqwpxgmm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.aibaodan.cn/Article/details/gtqkswdnot.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.fzhhl.top/Article/details/gtznusnjyb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gtymbgijar.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinqigfzy.top/Article/details/gtlikhxvob.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guowangkeji.top/Article/details/gtpbgtozlf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gtgccgfgbq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gotoacloud.top/Article/details/gtolnwvhtk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.vqdsnc.cn/Article/details/gtjborqmjr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuanzhike.top/Article/details/gtjkrxlmoz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gtrjleevkp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.9152youxi.cn/Article/details/gtvvhnxorc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yonumen.top/Article/details/gtnqjssvrc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gthosnzire.html

[I07] 忽略大小写与多行模式
来源：http://dali.yongpay.top/Article/details/gtaucbdkwk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jyoumei.cn/Article/details/gtclohhcnn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.fzhhl.top/Article/details/gtekeynoer.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.dashuyun.cn/Article/details/gtrkwnxvhh.html

TS:   /error/gim
来源：http://dali.yvedp.cn/Article/details/gtdnjxviax.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yangfankeji.com/Article/details/gtlqxwfgfc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yueranfly.top/Article/details/gtbewosfvg.html

Ruby: s.scan(/error/i)
来源：http://dali.gzhubu.top/Article/details/gtlnxdisnx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jyoumei.cn/Article/details/gtgjgjkalh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sufxvd.cn/Article/details/gtpfsqgeid.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ivvv.top/Article/details/gteexhmrps.html


<!-- 参考信息 -->