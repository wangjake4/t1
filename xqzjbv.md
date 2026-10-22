代发 wailian999

Py:   class User: pass
来源：http://dali.xinyue.icu/Article/details/gtpegdqtjj.html

PHP:  class User {}
来源：http://dali.dianchejie.cn/Article/details/gtkzfixvtc.html

JS:   class User {}
来源：http://dali.jqgfzy.top/Article/details/gtbjnkbzru.html

TS:   class User { name: string = ""; }
来源：http://dali.chenzaomai.com/Article/details/gtfqlclixh.html

Java: class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtxbptsqdm.html

Go:   type User struct { Name string }
来源：http://dali.yangfankeji.com/Article/details/gttctktmtc.html

Ruby: class User; end
来源：http://dali.ybcxt.top/Article/details/gtpihbvidf.html

C#:   class User {}
来源：http://dali.cucudq.cn/Article/details/gtfgkbwesz.html

[G02] 构造函数
来源：http://dali.sxryk.cn/Article/details/gthplxasdf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yangfankeji.com/Article/details/gtpsmasamx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.9152youxi.cn/Article/details/gtzbxdkxkj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gtlftrfcro.html

TS:   constructor(public name: string) {}
来源：http://dali.jiagoushi.top/Article/details/gtbpljpjmj.html

Java: User(String name) { this.name = name; }
来源：http://dali.9152youxi.cn/Article/details/gtkvqqkrlx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hfpthk.cn/Article/details/gthrqxzgov.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yangfankeji.com/Article/details/gtqxujrpeu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258.top/Article/details/gtvsfynkrk.html

[G03] 实例属性
来源：http://dali.yj202588.top/Article/details/gtfhktaoym.html

Py:   self.name = "x"
来源：http://dali.jlsjyb.cn/Article/details/gtizlcgdao.html

PHP:  public string $name = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtdhpyjuru.html

JS:   this.name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtnrlgyrps.html

TS:   name: string = "x";
来源：http://dali.jianghu66.top/Article/details/gtfzlrhhuq.html

Java: private String name;
来源：http://dali.yueranfly.top/Article/details/gtthgyyepn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zdqjudy.top/Article/details/gtrijujccd.html

Ruby: @name = "x"
来源：http://dali.yonumen.top/Article/details/gtsuqfwbjh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.havefunace.top/Article/details/gtaelvodkt.html

[G04] 定义方法
来源：http://dali.yonumen.top/Article/details/gtfchgpyzv.html

Py:   def greet(self): return self.name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmierdxac.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtnsfutucl.html

JS:   greet() { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtsrtsodim.html

TS:   greet(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtyochuzix.html

Java: String greet() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtydiaxgmz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gtzbtizcwq.html

Ruby: def greet; @name; end
来源：http://dali.pengpengdd.cyou/Article/details/gtuipwfzqh.html

C#:   public string Greet() => Name;
来源：http://dali.zhongyouzk.top/Article/details/gtuxettvws.html

[G05] 继承
来源：http://dali.shangyingyoupin.top/Article/details/gtefdzomsx.html

Py:   class Admin(User): pass
来源：http://dali.aizwys.cn/Article/details/gtykkeevej.html

PHP:  class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtbohmkyln.html

JS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtkwblrgrh.html

TS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gttsbhcyhj.html

Java: class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbuuxqfoo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.snrcjt.cn/Article/details/gtfbpxhjus.html

Ruby: class Admin < User; end
来源：http://dali.mhx1999.top/Article/details/gtulozcyiy.html

C#:   class Admin : User {}
来源：http://dali.zhengqikj.top/Article/details/gtzwvghdjh.html

[G06] 重写方法
来源：http://dali.snrcjt.cn/Article/details/gtrzhcxdcm.html

Py:   def greet(self): return "admin"
来源：http://dali.mhx1999.top/Article/details/gtlatbunov.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtctvaigny.html

JS:   greet() { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtbiyrlbhi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtnkffgzzl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtpazhybvt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hysaishi.cn/Article/details/gtxbhaaqja.html

Ruby: def greet; "admin"; end
来源：http://dali.fzhhl.top/Article/details/gtmztzomyb.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcaiakhxr.html

[G07] 调用父类方法
来源：http://dali.shzxlz.cn/Article/details/gtlhnpkykb.html

Py:   super().greet()
来源：http://dali.0kj1m.cn/Article/details/gtoihltcqe.html

PHP:  parent::greet();
来源：http://dali.yongpay.top/Article/details/gtkmnqhktw.html

JS:   super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gtlzqzrfdd.html

TS:   super.greet();
来源：http://dali.sweek.top/Article/details/gtmwxgpigv.html

Java: super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtwnrhwnao.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj202588.top/Article/details/gtsohkotjp.html

Ruby: super
来源：http://dali.quarkkingdee.top/Article/details/gtkyjastvt.html

C#:   base.Greet();
来源：http://dali.xuanzx.com/Article/details/gtmpsdxucg.html

[G08] 静态方法与属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsywmtqmd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgufenzy.top/Article/details/gtovjrkdcs.html

PHP:  public static function f() {}
来源：http://dali.9152youxi.cn/Article/details/gtxuzfwoyz.html

JS:   static f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtfipwmyhm.html

TS:   static f(): void {}
来源：http://dali.hammf.cn/Article/details/gtcylimufz.html

Java: static void f() {}
来源：http://dali.gotoacloud.top/Article/details/gttbjtvato.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shangyingyoupin.top/Article/details/gtrkyylllx.html

Ruby: def self.f; end
来源：http://dali.zhiwuduotai.top/Article/details/gtmtdomwhv.html

C#:   public static void F() {}
来源：http://dali.jiagoushi.top/Article/details/gtkxazfots.html

[G09] 接口 / 抽象类
来源：http://dali.yuxming.cn/Article/details/gtinplcueb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daria6918.cn/Article/details/gtyrfomnmo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnqzz.top/Article/details/gtaazegmtv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hfpthk.cn/Article/details/gtdcjpzohq.html

TS:   interface Shape { area(): number; }
来源：http://dali.ppjwa.cn/Article/details/gtqhvagifu.html

Java: interface Shape { double area(); }
来源：http://dali.chenzaomai.com/Article/details/gtolkwvtzf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cashguo.top/Article/details/gtdulvfmya.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangdashe.top/Article/details/gtmuoqvaad.html

C#:   interface IShape { double Area(); }
来源：http://dali.shuidangran.top/Article/details/gtabimwvcg.html

[G10] 访问控制
来源：http://dali.shuidangran.top/Article/details/gtykcvnytl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jianghu66.top/Article/details/gtzomybyco.html

PHP:  public / protected / private
来源：http://dali.ybcxt.top/Article/details/gttfklmffs.html

JS:   #private 字段；其余公开
来源：http://dali.yongpay.top/Article/details/gtgqdteauk.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gtjhusxkeu.html

Java: public / protected / private / 默认包级
来源：http://dali.cheryme.top/Article/details/gtngujocfb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hysaishi.cn/Article/details/gtlubmxfvg.html

Ruby: public / protected / private
来源：http://dali.316326.xyz/Article/details/gtghvytltr.html

C#:   public / protected / private / internal
来源：http://dali.aibaodan.cn/Article/details/gteqwitacz.html

[G11] getter / setter
来源：http://dali.aibaodan.cn/Article/details/gtiplpfvin.html

Py:   @property 与 @x.setter
来源：http://dali.wangshuangyany.cn/Article/details/gtndlunfah.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtgpwtvemn.html

JS:   get name() { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gtfvjgstci.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gtdyvpdxxv.html

Java: public String getName() { return name; }
来源：http://dali.andypj.xyz/Article/details/gtxcecccyi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gtqgpzbztw.html

Ruby: attr_accessor :name
来源：http://dali.yonumen.top/Article/details/gtykflyudi.html

C#:   public string Name { get; set; }
来源：http://dali.wangdashe.top/Article/details/gtpoyrclhr.html

[G12] 对象转字符串
来源：http://dali.fzhhl.top/Article/details/gtbsnarzkc.html

Py:   def __str__(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gtzarjdgjn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtjkdgexsa.html

JS:   toString() { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gtgsokpmol.html

TS:   toString(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtpczsqjkd.html

Java: @Override public String toString() { return name; }
来源：http://dali.cucudq.cn/Article/details/gtxfqwxmiz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gtnnccsemg.html

Ruby: def to_s; @name; end
来源：http://dali.ppjwa.cn/Article/details/gtuedigbim.html

C#:   public override string ToString() => Name;
来源：http://dali.cashguo.top/Article/details/gtuinaanji.html

[G13] 判断对象类型
来源：http://dali.kuanghao11.cn/Article/details/gtoeycehqx.html

Py:   isinstance(u, User)
来源：http://dali.nwbrower.top/Article/details/gtoxluvdzw.html

PHP:  $u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtdvofmaxs.html

JS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtngolegcs.html

TS:   u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtwwdkjxdw.html

Java: u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtpilqgotw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jlsjyb.cn/Article/details/gtlathoyan.html

Ruby: u.is_a?(User)
来源：http://dali.jlsjyb.cn/Article/details/gtvqemmpey.html

C#:   u is User
来源：http://dali.vqdsnc.cn/Article/details/gtwwntvonx.html

[G14] 数据类 / record
来源：http://dali.xylfe.cn/Article/details/gtnjkgqsdr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinyuanbaomall.cn/Article/details/gttnmiogyu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sxryk.cn/Article/details/gtzixkuvrz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jyoumei.cn/Article/details/gterfvgves.html

TS:   type User = { name: string; age: number };
来源：http://dali.meibo888.top/Article/details/gtmktvhcyg.html

Java: record User(String name, int age) {}
来源：http://dali.hfpthk.cn/Article/details/gtljfurvtz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cheryme.top/Article/details/gtuebkspmf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.andypj.xyz/Article/details/gtrqzchmic.html

C#:   record User(string Name, int Age);
来源：http://dali.vqdsnc.cn/Article/details/gtotemkspt.html

[G15] 枚举
来源：http://dali.ybcxt.top/Article/details/gtlrhwslxq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gzhubu.top/Article/details/gtnlrdvkmv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhixingplan.top/Article/details/gtnegarxim.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.kuanghao11.cn/Article/details/gtaoozwhez.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258.top/Article/details/gtelmxfzry.html

Java: enum Color { RED, GREEN }
来源：http://dali.cashguo.top/Article/details/gtkhcvboex.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258.top/Article/details/gtxzhgeddw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ydzc1.top/Article/details/gtyzgjegoc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtstpgqghb.html

[G16] 对象转数组 / 字典
来源：http://dali.shuidangran.top/Article/details/gtiogkwtep.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.havefunace.top/Article/details/gtxqzorske.html

PHP:  get_object_vars($obj);
来源：http://dali.wangdashe.top/Article/details/gtgqsiboin.html

JS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gtlsnubepa.html

TS:   Object.entries(obj)
来源：http://dali.zhengqikj.top/Article/details/gtytkrsxsl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.pengpengdd.cyou/Article/details/gtluynjaqg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yongpay.top/Article/details/gtyztefcnl.html

Ruby: obj.instance_variables
来源：http://dali.yvedp.cn/Article/details/gtetiwfkfo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.quarkkingdee.top/Article/details/gteogrstob.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtqhtnisqd.html

H. 异常与错误处理
来源：http://dali.redwolf501.top/Article/details/gthdywvhkp.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtojizfymv.html

[H01] try / catch 基础
来源：http://dali.gzhubu.top/Article/details/gtptuxlecm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jqgufenzy.top/Article/details/gtxfeyqfcz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zdqjudy.top/Article/details/gtblejmohe.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gtmejrnfzy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jyoumei.cn/Article/details/gtfqedcnef.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zdqjudy.top/Article/details/gtaprdhokm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.guannengcc.top/Article/details/gtqiycxmmj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.andypj.xyz/Article/details/gtmwlnslxc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrzysfdcw.html

[H02] finally / ensure 收尾
来源：http://dali.ehwqpu.com/Article/details/gtookuhese.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sufxvd.cn/Article/details/gtbnwzwuaf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gthfawshue.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gteuypkwcs.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtnndidufg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtvcswvyrl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhengqikj.top/Article/details/gtsmwofazw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aizwys.cn/Article/details/gtrnxaxrmx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtqtdflalu.html

[H03] 主动抛出异常
来源：http://dali.nanxuanxn.top/Article/details/gtyoqobzhe.html

Py:   raise ValueError("错误信息")
来源：http://dali.wangshuangyany.cn/Article/details/gtjpwfuvjc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtvnizydid.html

JS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtkbesclps.html

TS:   throw new Error("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtyqnjqrnm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtmylnfzyl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhengqikj.top/Article/details/gttwzwdmjt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nanxuanxn.top/Article/details/gtzjjpumbb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtgghpyolf.html

[H04] 自定义异常类型
来源：http://dali.sweek.top/Article/details/gtgrvzwzgq.html

Py:   class MyError(Exception): pass
来源：http://dali.ydzc1.top/Article/details/gtkucuwyck.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhiwuduotai.top/Article/details/gtrmojinlg.html

JS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyhypclvj.html

TS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gtqaojixhk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gtugvolnpu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.316326.xyz/Article/details/gtuxtqtkik.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhiwuduotai.top/Article/details/gtgagdsadh.html

C#:   class MyException : Exception {}
来源：http://dali.jiagoushi.top/Article/details/gtsvsyubhj.html

[H05] 捕获特定类型
来源：http://dali.yvedp.cn/Article/details/gtjqqxgbbs.html

Py:   except ValueError as e:
来源：http://dali.xziqi.cn/Article/details/gtuwgjgkyc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cheryme.top/Article/details/gtwryboydg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gtzywzdrud.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gtziadvqeb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gzhubu.top/Article/details/gtgfaxjyja.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.haohaochexian.top/Article/details/gthximadcm.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinqigufen.top/Article/details/gtyhndfulq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.quarkkingdee.top/Article/details/gtjuaohzdr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigufen.top/Article/details/gtcnedynyr.html

Py:   value = d.get("k") or default
来源：http://dali.hfpthk.cn/Article/details/gtgqslnzyu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwgdqiwb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yanxiufei.cn/Article/details/gthtmgtzyc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guowangkeji.top/Article/details/gtixmxxxrn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cashguo.top/Article/details/gtyvpbmkjf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xylfe.cn/Article/details/gtkellmbbs.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gzhubu.top/Article/details/gtiqvuznwp.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigufen.top/Article/details/gtjokpkwtc.html

[H07] 断言
来源：http://dali.shzxlz.cn/Article/details/gtbmtstzmx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gzhubu.top/Article/details/gtwesbsvcv.html

PHP:  assert($x > 0);
来源：http://dali.xinyue.icu/Article/details/gtxvnlctvd.html

JS:   console.assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwharfeea.html

TS:   console.assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtvzxcqkdn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sweek.top/Article/details/gtqsweqcrf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nanxuanxn.top/Article/details/gttymwbfwn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.birdmap.top/Article/details/gtgznjwnry.html

C#:   Debug.Assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtcjieoraf.html

[H08] 获取错误信息与堆栈
来源：http://dali.jiagoushi.top/Article/details/gtiagyinwv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gogol.net.cn/Article/details/gtwbnycbzm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigufen.top/Article/details/gtswefzphw.html

JS:   e.message;  e.stack
来源：http://dali.meibo888.top/Article/details/gttqmooyjk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aibaodan.cn/Article/details/gtptijoxdp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.quarkkingdee.top/Article/details/gtyxxgvvuu.html

Go:   err.Error()
来源：http://dali.dianchejie.cn/Article/details/gtjsujkyfn.html

Ruby: e.message;  e.backtrace
来源：http://dali.tanke756.top/Article/details/gttqcvtker.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xziqi.cn/Article/details/gtkrlaauxg.html

[H09] 带错误码的异常
来源：http://dali.ppjwa.cn/Article/details/gtfcdtitbg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.snrcjt.cn/Article/details/gtgedecowk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ehwqpu.com/Article/details/gtxnvkfbzm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenzaomai.com/Article/details/gtbcxrionq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ivvv.top/Article/details/gtidchqrwx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xuetiantiany.cn/Article/details/gtramwdkzl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cheryme.top/Article/details/gtqlroiigf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfrknrcbv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjhqoyfac.html

[H10] 资源自动释放
来源：http://dali.svipenyu.cn/Article/details/gtsxljbhpo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sufxvd.cn/Article/details/gtzbylcvcy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zycfv.cn/Article/details/gtesriawoe.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzpkodgii.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gtdezfflky.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yanxiufei.cn/Article/details/gttmiiwkoh.html

Go:   defer f.Close()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcumwqdlc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hnqzz.top/Article/details/gtrdrouyfo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtmypvdelo.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtgmmkvfov.html

I. 正则表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gturlcorkf.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtkzrgipqu.html

[I01] 判断是否匹配
来源：http://dali.dashuyun.cn/Article/details/gthzgkzmpy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.fengsongda.top/Article/details/gtnhdyvwqk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbmknkgot.html

JS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gtszoldndu.html

TS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gtsbewqkji.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ivvv.top/Article/details/gtwwkhfier.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sysykeji.top/Article/details/gtoijertkq.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhlsqmbn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tian-w.cn/Article/details/gtgdnygbbj.html

[I02] 提取所有匹配
来源：http://dali.shuidangran.top/Article/details/gtapkspcof.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhixingplan.top/Article/details/gtflqdqjpp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hnqzz.top/Article/details/gtwblcmelz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.andypj.xyz/Article/details/gtfawtmvbf.html

TS:   s.match(/\d+/g)
来源：http://dali.hfpthk.cn/Article/details/gtpwdiquoi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cqqwz.cn/Article/details/gtbinoaaew.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xylfe.cn/Article/details/gtljnrglqn.html

Ruby: s.scan(/\d+/)
来源：http://dali.yuanzhike.top/Article/details/gtyxifvmop.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtrywwaubg.html

[I03] 提取捕获分组
来源：http://dali.yvedp.cn/Article/details/gtjevqyhvf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.andypj.xyz/Article/details/gtwbpfscma.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cqqwz.cn/Article/details/gtfnzvokhg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangdashe.top/Article/details/gtikszxunb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.guowangkeji.top/Article/details/gtchdeycup.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.quarkkingdee.top/Article/details/gtwkfrmiio.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.mhx1999.top/Article/details/gtnkmneqzt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangdashe.top/Article/details/gtyobrgmer.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ybcxt.top/Article/details/gtvjsoikjs.html

[I04] 正则替换
来源：http://dali.wangshuangyany.cn/Article/details/gtswczmvvz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.meibo888.top/Article/details/gtmivwsjtm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yvedp.cn/Article/details/gtsmvmrtuj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtykmztpfp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daria6918.cn/Article/details/gtflaynvwv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.9152youxi.cn/Article/details/gtwougaasq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.aibaodan.cn/Article/details/gtodcabolf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yuxming.cn/Article/details/gtuivelpca.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cashguo.top/Article/details/gtcaucstwt.html

[I05] 按正则拆分
来源：http://dali.ybcxt.top/Article/details/gtvsmipdxv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenzaomai.com/Article/details/gtozsfwejm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtlhbtqhtc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gtffhcgxqb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gtqjgvmeir.html

Java: s.split("\\s*,\\s*")
来源：http://dali.haohaochexian.top/Article/details/gtusgqteuf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sxryk.cn/Article/details/gtltqqjqha.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gtbpqiogqo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yueranfly.top/Article/details/gtqfsoiamc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxviybdns.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.smart0.xyz/Article/details/gthkbqleut.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.daria6918.cn/Article/details/gtihqwsvcb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.svipenyu.cn/Article/details/gttkkqguwb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtntnjqw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shuidangran.top/Article/details/gtbzqkmhke.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shuidangran.top/Article/details/gtcyltpxva.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhongyouzk.top/Article/details/gteweshfcz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gtbpbklveb.html

[I07] 忽略大小写与多行模式
来源：http://dali.jqgufenzy.top/Article/details/gtskjwtpar.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.c1oappe.top/Article/details/gtjctpqhcb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gtftqagglr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gogol.net.cn/Article/details/gtxblsbjxv.html

TS:   /error/gim
来源：http://dali.hywenlv.cn/Article/details/gtlgvdiies.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjpcqijvt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shzxlz.cn/Article/details/gtqmmnppmv.html


<!-- 参考信息 -->