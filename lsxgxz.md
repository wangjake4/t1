代发 wailian999

Java: class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2ezawuynf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yanxiufei.cn/Article/details/gt2cjpzlcgd.html

Ruby: class Admin < User; end
来源：http://dali.nanxinkj.top/Article/details/gt2nwykitls.html

C#:   class Admin : User {}
来源：http://dali.9152youxi.cn/Article/details/gt2ehlyblyv.html

[G06] 重写方法
来源：http://dali.0kj1m.cn/Article/details/gt2gaelutzb.html

Py:   def greet(self): return "admin"
来源：http://dali.yvedp.cn/Article/details/gt2chfqbczk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gt2fkcfazal.html

JS:   greet() { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cxvfsfic.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gt2rxojxlro.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gt2skmvxetd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.redwolf501.top/Article/details/gt2eiblwtik.html

Ruby: def greet; "admin"; end
来源：http://dali.smart0.xyz/Article/details/gt2hhmumrss.html

C#:   public override string Greet() => "admin";
来源：http://dali.pycfn.com/Article/details/gt2cubrgopa.html

[G07] 调用父类方法
来源：http://dali.shangyingyoupin.top/Article/details/gt2zjhioeco.html

Py:   super().greet()
来源：http://dali.fengsongda.top/Article/details/gt2hicajiog.html

PHP:  parent::greet();
来源：http://dali.wangdashe.top/Article/details/gt2aebmiswd.html

JS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gt2ofqcaeie.html

TS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gt2ospiffdc.html

Java: super.greet();
来源：http://dali.fengsongda.top/Article/details/gt2frvwvrwf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yangfankeji.com/Article/details/gt2zxrlsgdq.html

Ruby: super
来源：http://dali.fzhhl.top/Article/details/gt2ptbuhlbl.html

C#:   base.Greet();
来源：http://dali.cucudq.cn/Article/details/gt2krramvcz.html

[G08] 静态方法与属性
来源：http://dali.zhixingplan.top/Article/details/gt2ijtizcmz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.fzhhl.top/Article/details/gt2rmgrgvav.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oxynurao.html

JS:   static f() {}
来源：http://dali.yuanzhike.top/Article/details/gt2gubexogo.html

TS:   static f(): void {}
来源：http://dali.zhengqikj.top/Article/details/gt2bjjtgjze.html

Java: static void f() {}
来源：http://dali.ybcxt.top/Article/details/gt2jylzgoln.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sxryk.cn/Article/details/gt2dlgytkrw.html

Ruby: def self.f; end
来源：http://dali.yvedp.cn/Article/details/gt2hutfkpoa.html

C#:   public static void F() {}
来源：http://dali.hnqzz.top/Article/details/gt2horfswuv.html

[G09] 接口 / 抽象类
来源：http://dali.havefunace.top/Article/details/gt2sndlqggw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhongyouzk.top/Article/details/gt2rirubjga.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ydzc1.top/Article/details/gt2blnypuku.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hfpthk.cn/Article/details/gt2gyqxvugo.html

TS:   interface Shape { area(): number; }
来源：http://dali.guowangkeji.top/Article/details/gt2winkuruz.html

Java: interface Shape { double area(); }
来源：http://dali.zdqjudy.top/Article/details/gt2zdnejumn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenzaomai.com/Article/details/gt2pzkrvkuu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinqigufen.top/Article/details/gt2pydasfch.html

C#:   interface IShape { double Area(); }
来源：http://dali.andypj.xyz/Article/details/gt2bvdfelid.html

[G10] 访问控制
来源：http://dali.havefunace.top/Article/details/gt2mdewfyhx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daria6918.cn/Article/details/gt2jnkunesp.html

PHP:  public / protected / private
来源：http://dali.pycfn.com/Article/details/gt2wkgxjhwa.html

JS:   #private 字段；其余公开
来源：http://dali.zhoulong.xyz/Article/details/gt2chwgcmkl.html

TS:   public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gt2yxwkvhzu.html

Java: public / protected / private / 默认包级
来源：http://dali.sxryk.cn/Article/details/gt2wrtqloey.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qpbqivrl.html

Ruby: public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gt2uimjvlsq.html

C#:   public / protected / private / internal
来源：http://dali.jinqigufen.top/Article/details/gt2rcvwwnnf.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgccyjj.html

Py:   @property 与 @x.setter
来源：http://dali.zhixingplan.top/Article/details/gt2cocgmhuj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gt2loamogdl.html

JS:   get name() { return this._name; }
来源：http://dali.hammf.cn/Article/details/gt2phivnfuc.html

TS:   get name(): string { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gt2offuusta.html

Java: public String getName() { return name; }
来源：http://dali.zycfv.cn/Article/details/gt2blmclezh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gt2xfbedvxg.html

Ruby: attr_accessor :name
来源：http://dali.aizwys.cn/Article/details/gt2hqcfhbbv.html

C#:   public string Name { get; set; }
来源：http://dali.jinqigufen.top/Article/details/gt2yqzapbli.html

[G12] 对象转字符串
来源：http://dali.yj202588.top/Article/details/gt2cwjasxme.html

Py:   def __str__(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gt2ksopomsf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gt2xebzvxug.html

JS:   toString() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gt2htmuqqaq.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2aicgfurm.html

Java: @Override public String toString() { return name; }
来源：http://dali.c1oappe.top/Article/details/gt2yguuikcb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gt2zecfaorc.html

Ruby: def to_s; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sfupeikt.html

C#:   public override string ToString() => Name;
来源：http://dali.guannengcc.top/Article/details/gt2hemynulk.html

[G13] 判断对象类型
来源：http://dali.316326.xyz/Article/details/gt2fulliyrv.html

Py:   isinstance(u, User)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ydvjjgrj.html

PHP:  $u instanceof User
来源：http://dali.birdmap.top/Article/details/gt2lhvwnkms.html

JS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gt2mzbecmjb.html

TS:   u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gt2adyvvxfr.html

Java: u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gt2ocmnueeo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dianchejie.cn/Article/details/gt2hvedsxka.html

Ruby: u.is_a?(User)
来源：http://dali.hfpthk.cn/Article/details/gt2cchbglkn.html

C#:   u is User
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gqipzjuc.html

[G14] 数据类 / record
来源：http://dali.sufxvd.cn/Article/details/gt2memotkah.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxinkj.top/Article/details/gt2fwquecdh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wtklktle.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuetiantiany.cn/Article/details/gt2jgumlsxx.html

TS:   type User = { name: string; age: number };
来源：http://dali.xinyue.icu/Article/details/gt2cmwmyrqa.html

Java: record User(String name, int age) {}
来源：http://dali.dashuyun.cn/Article/details/gt2rbnjvlst.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vvbyrnjn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenzaomai.com/Article/details/gt2lcbnagjo.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258.top/Article/details/gt2pqzcmoro.html

[G15] 枚举
来源：http://dali.xuanzx.com/Article/details/gt2dourrdvt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cucudq.cn/Article/details/gt2mogswpfs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.bjfxy.top/Article/details/gt2aaoxbjbn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yxwosira.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fzhhl.top/Article/details/gt2kalplkfm.html

Java: enum Color { RED, GREEN }
来源：http://dali.feifeiyinyue.top/Article/details/gt2bzeqxtjn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shangyingyoupin.top/Article/details/gt2anrxhpvu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jlsjyb.cn/Article/details/gt2rkvnazfg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gt2kxgscwtf.html

[G16] 对象转数组 / 字典
来源：http://dali.xuetiantiany.cn/Article/details/gt2wvzycret.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xinyue.icu/Article/details/gt2inddatbf.html

PHP:  get_object_vars($obj);
来源：http://dali.smart0.xyz/Article/details/gt2sskcmkuw.html

JS:   Object.entries(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2nzzssfwq.html

TS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2dukqezps.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shuidangran.top/Article/details/gt2zhwczmwy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xihmrovf.html

Ruby: obj.instance_variables
来源：http://dali.jqgufenzy.top/Article/details/gt2sinyaewp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.birdmap.top/Article/details/gt2qkhukdrc.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xlwgzuqt.html

H. 异常与错误处理
来源：http://dali.jinqigfzy.top/Article/details/gt2pwpjgxuv.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2njgasubz.html

[H01] try / catch 基础
来源：http://dali.mhx1999.top/Article/details/gt2pwhvelys.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.vqdsnc.cn/Article/details/gt2yrmklkjt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gzhubu.top/Article/details/gt2sxdacdui.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gt2whtftpbx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gt2nhsdqaik.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.snrcjt.cn/Article/details/gt2uauqkrpf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangdashe.top/Article/details/gt2ygbrbogo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jqgfzy.top/Article/details/gt2gimuypzf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hywufxyq.html

[H02] finally / ensure 收尾
来源：http://dali.pycfn.com/Article/details/gt2ekpwmwpa.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.iojbl.cn/Article/details/gt2rnvtgwwp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gt2huuupjzj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gt2svqtrnnx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2tztczdjt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ytymamiz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nwbrower.top/Article/details/gt2secorqrt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daxiang520.top/Article/details/gt2vitbarhe.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vjafxyfg.html

[H03] 主动抛出异常
来源：http://dali.cashguo.top/Article/details/gt2atxgqeif.html

Py:   raise ValueError("错误信息")
来源：http://dali.xziqi.cn/Article/details/gt2kdweevia.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gt2nawojtjp.html

JS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gt2xkurkasf.html

TS:   throw new Error("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gt2gyxwpnfs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gt2vacpwzgn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj20258888.top/Article/details/gt2zwamzvus.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cqqwz.cn/Article/details/gt2hqwkayzt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gt2yflpitdp.html

[H04] 自定义异常类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2pymirsyq.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258888.top/Article/details/gt2kxhyngyg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zycfv.cn/Article/details/gt2hlmjfwcx.html

JS:   class MyError extends Error {}
来源：http://dali.tian-w.cn/Article/details/gt2bkzwvdwx.html

TS:   class MyError extends Error {}
来源：http://dali.zdqjudy.top/Article/details/gt2zttgcnan.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhixingplan.top/Article/details/gt2smejlsqb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kchxnneo.html

Ruby: class MyError < StandardError; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2enbbbufs.html

C#:   class MyException : Exception {}
来源：http://dali.zdqjudy.top/Article/details/gt2vffldkoj.html

[H05] 捕获特定类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2frasqwcv.html

Py:   except ValueError as e:
来源：http://dali.haohaochexian.top/Article/details/gt2lttltfot.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.9152youxi.cn/Article/details/gt2osjvkfyl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hfpthk.cn/Article/details/gt2qsmwylxf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2opvtuedu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hnqzz.top/Article/details/gt2othjetgf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tian-w.cn/Article/details/gt2mojphkjs.html

Ruby: rescue ArgumentError => e
来源：http://dali.gotoacloud.top/Article/details/gt2plaulbtc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sxryk.cn/Article/details/gt2xoulfubs.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gaohongyu789.top/Article/details/gt2kaktnash.html

Py:   value = d.get("k") or default
来源：http://dali.xuanzx.com/Article/details/gt2mhvkrcbm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jlsjyb.cn/Article/details/gt2uqgxfbmf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangdashe.top/Article/details/gt2llnowkba.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gt2eyyfxbqq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.snrcjt.cn/Article/details/gt2vhbvirye.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zdqjudy.top/Article/details/gt2vizqfnad.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guowangkeji.top/Article/details/gt2doxqvppy.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnxiangtu.top/Article/details/gt2hvzdzxja.html

[H07] 断言
来源：http://dali.cdnleiting.top/Article/details/gt2ojlofyze.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ydzc1.top/Article/details/gt2ynoqjyah.html

PHP:  assert($x > 0);
来源：http://dali.316326.xyz/Article/details/gt2oyihtfma.html

JS:   console.assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ljttbbre.html

TS:   console.assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2jnjnkffl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ybcxt.top/Article/details/gt2eoioxtow.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2drmthdzg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj20258.top/Article/details/gt2hszzctga.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gt2tazydzhm.html

[H08] 获取错误信息与堆栈
来源：http://dali.fzhhl.top/Article/details/gt2fvtrpazd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yueranfly.top/Article/details/gt2mjzcexol.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sxryk.cn/Article/details/gt2ctnbrkdr.html

JS:   e.message;  e.stack
来源：http://dali.meibo888.top/Article/details/gt2xyijjqtj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sweek.top/Article/details/gt2ppkgexcb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.bjfxy.top/Article/details/gt2wljiuvgv.html

Go:   err.Error()
来源：http://dali.hnxiangtu.top/Article/details/gt2xvvwatkb.html

Ruby: e.message;  e.backtrace
来源：http://dali.hongshengwenyu.top/Article/details/gt2yuofplul.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jqgfzy.top/Article/details/gt2xlvvrnnk.html

[H09] 带错误码的异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bvwtxaxh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangdashe.top/Article/details/gt2iokamspc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhiwuduotai.top/Article/details/gt2gprghwwq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.dashuyun.cn/Article/details/gt2hrnkbtkh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yuanzhike.top/Article/details/gt2bxtghhco.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wpwepuyl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.meibo888.top/Article/details/gt2vqelupob.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qdoqtesq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cqqwz.cn/Article/details/gt2neyqdoiv.html

[H10] 资源自动释放
来源：http://dali.sweek.top/Article/details/gt2rzaenqmh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhixingplan.top/Article/details/gt2hytqkndw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ivvv.top/Article/details/gt2moopxfkk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.vqdsnc.cn/Article/details/gt2rooetape.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tianlin.xyz/Article/details/gt2eittvuth.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.havefunace.top/Article/details/gt2kvwwddbl.html

Go:   defer f.Close()
来源：http://dali.tianlin.xyz/Article/details/gt2gfckfvsu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zdqjudy.top/Article/details/gt2nrlmrotv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2somubdlu.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2lurobdsf.html

I. 正则表达式
来源：http://dali.yvedp.cn/Article/details/gt2kgnzrzfv.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2khdloewu.html

[I01] 判断是否匹配
来源：http://dali.shangyingyoupin.top/Article/details/gt2moailcef.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shuidangran.top/Article/details/gt2rxsjxeyg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sysykeji.top/Article/details/gt2jqzwkipe.html

JS:   /\d+/.test(s)
来源：http://dali.cheryme.top/Article/details/gt2grutpphe.html

TS:   /\d+/.test(s)
来源：http://dali.yvedp.cn/Article/details/gt2ypfffjto.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.redwolf501.top/Article/details/gt2blmfpeyv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gogol.net.cn/Article/details/gt2oxsmcejp.html

Ruby: s.match?(/\d+/)
来源：http://dali.vqdsnc.cn/Article/details/gt2cfnwbikf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xuanzx.com/Article/details/gt2emwoiyos.html

[I02] 提取所有匹配
来源：http://dali.cashguo.top/Article/details/gt2sehaxoxh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gt2thekxfbf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hammf.cn/Article/details/gt2lrvwcspp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenlongwang.top/Article/details/gt2vzekzyde.html

TS:   s.match(/\d+/g)
来源：http://dali.shuidangran.top/Article/details/gt2ccnaamcn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gzhubu.top/Article/details/gt2wyfajzqi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.havefunace.top/Article/details/gt2umkmonvy.html

Ruby: s.scan(/\d+/)
来源：http://dali.sufxvd.cn/Article/details/gt2uoifqwzd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2xjrofoll.html

[I03] 提取捕获分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kpgtzokj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ywzaedef.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jqgfzy.top/Article/details/gt2qbiowwkp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.daria6918.cn/Article/details/gt2amsxfqux.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.daxiang520.top/Article/details/gt2znmqlkuz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jlsjyb.cn/Article/details/gt2vsufnwqy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ivvv.top/Article/details/gt2votwotxy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jlsjyb.cn/Article/details/gt2gwqizdbd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pycfn.com/Article/details/gt2duygsngw.html

[I04] 正则替换
来源：http://dali.tianlin.xyz/Article/details/gt2xtfngmqe.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbfqvmw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxinkj.top/Article/details/gt2rskgqwmy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258888.top/Article/details/gt2kkspnxys.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xinyue.icu/Article/details/gt2jyxtuhvo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jyoumei.cn/Article/details/gt2mqkdhyna.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.smart0.xyz/Article/details/gt2kmmvskzu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ybcxt.top/Article/details/gt2dgrqyebx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yueranfly.top/Article/details/gt2wyvmolln.html

[I05] 按正则拆分
来源：http://dali.9152youxi.cn/Article/details/gt2qmvglffw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.quarkkingdee.top/Article/details/gt2tuvmzglm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2uxgumycn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eztpscbx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gt2nxvhuugb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wokqscdw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vjtdzmsu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gt2bpwgszqo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ppjwa.cn/Article/details/gt2acxicgjx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.c1oappe.top/Article/details/gt2wnoettar.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gt2sruvytqg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.redwolf501.top/Article/details/gt2khyvkfdg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yueranfly.top/Article/details/gt2pxhxzgpy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hysaishi.cn/Article/details/gt2biblyaeu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.tanke756.top/Article/details/gt2wtpmfmfo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ivvv.top/Article/details/gt2ukppajko.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xwdqhoga.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.smart0.xyz/Article/details/gt2ywvkznok.html

[I07] 忽略大小写与多行模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tyxyaclc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nanxuanxn.top/Article/details/gt2vtdqkeuq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.fengsongda.top/Article/details/gt2afpncqcc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yvedp.cn/Article/details/gt2xsufhspx.html

TS:   /error/gim
来源：http://dali.ivvv.top/Article/details/gt2cxvbybpw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenjidiqi.icu/Article/details/gt2waaiaaxt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.bjfxy.top/Article/details/gt2hctwxdjp.html

Ruby: s.scan(/error/i)
来源：http://dali.yangfankeji.com/Article/details/gt2tjnkmdif.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xylfe.cn/Article/details/gt2gdymspdj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gzhubu.top/Article/details/gt2tjbwchud.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhoulong.xyz/Article/details/gt2vhlfaxkk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xziqi.cn/Article/details/gt2akqdnvig.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lzlybcxu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xinyue.icu/Article/details/gt2hhnrxmrt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gzhubu.top/Article/details/gt2kmzsyxxn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cdnleiting.top/Article/details/gt2jjqbfary.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jianghu66.top/Article/details/gt2ytsxobqf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zdqjudy.top/Article/details/gt2xteghlqi.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2nhnwttnf.html

J. 日期与时间
来源：http://dali.jiagoushi.top/Article/details/gt2iozqyncs.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2ogxwptlq.html

[J01] 获取当前时间
来源：http://dali.pycfn.com/Article/details/gt2tihvjuch.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yanxiufei.cn/Article/details/gt2oltcmbwn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shzxlz.cn/Article/details/gt2tjshmcgb.html

JS:   new Date();  Date.now()
来源：http://dali.sxryk.cn/Article/details/gt2nevhuowi.html

TS:   new Date();  Date.now()
来源：http://dali.gzhubu.top/Article/details/gt2tbrnsizs.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jiagoushi.top/Article/details/gt2eipwmeiw.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gt2utuxjtes.html

Ruby: Time.now
来源：http://dali.gotoacloud.top/Article/details/gt2ufxmbcds.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.iojbl.cn/Article/details/gt2vijgenwr.html

[J02] 格式化输出
来源：http://dali.yueranfly.top/Article/details/gt2kpbhzzxx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gt2wubcvowt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.dashuyun.cn/Article/details/gt2teymwrmk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.svipenyu.cn/Article/details/gt2xbfilyhx.html

TS:   d.toISOString()
来源：http://dali.zycfv.cn/Article/details/gt2kglfaltu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hongshengwenyu.top/Article/details/gt2itaqyqzn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tian-w.cn/Article/details/gt2erqxlbfn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenzaomai.com/Article/details/gt2aklmxtkq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yvedp.cn/Article/details/gt2zkwieycu.html

[J03] 字符串解析为日期
来源：http://dali.dashuyun.cn/Article/details/gt2qlvktuqp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.dashuyun.cn/Article/details/gt2fjhukhna.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hongshengwenyu.top/Article/details/gt2myzaroty.html

JS:   new Date("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gt2nkqdejgu.html

TS:   new Date("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gt2vkrofgmh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gt2ehunhcji.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.havefunace.top/Article/details/gt2hyaexrmk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gt2sgoobotf.html


<!-- 参考信息 -->