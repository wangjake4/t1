代发 wailian999

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gtbsvxgabv.html

JS:   greet() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtrbrkgued.html

TS:   greet(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gthyghszin.html

Java: String greet() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtiwimucot.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gtjwhkvwnu.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtttuqovvf.html

C#:   public string Greet() => Name;
来源：http://dali.chenzaomai.com/Article/details/gttuwjqwog.html

[G05] 继承
来源：http://dali.sxryk.cn/Article/details/gtumieipfe.html

Py:   class Admin(User): pass
来源：http://dali.gotoacloud.top/Article/details/gticedfscv.html

PHP:  class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtfvzzdiya.html

JS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gthhamjmzg.html

TS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtwyjdrwma.html

Java: class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtooigvqcu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigfzy.top/Article/details/gtkezljjqr.html

Ruby: class Admin < User; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtosxaweqt.html

C#:   class Admin : User {}
来源：http://dali.cqqwz.cn/Article/details/gtdeybmetp.html

[G06] 重写方法
来源：http://dali.aibaodan.cn/Article/details/gtwpehaxkc.html

Py:   def greet(self): return "admin"
来源：http://dali.9152youxi.cn/Article/details/gtvmaypqgb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtqoksjldm.html

JS:   greet() { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtgwjzbrpb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gttpbkkrtk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtvigghycq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.redwolf501.top/Article/details/gthcmwrdkq.html

Ruby: def greet; "admin"; end
来源：http://dali.kuanghao11.cn/Article/details/gtmaazfyeo.html

C#:   public override string Greet() => "admin";
来源：http://dali.ybcxt.top/Article/details/gtyraqfqch.html

[G07] 调用父类方法
来源：http://dali.yj20258888.top/Article/details/gtntuzmpik.html

Py:   super().greet()
来源：http://dali.dashuyun.cn/Article/details/gtpsntykxg.html

PHP:  parent::greet();
来源：http://dali.aizwys.cn/Article/details/gtarggrqso.html

JS:   super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxuuqpuk.html

TS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gtivgcfcux.html

Java: super.greet();
来源：http://dali.ybcxt.top/Article/details/gtfdlotrsb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenjidiqi.icu/Article/details/gtoaiignhg.html

Ruby: super
来源：http://dali.ybcxt.top/Article/details/gtghyfnxak.html

C#:   base.Greet();
来源：http://dali.shuidangran.top/Article/details/gtaqjazwyk.html

[G08] 静态方法与属性
来源：http://dali.dashuyun.cn/Article/details/gtlsixxzaw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj20258.top/Article/details/gtdwuueoig.html

PHP:  public static function f() {}
来源：http://dali.zhixingplan.top/Article/details/gtqdxvdypu.html

JS:   static f() {}
来源：http://dali.gzhubu.top/Article/details/gtjpsbbwnw.html

TS:   static f(): void {}
来源：http://dali.hysaishi.cn/Article/details/gtpwtdkfyz.html

Java: static void f() {}
来源：http://dali.sxryk.cn/Article/details/gtdxosqcxe.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.aizwys.cn/Article/details/gttwomgvew.html

Ruby: def self.f; end
来源：http://dali.xziqi.cn/Article/details/gttalxeqpx.html

C#:   public static void F() {}
来源：http://dali.jqgfzy.top/Article/details/gtzxvncynk.html

[G09] 接口 / 抽象类
来源：http://dali.andypj.xyz/Article/details/gtxspwzqob.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhengqikj.top/Article/details/gtkejrwkov.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zdqjudy.top/Article/details/gtcxxsvvvl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.316326.xyz/Article/details/gtmrgvflhs.html

TS:   interface Shape { area(): number; }
来源：http://dali.kuanghao11.cn/Article/details/gtbmvifcrk.html

Java: interface Shape { double area(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtwfwodywp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ybcxt.top/Article/details/gtadyiamwu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenjidiqi.icu/Article/details/gtxjquswao.html

C#:   interface IShape { double Area(); }
来源：http://dali.gogol.net.cn/Article/details/gtcjdwpkys.html

[G10] 访问控制
来源：http://dali.yonumen.top/Article/details/gthfgrnzhu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sysykeji.top/Article/details/gtqgwdozbx.html

PHP:  public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtxfucxwvk.html

JS:   #private 字段；其余公开
来源：http://dali.pengpengdd.cyou/Article/details/gtagwpjjma.html

TS:   public / protected / private
来源：http://dali.iojbl.cn/Article/details/gtwxykjhix.html

Java: public / protected / private / 默认包级
来源：http://dali.yuxming.cn/Article/details/gtvgnnlaup.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hysaishi.cn/Article/details/gtnyqyzsuk.html

Ruby: public / protected / private
来源：http://dali.zycfv.cn/Article/details/gthkzipoes.html

C#:   public / protected / private / internal
来源：http://dali.ydzc1.top/Article/details/gtgidcavrs.html

[G11] getter / setter
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmfkekcs.html

Py:   @property 与 @x.setter
来源：http://dali.xuanzx.com/Article/details/gthdtiepds.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gtbawahulq.html

JS:   get name() { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gtawugxivg.html

TS:   get name(): string { return this._name; }
来源：http://dali.sxryk.cn/Article/details/gtovwphbom.html

Java: public String getName() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtbcmngadx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gtoiikljgc.html

Ruby: attr_accessor :name
来源：http://dali.xuanzx.com/Article/details/gtmiplgkui.html

C#:   public string Name { get; set; }
来源：http://dali.smart0.xyz/Article/details/gtxtvmvptj.html

[G12] 对象转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtzitkglam.html

Py:   def __str__(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gtnbbyftpc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gtkbrsywnz.html

JS:   toString() { return this.name; }
来源：http://dali.sweek.top/Article/details/gtbxggmgtm.html

TS:   toString(): string { return this.name; }
来源：http://dali.pycfn.com/Article/details/gttuqirqwo.html

Java: @Override public String toString() { return name; }
来源：http://dali.tanke756.top/Article/details/gtcoworwuc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gtqyyfwwca.html

Ruby: def to_s; @name; end
来源：http://dali.sufxvd.cn/Article/details/gtllhmmljn.html

C#:   public override string ToString() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtabcripfs.html

[G13] 判断对象类型
来源：http://dali.cdnleiting.top/Article/details/gtvyxwkfty.html

Py:   isinstance(u, User)
来源：http://dali.316326.xyz/Article/details/gtlfdtmikq.html

PHP:  $u instanceof User
来源：http://dali.ybcxt.top/Article/details/gtrtzhnpym.html

JS:   u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gtznwvuyan.html

TS:   u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtokklxlpc.html

Java: u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gtjfrynuck.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cashguo.top/Article/details/gtfhxkyiqq.html

Ruby: u.is_a?(User)
来源：http://dali.yj202588.top/Article/details/gtfqptahwt.html

C#:   u is User
来源：http://dali.yvedp.cn/Article/details/gtmkuvaejl.html

[G14] 数据类 / record
来源：http://dali.mhx1999.top/Article/details/gtgxtopzuj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tian-w.cn/Article/details/gtevjklfnk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cheryme.top/Article/details/gtttxitzrj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgufenzy.top/Article/details/gtbgjohksz.html

TS:   type User = { name: string; age: number };
来源：http://dali.gzhubu.top/Article/details/gtwhmfqjap.html

Java: record User(String name, int age) {}
来源：http://dali.yanxiufei.cn/Article/details/gtjsbrailz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.bjfxy.top/Article/details/gtijcctzce.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhixingplan.top/Article/details/gtbpvrqgcp.html

C#:   record User(string Name, int Age);
来源：http://dali.shuidangran.top/Article/details/gtfovepcja.html

[G15] 枚举
来源：http://dali.xuanzx.com/Article/details/gtnxblgaox.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj20258888.top/Article/details/gtkrkunsbz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jyoumei.cn/Article/details/gtwokeijxv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cqqwz.cn/Article/details/gtepwmkayo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dianchejie.cn/Article/details/gtgtkxtjku.html

Java: enum Color { RED, GREEN }
来源：http://dali.feifeiyinyue.top/Article/details/gtdsrlawjk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gaohongyu789.top/Article/details/gtcmkrqopv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shzxlz.cn/Article/details/gtmefycqji.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtfizymyuv.html

[G16] 对象转数组 / 字典
来源：http://dali.ydzc1.top/Article/details/gtcwsocdgq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.dianchejie.cn/Article/details/gtrejwetdy.html

PHP:  get_object_vars($obj);
来源：http://dali.hysaishi.cn/Article/details/gtrluqvpob.html

JS:   Object.entries(obj)
来源：http://dali.xziqi.cn/Article/details/gtzjuvvryn.html

TS:   Object.entries(obj)
来源：http://dali.jqgfzy.top/Article/details/gtpukjrbkc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shanyushiyangtech.top/Article/details/gtucqbryce.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.iojbl.cn/Article/details/gtvsvbvkjn.html

Ruby: obj.instance_variables
来源：http://dali.jinghuilouyu.cn/Article/details/gtiebkxoql.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gtjvmzeavw.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtygiiqgai.html

H. 异常与错误处理
来源：http://dali.sweek.top/Article/details/gttaarbcur.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtebxdswqj.html

[H01] try / catch 基础
来源：http://dali.yvedp.cn/Article/details/gtrypqekho.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jianghu66.top/Article/details/gtirfgqvpe.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tian-w.cn/Article/details/gtbrzrksqa.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gthopedaba.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gtaqwdvbbr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenjidiqi.icu/Article/details/gtiqrbmzub.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sysykeji.top/Article/details/gtywmamoyl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.pycfn.com/Article/details/gtfoomejwk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ydzc1.top/Article/details/gtzgidtvhl.html

[H02] finally / ensure 收尾
来源：http://dali.nanxinkj.top/Article/details/gtlhtxvshh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hongshengwenyu.top/Article/details/gtwkwkdzag.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtpsijfjqs.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtgexzaqng.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtfmokpfuw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtinltaglv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nwbrower.top/Article/details/gticdzcyuy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhongyouzk.top/Article/details/gtbtyqwbvd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtuphglqkw.html

[H03] 主动抛出异常
来源：http://dali.0kj1m.cn/Article/details/gtmhvwnwmt.html

Py:   raise ValueError("错误信息")
来源：http://dali.pycfn.com/Article/details/gttvgfpptu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqfxzlrtk.html

JS:   throw new Error("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtwjuyygpv.html

TS:   throw new Error("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtoediuccw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtyemygiwh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhixingplan.top/Article/details/gtodiziyjv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuxming.cn/Article/details/gtwprhtynb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtltfdrvvb.html

[H04] 自定义异常类型
来源：http://dali.meibo888.top/Article/details/gtjowoddls.html

Py:   class MyError(Exception): pass
来源：http://dali.birdmap.top/Article/details/gttxcxndkb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gzhubu.top/Article/details/gtwdacbpyi.html

JS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gtqlpwhkcd.html

TS:   class MyError extends Error {}
来源：http://dali.hywenlv.cn/Article/details/gtdmudugzu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gtrojtdxcx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pycfn.com/Article/details/gtpphlsgmh.html

Ruby: class MyError < StandardError; end
来源：http://dali.tian-w.cn/Article/details/gtomtwpolg.html

C#:   class MyException : Exception {}
来源：http://dali.jqgfzy.top/Article/details/gtvvcuaagb.html

[H05] 捕获特定类型
来源：http://dali.sweek.top/Article/details/gtydgwytze.html

Py:   except ValueError as e:
来源：http://dali.316326.xyz/Article/details/gtamjflaqo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xylfe.cn/Article/details/gtvuemiuou.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.havefunace.top/Article/details/gtwqxbynpr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gtnhdrozfa.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.svipenyu.cn/Article/details/gtcpkhagie.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.daxiang520.top/Article/details/gtylxcnlic.html

Ruby: rescue ArgumentError => e
来源：http://dali.jyoumei.cn/Article/details/gtezmqmrti.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nwbrower.top/Article/details/gtfnnjcjkb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvaznxbfr.html

Py:   value = d.get("k") or default
来源：http://dali.gotoacloud.top/Article/details/gtdvjhfmne.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gtfxojxrng.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhongyouzk.top/Article/details/gthvmmipta.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.pycfn.com/Article/details/gtzppughdf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yanxiufei.cn/Article/details/gtcjlefruk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cdnleiting.top/Article/details/gtrdeqjhxw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangdashe.top/Article/details/gtsizhfxos.html

C#:   obj?.A?.B ?? default
来源：http://dali.0kj1m.cn/Article/details/gtaxolysdg.html

[H07] 断言
来源：http://dali.zhiwuduotai.top/Article/details/gtdbspaxou.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xylfe.cn/Article/details/gttuokcltd.html

PHP:  assert($x > 0);
来源：http://dali.jianghu66.top/Article/details/gtmmjokhed.html

JS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gtrzgirohu.html

TS:   console.assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gtshsnzyhg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258.top/Article/details/gtaeslhacv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.c1oappe.top/Article/details/gtnqmshuzh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gzhubu.top/Article/details/gtdcrpmmlk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtriguqdbb.html

[H08] 获取错误信息与堆栈
来源：http://dali.tanke756.top/Article/details/gtmraytpwl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jqgfzy.top/Article/details/gtpunvbogg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gogol.net.cn/Article/details/gtavsxerpy.html

JS:   e.message;  e.stack
来源：http://dali.jqgufenzy.top/Article/details/gtsafewbbv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hammf.cn/Article/details/gturzenazz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhiwuduotai.top/Article/details/gtxbtlwezs.html

Go:   err.Error()
来源：http://dali.redwolf501.top/Article/details/gtibgqvoas.html

Ruby: e.message;  e.backtrace
来源：http://dali.xinyue.icu/Article/details/gtxthjviof.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmbxxzjqa.html

[H09] 带错误码的异常
来源：http://dali.wangshuangyany.cn/Article/details/gtfejbxvwd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.0kj1m.cn/Article/details/gtmdfhzznh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.0kj1m.cn/Article/details/gtzktivfjj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aizwys.cn/Article/details/gtpdpgfgub.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gaohongyu789.top/Article/details/gtbmovlczg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.snrcjt.cn/Article/details/gttziyrbcm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.vqdsnc.cn/Article/details/gtjpuubfnv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhengqikj.top/Article/details/gttwxiosrg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hnqzz.top/Article/details/gtyjrrqlqe.html

[H10] 资源自动释放
来源：http://dali.yongpay.top/Article/details/gtzilnaiwa.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jiagoushi.top/Article/details/gtwyzdnlho.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.chenlongwang.top/Article/details/gtwmiqmaao.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gtcpuuumqk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhoulong.xyz/Article/details/gtaooigyyd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hfpthk.cn/Article/details/gtmjfmsfhy.html

Go:   defer f.Close()
来源：http://dali.jianghu66.top/Article/details/gtngpuegjg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yangfankeji.com/Article/details/gtcespjuxs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtwvndwggt.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtpgceuzgo.html

I. 正则表达式
来源：http://dali.xuanzx.com/Article/details/gtkxkfxrxf.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtdzduxyda.html

[I01] 判断是否匹配
来源：http://dali.shuidangran.top/Article/details/gtuczgthlq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtkiwturoi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.daria6918.cn/Article/details/gtkrzubbnq.html

JS:   /\d+/.test(s)
来源：http://dali.xylfe.cn/Article/details/gtwhzivigv.html

TS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gtjgkbvmki.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shzxlz.cn/Article/details/gthuvzdnsh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jianghu66.top/Article/details/gtbufmhbyw.html

Ruby: s.match?(/\d+/)
来源：http://dali.cheryme.top/Article/details/gtjzfxjxrp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dianchejie.cn/Article/details/gttolwfzzc.html

[I02] 提取所有匹配
来源：http://dali.dianchejie.cn/Article/details/gtxcxqqznn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzspvbmea.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hammf.cn/Article/details/gttlyvsbbn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinghuilouyu.cn/Article/details/gtuwpocato.html

TS:   s.match(/\d+/g)
来源：http://dali.yonumen.top/Article/details/gtmaajeria.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jqgufenzy.top/Article/details/gtnsyyozyz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nwbrower.top/Article/details/gtmjndfvoi.html

Ruby: s.scan(/\d+/)
来源：http://dali.pycfn.com/Article/details/gtcqvgzeng.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.guannengcc.top/Article/details/gtylmjnayt.html

[I03] 提取捕获分组
来源：http://dali.gaohongyu789.top/Article/details/gtslxyfisz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.fengsongda.top/Article/details/gtlvrlrfhd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gzhubu.top/Article/details/gtdtfjljli.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.birdmap.top/Article/details/gtusihrjel.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tian-w.cn/Article/details/gtovnblfur.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenlongwang.top/Article/details/gtrmjrngmd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.dianchejie.cn/Article/details/gtrkgqrwaa.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpcmwqlth.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hnqzz.top/Article/details/gtwlmgiwup.html

[I04] 正则替换
来源：http://dali.wangdashe.top/Article/details/gtvyagguun.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yvedp.cn/Article/details/gtqjbsvrdn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cqqwz.cn/Article/details/gtymbqsqof.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenlongwang.top/Article/details/gtqruvweab.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yuxming.cn/Article/details/gtjhjaubwx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gthingelfa.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jyoumei.cn/Article/details/gtqoqgbqia.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nanxuanxn.top/Article/details/gtbtqjikxx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangdashe.top/Article/details/gtqphtddrl.html

[I05] 按正则拆分
来源：http://dali.ybcxt.top/Article/details/gtwzuezhax.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jqgfzy.top/Article/details/gtnwhrvqgt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.snrcjt.cn/Article/details/gtihohcpbf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gtljgyzjnw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtgmynqvsp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.andypj.xyz/Article/details/gthnnyyksx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhixingplan.top/Article/details/gtzzikanyg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gthpbpowth.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ppjwa.cn/Article/details/gtukzjbyrw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sysykeji.top/Article/details/gtgtlssegy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gtzwthbgqh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.vqdsnc.cn/Article/details/gtlcqcblob.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zdqjudy.top/Article/details/gtmhnakukn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jiagoushi.top/Article/details/gtpcypatve.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gtvlygfjqq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.c1oappe.top/Article/details/gtfiaolhpi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.daria6918.cn/Article/details/gtphatjefx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gtkuvbouro.html

[I07] 忽略大小写与多行模式
来源：http://dali.hammf.cn/Article/details/gtkwxxmtfv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.kuanghao11.cn/Article/details/gtyylfffzk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xuanzx.com/Article/details/gtrzglsrag.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tianlin.xyz/Article/details/gtxoeybmuw.html

TS:   /error/gim
来源：http://dali.yongpay.top/Article/details/gtomylojhu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aibaodan.cn/Article/details/gtvjhfkwke.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.wangshuangyany.cn/Article/details/gtxfjpksyf.html

Ruby: s.scan(/error/i)
来源：http://dali.xinyue.icu/Article/details/gtqklgtzrl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigfzy.top/Article/details/gtkkmurpzg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.guannengcc.top/Article/details/gtgkafzkny.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shzxlz.cn/Article/details/gtomzpczzj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sysykeji.top/Article/details/gtjfctwgqm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gtxvzsdcoi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daxiang520.top/Article/details/gtpopoeeat.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.guowangkeji.top/Article/details/gtempagfnh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xuetiantiany.cn/Article/details/gtymxhnzet.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ydzc1.top/Article/details/gtzohzrnjr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.kuanghao11.cn/Article/details/gtvmtetfqs.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtpdmfziwj.html

J. 日期与时间
来源：http://dali.xuanzx.com/Article/details/gtmvkyriwq.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtcfcsxetb.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gtrjkoabzo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cqqwz.cn/Article/details/gtdzxmznur.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gtdvvyampg.html

JS:   new Date();  Date.now()
来源：http://dali.316326.xyz/Article/details/gtgkrlapkr.html

TS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gtyjvimajb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cheryme.top/Article/details/gtjxzvzupq.html

Go:   time.Now()
来源：http://dali.tian-w.cn/Article/details/gtxnrgwobw.html

Ruby: Time.now
来源：http://dali.jlsjyb.cn/Article/details/gtlnhcrqvm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhoulong.xyz/Article/details/gtapxinhkp.html

[J02] 格式化输出
来源：http://dali.chenzaomai.com/Article/details/gtdtxnfrel.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gtzwictnyy.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.dashuyun.cn/Article/details/gtjxhoqdfr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hnxiangtu.top/Article/details/gtgdhmdfet.html

TS:   d.toISOString()
来源：http://dali.ppjwa.cn/Article/details/gtlvdyzhmt.html


<!-- 参考信息 -->