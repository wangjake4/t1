代发 wailian999

TS:   constructor(public name: string) {}
来源：http://dali.yj20258.top/Article/details/gt2crqfvpvq.html

Java: User(String name) { this.name = name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2mlrvhvvq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenlongwang.top/Article/details/gt2jtrbxfuv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.quarkkingdee.top/Article/details/gt2uviaznvy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj202588.top/Article/details/gt2nfbjzyfa.html

[G03] 实例属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aspifkxh.html

Py:   self.name = "x"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2snhfukln.html

PHP:  public string $name = "x";
来源：http://dali.shzxlz.cn/Article/details/gt2bprhzthi.html

JS:   this.name = "x";
来源：http://dali.gotoacloud.top/Article/details/gt2mjvucgxu.html

TS:   name: string = "x";
来源：http://dali.chenzaomai.com/Article/details/gt2zcmgzlaa.html

Java: private String name;
来源：http://dali.ydzc1.top/Article/details/gt2hpnjpdse.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.svipenyu.cn/Article/details/gt2ixnvsmfo.html

Ruby: @name = "x"
来源：http://dali.jiagoushi.top/Article/details/gt2yzjxtawb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aizwys.cn/Article/details/gt2qmpggndt.html

[G04] 定义方法
来源：http://dali.yvedp.cn/Article/details/gt2twggsgxv.html

Py:   def greet(self): return self.name
来源：http://dali.yangfankeji.com/Article/details/gt2tihmaanc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gt2xkluwpym.html

JS:   greet() { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gt2pxexcqzt.html

TS:   greet(): string { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gt2hztqxpyj.html

Java: String greet() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vttprium.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gt2ozvkamix.html

Ruby: def greet; @name; end
来源：http://dali.shzxlz.cn/Article/details/gt2yqzgrktg.html

C#:   public string Greet() => Name;
来源：http://dali.xuanzx.com/Article/details/gt2uycuafet.html

[G05] 继承
来源：http://dali.dianchejie.cn/Article/details/gt2sfsglqls.html

Py:   class Admin(User): pass
来源：http://dali.ybcxt.top/Article/details/gt2lxswmyxa.html

PHP:  class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gt2xermsqrj.html

JS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gt2ohrjhajv.html

TS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gt2gkhllsrb.html

Java: class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2jbkbrses.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jiagoushi.top/Article/details/gt2jdpbrvap.html

Ruby: class Admin < User; end
来源：http://dali.yj20258.top/Article/details/gt2quotjxsl.html

C#:   class Admin : User {}
来源：http://dali.ppjwa.cn/Article/details/gt2cmktnora.html

[G06] 重写方法
来源：http://dali.havefunace.top/Article/details/gt2qtbdmsrt.html

Py:   def greet(self): return "admin"
来源：http://dali.yongpay.top/Article/details/gt2qwaftsvt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gt2mqzmbawz.html

JS:   greet() { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gt2jxwffoup.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gt2rfiwygva.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2hhrudcjd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ydzc1.top/Article/details/gt2nhlmthce.html

Ruby: def greet; "admin"; end
来源：http://dali.ydzc1.top/Article/details/gt2qsxkawlx.html

C#:   public override string Greet() => "admin";
来源：http://dali.ehwqpu.com/Article/details/gt2tlptaxyk.html

[G07] 调用父类方法
来源：http://dali.zdqjudy.top/Article/details/gt2ltfbqyrx.html

Py:   super().greet()
来源：http://dali.hfpthk.cn/Article/details/gt2wfsexpza.html

PHP:  parent::greet();
来源：http://dali.hywenlv.cn/Article/details/gt2jdmjnide.html

JS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gt2nziehnqd.html

TS:   super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gt2wgqsgbhg.html

Java: super.greet();
来源：http://dali.aibaodan.cn/Article/details/gt2jhcgyhxx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgufenzy.top/Article/details/gt2tzalbuqs.html

Ruby: super
来源：http://dali.jlsjyb.cn/Article/details/gt2humpmvii.html

C#:   base.Greet();
来源：http://dali.gzhubu.top/Article/details/gt2nvrlwyzk.html

[G08] 静态方法与属性
来源：http://dali.jyoumei.cn/Article/details/gt2exypdxcn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hysaishi.cn/Article/details/gt2zqfbfxec.html

PHP:  public static function f() {}
来源：http://dali.dianchejie.cn/Article/details/gt2agffwlbp.html

JS:   static f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2wwhjjmac.html

TS:   static f(): void {}
来源：http://dali.snrcjt.cn/Article/details/gt2reotwogl.html

Java: static void f() {}
来源：http://dali.bjfxy.top/Article/details/gt2usdjserw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gzhubu.top/Article/details/gt2yqlayytj.html

Ruby: def self.f; end
来源：http://dali.hnxiangtu.top/Article/details/gt2ikfjijlh.html

C#:   public static void F() {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2qisxeomq.html

[G09] 接口 / 抽象类
来源：http://dali.wangdashe.top/Article/details/gt2bjuotmtm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhengqikj.top/Article/details/gt2vclshlsc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.snrcjt.cn/Article/details/gt2ctxxfrav.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xinyue.icu/Article/details/gt2cxxajurl.html

TS:   interface Shape { area(): number; }
来源：http://dali.316326.xyz/Article/details/gt2ededmbfd.html

Java: interface Shape { double area(); }
来源：http://dali.nwbrower.top/Article/details/gt2fqixveto.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tian-w.cn/Article/details/gt2cjlmxsdx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aizwys.cn/Article/details/gt2eezxjaby.html

C#:   interface IShape { double Area(); }
来源：http://dali.guannengcc.top/Article/details/gt2hbokrhoz.html

[G10] 访问控制
来源：http://dali.yuanzhike.top/Article/details/gt2utptlyyx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ivvv.top/Article/details/gt2anjvkxuf.html

PHP:  public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gt2dnsokjqx.html

JS:   #private 字段；其余公开
来源：http://dali.c1oappe.top/Article/details/gt2zxsronyo.html

TS:   public / protected / private
来源：http://dali.bjfxy.top/Article/details/gt2mvdgwlte.html

Java: public / protected / private / 默认包级
来源：http://dali.yanxiufei.cn/Article/details/gt2vsqhrujs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.daria6918.cn/Article/details/gt2nraawikf.html

Ruby: public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gt2zsggpikc.html

C#:   public / protected / private / internal
来源：http://dali.hfpthk.cn/Article/details/gt2qfqextek.html

[G11] getter / setter
来源：http://dali.birdmap.top/Article/details/gt2zfbvxodl.html

Py:   @property 与 @x.setter
来源：http://dali.sufxvd.cn/Article/details/gt2lpsxkggl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gt2nvsxmfve.html

JS:   get name() { return this._name; }
来源：http://dali.aibaodan.cn/Article/details/gt2ctdrujzm.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2inpbgpky.html

Java: public String getName() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2zpjaquzp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gt2inablmqe.html

Ruby: attr_accessor :name
来源：http://dali.ivvv.top/Article/details/gt2wugkdako.html

C#:   public string Name { get; set; }
来源：http://dali.daria6918.cn/Article/details/gt2asjkbglr.html

[G12] 对象转字符串
来源：http://dali.316326.xyz/Article/details/gt2kjpfiyba.html

Py:   def __str__(self): return self.name
来源：http://dali.hnqzz.top/Article/details/gt2hnupruwr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gt2bccptapk.html

JS:   toString() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gt2apzejurc.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gt2axbokjbr.html

Java: @Override public String toString() { return name; }
来源：http://dali.cucudq.cn/Article/details/gt2zfwdwdzv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gt2dkkbrygb.html

Ruby: def to_s; @name; end
来源：http://dali.mhx1999.top/Article/details/gt2gjkaoswh.html

C#:   public override string ToString() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gt2osfgkvmv.html

[G13] 判断对象类型
来源：http://dali.sufxvd.cn/Article/details/gt2xzcphpob.html

Py:   isinstance(u, User)
来源：http://dali.nanxinkj.top/Article/details/gt2zagfjyqp.html

PHP:  $u instanceof User
来源：http://dali.mhx1999.top/Article/details/gt2dkmmlfnh.html

JS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gt2zwcxfhmn.html

TS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gt2ctimimpd.html

Java: u instanceof User
来源：http://dali.pycfn.com/Article/details/gt2fhnljhdj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cqqwz.cn/Article/details/gt2ftepjytk.html

Ruby: u.is_a?(User)
来源：http://dali.dashuyun.cn/Article/details/gt2brnpmiil.html

C#:   u is User
来源：http://dali.yvedp.cn/Article/details/gt2depnteci.html

[G14] 数据类 / record
来源：http://dali.dianchejie.cn/Article/details/gt2lgdxhdfo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ppjwa.cn/Article/details/gt2dmjghoqy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhongyouzk.top/Article/details/gt2rpsttqsy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhixingplan.top/Article/details/gt2lqeawxiz.html

TS:   type User = { name: string; age: number };
来源：http://dali.sweek.top/Article/details/gt2kzbygbda.html

Java: record User(String name, int age) {}
来源：http://dali.smart0.xyz/Article/details/gt2waamwisz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.daxiang520.top/Article/details/gt2wzukbxix.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.aizwys.cn/Article/details/gt2qsouvkvu.html

C#:   record User(string Name, int Age);
来源：http://dali.gzhubu.top/Article/details/gt2ldptopyo.html

[G15] 枚举
来源：http://dali.ydzc1.top/Article/details/gt2lqjfmlab.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sweek.top/Article/details/gt2fliuzpxi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2thktybqy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zycfv.cn/Article/details/gt2wrwzfeeq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sxryk.cn/Article/details/gt2cundefoa.html

Java: enum Color { RED, GREEN }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xtbqupry.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sxryk.cn/Article/details/gt2pmnzottj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hfpthk.cn/Article/details/gt2bpsjhrcg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2zgpbfgrn.html

[G16] 对象转数组 / 字典
来源：http://dali.hnqzz.top/Article/details/gt2vmqavpyp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.0kj1m.cn/Article/details/gt2znktmzqk.html

PHP:  get_object_vars($obj);
来源：http://dali.yj202588.top/Article/details/gt2rildkorm.html

JS:   Object.entries(obj)
来源：http://dali.jianghu66.top/Article/details/gt2ttbzqycd.html

TS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gt2idoseidu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nbnvhbns.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.pengpengdd.cyou/Article/details/gt2ttjpnael.html

Ruby: obj.instance_variables
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2egqnypqs.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gt2qfoyakvr.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2mfmqfqmh.html

H. 异常与错误处理
来源：http://dali.cashguo.top/Article/details/gt2jjqscxhj.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2wypuczpo.html

[H01] try / catch 基础
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ngkljwyc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tianlin.xyz/Article/details/gt2xhmdqasy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cinlqicg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ysckkzuu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gt2sjdkwlxu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cheryme.top/Article/details/gt2zygyaoej.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tanke756.top/Article/details/gt2ukvsfjlv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sweek.top/Article/details/gt2nudmaedv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.smart0.xyz/Article/details/gt2xqxxwgsb.html

[H02] finally / ensure 收尾
来源：http://dali.tianlin.xyz/Article/details/gt2erufozke.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.havefunace.top/Article/details/gt2plfhlnis.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gt2nbeailyl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vqduvksl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gt2fhzgpvle.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gt2iiljbqeg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gaohongyu789.top/Article/details/gt2jdlnxyic.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhoulong.xyz/Article/details/gt2luolhdoa.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gt2hknbnjky.html

[H03] 主动抛出异常
来源：http://dali.ybcxt.top/Article/details/gt2eqvfyird.html

Py:   raise ValueError("错误信息")
来源：http://dali.xinyue.icu/Article/details/gt2qrzdeqor.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gt2fmcfutbc.html

JS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gt2uzroionf.html

TS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2dcjnniup.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gt2smoigjii.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zdqjudy.top/Article/details/gt2ohfefedb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.guannengcc.top/Article/details/gt2vxbuoyfj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gt2uoxkxxwf.html

[H04] 自定义异常类型
来源：http://dali.nwbrower.top/Article/details/gt2ervcbtbd.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxinkj.top/Article/details/gt2frqlyevs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.quarkkingdee.top/Article/details/gt2clzgxjxa.html

JS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gt2kkodkoet.html

TS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ebmukapx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcahczm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ybcxt.top/Article/details/gt2bgrvcwum.html

Ruby: class MyError < StandardError; end
来源：http://dali.cucudq.cn/Article/details/gt2ejnefqvm.html

C#:   class MyException : Exception {}
来源：http://dali.vqdsnc.cn/Article/details/gt2ahnoritw.html

[H05] 捕获特定类型
来源：http://dali.tian-w.cn/Article/details/gt2mszhwhns.html

Py:   except ValueError as e:
来源：http://dali.guannengcc.top/Article/details/gt2shxvngvl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.0kj1m.cn/Article/details/gt2yinhbihg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gt2oujmfqtr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gzhubu.top/Article/details/gt2vakmklms.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.daxiang520.top/Article/details/gt2mohtfpco.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gzhubu.top/Article/details/gt2ycscxmuo.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenzaomai.com/Article/details/gt2qsmcldfq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.birdmap.top/Article/details/gt2jmgnhrcg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gotoacloud.top/Article/details/gt2orkdveho.html

Py:   value = d.get("k") or default
来源：http://dali.feifeiyinyue.top/Article/details/gt2fwwwwlnv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hongshengwenyu.top/Article/details/gt2zfkfxdcz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cashguo.top/Article/details/gt2xscfsivh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gt2cdsydkmu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cheryme.top/Article/details/gt2dgsrwqez.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj20258.top/Article/details/gt2bmotijdl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.redwolf501.top/Article/details/gt2sqdexxac.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigfzy.top/Article/details/gt2xsqkhksn.html

[H07] 断言
来源：http://dali.fengsongda.top/Article/details/gt2cotohalc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.pengpengdd.cyou/Article/details/gt2ykufceoy.html

PHP:  assert($x > 0);
来源：http://dali.birdmap.top/Article/details/gt2hhoebcnb.html

JS:   console.assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gt2qrsuhuhl.html

TS:   console.assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gt2zcxajwbs.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenlongwang.top/Article/details/gt2fqeppuqi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yuxming.cn/Article/details/gt2pshjnilh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ehwqpu.com/Article/details/gt2ttdlqqhv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gt2zzgioocr.html

[H08] 获取错误信息与堆栈
来源：http://dali.sxryk.cn/Article/details/gt2spilbbzl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shuidangran.top/Article/details/gt2jysjoubc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ylhoxuub.html

JS:   e.message;  e.stack
来源：http://dali.jinqigufen.top/Article/details/gt2pjimfnmk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.guannengcc.top/Article/details/gt2letslhqe.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.bjfxy.top/Article/details/gt2carfbknj.html

Go:   err.Error()
来源：http://dali.sufxvd.cn/Article/details/gt2eklgqrns.html

Ruby: e.message;  e.backtrace
来源：http://dali.andypj.xyz/Article/details/gt2cpphipiq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.0kj1m.cn/Article/details/gt2qaycvmnu.html

[H09] 带错误码的异常
来源：http://dali.sweek.top/Article/details/gt2zwrxpjde.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hammf.cn/Article/details/gt2ailwgzsc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ndkstenr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ppjwa.cn/Article/details/gt2edargbie.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xuetiantiany.cn/Article/details/gt2nkqcwbji.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jqgufenzy.top/Article/details/gt2xdczwgic.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tanke756.top/Article/details/gt2gglleuei.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jqgufenzy.top/Article/details/gt2fmxeutet.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinqigfzy.top/Article/details/gt2jplnmthx.html

[H10] 资源自动释放
来源：http://dali.shzxlz.cn/Article/details/gt2tzlebcjy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gogol.net.cn/Article/details/gt2aogfqbva.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.9152youxi.cn/Article/details/gt2zcdgbaah.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gt2rrgjqyjq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gt2gkodewlf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sweek.top/Article/details/gt2rfmczkmp.html

Go:   defer f.Close()
来源：http://dali.jiagoushi.top/Article/details/gt2sondalxn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mptxakhf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2getwkids.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2nijewhyj.html

I. 正则表达式
来源：http://dali.jianghu66.top/Article/details/gt2rcylmjys.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2mtlpkrlh.html

[I01] 判断是否匹配
来源：http://dali.redwolf501.top/Article/details/gt2sewisrix.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ehwqpu.com/Article/details/gt2ngwebsxn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2bqmyadaa.html

JS:   /\d+/.test(s)
来源：http://dali.iojbl.cn/Article/details/gt2bdfgnqdu.html

TS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gt2lxftfsfh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hammf.cn/Article/details/gt2mgyxsjav.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgfzy.top/Article/details/gt2idhplzzz.html

Ruby: s.match?(/\d+/)
来源：http://dali.quarkkingdee.top/Article/details/gt2sbqsjaco.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.mhx1999.top/Article/details/gt2kyyqmkrk.html

[I02] 提取所有匹配
来源：http://dali.iojbl.cn/Article/details/gt2agzhcvjw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2whvbejzx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.snrcjt.cn/Article/details/gt2bcacebmn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenlongwang.top/Article/details/gt2ffkjaqxn.html

TS:   s.match(/\d+/g)
来源：http://dali.ivvv.top/Article/details/gt2ebycrsev.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhixingplan.top/Article/details/gt2vrxprwnx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jlsjyb.cn/Article/details/gt2iejejicu.html

Ruby: s.scan(/\d+/)
来源：http://dali.yueranfly.top/Article/details/gt2mxgvtnen.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hysaishi.cn/Article/details/gt2quivyjfz.html

[I03] 提取捕获分组
来源：http://dali.andypj.xyz/Article/details/gt2yfekwqgi.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.pycfn.com/Article/details/gt2poxeicmz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.smart0.xyz/Article/details/gt2rqqtxfmf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zdqjudy.top/Article/details/gt2yukvfsoa.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yuxming.cn/Article/details/gt2yipizbhg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenlongwang.top/Article/details/gt2dpaxtdzw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.316326.xyz/Article/details/gt2xexbyvfp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.c1oappe.top/Article/details/gt2bmklsuux.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj20258888.top/Article/details/gt2yulgolwt.html

[I04] 正则替换
来源：http://dali.zycfv.cn/Article/details/gt2mkunhutx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj20258.top/Article/details/gt2mmzjlfur.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2znqxbpqg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gt2qcccwtxs.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jiagoushi.top/Article/details/gt2hxqebafg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj202588.top/Article/details/gt2opjycjaw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jqgfzy.top/Article/details/gt2xikveqvu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.redwolf501.top/Article/details/gt2gdpfwnsj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.svipenyu.cn/Article/details/gt2hfxepkom.html

[I05] 按正则拆分
来源：http://dali.cdnleiting.top/Article/details/gt2zdfhjywg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jiagoushi.top/Article/details/gt2nedlsynk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gt2uaqmcyhb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gt2vlbytuqx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gt2jmbigfmc.html

Java: s.split("\\s*,\\s*")
来源：http://dali.haohaochexian.top/Article/details/gt2xgmxerda.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xuanzx.com/Article/details/gt2evlmkpfm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gt2yyfvoaes.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenlongwang.top/Article/details/gt2bamyrivj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.kuanghao11.cn/Article/details/gt2swpezppj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gt2miqzqjpr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.snrcjt.cn/Article/details/gt2uncdzyys.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.vqdsnc.cn/Article/details/gt2pintcxei.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenzaomai.com/Article/details/gt2dzkwhudf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gt2ckewmhcf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cheryme.top/Article/details/gt2tgpzllor.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhengqikj.top/Article/details/gt2fgzflicp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gt2qbrmwrnt.html

[I07] 忽略大小写与多行模式
来源：http://dali.guannengcc.top/Article/details/gt2vfqlqtqd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.aibaodan.cn/Article/details/gt2fsslissl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gt2xuugknlv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tian-w.cn/Article/details/gt2zrevpurf.html

TS:   /error/gim
来源：http://dali.tanke756.top/Article/details/gt2dwvyoptt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ybcxt.top/Article/details/gt2zcuegswy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2idybzugu.html

Ruby: s.scan(/error/i)
来源：http://dali.0kj1m.cn/Article/details/gt2ohrcunip.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.fzhhl.top/Article/details/gt2arcsukvc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.guowangkeji.top/Article/details/gt2epozocdd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hfpthk.cn/Article/details/gt2hzofmegd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhiwuduotai.top/Article/details/gt2svqvpkdk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gt2wgafphud.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gt2awlrmpng.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sweek.top/Article/details/gt2obxumbym.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gotoacloud.top/Article/details/gt2srowjexy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.meibo888.top/Article/details/gt2xtspmbfg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.fengsongda.top/Article/details/gt2bikvreht.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2wlpcomsh.html


<!-- 参考信息 -->