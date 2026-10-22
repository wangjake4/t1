代发 wailian999

TS:   constructor(public name: string) {}
来源：http://dali.cdnleiting.top/Article/details/gtbugaghye.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gtkvgzmfqp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hfpthk.cn/Article/details/gtxzqakher.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shzxlz.cn/Article/details/gtlzqrvogt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xziqi.cn/Article/details/gtnptvfikn.html

[G03] 实例属性
来源：http://dali.tanke756.top/Article/details/gtvcqknhyn.html

Py:   self.name = "x"
来源：http://dali.yanxiufei.cn/Article/details/gtzoiyfdot.html

PHP:  public string $name = "x";
来源：http://dali.yuxming.cn/Article/details/gtrahcsuvb.html

JS:   this.name = "x";
来源：http://dali.jyoumei.cn/Article/details/gtrcswjqht.html

TS:   name: string = "x";
来源：http://dali.tian-w.cn/Article/details/gtvwdjvpuv.html

Java: private String name;
来源：http://dali.ppjwa.cn/Article/details/gtnhiifgyi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaikyyvmf.html

Ruby: @name = "x"
来源：http://dali.hywenlv.cn/Article/details/gtvywcbgyv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gogol.net.cn/Article/details/gtbindngxs.html

[G04] 定义方法
来源：http://dali.c1oappe.top/Article/details/gtuszgiwco.html

Py:   def greet(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gtklplbilc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gtkvcsxfxi.html

JS:   greet() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtzcoeoxpx.html

TS:   greet(): string { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtjyxxsgzk.html

Java: String greet() { return name; }
来源：http://dali.andypj.xyz/Article/details/gtbctkgppc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gtvxzmtqrv.html

Ruby: def greet; @name; end
来源：http://dali.gotoacloud.top/Article/details/gttjjajyae.html

C#:   public string Greet() => Name;
来源：http://dali.ydzc1.top/Article/details/gtveghtyig.html

[G05] 继承
来源：http://dali.zhongyouzk.top/Article/details/gtjqrrkobo.html

Py:   class Admin(User): pass
来源：http://dali.pengpengdd.cyou/Article/details/gtfjiyoiyv.html

PHP:  class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtofvpgjby.html

JS:   class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gtplmdvosm.html

TS:   class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtxanoayoe.html

Java: class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gthyvoavoz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.daria6918.cn/Article/details/gtadbtlrnr.html

Ruby: class Admin < User; end
来源：http://dali.zycfv.cn/Article/details/gtmexxlfqf.html

C#:   class Admin : User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtfcoiqbil.html

[G06] 重写方法
来源：http://dali.zhengqikj.top/Article/details/gtesyeqkge.html

Py:   def greet(self): return "admin"
来源：http://dali.jiagoushi.top/Article/details/gtikqgrqpj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtylnplart.html

JS:   greet() { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtntehgedr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtzounqxec.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtacmzmcbo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258888.top/Article/details/gtdqehhopu.html

Ruby: def greet; "admin"; end
来源：http://dali.yueranfly.top/Article/details/gtgivlcddv.html

C#:   public override string Greet() => "admin";
来源：http://dali.yueranfly.top/Article/details/gthqxjwmuc.html

[G07] 调用父类方法
来源：http://dali.xuetiantiany.cn/Article/details/gtblkanwaa.html

Py:   super().greet()
来源：http://dali.ppjwa.cn/Article/details/gtylcepnmd.html

PHP:  parent::greet();
来源：http://dali.9152youxi.cn/Article/details/gtbamvmqok.html

JS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtoehsnhec.html

TS:   super.greet();
来源：http://dali.hfpthk.cn/Article/details/gtejavpiuu.html

Java: super.greet();
来源：http://dali.hammf.cn/Article/details/gtzsbcxyrt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yueranfly.top/Article/details/gtzvqiwzee.html

Ruby: super
来源：http://dali.jinqigfzy.top/Article/details/gtgzjkjetp.html

C#:   base.Greet();
来源：http://dali.vqdsnc.cn/Article/details/gteeolwgjj.html

[G08] 静态方法与属性
来源：http://dali.gaohongyu789.top/Article/details/gtltdsaoth.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nwbrower.top/Article/details/gtyokqpkwz.html

PHP:  public static function f() {}
来源：http://dali.hysaishi.cn/Article/details/gtsrpvhgzi.html

JS:   static f() {}
来源：http://dali.daxiang520.top/Article/details/gtehclknos.html

TS:   static f(): void {}
来源：http://dali.yonumen.top/Article/details/gtccpvccfp.html

Java: static void f() {}
来源：http://dali.xuanzx.com/Article/details/gtwjlqdizw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zycfv.cn/Article/details/gttagwkjde.html

Ruby: def self.f; end
来源：http://dali.chenlongwang.top/Article/details/gtfxxrqtzq.html

C#:   public static void F() {}
来源：http://dali.xuanzx.com/Article/details/gtuiprfsiu.html

[G09] 接口 / 抽象类
来源：http://dali.hnxiangtu.top/Article/details/gteqdstglg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yonumen.top/Article/details/gtksvtfvjd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigfzy.top/Article/details/gthsnuzrhg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.aibaodan.cn/Article/details/gtxqbzufdg.html

TS:   interface Shape { area(): number; }
来源：http://dali.smart0.xyz/Article/details/gtoigwdwdp.html

Java: interface Shape { double area(); }
来源：http://dali.fzhhl.top/Article/details/gtzfzklqsy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gaohongyu789.top/Article/details/gtiaoxmllb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sxryk.cn/Article/details/gtiruzgplv.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhoulong.xyz/Article/details/gtpoetbsvk.html

[G10] 访问控制
来源：http://dali.yuxming.cn/Article/details/gtdxutbker.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cqqwz.cn/Article/details/gthibcahko.html

PHP:  public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gtudiaacme.html

JS:   #private 字段；其余公开
来源：http://dali.pengpengdd.cyou/Article/details/gtdphmtdlg.html

TS:   public / protected / private
来源：http://dali.316326.xyz/Article/details/gtlrqtrcqn.html

Java: public / protected / private / 默认包级
来源：http://dali.andypj.xyz/Article/details/gtttyglxrv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.fengsongda.top/Article/details/gtobfiedmg.html

Ruby: public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gtrglpgmeb.html

C#:   public / protected / private / internal
来源：http://dali.wangdashe.top/Article/details/gtnqmybgnn.html

[G11] getter / setter
来源：http://dali.wangdashe.top/Article/details/gtjaayuvwg.html

Py:   @property 与 @x.setter
来源：http://dali.guowangkeji.top/Article/details/gtupnyljsf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gtbylmkzzt.html

JS:   get name() { return this._name; }
来源：http://dali.xuanzx.com/Article/details/gtvxvczlpq.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtwazukbwm.html

Java: public String getName() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrudxvtrb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gtsukuqlkx.html

Ruby: attr_accessor :name
来源：http://dali.zhongyouzk.top/Article/details/gtnqoniprt.html

C#:   public string Name { get; set; }
来源：http://dali.yuanzhike.top/Article/details/gtbpbtmyve.html

[G12] 对象转字符串
来源：http://dali.xylfe.cn/Article/details/gtbzqnxmrg.html

Py:   def __str__(self): return self.name
来源：http://dali.havefunace.top/Article/details/gtysuqdxzf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtsgxajcwg.html

JS:   toString() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwizxaqd.html

TS:   toString(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtfulftbza.html

Java: @Override public String toString() { return name; }
来源：http://dali.wangdashe.top/Article/details/gtggzcisoy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gtnfjklerw.html

Ruby: def to_s; @name; end
来源：http://dali.xylfe.cn/Article/details/gtguqrkboq.html

C#:   public override string ToString() => Name;
来源：http://dali.yangfankeji.com/Article/details/gtwfcnyqij.html

[G13] 判断对象类型
来源：http://dali.yonumen.top/Article/details/gtrbfcfmnk.html

Py:   isinstance(u, User)
来源：http://dali.kuanghao11.cn/Article/details/gtovsfdxyp.html

PHP:  $u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtupmwcsbd.html

JS:   u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtkvcwsyyt.html

TS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoiwnxnfx.html

Java: u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtftzktnna.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.svipenyu.cn/Article/details/gtnvnbngwt.html

Ruby: u.is_a?(User)
来源：http://dali.0kj1m.cn/Article/details/gtfoqgqgrt.html

C#:   u is User
来源：http://dali.xinyue.icu/Article/details/gtzqyhdbfz.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangtech.top/Article/details/gtseepbsrh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daxiang520.top/Article/details/gtbacnqfog.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gzhubu.top/Article/details/gtdtkpyyay.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuanzhike.top/Article/details/gtyohqrfjn.html

TS:   type User = { name: string; age: number };
来源：http://dali.cashguo.top/Article/details/gtzszdvpqj.html

Java: record User(String name, int age) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtzxafzwvh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhongyouzk.top/Article/details/gtdnqylcoe.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hongshengwenyu.top/Article/details/gtldjqbwak.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxinkj.top/Article/details/gtiomwlhwg.html

[G15] 枚举
来源：http://dali.redwolf501.top/Article/details/gtcwositoi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzjtesar.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhoulong.xyz/Article/details/gtryjwrdpx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.c1oappe.top/Article/details/gtukwlanjd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sxryk.cn/Article/details/gtuloifwod.html

Java: enum Color { RED, GREEN }
来源：http://dali.sysykeji.top/Article/details/gtrftjtlnx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jianghu66.top/Article/details/gthqymefqr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenlongwang.top/Article/details/gtfxeckbnw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sufxvd.cn/Article/details/gtubrwgvgm.html

[G16] 对象转数组 / 字典
来源：http://dali.zdqjudy.top/Article/details/gtmjcypeyl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daxiang520.top/Article/details/gtlzkxkczw.html

PHP:  get_object_vars($obj);
来源：http://dali.xylfe.cn/Article/details/gtfufpuxkw.html

JS:   Object.entries(obj)
来源：http://dali.daxiang520.top/Article/details/gtroigstbj.html

TS:   Object.entries(obj)
来源：http://dali.tian-w.cn/Article/details/gtwdxqlize.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hysaishi.cn/Article/details/gtgakyiyzx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinghuilouyu.cn/Article/details/gtdfjimuie.html

Ruby: obj.instance_variables
来源：http://dali.hongshengwenyu.top/Article/details/gtvmkxudma.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gtyrbyfmnf.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtxliyviim.html

H. 异常与错误处理
来源：http://dali.xinyue.icu/Article/details/gtlvncqcst.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtdibupcbf.html

[H01] try / catch 基础
来源：http://dali.yueranfly.top/Article/details/gtsykidsnu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.daria6918.cn/Article/details/gtzqwnigfl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hammf.cn/Article/details/gtvnmctvfd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gtqqkifxrr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gtrmzvybam.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.fengsongda.top/Article/details/gtzshqfuum.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hammf.cn/Article/details/gtrdrovycf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.havefunace.top/Article/details/gtfuxppfkl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sysykeji.top/Article/details/gtcwwfupgy.html

[H02] finally / ensure 收尾
来源：http://dali.cheryme.top/Article/details/gtiesnjmdm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shangyingyoupin.top/Article/details/gtzgduyyoj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtiirfsdkt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtnrkamrpu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gttnhgwoie.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtamocwrdz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sweek.top/Article/details/gtstbghlxe.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dianchejie.cn/Article/details/gtcbnzmguu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtfljtetrm.html

[H03] 主动抛出异常
来源：http://dali.dianchejie.cn/Article/details/gtikgazbsm.html

Py:   raise ValueError("错误信息")
来源：http://dali.tian-w.cn/Article/details/gtkbzyuowv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtvnlmsmwz.html

JS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtdryugtrt.html

TS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtabozdwwt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gtsysjjpbx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jlsjyb.cn/Article/details/gtfngpoltm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.0kj1m.cn/Article/details/gtlezcggcd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gtuziaesby.html

[H04] 自定义异常类型
来源：http://dali.wangshuangyany.cn/Article/details/gtrdwilklc.html

Py:   class MyError(Exception): pass
来源：http://dali.guowangkeji.top/Article/details/gtgcmevhtt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gtngegrqmt.html

JS:   class MyError extends Error {}
来源：http://dali.haohaochexian.top/Article/details/gtguizpslh.html

TS:   class MyError extends Error {}
来源：http://dali.yueranfly.top/Article/details/gtvytrltcg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gtzschugbo.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcvxozgdm.html

Ruby: class MyError < StandardError; end
来源：http://dali.fzhhl.top/Article/details/gttwltzprb.html

C#:   class MyException : Exception {}
来源：http://dali.cheryme.top/Article/details/gtwxezngtb.html

[H05] 捕获特定类型
来源：http://dali.zhengqikj.top/Article/details/gtdjfebrhm.html

Py:   except ValueError as e:
来源：http://dali.gaohongyu789.top/Article/details/gtfxwvwntc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sweek.top/Article/details/gtkhpnufxn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.birdmap.top/Article/details/gtntyeifwc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gtlgllairm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.guannengcc.top/Article/details/gtymmdjwdc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.quarkkingdee.top/Article/details/gtkbdfazfz.html

Ruby: rescue ArgumentError => e
来源：http://dali.vqdsnc.cn/Article/details/gtobqkxrug.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtbihqiwyz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hysaishi.cn/Article/details/gtvruduzxn.html

Py:   value = d.get("k") or default
来源：http://dali.dashuyun.cn/Article/details/gtbopomtzp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zdqjudy.top/Article/details/gtnnwqgsov.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuiiqmuor.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gtemhqbgpp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhixingplan.top/Article/details/gtgedoaiaa.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hnqzz.top/Article/details/gtqgckfxzh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.iojbl.cn/Article/details/gtrotmgflc.html

C#:   obj?.A?.B ?? default
来源：http://dali.tianlin.xyz/Article/details/gtqgjjzunj.html

[H07] 断言
来源：http://dali.jyoumei.cn/Article/details/gtungysmox.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gogol.net.cn/Article/details/gterbeszga.html

PHP:  assert($x > 0);
来源：http://dali.hysaishi.cn/Article/details/gttmheifad.html

JS:   console.assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtsqrqsdxm.html

TS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gtcmjypzpv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xylfe.cn/Article/details/gtxccdpmss.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gzhubu.top/Article/details/gtwoqohwal.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yanxiufei.cn/Article/details/gtnlwwtvsm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtuicnnpdg.html

[H08] 获取错误信息与堆栈
来源：http://dali.dianchejie.cn/Article/details/gtjokpcynm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.0kj1m.cn/Article/details/gtcxkpgbga.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sweek.top/Article/details/gtxjkbrdit.html

JS:   e.message;  e.stack
来源：http://dali.zdqjudy.top/Article/details/gtpkbhgppo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.andypj.xyz/Article/details/gturaiojqq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.haohaochexian.top/Article/details/gthiltiusw.html

Go:   err.Error()
来源：http://dali.redwolf501.top/Article/details/gtqpiuopki.html

Ruby: e.message;  e.backtrace
来源：http://dali.feifeiyinyue.top/Article/details/gtardppzrl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.mhx1999.top/Article/details/gtihncokal.html

[H09] 带错误码的异常
来源：http://dali.chenzaomai.com/Article/details/gtcafjatdk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shangyingyoupin.top/Article/details/gtygbhksvl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nwbrower.top/Article/details/gtxnclrtuc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigufen.top/Article/details/gtalsnllio.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj20258888.top/Article/details/gtqddjtdee.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ppjwa.cn/Article/details/gtfbwltgix.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtdxkigagc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nwbrower.top/Article/details/gtwralfglc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.aizwys.cn/Article/details/gtcxkbrted.html

[H10] 资源自动释放
来源：http://dali.sweek.top/Article/details/gtcjknjapp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.iojbl.cn/Article/details/gtcarlvzez.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ppjwa.cn/Article/details/gtdkosikbm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yueranfly.top/Article/details/gtujdxhurt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangtech.top/Article/details/gtsbsvrkmt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tianlin.xyz/Article/details/gtbfysepvp.html

Go:   defer f.Close()
来源：http://dali.yonumen.top/Article/details/gtdxrgswud.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hnxiangtu.top/Article/details/gtummlnabo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtugovjqtl.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtzahiqrgo.html

I. 正则表达式
来源：http://dali.jqgfzy.top/Article/details/gtcyshqwht.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtfrygllth.html

[I01] 判断是否匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtjaobkwnq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jiagoushi.top/Article/details/gtwazomxus.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yueranfly.top/Article/details/gtzhzcabgb.html

JS:   /\d+/.test(s)
来源：http://dali.nwbrower.top/Article/details/gtaoyvosor.html

TS:   /\d+/.test(s)
来源：http://dali.jqgufenzy.top/Article/details/gtlrbfnlyn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmrwmnzfu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.meibo888.top/Article/details/gtphsgasrl.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenlongwang.top/Article/details/gtwozfnawz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.birdmap.top/Article/details/gtloaownxv.html

[I02] 提取所有匹配
来源：http://dali.ivvv.top/Article/details/gtxboxgndf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ydzc1.top/Article/details/gtyvmyvdft.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenlongwang.top/Article/details/gtfwrdpxiw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.mhx1999.top/Article/details/gtolhlrmtc.html

TS:   s.match(/\d+/g)
来源：http://dali.hfpthk.cn/Article/details/gtqyvspskj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tanke756.top/Article/details/gtnxzsgbet.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenzaomai.com/Article/details/gtxlrheuxg.html

Ruby: s.scan(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gteigcturo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.0kj1m.cn/Article/details/gthhsrwhtj.html

[I03] 提取捕获分组
来源：http://dali.wangdashe.top/Article/details/gtypkxcgpv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gotoacloud.top/Article/details/gthmgjvxxz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnxiangtu.top/Article/details/gtzguryeff.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtqzlfltnw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtljsongqo.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuetiantiany.cn/Article/details/gtkehnxfmc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xylfe.cn/Article/details/gttpexktqn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.bjfxy.top/Article/details/gtcmotlmor.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.snrcjt.cn/Article/details/gtfcgnvtkh.html

[I04] 正则替换
来源：http://dali.yangfankeji.com/Article/details/gtaocvwiol.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.dashuyun.cn/Article/details/gtfhfykmqz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtcxbfxcdk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jyoumei.cn/Article/details/gtismfppjb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gttzjxwbvb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zycfv.cn/Article/details/gtdpzmysfn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtrhycckzc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtyfjjeltl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.guowangkeji.top/Article/details/gtgwrigrre.html

[I05] 按正则拆分
来源：http://dali.guowangkeji.top/Article/details/gtpjcrmxxp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zycfv.cn/Article/details/gtbuchcxfd.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.pycfn.com/Article/details/gtqvqqweec.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gtfbrskgjj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gtqgmakftq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.0kj1m.cn/Article/details/gtenrveuvr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj20258888.top/Article/details/gthwlexhts.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gthsqksxfk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.iojbl.cn/Article/details/gtvjmnxcsp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.wangshuangyany.cn/Article/details/gtyejtrfzd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gthhuipdjc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.0kj1m.cn/Article/details/gtzedliqmn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhongyouzk.top/Article/details/gtvszusxku.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gotoacloud.top/Article/details/gtypbglnge.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gtqzvmsvmf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.bjfxy.top/Article/details/gtoobgpquo.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.dashuyun.cn/Article/details/gtvqlnagui.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gtwtwbznbq.html

[I07] 忽略大小写与多行模式
来源：http://dali.jiagoushi.top/Article/details/gthqexonfp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhixingplan.top/Article/details/gtmwbjetdd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gtqcujtoib.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sysykeji.top/Article/details/gtpyqvcgga.html

TS:   /error/gim
来源：http://dali.9152youxi.cn/Article/details/gtpastrvly.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.9152youxi.cn/Article/details/gtxmvubklp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zdqjudy.top/Article/details/gthhlcgtlr.html

Ruby: s.scan(/error/i)
来源：http://dali.zhongyouzk.top/Article/details/gtxrbdmeil.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yuxming.cn/Article/details/gtlxulqrhr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.aizwys.cn/Article/details/gtsvoqnvvf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.birdmap.top/Article/details/gtavhezuoc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sysykeji.top/Article/details/gtbrrndwsk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.iojbl.cn/Article/details/gtnsbnvawv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tanke756.top/Article/details/gtjckvxvet.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ybcxt.top/Article/details/gtpngwrihk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yonumen.top/Article/details/gtaglrtqiw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jyoumei.cn/Article/details/gtarhzhpvq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zycfv.cn/Article/details/gtyzusasuw.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtjvrkueiy.html


<!-- 参考信息 -->