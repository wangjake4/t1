代发 wailian999

TS:   constructor(public name: string) {}
来源：http://dali.yvedp.cn/Article/details/gtnsexrnfj.html

Java: User(String name) { this.name = name; }
来源：http://dali.svipenyu.cn/Article/details/gtsckaymsw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yvedp.cn/Article/details/gtytfrecmd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhixingplan.top/Article/details/gtheiamfta.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hywenlv.cn/Article/details/gtqpqkgcng.html

[G03] 实例属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpyvjqejy.html

Py:   self.name = "x"
来源：http://dali.yuanzhike.top/Article/details/gtwqtpzmbd.html

PHP:  public string $name = "x";
来源：http://dali.nanxinkj.top/Article/details/gtfxoxbtyk.html

JS:   this.name = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtqgwuvyyy.html

TS:   name: string = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtnoxttwgr.html

Java: private String name;
来源：http://dali.c1oappe.top/Article/details/gtohtlyfxg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gotoacloud.top/Article/details/gttrinquam.html

Ruby: @name = "x"
来源：http://dali.hammf.cn/Article/details/gtbidiynha.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.fengsongda.top/Article/details/gtsytripgd.html

[G04] 定义方法
来源：http://dali.jianghu66.top/Article/details/gtcfvsxyaf.html

Py:   def greet(self): return self.name
来源：http://dali.cheryme.top/Article/details/gthkglplpy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxqdrxfgz.html

JS:   greet() { return this.name; }
来源：http://dali.sweek.top/Article/details/gtinmxarzp.html

TS:   greet(): string { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gtutztadbc.html

Java: String greet() { return name; }
来源：http://dali.andypj.xyz/Article/details/gtpvffndov.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gtwtajxnyf.html

Ruby: def greet; @name; end
来源：http://dali.hfpthk.cn/Article/details/gtpthaiadt.html

C#:   public string Greet() => Name;
来源：http://dali.xinyue.icu/Article/details/gtmykxozbb.html

[G05] 继承
来源：http://dali.xinyue.icu/Article/details/gtsegluxny.html

Py:   class Admin(User): pass
来源：http://dali.0kj1m.cn/Article/details/gtenfhsbvv.html

PHP:  class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gtmqhbeuvz.html

JS:   class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtutjrawkn.html

TS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtpepirxzi.html

Java: class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtzhcxbmqe.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xziqi.cn/Article/details/gtlnrgrznz.html

Ruby: class Admin < User; end
来源：http://dali.pycfn.com/Article/details/gtfobhwhev.html

C#:   class Admin : User {}
来源：http://dali.xuanzx.com/Article/details/gtowbafctq.html

[G06] 重写方法
来源：http://dali.chenlongwang.top/Article/details/gtnmklkmqm.html

Py:   def greet(self): return "admin"
来源：http://dali.9152youxi.cn/Article/details/gtauwkpjus.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtnaqncpoz.html

JS:   greet() { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtbprpwbcd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtcspcmura.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtminabfbe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigfzy.top/Article/details/gtmyatuzww.html

Ruby: def greet; "admin"; end
来源：http://dali.smart0.xyz/Article/details/gtcsawsuwq.html

C#:   public override string Greet() => "admin";
来源：http://dali.pycfn.com/Article/details/gtroqjwwyo.html

[G07] 调用父类方法
来源：http://dali.yj20258888.top/Article/details/gtihjqtbnh.html

Py:   super().greet()
来源：http://dali.hywenlv.cn/Article/details/gtzjubbkup.html

PHP:  parent::greet();
来源：http://dali.meibo888.top/Article/details/gtugfrozqx.html

JS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gthhwakdcl.html

TS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gtdxepzsnh.html

Java: super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtmeprvhnn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aibaodan.cn/Article/details/gtwzxjegbb.html

Ruby: super
来源：http://dali.shangyingyoupin.top/Article/details/gtahwoxkvd.html

C#:   base.Greet();
来源：http://dali.chenzaomai.com/Article/details/gtyainmdpq.html

[G08] 静态方法与属性
来源：http://dali.andypj.xyz/Article/details/gtbliktvqw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhoulong.xyz/Article/details/gtwaqaqrzd.html

PHP:  public static function f() {}
来源：http://dali.tian-w.cn/Article/details/gtyujnijso.html

JS:   static f() {}
来源：http://dali.xuanzx.com/Article/details/gteguezklk.html

TS:   static f(): void {}
来源：http://dali.guannengcc.top/Article/details/gtparvtchl.html

Java: static void f() {}
来源：http://dali.cqqwz.cn/Article/details/gtiwusloap.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenzaomai.com/Article/details/gteyiauzcf.html

Ruby: def self.f; end
来源：http://dali.birdmap.top/Article/details/gtniebibyh.html

C#:   public static void F() {}
来源：http://dali.vqdsnc.cn/Article/details/gtyjbtihtw.html

[G09] 接口 / 抽象类
来源：http://dali.wangshuangyany.cn/Article/details/gtkunpgwgs.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.havefunace.top/Article/details/gtekgonamt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gzhubu.top/Article/details/gtxdutroqy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbpwqkfd.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gtzbahzycr.html

Java: interface Shape { double area(); }
来源：http://dali.shuidangran.top/Article/details/gtpqqkpytt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gaohongyu789.top/Article/details/gtbwunqqns.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtencvdrkj.html

C#:   interface IShape { double Area(); }
来源：http://dali.xuanzx.com/Article/details/gtzferdonl.html

[G10] 访问控制
来源：http://dali.xziqi.cn/Article/details/gtocgxoqlc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuxming.cn/Article/details/gtclbahdba.html

PHP:  public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gtaqqrmyfr.html

JS:   #private 字段；其余公开
来源：http://dali.hnxiangtu.top/Article/details/gtkzvkfibi.html

TS:   public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gtqjyzsqsk.html

Java: public / protected / private / 默认包级
来源：http://dali.haohaochexian.top/Article/details/gtocwkfavr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aizwys.cn/Article/details/gtytcdhswi.html

Ruby: public / protected / private
来源：http://dali.andypj.xyz/Article/details/gtfanokxmf.html

C#:   public / protected / private / internal
来源：http://dali.aizwys.cn/Article/details/gtcikvglby.html

[G11] getter / setter
来源：http://dali.pengpengdd.cyou/Article/details/gtxaclipyk.html

Py:   @property 与 @x.setter
来源：http://dali.havefunace.top/Article/details/gtznsxrxdp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gtbysekpsh.html

JS:   get name() { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gtvtikqfkl.html

TS:   get name(): string { return this._name; }
来源：http://dali.0kj1m.cn/Article/details/gtdkprcqgr.html

Java: public String getName() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtuofjpuud.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtfkpzvvjb.html

Ruby: attr_accessor :name
来源：http://dali.9152youxi.cn/Article/details/gtesbzslee.html

C#:   public string Name { get; set; }
来源：http://dali.316326.xyz/Article/details/gtccocmyrm.html

[G12] 对象转字符串
来源：http://dali.wangdashe.top/Article/details/gtnjhpmocl.html

Py:   def __str__(self): return self.name
来源：http://dali.jianghu66.top/Article/details/gtkydlinxp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gtmvecrgbk.html

JS:   toString() { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtwzflrumd.html

TS:   toString(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtyrvniurd.html

Java: @Override public String toString() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtqvxoptps.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtoxhucfln.html

Ruby: def to_s; @name; end
来源：http://dali.hfpthk.cn/Article/details/gtemwnhuom.html

C#:   public override string ToString() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gtoutzuphj.html

[G13] 判断对象类型
来源：http://dali.fengsongda.top/Article/details/gtuvftwfms.html

Py:   isinstance(u, User)
来源：http://dali.chenjidiqi.icu/Article/details/gthvtuinmj.html

PHP:  $u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtvcpscpjy.html

JS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtubyoyoug.html

TS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtsjsyxsgk.html

Java: u instanceof User
来源：http://dali.meibo888.top/Article/details/gtbiqvqetl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.quarkkingdee.top/Article/details/gtkqaxxzmm.html

Ruby: u.is_a?(User)
来源：http://dali.tianlin.xyz/Article/details/gthasqzhhz.html

C#:   u is User
来源：http://dali.zhengqikj.top/Article/details/gttplnunee.html

[G14] 数据类 / record
来源：http://dali.yueranfly.top/Article/details/gtzxbtjmqh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ppjwa.cn/Article/details/gtpeopigyb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuetiantiany.cn/Article/details/gtndnsgbct.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgfzy.top/Article/details/gttgfjejkq.html

TS:   type User = { name: string; age: number };
来源：http://dali.redwolf501.top/Article/details/gtuuhjegyz.html

Java: record User(String name, int age) {}
来源：http://dali.ybcxt.top/Article/details/gtlgwqsmlr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.daxiang520.top/Article/details/gtoldzmryv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj20258888.top/Article/details/gtievxbjit.html

C#:   record User(string Name, int Age);
来源：http://dali.cheryme.top/Article/details/gtjcoggvvk.html

[G15] 枚举
来源：http://dali.birdmap.top/Article/details/gtfneoqzbv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangdashe.top/Article/details/gtzfsgttlf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtzjkowcht.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nwbrower.top/Article/details/gtauxpznne.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.9152youxi.cn/Article/details/gtzpccrwhk.html

Java: enum Color { RED, GREEN }
来源：http://dali.jqgfzy.top/Article/details/gtkvkdthmx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenzaomai.com/Article/details/gtsakaaluw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.dashuyun.cn/Article/details/gtvgaofnld.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gtvhyszupa.html

[G16] 对象转数组 / 字典
来源：http://dali.sufxvd.cn/Article/details/gtsvnspzpx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258.top/Article/details/gtxlxmamkw.html

PHP:  get_object_vars($obj);
来源：http://dali.iojbl.cn/Article/details/gtwoubpfif.html

JS:   Object.entries(obj)
来源：http://dali.jiagoushi.top/Article/details/gtweunavem.html

TS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gtupifkbcg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fzhhl.top/Article/details/gtyavdxjai.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cucudq.cn/Article/details/gtksluzkow.html

Ruby: obj.instance_variables
来源：http://dali.ppjwa.cn/Article/details/gtlmjdaxmf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cashguo.top/Article/details/gttiddqgrq.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtveddrzev.html

H. 异常与错误处理
来源：http://dali.ybcxt.top/Article/details/gtvbzghebz.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtebbmicys.html

[H01] try / catch 基础
来源：http://dali.yangfankeji.com/Article/details/gtangkdewc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hysaishi.cn/Article/details/gtvsxqmawg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xylfe.cn/Article/details/gtrblaybax.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gtjfmmbmem.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xylfe.cn/Article/details/gtgmfvvtqm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.0kj1m.cn/Article/details/gtqxcfhjjv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gogol.net.cn/Article/details/gtauiorfmj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.meibo888.top/Article/details/gtcnhsgwrg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigfzy.top/Article/details/gtqipxqwok.html

[H02] finally / ensure 收尾
来源：http://dali.guannengcc.top/Article/details/gtonhhfzyl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.aibaodan.cn/Article/details/gtiggfatrx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtzidulyvs.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpzqqceux.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtxiayesph.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtvgqcnwei.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hywenlv.cn/Article/details/gtguidxekx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.0kj1m.cn/Article/details/gttcaorsdf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtlnurfgfo.html

[H03] 主动抛出异常
来源：http://dali.yangfankeji.com/Article/details/gtrofyrerq.html

Py:   raise ValueError("错误信息")
来源：http://dali.iojbl.cn/Article/details/gtmwkeaxcd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtqjncvdhz.html

JS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtjprtfhoc.html

TS:   throw new Error("错误信息");
来源：http://dali.yueranfly.top/Article/details/gttqnuscqt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjwatupyb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cashguo.top/Article/details/gtexobvtay.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.fengsongda.top/Article/details/gtmqmlfmjk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtucmondmf.html

[H04] 自定义异常类型
来源：http://dali.hnxiangtu.top/Article/details/gttfrdwozh.html

Py:   class MyError(Exception): pass
来源：http://dali.nwbrower.top/Article/details/gtlecjwtdc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dianchejie.cn/Article/details/gtuipcglcm.html

JS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gtbcklfhmc.html

TS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gtdhduwrop.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hnxiangtu.top/Article/details/gtkerdaepl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyteoyrrs.html

Ruby: class MyError < StandardError; end
来源：http://dali.yvedp.cn/Article/details/gtrjiyntyt.html

C#:   class MyException : Exception {}
来源：http://dali.aizwys.cn/Article/details/gtonplmysh.html

[H05] 捕获特定类型
来源：http://dali.jlsjyb.cn/Article/details/gtjqzjhfvg.html

Py:   except ValueError as e:
来源：http://dali.yj20258888.top/Article/details/gtwywornjs.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hysaishi.cn/Article/details/gttjzwrgal.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hnqzz.top/Article/details/gtavjhlsyh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhoulong.xyz/Article/details/gtvhlvtrjy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jqgufenzy.top/Article/details/gtazweawrc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.feifeiyinyue.top/Article/details/gtevixlqkj.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinghuilouyu.cn/Article/details/gtnyvtwzmv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.iojbl.cn/Article/details/gtouirzyow.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxuanxn.top/Article/details/gtffssazvy.html

Py:   value = d.get("k") or default
来源：http://dali.yuanzhike.top/Article/details/gtdfhkazis.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gtmjkhchji.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gtoolryqvq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xziqi.cn/Article/details/gtsisuvzmx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangshuangyany.cn/Article/details/gtdoljshkb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhiwuduotai.top/Article/details/gtofnpircs.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nwbrower.top/Article/details/gtfmewljkn.html

C#:   obj?.A?.B ?? default
来源：http://dali.daria6918.cn/Article/details/gtbnwimmlj.html

[H07] 断言
来源：http://dali.chenzaomai.com/Article/details/gtgknyzsmi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpeyrynvs.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxctkpudh.html

JS:   console.assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gtxiwoefiv.html

TS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtzsflqjoo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sysykeji.top/Article/details/gthpjffvln.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pycfn.com/Article/details/gtkwlljaua.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.havefunace.top/Article/details/gtwlczirsw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gtnajeiwso.html

[H08] 获取错误信息与堆栈
来源：http://dali.tianlin.xyz/Article/details/gtfhodotak.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.pengpengdd.cyou/Article/details/gtkezhixzs.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yonumen.top/Article/details/gtxvsecsom.html

JS:   e.message;  e.stack
来源：http://dali.hongshengwenyu.top/Article/details/gtfjxgityn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbvuoulc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hywenlv.cn/Article/details/gtsbqtrecg.html

Go:   err.Error()
来源：http://dali.nanxinkj.top/Article/details/gthfxxcfdv.html

Ruby: e.message;  e.backtrace
来源：http://dali.hfpthk.cn/Article/details/gtnqutanso.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhoulong.xyz/Article/details/gttlwknekn.html

[H09] 带错误码的异常
来源：http://dali.andypj.xyz/Article/details/gtlnpwzrwi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shanyushiyangtech.top/Article/details/gtbchurwmx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.smart0.xyz/Article/details/gtlxdfvnmg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hfpthk.cn/Article/details/gtuvromxom.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ehwqpu.com/Article/details/gttwvhlxea.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.aibaodan.cn/Article/details/gtwqzppnhz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gtabtyimkp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.9152youxi.cn/Article/details/gtjisxlrvs.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hfpthk.cn/Article/details/gttrsojgbg.html

[H10] 资源自动释放
来源：http://dali.hongshengwenyu.top/Article/details/gtkhvyfave.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zdqjudy.top/Article/details/gtnoikwctl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nwbrower.top/Article/details/gtkohhstlh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pycfn.com/Article/details/gtpzorplmo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gotoacloud.top/Article/details/gtimlhdnta.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.pycfn.com/Article/details/gtouczshzm.html

Go:   defer f.Close()
来源：http://dali.cucudq.cn/Article/details/gthsfupgxd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.iojbl.cn/Article/details/gtrywzccnu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtsnmfsnwh.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtblxswhgc.html

I. 正则表达式
来源：http://dali.hnxiangtu.top/Article/details/gtnfjghkoh.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtctwxuixt.html

[I01] 判断是否匹配
来源：http://dali.ehwqpu.com/Article/details/gtdzlteomd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhiwuduotai.top/Article/details/gtzoaslgqa.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtdvcxpvdn.html

JS:   /\d+/.test(s)
来源：http://dali.yj202588.top/Article/details/gthdhnuocg.html

TS:   /\d+/.test(s)
来源：http://dali.vqdsnc.cn/Article/details/gtyvodrzyn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nanxuanxn.top/Article/details/gtmrucaffy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthhxgkaet.html

Ruby: s.match?(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gtnmacdqud.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.daria6918.cn/Article/details/gtahmhyksz.html

[I02] 提取所有匹配
来源：http://dali.yj20258.top/Article/details/gtbfylttbs.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gtogepdudi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.guannengcc.top/Article/details/gtlydzijfb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxuanxn.top/Article/details/gtulzmtlrt.html

TS:   s.match(/\d+/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhxpdzvh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ivvv.top/Article/details/gtrohlhgau.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cqqwz.cn/Article/details/gttrhjqdzj.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gtyapwbnzc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtfpwqhndm.html

[I03] 提取捕获分组
来源：http://dali.jlsjyb.cn/Article/details/gtczeqvbwf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hammf.cn/Article/details/gtkxcxwsqf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shuidangran.top/Article/details/gtjpglqlky.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hammf.cn/Article/details/gtpekdzqzb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gotoacloud.top/Article/details/gtgnunjffj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cheryme.top/Article/details/gtfioyfgkz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gtadvehzji.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhengqikj.top/Article/details/gtdnlfyrzl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xylfe.cn/Article/details/gtvgrkkild.html

[I04] 正则替换
来源：http://dali.hywenlv.cn/Article/details/gtkvzcfzzr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xziqi.cn/Article/details/gtinlmsdqx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xziqi.cn/Article/details/gtfaopolof.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.redwolf501.top/Article/details/gtyjxrnuvs.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsxgctmno.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.0kj1m.cn/Article/details/gtjampbokp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shuidangran.top/Article/details/gtarinjjdu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.wangdashe.top/Article/details/gtuwihxdwa.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sxryk.cn/Article/details/gtybnxrvmu.html

[I05] 按正则拆分
来源：http://dali.haohaochexian.top/Article/details/gtjhthzyue.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dianchejie.cn/Article/details/gtjslnuwil.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.dianchejie.cn/Article/details/gtzqscxkjw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gtidtnoymr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gtfuylagwg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.dianchejie.cn/Article/details/gtxvpctxha.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinqigfzy.top/Article/details/gtebdlmxbr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gtccgdbyzm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.guannengcc.top/Article/details/gtskkqylvx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.fzhhl.top/Article/details/gtvpufevpk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvjqihxkd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvdmtcbz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gtoljyjqqc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.havefunace.top/Article/details/gttuxqwngo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gtiahpnkpt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.wangshuangyany.cn/Article/details/gtwlufrbpu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gaohongyu789.top/Article/details/gtgjwuuzxh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gtmltprhlc.html

[I07] 忽略大小写与多行模式
来源：http://dali.yongpay.top/Article/details/gtfhepilgt.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gogol.net.cn/Article/details/gthsyrsqcv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cqqwz.cn/Article/details/gturoxddck.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sxryk.cn/Article/details/gtpnbqjjnj.html

TS:   /error/gim
来源：http://dali.jianghu66.top/Article/details/gtxwxwprjm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sysykeji.top/Article/details/gtxqddbvur.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tian-w.cn/Article/details/gtgcatshfd.html

Ruby: s.scan(/error/i)
来源：http://dali.smart0.xyz/Article/details/gtimuhznla.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.dianchejie.cn/Article/details/gtugkzeujt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hfpthk.cn/Article/details/gtqyjhnkdr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nanxuanxn.top/Article/details/gthdkklcpx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yvedp.cn/Article/details/gtbuvmlutu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj202588.top/Article/details/gtksjhnxmn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cheryme.top/Article/details/gtvwuhxmpe.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gzhubu.top/Article/details/gtywsohdon.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cucudq.cn/Article/details/gtvjdtfkok.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgufenzy.top/Article/details/gtlbahnegy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj20258.top/Article/details/gthhxebsvw.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtuhbzbnrn.html


<!-- 参考信息 -->