代发 wailian999

[G02] 构造函数
来源：http://dali.chenlongwang.top/Article/details/gt2owzebivx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ehwqpu.com/Article/details/gt2vbauhaco.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tian-w.cn/Article/details/gt2tctwdqnd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cqqwz.cn/Article/details/gt2esivqvkj.html

TS:   constructor(public name: string) {}
来源：http://dali.0kj1m.cn/Article/details/gt2slvhoznz.html

Java: User(String name) { this.name = name; }
来源：http://dali.aibaodan.cn/Article/details/gt2sgxwakbx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jyoumei.cn/Article/details/gt2ahnhztue.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.snrcjt.cn/Article/details/gt2mgkpozhc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yonumen.top/Article/details/gt2bgxuhxnf.html

[G03] 实例属性
来源：http://dali.pengpengdd.cyou/Article/details/gt2rzhspmql.html

Py:   self.name = "x"
来源：http://dali.shzxlz.cn/Article/details/gt2tamirgau.html

PHP:  public string $name = "x";
来源：http://dali.pycfn.com/Article/details/gt2phauwmyg.html

JS:   this.name = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gt2aaymlnrm.html

TS:   name: string = "x";
来源：http://dali.jianghu66.top/Article/details/gt2zjmhnubf.html

Java: private String name;
来源：http://dali.hnxiangtu.top/Article/details/gt2sxdcbjcp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shzxlz.cn/Article/details/gt2yvykdhnw.html

Ruby: @name = "x"
来源：http://dali.sxryk.cn/Article/details/gt2ezrlkssp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guannengcc.top/Article/details/gt2zuswakxw.html

[G04] 定义方法
来源：http://dali.0kj1m.cn/Article/details/gt2rmyfolzq.html

Py:   def greet(self): return self.name
来源：http://dali.bjfxy.top/Article/details/gt2xtmqzuki.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gt2syyypqno.html

JS:   greet() { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gt2wefwkqvi.html

TS:   greet(): string { return this.name; }
来源：http://dali.yonumen.top/Article/details/gt2qnebqrsy.html

Java: String greet() { return name; }
来源：http://dali.yj20258888.top/Article/details/gt2fwfmeujs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gt2xpjierlm.html

Ruby: def greet; @name; end
来源：http://dali.redwolf501.top/Article/details/gt2qlsadpro.html

C#:   public string Greet() => Name;
来源：http://dali.wangdashe.top/Article/details/gt2qhxwdywn.html

[G05] 继承
来源：http://dali.hnqzz.top/Article/details/gt2irbaxtim.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangtech.top/Article/details/gt2btbrescl.html

PHP:  class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gt2fmabibdi.html

JS:   class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gt2xdhnnrhm.html

TS:   class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gt2ryzruqog.html

Java: class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gt2bghcenge.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hfpthk.cn/Article/details/gt2dwnmzuvs.html

Ruby: class Admin < User; end
来源：http://dali.aizwys.cn/Article/details/gt2wegrordt.html

C#:   class Admin : User {}
来源：http://dali.haohaochexian.top/Article/details/gt2pmvjlgpd.html

[G06] 重写方法
来源：http://dali.ppjwa.cn/Article/details/gt2flmnbqsg.html

Py:   def greet(self): return "admin"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2arrlrqyu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gt2rrljvxns.html

JS:   greet() { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gt2vfdfvllb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gt2wpielcic.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gt2eshmztxo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.andypj.xyz/Article/details/gt2jkwrsxmx.html

Ruby: def greet; "admin"; end
来源：http://dali.yonumen.top/Article/details/gt2yxbslrks.html

C#:   public override string Greet() => "admin";
来源：http://dali.gogol.net.cn/Article/details/gt2lalfobqf.html

[G07] 调用父类方法
来源：http://dali.zhongyouzk.top/Article/details/gt2mmzhuqxr.html

Py:   super().greet()
来源：http://dali.ppjwa.cn/Article/details/gt2jmgarlgr.html

PHP:  parent::greet();
来源：http://dali.yangfankeji.com/Article/details/gt2ywbxuujy.html

JS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gt2hofxdynu.html

TS:   super.greet();
来源：http://dali.chenlongwang.top/Article/details/gt2edihmxfv.html

Java: super.greet();
来源：http://dali.aibaodan.cn/Article/details/gt2zrrschzx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gotoacloud.top/Article/details/gt2gcppgyvf.html

Ruby: super
来源：http://dali.jinqigufen.top/Article/details/gt2azyegflz.html

C#:   base.Greet();
来源：http://dali.sufxvd.cn/Article/details/gt2egtpafmm.html

[G08] 静态方法与属性
来源：http://dali.yueranfly.top/Article/details/gt2judhblmb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yonumen.top/Article/details/gt2wuuaaeqp.html

PHP:  public static function f() {}
来源：http://dali.zhoulong.xyz/Article/details/gt2wujxuahz.html

JS:   static f() {}
来源：http://dali.xinyue.icu/Article/details/gt2czonhndc.html

TS:   static f(): void {}
来源：http://dali.chenlongwang.top/Article/details/gt2mqqrggop.html

Java: static void f() {}
来源：http://dali.fzhhl.top/Article/details/gt2nbofgcae.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gogol.net.cn/Article/details/gt2xunktghi.html

Ruby: def self.f; end
来源：http://dali.wangdashe.top/Article/details/gt2oojadlui.html

C#:   public static void F() {}
来源：http://dali.havefunace.top/Article/details/gt2lxbdzzfu.html

[G09] 接口 / 抽象类
来源：http://dali.hammf.cn/Article/details/gt2ldwvacvi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vmmigakp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ppjwa.cn/Article/details/gt2vokbkypd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.aizwys.cn/Article/details/gt2hgkudmmc.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhoulong.xyz/Article/details/gt2xyqglyvj.html

Java: interface Shape { double area(); }
来源：http://dali.nanxinkj.top/Article/details/gt2bvbzsmav.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj20258.top/Article/details/gt2rhrfsfpy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.birdmap.top/Article/details/gt2lmjzuwbz.html

C#:   interface IShape { double Area(); }
来源：http://dali.hfpthk.cn/Article/details/gt2pvnjiryu.html

[G10] 访问控制
来源：http://dali.nanxuanxn.top/Article/details/gt2bdlljurc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.bjfxy.top/Article/details/gt2ourtbhcl.html

PHP:  public / protected / private
来源：http://dali.aizwys.cn/Article/details/gt2urrgamck.html

JS:   #private 字段；其余公开
来源：http://dali.ybcxt.top/Article/details/gt2cebqgxab.html

TS:   public / protected / private
来源：http://dali.yonumen.top/Article/details/gt2wmvogamj.html

Java: public / protected / private / 默认包级
来源：http://dali.zhoulong.xyz/Article/details/gt2sqyulltu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.fengsongda.top/Article/details/gt2zacfqrpd.html

Ruby: public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gt2sozokplg.html

C#:   public / protected / private / internal
来源：http://dali.316326.xyz/Article/details/gt2mfimgmuv.html

[G11] getter / setter
来源：http://dali.c1oappe.top/Article/details/gt2zgnuhxlw.html

Py:   @property 与 @x.setter
来源：http://dali.smart0.xyz/Article/details/gt2grtkoxoj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gt2jdyodwik.html

JS:   get name() { return this._name; }
来源：http://dali.guowangkeji.top/Article/details/gt2ospzarbz.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhixingplan.top/Article/details/gt2bhckdvug.html

Java: public String getName() { return name; }
来源：http://dali.guannengcc.top/Article/details/gt2xwmvsfnm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gt2zwhkfyig.html

Ruby: attr_accessor :name
来源：http://dali.haohaochexian.top/Article/details/gt2bdbhlpry.html

C#:   public string Name { get; set; }
来源：http://dali.mhx1999.top/Article/details/gt2qlkotrtw.html

[G12] 对象转字符串
来源：http://dali.sweek.top/Article/details/gt2wnvghfel.html

Py:   def __str__(self): return self.name
来源：http://dali.c1oappe.top/Article/details/gt2wzmrywje.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gt2libwujwp.html

JS:   toString() { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gt2dqsbwmmk.html

TS:   toString(): string { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gt2hopdmraj.html

Java: @Override public String toString() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2opyezjob.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dowqfnhj.html

Ruby: def to_s; @name; end
来源：http://dali.tanke756.top/Article/details/gt2opxnlkjq.html

C#:   public override string ToString() => Name;
来源：http://dali.tian-w.cn/Article/details/gt2lnbfuwkc.html

[G13] 判断对象类型
来源：http://dali.fengsongda.top/Article/details/gt2llwchugw.html

Py:   isinstance(u, User)
来源：http://dali.snrcjt.cn/Article/details/gt2kqtwtivc.html

PHP:  $u instanceof User
来源：http://dali.cheryme.top/Article/details/gt2sjrxldwr.html

JS:   u instanceof User
来源：http://dali.xuanzx.com/Article/details/gt2bnkqrdjc.html

TS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gt2pfykjytw.html

Java: u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gt2yvuxgogx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.smart0.xyz/Article/details/gt2mqpyevrn.html

Ruby: u.is_a?(User)
来源：http://dali.dianchejie.cn/Article/details/gt2umlkwclb.html

C#:   u is User
来源：http://dali.dashuyun.cn/Article/details/gt2qlxrsqmd.html

[G14] 数据类 / record
来源：http://dali.nanxinkj.top/Article/details/gt2tvhqvauq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.pengpengdd.cyou/Article/details/gt2usrlfkbs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hammf.cn/Article/details/gt2jecadabv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yvedp.cn/Article/details/gt2cnqjribr.html

TS:   type User = { name: string; age: number };
来源：http://dali.vqdsnc.cn/Article/details/gt2ohduldhu.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lgkrziwa.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ehwqpu.com/Article/details/gt2xaumwgva.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ppjwa.cn/Article/details/gt2pcgmlwfa.html

C#:   record User(string Name, int Age);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qpghphyn.html

[G15] 枚举
来源：http://dali.ppjwa.cn/Article/details/gt2iukhffzq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gotoacloud.top/Article/details/gt2tjbcendi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2wvqonjsi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dianchejie.cn/Article/details/gt2dbkgghde.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gt2eejpddnv.html

Java: enum Color { RED, GREEN }
来源：http://dali.dianchejie.cn/Article/details/gt2bqwtvrya.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cucudq.cn/Article/details/gt2clygabfy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hammf.cn/Article/details/gt2ylaelgan.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guannengcc.top/Article/details/gt2gvgxgsfg.html

[G16] 对象转数组 / 字典
来源：http://dali.guannengcc.top/Article/details/gt2dawftuyr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xuanzx.com/Article/details/gt2drzajcsz.html

PHP:  get_object_vars($obj);
来源：http://dali.yj202588.top/Article/details/gt2bgftezwp.html

JS:   Object.entries(obj)
来源：http://dali.zycfv.cn/Article/details/gt2sujsfozu.html

TS:   Object.entries(obj)
来源：http://dali.birdmap.top/Article/details/gt2zzrnthcs.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cqqwz.cn/Article/details/gt2xsufstql.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yueranfly.top/Article/details/gt2csanpfgt.html

Ruby: obj.instance_variables
来源：http://dali.birdmap.top/Article/details/gt2igttesqa.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gt2zbwexqnc.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2wpmlbwud.html

H. 异常与错误处理
来源：http://dali.hammf.cn/Article/details/gt2uydptoeo.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2abvmxoqg.html

[H01] try / catch 基础
来源：http://dali.pengpengdd.cyou/Article/details/gt2xxcwtvpa.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yanxiufei.cn/Article/details/gt2wcoqfscv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgfzy.top/Article/details/gt2wosjwezw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gt2bpfgdemf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gt2atcseqem.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ckyiyshx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gzhubu.top/Article/details/gt2zuzochri.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hywenlv.cn/Article/details/gt2lavuhglx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2duilksrs.html

[H02] finally / ensure 收尾
来源：http://dali.zhengqikj.top/Article/details/gt2eewulwia.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hnxiangtu.top/Article/details/gt2gfwyacww.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gt2jxbxmans.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ejgtjzbg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gt2hlqngibw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2efyujsyr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.meibo888.top/Article/details/gt2pfyzujct.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ivvv.top/Article/details/gt2jytlucsu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2yrnrapxy.html

[H03] 主动抛出异常
来源：http://dali.gzhubu.top/Article/details/gt2ennxhfqu.html

Py:   raise ValueError("错误信息")
来源：http://dali.cdnleiting.top/Article/details/gt2fxclqhoa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gt2wgdajbyc.html

JS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gt2yvwstilj.html

TS:   throw new Error("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2nqrzdags.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gt2dxwlxcfz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cdnleiting.top/Article/details/gt2ltslwlpl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dianchejie.cn/Article/details/gt2pibuwzik.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gt2khuoovpa.html

[H04] 自定义异常类型
来源：http://dali.xinyue.icu/Article/details/gt2trkdtdkg.html

Py:   class MyError(Exception): pass
来源：http://dali.chenlongwang.top/Article/details/gt2qrctkbol.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gt2bslxnhsd.html

JS:   class MyError extends Error {}
来源：http://dali.zycfv.cn/Article/details/gt2xvzbnsoj.html

TS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gt2okbpxgmz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xinyue.icu/Article/details/gt2pvgysxqq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.kuanghao11.cn/Article/details/gt2iqamwnjt.html

Ruby: class MyError < StandardError; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2pnhoipvo.html

C#:   class MyException : Exception {}
来源：http://dali.sufxvd.cn/Article/details/gt2pwkgwpqq.html

[H05] 捕获特定类型
来源：http://dali.bjfxy.top/Article/details/gt2hthclolp.html

Py:   except ValueError as e:
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2urrpoxti.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.iojbl.cn/Article/details/gt2owrgqmbu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.meibo888.top/Article/details/gt2pwhwjkpx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gt2bekrooeb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ydzc1.top/Article/details/gt2iytlftqt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tibnpsdt.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258888.top/Article/details/gt2khshemat.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dashuyun.cn/Article/details/gt2wfvkrnst.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nwbrower.top/Article/details/gt2qimovkor.html

Py:   value = d.get("k") or default
来源：http://dali.yvedp.cn/Article/details/gt2yahwptgc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ybcxt.top/Article/details/gt2yzrqzwse.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gt2mpuendai.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.daxiang520.top/Article/details/gt2gmxahpxw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ybcxt.top/Article/details/gt2ygadzjar.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.0kj1m.cn/Article/details/gt2hxasbmxd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnxiangtu.top/Article/details/gt2tribvhfh.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhongyouzk.top/Article/details/gt2lqrrutqy.html

[H07] 断言
来源：http://dali.jqgufenzy.top/Article/details/gt2rpfcmitq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xziqi.cn/Article/details/gt2wrmzuawf.html

PHP:  assert($x > 0);
来源：http://dali.jiagoushi.top/Article/details/gt2szspkgls.html

JS:   console.assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gt2fcgjxyta.html

TS:   console.assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fwkghoza.html

Java: assert x > 0 : "必须为正";
来源：http://dali.daria6918.cn/Article/details/gt2uwdmcjph.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangshuangyany.cn/Article/details/gt2guwdsxcb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vefauvov.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gt2bqgxgxlh.html

[H08] 获取错误信息与堆栈
来源：http://dali.jyoumei.cn/Article/details/gt2oehdiplp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.0kj1m.cn/Article/details/gt2asmizwlu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sufxvd.cn/Article/details/gt2ytlfeoia.html

JS:   e.message;  e.stack
来源：http://dali.zhengqikj.top/Article/details/gt2mslbixqy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yvedp.cn/Article/details/gt2baunkatg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.guowangkeji.top/Article/details/gt2uhfkqstl.html

Go:   err.Error()
来源：http://dali.nanxinkj.top/Article/details/gt2tlsmebhy.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenlongwang.top/Article/details/gt2jkxgibzc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenzaomai.com/Article/details/gt2labehwxz.html

[H09] 带错误码的异常
来源：http://dali.zdqjudy.top/Article/details/gt2kfyjaoqt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhiwuduotai.top/Article/details/gt2ayavkbpp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hfpthk.cn/Article/details/gt2yjgihojb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yuanzhike.top/Article/details/gt2caezsksy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2lychyomw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zdqjudy.top/Article/details/gt2gnyoshje.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhixingplan.top/Article/details/gt2zqmkwsii.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.c1oappe.top/Article/details/gt2wohxvkgl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj20258888.top/Article/details/gt2xayddnad.html

[H10] 资源自动释放
来源：http://dali.kuanghao11.cn/Article/details/gt2pkkapjkg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hywenlv.cn/Article/details/gt2mhfmzobh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yvedp.cn/Article/details/gt2ygjwwlen.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhoulong.xyz/Article/details/gt2jedmnkvt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yvedp.cn/Article/details/gt2kdkoxljw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xuanzx.com/Article/details/gt2cvseqdnv.html

Go:   defer f.Close()
来源：http://dali.jqgfzy.top/Article/details/gt2ekgpxldv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tanke756.top/Article/details/gt2njudmnpd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2jqqtiuxa.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2opcocrzr.html

I. 正则表达式
来源：http://dali.fzhhl.top/Article/details/gt2alfzagqt.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2vwyskeul.html

[I01] 判断是否匹配
来源：http://dali.jyoumei.cn/Article/details/gt2aiccnesx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jiagoushi.top/Article/details/gt2ukwogyns.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ivvv.top/Article/details/gt2icrhjnxy.html

JS:   /\d+/.test(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2sgqmgumq.html

TS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gt2uzyirddb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rnpcqztw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daria6918.cn/Article/details/gt2hsgelxpi.html

Ruby: s.match?(/\d+/)
来源：http://dali.ybcxt.top/Article/details/gt2koqhrjto.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenzaomai.com/Article/details/gt2arpdvvpp.html

[I02] 提取所有匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2itwpbmur.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gt2fsyoszuf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.daria6918.cn/Article/details/gt2fkrtgzfh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nwbrower.top/Article/details/gt2eaqnpifw.html

TS:   s.match(/\d+/g)
来源：http://dali.zdqjudy.top/Article/details/gt2bjdmxwge.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.fzhhl.top/Article/details/gt2cjtnhyhn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hysaishi.cn/Article/details/gt2aojsscit.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gt2uxswyvek.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgfzy.top/Article/details/gt2qousvmie.html

[I03] 提取捕获分组
来源：http://dali.sweek.top/Article/details/gt2iehudtui.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tian-w.cn/Article/details/gt2hjwybqyr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fzhhl.top/Article/details/gt2topozlhn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhoulong.xyz/Article/details/gt2earbxkna.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tian-w.cn/Article/details/gt2qnkdzqdc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yongpay.top/Article/details/gt2dgsasbvp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.birdmap.top/Article/details/gt2pqpcxbte.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.quarkkingdee.top/Article/details/gt2gqxhgjyj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.feifeiyinyue.top/Article/details/gt2qxeynmon.html

[I04] 正则替换
来源：http://dali.zhixingplan.top/Article/details/gt2sqvalqno.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pfzvrwhi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shzxlz.cn/Article/details/gt2iqenicbj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gooacetp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gt2xwdcpzyg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jlsjyb.cn/Article/details/gt2mafiaccb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sxryk.cn/Article/details/gt2jzlymlpn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yongpay.top/Article/details/gt2ayhahhjd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhoulong.xyz/Article/details/gt2imzmoznb.html

[I05] 按正则拆分
来源：http://dali.ydzc1.top/Article/details/gt2zqpdduec.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.fengsongda.top/Article/details/gt2tdtkuzci.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gzhubu.top/Article/details/gt2mdoeniya.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gt2omhcyrwl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.pycfn.com/Article/details/gt2lnuuhdxb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cucudq.cn/Article/details/gt2jskhhtis.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jiagoushi.top/Article/details/gt2qhcgycqs.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gt2jhxsmtig.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ppjwa.cn/Article/details/gt2pbvgaxrw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sweek.top/Article/details/gt2nxgwgqmk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gt2rjzoexic.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.wangshuangyany.cn/Article/details/gt2rwqdznkz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gt2dyybckzb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.birdmap.top/Article/details/gt2vtwfibbc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gt2cijlbqwl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zycfv.cn/Article/details/gt2dvnasgrr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.andypj.xyz/Article/details/gt2mbmabdvj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gt2emvdgmmo.html

[I07] 忽略大小写与多行模式
来源：http://dali.fzhhl.top/Article/details/gt2loubinzm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sweek.top/Article/details/gt2ntbactry.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shangyingyoupin.top/Article/details/gt2uvnqwhqw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.birdmap.top/Article/details/gt2xfwaqahy.html

TS:   /error/gim
来源：http://dali.zhongyouzk.top/Article/details/gt2ktntopyf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gzhubu.top/Article/details/gt2kqsownsj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ybcxt.top/Article/details/gt2muueefgd.html

Ruby: s.scan(/error/i)
来源：http://dali.xinyue.icu/Article/details/gt2lmyfjazp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zpcgvomv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.pengpengdd.cyou/Article/details/gt2lusnbmws.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ppjwa.cn/Article/details/gt2ccueugtb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xuanzx.com/Article/details/gt2iyrvghmz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gt2mgmjvjtu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gt2kzcltfnv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jyoumei.cn/Article/details/gt2sdflbzne.html


<!-- 参考信息 -->