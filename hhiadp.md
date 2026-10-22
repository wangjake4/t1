代发 wailian999

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhengqikj.top/Article/details/gt2bsgtftml.html

Ruby: def self.f; end
来源：http://dali.mhx1999.top/Article/details/gt2maaxsmdv.html

C#:   public static void F() {}
来源：http://dali.hysaishi.cn/Article/details/gt2erihtaam.html

[G09] 接口 / 抽象类
来源：http://dali.andypj.xyz/Article/details/gt2lgptdzew.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ppjwa.cn/Article/details/gt2jacjdegp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.kuanghao11.cn/Article/details/gt2aezstvkv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jlsjyb.cn/Article/details/gt2ttinreph.html

TS:   interface Shape { area(): number; }
来源：http://dali.yonumen.top/Article/details/gt2ahcwdfsg.html

Java: interface Shape { double area(); }
来源：http://dali.mhx1999.top/Article/details/gt2puqskupa.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yuxming.cn/Article/details/gt2bvgdnnoe.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.meibo888.top/Article/details/gt2uemzxyzd.html

C#:   interface IShape { double Area(); }
来源：http://dali.gogol.net.cn/Article/details/gt2nwqbzdjx.html

[G10] 访问控制
来源：http://dali.yj20258.top/Article/details/gt2cayfbgkc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ivvv.top/Article/details/gt2fbskvrut.html

PHP:  public / protected / private
来源：http://dali.gzhubu.top/Article/details/gt2qleixbop.html

JS:   #private 字段；其余公开
来源：http://dali.yanxiufei.cn/Article/details/gt2cbrufrwj.html

TS:   public / protected / private
来源：http://dali.sxryk.cn/Article/details/gt2rsaiapgo.html

Java: public / protected / private / 默认包级
来源：http://dali.pycfn.com/Article/details/gt2yogihpor.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jianghu66.top/Article/details/gt2urjmwtbn.html

Ruby: public / protected / private
来源：http://dali.sweek.top/Article/details/gt2ehjonjpx.html

C#:   public / protected / private / internal
来源：http://dali.chenlongwang.top/Article/details/gt2ihybbelh.html

[G11] getter / setter
来源：http://dali.redwolf501.top/Article/details/gt2vsglhrxv.html

Py:   @property 与 @x.setter
来源：http://dali.hongshengwenyu.top/Article/details/gt2muqclums.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gt2nzbqvrhe.html

JS:   get name() { return this._name; }
来源：http://dali.shzxlz.cn/Article/details/gt2jpovinyr.html

TS:   get name(): string { return this._name; }
来源：http://dali.ydzc1.top/Article/details/gt2ttosodzb.html

Java: public String getName() { return name; }
来源：http://dali.hnqzz.top/Article/details/gt2jtkmkbac.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gt2zfrsgcgj.html

Ruby: attr_accessor :name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2attrxdbz.html

C#:   public string Name { get; set; }
来源：http://dali.hywenlv.cn/Article/details/gt2lzlpcplz.html

[G12] 对象转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ltfyisjj.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258888.top/Article/details/gt2wnkdbnek.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gt2qzrbnbno.html

JS:   toString() { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gt2dmhvklje.html

TS:   toString(): string { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fviwtjov.html

Java: @Override public String toString() { return name; }
来源：http://dali.xylfe.cn/Article/details/gt2gjezxjdt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gt2raadxmil.html

Ruby: def to_s; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2pdgbfgyo.html

C#:   public override string ToString() => Name;
来源：http://dali.ydzc1.top/Article/details/gt2jmqkkwwv.html

[G13] 判断对象类型
来源：http://dali.bjfxy.top/Article/details/gt2zmlfvodw.html

Py:   isinstance(u, User)
来源：http://dali.cdnleiting.top/Article/details/gt2jlwhndnm.html

PHP:  $u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gt2zgzgslia.html

JS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gt2cbiwiipm.html

TS:   u instanceof User
来源：http://dali.ybcxt.top/Article/details/gt2tegrbkze.html

Java: u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gt2codybrix.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zdqjudy.top/Article/details/gt2qdgxmwsn.html

Ruby: u.is_a?(User)
来源：http://dali.9152youxi.cn/Article/details/gt2rrhoitjm.html

C#:   u is User
来源：http://dali.svipenyu.cn/Article/details/gt2dufgowui.html

[G14] 数据类 / record
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xldlgybx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tian-w.cn/Article/details/gt2phlbfwrl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cdnleiting.top/Article/details/gt2iyhbqbon.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jhsenupx.html

TS:   type User = { name: string; age: number };
来源：http://dali.snrcjt.cn/Article/details/gt2isqbrobe.html

Java: record User(String name, int age) {}
来源：http://dali.andypj.xyz/Article/details/gt2nmwpaolk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yonumen.top/Article/details/gt2weiwevwk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shzxlz.cn/Article/details/gt2wjhezytc.html

C#:   record User(string Name, int Age);
来源：http://dali.ppjwa.cn/Article/details/gt2mynradkh.html

[G15] 枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hwvxmbxs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.bjfxy.top/Article/details/gt2heyzzakk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuanzhike.top/Article/details/gt2gklthyjy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cdnleiting.top/Article/details/gt2yaxkepqo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj202588.top/Article/details/gt2dszdfuih.html

Java: enum Color { RED, GREEN }
来源：http://dali.hnqzz.top/Article/details/gt2nwehvksa.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhongyouzk.top/Article/details/gt2xwpcxuwl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hongshengwenyu.top/Article/details/gt2wmpuekjl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gt2yfbnigzx.html

[G16] 对象转数组 / 字典
来源：http://dali.yuanzhike.top/Article/details/gt2bqaxiztl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gotoacloud.top/Article/details/gt2slozspeb.html

PHP:  get_object_vars($obj);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pvclxtdd.html

JS:   Object.entries(obj)
来源：http://dali.yuxming.cn/Article/details/gt2dgvyylka.html

TS:   Object.entries(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2uiretjsz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tianlin.xyz/Article/details/gt2ualdeyek.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.redwolf501.top/Article/details/gt2qmmnwczw.html

Ruby: obj.instance_variables
来源：http://dali.zhiwuduotai.top/Article/details/gt2anxrbuzl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nwbrower.top/Article/details/gt2bwssaoti.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2yzgmttwx.html

H. 异常与错误处理
来源：http://dali.wangshuangyany.cn/Article/details/gt2qagsznty.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2glbtzrre.html

[H01] try / catch 基础
来源：http://dali.zhengqikj.top/Article/details/gt2rpaawxss.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dianchejie.cn/Article/details/gt2fauftgrq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhengqikj.top/Article/details/gt2qwuxhidb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.birdmap.top/Article/details/gt2awuovwqx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gt2bvhoateb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gaohongyu789.top/Article/details/gt2nxxlopae.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nwbrower.top/Article/details/gt2ubrxfnea.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.birdmap.top/Article/details/gt2umlodnhh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnqzz.top/Article/details/gt2gmokjoll.html

[H02] finally / ensure 收尾
来源：http://dali.yangfankeji.com/Article/details/gt2jvmqeypa.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sufxvd.cn/Article/details/gt2amfrxuez.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gt2sdekpjfw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2egqltcfj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gt2ztijwlux.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gt2neictyhz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.aizwys.cn/Article/details/gt2wuyeottv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sxryk.cn/Article/details/gt2rxpaxqaa.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vycsyles.html

[H03] 主动抛出异常
来源：http://dali.chenzaomai.com/Article/details/gt2exyhforg.html

Py:   raise ValueError("错误信息")
来源：http://dali.hywenlv.cn/Article/details/gt2gplvmzmp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2upetaejl.html

JS:   throw new Error("错误信息");
来源：http://dali.jianghu66.top/Article/details/gt2adowjexh.html

TS:   throw new Error("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gt2kuykgqxf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gt2ipmtzlzj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.aizwys.cn/Article/details/gt2mvciujve.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gaohongyu789.top/Article/details/gt2dpmsdnjt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gt2omrialbu.html

[H04] 自定义异常类型
来源：http://dali.daxiang520.top/Article/details/gt2bldbvirv.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258888.top/Article/details/gt2nwobnwyy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gt2yprgkwmg.html

JS:   class MyError extends Error {}
来源：http://dali.redwolf501.top/Article/details/gt2cbnponmb.html

TS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gt2modpvicy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.meibo888.top/Article/details/gt2bjxiudbl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nwbrower.top/Article/details/gt2aykxvmms.html

Ruby: class MyError < StandardError; end
来源：http://dali.hfpthk.cn/Article/details/gt2mcvfswvw.html

C#:   class MyException : Exception {}
来源：http://dali.tanke756.top/Article/details/gt2tulhkvmh.html

[H05] 捕获特定类型
来源：http://dali.0kj1m.cn/Article/details/gt2irtjcyun.html

Py:   except ValueError as e:
来源：http://dali.daxiang520.top/Article/details/gt2vviqedls.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jiagoushi.top/Article/details/gt2netwcmlf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tanke756.top/Article/details/gt2atbkcwdr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gt2idjkppqy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.iojbl.cn/Article/details/gt2vcozhask.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenzaomai.com/Article/details/gt2xusxqcum.html

Ruby: rescue ArgumentError => e
来源：http://dali.yvedp.cn/Article/details/gt2ozwuecah.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2hkmmbvbl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj202588.top/Article/details/gt2bzedwxsh.html

Py:   value = d.get("k") or default
来源：http://dali.dianchejie.cn/Article/details/gt2dvezjdhn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.316326.xyz/Article/details/gt2yzqvgujc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gt2mvufafrb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cheryme.top/Article/details/gt2vcypvmdp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hfpthk.cn/Article/details/gt2qxhscell.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.vqdsnc.cn/Article/details/gt2dcxjrujn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.svipenyu.cn/Article/details/gt2bhkdrway.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgufenzy.top/Article/details/gt2atrfqqje.html

[H07] 断言
来源：http://dali.316326.xyz/Article/details/gt2dtrynaey.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ybcxt.top/Article/details/gt2pbgkoeou.html

PHP:  assert($x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ziwagozk.html

JS:   console.assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gt2hepejnox.html

TS:   console.assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gt2uazhlhhq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yonumen.top/Article/details/gt2qkamjurl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pengpengdd.cyou/Article/details/gt2uzybvnum.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sufxvd.cn/Article/details/gt2rldchiar.html

C#:   Debug.Assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gt2tlgesfkr.html

[H08] 获取错误信息与堆栈
来源：http://dali.tianlin.xyz/Article/details/gt2ofvocjjc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj202588.top/Article/details/gt2dwcpdjnn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.aibaodan.cn/Article/details/gt2qbpdrlhb.html

JS:   e.message;  e.stack
来源：http://dali.xinyue.icu/Article/details/gt2zbkcchly.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hysaishi.cn/Article/details/gt2lrnqscwj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.smart0.xyz/Article/details/gt2sorfzxri.html

Go:   err.Error()
来源：http://dali.hfpthk.cn/Article/details/gt2oppzabjm.html

Ruby: e.message;  e.backtrace
来源：http://dali.daxiang520.top/Article/details/gt2mgvbfghb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.dianchejie.cn/Article/details/gt2ltvrgvgw.html

[H09] 带错误码的异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rrpzsvsy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jyoumei.cn/Article/details/gt2yertswrx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ivvv.top/Article/details/gt2tuabxlsv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj202588.top/Article/details/gt2kbkjflfp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhongyouzk.top/Article/details/gt2zhbpueqi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.guannengcc.top/Article/details/gt2yhetdvjw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yangfankeji.com/Article/details/gt2vkljtvon.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgennzah.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.redwolf501.top/Article/details/gt2hspdxmae.html

[H10] 资源自动释放
来源：http://dali.tianlin.xyz/Article/details/gt2vmqldpep.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cqqwz.cn/Article/details/gt2qavsuczm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj202588.top/Article/details/gt2wgihygyg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gt2xwlgacam.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sufxvd.cn/Article/details/gt2ykyksrhf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yuxming.cn/Article/details/gt2kmhxmkab.html

Go:   defer f.Close()
来源：http://dali.birdmap.top/Article/details/gt2tatyhbji.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fzhhl.top/Article/details/gt2ywpyzrcp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2zjpizvty.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2oqifoqxc.html

I. 正则表达式
来源：http://dali.gotoacloud.top/Article/details/gt2xnxgehxj.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2rehfjxns.html

[I01] 判断是否匹配
来源：http://dali.shangyingyoupin.top/Article/details/gt2oahrpvuv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nwlcbvkh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gzhubu.top/Article/details/gt2gxtrovxw.html

JS:   /\d+/.test(s)
来源：http://dali.cucudq.cn/Article/details/gt2qmapixxv.html

TS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2ailnzudk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhoulong.xyz/Article/details/gt2xfpnphqc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vwprswvu.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhongyouzk.top/Article/details/gt2ikuolpel.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.fzhhl.top/Article/details/gt2hotuuwod.html

[I02] 提取所有匹配
来源：http://dali.sufxvd.cn/Article/details/gt2puvhrinm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj202588.top/Article/details/gt2rrixkvgn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gotoacloud.top/Article/details/gt2umebtnqp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iyiajwlp.html

TS:   s.match(/\d+/g)
来源：http://dali.hfpthk.cn/Article/details/gt2bxyhfgqd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.0kj1m.cn/Article/details/gt2btsknymk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.vqdsnc.cn/Article/details/gt2qzlaoodg.html

Ruby: s.scan(/\d+/)
来源：http://dali.chenzaomai.com/Article/details/gt2inlidlek.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hammf.cn/Article/details/gt2nmvekmhb.html

[I03] 提取捕获分组
来源：http://dali.nwbrower.top/Article/details/gt2gbldbxwn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.andypj.xyz/Article/details/gt2mdqfwpyt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.wangdashe.top/Article/details/gt2otdnnlfb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.meibo888.top/Article/details/gt2wbcittzk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jpihjakv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xylfe.cn/Article/details/gt2ggdospyj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2chqxkwxr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cashguo.top/Article/details/gt2vtcvcwtv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ivvv.top/Article/details/gt2fgdqibqg.html

[I04] 正则替换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mcfqwysg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vpfarkpf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2rietrydy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ybcxt.top/Article/details/gt2tijkwldp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gt2fptgiwwj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cheryme.top/Article/details/gt2aatgeqkp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gaohongyu789.top/Article/details/gt2rkhrnxcy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.316326.xyz/Article/details/gt2ytetmkjd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinqigufen.top/Article/details/gt2vcoitpit.html

[I05] 按正则拆分
来源：http://dali.xinyue.icu/Article/details/gt2eragvevk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kqgbjthy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hnqzz.top/Article/details/gt2tcddvavb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gt2nzhnkeyk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zqdwaqnx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ivvv.top/Article/details/gt2mifbcapg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xxctbylr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gt2efrafvsq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xinyue.icu/Article/details/gt2gdbcvsci.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuxming.cn/Article/details/gt2wjmkyxbk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gt2uriibdok.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sweek.top/Article/details/gt2fhpxjzsr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ppjwa.cn/Article/details/gt2mhuikyyh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnqzz.top/Article/details/gt2gxqzjjnx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gt2ibxmcelw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gaohongyu789.top/Article/details/gt2waoefqrc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.meibo888.top/Article/details/gt2amaepzns.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gt2qpuslgoi.html

[I07] 忽略大小写与多行模式
来源：http://dali.hongshengwenyu.top/Article/details/gt2ymomszke.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.smart0.xyz/Article/details/gt2lmagwtoo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gt2pwyczdto.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vfwrokke.html

TS:   /error/gim
来源：http://dali.shuidangran.top/Article/details/gt2obunzznt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ydzc1.top/Article/details/gt2klcluabv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gogol.net.cn/Article/details/gt2tpojzrkt.html

Ruby: s.scan(/error/i)
来源：http://dali.daxiang520.top/Article/details/gt2lshfbxli.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.fengsongda.top/Article/details/gt2fgedgzdo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ivvv.top/Article/details/gt2chjmvqqe.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhengqikj.top/Article/details/gt2hbeyqiwe.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tanke756.top/Article/details/gt2kkygdaff.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gt2oaqklysv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guannengcc.top/Article/details/gt2prtelccy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yvedp.cn/Article/details/gt2walvjsza.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bltmkzmj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.guannengcc.top/Article/details/gt2stjwpwas.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zdqjudy.top/Article/details/gt2aavlrfqd.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2xqohxycm.html

J. 日期与时间
来源：http://dali.hywenlv.cn/Article/details/gt2ucsvbecd.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2lhyuhkhx.html

[J01] 获取当前时间
来源：http://dali.chenlongwang.top/Article/details/gt2kpgarvpg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.316326.xyz/Article/details/gt2lhqsooqj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.haohaochexian.top/Article/details/gt2mrcacxkb.html

JS:   new Date();  Date.now()
来源：http://dali.guannengcc.top/Article/details/gt2tzfmpqwe.html

TS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gt2yiheucor.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.pengpengdd.cyou/Article/details/gt2bcvqmphi.html

Go:   time.Now()
来源：http://dali.zdqjudy.top/Article/details/gt2ogsfhxcg.html

Ruby: Time.now
来源：http://dali.ydzc1.top/Article/details/gt2kzuzaoks.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.svipenyu.cn/Article/details/gt2nbxjrebk.html

[J02] 格式化输出
来源：http://dali.feifeiyinyue.top/Article/details/gt2grpwqjbl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yottahyn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yangfankeji.com/Article/details/gt2nwfugwgz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shangyingyoupin.top/Article/details/gt2dgmpprhc.html

TS:   d.toISOString()
来源：http://dali.quarkkingdee.top/Article/details/gt2piaefmgo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.pycfn.com/Article/details/gt2mxgmtnnq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ivvv.top/Article/details/gt2klyilfen.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yvedp.cn/Article/details/gt2fqduekry.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cucudq.cn/Article/details/gt2buvstemr.html

[J03] 字符串解析为日期
来源：http://dali.zhijiandao.cn/Article/details/gt2mgukvsah.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yanxiufei.cn/Article/details/gt2mjbafcmv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj202588.top/Article/details/gt2sdidirtc.html

JS:   new Date("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gt2tkwsyhva.html

TS:   new Date("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gt2rbczkusk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gt2zulzheha.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2hwsuyebw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gt2hlwzgsbw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yuanzhike.top/Article/details/gt2cfhxxpgk.html

[J04] 时间戳与日期互转
来源：http://dali.yueranfly.top/Article/details/gt2kuqefwiy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jlsjyb.cn/Article/details/gt2rxswhoim.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xuanzx.com/Article/details/gt2tveanpvj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.dashuyun.cn/Article/details/gt2mqfnjzla.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cdnleiting.top/Article/details/gt2asuyizpz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cqqwz.cn/Article/details/gt2ykdprjfr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hammf.cn/Article/details/gt2zhgqnmiy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aibaodan.cn/Article/details/gt2ibuwvcvh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yangfankeji.com/Article/details/gt2yuxpqxnq.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenjidiqi.icu/Article/details/gt2irtbokdf.html

Py:   now + timedelta(days=7)
来源：http://dali.jiagoushi.top/Article/details/gt2cpcbfxmk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zdqjudy.top/Article/details/gt2fzjeuege.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jiagoushi.top/Article/details/gt2mmepwaae.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ehwqpu.com/Article/details/gt2bmtucclp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj202588.top/Article/details/gt2sggvsgpj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qukcnqix.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hongshengwenyu.top/Article/details/gt2qwpyateg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yanxiufei.cn/Article/details/gt2rehenzky.html

[J06] 计算两时间之差
来源：http://dali.dianchejie.cn/Article/details/gt2jgsafvet.html

Py:   (end - start).total_seconds()
来源：http://dali.gzhubu.top/Article/details/gt2tldfmvav.html

PHP:  $end->diff($start)->days;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2chdmposn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shangyingyoupin.top/Article/details/gt2duerxafp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.wangshuangyany.cn/Article/details/gt2mattztun.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenlongwang.top/Article/details/gt2lchkldhl.html

Go:   end.Sub(start).Hours()
来源：http://dali.guowangkeji.top/Article/details/gt2zkrzrgrk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.daria6918.cn/Article/details/gt2twgkachm.html

C#:   (end - start).TotalSeconds
来源：http://dali.hysaishi.cn/Article/details/gt2xswvupyd.html


<!-- 参考信息 -->