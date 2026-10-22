代发 wailian999

TS:   constructor(public name: string) {}
来源：http://dali.hfpthk.cn/Article/details/gt2jtpluesk.html

Java: User(String name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gt2wplajjvz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aibaodan.cn/Article/details/gt2xxtkzjqp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tanke756.top/Article/details/gt2nttjxidk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2narvbsbx.html

[G03] 实例属性
来源：http://dali.feifeiyinyue.top/Article/details/gt2qgkemzkq.html

Py:   self.name = "x"
来源：http://dali.hfpthk.cn/Article/details/gt2bijdygxc.html

PHP:  public string $name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gt2npibltvv.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xlcessno.html

TS:   name: string = "x";
来源：http://dali.nwbrower.top/Article/details/gt2dpkxypzs.html

Java: private String name;
来源：http://dali.cashguo.top/Article/details/gt2czaeptvj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tanke756.top/Article/details/gt2susvdkxj.html

Ruby: @name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cmffkguc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kulibxqu.html

[G04] 定义方法
来源：http://dali.ppjwa.cn/Article/details/gt2hjtmggxl.html

Py:   def greet(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gt2rufkazwj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xgaxoafc.html

JS:   greet() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gt2dnuhtucj.html

TS:   greet(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gt2aeheonbo.html

Java: String greet() { return name; }
来源：http://dali.jianghu66.top/Article/details/gt2gexdnvyc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gt2yqmhedyr.html

Ruby: def greet; @name; end
来源：http://dali.ydzc1.top/Article/details/gt2xqlrlukw.html

C#:   public string Greet() => Name;
来源：http://dali.ivvv.top/Article/details/gt2mkqzlxck.html

[G05] 继承
来源：http://dali.guowangkeji.top/Article/details/gt2onyinshl.html

Py:   class Admin(User): pass
来源：http://dali.gotoacloud.top/Article/details/gt2xqoackra.html

PHP:  class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gt2yikwbmao.html

JS:   class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2fijddxjl.html

TS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gt2rtxrrlns.html

Java: class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2rxziukgw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj20258888.top/Article/details/gt2fsvqvmyd.html

Ruby: class Admin < User; end
来源：http://dali.xziqi.cn/Article/details/gt2latpbujh.html

C#:   class Admin : User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tugxfhsu.html

[G06] 重写方法
来源：http://dali.jiagoushi.top/Article/details/gt2qehjoqxj.html

Py:   def greet(self): return "admin"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2htbcymlt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gt2atgptabk.html

JS:   greet() { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gt2skcovhth.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hxumhths.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gt2unnrcyfg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.fzhhl.top/Article/details/gt2rqrejpcv.html

Ruby: def greet; "admin"; end
来源：http://dali.0kj1m.cn/Article/details/gt2mtneslow.html

C#:   public override string Greet() => "admin";
来源：http://dali.guannengcc.top/Article/details/gt2szmiczzb.html

[G07] 调用父类方法
来源：http://dali.andypj.xyz/Article/details/gt2cnyurtuw.html

Py:   super().greet()
来源：http://dali.cqqwz.cn/Article/details/gt2merbptmb.html

PHP:  parent::greet();
来源：http://dali.hongshengwenyu.top/Article/details/gt2uvtsypmw.html

JS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gt2gmuthxuj.html

TS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gt2knlejqco.html

Java: super.greet();
来源：http://dali.gzhubu.top/Article/details/gt2lmsrkqwh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sweek.top/Article/details/gt2clgxxtjm.html

Ruby: super
来源：http://dali.yj20258888.top/Article/details/gt2zfnyfqlj.html

C#:   base.Greet();
来源：http://dali.yj202588.top/Article/details/gt2urvfvhrf.html

[G08] 静态方法与属性
来源：http://dali.hnqzz.top/Article/details/gt2feweqoyx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pengpengdd.cyou/Article/details/gt2mltngxwe.html

PHP:  public static function f() {}
来源：http://dali.dashuyun.cn/Article/details/gt2dujjnbgw.html

JS:   static f() {}
来源：http://dali.gogol.net.cn/Article/details/gt2fuhymqmd.html

TS:   static f(): void {}
来源：http://dali.yangfankeji.com/Article/details/gt2wfepkdeg.html

Java: static void f() {}
来源：http://dali.fzhhl.top/Article/details/gt2dnbmwsps.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yanxiufei.cn/Article/details/gt2hsnmjhue.html

Ruby: def self.f; end
来源：http://dali.snrcjt.cn/Article/details/gt2gyctrjte.html

C#:   public static void F() {}
来源：http://dali.yuanzhike.top/Article/details/gt2wocihhrz.html

[G09] 接口 / 抽象类
来源：http://dali.xylfe.cn/Article/details/gt2jbpgzggk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.316326.xyz/Article/details/gt2ezikghtt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hysaishi.cn/Article/details/gt2bwaggtxg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yonumen.top/Article/details/gt2naidccvu.html

TS:   interface Shape { area(): number; }
来源：http://dali.xziqi.cn/Article/details/gt2arimieyo.html

Java: interface Shape { double area(); }
来源：http://dali.cqqwz.cn/Article/details/gt2ykofdcem.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.0kj1m.cn/Article/details/gt2reagzyxs.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenzaomai.com/Article/details/gt2pwfujbet.html

C#:   interface IShape { double Area(); }
来源：http://dali.hnqzz.top/Article/details/gt2xalyqakz.html

[G10] 访问控制
来源：http://dali.yvedp.cn/Article/details/gt2spgcwzlo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.kuanghao11.cn/Article/details/gt2hucatbkm.html

PHP:  public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gt2cjvwbzyn.html

JS:   #private 字段；其余公开
来源：http://dali.c1oappe.top/Article/details/gt2jjjpckoy.html

TS:   public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gt2uxetutxs.html

Java: public / protected / private / 默认包级
来源：http://dali.ehwqpu.com/Article/details/gt2uzglzhtk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.daria6918.cn/Article/details/gt2gspfcbyk.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vcfihirj.html

C#:   public / protected / private / internal
来源：http://dali.jiagoushi.top/Article/details/gt2vaedmkgu.html

[G11] getter / setter
来源：http://dali.zhengqikj.top/Article/details/gt2twwotmyr.html

Py:   @property 与 @x.setter
来源：http://dali.pycfn.com/Article/details/gt2obmyhxtg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gt2pakkwhvr.html

JS:   get name() { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gt2poadgstl.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gt2xssliyut.html

Java: public String getName() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2hriymsfo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gt2bildhnym.html

Ruby: attr_accessor :name
来源：http://dali.zhongyouzk.top/Article/details/gt2oiezfzwu.html

C#:   public string Name { get; set; }
来源：http://dali.sxryk.cn/Article/details/gt2pafkiywa.html

[G12] 对象转字符串
来源：http://dali.iojbl.cn/Article/details/gt2sowvdvtr.html

Py:   def __str__(self): return self.name
来源：http://dali.wangdashe.top/Article/details/gt2gifsvjtq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gt2lwjfrjdf.html

JS:   toString() { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2edbvhdip.html

TS:   toString(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gt2xepnsftg.html

Java: @Override public String toString() { return name; }
来源：http://dali.wangdashe.top/Article/details/gt2xageludj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gt2uvpykdza.html

Ruby: def to_s; @name; end
来源：http://dali.yj20258888.top/Article/details/gt2ncfeygpd.html

C#:   public override string ToString() => Name;
来源：http://dali.yongpay.top/Article/details/gt2nqnllldl.html

[G13] 判断对象类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ccndktto.html

Py:   isinstance(u, User)
来源：http://dali.gaohongyu789.top/Article/details/gt2rylybvsv.html

PHP:  $u instanceof User
来源：http://dali.gzhubu.top/Article/details/gt2fuveitzl.html

JS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gt2tuquksmj.html

TS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gt2gkdtuumi.html

Java: u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gt2yaylkvkm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.snrcjt.cn/Article/details/gt2dmulleap.html

Ruby: u.is_a?(User)
来源：http://dali.ppjwa.cn/Article/details/gt2fzutmaxx.html

C#:   u is User
来源：http://dali.tianlin.xyz/Article/details/gt2nmirozla.html

[G14] 数据类 / record
来源：http://dali.hysaishi.cn/Article/details/gt2bewsezbg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hammf.cn/Article/details/gt2yfsfxmsb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.smart0.xyz/Article/details/gt2qjcubaxj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuanzhike.top/Article/details/gt2kwmzmzmp.html

TS:   type User = { name: string; age: number };
来源：http://dali.hnxiangtu.top/Article/details/gt2wnnnhavk.html

Java: record User(String name, int age) {}
来源：http://dali.iojbl.cn/Article/details/gt2yoeowgvt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj202588.top/Article/details/gt2gscucqya.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cashguo.top/Article/details/gt2vxgcpxfi.html

C#:   record User(string Name, int Age);
来源：http://dali.gotoacloud.top/Article/details/gt2enhdmgxi.html

[G15] 枚举
来源：http://dali.sufxvd.cn/Article/details/gt2tmcxjkyj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ndoaahoj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhixingplan.top/Article/details/gt2voxddfln.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xziqi.cn/Article/details/gt2fbsuxelf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.haohaochexian.top/Article/details/gt2mjjmyatr.html

Java: enum Color { RED, GREEN }
来源：http://dali.hywenlv.cn/Article/details/gt2ntxjnpaj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mafgiycd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.feifeiyinyue.top/Article/details/gt2fmfvctpk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhixingplan.top/Article/details/gt2imfvlrjv.html

[G16] 对象转数组 / 字典
来源：http://dali.feifeiyinyue.top/Article/details/gt2qepangnr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.vqdsnc.cn/Article/details/gt2dseqnbhe.html

PHP:  get_object_vars($obj);
来源：http://dali.hywenlv.cn/Article/details/gt2gkykljdm.html

JS:   Object.entries(obj)
来源：http://dali.sweek.top/Article/details/gt2pysvbkdj.html

TS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gt2nnknlikp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jyoumei.cn/Article/details/gt2kljornvg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xinyue.icu/Article/details/gt2jquwguff.html

Ruby: obj.instance_variables
来源：http://dali.yonumen.top/Article/details/gt2uyzaegwx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.wangdashe.top/Article/details/gt2dikcmpfm.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2hwpssmyn.html

H. 异常与错误处理
来源：http://dali.aibaodan.cn/Article/details/gt2ctlxqfyx.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qbajtjkr.html

[H01] try / catch 基础
来源：http://dali.nwbrower.top/Article/details/gt2pmqtisdi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xylfe.cn/Article/details/gt2pypdkdct.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2veootqdn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhongyouzk.top/Article/details/gt2yekjckel.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gt2psobmlqb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zdqjudy.top/Article/details/gt2tquxmlxv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shzxlz.cn/Article/details/gt2wfserqvm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yueranfly.top/Article/details/gt2lzmuzbep.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hfpthk.cn/Article/details/gt2hphahlda.html

[H02] finally / ensure 收尾
来源：http://dali.meibo888.top/Article/details/gt2moputued.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigfzy.top/Article/details/gt2vvtomvka.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gt2cjlhngwy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2kioinqvx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gt2jjvoipkc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2leodvvmf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tanke756.top/Article/details/gt2plsxgvps.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2tmbzfntg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gt2wtdekutl.html

[H03] 主动抛出异常
来源：http://dali.yuxming.cn/Article/details/gt2wbjdxnpf.html

Py:   raise ValueError("错误信息")
来源：http://dali.svipenyu.cn/Article/details/gt2sylqcrkb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gt2pnufkeoa.html

JS:   throw new Error("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gt2szzncteq.html

TS:   throw new Error("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2grfqnuip.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gt2bnaufycw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.dashuyun.cn/Article/details/gt2kdyxasfs.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zycfv.cn/Article/details/gt2srheysxj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fvpluplq.html

[H04] 自定义异常类型
来源：http://dali.yongpay.top/Article/details/gt2bnpuwbhk.html

Py:   class MyError(Exception): pass
来源：http://dali.hfpthk.cn/Article/details/gt2rnxosrcs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.mhx1999.top/Article/details/gt2pwhhdwby.html

JS:   class MyError extends Error {}
来源：http://dali.yanxiufei.cn/Article/details/gt2ixhgumdg.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2porxstwi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jyoumei.cn/Article/details/gt2lxtrmjkc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tianlin.xyz/Article/details/gt2exaiwgam.html

Ruby: class MyError < StandardError; end
来源：http://dali.fengsongda.top/Article/details/gt2gvmfrggt.html

C#:   class MyException : Exception {}
来源：http://dali.sxryk.cn/Article/details/gt2vhztwuom.html

[H05] 捕获特定类型
来源：http://dali.meibo888.top/Article/details/gt2ldociacc.html

Py:   except ValueError as e:
来源：http://dali.chenzaomai.com/Article/details/gt2novvvyyj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.guannengcc.top/Article/details/gt2zrxahjid.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2rldhqbga.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gt2tatrvufk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tian-w.cn/Article/details/gt2dhybzzed.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.svipenyu.cn/Article/details/gt2suelozxx.html

Ruby: rescue ArgumentError => e
来源：http://dali.aizwys.cn/Article/details/gt2tigsyfcw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.smart0.xyz/Article/details/gt2iuwrekdp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.pengpengdd.cyou/Article/details/gt2yabjkpvx.html

Py:   value = d.get("k") or default
来源：http://dali.yj20258.top/Article/details/gt2jtwfwqii.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ivvv.top/Article/details/gt2nkrcoqhl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenzaomai.com/Article/details/gt2quhwadsk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zycfv.cn/Article/details/gt2mpwkeytj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.mhx1999.top/Article/details/gt2zlklwftv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhoulong.xyz/Article/details/gt2mizxsicy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sxryk.cn/Article/details/gt2brzjxgfq.html

C#:   obj?.A?.B ?? default
来源：http://dali.quarkkingdee.top/Article/details/gt2duqxiapz.html

[H07] 断言
来源：http://dali.dianchejie.cn/Article/details/gt2owiglyne.html

Py:   assert x > 0, "必须为正"
来源：http://dali.andypj.xyz/Article/details/gt2qzqediek.html

PHP:  assert($x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2orvdlpye.html

JS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gt2plidkpgm.html

TS:   console.assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gt2rtrrknpt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xuanzx.com/Article/details/gt2baiqwotm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pengpengdd.cyou/Article/details/gt2sktmakru.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.c1oappe.top/Article/details/gt2unxachge.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gt2tmgknwbb.html

[H08] 获取错误信息与堆栈
来源：http://dali.pycfn.com/Article/details/gt2hrvmhhgi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tanke756.top/Article/details/gt2wgpweysj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhengqikj.top/Article/details/gt2qrmaqive.html

JS:   e.message;  e.stack
来源：http://dali.gogol.net.cn/Article/details/gt2xxedqbmx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jqgufenzy.top/Article/details/gt2bgoabgjn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.vqdsnc.cn/Article/details/gt2rbhztxsd.html

Go:   err.Error()
来源：http://dali.cashguo.top/Article/details/gt2xiwhbqtz.html

Ruby: e.message;  e.backtrace
来源：http://dali.yvedp.cn/Article/details/gt2qnbkqinw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.quarkkingdee.top/Article/details/gt2pwcgldks.html

[H09] 带错误码的异常
来源：http://dali.xylfe.cn/Article/details/gt2cutvywfk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shuidangran.top/Article/details/gt2ggftspdb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2piojdgqd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhixingplan.top/Article/details/gt2ezebjfnu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nwbrower.top/Article/details/gt2mhwveqwq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.bjfxy.top/Article/details/gt2smgbpflo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhixingplan.top/Article/details/gt2mjdklewm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tianlin.xyz/Article/details/gt2bbqaemon.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sysykeji.top/Article/details/gt2hsvdamar.html

[H10] 资源自动释放
来源：http://dali.daxiang520.top/Article/details/gt2rjfaywnc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hnxiangtu.top/Article/details/gt2eckeevhe.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shuidangran.top/Article/details/gt2nhfwiylx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yvedp.cn/Article/details/gt2vbxbiuqh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.vqdsnc.cn/Article/details/gt2xnwyutxf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgufenzy.top/Article/details/gt2wpguljkp.html

Go:   defer f.Close()
来源：http://dali.yuanzhike.top/Article/details/gt2bqeuocag.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ppjwa.cn/Article/details/gt2mtqqipnp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2yvqqzciy.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2kfkpctkq.html

I. 正则表达式
来源：http://dali.jinqigfzy.top/Article/details/gt2cdcsmdgs.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2nhyuljns.html

[I01] 判断是否匹配
来源：http://dali.zdqjudy.top/Article/details/gt2cwvyrcgi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hnqzz.top/Article/details/gt2rmjafzyk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gt2hcpmnwwp.html

JS:   /\d+/.test(s)
来源：http://dali.gotoacloud.top/Article/details/gt2qavctdin.html

TS:   /\d+/.test(s)
来源：http://dali.xziqi.cn/Article/details/gt2olwnrcst.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cdnleiting.top/Article/details/gt2ywjoqxfl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hywenlv.cn/Article/details/gt2gwcdccst.html

Ruby: s.match?(/\d+/)
来源：http://dali.xinyue.icu/Article/details/gt2ljdhlxfp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hysaishi.cn/Article/details/gt2phqdjvml.html

[I02] 提取所有匹配
来源：http://dali.yonumen.top/Article/details/gt2ydmytymh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gt2qpvengpn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yueranfly.top/Article/details/gt2qomfqtxv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhixingplan.top/Article/details/gt2mescgfdm.html

TS:   s.match(/\d+/g)
来源：http://dali.xylfe.cn/Article/details/gt2yvhvkrft.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.birdmap.top/Article/details/gt2rnnwdtjs.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jiagoushi.top/Article/details/gt2urusacgc.html

Ruby: s.scan(/\d+/)
来源：http://dali.dashuyun.cn/Article/details/gt2uyhoelfq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.guowangkeji.top/Article/details/gt2jgmoypdd.html

[I03] 提取捕获分组
来源：http://dali.yuxming.cn/Article/details/gt2vllvsiqb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.snrcjt.cn/Article/details/gt2lgrvvzdc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnxiangtu.top/Article/details/gt2pqgdqhtf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xziqi.cn/Article/details/gt2mpoadnow.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2rnidkkwg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sysykeji.top/Article/details/gt2znmacyev.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.feifeiyinyue.top/Article/details/gt2kkskopni.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sysykeji.top/Article/details/gt2josvybng.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ctklaujo.html

[I04] 正则替换
来源：http://dali.mhx1999.top/Article/details/gt2thifuwkn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.birdmap.top/Article/details/gt2juwkdnwl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuanzx.com/Article/details/gt2dempfngz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.pycfn.com/Article/details/gt2ubkoxojp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xylfe.cn/Article/details/gt2soblmqkd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xinyue.icu/Article/details/gt2fajzkbtt.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jlsjyb.cn/Article/details/gt2yaqobdty.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2loutchmx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yangfankeji.com/Article/details/gt2ucfanpvw.html

[I05] 按正则拆分
来源：http://dali.snrcjt.cn/Article/details/gt2twncvrxt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hnqzz.top/Article/details/gt2bqsybdrn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.smart0.xyz/Article/details/gt2smmmdmxr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gt2bmqfmton.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gt2nrbkpmva.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhongyouzk.top/Article/details/gt2kqovpogh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2enhdhkvl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gt2oeyarqpk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2agqvmcrf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.dianchejie.cn/Article/details/gt2vnbuayeh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gt2yrgyrvrz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nanxinkj.top/Article/details/gt2qjteyaed.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nwbrower.top/Article/details/gt2rtfbwsis.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gt2pslyjcvl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gt2bybqgfzx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yuanzhike.top/Article/details/gt2uolqptws.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yangfankeji.com/Article/details/gt2nnyhruxb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gt2tspnmvvm.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pvsxsbqr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhoulong.xyz/Article/details/gt2pmjbpbmw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gt2xpelsyqv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yanxiufei.cn/Article/details/gt2brlcjlgn.html

TS:   /error/gim
来源：http://dali.shangyingyoupin.top/Article/details/gt2xvmitizz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gotoacloud.top/Article/details/gt2blgmrxwu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nanxinkj.top/Article/details/gt2fadtwsat.html

Ruby: s.scan(/error/i)
来源：http://dali.xziqi.cn/Article/details/gt2jmlbtbbo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xinyue.icu/Article/details/gt2pgqmgzzp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2nrnddcfz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ydzc1.top/Article/details/gt2hyjttltm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gt2zvfhlutx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guannengcc.top/Article/details/gt2rlmbdjja.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cucudq.cn/Article/details/gt2wtqjwbla.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zgjemsxt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.pycfn.com/Article/details/gt2wrrsxywt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yuxming.cn/Article/details/gt2nckkviii.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shzxlz.cn/Article/details/gt2lxxliohe.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2wqvxkror.html


<!-- 参考信息 -->