代发 wailian999

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtbkkzseat.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtfixwtmiv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shuidangran.top/Article/details/gtmgkjqnxr.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gtxpigzdmn.html

C#:   public override string Greet() => "admin";
来源：http://dali.yueranfly.top/Article/details/gtnaxcfivw.html

[G07] 调用父类方法
来源：http://dali.yuanzhike.top/Article/details/gtjjaahrmk.html

Py:   super().greet()
来源：http://dali.yj202588.top/Article/details/gtcpgnaovs.html

PHP:  parent::greet();
来源：http://dali.daxiang520.top/Article/details/gtoguuahyl.html

JS:   super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtnhnrkddb.html

TS:   super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gtnwmaopia.html

Java: super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtblaoggex.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yueranfly.top/Article/details/gtgkqvwqhe.html

Ruby: super
来源：http://dali.vqdsnc.cn/Article/details/gtapbkefxe.html

C#:   base.Greet();
来源：http://dali.cashguo.top/Article/details/gthwapofyl.html

[G08] 静态方法与属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjbyqfufl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.quarkkingdee.top/Article/details/gtmcduppyq.html

PHP:  public static function f() {}
来源：http://dali.zhongyouzk.top/Article/details/gtuquldzmj.html

JS:   static f() {}
来源：http://dali.hammf.cn/Article/details/gtzjchyxbp.html

TS:   static f(): void {}
来源：http://dali.yongpay.top/Article/details/gturfvqevq.html

Java: static void f() {}
来源：http://dali.pycfn.com/Article/details/gtdamjpked.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdkohckeq.html

Ruby: def self.f; end
来源：http://dali.iojbl.cn/Article/details/gtbdztjgrf.html

C#:   public static void F() {}
来源：http://dali.jiagoushi.top/Article/details/gtfhmstfao.html

[G09] 接口 / 抽象类
来源：http://dali.gogol.net.cn/Article/details/gtwzflmxke.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gaohongyu789.top/Article/details/gtgqholpcg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guannengcc.top/Article/details/gtqzpbzden.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sufxvd.cn/Article/details/gtledkhydr.html

TS:   interface Shape { area(): number; }
来源：http://dali.jianghu66.top/Article/details/gtnspjrhfi.html

Java: interface Shape { double area(); }
来源：http://dali.yj202588.top/Article/details/gtqyovpynm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gotoacloud.top/Article/details/gtkynwpbpu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ybcxt.top/Article/details/gtigsqmzct.html

C#:   interface IShape { double Area(); }
来源：http://dali.gaohongyu789.top/Article/details/gtzagokxmr.html

[G10] 访问控制
来源：http://dali.cdnleiting.top/Article/details/gtvjfapaik.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.havefunace.top/Article/details/gtharjimbd.html

PHP:  public / protected / private
来源：http://dali.hammf.cn/Article/details/gthugenkyd.html

JS:   #private 字段；其余公开
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfnhhongn.html

TS:   public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmvarock.html

Java: public / protected / private / 默认包级
来源：http://dali.ivvv.top/Article/details/gtngokvsjd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ivvv.top/Article/details/gtlwlwbqyd.html

Ruby: public / protected / private
来源：http://dali.smart0.xyz/Article/details/gtzogttrll.html

C#:   public / protected / private / internal
来源：http://dali.shuidangran.top/Article/details/gtntckieyr.html

[G11] getter / setter
来源：http://dali.pycfn.com/Article/details/gttvdmodrj.html

Py:   @property 与 @x.setter
来源：http://dali.cashguo.top/Article/details/gtqwrhgomi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gthstyqaoh.html

JS:   get name() { return this._name; }
来源：http://dali.yj202588.top/Article/details/gtjseukeuo.html

TS:   get name(): string { return this._name; }
来源：http://dali.xziqi.cn/Article/details/gtpjagmmpf.html

Java: public String getName() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtvxwmqgeh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtbrudbnua.html

Ruby: attr_accessor :name
来源：http://dali.hongshengwenyu.top/Article/details/gtfrvipqvo.html

C#:   public string Name { get; set; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgscftlih.html

[G12] 对象转字符串
来源：http://dali.shuidangran.top/Article/details/gtffcxkrka.html

Py:   def __str__(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gteewqozyr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gtcpmrthcj.html

JS:   toString() { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gticqyvpds.html

TS:   toString(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtinbgmgmm.html

Java: @Override public String toString() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtdhquavtd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gtnyblowei.html

Ruby: def to_s; @name; end
来源：http://dali.ivvv.top/Article/details/gtfblipbjz.html

C#:   public override string ToString() => Name;
来源：http://dali.daria6918.cn/Article/details/gthvbexjhx.html

[G13] 判断对象类型
来源：http://dali.tian-w.cn/Article/details/gtnpqddojw.html

Py:   isinstance(u, User)
来源：http://dali.ivvv.top/Article/details/gtaateaoqe.html

PHP:  $u instanceof User
来源：http://dali.yj20258.top/Article/details/gtwsikoiir.html

JS:   u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gthatmouwx.html

TS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtmfuwlpdo.html

Java: u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtifxilhpn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.haohaochexian.top/Article/details/gthmgegwuz.html

Ruby: u.is_a?(User)
来源：http://dali.fengsongda.top/Article/details/gtvaiaejpc.html

C#:   u is User
来源：http://dali.sxryk.cn/Article/details/gtwvxkqbfx.html

[G14] 数据类 / record
来源：http://dali.meibo888.top/Article/details/gtefemtkck.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yongpay.top/Article/details/gteqijobtb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zdqjudy.top/Article/details/gtklgaaoxr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinqigufen.top/Article/details/gtkwecgnoq.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhongyouzk.top/Article/details/gtyonempgv.html

Java: record User(String name, int age) {}
来源：http://dali.yongpay.top/Article/details/gtsnslovsa.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hammf.cn/Article/details/gtjclrsbgi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jyoumei.cn/Article/details/gtahpmusfn.html

C#:   record User(string Name, int Age);
来源：http://dali.kuanghao11.cn/Article/details/gtsktmgjln.html

[G15] 枚举
来源：http://dali.pengpengdd.cyou/Article/details/gtzbdojfbo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.meibo888.top/Article/details/gtquddvhyt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sxryk.cn/Article/details/gtovsjdwww.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenjidiqi.icu/Article/details/gtempjmjrs.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.mhx1999.top/Article/details/gtcpbuodja.html

Java: enum Color { RED, GREEN }
来源：http://dali.hongshengwenyu.top/Article/details/gtnpasryhi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258888.top/Article/details/gtktxlocvm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.vqdsnc.cn/Article/details/gthttyclku.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gtirhbrvjd.html

[G16] 对象转数组 / 字典
来源：http://dali.zdqjudy.top/Article/details/gttwrliwmp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258888.top/Article/details/gtqvwbxbcm.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gtrnjssvmb.html

JS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gtaytptkzm.html

TS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gtqvjalvou.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hysaishi.cn/Article/details/gtyafsktaj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sufxvd.cn/Article/details/gtbvfgluln.html

Ruby: obj.instance_variables
来源：http://dali.smart0.xyz/Article/details/gtzsbowojp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hysaishi.cn/Article/details/gtkckgdhfj.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtvbzofmdn.html

H. 异常与错误处理
来源：http://dali.wangdashe.top/Article/details/gtvwuljzmr.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtmpzruifp.html

[H01] try / catch 基础
来源：http://dali.sweek.top/Article/details/gtwarlmhiy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yueranfly.top/Article/details/gtftveslil.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhixingplan.top/Article/details/gtxwvyzotg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gtvijdollb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gtxlmpiyvy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ybcxt.top/Article/details/gtvkjkycku.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.aizwys.cn/Article/details/gtqvvuxzwu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ybcxt.top/Article/details/gtzwbzzuga.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj20258.top/Article/details/gtlomkbsob.html

[H02] finally / ensure 收尾
来源：http://dali.pengpengdd.cyou/Article/details/gtipgrxrjc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.daria6918.cn/Article/details/gtaiyreetz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtursjxmkv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtzdxnuexg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtbbpbqdvh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtkwiormjx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzruvowyr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shangyingyoupin.top/Article/details/gtqrmfxzgq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtgootcoqm.html

[H03] 主动抛出异常
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwmlazjd.html

Py:   raise ValueError("错误信息")
来源：http://dali.yueranfly.top/Article/details/gtlhrvlabl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtksyacyrv.html

JS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtqqfehlnr.html

TS:   throw new Error("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtdldsrrvz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtogbaacsc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhoulong.xyz/Article/details/gtvbhgjewt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.quarkkingdee.top/Article/details/gtyytsbpdp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtxdcvvrtc.html

[H04] 自定义异常类型
来源：http://dali.kuanghao11.cn/Article/details/gtannidjes.html

Py:   class MyError(Exception): pass
来源：http://dali.316326.xyz/Article/details/gtfivtciit.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhiwuduotai.top/Article/details/gtzaprgrai.html

JS:   class MyError extends Error {}
来源：http://dali.zdqjudy.top/Article/details/gtsnyuixap.html

TS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gtmkykiiat.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gtcmmcoxyo.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jqgfzy.top/Article/details/gtjprbgmik.html

Ruby: class MyError < StandardError; end
来源：http://dali.jqgfzy.top/Article/details/gtofvwfyoz.html

C#:   class MyException : Exception {}
来源：http://dali.zhiwuduotai.top/Article/details/gtkbflmyqo.html

[H05] 捕获特定类型
来源：http://dali.hnqzz.top/Article/details/gteyberwin.html

Py:   except ValueError as e:
来源：http://dali.aibaodan.cn/Article/details/gtddtjeigg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.0kj1m.cn/Article/details/gtsvncoomd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yangfankeji.com/Article/details/gtsyzbknwi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gthfnvagvt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj20258.top/Article/details/gtndwajthi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hfpthk.cn/Article/details/gtamtwmhab.html

Ruby: rescue ArgumentError => e
来源：http://dali.wangdashe.top/Article/details/gtgcwppqkd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.fengsongda.top/Article/details/gthjyeltty.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fzhhl.top/Article/details/gtcwmpfcvo.html

Py:   value = d.get("k") or default
来源：http://dali.snrcjt.cn/Article/details/gtsfpaerit.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgprocahc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gtxkhzuzjw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jlsjyb.cn/Article/details/gtzuhmhkkl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenzaomai.com/Article/details/gtjgkwuhnn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cheryme.top/Article/details/gtbtwahtya.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ydzc1.top/Article/details/gtwvqyjttw.html

C#:   obj?.A?.B ?? default
来源：http://dali.gzhubu.top/Article/details/gtjsobbhul.html

[H07] 断言
来源：http://dali.hfpthk.cn/Article/details/gtgbghxiua.html

Py:   assert x > 0, "必须为正"
来源：http://dali.guannengcc.top/Article/details/gtwidpurvh.html

PHP:  assert($x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtigbmiknt.html

JS:   console.assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gtydshlekr.html

TS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtxrabilvk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jqgufenzy.top/Article/details/gtzvpcxvjw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sweek.top/Article/details/gtlftugluh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj20258.top/Article/details/gtchavdqbz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtnoewisdx.html

[H08] 获取错误信息与堆栈
来源：http://dali.sufxvd.cn/Article/details/gtfcblzsod.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sufxvd.cn/Article/details/gteoeeaiha.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cdnleiting.top/Article/details/gtzrcgsbmf.html

JS:   e.message;  e.stack
来源：http://dali.mhx1999.top/Article/details/gtzclasumf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.quarkkingdee.top/Article/details/gtjlmsywck.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sysykeji.top/Article/details/gtabnlenod.html

Go:   err.Error()
来源：http://dali.tianlin.xyz/Article/details/gthjlppdst.html

Ruby: e.message;  e.backtrace
来源：http://dali.cdnleiting.top/Article/details/gtqglabkpy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yanxiufei.cn/Article/details/gtdhwoggod.html

[H09] 带错误码的异常
来源：http://dali.quarkkingdee.top/Article/details/gtnpiaeuzr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hysaishi.cn/Article/details/gtejpalgbr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.9152youxi.cn/Article/details/gtxbdpxmfu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gtkagmtsfi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tanke756.top/Article/details/gtavepeagl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ydzc1.top/Article/details/gtljadmmey.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenzaomai.com/Article/details/gtxyvoptjt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cucudq.cn/Article/details/gtodxlftts.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yueranfly.top/Article/details/gtmktcdacf.html

[H10] 资源自动释放
来源：http://dali.hnxiangtu.top/Article/details/gtmufelpui.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj202588.top/Article/details/gtjwgsrtct.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.snrcjt.cn/Article/details/gtyrupbkkr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhiwuduotai.top/Article/details/gtncrwnels.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guannengcc.top/Article/details/gtoleuwyda.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hammf.cn/Article/details/gtgssjwqba.html

Go:   defer f.Close()
来源：http://dali.hfpthk.cn/Article/details/gtwagsgiot.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hnxiangtu.top/Article/details/gtirvotuef.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtkjismmyg.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtxmwonbns.html

I. 正则表达式
来源：http://dali.zhixingplan.top/Article/details/gtkxfprpcl.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtwedxdcls.html

[I01] 判断是否匹配
来源：http://dali.ppjwa.cn/Article/details/gtvwvoxlph.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hysaishi.cn/Article/details/gtzmirmyuj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtlsndptuw.html

JS:   /\d+/.test(s)
来源：http://dali.dashuyun.cn/Article/details/gtmoldhett.html

TS:   /\d+/.test(s)
来源：http://dali.gotoacloud.top/Article/details/gtbwjuqagx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gaohongyu789.top/Article/details/gtmuwncsfl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqtuhmrz.html

Ruby: s.match?(/\d+/)
来源：http://dali.zycfv.cn/Article/details/gtkubntfgm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gtvjbpfyko.html

[I02] 提取所有匹配
来源：http://dali.zhongyouzk.top/Article/details/gtiyzoyaju.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yongpay.top/Article/details/gtvcvbbwuy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhongyouzk.top/Article/details/gtgdnadmtx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.birdmap.top/Article/details/gtvvdugejn.html

TS:   s.match(/\d+/g)
来源：http://dali.ppjwa.cn/Article/details/gtaccxhrfu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yuxming.cn/Article/details/gterxskqpl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.aibaodan.cn/Article/details/gtuvupyffk.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangshuangyany.cn/Article/details/gtaekgmbfe.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xziqi.cn/Article/details/gtbtkhqbwv.html

[I03] 提取捕获分组
来源：http://dali.vqdsnc.cn/Article/details/gtueluxvfp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.svipenyu.cn/Article/details/gtlpffwnwf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jlsjyb.cn/Article/details/gtofqkrjzv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yongpay.top/Article/details/gtnulmxkqj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.andypj.xyz/Article/details/gttnzqtabu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.daria6918.cn/Article/details/gtvbvtyrxr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.andypj.xyz/Article/details/gtwofuomez.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cashguo.top/Article/details/gtmdrqpful.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhixingplan.top/Article/details/gtsdtgbozf.html

[I04] 正则替换
来源：http://dali.0kj1m.cn/Article/details/gtzxysnhqa.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.meibo888.top/Article/details/gtmfnxmewu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxinkj.top/Article/details/gtavbswfwz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tian-w.cn/Article/details/gtgtaowzbk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gtkbpnotjk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.wangdashe.top/Article/details/gtlznmexsh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cheryme.top/Article/details/gtfdqfichb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ydzc1.top/Article/details/gttfmqinjw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbjbbohgg.html

[I05] 按正则拆分
来源：http://dali.shuidangran.top/Article/details/gtbxkouwqr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hysaishi.cn/Article/details/gtuxppskxu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hysaishi.cn/Article/details/gtiovvhgoi.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gtvtepjdcq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gtguhtkcno.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xinyue.icu/Article/details/gtgtmhhqby.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hysaishi.cn/Article/details/gtcrqfvgfs.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gtmgqwikpe.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtndzzcfqo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhoulong.xyz/Article/details/gtwmelguzj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hammf.cn/Article/details/gtqkeawkuz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hnqzz.top/Article/details/gtlyzpjint.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guannengcc.top/Article/details/gtouzovigy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmpbpfubz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gtfvhjugfi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ehwqpu.com/Article/details/gthlbbjwyn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.feifeiyinyue.top/Article/details/gteyluxmoo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gtnlndvovx.html

[I07] 忽略大小写与多行模式
来源：http://dali.bjfxy.top/Article/details/gtlrxlbkty.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nwbrower.top/Article/details/gtnxaoymbt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hywenlv.cn/Article/details/gtvqahsoyx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yueranfly.top/Article/details/gtoacjtwdp.html

TS:   /error/gim
来源：http://dali.0kj1m.cn/Article/details/gtqzzmbiuj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.tian-w.cn/Article/details/gtjhtcfoyz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hnxiangtu.top/Article/details/gtvqhvavjw.html

Ruby: s.scan(/error/i)
来源：http://dali.hongshengwenyu.top/Article/details/gtadpihfof.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxrzbzhjh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtgrvplzkh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.vqdsnc.cn/Article/details/gtjlekzvkl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.9152youxi.cn/Article/details/gtlabdfgtz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sufxvd.cn/Article/details/gtmvsfouqi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dianchejie.cn/Article/details/gtnlcbemzh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.smart0.xyz/Article/details/gtcxjieaeh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yonumen.top/Article/details/gtvlldsjmh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.havefunace.top/Article/details/gtufaclrpg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.quarkkingdee.top/Article/details/gtlnemqulf.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gttxawhigv.html

J. 日期与时间
来源：http://dali.zhixingplan.top/Article/details/gtuebocpdf.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtoxmzvzly.html

[J01] 获取当前时间
来源：http://dali.yj202588.top/Article/details/gtflytfsao.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrtvaicfd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jqgfzy.top/Article/details/gtxitkarxo.html

JS:   new Date();  Date.now()
来源：http://dali.yuxming.cn/Article/details/gtyucqgpkz.html

TS:   new Date();  Date.now()
来源：http://dali.xuetiantiany.cn/Article/details/gtvfinvtch.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zdqjudy.top/Article/details/gthgevjbou.html

Go:   time.Now()
来源：http://dali.0kj1m.cn/Article/details/gtucusoqll.html

Ruby: Time.now
来源：http://dali.sufxvd.cn/Article/details/gtlpqctrhd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuanzx.com/Article/details/gtedezzquf.html

[J02] 格式化输出
来源：http://dali.316326.xyz/Article/details/gtyjmdrpza.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zdqjudy.top/Article/details/gtpsyuwslz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hnxiangtu.top/Article/details/gtvhrhkkve.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.316326.xyz/Article/details/gttaenyvzu.html

TS:   d.toISOString()
来源：http://dali.zhongyouzk.top/Article/details/gtjkarrqae.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.guowangkeji.top/Article/details/gtlmbdsvez.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hnxiangtu.top/Article/details/gtwasgeiqv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.havefunace.top/Article/details/gtwoozmwfc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhixingplan.top/Article/details/gttbhgfetd.html

[J03] 字符串解析为日期
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwfeqclt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.316326.xyz/Article/details/gtlbmuukqg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tanke756.top/Article/details/gtjqsfokmg.html

JS:   new Date("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtjyvsgant.html

TS:   new Date("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtglyyunop.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtnfavwgag.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtehyebhst.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtmzdankgp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jianghu66.top/Article/details/gtkyhyhfgd.html

[J04] 时间戳与日期互转
来源：http://dali.hysaishi.cn/Article/details/gtssxdhknv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ppjwa.cn/Article/details/gtmitzcgga.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cucudq.cn/Article/details/gtkfznvaij.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nanxinkj.top/Article/details/gtoazlaikn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shangyingyoupin.top/Article/details/gtylsfpwyi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.fzhhl.top/Article/details/gtzctilely.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pycfn.com/Article/details/gttzasxikv.html


<!-- 参考信息 -->