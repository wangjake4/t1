代发 wailian999

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nanxuanxn.top/Article/details/gtilghkvqb.html

Ruby: def self.f; end
来源：http://dali.feifeiyinyue.top/Article/details/gtzkgyojvw.html

C#:   public static void F() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbblvflb.html

[G09] 接口 / 抽象类
来源：http://dali.svipenyu.cn/Article/details/gtvujgkjfe.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yangfankeji.com/Article/details/gtcczygxwt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zdqjudy.top/Article/details/gthbaggsff.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.aizwys.cn/Article/details/gtonxnoclg.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gtprzftbnc.html

Java: interface Shape { double area(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqyrjodc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.aizwys.cn/Article/details/gtxdsszwcy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xinyue.icu/Article/details/gthelxvfzk.html

C#:   interface IShape { double Area(); }
来源：http://dali.xylfe.cn/Article/details/gtrtwvllfr.html

[G10] 访问控制
来源：http://dali.smart0.xyz/Article/details/gtcdlmulbu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sysykeji.top/Article/details/gthpwbpmhy.html

PHP:  public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gtqygejmlv.html

JS:   #private 字段；其余公开
来源：http://dali.guowangkeji.top/Article/details/gtymowakmo.html

TS:   public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gthmfxihiz.html

Java: public / protected / private / 默认包级
来源：http://dali.hnqzz.top/Article/details/gtlslxrmha.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.haohaochexian.top/Article/details/gtyzoegbog.html

Ruby: public / protected / private
来源：http://dali.redwolf501.top/Article/details/gtyjtrazgh.html

C#:   public / protected / private / internal
来源：http://dali.xuanzx.com/Article/details/gtifwvuumu.html

[G11] getter / setter
来源：http://dali.tanke756.top/Article/details/gtcjfummlh.html

Py:   @property 与 @x.setter
来源：http://dali.cucudq.cn/Article/details/gtjbhlbfxi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtpbdjqiiv.html

JS:   get name() { return this._name; }
来源：http://dali.shzxlz.cn/Article/details/gtmwiukkmq.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gtkfwlhcyz.html

Java: public String getName() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtjbftfmzc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gtevxszunu.html

Ruby: attr_accessor :name
来源：http://dali.nanxuanxn.top/Article/details/gtdqntxiug.html

C#:   public string Name { get; set; }
来源：http://dali.quarkkingdee.top/Article/details/gthwcdxjrj.html

[G12] 对象转字符串
来源：http://dali.jlsjyb.cn/Article/details/gtjvpyqeoq.html

Py:   def __str__(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gtwkgswglc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gtmhrmilie.html

JS:   toString() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtqcwleadr.html

TS:   toString(): string { return this.name; }
来源：http://dali.316326.xyz/Article/details/gtbpntoamj.html

Java: @Override public String toString() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtnkpttghj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gtrknacvys.html

Ruby: def to_s; @name; end
来源：http://dali.pycfn.com/Article/details/gtsibkcgjw.html

C#:   public override string ToString() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gtysyovbae.html

[G13] 判断对象类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlsfrtaht.html

Py:   isinstance(u, User)
来源：http://dali.yongpay.top/Article/details/gtpbysexgx.html

PHP:  $u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtethdgozw.html

JS:   u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gteqkusghm.html

TS:   u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gtnlgmvsct.html

Java: u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtmrhwkqwq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jyoumei.cn/Article/details/gtgpphkppg.html

Ruby: u.is_a?(User)
来源：http://dali.daria6918.cn/Article/details/gtdjvtogif.html

C#:   u is User
来源：http://dali.dashuyun.cn/Article/details/gtbiymipbo.html

[G14] 数据类 / record
来源：http://dali.sufxvd.cn/Article/details/gtpbnufmjh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gaohongyu789.top/Article/details/gttkqysqbi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ybcxt.top/Article/details/gtxnmlnqzn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xziqi.cn/Article/details/gtmsjukjho.html

TS:   type User = { name: string; age: number };
来源：http://dali.sysykeji.top/Article/details/gteocpdxgv.html

Java: record User(String name, int age) {}
来源：http://dali.ivvv.top/Article/details/gtepikdhvn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tianlin.xyz/Article/details/gtriuzglhy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.vqdsnc.cn/Article/details/gtyrbdjyqq.html

C#:   record User(string Name, int Age);
来源：http://dali.yangfankeji.com/Article/details/gtfjwcvtbv.html

[G15] 枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gthfvtgshy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnxiangtu.top/Article/details/gtznowaqwf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cqqwz.cn/Article/details/gtchabowgq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.haohaochexian.top/Article/details/gtcvzynvsd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gtkupuuucx.html

Java: enum Color { RED, GREEN }
来源：http://dali.cucudq.cn/Article/details/gtjdepwyep.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhxcjupi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenjidiqi.icu/Article/details/gtlikizxnf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hfpthk.cn/Article/details/gthhzqiaxk.html

[G16] 对象转数组 / 字典
来源：http://dali.gaohongyu789.top/Article/details/gtyxltvhpw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.redwolf501.top/Article/details/gtrspxjndp.html

PHP:  get_object_vars($obj);
来源：http://dali.birdmap.top/Article/details/gtztenvjzn.html

JS:   Object.entries(obj)
来源：http://dali.ivvv.top/Article/details/gtzbgckuhx.html

TS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gtlzkdmbaf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shuidangran.top/Article/details/gteqhpachp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgfzy.top/Article/details/gtjaxddsjq.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gtlulbrocb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ivvv.top/Article/details/gtqigbnloo.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtkfdoetur.html

H. 异常与错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvpabkkea.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtedocxrhj.html

[H01] try / catch 基础
来源：http://dali.jianghu66.top/Article/details/gtzqvrbbxe.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ybcxt.top/Article/details/gtvdncqmrg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigufen.top/Article/details/gtaoaycare.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtezsoelkl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgolggsff.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cqqwz.cn/Article/details/gtzizwgduo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hywenlv.cn/Article/details/gtaavphuvi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.kuanghao11.cn/Article/details/gtmmvqqufj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shzxlz.cn/Article/details/gtgqmlcbrb.html

[H02] finally / ensure 收尾
来源：http://dali.birdmap.top/Article/details/gtfwmvefmc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.svipenyu.cn/Article/details/gtkngrrxkz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtqzxirsfb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtymelovoy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtrjddoruy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtaqmtacxz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvoacimk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangshuangyany.cn/Article/details/gtetqtizbm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtmbnfofkh.html

[H03] 主动抛出异常
来源：http://dali.gaohongyu789.top/Article/details/gtzseljmcg.html

Py:   raise ValueError("错误信息")
来源：http://dali.smart0.xyz/Article/details/gtkogkfldj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtaaunzuzw.html

JS:   throw new Error("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtsybgrmem.html

TS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtuoqpopon.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtjuujofvp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.0kj1m.cn/Article/details/gtzywragli.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gaohongyu789.top/Article/details/gtzuokbsuj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtqzxfgyhu.html

[H04] 自定义异常类型
来源：http://dali.jyoumei.cn/Article/details/gtxzxpdzas.html

Py:   class MyError(Exception): pass
来源：http://dali.fzhhl.top/Article/details/gtzlpsszql.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gtomptdamd.html

JS:   class MyError extends Error {}
来源：http://dali.gogol.net.cn/Article/details/gtjnznqcjx.html

TS:   class MyError extends Error {}
来源：http://dali.shangyingyoupin.top/Article/details/gtxtlsyxhg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gtllelzzzu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.snrcjt.cn/Article/details/gtbssugabm.html

Ruby: class MyError < StandardError; end
来源：http://dali.hnqzz.top/Article/details/gtiswpumqk.html

C#:   class MyException : Exception {}
来源：http://dali.xziqi.cn/Article/details/gtgxppxurz.html

[H05] 捕获特定类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyygsrqlj.html

Py:   except ValueError as e:
来源：http://dali.yanxiufei.cn/Article/details/gtuhdkrhdx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.smart0.xyz/Article/details/gtuadfqmdo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yanxiufei.cn/Article/details/gtkulhpblx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jqgufenzy.top/Article/details/gtrmsknsfy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.quarkkingdee.top/Article/details/gtlhmgwthk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnlnbkei.html

Ruby: rescue ArgumentError => e
来源：http://dali.daria6918.cn/Article/details/gtdtqxbtim.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jiagoushi.top/Article/details/gtjpkjhxzu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yanxiufei.cn/Article/details/gtaoylpmzg.html

Py:   value = d.get("k") or default
来源：http://dali.jlsjyb.cn/Article/details/gthwxeziub.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gttoglwgxf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hysaishi.cn/Article/details/gtsccxojmj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuanzx.com/Article/details/gtqcktqrmj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ppjwa.cn/Article/details/gtrcfdnxlt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj20258.top/Article/details/gtjkchafmz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jiagoushi.top/Article/details/gtbtuxptrj.html

C#:   obj?.A?.B ?? default
来源：http://dali.xziqi.cn/Article/details/gtywsprzau.html

[H07] 断言
来源：http://dali.yongpay.top/Article/details/gtwzuqbnox.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hfpthk.cn/Article/details/gtffrqazqv.html

PHP:  assert($x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtxjldzhbe.html

JS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gtkmjkahpf.html

TS:   console.assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtcqponaqf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.c1oappe.top/Article/details/gtoudqiwyf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangshuangyany.cn/Article/details/gtyrmddygk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyhkgsoog.html

C#:   Debug.Assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gtgaoitrzt.html

[H08] 获取错误信息与堆栈
来源：http://dali.ppjwa.cn/Article/details/gtsvuovjho.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuanzhike.top/Article/details/gttdxztcyt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yuxming.cn/Article/details/gtwzkfhijo.html

JS:   e.message;  e.stack
来源：http://dali.ehwqpu.com/Article/details/gtmlbqrcsw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yonumen.top/Article/details/gtfuuggcys.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cashguo.top/Article/details/gtgnmbxcym.html

Go:   err.Error()
来源：http://dali.daria6918.cn/Article/details/gtdcrrcxmz.html

Ruby: e.message;  e.backtrace
来源：http://dali.daria6918.cn/Article/details/gtcbzbhipp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenzaomai.com/Article/details/gtzzugpujc.html

[H09] 带错误码的异常
来源：http://dali.xuetiantiany.cn/Article/details/gtpezzrmgz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenzaomai.com/Article/details/gtievlqxlb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.quarkkingdee.top/Article/details/gtpkwxicro.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nanxinkj.top/Article/details/gtvztgxtgj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yvedp.cn/Article/details/gtzopqexbf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.smart0.xyz/Article/details/gtpofycpmm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shzxlz.cn/Article/details/gtikzijusg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj202588.top/Article/details/gtwjhbkoph.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shanyushiyangtech.top/Article/details/gtdrygprvd.html

[H10] 资源自动释放
来源：http://dali.nanxuanxn.top/Article/details/gtsirezweo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.c1oappe.top/Article/details/gtmxkapvdn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yuanzhike.top/Article/details/gtfbcalcem.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hfpthk.cn/Article/details/gtqhdfonqt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258.top/Article/details/gtphmvbesf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shangyingyoupin.top/Article/details/gtumihpsly.html

Go:   defer f.Close()
来源：http://dali.xuetiantiany.cn/Article/details/gtsrhenbyf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ydzc1.top/Article/details/gtmezdmzac.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtibmjmofo.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwyyzpvbv.html

I. 正则表达式
来源：http://dali.zhixingplan.top/Article/details/gtqeqtsmkr.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtswfwujbz.html

[I01] 判断是否匹配
来源：http://dali.aizwys.cn/Article/details/gtzmcduqnd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.meibo888.top/Article/details/gtlyltmbty.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtoqemqnfq.html

JS:   /\d+/.test(s)
来源：http://dali.jyoumei.cn/Article/details/gtasutgdhs.html

TS:   /\d+/.test(s)
来源：http://dali.jinqigfzy.top/Article/details/gtniwnchrp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinqigufen.top/Article/details/gtguwvnudg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhoulong.xyz/Article/details/gtkxtxxxfd.html

Ruby: s.match?(/\d+/)
来源：http://dali.hnxiangtu.top/Article/details/gtujganynt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnqzz.top/Article/details/gtpyowmoxm.html

[I02] 提取所有匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtvxxgzpsi.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ybcxt.top/Article/details/gtznrdzarv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gogol.net.cn/Article/details/gtykmmuscl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cheryme.top/Article/details/gtzorehhdl.html

TS:   s.match(/\d+/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gtygkyhemo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nanxinkj.top/Article/details/gttyjxiypn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.c1oappe.top/Article/details/gtjcojaqxm.html

Ruby: s.scan(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gtuzzaqsfp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ybcxt.top/Article/details/gtypbqtfrr.html

[I03] 提取捕获分组
来源：http://dali.aizwys.cn/Article/details/gtovrfidiu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.snrcjt.cn/Article/details/gthattemgu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jyoumei.cn/Article/details/gtxccgzumq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gtdzdtqwwi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nanxinkj.top/Article/details/gtdukesota.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhoulong.xyz/Article/details/gtlzughwxc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhaomingkeji.xyz/Article/details/gtptkdzmtm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinqigfzy.top/Article/details/gtvfylsprg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.iojbl.cn/Article/details/gtinoncngs.html

[I04] 正则替换
来源：http://dali.shzxlz.cn/Article/details/gtmgijwqtf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinqigufen.top/Article/details/gtflxxgetf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtidzaxaxd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gttcdqvcgc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xinyue.icu/Article/details/gtjfeyxkfu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zdqjudy.top/Article/details/gtbgsuupja.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yuanzhike.top/Article/details/gtwpmkmxdv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hfpthk.cn/Article/details/gtneebidmq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.meibo888.top/Article/details/gtdgwfwloi.html

[I05] 按正则拆分
来源：http://dali.havefunace.top/Article/details/gtnxksiqus.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gzhubu.top/Article/details/gtnmajmwwh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtxkmoveuf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gtejgvxjzv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gtkvblbhee.html

Java: s.split("\\s*,\\s*")
来源：http://dali.bjfxy.top/Article/details/gtfozhjenz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jianghu66.top/Article/details/gtjkdxjpbl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gtvwrwcakn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenzaomai.com/Article/details/gtvxlwrgcc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hnxiangtu.top/Article/details/gtfzcvfffk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tanke756.top/Article/details/gtdxvuzxvm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.wangdashe.top/Article/details/gtbhhrdmgt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.0kj1m.cn/Article/details/gtqhpynqdm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zdqjudy.top/Article/details/gtmadvzncf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gtjpvhqsjm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcejfjppv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.havefunace.top/Article/details/gtfuuoolqm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yonumen.top/Article/details/gtfardvyzl.html

[I07] 忽略大小写与多行模式
来源：http://dali.tanke756.top/Article/details/gtfagutaeb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.316326.xyz/Article/details/gtlmudqzrf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.aibaodan.cn/Article/details/gtbfkuxfoo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xuetiantiany.cn/Article/details/gthyfmktua.html

TS:   /error/gim
来源：http://dali.yonumen.top/Article/details/gtgzqueeec.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinqigufen.top/Article/details/gtfroatqko.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ivvv.top/Article/details/gtuarvxeqd.html

Ruby: s.scan(/error/i)
来源：http://dali.jiagoushi.top/Article/details/gttubnbmzb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shuidangran.top/Article/details/gtsrbkjwyd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ehwqpu.com/Article/details/gtznhdbiix.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinqigfzy.top/Article/details/gtlsmrmkep.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.wangdashe.top/Article/details/gtovxywlng.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gtgykatdwe.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkjdghiuw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cheryme.top/Article/details/gtspppuaxt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gtoyejmmym.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgfzy.top/Article/details/gtxxqkblog.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jyoumei.cn/Article/details/gttibzhzkj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtsywypajm.html

J. 日期与时间
来源：http://dali.hywenlv.cn/Article/details/gtzrzyeczq.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtwudvomxl.html

[J01] 获取当前时间
来源：http://dali.0kj1m.cn/Article/details/gtfepqzzwz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sysykeji.top/Article/details/gtjpwotenh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.tian-w.cn/Article/details/gtnzxbefkw.html

JS:   new Date();  Date.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gtejuneawo.html

TS:   new Date();  Date.now()
来源：http://dali.tanke756.top/Article/details/gtxrrduhuz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sweek.top/Article/details/gtarzowoef.html

Go:   time.Now()
来源：http://dali.chenlongwang.top/Article/details/gtosxcmrwq.html

Ruby: Time.now
来源：http://dali.hywenlv.cn/Article/details/gtsjehiohp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.bjfxy.top/Article/details/gtmsmptmgo.html

[J02] 格式化输出
来源：http://dali.guannengcc.top/Article/details/gtxkkesvea.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jlsjyb.cn/Article/details/gtqxthvouk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gtoetsgvfu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shzxlz.cn/Article/details/gtaxcrrmyx.html

TS:   d.toISOString()
来源：http://dali.gzhubu.top/Article/details/gtsdauyglv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yonumen.top/Article/details/gttpbnwxii.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nwbrower.top/Article/details/gtaqvfolcx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzofrgod.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.wangdashe.top/Article/details/gtoekbupuv.html

[J03] 字符串解析为日期
来源：http://dali.chenjidiqi.icu/Article/details/gtescwsssn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hongshengwenyu.top/Article/details/gthrjlczax.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xylfe.cn/Article/details/gtreszslqv.html

JS:   new Date("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtsvbndssn.html

TS:   new Date("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtpmyyiyxd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtmhdnmgtv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtwsasyhrr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtlyhiozur.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.smart0.xyz/Article/details/gtnedhcmsh.html

[J04] 时间戳与日期互转
来源：http://dali.bjfxy.top/Article/details/gtmbvonvcn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tian-w.cn/Article/details/gtlbvybhtx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.aibaodan.cn/Article/details/gtebsjkzta.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.guowangkeji.top/Article/details/gtzyvfvhjl.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnzcuiqqn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yuxming.cn/Article/details/gtrxdzaopk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangdashe.top/Article/details/gtluarcoof.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yuxming.cn/Article/details/gtinfhmrqm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gogol.net.cn/Article/details/gtgavyyfor.html

[J05] 时间加减（加 7 天）
来源：http://dali.ehwqpu.com/Article/details/gtjzxxafes.html

Py:   now + timedelta(days=7)
来源：http://dali.tianlin.xyz/Article/details/gtsbbiubaz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yanxiufei.cn/Article/details/gtxhetvged.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gtesdtxguq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gtylvdsssc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gogol.net.cn/Article/details/gtshuatiwu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hongshengwenyu.top/Article/details/gtenezmrba.html

Ruby: Time.now + 7 * 86400
来源：http://dali.andypj.xyz/Article/details/gtiqaaozni.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daxiang520.top/Article/details/gtfbuzsiwb.html

[J06] 计算两时间之差
来源：http://dali.cucudq.cn/Article/details/gtdnyfqhzc.html

Py:   (end - start).total_seconds()
来源：http://dali.9152youxi.cn/Article/details/gtsfbzfetu.html

PHP:  $end->diff($start)->days;
来源：http://dali.tanke756.top/Article/details/gtxrliowuu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhongyouzk.top/Article/details/gtygimejut.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sweek.top/Article/details/gtcrwjhegm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yongpay.top/Article/details/gtsdzjjimk.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenzaomai.com/Article/details/gtpvwfpyyt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ivvv.top/Article/details/gtiwuegibc.html

C#:   (end - start).TotalSeconds
来源：http://dali.gogol.net.cn/Article/details/gtgcjjldly.html


<!-- 参考信息 -->