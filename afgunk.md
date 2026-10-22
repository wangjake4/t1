代发 wailian999

C#:   public override string Greet() => "admin";
来源：http://dali.hnxiangtu.top/Article/details/gt2uvhwnnpy.html

[G07] 调用父类方法
来源：http://dali.wangshuangyany.cn/Article/details/gt2kzjvngcy.html

Py:   super().greet()
来源：http://dali.cqqwz.cn/Article/details/gt2aeambieo.html

PHP:  parent::greet();
来源：http://dali.sxryk.cn/Article/details/gt2lzfzdjkl.html

JS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gt2ikvbejfp.html

TS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gt2focqfkuf.html

Java: super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2iymzhilc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gogol.net.cn/Article/details/gt2bbopugeu.html

Ruby: super
来源：http://dali.gaohongyu789.top/Article/details/gt2prgigecm.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkqpaug.html

[G08] 静态方法与属性
来源：http://dali.yj202588.top/Article/details/gt2qrxrpjmb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.fengsongda.top/Article/details/gt2vxmlnxas.html

PHP:  public static function f() {}
来源：http://dali.yj202588.top/Article/details/gt2nbpbhceo.html

JS:   static f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2kfvstdwk.html

TS:   static f(): void {}
来源：http://dali.guannengcc.top/Article/details/gt2ctbuwxaj.html

Java: static void f() {}
来源：http://dali.hammf.cn/Article/details/gt2tetslhga.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yangfankeji.com/Article/details/gt2ebnhefqz.html

Ruby: def self.f; end
来源：http://dali.nwbrower.top/Article/details/gt2uzdwjvxg.html

C#:   public static void F() {}
来源：http://dali.hysaishi.cn/Article/details/gt2gxzgshdh.html

[G09] 接口 / 抽象类
来源：http://dali.jyoumei.cn/Article/details/gt2dtjwossj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tanke756.top/Article/details/gt2faxhhytq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnqzz.top/Article/details/gt2wwwjtukf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinghuilouyu.cn/Article/details/gt2veoakiot.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangdashe.top/Article/details/gt2quvxhlcr.html

Java: interface Shape { double area(); }
来源：http://dali.shzxlz.cn/Article/details/gt2viqhceuv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cqqwz.cn/Article/details/gt2dqjqikjs.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.kuanghao11.cn/Article/details/gt2flivsbts.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2uxtbcgri.html

[G10] 访问控制
来源：http://dali.xuanzx.com/Article/details/gt2xfldrsbs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.0kj1m.cn/Article/details/gt2gsyqahef.html

PHP:  public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gt2oefxhlft.html

JS:   #private 字段；其余公开
来源：http://dali.dashuyun.cn/Article/details/gt2osexjmes.html

TS:   public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gt2cnjcnhtk.html

Java: public / protected / private / 默认包级
来源：http://dali.pycfn.com/Article/details/gt2rkwaevfg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gaohongyu789.top/Article/details/gt2zqkmoiwb.html

Ruby: public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gt2piakqgdc.html

C#:   public / protected / private / internal
来源：http://dali.hnqzz.top/Article/details/gt2jdjjuswi.html

[G11] getter / setter
来源：http://dali.hongshengwenyu.top/Article/details/gt2odhwkvch.html

Py:   @property 与 @x.setter
来源：http://dali.zdqjudy.top/Article/details/gt2niwtxtvr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gt2xvpahgna.html

JS:   get name() { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gt2iwrgspkp.html

TS:   get name(): string { return this._name; }
来源：http://dali.sweek.top/Article/details/gt2wcvojfmm.html

Java: public String getName() { return name; }
来源：http://dali.yj20258888.top/Article/details/gt2rdqbumzo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gt2yljarzft.html

Ruby: attr_accessor :name
来源：http://dali.0kj1m.cn/Article/details/gt2zpnkobbq.html

C#:   public string Name { get; set; }
来源：http://dali.9152youxi.cn/Article/details/gt2infznwqb.html

[G12] 对象转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2xedihwnn.html

Py:   def __str__(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gt2kjlmliqk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2otmgfwsz.html

JS:   toString() { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gt2culprhrs.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gt2ydxhwaxn.html

Java: @Override public String toString() { return name; }
来源：http://dali.shuidangran.top/Article/details/gt2flfbgnvw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gt2ytycyqqb.html

Ruby: def to_s; @name; end
来源：http://dali.sufxvd.cn/Article/details/gt2jtcgnzsl.html

C#:   public override string ToString() => Name;
来源：http://dali.zhixingplan.top/Article/details/gt2huyhmbks.html

[G13] 判断对象类型
来源：http://dali.gogol.net.cn/Article/details/gt2elfpokch.html

Py:   isinstance(u, User)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ljbahfck.html

PHP:  $u instanceof User
来源：http://dali.yj202588.top/Article/details/gt2kpsmshve.html

JS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gt2xnnkowcf.html

TS:   u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gt2capaotaq.html

Java: u instanceof User
来源：http://dali.sxryk.cn/Article/details/gt2xscsbmyj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hfpthk.cn/Article/details/gt2hbjgyxlc.html

Ruby: u.is_a?(User)
来源：http://dali.gzhubu.top/Article/details/gt2nronzier.html

C#:   u is User
来源：http://dali.tanke756.top/Article/details/gt2iiaydphb.html

[G14] 数据类 / record
来源：http://dali.zhoulong.xyz/Article/details/gt2ltqjszvj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aysmvcgq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aizwys.cn/Article/details/gt2illogyao.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yvedp.cn/Article/details/gt2cbkbupxw.html

TS:   type User = { name: string; age: number };
来源：http://dali.mhx1999.top/Article/details/gt2rpzcvvet.html

Java: record User(String name, int age) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2dohmbrbq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.0kj1m.cn/Article/details/gt2iopjjtcn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.svipenyu.cn/Article/details/gt2khqpsohw.html

C#:   record User(string Name, int Age);
来源：http://dali.chenlongwang.top/Article/details/gt2augsajdz.html

[G15] 枚举
来源：http://dali.wangdashe.top/Article/details/gt2akysfeik.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.316326.xyz/Article/details/gt2bgqngklf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hvazhenp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.andypj.xyz/Article/details/gt2wwknmiyv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.bjfxy.top/Article/details/gt2lkdojrlv.html

Java: enum Color { RED, GREEN }
来源：http://dali.wangdashe.top/Article/details/gt2djtviubb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yvedp.cn/Article/details/gt2svxgpxsj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.pycfn.com/Article/details/gt2vgyydxvm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuanzx.com/Article/details/gt2vzgtgwat.html

[G16] 对象转数组 / 字典
来源：http://dali.bjfxy.top/Article/details/gt2ipogiopa.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenlongwang.top/Article/details/gt2nzdsgsac.html

PHP:  get_object_vars($obj);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aajvpdbu.html

JS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gt2ayntunpi.html

TS:   Object.entries(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2haridfrc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenjidiqi.icu/Article/details/gt2jjlsndcu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hfpthk.cn/Article/details/gt2hyfojwnb.html

Ruby: obj.instance_variables
来源：http://dali.cqqwz.cn/Article/details/gt2tfldspvo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shzxlz.cn/Article/details/gt2vnozayah.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tdcgcyhg.html

H. 异常与错误处理
来源：http://dali.yj202588.top/Article/details/gt2gmnyanjv.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2nyfemnks.html

[H01] try / catch 基础
来源：http://dali.cashguo.top/Article/details/gt2vzfxcnwk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.birdmap.top/Article/details/gt2nrczqfjj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.dashuyun.cn/Article/details/gt2txdqkuzi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.daxiang520.top/Article/details/gt2vbtkuluq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gt2mdusezip.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aibaodan.cn/Article/details/gt2ldavgflt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lspwvcfz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2aothbjut.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ydzc1.top/Article/details/gt2hzkiuwps.html

[H02] finally / ensure 收尾
来源：http://dali.hammf.cn/Article/details/gt2ypkyuorl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.guannengcc.top/Article/details/gt2ysvkktku.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gt2mvlgzcsu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gt2gozsjnkf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gt2hqyybouo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gt2bcudmyum.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinghuilouyu.cn/Article/details/gt2btptwsyu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj20258.top/Article/details/gt2bacoohwa.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gt2vunlwodq.html

[H03] 主动抛出异常
来源：http://dali.dashuyun.cn/Article/details/gt2cjfpjthn.html

Py:   raise ValueError("错误信息")
来源：http://dali.jiagoushi.top/Article/details/gt2xvjlqprr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gt2utafpnja.html

JS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gt2xuclpvfd.html

TS:   throw new Error("错误信息");
来源：http://dali.jianghu66.top/Article/details/gt2awhgyeuy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gt2egwxckpv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hammf.cn/Article/details/gt2iqhdnrie.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cqqwz.cn/Article/details/gt2adensuwk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gt2ejrebfgc.html

[H04] 自定义异常类型
来源：http://dali.snrcjt.cn/Article/details/gt2dopcwoyz.html

Py:   class MyError(Exception): pass
来源：http://dali.chenlongwang.top/Article/details/gt2yidzxzub.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2tjzjqglc.html

JS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gt2zrzzmmlg.html

TS:   class MyError extends Error {}
来源：http://dali.daxiang520.top/Article/details/gt2rzyxttlx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gt2eyuskzcx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.quarkkingdee.top/Article/details/gt2rqfkmhnb.html

Ruby: class MyError < StandardError; end
来源：http://dali.sxryk.cn/Article/details/gt2ukfybtdo.html

C#:   class MyException : Exception {}
来源：http://dali.yj202588.top/Article/details/gt2bpkbfvkg.html

[H05] 捕获特定类型
来源：http://dali.dashuyun.cn/Article/details/gt2qogpuqxw.html

Py:   except ValueError as e:
来源：http://dali.jlsjyb.cn/Article/details/gt2dunquxmt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.andypj.xyz/Article/details/gt2pxljuszi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenzaomai.com/Article/details/gt2fxiojobr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.meibo888.top/Article/details/gt2ocboolrn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cashguo.top/Article/details/gt2ouroxaai.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ehwqpu.com/Article/details/gt2bgdsunjy.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2mabbakws.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2ldvcocsp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhoulong.xyz/Article/details/gt2rsthzoxo.html

Py:   value = d.get("k") or default
来源：http://dali.jqgfzy.top/Article/details/gt2ttmjtmen.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gt2isbuyvid.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258888.top/Article/details/gt2fqvfuiuj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gt2mpwyhpoy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yongpay.top/Article/details/gt2eknhsaem.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xinyue.icu/Article/details/gt2ssloutlf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jianghu66.top/Article/details/gt2fucnvmie.html

C#:   obj?.A?.B ?? default
来源：http://dali.sysykeji.top/Article/details/gt2gxupfdkm.html

[H07] 断言
来源：http://dali.yanxiufei.cn/Article/details/gt2kedjhcte.html

Py:   assert x > 0, "必须为正"
来源：http://dali.mhx1999.top/Article/details/gt2fekqlfrq.html

PHP:  assert($x > 0);
来源：http://dali.daxiang520.top/Article/details/gt2pkeswwlm.html

JS:   console.assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gt2meihnwca.html

TS:   console.assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gt2hftrrayr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxinkj.top/Article/details/gt2xelrhtfg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hywenlv.cn/Article/details/gt2msjdjine.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ehwqpu.com/Article/details/gt2entfrmrf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dianchejie.cn/Article/details/gt2midzgmmh.html

[H08] 获取错误信息与堆栈
来源：http://dali.yanxiufei.cn/Article/details/gt2cqxuhvpc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ylkajxxy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.vqdsnc.cn/Article/details/gt2ubwmznau.html

JS:   e.message;  e.stack
来源：http://dali.cqqwz.cn/Article/details/gt2bfirfsyu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pengpengdd.cyou/Article/details/gt2izyrelxn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.andypj.xyz/Article/details/gt2cqnefqlw.html

Go:   err.Error()
来源：http://dali.gotoacloud.top/Article/details/gt2ilpzgwbu.html

Ruby: e.message;  e.backtrace
来源：http://dali.birdmap.top/Article/details/gt2rahldwte.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zdqjudy.top/Article/details/gt2eqckyiis.html

[H09] 带错误码的异常
来源：http://dali.xziqi.cn/Article/details/gt2yucvgvnz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guannengcc.top/Article/details/gt2wfkofnjm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yonumen.top/Article/details/gt2ymyoenmo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jyoumei.cn/Article/details/gt2ckfxgpub.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.bjfxy.top/Article/details/gt2motrihzo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jqgfzy.top/Article/details/gt2jkgwtklk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinqigufen.top/Article/details/gt2gxuoixgv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xziqi.cn/Article/details/gt2hecjuivy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.daxiang520.top/Article/details/gt2nxxpeunm.html

[H10] 资源自动释放
来源：http://dali.iojbl.cn/Article/details/gt2roetfijs.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ycfdsseh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhoulong.xyz/Article/details/gt2cxowtreu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.svipenyu.cn/Article/details/gt2fmazched.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gt2lxcdmhgj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guannengcc.top/Article/details/gt2dbnbtmzu.html

Go:   defer f.Close()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hddkoqvn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ngipbwcr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2qwgdffms.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lnaoojla.html

I. 正则表达式
来源：http://dali.wangshuangyany.cn/Article/details/gt2aljprsua.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2ucshspzl.html

[I01] 判断是否匹配
来源：http://dali.zhixingplan.top/Article/details/gt2uerefmdu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cdnleiting.top/Article/details/gt2vxzkymha.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.andypj.xyz/Article/details/gt2tvanbmib.html

JS:   /\d+/.test(s)
来源：http://dali.cashguo.top/Article/details/gt2tkhkkixc.html

TS:   /\d+/.test(s)
来源：http://dali.hfpthk.cn/Article/details/gt2ipnnlnpu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tanke756.top/Article/details/gt2qhrvoxif.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bsfrdqju.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qfevyvol.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.aibaodan.cn/Article/details/gt2uzybtjna.html

[I02] 提取所有匹配
来源：http://dali.feifeiyinyue.top/Article/details/gt2tcerscok.html

Py:   re.findall(r"\d+", s)
来源：http://dali.haohaochexian.top/Article/details/gt2ftxbcbsu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.smart0.xyz/Article/details/gt2xuflrazg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.feifeiyinyue.top/Article/details/gt2futbhxhi.html

TS:   s.match(/\d+/g)
来源：http://dali.kuanghao11.cn/Article/details/gt2mpqzlsex.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nwbrower.top/Article/details/gt2ueyctxhk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gaohongyu789.top/Article/details/gt2tjvksycx.html

Ruby: s.scan(/\d+/)
来源：http://dali.gaohongyu789.top/Article/details/gt2cobjmugt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ydzc1.top/Article/details/gt2fqhpagsq.html

[I03] 提取捕获分组
来源：http://dali.jinqigfzy.top/Article/details/gt2pfelcwpl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ngwfnqra.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.c1oappe.top/Article/details/gt2uxcpedfr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.guowangkeji.top/Article/details/gt2qapfwwxy.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jqgfzy.top/Article/details/gt2beemyeza.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.wangshuangyany.cn/Article/details/gt2yetgopyo.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.meibo888.top/Article/details/gt2vsiuhqoi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hywenlv.cn/Article/details/gt2uommcfzx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hongshengwenyu.top/Article/details/gt2hluscijd.html

[I04] 正则替换
来源：http://dali.aizwys.cn/Article/details/gt2qusoenmi.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.iojbl.cn/Article/details/gt2mynxpbtv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj202588.top/Article/details/gt2ieabjkgg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zycfv.cn/Article/details/gt2kjicalzc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.pycfn.com/Article/details/gt2levkzvob.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gt2gsgbhvmb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.dashuyun.cn/Article/details/gt2qnmvtvev.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yanxiufei.cn/Article/details/gt2aolsahoq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gt2tdakdnyt.html

[I05] 按正则拆分
来源：http://dali.yongpay.top/Article/details/gt2euydqdsl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dmvoyuhj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258888.top/Article/details/gt2cosvdwsa.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gt2pnwqpeur.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gt2mxklalso.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhongyouzk.top/Article/details/gt2huceubqh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sysykeji.top/Article/details/gt2effcqloi.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fpwkxuhy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.316326.xyz/Article/details/gt2dfnbmalh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mgbjrimo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gt2kxodgstn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yangfankeji.com/Article/details/gt2mkqhrasn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhixingplan.top/Article/details/gt2okkuyrwq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.316326.xyz/Article/details/gt2ajnwdtkg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gt2ebgagojk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xylfe.cn/Article/details/gt2viqcvsoa.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenjidiqi.icu/Article/details/gt2pukmgprv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gt2svplggtn.html

[I07] 忽略大小写与多行模式
来源：http://dali.iojbl.cn/Article/details/gt2ritteviw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.aizwys.cn/Article/details/gt2adliwbrl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gotoacloud.top/Article/details/gt2copnpyvo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.quarkkingdee.top/Article/details/gt2fyqhnybg.html

TS:   /error/gim
来源：http://dali.tianlin.xyz/Article/details/gt2bbbovujo.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.0kj1m.cn/Article/details/gt2btqiztmn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ubontcht.html

Ruby: s.scan(/error/i)
来源：http://dali.jqgfzy.top/Article/details/gt2pxuzguoc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pfhyjizf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tian-w.cn/Article/details/gt2ynrcvpey.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wverhcln.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ybcxt.top/Article/details/gt2lsrqbtgb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258.top/Article/details/gt2hgwibvpy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jianghu66.top/Article/details/gt2ehyqxlqw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tian-w.cn/Article/details/gt2ufcxldil.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhiwuduotai.top/Article/details/gt2qldxarpu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sysykeji.top/Article/details/gt2pvjxlrpc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.pycfn.com/Article/details/gt2yqekjkpg.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2dbmkljrq.html

J. 日期与时间
来源：http://dali.yj202588.top/Article/details/gt2cjynznhq.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2ztixozea.html

[J01] 获取当前时间
来源：http://dali.hfpthk.cn/Article/details/gt2uygsuabn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shzxlz.cn/Article/details/gt2rxwkfbtd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gaohongyu789.top/Article/details/gt2fnjpybye.html

JS:   new Date();  Date.now()
来源：http://dali.hammf.cn/Article/details/gt2xebjydib.html

TS:   new Date();  Date.now()
来源：http://dali.wangdashe.top/Article/details/gt2rvtsjjcl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinqigufen.top/Article/details/gt2pgyskjmp.html

Go:   time.Now()
来源：http://dali.yuanzhike.top/Article/details/gt2wiikhsoi.html

Ruby: Time.now
来源：http://dali.shangyingyoupin.top/Article/details/gt2astzqecx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.guannengcc.top/Article/details/gt2kaxtqrgd.html

[J02] 格式化输出
来源：http://dali.dashuyun.cn/Article/details/gt2ndenagfr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xinyue.icu/Article/details/gt2isnfhvsm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.guowangkeji.top/Article/details/gt2ztfkmxqu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenlongwang.top/Article/details/gt2fxahneoq.html

TS:   d.toISOString()
来源：http://dali.ybcxt.top/Article/details/gt2uqanozxo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.haohaochexian.top/Article/details/gt2bvsqonbo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sufxvd.cn/Article/details/gt2hefawuae.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guowangkeji.top/Article/details/gt2darsnmti.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.svipenyu.cn/Article/details/gt2ymjttott.html

[J03] 字符串解析为日期
来源：http://dali.cdnleiting.top/Article/details/gt2wfjwxoub.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.guannengcc.top/Article/details/gt2yxmrzleq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.aibaodan.cn/Article/details/gt2kuaddxdl.html

JS:   new Date("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gt2yrsfrpwa.html

TS:   new Date("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2fjdccpdj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gt2kdtivapd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gt2vlfkcuhk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gt2vnugadga.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.pycfn.com/Article/details/gt2prdkufjb.html

[J04] 时间戳与日期互转
来源：http://dali.birdmap.top/Article/details/gt2aieogtdg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.havefunace.top/Article/details/gt2rghidkah.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258888.top/Article/details/gt2lxtyhxej.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zdqjudy.top/Article/details/gt2vqmukmqz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.haohaochexian.top/Article/details/gt2mtvefchx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.c1oappe.top/Article/details/gt2qtosygku.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2yqqyynjt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aibaodan.cn/Article/details/gt2ltwbpfdw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jqgfzy.top/Article/details/gt2jlildsdf.html

[J05] 时间加减（加 7 天）
来源：http://dali.yvedp.cn/Article/details/gt2maauxlsx.html

Py:   now + timedelta(days=7)
来源：http://dali.cashguo.top/Article/details/gt2zmsbxuka.html


<!-- 参考信息 -->