代发 wailian999

Py:   from abc import ABC, abstractmethod
来源：http://dali.sweek.top/Article/details/gt2ogmnqzux.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hammf.cn/Article/details/gt2jnargcll.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cqqwz.cn/Article/details/gt2urqxnuoy.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kqnogliq.html

Java: interface Shape { double area(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2bzbboxcq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hywenlv.cn/Article/details/gt2wlhpzstw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gotoacloud.top/Article/details/gt2wyuojvbi.html

C#:   interface IShape { double Area(); }
来源：http://dali.meibo888.top/Article/details/gt2qdoewoxj.html

[G10] 访问控制
来源：http://dali.hywenlv.cn/Article/details/gt2axuubjow.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cucudq.cn/Article/details/gt2vmanxwgy.html

PHP:  public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gt2gyqrebjz.html

JS:   #private 字段；其余公开
来源：http://dali.snrcjt.cn/Article/details/gt2zodakbza.html

TS:   public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gt2dvqwvkve.html

Java: public / protected / private / 默认包级
来源：http://dali.hfpthk.cn/Article/details/gt2bvggvwzp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhiwuduotai.top/Article/details/gt2eqqapdrl.html

Ruby: public / protected / private
来源：http://dali.cheryme.top/Article/details/gt2slhpxcrz.html

C#:   public / protected / private / internal
来源：http://dali.fzhhl.top/Article/details/gt2azykqcsi.html

[G11] getter / setter
来源：http://dali.ybcxt.top/Article/details/gt2fcuqioql.html

Py:   @property 与 @x.setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zapvdsyt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gt2resqekgq.html

JS:   get name() { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2eldhaefn.html

TS:   get name(): string { return this._name; }
来源：http://dali.aizwys.cn/Article/details/gt2rclghare.html

Java: public String getName() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2cccjtlol.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gt2mdtgjibh.html

Ruby: attr_accessor :name
来源：http://dali.ppjwa.cn/Article/details/gt2zwubocvy.html

C#:   public string Name { get; set; }
来源：http://dali.svipenyu.cn/Article/details/gt2ibqisqip.html

[G12] 对象转字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2uqpouywm.html

Py:   def __str__(self): return self.name
来源：http://dali.aibaodan.cn/Article/details/gt2rxmxxkie.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gt2xhcwatll.html

JS:   toString() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gt2frmnkxib.html

TS:   toString(): string { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gt2lvpryiih.html

Java: @Override public String toString() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fbiqejsx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gt2lxrpxfgp.html

Ruby: def to_s; @name; end
来源：http://dali.zhongyouzk.top/Article/details/gt2pjndncgy.html

C#:   public override string ToString() => Name;
来源：http://dali.ehwqpu.com/Article/details/gt2arwdfbtv.html

[G13] 判断对象类型
来源：http://dali.nanxuanxn.top/Article/details/gt2hdblrrlq.html

Py:   isinstance(u, User)
来源：http://dali.smart0.xyz/Article/details/gt2dhdlxwxj.html

PHP:  $u instanceof User
来源：http://dali.daria6918.cn/Article/details/gt2kuibejqf.html

JS:   u instanceof User
来源：http://dali.yj20258.top/Article/details/gt2bzaifwho.html

TS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gt2nlloimiu.html

Java: u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gt2hdxamngj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gotoacloud.top/Article/details/gt2gtejyymr.html

Ruby: u.is_a?(User)
来源：http://dali.nanxuanxn.top/Article/details/gt2iguorbop.html

C#:   u is User
来源：http://dali.aibaodan.cn/Article/details/gt2wgcpwcwu.html

[G14] 数据类 / record
来源：http://dali.shangyingyoupin.top/Article/details/gt2kccemqnf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sxryk.cn/Article/details/gt2zxifvjod.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jyoumei.cn/Article/details/gt2vvwgfnnu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daria6918.cn/Article/details/gt2njjghror.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhiwuduotai.top/Article/details/gt2cegpuqgj.html

Java: record User(String name, int age) {}
来源：http://dali.zhengqikj.top/Article/details/gt2qmibusvn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.9152youxi.cn/Article/details/gt2ytbdeewm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sxryk.cn/Article/details/gt2stjehibo.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258.top/Article/details/gt2cwfyxkhy.html

[G15] 枚举
来源：http://dali.nwbrower.top/Article/details/gt2bryoilsi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.bjfxy.top/Article/details/gt2jdkiszev.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhixingplan.top/Article/details/gt2ruikabeo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mvxpbalx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xylfe.cn/Article/details/gt2qcfloehc.html

Java: enum Color { RED, GREEN }
来源：http://dali.jianghu66.top/Article/details/gt2riigfjez.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nanxuanxn.top/Article/details/gt2thkzzyiw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shzxlz.cn/Article/details/gt2olnjzplm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgufenzy.top/Article/details/gt2okvwggnt.html

[G16] 对象转数组 / 字典
来源：http://dali.hywenlv.cn/Article/details/gt2vftdypvo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gaohongyu789.top/Article/details/gt2gxxztson.html

PHP:  get_object_vars($obj);
来源：http://dali.dashuyun.cn/Article/details/gt2iiejafae.html

JS:   Object.entries(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2jiunanhv.html

TS:   Object.entries(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2upkrgepv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jlsjyb.cn/Article/details/gt2ilykmntb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhoulong.xyz/Article/details/gt2lfdhiowk.html

Ruby: obj.instance_variables
来源：http://dali.cqqwz.cn/Article/details/gt2ibnoynfj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shzxlz.cn/Article/details/gt2uzbimfeh.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2upfljhhx.html

H. 异常与错误处理
来源：http://dali.gogol.net.cn/Article/details/gt2albpnjsd.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2vdxtjxyx.html

[H01] try / catch 基础
来源：http://dali.cucudq.cn/Article/details/gt2rwirwnjr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dianchejie.cn/Article/details/gt2bwjpabym.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2cmvurfqe.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gt2ltvnpspf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gt2rpxfgzka.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.wangdashe.top/Article/details/gt2clkqllqj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cdnleiting.top/Article/details/gt2tlmnzmne.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.redwolf501.top/Article/details/gt2gfgcffrx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jqgufenzy.top/Article/details/gt2elbxkfwl.html

[H02] finally / ensure 收尾
来源：http://dali.iojbl.cn/Article/details/gt2mtqdeocq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sufxvd.cn/Article/details/gt2ecbfuskg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gt2oimtyezo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gt2pfggpkvx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gt2pehvqosh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2smkclfcr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ydzc1.top/Article/details/gt2csddwlnz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinqigfzy.top/Article/details/gt2qgohjkdt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gt2iaqrfmuu.html

[H03] 主动抛出异常
来源：http://dali.havefunace.top/Article/details/gt2qkilkgix.html

Py:   raise ValueError("错误信息")
来源：http://dali.hysaishi.cn/Article/details/gt2srobyohx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gt2lwmyygcw.html

JS:   throw new Error("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gt2fmxxawua.html

TS:   throw new Error("错误信息");
来源：http://dali.cucudq.cn/Article/details/gt2ovbrlckt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jqkkhuvh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.vqdsnc.cn/Article/details/gt2zqcxumkl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dashuyun.cn/Article/details/gt2gnravqns.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gt2jekdsoau.html

[H04] 自定义异常类型
来源：http://dali.pycfn.com/Article/details/gt2bevkvjrr.html

Py:   class MyError(Exception): pass
来源：http://dali.316326.xyz/Article/details/gt2slzdikcp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2djewycjr.html

JS:   class MyError extends Error {}
来源：http://dali.yuxming.cn/Article/details/gt2lpfmomug.html

TS:   class MyError extends Error {}
来源：http://dali.redwolf501.top/Article/details/gt2eulozhwr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tianlin.xyz/Article/details/gt2zixjjbha.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.quarkkingdee.top/Article/details/gt2oqvqqaxx.html

Ruby: class MyError < StandardError; end
来源：http://dali.shzxlz.cn/Article/details/gt2wqzfgwgp.html

C#:   class MyException : Exception {}
来源：http://dali.shzxlz.cn/Article/details/gt2vpulknzc.html

[H05] 捕获特定类型
来源：http://dali.jyoumei.cn/Article/details/gt2cfimigmr.html

Py:   except ValueError as e:
来源：http://dali.c1oappe.top/Article/details/gt2ewuidtbp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hnqzz.top/Article/details/gt2ywqpjdzt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ihsehkrr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gt2lzqqlugr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aibaodan.cn/Article/details/gt2czrstygx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yongpay.top/Article/details/gt2ojwwgsko.html

Ruby: rescue ArgumentError => e
来源：http://dali.jianghu66.top/Article/details/gt2vueozfzs.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yonumen.top/Article/details/gt2utahqlib.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ppjwa.cn/Article/details/gt2lmvnotba.html

Py:   value = d.get("k") or default
来源：http://dali.ehwqpu.com/Article/details/gt2zayghbxv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yongpay.top/Article/details/gt2xqcgmcwf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qaaedwlk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gt2oyqutxhj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hfpthk.cn/Article/details/gt2ewxiwtst.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xuetiantiany.cn/Article/details/gt2einscveu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yangfankeji.com/Article/details/gt2dfderyng.html

C#:   obj?.A?.B ?? default
来源：http://dali.tanke756.top/Article/details/gt2tchcevuo.html

[H07] 断言
来源：http://dali.c1oappe.top/Article/details/gt2kquexbfk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jlsjyb.cn/Article/details/gt2hvrfnzeh.html

PHP:  assert($x > 0);
来源：http://dali.iojbl.cn/Article/details/gt2ladmeivd.html

JS:   console.assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gt2ochziqsf.html

TS:   console.assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gt2avdllbuy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.birdmap.top/Article/details/gt2petnegyb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xinyue.icu/Article/details/gt2poedxoli.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xziqi.cn/Article/details/gt2kzogyvlj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2klkjbwet.html

[H08] 获取错误信息与堆栈
来源：http://dali.cashguo.top/Article/details/gt2zhzjrari.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cashguo.top/Article/details/gt2rvdoxibo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xuanzx.com/Article/details/gt2ggwbwgdn.html

JS:   e.message;  e.stack
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2newownwv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258.top/Article/details/gt2mxzxzzfe.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zdqjudy.top/Article/details/gt2gxkcdtcq.html

Go:   err.Error()
来源：http://dali.cqqwz.cn/Article/details/gt2hcygtpqq.html

Ruby: e.message;  e.backtrace
来源：http://dali.andypj.xyz/Article/details/gt2wmovmyhf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.svipenyu.cn/Article/details/gt2jemfbocv.html

[H09] 带错误码的异常
来源：http://dali.jinqigfzy.top/Article/details/gt2phmrylyn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangshuangyany.cn/Article/details/gt2gtoqwutx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nwbrower.top/Article/details/gt2pxdeaioi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shangyingyoupin.top/Article/details/gt2jpapsfdx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xuanzx.com/Article/details/gt2nodkbntt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sxryk.cn/Article/details/gt2untkehbf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ybcxt.top/Article/details/gt2afcppnln.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ygmsvvjj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xuanzx.com/Article/details/gt2uxrtzlgj.html

[H10] 资源自动释放
来源：http://dali.jqgfzy.top/Article/details/gt2hgwsgafj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yongpay.top/Article/details/gt2yfnffqpe.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.chenzaomai.com/Article/details/gt2gcuplgnm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gt2zflmskxj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnqzz.top/Article/details/gt2mcgaidfi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.aizwys.cn/Article/details/gt2djoaswau.html

Go:   defer f.Close()
来源：http://dali.chenlongwang.top/Article/details/gt2ntfmdvoa.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yangfankeji.com/Article/details/gt2gjkmiijl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bweyffdb.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2pawayeuy.html

I. 正则表达式
来源：http://dali.sweek.top/Article/details/gt2ocwfwveq.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2wwfnpcyf.html

[I01] 判断是否匹配
来源：http://dali.yj20258.top/Article/details/gt2sridjbej.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sweek.top/Article/details/gt2jqpbxiev.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjktzah.html

JS:   /\d+/.test(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vkajsvwt.html

TS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gt2dgjmrdtl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.svipenyu.cn/Article/details/gt2ahvagkgg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2yknrdmqq.html

Ruby: s.match?(/\d+/)
来源：http://dali.daria6918.cn/Article/details/gt2wiexhnzd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cashguo.top/Article/details/gt2wbjlzfrl.html

[I02] 提取所有匹配
来源：http://dali.quarkkingdee.top/Article/details/gt2sdqsxjoa.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gt2dlilwihn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tian-w.cn/Article/details/gt2wnhatjrs.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tian-w.cn/Article/details/gt2yzjczdil.html

TS:   s.match(/\d+/g)
来源：http://dali.svipenyu.cn/Article/details/gt2oxlrukfb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2syeuubyx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.havefunace.top/Article/details/gt2zbgailee.html

Ruby: s.scan(/\d+/)
来源：http://dali.chenlongwang.top/Article/details/gt2ipcyelcc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ppjwa.cn/Article/details/gt2sfvsswnc.html

[I03] 提取捕获分组
来源：http://dali.xuanzx.com/Article/details/gt2dtupwpbr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.svipenyu.cn/Article/details/gt2wxbojxye.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.mhx1999.top/Article/details/gt2ebadmpkm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xinyue.icu/Article/details/gt2mtlvnigc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.fengsongda.top/Article/details/gt2nqfebvlx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cqqwz.cn/Article/details/gt2rhfyqaxi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenzaomai.com/Article/details/gt2wjpbxcyj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj202588.top/Article/details/gt2jnepdxnc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jlsjyb.cn/Article/details/gt2nizbzxnb.html

[I04] 正则替换
来源：http://dali.tanke756.top/Article/details/gt2kcfunycv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.316326.xyz/Article/details/gt2uziochfz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ydzc1.top/Article/details/gt2ljnxbtzp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ksepkefg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhoulong.xyz/Article/details/gt2pvfhpfqr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.havefunace.top/Article/details/gt2gddamjao.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.c1oappe.top/Article/details/gt2tailewds.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.aibaodan.cn/Article/details/gt2vkffvobr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yanxiufei.cn/Article/details/gt2ionzlvxz.html

[I05] 按正则拆分
来源：http://dali.jinqigufen.top/Article/details/gt2mgvkngkt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cheryme.top/Article/details/gt2cxsibrfo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xuanzx.com/Article/details/gt2cxsssiie.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gt2nzsqyvpx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gt2rkiyhtgu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhixingplan.top/Article/details/gt2jtqrrcll.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gotoacloud.top/Article/details/gt2yzafqfhd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gt2feddhntp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jiagoushi.top/Article/details/gt2gvszmjjq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shangyingyoupin.top/Article/details/gt2hwpaeepx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gt2zshvpjdv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.wangshuangyany.cn/Article/details/gt2zmjzjjgu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gt2pnfjsxyy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tanke756.top/Article/details/gt2vnuwsifj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gt2mmoxunxv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hysaishi.cn/Article/details/gt2fqljwekl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.meibo888.top/Article/details/gt2klemctie.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gt2cwdoudrk.html

[I07] 忽略大小写与多行模式
来源：http://dali.cheryme.top/Article/details/gt2cudabgeo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.9152youxi.cn/Article/details/gt2cstzmlew.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gt2plgwzusb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhongyouzk.top/Article/details/gt2mulycmvk.html

TS:   /error/gim
来源：http://dali.pycfn.com/Article/details/gt2hdwgxlnk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.c1oappe.top/Article/details/gt2btjojbfa.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.daria6918.cn/Article/details/gt2oaldvhjm.html

Ruby: s.scan(/error/i)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iojazidu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cucudq.cn/Article/details/gt2bvuwmirw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fyufitku.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.wangdashe.top/Article/details/gt2erqyexbn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.kuanghao11.cn/Article/details/gt2ffkjoccl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gt2ysnxxqmt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daria6918.cn/Article/details/gt2yboylhql.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.meibo888.top/Article/details/gt2hrnxdwqc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.fzhhl.top/Article/details/gt2kjmmfxfx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jiagoushi.top/Article/details/gt2jadgqaje.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dtovqnol.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2gxdzexjw.html

J. 日期与时间
来源：http://dali.zycfv.cn/Article/details/gt2ruutmoyh.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2lyshdnat.html

[J01] 获取当前时间
来源：http://dali.yj20258888.top/Article/details/gt2vtxdygea.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.pycfn.com/Article/details/gt2gexrwgyi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shzxlz.cn/Article/details/gt2hmxvjhyy.html

JS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gt2yunsxikg.html

TS:   new Date();  Date.now()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ukoilxjv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lcfubnph.html

Go:   time.Now()
来源：http://dali.chenzaomai.com/Article/details/gt2fnoqjqfo.html

Ruby: Time.now
来源：http://dali.dashuyun.cn/Article/details/gt2lrgetqoo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ufqanwxz.html

[J02] 格式化输出
来源：http://dali.dianchejie.cn/Article/details/gt2aaqqgudo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.316326.xyz/Article/details/gt2lypzojua.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gt2fisykonf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.bjfxy.top/Article/details/gt2rmhecwek.html

TS:   d.toISOString()
来源：http://dali.hammf.cn/Article/details/gt2jtjshlws.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hysaishi.cn/Article/details/gt2liguoehg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.havefunace.top/Article/details/gt2dhgmvykw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cucudq.cn/Article/details/gt2gcplxkoc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.bjfxy.top/Article/details/gt2kqkaumlp.html

[J03] 字符串解析为日期
来源：http://dali.gogol.net.cn/Article/details/gt2ziakgvmv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daria6918.cn/Article/details/gt2gvhsgluc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.haohaochexian.top/Article/details/gt2erdydcsx.html

JS:   new Date("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gt2fptrnycr.html

TS:   new Date("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2yksdcvki.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gt2uixqdxgx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gt2idmiexpg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gt2tywrhmnm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wnujqeiu.html

[J04] 时间戳与日期互转
来源：http://dali.yj202588.top/Article/details/gt2zfwewxjo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gt2sxeaizpv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yuxming.cn/Article/details/gt2znwrdxre.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xuanzx.com/Article/details/gt2gybwmidj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ppjwa.cn/Article/details/gt2hssagvbs.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jqgufenzy.top/Article/details/gt2xphpcdgk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj202588.top/Article/details/gt2wwhoetyh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinqigufen.top/Article/details/gt2utiigzne.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.meibo888.top/Article/details/gt2icydjvio.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinqigufen.top/Article/details/gt2eplceqag.html

Py:   now + timedelta(days=7)
来源：http://dali.yj202588.top/Article/details/gt2xfdvxcpy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tianlin.xyz/Article/details/gt2emtuttvn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.andypj.xyz/Article/details/gt2engwyogd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.birdmap.top/Article/details/gt2idtojube.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gogol.net.cn/Article/details/gt2wbscolov.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.wangdashe.top/Article/details/gt2jzgxkjti.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xuanzx.com/Article/details/gt2ehjbslsi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.pycfn.com/Article/details/gt2zzkdipbq.html

[J06] 计算两时间之差
来源：http://dali.gogol.net.cn/Article/details/gt2ngqrmxcf.html

Py:   (end - start).total_seconds()
来源：http://dali.hywenlv.cn/Article/details/gt2azfgprer.html

PHP:  $end->diff($start)->days;
来源：http://dali.hywenlv.cn/Article/details/gt2gcxsxxoi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.mhx1999.top/Article/details/gt2sjtqnruf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jianghu66.top/Article/details/gt2xjfzvrme.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.daxiang520.top/Article/details/gt2prlxmxgq.html

Go:   end.Sub(start).Hours()
来源：http://dali.daxiang520.top/Article/details/gt2fdbxqeof.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tpobiudu.html

C#:   (end - start).TotalSeconds
来源：http://dali.birdmap.top/Article/details/gt2jerqpyua.html

[J07] 比较两个日期
来源：http://dali.yj202588.top/Article/details/gt2wnraldhh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gt2qtjnxkxh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.daria6918.cn/Article/details/gt2vehbmbeu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hnqzz.top/Article/details/gt2drnwthnv.html


<!-- 参考信息 -->