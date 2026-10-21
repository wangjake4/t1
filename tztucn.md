代发 wailian999

PHP:  public static function f() {}
来源：http://dali.shzxlz.cn/Article/details/gtzsllpyxg.html

JS:   static f() {}
来源：http://dali.hysaishi.cn/Article/details/gtgyvowpkx.html

TS:   static f(): void {}
来源：http://dali.daria6918.cn/Article/details/gtqbchuqdr.html

Java: static void f() {}
来源：http://dali.yonumen.top/Article/details/gtxgboyebc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.wangdashe.top/Article/details/gtppmztvth.html

Ruby: def self.f; end
来源：http://dali.kuanghao11.cn/Article/details/gtnxpblbkw.html

C#:   public static void F() {}
来源：http://dali.birdmap.top/Article/details/gtnxlnldti.html

[G09] 接口 / 抽象类
来源：http://dali.aibaodan.cn/Article/details/gtqnzcdyto.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hfpthk.cn/Article/details/gtkcanazfc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yuxming.cn/Article/details/gtxemsgkia.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cdnleiting.top/Article/details/gtsfhcxgbv.html

TS:   interface Shape { area(): number; }
来源：http://dali.redwolf501.top/Article/details/gtevoqmrrt.html

Java: interface Shape { double area(); }
来源：http://dali.cheryme.top/Article/details/gtbprprvnh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fzhhl.top/Article/details/gtamawgerj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxtgnutqb.html

C#:   interface IShape { double Area(); }
来源：http://dali.gotoacloud.top/Article/details/gtqelqjday.html

[G10] 访问控制
来源：http://dali.guannengcc.top/Article/details/gtmzmooksx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.c1oappe.top/Article/details/gtufzwzazx.html

PHP:  public / protected / private
来源：http://dali.zycfv.cn/Article/details/gttqmdrdas.html

JS:   #private 字段；其余公开
来源：http://dali.xuanzx.com/Article/details/gtmyjfyqmf.html

TS:   public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gtopcehwuv.html

Java: public / protected / private / 默认包级
来源：http://dali.zhixingplan.top/Article/details/gtkwmomfun.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.wangdashe.top/Article/details/gtggbqjdxh.html

Ruby: public / protected / private
来源：http://dali.nwbrower.top/Article/details/gtkgusbtpt.html

C#:   public / protected / private / internal
来源：http://dali.hnqzz.top/Article/details/gtveyoiqjb.html

[G11] getter / setter
来源：http://dali.tanke756.top/Article/details/gtfqidtfos.html

Py:   @property 与 @x.setter
来源：http://dali.yuanzhike.top/Article/details/gttykeeobm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtpnucigqx.html

JS:   get name() { return this._name; }
来源：http://dali.bjfxy.top/Article/details/gtlbdkicie.html

TS:   get name(): string { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gtpsqznree.html

Java: public String getName() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtibdktrah.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gtjvseafwm.html

Ruby: attr_accessor :name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtminnzxbs.html

C#:   public string Name { get; set; }
来源：http://dali.jlsjyb.cn/Article/details/gthjcnzrev.html

[G12] 对象转字符串
来源：http://dali.redwolf501.top/Article/details/gtcncodsqx.html

Py:   def __str__(self): return self.name
来源：http://dali.sysykeji.top/Article/details/gthlzrtglm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtqemdgjhp.html

JS:   toString() { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtkjehwykd.html

TS:   toString(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtacbkxjpc.html

Java: @Override public String toString() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtahypmrgb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gtpdwgqetj.html

Ruby: def to_s; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtklvqfdgw.html

C#:   public override string ToString() => Name;
来源：http://dali.zycfv.cn/Article/details/gtfcnhmzea.html

[G13] 判断对象类型
来源：http://dali.jlsjyb.cn/Article/details/gtaoagjlvh.html

Py:   isinstance(u, User)
来源：http://dali.gaohongyu789.top/Article/details/gtbzmngxrr.html

PHP:  $u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtyquziabf.html

JS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtulfikdwp.html

TS:   u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtlhvsvlkp.html

Java: u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gteqmkuuru.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xinyue.icu/Article/details/gtitwypboa.html

Ruby: u.is_a?(User)
来源：http://dali.feifeiyinyue.top/Article/details/gtjwwunhkr.html

C#:   u is User
来源：http://dali.jiagoushi.top/Article/details/gtozeaylkb.html

[G14] 数据类 / record
来源：http://dali.jiagoushi.top/Article/details/gtfdebwrqs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj202588.top/Article/details/gtcgthluar.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yongpay.top/Article/details/gtujzmcbou.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cashguo.top/Article/details/gtxvqhvabo.html

TS:   type User = { name: string; age: number };
来源：http://dali.kuanghao11.cn/Article/details/gtxizdnysk.html

Java: record User(String name, int age) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtixwxmjla.html

Go:   type User struct { Name string; Age int }
来源：http://dali.kuanghao11.cn/Article/details/gtsanpnnqj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhongyouzk.top/Article/details/gtdfiufeen.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigfzy.top/Article/details/gtrhagyzjv.html

[G15] 枚举
来源：http://dali.wangshuangyany.cn/Article/details/gtgkukwtoi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtawuaobbg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinqigufen.top/Article/details/gtgzmkyvgz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daxiang520.top/Article/details/gtjkvdlbsz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gtltkxskmb.html

Java: enum Color { RED, GREEN }
来源：http://dali.fzhhl.top/Article/details/gtxynfbmcm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.aibaodan.cn/Article/details/gtnzjrcoon.html

Ruby: Color = %i[red green].freeze
来源：http://dali.smart0.xyz/Article/details/gttajkeyiz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guannengcc.top/Article/details/gtuakjnuvw.html

[G16] 对象转数组 / 字典
来源：http://dali.kuanghao11.cn/Article/details/gtikviatuo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sweek.top/Article/details/gtmkjiyiic.html

PHP:  get_object_vars($obj);
来源：http://dali.yuxming.cn/Article/details/gtcddbqdna.html

JS:   Object.entries(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtmwfugdse.html

TS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtvclxtlou.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yonumen.top/Article/details/gtlhwqpgzc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cashguo.top/Article/details/gtouujnptj.html

Ruby: obj.instance_variables
来源：http://dali.shzxlz.cn/Article/details/gtuohkqjxt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gtockfpziw.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtibmqaalo.html

H. 异常与错误处理
来源：http://dali.sufxvd.cn/Article/details/gtroobaajo.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtcfezducc.html

[H01] try / catch 基础
来源：http://dali.jyoumei.cn/Article/details/gtzaokfcfy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.redwolf501.top/Article/details/gtcnwqsbba.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.c1oappe.top/Article/details/gtwcxarnzx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gtuhrjweji.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gtdlcjjxlo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sxryk.cn/Article/details/gtwlthyjuq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gtasyyuxwl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jyoumei.cn/Article/details/gtbrsszzyk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.c1oappe.top/Article/details/gtaxdwzwie.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangtech.top/Article/details/gttwqxumop.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangshuangyany.cn/Article/details/gtjeqmvtoz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtqammkbhe.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtveexgnsx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtmkdrmgxj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtifreeorp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gotoacloud.top/Article/details/gturvewvci.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nwbrower.top/Article/details/gtnjwynpfs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cashguo.top/Article/details/gteheqpkfq.html

[H03] 主动抛出异常
来源：http://dali.yj202588.top/Article/details/gtmhcuilvs.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuanzhike.top/Article/details/gthrkelxdc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtgyipvtha.html

JS:   throw new Error("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtmegdkvny.html

TS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtbmvfmxws.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtdailpdym.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj202588.top/Article/details/gtwocnchpp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.snrcjt.cn/Article/details/gtyuyunowr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtdmnpxigw.html

[H04] 自定义异常类型
来源：http://dali.xinyue.icu/Article/details/gtsxhzatdy.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258888.top/Article/details/gttsswyqeh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gtopwypmuv.html

JS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gtzpsxabgb.html

TS:   class MyError extends Error {}
来源：http://dali.hongshengwenyu.top/Article/details/gtqgzurjro.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtgdxecubc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yongpay.top/Article/details/gttjtxvduw.html

Ruby: class MyError < StandardError; end
来源：http://dali.hongshengwenyu.top/Article/details/gtsitgtycn.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigufen.top/Article/details/gtrfotvzjc.html

[H05] 捕获特定类型
来源：http://dali.316326.xyz/Article/details/gtodeeibjt.html

Py:   except ValueError as e:
来源：http://dali.ydzc1.top/Article/details/gtfokppbes.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cheryme.top/Article/details/gtkctivogq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tian-w.cn/Article/details/gtlfyaidiu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.vqdsnc.cn/Article/details/gtdcmtksbs.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.9152youxi.cn/Article/details/gteasvidpy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.havefunace.top/Article/details/gtsmfpydme.html

Ruby: rescue ArgumentError => e
来源：http://dali.ehwqpu.com/Article/details/gtueaghtxx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.meibo888.top/Article/details/gtieqxehlw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hongshengwenyu.top/Article/details/gtwgqrxmsz.html

Py:   value = d.get("k") or default
来源：http://dali.jqgfzy.top/Article/details/gtfngmkkjs.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hammf.cn/Article/details/gtwvdkxzgf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shuidangran.top/Article/details/gtftmsayct.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gtqfnuflji.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shangyingyoupin.top/Article/details/gtlwaxpfjy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.redwolf501.top/Article/details/gtjsteihvz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cucudq.cn/Article/details/gtkmwjyhub.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhoulong.xyz/Article/details/gtcawngekt.html

[H07] 断言
来源：http://dali.chenjidiqi.icu/Article/details/gtkaivizok.html

Py:   assert x > 0, "必须为正"
来源：http://dali.c1oappe.top/Article/details/gtnsnjdtwi.html

PHP:  assert($x > 0);
来源：http://dali.daria6918.cn/Article/details/gtdqqjabqk.html

JS:   console.assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gtfmbdmyuz.html

TS:   console.assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtezxniffc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shuidangran.top/Article/details/gtizlgwbqh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sxryk.cn/Article/details/gtcnywrzuk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ybcxt.top/Article/details/gtgjbnbgyp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gtqqwurmdf.html

[H08] 获取错误信息与堆栈
来源：http://dali.hywenlv.cn/Article/details/gtxwkdgiwi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cheryme.top/Article/details/gtelukjolz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gtnmohjzbz.html

JS:   e.message;  e.stack
来源：http://dali.gzhubu.top/Article/details/gtrugjekho.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sxryk.cn/Article/details/gtcbmkclor.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhiwuduotai.top/Article/details/gtgzldgnjo.html

Go:   err.Error()
来源：http://dali.fzhhl.top/Article/details/gtkdvwphye.html

Ruby: e.message;  e.backtrace
来源：http://dali.fzhhl.top/Article/details/gtoxsojhtf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.quarkkingdee.top/Article/details/gtwsygcusj.html

[H09] 带错误码的异常
来源：http://dali.yvedp.cn/Article/details/gtarvpwwgv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pycfn.com/Article/details/gtghchjkom.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xylfe.cn/Article/details/gtaiwkrcdl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jyoumei.cn/Article/details/gtushfycdp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ydzc1.top/Article/details/gtfrxmrvrp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jlsjyb.cn/Article/details/gtavttlsrq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xinyue.icu/Article/details/gtylzcbowc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj20258.top/Article/details/gtnbugejcr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwxzkqpe.html

[H10] 资源自动释放
来源：http://dali.ivvv.top/Article/details/gtuckugyyz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daria6918.cn/Article/details/gtgjdfbous.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hfpthk.cn/Article/details/gtzvpopgmo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xylfe.cn/Article/details/gtkrakgvkz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gtqstzoeck.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.kuanghao11.cn/Article/details/gthjllmhwx.html

Go:   defer f.Close()
来源：http://dali.cdnleiting.top/Article/details/gtzpdytvch.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zycfv.cn/Article/details/gtqfcqfhch.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtrwszotsp.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtsjjncalq.html

I. 正则表达式
来源：http://dali.feifeiyinyue.top/Article/details/gtfayygltq.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtrmqvldyr.html

[I01] 判断是否匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwwpbbzsy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ivvv.top/Article/details/gtjcioogqg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtoagkqmpa.html

JS:   /\d+/.test(s)
来源：http://dali.snrcjt.cn/Article/details/gtjuityjga.html

TS:   /\d+/.test(s)
来源：http://dali.yueranfly.top/Article/details/gtlymzcroz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ydzc1.top/Article/details/gtxjsewkqt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258888.top/Article/details/gtdipyrczw.html

Ruby: s.match?(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gtypdxpfqc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xylfe.cn/Article/details/gtyeydgtve.html

[I02] 提取所有匹配
来源：http://dali.tianlin.xyz/Article/details/gtjflzegqy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hnqzz.top/Article/details/gtaqcgbphu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.guannengcc.top/Article/details/gtnkbkvvut.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cheryme.top/Article/details/gtusvvwvvo.html

TS:   s.match(/\d+/g)
来源：http://dali.cucudq.cn/Article/details/gtehjzxedk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenzaomai.com/Article/details/gtggilrmfj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ivvv.top/Article/details/gtefgicoth.html

Ruby: s.scan(/\d+/)
来源：http://dali.svipenyu.cn/Article/details/gttagaxvdc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.mhx1999.top/Article/details/gtgfayxjob.html

[I03] 提取捕获分组
来源：http://dali.yuxming.cn/Article/details/gtfqoarzth.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgufenzy.top/Article/details/gtffytixcm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtkqxbxtdl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangshuangyany.cn/Article/details/gttwavtubt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.dashuyun.cn/Article/details/gtfzhspvuk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jlsjyb.cn/Article/details/gtepowegzx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hywenlv.cn/Article/details/gtjplcrcgo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.andypj.xyz/Article/details/gtkmfwbxvw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.feifeiyinyue.top/Article/details/gttcrwrjic.html

[I04] 正则替换
来源：http://dali.haohaochexian.top/Article/details/gtyizbzwfm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.daxiang520.top/Article/details/gtyhdpsrtq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sysykeji.top/Article/details/gtkqfhddbr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yongpay.top/Article/details/gtvjntqiey.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ybcxt.top/Article/details/gtrvvassfq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.daxiang520.top/Article/details/gtatzjruaw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zdqjudy.top/Article/details/gtijnqbasv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtiiyuuixk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.fengsongda.top/Article/details/gtougiclva.html

[I05] 按正则拆分
来源：http://dali.shangyingyoupin.top/Article/details/gtcelqcbpx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.andypj.xyz/Article/details/gtgdpxrywl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbysqwvy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gtgiomxdqg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gtwalegfdp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hnqzz.top/Article/details/gtdseqrinv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gtrvnppfxu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gtwhhqvhov.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cheryme.top/Article/details/gtcihbskdz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yueranfly.top/Article/details/gtegpxonor.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gtvccqtzxn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yongpay.top/Article/details/gteihionjq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pengpengdd.cyou/Article/details/gtbloxzmos.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.snrcjt.cn/Article/details/gtfktezwni.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gtdhyatarc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yongpay.top/Article/details/gtdapigagr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.smart0.xyz/Article/details/gtfufqjvlj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gtehmfmobm.html

[I07] 忽略大小写与多行模式
来源：http://dali.bjfxy.top/Article/details/gtukwszfew.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.haohaochexian.top/Article/details/gtbjkxnwyi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tanke756.top/Article/details/gtldxkuqfv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtisusbmxp.html

TS:   /error/gim
来源：http://dali.dashuyun.cn/Article/details/gtjuvgrjgx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sysykeji.top/Article/details/gtzkzgpnut.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nanxinkj.top/Article/details/gtmuncgfnj.html

Ruby: s.scan(/error/i)
来源：http://dali.dianchejie.cn/Article/details/gtwcgolasx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yonumen.top/Article/details/gthvgxlaoi.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shuidangran.top/Article/details/gtviblzgtt.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jqgufenzy.top/Article/details/gtxapdgeox.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.dashuyun.cn/Article/details/gtxwibjccx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ivvv.top/Article/details/gtdafrgcqr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cucudq.cn/Article/details/gtjgxkucbx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.snrcjt.cn/Article/details/gtzalusfsl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jqgufenzy.top/Article/details/gtjykpwhsy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.quarkkingdee.top/Article/details/gtskwhrcqj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sufxvd.cn/Article/details/gtwkmxixhb.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gthahxwqrr.html

J. 日期与时间
来源：http://dali.haohaochexian.top/Article/details/gtqudflqoo.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtzhjazmne.html

[J01] 获取当前时间
来源：http://dali.birdmap.top/Article/details/gtitpbpkii.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.guowangkeji.top/Article/details/gtrcdntudp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gtmkfmarwi.html

JS:   new Date();  Date.now()
来源：http://dali.cashguo.top/Article/details/gtutjlbfgn.html

TS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gtfthvjbms.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xuetiantiany.cn/Article/details/gtbzbllist.html

Go:   time.Now()
来源：http://dali.chenlongwang.top/Article/details/gtnmphgxgi.html

Ruby: Time.now
来源：http://dali.hfpthk.cn/Article/details/gtnafzudma.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhongyouzk.top/Article/details/gtgkvofcns.html

[J02] 格式化输出
来源：http://dali.hnxiangtu.top/Article/details/gtaoyndgib.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yongpay.top/Article/details/gtlehdjxpq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.c1oappe.top/Article/details/gtqrykmvne.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.snrcjt.cn/Article/details/gtivshenve.html

TS:   d.toISOString()
来源：http://dali.ehwqpu.com/Article/details/gtwhjrojxd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jyoumei.cn/Article/details/gtyzttxxhx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.9152youxi.cn/Article/details/gtdiesrevt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gtiapznqud.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shangyingyoupin.top/Article/details/gtgwcyuxtr.html

[J03] 字符串解析为日期
来源：http://dali.wangdashe.top/Article/details/gtkvmexzyu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.9152youxi.cn/Article/details/gtnvrswssd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tanke756.top/Article/details/gtflxurwqh.html

JS:   new Date("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtkxtxbgcz.html

TS:   new Date("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtifgzwolh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrhlmmghs.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtnkhoqdgp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtlztdhnpu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gaohongyu789.top/Article/details/gtpigmbifi.html

[J04] 时间戳与日期互转
来源：http://dali.hammf.cn/Article/details/gtcsgxhzex.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shzxlz.cn/Article/details/gtwzxvrjzn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cdnleiting.top/Article/details/gtftwjqoqv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtezowcjzu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.meibo888.top/Article/details/gtbwpwujmn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.wangdashe.top/Article/details/gtpqaspiqf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtswdmfykx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinqigfzy.top/Article/details/gtsqchxzoh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sufxvd.cn/Article/details/gtanbvcdvh.html

[J05] 时间加减（加 7 天）
来源：http://dali.iojbl.cn/Article/details/gtmbuavvzv.html

Py:   now + timedelta(days=7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycoehicc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhoulong.xyz/Article/details/gtodntkvhr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gtbyjrrino.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dashuyun.cn/Article/details/gtrbnjstua.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoktkravm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gogol.net.cn/Article/details/gtxzygzkla.html

Ruby: Time.now + 7 * 86400
来源：http://dali.0kj1m.cn/Article/details/gtfjepxrai.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hongshengwenyu.top/Article/details/gtvberdyyo.html

[J06] 计算两时间之差
来源：http://dali.pycfn.com/Article/details/gtekqcehsm.html

Py:   (end - start).total_seconds()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsboekupm.html

PHP:  $end->diff($start)->days;
来源：http://dali.cdnleiting.top/Article/details/gtthezscnj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cashguo.top/Article/details/gtgqqljile.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cucudq.cn/Article/details/gttbcytuco.html


<!-- 参考信息 -->