代发 wailian999

[G06] 重写方法
来源：http://dali.guowangkeji.top/Article/details/gtywkmamxu.html

Py:   def greet(self): return "admin"
来源：http://dali.shangyingyoupin.top/Article/details/gtpexouizy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gticrmmqvw.html

JS:   greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtzkrhvzpg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbutpkhnb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtcfseodum.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hnqzz.top/Article/details/gtsneggemh.html

Ruby: def greet; "admin"; end
来源：http://dali.gogol.net.cn/Article/details/gtxsxbmrfm.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhixingplan.top/Article/details/gtzlpithub.html

[G07] 调用父类方法
来源：http://dali.fzhhl.top/Article/details/gtpiprjaxv.html

Py:   super().greet()
来源：http://dali.tian-w.cn/Article/details/gtzhfqvtld.html

PHP:  parent::greet();
来源：http://dali.cashguo.top/Article/details/gtxjluwztg.html

JS:   super.greet();
来源：http://dali.yangfankeji.com/Article/details/gtnpuzzxcw.html

TS:   super.greet();
来源：http://dali.ppjwa.cn/Article/details/gtvdxbejli.html

Java: super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gtgiiixgyz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sweek.top/Article/details/gtkisvpkqe.html

Ruby: super
来源：http://dali.pycfn.com/Article/details/gtcrofemut.html

C#:   base.Greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdxjpjotb.html

[G08] 静态方法与属性
来源：http://dali.shzxlz.cn/Article/details/gtflprjupd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhengqikj.top/Article/details/gtfoqimtid.html

PHP:  public static function f() {}
来源：http://dali.fengsongda.top/Article/details/gtqateuvcg.html

JS:   static f() {}
来源：http://dali.zhoulong.xyz/Article/details/gtaczprtwz.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gtrbjhfhdh.html

Java: static void f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtrzfnsmdi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sufxvd.cn/Article/details/gtdkgvrhbw.html

Ruby: def self.f; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnfjmmhyf.html

C#:   public static void F() {}
来源：http://dali.shuidangran.top/Article/details/gtoubicttb.html

[G09] 接口 / 抽象类
来源：http://dali.gogol.net.cn/Article/details/gtamckkkjx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yanxiufei.cn/Article/details/gtsaxnpayd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.quarkkingdee.top/Article/details/gtdjjnmonv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yanxiufei.cn/Article/details/gtawejtaay.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigufen.top/Article/details/gtxbpnjpgz.html

Java: interface Shape { double area(); }
来源：http://dali.shzxlz.cn/Article/details/gtdmfhuvbm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xylfe.cn/Article/details/gtledtvals.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guannengcc.top/Article/details/gtsjpjgahs.html

C#:   interface IShape { double Area(); }
来源：http://dali.smart0.xyz/Article/details/gtpvpvedtz.html

[G10] 访问控制
来源：http://dali.316326.xyz/Article/details/gtodekwqly.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdhzzqfpu.html

PHP:  public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gtjrztpvxz.html

JS:   #private 字段；其余公开
来源：http://dali.shanyushiyangtech.top/Article/details/gtntfpprbi.html

TS:   public / protected / private
来源：http://dali.nwbrower.top/Article/details/gtenypsgsq.html

Java: public / protected / private / 默认包级
来源：http://dali.cucudq.cn/Article/details/gteglkndhy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangkeji.top/Article/details/gttvhbkkpn.html

Ruby: public / protected / private
来源：http://dali.andypj.xyz/Article/details/gtmqjblyud.html

C#:   public / protected / private / internal
来源：http://dali.yonumen.top/Article/details/gteewtitfk.html

[G11] getter / setter
来源：http://dali.dianchejie.cn/Article/details/gtxvxnsaxt.html

Py:   @property 与 @x.setter
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnxrzckmg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gtvitzqhrq.html

JS:   get name() { return this._name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpfbsrmbv.html

TS:   get name(): string { return this._name; }
来源：http://dali.aizwys.cn/Article/details/gtcxpbpqud.html

Java: public String getName() { return name; }
来源：http://dali.ivvv.top/Article/details/gtqsseuxlz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gtdhijickz.html

Ruby: attr_accessor :name
来源：http://dali.nanxinkj.top/Article/details/gtxzpghkhm.html

C#:   public string Name { get; set; }
来源：http://dali.shangyingyoupin.top/Article/details/gtgbeeyhqe.html

[G12] 对象转字符串
来源：http://dali.birdmap.top/Article/details/gtppasumcb.html

Py:   def __str__(self): return self.name
来源：http://dali.tanke756.top/Article/details/gtixqjlkhr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gtuuzbvukz.html

JS:   toString() { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtkelueenv.html

TS:   toString(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtzkwatetv.html

Java: @Override public String toString() { return name; }
来源：http://dali.fzhhl.top/Article/details/gthehmeexg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gtrtzzbfhd.html

Ruby: def to_s; @name; end
来源：http://dali.xylfe.cn/Article/details/gtmhqwdnfd.html

C#:   public override string ToString() => Name;
来源：http://dali.sweek.top/Article/details/gtxrsnlwli.html

[G13] 判断对象类型
来源：http://dali.kuanghao11.cn/Article/details/gtbwdoybeq.html

Py:   isinstance(u, User)
来源：http://dali.havefunace.top/Article/details/gtuieyrvvu.html

PHP:  $u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtayftsygd.html

JS:   u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtuhjlpwoq.html

TS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtufiliikj.html

Java: u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtmqwfgwop.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aibaodan.cn/Article/details/gtuoxawvtw.html

Ruby: u.is_a?(User)
来源：http://dali.chenzaomai.com/Article/details/gtxdsntxbx.html

C#:   u is User
来源：http://dali.hnxiangtu.top/Article/details/gtkfycyxkc.html

[G14] 数据类 / record
来源：http://dali.shzxlz.cn/Article/details/gtwwmdtpzc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.pycfn.com/Article/details/gtswimmxue.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yongpay.top/Article/details/gtifpdnqxf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.svipenyu.cn/Article/details/gtaohtutha.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhengqikj.top/Article/details/gtcabkpsqq.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjlqlqqxa.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yangfankeji.com/Article/details/gthjspfafo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinqigfzy.top/Article/details/gtocquqahu.html

C#:   record User(string Name, int Age);
来源：http://dali.chenjidiqi.icu/Article/details/gtiaidoscg.html

[G15] 枚举
来源：http://dali.xuanzx.com/Article/details/gtibsmfwjv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shuidangran.top/Article/details/gtovwstuyf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sweek.top/Article/details/gtzbyufvdy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nwbrower.top/Article/details/gtdphluzmr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gtfybqoduz.html

Java: enum Color { RED, GREEN }
来源：http://dali.shangyingyoupin.top/Article/details/gtrryatnzh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jqgfzy.top/Article/details/gtnpaxoeeq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ydzc1.top/Article/details/gtvnhxvvht.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gtxrixjegk.html

[G16] 对象转数组 / 字典
来源：http://dali.andypj.xyz/Article/details/gtfafyquvi.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.vqdsnc.cn/Article/details/gtaebcpxww.html

PHP:  get_object_vars($obj);
来源：http://dali.tianlin.xyz/Article/details/gtmfcirrhc.html

JS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gtwdzlyzqf.html

TS:   Object.entries(obj)
来源：http://dali.0kj1m.cn/Article/details/gtqntqaohe.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.iojbl.cn/Article/details/gttowrjlyd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gzhubu.top/Article/details/gttylhhoxn.html

Ruby: obj.instance_variables
来源：http://dali.havefunace.top/Article/details/gtjxhfvuon.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gtusrgwfrr.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtckvcsfxz.html

H. 异常与错误处理
来源：http://dali.shangyingyoupin.top/Article/details/gtkwlggjcy.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtilacnois.html

[H01] try / catch 基础
来源：http://dali.gogol.net.cn/Article/details/gtsislucir.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.svipenyu.cn/Article/details/gtjaoiayjh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgfzy.top/Article/details/gtwixhqqep.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gtsmkytjno.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gtodnzmqap.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daria6918.cn/Article/details/gtgojvgkkz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xziqi.cn/Article/details/gtucavkwuw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnmhqucfa.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sweek.top/Article/details/gtjeveahel.html

[H02] finally / ensure 收尾
来源：http://dali.chenlongwang.top/Article/details/gtdhrqrgzd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xziqi.cn/Article/details/gtlxitnnjf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtkrkyibky.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gttqlxjkuf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtzwrcvhpt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzlxqbznc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.andypj.xyz/Article/details/gtfxlmyncb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrpfkosyq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtmpkyrmuh.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqpzvaze.html

Py:   raise ValueError("错误信息")
来源：http://dali.redwolf501.top/Article/details/gtdnxbbbsa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtyddxmvox.html

JS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtlqzmgvaa.html

TS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtexytbnjk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gtbdespjos.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daxiang520.top/Article/details/gtkjcwjvun.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.c1oappe.top/Article/details/gtofltuilp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdpykgszo.html

[H04] 自定义异常类型
来源：http://dali.hnxiangtu.top/Article/details/gtvektvkco.html

Py:   class MyError(Exception): pass
来源：http://dali.shuidangran.top/Article/details/gtoduynxoz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gaohongyu789.top/Article/details/gtreljbqkc.html

JS:   class MyError extends Error {}
来源：http://dali.yanxiufei.cn/Article/details/gtcntsggzu.html

TS:   class MyError extends Error {}
来源：http://dali.jiagoushi.top/Article/details/gtsshgqjzw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.9152youxi.cn/Article/details/gtblbatcqr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nwbrower.top/Article/details/gtuhciurif.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenzaomai.com/Article/details/gtcdusjumy.html

C#:   class MyException : Exception {}
来源：http://dali.gzhubu.top/Article/details/gtkwjinkvy.html

[H05] 捕获特定类型
来源：http://dali.hnxiangtu.top/Article/details/gtoyediyla.html

Py:   except ValueError as e:
来源：http://dali.dianchejie.cn/Article/details/gtuowuspev.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yvedp.cn/Article/details/gtqidfgbkm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gttyogjryb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.wangdashe.top/Article/details/gtukhjtibl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yueranfly.top/Article/details/gtsjbjhzfs.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cdnleiting.top/Article/details/gtbljawdxw.html

Ruby: rescue ArgumentError => e
来源：http://dali.pycfn.com/Article/details/gtnvgmvtuc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.bjfxy.top/Article/details/gtzqglytmr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dianchejie.cn/Article/details/gtolzhcnan.html

Py:   value = d.get("k") or default
来源：http://dali.jiagoushi.top/Article/details/gtsvkmzgmc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ydzc1.top/Article/details/gtnekwjtrz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gtpiysfmha.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gtbtylfxfo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.smart0.xyz/Article/details/gtxnpuxpmj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cqqwz.cn/Article/details/gtyhsydmkr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.havefunace.top/Article/details/gtiolmxnzd.html

C#:   obj?.A?.B ?? default
来源：http://dali.sufxvd.cn/Article/details/gtfiqaftbm.html

[H07] 断言
来源：http://dali.jianghu66.top/Article/details/gteykaxbhn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenlongwang.top/Article/details/gtaoputmea.html

PHP:  assert($x > 0);
来源：http://dali.snrcjt.cn/Article/details/gtsdukbxio.html

JS:   console.assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtdukknkzm.html

TS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtyxkfnykp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cashguo.top/Article/details/gttmhwlvxv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jyoumei.cn/Article/details/gtogumpaun.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.birdmap.top/Article/details/gtsfuuuwdd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtidsvwzjs.html

[H08] 获取错误信息与堆栈
来源：http://dali.zdqjudy.top/Article/details/gtvfxlrqbu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gzhubu.top/Article/details/gtvdbjymdp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shanyushiyangtech.top/Article/details/gtcufirkgb.html

JS:   e.message;  e.stack
来源：http://dali.ivvv.top/Article/details/gtdtmnwqeg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jlsjyb.cn/Article/details/gtjcfatafw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gzhubu.top/Article/details/gtzrtfbppg.html

Go:   err.Error()
来源：http://dali.quarkkingdee.top/Article/details/gtjcunkxwu.html

Ruby: e.message;  e.backtrace
来源：http://dali.xylfe.cn/Article/details/gtrhprwkpn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jiagoushi.top/Article/details/gtuhtgtaqt.html

[H09] 带错误码的异常
来源：http://dali.ehwqpu.com/Article/details/gtgxzdaijn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.birdmap.top/Article/details/gtgoxxvhpz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangshuangyany.cn/Article/details/gtpyjvoiuh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.0kj1m.cn/Article/details/gtrulcahjz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.redwolf501.top/Article/details/gtrhgcmfsz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuxming.cn/Article/details/gtjpmkebkw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinqigfzy.top/Article/details/gtirlpqehm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cqqwz.cn/Article/details/gtpkzwubzx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenlongwang.top/Article/details/gtlpoolgkc.html

[H10] 资源自动释放
来源：http://dali.hongshengwenyu.top/Article/details/gtmdrvuuvb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tian-w.cn/Article/details/gtymlqlked.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.guowangkeji.top/Article/details/gtdqsybldq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.smart0.xyz/Article/details/gtyfntttgu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrwutipam.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.pycfn.com/Article/details/gtfagcplma.html

Go:   defer f.Close()
来源：http://dali.hywenlv.cn/Article/details/gthunpauyu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yvedp.cn/Article/details/gtvohxctoe.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hammf.cn/Article/details/gtsljinpsj.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtgowekgqf.html

I. 正则表达式
来源：http://dali.gzhubu.top/Article/details/gtjmmhpyrm.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtrkovvuut.html

[I01] 判断是否匹配
来源：http://dali.jinqigfzy.top/Article/details/gtoikmynte.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gtwsauxrpq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj202588.top/Article/details/gtchworcfw.html

JS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gtgwvqrcsa.html

TS:   /\d+/.test(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmabbaap.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.svipenyu.cn/Article/details/gtedlhvrza.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yanxiufei.cn/Article/details/gtfmpovlqt.html

Ruby: s.match?(/\d+/)
来源：http://dali.xziqi.cn/Article/details/gtilnensps.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangshuangyany.cn/Article/details/gtfhciqaih.html

[I02] 提取所有匹配
来源：http://dali.ehwqpu.com/Article/details/gtcmwvpbvr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guannengcc.top/Article/details/gtdolwjcyd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtulgaxahi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinqigufen.top/Article/details/gtrvxtqcha.html

TS:   s.match(/\d+/g)
来源：http://dali.smart0.xyz/Article/details/gtyetrtsmz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yongpay.top/Article/details/gtcwedsizy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ppjwa.cn/Article/details/gtntdfrlnc.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gtrjqapxqi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.redwolf501.top/Article/details/gtbdaxzqym.html

[I03] 提取捕获分组
来源：http://dali.sxryk.cn/Article/details/gtbhqwnshb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.aizwys.cn/Article/details/gtrsgdjwan.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xylfe.cn/Article/details/gtobjubsbo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenlongwang.top/Article/details/gtsoamzsrw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtqwezoqvr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shzxlz.cn/Article/details/gtxoowesfg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tianlin.xyz/Article/details/gtkdtysmgq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.meibo888.top/Article/details/gtsmztabrn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gotoacloud.top/Article/details/gtdookyvff.html

[I04] 正则替换
来源：http://dali.zhongyouzk.top/Article/details/gtktfiegbf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ppjwa.cn/Article/details/gtshfnmmxb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gzhubu.top/Article/details/gttxbtpidl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gtfblpgaef.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ydzc1.top/Article/details/gthondqpid.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gtrppkksbn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtcariygvo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.9152youxi.cn/Article/details/gtguxfneso.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gtmvwyvfbt.html

[I05] 按正则拆分
来源：http://dali.ydzc1.top/Article/details/gtowpxznwb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ehwqpu.com/Article/details/gtyggkqosj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zdqjudy.top/Article/details/gttrrmxzoq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gtukwzzelu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtdxtwqkrj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtasrnxvra.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yueranfly.top/Article/details/gtxlhwbpcr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gtazgzckns.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yuanzhike.top/Article/details/gtwwsafwmk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuxming.cn/Article/details/gtrbxwahau.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gtlqukfwov.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ybcxt.top/Article/details/gtkbxcparc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jyoumei.cn/Article/details/gtqwjuwtgf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gtzmpvdefd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gtszujiqwg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.bjfxy.top/Article/details/gtdvjzgcaz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuxming.cn/Article/details/gtaccxyrrx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtunpftpzs.html

[I07] 忽略大小写与多行模式
来源：http://dali.gaohongyu789.top/Article/details/gtbqyfpzge.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ppjwa.cn/Article/details/gtlyuawxuv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xuanzx.com/Article/details/gtpccllsih.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ydzc1.top/Article/details/gtvzeciqps.html

TS:   /error/gim
来源：http://dali.xylfe.cn/Article/details/gtsanyrepe.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenzaomai.com/Article/details/gtwpymkkoh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yvedp.cn/Article/details/gtfnewfvie.html

Ruby: s.scan(/error/i)
来源：http://dali.tian-w.cn/Article/details/gtdusvhvav.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hywenlv.cn/Article/details/gtriszjwlj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ivvv.top/Article/details/gtyhqgxaex.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhengqikj.top/Article/details/gtruqofqut.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxuanxn.top/Article/details/gtquhglfua.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ybcxt.top/Article/details/gtdfpagfmy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daxiang520.top/Article/details/gtaywuimas.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.chenjidiqi.icu/Article/details/gtbyoaexfi.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenzaomai.com/Article/details/gttezcvfap.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sysykeji.top/Article/details/gthrlqlwnt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj20258.top/Article/details/gtqlzjtfpy.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtwgnvdkvo.html

J. 日期与时间
来源：http://dali.yanxiufei.cn/Article/details/gtlwdwtnec.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtbwsdosey.html

[J01] 获取当前时间
来源：http://dali.fzhhl.top/Article/details/gtpjnlfeus.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sufxvd.cn/Article/details/gtvtaspikr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gtnobbhueg.html

JS:   new Date();  Date.now()
来源：http://dali.tian-w.cn/Article/details/gtxkxbmvln.html

TS:   new Date();  Date.now()
来源：http://dali.hnqzz.top/Article/details/gthhwyshmp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hongshengwenyu.top/Article/details/gtawycpzbs.html

Go:   time.Now()
来源：http://dali.sufxvd.cn/Article/details/gtzakylgcv.html

Ruby: Time.now
来源：http://dali.pengpengdd.cyou/Article/details/gtpkfsnnjl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yuxming.cn/Article/details/gtweoentfz.html

[J02] 格式化输出
来源：http://dali.ehwqpu.com/Article/details/gtlmmfokkj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ppjwa.cn/Article/details/gtuchuzlgb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.c1oappe.top/Article/details/gtuqqtgyuq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gaohongyu789.top/Article/details/gtmwiczylz.html

TS:   d.toISOString()
来源：http://dali.cashguo.top/Article/details/gterpkwuhh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jqgufenzy.top/Article/details/gtsxtvlcrj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xuetiantiany.cn/Article/details/gtkwlidtqq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.haohaochexian.top/Article/details/gtixnhewoh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgalxdqda.html

[J03] 字符串解析为日期
来源：http://dali.jinghuilouyu.cn/Article/details/gtjnbsppsz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhengqikj.top/Article/details/gtpuptutrh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tianlin.xyz/Article/details/gtbzcfclxb.html

JS:   new Date("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtvgpnxmxd.html

TS:   new Date("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtmoivuxrk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtfpniggde.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtdqdjgkgw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtygkjxuwp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hnxiangtu.top/Article/details/gteisdkkyn.html

[J04] 时间戳与日期互转
来源：http://dali.ivvv.top/Article/details/gtjrkqslpc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhijiandao.cn/Article/details/gtloetmesg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.meibo888.top/Article/details/gtyklltrgd.html


<!-- 参考信息 -->