代发 wailian999

Py:   class Admin(User): pass
来源：http://dali.gotoacloud.top/Article/details/gtvpdjrxli.html

PHP:  class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtdpocntpe.html

JS:   class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtzuxymhto.html

TS:   class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gttkdbccll.html

Java: class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtcacqucoe.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuetiantiany.cn/Article/details/gtnzwcnnwq.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtcigxgdzp.html

C#:   class Admin : User {}
来源：http://dali.yanxiufei.cn/Article/details/gtkcqsunnm.html

[G06] 重写方法
来源：http://dali.jinqigufen.top/Article/details/gtgtftzzvj.html

Py:   def greet(self): return "admin"
来源：http://dali.yongpay.top/Article/details/gtpuzblzue.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtpygmwpxk.html

JS:   greet() { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtfgoruzdw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtearaqigx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtqbajsxwj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yonumen.top/Article/details/gtcltulsix.html

Ruby: def greet; "admin"; end
来源：http://dali.sufxvd.cn/Article/details/gtmheikxwd.html

C#:   public override string Greet() => "admin";
来源：http://dali.hfpthk.cn/Article/details/gtfyhogqlc.html

[G07] 调用父类方法
来源：http://dali.yuxming.cn/Article/details/gtfejrwljo.html

Py:   super().greet()
来源：http://dali.zhongyouzk.top/Article/details/gtkensyaaw.html

PHP:  parent::greet();
来源：http://dali.gotoacloud.top/Article/details/gtgomckvbd.html

JS:   super.greet();
来源：http://dali.dashuyun.cn/Article/details/gtcgdhmhkt.html

TS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gtbngcaxzn.html

Java: super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtqfuswrqh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.pengpengdd.cyou/Article/details/gtobfopejx.html

Ruby: super
来源：http://dali.quarkkingdee.top/Article/details/gthbngbesu.html

C#:   base.Greet();
来源：http://dali.zhengqikj.top/Article/details/gteyddumed.html

[G08] 静态方法与属性
来源：http://dali.ehwqpu.com/Article/details/gtzlhitchs.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nanxuanxn.top/Article/details/gtdzysealn.html

PHP:  public static function f() {}
来源：http://dali.yj20258.top/Article/details/gtguopecfc.html

JS:   static f() {}
来源：http://dali.chenzaomai.com/Article/details/gthaicbpti.html

TS:   static f(): void {}
来源：http://dali.smart0.xyz/Article/details/gtsjnbzzes.html

Java: static void f() {}
来源：http://dali.sxryk.cn/Article/details/gtljjqijpl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cashguo.top/Article/details/gthurctsds.html

Ruby: def self.f; end
来源：http://dali.yangfankeji.com/Article/details/gtdmjststf.html

C#:   public static void F() {}
来源：http://dali.shuidangran.top/Article/details/gtcxsltimy.html

[G09] 接口 / 抽象类
来源：http://dali.gzhubu.top/Article/details/gtmhotsgrf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.vqdsnc.cn/Article/details/gteunpiamy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cheryme.top/Article/details/gttvpkczov.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shangyingyoupin.top/Article/details/gtilrkpqev.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhengqikj.top/Article/details/gtellbpjie.html

Java: interface Shape { double area(); }
来源：http://dali.guowangkeji.top/Article/details/gtjvxbhwse.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ehwqpu.com/Article/details/gtriibovez.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guowangkeji.top/Article/details/gtprltxsez.html

C#:   interface IShape { double Area(); }
来源：http://dali.jianghu66.top/Article/details/gtliugozqm.html

[G10] 访问控制
来源：http://dali.wangdashe.top/Article/details/gtmhqqwwbp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zdqjudy.top/Article/details/gtqtcrnfww.html

PHP:  public / protected / private
来源：http://dali.mhx1999.top/Article/details/gttfaczuad.html

JS:   #private 字段；其余公开
来源：http://dali.xuetiantiany.cn/Article/details/gtmoixwegg.html

TS:   public / protected / private
来源：http://dali.ybcxt.top/Article/details/gtyzbfyhvb.html

Java: public / protected / private / 默认包级
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtckuoehwb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nanxuanxn.top/Article/details/gtbgjfarbg.html

Ruby: public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtipeaedqq.html

C#:   public / protected / private / internal
来源：http://dali.redwolf501.top/Article/details/gtmzhiisfv.html

[G11] getter / setter
来源：http://dali.hywenlv.cn/Article/details/gtsehglefq.html

Py:   @property 与 @x.setter
来源：http://dali.mhx1999.top/Article/details/gtwkucrmih.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gtmvtwpsok.html

JS:   get name() { return this._name; }
来源：http://dali.yuxming.cn/Article/details/gtzmrcspmx.html

TS:   get name(): string { return this._name; }
来源：http://dali.aizwys.cn/Article/details/gtusngniwj.html

Java: public String getName() { return name; }
来源：http://dali.sweek.top/Article/details/gtrchopamu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gtlcupbite.html

Ruby: attr_accessor :name
来源：http://dali.ehwqpu.com/Article/details/gtzpcxqgqy.html

C#:   public string Name { get; set; }
来源：http://dali.zhiwuduotai.top/Article/details/gtfbeaedxd.html

[G12] 对象转字符串
来源：http://dali.mhx1999.top/Article/details/gtdnwxudnq.html

Py:   def __str__(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gtlwzuwesk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtronrglep.html

JS:   toString() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtzuvwrqce.html

TS:   toString(): string { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtyqibovua.html

Java: @Override public String toString() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtlabdwdno.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.0kj1m.cn/Article/details/gtibknydcc.html

Ruby: def to_s; @name; end
来源：http://dali.jqgufenzy.top/Article/details/gtsufhpgfc.html

C#:   public override string ToString() => Name;
来源：http://dali.yanxiufei.cn/Article/details/gtwlkeqmlo.html

[G13] 判断对象类型
来源：http://dali.jianghu66.top/Article/details/gtbosquhsn.html

Py:   isinstance(u, User)
来源：http://dali.nwbrower.top/Article/details/gtddgicxmo.html

PHP:  $u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtryclvwfa.html

JS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtusgdukeb.html

TS:   u instanceof User
来源：http://dali.cheryme.top/Article/details/gtujanvgrx.html

Java: u instanceof User
来源：http://dali.316326.xyz/Article/details/gtvdalzjrc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.guowangkeji.top/Article/details/gtzqnrwaph.html

Ruby: u.is_a?(User)
来源：http://dali.jqgfzy.top/Article/details/gtmiyvdljh.html

C#:   u is User
来源：http://dali.hammf.cn/Article/details/gthtuhqmhx.html

[G14] 数据类 / record
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuybymykn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cdnleiting.top/Article/details/gtyenxpapm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jianghu66.top/Article/details/gtvpyjttbr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.0kj1m.cn/Article/details/gthtrcojmm.html

TS:   type User = { name: string; age: number };
来源：http://dali.aizwys.cn/Article/details/gtohkbiwvc.html

Java: record User(String name, int age) {}
来源：http://dali.ivvv.top/Article/details/gtwfttjryd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cqqwz.cn/Article/details/gtwsoyfikg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenzaomai.com/Article/details/gtsyiyecxf.html

C#:   record User(string Name, int Age);
来源：http://dali.jiagoushi.top/Article/details/gtupjtemrp.html

[G15] 枚举
来源：http://dali.pycfn.com/Article/details/gtypfuiyro.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenjidiqi.icu/Article/details/gtxocipxja.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.haohaochexian.top/Article/details/gtgzqalzhc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigfzy.top/Article/details/gtombjnjot.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.c1oappe.top/Article/details/gtzdtisifg.html

Java: enum Color { RED, GREEN }
来源：http://dali.tianlin.xyz/Article/details/gtsvicwbvl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangdashe.top/Article/details/gtfpntdqbd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangdashe.top/Article/details/gttofycpxy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuanzx.com/Article/details/gtzmbjzcih.html

[G16] 对象转数组 / 字典
来源：http://dali.sxryk.cn/Article/details/gtdeznwquu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shzxlz.cn/Article/details/gtlskavxjz.html

PHP:  get_object_vars($obj);
来源：http://dali.havefunace.top/Article/details/gtzgcstcoe.html

JS:   Object.entries(obj)
来源：http://dali.cdnleiting.top/Article/details/gtbqximrps.html

TS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gtdtpbvlii.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jyoumei.cn/Article/details/gtvnbqifrl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daria6918.cn/Article/details/gtnlwbtsww.html

Ruby: obj.instance_variables
来源：http://dali.shzxlz.cn/Article/details/gtqplidugq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yonumen.top/Article/details/gtkjdkcibr.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtjfavqhrl.html

H. 异常与错误处理
来源：http://dali.nanxinkj.top/Article/details/gtvvrygaqs.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtymitbmtw.html

[H01] try / catch 基础
来源：http://dali.yangfankeji.com/Article/details/gtxtqjvoeg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yonumen.top/Article/details/gtudnqpxmk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj202588.top/Article/details/gtrfvgqckl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hammf.cn/Article/details/gtiulgyzbz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gtarvmwmmy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.meibo888.top/Article/details/gtmcvfgvba.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.daria6918.cn/Article/details/gtbpbflhdz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxoksoel.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.haohaochexian.top/Article/details/gtttazmasl.html

[H02] finally / ensure 收尾
来源：http://dali.jqgufenzy.top/Article/details/gtzxbwvprl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xuetiantiany.cn/Article/details/gtiobumqkv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpckyvyhq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtgmigkosj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtpyquoydw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtkqjpkzyr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jianghu66.top/Article/details/gttheicjsn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gogol.net.cn/Article/details/gthmojskvg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtqnznhthw.html

[H03] 主动抛出异常
来源：http://dali.guannengcc.top/Article/details/gtaolatyyp.html

Py:   raise ValueError("错误信息")
来源：http://dali.kuanghao11.cn/Article/details/gtpuyyxxbu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtdqmxlzbm.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwffwqdbo.html

TS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtktqnspdd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtwveoxjkf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxuanxn.top/Article/details/gtusomhekc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258888.top/Article/details/gtwzmmgrjr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtvweqwgfk.html

[H04] 自定义异常类型
来源：http://dali.zhoulong.xyz/Article/details/gtrldgdyhy.html

Py:   class MyError(Exception): pass
来源：http://dali.daxiang520.top/Article/details/gtwoewftwu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ydzc1.top/Article/details/gteoagejbs.html

JS:   class MyError extends Error {}
来源：http://dali.yj20258888.top/Article/details/gtdiumzmcr.html

TS:   class MyError extends Error {}
来源：http://dali.fengsongda.top/Article/details/gtpyxtgfea.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhoulong.xyz/Article/details/gtcebfhiyn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cheryme.top/Article/details/gtxczrcyev.html

Ruby: class MyError < StandardError; end
来源：http://dali.yanxiufei.cn/Article/details/gthfsagvxk.html

C#:   class MyException : Exception {}
来源：http://dali.cucudq.cn/Article/details/gtdeidztbv.html

[H05] 捕获特定类型
来源：http://dali.jqgfzy.top/Article/details/gtjxbutkpg.html

Py:   except ValueError as e:
来源：http://dali.wangshuangyany.cn/Article/details/gtkrgbgnlz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.birdmap.top/Article/details/gtcvbrrvyl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtxiwkpgms.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtrzvodmva.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenlongwang.top/Article/details/gtwanrdrib.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.smart0.xyz/Article/details/gtsxclqggt.html

Ruby: rescue ArgumentError => e
来源：http://dali.yuanzhike.top/Article/details/gtpgbbejit.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdiinevlg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cashguo.top/Article/details/gtqwpcgiod.html

Py:   value = d.get("k") or default
来源：http://dali.bjfxy.top/Article/details/gtkyjdnyrl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shzxlz.cn/Article/details/gtavjdesqm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gtzwpecrjk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gaohongyu789.top/Article/details/gtdjnsftvk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hammf.cn/Article/details/gtyfsdndxm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhixingplan.top/Article/details/gtstoeiiqq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangshuangyany.cn/Article/details/gtuszxtfwn.html

C#:   obj?.A?.B ?? default
来源：http://dali.ppjwa.cn/Article/details/gtqqhrmeoh.html

[H07] 断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteckdkujx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.svipenyu.cn/Article/details/gtduonxunp.html

PHP:  assert($x > 0);
来源：http://dali.meibo888.top/Article/details/gtfoeukpxg.html

JS:   console.assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtmrqauskw.html

TS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gtgutmimwz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tanke756.top/Article/details/gtqanynvpf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.kuanghao11.cn/Article/details/gtiwdfdzjc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ehwqpu.com/Article/details/gtuixktzhi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtemarblmk.html

[H08] 获取错误信息与堆栈
来源：http://dali.hnxiangtu.top/Article/details/gtkydaasgz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.redwolf501.top/Article/details/gtseyeieah.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xuetiantiany.cn/Article/details/gtkjovqefz.html

JS:   e.message;  e.stack
来源：http://dali.gzhubu.top/Article/details/gtvzesffxa.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hysaishi.cn/Article/details/gtvzcyunwh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sweek.top/Article/details/gtalvcqdht.html

Go:   err.Error()
来源：http://dali.zhixingplan.top/Article/details/gtirowapum.html

Ruby: e.message;  e.backtrace
来源：http://dali.jiagoushi.top/Article/details/gthpoxdvzt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.haohaochexian.top/Article/details/gttkftpdia.html

[H09] 带错误码的异常
来源：http://dali.hnqzz.top/Article/details/gtcvrnldjn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gotoacloud.top/Article/details/gterpamxmo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.fzhhl.top/Article/details/gthhcealhh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.haohaochexian.top/Article/details/gtoqomtexp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtofqlsswu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jyoumei.cn/Article/details/gtpnozljzu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shangyingyoupin.top/Article/details/gtqmveajkr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nanxuanxn.top/Article/details/gtnozsvorc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jiagoushi.top/Article/details/gtbsyqkjdz.html

[H10] 资源自动释放
来源：http://dali.gogol.net.cn/Article/details/gtfygsusqx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gogol.net.cn/Article/details/gtlcyymhlg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.wangshuangyany.cn/Article/details/gtubckwcyv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gtmkshdzbb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jiagoushi.top/Article/details/gtcynmizvf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cashguo.top/Article/details/gtpvjpisva.html

Go:   defer f.Close()
来源：http://dali.haohaochexian.top/Article/details/gtesrytojj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.aizwys.cn/Article/details/gtryghollf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtlbawgizy.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtwywralmx.html

I. 正则表达式
来源：http://dali.chenjidiqi.icu/Article/details/gtkaivgkdh.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtghsrghwo.html

[I01] 判断是否匹配
来源：http://dali.havefunace.top/Article/details/gthehmqoge.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.kuanghao11.cn/Article/details/gtqvaddnhm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj20258.top/Article/details/gtxxvtkauc.html

JS:   /\d+/.test(s)
来源：http://dali.aibaodan.cn/Article/details/gtfhwtwybj.html

TS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gtjfglhtaw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yangfankeji.com/Article/details/gtyrmvakzh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zycfv.cn/Article/details/gtkhkbvbpl.html

Ruby: s.match?(/\d+/)
来源：http://dali.vqdsnc.cn/Article/details/gtdeyhzwim.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.haohaochexian.top/Article/details/gtenxspgms.html

[I02] 提取所有匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtofyveaho.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xziqi.cn/Article/details/gtwmfaadzq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yanxiufei.cn/Article/details/gtgdsagisb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yanxiufei.cn/Article/details/gtseykewfy.html

TS:   s.match(/\d+/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdcwzrupv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.havefunace.top/Article/details/gtziafkafm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.bjfxy.top/Article/details/gtwfjngqmo.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhiwuduotai.top/Article/details/gtztkukkbr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtbqmyvohm.html

[I03] 提取捕获分组
来源：http://dali.sufxvd.cn/Article/details/gtiyhpcrxr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xinyue.icu/Article/details/gtscbtcvoc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtddsscjrb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xuetiantiany.cn/Article/details/gtfipdfpny.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhengqikj.top/Article/details/gtlitlypgb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.dianchejie.cn/Article/details/gtoqvpklip.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinghuilouyu.cn/Article/details/gtcsxlyjsj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cdnleiting.top/Article/details/gttypumbch.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj202588.top/Article/details/gtzgcinlpa.html

[I04] 正则替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqasjsvfh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.fengsongda.top/Article/details/gtnderolzu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.pycfn.com/Article/details/gtpffctpyn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shzxlz.cn/Article/details/gtopegplzl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sxryk.cn/Article/details/gtwowreacw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hfpthk.cn/Article/details/gtxmneqkty.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xinyue.icu/Article/details/gtaohzrzvj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtepstcjxo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.birdmap.top/Article/details/gtwhiwycjf.html

[I05] 按正则拆分
来源：http://dali.hywenlv.cn/Article/details/gtyepcohdo.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.kuanghao11.cn/Article/details/gtolqwaqkc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtuexaostk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gticaixmdx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gtatrmyswy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.316326.xyz/Article/details/gtetohbtid.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sufxvd.cn/Article/details/gtbioretyq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gthdpnqryj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hongshengwenyu.top/Article/details/gtcudodfyk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jyoumei.cn/Article/details/gtpeiqmgmx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gtogxywtgl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jlsjyb.cn/Article/details/gthtsjwtct.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.andypj.xyz/Article/details/gtmggzrwif.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daria6918.cn/Article/details/gtjjddqbso.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xuanzx.com/Article/details/gtofplrmdm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.wangdashe.top/Article/details/gtzsohwsqp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yonumen.top/Article/details/gtulpxibvo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gtmqglghvf.html

[I07] 忽略大小写与多行模式
来源：http://dali.andypj.xyz/Article/details/gtlxnzzupa.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxzruqzfq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gtumgjhhtz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ydzc1.top/Article/details/gtkqlozusk.html

TS:   /error/gim
来源：http://dali.bjfxy.top/Article/details/gtsylfqinh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.vqdsnc.cn/Article/details/gttlytixmv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hysaishi.cn/Article/details/gttwswlcxt.html

Ruby: s.scan(/error/i)
来源：http://dali.hysaishi.cn/Article/details/gtosrujlud.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gotoacloud.top/Article/details/gtoctyodlm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.andypj.xyz/Article/details/gtzslmzyny.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xziqi.cn/Article/details/gtszgjdsmf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.wangdashe.top/Article/details/gtieiqtyet.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shzxlz.cn/Article/details/gtnlwayqqe.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxuanxn.top/Article/details/gtljxejrve.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xinyue.icu/Article/details/gtkgorubwo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tanke756.top/Article/details/gtgxxzsshw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nwbrower.top/Article/details/gtwhwbsllz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gtizmebutd.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtjpbnvqho.html

J. 日期与时间
来源：http://dali.xinyue.icu/Article/details/gtdnzmswnt.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtermpxmqr.html

[J01] 获取当前时间
来源：http://dali.sysykeji.top/Article/details/gtfxgdorsu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.wangshuangyany.cn/Article/details/gtfhinznke.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gtdeqjknia.html

JS:   new Date();  Date.now()
来源：http://dali.daxiang520.top/Article/details/gtgmqmielx.html

TS:   new Date();  Date.now()
来源：http://dali.daxiang520.top/Article/details/gtgcwiebgw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmmnwzswk.html

Go:   time.Now()
来源：http://dali.sweek.top/Article/details/gtyusautgv.html

Ruby: Time.now
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzshezccu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangkeji.top/Article/details/gttfgjgufx.html

[J02] 格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gtjxufcdrx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hfpthk.cn/Article/details/gtveyjwznd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shangyingyoupin.top/Article/details/gtycncucnt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.andypj.xyz/Article/details/gtswwqqshz.html

TS:   d.toISOString()
来源：http://dali.jiagoushi.top/Article/details/gtdhhogoph.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.daxiang520.top/Article/details/gttiamvzml.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmbqgtud.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fengsongda.top/Article/details/gtrrbikomp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ydzc1.top/Article/details/gtxowoeaqe.html

[J03] 字符串解析为日期
来源：http://dali.wangshuangyany.cn/Article/details/gtpioobfxc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenzaomai.com/Article/details/gtxrlsqmam.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhijiandao.cn/Article/details/gtrgktvuxa.html

JS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtqjercefi.html


<!-- 参考信息 -->