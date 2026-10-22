代发 wailian999

C#:   public User(string name) { Name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2wygcyyfc.html

[G03] 实例属性
来源：http://dali.jiagoushi.top/Article/details/gt2ifllylku.html

Py:   self.name = "x"
来源：http://dali.yongpay.top/Article/details/gt2uvsgljel.html

PHP:  public string $name = "x";
来源：http://dali.jqgufenzy.top/Article/details/gt2krdaigzr.html

JS:   this.name = "x";
来源：http://dali.9152youxi.cn/Article/details/gt2qhruleuw.html

TS:   name: string = "x";
来源：http://dali.hnxiangtu.top/Article/details/gt2dkvcowxy.html

Java: private String name;
来源：http://dali.cashguo.top/Article/details/gt2lotoilmd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.feifeiyinyue.top/Article/details/gt2ksilyyfj.html

Ruby: @name = "x"
来源：http://dali.meibo888.top/Article/details/gt2yhixnypo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.smart0.xyz/Article/details/gt2akwjjwhp.html

[G04] 定义方法
来源：http://dali.ppjwa.cn/Article/details/gt2dnrvupmv.html

Py:   def greet(self): return self.name
来源：http://dali.chenzaomai.com/Article/details/gt2byxpxeno.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gt2occpkjvx.html

JS:   greet() { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2onjqyjiy.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cldtmyen.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nrhzpuxi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gt2wqiuernv.html

Ruby: def greet; @name; end
来源：http://dali.cheryme.top/Article/details/gt2omifiiaf.html

C#:   public string Greet() => Name;
来源：http://dali.zycfv.cn/Article/details/gt2dfpykfep.html

[G05] 继承
来源：http://dali.guannengcc.top/Article/details/gt2omacsygv.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vcsuqvoq.html

PHP:  class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gt2gbnwlmla.html

JS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gt2vltrucaz.html

TS:   class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gt2qqoiaciq.html

Java: class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gt2kuxdyyfb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.svipenyu.cn/Article/details/gt2bcatyphx.html

Ruby: class Admin < User; end
来源：http://dali.ydzc1.top/Article/details/gt2hweszurj.html

C#:   class Admin : User {}
来源：http://dali.yj202588.top/Article/details/gt2tqnwdfub.html

[G06] 重写方法
来源：http://dali.feifeiyinyue.top/Article/details/gt2xpcsaxnf.html

Py:   def greet(self): return "admin"
来源：http://dali.andypj.xyz/Article/details/gt2sqijvkuh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gt2rhjdfdfh.html

JS:   greet() { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gt2vgnhsyse.html

TS:   greet(): string { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gt2yxgzbzwd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gt2alksqwgr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xinyue.icu/Article/details/gt2pevvcrnr.html

Ruby: def greet; "admin"; end
来源：http://dali.hammf.cn/Article/details/gt2yaizdtwv.html

C#:   public override string Greet() => "admin";
来源：http://dali.andypj.xyz/Article/details/gt2zhprdwma.html

[G07] 调用父类方法
来源：http://dali.chenzaomai.com/Article/details/gt2rkdbsprg.html

Py:   super().greet()
来源：http://dali.daria6918.cn/Article/details/gt2mjmoccau.html

PHP:  parent::greet();
来源：http://dali.hongshengwenyu.top/Article/details/gt2urvbhvbx.html

JS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gt2jfvrgnwm.html

TS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gt2dtxtjhqf.html

Java: super.greet();
来源：http://dali.aibaodan.cn/Article/details/gt2pdnocgag.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ehwqpu.com/Article/details/gt2xqwqzelv.html

Ruby: super
来源：http://dali.gaohongyu789.top/Article/details/gt2upivvxwh.html

C#:   base.Greet();
来源：http://dali.fengsongda.top/Article/details/gt2wtluuoxq.html

[G08] 静态方法与属性
来源：http://dali.quarkkingdee.top/Article/details/gt2xdfqrzom.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.smart0.xyz/Article/details/gt2oxipkxiq.html

PHP:  public static function f() {}
来源：http://dali.zycfv.cn/Article/details/gt2ogtwwihs.html

JS:   static f() {}
来源：http://dali.jinqigfzy.top/Article/details/gt2phxcfuvr.html

TS:   static f(): void {}
来源：http://dali.andypj.xyz/Article/details/gt2futyvfsp.html

Java: static void f() {}
来源：http://dali.gzhubu.top/Article/details/gt2fybcnrvd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.smart0.xyz/Article/details/gt2qqilboee.html

Ruby: def self.f; end
来源：http://dali.mhx1999.top/Article/details/gt2mxlafxll.html

C#:   public static void F() {}
来源：http://dali.chenzaomai.com/Article/details/gt2bngquxjx.html

[G09] 接口 / 抽象类
来源：http://dali.tianlin.xyz/Article/details/gt2uwedbhho.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sysykeji.top/Article/details/gt2bvrjlgnx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.birdmap.top/Article/details/gt2jtwqyioc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sxryk.cn/Article/details/gt2zlyryddk.html

TS:   interface Shape { area(): number; }
来源：http://dali.hammf.cn/Article/details/gt2iipkkzpy.html

Java: interface Shape { double area(); }
来源：http://dali.ybcxt.top/Article/details/gt2hnnpqjqm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.0kj1m.cn/Article/details/gt2frdbpavx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.andypj.xyz/Article/details/gt2qoejfrgz.html

C#:   interface IShape { double Area(); }
来源：http://dali.yuxming.cn/Article/details/gt2jxdocudt.html

[G10] 访问控制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hkzyhubz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenlongwang.top/Article/details/gt2tjkxwely.html

PHP:  public / protected / private
来源：http://dali.aizwys.cn/Article/details/gt2cilvgknq.html

JS:   #private 字段；其余公开
来源：http://dali.andypj.xyz/Article/details/gt2slwdnwhj.html

TS:   public / protected / private
来源：http://dali.meibo888.top/Article/details/gt2ixznotza.html

Java: public / protected / private / 默认包级
来源：http://dali.hfpthk.cn/Article/details/gt2fznhsnmx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnqzz.top/Article/details/gt2nqutatcf.html

Ruby: public / protected / private
来源：http://dali.sweek.top/Article/details/gt2hpognwww.html

C#:   public / protected / private / internal
来源：http://dali.smart0.xyz/Article/details/gt2kdbesjax.html

[G11] getter / setter
来源：http://dali.ydzc1.top/Article/details/gt2ycneqylh.html

Py:   @property 与 @x.setter
来源：http://dali.haohaochexian.top/Article/details/gt2zsrechpg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gt2hlyvcgii.html

JS:   get name() { return this._name; }
来源：http://dali.meibo888.top/Article/details/gt2zqmepgjq.html

TS:   get name(): string { return this._name; }
来源：http://dali.aibaodan.cn/Article/details/gt2qhttfxwu.html

Java: public String getName() { return name; }
来源：http://dali.smart0.xyz/Article/details/gt2phzbtinf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wpwshmim.html

Ruby: attr_accessor :name
来源：http://dali.yangfankeji.com/Article/details/gt2kjsvfwsw.html

C#:   public string Name { get; set; }
来源：http://dali.daria6918.cn/Article/details/gt2lwucdlie.html

[G12] 对象转字符串
来源：http://dali.snrcjt.cn/Article/details/gt2revqpjkf.html

Py:   def __str__(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gt2fgmoruck.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gt2qorzztvr.html

JS:   toString() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gt2jrigplgb.html

TS:   toString(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gt2ajjnvbsl.html

Java: @Override public String toString() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gt2rluzpsgl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gt2gjnyurrc.html

Ruby: def to_s; @name; end
来源：http://dali.dianchejie.cn/Article/details/gt2uigbjmbo.html

C#:   public override string ToString() => Name;
来源：http://dali.sxryk.cn/Article/details/gt2tqpbkcsv.html

[G13] 判断对象类型
来源：http://dali.yuanzhike.top/Article/details/gt2mqihgkld.html

Py:   isinstance(u, User)
来源：http://dali.zhoulong.xyz/Article/details/gt2dgmbzekk.html

PHP:  $u instanceof User
来源：http://dali.xuanzx.com/Article/details/gt2fgfgsopw.html

JS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gt2fqimsrwn.html

TS:   u instanceof User
来源：http://dali.zycfv.cn/Article/details/gt2qufqtszb.html

Java: u instanceof User
来源：http://dali.tian-w.cn/Article/details/gt2slabdpsy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.mhx1999.top/Article/details/gt2jjvfkrig.html

Ruby: u.is_a?(User)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xubfsngc.html

C#:   u is User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vexywazf.html

[G14] 数据类 / record
来源：http://dali.cashguo.top/Article/details/gt2lpeigufi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenlongwang.top/Article/details/gt2mldlywvt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cheryme.top/Article/details/gt2uigkezhx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhengqikj.top/Article/details/gt2mgtpwmci.html

TS:   type User = { name: string; age: number };
来源：http://dali.shangyingyoupin.top/Article/details/gt2ehmjrevm.html

Java: record User(String name, int age) {}
来源：http://dali.cheryme.top/Article/details/gt2mkhehfhe.html

Go:   type User struct { Name string; Age int }
来源：http://dali.andypj.xyz/Article/details/gt2lavuluoe.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wzvykxyy.html

C#:   record User(string Name, int Age);
来源：http://dali.chenlongwang.top/Article/details/gt2gpfzfdwb.html

[G15] 枚举
来源：http://dali.hnxiangtu.top/Article/details/gt2adhezejz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.svipenyu.cn/Article/details/gt2oqgaharh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gotoacloud.top/Article/details/gt2nvpbmgux.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xinyue.icu/Article/details/gt2wllvjocb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shzxlz.cn/Article/details/gt2mzubvhnk.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qyvtndan.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.9152youxi.cn/Article/details/gt2pofegogu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cqcuuolh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.iojbl.cn/Article/details/gt2kddtzvsr.html

[G16] 对象转数组 / 字典
来源：http://dali.gaohongyu789.top/Article/details/gt2ifktihwp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yanxiufei.cn/Article/details/gt2yhaqfzoq.html

PHP:  get_object_vars($obj);
来源：http://dali.zhengqikj.top/Article/details/gt2qxyeeixo.html

JS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gt2olrubvaj.html

TS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gt2fnagsjfa.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgfzy.top/Article/details/gt2pimlakug.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangshuangyany.cn/Article/details/gt2agkqwqfq.html

Ruby: obj.instance_variables
来源：http://dali.sxryk.cn/Article/details/gt2iktlqgts.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cqqwz.cn/Article/details/gt2xavmufeo.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2tizorece.html

H. 异常与错误处理
来源：http://dali.nwbrower.top/Article/details/gt2fjyglkuh.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dljucqpa.html

[H01] try / catch 基础
来源：http://dali.vqdsnc.cn/Article/details/gt2rewgiwwo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jiagoushi.top/Article/details/gt2olxeewxz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guannengcc.top/Article/details/gt2cublbqzt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tvkrcdoo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gt2ojbttthc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2eftmbdda.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cqqwz.cn/Article/details/gt2oticrsaf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jiagoushi.top/Article/details/gt2cvszupts.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.quarkkingdee.top/Article/details/gt2dmrhndrr.html

[H02] finally / ensure 收尾
来源：http://dali.cdnleiting.top/Article/details/gt2hktvsuuj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yonumen.top/Article/details/gt2wqzgtatd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2xpurprtm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2iriphggz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2kdmarfhn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gt2pxsnvneg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.fzhhl.top/Article/details/gt2bddhpsad.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2uxwcewrr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gt2kxjouuxm.html

[H03] 主动抛出异常
来源：http://dali.hfpthk.cn/Article/details/gt2bjqjshdd.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuanzx.com/Article/details/gt2sahjrjmj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gt2xrtgwois.html

JS:   throw new Error("错误信息");
来源：http://dali.316326.xyz/Article/details/gt2gdmbncdn.html

TS:   throw new Error("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gt2rijlehzu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gt2chukubua.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yuxming.cn/Article/details/gt2ulwcvzzg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xuetiantiany.cn/Article/details/gt2rshsrldi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gt2eacdtkco.html

[H04] 自定义异常类型
来源：http://dali.cheryme.top/Article/details/gt2aruorluk.html

Py:   class MyError(Exception): pass
来源：http://dali.yonumen.top/Article/details/gt2mcozfzcx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.pycfn.com/Article/details/gt2fgqgxzud.html

JS:   class MyError extends Error {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ewbmmfgu.html

TS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gt2uvdkojhq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aizwys.cn/Article/details/gt2dljvgnys.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.fzhhl.top/Article/details/gt2jxsgbxla.html

Ruby: class MyError < StandardError; end
来源：http://dali.wangdashe.top/Article/details/gt2rooawrte.html

C#:   class MyException : Exception {}
来源：http://dali.shzxlz.cn/Article/details/gt2imtfriaz.html

[H05] 捕获特定类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2cvzfifcp.html

Py:   except ValueError as e:
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tqxdddiy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.smart0.xyz/Article/details/gt2kmnqjmul.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ppjwa.cn/Article/details/gt2ocouefpv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sxryk.cn/Article/details/gt2ylaqqlxb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.guowangkeji.top/Article/details/gt2sfuhwlyp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dianchejie.cn/Article/details/gt2jwjwrtmt.html

Ruby: rescue ArgumentError => e
来源：http://dali.gotoacloud.top/Article/details/gt2oqaanmua.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jiagoushi.top/Article/details/gt2drdfkdwq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hammf.cn/Article/details/gt2jxwygzuy.html

Py:   value = d.get("k") or default
来源：http://dali.gaohongyu789.top/Article/details/gt2paxyxkyq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.feifeiyinyue.top/Article/details/gt2dkrpnlqi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gt2edkliwpl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sxryk.cn/Article/details/gt2udllibae.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yueranfly.top/Article/details/gt2nblklary.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhixingplan.top/Article/details/gt2zzlofgte.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yueranfly.top/Article/details/gt2eqhoxrwr.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gt2shpaylaz.html

[H07] 断言
来源：http://dali.daria6918.cn/Article/details/gt2mrcapxan.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenlongwang.top/Article/details/gt2uzjnagwb.html

PHP:  assert($x > 0);
来源：http://dali.gzhubu.top/Article/details/gt2nbubkgio.html

JS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gt2blyczocc.html

TS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2kcjfnfcc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tian-w.cn/Article/details/gt2tyxhrcba.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.fzhhl.top/Article/details/gt2xiaaosxg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.fengsongda.top/Article/details/gt2pbkrvocp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gt2pvokxgwx.html

[H08] 获取错误信息与堆栈
来源：http://dali.sweek.top/Article/details/gt2uvcowoar.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.0kj1m.cn/Article/details/gt2bfelnokb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yqfhifct.html

JS:   e.message;  e.stack
来源：http://dali.chenlongwang.top/Article/details/gt2hzmtsorh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.redwolf501.top/Article/details/gt2vshqbuqg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jiagoushi.top/Article/details/gt2mziyfkkg.html

Go:   err.Error()
来源：http://dali.cdnleiting.top/Article/details/gt2wspudljc.html

Ruby: e.message;  e.backtrace
来源：http://dali.nwbrower.top/Article/details/gt2smfwvbfx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fzhhl.top/Article/details/gt2kwddygfy.html

[H09] 带错误码的异常
来源：http://dali.jyoumei.cn/Article/details/gt2jxcmlawr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhiwuduotai.top/Article/details/gt2uipldmgx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.meibo888.top/Article/details/gt2yajfrvmo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.feifeiyinyue.top/Article/details/gt2wvuqtvzy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yangfankeji.com/Article/details/gt2ujubclvd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hysaishi.cn/Article/details/gt2kgghcbco.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xyfdljlj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj20258888.top/Article/details/gt2fjjnedva.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xuetiantiany.cn/Article/details/gt2edwtywik.html

[H10] 资源自动释放
来源：http://dali.hywenlv.cn/Article/details/gt2drqxtksh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.wangdashe.top/Article/details/gt2ytlaicza.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tian-w.cn/Article/details/gt2brvmrlna.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gt2byfjvbhf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gt2uhdqodsf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hysaishi.cn/Article/details/gt2wctrwqgi.html

Go:   defer f.Close()
来源：http://dali.c1oappe.top/Article/details/gt2uvoqzmym.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hfpthk.cn/Article/details/gt2fywfjuvg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2tmfwnnam.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2ctmdxgkw.html

I. 正则表达式
来源：http://dali.bjfxy.top/Article/details/gt2jgzqpmtj.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2jogzyihh.html

[I01] 判断是否匹配
来源：http://dali.xylfe.cn/Article/details/gt2krfoebhk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cucudq.cn/Article/details/gt2owejjccv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2aupihpfl.html

JS:   /\d+/.test(s)
来源：http://dali.yangfankeji.com/Article/details/gt2dbaibruw.html

TS:   /\d+/.test(s)
来源：http://dali.yuanzhike.top/Article/details/gt2oblwgrvj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tian-w.cn/Article/details/gt2katqlqbw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shuidangran.top/Article/details/gt2iplytncq.html

Ruby: s.match?(/\d+/)
来源：http://dali.vqdsnc.cn/Article/details/gt2ngnripql.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cheryme.top/Article/details/gt2epazvxzq.html

[I02] 提取所有匹配
来源：http://dali.yuanzhike.top/Article/details/gt2gcvpvgex.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hfpthk.cn/Article/details/gt2oaogmvla.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dashuyun.cn/Article/details/gt2kryfyoiz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.mhx1999.top/Article/details/gt2cmdnrlqf.html

TS:   s.match(/\d+/g)
来源：http://dali.jianghu66.top/Article/details/gt2qgxcldfl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cashguo.top/Article/details/gt2epuymqyh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ybcxt.top/Article/details/gt2kbsyprtk.html

Ruby: s.scan(/\d+/)
来源：http://dali.gogol.net.cn/Article/details/gt2atqxgaqy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cqqwz.cn/Article/details/gt2scuwtlrf.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fydxijfw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cdnleiting.top/Article/details/gt2wzmqwwag.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ppjwa.cn/Article/details/gt2jayeoahe.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oyuzlawf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xuanzx.com/Article/details/gt2iinblywb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xziqi.cn/Article/details/gt2uvypnoil.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.316326.xyz/Article/details/gt2orfwsrbm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shuidangran.top/Article/details/gt2wojhsnxy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenlongwang.top/Article/details/gt2fdojjbsb.html

[I04] 正则替换
来源：http://dali.nanxinkj.top/Article/details/gt2kcmcghhd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.wangdashe.top/Article/details/gt2nioauyxp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2beihaphh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.smart0.xyz/Article/details/gt2gnchmbje.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jianghu66.top/Article/details/gt2mgfefauv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenlongwang.top/Article/details/gt2scqrgpkv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2tabizoeu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj20258888.top/Article/details/gt2gbhobgkl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cashguo.top/Article/details/gt2tmndvnqs.html

[I05] 按正则拆分
来源：http://dali.shuidangran.top/Article/details/gt2xxkipgjf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenlongwang.top/Article/details/gt2bwdalxso.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gt2ufwlmsdm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gt2pyaaheea.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gt2lxtkrviz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.c1oappe.top/Article/details/gt2lumwzteg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xziqi.cn/Article/details/gt2baexerku.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gt2ehmgmjqe.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zdqjudy.top/Article/details/gt2yqjankcb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhengqikj.top/Article/details/gt2gtdqstoi.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gt2hggdgosd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zycfv.cn/Article/details/gt2bigiuluc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gt2suuqzxzd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgufenzy.top/Article/details/gt2pplavuql.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gt2yskdhdov.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iotryxqr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.pengpengdd.cyou/Article/details/gt2hfgubyjo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gt2tsdotsju.html

[I07] 忽略大小写与多行模式
来源：http://dali.mhx1999.top/Article/details/gt2lxcmgyfn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hammf.cn/Article/details/gt2ilqghzyk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gt2telbysgx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yanxiufei.cn/Article/details/gt2woedttfp.html

TS:   /error/gim
来源：http://dali.smart0.xyz/Article/details/gt2dhyhfmdh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cheryme.top/Article/details/gt2qfrwcbws.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cdnleiting.top/Article/details/gt2qwskhldg.html

Ruby: s.scan(/error/i)
来源：http://dali.ybcxt.top/Article/details/gt2iahufbzz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qxtzvkpz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xuanzx.com/Article/details/gt2lkiifwtj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tian-w.cn/Article/details/gt2dhkyvayz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.c1oappe.top/Article/details/gt2fxznssii.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xylfe.cn/Article/details/gt2sezxetty.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gt2nlkgknxb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.daxiang520.top/Article/details/gt2pllhfmyc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daxiang520.top/Article/details/gt2cxyvbisu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hywenlv.cn/Article/details/gt2cshmglyd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xuanzx.com/Article/details/gt2ceoxmrzi.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2hjuihujs.html

J. 日期与时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bkrewxuw.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2wcnzcuow.html

[J01] 获取当前时间
来源：http://dali.aibaodan.cn/Article/details/gt2acpqvnud.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.haohaochexian.top/Article/details/gt2tglolbzl.html


<!-- 参考信息 -->