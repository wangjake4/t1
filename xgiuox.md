代发 wailian999

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gtaxazvcxn.html

JS:   greet() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gthqyiivfq.html

TS:   greet(): string { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtwrpcdasp.html

Java: String greet() { return name; }
来源：http://dali.gzhubu.top/Article/details/gtxhhmbtjc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtymhfmfnj.html

Ruby: def greet; @name; end
来源：http://dali.daxiang520.top/Article/details/gtonotgkkv.html

C#:   public string Greet() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvpkpatrn.html

[G05] 继承
来源：http://dali.birdmap.top/Article/details/gtqlvdvbyf.html

Py:   class Admin(User): pass
来源：http://dali.chenzaomai.com/Article/details/gtspspkkcq.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtdsvndoth.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtebeeiwhd.html

TS:   class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtijmznzaw.html

Java: class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtvlvwqaut.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hysaishi.cn/Article/details/gtecervfus.html

Ruby: class Admin < User; end
来源：http://dali.mhx1999.top/Article/details/gtxatddngl.html

C#:   class Admin : User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtnuqsowfw.html

[G06] 重写方法
来源：http://dali.daxiang520.top/Article/details/gtitksyroi.html

Py:   def greet(self): return "admin"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcehmgcjd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxpvazqkc.html

JS:   greet() { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gtievlhojp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtugmmavmf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtpkbsnabx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yvedp.cn/Article/details/gtmiuuynir.html

Ruby: def greet; "admin"; end
来源：http://dali.chenjidiqi.icu/Article/details/gtrrusyjad.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxinkj.top/Article/details/gtehakkmgw.html

[G07] 调用父类方法
来源：http://dali.fzhhl.top/Article/details/gtbwsxdicg.html

Py:   super().greet()
来源：http://dali.gogol.net.cn/Article/details/gtrizplmmm.html

PHP:  parent::greet();
来源：http://dali.tanke756.top/Article/details/gtpiyijycg.html

JS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gtuogbrbue.html

TS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gtjyawqzjo.html

Java: super.greet();
来源：http://dali.daria6918.cn/Article/details/gtllixddjm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.fzhhl.top/Article/details/gtsryzbemh.html

Ruby: super
来源：http://dali.mhx1999.top/Article/details/gtaxhpjdcy.html

C#:   base.Greet();
来源：http://dali.mhx1999.top/Article/details/gtcgjkjssa.html

[G08] 静态方法与属性
来源：http://dali.vqdsnc.cn/Article/details/gtyurojvqq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.birdmap.top/Article/details/gtglxglkui.html

PHP:  public static function f() {}
来源：http://dali.yangfankeji.com/Article/details/gtnmsejbia.html

JS:   static f() {}
来源：http://dali.9152youxi.cn/Article/details/gtjccjiuqg.html

TS:   static f(): void {}
来源：http://dali.pycfn.com/Article/details/gtrwdhqcgl.html

Java: static void f() {}
来源：http://dali.aibaodan.cn/Article/details/gtqqcedofb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.pengpengdd.cyou/Article/details/gtcbeshsws.html

Ruby: def self.f; end
来源：http://dali.yuanzhike.top/Article/details/gtrquiyoxl.html

C#:   public static void F() {}
来源：http://dali.jinqigufen.top/Article/details/gtdiulbueq.html

[G09] 接口 / 抽象类
来源：http://dali.jlsjyb.cn/Article/details/gtowcobgnk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.meibo888.top/Article/details/gtegleiwfo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shzxlz.cn/Article/details/gtudafqewv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ehwqpu.com/Article/details/gteahyuala.html

TS:   interface Shape { area(): number; }
来源：http://dali.shangyingyoupin.top/Article/details/gtjfiarntn.html

Java: interface Shape { double area(); }
来源：http://dali.yonumen.top/Article/details/gtccwlumft.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xylfe.cn/Article/details/gtvguuwdpq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.meibo888.top/Article/details/gtfxxbnepc.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqarvzji.html

[G10] 访问控制
来源：http://dali.jyoumei.cn/Article/details/gtghoyxuzi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sxryk.cn/Article/details/gtjrbjmzyo.html

PHP:  public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gtwfyrrcwo.html

JS:   #private 字段；其余公开
来源：http://dali.hfpthk.cn/Article/details/gtqaxcjfov.html

TS:   public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gtvdxhabsq.html

Java: public / protected / private / 默认包级
来源：http://dali.zhixingplan.top/Article/details/gtuiaeeysy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.meibo888.top/Article/details/gtjsfwuupg.html

Ruby: public / protected / private
来源：http://dali.aizwys.cn/Article/details/gtsxzwnkyi.html

C#:   public / protected / private / internal
来源：http://dali.quarkkingdee.top/Article/details/gtbmlmkaqe.html

[G11] getter / setter
来源：http://dali.daxiang520.top/Article/details/gtanekimyo.html

Py:   @property 与 @x.setter
来源：http://dali.tanke756.top/Article/details/gtwoknorrb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtihkxoxru.html

JS:   get name() { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gtzzqmjwss.html

TS:   get name(): string { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gtnijnlvwn.html

Java: public String getName() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtbbbqfqsj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gtooggiwth.html

Ruby: attr_accessor :name
来源：http://dali.smart0.xyz/Article/details/gtbhyjarrn.html

C#:   public string Name { get; set; }
来源：http://dali.xinyue.icu/Article/details/gtylqdtxxg.html

[G12] 对象转字符串
来源：http://dali.wangdashe.top/Article/details/gtkhailcot.html

Py:   def __str__(self): return self.name
来源：http://dali.yueranfly.top/Article/details/gthxdfgwcg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gtdhwodnqx.html

JS:   toString() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtzdzqcnui.html

TS:   toString(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtrzimoawp.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtksifduck.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gtaupppwce.html

Ruby: def to_s; @name; end
来源：http://dali.daria6918.cn/Article/details/gtsjfslkcn.html

C#:   public override string ToString() => Name;
来源：http://dali.c1oappe.top/Article/details/gtwyaydwkz.html

[G13] 判断对象类型
来源：http://dali.svipenyu.cn/Article/details/gthospbmsk.html

Py:   isinstance(u, User)
来源：http://dali.bjfxy.top/Article/details/gtiszoohjh.html

PHP:  $u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtmfjpgjgs.html

JS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtloktsvre.html

TS:   u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtuahvafer.html

Java: u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gtoodyowph.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.kuanghao11.cn/Article/details/gtlasfzbqj.html

Ruby: u.is_a?(User)
来源：http://dali.fengsongda.top/Article/details/gtdgzxfmzh.html

C#:   u is User
来源：http://dali.0kj1m.cn/Article/details/gteqltkznj.html

[G14] 数据类 / record
来源：http://dali.xylfe.cn/Article/details/gtxqiuoaqt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.mhx1999.top/Article/details/gtehlyvsfi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhiwuduotai.top/Article/details/gtjrulvnlm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tian-w.cn/Article/details/gtfiqjntiw.html

TS:   type User = { name: string; age: number };
来源：http://dali.jianghu66.top/Article/details/gtjacafuxs.html

Java: record User(String name, int age) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtznyfpcqm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gtezjkjwnx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hammf.cn/Article/details/gtuqbvmnyd.html

C#:   record User(string Name, int Age);
来源：http://dali.hammf.cn/Article/details/gtcyzhdoxn.html

[G15] 枚举
来源：http://dali.hywenlv.cn/Article/details/gtvaslfmbr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shangyingyoupin.top/Article/details/gtfworhqrn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yonumen.top/Article/details/gthpbywbqf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hammf.cn/Article/details/gtdfisiogv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.mhx1999.top/Article/details/gtoaoaufxr.html

Java: enum Color { RED, GREEN }
来源：http://dali.jqgufenzy.top/Article/details/gtctrfjudt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhiwuduotai.top/Article/details/gtwhublzgj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nwbrower.top/Article/details/gtkrxhjdzm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fzhhl.top/Article/details/gtwzhydfpw.html

[G16] 对象转数组 / 字典
来源：http://dali.haohaochexian.top/Article/details/gtnumrkhzz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tian-w.cn/Article/details/gtbjuybkpp.html

PHP:  get_object_vars($obj);
来源：http://dali.yuxming.cn/Article/details/gtjdisyjwe.html

JS:   Object.entries(obj)
来源：http://dali.tian-w.cn/Article/details/gtftbwnhov.html

TS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gtddkukood.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoiplzhbb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangdashe.top/Article/details/gtomsexdud.html

Ruby: obj.instance_variables
来源：http://dali.zhiwuduotai.top/Article/details/gtrjdyyiwh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.meibo888.top/Article/details/gtfadhlklu.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtlaqlrilb.html

H. 异常与错误处理
来源：http://dali.havefunace.top/Article/details/gtuwagtvet.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtuikrqihi.html

[H01] try / catch 基础
来源：http://dali.guowangkeji.top/Article/details/gtmjinxvsg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenlongwang.top/Article/details/gtdnxhpsbz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.c1oappe.top/Article/details/gtxxldwwye.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gtjhwhtivx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gtdakrhprr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yueranfly.top/Article/details/gtevjoarob.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xuetiantiany.cn/Article/details/gtzeomoqgy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tanke756.top/Article/details/gtqjytbwtj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shzxlz.cn/Article/details/gtmuatyddf.html

[H02] finally / ensure 收尾
来源：http://dali.yuanzhike.top/Article/details/gtjgplnywj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.daxiang520.top/Article/details/gtnsxlnggx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtxlwlyxay.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtywhnncqx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtuzqvtopy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtsbnggzzq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cdnleiting.top/Article/details/gtmdsedgbw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhongyouzk.top/Article/details/gtzdbryaul.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtmdyyqmll.html

[H03] 主动抛出异常
来源：http://dali.jinqigufen.top/Article/details/gtjyeuhgjp.html

Py:   raise ValueError("错误信息")
来源：http://dali.smart0.xyz/Article/details/gtbahmfzpe.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtjrflbbvl.html

JS:   throw new Error("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gterejvmjd.html

TS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtvuwmlinu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtfdgkcgaz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxuanxn.top/Article/details/gtyfomgaxd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yangfankeji.com/Article/details/gtvhelngzs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtqfudxieb.html

[H04] 自定义异常类型
来源：http://dali.chenjidiqi.icu/Article/details/gtdeaqedsr.html

Py:   class MyError(Exception): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gtstgabvqb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yangfankeji.com/Article/details/gtvnpwvpul.html

JS:   class MyError extends Error {}
来源：http://dali.yj20258888.top/Article/details/gtqawhebsg.html

TS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gtfwtjtjqf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gtkhtrmhwt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gaohongyu789.top/Article/details/gtryorrphe.html

Ruby: class MyError < StandardError; end
来源：http://dali.wangdashe.top/Article/details/gtmgtqhluh.html

C#:   class MyException : Exception {}
来源：http://dali.gogol.net.cn/Article/details/gtjbybcpza.html

[H05] 捕获特定类型
来源：http://dali.sysykeji.top/Article/details/gtaghmdlgd.html

Py:   except ValueError as e:
来源：http://dali.hongshengwenyu.top/Article/details/gtcazzcnqr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xinyue.icu/Article/details/gtvsmxvhwc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shuidangran.top/Article/details/gtuifpflml.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nanxuanxn.top/Article/details/gthxagazlk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuanzhike.top/Article/details/gtummxixea.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.wangdashe.top/Article/details/gtmhokqafb.html

Ruby: rescue ArgumentError => e
来源：http://dali.yueranfly.top/Article/details/gtyffhddji.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.svipenyu.cn/Article/details/gtwantmidq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dashuyun.cn/Article/details/gttyilxdjx.html

Py:   value = d.get("k") or default
来源：http://dali.cdnleiting.top/Article/details/gtoosnteqi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cheryme.top/Article/details/gtiawaxpeq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.redwolf501.top/Article/details/gtfzjxfpqa.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sweek.top/Article/details/gtaqfghcal.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj20258888.top/Article/details/gtxwzmxafw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jlsjyb.cn/Article/details/gtjguvbtbr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gaohongyu789.top/Article/details/gtxtsrrstm.html

C#:   obj?.A?.B ?? default
来源：http://dali.haohaochexian.top/Article/details/gtdhzvrxlk.html

[H07] 断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gtluwwhwuq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.redwolf501.top/Article/details/gtxwrbyuvm.html

PHP:  assert($x > 0);
来源：http://dali.cashguo.top/Article/details/gtrtfosqun.html

JS:   console.assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtkhookrtt.html

TS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtzonjlbna.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shuidangran.top/Article/details/gtftwiivdj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yangfankeji.com/Article/details/gttlcpuxgz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.wangdashe.top/Article/details/gtblvprioj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtsllfonfe.html

[H08] 获取错误信息与堆栈
来源：http://dali.hongshengwenyu.top/Article/details/gtqdmjllbg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hongshengwenyu.top/Article/details/gtoqegslsh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.c1oappe.top/Article/details/gtqobddfwv.html

JS:   e.message;  e.stack
来源：http://dali.wangshuangyany.cn/Article/details/gtgftkdxfo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.redwolf501.top/Article/details/gtmicwamtg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.guannengcc.top/Article/details/gtcwzbavev.html

Go:   err.Error()
来源：http://dali.hongshengwenyu.top/Article/details/gtkaycdmww.html

Ruby: e.message;  e.backtrace
来源：http://dali.haohaochexian.top/Article/details/gtwvpfiqsu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hysaishi.cn/Article/details/gtmhuszvsp.html

[H09] 带错误码的异常
来源：http://dali.pengpengdd.cyou/Article/details/gtbtaweppb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.daria6918.cn/Article/details/gtkzojjzon.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.0kj1m.cn/Article/details/gtnbphasrb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fengsongda.top/Article/details/gtdkspfden.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daria6918.cn/Article/details/gtaydqmqgf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cucudq.cn/Article/details/gtzgpmfayc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhoulong.xyz/Article/details/gtjbmxrvsj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.meibo888.top/Article/details/gtdbwpzlko.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hongshengwenyu.top/Article/details/gtjmsohfvr.html

[H10] 资源自动释放
来源：http://dali.daxiang520.top/Article/details/gtmmsnynsv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.redwolf501.top/Article/details/gthcaxwbiz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.birdmap.top/Article/details/gtvkvciwhu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gtelmqzjjp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cqqwz.cn/Article/details/gtevynampq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gogol.net.cn/Article/details/gtmokrnhdf.html

Go:   defer f.Close()
来源：http://dali.yueranfly.top/Article/details/gtnkjatnyd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.dianchejie.cn/Article/details/gtkratugzv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtozgmrgbd.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtrwoyljpx.html

I. 正则表达式
来源：http://dali.tianlin.xyz/Article/details/gtaobeknwm.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtdlccwgrr.html

[I01] 判断是否匹配
来源：http://dali.jinqigufen.top/Article/details/gtpqnookvi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daria6918.cn/Article/details/gtxovepeja.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ydzc1.top/Article/details/gtumdrtjkj.html

JS:   /\d+/.test(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlxtwdbiq.html

TS:   /\d+/.test(s)
来源：http://dali.hysaishi.cn/Article/details/gtrjpsknux.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.vqdsnc.cn/Article/details/gtlneapxoy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.pycfn.com/Article/details/gtnptuiorb.html

Ruby: s.match?(/\d+/)
来源：http://dali.sweek.top/Article/details/gtzfteaftv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgufenzy.top/Article/details/gtanwcdbrw.html

[I02] 提取所有匹配
来源：http://dali.zhengqikj.top/Article/details/gtkytoghpo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yvedp.cn/Article/details/gttksxijia.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jqgfzy.top/Article/details/gtxntihkbh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jqgufenzy.top/Article/details/gtgkuhlxxa.html

TS:   s.match(/\d+/g)
来源：http://dali.vqdsnc.cn/Article/details/gtjuyslybu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tianlin.xyz/Article/details/gtbjxxdhhz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.feifeiyinyue.top/Article/details/gtotrltffl.html

Ruby: s.scan(/\d+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytwyuipt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cheryme.top/Article/details/gtucifmaok.html

[I03] 提取捕获分组
来源：http://dali.kuanghao11.cn/Article/details/gtxibezsdk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.bjfxy.top/Article/details/gtucqfdoat.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nwbrower.top/Article/details/gtgwjlybaq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sxryk.cn/Article/details/gtkktedhia.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.vqdsnc.cn/Article/details/gtzmgizdjg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gogol.net.cn/Article/details/gtrfureaev.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hammf.cn/Article/details/gtukrdsqag.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hywenlv.cn/Article/details/gtszrrtkpn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xylfe.cn/Article/details/gtgiralfby.html

[I04] 正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvnkgbeo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtjeohwabm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxjqyhsh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpehfjdem.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigufen.top/Article/details/gtclddgzwf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cheryme.top/Article/details/gtisiefalj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.iojbl.cn/Article/details/gtzyomnmyj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtopnkjcoq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jianghu66.top/Article/details/gtnfjhfhet.html

[I05] 按正则拆分
来源：http://dali.kuanghao11.cn/Article/details/gtuequwdnt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.guannengcc.top/Article/details/gtlyrhjqgj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hysaishi.cn/Article/details/gtzrbnicdk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gtuhkatfrm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gtlqnksfuq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhiwuduotai.top/Article/details/gtennjwdhr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jianghu66.top/Article/details/gtwclapsmn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gtwzrffqyb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jiagoushi.top/Article/details/gtzcfqamfs.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gotoacloud.top/Article/details/gthcdusuen.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gtmioqcxfo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tanke756.top/Article/details/gtymtwiipr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pengpengdd.cyou/Article/details/gtslvqibyg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ybcxt.top/Article/details/gtcjygtgwh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gtzisqdtvb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.c1oappe.top/Article/details/gtavzkyitz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shuidangran.top/Article/details/gtnwqsfepk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gtuemtsvpn.html

[I07] 忽略大小写与多行模式
来源：http://dali.smart0.xyz/Article/details/gtdcwtspbd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xinyue.icu/Article/details/gtjnmxzjod.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cucudq.cn/Article/details/gtduckswlg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zycfv.cn/Article/details/gtwtbuhtbo.html

TS:   /error/gim
来源：http://dali.zhiwuduotai.top/Article/details/gttnhxgbng.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yongpay.top/Article/details/gtvqiyebvn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.c1oappe.top/Article/details/gtrquanwsg.html

Ruby: s.scan(/error/i)
来源：http://dali.zhoulong.xyz/Article/details/gtpxqvbxwb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yuanzhike.top/Article/details/gtujwsukta.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yuanzhike.top/Article/details/gttanuxemi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xinyue.icu/Article/details/gtkkqhejyw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yonumen.top/Article/details/gtkjsrwxsw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrbzlcovp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnqzz.top/Article/details/gtbhmmfkua.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gtewgylwvz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yvedp.cn/Article/details/gtjrphpdvf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.guannengcc.top/Article/details/gtzdegwlkr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.meibo888.top/Article/details/gtoxmhrhop.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtadjpsadj.html

J. 日期与时间
来源：http://dali.pycfn.com/Article/details/gtqgazczdl.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtmunvqhwh.html

[J01] 获取当前时间
来源：http://dali.xuetiantiany.cn/Article/details/gtgqkcuiro.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zycfv.cn/Article/details/gtxxzqimmh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.fzhhl.top/Article/details/gtzhohxcaz.html

JS:   new Date();  Date.now()
来源：http://dali.dashuyun.cn/Article/details/gtfucngdjo.html

TS:   new Date();  Date.now()
来源：http://dali.zhongyouzk.top/Article/details/gtvtdirrpt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gtnywlncdg.html

Go:   time.Now()
来源：http://dali.nanxuanxn.top/Article/details/gtznwtxtbz.html

Ruby: Time.now
来源：http://dali.jyoumei.cn/Article/details/gtaavckcjx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinqigfzy.top/Article/details/gthtkqdgrx.html

[J02] 格式化输出
来源：http://dali.cqqwz.cn/Article/details/gtwoputtua.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.redwolf501.top/Article/details/gtxwybzmwf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cdnleiting.top/Article/details/gtgzwuqyrc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yueranfly.top/Article/details/gtdhupugov.html

TS:   d.toISOString()
来源：http://dali.tianlin.xyz/Article/details/gtkdvbajze.html


<!-- 参考信息 -->