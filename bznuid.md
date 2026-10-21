代发 wailian999

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gtpuivdoij.html

JS:   greet() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtyumcofeb.html

TS:   greet(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gtmrdodyet.html

Java: String greet() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtgtoqqqcw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtmvrkrwpz.html

Ruby: def greet; @name; end
来源：http://dali.hfpthk.cn/Article/details/gtsbjyvkyo.html

C#:   public string Greet() => Name;
来源：http://dali.andypj.xyz/Article/details/gtfdoxbfjz.html

[G05] 继承
来源：http://dali.yanxiufei.cn/Article/details/gtwggrcgor.html

Py:   class Admin(User): pass
来源：http://dali.sxryk.cn/Article/details/gtdvoumbpb.html

PHP:  class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtgpbpjncj.html

JS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtzttsohwu.html

TS:   class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtdkpnolty.html

Java: class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gthxykwwhj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenlongwang.top/Article/details/gtiqmxizbq.html

Ruby: class Admin < User; end
来源：http://dali.xinyue.icu/Article/details/gttleakklk.html

C#:   class Admin : User {}
来源：http://dali.tanke756.top/Article/details/gtafaoclro.html

[G06] 重写方法
来源：http://dali.yuxming.cn/Article/details/gthqtdmojc.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258.top/Article/details/gtdinmmbje.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtxdmeedop.html

JS:   greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzzgcxptc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtqftlumeh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtgfahublv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xinyue.icu/Article/details/gtplytobjx.html

Ruby: def greet; "admin"; end
来源：http://dali.guowangkeji.top/Article/details/gtrbjmsaht.html

C#:   public override string Greet() => "admin";
来源：http://dali.ivvv.top/Article/details/gtmnvjeofd.html

[G07] 调用父类方法
来源：http://dali.fengsongda.top/Article/details/gtwpvkieki.html

Py:   super().greet()
来源：http://dali.aibaodan.cn/Article/details/gtsfppoxub.html

PHP:  parent::greet();
来源：http://dali.yangfankeji.com/Article/details/gtruqtkwvj.html

JS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtuaziycnm.html

TS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtdfaximbj.html

Java: super.greet();
来源：http://dali.yangfankeji.com/Article/details/gtbaxcoaar.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yueranfly.top/Article/details/gtxqeasuci.html

Ruby: super
来源：http://dali.jlsjyb.cn/Article/details/gtrbzwcifo.html

C#:   base.Greet();
来源：http://dali.guannengcc.top/Article/details/gtrwylbsml.html

[G08] 静态方法与属性
来源：http://dali.iojbl.cn/Article/details/gtpubpewko.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shangyingyoupin.top/Article/details/gtqymmuayg.html

PHP:  public static function f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gttdyofkaf.html

JS:   static f() {}
来源：http://dali.cqqwz.cn/Article/details/gtucjebygl.html

TS:   static f(): void {}
来源：http://dali.dashuyun.cn/Article/details/gtjeuaxwah.html

Java: static void f() {}
来源：http://dali.tanke756.top/Article/details/gtmyhxasyi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpoqxoezv.html

Ruby: def self.f; end
来源：http://dali.kuanghao11.cn/Article/details/gtsovzjijz.html

C#:   public static void F() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrydzlcho.html

[G09] 接口 / 抽象类
来源：http://dali.jinqigfzy.top/Article/details/gtyleymxso.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yueranfly.top/Article/details/gtvmlzfhhn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.kuanghao11.cn/Article/details/gtfuafleen.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yangfankeji.com/Article/details/gtxvrnluox.html

TS:   interface Shape { area(): number; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtspsojtbi.html

Java: interface Shape { double area(); }
来源：http://dali.snrcjt.cn/Article/details/gttdvuwssa.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgzlpdqxm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shangyingyoupin.top/Article/details/gtypffxggw.html

C#:   interface IShape { double Area(); }
来源：http://dali.nwbrower.top/Article/details/gtekozqxse.html

[G10] 访问控制
来源：http://dali.vqdsnc.cn/Article/details/gtwbuotigc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfxuyyed.html

PHP:  public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gtzzfiolou.html

JS:   #private 字段；其余公开
来源：http://dali.jianghu66.top/Article/details/gticzpnfuc.html

TS:   public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gtfreixfnz.html

Java: public / protected / private / 默认包级
来源：http://dali.yuanzhike.top/Article/details/gtweovacgu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.fzhhl.top/Article/details/gtbrgjcmio.html

Ruby: public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gtqdlvxtjh.html

C#:   public / protected / private / internal
来源：http://dali.316326.xyz/Article/details/gttiqhfcgq.html

[G11] getter / setter
来源：http://dali.redwolf501.top/Article/details/gtucuzurxn.html

Py:   @property 与 @x.setter
来源：http://dali.hongshengwenyu.top/Article/details/gtohnderjm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtumakppgh.html

JS:   get name() { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gtzhdqsegn.html

TS:   get name(): string { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gtulavltsp.html

Java: public String getName() { return name; }
来源：http://dali.xziqi.cn/Article/details/gtqrnjsjgb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gtpxbopyxu.html

Ruby: attr_accessor :name
来源：http://dali.chenlongwang.top/Article/details/gtruzoeoev.html

C#:   public string Name { get; set; }
来源：http://dali.9152youxi.cn/Article/details/gtkacemiiv.html

[G12] 对象转字符串
来源：http://dali.316326.xyz/Article/details/gtafeegfad.html

Py:   def __str__(self): return self.name
来源：http://dali.yvedp.cn/Article/details/gtkilcdfwf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gtldqwocuj.html

JS:   toString() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtogcibdsl.html

TS:   toString(): string { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtlqfbrrak.html

Java: @Override public String toString() { return name; }
来源：http://dali.fzhhl.top/Article/details/gtofqcydol.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gtyfrdfzbu.html

Ruby: def to_s; @name; end
来源：http://dali.quarkkingdee.top/Article/details/gtpjwvjpmw.html

C#:   public override string ToString() => Name;
来源：http://dali.cucudq.cn/Article/details/gtxbamlbqm.html

[G13] 判断对象类型
来源：http://dali.yanxiufei.cn/Article/details/gtlycnkxoa.html

Py:   isinstance(u, User)
来源：http://dali.yj202588.top/Article/details/gthtyymhsi.html

PHP:  $u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtrbeyeoaz.html

JS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtnymvgpqa.html

TS:   u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtcylpygpt.html

Java: u instanceof User
来源：http://dali.yj202588.top/Article/details/gtyblkgbty.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gtjjodcusp.html

Ruby: u.is_a?(User)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwgzqtael.html

C#:   u is User
来源：http://dali.kuanghao11.cn/Article/details/gtqyovgnex.html

[G14] 数据类 / record
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoxzujrpw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sxryk.cn/Article/details/gtnwkanotu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xylfe.cn/Article/details/gtznwrngon.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuetiantiany.cn/Article/details/gttkrzuouq.html

TS:   type User = { name: string; age: number };
来源：http://dali.kuanghao11.cn/Article/details/gthutnkltk.html

Java: record User(String name, int age) {}
来源：http://dali.hywenlv.cn/Article/details/gtfryziyzc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zycfv.cn/Article/details/gttcaiguvx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yuanzhike.top/Article/details/gtzlneqviu.html

C#:   record User(string Name, int Age);
来源：http://dali.hnxiangtu.top/Article/details/gtunwpebxn.html

[G15] 枚举
来源：http://dali.shuidangran.top/Article/details/gtcsbfotel.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gtfjoafvpk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.9152youxi.cn/Article/details/gtcgioqlps.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yuanzhike.top/Article/details/gtkxpbkvpc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gtwglxglqp.html

Java: enum Color { RED, GREEN }
来源：http://dali.fengsongda.top/Article/details/gtaeahgsyj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.vqdsnc.cn/Article/details/gtbvevrcuw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hfpthk.cn/Article/details/gtiyaajwvl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpbzfsbt.html

[G16] 对象转数组 / 字典
来源：http://dali.xuanzx.com/Article/details/gtsbdizzgt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ivvv.top/Article/details/gtwvinxfun.html

PHP:  get_object_vars($obj);
来源：http://dali.nanxuanxn.top/Article/details/gtkenetcjr.html

JS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gtveskthdd.html

TS:   Object.entries(obj)
来源：http://dali.iojbl.cn/Article/details/gtlmpmbeqg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwrjhjlgd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.andypj.xyz/Article/details/gthbuypdck.html

Ruby: obj.instance_variables
来源：http://dali.daxiang520.top/Article/details/gtljwuminu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ydzc1.top/Article/details/gtcaekbbby.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtikansxki.html

H. 异常与错误处理
来源：http://dali.chenzaomai.com/Article/details/gtjkbevzsi.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtawionquj.html

[H01] try / catch 基础
来源：http://dali.zhixingplan.top/Article/details/gtkgkxrait.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guowangkeji.top/Article/details/gtbkplhefi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.316326.xyz/Article/details/gtbbewizvk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xylfe.cn/Article/details/gtqpotqcoo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gtjqzdfrfc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xylfe.cn/Article/details/gtyezserbx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnqzz.top/Article/details/gtlcjggwlb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ivvv.top/Article/details/gtkjqemumm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.iojbl.cn/Article/details/gtzdkmdxkc.html

[H02] finally / ensure 收尾
来源：http://dali.jqgufenzy.top/Article/details/gttehekpfg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tianlin.xyz/Article/details/gtvihmhuvo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtqfatmkvl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gteqgigfvv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtljqmpbob.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtnjtvdqwf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xinyue.icu/Article/details/gtfjwmgsxm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aizwys.cn/Article/details/gtjgsiroyz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtfyzbvvcs.html

[H03] 主动抛出异常
来源：http://dali.pengpengdd.cyou/Article/details/gtwueuvemn.html

Py:   raise ValueError("错误信息")
来源：http://dali.birdmap.top/Article/details/gtvxmlbdjp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtamjnseka.html

JS:   throw new Error("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtkndegbwh.html

TS:   throw new Error("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsaztnrxh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtdbeqgbdv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hnqzz.top/Article/details/gttowlyzbs.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ivvv.top/Article/details/gtrxeokuhf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtlcmsoisb.html

[H04] 自定义异常类型
来源：http://dali.xuetiantiany.cn/Article/details/gtgkwisxij.html

Py:   class MyError(Exception): pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqqdcnnke.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuxming.cn/Article/details/gtynokvdly.html

JS:   class MyError extends Error {}
来源：http://dali.yongpay.top/Article/details/gtjnjdysiw.html

TS:   class MyError extends Error {}
来源：http://dali.zycfv.cn/Article/details/gtxltueljp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gtngczudsk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.havefunace.top/Article/details/gtbypynjar.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhiwuduotai.top/Article/details/gtgykelfzb.html

C#:   class MyException : Exception {}
来源：http://dali.sysykeji.top/Article/details/gtflbhkony.html

[H05] 捕获特定类型
来源：http://dali.yonumen.top/Article/details/gtclxsqyuc.html

Py:   except ValueError as e:
来源：http://dali.mhx1999.top/Article/details/gtvvayissp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.316326.xyz/Article/details/gtauijanii.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gtxooetwcb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tian-w.cn/Article/details/gteetifoeq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.9152youxi.cn/Article/details/gtcjvxqsrk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cashguo.top/Article/details/gtisndlnff.html

Ruby: rescue ArgumentError => e
来源：http://dali.sufxvd.cn/Article/details/gthgegmxko.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jqgfzy.top/Article/details/gtyhykuvlk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.pengpengdd.cyou/Article/details/gtryhhxqty.html

Py:   value = d.get("k") or default
来源：http://dali.feifeiyinyue.top/Article/details/gtvxvblbqs.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tianlin.xyz/Article/details/gtinngmnls.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sweek.top/Article/details/gtmzqtvdoz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cdnleiting.top/Article/details/gtzehwddlq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cashguo.top/Article/details/gtqkahyfog.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sufxvd.cn/Article/details/gtwmrnsolr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hywenlv.cn/Article/details/gtghwsmihz.html

C#:   obj?.A?.B ?? default
来源：http://dali.jianghu66.top/Article/details/gtguoutyom.html

[H07] 断言
来源：http://dali.xuanzx.com/Article/details/gtfanraovg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuanzx.com/Article/details/gtvxblslrr.html

PHP:  assert($x > 0);
来源：http://dali.bjfxy.top/Article/details/gthkxukajy.html

JS:   console.assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gtvvgdmjmf.html

TS:   console.assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gtvrzdoilb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.havefunace.top/Article/details/gtiyyfdouv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gtepbgxuwi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.andypj.xyz/Article/details/gtnahyqsib.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gtqexgkcxi.html

[H08] 获取错误信息与堆栈
来源：http://dali.guowangkeji.top/Article/details/gtivsrquzn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.andypj.xyz/Article/details/gtgifrpqye.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.daxiang520.top/Article/details/gtxcpueykn.html

JS:   e.message;  e.stack
来源：http://dali.zhiwuduotai.top/Article/details/gtbuihcwgi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yongpay.top/Article/details/gtamdegqbb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.wangshuangyany.cn/Article/details/gtizensezq.html

Go:   err.Error()
来源：http://dali.wangdashe.top/Article/details/gtoaquvmvg.html

Ruby: e.message;  e.backtrace
来源：http://dali.zycfv.cn/Article/details/gtlvrnwtvf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.pycfn.com/Article/details/gteyldxbfc.html

[H09] 带错误码的异常
来源：http://dali.mhx1999.top/Article/details/gtadznwida.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.snrcjt.cn/Article/details/gtvvaavvzt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yongpay.top/Article/details/gtsngccchx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.meibo888.top/Article/details/gtodakthvw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yangfankeji.com/Article/details/gtwbnerixb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.aibaodan.cn/Article/details/gtltilcndu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tanke756.top/Article/details/gtafzqjovj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenjidiqi.icu/Article/details/gtxdyhuqda.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cucudq.cn/Article/details/gtepliixps.html

[H10] 资源自动释放
来源：http://dali.yj20258.top/Article/details/gtrnwaukhl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nanxinkj.top/Article/details/gtejrszcrx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.feifeiyinyue.top/Article/details/gtixkifniy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yangfankeji.com/Article/details/gtswymjsjf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhongyouzk.top/Article/details/gtybbzgaiy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenzaomai.com/Article/details/gtfopaspxy.html

Go:   defer f.Close()
来源：http://dali.9152youxi.cn/Article/details/gtecvrjqnx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hnxiangtu.top/Article/details/gtwxbgcbuj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtqinmephx.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtcltfqqls.html

I. 正则表达式
来源：http://dali.guannengcc.top/Article/details/gtvirpgbpq.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtbfdukcgr.html

[I01] 判断是否匹配
来源：http://dali.hywenlv.cn/Article/details/gtvrlopljx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gaohongyu789.top/Article/details/gtbkfkulju.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.9152youxi.cn/Article/details/gtebfclplb.html

JS:   /\d+/.test(s)
来源：http://dali.sweek.top/Article/details/gtspnuafpw.html

TS:   /\d+/.test(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdaktqwve.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ydzc1.top/Article/details/gtaulchauy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.haohaochexian.top/Article/details/gtdalxurus.html

Ruby: s.match?(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gtccsythaz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.aizwys.cn/Article/details/gtioiiflun.html

[I02] 提取所有匹配
来源：http://dali.9152youxi.cn/Article/details/gthyhegwef.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjttxodca.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yueranfly.top/Article/details/gtglgnfily.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.aibaodan.cn/Article/details/gtqceiyfuo.html

TS:   s.match(/\d+/g)
来源：http://dali.jinqigufen.top/Article/details/gtnzweufbb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sxryk.cn/Article/details/gtqmmyubbe.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shuidangran.top/Article/details/gtgyntisfh.html

Ruby: s.scan(/\d+/)
来源：http://dali.ivvv.top/Article/details/gtaycarzos.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtjzeubezi.html

[I03] 提取捕获分组
来源：http://dali.shuidangran.top/Article/details/gtmphwgbvs.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sufxvd.cn/Article/details/gtlymoxnbv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hysaishi.cn/Article/details/gtjchurigp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jlsjyb.cn/Article/details/gtxtnknvay.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hnxiangtu.top/Article/details/gttqmtlzpq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.bjfxy.top/Article/details/gtdllonxyf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.fzhhl.top/Article/details/gtziplcbti.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtnzyaliby.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangshuangyany.cn/Article/details/gthslgsohx.html

[I04] 正则替换
来源：http://dali.yonumen.top/Article/details/gtfektstey.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.bjfxy.top/Article/details/gtbemqzizx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.9152youxi.cn/Article/details/gtmpgeqzpe.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtspcaufqm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daria6918.cn/Article/details/gtbwhhcuap.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gtqqyvxstb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdklckzx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtodebqlkj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtquvxqhyh.html

[I05] 按正则拆分
来源：http://dali.tian-w.cn/Article/details/gtzhmrtnoq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzkwherxm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yangfankeji.com/Article/details/gtqpsvxemx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gtgaffkgcn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gtfuerpges.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jiagoushi.top/Article/details/gtbmqesfrs.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hysaishi.cn/Article/details/gtfmtpdaee.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gtzhqiefiv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hammf.cn/Article/details/gtrhyyhshg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shanyushiyangtech.top/Article/details/gthhofqego.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gtsbmwvrbm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jyoumei.cn/Article/details/gtzjewsjew.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sysykeji.top/Article/details/gttojhrdtc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fzhhl.top/Article/details/gtfxhvbsdl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cashguo.top/Article/details/gtdumounuv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.guowangkeji.top/Article/details/gtasyhgrxr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ivvv.top/Article/details/gtlhusyljc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gtdvfmrapo.html

[I07] 忽略大小写与多行模式
来源：http://dali.guannengcc.top/Article/details/gtezbgcitf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigfzy.top/Article/details/gtegbfdemn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gtmksxzvyk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.pengpengdd.cyou/Article/details/gtyojxjcnm.html

TS:   /error/gim
来源：http://dali.yonumen.top/Article/details/gtkmkvhbrd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenzaomai.com/Article/details/gteiwvstfv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenjidiqi.icu/Article/details/gtfdplmurr.html

Ruby: s.scan(/error/i)
来源：http://dali.shzxlz.cn/Article/details/gtfrrluwzt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hysaishi.cn/Article/details/gtrynihako.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtajfqjnjl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hnqzz.top/Article/details/gtemjsbtrv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gtnujjtjdg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yongpay.top/Article/details/gttwnxjhub.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daria6918.cn/Article/details/gtzhjradzr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gtspigzktd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.smart0.xyz/Article/details/gtrhkgyfmk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yueranfly.top/Article/details/gtvlluqwsa.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gtnjswuexn.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtvrszbfqr.html

J. 日期与时间
来源：http://dali.pycfn.com/Article/details/gtomlqyumk.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtgelbdzqj.html

[J01] 获取当前时间
来源：http://dali.nwbrower.top/Article/details/gtzjktfyry.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.wangshuangyany.cn/Article/details/gtmgfjtewz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.aibaodan.cn/Article/details/gtqclybaay.html

JS:   new Date();  Date.now()
来源：http://dali.nwbrower.top/Article/details/gtahxxvvtw.html

TS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gtkfqtcejt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shuidangran.top/Article/details/gtezextpex.html

Go:   time.Now()
来源：http://dali.aibaodan.cn/Article/details/gtfgkvbuic.html

Ruby: Time.now
来源：http://dali.pycfn.com/Article/details/gtwmfooxnn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yuanzhike.top/Article/details/gtwrwddjlb.html

[J02] 格式化输出
来源：http://dali.mhx1999.top/Article/details/gtvyqsldkq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cqqwz.cn/Article/details/gtladkpbjl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.svipenyu.cn/Article/details/gtpvcayhqe.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.meibo888.top/Article/details/gteqthsszs.html

TS:   d.toISOString()
来源：http://dali.yongpay.top/Article/details/gtrqivtvic.html


<!-- 参考信息 -->