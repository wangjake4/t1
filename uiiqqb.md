代发 wailian999

C#:   public User(string name) { Name = name; }
来源：http://dali.sufxvd.cn/Article/details/gtluzpppuo.html

[G03] 实例属性
来源：http://dali.yuxming.cn/Article/details/gtatxpelgc.html

Py:   self.name = "x"
来源：http://dali.xziqi.cn/Article/details/gtlwoyrrub.html

PHP:  public string $name = "x";
来源：http://dali.hfpthk.cn/Article/details/gtjhvwldgx.html

JS:   this.name = "x";
来源：http://dali.chenlongwang.top/Article/details/gteerxdrlb.html

TS:   name: string = "x";
来源：http://dali.chenzaomai.com/Article/details/gtxouruqlf.html

Java: private String name;
来源：http://dali.pengpengdd.cyou/Article/details/gtygajpnlv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258.top/Article/details/gtmqhdfopm.html

Ruby: @name = "x"
来源：http://dali.gzhubu.top/Article/details/gtvzsfxyqz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dashuyun.cn/Article/details/gtjeonuuhk.html

[G04] 定义方法
来源：http://dali.fengsongda.top/Article/details/gtedcoekyn.html

Py:   def greet(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gttvfxpoyg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtmljtzdpq.html

JS:   greet() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjdjonhm.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtpksoaayj.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtoqthjspe.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtstooeenp.html

Ruby: def greet; @name; end
来源：http://dali.zycfv.cn/Article/details/gtdzktbfuo.html

C#:   public string Greet() => Name;
来源：http://dali.dianchejie.cn/Article/details/gtjrhetzvo.html

[G05] 继承
来源：http://dali.xinyue.icu/Article/details/gtmcdbwvlz.html

Py:   class Admin(User): pass
来源：http://dali.shuidangran.top/Article/details/gtagqtzdeh.html

PHP:  class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtepmkkbpc.html

JS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtgqaxtuio.html

TS:   class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtjrxulfbn.html

Java: class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtnbuzsdnf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.kuanghao11.cn/Article/details/gtnrszqdqa.html

Ruby: class Admin < User; end
来源：http://dali.chenlongwang.top/Article/details/gtcezzwahz.html

C#:   class Admin : User {}
来源：http://dali.sxryk.cn/Article/details/gtrljtzoux.html

[G06] 重写方法
来源：http://dali.316326.xyz/Article/details/gtsgqvxeoj.html

Py:   def greet(self): return "admin"
来源：http://dali.zhengqikj.top/Article/details/gtspcrbuhc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtgefuhavv.html

JS:   greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtukiyiubw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtopcojgza.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtodkcgnrl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shangyingyoupin.top/Article/details/gtfrirbgfe.html

Ruby: def greet; "admin"; end
来源：http://dali.haohaochexian.top/Article/details/gtiuvolech.html

C#:   public override string Greet() => "admin";
来源：http://dali.smart0.xyz/Article/details/gtxbjdmdgp.html

[G07] 调用父类方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtpkkowymg.html

Py:   super().greet()
来源：http://dali.yonumen.top/Article/details/gtclalutsu.html

PHP:  parent::greet();
来源：http://dali.aizwys.cn/Article/details/gtjsyvyctg.html

JS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gttpsvddqu.html

TS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gtafeqjhsr.html

Java: super.greet();
来源：http://dali.yonumen.top/Article/details/gtkowkdlfr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj20258.top/Article/details/gtuvneluoy.html

Ruby: super
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxisqeibh.html

C#:   base.Greet();
来源：http://dali.jqgfzy.top/Article/details/gtogdzqgtb.html

[G08] 静态方法与属性
来源：http://dali.haohaochexian.top/Article/details/gtyrydedst.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgufenzy.top/Article/details/gthnnmnocg.html

PHP:  public static function f() {}
来源：http://dali.meibo888.top/Article/details/gtepyfygyj.html

JS:   static f() {}
来源：http://dali.nanxuanxn.top/Article/details/gtxdttfmcz.html

TS:   static f(): void {}
来源：http://dali.birdmap.top/Article/details/gtlzkuetsc.html

Java: static void f() {}
来源：http://dali.xziqi.cn/Article/details/gtzbadzcrw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhoulong.xyz/Article/details/gtwiowvtrr.html

Ruby: def self.f; end
来源：http://dali.bjfxy.top/Article/details/gtktoxalpt.html

C#:   public static void F() {}
来源：http://dali.yj202588.top/Article/details/gtimdssxwp.html

[G09] 接口 / 抽象类
来源：http://dali.gaohongyu789.top/Article/details/gtfuuoxubd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shzxlz.cn/Article/details/gtgsupavgn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.vqdsnc.cn/Article/details/gtutbmbnqb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.wangshuangyany.cn/Article/details/gtmniucbsu.html

TS:   interface Shape { area(): number; }
来源：http://dali.haohaochexian.top/Article/details/gtbikgrzyz.html

Java: interface Shape { double area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtonktamlh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.andypj.xyz/Article/details/gtbyvxuybb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuetiantiany.cn/Article/details/gtqgccliim.html

C#:   interface IShape { double Area(); }
来源：http://dali.hywenlv.cn/Article/details/gticulxggd.html

[G10] 访问控制
来源：http://dali.yueranfly.top/Article/details/gtcmnhhlle.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sufxvd.cn/Article/details/gtyvcnmzzu.html

PHP:  public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gtpifkqklb.html

JS:   #private 字段；其余公开
来源：http://dali.yuanzhike.top/Article/details/gtjylnjxlc.html

TS:   public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuaxfmitf.html

Java: public / protected / private / 默认包级
来源：http://dali.guowangkeji.top/Article/details/gthrkhjwwj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.iojbl.cn/Article/details/gtklgylitc.html

Ruby: public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gtnjzcwyxg.html

C#:   public / protected / private / internal
来源：http://dali.havefunace.top/Article/details/gtnrhihwnm.html

[G11] getter / setter
来源：http://dali.cqqwz.cn/Article/details/gtsojhkuyu.html

Py:   @property 与 @x.setter
来源：http://dali.shuidangran.top/Article/details/gtjjrnkktq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gtgvygusbp.html

JS:   get name() { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gterenuljz.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj20258888.top/Article/details/gtwkqqzjow.html

Java: public String getName() { return name; }
来源：http://dali.meibo888.top/Article/details/gtytkjeshk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gtjuboghnf.html

Ruby: attr_accessor :name
来源：http://dali.ivvv.top/Article/details/gthiavhtfc.html

C#:   public string Name { get; set; }
来源：http://dali.wangdashe.top/Article/details/gtcwvfydkx.html

[G12] 对象转字符串
来源：http://dali.chenlongwang.top/Article/details/gtevgivehv.html

Py:   def __str__(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gtefgigdhk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtxebcfntn.html

JS:   toString() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtwkiwvptw.html

TS:   toString(): string { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtirxyzkms.html

Java: @Override public String toString() { return name; }
来源：http://dali.aizwys.cn/Article/details/gttloyvnuv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gtkvuefvef.html

Ruby: def to_s; @name; end
来源：http://dali.bjfxy.top/Article/details/gtwbefocoj.html

C#:   public override string ToString() => Name;
来源：http://dali.hnxiangtu.top/Article/details/gtwdkmbohc.html

[G13] 判断对象类型
来源：http://dali.nanxuanxn.top/Article/details/gtioopiazx.html

Py:   isinstance(u, User)
来源：http://dali.cashguo.top/Article/details/gtdhfwokan.html

PHP:  $u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gtrcoorijs.html

JS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtixwvwfoo.html

TS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtmxvpzzcs.html

Java: u instanceof User
来源：http://dali.tian-w.cn/Article/details/gttdxsxonl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gzhubu.top/Article/details/gtdngbemhz.html

Ruby: u.is_a?(User)
来源：http://dali.yj202588.top/Article/details/gthvvpobvm.html

C#:   u is User
来源：http://dali.xylfe.cn/Article/details/gtrtucytus.html

[G14] 数据类 / record
来源：http://dali.ybcxt.top/Article/details/gtlunujzgn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258.top/Article/details/gtgjheyfgt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.wangdashe.top/Article/details/gtenoibkpq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gzhubu.top/Article/details/gtobqsajqh.html

TS:   type User = { name: string; age: number };
来源：http://dali.yuxming.cn/Article/details/gtptcfsgyq.html

Java: record User(String name, int age) {}
来源：http://dali.yuxming.cn/Article/details/gtcvlbnlqj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ivvv.top/Article/details/gtqxmgumyl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.quarkkingdee.top/Article/details/gtjahsqiqg.html

C#:   record User(string Name, int Age);
来源：http://dali.hywenlv.cn/Article/details/gtousvufvm.html

[G15] 枚举
来源：http://dali.jinqigfzy.top/Article/details/gtggfvalzn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgfzy.top/Article/details/gtngjxmfsy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yueranfly.top/Article/details/gtcynfpcnb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jianghu66.top/Article/details/gthfurfjtw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtdysnpdyt.html

Java: enum Color { RED, GREEN }
来源：http://dali.yongpay.top/Article/details/gtvxaztrud.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.9152youxi.cn/Article/details/gtgoiqhmgv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yongpay.top/Article/details/gtmwldbcfi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtbmhloayi.html

[G16] 对象转数组 / 字典
来源：http://dali.hnqzz.top/Article/details/gtskpvcoiw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.wangshuangyany.cn/Article/details/gtnwlppkry.html

PHP:  get_object_vars($obj);
来源：http://dali.sufxvd.cn/Article/details/gtgkgoisbs.html

JS:   Object.entries(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtseattxtg.html

TS:   Object.entries(obj)
来源：http://dali.ivvv.top/Article/details/gtqiytrxyg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.haohaochexian.top/Article/details/gtmgyxlpme.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jiagoushi.top/Article/details/gtsicajqwv.html

Ruby: obj.instance_variables
来源：http://dali.yj202588.top/Article/details/gtssjsltaw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gtqknpdfpf.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtxmathacn.html

H. 异常与错误处理
来源：http://dali.cucudq.cn/Article/details/gtxeorosak.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtjwyxligu.html

[H01] try / catch 基础
来源：http://dali.pycfn.com/Article/details/gtvyzbpiia.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhixingplan.top/Article/details/gtqpudepkc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tanke756.top/Article/details/gtbqaegkvg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcwfjenwk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gtjhlzlzca.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jyoumei.cn/Article/details/gtvpqgufgb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hfpthk.cn/Article/details/gtdjisrryr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.iojbl.cn/Article/details/gtlkjsqeob.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.feifeiyinyue.top/Article/details/gtsagcjzqx.html

[H02] finally / ensure 收尾
来源：http://dali.jiagoushi.top/Article/details/gtagdxzhyf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xziqi.cn/Article/details/gtfujppcyo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtmhtffbwf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtijsnulyl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gttfjktuxv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtyniafoqi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hywenlv.cn/Article/details/gtwlacikor.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hongshengwenyu.top/Article/details/gtanjzjiox.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtearylsuf.html

[H03] 主动抛出异常
来源：http://dali.feifeiyinyue.top/Article/details/gtvkfvntuf.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxinkj.top/Article/details/gtuhyduboj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgmfolrjm.html

JS:   throw new Error("错误信息");
来源：http://dali.birdmap.top/Article/details/gtkhmwkwiw.html

TS:   throw new Error("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtmcwyvdni.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gtsgwfbmsp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jyoumei.cn/Article/details/gtfnxsjosl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gaohongyu789.top/Article/details/gtlatuhfsw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gtzukpigpt.html

[H04] 自定义异常类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydorzhey.html

Py:   class MyError(Exception): pass
来源：http://dali.dianchejie.cn/Article/details/gtrxnpuxrt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gtjnebwrvx.html

JS:   class MyError extends Error {}
来源：http://dali.hnxiangtu.top/Article/details/gtlwdisssy.html

TS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gtruywxiit.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gtazsimczd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sweek.top/Article/details/gteexpfrvv.html

Ruby: class MyError < StandardError; end
来源：http://dali.fengsongda.top/Article/details/gtwyyjucxz.html

C#:   class MyException : Exception {}
来源：http://dali.nanxinkj.top/Article/details/gteccactwa.html

[H05] 捕获特定类型
来源：http://dali.aibaodan.cn/Article/details/gtqmicemsq.html

Py:   except ValueError as e:
来源：http://dali.birdmap.top/Article/details/gtdzprmqab.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nwbrower.top/Article/details/gtytndgtld.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.iojbl.cn/Article/details/gtlxlnoabp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gtpjrbrifs.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shuidangran.top/Article/details/gtjsuwoyrj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gotoacloud.top/Article/details/gtxxcdkawf.html

Ruby: rescue ArgumentError => e
来源：http://dali.xziqi.cn/Article/details/gtmqbovlnp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.kuanghao11.cn/Article/details/gtstranvdb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yuanzhike.top/Article/details/gtdbxtbisa.html

Py:   value = d.get("k") or default
来源：http://dali.yuxming.cn/Article/details/gttpwychqx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gtqzkczsem.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gtetmycaol.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gtgirqqajm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yonumen.top/Article/details/gteophgbfq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.smart0.xyz/Article/details/gtpwedcfnp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xziqi.cn/Article/details/gthsnbxqbr.html

C#:   obj?.A?.B ?? default
来源：http://dali.jiagoushi.top/Article/details/gtbtpwpeev.html

[H07] 断言
来源：http://dali.yongpay.top/Article/details/gtehbqnedu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zdqjudy.top/Article/details/gtzeqkbqwp.html

PHP:  assert($x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtvfdogkux.html

JS:   console.assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gtobbquzhv.html

TS:   console.assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gtjetcxxck.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbgnxiqe.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ppjwa.cn/Article/details/gtgxatnsav.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.feifeiyinyue.top/Article/details/gtpsnjhkdl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gtbsxeidre.html

[H08] 获取错误信息与堆栈
来源：http://dali.nanxuanxn.top/Article/details/gtnwqrnvbu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yueranfly.top/Article/details/gtwiodjiji.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.bjfxy.top/Article/details/gtuvbretpw.html

JS:   e.message;  e.stack
来源：http://dali.zhoulong.xyz/Article/details/gtocsiddzb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbzvjzbak.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.wangshuangyany.cn/Article/details/gticfjpxjq.html

Go:   err.Error()
来源：http://dali.ydzc1.top/Article/details/gtjxhfcctw.html

Ruby: e.message;  e.backtrace
来源：http://dali.yuxming.cn/Article/details/gtsxlkkwse.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cqqwz.cn/Article/details/gtznnxnuya.html

[H09] 带错误码的异常
来源：http://dali.shangyingyoupin.top/Article/details/gtfeewluep.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jyoumei.cn/Article/details/gtobouqzkv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nanxuanxn.top/Article/details/gtpwvuvvps.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cdnleiting.top/Article/details/gtonpyymej.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shuidangran.top/Article/details/gtxevlkkni.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.feifeiyinyue.top/Article/details/gtenlzopof.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cqqwz.cn/Article/details/gtymxmfvps.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.aizwys.cn/Article/details/gtvgdzcixe.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.redwolf501.top/Article/details/gtgjenhrwa.html

[H10] 资源自动释放
来源：http://dali.vqdsnc.cn/Article/details/gtvvbkueix.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgfzy.top/Article/details/gtvmdyxzqc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ppjwa.cn/Article/details/gthetbcxql.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.redwolf501.top/Article/details/gtcyildyfb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenzaomai.com/Article/details/gtnnmfwaln.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hnqzz.top/Article/details/gtrbqerkgq.html

Go:   defer f.Close()
来源：http://dali.yongpay.top/Article/details/gtmefyzuje.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gotoacloud.top/Article/details/gtaeiwyngz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtdyaujdzd.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtaoxcpjuo.html

I. 正则表达式
来源：http://dali.ppjwa.cn/Article/details/gtjustoarn.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gthrlrnpmx.html

[I01] 判断是否匹配
来源：http://dali.shuidangran.top/Article/details/gthhcexeco.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hnqzz.top/Article/details/gtygidmtzh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ybcxt.top/Article/details/gtrkfnwzxx.html

JS:   /\d+/.test(s)
来源：http://dali.zhengqikj.top/Article/details/gtdovckaod.html

TS:   /\d+/.test(s)
来源：http://dali.nwbrower.top/Article/details/gtuscdjrzl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cheryme.top/Article/details/gtbmpuqdpj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhixingplan.top/Article/details/gtilhxiccw.html

Ruby: s.match?(/\d+/)
来源：http://dali.shuidangran.top/Article/details/gtorirrpvx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zdqjudy.top/Article/details/gtxgvojhyx.html

[I02] 提取所有匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtqiugmoig.html

Py:   re.findall(r"\d+", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtumdrgopy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ivvv.top/Article/details/gtlizayldb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.fengsongda.top/Article/details/gthjqwucdq.html

TS:   s.match(/\d+/g)
来源：http://dali.yongpay.top/Article/details/gtpgsawhoj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nanxinkj.top/Article/details/gtkpblhopv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ehwqpu.com/Article/details/gtalmkwrnx.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gtqfgnyanm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sxryk.cn/Article/details/gtikxrqzmt.html

[I03] 提取捕获分组
来源：http://dali.gotoacloud.top/Article/details/gtkdqplvhl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhongyouzk.top/Article/details/gtrcassqrf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnxiangtu.top/Article/details/gtgbfceiid.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hysaishi.cn/Article/details/gttxziymqp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.haohaochexian.top/Article/details/gtgpucemve.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.pengpengdd.cyou/Article/details/gtygmnrpig.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.dianchejie.cn/Article/details/gtwcidfyec.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gaohongyu789.top/Article/details/gtkzbfjnnf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yuxming.cn/Article/details/gtghgqohwv.html

[I04] 正则替换
来源：http://dali.cheryme.top/Article/details/gtzvwvrowl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xinyue.icu/Article/details/gttsxqafap.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sufxvd.cn/Article/details/gtaiudirfy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hysaishi.cn/Article/details/gtekdzvwki.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ydzc1.top/Article/details/gtsmnxlxzx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtezuwumtg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgjepzies.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.andypj.xyz/Article/details/gtsfbqntja.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gtippsmqlj.html

[I05] 按正则拆分
来源：http://dali.sysykeji.top/Article/details/gtexquvelq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhixingplan.top/Article/details/gtlhlgsujq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gttxrktjhh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gtpbccsqhl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gtkdwbfcjz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhiwuduotai.top/Article/details/gtmvipjshq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sweek.top/Article/details/gtwwpjuyit.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gttmlapikh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xinyue.icu/Article/details/gtzktjdywi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hysaishi.cn/Article/details/gtcbgvifjq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xuanzx.com/Article/details/gtieuorwpr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jiagoushi.top/Article/details/gtkxwrevdp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj202588.top/Article/details/gtdsppgymv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj202588.top/Article/details/gtmqaxiruv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gtrugjdeiw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yangfankeji.com/Article/details/gtaapahlka.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jqgufenzy.top/Article/details/gtxvdmhslx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gtcxgaielu.html

[I07] 忽略大小写与多行模式
来源：http://dali.ywan-chungtsiang.top/Article/details/gttygdkpva.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yuxming.cn/Article/details/gtonibjnzp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.guowangkeji.top/Article/details/gtuahaytfh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jianghu66.top/Article/details/gtecvuvhct.html

TS:   /error/gim
来源：http://dali.cashguo.top/Article/details/gtzhcuqgut.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hongshengwenyu.top/Article/details/gtmemfgtxy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.bjfxy.top/Article/details/gtjivortuo.html

Ruby: s.scan(/error/i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmcecsdm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhiwuduotai.top/Article/details/gtlurlgjuv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shuidangran.top/Article/details/gtevbuljrt.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ppjwa.cn/Article/details/gtkfsxrwga.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.fzhhl.top/Article/details/gtmdjgsnbz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gtrffgnlio.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pycfn.com/Article/details/gtyhjphvor.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gtjevkmpjn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.9152youxi.cn/Article/details/gthjoyjlhv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aibaodan.cn/Article/details/gtbgyncvbn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yangfankeji.com/Article/details/gtbylgvkoz.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gteiqpcbus.html

J. 日期与时间
来源：http://dali.nanxuanxn.top/Article/details/gtbotroirs.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtehligalj.html

[J01] 获取当前时间
来源：http://dali.yj20258888.top/Article/details/gtwvrwzkab.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ivvv.top/Article/details/gtucgcxvct.html


<!-- 参考信息 -->