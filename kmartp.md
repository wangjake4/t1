代发 wailian999

TS:   constructor(public name: string) {}
来源：http://dali.daxiang520.top/Article/details/gtlmluzymr.html

Java: User(String name) { this.name = name; }
来源：http://dali.gogol.net.cn/Article/details/gtapmnfllu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ehwqpu.com/Article/details/gtzjurwvhm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jqgufenzy.top/Article/details/gteusxgugr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtuizbtyuk.html

[G03] 实例属性
来源：http://dali.aizwys.cn/Article/details/gtxgmatcmc.html

Py:   self.name = "x"
来源：http://dali.ydzc1.top/Article/details/gtzystaqip.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtogngdhig.html

JS:   this.name = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtqqrgyeaz.html

TS:   name: string = "x";
来源：http://dali.gotoacloud.top/Article/details/gtptrxdagu.html

Java: private String name;
来源：http://dali.c1oappe.top/Article/details/gtlleufyvw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.guowangkeji.top/Article/details/gtdveltugn.html

Ruby: @name = "x"
来源：http://dali.jinyuanbaomall.cn/Article/details/gterllnhjc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hammf.cn/Article/details/gtwvpzejfo.html

[G04] 定义方法
来源：http://dali.dashuyun.cn/Article/details/gtllxzfjri.html

Py:   def greet(self): return self.name
来源：http://dali.zhiwuduotai.top/Article/details/gtsjjixcfe.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gtpkkqbxem.html

JS:   greet() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gthiendopa.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtwnefqcdp.html

Java: String greet() { return name; }
来源：http://dali.hnqzz.top/Article/details/gtusxsguqr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gtbkkibtdk.html

Ruby: def greet; @name; end
来源：http://dali.yj202588.top/Article/details/gtbekurhwa.html

C#:   public string Greet() => Name;
来源：http://dali.guowangkeji.top/Article/details/gtwdyppaaw.html

[G05] 继承
来源：http://dali.andypj.xyz/Article/details/gtqocmglfj.html

Py:   class Admin(User): pass
来源：http://dali.yj20258.top/Article/details/gttcxraefl.html

PHP:  class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtonpdazep.html

JS:   class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gttkbhndly.html

TS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtuhuazufe.html

Java: class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtdrzewtgb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.fengsongda.top/Article/details/gtcsanfiny.html

Ruby: class Admin < User; end
来源：http://dali.daxiang520.top/Article/details/gttejnfbrn.html

C#:   class Admin : User {}
来源：http://dali.yonumen.top/Article/details/gtlgitpyhy.html

[G06] 重写方法
来源：http://dali.cqqwz.cn/Article/details/gtwumxjhvn.html

Py:   def greet(self): return "admin"
来源：http://dali.jlsjyb.cn/Article/details/gtyyhhrtaf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtkmcyrxrg.html

JS:   greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gttyjutqbz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtsqrrgufu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtwadurncw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigfzy.top/Article/details/gtdrhvqxca.html

Ruby: def greet; "admin"; end
来源：http://dali.hnqzz.top/Article/details/gtjmqkiaao.html

C#:   public override string Greet() => "admin";
来源：http://dali.sysykeji.top/Article/details/gtchjsspln.html

[G07] 调用父类方法
来源：http://dali.jqgufenzy.top/Article/details/gtnwtlkfka.html

Py:   super().greet()
来源：http://dali.jianghu66.top/Article/details/gtnzvysjdd.html

PHP:  parent::greet();
来源：http://dali.fzhhl.top/Article/details/gtlvcfvzpp.html

JS:   super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtukrruvmf.html

TS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gtxekcxakr.html

Java: super.greet();
来源：http://dali.gogol.net.cn/Article/details/gttcouuykj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqmhpegu.html

Ruby: super
来源：http://dali.yonumen.top/Article/details/gtqcrljygk.html

C#:   base.Greet();
来源：http://dali.fzhhl.top/Article/details/gtvszucyet.html

[G08] 静态方法与属性
来源：http://dali.yj20258888.top/Article/details/gtcaftfipl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cdnleiting.top/Article/details/gtqbxqoexg.html

PHP:  public static function f() {}
来源：http://dali.zhengqikj.top/Article/details/gteiqnpzdq.html

JS:   static f() {}
来源：http://dali.dianchejie.cn/Article/details/gtvzqvwtti.html

TS:   static f(): void {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsjhohuzv.html

Java: static void f() {}
来源：http://dali.hywenlv.cn/Article/details/gteujfnlav.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jqgufenzy.top/Article/details/gtfjmhzvzo.html

Ruby: def self.f; end
来源：http://dali.nanxuanxn.top/Article/details/gtfaykjkzg.html

C#:   public static void F() {}
来源：http://dali.dashuyun.cn/Article/details/gtjzfgwwax.html

[G09] 接口 / 抽象类
来源：http://dali.chenjidiqi.icu/Article/details/gtnruioazo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tianlin.xyz/Article/details/gtfegrpwzg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258.top/Article/details/gtgyeysnsk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenjidiqi.icu/Article/details/gtrqulirhm.html

TS:   interface Shape { area(): number; }
来源：http://dali.guannengcc.top/Article/details/gtezbwiqku.html

Java: interface Shape { double area(); }
来源：http://dali.hywenlv.cn/Article/details/gtgwcjsgsg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.svipenyu.cn/Article/details/gtgepponsp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guowangkeji.top/Article/details/gtvzrlqmka.html

C#:   interface IShape { double Area(); }
来源：http://dali.hammf.cn/Article/details/gtvexhenbn.html

[G10] 访问控制
来源：http://dali.daxiang520.top/Article/details/gtqwgyymqj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hysaishi.cn/Article/details/gtpwqfmrsl.html

PHP:  public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtmanvhfwj.html

JS:   #private 字段；其余公开
来源：http://dali.ybcxt.top/Article/details/gtvkzslpvz.html

TS:   public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtqxjicjxo.html

Java: public / protected / private / 默认包级
来源：http://dali.jinghuilouyu.cn/Article/details/gtjdxmtbme.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.9152youxi.cn/Article/details/gttsgkokuk.html

Ruby: public / protected / private
来源：http://dali.cheryme.top/Article/details/gtyqbqiedv.html

C#:   public / protected / private / internal
来源：http://dali.zhixingplan.top/Article/details/gtaagnugzl.html

[G11] getter / setter
来源：http://dali.hammf.cn/Article/details/gtrwnlxylx.html

Py:   @property 与 @x.setter
来源：http://dali.mhx1999.top/Article/details/gtjgugcqyc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gtzjsjdthy.html

JS:   get name() { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gtaaazmzkg.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gttwfhpbvu.html

Java: public String getName() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtacixaaly.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gthvwdddne.html

Ruby: attr_accessor :name
来源：http://dali.yonumen.top/Article/details/gthvwnjzps.html

C#:   public string Name { get; set; }
来源：http://dali.xylfe.cn/Article/details/gtlesvfhut.html

[G12] 对象转字符串
来源：http://dali.cucudq.cn/Article/details/gtpqkdikni.html

Py:   def __str__(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gtbnydbysl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtjpuhwayt.html

JS:   toString() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtqfyqfgmw.html

TS:   toString(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtuksohqwu.html

Java: @Override public String toString() { return name; }
来源：http://dali.ydzc1.top/Article/details/gtxrtfjafg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gtlskllboa.html

Ruby: def to_s; @name; end
来源：http://dali.shzxlz.cn/Article/details/gtosrtjozb.html

C#:   public override string ToString() => Name;
来源：http://dali.tanke756.top/Article/details/gtgeaaktfg.html

[G13] 判断对象类型
来源：http://dali.shuidangran.top/Article/details/gttxiuqoky.html

Py:   isinstance(u, User)
来源：http://dali.shzxlz.cn/Article/details/gtvxwkapmd.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gtuykdiegt.html

JS:   u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtshronvnp.html

TS:   u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtzztbhizc.html

Java: u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtvhaqqrfu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.wangdashe.top/Article/details/gtcniutchq.html

Ruby: u.is_a?(User)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlleucffd.html

C#:   u is User
来源：http://dali.tanke756.top/Article/details/gtmmplqacy.html

[G14] 数据类 / record
来源：http://dali.wangdashe.top/Article/details/gttdoqubrm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yangfankeji.com/Article/details/gtluzyxyqo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yueranfly.top/Article/details/gtplubbvrg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hysaishi.cn/Article/details/gtwppjhpsm.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj20258888.top/Article/details/gtbstvwkis.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gtucwamrxz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ydzc1.top/Article/details/gtivffrzsr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nanxuanxn.top/Article/details/gtkvmaukht.html

C#:   record User(string Name, int Age);
来源：http://dali.cucudq.cn/Article/details/gthtduihjk.html

[G15] 枚举
来源：http://dali.jlsjyb.cn/Article/details/gtynkmduus.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jiagoushi.top/Article/details/gtgmgrzgzb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nanxinkj.top/Article/details/gtoomabvzz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.meibo888.top/Article/details/gtauauohyt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sufxvd.cn/Article/details/gtllbtaaxc.html

Java: enum Color { RED, GREEN }
来源：http://dali.haohaochexian.top/Article/details/gtvgxkyatu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuanzhike.top/Article/details/gtfpemakzq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenzaomai.com/Article/details/gtimybznwn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gttwhxrafy.html

[G16] 对象转数组 / 字典
来源：http://dali.svipenyu.cn/Article/details/gtgenfegkr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cdnleiting.top/Article/details/gtuutfreqy.html

PHP:  get_object_vars($obj);
来源：http://dali.yuxming.cn/Article/details/gtmymerpub.html

JS:   Object.entries(obj)
来源：http://dali.hammf.cn/Article/details/gttbxyalkf.html

TS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvymhkjss.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hywenlv.cn/Article/details/gtnbvuhlfk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhongyouzk.top/Article/details/gtfrydahsb.html

Ruby: obj.instance_variables
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhoewzdf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yongpay.top/Article/details/gtxvpzpoil.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtztnnjrzv.html

H. 异常与错误处理
来源：http://dali.yanxiufei.cn/Article/details/gtysnovlyz.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtexzdltpp.html

[H01] try / catch 基础
来源：http://dali.chenjidiqi.icu/Article/details/gtecdhshum.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fzhhl.top/Article/details/gtxgoixfqt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.bjfxy.top/Article/details/gtmrfuimcr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gtezaddlon.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gtoxvriqrh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.wangdashe.top/Article/details/gtstlhukaj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xinyue.icu/Article/details/gtssnafglo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ehwqpu.com/Article/details/gtqdrjdggm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ppjwa.cn/Article/details/gturxqqynm.html

[H02] finally / ensure 收尾
来源：http://dali.wangdashe.top/Article/details/gthznweibf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.guowangkeji.top/Article/details/gtenuexmry.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtgxnfsfqf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gttcwyofbu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttakkbshk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtctrhlshz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.316326.xyz/Article/details/gtvlubexzo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgfzy.top/Article/details/gtrcyeaqey.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtkdjuhkrv.html

[H03] 主动抛出异常
来源：http://dali.zhiwuduotai.top/Article/details/gtlsfmchpo.html

Py:   raise ValueError("错误信息")
来源：http://dali.cdnleiting.top/Article/details/gtxstltalx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtjbojqcph.html

JS:   throw new Error("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtrrypmgfz.html

TS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtsjebpslw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gthrzaeczw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinqigfzy.top/Article/details/gtalhawvza.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.pycfn.com/Article/details/gtfaypywxc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gtmktmogke.html

[H04] 自定义异常类型
来源：http://dali.bjfxy.top/Article/details/gtgdrlucvs.html

Py:   class MyError(Exception): pass
来源：http://dali.xinyue.icu/Article/details/gtojatwlfx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gtayexiyex.html

JS:   class MyError extends Error {}
来源：http://dali.yongpay.top/Article/details/gtkalnpscz.html

TS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gtydqzpxtt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gtvsytryha.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.aizwys.cn/Article/details/gtzroaltqi.html

Ruby: class MyError < StandardError; end
来源：http://dali.hfpthk.cn/Article/details/gtejjcphbg.html

C#:   class MyException : Exception {}
来源：http://dali.snrcjt.cn/Article/details/gtpafmqekt.html

[H05] 捕获特定类型
来源：http://dali.jqgufenzy.top/Article/details/gtydllggrc.html

Py:   except ValueError as e:
来源：http://dali.havefunace.top/Article/details/gtbewwfodk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jqgfzy.top/Article/details/gtoldnwnro.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tanke756.top/Article/details/gtwjstwyef.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.vqdsnc.cn/Article/details/gtzluhuxaq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.birdmap.top/Article/details/gtmlgkeopp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hnqzz.top/Article/details/gtqwyztvlt.html

Ruby: rescue ArgumentError => e
来源：http://dali.hnxiangtu.top/Article/details/gtfjgwltyt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sufxvd.cn/Article/details/gtjnrnhbro.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fengsongda.top/Article/details/gtdppjsgbp.html

Py:   value = d.get("k") or default
来源：http://dali.jqgufenzy.top/Article/details/gtnwxqshvt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gthviwzoph.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.kuanghao11.cn/Article/details/gtjfukvmgh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gotoacloud.top/Article/details/gtnmgluqjl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xziqi.cn/Article/details/gteyqsptrm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jianghu66.top/Article/details/gtazcnttbm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hfpthk.cn/Article/details/gtpshjxhug.html

C#:   obj?.A?.B ?? default
来源：http://dali.meibo888.top/Article/details/gtkfsjkdui.html

[H07] 断言
来源：http://dali.hnxiangtu.top/Article/details/gtvmnjfxye.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shzxlz.cn/Article/details/gtzgftcgcr.html

PHP:  assert($x > 0);
来源：http://dali.chenzaomai.com/Article/details/gtsjomtqfx.html

JS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtvxzgloul.html

TS:   console.assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gtvlvnevfa.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jqgufenzy.top/Article/details/gthtmpqkkm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.feifeiyinyue.top/Article/details/gtbwthmvlb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.bjfxy.top/Article/details/gtdjsxeogs.html

C#:   Debug.Assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gttekbtrob.html

[H08] 获取错误信息与堆栈
来源：http://dali.tianlin.xyz/Article/details/gtzecifdhv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.quarkkingdee.top/Article/details/gtbqtaimah.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.guowangkeji.top/Article/details/gtopxjghfv.html

JS:   e.message;  e.stack
来源：http://dali.quarkkingdee.top/Article/details/gtuzyxmmmq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.feifeiyinyue.top/Article/details/gtgpdadbty.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hywenlv.cn/Article/details/gthrmjnaml.html

Go:   err.Error()
来源：http://dali.yj20258888.top/Article/details/gtnsytvuus.html

Ruby: e.message;  e.backtrace
来源：http://dali.aizwys.cn/Article/details/gtjyynbpfz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.quarkkingdee.top/Article/details/gtwrsqsvzr.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskwtyoav.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jianghu66.top/Article/details/gttjadykjo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenzaomai.com/Article/details/gttvcupzmm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhengqikj.top/Article/details/gtoyjjqadr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.pycfn.com/Article/details/gteswdtodc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sxryk.cn/Article/details/gtsuenebap.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gaohongyu789.top/Article/details/gttamlowkj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jlsjyb.cn/Article/details/gtyhemcyyo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrhgigftb.html

[H10] 资源自动释放
来源：http://dali.gotoacloud.top/Article/details/gtwboxsvgt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nanxuanxn.top/Article/details/gtqkjtzyho.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.smart0.xyz/Article/details/gtnxaeerfa.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gtlneynkba.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daria6918.cn/Article/details/gtlfzqnbyx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ywan-chungtsiang.top/Article/details/gtijwlwgav.html

Go:   defer f.Close()
来源：http://dali.fengsongda.top/Article/details/gtneradzkv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.daria6918.cn/Article/details/gtoplbghud.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtpiwqrikk.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtizjqyidh.html

I. 正则表达式
来源：http://dali.pengpengdd.cyou/Article/details/gtkdbndmcx.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtwdqxlidp.html

[I01] 判断是否匹配
来源：http://dali.ydzc1.top/Article/details/gtlgepbvaa.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ppjwa.cn/Article/details/gtippbbfyc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtjvyysdqy.html

JS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gtlooyfdvn.html

TS:   /\d+/.test(s)
来源：http://dali.cashguo.top/Article/details/gtxkhusnow.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tianlin.xyz/Article/details/gtqyiwpflz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ehwqpu.com/Article/details/gtwypgskud.html

Ruby: s.match?(/\d+/)
来源：http://dali.hammf.cn/Article/details/gtopndqquc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnqzz.top/Article/details/gtofgphrfk.html

[I02] 提取所有匹配
来源：http://dali.sxryk.cn/Article/details/gtuufjmffq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yuxming.cn/Article/details/gtccfwpwfe.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.316326.xyz/Article/details/gtqbqoldqj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttljifxrf.html

TS:   s.match(/\d+/g)
来源：http://dali.haohaochexian.top/Article/details/gtyafkrwxe.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nanxuanxn.top/Article/details/gtpvobjtpk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.bjfxy.top/Article/details/gtfjylyzjk.html

Ruby: s.scan(/\d+/)
来源：http://dali.xinyue.icu/Article/details/gtidhyaram.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtjdlruvwa.html

[I03] 提取捕获分组
来源：http://dali.tianlin.xyz/Article/details/gtqplayhhs.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.fengsongda.top/Article/details/gtymprjtvg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.svipenyu.cn/Article/details/gtunfketsg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yuxming.cn/Article/details/gtzjjiwkxv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.dianchejie.cn/Article/details/gtubbzyelp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhixingplan.top/Article/details/gtdzxqusri.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yangfankeji.com/Article/details/gthodezaxy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cqqwz.cn/Article/details/gtsugutwbr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nwbrower.top/Article/details/gtujlwucei.html

[I04] 正则替换
来源：http://dali.meibo888.top/Article/details/gtlhczbomt.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xylfe.cn/Article/details/gtkelhbwpu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yuxming.cn/Article/details/gtphlqcizu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hammf.cn/Article/details/gtxjvrfqdf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hfpthk.cn/Article/details/gtsgrrrudm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.quarkkingdee.top/Article/details/gtjvzahixp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hywenlv.cn/Article/details/gtfwdhavwl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jiagoushi.top/Article/details/gtqaxufvxm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jyoumei.cn/Article/details/gtusjnxaqx.html

[I05] 按正则拆分
来源：http://dali.cheryme.top/Article/details/gtdznqfgdp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hywenlv.cn/Article/details/gtgvzgkswj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xylfe.cn/Article/details/gtbntustyk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gtoymbauyx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gtuysddhkl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhixingplan.top/Article/details/gtxkeuzcua.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gtgquajibg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gtvecqdjtd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhiwuduotai.top/Article/details/gtybbfgoqo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.c1oappe.top/Article/details/gtugdaljkc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gtpwzovwom.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jqgufenzy.top/Article/details/gtszbmobjb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxinkj.top/Article/details/gthucuzwxp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gtrfxzpids.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gteqfpffab.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shuidangran.top/Article/details/gtzlvxloyh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gotoacloud.top/Article/details/gtdbciyiut.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gtgncknpfa.html

[I07] 忽略大小写与多行模式
来源：http://dali.tanke756.top/Article/details/gtbqteocrl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.fengsongda.top/Article/details/gtlkwtnbgm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhoulong.xyz/Article/details/gtmlbhvvmo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.fengsongda.top/Article/details/gtpssomuyn.html

TS:   /error/gim
来源：http://dali.feifeiyinyue.top/Article/details/gtqoaczpft.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvpgjbpao.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jiagoushi.top/Article/details/gtvpybhvck.html

Ruby: s.scan(/error/i)
来源：http://dali.yuxming.cn/Article/details/gtfldxgcja.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yvedp.cn/Article/details/gtczitqyyd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.0kj1m.cn/Article/details/gthbiwssjc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yonumen.top/Article/details/gtukisrzxp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hammf.cn/Article/details/gtmexsmypv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxoardjsb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cdnleiting.top/Article/details/gtqdvbbsgm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gzhubu.top/Article/details/gteftwtqfv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.bjfxy.top/Article/details/gtlpbckuib.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jiagoushi.top/Article/details/gthkmuzwis.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gtfbhqsizf.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtskjwwutk.html


<!-- 参考信息 -->