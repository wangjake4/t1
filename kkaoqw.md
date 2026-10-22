代发 wailian999

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtqnhxcacl.html

JS:   greet() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqckyegtt.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtliiedyhw.html

Java: String greet() { return name; }
来源：http://dali.ydzc1.top/Article/details/gtrjkdywwp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gtpbdrclyn.html

Ruby: def greet; @name; end
来源：http://dali.yueranfly.top/Article/details/gtuobgktwj.html

C#:   public string Greet() => Name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyfjjchvg.html

[G05] 继承
来源：http://dali.feifeiyinyue.top/Article/details/gtylssevkn.html

Py:   class Admin(User): pass
来源：http://dali.yueranfly.top/Article/details/gtqphhqczk.html

PHP:  class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtzmklzznq.html

JS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtzudejcoz.html

TS:   class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gtqhvuqesd.html

Java: class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtozhzbyft.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.andypj.xyz/Article/details/gtoszonhwp.html

Ruby: class Admin < User; end
来源：http://dali.tanke756.top/Article/details/gtmmhfaufi.html

C#:   class Admin : User {}
来源：http://dali.gzhubu.top/Article/details/gthhydeqed.html

[G06] 重写方法
来源：http://dali.hnxiangtu.top/Article/details/gtcubvpzia.html

Py:   def greet(self): return "admin"
来源：http://dali.havefunace.top/Article/details/gtwivpahqt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtpevjwlxc.html

JS:   greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtycsafsla.html

TS:   greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtbjvnmcwa.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtrrvisbsi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nanxuanxn.top/Article/details/gtqxvxadso.html

Ruby: def greet; "admin"; end
来源：http://dali.sysykeji.top/Article/details/gtumrbtnws.html

C#:   public override string Greet() => "admin";
来源：http://dali.feifeiyinyue.top/Article/details/gtwmsdprmq.html

[G07] 调用父类方法
来源：http://dali.pycfn.com/Article/details/gtoqyqnlnk.html

Py:   super().greet()
来源：http://dali.wangdashe.top/Article/details/gttekhhfuz.html

PHP:  parent::greet();
来源：http://dali.quarkkingdee.top/Article/details/gtgcytpjiu.html

JS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gtnbvsfbfi.html

TS:   super.greet();
来源：http://dali.jqgfzy.top/Article/details/gteqqaices.html

Java: super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtckbcwfxp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.pengpengdd.cyou/Article/details/gtvgeqsgip.html

Ruby: super
来源：http://dali.smart0.xyz/Article/details/gtedzpojnm.html

C#:   base.Greet();
来源：http://dali.iojbl.cn/Article/details/gtwtvawzgp.html

[G08] 静态方法与属性
来源：http://dali.yj202588.top/Article/details/gtilfppgta.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zycfv.cn/Article/details/gtvcjapvkn.html

PHP:  public static function f() {}
来源：http://dali.0kj1m.cn/Article/details/gtrswtusio.html

JS:   static f() {}
来源：http://dali.jlsjyb.cn/Article/details/gthmnetiwj.html

TS:   static f(): void {}
来源：http://dali.xziqi.cn/Article/details/gtasrtbrgi.html

Java: static void f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtishrwwhy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.haohaochexian.top/Article/details/gtbuquvfxg.html

Ruby: def self.f; end
来源：http://dali.jlsjyb.cn/Article/details/gtkctihvjw.html

C#:   public static void F() {}
来源：http://dali.havefunace.top/Article/details/gttekwiuci.html

[G09] 接口 / 抽象类
来源：http://dali.shangyingyoupin.top/Article/details/gterrhexsa.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hysaishi.cn/Article/details/gtofiwynyy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenlongwang.top/Article/details/gttagwiclg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgufenzy.top/Article/details/gtqtvnrbxz.html

TS:   interface Shape { area(): number; }
来源：http://dali.xinyue.icu/Article/details/gtxsfsnvbs.html

Java: interface Shape { double area(); }
来源：http://dali.316326.xyz/Article/details/gtfrcikedb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yanxiufei.cn/Article/details/gtqsivkyvy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.kuanghao11.cn/Article/details/gtochflnsm.html

C#:   interface IShape { double Area(); }
来源：http://dali.cqqwz.cn/Article/details/gtwhyvxpid.html

[G10] 访问控制
来源：http://dali.wangdashe.top/Article/details/gtgikddxis.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cdnleiting.top/Article/details/gttlkiyxlv.html

PHP:  public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gttbfctyrz.html

JS:   #private 字段；其余公开
来源：http://dali.xziqi.cn/Article/details/gtzslistjr.html

TS:   public / protected / private
来源：http://dali.c1oappe.top/Article/details/gtlondldnh.html

Java: public / protected / private / 默认包级
来源：http://dali.hysaishi.cn/Article/details/gtthlzqacy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.daria6918.cn/Article/details/gtmowrauya.html

Ruby: public / protected / private
来源：http://dali.ydzc1.top/Article/details/gtjzmvjbkv.html

C#:   public / protected / private / internal
来源：http://dali.sxryk.cn/Article/details/gtyikehorl.html

[G11] getter / setter
来源：http://dali.sweek.top/Article/details/gtsplgivag.html

Py:   @property 与 @x.setter
来源：http://dali.ivvv.top/Article/details/gtyddfbbmv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbbjinsnu.html

JS:   get name() { return this._name; }
来源：http://dali.jqgfzy.top/Article/details/gtlsihislt.html

TS:   get name(): string { return this._name; }
来源：http://dali.aibaodan.cn/Article/details/gtiwaxrwyu.html

Java: public String getName() { return name; }
来源：http://dali.ydzc1.top/Article/details/gtxhajlmqv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gtakvyagpz.html

Ruby: attr_accessor :name
来源：http://dali.gogol.net.cn/Article/details/gtmnmbprlq.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtamxerbrl.html

[G12] 对象转字符串
来源：http://dali.ybcxt.top/Article/details/gtzdfzhgjb.html

Py:   def __str__(self): return self.name
来源：http://dali.sysykeji.top/Article/details/gtcfpsxlag.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtuqroietn.html

JS:   toString() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gthmwkmtjz.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtuixrjutl.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtocfcqstf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsitbeczn.html

Ruby: def to_s; @name; end
来源：http://dali.yueranfly.top/Article/details/gtwaoolwmp.html

C#:   public override string ToString() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gtjvelkfti.html

[G13] 判断对象类型
来源：http://dali.fzhhl.top/Article/details/gtxedjvctr.html

Py:   isinstance(u, User)
来源：http://dali.jinqigufen.top/Article/details/gtdatoebkr.html

PHP:  $u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtugqtroqb.html

JS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gtldtvcmaw.html

TS:   u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtcntdjkbt.html

Java: u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtomrekioc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cqqwz.cn/Article/details/gtmijjfvjg.html

Ruby: u.is_a?(User)
来源：http://dali.fzhhl.top/Article/details/gtapglxblf.html

C#:   u is User
来源：http://dali.guannengcc.top/Article/details/gtbckxjfci.html

[G14] 数据类 / record
来源：http://dali.hnxiangtu.top/Article/details/gteadseduk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.bjfxy.top/Article/details/gtzsyvaqgi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yueranfly.top/Article/details/gtyoiagili.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.pycfn.com/Article/details/gtwpagyjnw.html

TS:   type User = { name: string; age: number };
来源：http://dali.yongpay.top/Article/details/gtispozwxg.html

Java: record User(String name, int age) {}
来源：http://dali.daria6918.cn/Article/details/gtotkbygrs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yueranfly.top/Article/details/gtvbhujhxh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.meibo888.top/Article/details/gtobthzgty.html

C#:   record User(string Name, int Age);
来源：http://dali.zdqjudy.top/Article/details/gtxnyqwrzj.html

[G15] 枚举
来源：http://dali.aizwys.cn/Article/details/gtgefnqdtv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shangyingyoupin.top/Article/details/gtdkjfnzbp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.wangdashe.top/Article/details/gtpjriials.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.pycfn.com/Article/details/gtxhzxkpnr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.andypj.xyz/Article/details/gtkoujnyrs.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj202588.top/Article/details/gtgjktjavz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.haohaochexian.top/Article/details/gtxhfihucb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hysaishi.cn/Article/details/gtzapzfllw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtsbzayxej.html

[G16] 对象转数组 / 字典
来源：http://dali.jlsjyb.cn/Article/details/gtnolbgzrx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.c1oappe.top/Article/details/gtewfqkqld.html

PHP:  get_object_vars($obj);
来源：http://dali.chenjidiqi.icu/Article/details/gthvrgareq.html

JS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvmcksffs.html

TS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gtphdtuiyh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.havefunace.top/Article/details/gthffdrqwi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xziqi.cn/Article/details/gtjstlomaq.html

Ruby: obj.instance_variables
来源：http://dali.jinghuilouyu.cn/Article/details/gtgphmzapr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.daxiang520.top/Article/details/gtfdvcnwdb.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtpglysusf.html

H. 异常与错误处理
来源：http://dali.ivvv.top/Article/details/gtxuxyhiax.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtuwgiwdji.html

[H01] try / catch 基础
来源：http://dali.svipenyu.cn/Article/details/gttfbaxbjc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuxming.cn/Article/details/gtcsncqxij.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ppjwa.cn/Article/details/gtsnousrqb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gthjgknstk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gtaunyjgdn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.smart0.xyz/Article/details/gtuudtnpxy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ivvv.top/Article/details/gtpfkqvaup.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtqggnqjbq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhoulong.xyz/Article/details/gttpbyyhrk.html

[H02] finally / ensure 收尾
来源：http://dali.chenjidiqi.icu/Article/details/gtwqlihlwm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yuxming.cn/Article/details/gtgwyqoiyw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtyrkvlxss.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gttlnhfxri.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtzfrgdahv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtvrhlaxfn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nanxinkj.top/Article/details/gtrkswsfwn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtheljhxwn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtueyzlgnb.html

[H03] 主动抛出异常
来源：http://dali.xinyue.icu/Article/details/gtxsrrrpwm.html

Py:   raise ValueError("错误信息")
来源：http://dali.zdqjudy.top/Article/details/gtroyatyet.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtdkfwmhwq.html

JS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gtfumtrfge.html

TS:   throw new Error("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtdpdigivg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gthbknnfkv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.vqdsnc.cn/Article/details/gtyjbglchg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yonumen.top/Article/details/gtebcwamrv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtefcdhxpc.html

[H04] 自定义异常类型
来源：http://dali.fengsongda.top/Article/details/gtocwkceog.html

Py:   class MyError(Exception): pass
来源：http://dali.zhoulong.xyz/Article/details/gtipvfdxau.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkeoqyxs.html

JS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gtbzsvrwps.html

TS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gthynohlvt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gtvuwsgwrq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yongpay.top/Article/details/gtjmmqxuhi.html

Ruby: class MyError < StandardError; end
来源：http://dali.daria6918.cn/Article/details/gtcnrwbxvh.html

C#:   class MyException : Exception {}
来源：http://dali.shzxlz.cn/Article/details/gthwtoukhd.html

[H05] 捕获特定类型
来源：http://dali.snrcjt.cn/Article/details/gtqhvywksi.html

Py:   except ValueError as e:
来源：http://dali.ybcxt.top/Article/details/gtcyazzdwf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tian-w.cn/Article/details/gtjyjlbibz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.daria6918.cn/Article/details/gtovacgvlm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gtnxoodoip.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xylfe.cn/Article/details/gtibuvtfsi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenlongwang.top/Article/details/gtghgsexeq.html

Ruby: rescue ArgumentError => e
来源：http://dali.pengpengdd.cyou/Article/details/gtlwfftuge.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sufxvd.cn/Article/details/gtbgljhiyc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shuidangran.top/Article/details/gtfwmqcyoh.html

Py:   value = d.get("k") or default
来源：http://dali.zhixingplan.top/Article/details/gtohrzrcmq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.daria6918.cn/Article/details/gtviwgmodq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gtznmqtimv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ivvv.top/Article/details/gtytghwpyc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hysaishi.cn/Article/details/gturnppzhw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.bjfxy.top/Article/details/gtpcxnjdyk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.kuanghao11.cn/Article/details/gtamndmvdp.html

C#:   obj?.A?.B ?? default
来源：http://dali.snrcjt.cn/Article/details/gtvqciuagu.html

[H07] 断言
来源：http://dali.aizwys.cn/Article/details/gtwkogtoqo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nanxuanxn.top/Article/details/gtlhtnoilr.html

PHP:  assert($x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtzyfwgcba.html

JS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gtndqffdyj.html

TS:   console.assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gtklfcsxkj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hfpthk.cn/Article/details/gtormbvjqx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.guowangkeji.top/Article/details/gtsumfyqac.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwkngrroi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gtxqpfygce.html

[H08] 获取错误信息与堆栈
来源：http://dali.cucudq.cn/Article/details/gtbaoxymxd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.guowangkeji.top/Article/details/gtfwkztlyy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.pengpengdd.cyou/Article/details/gtatdgbekl.html

JS:   e.message;  e.stack
来源：http://dali.kuanghao11.cn/Article/details/gtqazjgzxw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gogol.net.cn/Article/details/gtuexeyani.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gaohongyu789.top/Article/details/gthmweotil.html

Go:   err.Error()
来源：http://dali.quarkkingdee.top/Article/details/gtjihmikqb.html

Ruby: e.message;  e.backtrace
来源：http://dali.xziqi.cn/Article/details/gtuhqdawxh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yueranfly.top/Article/details/gtixavinsf.html

[H09] 带错误码的异常
来源：http://dali.0kj1m.cn/Article/details/gtofslsnks.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hywenlv.cn/Article/details/gtdeaisxka.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuanzhike.top/Article/details/gtubqvzrcz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.kuanghao11.cn/Article/details/gtcamgbseq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.andypj.xyz/Article/details/gtrjloznyy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.vqdsnc.cn/Article/details/gtiobgndse.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnxiangtu.top/Article/details/gtfmgfebhq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nwbrower.top/Article/details/gtqkhnhlod.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.svipenyu.cn/Article/details/gtqxrfoorx.html

[H10] 资源自动释放
来源：http://dali.316326.xyz/Article/details/gtviizblnr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.fzhhl.top/Article/details/gtijbxtlyk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.guowangkeji.top/Article/details/gtyjjuldtt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gtbalozzad.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigufen.top/Article/details/gtxjdheqlb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cdnleiting.top/Article/details/gtdhohhlhr.html

Go:   defer f.Close()
来源：http://dali.birdmap.top/Article/details/gtvlsxikzy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hnxiangtu.top/Article/details/gtvvnqoign.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtamrymjdp.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtcwidbndh.html

I. 正则表达式
来源：http://dali.guannengcc.top/Article/details/gtplzsdugc.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gttepnupjo.html

[I01] 判断是否匹配
来源：http://dali.meibo888.top/Article/details/gtxruwteal.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gtpfmehxmp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtpetpbvvz.html

JS:   /\d+/.test(s)
来源：http://dali.yj202588.top/Article/details/gtjvhephgf.html

TS:   /\d+/.test(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvjxfgaj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.svipenyu.cn/Article/details/gthaxqotnx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cqqwz.cn/Article/details/gtguovdsae.html

Ruby: s.match?(/\d+/)
来源：http://dali.yanxiufei.cn/Article/details/gtveamiogd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.0kj1m.cn/Article/details/gtaerwqeug.html

[I02] 提取所有匹配
来源：http://dali.cdnleiting.top/Article/details/gtbexjqfsm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gaohongyu789.top/Article/details/gtvoklrowl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yanxiufei.cn/Article/details/gtzncyntco.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sxryk.cn/Article/details/gtsulsfpod.html

TS:   s.match(/\d+/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbzvhrsyt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.smart0.xyz/Article/details/gtqryxfzij.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gaohongyu789.top/Article/details/gtfbdkkrqe.html

Ruby: s.scan(/\d+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtunvuufgg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtjbppmwrj.html

[I03] 提取捕获分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkqbnqtr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hfpthk.cn/Article/details/gtwhnhrpvj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.vqdsnc.cn/Article/details/gtkisrupox.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yanxiufei.cn/Article/details/gtpymzumot.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cashguo.top/Article/details/gtnebcxwuq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuetiantiany.cn/Article/details/gtriitytuu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xziqi.cn/Article/details/gtcrhkojpi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.vqdsnc.cn/Article/details/gtwbcjjyyb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhixingplan.top/Article/details/gtzwtssxlh.html

[I04] 正则替换
来源：http://dali.yuanzhike.top/Article/details/gtuqtestxs.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmjqvatmx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jianghu66.top/Article/details/gtepmcxdrg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenlongwang.top/Article/details/gtuucatnns.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shuidangran.top/Article/details/gtpaqsuffw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gtdilfqhpx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xziqi.cn/Article/details/gtpqidxdvi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.guannengcc.top/Article/details/gtfmqftgoj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gtiflpvyro.html

[I05] 按正则拆分
来源：http://dali.daria6918.cn/Article/details/gtoyfzqcjv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.wangdashe.top/Article/details/gtcfijcenr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtjjldzwby.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gtmeqxidrt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gtrefhdzlz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sweek.top/Article/details/gtgjukapob.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xziqi.cn/Article/details/gtppaarpzc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gtwoghrexu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.9152youxi.cn/Article/details/gttiyvyiog.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xziqi.cn/Article/details/gtngkrkqtw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gtzkigczge.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nanxuanxn.top/Article/details/gtopelptrw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shuidangran.top/Article/details/gttbtmseck.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gttywkqfrf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gtqiqdynfn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xziqi.cn/Article/details/gtpgvphzpg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jiagoushi.top/Article/details/gtkqegnash.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajeyoqdo.html

[I07] 忽略大小写与多行模式
来源：http://dali.tanke756.top/Article/details/gtlnpivjif.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yongpay.top/Article/details/gtozxfgpyn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gtvqrzodep.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hnqzz.top/Article/details/gtalhmzjvf.html

TS:   /error/gim
来源：http://dali.xuetiantiany.cn/Article/details/gtnvmhsglm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.quarkkingdee.top/Article/details/gtxixfgqzd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yangfankeji.com/Article/details/gtmnyydbcr.html

Ruby: s.scan(/error/i)
来源：http://dali.gotoacloud.top/Article/details/gtbacyqkuz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ppjwa.cn/Article/details/gtcqbvtcxo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hysaishi.cn/Article/details/gtiswffffy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gthugmaesa.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.wangshuangyany.cn/Article/details/gtvhteimsj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gtjyegxqup.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guowangkeji.top/Article/details/gtgtynbhfv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xuetiantiany.cn/Article/details/gtyvhatqkf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhoulong.xyz/Article/details/gtsnchoxyc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.fzhhl.top/Article/details/gtoduivndd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ivvv.top/Article/details/gtyuxdfgge.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtasdastsq.html

J. 日期与时间
来源：http://dali.shuidangran.top/Article/details/gtzkjsbefm.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtdrlvbmzh.html

[J01] 获取当前时间
来源：http://dali.zycfv.cn/Article/details/gtxhxjrlfk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj202588.top/Article/details/gtkrpffvno.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hammf.cn/Article/details/gtokhsmvkb.html

JS:   new Date();  Date.now()
来源：http://dali.zhiwuduotai.top/Article/details/gtzuahysjy.html

TS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gtwvebucgh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhongyouzk.top/Article/details/gtbmaghffx.html

Go:   time.Now()
来源：http://dali.hywenlv.cn/Article/details/gtknkmwque.html

Ruby: Time.now
来源：http://dali.yj20258.top/Article/details/gtsvibhyio.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.c1oappe.top/Article/details/gtjjkfbwvj.html

[J02] 格式化输出
来源：http://dali.hfpthk.cn/Article/details/gtxvgbgsgj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daxiang520.top/Article/details/gtqggwfcnj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.vqdsnc.cn/Article/details/gtysiyyvxa.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpmnufdbo.html

TS:   d.toISOString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcfyzwglz.html


<!-- 参考信息 -->