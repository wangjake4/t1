代发 wailian999

TS:   constructor(public name: string) {}
来源：http://dali.yvedp.cn/Article/details/gtafmzvvuz.html

Java: User(String name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gtvesvyzbb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ydzc1.top/Article/details/gtodpeptxc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenlongwang.top/Article/details/gtddmnekit.html

C#:   public User(string name) { Name = name; }
来源：http://dali.mhx1999.top/Article/details/gtclvbfelh.html

[G03] 实例属性
来源：http://dali.shzxlz.cn/Article/details/gtnvfxigkv.html

Py:   self.name = "x"
来源：http://dali.tianlin.xyz/Article/details/gtenymaham.html

PHP:  public string $name = "x";
来源：http://dali.daxiang520.top/Article/details/gtrhatnzhj.html

JS:   this.name = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrldwgbxr.html

TS:   name: string = "x";
来源：http://dali.tian-w.cn/Article/details/gtyobpgyid.html

Java: private String name;
来源：http://dali.smart0.xyz/Article/details/gtraqbjyfy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdxybuwpx.html

Ruby: @name = "x"
来源：http://dali.chenzaomai.com/Article/details/gtozsxvttm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tanke756.top/Article/details/gtbzogkbxf.html

[G04] 定义方法
来源：http://dali.yanxiufei.cn/Article/details/gtbxicwbbi.html

Py:   def greet(self): return self.name
来源：http://dali.kuanghao11.cn/Article/details/gtiefeqngf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gtawhzwrrd.html

JS:   greet() { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtrkefzvqi.html

TS:   greet(): string { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtycjvfpta.html

Java: String greet() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtbqewbcid.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gtwqfhmuuq.html

Ruby: def greet; @name; end
来源：http://dali.0kj1m.cn/Article/details/gtwjhxkaji.html

C#:   public string Greet() => Name;
来源：http://dali.c1oappe.top/Article/details/gtxinklklx.html

[G05] 继承
来源：http://dali.shuidangran.top/Article/details/gtaxfgwgle.html

Py:   class Admin(User): pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsgwyavyh.html

PHP:  class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtgcfcfesu.html

JS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtbcipjyce.html

TS:   class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gtrqhnwiju.html

Java: class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtnyumbrue.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenlongwang.top/Article/details/gtrxpwolbs.html

Ruby: class Admin < User; end
来源：http://dali.mhx1999.top/Article/details/gtswgjvxmq.html

C#:   class Admin : User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtaqcrjick.html

[G06] 重写方法
来源：http://dali.andypj.xyz/Article/details/gtmglsizlz.html

Py:   def greet(self): return "admin"
来源：http://dali.jianghu66.top/Article/details/gtiqlzilos.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtmtevojtn.html

JS:   greet() { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtzlvtnjyj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtdzevluyr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtlxalehib.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj202588.top/Article/details/gtwzlmspge.html

Ruby: def greet; "admin"; end
来源：http://dali.chenjidiqi.icu/Article/details/gtcnoqurst.html

C#:   public override string Greet() => "admin";
来源：http://dali.yuxming.cn/Article/details/gtxuicmfts.html

[G07] 调用父类方法
来源：http://dali.ehwqpu.com/Article/details/gtordqvxsh.html

Py:   super().greet()
来源：http://dali.hongshengwenyu.top/Article/details/gteiibogvo.html

PHP:  parent::greet();
来源：http://dali.nanxuanxn.top/Article/details/gtyluxciig.html

JS:   super.greet();
来源：http://dali.ehwqpu.com/Article/details/gtogvwzcpz.html

TS:   super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtbviethnr.html

Java: super.greet();
来源：http://dali.xinyue.icu/Article/details/gtemklwhat.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.wangdashe.top/Article/details/gtezuaaddx.html

Ruby: super
来源：http://dali.tian-w.cn/Article/details/gtonwkwmpj.html

C#:   base.Greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtpxhtghyi.html

[G08] 静态方法与属性
来源：http://dali.kuanghao11.cn/Article/details/gtymecrheq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tian-w.cn/Article/details/gtepcmzyax.html

PHP:  public static function f() {}
来源：http://dali.yongpay.top/Article/details/gtvklmznaj.html

JS:   static f() {}
来源：http://dali.ivvv.top/Article/details/gtwvekboqq.html

TS:   static f(): void {}
来源：http://dali.0kj1m.cn/Article/details/gtzjuezyhm.html

Java: static void f() {}
来源：http://dali.ppjwa.cn/Article/details/gtnekitbaj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shangyingyoupin.top/Article/details/gtiqzubjht.html

Ruby: def self.f; end
来源：http://dali.chenjidiqi.icu/Article/details/gtzvmlyblx.html

C#:   public static void F() {}
来源：http://dali.aibaodan.cn/Article/details/gtarrelhgr.html

[G09] 接口 / 抽象类
来源：http://dali.xziqi.cn/Article/details/gtplpqpmje.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.mhx1999.top/Article/details/gtavovdugp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbkmgrye.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ybcxt.top/Article/details/gthfvsxcrx.html

TS:   interface Shape { area(): number; }
来源：http://dali.ivvv.top/Article/details/gtifqnnyxo.html

Java: interface Shape { double area(); }
来源：http://dali.hnxiangtu.top/Article/details/gtfmdedlwq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxcnpfgnw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jianghu66.top/Article/details/gtlayprjnd.html

C#:   interface IShape { double Area(); }
来源：http://dali.guowangkeji.top/Article/details/gtpaqfvinv.html

[G10] 访问控制
来源：http://dali.nwbrower.top/Article/details/gtfkbnbblw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ehwqpu.com/Article/details/gtgpyyiowo.html

PHP:  public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gtgneriqby.html

JS:   #private 字段；其余公开
来源：http://dali.jyoumei.cn/Article/details/gtzfofhpwx.html

TS:   public / protected / private
来源：http://dali.hammf.cn/Article/details/gtsaavkqgp.html

Java: public / protected / private / 默认包级
来源：http://dali.wangshuangyany.cn/Article/details/gtxeivqdwe.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhengqikj.top/Article/details/gtnffeaapo.html

Ruby: public / protected / private
来源：http://dali.hnqzz.top/Article/details/gtxjqxnqrp.html

C#:   public / protected / private / internal
来源：http://dali.sysykeji.top/Article/details/gtcwmwjrud.html

[G11] getter / setter
来源：http://dali.jinghuilouyu.cn/Article/details/gtzlvpixbt.html

Py:   @property 与 @x.setter
来源：http://dali.yuanzhike.top/Article/details/gtkicsioae.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtovgifmsv.html

JS:   get name() { return this._name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtirnxjyhe.html

TS:   get name(): string { return this._name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbtwivdof.html

Java: public String getName() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtlialycxz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gtzuqprgtf.html

Ruby: attr_accessor :name
来源：http://dali.hysaishi.cn/Article/details/gtquznyhfm.html

C#:   public string Name { get; set; }
来源：http://dali.smart0.xyz/Article/details/gtptgwmamu.html

[G12] 对象转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gttgpjbbrs.html

Py:   def __str__(self): return self.name
来源：http://dali.havefunace.top/Article/details/gtzolcsoei.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gtfwhahaao.html

JS:   toString() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtlwnioedm.html

TS:   toString(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtsqkeqvoq.html

Java: @Override public String toString() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtfdcnspnz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gtiqfydrji.html

Ruby: def to_s; @name; end
来源：http://dali.yuxming.cn/Article/details/gtoaesgyfw.html

C#:   public override string ToString() => Name;
来源：http://dali.zycfv.cn/Article/details/gtbqsvglsr.html

[G13] 判断对象类型
来源：http://dali.guowangkeji.top/Article/details/gtoaoqldrb.html

Py:   isinstance(u, User)
来源：http://dali.ehwqpu.com/Article/details/gtbuovhomf.html

PHP:  $u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtynyytuwp.html

JS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtzdjqeyyj.html

TS:   u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtnnyuzfpj.html

Java: u instanceof User
来源：http://dali.ydzc1.top/Article/details/gttdejgrqr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.fzhhl.top/Article/details/gtdbtbsnrf.html

Ruby: u.is_a?(User)
来源：http://dali.cqqwz.cn/Article/details/gthfqoyzss.html

C#:   u is User
来源：http://dali.c1oappe.top/Article/details/gtiahitaic.html

[G14] 数据类 / record
来源：http://dali.havefunace.top/Article/details/gtcocoxqtg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gzhubu.top/Article/details/gtgzuwffdq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aibaodan.cn/Article/details/gthtbmrqbp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hnxiangtu.top/Article/details/gtkdcuceit.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzedvbswa.html

Java: record User(String name, int age) {}
来源：http://dali.tian-w.cn/Article/details/gtqeagmsec.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhoulong.xyz/Article/details/gtjabljnkp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.iojbl.cn/Article/details/gtbtdniuks.html

C#:   record User(string Name, int Age);
来源：http://dali.bjfxy.top/Article/details/gtpvdvpyyr.html

[G15] 枚举
来源：http://dali.jiagoushi.top/Article/details/gtfewifrof.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.dashuyun.cn/Article/details/gthnmmteeu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbfojtzpr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jlsjyb.cn/Article/details/gtsiayzfse.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daria6918.cn/Article/details/gtxzjvzrwo.html

Java: enum Color { RED, GREEN }
来源：http://dali.tanke756.top/Article/details/gtwjbygcfb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.birdmap.top/Article/details/gtuejupbut.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhiwuduotai.top/Article/details/gtfzcbmnnv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtgtlbwpkr.html

[G16] 对象转数组 / 字典
来源：http://dali.xuetiantiany.cn/Article/details/gtibpwfajg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.9152youxi.cn/Article/details/gtmnvhqybg.html

PHP:  get_object_vars($obj);
来源：http://dali.sweek.top/Article/details/gtabuvstwm.html

JS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gtdhwdcgmg.html

TS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gteseycoxe.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.0kj1m.cn/Article/details/gtgdqhfjpv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jiagoushi.top/Article/details/gtolxfsmur.html

Ruby: obj.instance_variables
来源：http://dali.hysaishi.cn/Article/details/gtnjgvmyqo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xinyue.icu/Article/details/gtsbpzwhqv.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtwlkrubwk.html

H. 异常与错误处理
来源：http://dali.ehwqpu.com/Article/details/gtsgxkpezr.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gttwebetil.html

[H01] try / catch 基础
来源：http://dali.wangdashe.top/Article/details/gthreygsbp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dashuyun.cn/Article/details/gtaphrbrvp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sxryk.cn/Article/details/gtuqtvrbhq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xylfe.cn/Article/details/gtcsempoxm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gtevndihca.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tanke756.top/Article/details/gtnwqgydwd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jiagoushi.top/Article/details/gtkuaqifib.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhoulong.xyz/Article/details/gtajiiqnxy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hammf.cn/Article/details/gtclcvrkcm.html

[H02] finally / ensure 收尾
来源：http://dali.feifeiyinyue.top/Article/details/gthvodvzwd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.feifeiyinyue.top/Article/details/gtvbjvilho.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gttygureln.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtsvybxjcf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtlfnqzlfz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtcwvpnoge.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj202588.top/Article/details/gttxfuamzq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinqigufen.top/Article/details/gtbtyjtips.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtujijlbdn.html

[H03] 主动抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gtcphhrqup.html

Py:   raise ValueError("错误信息")
来源：http://dali.smart0.xyz/Article/details/gtdsyzzdbx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gttretygbd.html

JS:   throw new Error("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtcubejylf.html

TS:   throw new Error("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtqaoeitlp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtqshjuhdw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.aibaodan.cn/Article/details/gtudpceyfl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.c1oappe.top/Article/details/gtvwuhikka.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtqakrjpdw.html

[H04] 自定义异常类型
来源：http://dali.tianlin.xyz/Article/details/gtzwcdecua.html

Py:   class MyError(Exception): pass
来源：http://dali.aizwys.cn/Article/details/gtytrvftfp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.9152youxi.cn/Article/details/gthekmxvad.html

JS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gtmumwzxkr.html

TS:   class MyError extends Error {}
来源：http://dali.snrcjt.cn/Article/details/gtdumsqzho.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yangfankeji.com/Article/details/gtbxbczhau.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gotoacloud.top/Article/details/gtqwxbbjgl.html

Ruby: class MyError < StandardError; end
来源：http://dali.hnxiangtu.top/Article/details/gtkqtpgaba.html

C#:   class MyException : Exception {}
来源：http://dali.redwolf501.top/Article/details/gtrysbmnht.html

[H05] 捕获特定类型
来源：http://dali.fzhhl.top/Article/details/gtjtjzivkh.html

Py:   except ValueError as e:
来源：http://dali.sysykeji.top/Article/details/gtitmfcnud.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.wangdashe.top/Article/details/gtrnxyyfuc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yvedp.cn/Article/details/gtdhcrlmkc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gtcjbrsgqp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ivvv.top/Article/details/gtarpbrljr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.feifeiyinyue.top/Article/details/gtktgmqhlh.html

Ruby: rescue ArgumentError => e
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebqbfvly.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.c1oappe.top/Article/details/gtnxexshih.html

[H06] 可选值 / 空值安全访问
来源：http://dali.smart0.xyz/Article/details/gtmigfmnbp.html

Py:   value = d.get("k") or default
来源：http://dali.xuanzx.com/Article/details/gtnfnrzuwc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqepckewq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jianghu66.top/Article/details/gtyfjuktqf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhengqikj.top/Article/details/gtkyddmein.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.iojbl.cn/Article/details/gtrfsnvazo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhengqikj.top/Article/details/gtceuzccuz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shzxlz.cn/Article/details/gtzfbyjzrw.html

C#:   obj?.A?.B ?? default
来源：http://dali.yonumen.top/Article/details/gtqqthvizv.html

[H07] 断言
来源：http://dali.zycfv.cn/Article/details/gtpgclmwph.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shzxlz.cn/Article/details/gtpvqyfqne.html

PHP:  assert($x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtoklisuya.html

JS:   console.assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gttqazhivl.html

TS:   console.assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gtwzsuhfyj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.mhx1999.top/Article/details/gtveaqbzsu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yvedp.cn/Article/details/gtkhikrmgo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.dianchejie.cn/Article/details/gtmrawofzn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gtmhvrkjuf.html

[H08] 获取错误信息与堆栈
来源：http://dali.nanxinkj.top/Article/details/gtspyonjyu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hammf.cn/Article/details/gtejqyfwuw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.kuanghao11.cn/Article/details/gtqkximtul.html

JS:   e.message;  e.stack
来源：http://dali.jlsjyb.cn/Article/details/gtwkyystfx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aizwys.cn/Article/details/gtbucxrcbm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.pengpengdd.cyou/Article/details/gtwfxuzlfm.html

Go:   err.Error()
来源：http://dali.ydzc1.top/Article/details/gtqhlnaowe.html

Ruby: e.message;  e.backtrace
来源：http://dali.hywenlv.cn/Article/details/gtdssiwkqv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.wangshuangyany.cn/Article/details/gtsdarslqt.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzihlozpn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ehwqpu.com/Article/details/gtkrcewvap.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yvedp.cn/Article/details/gtqumuvpum.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shuidangran.top/Article/details/gtutkzjsll.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhixingplan.top/Article/details/gtmlelrsif.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.316326.xyz/Article/details/gtazbxrzmk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shuidangran.top/Article/details/gtiyowdlwn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.meibo888.top/Article/details/gtmoadtwkk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jyoumei.cn/Article/details/gtqreofhie.html

[H10] 资源自动释放
来源：http://dali.yuxming.cn/Article/details/gtkskfdmxu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.havefunace.top/Article/details/gtzuzicwak.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.birdmap.top/Article/details/gtuwuyhuvb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenlongwang.top/Article/details/gtajugtuhc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxuanxn.top/Article/details/gtvpzncloz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.iojbl.cn/Article/details/gtklrkglzv.html

Go:   defer f.Close()
来源：http://dali.bjfxy.top/Article/details/gtzyxlziky.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.feifeiyinyue.top/Article/details/gtvkypblzu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.316326.xyz/Article/details/gtwynenvju.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtyapdfdkt.html

I. 正则表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxfzjslir.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtgdpnfpep.html

[I01] 判断是否匹配
来源：http://dali.yongpay.top/Article/details/gtvrydrfxj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gtkvnspyju.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jyoumei.cn/Article/details/gtnryqjqtk.html

JS:   /\d+/.test(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtkxzzepxt.html

TS:   /\d+/.test(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtyogtkczy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nanxinkj.top/Article/details/gtdghyacpn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.dashuyun.cn/Article/details/gtaelekjeu.html

Ruby: s.match?(/\d+/)
来源：http://dali.tanke756.top/Article/details/gtfmnlwbgv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.vqdsnc.cn/Article/details/gtnynvceqe.html

[I02] 提取所有匹配
来源：http://dali.andypj.xyz/Article/details/gtaxjxwhyw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jiagoushi.top/Article/details/gtbzelwtbg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shzxlz.cn/Article/details/gtempjtgso.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gzhubu.top/Article/details/gtzrzhkuhe.html

TS:   s.match(/\d+/g)
来源：http://dali.zhixingplan.top/Article/details/gtwkxqrmqr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tianlin.xyz/Article/details/gtlkmzjrnl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sufxvd.cn/Article/details/gteiksqwlo.html

Ruby: s.scan(/\d+/)
来源：http://dali.ehwqpu.com/Article/details/gtghbqynvu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtdabhwyco.html

[I03] 提取捕获分组
来源：http://dali.chenlongwang.top/Article/details/gtpulijjru.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cashguo.top/Article/details/gthwtulapm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gogol.net.cn/Article/details/gtutvuxbup.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.svipenyu.cn/Article/details/gtvhpjqnrf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigfzy.top/Article/details/gtivzqxtna.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tianlin.xyz/Article/details/gtyihkndwu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinghuilouyu.cn/Article/details/gtmrtaurwg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ehwqpu.com/Article/details/gtuakyifmx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinqigufen.top/Article/details/gtaxhqsfqv.html

[I04] 正则替换
来源：http://dali.aizwys.cn/Article/details/gtlhpaiicv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtpoclydgi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfkfjfouf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gzhubu.top/Article/details/gtwqvzyvkr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258888.top/Article/details/gthjdtjkvz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.svipenyu.cn/Article/details/gtkkltkckh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tanke756.top/Article/details/gtezjqiffc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfmhbudj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ybcxt.top/Article/details/gtowsrqevk.html

[I05] 按正则拆分
来源：http://dali.shuidangran.top/Article/details/gtxtauxsan.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtktcjfuct.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtckjwrvzc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gtbinwipxq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gtmairvmco.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yonumen.top/Article/details/gtmsnvdmmj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.aibaodan.cn/Article/details/gtdrpoiexb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gttcfbjehu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenzaomai.com/Article/details/gtsczdsysa.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gtkmqlmdva.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gtngyuosae.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljafuelx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gtmjqrzxky.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ppjwa.cn/Article/details/gtuctzbadd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gtcknnuien.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gzhubu.top/Article/details/gtgamnoate.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.0kj1m.cn/Article/details/gtirxqhyez.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gtpdfrfmfi.html

[I07] 忽略大小写与多行模式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbppjxjw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj20258.top/Article/details/gtcvjibpqv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.daria6918.cn/Article/details/gtnlghfdnx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhengqikj.top/Article/details/gtgnglidno.html

TS:   /error/gim
来源：http://dali.chenzaomai.com/Article/details/gtyjcrghak.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.tian-w.cn/Article/details/gtmvzgadba.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.guowangkeji.top/Article/details/gtpqwgkgbl.html

Ruby: s.scan(/error/i)
来源：http://dali.iojbl.cn/Article/details/gtkyvkrnjk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhongyouzk.top/Article/details/gtqiyumjtk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jiagoushi.top/Article/details/gtrrrvqfvn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhengqikj.top/Article/details/gtcpcrzthd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hongshengwenyu.top/Article/details/gthvybqlxm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gtmzufbtzm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dashuyun.cn/Article/details/gtrmtdagvy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hywenlv.cn/Article/details/gtgitgklxj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jqgfzy.top/Article/details/gthahlljig.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ivvv.top/Article/details/gtafjlhedy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigfzy.top/Article/details/gtqrlghtup.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gteuhgfbzu.html


<!-- 参考信息 -->