代发 wailian999

Java: class User {}
来源：http://dali.9152youxi.cn/Article/details/gtsufanouy.html

Go:   type User struct { Name string }
来源：http://dali.yj20258.top/Article/details/gtgtlzpkqn.html

Ruby: class User; end
来源：http://dali.quarkkingdee.top/Article/details/gtbyyyrabz.html

C#:   class User {}
来源：http://dali.gzhubu.top/Article/details/gtnqfeziig.html

[G02] 构造函数
来源：http://dali.yj20258.top/Article/details/gtwjyvhrhl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ydzc1.top/Article/details/gtifnpblnb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zycfv.cn/Article/details/gtmlukhdpx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gtnvirbjiu.html

TS:   constructor(public name: string) {}
来源：http://dali.ehwqpu.com/Article/details/gtyaysirig.html

Java: User(String name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gtaxxlvzlf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj20258.top/Article/details/gtqulqlrop.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtczpiydvv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxinkj.top/Article/details/gtozylpbjd.html

[G03] 实例属性
来源：http://dali.nanxuanxn.top/Article/details/gtzoefyump.html

Py:   self.name = "x"
来源：http://dali.jqgfzy.top/Article/details/gteinmxkns.html

PHP:  public string $name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtvyyhiyzt.html

JS:   this.name = "x";
来源：http://dali.havefunace.top/Article/details/gtwvrauvwv.html

TS:   name: string = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtyodeylti.html

Java: private String name;
来源：http://dali.havefunace.top/Article/details/gtdmjepwoc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.quarkkingdee.top/Article/details/gtgtpssfyp.html

Ruby: @name = "x"
来源：http://dali.jinqigufen.top/Article/details/gtnnjebdcs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigfzy.top/Article/details/gteouaoujm.html

[G04] 定义方法
来源：http://dali.fengsongda.top/Article/details/gtkpczexwg.html

Py:   def greet(self): return self.name
来源：http://dali.quarkkingdee.top/Article/details/gtrjnvdwyb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtiboluikt.html

JS:   greet() { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtlermsldm.html

TS:   greet(): string { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtcyrrnrzi.html

Java: String greet() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtgwajlwjl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtskhzkrdu.html

Ruby: def greet; @name; end
来源：http://dali.xuetiantiany.cn/Article/details/gtjbgehszv.html

C#:   public string Greet() => Name;
来源：http://dali.ivvv.top/Article/details/gtfhlqzryj.html

[G05] 继承
来源：http://dali.birdmap.top/Article/details/gteiuwxzey.html

Py:   class Admin(User): pass
来源：http://dali.haohaochexian.top/Article/details/gtzictxefk.html

PHP:  class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtmtfpoyjy.html

JS:   class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtgmmuvort.html

TS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtiyaoionj.html

Java: class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtgbeiswuq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jyoumei.cn/Article/details/gttgiqwhnk.html

Ruby: class Admin < User; end
来源：http://dali.zhongyouzk.top/Article/details/gtwzkknzwa.html

C#:   class Admin : User {}
来源：http://dali.snrcjt.cn/Article/details/gtqpbqyubf.html

[G06] 重写方法
来源：http://dali.xziqi.cn/Article/details/gtmxnhqjij.html

Py:   def greet(self): return "admin"
来源：http://dali.zhoulong.xyz/Article/details/gtkauopkte.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtlmauowpf.html

JS:   greet() { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gtvzodorqs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gtafxlgrrc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtxlktwruq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shzxlz.cn/Article/details/gtleyiownj.html

Ruby: def greet; "admin"; end
来源：http://dali.dashuyun.cn/Article/details/gtgxuqimrf.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuanzx.com/Article/details/gtstjsdghf.html

[G07] 调用父类方法
来源：http://dali.iojbl.cn/Article/details/gtedzydxdh.html

Py:   super().greet()
来源：http://dali.zdqjudy.top/Article/details/gtvhgdjtsk.html

PHP:  parent::greet();
来源：http://dali.cheryme.top/Article/details/gtkkvvlgoh.html

JS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gtlylcdggv.html

TS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gtvdqtitch.html

Java: super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtomgpvdem.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnxiangtu.top/Article/details/gtuposzkxj.html

Ruby: super
来源：http://dali.aibaodan.cn/Article/details/gtmbkidbyr.html

C#:   base.Greet();
来源：http://dali.gzhubu.top/Article/details/gtnmhdglgo.html

[G08] 静态方法与属性
来源：http://dali.0kj1m.cn/Article/details/gtrqwsmwci.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cucudq.cn/Article/details/gtnnyzoufa.html

PHP:  public static function f() {}
来源：http://dali.ppjwa.cn/Article/details/gtlcgfiabd.html

JS:   static f() {}
来源：http://dali.yj20258.top/Article/details/gtpqwtncbo.html

TS:   static f(): void {}
来源：http://dali.daxiang520.top/Article/details/gtwiyrqsfp.html

Java: static void f() {}
来源：http://dali.svipenyu.cn/Article/details/gtjpkrwgwi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ybcxt.top/Article/details/gtwighzikz.html

Ruby: def self.f; end
来源：http://dali.cheryme.top/Article/details/gtyqmjrbzi.html

C#:   public static void F() {}
来源：http://dali.nanxuanxn.top/Article/details/gtunbkteft.html

[G09] 接口 / 抽象类
来源：http://dali.daxiang520.top/Article/details/gtashlbdea.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tianlin.xyz/Article/details/gtpsatsyyg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258.top/Article/details/gtukcpvzry.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ybcxt.top/Article/details/gtsxvquico.html

TS:   interface Shape { area(): number; }
来源：http://dali.xuetiantiany.cn/Article/details/gtpugfzjms.html

Java: interface Shape { double area(); }
来源：http://dali.9152youxi.cn/Article/details/gtxchavkxr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xziqi.cn/Article/details/gtjzvyphvb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jyoumei.cn/Article/details/gtmkathrfn.html

C#:   interface IShape { double Area(); }
来源：http://dali.xinyue.icu/Article/details/gtafllkmcd.html

[G10] 访问控制
来源：http://dali.tanke756.top/Article/details/gtrphgkyue.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yanxiufei.cn/Article/details/gtnowhjwwd.html

PHP:  public / protected / private
来源：http://dali.nwbrower.top/Article/details/gtmawxiqvh.html

JS:   #private 字段；其余公开
来源：http://dali.gaohongyu789.top/Article/details/gtsplggkrl.html

TS:   public / protected / private
来源：http://dali.jianghu66.top/Article/details/gtcbbaglij.html

Java: public / protected / private / 默认包级
来源：http://dali.hongshengwenyu.top/Article/details/gttqkonmdy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.snrcjt.cn/Article/details/gtspdzmuor.html

Ruby: public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtrwlnpsvl.html

C#:   public / protected / private / internal
来源：http://dali.shanyushiyangtech.top/Article/details/gtwnjdcjqe.html

[G11] getter / setter
来源：http://dali.jyoumei.cn/Article/details/gteystsfxm.html

Py:   @property 与 @x.setter
来源：http://dali.cheryme.top/Article/details/gtoczcpmji.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtfgjvqmaz.html

JS:   get name() { return this._name; }
来源：http://dali.aibaodan.cn/Article/details/gtatwkbfbf.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gtujdquudn.html

Java: public String getName() { return name; }
来源：http://dali.jianghu66.top/Article/details/gtrwfeizdi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtgqzkidvq.html

Ruby: attr_accessor :name
来源：http://dali.cqqwz.cn/Article/details/gttlksjetu.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtflggoqed.html

[G12] 对象转字符串
来源：http://dali.yanxiufei.cn/Article/details/gtnihuvhdy.html

Py:   def __str__(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gtcwbriuzt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gtmfuaeusp.html

JS:   toString() { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtyrwesygi.html

TS:   toString(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtvcadrjci.html

Java: @Override public String toString() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtgiamliqc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtfmgiygeo.html

Ruby: def to_s; @name; end
来源：http://dali.cucudq.cn/Article/details/gtpgosqjzl.html

C#:   public override string ToString() => Name;
来源：http://dali.sxryk.cn/Article/details/gtprmhfkwj.html

[G13] 判断对象类型
来源：http://dali.redwolf501.top/Article/details/gtmbsafybz.html

Py:   isinstance(u, User)
来源：http://dali.sufxvd.cn/Article/details/gtiraqsxcn.html

PHP:  $u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtifpkpkmy.html

JS:   u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gttehnsuye.html

TS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtbdaeknke.html

Java: u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtxyibtoiz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.chenlongwang.top/Article/details/gtmlbfryvj.html

Ruby: u.is_a?(User)
来源：http://dali.aibaodan.cn/Article/details/gtgaxtmudc.html

C#:   u is User
来源：http://dali.meibo888.top/Article/details/gtvccnxuzw.html

[G14] 数据类 / record
来源：http://dali.gaohongyu789.top/Article/details/gtuncxvrts.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gzhubu.top/Article/details/gttjmomysy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pycfn.com/Article/details/gtzqhhypre.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zycfv.cn/Article/details/gtpylujfjt.html

TS:   type User = { name: string; age: number };
来源：http://dali.yongpay.top/Article/details/gtmkfatrov.html

Java: record User(String name, int age) {}
来源：http://dali.aizwys.cn/Article/details/gtborkeibf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zycfv.cn/Article/details/gtmcgvxuuc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tianlin.xyz/Article/details/gtnquvntue.html

C#:   record User(string Name, int Age);
来源：http://dali.yueranfly.top/Article/details/gttbdqysii.html

[G15] 枚举
来源：http://dali.dianchejie.cn/Article/details/gtrgbzdgiq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yonumen.top/Article/details/gtunjbptax.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258.top/Article/details/gtoezgkvdg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangshuangyany.cn/Article/details/gtmchnlsbp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gtochovaet.html

Java: enum Color { RED, GREEN }
来源：http://dali.ydzc1.top/Article/details/gtjashowne.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nwbrower.top/Article/details/gteomgfnzr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.feifeiyinyue.top/Article/details/gtzdonexng.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zycfv.cn/Article/details/gtjkrlvyup.html

[G16] 对象转数组 / 字典
来源：http://dali.xinyue.icu/Article/details/gtnwddtjoq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigfzy.top/Article/details/gtgvusmmvm.html

PHP:  get_object_vars($obj);
来源：http://dali.xinyue.icu/Article/details/gtebmowsuj.html

JS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gtghxekzqe.html

TS:   Object.entries(obj)
来源：http://dali.svipenyu.cn/Article/details/gtpkraachz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.birdmap.top/Article/details/gtgykocwuf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yuxming.cn/Article/details/gtaxlymtok.html

Ruby: obj.instance_variables
来源：http://dali.pengpengdd.cyou/Article/details/gtblmxglab.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gtsamwyepl.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtsdqgawkf.html

H. 异常与错误处理
来源：http://dali.kuanghao11.cn/Article/details/gtbsjednzk.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtjzpgodub.html

[H01] try / catch 基础
来源：http://dali.ehwqpu.com/Article/details/gtzrsrhmlv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jlsjyb.cn/Article/details/gtiprdfbzb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jlsjyb.cn/Article/details/gtoqpqorck.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gtkkvpqhcb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbdydheed.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nanxinkj.top/Article/details/gtwblhhwhy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shangyingyoupin.top/Article/details/gtpyqzwrxu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hywenlv.cn/Article/details/gtfnpljldf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shangyingyoupin.top/Article/details/gtyhocseue.html

[H02] finally / ensure 收尾
来源：http://dali.yanxiufei.cn/Article/details/gtxljfuxsr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenzaomai.com/Article/details/gtwtohsdrm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtjvntkiqn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtcumrrlhc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtmihhyauo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtwfpnjpka.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ybcxt.top/Article/details/gtvgwlmgsa.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gtyhrtrkmh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtwzggsquh.html

[H03] 主动抛出异常
来源：http://dali.zhiwuduotai.top/Article/details/gttqwyfkgd.html

Py:   raise ValueError("错误信息")
来源：http://dali.yongpay.top/Article/details/gtqrqicfbt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gtqtjxwlbi.html

JS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtisgtprsh.html

TS:   throw new Error("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtxvciiseq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gthzpnjzkc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenlongwang.top/Article/details/gtvuxueqco.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258.top/Article/details/gtdpoyfqgn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gthtsmurnt.html

[H04] 自定义异常类型
来源：http://dali.fengsongda.top/Article/details/gtayybcmcu.html

Py:   class MyError(Exception): pass
来源：http://dali.zhengqikj.top/Article/details/gtatpggrkg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenlongwang.top/Article/details/gtmntoojki.html

JS:   class MyError extends Error {}
来源：http://dali.cucudq.cn/Article/details/gtevjshalk.html

TS:   class MyError extends Error {}
来源：http://dali.hammf.cn/Article/details/gtxxpyespq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.mhx1999.top/Article/details/gtduuhcwpl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigfzy.top/Article/details/gtyitrydvz.html

Ruby: class MyError < StandardError; end
来源：http://dali.nanxinkj.top/Article/details/gtqdlqmypq.html

C#:   class MyException : Exception {}
来源：http://dali.hnxiangtu.top/Article/details/gtvwbgdjkx.html

[H05] 捕获特定类型
来源：http://dali.0kj1m.cn/Article/details/gtaawbshcp.html

Py:   except ValueError as e:
来源：http://dali.cucudq.cn/Article/details/gtprglxirw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gzhubu.top/Article/details/gteludqnzf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hywenlv.cn/Article/details/gtezipkdaw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ivvv.top/Article/details/gtayfjptpq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ydzc1.top/Article/details/gtdskhftmx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gzhubu.top/Article/details/gtszbdysal.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhixingplan.top/Article/details/gtiihbqlnd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtfuaqmgyz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhiwuduotai.top/Article/details/gtupzbgdms.html

Py:   value = d.get("k") or default
来源：http://dali.jiagoushi.top/Article/details/gtwafferxr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yueranfly.top/Article/details/gthlgizivz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gtuahgtcoi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gtxrwgpmvy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.316326.xyz/Article/details/gtbclvezwf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nanxinkj.top/Article/details/gtsqobhztd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gtmbkaqpmj.html

C#:   obj?.A?.B ?? default
来源：http://dali.hywenlv.cn/Article/details/gtrmsqaxos.html

[H07] 断言
来源：http://dali.xuanzx.com/Article/details/gttdrifhhz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhiwuduotai.top/Article/details/gtuuagrznn.html

PHP:  assert($x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtqoziayvp.html

JS:   console.assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtibxxbeac.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtzrcwetae.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ydzc1.top/Article/details/gtjmjptkod.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hongshengwenyu.top/Article/details/gtvmaitbvk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gzhubu.top/Article/details/gtyxmpwyyk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtnldtrizj.html

[H08] 获取错误信息与堆栈
来源：http://dali.sweek.top/Article/details/gtrdjmzzfc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.c1oappe.top/Article/details/gtfcqxzocb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cdnleiting.top/Article/details/gtfezvkdaq.html

JS:   e.message;  e.stack
来源：http://dali.guannengcc.top/Article/details/gtgxilrbcg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenzaomai.com/Article/details/gtbymhqace.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sufxvd.cn/Article/details/gtpwntlqyy.html

Go:   err.Error()
来源：http://dali.yongpay.top/Article/details/gtxxsyokvs.html

Ruby: e.message;  e.backtrace
来源：http://dali.jianghu66.top/Article/details/gtwexizlfw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.aizwys.cn/Article/details/gtnrkioxtq.html

[H09] 带错误码的异常
来源：http://dali.cheryme.top/Article/details/gtvimqkxuj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gotoacloud.top/Article/details/gtgqvvtutg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pycfn.com/Article/details/gthkbtezgm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fzhhl.top/Article/details/gtekvckine.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tanke756.top/Article/details/gtwsvhsvei.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gogol.net.cn/Article/details/gtdmquutiu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xinyue.icu/Article/details/gtwtesnduc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.haohaochexian.top/Article/details/gtasiwwwli.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zdqjudy.top/Article/details/gthaczspew.html

[H10] 资源自动释放
来源：http://dali.yueranfly.top/Article/details/gtlthsbheh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.pengpengdd.cyou/Article/details/gtwujigjuo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yangfankeji.com/Article/details/gtvmeitvfa.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangshuangyany.cn/Article/details/gtdzgqtgil.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gtrcnrfigi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.pengpengdd.cyou/Article/details/gtissemogv.html

Go:   defer f.Close()
来源：http://dali.cucudq.cn/Article/details/gtsvouzxgc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj20258888.top/Article/details/gtobputxis.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtmfxqbszv.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtrzdcnhsd.html

I. 正则表达式
来源：http://dali.havefunace.top/Article/details/gtadrmbgxr.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtfegsrdjc.html

[I01] 判断是否匹配
来源：http://dali.zhixingplan.top/Article/details/gtdffcqjlu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gogol.net.cn/Article/details/gtbuikmica.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.dianchejie.cn/Article/details/gthcrhszmg.html

JS:   /\d+/.test(s)
来源：http://dali.yuanzhike.top/Article/details/gtpswloaxm.html

TS:   /\d+/.test(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtpfcokiev.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sxryk.cn/Article/details/gtlwedbwyw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sufxvd.cn/Article/details/gtfqiuvslv.html

Ruby: s.match?(/\d+/)
来源：http://dali.316326.xyz/Article/details/gtmcrllpaf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nanxinkj.top/Article/details/gthghbluut.html

[I02] 提取所有匹配
来源：http://dali.aizwys.cn/Article/details/gtfzpgwtut.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gtcveqdrgy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.andypj.xyz/Article/details/gtudazimip.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenzaomai.com/Article/details/gtiedvamaj.html

TS:   s.match(/\d+/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkoqgukxo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cheryme.top/Article/details/gtpzyydina.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hongshengwenyu.top/Article/details/gtnsnhphpu.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj20258888.top/Article/details/gtdvvabure.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sysykeji.top/Article/details/gtwfwjgzlr.html

[I03] 提取捕获分组
来源：http://dali.yangfankeji.com/Article/details/gtrudspovm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xziqi.cn/Article/details/gthfcxpbsd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sufxvd.cn/Article/details/gthuewnbtm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangdashe.top/Article/details/gtehryrzyq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.iojbl.cn/Article/details/gtmrvjophz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jqgufenzy.top/Article/details/gtjajlyydb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.vqdsnc.cn/Article/details/gtlpmrryxp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tian-w.cn/Article/details/gttaafshrp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.daria6918.cn/Article/details/gtniqyxyyq.html

[I04] 正则替换
来源：http://dali.xinyue.icu/Article/details/gtaoccpwmg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gzhubu.top/Article/details/gtkxkalvel.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenzaomai.com/Article/details/gtvvumvdri.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gtbospjqzp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sxryk.cn/Article/details/gtqsgpmlwq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.smart0.xyz/Article/details/gttkbppobi.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenlongwang.top/Article/details/gtehsdbsgd.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtahgrqkxc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.fzhhl.top/Article/details/gtinudaxlq.html

[I05] 按正则拆分
来源：http://dali.jqgfzy.top/Article/details/gtcqyzgxfp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhoulong.xyz/Article/details/gttoinynjt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shzxlz.cn/Article/details/gtelbtvqst.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.snrcjt.cn/Article/details/gtfbznmnpa.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gthibyoujr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcsjpzrti.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hammf.cn/Article/details/gtljoygdxo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gtatixuwzx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinqigfzy.top/Article/details/gtmtqdwhik.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.fzhhl.top/Article/details/gtrzgpxqbq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gtduafimbk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hfpthk.cn/Article/details/gtphztvdun.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gtkzetdgjb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jiagoushi.top/Article/details/gtenxamlxi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj20258.top/Article/details/gtjgnqcbex.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.wangdashe.top/Article/details/gtpqcyjkqa.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cucudq.cn/Article/details/gtyotyzysf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtposqvvkj.html

[I07] 忽略大小写与多行模式
来源：http://dali.sysykeji.top/Article/details/gtlnnfmywq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nwbrower.top/Article/details/gtzxbvxifx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yanxiufei.cn/Article/details/gtueptbekp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.wangshuangyany.cn/Article/details/gtdkfansaw.html

TS:   /error/gim
来源：http://dali.daria6918.cn/Article/details/gtzwughaxv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.bjfxy.top/Article/details/gtysnllhsv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hfpthk.cn/Article/details/gtzucaymtt.html

Ruby: s.scan(/error/i)
来源：http://dali.feifeiyinyue.top/Article/details/gttnpiopbb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yueranfly.top/Article/details/gtzsetwscc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sufxvd.cn/Article/details/gtwpspgnrk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmqmpejls.html


<!-- 参考信息 -->