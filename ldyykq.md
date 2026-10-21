代发 wailian999

TS:   constructor(public name: string) {}
来源：http://dali.hfpthk.cn/Article/details/gtobcizfdu.html

Java: User(String name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gtosphills.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hysaishi.cn/Article/details/gtyzfxnxif.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqayhfrp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dianchejie.cn/Article/details/gthniwklht.html

[G03] 实例属性
来源：http://dali.jinqigufen.top/Article/details/gtohmtqosq.html

Py:   self.name = "x"
来源：http://dali.tianlin.xyz/Article/details/gtrpjdiitk.html

PHP:  public string $name = "x";
来源：http://dali.hywenlv.cn/Article/details/gtuusicije.html

JS:   this.name = "x";
来源：http://dali.quarkkingdee.top/Article/details/gtoablxdat.html

TS:   name: string = "x";
来源：http://dali.meibo888.top/Article/details/gtpcfgbqwc.html

Java: private String name;
来源：http://dali.pycfn.com/Article/details/gtfliqfprt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgfzy.top/Article/details/gtobjmmibx.html

Ruby: @name = "x"
来源：http://dali.jinqigufen.top/Article/details/gtdmimcxbr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtwxuweqgb.html

[G04] 定义方法
来源：http://dali.guannengcc.top/Article/details/gtygxmeabq.html

Py:   def greet(self): return self.name
来源：http://dali.jinqigufen.top/Article/details/gtbnaatmoo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtnihcfuku.html

JS:   greet() { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gthbxlakwu.html

TS:   greet(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtwdzmmfrm.html

Java: String greet() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gttysudtas.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gtsmtwtrzd.html

Ruby: def greet; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gtlgmttdwp.html

C#:   public string Greet() => Name;
来源：http://dali.ybcxt.top/Article/details/gtrlgxkmee.html

[G05] 继承
来源：http://dali.9152youxi.cn/Article/details/gtftsahmbv.html

Py:   class Admin(User): pass
来源：http://dali.zhoulong.xyz/Article/details/gtjshvwcla.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtyxhpemax.html

JS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtghhvgzoc.html

TS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtawoxpijg.html

Java: class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtugrizyvi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cdnleiting.top/Article/details/gtvkpeqfhx.html

Ruby: class Admin < User; end
来源：http://dali.yueranfly.top/Article/details/gtqcczexsl.html

C#:   class Admin : User {}
来源：http://dali.0kj1m.cn/Article/details/gtxjscyhyc.html

[G06] 重写方法
来源：http://dali.0kj1m.cn/Article/details/gtcnatwwdg.html

Py:   def greet(self): return "admin"
来源：http://dali.zdqjudy.top/Article/details/gtictmliub.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtyjzvgghw.html

JS:   greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtiocuxwte.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtytsjvypx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtidqkiauz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xylfe.cn/Article/details/gtylfbpapz.html

Ruby: def greet; "admin"; end
来源：http://dali.pycfn.com/Article/details/gtniorgrsu.html

C#:   public override string Greet() => "admin";
来源：http://dali.xziqi.cn/Article/details/gtdjzaqnmc.html

[G07] 调用父类方法
来源：http://dali.hywenlv.cn/Article/details/gtiogseqxm.html

Py:   super().greet()
来源：http://dali.iojbl.cn/Article/details/gtrbjbsacy.html

PHP:  parent::greet();
来源：http://dali.chenzaomai.com/Article/details/gtfunvduek.html

JS:   super.greet();
来源：http://dali.yj202588.top/Article/details/gtgponvcym.html

TS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gtwjemshop.html

Java: super.greet();
来源：http://dali.cdnleiting.top/Article/details/gthvxmmuar.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.bjfxy.top/Article/details/gthvoalpgx.html

Ruby: super
来源：http://dali.iojbl.cn/Article/details/gtkzdkamzo.html

C#:   base.Greet();
来源：http://dali.andypj.xyz/Article/details/gtzmzygand.html

[G08] 静态方法与属性
来源：http://dali.zhongyouzk.top/Article/details/gttbsoqwgp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.guowangkeji.top/Article/details/gtmyepxbdy.html

PHP:  public static function f() {}
来源：http://dali.0kj1m.cn/Article/details/gttqbpktht.html

JS:   static f() {}
来源：http://dali.zycfv.cn/Article/details/gtlvnflvqw.html

TS:   static f(): void {}
来源：http://dali.redwolf501.top/Article/details/gthytplash.html

Java: static void f() {}
来源：http://dali.shuidangran.top/Article/details/gtpajjbzsx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.daxiang520.top/Article/details/gtfopyqqgv.html

Ruby: def self.f; end
来源：http://dali.havefunace.top/Article/details/gtgbjanwtv.html

C#:   public static void F() {}
来源：http://dali.gotoacloud.top/Article/details/gtqscustlk.html

[G09] 接口 / 抽象类
来源：http://dali.c1oappe.top/Article/details/gttaiyaijh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.iojbl.cn/Article/details/gtajqowknp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258.top/Article/details/gtutcgwgrd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhoulong.xyz/Article/details/gtmdafxegn.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangshuangyany.cn/Article/details/gthavowsku.html

Java: interface Shape { double area(); }
来源：http://dali.jyoumei.cn/Article/details/gttvblmyau.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yvedp.cn/Article/details/gtdkhavkvu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.vqdsnc.cn/Article/details/gtxjztgiot.html

C#:   interface IShape { double Area(); }
来源：http://dali.havefunace.top/Article/details/gtndqlgiwi.html

[G10] 访问控制
来源：http://dali.yueranfly.top/Article/details/gtdmudvnrl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yangfankeji.com/Article/details/gtjugjxpag.html

PHP:  public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gtfabrdcav.html

JS:   #private 字段；其余公开
来源：http://dali.feifeiyinyue.top/Article/details/gtrsrtluzc.html

TS:   public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gtfcawmtzy.html

Java: public / protected / private / 默认包级
来源：http://dali.yueranfly.top/Article/details/gtnhcnsakn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hysaishi.cn/Article/details/gterzwnpqr.html

Ruby: public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtteozaqre.html

C#:   public / protected / private / internal
来源：http://dali.havefunace.top/Article/details/gtmmgihszu.html

[G11] getter / setter
来源：http://dali.daxiang520.top/Article/details/gtydntwfkv.html

Py:   @property 与 @x.setter
来源：http://dali.jlsjyb.cn/Article/details/gtpnqxhcck.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gtiqquegqy.html

JS:   get name() { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gtpesmfnnw.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmddaryjw.html

Java: public String getName() { return name; }
来源：http://dali.xylfe.cn/Article/details/gtvhagbflx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gtlfnaxbyo.html

Ruby: attr_accessor :name
来源：http://dali.jinqigufen.top/Article/details/gtdlzshxzj.html

C#:   public string Name { get; set; }
来源：http://dali.jqgufenzy.top/Article/details/gtdcoqufdy.html

[G12] 对象转字符串
来源：http://dali.jinqigfzy.top/Article/details/gtdejyxvwd.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgufenzy.top/Article/details/gtqlucuiqj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtesndjulh.html

JS:   toString() { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtbjzdnezk.html

TS:   toString(): string { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtoqeongie.html

Java: @Override public String toString() { return name; }
来源：http://dali.fengsongda.top/Article/details/gtydtafswt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gtjlzqxgph.html

Ruby: def to_s; @name; end
来源：http://dali.feifeiyinyue.top/Article/details/gtlqwldaud.html

C#:   public override string ToString() => Name;
来源：http://dali.cucudq.cn/Article/details/gtlgagvlre.html

[G13] 判断对象类型
来源：http://dali.gaohongyu789.top/Article/details/gtdhsywvsp.html

Py:   isinstance(u, User)
来源：http://dali.jqgfzy.top/Article/details/gtugnynjdr.html

PHP:  $u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gtmkgjycli.html

JS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtchwbudys.html

TS:   u instanceof User
来源：http://dali.yj20258.top/Article/details/gtdgsmsgvi.html

Java: u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gthdjhpdrm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuetiantiany.cn/Article/details/gttlgeekny.html

Ruby: u.is_a?(User)
来源：http://dali.xylfe.cn/Article/details/gtqbqrkfpr.html

C#:   u is User
来源：http://dali.hnqzz.top/Article/details/gtibgjlfdz.html

[G14] 数据类 / record
来源：http://dali.redwolf501.top/Article/details/gtbwfybenr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.iojbl.cn/Article/details/gtmuozsrjv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhengqikj.top/Article/details/gtyhbrwbhi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.9152youxi.cn/Article/details/gtovbnykfu.html

TS:   type User = { name: string; age: number };
来源：http://dali.yangfankeji.com/Article/details/gtiajrhela.html

Java: record User(String name, int age) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthdzxejfm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.316326.xyz/Article/details/gtzagwhtal.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pengpengdd.cyou/Article/details/gtcjnadoik.html

C#:   record User(string Name, int Age);
来源：http://dali.cdnleiting.top/Article/details/gttnfcwxkl.html

[G15] 枚举
来源：http://dali.feifeiyinyue.top/Article/details/gtiepxmbxp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.pycfn.com/Article/details/gtjxhbqcea.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtendpxusl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sxryk.cn/Article/details/gtrbqqwrlj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtvzpdye.html

Java: enum Color { RED, GREEN }
来源：http://dali.jianghu66.top/Article/details/gtfwsfhyxi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.fzhhl.top/Article/details/gtkmjywsrj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhixingplan.top/Article/details/gtuljomxxy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuanzx.com/Article/details/gtecmzvtbl.html

[G16] 对象转数组 / 字典
来源：http://dali.zhengqikj.top/Article/details/gtkvfzkrrl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guannengcc.top/Article/details/gtkuaywhos.html

PHP:  get_object_vars($obj);
来源：http://dali.nwbrower.top/Article/details/gtskatuvef.html

JS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gtxditwygq.html

TS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gtkvwhdpct.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ydzc1.top/Article/details/gtelomtoxb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.quarkkingdee.top/Article/details/gtzemhobvp.html

Ruby: obj.instance_variables
来源：http://dali.fengsongda.top/Article/details/gtjydrbbfl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenzaomai.com/Article/details/gtpzlmlarq.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gthmvtqjir.html

H. 异常与错误处理
来源：http://dali.cashguo.top/Article/details/gtefpmmkdd.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtqdarnsuc.html

[H01] try / catch 基础
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgajdasjx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shangyingyoupin.top/Article/details/gtrsxgpprd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xinyue.icu/Article/details/gtagxrniwk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gtymluoygn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gtuywnnmof.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nwbrower.top/Article/details/gtijlfyqbv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.snrcjt.cn/Article/details/gtktgxoeky.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dashuyun.cn/Article/details/gtwcxidbdt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gogol.net.cn/Article/details/gtseobaiwa.html

[H02] finally / ensure 收尾
来源：http://dali.cdnleiting.top/Article/details/gtqomonwag.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gzhubu.top/Article/details/gtvlkxrlal.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtcjuqtgqy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtmqysnnog.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtzvecczcx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtnemnfhnw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hfpthk.cn/Article/details/gtzgnetrns.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.0kj1m.cn/Article/details/gtwljmfmgg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtcqtepsxh.html

[H03] 主动抛出异常
来源：http://dali.chenlongwang.top/Article/details/gtmbpnldli.html

Py:   raise ValueError("错误信息")
来源：http://dali.xylfe.cn/Article/details/gtbqhqfoai.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtoptedqdf.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gthkzbpmpl.html

TS:   throw new Error("错误信息");
来源：http://dali.meibo888.top/Article/details/gtggagwjko.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gthvaxqzhd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.9152youxi.cn/Article/details/gtxwqebfpn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.daria6918.cn/Article/details/gtrqxxdxjv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtxryastpx.html

[H04] 自定义异常类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwxcsfprd.html

Py:   class MyError(Exception): pass
来源：http://dali.sufxvd.cn/Article/details/gtnriepsca.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.guowangkeji.top/Article/details/gtqdoyhygi.html

JS:   class MyError extends Error {}
来源：http://dali.hnxiangtu.top/Article/details/gtxedtwefl.html

TS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gttttppwbo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ehwqpu.com/Article/details/gtnjnmyaun.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.birdmap.top/Article/details/gtqquwyxws.html

Ruby: class MyError < StandardError; end
来源：http://dali.cheryme.top/Article/details/gtwrfqhwqp.html

C#:   class MyException : Exception {}
来源：http://dali.xinyue.icu/Article/details/gtimjeqxal.html

[H05] 捕获特定类型
来源：http://dali.andypj.xyz/Article/details/gtyjbfaial.html

Py:   except ValueError as e:
来源：http://dali.sysykeji.top/Article/details/gtxtvleifu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gotoacloud.top/Article/details/gtrmmretxn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajggksbl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlcomaxzx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yvedp.cn/Article/details/gtrmhlsvxn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxuanxn.top/Article/details/gtapuccilj.html

Ruby: rescue ArgumentError => e
来源：http://dali.guowangkeji.top/Article/details/gtbcdzpdqc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nwbrower.top/Article/details/gtvikyaryp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ppjwa.cn/Article/details/gtutwvzqke.html

Py:   value = d.get("k") or default
来源：http://dali.cucudq.cn/Article/details/gtmgkdagqm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zycfv.cn/Article/details/gtgssogzqk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenlongwang.top/Article/details/gtdwzduzed.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hywenlv.cn/Article/details/gthnmbqzdp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ybcxt.top/Article/details/gtipviscru.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ydzc1.top/Article/details/gtbfogjdvf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jqgfzy.top/Article/details/gtcfurpwev.html

C#:   obj?.A?.B ?? default
来源：http://dali.ydzc1.top/Article/details/gtrofrquww.html

[H07] 断言
来源：http://dali.nanxuanxn.top/Article/details/gtnfwxegsf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gaohongyu789.top/Article/details/gtewgevigw.html

PHP:  assert($x > 0);
来源：http://dali.birdmap.top/Article/details/gthzmbfrot.html

JS:   console.assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gtzykapnjs.html

TS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtkixraloa.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ivvv.top/Article/details/gthdwnzhad.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.smart0.xyz/Article/details/gtanykpwck.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.aibaodan.cn/Article/details/gtwjggcgkp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gtcqpkcyao.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinqigfzy.top/Article/details/gtogeetfbd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.smart0.xyz/Article/details/gtiirqzcij.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gzhubu.top/Article/details/gtadbgvivt.html

JS:   e.message;  e.stack
来源：http://dali.nanxuanxn.top/Article/details/gtgbgmtsru.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ppjwa.cn/Article/details/gtdanugzgo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hammf.cn/Article/details/gthbrrrsrv.html

Go:   err.Error()
来源：http://dali.zhoulong.xyz/Article/details/gtkmmwcxbg.html

Ruby: e.message;  e.backtrace
来源：http://dali.hysaishi.cn/Article/details/gtxsjkmrep.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxuanxn.top/Article/details/gtfskglwoq.html

[H09] 带错误码的异常
来源：http://dali.jinghuilouyu.cn/Article/details/gtaibcdinl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.quarkkingdee.top/Article/details/gtpaewtakx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.guannengcc.top/Article/details/gtyakxfzew.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.mhx1999.top/Article/details/gticcwxiib.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoqnlhphw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.wangshuangyany.cn/Article/details/gtfbwfqvnj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthuipndgp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yvedp.cn/Article/details/gtdyquixtp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shzxlz.cn/Article/details/gtzymykpav.html

[H10] 资源自动释放
来源：http://dali.jyoumei.cn/Article/details/gtrukvywgt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.redwolf501.top/Article/details/gtkafylwey.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cheryme.top/Article/details/gtjxpcxymw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gtkzzezjiu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuanzx.com/Article/details/gtpuzbapuj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jyoumei.cn/Article/details/gtdapqkxmt.html

Go:   defer f.Close()
来源：http://dali.yvedp.cn/Article/details/gtkpjbzfpc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xinyue.icu/Article/details/gtbrckekua.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtugzvbwho.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtotqzcdai.html

I. 正则表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gtycucfyug.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtwfvvaxvt.html

[I01] 判断是否匹配
来源：http://dali.nanxuanxn.top/Article/details/gtouzdleyd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.fengsongda.top/Article/details/gtekkjnhwx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xziqi.cn/Article/details/gtptdkvfwa.html

JS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gtkpugxpbj.html

TS:   /\d+/.test(s)
来源：http://dali.cucudq.cn/Article/details/gthmlczqpc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yanxiufei.cn/Article/details/gthbcxrkos.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yonumen.top/Article/details/gtkkhbczzf.html

Ruby: s.match?(/\d+/)
来源：http://dali.snrcjt.cn/Article/details/gtebmqupgj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hfpthk.cn/Article/details/gtjljdpshy.html

[I02] 提取所有匹配
来源：http://dali.gaohongyu789.top/Article/details/gteeljuotp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigufen.top/Article/details/gtwxsteytk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.smart0.xyz/Article/details/gtusricgtl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxuanxn.top/Article/details/gtplkujmai.html

TS:   s.match(/\d+/g)
来源：http://dali.sufxvd.cn/Article/details/gtmmehzcte.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jqgfzy.top/Article/details/gtawhkhyyq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sufxvd.cn/Article/details/gthaxqocok.html

Ruby: s.scan(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gtqlployvt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hnqzz.top/Article/details/gttkhubmoo.html

[I03] 提取捕获分组
来源：http://dali.iojbl.cn/Article/details/gthdkckbxs.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhoulong.xyz/Article/details/gtvupklgde.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yueranfly.top/Article/details/gtfgdkvsqg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jlsjyb.cn/Article/details/gtqvxvxnht.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.birdmap.top/Article/details/gtijcluuvm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zycfv.cn/Article/details/gteokiyosh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.dashuyun.cn/Article/details/gtgvmzknoh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cheryme.top/Article/details/gtlqhhkhmo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqrtvfxjs.html

[I04] 正则替换
来源：http://dali.nanxuanxn.top/Article/details/gtdvvbakro.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gotoacloud.top/Article/details/gtujfkrumn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cdnleiting.top/Article/details/gtssyocbnt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gtljhghdcm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtbsksypos.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhongyouzk.top/Article/details/gthhkgigwn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.redwolf501.top/Article/details/gtowhkulnw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ivvv.top/Article/details/gtzbjyyxwu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yonumen.top/Article/details/gtwjhlbfky.html

[I05] 按正则拆分
来源：http://dali.sysykeji.top/Article/details/gtjssrmitb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xinyue.icu/Article/details/gtxnmbnuee.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xylfe.cn/Article/details/gtxhidakxn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gtnlksxumu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gtghrnyspb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hammf.cn/Article/details/gtgjxzoctt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hfpthk.cn/Article/details/gtaovypwwv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gtnzdjxtgu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jqgufenzy.top/Article/details/gtyxrapfrq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj20258888.top/Article/details/gtjbmbzztu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gtwgeytykf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.andypj.xyz/Article/details/gtgxprhcce.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yongpay.top/Article/details/gtbpdxmfhy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejgwwqzu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenlongwang.top/Article/details/gtjtodjgzf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sweek.top/Article/details/gtbrpaszse.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.0kj1m.cn/Article/details/gtsxqrzckz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gtuwluuvvd.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhiwuduotai.top/Article/details/gtudewhfwl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shuidangran.top/Article/details/gtqixfufup.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthssnfzkf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hnqzz.top/Article/details/gtkduongin.html

TS:   /error/gim
来源：http://dali.xinyue.icu/Article/details/gtbzctpirk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnsbxrnvd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yuxming.cn/Article/details/gtppzysxlj.html

Ruby: s.scan(/error/i)
来源：http://dali.zycfv.cn/Article/details/gtdritajlo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.chenzaomai.com/Article/details/gtgrljtmxg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtjzfjcckh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.snrcjt.cn/Article/details/gtupusvwbg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gtoelumvso.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuxming.cn/Article/details/gttaxfwnxe.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.smart0.xyz/Article/details/gtfleketnr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jianghu66.top/Article/details/gtiqeftatb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tian-w.cn/Article/details/gtuvxrkcxj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.c1oappe.top/Article/details/gtiiqrzakv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gtoqxfchdz.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gttfboychb.html


<!-- 参考信息 -->