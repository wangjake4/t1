代发 wailian999

C#:   public User(string name) { Name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgplovddk.html

[G03] 实例属性
来源：http://dali.fzhhl.top/Article/details/gtsyfziebs.html

Py:   self.name = "x"
来源：http://dali.quarkkingdee.top/Article/details/gtlhgfhwol.html

PHP:  public string $name = "x";
来源：http://dali.tian-w.cn/Article/details/gtpzyihqlk.html

JS:   this.name = "x";
来源：http://dali.aizwys.cn/Article/details/gtjsfelcln.html

TS:   name: string = "x";
来源：http://dali.yj202588.top/Article/details/gteencylvb.html

Java: private String name;
来源：http://dali.havefunace.top/Article/details/gtzvtuqpbn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cashguo.top/Article/details/gteqtgxmko.html

Ruby: @name = "x"
来源：http://dali.yonumen.top/Article/details/gtacshrfmq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtlnaoptqf.html

[G04] 定义方法
来源：http://dali.zycfv.cn/Article/details/gtgfskumzh.html

Py:   def greet(self): return self.name
来源：http://dali.daria6918.cn/Article/details/gtnywysgoo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtjoatonig.html

JS:   greet() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtqcwpdfjv.html

TS:   greet(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gtifgqgcte.html

Java: String greet() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtmszhuqey.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gthogeceaf.html

Ruby: def greet; @name; end
来源：http://dali.tanke756.top/Article/details/gtzxwhswhz.html

C#:   public string Greet() => Name;
来源：http://dali.daria6918.cn/Article/details/gtkyvhzvuh.html

[G05] 继承
来源：http://dali.yj202588.top/Article/details/gtuooatpac.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbzatmdz.html

PHP:  class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtzaaaakuk.html

JS:   class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtqfwvdrer.html

TS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtqixlfwcb.html

Java: class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gtonfvozob.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ybcxt.top/Article/details/gtrwewhggl.html

Ruby: class Admin < User; end
来源：http://dali.cdnleiting.top/Article/details/gtihtuctlh.html

C#:   class Admin : User {}
来源：http://dali.birdmap.top/Article/details/gtxtbrsmax.html

[G06] 重写方法
来源：http://dali.zhixingplan.top/Article/details/gtdwiacscd.html

Py:   def greet(self): return "admin"
来源：http://dali.iojbl.cn/Article/details/gtbtsgxili.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtudbmdyje.html

JS:   greet() { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtloqmuufu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtqqprzczy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtfbjtqnve.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.smart0.xyz/Article/details/gtazznaiyy.html

Ruby: def greet; "admin"; end
来源：http://dali.meibo888.top/Article/details/gtkboakvhs.html

C#:   public override string Greet() => "admin";
来源：http://dali.ppjwa.cn/Article/details/gtzmatsgwn.html

[G07] 调用父类方法
来源：http://dali.chenzaomai.com/Article/details/gtyukddxqf.html

Py:   super().greet()
来源：http://dali.ppjwa.cn/Article/details/gtaxyjuhtk.html

PHP:  parent::greet();
来源：http://dali.snrcjt.cn/Article/details/gtbywlddag.html

JS:   super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtrasedwhe.html

TS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gtbopbqzfo.html

Java: super.greet();
来源：http://dali.pycfn.com/Article/details/gtdtivlsar.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcptqdabn.html

Ruby: super
来源：http://dali.hammf.cn/Article/details/gtcipbspso.html

C#:   base.Greet();
来源：http://dali.yj202588.top/Article/details/gtidxsimyj.html

[G08] 静态方法与属性
来源：http://dali.guannengcc.top/Article/details/gtkblwjxov.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xylfe.cn/Article/details/gtewvuaxql.html

PHP:  public static function f() {}
来源：http://dali.svipenyu.cn/Article/details/gtcqfobtfi.html

JS:   static f() {}
来源：http://dali.nanxinkj.top/Article/details/gtwnxpqzuv.html

TS:   static f(): void {}
来源：http://dali.xziqi.cn/Article/details/gteuqeiive.html

Java: static void f() {}
来源：http://dali.hysaishi.cn/Article/details/gtnvgleqdr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dianchejie.cn/Article/details/gtlmgjhesr.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gtkdjobdlf.html

C#:   public static void F() {}
来源：http://dali.c1oappe.top/Article/details/gtbkwafksj.html

[G09] 接口 / 抽象类
来源：http://dali.jyoumei.cn/Article/details/gtqnifglag.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangshuangyany.cn/Article/details/gtfuexawbe.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.aibaodan.cn/Article/details/gtqdiavmsx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xuetiantiany.cn/Article/details/gtlnjguypn.html

TS:   interface Shape { area(): number; }
来源：http://dali.hfpthk.cn/Article/details/gtgagxccvb.html

Java: interface Shape { double area(); }
来源：http://dali.redwolf501.top/Article/details/gtjnailwfg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.bjfxy.top/Article/details/gtaztrfygp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hysaishi.cn/Article/details/gtezrykstl.html

C#:   interface IShape { double Area(); }
来源：http://dali.jiagoushi.top/Article/details/gtvczuzcuz.html

[G10] 访问控制
来源：http://dali.cqqwz.cn/Article/details/gtztnrxmtj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hnxiangtu.top/Article/details/gthduuxwsm.html

PHP:  public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gtytnwexae.html

JS:   #private 字段；其余公开
来源：http://dali.chenjidiqi.icu/Article/details/gttlxlviaf.html

TS:   public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gtujjgrygs.html

Java: public / protected / private / 默认包级
来源：http://dali.zhixingplan.top/Article/details/gtwogfljxo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenzaomai.com/Article/details/gtzrsqtiul.html

Ruby: public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtjvelaewm.html

C#:   public / protected / private / internal
来源：http://dali.hammf.cn/Article/details/gthmqjujzx.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gtjxgavtag.html

Py:   @property 与 @x.setter
来源：http://dali.tian-w.cn/Article/details/gttavhwozs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gttutnezhy.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258888.top/Article/details/gtzikiozaz.html

TS:   get name(): string { return this._name; }
来源：http://dali.dashuyun.cn/Article/details/gtjactdxxc.html

Java: public String getName() { return name; }
来源：http://dali.aizwys.cn/Article/details/gtdeexkysh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtigzozsvy.html

Ruby: attr_accessor :name
来源：http://dali.xuetiantiany.cn/Article/details/gtzjsazjyg.html

C#:   public string Name { get; set; }
来源：http://dali.zycfv.cn/Article/details/gtitwxbyow.html

[G12] 对象转字符串
来源：http://dali.yonumen.top/Article/details/gtmamzxpfp.html

Py:   def __str__(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gticfhecjq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gtbqrtokdh.html

JS:   toString() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtgszxgrim.html

TS:   toString(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gthdtsvfov.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtetfpxffd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gtqhycacux.html

Ruby: def to_s; @name; end
来源：http://dali.aibaodan.cn/Article/details/gtxfyxlonr.html

C#:   public override string ToString() => Name;
来源：http://dali.dianchejie.cn/Article/details/gtpzrqqpme.html

[G13] 判断对象类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtncquuidl.html

Py:   isinstance(u, User)
来源：http://dali.yj202588.top/Article/details/gtsvdzzilp.html

PHP:  $u instanceof User
来源：http://dali.havefunace.top/Article/details/gtkkqnutzg.html

JS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtnvvrvdvg.html

TS:   u instanceof User
来源：http://dali.tanke756.top/Article/details/gtsmsbuaxc.html

Java: u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtvhxpiort.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zycfv.cn/Article/details/gtfcapxnqy.html

Ruby: u.is_a?(User)
来源：http://dali.nanxinkj.top/Article/details/gtgtflqsct.html

C#:   u is User
来源：http://dali.cdnleiting.top/Article/details/gtfrkfpmyj.html

[G14] 数据类 / record
来源：http://dali.zycfv.cn/Article/details/gtggwkyprk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigufen.top/Article/details/gtrtwhqgwv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sweek.top/Article/details/gtzgrzduaj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.316326.xyz/Article/details/gtsgbqvibm.html

TS:   type User = { name: string; age: number };
来源：http://dali.haohaochexian.top/Article/details/gtecrusfit.html

Java: record User(String name, int age) {}
来源：http://dali.yueranfly.top/Article/details/gtwycjemcj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shangyingyoupin.top/Article/details/gthilouvol.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.vqdsnc.cn/Article/details/gttyrpebls.html

C#:   record User(string Name, int Age);
来源：http://dali.chenzaomai.com/Article/details/gtzysipybk.html

[G15] 枚举
来源：http://dali.daria6918.cn/Article/details/gtoistmxen.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj202588.top/Article/details/gtxggmmopu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinqigfzy.top/Article/details/gtvwgpxjeh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zycfv.cn/Article/details/gtchtftipa.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtvcfjccgs.html

Java: enum Color { RED, GREEN }
来源：http://dali.gaohongyu789.top/Article/details/gtjzqcanrt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258888.top/Article/details/gtdlkcjzth.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tian-w.cn/Article/details/gtslmyemsl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gaohongyu789.top/Article/details/gthvefclys.html

[G16] 对象转数组 / 字典
来源：http://dali.pengpengdd.cyou/Article/details/gtdqwxpwmx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hnxiangtu.top/Article/details/gttqnibwhn.html

PHP:  get_object_vars($obj);
来源：http://dali.kuanghao11.cn/Article/details/gtoyxmhcpf.html

JS:   Object.entries(obj)
来源：http://dali.0kj1m.cn/Article/details/gtrqrdkedb.html

TS:   Object.entries(obj)
来源：http://dali.hywenlv.cn/Article/details/gtlapjichl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnqzz.top/Article/details/gtkqbwjgbf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aizwys.cn/Article/details/gtgvisyffz.html

Ruby: obj.instance_variables
来源：http://dali.yongpay.top/Article/details/gtlpywrsht.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.daxiang520.top/Article/details/gtojtoiorw.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtdyclnayj.html

H. 异常与错误处理
来源：http://dali.dashuyun.cn/Article/details/gtagtdngmx.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtytmozvbl.html

[H01] try / catch 基础
来源：http://dali.xinyue.icu/Article/details/gtfafumzfb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guannengcc.top/Article/details/gtqeunzxcn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gtisqmqnrb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gtqtuuiwjc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gtevxlpttt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yonumen.top/Article/details/gtcgbewqqk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.smart0.xyz/Article/details/gtsmexbiyu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhixingplan.top/Article/details/gtbfanynfd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hongshengwenyu.top/Article/details/gtkhzpbfpw.html

[H02] finally / ensure 收尾
来源：http://dali.jianghu66.top/Article/details/gtvosfvnlr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yuanzhike.top/Article/details/gthksxnmls.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtoqiqegef.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gthohgprss.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtrhiqgrcb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtormppmzx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.kuanghao11.cn/Article/details/gtslisbrml.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shuidangran.top/Article/details/gthektljkl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtqcsglefv.html

[H03] 主动抛出异常
来源：http://dali.yuxming.cn/Article/details/gtugnyjspd.html

Py:   raise ValueError("错误信息")
来源：http://dali.haohaochexian.top/Article/details/gtbzupdbks.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtwohgtmht.html

JS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtxmtcaxef.html

TS:   throw new Error("错误信息");
来源：http://dali.birdmap.top/Article/details/gtyubrzqgo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsfmthhzn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.svipenyu.cn/Article/details/gtjtyptrbm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nwbrower.top/Article/details/gtzdvfecpg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtrjftvueb.html

[H04] 自定义异常类型
来源：http://dali.redwolf501.top/Article/details/gtsnptskfp.html

Py:   class MyError(Exception): pass
来源：http://dali.guowangkeji.top/Article/details/gtmmpwtjix.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.vqdsnc.cn/Article/details/gtssnkfkcv.html

JS:   class MyError extends Error {}
来源：http://dali.yueranfly.top/Article/details/gtxjepmlhm.html

TS:   class MyError extends Error {}
来源：http://dali.havefunace.top/Article/details/gtwimktlbj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gtpbnflrsd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zdqjudy.top/Article/details/gtxldkkmgm.html

Ruby: class MyError < StandardError; end
来源：http://dali.gogol.net.cn/Article/details/gtustylgwn.html

C#:   class MyException : Exception {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gttlgqzmpe.html

[H05] 捕获特定类型
来源：http://dali.guannengcc.top/Article/details/gtxwrnlpzw.html

Py:   except ValueError as e:
来源：http://dali.jiagoushi.top/Article/details/gthragnbyh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.pycfn.com/Article/details/gtmjpmenil.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gtmnsnntlv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigfzy.top/Article/details/gtlalkypdn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sxryk.cn/Article/details/gtmxgvbyyb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcxktalqs.html

Ruby: rescue ArgumentError => e
来源：http://dali.yongpay.top/Article/details/gtumznpxof.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.haohaochexian.top/Article/details/gtukqtsgln.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sxryk.cn/Article/details/gtbkzturjm.html

Py:   value = d.get("k") or default
来源：http://dali.tanke756.top/Article/details/gtwalrqcsi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.fengsongda.top/Article/details/gtamovucjg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.meibo888.top/Article/details/gtbrgxocpc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hywenlv.cn/Article/details/gtzcxecuha.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gzhubu.top/Article/details/gtwosvqrxp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tian-w.cn/Article/details/gtnokqfgem.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gogol.net.cn/Article/details/gtcygizsjv.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhoulong.xyz/Article/details/gtrgjlxrnj.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gtkrrutvew.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hammf.cn/Article/details/gthxdanlwt.html

PHP:  assert($x > 0);
来源：http://dali.mhx1999.top/Article/details/gtrzlwogrh.html

JS:   console.assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gtixuwmpsz.html

TS:   console.assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gtorurioll.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhoulong.xyz/Article/details/gtvwjczolh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ehwqpu.com/Article/details/gtvblelmxr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hnqzz.top/Article/details/gtzbppecvm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gtccrfhdpy.html

[H08] 获取错误信息与堆栈
来源：http://dali.9152youxi.cn/Article/details/gtdcgprltk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cucudq.cn/Article/details/gtxcsuwxqf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtegarmpfl.html

JS:   e.message;  e.stack
来源：http://dali.smart0.xyz/Article/details/gtfrrqquff.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jqgufenzy.top/Article/details/gtztgtbnld.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gzhubu.top/Article/details/gtdnxfztrp.html

Go:   err.Error()
来源：http://dali.snrcjt.cn/Article/details/gtpuuprnby.html

Ruby: e.message;  e.backtrace
来源：http://dali.hammf.cn/Article/details/gtvsnazsov.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenzaomai.com/Article/details/gtunnixmpq.html

[H09] 带错误码的异常
来源：http://dali.hnqzz.top/Article/details/gtteldloyw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shzxlz.cn/Article/details/gtqueqlitf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xuetiantiany.cn/Article/details/gtbysiyols.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tianlin.xyz/Article/details/gtkqfesfqg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xuanzx.com/Article/details/gtlfmkajqi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yueranfly.top/Article/details/gtgpztwpyb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jqgufenzy.top/Article/details/gtgsrduycb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.0kj1m.cn/Article/details/gtzsvaruzr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nanxuanxn.top/Article/details/gtjkretkum.html

[H10] 资源自动释放
来源：http://dali.chenzaomai.com/Article/details/gtltkizoxo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yuanzhike.top/Article/details/gtkcrtgyyc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ppjwa.cn/Article/details/gtevoiucda.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jianghu66.top/Article/details/gtcwkltkny.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gtmhhaofft.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.iojbl.cn/Article/details/gtloirepsw.html

Go:   defer f.Close()
来源：http://dali.meibo888.top/Article/details/gtskiyaqya.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hysaishi.cn/Article/details/gtdtgkavzx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtbryssupr.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtoyojpqux.html

I. 正则表达式
来源：http://dali.jianghu66.top/Article/details/gtkmqzjfwi.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtlevbptbe.html

[I01] 判断是否匹配
来源：http://dali.gzhubu.top/Article/details/gtpqjnoecg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtiecfhouv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yvedp.cn/Article/details/gtuiewofda.html

JS:   /\d+/.test(s)
来源：http://dali.shzxlz.cn/Article/details/gtljfmhlue.html

TS:   /\d+/.test(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgfxxxztn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.dashuyun.cn/Article/details/gtzqggdzxf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daria6918.cn/Article/details/gtpatvntjj.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtipjvvupo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sweek.top/Article/details/gtuufvwjzt.html

[I02] 提取所有匹配
来源：http://dali.jlsjyb.cn/Article/details/gtalmukyiy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jiagoushi.top/Article/details/gthsvdehpg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sufxvd.cn/Article/details/gtunoqntlg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.birdmap.top/Article/details/gteghvjwvh.html

TS:   s.match(/\d+/g)
来源：http://dali.iojbl.cn/Article/details/gtvueetadt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.fzhhl.top/Article/details/gttjrfwpjg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cdnleiting.top/Article/details/gtgxhscxhb.html

Ruby: s.scan(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gtebzkskeo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zycfv.cn/Article/details/gtobdvqcvx.html

[I03] 提取捕获分组
来源：http://dali.wangshuangyany.cn/Article/details/gtwprngatj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ydzc1.top/Article/details/gtuiznitea.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hammf.cn/Article/details/gtfotwjfoj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gthjczyfbs.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hfpthk.cn/Article/details/gtlufeoohv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shuidangran.top/Article/details/gttgcuhyys.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.mhx1999.top/Article/details/gtapuioqpl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hongshengwenyu.top/Article/details/gtxclijpuu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yuanzhike.top/Article/details/gtdlgqyjlr.html

[I04] 正则替换
来源：http://dali.sufxvd.cn/Article/details/gtlcytbjho.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ehwqpu.com/Article/details/gtzevpkcbf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guannengcc.top/Article/details/gtsgnyfgjs.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.aizwys.cn/Article/details/gtrqzwgpow.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj202588.top/Article/details/gtgddbstdv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zycfv.cn/Article/details/gtooehkawu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gtaxpjyhya.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.snrcjt.cn/Article/details/gtntxfhjug.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gtibcqnbrb.html

[I05] 按正则拆分
来源：http://dali.dianchejie.cn/Article/details/gtjojhdrmg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj202588.top/Article/details/gtnnnejgot.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.bjfxy.top/Article/details/gtcfoydzys.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zycfv.cn/Article/details/gtwmbrjyxf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gtqnyuogjv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.pengpengdd.cyou/Article/details/gtezwiohba.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gtkidwzirz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gtfcxwqhof.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.mhx1999.top/Article/details/gtslemnjky.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zdqjudy.top/Article/details/gthhsxyopd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gtizmqtfgw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhongyouzk.top/Article/details/gtgetcbubr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cqqwz.cn/Article/details/gtqfpyvrky.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.haohaochexian.top/Article/details/gtatkisigc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.pycfn.com/Article/details/gtvpcrrrxi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hnqzz.top/Article/details/gtfkhcpulf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinqigfzy.top/Article/details/gtocwwdvai.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gtnbjvorku.html

[I07] 忽略大小写与多行模式
来源：http://dali.havefunace.top/Article/details/gtekxiasxy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ehwqpu.com/Article/details/gttueohxoh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zdqjudy.top/Article/details/gtpbqidjeq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.dashuyun.cn/Article/details/gtsfzegfri.html

TS:   /error/gim
来源：http://dali.hongshengwenyu.top/Article/details/gtyosxlyca.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aizwys.cn/Article/details/gtanbvzkql.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinqigfzy.top/Article/details/gtqmaoehlq.html

Ruby: s.scan(/error/i)
来源：http://dali.zycfv.cn/Article/details/gtyabxynsj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.chenjidiqi.icu/Article/details/gtwpnxtzdd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.guannengcc.top/Article/details/gtstrdwdab.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.316326.xyz/Article/details/gtjywblpmc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gtepsbnjcy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.svipenyu.cn/Article/details/gtrqcklniq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hongshengwenyu.top/Article/details/gtusjmnwid.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuanzhike.top/Article/details/gtwrkcvxfq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shangyingyoupin.top/Article/details/gttmuurlgi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nanxuanxn.top/Article/details/gtdnjxjmsy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shzxlz.cn/Article/details/gtutieqbaq.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtemornckj.html

J. 日期与时间
来源：http://dali.nanxuanxn.top/Article/details/gtoxccghil.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtnlbeffcr.html

[J01] 获取当前时间
来源：http://dali.birdmap.top/Article/details/gtkemgrtpf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yuxming.cn/Article/details/gtyjxbotwc.html


<!-- 参考信息 -->