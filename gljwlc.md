代发 wailian999

Ruby: @name = "x"
来源：http://dali.yonumen.top/Article/details/gtjdswvicf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xuanzx.com/Article/details/gtgpniubqz.html

[G04] 定义方法
来源：http://dali.c1oappe.top/Article/details/gtwuvkxkvq.html

Py:   def greet(self): return self.name
来源：http://dali.shuidangran.top/Article/details/gttpjlbgfb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gtbmphctwq.html

JS:   greet() { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtkvuhsmsr.html

TS:   greet(): string { return this.name; }
来源：http://dali.cashguo.top/Article/details/gtgmwaufcm.html

Java: String greet() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmxmuklgq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtxsnyiphx.html

Ruby: def greet; @name; end
来源：http://dali.snrcjt.cn/Article/details/gtfhfcwfxg.html

C#:   public string Greet() => Name;
来源：http://dali.yj20258888.top/Article/details/gteqkidkqe.html

[G05] 继承
来源：http://dali.chenlongwang.top/Article/details/gtxogicjnv.html

Py:   class Admin(User): pass
来源：http://dali.birdmap.top/Article/details/gttvxmubdd.html

PHP:  class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtdaqiuxyk.html

JS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvzacrhr.html

TS:   class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtyrlelfkv.html

Java: class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtqoehnpoy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ywan-chungtsiang.top/Article/details/gtseqqdazb.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmsslmjlr.html

C#:   class Admin : User {}
来源：http://dali.yvedp.cn/Article/details/gteapkshkr.html

[G06] 重写方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkhhqdxaa.html

Py:   def greet(self): return "admin"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxducoyu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtuybygutn.html

JS:   greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvzcgzzis.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtktmypluu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtosewckbw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hywenlv.cn/Article/details/gtmtnehesm.html

Ruby: def greet; "admin"; end
来源：http://dali.iojbl.cn/Article/details/gtwpplltgz.html

C#:   public override string Greet() => "admin";
来源：http://dali.hywenlv.cn/Article/details/gtkxyfqrao.html

[G07] 调用父类方法
来源：http://dali.shangyingyoupin.top/Article/details/gtmsbwxxfk.html

Py:   super().greet()
来源：http://dali.zhixingplan.top/Article/details/gtxtrlqctm.html

PHP:  parent::greet();
来源：http://dali.gotoacloud.top/Article/details/gtixgmpefz.html

JS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gtrclrsdbs.html

TS:   super.greet();
来源：http://dali.hysaishi.cn/Article/details/gtpezcyedk.html

Java: super.greet();
来源：http://dali.tian-w.cn/Article/details/gtktztjdec.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxpkqizne.html

Ruby: super
来源：http://dali.chenlongwang.top/Article/details/gtjmltblie.html

C#:   base.Greet();
来源：http://dali.9152youxi.cn/Article/details/gtrbtoqetw.html

[G08] 静态方法与属性
来源：http://dali.sweek.top/Article/details/gtqmtwtgme.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.snrcjt.cn/Article/details/gtxawowrtj.html

PHP:  public static function f() {}
来源：http://dali.cheryme.top/Article/details/gtjwdvmrdu.html

JS:   static f() {}
来源：http://dali.nanxuanxn.top/Article/details/gtjacsuekn.html

TS:   static f(): void {}
来源：http://dali.jianghu66.top/Article/details/gtfuncftsn.html

Java: static void f() {}
来源：http://dali.iojbl.cn/Article/details/gtrjhjiwbw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ydzc1.top/Article/details/gthmdxpsuh.html

Ruby: def self.f; end
来源：http://dali.chenjidiqi.icu/Article/details/gtvyuxtelk.html

C#:   public static void F() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtowobfnhq.html

[G09] 接口 / 抽象类
来源：http://dali.yvedp.cn/Article/details/gtgkwytrha.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.dashuyun.cn/Article/details/gtoyfjtnow.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hammf.cn/Article/details/gtoqduyhvm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cqqwz.cn/Article/details/gtainmtpvg.html

TS:   interface Shape { area(): number; }
来源：http://dali.andypj.xyz/Article/details/gtsktyxcvc.html

Java: interface Shape { double area(); }
来源：http://dali.fzhhl.top/Article/details/gtgdjveyji.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yanxiufei.cn/Article/details/gtoygfrvlh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ehwqpu.com/Article/details/gtjyyuyske.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj202588.top/Article/details/gtfurkzqsk.html

[G10] 访问控制
来源：http://dali.yangfankeji.com/Article/details/gtnrcmcvht.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sufxvd.cn/Article/details/gtvzfjjevz.html

PHP:  public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gteszcfsuo.html

JS:   #private 字段；其余公开
来源：http://dali.jlsjyb.cn/Article/details/gtwlavdfyy.html

TS:   public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gtdknwyuju.html

Java: public / protected / private / 默认包级
来源：http://dali.xuetiantiany.cn/Article/details/gtmrmsmwla.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.meibo888.top/Article/details/gtktikfuvq.html

Ruby: public / protected / private
来源：http://dali.gzhubu.top/Article/details/gteafyjhqm.html

C#:   public / protected / private / internal
来源：http://dali.tanke756.top/Article/details/gtrgakiupp.html

[G11] getter / setter
来源：http://dali.yvedp.cn/Article/details/gtoijncvzn.html

Py:   @property 与 @x.setter
来源：http://dali.hfpthk.cn/Article/details/gtwxbvpzdc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtpdwyogwm.html

JS:   get name() { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gtbunmvhjx.html

TS:   get name(): string { return this._name; }
来源：http://dali.gaohongyu789.top/Article/details/gtgdzaqnjk.html

Java: public String getName() { return name; }
来源：http://dali.redwolf501.top/Article/details/gteiibtuza.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gtsdywsdub.html

Ruby: attr_accessor :name
来源：http://dali.dashuyun.cn/Article/details/gtgiucpoty.html

C#:   public string Name { get; set; }
来源：http://dali.kuanghao11.cn/Article/details/gtihkcmmeb.html

[G12] 对象转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidhzslld.html

Py:   def __str__(self): return self.name
来源：http://dali.ehwqpu.com/Article/details/gtmhharoph.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gtitxifdqp.html

JS:   toString() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gthvasoxzo.html

TS:   toString(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtajtujpop.html

Java: @Override public String toString() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtzqybtdsu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gttqgasbwe.html

Ruby: def to_s; @name; end
来源：http://dali.sxryk.cn/Article/details/gtrtcjqhou.html

C#:   public override string ToString() => Name;
来源：http://dali.redwolf501.top/Article/details/gtvfdgrtji.html

[G13] 判断对象类型
来源：http://dali.nanxuanxn.top/Article/details/gtqfitrrzs.html

Py:   isinstance(u, User)
来源：http://dali.316326.xyz/Article/details/gtxbpofhrz.html

PHP:  $u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtbzunrgtq.html

JS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtacschezk.html

TS:   u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gtczcrhxyv.html

Java: u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtsryzyopy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tanke756.top/Article/details/gttgfcuvsc.html

Ruby: u.is_a?(User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtssznkypt.html

C#:   u is User
来源：http://dali.zhengqikj.top/Article/details/gtlbvbyolh.html

[G14] 数据类 / record
来源：http://dali.jyoumei.cn/Article/details/gtppayrowb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hongshengwenyu.top/Article/details/gtwklvqvco.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigfzy.top/Article/details/gtivseaele.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sufxvd.cn/Article/details/gtoxnrdbju.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj202588.top/Article/details/gtxdusepyq.html

Java: record User(String name, int age) {}
来源：http://dali.sweek.top/Article/details/gtzxblimqz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hfpthk.cn/Article/details/gtidhepfmu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sxryk.cn/Article/details/gtfghwhoct.html

C#:   record User(string Name, int Age);
来源：http://dali.gaohongyu789.top/Article/details/gtcemwbifv.html

[G15] 枚举
来源：http://dali.jinqigfzy.top/Article/details/gtfsuxkgnu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenlongwang.top/Article/details/gtowehaffr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhengqikj.top/Article/details/gtlivmypfw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cucudq.cn/Article/details/gtibaobfux.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zycfv.cn/Article/details/gthgtmgfxy.html

Java: enum Color { RED, GREEN }
来源：http://dali.nwbrower.top/Article/details/gtubogxgbt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ybcxt.top/Article/details/gttodgcixd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.dianchejie.cn/Article/details/gtlbtytkks.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gtdnwdjuao.html

[G16] 对象转数组 / 字典
来源：http://dali.yuxming.cn/Article/details/gtpnrghlhs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhengqikj.top/Article/details/gtliuhclts.html

PHP:  get_object_vars($obj);
来源：http://dali.hnqzz.top/Article/details/gtdzehotaw.html

JS:   Object.entries(obj)
来源：http://dali.svipenyu.cn/Article/details/gtxmblnghu.html

TS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gtsscbzgua.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nanxinkj.top/Article/details/gtqizafcee.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgufenzy.top/Article/details/gtgjsujuhp.html

Ruby: obj.instance_variables
来源：http://dali.sysykeji.top/Article/details/gtmwigatsr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gtbbylxibc.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtqzevbeba.html

H. 异常与错误处理
来源：http://dali.pycfn.com/Article/details/gtjpxdgmtk.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtwrzmwcyj.html

[H01] try / catch 基础
来源：http://dali.gzhubu.top/Article/details/gtvzgknvmk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.pycfn.com/Article/details/gtrymhxjja.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gaohongyu789.top/Article/details/gtgvynguxo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gtsjedzheh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gtkhzsfmeq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.iojbl.cn/Article/details/gtcmoxvdgw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sysykeji.top/Article/details/gtgofuqubz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gtbunzgluf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.316326.xyz/Article/details/gtkfxyuzua.html

[H02] finally / ensure 收尾
来源：http://dali.dianchejie.cn/Article/details/gtcqjwffzi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xuetiantiany.cn/Article/details/gtjiqdcjdt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtndyrkhny.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtcualwumy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtzknuljkk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtdjeserfq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenlongwang.top/Article/details/gtfgrfmuwm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cucudq.cn/Article/details/gtzfrzhfoe.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtdpfxvodf.html

[H03] 主动抛出异常
来源：http://dali.haohaochexian.top/Article/details/gtawiwblzt.html

Py:   raise ValueError("错误信息")
来源：http://dali.dianchejie.cn/Article/details/gttsoqwmxb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gtwdqnlotg.html

JS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtssikhucb.html

TS:   throw new Error("错误信息");
来源：http://dali.meibo888.top/Article/details/gtjeafpxia.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtmvccqtbb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.feifeiyinyue.top/Article/details/gtmcemmpyo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hywenlv.cn/Article/details/gtjlefhhec.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gteqnboopg.html

[H04] 自定义异常类型
来源：http://dali.hammf.cn/Article/details/gtgapzfahs.html

Py:   class MyError(Exception): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxeoizdy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gtwgxwpxfp.html

JS:   class MyError extends Error {}
来源：http://dali.zycfv.cn/Article/details/gtanfkrvog.html

TS:   class MyError extends Error {}
来源：http://dali.wangshuangyany.cn/Article/details/gtaesjxdsp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gtxbatuzuq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ydzc1.top/Article/details/gtqacfntdt.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenzaomai.com/Article/details/gtuafcfgdn.html

C#:   class MyException : Exception {}
来源：http://dali.yongpay.top/Article/details/gtjphdrlnu.html

[H05] 捕获特定类型
来源：http://dali.fzhhl.top/Article/details/gtirbgaslh.html

Py:   except ValueError as e:
来源：http://dali.xuanzx.com/Article/details/gtxtucetzv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtofhjojew.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hnqzz.top/Article/details/gtkugfpmgc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gthkprlchq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ehwqpu.com/Article/details/gtpjdmabhl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xuetiantiany.cn/Article/details/gtmclzvwlo.html

Ruby: rescue ArgumentError => e
来源：http://dali.yvedp.cn/Article/details/gtdgxtzold.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jianghu66.top/Article/details/gtmsxcecvf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.pengpengdd.cyou/Article/details/gturxpnqmv.html

Py:   value = d.get("k") or default
来源：http://dali.hnxiangtu.top/Article/details/gtfrqwnmtb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gtzghqqvuh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jyoumei.cn/Article/details/gtixhaepuo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cdnleiting.top/Article/details/gtdxwkihxa.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.dianchejie.cn/Article/details/gtepjvcxfp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shzxlz.cn/Article/details/gtduprzpsw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gtuucugpqt.html

C#:   obj?.A?.B ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtvuwiddjt.html

[H07] 断言
来源：http://dali.xinyue.icu/Article/details/gtgprvsmzt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.guowangkeji.top/Article/details/gtanlomjvr.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtqjzxlsgo.html

JS:   console.assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gtkeqcojqe.html

TS:   console.assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gtksnywbhx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.fengsongda.top/Article/details/gtctsfjjon.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.9152youxi.cn/Article/details/gtpxxpqdwc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jqgufenzy.top/Article/details/gtvqihrusi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtuwgtmpej.html

[H08] 获取错误信息与堆栈
来源：http://dali.tanke756.top/Article/details/gttfhrysxr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jiagoushi.top/Article/details/gtxvqoacfs.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yvedp.cn/Article/details/gtxktrvstk.html

JS:   e.message;  e.stack
来源：http://dali.smart0.xyz/Article/details/gtnvoyxreq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yongpay.top/Article/details/gtcmodypjz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shuidangran.top/Article/details/gtvsdmzica.html

Go:   err.Error()
来源：http://dali.316326.xyz/Article/details/gtxyolkpni.html

Ruby: e.message;  e.backtrace
来源：http://dali.mhx1999.top/Article/details/gtwcfzhagi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shzxlz.cn/Article/details/gtsltfyupd.html

[H09] 带错误码的异常
来源：http://dali.tian-w.cn/Article/details/gtcnaimiwo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aibaodan.cn/Article/details/gtgcaxlcwb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cucudq.cn/Article/details/gtjpxjwync.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tian-w.cn/Article/details/gtzwspeayi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbiaudwdl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhengqikj.top/Article/details/gttpksmjzh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tian-w.cn/Article/details/gtfcfqsdli.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xuetiantiany.cn/Article/details/gtuvisddbr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xinyue.icu/Article/details/gtzmcdnjfb.html

[H10] 资源自动释放
来源：http://dali.zhixingplan.top/Article/details/gtndbinimz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yvedp.cn/Article/details/gtzgcnkdcc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jyoumei.cn/Article/details/gtmesvoyix.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gtcgufrdru.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gtmzzwgnck.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hfpthk.cn/Article/details/gtyejvyucu.html

Go:   defer f.Close()
来源：http://dali.yonumen.top/Article/details/gtpsxndury.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hongshengwenyu.top/Article/details/gtedvhmouv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtvauvqgbo.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtlghziiei.html

I. 正则表达式
来源：http://dali.shangyingyoupin.top/Article/details/gtnhguzjyy.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtzcqjfeis.html

[I01] 判断是否匹配
来源：http://dali.zdqjudy.top/Article/details/gtzcwvypsc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ybcxt.top/Article/details/gtcoscvysb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.fzhhl.top/Article/details/gtzasgtptj.html

JS:   /\d+/.test(s)
来源：http://dali.guannengcc.top/Article/details/gtqjnjbsyi.html

TS:   /\d+/.test(s)
来源：http://dali.andypj.xyz/Article/details/gtefyszoho.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shangyingyoupin.top/Article/details/gtffefvjra.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinqigfzy.top/Article/details/gtyxgsedlb.html

Ruby: s.match?(/\d+/)
来源：http://dali.daxiang520.top/Article/details/gthulwqohv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sysykeji.top/Article/details/gtpozgymav.html

[I02] 提取所有匹配
来源：http://dali.yangfankeji.com/Article/details/gtqioajfhy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.redwolf501.top/Article/details/gtpiragkjd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.c1oappe.top/Article/details/gtfwoeedrc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xinyue.icu/Article/details/gtgebpwowc.html

TS:   s.match(/\d+/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrzfsont.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.quarkkingdee.top/Article/details/gtqavevorw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.aizwys.cn/Article/details/gtvvxmtlwl.html

Ruby: s.scan(/\d+/)
来源：http://dali.yvedp.cn/Article/details/gtwtmlwrwm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtrhgsmany.html

[I03] 提取捕获分组
来源：http://dali.nanxinkj.top/Article/details/gtlqvwsnss.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.kuanghao11.cn/Article/details/gtknenlwvh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.haohaochexian.top/Article/details/gtobsvagmi.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhoulong.xyz/Article/details/gtgjqsqiid.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.andypj.xyz/Article/details/gtklsfnoic.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yueranfly.top/Article/details/gtbooeuukc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gotoacloud.top/Article/details/gticairmoo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ehwqpu.com/Article/details/gtmgxzuvcq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gzhubu.top/Article/details/gtiivecnch.html

[I04] 正则替换
来源：http://dali.0kj1m.cn/Article/details/gtmomqpodp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ivvv.top/Article/details/gtkdseqemc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtaabwipuu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.quarkkingdee.top/Article/details/gthcckinkw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xuanzx.com/Article/details/gtepuhsnxs.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gtclghxzdg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tian-w.cn/Article/details/gtovgemjuf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ybcxt.top/Article/details/gtcwhwonbw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.dashuyun.cn/Article/details/gtjtyiqkcv.html

[I05] 按正则拆分
来源：http://dali.9152youxi.cn/Article/details/gtngxzpwxa.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.c1oappe.top/Article/details/gtbisyoajw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yonumen.top/Article/details/gtmwoaikju.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtplzvjkvw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gtmkjitnko.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hnxiangtu.top/Article/details/gthqnibfzf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.316326.xyz/Article/details/gtdjlvibof.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gtiutozbht.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.snrcjt.cn/Article/details/gtjnhbbjxa.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.meibo888.top/Article/details/gtiolpfvby.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.fengsongda.top/Article/details/gtpzavgapa.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.316326.xyz/Article/details/gtkidfpllh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gtaplnyedp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgfzy.top/Article/details/gtpibiszll.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gtvlmnaiwn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jiagoushi.top/Article/details/gtgctzenzr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cashguo.top/Article/details/gtrhqkvtqx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.316326.xyz/Article/details/gtmmiepmte.html

[I07] 忽略大小写与多行模式
来源：http://dali.nwbrower.top/Article/details/gtefgpzesr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteajsayou.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gtnzksgbhi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yongpay.top/Article/details/gtjoxfqvkq.html

TS:   /error/gim
来源：http://dali.hammf.cn/Article/details/gtdmealnna.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shangyingyoupin.top/Article/details/gtpqrpoqtt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.316326.xyz/Article/details/gtpqcvisct.html

Ruby: s.scan(/error/i)
来源：http://dali.fzhhl.top/Article/details/gtazycvmir.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hongshengwenyu.top/Article/details/gtgkpgshve.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.havefunace.top/Article/details/gtatpwzyvr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zdqjudy.top/Article/details/gthumianlh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xziqi.cn/Article/details/gtibtinavy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gttqnrigyd.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuanzhike.top/Article/details/gtalhbjkcq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jqgfzy.top/Article/details/gtwkaugueb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xuanzx.com/Article/details/gtaglaavth.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.havefunace.top/Article/details/gtsnrimatr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenjidiqi.icu/Article/details/gtxbqrsnmp.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtzbhgbplj.html

J. 日期与时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtanbymsus.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtcipwtfgx.html

[J01] 获取当前时间
来源：http://dali.tanke756.top/Article/details/gtgnynjtuw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.fzhhl.top/Article/details/gthmtzxlxx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuxming.cn/Article/details/gtyqvmacyw.html

JS:   new Date();  Date.now()
来源：http://dali.ivvv.top/Article/details/gtxvnfgoon.html

TS:   new Date();  Date.now()
来源：http://dali.316326.xyz/Article/details/gtyaeqxlzw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nanxinkj.top/Article/details/gtsolcjuvl.html

Go:   time.Now()
来源：http://dali.yangfankeji.com/Article/details/gtinmtrfrr.html

Ruby: Time.now
来源：http://dali.cdnleiting.top/Article/details/gtwosnwirp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.316326.xyz/Article/details/gtsdgsduew.html

[J02] 格式化输出
来源：http://dali.jqgufenzy.top/Article/details/gtdmauhdit.html


<!-- 参考信息 -->