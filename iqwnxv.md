代发 wailian999

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfcnpqno.html

Ruby: def greet; @name; end
来源：http://dali.sweek.top/Article/details/gtqdqhonvv.html

C#:   public string Greet() => Name;
来源：http://dali.gaohongyu789.top/Article/details/gtgultyuip.html

[G05] 继承
来源：http://dali.jinqigfzy.top/Article/details/gteuyrhkti.html

Py:   class Admin(User): pass
来源：http://dali.nanxinkj.top/Article/details/gtamybcbib.html

PHP:  class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtylibtgpf.html

JS:   class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gtcrqhujax.html

TS:   class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gtddvappic.html

Java: class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtvciczoev.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.snrcjt.cn/Article/details/gttjtcdenr.html

Ruby: class Admin < User; end
来源：http://dali.mhx1999.top/Article/details/gtiggwcgsw.html

C#:   class Admin : User {}
来源：http://dali.sxryk.cn/Article/details/gtwbaiecud.html

[G06] 重写方法
来源：http://dali.gogol.net.cn/Article/details/gtnzzvmbdh.html

Py:   def greet(self): return "admin"
来源：http://dali.hongshengwenyu.top/Article/details/gttmrhhsji.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtezccsoza.html

JS:   greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtqdlndxjx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtgyphczaz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxiwjafqf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cqqwz.cn/Article/details/gtpczqglgj.html

Ruby: def greet; "admin"; end
来源：http://dali.meibo888.top/Article/details/gtvzlwjjol.html

C#:   public override string Greet() => "admin";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxkeayjby.html

[G07] 调用父类方法
来源：http://dali.xziqi.cn/Article/details/gtttxshbzt.html

Py:   super().greet()
来源：http://dali.yvedp.cn/Article/details/gtdojlwghj.html

PHP:  parent::greet();
来源：http://dali.dianchejie.cn/Article/details/gtmmaymzaw.html

JS:   super.greet();
来源：http://dali.yueranfly.top/Article/details/gtvqahxnpf.html

TS:   super.greet();
来源：http://dali.yj202588.top/Article/details/gtacgifuxo.html

Java: super.greet();
来源：http://dali.sysykeji.top/Article/details/gteugybibb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.mhx1999.top/Article/details/gtbelxyntw.html

Ruby: super
来源：http://dali.chenzaomai.com/Article/details/gtndhdqwzs.html

C#:   base.Greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjwwnuzh.html

[G08] 静态方法与属性
来源：http://dali.hongshengwenyu.top/Article/details/gtanmvihhh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.daria6918.cn/Article/details/gtqiswmgxh.html

PHP:  public static function f() {}
来源：http://dali.xylfe.cn/Article/details/gtbeqafvsq.html

JS:   static f() {}
来源：http://dali.meibo888.top/Article/details/gtndesgkls.html

TS:   static f(): void {}
来源：http://dali.hfpthk.cn/Article/details/gteiuvsook.html

Java: static void f() {}
来源：http://dali.havefunace.top/Article/details/gtmwpklzru.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.0kj1m.cn/Article/details/gtfqllmkdo.html

Ruby: def self.f; end
来源：http://dali.ydzc1.top/Article/details/gtxonqzdyx.html

C#:   public static void F() {}
来源：http://dali.sxryk.cn/Article/details/gtxvfwooxf.html

[G09] 接口 / 抽象类
来源：http://dali.aizwys.cn/Article/details/gtdvzhfnfd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yuxming.cn/Article/details/gtjyuegtgl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.havefunace.top/Article/details/gtjwdfehlj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj20258.top/Article/details/gtpdjltkbk.html

TS:   interface Shape { area(): number; }
来源：http://dali.jlsjyb.cn/Article/details/gtypmhxwey.html

Java: interface Shape { double area(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtgnqqanpw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hysaishi.cn/Article/details/gtiljncldk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yanxiufei.cn/Article/details/gthxtghgpr.html

C#:   interface IShape { double Area(); }
来源：http://dali.jianghu66.top/Article/details/gtajzffjkc.html

[G10] 访问控制
来源：http://dali.ybcxt.top/Article/details/gtrfiyubrh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xuetiantiany.cn/Article/details/gtfiizwmcj.html

PHP:  public / protected / private
来源：http://dali.smart0.xyz/Article/details/gtacdbttta.html

JS:   #private 字段；其余公开
来源：http://dali.ydzc1.top/Article/details/gtbflppvvu.html

TS:   public / protected / private
来源：http://dali.havefunace.top/Article/details/gtnkigjwfr.html

Java: public / protected / private / 默认包级
来源：http://dali.yongpay.top/Article/details/gtdvghpniz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hfpthk.cn/Article/details/gttbdpkdlr.html

Ruby: public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gthhrxzwbc.html

C#:   public / protected / private / internal
来源：http://dali.meibo888.top/Article/details/gtmwwxfhbg.html

[G11] getter / setter
来源：http://dali.xuetiantiany.cn/Article/details/gtauvbfehw.html

Py:   @property 与 @x.setter
来源：http://dali.jyoumei.cn/Article/details/gtdxlptaoe.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gtlaeypbgl.html

JS:   get name() { return this._name; }
来源：http://dali.jyoumei.cn/Article/details/gtakqxawnf.html

TS:   get name(): string { return this._name; }
来源：http://dali.birdmap.top/Article/details/gtwizzlvod.html

Java: public String getName() { return name; }
来源：http://dali.meibo888.top/Article/details/gtlsfqfzzc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gtssnqwgyi.html

Ruby: attr_accessor :name
来源：http://dali.cdnleiting.top/Article/details/gtopwyelms.html

C#:   public string Name { get; set; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtehcrigwo.html

[G12] 对象转字符串
来源：http://dali.yuanzhike.top/Article/details/gtogbgxzqa.html

Py:   def __str__(self): return self.name
来源：http://dali.dianchejie.cn/Article/details/gtoqszlsxa.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwgcojpzy.html

JS:   toString() { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtkyuaczbg.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtlidtywnq.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtipiozope.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtjwlqiqsk.html

Ruby: def to_s; @name; end
来源：http://dali.yj202588.top/Article/details/gtfrqmsdsh.html

C#:   public override string ToString() => Name;
来源：http://dali.feifeiyinyue.top/Article/details/gtyxbjphkn.html

[G13] 判断对象类型
来源：http://dali.fzhhl.top/Article/details/gtizqoiofe.html

Py:   isinstance(u, User)
来源：http://dali.zhiwuduotai.top/Article/details/gtxozqyxij.html

PHP:  $u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtmgumnvgs.html

JS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gteombmoib.html

TS:   u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtdvmcxjlf.html

Java: u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtomorhrhk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sxryk.cn/Article/details/gtixincueg.html

Ruby: u.is_a?(User)
来源：http://dali.shzxlz.cn/Article/details/gtoezwpqay.html

C#:   u is User
来源：http://dali.chenlongwang.top/Article/details/gtoatfgdqq.html

[G14] 数据类 / record
来源：http://dali.vqdsnc.cn/Article/details/gtheochusn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigufen.top/Article/details/gtqibmepib.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.guowangkeji.top/Article/details/gtobbeluou.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenjidiqi.icu/Article/details/gtlucvaswq.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj20258.top/Article/details/gtbeglmvtr.html

Java: record User(String name, int age) {}
来源：http://dali.yonumen.top/Article/details/gttxcfgedb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpmaggrbv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.meibo888.top/Article/details/gtpvhnakmg.html

C#:   record User(string Name, int Age);
来源：http://dali.ehwqpu.com/Article/details/gtctuqbbbx.html

[G15] 枚举
来源：http://dali.redwolf501.top/Article/details/gtizvqjvxe.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.daria6918.cn/Article/details/gtnzuickxu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ivvv.top/Article/details/gtsgghslpw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.iojbl.cn/Article/details/gtpfxrktpc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sxryk.cn/Article/details/gtfljbutvn.html

Java: enum Color { RED, GREEN }
来源：http://dali.sxryk.cn/Article/details/gtucmpgrcp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.aizwys.cn/Article/details/gtiwlibbur.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jyoumei.cn/Article/details/gtvxjdubqt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258.top/Article/details/gtxxzhlzef.html

[G16] 对象转数组 / 字典
来源：http://dali.hnxiangtu.top/Article/details/gtemhixtnd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.bjfxy.top/Article/details/gtogfqiqde.html

PHP:  get_object_vars($obj);
来源：http://dali.yonumen.top/Article/details/gtiqzxkvwy.html

JS:   Object.entries(obj)
来源：http://dali.pycfn.com/Article/details/gtrzwoepog.html

TS:   Object.entries(obj)
来源：http://dali.tian-w.cn/Article/details/gtqpbmjpgt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hywenlv.cn/Article/details/gtbgupvrvi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhixingplan.top/Article/details/gtllmiwzlb.html

Ruby: obj.instance_variables
来源：http://dali.nwbrower.top/Article/details/gtvlfemqkx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gtynfddmta.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtdnwvqmwk.html

H. 异常与错误处理
来源：http://dali.0kj1m.cn/Article/details/gtzujjzntr.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtrmbmuwrw.html

[H01] try / catch 基础
来源：http://dali.svipenyu.cn/Article/details/gtzsomepic.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dianchejie.cn/Article/details/gtthroqrax.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ybcxt.top/Article/details/gtnsvsafze.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.quarkkingdee.top/Article/details/gtxpeowdbv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvjjvekv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.havefunace.top/Article/details/gtqnetcvjc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.guannengcc.top/Article/details/gtegvtkgjg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhongyouzk.top/Article/details/gtynbbjptu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aibaodan.cn/Article/details/gtprfkcctk.html

[H02] finally / ensure 收尾
来源：http://dali.hnqzz.top/Article/details/gtrtmgxsli.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dianchejie.cn/Article/details/gttzwlinmz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtinkkfajk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtoezncqct.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtqusdtkpz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtpeudjqgv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhengqikj.top/Article/details/gtyflkhxmv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.316326.xyz/Article/details/gtbbmhntff.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtwytissub.html

[H03] 主动抛出异常
来源：http://dali.quarkkingdee.top/Article/details/gtpohstbsw.html

Py:   raise ValueError("错误信息")
来源：http://dali.gogol.net.cn/Article/details/gtdpavlbhi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtoyqgqvlb.html

JS:   throw new Error("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtdkpodsfd.html

TS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtbhhxxqvm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtitdiqkpf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zycfv.cn/Article/details/gtcejzsnck.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cucudq.cn/Article/details/gtjnwgpjmj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtgkmvrrax.html

[H04] 自定义异常类型
来源：http://dali.feifeiyinyue.top/Article/details/gtjukkagah.html

Py:   class MyError(Exception): pass
来源：http://dali.sxryk.cn/Article/details/gtksbxvitz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gtropyiobt.html

JS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gtqowehgmp.html

TS:   class MyError extends Error {}
来源：http://dali.tian-w.cn/Article/details/gtlgjjnixe.html

Java: class MyException extends RuntimeException {}
来源：http://dali.bjfxy.top/Article/details/gtuwfyetfi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jianghu66.top/Article/details/gtrassnxld.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj20258.top/Article/details/gtrzhtgooc.html

C#:   class MyException : Exception {}
来源：http://dali.nwbrower.top/Article/details/gtcmvfyhgz.html

[H05] 捕获特定类型
来源：http://dali.jqgufenzy.top/Article/details/gtgvdyhvgt.html

Py:   except ValueError as e:
来源：http://dali.yongpay.top/Article/details/gtraxldaug.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.havefunace.top/Article/details/gthwelkrhl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.redwolf501.top/Article/details/gtxsyxxhrr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tian-w.cn/Article/details/gtmfkowfdm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jiagoushi.top/Article/details/gtsuphrqew.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.9152youxi.cn/Article/details/gtnqiccdlt.html

Ruby: rescue ArgumentError => e
来源：http://dali.yanxiufei.cn/Article/details/gttdwbqfnf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cqqwz.cn/Article/details/gtzrnifagp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.haohaochexian.top/Article/details/gtexcxftni.html

Py:   value = d.get("k") or default
来源：http://dali.smart0.xyz/Article/details/gtmuhtvttj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yvedp.cn/Article/details/gtouaraiho.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.snrcjt.cn/Article/details/gtiqhrcnxn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hysaishi.cn/Article/details/gthfgcdfzw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.mhx1999.top/Article/details/gtepmnmzbu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.guowangkeji.top/Article/details/gtohzvxscp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj202588.top/Article/details/gtqwnujycc.html

C#:   obj?.A?.B ?? default
来源：http://dali.haohaochexian.top/Article/details/gtikxwmagx.html

[H07] 断言
来源：http://dali.zdqjudy.top/Article/details/gtycysgkem.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shzxlz.cn/Article/details/gtiilfmtmb.html

PHP:  assert($x > 0);
来源：http://dali.cqqwz.cn/Article/details/gtemivrmcj.html

JS:   console.assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gttogzowwd.html

TS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtznxwfrvi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnxiangtu.top/Article/details/gttbgxsmct.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj20258888.top/Article/details/gtskzwhwrh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sweek.top/Article/details/gtzeageemx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtkueelcpe.html

[H08] 获取错误信息与堆栈
来源：http://dali.andypj.xyz/Article/details/gtmdmcxhhl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuanzhike.top/Article/details/gtsvuubiea.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenlongwang.top/Article/details/gtxylmtdvi.html

JS:   e.message;  e.stack
来源：http://dali.shuidangran.top/Article/details/gtwyqkpblu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.feifeiyinyue.top/Article/details/gtkqxdjywg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gtdokfogoy.html

Go:   err.Error()
来源：http://dali.snrcjt.cn/Article/details/gtqjteffgc.html

Ruby: e.message;  e.backtrace
来源：http://dali.tianlin.xyz/Article/details/gtpgtqiugk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.iojbl.cn/Article/details/gtachkrmzo.html

[H09] 带错误码的异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzpmgjpst.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj20258.top/Article/details/gthvksaczu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yongpay.top/Article/details/gtaovfexbx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.mhx1999.top/Article/details/gtrbrwjznr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj20258888.top/Article/details/gtlprgerli.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daria6918.cn/Article/details/gtgmmphxaz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.feifeiyinyue.top/Article/details/gtnpxanudb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sysykeji.top/Article/details/gtbnjsdmhb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yuxming.cn/Article/details/gtfxunqbvv.html

[H10] 资源自动释放
来源：http://dali.hnxiangtu.top/Article/details/gtphntgqdb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xuetiantiany.cn/Article/details/gteonfyktr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jyoumei.cn/Article/details/gthrkgvzth.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gtomgpjxkw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hammf.cn/Article/details/gtxqxalnsm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ppjwa.cn/Article/details/gtvoagksie.html

Go:   defer f.Close()
来源：http://dali.sysykeji.top/Article/details/gtbornwfqw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jianghu66.top/Article/details/gthcnqgxos.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtyxsfrdbz.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtfroggasj.html

I. 正则表达式
来源：http://dali.hfpthk.cn/Article/details/gtgthrabip.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtfcybkskf.html

[I01] 判断是否匹配
来源：http://dali.yj20258.top/Article/details/gtxsnqaoyt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.fengsongda.top/Article/details/gtktpjqpbq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtgbgeegyk.html

JS:   /\d+/.test(s)
来源：http://dali.cucudq.cn/Article/details/gtwxhzyqnp.html

TS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gtpouiwzpv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.aibaodan.cn/Article/details/gtodmccvqg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nwbrower.top/Article/details/gtejumcokg.html

Ruby: s.match?(/\d+/)
来源：http://dali.xinyue.icu/Article/details/gtuxhhloqn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.iojbl.cn/Article/details/gtyrtlyygh.html

[I02] 提取所有匹配
来源：http://dali.kuanghao11.cn/Article/details/gtdhzcxkbt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ydzc1.top/Article/details/gtmlyytkzl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.feifeiyinyue.top/Article/details/gtunshetjj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hfpthk.cn/Article/details/gtigkycquk.html

TS:   s.match(/\d+/g)
来源：http://dali.dianchejie.cn/Article/details/gtgsqwytid.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ppjwa.cn/Article/details/gtvvgqnata.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dashuyun.cn/Article/details/gtypysfiin.html

Ruby: s.scan(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gtfmlmgljw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yonumen.top/Article/details/gtbejbowvv.html

[I03] 提取捕获分组
来源：http://dali.xziqi.cn/Article/details/gtewtoqlyw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gogol.net.cn/Article/details/gtvipvhodw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tanke756.top/Article/details/gttlhdppmh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtfmtkzlbu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigfzy.top/Article/details/gtyqwuydpq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xziqi.cn/Article/details/gtvkaljckl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jianghu66.top/Article/details/gtqdhgcwsq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xylfe.cn/Article/details/gtaafeqqhk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangshuangyany.cn/Article/details/gtszgqetjo.html

[I04] 正则替换
来源：http://dali.xylfe.cn/Article/details/gtfjchwvuc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hammf.cn/Article/details/gtjheabaki.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cucudq.cn/Article/details/gtqeclyxwm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.dianchejie.cn/Article/details/gtfhrjczkh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gogol.net.cn/Article/details/gthgyhnueq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.316326.xyz/Article/details/gtjmzvbyog.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cqqwz.cn/Article/details/gtuyaxoyjc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yongpay.top/Article/details/gtvqtehbxr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sufxvd.cn/Article/details/gtkgxuztch.html

[I05] 按正则拆分
来源：http://dali.pycfn.com/Article/details/gtxpbbtpwf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenzaomai.com/Article/details/gtiaseywdw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.daria6918.cn/Article/details/gtjiynqdkk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gtaijkgvuj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gtheadvypi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cdnleiting.top/Article/details/gtbkxslugm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiimdrwug.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yonumen.top/Article/details/gtaadzdubz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sysykeji.top/Article/details/gtjuuqnmdt.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jqgufenzy.top/Article/details/gtycnxmxsc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gtqqpfovfp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.0kj1m.cn/Article/details/gtqgpvylwo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ehwqpu.com/Article/details/gtaverovyp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yueranfly.top/Article/details/gtxwqfzatl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gtxdbpnzug.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jianghu66.top/Article/details/gtrwwakext.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sysykeji.top/Article/details/gtanrububd.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gtwjkbgnat.html

[I07] 忽略大小写与多行模式
来源：http://dali.meibo888.top/Article/details/gtvuhjircb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dianchejie.cn/Article/details/gtwvutyxuz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shzxlz.cn/Article/details/gtihgwytyj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jiagoushi.top/Article/details/gtemsagfkk.html

TS:   /error/gim
来源：http://dali.gogol.net.cn/Article/details/gttocrksrq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aibaodan.cn/Article/details/gtwngxctos.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gaohongyu789.top/Article/details/gtcuklvyms.html

Ruby: s.scan(/error/i)
来源：http://dali.cdnleiting.top/Article/details/gtllpnyuth.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.bjfxy.top/Article/details/gthwjamksu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbsfwfzi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jqgfzy.top/Article/details/gtczyvqahx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gttbnuuqjv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ppjwa.cn/Article/details/gtmzdhkage.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gttdeglind.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jlsjyb.cn/Article/details/gtfgxuehyz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.iojbl.cn/Article/details/gtvrfbobnu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aizwys.cn/Article/details/gtnstgfdfx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.guowangkeji.top/Article/details/gtgsmuqknu.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtwbucffwq.html

J. 日期与时间
来源：http://dali.nanxuanxn.top/Article/details/gtpjuieuhb.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtoyjmmlcr.html

[J01] 获取当前时间
来源：http://dali.aibaodan.cn/Article/details/gtnslazvtr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuvirpaah.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.316326.xyz/Article/details/gtdqdqdvey.html

JS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gtcoyhkctz.html

TS:   new Date();  Date.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbksqeuv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xuetiantiany.cn/Article/details/gtgyraactu.html

Go:   time.Now()
来源：http://dali.nanxinkj.top/Article/details/gtalkhfjwp.html

Ruby: Time.now
来源：http://dali.316326.xyz/Article/details/gtkpnkject.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jyoumei.cn/Article/details/gtpiorpmow.html

[J02] 格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxxikocum.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj202588.top/Article/details/gtyixgmnax.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.vqdsnc.cn/Article/details/gtlvrrelvs.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.daxiang520.top/Article/details/gtogofaeif.html

TS:   d.toISOString()
来源：http://dali.daxiang520.top/Article/details/gtrpnytmgf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cucudq.cn/Article/details/gtglieyhck.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jyoumei.cn/Article/details/gtcouotygp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fzhhl.top/Article/details/gtqtpazbnq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhongyouzk.top/Article/details/gtyuktzrny.html


<!-- 参考信息 -->