代发 wailian999

Java: interface Shape { double area(); }
来源：http://dali.nanxinkj.top/Article/details/gt2unyxsqop.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tianlin.xyz/Article/details/gt2qetkupgr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gaohongyu789.top/Article/details/gt2klbskknv.html

C#:   interface IShape { double Area(); }
来源：http://dali.tian-w.cn/Article/details/gt2rbpnogzv.html

[G10] 访问控制
来源：http://dali.ehwqpu.com/Article/details/gt2vbwhbstw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zdqjudy.top/Article/details/gt2dixjaeba.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dmoiecbf.html

JS:   #private 字段；其余公开
来源：http://dali.tianlin.xyz/Article/details/gt2icsnkgyo.html

TS:   public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gt2xaktbwap.html

Java: public / protected / private / 默认包级
来源：http://dali.zhongyouzk.top/Article/details/gt2kmrehhjp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenzaomai.com/Article/details/gt2rfyissyr.html

Ruby: public / protected / private
来源：http://dali.tian-w.cn/Article/details/gt2hllmtvbt.html

C#:   public / protected / private / internal
来源：http://dali.cucudq.cn/Article/details/gt2xhcznuvv.html

[G11] getter / setter
来源：http://dali.daxiang520.top/Article/details/gt2ovcwmpfj.html

Py:   @property 与 @x.setter
来源：http://dali.xziqi.cn/Article/details/gt2zwbonunw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2zldqgzmo.html

JS:   get name() { return this._name; }
来源：http://dali.gotoacloud.top/Article/details/gt2birshrfy.html

TS:   get name(): string { return this._name; }
来源：http://dali.bjfxy.top/Article/details/gt2pggecpwb.html

Java: public String getName() { return name; }
来源：http://dali.nwbrower.top/Article/details/gt2dsyaljww.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gt2clnjghbf.html

Ruby: attr_accessor :name
来源：http://dali.sufxvd.cn/Article/details/gt2udpspnjp.html

C#:   public string Name { get; set; }
来源：http://dali.316326.xyz/Article/details/gt2vrvjgqtm.html

[G12] 对象转字符串
来源：http://dali.gotoacloud.top/Article/details/gt2xpmuezlq.html

Py:   def __str__(self): return self.name
来源：http://dali.cashguo.top/Article/details/gt2izqllrst.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gt2ufutfqga.html

JS:   toString() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2gxhdnvol.html

TS:   toString(): string { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ccquzcpm.html

Java: @Override public String toString() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gt2hzsrjfct.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gt2yftjbaut.html

Ruby: def to_s; @name; end
来源：http://dali.nanxuanxn.top/Article/details/gt2veowajlw.html

C#:   public override string ToString() => Name;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cfxtrmoy.html

[G13] 判断对象类型
来源：http://dali.nanxinkj.top/Article/details/gt2bmhacweu.html

Py:   isinstance(u, User)
来源：http://dali.yvedp.cn/Article/details/gt2qksahyhl.html

PHP:  $u instanceof User
来源：http://dali.havefunace.top/Article/details/gt2enlvilak.html

JS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gt2iwvotgvx.html

TS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gt2yzxruyju.html

Java: u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gt2mxnwkfbu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuetiantiany.cn/Article/details/gt2frsghbui.html

Ruby: u.is_a?(User)
来源：http://dali.yvedp.cn/Article/details/gt2hbcvzwdb.html

C#:   u is User
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qwutxqit.html

[G14] 数据类 / record
来源：http://dali.zhoulong.xyz/Article/details/gt2ufozjvmq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yonumen.top/Article/details/gt2cktssrtt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jqgufenzy.top/Article/details/gt2zeuyvqwm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sweek.top/Article/details/gt2uawxunuk.html

TS:   type User = { name: string; age: number };
来源：http://dali.jyoumei.cn/Article/details/gt2ytomesce.html

Java: record User(String name, int age) {}
来源：http://dali.yangfankeji.com/Article/details/gt2ajlyzaxc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xziqi.cn/Article/details/gt2cjtoptkt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tian-w.cn/Article/details/gt2euewbgbx.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxuanxn.top/Article/details/gt2cvmbtcit.html

[G15] 枚举
来源：http://dali.hnqzz.top/Article/details/gt2flalgxrt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.fzhhl.top/Article/details/gt2nvqsyhgy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zdqjudy.top/Article/details/gt2xcouhdut.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xinyue.icu/Article/details/gt2diamfeuh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gt2egusnsxp.html

Java: enum Color { RED, GREEN }
来源：http://dali.cqqwz.cn/Article/details/gt2uugmacue.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.bjfxy.top/Article/details/gt2nucefoty.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hysaishi.cn/Article/details/gt2yroyvbtx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.birdmap.top/Article/details/gt2foqzyvtv.html

[G16] 对象转数组 / 字典
来源：http://dali.feifeiyinyue.top/Article/details/gt2paauitpj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxinkj.top/Article/details/gt2vhachbar.html

PHP:  get_object_vars($obj);
来源：http://dali.c1oappe.top/Article/details/gt2vobhelwa.html

JS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2jqkfxlau.html

TS:   Object.entries(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2rdfftsek.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnxiangtu.top/Article/details/gt2yuuxozmo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.mhx1999.top/Article/details/gt2nhmlxpon.html

Ruby: obj.instance_variables
来源：http://dali.iojbl.cn/Article/details/gt2rxbmqecb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ydzc1.top/Article/details/gt2xdepoave.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2hfgjmtlw.html

H. 异常与错误处理
来源：http://dali.andypj.xyz/Article/details/gt2oxbtnvln.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2snjyyvic.html

[H01] try / catch 基础
来源：http://dali.shuidangran.top/Article/details/gt2gtxgywyn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jqgfzy.top/Article/details/gt2ldftnqai.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kqljvlxx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gt2hfbwlywb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.daria6918.cn/Article/details/gt2zdavlmaq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2cxewndtx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenjidiqi.icu/Article/details/gt2thtakwaj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.iojbl.cn/Article/details/gt2wuqfbbib.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yonumen.top/Article/details/gt2szymydtc.html

[H02] finally / ensure 收尾
来源：http://dali.hammf.cn/Article/details/gt2otvwcwqt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hnqzz.top/Article/details/gt2hpnsbhqo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gt2pmsntifg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gt2hjwvsdgm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jrqrwjpw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gt2ofydbrtz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yvedp.cn/Article/details/gt2guvamtvh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.fengsongda.top/Article/details/gt2oduimrzz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gt2zqjeibwo.html

[H03] 主动抛出异常
来源：http://dali.wangdashe.top/Article/details/gt2djwovbej.html

Py:   raise ValueError("错误信息")
来源：http://dali.pengpengdd.cyou/Article/details/gt2gmbejfim.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gt2tniqorha.html

JS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gt2kbwlyqxm.html

TS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gt2rftnzsbs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gt2uddwckes.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gaohongyu789.top/Article/details/gt2jcfmgxjc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jiagoushi.top/Article/details/gt2fdiberkv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gt2pntihshc.html

[H04] 自定义异常类型
来源：http://dali.vqdsnc.cn/Article/details/gt2dvtbhxnv.html

Py:   class MyError(Exception): pass
来源：http://dali.cqqwz.cn/Article/details/gt2ipkymopm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gt2kyrlvxtd.html

JS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gt2hkmhgxcp.html

TS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gt2spefxwfj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhengqikj.top/Article/details/gt2cykookbu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yanxiufei.cn/Article/details/gt2nqkygksw.html

Ruby: class MyError < StandardError; end
来源：http://dali.c1oappe.top/Article/details/gt2fsvzvlqq.html

C#:   class MyException : Exception {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2bravzofm.html

[H05] 捕获特定类型
来源：http://dali.havefunace.top/Article/details/gt2rekcbwio.html

Py:   except ValueError as e:
来源：http://dali.fzhhl.top/Article/details/gt2raoqgble.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuanzhike.top/Article/details/gt2eztvbosn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yvedp.cn/Article/details/gt2jpmrwrvc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gt2cdwtqqzg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.daxiang520.top/Article/details/gt2rmqdynxr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jianghu66.top/Article/details/gt2azqfzprb.html

Ruby: rescue ArgumentError => e
来源：http://dali.nanxuanxn.top/Article/details/gt2ldeiwlyn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2mswqsmap.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fengsongda.top/Article/details/gt2iateveme.html

Py:   value = d.get("k") or default
来源：http://dali.ppjwa.cn/Article/details/gt2vyvjnouj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gt2vauffkte.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rppieeji.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gt2eautygey.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2liqjumrp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xylfe.cn/Article/details/gt2ucudnlde.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinqigfzy.top/Article/details/gt2eusbtvlu.html

C#:   obj?.A?.B ?? default
来源：http://dali.gaohongyu789.top/Article/details/gt2sjifvegg.html

[H07] 断言
来源：http://dali.chenlongwang.top/Article/details/gt2znlccdyi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ivvv.top/Article/details/gt2lszrsejp.html

PHP:  assert($x > 0);
来源：http://dali.sweek.top/Article/details/gt2sohausik.html

JS:   console.assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ohsozict.html

TS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gt2ctbtpyfu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cheryme.top/Article/details/gt2omuzyzvj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mrbvdotr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cheryme.top/Article/details/gt2qrbmajqj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gt2nbrrqzzf.html

[H08] 获取错误信息与堆栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hbaavnsh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.havefunace.top/Article/details/gt2wyegwrlz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xinyue.icu/Article/details/gt2agnobedw.html

JS:   e.message;  e.stack
来源：http://dali.yangfankeji.com/Article/details/gt2sdbdzikh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shuidangran.top/Article/details/gt2vetjfiab.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zdqjudy.top/Article/details/gt2eawohrub.html

Go:   err.Error()
来源：http://dali.yueranfly.top/Article/details/gt2nrmlxezz.html

Ruby: e.message;  e.backtrace
来源：http://dali.cheryme.top/Article/details/gt2tomhngpp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fzhhl.top/Article/details/gt2lsbwpfeg.html

[H09] 带错误码的异常
来源：http://dali.redwolf501.top/Article/details/gt2gyaywfgn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ybcxt.top/Article/details/gt2nqxjiwox.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fugbjyvj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yuxming.cn/Article/details/gt2qmqjvurw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.guowangkeji.top/Article/details/gt2yacancqt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhongyouzk.top/Article/details/gt2gletwrvg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daria6918.cn/Article/details/gt2xqrdcxck.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hfpthk.cn/Article/details/gt2eqqpsmbk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shangyingyoupin.top/Article/details/gt2rnqrsglv.html

[H10] 资源自动释放
来源：http://dali.zdqjudy.top/Article/details/gt2qgpzxjos.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.0kj1m.cn/Article/details/gt2vwwwzako.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hywenlv.cn/Article/details/gt2fbyrlfvb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lzqvnhga.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gt2fewwmsaa.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenzaomai.com/Article/details/gt2dokyllsq.html

Go:   defer f.Close()
来源：http://dali.cashguo.top/Article/details/gt2mirwgjzl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jlsjyb.cn/Article/details/gt2ofczodco.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2pemoiyjt.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2ezxybgfg.html

I. 正则表达式
来源：http://dali.dianchejie.cn/Article/details/gt2yidryzai.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2jljwyjov.html

[I01] 判断是否匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2mftwqmqv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ehwqpu.com/Article/details/gt2djxmtiwo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zycfv.cn/Article/details/gt2ressjdod.html

JS:   /\d+/.test(s)
来源：http://dali.sxryk.cn/Article/details/gt2lczndels.html

TS:   /\d+/.test(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ukjnjvyu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.redwolf501.top/Article/details/gt2wrgbfmcm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2juvddvke.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gt2cfqgjfpi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgufenzy.top/Article/details/gt2ogtocbgz.html

[I02] 提取所有匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2scaimddj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nwbrower.top/Article/details/gt2sxunqjql.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.wangdashe.top/Article/details/gt2wnvkqlwc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ymxfxfxx.html

TS:   s.match(/\d+/g)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hmjrdoov.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uahwfimf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tian-w.cn/Article/details/gt2rsqlkipb.html

Ruby: s.scan(/\d+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2auwryiyw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cucudq.cn/Article/details/gt2bctwooaj.html

[I03] 提取捕获分组
来源：http://dali.redwolf501.top/Article/details/gt2krwsmhec.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.fengsongda.top/Article/details/gt2ffvpzper.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cqqwz.cn/Article/details/gt2bgvafrpx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tian-w.cn/Article/details/gt2nvaayrjn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gotoacloud.top/Article/details/gt2duayhrxh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cucudq.cn/Article/details/gt2jpxrspav.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.meibo888.top/Article/details/gt2kaggjpjt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.dianchejie.cn/Article/details/gt2retsgzna.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hysaishi.cn/Article/details/gt2eqcbraba.html

[I04] 正则替换
来源：http://dali.gotoacloud.top/Article/details/gt2wecatjjr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hysaishi.cn/Article/details/gt2ejlwrzux.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.redwolf501.top/Article/details/gt2ptqugchs.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.aibaodan.cn/Article/details/gt2oryamyah.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.meibo888.top/Article/details/gt2yboxukit.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.smart0.xyz/Article/details/gt2lkzyeokt.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yonumen.top/Article/details/gt2wqnytbps.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.0kj1m.cn/Article/details/gt2rivpjlvi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tian-w.cn/Article/details/gt2dvrvedhp.html

[I05] 按正则拆分
来源：http://dali.hfpthk.cn/Article/details/gt2szanpsxm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tianlin.xyz/Article/details/gt2vfdmkbtl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ydzc1.top/Article/details/gt2lbhbgxjz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gt2zdlhlmqj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gt2veejtyxz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yongpay.top/Article/details/gt2koiehlqw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhengqikj.top/Article/details/gt2ojkkparb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gt2cforlqsu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xuetiantiany.cn/Article/details/gt2wnodudle.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhixingplan.top/Article/details/gt2mmuqphdd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gt2baqwbxbv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.mhx1999.top/Article/details/gt2spspzuoa.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jiagoushi.top/Article/details/gt2dmqrluyl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gt2clzzpeqr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gt2ivyjkmrb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yongpay.top/Article/details/gt2ofajqeyq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.fzhhl.top/Article/details/gt2mdvbraon.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gt2inehuaex.html

[I07] 忽略大小写与多行模式
来源：http://dali.mhx1999.top/Article/details/gt2omgzjvvp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.9152youxi.cn/Article/details/gt2fikmnept.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shuidangran.top/Article/details/gt2bhbdqghp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yueranfly.top/Article/details/gt2sxtwsqin.html

TS:   /error/gim
来源：http://dali.cucudq.cn/Article/details/gt2cnkrflqj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nanxinkj.top/Article/details/gt2vzkvrybf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinqigufen.top/Article/details/gt2tjhyhdvo.html

Ruby: s.scan(/error/i)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2noxcxnme.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnqzz.top/Article/details/gt2dzgafpsn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.vqdsnc.cn/Article/details/gt2gojnxexd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hywenlv.cn/Article/details/gt2qlchsajb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gt2vutnvoke.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sysykeji.top/Article/details/gt2roixixsr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.iojbl.cn/Article/details/gt2tehiilnr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.fengsongda.top/Article/details/gt2abvijntb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yvedp.cn/Article/details/gt2vdfuxntg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yuanzhike.top/Article/details/gt2ppfowilb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2obgdiyba.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2yeewstqs.html

J. 日期与时间
来源：http://dali.fzhhl.top/Article/details/gt2xsuqlaak.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2kqzjrujr.html

[J01] 获取当前时间
来源：http://dali.wangdashe.top/Article/details/gt2gcboqokm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.guowangkeji.top/Article/details/gt2kminakuv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gt2vexwcnbn.html

JS:   new Date();  Date.now()
来源：http://dali.yuxming.cn/Article/details/gt2cckftkmo.html

TS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gt2qjgkulnt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.andypj.xyz/Article/details/gt2lqhvsrlv.html

Go:   time.Now()
来源：http://dali.haohaochexian.top/Article/details/gt2bclnfnie.html

Ruby: Time.now
来源：http://dali.xuetiantiany.cn/Article/details/gt2jwkayshz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gzhubu.top/Article/details/gt2swhvzpql.html

[J02] 格式化输出
来源：http://dali.jinqigfzy.top/Article/details/gt2fsqykyzd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sypotpaa.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cucudq.cn/Article/details/gt2uxcogbwg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gotoacloud.top/Article/details/gt2eybizyrw.html

TS:   d.toISOString()
来源：http://dali.yvedp.cn/Article/details/gt2pvgdwdtb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jyoumei.cn/Article/details/gt2laqpnwej.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jiagoushi.top/Article/details/gt2dcnpwjuh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.meibo888.top/Article/details/gt2zeoitizv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shuidangran.top/Article/details/gt2hbhzbmup.html

[J03] 字符串解析为日期
来源：http://dali.ivvv.top/Article/details/gt2fsuskphj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.9152youxi.cn/Article/details/gt2wzpyjbqe.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nanxuanxn.top/Article/details/gt2vsqdznpf.html

JS:   new Date("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gt2obicmzkl.html

TS:   new Date("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gt2dkvehphs.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gt2irsplhmn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gt2hlylznxr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ahdcngbd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yongpay.top/Article/details/gt2bmcmxurt.html

[J04] 时间戳与日期互转
来源：http://dali.yj202588.top/Article/details/gt2wfpgvgld.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhengqikj.top/Article/details/gt2uwlgjnzr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jianghu66.top/Article/details/gt2bzcmwrpr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bawwhtmi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tanke756.top/Article/details/gt2sqnpfixq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.snrcjt.cn/Article/details/gt2pqieoxao.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2jcqdqyrb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinqigfzy.top/Article/details/gt2vwcaztmq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zdqjudy.top/Article/details/gt2gndecjyu.html

[J05] 时间加减（加 7 天）
来源：http://dali.meibo888.top/Article/details/gt2urqrhdhz.html

Py:   now + timedelta(days=7)
来源：http://dali.wangdashe.top/Article/details/gt2drbngggi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.kuanghao11.cn/Article/details/gt2favcangq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gt2gspdlmjs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daxiang520.top/Article/details/gt2cbeuqlui.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sufxvd.cn/Article/details/gt2phkikxdx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yongpay.top/Article/details/gt2xnqwpwkv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.andypj.xyz/Article/details/gt2sqzxtsjb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ehwqpu.com/Article/details/gt2heiunjid.html

[J06] 计算两时间之差
来源：http://dali.guowangkeji.top/Article/details/gt2buxnwcsx.html

Py:   (end - start).total_seconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2soyxefcw.html

PHP:  $end->diff($start)->days;
来源：http://dali.fzhhl.top/Article/details/gt2mzymeyqa.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gogol.net.cn/Article/details/gt2itguujcu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hammf.cn/Article/details/gt2pcqolqgh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xziqi.cn/Article/details/gt2nboqgqup.html

Go:   end.Sub(start).Hours()
来源：http://dali.yueranfly.top/Article/details/gt2rhpqjtgs.html

Ruby: end - start                 # 返回秒数
来源：http://dali.bjfxy.top/Article/details/gt2hapxfdcs.html

C#:   (end - start).TotalSeconds
来源：http://dali.gaohongyu789.top/Article/details/gt2cprdajhh.html

[J07] 比较两个日期
来源：http://dali.redwolf501.top/Article/details/gt2mcqqecvr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gt2oziznfsr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.0kj1m.cn/Article/details/gt2dengzqzw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hnqzz.top/Article/details/gt2ufnbrmrf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sysykeji.top/Article/details/gt2tcppxuzf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ehwqpu.com/Article/details/gt2dfozcokm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ehwqpu.com/Article/details/gt2rrdqbsmw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gt2zknpzkze.html


<!-- 参考信息 -->