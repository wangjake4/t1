代发 wailian999

[G02] 构造函数
来源：http://dali.xuanzx.com/Article/details/gtfevrfgfz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtemskjabd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdecxulng.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gthvtirkmh.html

TS:   constructor(public name: string) {}
来源：http://dali.shuidangran.top/Article/details/gtyswfgjnn.html

Java: User(String name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtnhyhkshe.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gotoacloud.top/Article/details/gtgxudygac.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xuanzx.com/Article/details/gttznfkizc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtkhnkbmvx.html

[G03] 实例属性
来源：http://dali.jlsjyb.cn/Article/details/gtibphtqvs.html

Py:   self.name = "x"
来源：http://dali.xinyue.icu/Article/details/gttuavbvno.html

PHP:  public string $name = "x";
来源：http://dali.havefunace.top/Article/details/gticmrhyqo.html

JS:   this.name = "x";
来源：http://dali.316326.xyz/Article/details/gtioxucujr.html

TS:   name: string = "x";
来源：http://dali.hnqzz.top/Article/details/gtezusrldc.html

Java: private String name;
来源：http://dali.jyoumei.cn/Article/details/gteejctosh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.0kj1m.cn/Article/details/gtjffeqrqq.html

Ruby: @name = "x"
来源：http://dali.xinyue.icu/Article/details/gtzigiezwj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jyoumei.cn/Article/details/gtoajwsxsh.html

[G04] 定义方法
来源：http://dali.cucudq.cn/Article/details/gtzeemhsgx.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangtech.top/Article/details/gtkzkdjugq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gtvcztpqyr.html

JS:   greet() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gttnxsevdx.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtysqcylwb.html

Java: String greet() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtnggvusud.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gtviaeybfe.html

Ruby: def greet; @name; end
来源：http://dali.gotoacloud.top/Article/details/gttngxilrt.html

C#:   public string Greet() => Name;
来源：http://dali.cqqwz.cn/Article/details/gtfcfbuyvi.html

[G05] 继承
来源：http://dali.haohaochexian.top/Article/details/gtlxavoqtf.html

Py:   class Admin(User): pass
来源：http://dali.jqgufenzy.top/Article/details/gtfvjuzoep.html

PHP:  class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtrjchehua.html

JS:   class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtaadhefxb.html

TS:   class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gtarudlajz.html

Java: class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gtmuvssbge.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.9152youxi.cn/Article/details/gtswqhchuj.html

Ruby: class Admin < User; end
来源：http://dali.mhx1999.top/Article/details/gtlsfkvijp.html

C#:   class Admin : User {}
来源：http://dali.0kj1m.cn/Article/details/gtkmlwuxam.html

[G06] 重写方法
来源：http://dali.haohaochexian.top/Article/details/gtwzzrykwx.html

Py:   def greet(self): return "admin"
来源：http://dali.andypj.xyz/Article/details/gtybeljhyt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtkcfxtsun.html

JS:   greet() { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthgqboctz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtvrltrskn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtmbgdtxzw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yangfankeji.com/Article/details/gtvbclghqj.html

Ruby: def greet; "admin"; end
来源：http://dali.guowangkeji.top/Article/details/gtcbwlzpzi.html

C#:   public override string Greet() => "admin";
来源：http://dali.yuanzhike.top/Article/details/gtzqrtmbmj.html

[G07] 调用父类方法
来源：http://dali.gotoacloud.top/Article/details/gtiteigmvp.html

Py:   super().greet()
来源：http://dali.iojbl.cn/Article/details/gtiozvycll.html

PHP:  parent::greet();
来源：http://dali.ppjwa.cn/Article/details/gtursoprgr.html

JS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtkddubfym.html

TS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gthawgnaca.html

Java: super.greet();
来源：http://dali.ppjwa.cn/Article/details/gtolgphifa.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenjidiqi.icu/Article/details/gttnxtyqgs.html

Ruby: super
来源：http://dali.jinghuilouyu.cn/Article/details/gtswjrsqnz.html

C#:   base.Greet();
来源：http://dali.yj20258888.top/Article/details/gtuokkcoac.html

[G08] 静态方法与属性
来源：http://dali.jqgufenzy.top/Article/details/gtagjjnmob.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pengpengdd.cyou/Article/details/gtjfcwqzjs.html

PHP:  public static function f() {}
来源：http://dali.nanxuanxn.top/Article/details/gtpsfzcgne.html

JS:   static f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtaqpharbt.html

TS:   static f(): void {}
来源：http://dali.hongshengwenyu.top/Article/details/gtqrloijol.html

Java: static void f() {}
来源：http://dali.hysaishi.cn/Article/details/gtwnzwupsr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jyoumei.cn/Article/details/gtmqgzfxnm.html

Ruby: def self.f; end
来源：http://dali.gogol.net.cn/Article/details/gtfcalbwnc.html

C#:   public static void F() {}
来源：http://dali.yuxming.cn/Article/details/gtpzsvplxu.html

[G09] 接口 / 抽象类
来源：http://dali.jiagoushi.top/Article/details/gtmtbzhaif.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pycfn.com/Article/details/gtmfqljrtn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sufxvd.cn/Article/details/gtzbciooim.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.dianchejie.cn/Article/details/gtetnxzbhq.html

TS:   interface Shape { area(): number; }
来源：http://dali.yanxiufei.cn/Article/details/gtcrcmgoki.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigfzy.top/Article/details/gtpwbrjsda.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jianghu66.top/Article/details/gtgrysptpp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fzhhl.top/Article/details/gtcovolsyj.html

C#:   interface IShape { double Area(); }
来源：http://dali.quarkkingdee.top/Article/details/gtgrnzaeux.html

[G10] 访问控制
来源：http://dali.ybcxt.top/Article/details/gtefjhyseu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.c1oappe.top/Article/details/gtmdfvxakr.html

PHP:  public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtmohpzjzv.html

JS:   #private 字段；其余公开
来源：http://dali.yonumen.top/Article/details/gtgqpppeea.html

TS:   public / protected / private
来源：http://dali.ybcxt.top/Article/details/gtqhmhkiba.html

Java: public / protected / private / 默认包级
来源：http://dali.nanxinkj.top/Article/details/gtklawxmcl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrxiodgc.html

Ruby: public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gteegfqios.html

C#:   public / protected / private / internal
来源：http://dali.yvedp.cn/Article/details/gtmcshazbw.html

[G11] getter / setter
来源：http://dali.hongshengwenyu.top/Article/details/gtdfbsyxrp.html

Py:   @property 与 @x.setter
来源：http://dali.iojbl.cn/Article/details/gtleroitwe.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtotvrdypp.html

JS:   get name() { return this._name; }
来源：http://dali.ydzc1.top/Article/details/gtzsczxjgn.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuanzx.com/Article/details/gtwixhzwtc.html

Java: public String getName() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtqndjqqvl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gtpceithgh.html

Ruby: attr_accessor :name
来源：http://dali.dashuyun.cn/Article/details/gtuoaawzey.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtaojawgse.html

[G12] 对象转字符串
来源：http://dali.316326.xyz/Article/details/gttugkayis.html

Py:   def __str__(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gtjswwtjsc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gtabtwuzbo.html

JS:   toString() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gthrqngbnq.html

TS:   toString(): string { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gtaamfksud.html

Java: @Override public String toString() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtzbbeujxy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtxudaayyp.html

Ruby: def to_s; @name; end
来源：http://dali.bjfxy.top/Article/details/gtnxfifxcd.html

C#:   public override string ToString() => Name;
来源：http://dali.sysykeji.top/Article/details/gtmdcksrnn.html

[G13] 判断对象类型
来源：http://dali.xinyue.icu/Article/details/gtsegplijt.html

Py:   isinstance(u, User)
来源：http://dali.gogol.net.cn/Article/details/gtyeviqcub.html

PHP:  $u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtxrjenjbf.html

JS:   u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gtsmmxriuv.html

TS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtpadwjklx.html

Java: u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtqbqwoigk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.fengsongda.top/Article/details/gtgijqlsvx.html

Ruby: u.is_a?(User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdhpljbbs.html

C#:   u is User
来源：http://dali.hysaishi.cn/Article/details/gtniblmtrm.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gtsjdskibu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj202588.top/Article/details/gtqovgcpmx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sufxvd.cn/Article/details/gtcuhfpwgz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hywenlv.cn/Article/details/gtatfliiyq.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangtech.top/Article/details/gtppktgled.html

Java: record User(String name, int age) {}
来源：http://dali.tanke756.top/Article/details/gtyjztdzoe.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenzaomai.com/Article/details/gtgsqfdhgr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yangfankeji.com/Article/details/gttemlnyct.html

C#:   record User(string Name, int Age);
来源：http://dali.shzxlz.cn/Article/details/gtwzjyzkfr.html

[G15] 枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmhryuxtt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhvbsvoh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtirqvnkko.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jianghu66.top/Article/details/gtytwunkhx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxinkj.top/Article/details/gtimebkytd.html

Java: enum Color { RED, GREEN }
来源：http://dali.aibaodan.cn/Article/details/gtlolwnmke.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sweek.top/Article/details/gtgnyrthjg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenlongwang.top/Article/details/gtztdahswl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtygtnaxag.html

[G16] 对象转数组 / 字典
来源：http://dali.havefunace.top/Article/details/gtsgtpxynq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhmgssdf.html

PHP:  get_object_vars($obj);
来源：http://dali.redwolf501.top/Article/details/gtbizlapzy.html

JS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gtfaovhyqf.html

TS:   Object.entries(obj)
来源：http://dali.guannengcc.top/Article/details/gtgbgqlxhf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenzaomai.com/Article/details/gtmckziezz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zycfv.cn/Article/details/gteqltleni.html

Ruby: obj.instance_variables
来源：http://dali.aizwys.cn/Article/details/gtqxqodczl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tanke756.top/Article/details/gtcmflmnar.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtnbvhqadq.html

H. 异常与错误处理
来源：http://dali.zdqjudy.top/Article/details/gtgiakvwig.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtuuoytifv.html

[H01] try / catch 基础
来源：http://dali.chenjidiqi.icu/Article/details/gtxmowfonu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hnxiangtu.top/Article/details/gtkuqflshw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jlsjyb.cn/Article/details/gtwaezaslv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gtskctlafw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gtatkusefn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtayigrwzk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hongshengwenyu.top/Article/details/gtttqesakz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.316326.xyz/Article/details/gtpfkwljup.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gogol.net.cn/Article/details/gtjlgarlup.html

[H02] finally / ensure 收尾
来源：http://dali.tanke756.top/Article/details/gtjijqypup.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhengqikj.top/Article/details/gtjqwhibsg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtcxnbbnjc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtdeepwqmf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtiiphnkle.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gthrmqtxjq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhoulong.xyz/Article/details/gtdbkgzrzz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hywenlv.cn/Article/details/gtvxpzwbqf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtgooouijs.html

[H03] 主动抛出异常
来源：http://dali.yj20258888.top/Article/details/gtqfcejjrk.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuetiantiany.cn/Article/details/gtijakqsvn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtvsicqsym.html

JS:   throw new Error("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtyqotsmbt.html

TS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtbskzygif.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtjdwhqfze.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.pycfn.com/Article/details/gtcpmppxiq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.kuanghao11.cn/Article/details/gtiooeqrpj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtfbjrvbbh.html

[H04] 自定义异常类型
来源：http://dali.ehwqpu.com/Article/details/gtbfivfkhp.html

Py:   class MyError(Exception): pass
来源：http://dali.birdmap.top/Article/details/gtpqtxgxnd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gttwaulemg.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvprbgiem.html

TS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gtmgqafjiv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gtvlwbebkh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nwbrower.top/Article/details/gtgdzdpuel.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhiwuduotai.top/Article/details/gtrpcskwlp.html

C#:   class MyException : Exception {}
来源：http://dali.cdnleiting.top/Article/details/gtckdnmutj.html

[H05] 捕获特定类型
来源：http://dali.tian-w.cn/Article/details/gttbqibjnm.html

Py:   except ValueError as e:
来源：http://dali.zdqjudy.top/Article/details/gtvlajsuou.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tanke756.top/Article/details/gtiitsvxpe.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gtkhhazecq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gthxxobniq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gogol.net.cn/Article/details/gtldbcemnv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tanke756.top/Article/details/gtdartrnbf.html

Ruby: rescue ArgumentError => e
来源：http://dali.hfpthk.cn/Article/details/gtozlnlmbw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtrxuftyad.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj20258888.top/Article/details/gtzkmbucfl.html

Py:   value = d.get("k") or default
来源：http://dali.cashguo.top/Article/details/gtbmsdnery.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.guowangkeji.top/Article/details/gtfyelavsx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hywenlv.cn/Article/details/gtwmfnwmip.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gtjncgbxge.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtincubryz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jiagoushi.top/Article/details/gtfrfgnaeb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xziqi.cn/Article/details/gtyzptvfvs.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigufen.top/Article/details/gtsvzsjupk.html

[H07] 断言
来源：http://dali.fzhhl.top/Article/details/gtqibmgjkm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tanke756.top/Article/details/gtnujtdaou.html

PHP:  assert($x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gtaokapxyt.html

JS:   console.assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtyesbuxst.html

TS:   console.assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtdzxloxdj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258888.top/Article/details/gtpcrjlgub.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sysykeji.top/Article/details/gtvwhpaarh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ehwqpu.com/Article/details/gtfrakubfn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gtjorrgwkf.html

[H08] 获取错误信息与堆栈
来源：http://dali.quarkkingdee.top/Article/details/gtpwicsjsv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gtejxbyaxp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.daria6918.cn/Article/details/gtvoqtoyux.html

JS:   e.message;  e.stack
来源：http://dali.pengpengdd.cyou/Article/details/gtcwhddkcy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.wangdashe.top/Article/details/gtpltapdox.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yuanzhike.top/Article/details/gtpxhgwskm.html

Go:   err.Error()
来源：http://dali.chenlongwang.top/Article/details/gtxwtnyvor.html

Ruby: e.message;  e.backtrace
来源：http://dali.tanke756.top/Article/details/gtapseloar.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxinkj.top/Article/details/gtzuwhdhvg.html

[H09] 带错误码的异常
来源：http://dali.yueranfly.top/Article/details/gttbbiynrc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shuidangran.top/Article/details/gtckyvdsxa.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.0kj1m.cn/Article/details/gtrvwmzsca.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.pengpengdd.cyou/Article/details/gtldhnmewz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yuanzhike.top/Article/details/gttdbsqlti.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jiagoushi.top/Article/details/gtyomsypnh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hfpthk.cn/Article/details/gtcoqfvzip.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hongshengwenyu.top/Article/details/gtktwnfbqy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zdqjudy.top/Article/details/gtefqzmdzd.html

[H10] 资源自动释放
来源：http://dali.xylfe.cn/Article/details/gtqmthjjcs.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yongpay.top/Article/details/gthecsppvz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tanke756.top/Article/details/gtgcggpwyl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhengqikj.top/Article/details/gtryezgglg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yvedp.cn/Article/details/gtkxmxdjvx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hammf.cn/Article/details/gtseqdaxan.html

Go:   defer f.Close()
来源：http://dali.jianghu66.top/Article/details/gtyafgohjf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.wangshuangyany.cn/Article/details/gtntnnfcxe.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtebswayvo.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gturdzxxud.html

I. 正则表达式
来源：http://dali.xinyue.icu/Article/details/gthipbfmnm.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtkqetmgcm.html

[I01] 判断是否匹配
来源：http://dali.shuidangran.top/Article/details/gtqupqtzsa.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.aibaodan.cn/Article/details/gthaoekknx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yvedp.cn/Article/details/gtiuvhylxq.html

JS:   /\d+/.test(s)
来源：http://dali.aibaodan.cn/Article/details/gtbnzponnl.html

TS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gtuqcsbmmb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hammf.cn/Article/details/gthubynfvu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daria6918.cn/Article/details/gtwilqdjey.html

Ruby: s.match?(/\d+/)
来源：http://dali.kuanghao11.cn/Article/details/gtdgguzfua.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.meibo888.top/Article/details/gthhtuwckx.html

[I02] 提取所有匹配
来源：http://dali.snrcjt.cn/Article/details/gtltxdxmyw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.snrcjt.cn/Article/details/gthxtxzfcc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhiwuduotai.top/Article/details/gttmxlvldz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hywenlv.cn/Article/details/gtxvbwujda.html

TS:   s.match(/\d+/g)
来源：http://dali.316326.xyz/Article/details/gtzpbsxwdq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.smart0.xyz/Article/details/gtpdhpmxkm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.meibo888.top/Article/details/gtgfubxirp.html

Ruby: s.scan(/\d+/)
来源：http://dali.gogol.net.cn/Article/details/gtwkzjoitk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xziqi.cn/Article/details/gtymwfqret.html

[I03] 提取捕获分组
来源：http://dali.ehwqpu.com/Article/details/gtvgqybdjy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nanxinkj.top/Article/details/gtfsaygztj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.meibo888.top/Article/details/gteohwhiqr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ydzc1.top/Article/details/gtkpvvwdvz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cucudq.cn/Article/details/gtteifwqws.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shuidangran.top/Article/details/gtsghvzebn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tian-w.cn/Article/details/gtghwrjtmm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhongyouzk.top/Article/details/gttdzwbxqq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hfpthk.cn/Article/details/gtouoqtltf.html

[I04] 正则替换
来源：http://dali.haohaochexian.top/Article/details/gtbqyyrioq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hnqzz.top/Article/details/gtfglrfnhx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.0kj1m.cn/Article/details/gtgqgukjis.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.pycfn.com/Article/details/gtuwoxjgdg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.dashuyun.cn/Article/details/gtdrzovbjj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj20258888.top/Article/details/gtmktyhjjd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfoxziodj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yuxming.cn/Article/details/gtdokdpood.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.fzhhl.top/Article/details/gtchuocjod.html

[I05] 按正则拆分
来源：http://dali.yj202588.top/Article/details/gtcqwdqutr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinqigfzy.top/Article/details/gtictvtagq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xinyue.icu/Article/details/gtmenxbkvg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcezuyxti.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gtarhgnhea.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sufxvd.cn/Article/details/gtpizbywdd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tanke756.top/Article/details/gtoefbjwbu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gtttczktvv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xylfe.cn/Article/details/gtsgdlqcvc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cucudq.cn/Article/details/gtsuzdyoum.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gtvtalkqrl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jianghu66.top/Article/details/gtqioxnsxq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gtpwumcjxq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258888.top/Article/details/gtuliziqzh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gtsnmyhciq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinqigufen.top/Article/details/gtpnsmyshj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jqgufenzy.top/Article/details/gtrcbkfdfc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gtzikjeawi.html

[I07] 忽略大小写与多行模式
来源：http://dali.kuanghao11.cn/Article/details/gtixqryyur.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtprowtbml.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.fengsongda.top/Article/details/gtkzoyonlt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shangyingyoupin.top/Article/details/gtqigqxmtr.html

TS:   /error/gim
来源：http://dali.shuidangran.top/Article/details/gtzpwwtqya.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.andypj.xyz/Article/details/gtlkpipghx.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cqqwz.cn/Article/details/gtvdyikhrt.html

Ruby: s.scan(/error/i)
来源：http://dali.wangdashe.top/Article/details/gtgmlmgzum.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxxgbtyxa.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtvjtdapex.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.andypj.xyz/Article/details/gtyacwbrpy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jlsjyb.cn/Article/details/gtvrgfvvvu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dashuyun.cn/Article/details/gtsvhtsdkz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.iojbl.cn/Article/details/gtiundxgeg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwdfofbga.html


<!-- 参考信息 -->