代发 wailian999

C#:   public override string Greet() => "admin";
来源：http://dali.tian-w.cn/Article/details/gt2dpvyndxo.html

[G07] 调用父类方法
来源：http://dali.xziqi.cn/Article/details/gt2lecriyoe.html

Py:   super().greet()
来源：http://dali.chenzaomai.com/Article/details/gt2mmyjqtqo.html

PHP:  parent::greet();
来源：http://dali.fengsongda.top/Article/details/gt2hdozhjhv.html

JS:   super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mdydzuvq.html

TS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gt2zkfgpobq.html

Java: super.greet();
来源：http://dali.daxiang520.top/Article/details/gt2hpggpabe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.316326.xyz/Article/details/gt2bxkqjaop.html

Ruby: super
来源：http://dali.snrcjt.cn/Article/details/gt2lmgxkiyq.html

C#:   base.Greet();
来源：http://dali.shuidangran.top/Article/details/gt2axgobyxh.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjlzwhu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.c1oappe.top/Article/details/gt2kpwxbafz.html

PHP:  public static function f() {}
来源：http://dali.cqqwz.cn/Article/details/gt2tkoxxoul.html

JS:   static f() {}
来源：http://dali.nanxuanxn.top/Article/details/gt2obavroro.html

TS:   static f(): void {}
来源：http://dali.svipenyu.cn/Article/details/gt2ykxwltua.html

Java: static void f() {}
来源：http://dali.yj20258.top/Article/details/gt2gdcjebdi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenzaomai.com/Article/details/gt2wkcbcyfj.html

Ruby: def self.f; end
来源：http://dali.zycfv.cn/Article/details/gt2tfdtpkrx.html

C#:   public static void F() {}
来源：http://dali.yueranfly.top/Article/details/gt2rvblucjh.html

[G09] 接口 / 抽象类
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eghcieey.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.c1oappe.top/Article/details/gt2jkspmqew.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sysykeji.top/Article/details/gt2lzcrezel.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhongyouzk.top/Article/details/gt2wrypxriu.html

TS:   interface Shape { area(): number; }
来源：http://dali.bjfxy.top/Article/details/gt2hzhldrlz.html

Java: interface Shape { double area(); }
来源：http://dali.sysykeji.top/Article/details/gt2zwbdsmnc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yvedp.cn/Article/details/gt2zcntujio.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xziqi.cn/Article/details/gt2dvabkils.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj202588.top/Article/details/gt2wrxiojmb.html

[G10] 访问控制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2spzibnhn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nwbrower.top/Article/details/gt2gbtcddrp.html

PHP:  public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gt2swinoglh.html

JS:   #private 字段；其余公开
来源：http://dali.zhongyouzk.top/Article/details/gt2xyjnurqw.html

TS:   public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gt2kxrmcfup.html

Java: public / protected / private / 默认包级
来源：http://dali.feifeiyinyue.top/Article/details/gt2vnkpcwsg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.andypj.xyz/Article/details/gt2pcwxbtna.html

Ruby: public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gt2cjbspofn.html

C#:   public / protected / private / internal
来源：http://dali.gotoacloud.top/Article/details/gt2xnheoain.html

[G11] getter / setter
来源：http://dali.tanke756.top/Article/details/gt2mprqjirg.html

Py:   @property 与 @x.setter
来源：http://dali.yonumen.top/Article/details/gt2awatsqjy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gt2vrhsxyfo.html

JS:   get name() { return this._name; }
来源：http://dali.jyoumei.cn/Article/details/gt2ymtssnvt.html

TS:   get name(): string { return this._name; }
来源：http://dali.pycfn.com/Article/details/gt2byehhmkl.html

Java: public String getName() { return name; }
来源：http://dali.xziqi.cn/Article/details/gt2gzbzilld.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gt2lwgnyuma.html

Ruby: attr_accessor :name
来源：http://dali.vqdsnc.cn/Article/details/gt2vtewoomj.html

C#:   public string Name { get; set; }
来源：http://dali.zhoulong.xyz/Article/details/gt2gzxmioxc.html

[G12] 对象转字符串
来源：http://dali.daxiang520.top/Article/details/gt2nuwgqfye.html

Py:   def __str__(self): return self.name
来源：http://dali.gzhubu.top/Article/details/gt2wmdizllm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2xwxhooqr.html

JS:   toString() { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2awrlbzib.html

TS:   toString(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gt2ukovpywb.html

Java: @Override public String toString() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gt2qljcpalo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gt2wlwexatu.html

Ruby: def to_s; @name; end
来源：http://dali.cheryme.top/Article/details/gt2pevefizc.html

C#:   public override string ToString() => Name;
来源：http://dali.haohaochexian.top/Article/details/gt2xhtyhkmg.html

[G13] 判断对象类型
来源：http://dali.kuanghao11.cn/Article/details/gt2dsacagdg.html

Py:   isinstance(u, User)
来源：http://dali.ybcxt.top/Article/details/gt2gkpksgwx.html

PHP:  $u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gt2kjkepvze.html

JS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gt2mezenqop.html

TS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gt2yqnmkupk.html

Java: u instanceof User
来源：http://dali.yuxming.cn/Article/details/gt2ypcbdlri.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj20258.top/Article/details/gt2ewpsuofq.html

Ruby: u.is_a?(User)
来源：http://dali.gotoacloud.top/Article/details/gt2hkhbzjex.html

C#:   u is User
来源：http://dali.jyoumei.cn/Article/details/gt2dcgevnbi.html

[G14] 数据类 / record
来源：http://dali.cdnleiting.top/Article/details/gt2fxhcjqhp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.smart0.xyz/Article/details/gt2bznmubgl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yonumen.top/Article/details/gt2yrvinzuz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jlsjyb.cn/Article/details/gt2eslbqgvo.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2emzrzcbj.html

Java: record User(String name, int age) {}
来源：http://dali.hysaishi.cn/Article/details/gt2dfqdeqfv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2chduvigh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sobctrym.html

C#:   record User(string Name, int Age);
来源：http://dali.daxiang520.top/Article/details/gt2vsyhcwht.html

[G15] 枚举
来源：http://dali.andypj.xyz/Article/details/gt2fjggfwyn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gotoacloud.top/Article/details/gt2dibelqkb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2sjxghyrx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.birdmap.top/Article/details/gt2vlclqikq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gt2xubwfyzt.html

Java: enum Color { RED, GREEN }
来源：http://dali.gotoacloud.top/Article/details/gt2dfslungk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xylfe.cn/Article/details/gt2ivafscqn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenzaomai.com/Article/details/gt2hcyudzae.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gt2dplvaaql.html

[G16] 对象转数组 / 字典
来源：http://dali.yonumen.top/Article/details/gt2aplivsqm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bqmnsfka.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzhydhz.html

JS:   Object.entries(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zvpkfvqw.html

TS:   Object.entries(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xjvyxsvq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.vqdsnc.cn/Article/details/gt2jzuakgdh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yangfankeji.com/Article/details/gt2glbwxzub.html

Ruby: obj.instance_variables
来源：http://dali.feifeiyinyue.top/Article/details/gt2mqmqrmkw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.pycfn.com/Article/details/gt2cgkaevef.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2sbjqpjak.html

H. 异常与错误处理
来源：http://dali.cucudq.cn/Article/details/gt2lnsdragc.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2ysmfxyev.html

[H01] try / catch 基础
来源：http://dali.daria6918.cn/Article/details/gt2wjyvmmjc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhongyouzk.top/Article/details/gt2ebljpyzm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ivvv.top/Article/details/gt2nekkyuly.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gt2vknvogoj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gt2zbagnqxh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yonumen.top/Article/details/gt2phhhftgt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xylfe.cn/Article/details/gt2bykrivvz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hnxiangtu.top/Article/details/gt2wokjehaa.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hammf.cn/Article/details/gt2yazbqaiw.html

[H02] finally / ensure 收尾
来源：http://dali.yuxming.cn/Article/details/gt2lqwjlpqr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.c1oappe.top/Article/details/gt2lovznhty.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2knjxytwl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gt2psnztsxl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gt2dugcxuhn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2adqtpnzf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nwbrower.top/Article/details/gt2sfqctsza.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dianchejie.cn/Article/details/gt2wttyzwbd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gt2gnfdfydl.html

[H03] 主动抛出异常
来源：http://dali.jqgufenzy.top/Article/details/gt2yqglrivm.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenlongwang.top/Article/details/gt2qaornxvs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2bornroop.html

JS:   throw new Error("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gt2irkidbnh.html

TS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gt2xneqlnyp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2vkvmpham.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.kuanghao11.cn/Article/details/gt2ddipjucm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigfzy.top/Article/details/gt2uyclrqam.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sivwuzsr.html

[H04] 自定义异常类型
来源：http://dali.zhoulong.xyz/Article/details/gt2ftukxyzr.html

Py:   class MyError(Exception): pass
来源：http://dali.gzhubu.top/Article/details/gt2tansftxh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gt2rxwqdgeq.html

JS:   class MyError extends Error {}
来源：http://dali.jiagoushi.top/Article/details/gt2btlzvigl.html

TS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gt2uwpcplnd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gaohongyu789.top/Article/details/gt2kztafjwc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guannengcc.top/Article/details/gt2nhnbssid.html

Ruby: class MyError < StandardError; end
来源：http://dali.0kj1m.cn/Article/details/gt2ywgepdys.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigfzy.top/Article/details/gt2duogcavc.html

[H05] 捕获特定类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dermpnwf.html

Py:   except ValueError as e:
来源：http://dali.yangfankeji.com/Article/details/gt2mnywontf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.aibaodan.cn/Article/details/gt2cjpbjltm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gt2ovvxpmvr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2iwkzkuqk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2vtjuqsga.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cheryme.top/Article/details/gt2oycgtoai.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgufenzy.top/Article/details/gt2kbrszhcd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2dtswqbzx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.redwolf501.top/Article/details/gt2chdecdrt.html

Py:   value = d.get("k") or default
来源：http://dali.dianchejie.cn/Article/details/gt2potuauia.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shangyingyoupin.top/Article/details/gt2vjptlccm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.snrcjt.cn/Article/details/gt2xklzabzk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sweek.top/Article/details/gt2lholaxvx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gotoacloud.top/Article/details/gt2wcjmvrhu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zpzfpjgo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhengqikj.top/Article/details/gt2donamfcv.html

C#:   obj?.A?.B ?? default
来源：http://dali.yonumen.top/Article/details/gt2xhumevrd.html

[H07] 断言
来源：http://dali.dianchejie.cn/Article/details/gt2jtffvbbr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.meibo888.top/Article/details/gt2uwcoohxs.html

PHP:  assert($x > 0);
来源：http://dali.zycfv.cn/Article/details/gt2zyawprfr.html

JS:   console.assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ilfgpunv.html

TS:   console.assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tpirzdgz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.daxiang520.top/Article/details/gt2chierjox.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2glzyjzpn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cucudq.cn/Article/details/gt2ccrfcpdd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gt2pfozbrku.html

[H08] 获取错误信息与堆栈
来源：http://dali.hongshengwenyu.top/Article/details/gt2xesndhox.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.316326.xyz/Article/details/gt2ofyvluhf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.mhx1999.top/Article/details/gt2uzutwrpo.html

JS:   e.message;  e.stack
来源：http://dali.wangdashe.top/Article/details/gt2cplxshin.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gzhubu.top/Article/details/gt2ipklyaxg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmdwzwg.html

Go:   err.Error()
来源：http://dali.nwbrower.top/Article/details/gt2xxrglpdv.html

Ruby: e.message;  e.backtrace
来源：http://dali.ppjwa.cn/Article/details/gt2rdcpduoi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jlsjyb.cn/Article/details/gt2utgwuijt.html

[H09] 带错误码的异常
来源：http://dali.gaohongyu789.top/Article/details/gt2ztckwmjn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jqgufenzy.top/Article/details/gt2euzofymr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.316326.xyz/Article/details/gt2dzlhybtq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.svipenyu.cn/Article/details/gt2avyfxbaa.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cdnleiting.top/Article/details/gt2uxzitvvi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2nrolnvau.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daria6918.cn/Article/details/gt2yqhvlhyo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinqigufen.top/Article/details/gt2njedcsug.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.vqdsnc.cn/Article/details/gt2eopbiphq.html

[H10] 资源自动释放
来源：http://dali.guannengcc.top/Article/details/gt2vnjrlocx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.0kj1m.cn/Article/details/gt2nafrdypo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hongshengwenyu.top/Article/details/gt2yvmuwrxo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhiwuduotai.top/Article/details/gt2yzycazrh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gt2goxxqjiv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nanxinkj.top/Article/details/gt2cfyuulek.html

Go:   defer f.Close()
来源：http://dali.havefunace.top/Article/details/gt2tncafylk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenjidiqi.icu/Article/details/gt2dltixjvh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2mejpddyd.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2xpnbaytg.html

I. 正则表达式
来源：http://dali.guannengcc.top/Article/details/gt2wgvczxhv.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2folvpazy.html

[I01] 判断是否匹配
来源：http://dali.xuetiantiany.cn/Article/details/gt2lzugqsae.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nanxuanxn.top/Article/details/gt2bovwubgn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ybcxt.top/Article/details/gt2ajulemoh.html

JS:   /\d+/.test(s)
来源：http://dali.yonumen.top/Article/details/gt2opmumnog.html

TS:   /\d+/.test(s)
来源：http://dali.fengsongda.top/Article/details/gt2txydbtot.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xuanzx.com/Article/details/gt2xeusrjhq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vfnyuutt.html

Ruby: s.match?(/\d+/)
来源：http://dali.xylfe.cn/Article/details/gt2apkosvum.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hongshengwenyu.top/Article/details/gt2aiyulnwo.html

[I02] 提取所有匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2oertelij.html

Py:   re.findall(r"\d+", s)
来源：http://dali.redwolf501.top/Article/details/gt2erxmcsie.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.fzhhl.top/Article/details/gt2pshkzivo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.dashuyun.cn/Article/details/gt2kugyrads.html

TS:   s.match(/\d+/g)
来源：http://dali.yuanzhike.top/Article/details/gt2bipadvpe.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yuanzhike.top/Article/details/gt2tdhdeeig.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ftogoglg.html

Ruby: s.scan(/\d+/)
来源：http://dali.quarkkingdee.top/Article/details/gt2jqrhnjbr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gt2ecvcfsli.html

[I03] 提取捕获分组
来源：http://dali.yvedp.cn/Article/details/gt2nzbumsme.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cqqwz.cn/Article/details/gt2tprzidis.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fengsongda.top/Article/details/gt2bfyoxcwo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nanxinkj.top/Article/details/gt2ifltoayx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cqqwz.cn/Article/details/gt2ayaesmne.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rddulkos.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinqigufen.top/Article/details/gt2rjdkoekk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhoulong.xyz/Article/details/gt2sdqyqfwt.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shangyingyoupin.top/Article/details/gt2hykfjdqf.html

[I04] 正则替换
来源：http://dali.havefunace.top/Article/details/gt2syinujmf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vgyqngdo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yvedp.cn/Article/details/gt2tmlqxdxy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yangfankeji.com/Article/details/gt2twvitmjx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tywcpvfc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nanxinkj.top/Article/details/gt2ftzwucfz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.316326.xyz/Article/details/gt2wxiwdrlu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gt2yqepusqw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.316326.xyz/Article/details/gt2avqjojoo.html

[I05] 按正则拆分
来源：http://dali.dianchejie.cn/Article/details/gt2bhamjosv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dashuyun.cn/Article/details/gt2oynmoyso.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.daria6918.cn/Article/details/gt2chqwygue.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gt2xwnumrib.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gt2zqvckeue.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sysykeji.top/Article/details/gt2fevyiuhq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.fzhhl.top/Article/details/gt2epyrxwoq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gt2rotmnaux.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yueranfly.top/Article/details/gt2dzaeriry.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhoulong.xyz/Article/details/gt2uuvrmhae.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gt2zjxsyiok.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yongpay.top/Article/details/gt2awzeltix.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangshuangyany.cn/Article/details/gt2pptkwtux.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ngxqgcii.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gt2flmurgju.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xinyue.icu/Article/details/gt2odkoygwl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hywenlv.cn/Article/details/gt2wbmmhgsk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gt2gbxgateh.html

[I07] 忽略大小写与多行模式
来源：http://dali.ehwqpu.com/Article/details/gt2yafxatdb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shzxlz.cn/Article/details/gt2nbxcktlc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhoulong.xyz/Article/details/gt2eapijrqr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jiagoushi.top/Article/details/gt2lojpfxin.html

TS:   /error/gim
来源：http://dali.jinqigfzy.top/Article/details/gt2zlwwbmfv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bcrhaabi.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nanxinkj.top/Article/details/gt2oqlvlhjz.html

Ruby: s.scan(/error/i)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ftnoxviz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sufxvd.cn/Article/details/gt2zhnuywws.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.havefunace.top/Article/details/gt2qwwffitw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cdnleiting.top/Article/details/gt2vrkycwvy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gt2wvbnhuzd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shuidangran.top/Article/details/gt2xgnavaim.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.iojbl.cn/Article/details/gt2hpthpkki.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gotoacloud.top/Article/details/gt2yhebkprn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xylfe.cn/Article/details/gt2oznpauka.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.smart0.xyz/Article/details/gt2vjzhjvch.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sxryk.cn/Article/details/gt2tcxytzxp.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2dgfsbumk.html

J. 日期与时间
来源：http://dali.jyoumei.cn/Article/details/gt2raohsewy.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2iiabtviv.html

[J01] 获取当前时间
来源：http://dali.zhiwuduotai.top/Article/details/gt2qkbaztmh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jianghu66.top/Article/details/gt2ofcofsxt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jiagoushi.top/Article/details/gt2kizqoyac.html

JS:   new Date();  Date.now()
来源：http://dali.daxiang520.top/Article/details/gt2hhfrcrsd.html

TS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gt2pvbsdysz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hywenlv.cn/Article/details/gt2lcpxvfap.html

Go:   time.Now()
来源：http://dali.hnqzz.top/Article/details/gt2xsnfifyw.html

Ruby: Time.now
来源：http://dali.sysykeji.top/Article/details/gt2hcpcthgj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sysykeji.top/Article/details/gt2onfbfris.html

[J02] 格式化输出
来源：http://dali.gotoacloud.top/Article/details/gt2pahlrqpw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zdqjudy.top/Article/details/gt2qlecrsln.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sufxvd.cn/Article/details/gt2aeddwpgh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tanke756.top/Article/details/gt2dccvfdrj.html

TS:   d.toISOString()
来源：http://dali.hywenlv.cn/Article/details/gt2gngaeiip.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.meibo888.top/Article/details/gt2otyyuico.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xinyue.icu/Article/details/gt2wvlnrota.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gt2byglweeo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.bjfxy.top/Article/details/gt2lxghdcyp.html

[J03] 字符串解析为日期
来源：http://dali.sweek.top/Article/details/gt2hxsjbgmh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jyoumei.cn/Article/details/gt2xvztebze.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ivvv.top/Article/details/gt2xkzirwqv.html

JS:   new Date("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2uxulyaem.html

TS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gt2hjquaueo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gt2gucxxqpp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gt2axeowsny.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sweek.top/Article/details/gt2tlpksalu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuanzx.com/Article/details/gt2hilpsokl.html

[J04] 时间戳与日期互转
来源：http://dali.tanke756.top/Article/details/gt2olosusgr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.andypj.xyz/Article/details/gt2aoyjuuyp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jiagoushi.top/Article/details/gt2epksfupc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.pycfn.com/Article/details/gt2nzytdftd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cqqwz.cn/Article/details/gt2icgrnpyu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.9152youxi.cn/Article/details/gt2cydrzaxz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.mhx1999.top/Article/details/gt2cgvclycn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.c1oappe.top/Article/details/gt2kudsgmdv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.svipenyu.cn/Article/details/gt2drwbkfwx.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgfzy.top/Article/details/gt2gcqbcjdq.html

Py:   now + timedelta(days=7)
来源：http://dali.ehwqpu.com/Article/details/gt2symwqncp.html


<!-- 参考信息 -->