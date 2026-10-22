代发 wailian999

Py:   from abc import ABC, abstractmethod
来源：http://dali.jlsjyb.cn/Article/details/gt2xszmhjkq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.haohaochexian.top/Article/details/gt2hsxidgit.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pengpengdd.cyou/Article/details/gt2hwwuojdh.html

TS:   interface Shape { area(): number; }
来源：http://dali.smart0.xyz/Article/details/gt2vnpatxcr.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kqnldayx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.svipenyu.cn/Article/details/gt2tondyuhv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.redwolf501.top/Article/details/gt2qwtqyzqi.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2qlruwrgd.html

[G10] 访问控制
来源：http://dali.aibaodan.cn/Article/details/gt2crffxajk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vojpedpn.html

PHP:  public / protected / private
来源：http://dali.yongpay.top/Article/details/gt2hkmgouhk.html

JS:   #private 字段；其余公开
来源：http://dali.zhongyouzk.top/Article/details/gt2thyrkbzw.html

TS:   public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gt2cforrbjh.html

Java: public / protected / private / 默认包级
来源：http://dali.yuxming.cn/Article/details/gt2nlabbnnz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xylfe.cn/Article/details/gt2ejrbomck.html

Ruby: public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gt2gmvimzta.html

C#:   public / protected / private / internal
来源：http://dali.hysaishi.cn/Article/details/gt2ihthzrkt.html

[G11] getter / setter
来源：http://dali.yueranfly.top/Article/details/gt2mgkadxvm.html

Py:   @property 与 @x.setter
来源：http://dali.nwbrower.top/Article/details/gt2pxbftntl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gt2xyzyblsh.html

JS:   get name() { return this._name; }
来源：http://dali.guannengcc.top/Article/details/gt2cfyccxpo.html

TS:   get name(): string { return this._name; }
来源：http://dali.guannengcc.top/Article/details/gt2rifvjirc.html

Java: public String getName() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gt2bfddjzbv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gt2gjinebgm.html

Ruby: attr_accessor :name
来源：http://dali.xinyue.icu/Article/details/gt2bfnxhzph.html

C#:   public string Name { get; set; }
来源：http://dali.hnqzz.top/Article/details/gt2eltyquzl.html

[G12] 对象转字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2mtvoatxp.html

Py:   def __str__(self): return self.name
来源：http://dali.sweek.top/Article/details/gt2squhagwx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2hmuizlfo.html

JS:   toString() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gt2fbsdvmpj.html

TS:   toString(): string { return this.name; }
来源：http://dali.cashguo.top/Article/details/gt2nnsdgrrj.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gt2ovokpvhm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sdibslpe.html

Ruby: def to_s; @name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cpgdarec.html

C#:   public override string ToString() => Name;
来源：http://dali.gotoacloud.top/Article/details/gt2tznbfgyw.html

[G13] 判断对象类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2zxblwose.html

Py:   isinstance(u, User)
来源：http://dali.shzxlz.cn/Article/details/gt2xdaqtjea.html

PHP:  $u instanceof User
来源：http://dali.yj20258.top/Article/details/gt2qxcmdteq.html

JS:   u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gt2dxpddgdl.html

TS:   u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gt2gonuyeyh.html

Java: u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gt2awyrycqx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ybcxt.top/Article/details/gt2kgeirdvd.html

Ruby: u.is_a?(User)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ihfgsqqr.html

C#:   u is User
来源：http://dali.jiagoushi.top/Article/details/gt2iaosusrx.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhvuqrg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.redwolf501.top/Article/details/gt2mjaymoqy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.quarkkingdee.top/Article/details/gt2nkkadvne.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hfpthk.cn/Article/details/gt2jtenkqvn.html

TS:   type User = { name: string; age: number };
来源：http://dali.bjfxy.top/Article/details/gt2eyjgjetp.html

Java: record User(String name, int age) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2msecvdrr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jlsjyb.cn/Article/details/gt2zslgldpx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.wangshuangyany.cn/Article/details/gt2zjbftyon.html

C#:   record User(string Name, int Age);
来源：http://dali.snrcjt.cn/Article/details/gt2pywxgpdl.html

[G15] 枚举
来源：http://dali.yj20258.top/Article/details/gt2ygyoyxhb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oejxxqes.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cucudq.cn/Article/details/gt2mncyotqv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhengqikj.top/Article/details/gt2vmjwfndm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbwqvxc.html

Java: enum Color { RED, GREEN }
来源：http://dali.cheryme.top/Article/details/gt2ngzzsaij.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.fengsongda.top/Article/details/gt2jkupevbp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yanxiufei.cn/Article/details/gt2zwhmtpev.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dianchejie.cn/Article/details/gt2ccthoekp.html

[G16] 对象转数组 / 字典
来源：http://dali.yonumen.top/Article/details/gt2upkajyfo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cqqwz.cn/Article/details/gt2zhwuiplr.html

PHP:  get_object_vars($obj);
来源：http://dali.zhoulong.xyz/Article/details/gt2ivuskhyi.html

JS:   Object.entries(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fdoluqnk.html

TS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gt2jzsgnvmh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ybcxt.top/Article/details/gt2nwlrkzyh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yanxiufei.cn/Article/details/gt2pfoysdhz.html

Ruby: obj.instance_variables
来源：http://dali.jianghu66.top/Article/details/gt2kiytmnlu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.bjfxy.top/Article/details/gt2wrqicidj.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2tofkptji.html

H. 异常与错误处理
来源：http://dali.iojbl.cn/Article/details/gt2mqzwlqbc.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2dtwwjdhd.html

[H01] try / catch 基础
来源：http://dali.fzhhl.top/Article/details/gt2wmuktlhk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhengqikj.top/Article/details/gt2yjkmflqn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pycfn.com/Article/details/gt2vhyonayo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gt2idmlnmam.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.daria6918.cn/Article/details/gt2jrmoddzq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ocbbkuoz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.pycfn.com/Article/details/gt2tcdtcriy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hnqzz.top/Article/details/gt2lolmfvys.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xziqi.cn/Article/details/gt2nbjsxbna.html

[H02] finally / ensure 收尾
来源：http://dali.smart0.xyz/Article/details/gt2kqghxkib.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jlsjyb.cn/Article/details/gt2abamzhlo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gt2uqamppuc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gt2jgomnpdp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gt2mpvsdirm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2hqjxoirz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.guowangkeji.top/Article/details/gt2rwhfgskt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj202588.top/Article/details/gt2adnyrwos.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2zserrcdu.html

[H03] 主动抛出异常
来源：http://dali.xuanzx.com/Article/details/gt2tzyxcdxe.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnxiangtu.top/Article/details/gt2qhqxwwcd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xktaaqjx.html

JS:   throw new Error("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gt2scuagevo.html

TS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gt2uehoylpb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2uvajcvvp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xbtnbott.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ydzc1.top/Article/details/gt2crqgrhsa.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gt2adzowfjq.html

[H04] 自定义异常类型
来源：http://dali.9152youxi.cn/Article/details/gt2nvvekhgv.html

Py:   class MyError(Exception): pass
来源：http://dali.mhx1999.top/Article/details/gt2gsavfzqp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ivvv.top/Article/details/gt2ajfqnhva.html

JS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gt2hjxscebz.html

TS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gt2aufegsyo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.mhx1999.top/Article/details/gt2yhdsnxtf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.birdmap.top/Article/details/gt2oghewred.html

Ruby: class MyError < StandardError; end
来源：http://dali.cucudq.cn/Article/details/gt2vywvzwtc.html

C#:   class MyException : Exception {}
来源：http://dali.jiagoushi.top/Article/details/gt2gciiycgg.html

[H05] 捕获特定类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2rtbkbezb.html

Py:   except ValueError as e:
来源：http://dali.jyoumei.cn/Article/details/gt2dnviqszb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.snrcjt.cn/Article/details/gt2bwluoiun.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.mhx1999.top/Article/details/gt2wuftjiws.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fzhhl.top/Article/details/gt2azsrhtcp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2dtncjelw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ivvv.top/Article/details/gt2fvisdfqd.html

Ruby: rescue ArgumentError => e
来源：http://dali.ivvv.top/Article/details/gt2ktxbsxij.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2ugzeuomz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hnqzz.top/Article/details/gt2zerxaohj.html

Py:   value = d.get("k") or default
来源：http://dali.shzxlz.cn/Article/details/gt2gcwjyagu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pruhaalq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jlsjyb.cn/Article/details/gt2dosfkjxp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cashguo.top/Article/details/gt2zdnftrai.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tucndczp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.guannengcc.top/Article/details/gt2knjgfqsu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yonumen.top/Article/details/gt2jgdisfej.html

C#:   obj?.A?.B ?? default
来源：http://dali.sxryk.cn/Article/details/gt2fbowweox.html

[H07] 断言
来源：http://dali.gogol.net.cn/Article/details/gt2sgvsirji.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ydzc1.top/Article/details/gt2mmpqxpbw.html

PHP:  assert($x > 0);
来源：http://dali.gzhubu.top/Article/details/gt2lefcunev.html

JS:   console.assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2keytcamt.html

TS:   console.assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2bewvifoq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sysykeji.top/Article/details/gt2oprxsgxo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.mhx1999.top/Article/details/gt2hirikmhq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenjidiqi.icu/Article/details/gt2ustfjzwd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2lylhdszl.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qvtcllzw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xziqi.cn/Article/details/gt2ufieipmv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.aizwys.cn/Article/details/gt2ybccjgwn.html

JS:   e.message;  e.stack
来源：http://dali.pengpengdd.cyou/Article/details/gt2tujpayia.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xinyue.icu/Article/details/gt2vewkgjnw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cheryme.top/Article/details/gt2fehufdpd.html

Go:   err.Error()
来源：http://dali.jyoumei.cn/Article/details/gt2uqlrzual.html

Ruby: e.message;  e.backtrace
来源：http://dali.jiagoushi.top/Article/details/gt2wwzaghtv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hywenlv.cn/Article/details/gt2gbcmdwuo.html

[H09] 带错误码的异常
来源：http://dali.jianghu66.top/Article/details/gt2wavhxuxp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gzhubu.top/Article/details/gt2zstjawwc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jenenxgb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ewxxdsuf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj20258888.top/Article/details/gt2xettryfb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.9152youxi.cn/Article/details/gt2lqwuedjk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.redwolf501.top/Article/details/gt2ofpqelvg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cqqwz.cn/Article/details/gt2qibitcat.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj20258.top/Article/details/gt2qxtizrmm.html

[H10] 资源自动释放
来源：http://dali.gzhubu.top/Article/details/gt2poqnfgtr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xuetiantiany.cn/Article/details/gt2htlpurpw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nanxuanxn.top/Article/details/gt2yypwcsdv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gt2jrgicgjy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aibaodan.cn/Article/details/gt2zbjbgsav.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.andypj.xyz/Article/details/gt2noynwfrq.html

Go:   defer f.Close()
来源：http://dali.quarkkingdee.top/Article/details/gt2hlpihnzt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jiagoushi.top/Article/details/gt2sabplyhv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.pycfn.com/Article/details/gt2qiwlrsya.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2lhvfjymv.html

I. 正则表达式
来源：http://dali.hammf.cn/Article/details/gt2xtndsado.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2cwmkirvy.html

[I01] 判断是否匹配
来源：http://dali.yueranfly.top/Article/details/gt2oebismmh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.9152youxi.cn/Article/details/gt2jrywykbe.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shuidangran.top/Article/details/gt2zirbtyzj.html

JS:   /\d+/.test(s)
来源：http://dali.xylfe.cn/Article/details/gt2goheygag.html

TS:   /\d+/.test(s)
来源：http://dali.smart0.xyz/Article/details/gt2exkzyirx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iicszqfl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xinyue.icu/Article/details/gt2icdttqrq.html

Ruby: s.match?(/\d+/)
来源：http://dali.hammf.cn/Article/details/gt2hgvsyvrc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ybcxt.top/Article/details/gt2dievhsio.html

[I02] 提取所有匹配
来源：http://dali.pengpengdd.cyou/Article/details/gt2kuyudmkj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hysaishi.cn/Article/details/gt2yrqwgkdo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhiwuduotai.top/Article/details/gt2llrlnmfs.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhengqikj.top/Article/details/gt2zawrqhvx.html

TS:   s.match(/\d+/g)
来源：http://dali.ivvv.top/Article/details/gt2peuodwij.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2shefzcuf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.haohaochexian.top/Article/details/gt2iyztyldf.html

Ruby: s.scan(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gt2wsztmdvg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.haohaochexian.top/Article/details/gt2twpforok.html

[I03] 提取捕获分组
来源：http://dali.ehwqpu.com/Article/details/gt2vnldzdvy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2raanyhsr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jlsjyb.cn/Article/details/gt2ocqcuzan.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2opqdftyx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gzhubu.top/Article/details/gt2zkrapxim.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sxryk.cn/Article/details/gt2qkxgciab.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.haohaochexian.top/Article/details/gt2bpmzqpzy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangdashe.top/Article/details/gt2ptkplnhw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yonumen.top/Article/details/gt2iopmbdtr.html

[I04] 正则替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bzpsmyqb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hfpthk.cn/Article/details/gt2xikyxtec.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2wcqyoyia.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2filistqm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gzhubu.top/Article/details/gt2hnxuzwdh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.pycfn.com/Article/details/gt2ntfiieen.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.c1oappe.top/Article/details/gt2yhwzenux.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cashguo.top/Article/details/gt2hfiidium.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2qmodolxs.html

[I05] 按正则拆分
来源：http://dali.gotoacloud.top/Article/details/gt2rqvbmbsa.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jyoumei.cn/Article/details/gt2ihpnjldv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sufxvd.cn/Article/details/gt2ixutyuph.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kntipipu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gt2wmehptej.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gogol.net.cn/Article/details/gt2mkimsxdp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nanxuanxn.top/Article/details/gt2vifmyidr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gt2pnsaowbw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hongshengwenyu.top/Article/details/gt2dmejzrtw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shuidangran.top/Article/details/gt2suwtzbgr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gt2isboungx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shzxlz.cn/Article/details/gt2fjravmfm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgufenzy.top/Article/details/gt2progjuxi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.meibo888.top/Article/details/gt2rnylgxaj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gt2hlhfmqqj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj202588.top/Article/details/gt2iesffdxf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jyoumei.cn/Article/details/gt2rxjpplak.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gt2imptcdvq.html

[I07] 忽略大小写与多行模式
来源：http://dali.cdnleiting.top/Article/details/gt2uiqkzlcm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhoulong.xyz/Article/details/gt2dnbkkgox.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gt2eiysyoic.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.redwolf501.top/Article/details/gt2yakhcqqj.html

TS:   /error/gim
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wjdnsthe.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cucudq.cn/Article/details/gt2bohorksf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xuanzx.com/Article/details/gt2wpgpwhrg.html

Ruby: s.scan(/error/i)
来源：http://dali.cucudq.cn/Article/details/gt2tmbdmdmp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2myyxjujk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ybcxt.top/Article/details/gt2vgulowvy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daxiang520.top/Article/details/gt2zzigmoki.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jqgfzy.top/Article/details/gt2djpqxylu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gt2oapbjuid.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gt2piimucgl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xinyue.icu/Article/details/gt2djlizmlm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nwbrower.top/Article/details/gt2khjbusjk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zycfv.cn/Article/details/gt2qjwaoxxo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.smart0.xyz/Article/details/gt2htjliaic.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2jezploeu.html

J. 日期与时间
来源：http://dali.chenlongwang.top/Article/details/gt2lsoovgsv.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2eqnxqwfc.html

[J01] 获取当前时间
来源：http://dali.hnqzz.top/Article/details/gt2ehriqkfc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gaohongyu789.top/Article/details/gt2yhewhidh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jiagoushi.top/Article/details/gt2hdtlhwja.html

JS:   new Date();  Date.now()
来源：http://dali.fzhhl.top/Article/details/gt2hbtppcwm.html

TS:   new Date();  Date.now()
来源：http://dali.wangdashe.top/Article/details/gt2mqfdfyiy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.daxiang520.top/Article/details/gt2hodicdrs.html

Go:   time.Now()
来源：http://dali.andypj.xyz/Article/details/gt2cqzeilfu.html

Ruby: Time.now
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cwinkyyf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gotoacloud.top/Article/details/gt2lytxkipj.html

[J02] 格式化输出
来源：http://dali.xylfe.cn/Article/details/gt2dabvrdgv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tian-w.cn/Article/details/gt2djhnhehy.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sjgvwwex.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.kuanghao11.cn/Article/details/gt2tbyszuei.html

TS:   d.toISOString()
来源：http://dali.sweek.top/Article/details/gt2jqdaqqzf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenjidiqi.icu/Article/details/gt2ijzdnhhw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.fzhhl.top/Article/details/gt2gcamlghg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jianghu66.top/Article/details/gt2rqzsvzhb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zdcrubce.html

[J03] 字符串解析为日期
来源：http://dali.wangshuangyany.cn/Article/details/gt2tavamnjc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xziqi.cn/Article/details/gt2vpqizeen.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.9152youxi.cn/Article/details/gt2tauokgod.html

JS:   new Date("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gt2coyxgcmv.html

TS:   new Date("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gt2owrojunj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gt2eebrlbzb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gt2slpkgwuz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gt2flnjigmx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gogol.net.cn/Article/details/gt2arwakjbj.html

[J04] 时间戳与日期互转
来源：http://dali.aibaodan.cn/Article/details/gt2dzgwmajc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj202588.top/Article/details/gt2gjzgdpzb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cashguo.top/Article/details/gt2lmhjpwvd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xylfe.cn/Article/details/gt2otahcrtm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yuanzhike.top/Article/details/gt2xlhwlfsp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yuxming.cn/Article/details/gt2bwkelrrr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zycfv.cn/Article/details/gt2mvmyyjvp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tanke756.top/Article/details/gt2nzbvctrb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuanzx.com/Article/details/gt2bcafkglr.html

[J05] 时间加减（加 7 天）
来源：http://dali.wangdashe.top/Article/details/gt2nxvrhiuu.html

Py:   now + timedelta(days=7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jxgfmsth.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhongyouzk.top/Article/details/gt2iixtpnop.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jlsjyb.cn/Article/details/gt2vqsgacod.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuanzx.com/Article/details/gt2lhuikjcn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yangfankeji.com/Article/details/gt2prebeaov.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinqigufen.top/Article/details/gt2cldorynr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.fengsongda.top/Article/details/gt2cylbypjo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.birdmap.top/Article/details/gt2ufuuvexz.html

[J06] 计算两时间之差
来源：http://dali.aizwys.cn/Article/details/gt2roskqzdl.html

Py:   (end - start).total_seconds()
来源：http://dali.ppjwa.cn/Article/details/gt2mlizxzem.html

PHP:  $end->diff($start)->days;
来源：http://dali.xziqi.cn/Article/details/gt2ttzumwle.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hywenlv.cn/Article/details/gt2jwmfsgtt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.bjfxy.top/Article/details/gt2huvgpwem.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hysaishi.cn/Article/details/gt2eanhmvkf.html

Go:   end.Sub(start).Hours()
来源：http://dali.quarkkingdee.top/Article/details/gt2bpzpjcet.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xinyue.icu/Article/details/gt2gywfmozf.html

C#:   (end - start).TotalSeconds
来源：http://dali.jianghu66.top/Article/details/gt2zmqvcugm.html

[J07] 比较两个日期
来源：http://dali.nwbrower.top/Article/details/gt2cwwcycnb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2scwcpiai.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ubbkihas.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.aizwys.cn/Article/details/gt2qxhvskhx.html


<!-- 参考信息 -->