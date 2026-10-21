代发 wailian999

C#:   public override string Greet() => "admin";
来源：http://dali.hywenlv.cn/Article/details/gtvoxtftxr.html

[G07] 调用父类方法
来源：http://dali.yonumen.top/Article/details/gtlzhwmejd.html

Py:   super().greet()
来源：http://dali.zhiwuduotai.top/Article/details/gtmmqqbpcm.html

PHP:  parent::greet();
来源：http://dali.yanxiufei.cn/Article/details/gtkkctemjp.html

JS:   super.greet();
来源：http://dali.ppjwa.cn/Article/details/gthymksdpj.html

TS:   super.greet();
来源：http://dali.cheryme.top/Article/details/gtjrocbwfl.html

Java: super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtxtsjgnqv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cucudq.cn/Article/details/gtmtqxochf.html

Ruby: super
来源：http://dali.hysaishi.cn/Article/details/gtwswvfwbr.html

C#:   base.Greet();
来源：http://dali.cucudq.cn/Article/details/gtlldxcxmf.html

[G08] 静态方法与属性
来源：http://dali.vqdsnc.cn/Article/details/gttubbcwgg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgufenzy.top/Article/details/gtcvwthvum.html

PHP:  public static function f() {}
来源：http://dali.pycfn.com/Article/details/gtlduxmkee.html

JS:   static f() {}
来源：http://dali.9152youxi.cn/Article/details/gtvqzerbjk.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtfudknjbx.html

Java: static void f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtstnqusii.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dashuyun.cn/Article/details/gtplodnnsm.html

Ruby: def self.f; end
来源：http://dali.xziqi.cn/Article/details/gtwqijifjh.html

C#:   public static void F() {}
来源：http://dali.zdqjudy.top/Article/details/gtiknzrbqp.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gtuyuvucyn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xuanzx.com/Article/details/gtgmydedwr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.dashuyun.cn/Article/details/gtmrgeirnp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xziqi.cn/Article/details/gtachfnldh.html

TS:   interface Shape { area(): number; }
来源：http://dali.ydzc1.top/Article/details/gtxoweywih.html

Java: interface Shape { double area(); }
来源：http://dali.sysykeji.top/Article/details/gtxtfblwsa.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.pycfn.com/Article/details/gtihccxqbk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jqgufenzy.top/Article/details/gtvasxvowh.html

C#:   interface IShape { double Area(); }
来源：http://dali.jlsjyb.cn/Article/details/gtunvaqniy.html

[G10] 访问控制
来源：http://dali.pycfn.com/Article/details/gtopmnpwur.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.svipenyu.cn/Article/details/gtsqafuoir.html

PHP:  public / protected / private
来源：http://dali.yvedp.cn/Article/details/gtsctdjsqq.html

JS:   #private 字段；其余公开
来源：http://dali.dashuyun.cn/Article/details/gtslmsxlle.html

TS:   public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gttmtucsqc.html

Java: public / protected / private / 默认包级
来源：http://dali.yangfankeji.com/Article/details/gtguelarsb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gthvuvsabs.html

Ruby: public / protected / private
来源：http://dali.cashguo.top/Article/details/gttpbcvsio.html

C#:   public / protected / private / internal
来源：http://dali.ppjwa.cn/Article/details/gtoterxjrz.html

[G11] getter / setter
来源：http://dali.chenlongwang.top/Article/details/gthgbeqylz.html

Py:   @property 与 @x.setter
来源：http://dali.nwbrower.top/Article/details/gtewwteshx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gththngout.html

JS:   get name() { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gtwknzszzr.html

TS:   get name(): string { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gtonwwznta.html

Java: public String getName() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrpawili.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gtcarzrikx.html

Ruby: attr_accessor :name
来源：http://dali.jlsjyb.cn/Article/details/gtebblnezk.html

C#:   public string Name { get; set; }
来源：http://dali.bjfxy.top/Article/details/gtnitkzlov.html

[G12] 对象转字符串
来源：http://dali.jyoumei.cn/Article/details/gtpdyiptzr.html

Py:   def __str__(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gtjqnsdvgm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtlfkxlwim.html

JS:   toString() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gttelzubwa.html

TS:   toString(): string { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtwazplthi.html

Java: @Override public String toString() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtcjrkrqro.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gtkvmkvflb.html

Ruby: def to_s; @name; end
来源：http://dali.zycfv.cn/Article/details/gtizmbtlhv.html

C#:   public override string ToString() => Name;
来源：http://dali.snrcjt.cn/Article/details/gtmkpfhbaj.html

[G13] 判断对象类型
来源：http://dali.quarkkingdee.top/Article/details/gtxvledmqe.html

Py:   isinstance(u, User)
来源：http://dali.birdmap.top/Article/details/gtdeyyaixr.html

PHP:  $u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gttljubihp.html

JS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gttmssdmaw.html

TS:   u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtnnkcblkc.html

Java: u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtregpmqzv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.snrcjt.cn/Article/details/gtwmllnqiu.html

Ruby: u.is_a?(User)
来源：http://dali.xuetiantiany.cn/Article/details/gtbuvjivoo.html

C#:   u is User
来源：http://dali.316326.xyz/Article/details/gtuauqcdcs.html

[G14] 数据类 / record
来源：http://dali.nwbrower.top/Article/details/gtftbfzskv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.redwolf501.top/Article/details/gtwgoqthnh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxinkj.top/Article/details/gtcbwqnuzz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinqigufen.top/Article/details/gtvfoxpmdv.html

TS:   type User = { name: string; age: number };
来源：http://dali.cheryme.top/Article/details/gtftcoqloz.html

Java: record User(String name, int age) {}
来源：http://dali.yj20258888.top/Article/details/gtwerghecl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthwimxer.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.haohaochexian.top/Article/details/gttvndgvql.html

C#:   record User(string Name, int Age);
来源：http://dali.jqgfzy.top/Article/details/gtoynuyyzz.html

[G15] 枚举
来源：http://dali.birdmap.top/Article/details/gtneuevgrb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hammf.cn/Article/details/gtuyzijstn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yueranfly.top/Article/details/gtvsbeclqg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dianchejie.cn/Article/details/gtbihjabbz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.haohaochexian.top/Article/details/gtsbtsvecd.html

Java: enum Color { RED, GREEN }
来源：http://dali.sxryk.cn/Article/details/gtgvtmnudu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuanzhike.top/Article/details/gtihfrqfjp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gtglcppdjy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gtgdpicuys.html

[G16] 对象转数组 / 字典
来源：http://dali.ivvv.top/Article/details/gtmoqmoqhd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shzxlz.cn/Article/details/gtqqgomuls.html

PHP:  get_object_vars($obj);
来源：http://dali.andypj.xyz/Article/details/gtqxcmqnop.html

JS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhrvpafu.html

TS:   Object.entries(obj)
来源：http://dali.hnxiangtu.top/Article/details/gthiazhigr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hfpthk.cn/Article/details/gtgqdhrghv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hammf.cn/Article/details/gtfxpdfoqc.html

Ruby: obj.instance_variables
来源：http://dali.0kj1m.cn/Article/details/gtyxatnvxc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gtxxiihahf.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtwgntrsay.html

H. 异常与错误处理
来源：http://dali.xuanzx.com/Article/details/gttiubczxk.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtworevmqj.html

[H01] try / catch 基础
来源：http://dali.wangdashe.top/Article/details/gtkasevhyn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfpevgets.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuanzhike.top/Article/details/gtmjumryfb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hammf.cn/Article/details/gtdkoizaar.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gtnbkiqylk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zycfv.cn/Article/details/gtadmzmyjh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.andypj.xyz/Article/details/gtcaccrppx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sysykeji.top/Article/details/gttcbejodu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenlongwang.top/Article/details/gtmarhujgv.html

[H02] finally / ensure 收尾
来源：http://dali.hongshengwenyu.top/Article/details/gtuwrymbzr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgufenzy.top/Article/details/gtbusipmnz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtobasalji.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtcxnifejt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gthqyzztsl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gttlpqdrgu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.daria6918.cn/Article/details/gtfedlazrj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ydzc1.top/Article/details/gtfndaqqud.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtujmzstiw.html

[H03] 主动抛出异常
来源：http://dali.tianlin.xyz/Article/details/gtbfgqtrcq.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuetiantiany.cn/Article/details/gtewaegebd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtdihtsroe.html

JS:   throw new Error("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtkwkjtjgt.html

TS:   throw new Error("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtuscggxer.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtkrcqbbyn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqeeylqcy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yueranfly.top/Article/details/gtchpqqinj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtkytqvzte.html

[H04] 自定义异常类型
来源：http://dali.yueranfly.top/Article/details/gtjdqgajff.html

Py:   class MyError(Exception): pass
来源：http://dali.guannengcc.top/Article/details/gtlyolryub.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinqigufen.top/Article/details/gtduycdgpw.html

JS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gtkujgkmrm.html

TS:   class MyError extends Error {}
来源：http://dali.aibaodan.cn/Article/details/gtexestlvn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gogol.net.cn/Article/details/gtekwnznso.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.kuanghao11.cn/Article/details/gtgitnysbb.html

Ruby: class MyError < StandardError; end
来源：http://dali.jqgfzy.top/Article/details/gtnicdjsjb.html

C#:   class MyException : Exception {}
来源：http://dali.iojbl.cn/Article/details/gtehyaocsg.html

[H05] 捕获特定类型
来源：http://dali.haohaochexian.top/Article/details/gtjsylborw.html

Py:   except ValueError as e:
来源：http://dali.nanxinkj.top/Article/details/gtqtksgmuq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuetiantiany.cn/Article/details/gtqcotthbd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gtoanmghyy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hysaishi.cn/Article/details/gtpxbxqmcp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.haohaochexian.top/Article/details/gtjofqdwwb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ppjwa.cn/Article/details/gtmtejdnkg.html

Ruby: rescue ArgumentError => e
来源：http://dali.sxryk.cn/Article/details/gtqqeleqpg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinqigufen.top/Article/details/gtdnqdaihr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigfzy.top/Article/details/gtrklenzvr.html

Py:   value = d.get("k") or default
来源：http://dali.nanxuanxn.top/Article/details/gtslclpxpr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yueranfly.top/Article/details/gtipnfssll.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cashguo.top/Article/details/gtnhojuigw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.9152youxi.cn/Article/details/gtqsdimyvh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.redwolf501.top/Article/details/gtcdxydutt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ydzc1.top/Article/details/gtxmjpxiyw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuetiantiany.cn/Article/details/gtyiusfgiq.html

C#:   obj?.A?.B ?? default
来源：http://dali.gogol.net.cn/Article/details/gtyhhethoo.html

[H07] 断言
来源：http://dali.daria6918.cn/Article/details/gtgdxjtmkh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gogol.net.cn/Article/details/gtwcdrksgq.html

PHP:  assert($x > 0);
来源：http://dali.yongpay.top/Article/details/gtbxfdmekq.html

JS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtwxxaxrve.html

TS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gtsvxwyehw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.pengpengdd.cyou/Article/details/gtxherqovj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.daria6918.cn/Article/details/gthcnmvrjk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tianlin.xyz/Article/details/gtqpkupnwa.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtwzermjxp.html

[H08] 获取错误信息与堆栈
来源：http://dali.hfpthk.cn/Article/details/gtbocsnilb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenjidiqi.icu/Article/details/gtapvcozel.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shzxlz.cn/Article/details/gtmlbwvxit.html

JS:   e.message;  e.stack
来源：http://dali.316326.xyz/Article/details/gtgtisnorm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.havefunace.top/Article/details/gtzrzfswjm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.feifeiyinyue.top/Article/details/gtbzwklvfo.html

Go:   err.Error()
来源：http://dali.nanxuanxn.top/Article/details/gtedvotbyc.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj202588.top/Article/details/gtluzmxrsp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.snrcjt.cn/Article/details/gtsezxylbw.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtgglosybl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sxryk.cn/Article/details/gtotmxifne.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xuanzx.com/Article/details/gtuwsadsbt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cucudq.cn/Article/details/gtauogdqfk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yangfankeji.com/Article/details/gtzozcdgtv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daria6918.cn/Article/details/gtgansgdvi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhiwuduotai.top/Article/details/gtpnjupgsz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jqgfzy.top/Article/details/gtqeyccghj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj20258888.top/Article/details/gtueqyxtzc.html

[H10] 资源自动释放
来源：http://dali.ehwqpu.com/Article/details/gtexzgukzd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yonumen.top/Article/details/gtepcgfflu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj20258888.top/Article/details/gtoiqmbdbi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hammf.cn/Article/details/gtztifrjxb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangkeji.top/Article/details/gtypsjaqpp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.meibo888.top/Article/details/gtattoumsf.html

Go:   defer f.Close()
来源：http://dali.hywenlv.cn/Article/details/gtrlswlgxg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinqigufen.top/Article/details/gtjtrsswkw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtrbaksppb.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtboswgkia.html

I. 正则表达式
来源：http://dali.jianghu66.top/Article/details/gtbhjgifsv.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtxcrovfeu.html

[I01] 判断是否匹配
来源：http://dali.hnxiangtu.top/Article/details/gtfgercrtd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jlsjyb.cn/Article/details/gtlreihfxv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtiyoxcxwz.html

JS:   /\d+/.test(s)
来源：http://dali.dashuyun.cn/Article/details/gtcqzujfdd.html

TS:   /\d+/.test(s)
来源：http://dali.yuanzhike.top/Article/details/gtctiudmnp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.wangshuangyany.cn/Article/details/gthsxkosmw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shuidangran.top/Article/details/gtnjvthvmg.html

Ruby: s.match?(/\d+/)
来源：http://dali.havefunace.top/Article/details/gtzxzhasli.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhoulong.xyz/Article/details/gtttmrdvcw.html

[I02] 提取所有匹配
来源：http://dali.guowangkeji.top/Article/details/gtrdvyploj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpiklelsf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj20258.top/Article/details/gtrbcwktvq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tanke756.top/Article/details/gtsarhwkeo.html

TS:   s.match(/\d+/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtstvqwjms.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nanxuanxn.top/Article/details/gthuvlwpqk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenlongwang.top/Article/details/gtucuzouql.html

Ruby: s.scan(/\d+/)
来源：http://dali.yangfankeji.com/Article/details/gtvxfrjzaw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sweek.top/Article/details/gttystmjtl.html

[I03] 提取捕获分组
来源：http://dali.zhixingplan.top/Article/details/gthzcpkvph.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xziqi.cn/Article/details/gtmotkpplm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yuxming.cn/Article/details/gtmjbgbgag.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gthoiswdrc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.svipenyu.cn/Article/details/gtjhxlxwyg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hfpthk.cn/Article/details/gttvunjasr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.guowangkeji.top/Article/details/gtfpckhmzj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.guannengcc.top/Article/details/gtwomiswpo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zycfv.cn/Article/details/gtngvhkxze.html

[I04] 正则替换
来源：http://dali.nanxinkj.top/Article/details/gtayozhrqy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.birdmap.top/Article/details/gtlqkivkto.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zdqjudy.top/Article/details/gtaghoshlc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gtnyrrhudu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cqqwz.cn/Article/details/gtndhlystj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhengqikj.top/Article/details/gtcoutvdau.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtjoaglyqp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zdqjudy.top/Article/details/gtjgasccum.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yonumen.top/Article/details/gtpsxkydgu.html

[I05] 按正则拆分
来源：http://dali.xinyue.icu/Article/details/gtfzwpnbxd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.guowangkeji.top/Article/details/gtdphquflt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yangfankeji.com/Article/details/gtfixxfymv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gtluafrbxv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnoayfumb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtktfwxkct.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sysykeji.top/Article/details/gtthzzwqke.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gtnwubdvvz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cdnleiting.top/Article/details/gtjdsokvdk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cheryme.top/Article/details/gtednwmdqy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtgqsikbem.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.bjfxy.top/Article/details/gttgmeqzyk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gttwlranir.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangtech.top/Article/details/gtvajmeojb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gtyhvjwuoc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gzhubu.top/Article/details/gtzyrmorgc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhengqikj.top/Article/details/gttdtltcsp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gttahpkwjx.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj202588.top/Article/details/gtotuwybpq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hnxiangtu.top/Article/details/gtzqqlgamp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gtjfisiakt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tianlin.xyz/Article/details/gtkifyeiiz.html

TS:   /error/gim
来源：http://dali.c1oappe.top/Article/details/gtdnggbqkm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.c1oappe.top/Article/details/gtrotmmlty.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhoulong.xyz/Article/details/gtolyrtslk.html

Ruby: s.scan(/error/i)
来源：http://dali.gaohongyu789.top/Article/details/gtylixyuap.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yuxming.cn/Article/details/gtaeidlwli.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cheryme.top/Article/details/gtgclcplsi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ppjwa.cn/Article/details/gtwcgvuntc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gtgryzuftq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gteqgqcpwo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sxryk.cn/Article/details/gtadhjvqpx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sxryk.cn/Article/details/gtmsxmvfgh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tianlin.xyz/Article/details/gtmwsybssc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnsccpfzv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenjidiqi.icu/Article/details/gtsnecxuow.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtgumhinjo.html

J. 日期与时间
来源：http://dali.yuxming.cn/Article/details/gtlehwdhgs.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtdnspnkrx.html

[J01] 获取当前时间
来源：http://dali.sweek.top/Article/details/gtwoufwrtj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnldwshbf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gtmajtctha.html

JS:   new Date();  Date.now()
来源：http://dali.shangyingyoupin.top/Article/details/gtfuitnefe.html

TS:   new Date();  Date.now()
来源：http://dali.cashguo.top/Article/details/gtdvvlrpot.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.feifeiyinyue.top/Article/details/gtkuebxjhl.html

Go:   time.Now()
来源：http://dali.svipenyu.cn/Article/details/gtvdftrpox.html

Ruby: Time.now
来源：http://dali.jianghu66.top/Article/details/gtsmxpkyom.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.iojbl.cn/Article/details/gttuvrdfkj.html

[J02] 格式化输出
来源：http://dali.hongshengwenyu.top/Article/details/gtvftfbvvt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hywenlv.cn/Article/details/gtapyrlvqt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ybcxt.top/Article/details/gtdmhmizfo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.redwolf501.top/Article/details/gtlumekldc.html

TS:   d.toISOString()
来源：http://dali.zycfv.cn/Article/details/gtlbgevext.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sweek.top/Article/details/gtgxpgzdit.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.mhx1999.top/Article/details/gtnhyuujee.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aibaodan.cn/Article/details/gtdhfapdpj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cashguo.top/Article/details/gtzbwivplb.html

[J03] 字符串解析为日期
来源：http://dali.shangyingyoupin.top/Article/details/gtdmepdvjs.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gzhubu.top/Article/details/gttnbgldxz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jianghu66.top/Article/details/gtpwbexkqs.html

JS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtogicxxsf.html

TS:   new Date("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtxkcuqcsa.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtmndhqouj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtxyhormpz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtcymdzkbm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhijiandao.cn/Article/details/gtxdgsgpyi.html

[J04] 时间戳与日期互转
来源：http://dali.mhx1999.top/Article/details/gtfoxappak.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhoulong.xyz/Article/details/gthqwrrdyo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jyoumei.cn/Article/details/gtquezrwyi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xylfe.cn/Article/details/gtrzgmlfgh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfysxbwwa.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hnqzz.top/Article/details/gtkurzulrh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangdashe.top/Article/details/gtgrjyztsj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.bjfxy.top/Article/details/gttlmdbcqp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtcammkepl.html

[J05] 时间加减（加 7 天）
来源：http://dali.sufxvd.cn/Article/details/gtsnqwziox.html

Py:   now + timedelta(days=7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtddxkufzw.html


<!-- 参考信息 -->