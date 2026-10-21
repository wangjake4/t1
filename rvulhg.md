代发 wailian999

TS:   greet(): string { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtviqnwuqo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtbhbekvrx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gaohongyu789.top/Article/details/gtryrvixgv.html

Ruby: def greet; "admin"; end
来源：http://dali.xylfe.cn/Article/details/gtevvuvhoq.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxinkj.top/Article/details/gtqhpjjjft.html

[G07] 调用父类方法
来源：http://dali.xziqi.cn/Article/details/gttegplonr.html

Py:   super().greet()
来源：http://dali.tian-w.cn/Article/details/gtiamqycnn.html

PHP:  parent::greet();
来源：http://dali.guannengcc.top/Article/details/gtglrylkjz.html

JS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gtkecrhqod.html

TS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gttyzhmogn.html

Java: super.greet();
来源：http://dali.gogol.net.cn/Article/details/gtcdqeskaf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.fzhhl.top/Article/details/gttywujpzk.html

Ruby: super
来源：http://dali.zycfv.cn/Article/details/gtzytudyze.html

C#:   base.Greet();
来源：http://dali.sufxvd.cn/Article/details/gtlufnculq.html

[G08] 静态方法与属性
来源：http://dali.yuanzhike.top/Article/details/gtlyoahpjo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sweek.top/Article/details/gtrqilwwgb.html

PHP:  public static function f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtuftgpqsm.html

JS:   static f() {}
来源：http://dali.svipenyu.cn/Article/details/gtdzoubzmq.html

TS:   static f(): void {}
来源：http://dali.shzxlz.cn/Article/details/gtphueopzm.html

Java: static void f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gttascdyvu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.quarkkingdee.top/Article/details/gtxzaokyxf.html

Ruby: def self.f; end
来源：http://dali.yj202588.top/Article/details/gtrcwchoti.html

C#:   public static void F() {}
来源：http://dali.hammf.cn/Article/details/gtfgcikdpa.html

[G09] 接口 / 抽象类
来源：http://dali.sysykeji.top/Article/details/gtevywmpdk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdodtkgqz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.redwolf501.top/Article/details/gtrouhdmmg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cucudq.cn/Article/details/gtizqvzuyh.html

TS:   interface Shape { area(): number; }
来源：http://dali.dianchejie.cn/Article/details/gtagfvpeag.html

Java: interface Shape { double area(); }
来源：http://dali.zhixingplan.top/Article/details/gtaqbccggg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hnqzz.top/Article/details/gtlkbfuxxu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangdashe.top/Article/details/gtzixbrodw.html

C#:   interface IShape { double Area(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtjkkkocbv.html

[G10] 访问控制
来源：http://dali.cheryme.top/Article/details/gtbfeyssln.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xylfe.cn/Article/details/gtvwzqvntr.html

PHP:  public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gtovapgfks.html

JS:   #private 字段；其余公开
来源：http://dali.zycfv.cn/Article/details/gtfxumapqy.html

TS:   public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gttzgdwfhd.html

Java: public / protected / private / 默认包级
来源：http://dali.zhongyouzk.top/Article/details/gtolujbvrk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tian-w.cn/Article/details/gtiztcnrhm.html

Ruby: public / protected / private
来源：http://dali.tanke756.top/Article/details/gtdpkzordn.html

C#:   public / protected / private / internal
来源：http://dali.sxryk.cn/Article/details/gtkaetesjk.html

[G11] getter / setter
来源：http://dali.aibaodan.cn/Article/details/gtsiimyexd.html

Py:   @property 与 @x.setter
来源：http://dali.tian-w.cn/Article/details/gtcrzpzbwt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gtnrmgsnxt.html

JS:   get name() { return this._name; }
来源：http://dali.cashguo.top/Article/details/gtxvfyvbas.html

TS:   get name(): string { return this._name; }
来源：http://dali.iojbl.cn/Article/details/gtdamwilyx.html

Java: public String getName() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtmawqqfeu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gtkzvnystb.html

Ruby: attr_accessor :name
来源：http://dali.chenjidiqi.icu/Article/details/gtekddlvob.html

C#:   public string Name { get; set; }
来源：http://dali.hysaishi.cn/Article/details/gtugbyuwhe.html

[G12] 对象转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtswbceyvh.html

Py:   def __str__(self): return self.name
来源：http://dali.birdmap.top/Article/details/gtdbytargt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtozescpos.html

JS:   toString() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gttbaprrjm.html

TS:   toString(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gttwyxdalb.html

Java: @Override public String toString() { return name; }
来源：http://dali.daria6918.cn/Article/details/gtedszzfbb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gtncbfevnk.html

Ruby: def to_s; @name; end
来源：http://dali.yuxming.cn/Article/details/gtbxwaamci.html

C#:   public override string ToString() => Name;
来源：http://dali.yangfankeji.com/Article/details/gtfhoajyuc.html

[G13] 判断对象类型
来源：http://dali.sufxvd.cn/Article/details/gttlgcwivu.html

Py:   isinstance(u, User)
来源：http://dali.hnxiangtu.top/Article/details/gtkxogkabu.html

PHP:  $u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtxqdsqtzo.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gtrkkeqoll.html

TS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtsugwuolv.html

Java: u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtrwzlklen.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sufxvd.cn/Article/details/gtfkdbednh.html

Ruby: u.is_a?(User)
来源：http://dali.cashguo.top/Article/details/gtuzqeucfl.html

C#:   u is User
来源：http://dali.yangfankeji.com/Article/details/gtqdiyaank.html

[G14] 数据类 / record
来源：http://dali.yangfankeji.com/Article/details/gtmwznvkav.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hammf.cn/Article/details/gtidwgixik.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pengpengdd.cyou/Article/details/gtfhzlxxzd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gaohongyu789.top/Article/details/gtlgqslgld.html

TS:   type User = { name: string; age: number };
来源：http://dali.ydzc1.top/Article/details/gtiobliech.html

Java: record User(String name, int age) {}
来源：http://dali.cdnleiting.top/Article/details/gttjzbqbdk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.daxiang520.top/Article/details/gtsuyopsrm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hfpthk.cn/Article/details/gtusyvylnk.html

C#:   record User(string Name, int Age);
来源：http://dali.yuanzhike.top/Article/details/gtfhyngdhc.html

[G15] 枚举
来源：http://dali.hnqzz.top/Article/details/gttgtgnvzw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangshuangyany.cn/Article/details/gtzdwyengb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.daria6918.cn/Article/details/gtxxkucxyn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yuxming.cn/Article/details/gtzfzurczc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yueranfly.top/Article/details/gtdgetydiw.html

Java: enum Color { RED, GREEN }
来源：http://dali.pycfn.com/Article/details/gtmmajgyzp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gzhubu.top/Article/details/gtnxsmnedi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cucudq.cn/Article/details/gtjxoensma.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guowangkeji.top/Article/details/gtiijrbobz.html

[G16] 对象转数组 / 字典
来源：http://dali.hysaishi.cn/Article/details/gtpttdqhzy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenjidiqi.icu/Article/details/gtnvicpkis.html

PHP:  get_object_vars($obj);
来源：http://dali.hysaishi.cn/Article/details/gtrwvyalbk.html

JS:   Object.entries(obj)
来源：http://dali.gzhubu.top/Article/details/gtxriyojzn.html

TS:   Object.entries(obj)
来源：http://dali.yuxming.cn/Article/details/gtneqfjvap.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shzxlz.cn/Article/details/gtfyifwvyh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yueranfly.top/Article/details/gtytksvncb.html

Ruby: obj.instance_variables
来源：http://dali.daria6918.cn/Article/details/gthppqmpdn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.bjfxy.top/Article/details/gtotbtssfd.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtjamcajjh.html

H. 异常与错误处理
来源：http://dali.daxiang520.top/Article/details/gtxynhcssn.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtbuovhipm.html

[H01] try / catch 基础
来源：http://dali.xylfe.cn/Article/details/gtrbungpht.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dashuyun.cn/Article/details/gtcfxavpua.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxxcmwciz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gtwtifpbuu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gtoqaivgfc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.kuanghao11.cn/Article/details/gtbixznjbg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.snrcjt.cn/Article/details/gtbuktbfkd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxinkj.top/Article/details/gtrqcdattj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.meibo888.top/Article/details/gtwvejqcwk.html

[H02] finally / ensure 收尾
来源：http://dali.yuxming.cn/Article/details/gtyghlinbg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shzxlz.cn/Article/details/gtbaqujszt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtkfhwnjfk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtixjdoiqd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gteluiavdp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkoxiqsb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sweek.top/Article/details/gtlhydqtqy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yanxiufei.cn/Article/details/gtuyluexww.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtfgnorwbf.html

[H03] 主动抛出异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrekbmoui.html

Py:   raise ValueError("错误信息")
来源：http://dali.smart0.xyz/Article/details/gtubyqalzo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqquqdsbv.html

JS:   throw new Error("错误信息");
来源：http://dali.zycfv.cn/Article/details/gteouesyhx.html

TS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtstkskyvl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtnebsceil.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.andypj.xyz/Article/details/gthpzbcfvt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jiagoushi.top/Article/details/gtulfgunnn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtambjivji.html

[H04] 自定义异常类型
来源：http://dali.gogol.net.cn/Article/details/gtfxlmjaya.html

Py:   class MyError(Exception): pass
来源：http://dali.aibaodan.cn/Article/details/gtntxfzwwx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tianlin.xyz/Article/details/gtjtfiqckt.html

JS:   class MyError extends Error {}
来源：http://dali.hfpthk.cn/Article/details/gtqkwbloxo.html

TS:   class MyError extends Error {}
来源：http://dali.shangyingyoupin.top/Article/details/gtgqgcupdw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.9152youxi.cn/Article/details/gtxwlvfslw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.c1oappe.top/Article/details/gtqfmbcjrt.html

Ruby: class MyError < StandardError; end
来源：http://dali.cheryme.top/Article/details/gtbbcunltq.html

C#:   class MyException : Exception {}
来源：http://dali.jianghu66.top/Article/details/gtlbstdyss.html

[H05] 捕获特定类型
来源：http://dali.cucudq.cn/Article/details/gthfhmhnin.html

Py:   except ValueError as e:
来源：http://dali.shangyingyoupin.top/Article/details/gtioftiyxr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ybcxt.top/Article/details/gtfectrwkt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtgqstmexo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gtrdknhmhn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuxming.cn/Article/details/gtjxkxqtea.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guowangkeji.top/Article/details/gtbltfhjlk.html

Ruby: rescue ArgumentError => e
来源：http://dali.nwbrower.top/Article/details/gtxlgiowee.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtjukndstu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dianchejie.cn/Article/details/gtwdunmqlb.html

Py:   value = d.get("k") or default
来源：http://dali.hammf.cn/Article/details/gtdtwduzsc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gtrjuzmdbh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.mhx1999.top/Article/details/gtbshcqoap.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gtmscsatwc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gogol.net.cn/Article/details/gtmqjzoyvp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jiagoushi.top/Article/details/gtohnckegf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenzaomai.com/Article/details/gtefahjxfx.html

C#:   obj?.A?.B ?? default
来源：http://dali.yangfankeji.com/Article/details/gtkvpfzrqt.html

[H07] 断言
来源：http://dali.hnxiangtu.top/Article/details/gtqsabdocg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aizwys.cn/Article/details/gtkxljovsk.html

PHP:  assert($x > 0);
来源：http://dali.guannengcc.top/Article/details/gtfcoayplv.html

JS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtcoamlrhm.html

TS:   console.assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gtjdtjqvdx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yvedp.cn/Article/details/gtdwwobtfi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.kuanghao11.cn/Article/details/gtcordcmvu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zycfv.cn/Article/details/gtgkfhmlng.html

C#:   Debug.Assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtbexbbikv.html

[H08] 获取错误信息与堆栈
来源：http://dali.yonumen.top/Article/details/gtlipnsvnq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yangfankeji.com/Article/details/gtogftlorg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.pycfn.com/Article/details/gteticuksa.html

JS:   e.message;  e.stack
来源：http://dali.redwolf501.top/Article/details/gtzsughzpf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenzaomai.com/Article/details/gtjbrmnxkl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jianghu66.top/Article/details/gtvtulrcsu.html

Go:   err.Error()
来源：http://dali.hnqzz.top/Article/details/gtrbbfkhhb.html

Ruby: e.message;  e.backtrace
来源：http://dali.ybcxt.top/Article/details/gthoppzmha.html

C#:   e.Message;  e.StackTrace
来源：http://dali.smart0.xyz/Article/details/gtuwiqflnd.html

[H09] 带错误码的异常
来源：http://dali.snrcjt.cn/Article/details/gtruvttjxp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jqgufenzy.top/Article/details/gtilflhevj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangshuangyany.cn/Article/details/gtmtoqxrne.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjknwzaft.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.redwolf501.top/Article/details/gtsvgaoatb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hongshengwenyu.top/Article/details/gtzeujrnxp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.316326.xyz/Article/details/gtgijdodhk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnqzz.top/Article/details/gtqouhputo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.iojbl.cn/Article/details/gtzncrqpug.html

[H10] 资源自动释放
来源：http://dali.yueranfly.top/Article/details/gtzglvgdvc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.aizwys.cn/Article/details/gtjibmqxwq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.c1oappe.top/Article/details/gtmqtifgjb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.quarkkingdee.top/Article/details/gtroeqtwqy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gtpisontuf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yuanzhike.top/Article/details/gtkzpehycc.html

Go:   defer f.Close()
来源：http://dali.xylfe.cn/Article/details/gtzfcjuwjt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cheryme.top/Article/details/gtwqkvbowt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtudzuikec.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtgiwvkxei.html

I. 正则表达式
来源：http://dali.zycfv.cn/Article/details/gtmbvgvvtu.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gticztmsxx.html

[I01] 判断是否匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtqkniarbw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gtreqamzkj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.mhx1999.top/Article/details/gtjtmxtdwx.html

JS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gtcfpdphya.html

TS:   /\d+/.test(s)
来源：http://dali.jinqigfzy.top/Article/details/gtagwjiwbo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sufxvd.cn/Article/details/gtznrllbaj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.aizwys.cn/Article/details/gtdayrwcsk.html

Ruby: s.match?(/\d+/)
来源：http://dali.quarkkingdee.top/Article/details/gtnydrktpk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xinyue.icu/Article/details/gtocdhkguf.html

[I02] 提取所有匹配
来源：http://dali.0kj1m.cn/Article/details/gtsmcwobss.html

Py:   re.findall(r"\d+", s)
来源：http://dali.meibo888.top/Article/details/gtvhqefkku.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.feifeiyinyue.top/Article/details/gtjuzgpubg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.vqdsnc.cn/Article/details/gtczhqvlzg.html

TS:   s.match(/\d+/g)
来源：http://dali.shzxlz.cn/Article/details/gtmacaaevv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnrcbborf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jianghu66.top/Article/details/gttrkqwvyr.html

Ruby: s.scan(/\d+/)
来源：http://dali.zdqjudy.top/Article/details/gteirooiph.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.meibo888.top/Article/details/gtgappfsvm.html

[I03] 提取捕获分组
来源：http://dali.yuanzhike.top/Article/details/gtuykpbmve.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.aibaodan.cn/Article/details/gtgqpxgsnw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ehwqpu.com/Article/details/gtyongrchc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gotoacloud.top/Article/details/gtxstxvwtz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yueranfly.top/Article/details/gtwfnwleeu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gaohongyu789.top/Article/details/gtujihtkpv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xuetiantiany.cn/Article/details/gthscmastq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhengqikj.top/Article/details/gtrfndrrcx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyfperjvd.html

[I04] 正则替换
来源：http://dali.cashguo.top/Article/details/gtpphijfvd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.guannengcc.top/Article/details/gtqgbrqume.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yvedp.cn/Article/details/gtxoexcedj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gtafformxs.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigufen.top/Article/details/gtmeejpngc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gzhubu.top/Article/details/gturddcvow.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtfjcdssjx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daxiang520.top/Article/details/gtejridzcz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hammf.cn/Article/details/gteobfpbkb.html

[I05] 按正则拆分
来源：http://dali.xylfe.cn/Article/details/gtwvrnvbmn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.iojbl.cn/Article/details/gtgrwsdnnv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tanke756.top/Article/details/gteamjocdk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gtllvthvsv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gtunwyofvc.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yonumen.top/Article/details/gtfeyzyiqy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shuidangran.top/Article/details/gtljmecwrj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gtwbglyxhb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ivvv.top/Article/details/gtsgqbsrvb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hongshengwenyu.top/Article/details/gtbhpdamry.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gtdvqvkgzy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.316326.xyz/Article/details/gtflbcfqde.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhiwuduotai.top/Article/details/gtabyngkrf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aibaodan.cn/Article/details/gtlmiulfbi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gtkkeyrjor.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zdqjudy.top/Article/details/gtlxljwnjd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcnygdwan.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.fengsongda.top/Article/details/gtcgansorc.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhixingplan.top/Article/details/gtunqwdxpa.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ppjwa.cn/Article/details/gteiqdxlkq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gtlvmhqeqb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yonumen.top/Article/details/gtrvmrnphy.html

TS:   /error/gim
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxgkwiquq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbfnnfbut.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sysykeji.top/Article/details/gtnwrspyrt.html

Ruby: s.scan(/error/i)
来源：http://dali.9152youxi.cn/Article/details/gtubgddqec.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tian-w.cn/Article/details/gtztnrzkik.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.fzhhl.top/Article/details/gtuvzxkdco.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.bjfxy.top/Article/details/gtfswlntul.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.snrcjt.cn/Article/details/gtnjvoqfny.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gtijhgbkya.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhengqikj.top/Article/details/gtyyjtlzhr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpvcufllu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenzaomai.com/Article/details/gtufbbgnwz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zycfv.cn/Article/details/gthwbkcxdv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.bjfxy.top/Article/details/gtbcinrmdz.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtxmpprhml.html

J. 日期与时间
来源：http://dali.gzhubu.top/Article/details/gtxagrwdgl.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtsgbjwhah.html

[J01] 获取当前时间
来源：http://dali.feifeiyinyue.top/Article/details/gtqjfbyjxg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sysykeji.top/Article/details/gtlzvfchdf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.feifeiyinyue.top/Article/details/gtuhzpnfnt.html

JS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gtreddchzf.html

TS:   new Date();  Date.now()
来源：http://dali.jyoumei.cn/Article/details/gtkxzzkwrd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jianghu66.top/Article/details/gttixrbfjn.html

Go:   time.Now()
来源：http://dali.c1oappe.top/Article/details/gtqbtlttji.html

Ruby: Time.now
来源：http://dali.fzhhl.top/Article/details/gtbsscuiga.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gotoacloud.top/Article/details/gtbusjrept.html

[J02] 格式化输出
来源：http://dali.sweek.top/Article/details/gtzzgbbcpt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fzhhl.top/Article/details/gtykafjfhr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenlongwang.top/Article/details/gtuqxsonog.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.smart0.xyz/Article/details/gtlhlrcmak.html

TS:   d.toISOString()
来源：http://dali.nwbrower.top/Article/details/gtdyffnqwj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sysykeji.top/Article/details/gtipfcyqty.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hnqzz.top/Article/details/gtrrpbniap.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cucudq.cn/Article/details/gtldiwebgs.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.dashuyun.cn/Article/details/gtcwohtyun.html

[J03] 字符串解析为日期
来源：http://dali.0kj1m.cn/Article/details/gtswdolrkk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.wangdashe.top/Article/details/gtqhdshdpn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nwbrower.top/Article/details/gtjwdtaxtk.html

JS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgkhwmxzq.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtwbynwlxo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gthneawjio.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtsdsndieo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtbrighkbp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jqgfzy.top/Article/details/gttfmvtfht.html

[J04] 时间戳与日期互转
来源：http://dali.sweek.top/Article/details/gteipcladn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.smart0.xyz/Article/details/gttogyojbd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xuanzx.com/Article/details/gtficdwtax.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.haohaochexian.top/Article/details/gtzkfwtsvy.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ybcxt.top/Article/details/gtxltzxryk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtromtqifj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yonumen.top/Article/details/gtunlntvmh.html


<!-- 参考信息 -->