代发 wailian999

Ruby: super
来源：http://dali.iojbl.cn/Article/details/gt2uifwwmos.html

C#:   base.Greet();
来源：http://dali.316326.xyz/Article/details/gt2jzamgzpc.html

[G08] 静态方法与属性
来源：http://dali.shangyingyoupin.top/Article/details/gt2qrqaollo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.quarkkingdee.top/Article/details/gt2agrbqbrm.html

PHP:  public static function f() {}
来源：http://dali.zhoulong.xyz/Article/details/gt2ltzaappk.html

JS:   static f() {}
来源：http://dali.cashguo.top/Article/details/gt2uimsjppg.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2glienbrc.html

Java: static void f() {}
来源：http://dali.nanxinkj.top/Article/details/gt2kyxjuxda.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yuanzhike.top/Article/details/gt2ktzkjvdr.html

Ruby: def self.f; end
来源：http://dali.jlsjyb.cn/Article/details/gt2lvtdzwpl.html

C#:   public static void F() {}
来源：http://dali.iojbl.cn/Article/details/gt2qteqeyzr.html

[G09] 接口 / 抽象类
来源：http://dali.zdqjudy.top/Article/details/gt2nqpdbjyn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ivvv.top/Article/details/gt2urmlgkex.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cheryme.top/Article/details/gt2hzlhrkqt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.meibo888.top/Article/details/gt2zvzxggqe.html

TS:   interface Shape { area(): number; }
来源：http://dali.vqdsnc.cn/Article/details/gt2ftffpcro.html

Java: interface Shape { double area(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2elqocpaa.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ylkferyh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnxiangtu.top/Article/details/gt2oacswidg.html

C#:   interface IShape { double Area(); }
来源：http://dali.snrcjt.cn/Article/details/gt2wejtzamc.html

[G10] 访问控制
来源：http://dali.ybcxt.top/Article/details/gt2cgcnrrna.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.quarkkingdee.top/Article/details/gt2bgwmidjg.html

PHP:  public / protected / private
来源：http://dali.sxryk.cn/Article/details/gt2pmmfadbs.html

JS:   #private 字段；其余公开
来源：http://dali.cheryme.top/Article/details/gt2wfqziqes.html

TS:   public / protected / private
来源：http://dali.birdmap.top/Article/details/gt2smukgaul.html

Java: public / protected / private / 默认包级
来源：http://dali.chenzaomai.com/Article/details/gt2znkhihtl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yongpay.top/Article/details/gt2brcwrljv.html

Ruby: public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gt2zvjtqynz.html

C#:   public / protected / private / internal
来源：http://dali.guannengcc.top/Article/details/gt2cwzfynla.html

[G11] getter / setter
来源：http://dali.tanke756.top/Article/details/gt2eskuwqxp.html

Py:   @property 与 @x.setter
来源：http://dali.havefunace.top/Article/details/gt2fyrzqrcw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gt2upnqnmaz.html

JS:   get name() { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2jgrvsjhh.html

TS:   get name(): string { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gt2iithjdfx.html

Java: public String getName() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2mxljeehl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nzvxjldi.html

Ruby: attr_accessor :name
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nzlttaep.html

C#:   public string Name { get; set; }
来源：http://dali.tianlin.xyz/Article/details/gt2tjrbzeaw.html

[G12] 对象转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2lcagqkys.html

Py:   def __str__(self): return self.name
来源：http://dali.hnqzz.top/Article/details/gt2htbotnqt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gt2cdshrqhz.html

JS:   toString() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2zhikizys.html

TS:   toString(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gt2zuayzttw.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj20258.top/Article/details/gt2dqqipvga.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gt2raaoxooi.html

Ruby: def to_s; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gt2sttdbdcr.html

C#:   public override string ToString() => Name;
来源：http://dali.smart0.xyz/Article/details/gt2hbmistop.html

[G13] 判断对象类型
来源：http://dali.sxryk.cn/Article/details/gt2ablczqqe.html

Py:   isinstance(u, User)
来源：http://dali.yonumen.top/Article/details/gt2othrgnho.html

PHP:  $u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gt2fgaalkwd.html

JS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gt2aknxjfef.html

TS:   u instanceof User
来源：http://dali.pycfn.com/Article/details/gt2vnrszpnp.html

Java: u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gt2ncrhgriy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mfmsztul.html

Ruby: u.is_a?(User)
来源：http://dali.zhongyouzk.top/Article/details/gt2plcjpctw.html

C#:   u is User
来源：http://dali.jyoumei.cn/Article/details/gt2fbptakuw.html

[G14] 数据类 / record
来源：http://dali.0kj1m.cn/Article/details/gt2yxirhsir.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.snrcjt.cn/Article/details/gt2uglhlhwh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aizwys.cn/Article/details/gt2ijzypezi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cheryme.top/Article/details/gt2bbiqyacj.html

TS:   type User = { name: string; age: number };
来源：http://dali.nanxuanxn.top/Article/details/gt2thetrvqf.html

Java: record User(String name, int age) {}
来源：http://dali.sufxvd.cn/Article/details/gt2znhvtdms.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgufenzy.top/Article/details/gt2ahumqvss.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.wangdashe.top/Article/details/gt2qcfqshhx.html

C#:   record User(string Name, int Age);
来源：http://dali.quarkkingdee.top/Article/details/gt2inulsbzb.html

[G15] 枚举
来源：http://dali.zhixingplan.top/Article/details/gt2xmgteslq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenzaomai.com/Article/details/gt2sekipjgl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.pycfn.com/Article/details/gt2bmrcbnkl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.c1oappe.top/Article/details/gt2ahbwllqz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ccrubrrz.html

Java: enum Color { RED, GREEN }
来源：http://dali.nwbrower.top/Article/details/gt2tmvclpca.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shuidangran.top/Article/details/gt2eepytvvc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.havefunace.top/Article/details/gt2jxuxgwpv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gt2ibjnojyr.html

[G16] 对象转数组 / 字典
来源：http://dali.sxryk.cn/Article/details/gt2rxopakty.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhengqikj.top/Article/details/gt2brhdfkwr.html

PHP:  get_object_vars($obj);
来源：http://dali.hnxiangtu.top/Article/details/gt2fblnzuog.html

JS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2rbnnvjov.html

TS:   Object.entries(obj)
来源：http://dali.yonumen.top/Article/details/gt2xadldupj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hammf.cn/Article/details/gt2wwayfunr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj20258888.top/Article/details/gt2kqlaskge.html

Ruby: obj.instance_variables
来源：http://dali.cdnleiting.top/Article/details/gt2lbqudqpi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gt2cjlpdytx.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2ryqvtyrs.html

H. 异常与错误处理
来源：http://dali.tian-w.cn/Article/details/gt2hcugsssr.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2srbpgvzb.html

[H01] try / catch 基础
来源：http://dali.xinyue.icu/Article/details/gt2otbyfpuw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.daria6918.cn/Article/details/gt2izbvjypx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cheryme.top/Article/details/gt2imhjdydg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gt2spkmkiep.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gt2xabayuxl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2seatptde.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.birdmap.top/Article/details/gt2munjxuom.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2prihtfwm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xinyue.icu/Article/details/gt2fwooyzyh.html

[H02] finally / ensure 收尾
来源：http://dali.sxryk.cn/Article/details/gt2eoptfuog.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.daxiang520.top/Article/details/gt2lxnlzkkj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gt2qiexicbg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gt2cdiotbzl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2usnezezh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gt2lriifnrb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.aizwys.cn/Article/details/gt2nkcyajjo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgfzy.top/Article/details/gt2qwjyypkx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gt2hhjuuzoh.html

[H03] 主动抛出异常
来源：http://dali.yj20258888.top/Article/details/gt2zigrkded.html

Py:   raise ValueError("错误信息")
来源：http://dali.yongpay.top/Article/details/gt2hnbxauzx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gt2mviofpbl.html

JS:   throw new Error("错误信息");
来源：http://dali.fzhhl.top/Article/details/gt2pqcazpvy.html

TS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gt2jxtmsbhf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gt2rgpjaqlx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sufxvd.cn/Article/details/gt2ssuoppex.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.bjfxy.top/Article/details/gt2ntqpxifz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gt2relsrnnb.html

[H04] 自定义异常类型
来源：http://dali.cqqwz.cn/Article/details/gt2yibffvht.html

Py:   class MyError(Exception): pass
来源：http://dali.sweek.top/Article/details/gt2xghfdiwt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.andypj.xyz/Article/details/gt2efsyzmue.html

JS:   class MyError extends Error {}
来源：http://dali.yuxming.cn/Article/details/gt2ipyueatl.html

TS:   class MyError extends Error {}
来源：http://dali.svipenyu.cn/Article/details/gt2xjjzhhct.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shuidangran.top/Article/details/gt2sfnbibvk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pycfn.com/Article/details/gt2fhjrrcwx.html

Ruby: class MyError < StandardError; end
来源：http://dali.dashuyun.cn/Article/details/gt2xomaxeqo.html

C#:   class MyException : Exception {}
来源：http://dali.316326.xyz/Article/details/gt2ncvjvxdh.html

[H05] 捕获特定类型
来源：http://dali.mhx1999.top/Article/details/gt2xpzncykk.html

Py:   except ValueError as e:
来源：http://dali.jinqigufen.top/Article/details/gt2qsjxiepk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2jjsvudsi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gt2cmiqxlhj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gt2hupnkcxx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2hvbngtdl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhoulong.xyz/Article/details/gt2rmxyvfgk.html

Ruby: rescue ArgumentError => e
来源：http://dali.wangdashe.top/Article/details/gt2dgfcasxy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuanzhike.top/Article/details/gt2ztnknonm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2avdcqiky.html

Py:   value = d.get("k") or default
来源：http://dali.zycfv.cn/Article/details/gt2jcegonhp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zycfv.cn/Article/details/gt2lywdzbvi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gt2cufhtvtt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lvxffvnl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.316326.xyz/Article/details/gt2anbbfaia.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ntdylrqb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hywenlv.cn/Article/details/gt2bsqpivir.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnxiangtu.top/Article/details/gt2sihjtvpd.html

[H07] 断言
来源：http://dali.jyoumei.cn/Article/details/gt2wvdtmjkq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cucudq.cn/Article/details/gt2detyhpgs.html

PHP:  assert($x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2zqfhgemg.html

JS:   console.assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gt2bcdajrkw.html

TS:   console.assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gt2mhdhrsjp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hongshengwenyu.top/Article/details/gt2gwenjjib.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yangfankeji.com/Article/details/gt2iwnbwjdi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj202588.top/Article/details/gt2cgqmecpe.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gt2jhqeuqns.html

[H08] 获取错误信息与堆栈
来源：http://dali.smart0.xyz/Article/details/gt2vehsknzw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gogol.net.cn/Article/details/gt2iyhsnjla.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.svipenyu.cn/Article/details/gt2nmfyfcje.html

JS:   e.message;  e.stack
来源：http://dali.daria6918.cn/Article/details/gt2ryzdurde.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yanxiufei.cn/Article/details/gt2vzvsdbsn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.aibaodan.cn/Article/details/gt2odxtjitw.html

Go:   err.Error()
来源：http://dali.yvedp.cn/Article/details/gt2xzkckmnj.html

Ruby: e.message;  e.backtrace
来源：http://dali.sweek.top/Article/details/gt2dxjvekhv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.feifeiyinyue.top/Article/details/gt2rxajhrvc.html

[H09] 带错误码的异常
来源：http://dali.zhixingplan.top/Article/details/gt2cqcrbsyo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.kuanghao11.cn/Article/details/gt2cungzoiz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.fzhhl.top/Article/details/gt2hoohidxe.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangshuangyany.cn/Article/details/gt2lhlgindh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hongshengwenyu.top/Article/details/gt2bvyuwhzy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.316326.xyz/Article/details/gt2ljfsavql.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shanyushiyangtech.top/Article/details/gt2didixofj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jazijoar.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinqigufen.top/Article/details/gt2bigaovrz.html

[H10] 资源自动释放
来源：http://dali.zycfv.cn/Article/details/gt2cdqgcuff.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.haohaochexian.top/Article/details/gt2ypumqipe.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigufen.top/Article/details/gt2ucrlqopn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tanke756.top/Article/details/gt2mlvfyzrv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.snrcjt.cn/Article/details/gt2vvltxoed.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.dashuyun.cn/Article/details/gt2ljjwdrpd.html

Go:   defer f.Close()
来源：http://dali.andypj.xyz/Article/details/gt2zsnljkuc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.0kj1m.cn/Article/details/gt2ipjulvnl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2plskwuaz.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2zwepkstb.html

I. 正则表达式
来源：http://dali.nanxinkj.top/Article/details/gt2heawvtrz.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2mkhfxycy.html

[I01] 判断是否匹配
来源：http://dali.mhx1999.top/Article/details/gt2ltyfayst.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nanxinkj.top/Article/details/gt2zxfwlibu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mfcuuoet.html

JS:   /\d+/.test(s)
来源：http://dali.nanxinkj.top/Article/details/gt2otvrzeln.html

TS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gt2gqvctord.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.guowangkeji.top/Article/details/gt2noynfrjz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinqigufen.top/Article/details/gt2hlhihuiy.html

Ruby: s.match?(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gt2ttzpzmiy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangshuangyany.cn/Article/details/gt2thuamjkz.html

[I02] 提取所有匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gvttuljl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gt2hyjkpqyc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.svipenyu.cn/Article/details/gt2opdlvaoy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.0kj1m.cn/Article/details/gt2ayqjeycw.html

TS:   s.match(/\d+/g)
来源：http://dali.yonumen.top/Article/details/gt2qmlwegnw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lhczegzj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2agqlpwdw.html

Ruby: s.scan(/\d+/)
来源：http://dali.dianchejie.cn/Article/details/gt2xmxdwejv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cheryme.top/Article/details/gt2ppycnqiw.html

[I03] 提取捕获分组
来源：http://dali.sweek.top/Article/details/gt2gctydaav.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xylfe.cn/Article/details/gt2jcfsfhom.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2upqvrsjq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sxryk.cn/Article/details/gt2hqxfjsoy.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2qwuyllla.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.daria6918.cn/Article/details/gt2bnhypjst.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenjidiqi.icu/Article/details/gt2ymtyrkgl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cashguo.top/Article/details/gt2tvslizfo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.c1oappe.top/Article/details/gt2pbcwfhlf.html

[I04] 正则替换
来源：http://dali.yangfankeji.com/Article/details/gt2nrnpbogg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.aizwys.cn/Article/details/gt2gtvulosn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgfzy.top/Article/details/gt2cvlfpwpm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gt2jncgqiml.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zdqjudy.top/Article/details/gt2mgearumi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zdqjudy.top/Article/details/gt2evzvoprz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hivtpuol.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ydzc1.top/Article/details/gt2fnlntdds.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yuxming.cn/Article/details/gt2wnbelhdj.html

[I05] 按正则拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gifhlgts.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yuxming.cn/Article/details/gt2broqqeir.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2hplskirf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gt2eaxfzejv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gt2kkdbscdh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nanxuanxn.top/Article/details/gt2szoqrtrv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nbnbsmem.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2flwnghpq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.smart0.xyz/Article/details/gt2lekauvdw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.svipenyu.cn/Article/details/gt2vupgxzjn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gt2pqjtuvzb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guannengcc.top/Article/details/gt2dekwpvgc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sysykeji.top/Article/details/gt2oxfpzdrl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oofozptb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gt2bczqwcec.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xinyue.icu/Article/details/gt2zvryhfay.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.fzhhl.top/Article/details/gt2xrhvsfdg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gt2thyiiati.html

[I07] 忽略大小写与多行模式
来源：http://dali.pycfn.com/Article/details/gt2prxeobff.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tianlin.xyz/Article/details/gt2awjwqkkq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gt2cthxteqk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cashguo.top/Article/details/gt2vlbnhcvn.html

TS:   /error/gim
来源：http://dali.shangyingyoupin.top/Article/details/gt2dvwgkyiv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hashxepu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zllalseg.html

Ruby: s.scan(/error/i)
来源：http://dali.dianchejie.cn/Article/details/gt2mqrmvqee.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.pycfn.com/Article/details/gt2rplphklj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.guowangkeji.top/Article/details/gt2slimazno.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jiagoushi.top/Article/details/gt2iwazmahm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj202588.top/Article/details/gt2ymtdsdzb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sufxvd.cn/Article/details/gt2diffhhsh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jyoumei.cn/Article/details/gt2vsnhxopn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xylfe.cn/Article/details/gt2mxffzlcm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.fzhhl.top/Article/details/gt2rlpvzjtz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hywenlv.cn/Article/details/gt2ouxhfflt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hysaishi.cn/Article/details/gt2kttdpfrg.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2fipqghlz.html

J. 日期与时间
来源：http://dali.hnqzz.top/Article/details/gt2itdvbgsz.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hntyclow.html

[J01] 获取当前时间
来源：http://dali.pengpengdd.cyou/Article/details/gt2ndkejxgq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.snrcjt.cn/Article/details/gt2hbfqdkec.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.wangdashe.top/Article/details/gt2jrteymls.html

JS:   new Date();  Date.now()
来源：http://dali.hfpthk.cn/Article/details/gt2cmugoguk.html

TS:   new Date();  Date.now()
来源：http://dali.jyoumei.cn/Article/details/gt2ctrdfdhw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.pengpengdd.cyou/Article/details/gt2mtbywrzj.html

Go:   time.Now()
来源：http://dali.ehwqpu.com/Article/details/gt2haktnhsa.html

Ruby: Time.now
来源：http://dali.chenzaomai.com/Article/details/gt2jlewyfdk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yvedp.cn/Article/details/gt2pijaytiq.html

[J02] 格式化输出
来源：http://dali.ivvv.top/Article/details/gt2sisbwbqh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.vqdsnc.cn/Article/details/gt2gncxdltd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hnqzz.top/Article/details/gt2fqhzfmte.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhengqikj.top/Article/details/gt2weeecwop.html

TS:   d.toISOString()
来源：http://dali.ydzc1.top/Article/details/gt2fdvxtzhb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhixingplan.top/Article/details/gt2ittdeqte.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.fzhhl.top/Article/details/gt2srxmbucp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yangfankeji.com/Article/details/gt2hnhxzlek.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenzaomai.com/Article/details/gt2ohmcuhmv.html

[J03] 字符串解析为日期
来源：http://dali.shangyingyoupin.top/Article/details/gt2bqybkmcy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ivvv.top/Article/details/gt2cedqevnk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangdashe.top/Article/details/gt2vulnwrwy.html

JS:   new Date("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gt2fogofiuj.html

TS:   new Date("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gt2ofbotihc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gt2knbuovxa.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gt2hoxzxtzx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gt2bfrjnrpb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yuanzhike.top/Article/details/gt2mikrqtfo.html

[J04] 时间戳与日期互转
来源：http://dali.yongpay.top/Article/details/gt2yjhzmmdy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenlongwang.top/Article/details/gt2shxazkvn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hongshengwenyu.top/Article/details/gt2ymcpbrod.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.quarkkingdee.top/Article/details/gt2uhuskfpv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.bjfxy.top/Article/details/gt2cwxuvmum.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gt2khutrwxw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.aizwys.cn/Article/details/gt2lzkihejj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2ryedrffm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jqgufenzy.top/Article/details/gt2adudwlqq.html

[J05] 时间加减（加 7 天）
来源：http://dali.nanxuanxn.top/Article/details/gt2inawxfvn.html

Py:   now + timedelta(days=7)
来源：http://dali.aizwys.cn/Article/details/gt2jltdvjjp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zdqjudy.top/Article/details/gt2tvadqlqi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgufenzy.top/Article/details/gt2xvpuxymq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gt2ctxpwbwv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nwbrower.top/Article/details/gt2skofhkkq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jyoumei.cn/Article/details/gt2srlexmok.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jlsjyb.cn/Article/details/gt2kxyfdpvr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pdlqeygi.html

[J06] 计算两时间之差
来源：http://dali.jlsjyb.cn/Article/details/gt2kyfiifvh.html


<!-- 参考信息 -->