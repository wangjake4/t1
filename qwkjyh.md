代发 wailian999

Ruby: super
来源：http://dali.fzhhl.top/Article/details/gt2kgnqvllo.html

C#:   base.Greet();
来源：http://dali.zdqjudy.top/Article/details/gt2gsymjifp.html

[G08] 静态方法与属性
来源：http://dali.dashuyun.cn/Article/details/gt2xmbovjsk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2badezjtu.html

PHP:  public static function f() {}
来源：http://dali.nwbrower.top/Article/details/gt2krtokmhl.html

JS:   static f() {}
来源：http://dali.nwbrower.top/Article/details/gt2ybpbbkgz.html

TS:   static f(): void {}
来源：http://dali.zhixingplan.top/Article/details/gt2tlqsghwl.html

Java: static void f() {}
来源：http://dali.hywenlv.cn/Article/details/gt2vwxxebai.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenlongwang.top/Article/details/gt2fvsmjewi.html

Ruby: def self.f; end
来源：http://dali.tian-w.cn/Article/details/gt2wytiprve.html

C#:   public static void F() {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2vvqnplrn.html

[G09] 接口 / 抽象类
来源：http://dali.fengsongda.top/Article/details/gt2ppuxmwtz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jtrplmuj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nwbrower.top/Article/details/gt2hfheybue.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.redwolf501.top/Article/details/gt2dtlwxmqs.html

TS:   interface Shape { area(): number; }
来源：http://dali.yongpay.top/Article/details/gt2gyeyzody.html

Java: interface Shape { double area(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2adczjqdr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fengsongda.top/Article/details/gt2qldlgflr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daxiang520.top/Article/details/gt2ignccdcm.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenzaomai.com/Article/details/gt2fwmfeolk.html

[G10] 访问控制
来源：http://dali.zhengqikj.top/Article/details/gt2dfxsfkwy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gaohongyu789.top/Article/details/gt2joujcdbb.html

PHP:  public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gt2objvhihp.html

JS:   #private 字段；其余公开
来源：http://dali.yuanzhike.top/Article/details/gt2xytazoal.html

TS:   public / protected / private
来源：http://dali.andypj.xyz/Article/details/gt2ozqcseus.html

Java: public / protected / private / 默认包级
来源：http://dali.yueranfly.top/Article/details/gt2jzvlopgi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yanxiufei.cn/Article/details/gt2xocssywa.html

Ruby: public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gt2hrqviipf.html

C#:   public / protected / private / internal
来源：http://dali.wangdashe.top/Article/details/gt2kkhfahag.html

[G11] getter / setter
来源：http://dali.bjfxy.top/Article/details/gt2xvpqxagr.html

Py:   @property 与 @x.setter
来源：http://dali.chenlongwang.top/Article/details/gt2vpznnpnl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tedqyuta.html

JS:   get name() { return this._name; }
来源：http://dali.shzxlz.cn/Article/details/gt2lqhlryiz.html

TS:   get name(): string { return this._name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2ohtnlrmg.html

Java: public String getName() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gt2bvyzmiph.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ymdqxsav.html

Ruby: attr_accessor :name
来源：http://dali.feifeiyinyue.top/Article/details/gt2gszysijq.html

C#:   public string Name { get; set; }
来源：http://dali.hfpthk.cn/Article/details/gt2pttliioo.html

[G12] 对象转字符串
来源：http://dali.jianghu66.top/Article/details/gt2wtldckpg.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgufenzy.top/Article/details/gt2ojxbmlzv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gt2qawscjmv.html

JS:   toString() { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gt2phdpxqkg.html

TS:   toString(): string { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2bennxhrl.html

Java: @Override public String toString() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2iirzbnja.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gt2xigdisnr.html

Ruby: def to_s; @name; end
来源：http://dali.zhengqikj.top/Article/details/gt2chtdtzbz.html

C#:   public override string ToString() => Name;
来源：http://dali.smart0.xyz/Article/details/gt2vntxkxhp.html

[G13] 判断对象类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2xbtynvcc.html

Py:   isinstance(u, User)
来源：http://dali.hfpthk.cn/Article/details/gt2nozievfl.html

PHP:  $u instanceof User
来源：http://dali.xuanzx.com/Article/details/gt2icivohum.html

JS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gt2jjarvqcj.html

TS:   u instanceof User
来源：http://dali.sxryk.cn/Article/details/gt2ezubmgqv.html

Java: u instanceof User
来源：http://dali.andypj.xyz/Article/details/gt2wldakihr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.snrcjt.cn/Article/details/gt2fpowyqaw.html

Ruby: u.is_a?(User)
来源：http://dali.ehwqpu.com/Article/details/gt2jsbyaxtl.html

C#:   u is User
来源：http://dali.yj20258.top/Article/details/gt2twewsqmy.html

[G14] 数据类 / record
来源：http://dali.zhengqikj.top/Article/details/gt2zhwfixju.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cqqwz.cn/Article/details/gt2bpfnfgoo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hywenlv.cn/Article/details/gt2tmdgitjc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gzhubu.top/Article/details/gt2nvltgyqa.html

TS:   type User = { name: string; age: number };
来源：http://dali.cdnleiting.top/Article/details/gt2akszyjcz.html

Java: record User(String name, int age) {}
来源：http://dali.jianghu66.top/Article/details/gt2ytxqzpvu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sxryk.cn/Article/details/gt2owninavl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xinyue.icu/Article/details/gt2osgaogdu.html

C#:   record User(string Name, int Age);
来源：http://dali.havefunace.top/Article/details/gt2ucvuaeui.html

[G15] 枚举
来源：http://dali.ppjwa.cn/Article/details/gt2agnyvyrv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gaohongyu789.top/Article/details/gt2xhflqouk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuanzx.com/Article/details/gt2ybdwiwyu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yongpay.top/Article/details/gt2hztdidcc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ivvv.top/Article/details/gt2crbiydlb.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenlongwang.top/Article/details/gt2bdgmxztd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenlongwang.top/Article/details/gt2krlkukoe.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yonumen.top/Article/details/gt2nbytjtps.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gt2stvnrntt.html

[G16] 对象转数组 / 字典
来源：http://dali.yongpay.top/Article/details/gt2vnchemoy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jlsjyb.cn/Article/details/gt2vpukizlp.html

PHP:  get_object_vars($obj);
来源：http://dali.yj202588.top/Article/details/gt2ricvvrbg.html

JS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2usvuzjep.html

TS:   Object.entries(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gphfodyt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.pengpengdd.cyou/Article/details/gt2pythfknd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangdashe.top/Article/details/gt2ticnohva.html

Ruby: obj.instance_variables
来源：http://dali.jinqigfzy.top/Article/details/gt2pbktqwck.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sufxvd.cn/Article/details/gt2hwcenxpw.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2cmqigvwo.html

H. 异常与错误处理
来源：http://dali.cdnleiting.top/Article/details/gt2twwicpnb.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2mlcncvlh.html

[H01] try / catch 基础
来源：http://dali.hfpthk.cn/Article/details/gt2brusfycv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigufen.top/Article/details/gt2hwpgxpll.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shzxlz.cn/Article/details/gt2aytueelu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gt2htaoeetg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gt2iyxrkgbd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aizwys.cn/Article/details/gt2fjgjsmim.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhiwuduotai.top/Article/details/gt2ubofohom.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj202588.top/Article/details/gt2ruassvrf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cqqwz.cn/Article/details/gt2ylqplcck.html

[H02] finally / ensure 收尾
来源：http://dali.xuetiantiany.cn/Article/details/gt2ucounzhk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.daxiang520.top/Article/details/gt2chtzzzvs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2nsgyeycc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2crvsvjqk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gt2qqkdyqgp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2uehkbdth.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xziqi.cn/Article/details/gt2ojtawsvb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aibaodan.cn/Article/details/gt2sdrxxwfk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yj202588.top/Article/details/gt2unqrohdb.html

[H03] 主动抛出异常
来源：http://dali.vqdsnc.cn/Article/details/gt2hmsefekd.html

Py:   raise ValueError("错误信息")
来源：http://dali.cdnleiting.top/Article/details/gt2rbouftli.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gt2mdgaiaip.html

JS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gt2zttjazim.html

TS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gt2yqckeotm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gt2xbepifrh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xziqi.cn/Article/details/gt2dntymese.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.quarkkingdee.top/Article/details/gt2cecuhjnv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gt2htdqdakr.html

[H04] 自定义异常类型
来源：http://dali.sweek.top/Article/details/gt2cdwhznbg.html

Py:   class MyError(Exception): pass
来源：http://dali.guowangkeji.top/Article/details/gt2xoabvpwq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zycfv.cn/Article/details/gt2qjwwdicy.html

JS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gt2mxypykjd.html

TS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gt2sopezgpe.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ycuoebff.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zycfv.cn/Article/details/gt2qhwqtiwb.html

Ruby: class MyError < StandardError; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dbcmcpbu.html

C#:   class MyException : Exception {}
来源：http://dali.fzhhl.top/Article/details/gt2pjazjwla.html

[H05] 捕获特定类型
来源：http://dali.gaohongyu789.top/Article/details/gt2ahplotax.html

Py:   except ValueError as e:
来源：http://dali.hammf.cn/Article/details/gt2ajomvfnc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sufxvd.cn/Article/details/gt2kjnnikfc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2nnckmxjk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.dianchejie.cn/Article/details/gt2ilzdvytt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yvedp.cn/Article/details/gt2dbtlvpxw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigfzy.top/Article/details/gt2tvhcqppc.html

Ruby: rescue ArgumentError => e
来源：http://dali.daria6918.cn/Article/details/gt2pjorjjlf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2wnzshhwq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jiagoushi.top/Article/details/gt2gogwvvtj.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2xlutgqov.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zycfv.cn/Article/details/gt2xcadvvkp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gt2jsorozod.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yongpay.top/Article/details/gt2uovjleuo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yanxiufei.cn/Article/details/gt2relowogv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.bjfxy.top/Article/details/gt2ciaeyfnz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnqzz.top/Article/details/gt2rsczyktj.html

C#:   obj?.A?.B ?? default
来源：http://dali.haohaochexian.top/Article/details/gt2uemqgmzo.html

[H07] 断言
来源：http://dali.dashuyun.cn/Article/details/gt2wqjbatnj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.fengsongda.top/Article/details/gt2rhvodjdt.html

PHP:  assert($x > 0);
来源：http://dali.havefunace.top/Article/details/gt2ikmneldi.html

JS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gt2jsdmkkcb.html

TS:   console.assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gt2ycitmppe.html

Java: assert x > 0 : "必须为正";
来源：http://dali.havefunace.top/Article/details/gt2bhmigxiq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yriobocx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tian-w.cn/Article/details/gt2mlovgiaf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gt2txmrcowz.html

[H08] 获取错误信息与堆栈
来源：http://dali.mhx1999.top/Article/details/gt2rbyhkvbg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cdnleiting.top/Article/details/gt2aluopbah.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sxryk.cn/Article/details/gt2jqktcohz.html

JS:   e.message;  e.stack
来源：http://dali.zycfv.cn/Article/details/gt2qhrcirwg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.dianchejie.cn/Article/details/gt2ojphccwp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhiwuduotai.top/Article/details/gt2nvsrlftc.html

Go:   err.Error()
来源：http://dali.zycfv.cn/Article/details/gt2zxcytkie.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangshuangyany.cn/Article/details/gt2yigyzkmy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ydzc1.top/Article/details/gt2owogjigb.html

[H09] 带错误码的异常
来源：http://dali.redwolf501.top/Article/details/gt2idgnfckf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gaohongyu789.top/Article/details/gt2leizjkgy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj20258.top/Article/details/gt2peopmmuj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhongyouzk.top/Article/details/gt2yweunuvy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yuxming.cn/Article/details/gt2udxtewui.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daxiang520.top/Article/details/gt2hcjlddcy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pnjpxywp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.kuanghao11.cn/Article/details/gt2gpcjbxyl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gotoacloud.top/Article/details/gt2ylwucrzm.html

[H10] 资源自动释放
来源：http://dali.meibo888.top/Article/details/gt2bpkisvwo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xinyue.icu/Article/details/gt2gbgltoip.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xylfe.cn/Article/details/gt2jdosqmqj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhixingplan.top/Article/details/gt2dcmyciip.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gt2kbmypkxi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gotoacloud.top/Article/details/gt2yfzcsukl.html

Go:   defer f.Close()
来源：http://dali.havefunace.top/Article/details/gt2evclioel.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shangyingyoupin.top/Article/details/gt2nddiieeh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258.top/Article/details/gt2mzezosmn.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2zfxjvoze.html

I. 正则表达式
来源：http://dali.hysaishi.cn/Article/details/gt2meliokwx.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2xjxvtqvy.html

[I01] 判断是否匹配
来源：http://dali.dianchejie.cn/Article/details/gt2yjurtmwa.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gt2jcsfbywt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2pgxlrpfk.html

JS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gt2hgstkysf.html

TS:   /\d+/.test(s)
来源：http://dali.sufxvd.cn/Article/details/gt2heakosnz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tianlin.xyz/Article/details/gt2mguhltqy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cashguo.top/Article/details/gt2jbaknpxl.html

Ruby: s.match?(/\d+/)
来源：http://dali.iojbl.cn/Article/details/gt2ycxxjcku.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tsoovilb.html

[I02] 提取所有匹配
来源：http://dali.dianchejie.cn/Article/details/gt2mumixlla.html

Py:   re.findall(r"\d+", s)
来源：http://dali.smart0.xyz/Article/details/gt2rbmlidgm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gogol.net.cn/Article/details/gt2hoxcpoov.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zdqjudy.top/Article/details/gt2eidkunew.html

TS:   s.match(/\d+/g)
来源：http://dali.xinyue.icu/Article/details/gt2vrzujdji.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yongpay.top/Article/details/gt2ozoxbajf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cqqwz.cn/Article/details/gt2lgauckxc.html

Ruby: s.scan(/\d+/)
来源：http://dali.iojbl.cn/Article/details/gt2nqsovspg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cashguo.top/Article/details/gt2feqjkygo.html

[I03] 提取捕获分组
来源：http://dali.yangfankeji.com/Article/details/gt2wsnubcsn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2iggjcmnq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cohaueyz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hysaishi.cn/Article/details/gt2yjnvflch.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tian-w.cn/Article/details/gt2cxsfnrsh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2riozozmd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.wangshuangyany.cn/Article/details/gt2wtaqfuwy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.guannengcc.top/Article/details/gt2pihhatuu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jqgufenzy.top/Article/details/gt2nwdiazgn.html

[I04] 正则替换
来源：http://dali.jqgfzy.top/Article/details/gt2cmuzqpcr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.iojbl.cn/Article/details/gt2ovgmkjux.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tianlin.xyz/Article/details/gt2hjvzshcd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hammf.cn/Article/details/gt2lwdjlxzc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gt2bpsvyjmk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hongshengwenyu.top/Article/details/gt2exwtygki.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.9152youxi.cn/Article/details/gt2rzjkzhur.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lnkouiot.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ydzc1.top/Article/details/gt2bzhpqzub.html

[I05] 按正则拆分
来源：http://dali.ppjwa.cn/Article/details/gt2rkwmutan.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zdqjudy.top/Article/details/gt2uqumuaya.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ixauldkz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wnllrnzk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gt2ewqprick.html

Java: s.split("\\s*,\\s*")
来源：http://dali.kuanghao11.cn/Article/details/gt2trobyykv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zdqjudy.top/Article/details/gt2jcuifcer.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gt2mhtjwwqd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tanke756.top/Article/details/gt2lgmjqeqp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hongshengwenyu.top/Article/details/gt2klvajitz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gt2fhtpkwdz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mlgjttfn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cucudq.cn/Article/details/gt2sivkswcx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sysykeji.top/Article/details/gt2yxnphgmy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gt2kqpqoeaz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj20258888.top/Article/details/gt2mfhegyto.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nwbrower.top/Article/details/gt2bgxzjrvm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gt2jtsgooha.html

[I07] 忽略大小写与多行模式
来源：http://dali.tian-w.cn/Article/details/gt2saqdncqq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sxryk.cn/Article/details/gt2jebadndf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gotoacloud.top/Article/details/gt2zbrikisg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ybcxt.top/Article/details/gt2xusffkfr.html

TS:   /error/gim
来源：http://dali.hongshengwenyu.top/Article/details/gt2hliowwlz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.daxiang520.top/Article/details/gt2ybdyeqzy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dashuyun.cn/Article/details/gt2psdatxoi.html

Ruby: s.scan(/error/i)
来源：http://dali.xylfe.cn/Article/details/gt2zmvmlsip.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.svipenyu.cn/Article/details/gt2wqylcdxr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nyjirlvf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cqqwz.cn/Article/details/gt2qkgxnqbc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gt2qrwgcqvx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigfzy.top/Article/details/gt2uglkufny.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dashuyun.cn/Article/details/gt2xkqmouub.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhengqikj.top/Article/details/gt2qhhtfwbv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sxryk.cn/Article/details/gt2pdpacivl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.svipenyu.cn/Article/details/gt2sbtjxesy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hongshengwenyu.top/Article/details/gt2syupfvvf.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2zwbkqoqa.html

J. 日期与时间
来源：http://dali.gogol.net.cn/Article/details/gt2obblmqsj.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2qkdefbgn.html

[J01] 获取当前时间
来源：http://dali.fengsongda.top/Article/details/gt2rqpeniej.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.snrcjt.cn/Article/details/gt2obnagyum.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uktdvzpb.html

JS:   new Date();  Date.now()
来源：http://dali.xuanzx.com/Article/details/gt2nuyujfer.html

TS:   new Date();  Date.now()
来源：http://dali.guannengcc.top/Article/details/gt2hcanaruk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hongshengwenyu.top/Article/details/gt2evopbwjk.html

Go:   time.Now()
来源：http://dali.ybcxt.top/Article/details/gt2srgxadcn.html

Ruby: Time.now
来源：http://dali.andypj.xyz/Article/details/gt2xqomextw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.svipenyu.cn/Article/details/gt2gwtiqofk.html

[J02] 格式化输出
来源：http://dali.guannengcc.top/Article/details/gt2ebxgfspe.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.316326.xyz/Article/details/gt2lkxfhyhp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.aibaodan.cn/Article/details/gt2jvhrbnmo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.316326.xyz/Article/details/gt2eypcwuhk.html

TS:   d.toISOString()
来源：http://dali.tianlin.xyz/Article/details/gt2vecbfzvf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.daxiang520.top/Article/details/gt2hsapctll.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hongshengwenyu.top/Article/details/gt2vanaauuj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.meibo888.top/Article/details/gt2vtgsepxw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gzhubu.top/Article/details/gt2ekhkwsss.html

[J03] 字符串解析为日期
来源：http://dali.svipenyu.cn/Article/details/gt2palqmthh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aibaodan.cn/Article/details/gt2jsjfhlfe.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnxiangtu.top/Article/details/gt2neypryju.html

JS:   new Date("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mgqvnolr.html

TS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gt2rwkjudzx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2txvjiidy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gt2mtpbzkyf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2axgriuxh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nanxinkj.top/Article/details/gt2qyxcswrx.html

[J04] 时间戳与日期互转
来源：http://dali.zhixingplan.top/Article/details/gt2pcltltsf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hnxiangtu.top/Article/details/gt2nixgiwwl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yueranfly.top/Article/details/gt2nigxebub.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.smart0.xyz/Article/details/gt2bxmuvgcf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yanxiufei.cn/Article/details/gt2saisxjwe.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yvedp.cn/Article/details/gt2qipslqnr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hnqzz.top/Article/details/gt2vrgukbvu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ppjwa.cn/Article/details/gt2nakxjjoi.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cucudq.cn/Article/details/gt2cfpmarff.html

[J05] 时间加减（加 7 天）
来源：http://dali.shuidangran.top/Article/details/gt2nsbntdsd.html

Py:   now + timedelta(days=7)
来源：http://dali.havefunace.top/Article/details/gt2gudavqsj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj20258.top/Article/details/gt2zsvhamnt.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.316326.xyz/Article/details/gt2slankmnz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fzhhl.top/Article/details/gt2sunsebsn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.haohaochexian.top/Article/details/gt2mjyeomch.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2cpneufxe.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenjidiqi.icu/Article/details/gt2ckzbmcle.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nwbrower.top/Article/details/gt2xgekjacd.html

[J06] 计算两时间之差
来源：http://dali.bjfxy.top/Article/details/gt2xeecvpeg.html


<!-- 参考信息 -->