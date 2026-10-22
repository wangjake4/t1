代发 wailian999

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtxokxtrux.html

JS:   greet() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtzclvoqhl.html

TS:   greet(): string { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtwuvfyqzl.html

Java: String greet() { return name; }
来源：http://dali.yvedp.cn/Article/details/gtomsctngb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtgerevktm.html

Ruby: def greet; @name; end
来源：http://dali.zhengqikj.top/Article/details/gtjvurbnzb.html

C#:   public string Greet() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtictjczhl.html

[G05] 继承
来源：http://dali.yongpay.top/Article/details/gtqbycpxoa.html

Py:   class Admin(User): pass
来源：http://dali.9152youxi.cn/Article/details/gtcaekuxmp.html

PHP:  class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtfntzxbit.html

JS:   class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtmepdolsi.html

TS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvkltxirl.html

Java: class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gtlnnysmmk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvspklhyj.html

Ruby: class Admin < User; end
来源：http://dali.cashguo.top/Article/details/gtojkiwdch.html

C#:   class Admin : User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbrrspzim.html

[G06] 重写方法
来源：http://dali.ehwqpu.com/Article/details/gtnpevogfe.html

Py:   def greet(self): return "admin"
来源：http://dali.shanyushiyangtech.top/Article/details/gtuyxwejqq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtksnpmzco.html

JS:   greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtwhcgdzfl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtqoyxfgjt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtsekcayqj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.kuanghao11.cn/Article/details/gtckselkca.html

Ruby: def greet; "admin"; end
来源：http://dali.hysaishi.cn/Article/details/gtxuouuawp.html

C#:   public override string Greet() => "admin";
来源：http://dali.gotoacloud.top/Article/details/gtyuabtplt.html

[G07] 调用父类方法
来源：http://dali.cucudq.cn/Article/details/gtuvykevdg.html

Py:   super().greet()
来源：http://dali.c1oappe.top/Article/details/gtixeekmbg.html

PHP:  parent::greet();
来源：http://dali.cheryme.top/Article/details/gtgaftvpxl.html

JS:   super.greet();
来源：http://dali.chenlongwang.top/Article/details/gtmpnwrzgb.html

TS:   super.greet();
来源：http://dali.hammf.cn/Article/details/gtxapeofww.html

Java: super.greet();
来源：http://dali.bjfxy.top/Article/details/gtcemkbdkl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfwdoywke.html

Ruby: super
来源：http://dali.quarkkingdee.top/Article/details/gtenawhtyn.html

C#:   base.Greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtodsvquww.html

[G08] 静态方法与属性
来源：http://dali.jinqigfzy.top/Article/details/gttcgjdjlf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjxgpufc.html

PHP:  public static function f() {}
来源：http://dali.c1oappe.top/Article/details/gtpsvxoeaz.html

JS:   static f() {}
来源：http://dali.hfpthk.cn/Article/details/gthgtjiwet.html

TS:   static f(): void {}
来源：http://dali.zhengqikj.top/Article/details/gtupfqvkmn.html

Java: static void f() {}
来源：http://dali.dianchejie.cn/Article/details/gtqoepqgmv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.0kj1m.cn/Article/details/gtcluqfyhy.html

Ruby: def self.f; end
来源：http://dali.vqdsnc.cn/Article/details/gtxaszrbkh.html

C#:   public static void F() {}
来源：http://dali.gotoacloud.top/Article/details/gtpobhuagq.html

[G09] 接口 / 抽象类
来源：http://dali.jyoumei.cn/Article/details/gtclkpmezk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvjqcyfo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cucudq.cn/Article/details/gtwnfkpnxn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.birdmap.top/Article/details/gtgzvpmmpn.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj202588.top/Article/details/gtewucebmq.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdwjnyrol.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nwbrower.top/Article/details/gtkflwelkr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yvedp.cn/Article/details/gtuglaolaq.html

C#:   interface IShape { double Area(); }
来源：http://dali.gogol.net.cn/Article/details/gthsjjgbyv.html

[G10] 访问控制
来源：http://dali.hongshengwenyu.top/Article/details/gtshjiktwe.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.bjfxy.top/Article/details/gtaopalpeh.html

PHP:  public / protected / private
来源：http://dali.hammf.cn/Article/details/gtfzghfyjm.html

JS:   #private 字段；其余公开
来源：http://dali.yueranfly.top/Article/details/gtcdgxxakt.html

TS:   public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtiltvrtpk.html

Java: public / protected / private / 默认包级
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthmygtriy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.quarkkingdee.top/Article/details/gtplyuawpu.html

Ruby: public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gtkhxtrnao.html

C#:   public / protected / private / internal
来源：http://dali.smart0.xyz/Article/details/gtrxfsdmae.html

[G11] getter / setter
来源：http://dali.xuetiantiany.cn/Article/details/gtvwieidfc.html

Py:   @property 与 @x.setter
来源：http://dali.fzhhl.top/Article/details/gtpiaplhic.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtakpqcl.html

JS:   get name() { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtjncmynca.html

TS:   get name(): string { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gtcxlcjxtw.html

Java: public String getName() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtirljznfd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gtzuavqwov.html

Ruby: attr_accessor :name
来源：http://dali.jinqigufen.top/Article/details/gtuesxfzpv.html

C#:   public string Name { get; set; }
来源：http://dali.yuxming.cn/Article/details/gtaympdiro.html

[G12] 对象转字符串
来源：http://dali.dashuyun.cn/Article/details/gtsrvjtitg.html

Py:   def __str__(self): return self.name
来源：http://dali.cashguo.top/Article/details/gtfjepdqgz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gtltntqrha.html

JS:   toString() { return this.name; }
来源：http://dali.sweek.top/Article/details/gtjstzkcaq.html

TS:   toString(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtvigatbdp.html

Java: @Override public String toString() { return name; }
来源：http://dali.aizwys.cn/Article/details/gtbeuyepal.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gtjzzqbggh.html

Ruby: def to_s; @name; end
来源：http://dali.quarkkingdee.top/Article/details/gtrpgvjbqa.html

C#:   public override string ToString() => Name;
来源：http://dali.gaohongyu789.top/Article/details/gtnlfzbnou.html

[G13] 判断对象类型
来源：http://dali.shuidangran.top/Article/details/gtmdrinelt.html

Py:   isinstance(u, User)
来源：http://dali.redwolf501.top/Article/details/gtwuqeltmk.html

PHP:  $u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtpebwwawp.html

JS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtqmrpyede.html

TS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtmfisjtks.html

Java: u instanceof User
来源：http://dali.fengsongda.top/Article/details/gthqwguicf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yongpay.top/Article/details/gtvxlvzeyc.html

Ruby: u.is_a?(User)
来源：http://dali.xinyue.icu/Article/details/gtrjxnjzlq.html

C#:   u is User
来源：http://dali.xuanzx.com/Article/details/gtwzhdedmy.html

[G14] 数据类 / record
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrcxsilae.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.pycfn.com/Article/details/gtgebdphsx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sufxvd.cn/Article/details/gtfyegetlb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shanyushiyangtech.top/Article/details/gtvnvgwwjn.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenjidiqi.icu/Article/details/gtzluucfdm.html

Java: record User(String name, int age) {}
来源：http://dali.guowangkeji.top/Article/details/gtjbxryicj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hfpthk.cn/Article/details/gtwryulgzu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hnxiangtu.top/Article/details/gtevwnnyfr.html

C#:   record User(string Name, int Age);
来源：http://dali.gaohongyu789.top/Article/details/gtuvueyxxg.html

[G15] 枚举
来源：http://dali.wangdashe.top/Article/details/gtteezrxhj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtmfhtxfjy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yueranfly.top/Article/details/gtdllamrkq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tianlin.xyz/Article/details/gtperhlkbw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gtyydfolix.html

Java: enum Color { RED, GREEN }
来源：http://dali.yanxiufei.cn/Article/details/gtkxumfzrh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ehwqpu.com/Article/details/gtkiiozeqg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.dianchejie.cn/Article/details/gtwihmraoc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjozospv.html

[G16] 对象转数组 / 字典
来源：http://dali.hongshengwenyu.top/Article/details/gtartgnpbr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hnqzz.top/Article/details/gtxubrfkpu.html

PHP:  get_object_vars($obj);
来源：http://dali.redwolf501.top/Article/details/gttdtjhwii.html

JS:   Object.entries(obj)
来源：http://dali.tian-w.cn/Article/details/gtsvorqhgv.html

TS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gtzqgdcyng.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.c1oappe.top/Article/details/gtumnppxcf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ppjwa.cn/Article/details/gtyaujuqep.html

Ruby: obj.instance_variables
来源：http://dali.jinqigfzy.top/Article/details/gtwksxbtyi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.havefunace.top/Article/details/gtvenyvagd.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtvweqaoej.html

H. 异常与错误处理
来源：http://dali.shangyingyoupin.top/Article/details/gtrdwqysyk.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtmlsfegec.html

[H01] try / catch 基础
来源：http://dali.yj202588.top/Article/details/gtqipwzkgo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yanxiufei.cn/Article/details/gtynmzclyo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jyoumei.cn/Article/details/gtclzfczbk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gtmpmsnjgd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gtjwozmtsj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.snrcjt.cn/Article/details/gtgikyjqbn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sxryk.cn/Article/details/gtdwgavhgj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ydzc1.top/Article/details/gttbigzcre.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuxming.cn/Article/details/gtolorscmc.html

[H02] finally / ensure 收尾
来源：http://dali.redwolf501.top/Article/details/gtiomcnlrv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.kuanghao11.cn/Article/details/gtzylhnbsz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtslwoiqvd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtppwtbojv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtxnvaeboc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtlxrkwlmj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zycfv.cn/Article/details/gthuyxmpit.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ybcxt.top/Article/details/gtyktemnjx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtyatpbenh.html

[H03] 主动抛出异常
来源：http://dali.zhixingplan.top/Article/details/gttnppqnzv.html

Py:   raise ValueError("错误信息")
来源：http://dali.ydzc1.top/Article/details/gtuzxeknkg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtjzhvoyva.html

JS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtcscupxbf.html

TS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtqxxwpkmg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtevteevrz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnygatxdu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258.top/Article/details/gtfadsddmz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtmdpsvbtg.html

[H04] 自定义异常类型
来源：http://dali.ydzc1.top/Article/details/gtnwjtfoyu.html

Py:   class MyError(Exception): pass
来源：http://dali.nwbrower.top/Article/details/gtvkbrbawr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xziqi.cn/Article/details/gtmztvlckd.html

JS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gtwgmsqqms.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtrcguzyez.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xylfe.cn/Article/details/gthcfuthan.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.smart0.xyz/Article/details/gteizyeuey.html

Ruby: class MyError < StandardError; end
来源：http://dali.sweek.top/Article/details/gtxfafsqju.html

C#:   class MyException : Exception {}
来源：http://dali.sufxvd.cn/Article/details/gthkbtfqjq.html

[H05] 捕获特定类型
来源：http://dali.dashuyun.cn/Article/details/gtoncojrvh.html

Py:   except ValueError as e:
来源：http://dali.smart0.xyz/Article/details/gtdifrmoto.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shzxlz.cn/Article/details/gtkkvvgvig.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xuanzx.com/Article/details/gtjdinctpt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.svipenyu.cn/Article/details/gtpxdvptnd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhengqikj.top/Article/details/gtrqaqfrig.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenlongwang.top/Article/details/gtdeudmnvc.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhixingplan.top/Article/details/gtzlsbditr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj20258888.top/Article/details/gtsfjbspsr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.mhx1999.top/Article/details/gtnpzjvwyz.html

Py:   value = d.get("k") or default
来源：http://dali.redwolf501.top/Article/details/gtoqezolsl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.guannengcc.top/Article/details/gtbsblybox.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gtsmpgnkju.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.aizwys.cn/Article/details/gtzamhmkwj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yangfankeji.com/Article/details/gtqeibagep.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.daria6918.cn/Article/details/gtkcoxkuei.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ydzc1.top/Article/details/gtqprngzfe.html

C#:   obj?.A?.B ?? default
来源：http://dali.cashguo.top/Article/details/gtnnhvxdsx.html

[H07] 断言
来源：http://dali.xuanzx.com/Article/details/gtveszdqku.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ybcxt.top/Article/details/gtfmelxqek.html

PHP:  assert($x > 0);
来源：http://dali.zdqjudy.top/Article/details/gtgarqtywv.html

JS:   console.assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtszyuiblb.html

TS:   console.assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gttxwqicny.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnxiangtu.top/Article/details/gtjvmkhgcs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gzhubu.top/Article/details/gtbmdeoofx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.316326.xyz/Article/details/gtmfyobwny.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtjsgzgbqr.html

[H08] 获取错误信息与堆栈
来源：http://dali.yuxming.cn/Article/details/gtorgfnjfb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ydzc1.top/Article/details/gtnchitjec.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hnxiangtu.top/Article/details/gtbngkzjgb.html

JS:   e.message;  e.stack
来源：http://dali.hysaishi.cn/Article/details/gtcspshidw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenjidiqi.icu/Article/details/gthuanunzm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnxiangtu.top/Article/details/gtlyevubkd.html

Go:   err.Error()
来源：http://dali.fzhhl.top/Article/details/gtglektmgk.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinghuilouyu.cn/Article/details/gtukckspil.html

C#:   e.Message;  e.StackTrace
来源：http://dali.aizwys.cn/Article/details/gtlnqxlfqe.html

[H09] 带错误码的异常
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwxvpnpg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.vqdsnc.cn/Article/details/gtwqelpoyx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangshuangyany.cn/Article/details/gtyakysyae.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hysaishi.cn/Article/details/gttcrsodvf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cucudq.cn/Article/details/gtsyrirwua.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.quarkkingdee.top/Article/details/gtdxozvfdm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhoulong.xyz/Article/details/gtcmesqvqf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cheryme.top/Article/details/gthltnjmqv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinqigfzy.top/Article/details/gterystiho.html

[H10] 资源自动释放
来源：http://dali.yvedp.cn/Article/details/gtwubmtjzm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.bjfxy.top/Article/details/gtcnqgpxwb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hfpthk.cn/Article/details/gtmdkanyul.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xylfe.cn/Article/details/gtkeynpsqm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cdnleiting.top/Article/details/gtgoacouoz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.iojbl.cn/Article/details/gtkregypgq.html

Go:   defer f.Close()
来源：http://dali.yueranfly.top/Article/details/gtrvejqgfz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zycfv.cn/Article/details/gtmlciqnht.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpsmdrclt.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtfhgsbvon.html

I. 正则表达式
来源：http://dali.zhoulong.xyz/Article/details/gtuzqudalf.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtyyekligy.html

[I01] 判断是否匹配
来源：http://dali.sufxvd.cn/Article/details/gtotjpobkp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtoaspngdm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtglviutyw.html

JS:   /\d+/.test(s)
来源：http://dali.yj20258888.top/Article/details/gtmhkfwkhh.html

TS:   /\d+/.test(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuheibsur.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sufxvd.cn/Article/details/gtfmzpdxwd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqswjyxgv.html

Ruby: s.match?(/\d+/)
来源：http://dali.mhx1999.top/Article/details/gtgaddvuir.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuanzhike.top/Article/details/gtyfawabeh.html

[I02] 提取所有匹配
来源：http://dali.yj20258.top/Article/details/gttasqrtia.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsjnbdfxp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.pycfn.com/Article/details/gtyouzxfvf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxinkj.top/Article/details/gtuzycuzhr.html

TS:   s.match(/\d+/g)
来源：http://dali.yvedp.cn/Article/details/gtnrgnurak.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jlsjyb.cn/Article/details/gtunxproqd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hnqzz.top/Article/details/gtmnscszql.html

Ruby: s.scan(/\d+/)
来源：http://dali.jqgfzy.top/Article/details/gtuhuwehep.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkupsqrsz.html

[I03] 提取捕获分组
来源：http://dali.yongpay.top/Article/details/gtwlkuhjmk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gogol.net.cn/Article/details/gtteezvybb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tanke756.top/Article/details/gtpmlfhxxs.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gogol.net.cn/Article/details/gtrmpeykus.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.vqdsnc.cn/Article/details/gtuetxfgsz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj20258.top/Article/details/gtixrjxype.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.iojbl.cn/Article/details/gtgafcxotv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shzxlz.cn/Article/details/gtgaakhxol.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nanxuanxn.top/Article/details/gtczgdukur.html

[I04] 正则替换
来源：http://dali.ehwqpu.com/Article/details/gtfmeaguwr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jqgfzy.top/Article/details/gtiucbolsl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tian-w.cn/Article/details/gtclsqwvyy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhixingplan.top/Article/details/gtafcmjafv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtatilyngc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gtwisblktf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.guowangkeji.top/Article/details/gtttlnfhbt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zycfv.cn/Article/details/gtgfrxylxd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gotoacloud.top/Article/details/gtrzdqwvnu.html

[I05] 按正则拆分
来源：http://dali.nanxinkj.top/Article/details/gtbycrdodr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pycfn.com/Article/details/gtbzmphpxc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwvjdwonh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gtoceaxvoi.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gtitoxohuj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.wangdashe.top/Article/details/gtzkmunbzn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cqqwz.cn/Article/details/gtofkenxpx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gtkycpixzx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zycfv.cn/Article/details/gtzhydelng.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ehwqpu.com/Article/details/gtlewvxnee.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gthrxtnxqr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cqqwz.cn/Article/details/gtiuzlqqvu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj202588.top/Article/details/gtiqlxtqxm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gtwlvvhpkh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gtgehpudur.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenlongwang.top/Article/details/gtdnpmqqvg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hywenlv.cn/Article/details/gtokbdvrwn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtbelukvja.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenlongwang.top/Article/details/gtdyidynpn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ivvv.top/Article/details/gtisbixslb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenjidiqi.icu/Article/details/gtazqgtoky.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hnxiangtu.top/Article/details/gtjnwwovhf.html

TS:   /error/gim
来源：http://dali.hywenlv.cn/Article/details/gtaipjacui.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.guannengcc.top/Article/details/gtojayojzl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jiagoushi.top/Article/details/gthcxdxxoo.html

Ruby: s.scan(/error/i)
来源：http://dali.pycfn.com/Article/details/gtjmmmwihh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.havefunace.top/Article/details/gtffvhbqah.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtkzljsdnz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cdnleiting.top/Article/details/gtlmnuiszr.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yongpay.top/Article/details/gtniyqefni.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ivvv.top/Article/details/gttndwlrrj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ppjwa.cn/Article/details/gtpfjtghcs.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hongshengwenyu.top/Article/details/gtmamnzmeb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gtbgbjddfd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hongshengwenyu.top/Article/details/gtorhgyubt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.kuanghao11.cn/Article/details/gtnbfquezs.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtszdksbkb.html

J. 日期与时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsjcqowxj.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gterodhxtn.html

[J01] 获取当前时间
来源：http://dali.316326.xyz/Article/details/gtehuojhkh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.aibaodan.cn/Article/details/gtknpexakn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.wangshuangyany.cn/Article/details/gtbwxrneap.html

JS:   new Date();  Date.now()
来源：http://dali.jinqigufen.top/Article/details/gtxocoeahb.html

TS:   new Date();  Date.now()
来源：http://dali.jianghu66.top/Article/details/gtapzvgdvk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sxryk.cn/Article/details/gtqxmkeyqn.html

Go:   time.Now()
来源：http://dali.ybcxt.top/Article/details/gtblgluczm.html

Ruby: Time.now
来源：http://dali.xuetiantiany.cn/Article/details/gtbnlpkaqx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.quarkkingdee.top/Article/details/gtzfprcroy.html

[J02] 格式化输出
来源：http://dali.xuetiantiany.cn/Article/details/gtwoorwyhd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.havefunace.top/Article/details/gtfibpmwqr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xylfe.cn/Article/details/gtosqfjmkl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsszozaka.html

TS:   d.toISOString()
来源：http://dali.xziqi.cn/Article/details/gttvznfssc.html


<!-- 参考信息 -->