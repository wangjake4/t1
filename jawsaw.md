代发 wailian999

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gtfvlrkpqw.html

JS:   greet() { return this.name; }
来源：http://dali.yj20258.top/Article/details/gtwfpgyqsu.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gttrkdtffb.html

Java: String greet() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtbyyyhriw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shanyushiyangtech.top/Article/details/gtelewxbgk.html

Ruby: def greet; @name; end
来源：http://dali.cqqwz.cn/Article/details/gtltajxqup.html

C#:   public string Greet() => Name;
来源：http://dali.hysaishi.cn/Article/details/gtaqgsbpaj.html

[G05] 继承
来源：http://dali.vqdsnc.cn/Article/details/gtwwnnzbdd.html

Py:   class Admin(User): pass
来源：http://dali.dianchejie.cn/Article/details/gtuoxmqmaj.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtybyrwsei.html

JS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtmrwztyom.html

TS:   class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtzpooezjl.html

Java: class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtiwomwuiz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkjmwukvi.html

Ruby: class Admin < User; end
来源：http://dali.yvedp.cn/Article/details/gtdaqiytoo.html

C#:   class Admin : User {}
来源：http://dali.svipenyu.cn/Article/details/gtqtvkdvha.html

[G06] 重写方法
来源：http://dali.shangyingyoupin.top/Article/details/gtnwunihjk.html

Py:   def greet(self): return "admin"
来源：http://dali.meibo888.top/Article/details/gtsmiqpodg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtfqyjjrvg.html

JS:   greet() { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtrfrgiscm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtrwtubnmz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtedxpylvi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cheryme.top/Article/details/gtwuxgmvku.html

Ruby: def greet; "admin"; end
来源：http://dali.xylfe.cn/Article/details/gtkuwpfvzh.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrfnxdlbj.html

[G07] 调用父类方法
来源：http://dali.yangfankeji.com/Article/details/gtmqefdcgb.html

Py:   super().greet()
来源：http://dali.gaohongyu789.top/Article/details/gtfpqzhcoo.html

PHP:  parent::greet();
来源：http://dali.aizwys.cn/Article/details/gtitwswxts.html

JS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gtbztgboag.html

TS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gtqcvnagcb.html

Java: super.greet();
来源：http://dali.fzhhl.top/Article/details/gtanjbcysy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shangyingyoupin.top/Article/details/gtlwbphlbt.html

Ruby: super
来源：http://dali.gzhubu.top/Article/details/gtvhyhkoyc.html

C#:   base.Greet();
来源：http://dali.snrcjt.cn/Article/details/gtrwmneupx.html

[G08] 静态方法与属性
来源：http://dali.wangdashe.top/Article/details/gtjzgtkzod.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuanzx.com/Article/details/gtodmodpta.html

PHP:  public static function f() {}
来源：http://dali.aibaodan.cn/Article/details/gtciayctxv.html

JS:   static f() {}
来源：http://dali.hysaishi.cn/Article/details/gtublvxaaw.html

TS:   static f(): void {}
来源：http://dali.meibo888.top/Article/details/gtfcklghqz.html

Java: static void f() {}
来源：http://dali.svipenyu.cn/Article/details/gttaixdoiv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhixingplan.top/Article/details/gtpcdjhkim.html

Ruby: def self.f; end
来源：http://dali.gotoacloud.top/Article/details/gtajewvikq.html

C#:   public static void F() {}
来源：http://dali.redwolf501.top/Article/details/gtzansrrzk.html

[G09] 接口 / 抽象类
来源：http://dali.dianchejie.cn/Article/details/gtyhrffcrh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj20258.top/Article/details/gtbsebdfow.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sysykeji.top/Article/details/gtvnogkhaf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.redwolf501.top/Article/details/gtiznpmtdm.html

TS:   interface Shape { area(): number; }
来源：http://dali.jiagoushi.top/Article/details/gtjdarwkct.html

Java: interface Shape { double area(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjcbyhfjv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hysaishi.cn/Article/details/gtiyvktjrj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.svipenyu.cn/Article/details/gthilwqdcw.html

C#:   interface IShape { double Area(); }
来源：http://dali.9152youxi.cn/Article/details/gtxanoscqm.html

[G10] 访问控制
来源：http://dali.ivvv.top/Article/details/gtnmkfzvug.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sufxvd.cn/Article/details/gtpotijzwq.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gttpojahhe.html

JS:   #private 字段；其余公开
来源：http://dali.9152youxi.cn/Article/details/gtahefndke.html

TS:   public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtthxfoawk.html

Java: public / protected / private / 默认包级
来源：http://dali.nanxinkj.top/Article/details/gtutvluczs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xylfe.cn/Article/details/gtqtujgfln.html

Ruby: public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtzpgkxaku.html

C#:   public / protected / private / internal
来源：http://dali.zhiwuduotai.top/Article/details/gtnbmtumih.html

[G11] getter / setter
来源：http://dali.jlsjyb.cn/Article/details/gtjsvktdff.html

Py:   @property 与 @x.setter
来源：http://dali.vqdsnc.cn/Article/details/gtkqugacsn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gtvibktmgd.html

JS:   get name() { return this._name; }
来源：http://dali.tian-w.cn/Article/details/gtcmxvnglh.html

TS:   get name(): string { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gtcffqmuwl.html

Java: public String getName() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtphmxvqtl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gtfrcarval.html

Ruby: attr_accessor :name
来源：http://dali.meibo888.top/Article/details/gtniockwbt.html

C#:   public string Name { get; set; }
来源：http://dali.sxryk.cn/Article/details/gtuepxucqy.html

[G12] 对象转字符串
来源：http://dali.yj20258888.top/Article/details/gtesgazchv.html

Py:   def __str__(self): return self.name
来源：http://dali.zhiwuduotai.top/Article/details/gtbbhhymbg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtfdlsfxbf.html

JS:   toString() { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gtvuvdyfxk.html

TS:   toString(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtxgdpmixy.html

Java: @Override public String toString() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtaqhilsmp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gtkcyxgmip.html

Ruby: def to_s; @name; end
来源：http://dali.wangdashe.top/Article/details/gtqdlfgmjz.html

C#:   public override string ToString() => Name;
来源：http://dali.ivvv.top/Article/details/gtplwywwpu.html

[G13] 判断对象类型
来源：http://dali.yvedp.cn/Article/details/gtxxgllqgs.html

Py:   isinstance(u, User)
来源：http://dali.fzhhl.top/Article/details/gtzgmbavlg.html

PHP:  $u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtzhhccokd.html

JS:   u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtisskbrae.html

TS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtxioxymul.html

Java: u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtxoxuzkwx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.9152youxi.cn/Article/details/gtgxolbhbd.html

Ruby: u.is_a?(User)
来源：http://dali.bjfxy.top/Article/details/gtmvpvyqjj.html

C#:   u is User
来源：http://dali.zhixingplan.top/Article/details/gtzlporuis.html

[G14] 数据类 / record
来源：http://dali.yangfankeji.com/Article/details/gthcufgpro.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.feifeiyinyue.top/Article/details/gtxsimkvum.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxbgwwro.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.fengsongda.top/Article/details/gtbdgousww.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gtsbpnniag.html

Java: record User(String name, int age) {}
来源：http://dali.bjfxy.top/Article/details/gtjborlrvq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tianlin.xyz/Article/details/gtbpoiwyht.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhengqikj.top/Article/details/gtbilkbryj.html

C#:   record User(string Name, int Age);
来源：http://dali.xylfe.cn/Article/details/gtzrnthuom.html

[G15] 枚举
来源：http://dali.wangshuangyany.cn/Article/details/gtrjghnhpf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ppjwa.cn/Article/details/gtddmnyahk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinqigufen.top/Article/details/gthlitafbn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cashguo.top/Article/details/gtidckvgzk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gtyoycfxvg.html

Java: enum Color { RED, GREEN }
来源：http://dali.meibo888.top/Article/details/gtqwteiypr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258888.top/Article/details/gtctkaqkrw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yuxming.cn/Article/details/gtwuwgbszc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gtkragctkb.html

[G16] 对象转数组 / 字典
来源：http://dali.smart0.xyz/Article/details/gteywrsyim.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yueranfly.top/Article/details/gtsesazqvj.html

PHP:  get_object_vars($obj);
来源：http://dali.kuanghao11.cn/Article/details/gtapbejcdq.html

JS:   Object.entries(obj)
来源：http://dali.316326.xyz/Article/details/gteekolbct.html

TS:   Object.entries(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtswlctrjb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sweek.top/Article/details/gtefbkjjhl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yuanzhike.top/Article/details/gtsldcxldj.html

Ruby: obj.instance_variables
来源：http://dali.daxiang520.top/Article/details/gtukqsnzbh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhongyouzk.top/Article/details/gtiruowwsf.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtunuwmdei.html

H. 异常与错误处理
来源：http://dali.meibo888.top/Article/details/gttliqwdku.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtmzxfkpxp.html

[H01] try / catch 基础
来源：http://dali.jinghuilouyu.cn/Article/details/gtxbvmedwn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.bjfxy.top/Article/details/gtuofpetim.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xziqi.cn/Article/details/gtompjlpwx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtutbhpevm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gtzvhykvms.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xziqi.cn/Article/details/gtkcbiixoi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hysaishi.cn/Article/details/gtxknbhlkp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yuxming.cn/Article/details/gtpdzunmrt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.daria6918.cn/Article/details/gttqrzyuia.html

[H02] finally / ensure 收尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbdqvvgfm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.kuanghao11.cn/Article/details/gtjafjgjtz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtjlptwhag.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtxoopxmme.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtgdimocog.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpecmbhoo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.fzhhl.top/Article/details/gtamaeswlt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ehwqpu.com/Article/details/gthlrhbqxz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtpafotnsj.html

[H03] 主动抛出异常
来源：http://dali.nwbrower.top/Article/details/gtzafxepwf.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinqigufen.top/Article/details/gtalpjpyjn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gtjqcsmdji.html

JS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gttxpqlgbj.html

TS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtsuakomoy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gtdzqhqumb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shuidangran.top/Article/details/gtcxvqzyuq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hongshengwenyu.top/Article/details/gtwagshoqn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtfiwbksxt.html

[H04] 自定义异常类型
来源：http://dali.yanxiufei.cn/Article/details/gtluryugch.html

Py:   class MyError(Exception): pass
来源：http://dali.haohaochexian.top/Article/details/gtfhmmkkic.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gtdvuflukt.html

JS:   class MyError extends Error {}
来源：http://dali.hnqzz.top/Article/details/gttglycjrw.html

TS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gtkesyyzih.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gtxdfjpnem.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xinyue.icu/Article/details/gtfbvixgvf.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtszjueisf.html

C#:   class MyException : Exception {}
来源：http://dali.cheryme.top/Article/details/gtclllonxt.html

[H05] 捕获特定类型
来源：http://dali.cqqwz.cn/Article/details/gtawbclkpi.html

Py:   except ValueError as e:
来源：http://dali.jiagoushi.top/Article/details/gtemucsijj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuanzhike.top/Article/details/gtaayfkvmy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gtigtgpopx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xuanzx.com/Article/details/gtyyntmtss.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cheryme.top/Article/details/gthjsybuvk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cashguo.top/Article/details/gtgllqtbtl.html

Ruby: rescue ArgumentError => e
来源：http://dali.hfpthk.cn/Article/details/gtuahuxvwd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yonumen.top/Article/details/gthleqrixw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhiwuduotai.top/Article/details/gttvtgxgum.html

Py:   value = d.get("k") or default
来源：http://dali.zycfv.cn/Article/details/gttntmfeeb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnxiangtu.top/Article/details/gtxogwooxv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.havefunace.top/Article/details/gtngcswlzd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gtcajmdpym.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xinyue.icu/Article/details/gtaiznytbe.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhoulong.xyz/Article/details/gthcvtoemd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuetiantiany.cn/Article/details/gtaznutsbw.html

C#:   obj?.A?.B ?? default
来源：http://dali.iojbl.cn/Article/details/gtiwfqhjyb.html

[H07] 断言
来源：http://dali.ppjwa.cn/Article/details/gtwsrikneo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcgozeya.html

PHP:  assert($x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtnagtnmnl.html

JS:   console.assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtqcosxvtr.html

TS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtxeijvsmj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gzhubu.top/Article/details/gtyowsvomv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jlsjyb.cn/Article/details/gtuiwcwhzp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gogol.net.cn/Article/details/gtxfvumkbp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtnckevube.html

[H08] 获取错误信息与堆栈
来源：http://dali.jqgufenzy.top/Article/details/gtkodridyd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xinyue.icu/Article/details/gtexkrdtoc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258.top/Article/details/gtugnorogo.html

JS:   e.message;  e.stack
来源：http://dali.aibaodan.cn/Article/details/gtrudpppgp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258888.top/Article/details/gtxgluotsv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.smart0.xyz/Article/details/gtygndbqbd.html

Go:   err.Error()
来源：http://dali.jinqigfzy.top/Article/details/gtkpxiagis.html

Ruby: e.message;  e.backtrace
来源：http://dali.hammf.cn/Article/details/gtwaxarpoc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj202588.top/Article/details/gthunknerf.html

[H09] 带错误码的异常
来源：http://dali.0kj1m.cn/Article/details/gtjxbtbwia.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yangfankeji.com/Article/details/gtwehkdmeq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.c1oappe.top/Article/details/gttbypeakd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yonumen.top/Article/details/gthltyfgdh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgcychvvh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.andypj.xyz/Article/details/gtgmcxdtje.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhongyouzk.top/Article/details/gtcolnstar.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hysaishi.cn/Article/details/gtkzwrjtpq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sweek.top/Article/details/gtzybiukmo.html

[H10] 资源自动释放
来源：http://dali.havefunace.top/Article/details/gtbputbwua.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hfpthk.cn/Article/details/gtnoolmnpx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj20258888.top/Article/details/gtjkufgpue.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.c1oappe.top/Article/details/gtgzmcswfn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.birdmap.top/Article/details/gtxlthwnqx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj20258.top/Article/details/gtptuyzyod.html

Go:   defer f.Close()
来源：http://dali.fengsongda.top/Article/details/gthuwscgdv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuanzhike.top/Article/details/gtbbjmjbnu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtewnpzsjy.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejkxmqem.html

I. 正则表达式
来源：http://dali.bjfxy.top/Article/details/gtoxewbjrt.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtfvclktqm.html

[I01] 判断是否匹配
来源：http://dali.yuxming.cn/Article/details/gtvqjnrnsc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcpsdapim.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtewirgfog.html

JS:   /\d+/.test(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtaovyxdiw.html

TS:   /\d+/.test(s)
来源：http://dali.zhongyouzk.top/Article/details/gtxudfcxmg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shuidangran.top/Article/details/gtofgyqrow.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sysykeji.top/Article/details/gttnvfitjm.html

Ruby: s.match?(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gtltdmgdhm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgufenzy.top/Article/details/gtlslsklqe.html

[I02] 提取所有匹配
来源：http://dali.xziqi.cn/Article/details/gtwgvadrao.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yuxming.cn/Article/details/gttopfcqej.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinqigufen.top/Article/details/gtuemgoptn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyiktkmii.html

TS:   s.match(/\d+/g)
来源：http://dali.hysaishi.cn/Article/details/gtdgdycrds.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.0kj1m.cn/Article/details/gtbwyfxukr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tian-w.cn/Article/details/gtpaptbgsc.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnebnlpxg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.iojbl.cn/Article/details/gtjagohpsw.html

[I03] 提取捕获分组
来源：http://dali.shzxlz.cn/Article/details/gtxidlejwf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhixingplan.top/Article/details/gtfzqsaqum.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj20258888.top/Article/details/gthndldszi.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.birdmap.top/Article/details/gtiprcbyze.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nwbrower.top/Article/details/gtdqzjarod.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gogol.net.cn/Article/details/gtzqzeshja.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xylfe.cn/Article/details/gtwgldmgde.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zycfv.cn/Article/details/gtnyveycir.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.aizwys.cn/Article/details/gtlaurcken.html

[I04] 正则替换
来源：http://dali.jianghu66.top/Article/details/gtfryphooc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jiagoushi.top/Article/details/gtemyzlhiu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yongpay.top/Article/details/gtebhigeqv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cashguo.top/Article/details/gthwhjxpbw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigufen.top/Article/details/gtudmlkaxh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.snrcjt.cn/Article/details/gtagovuajz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yongpay.top/Article/details/gtuiwcinbr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xylfe.cn/Article/details/gtzkuaquax.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtxwpbjayd.html

[I05] 按正则拆分
来源：http://dali.xuanzx.com/Article/details/gttjtmqdno.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tian-w.cn/Article/details/gtttuefpgf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtbqpkvmuo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gtmndifmhb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gtxmvkowmj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xziqi.cn/Article/details/gtujrvkvrd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.9152youxi.cn/Article/details/gtsfqmrbxg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gtxlmjuinj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tanke756.top/Article/details/gtirfnxrwp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hfpthk.cn/Article/details/gthnxouded.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gtxkfbevpa.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gogol.net.cn/Article/details/gtoqixqluz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gtczaxfkhh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xinyue.icu/Article/details/gttwpqjecs.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gtxnfjvsxo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shangyingyoupin.top/Article/details/gtpeqijzem.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.316326.xyz/Article/details/gtnwnalsyj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gtoypznxyv.html

[I07] 忽略大小写与多行模式
来源：http://dali.9152youxi.cn/Article/details/gtgildpnqp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hysaishi.cn/Article/details/gtbsydfavu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gtwdvrpkkb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yanxiufei.cn/Article/details/gthijptewq.html

TS:   /error/gim
来源：http://dali.shuidangran.top/Article/details/gtnnnshdea.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.quarkkingdee.top/Article/details/gtglahhiqp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nwbrower.top/Article/details/gttxqclexb.html

Ruby: s.scan(/error/i)
来源：http://dali.nwbrower.top/Article/details/gtgazqgdac.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zycfv.cn/Article/details/gtjwnkstrx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tanke756.top/Article/details/gtejwvgxmm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhixingplan.top/Article/details/gtlskmyyca.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hongshengwenyu.top/Article/details/gtddxqdytg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.svipenyu.cn/Article/details/gtgolhurxf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.smart0.xyz/Article/details/gtvvyiwexz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gtxiqgsblc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hywenlv.cn/Article/details/gtcgzeqtfm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqohcllif.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cdnleiting.top/Article/details/gtobmojlzk.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtjkrncqnw.html

J. 日期与时间
来源：http://dali.chenlongwang.top/Article/details/gtmatwqueg.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gthyoceewe.html

[J01] 获取当前时间
来源：http://dali.daxiang520.top/Article/details/gtcwxibten.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yuanzhike.top/Article/details/gtkjttxvxx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gtxomhvwum.html

JS:   new Date();  Date.now()
来源：http://dali.jinqigfzy.top/Article/details/gtqzbeoyqx.html

TS:   new Date();  Date.now()
来源：http://dali.zhongyouzk.top/Article/details/gtzvafcmak.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.andypj.xyz/Article/details/gtblmawofv.html

Go:   time.Now()
来源：http://dali.chenzaomai.com/Article/details/gtyqkktvbd.html

Ruby: Time.now
来源：http://dali.jlsjyb.cn/Article/details/gtswcivwdq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.bjfxy.top/Article/details/gtipqtbesb.html

[J02] 格式化输出
来源：http://dali.nwbrower.top/Article/details/gtdvmajdek.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangshuangyany.cn/Article/details/gtnfoihjah.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xylfe.cn/Article/details/gtuxacgpiu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tian-w.cn/Article/details/gtdodiyoln.html

TS:   d.toISOString()
来源：http://dali.snrcjt.cn/Article/details/gtmxarwbej.html


<!-- 参考信息 -->