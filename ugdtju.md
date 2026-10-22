代发 wailian999

Ruby: super
来源：http://dali.jyoumei.cn/Article/details/gt2ucvbfwgh.html

C#:   base.Greet();
来源：http://dali.shangyingyoupin.top/Article/details/gt2bhnyqnrm.html

[G08] 静态方法与属性
来源：http://dali.hywenlv.cn/Article/details/gt2tidynnfc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gogol.net.cn/Article/details/gt2pbmbujno.html

PHP:  public static function f() {}
来源：http://dali.dianchejie.cn/Article/details/gt2yywsjfba.html

JS:   static f() {}
来源：http://dali.sweek.top/Article/details/gt2qridpfxc.html

TS:   static f(): void {}
来源：http://dali.guannengcc.top/Article/details/gt2xmwsazyu.html

Java: static void f() {}
来源：http://dali.pycfn.com/Article/details/gt2uzzilfpt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nwbrower.top/Article/details/gt2wcunfovb.html

Ruby: def self.f; end
来源：http://dali.vqdsnc.cn/Article/details/gt2zuzylidp.html

C#:   public static void F() {}
来源：http://dali.cheryme.top/Article/details/gt2iuqghdzg.html

[G09] 接口 / 抽象类
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qxfwtunv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.0kj1m.cn/Article/details/gt2zviahlsd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guannengcc.top/Article/details/gt2ptmsdemz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nwbrower.top/Article/details/gt2bnzcwqse.html

TS:   interface Shape { area(): number; }
来源：http://dali.xziqi.cn/Article/details/gt2zoplkeus.html

Java: interface Shape { double area(); }
来源：http://dali.xylfe.cn/Article/details/gt2xljmhtiz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj20258.top/Article/details/gt2edhfmbjv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zyjjormi.html

C#:   interface IShape { double Area(); }
来源：http://dali.dianchejie.cn/Article/details/gt2fjqtzdfj.html

[G10] 访问控制
来源：http://dali.meibo888.top/Article/details/gt2eqifxmvu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shangyingyoupin.top/Article/details/gt2jlqmtrfj.html

PHP:  public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qulooqem.html

JS:   #private 字段；其余公开
来源：http://dali.nwbrower.top/Article/details/gt2kcvznpoj.html

TS:   public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2moewnekg.html

Java: public / protected / private / 默认包级
来源：http://dali.gogol.net.cn/Article/details/gt2zwcohwbx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gohamwuy.html

Ruby: public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gt2gdjkvtol.html

C#:   public / protected / private / internal
来源：http://dali.nwbrower.top/Article/details/gt2stwqwjty.html

[G11] getter / setter
来源：http://dali.fengsongda.top/Article/details/gt2yhlpdswo.html

Py:   @property 与 @x.setter
来源：http://dali.zhoulong.xyz/Article/details/gt2mymcafrx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gt2vcoowuxu.html

JS:   get name() { return this._name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pwzhbemq.html

TS:   get name(): string { return this._name; }
来源：http://dali.nwbrower.top/Article/details/gt2purqdzxn.html

Java: public String getName() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gt2rxtjqqgr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gt2wmioiblb.html

Ruby: attr_accessor :name
来源：http://dali.sxryk.cn/Article/details/gt2plhbkwax.html

C#:   public string Name { get; set; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2pdputfam.html

[G12] 对象转字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2uqizroky.html

Py:   def __str__(self): return self.name
来源：http://dali.fengsongda.top/Article/details/gt2wcehbtgm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lncznlpp.html

JS:   toString() { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gt2bdsnhzfd.html

TS:   toString(): string { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gt2gtoeynhj.html

Java: @Override public String toString() { return name; }
来源：http://dali.sysykeji.top/Article/details/gt2sdhrllkw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gt2fcliivrn.html

Ruby: def to_s; @name; end
来源：http://dali.pycfn.com/Article/details/gt2uztkmmis.html

C#:   public override string ToString() => Name;
来源：http://dali.gzhubu.top/Article/details/gt2craskfve.html

[G13] 判断对象类型
来源：http://dali.jinqigfzy.top/Article/details/gt2qrwcuikj.html

Py:   isinstance(u, User)
来源：http://dali.xinyue.icu/Article/details/gt2tlqbqwjk.html

PHP:  $u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gt2zbmqbybd.html

JS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gt2qspzwcbi.html

TS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gt2lshsxnwc.html

Java: u instanceof User
来源：http://dali.daria6918.cn/Article/details/gt2vgtpmwbs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.redwolf501.top/Article/details/gt2jcjruxqy.html

Ruby: u.is_a?(User)
来源：http://dali.andypj.xyz/Article/details/gt2ldckovsh.html

C#:   u is User
来源：http://dali.jinqigfzy.top/Article/details/gt2ftlxsmon.html

[G14] 数据类 / record
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hszjaegg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jxygngku.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lohboudr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guowangkeji.top/Article/details/gt2vdipbdmu.html

TS:   type User = { name: string; age: number };
来源：http://dali.yonumen.top/Article/details/gt2zpiyoayw.html

Java: record User(String name, int age) {}
来源：http://dali.haohaochexian.top/Article/details/gt2hsyrqoyy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tianlin.xyz/Article/details/gt2dlwdoizp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ukjhmjhb.html

C#:   record User(string Name, int Age);
来源：http://dali.zhixingplan.top/Article/details/gt2crkzehvt.html

[G15] 枚举
来源：http://dali.snrcjt.cn/Article/details/gt2vappaxzk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2zekhffka.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2yevvqfzv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.bjfxy.top/Article/details/gt2hsexnytz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.meibo888.top/Article/details/gt2edttwtdk.html

Java: enum Color { RED, GREEN }
来源：http://dali.haohaochexian.top/Article/details/gt2zilvouni.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ydzc1.top/Article/details/gt2bmdgereq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.birdmap.top/Article/details/gt2ljtzizyc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjnxadv.html

[G16] 对象转数组 / 字典
来源：http://dali.zycfv.cn/Article/details/gt2ddnbgwmh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhengqikj.top/Article/details/gt2srgahkmt.html

PHP:  get_object_vars($obj);
来源：http://dali.meibo888.top/Article/details/gt2edbnshpr.html

JS:   Object.entries(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2nrpokkqh.html

TS:   Object.entries(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2hfiegakj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cashguo.top/Article/details/gt2rxbtsvkv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gogol.net.cn/Article/details/gt2kitevqmn.html

Ruby: obj.instance_variables
来源：http://dali.jqgfzy.top/Article/details/gt2euqhhusr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shzxlz.cn/Article/details/gt2kgxlaabo.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2yndntapj.html

H. 异常与错误处理
来源：http://dali.jyoumei.cn/Article/details/gt2dtpwfqzv.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2kcecfzir.html

[H01] try / catch 基础
来源：http://dali.pengpengdd.cyou/Article/details/gt2rsdrvpin.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xuanzx.com/Article/details/gt2ggthtpdh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sxryk.cn/Article/details/gt2qlesggqt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gt2lbcngyhw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xylfe.cn/Article/details/gt2wewdphzm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2nlcjsagk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.birdmap.top/Article/details/gt2iviiuabh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.smart0.xyz/Article/details/gt2wyyrbapi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ehwqpu.com/Article/details/gt2vxdyckoc.html

[H02] finally / ensure 收尾
来源：http://dali.kuanghao11.cn/Article/details/gt2qmsprvad.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenlongwang.top/Article/details/gt2zeupfeuc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gt2lyaezhyi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gt2tewxvdqa.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gt2goifsqcl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gt2cjhgmceq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tanke756.top/Article/details/gt2xabhzwxn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daxiang520.top/Article/details/gt2byxljkby.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2skhjjuhs.html

[H03] 主动抛出异常
来源：http://dali.cdnleiting.top/Article/details/gt2cwpxcixy.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yelmqbrt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gt2tqtzpayy.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gt2ujnhcnwh.html

TS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gt2hmynxqfa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gt2ivctpkeg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cheryme.top/Article/details/gt2klyqohft.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dianchejie.cn/Article/details/gt2qupefopn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gt2deoujqkq.html

[H04] 自定义异常类型
来源：http://dali.gzhubu.top/Article/details/gt2zgjejthv.html

Py:   class MyError(Exception): pass
来源：http://dali.cashguo.top/Article/details/gt2jniwgkmq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gt2gmyzpnit.html

JS:   class MyError extends Error {}
来源：http://dali.daria6918.cn/Article/details/gt2kuiehdjt.html

TS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gt2ezsoztjb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.pycfn.com/Article/details/gt2kckjrrdp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hnxiangtu.top/Article/details/gt2bxjkfmbx.html

Ruby: class MyError < StandardError; end
来源：http://dali.0kj1m.cn/Article/details/gt2dizkfihu.html

C#:   class MyException : Exception {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ooyokinb.html

[H05] 捕获特定类型
来源：http://dali.jianghu66.top/Article/details/gt2fbhdxthm.html

Py:   except ValueError as e:
来源：http://dali.chenzaomai.com/Article/details/gt2vivqhyzk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.aizwys.cn/Article/details/gt2wcespwra.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258888.top/Article/details/gt2lcwgnnva.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2vizviwkc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2fetevasy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hywenlv.cn/Article/details/gt2fcfajkki.html

Ruby: rescue ArgumentError => e
来源：http://dali.yangfankeji.com/Article/details/gt2ztszxfdz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuxming.cn/Article/details/gt2cpiwufcv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.mhx1999.top/Article/details/gt2vcrlfqzy.html

Py:   value = d.get("k") or default
来源：http://dali.yangfankeji.com/Article/details/gt2kbewttec.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tian-w.cn/Article/details/gt2mgsfjeex.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cucudq.cn/Article/details/gt2fetsnjvm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shuidangran.top/Article/details/gt2cvpoocgk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.aibaodan.cn/Article/details/gt2tgegysuy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cqqwz.cn/Article/details/gt2ohwnvlvn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.vqdsnc.cn/Article/details/gt2wzirjuhq.html

C#:   obj?.A?.B ?? default
来源：http://dali.shuidangran.top/Article/details/gt2ayaoiqwl.html

[H07] 断言
来源：http://dali.yvedp.cn/Article/details/gt2airfmzrv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.smart0.xyz/Article/details/gt2wmdddsdn.html

PHP:  assert($x > 0);
来源：http://dali.jqgfzy.top/Article/details/gt2bodcfhfu.html

JS:   console.assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gt2gxfopmzu.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gt2yyiaezui.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gotoacloud.top/Article/details/gt2wwhibvxw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.snrcjt.cn/Article/details/gt2qxnsgpux.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yongpay.top/Article/details/gt2pzpcuuuh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gt2pwaxwdqn.html

[H08] 获取错误信息与堆栈
来源：http://dali.kuanghao11.cn/Article/details/gt2wmzfclgi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ivvv.top/Article/details/gt2ywyidkzb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.c1oappe.top/Article/details/gt2yifkimxu.html

JS:   e.message;  e.stack
来源：http://dali.guowangkeji.top/Article/details/gt2slkkdrph.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zdqjudy.top/Article/details/gt2qubowakn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.svipenyu.cn/Article/details/gt2sbmepyvk.html

Go:   err.Error()
来源：http://dali.0kj1m.cn/Article/details/gt2bkzhqwgn.html

Ruby: e.message;  e.backtrace
来源：http://dali.ybcxt.top/Article/details/gt2tplwtydo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.smart0.xyz/Article/details/gt2dsgidawn.html

[H09] 带错误码的异常
来源：http://dali.aizwys.cn/Article/details/gt2ohrqynbc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xuanzx.com/Article/details/gt2lnnfmerd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangshuangyany.cn/Article/details/gt2fpeabiei.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cheryme.top/Article/details/gt2qbbfwkzq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ppjwa.cn/Article/details/gt2izsfyjtx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cdnleiting.top/Article/details/gt2cchilseg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinqigfzy.top/Article/details/gt2soayisxj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.bjfxy.top/Article/details/gt2uexcslge.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cqqwz.cn/Article/details/gt2odyjimfn.html

[H10] 资源自动释放
来源：http://dali.zycfv.cn/Article/details/gt2mjgowjbw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.snrcjt.cn/Article/details/gt2ibuxwyek.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gaohongyu789.top/Article/details/gt2jgghbioz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.smart0.xyz/Article/details/gt2ctuysaoc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangtech.top/Article/details/gt2navilkht.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yangfankeji.com/Article/details/gt2gdiiregc.html

Go:   defer f.Close()
来源：http://dali.dashuyun.cn/Article/details/gt2silnwzsk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.redwolf501.top/Article/details/gt2mhppsuyt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2byueumte.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2xhlfkdgl.html

I. 正则表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iytimpcd.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2pofhxbep.html

[I01] 判断是否匹配
来源：http://dali.wangdashe.top/Article/details/gt2rjikjrmn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gjxgchfr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aizwys.cn/Article/details/gt2yxcdaovx.html

JS:   /\d+/.test(s)
来源：http://dali.9152youxi.cn/Article/details/gt2njykoorb.html

TS:   /\d+/.test(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hmlprels.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tian-w.cn/Article/details/gt2ilxoiowd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tian-w.cn/Article/details/gt2bhuvhlxd.html

Ruby: s.match?(/\d+/)
来源：http://dali.sufxvd.cn/Article/details/gt2lpdnfuqk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhiwuduotai.top/Article/details/gt2mmcdjqzz.html

[I02] 提取所有匹配
来源：http://dali.guannengcc.top/Article/details/gt2gwiopyxg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.birdmap.top/Article/details/gt2gkjcjpsu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tian-w.cn/Article/details/gt2jpouorji.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.316326.xyz/Article/details/gt2mfiprbsk.html

TS:   s.match(/\d+/g)
来源：http://dali.tianlin.xyz/Article/details/gt2dyfvdcfg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ybcxt.top/Article/details/gt2jaekkras.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gt2xwhitmlm.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxinkj.top/Article/details/gt2indilsuq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhengqikj.top/Article/details/gt2pkhuokbq.html

[I03] 提取捕获分组
来源：http://dali.feifeiyinyue.top/Article/details/gt2skjujush.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cheryme.top/Article/details/gt2zksqwzvv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hywenlv.cn/Article/details/gt2uczwjsgc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.daxiang520.top/Article/details/gt2atgrhisx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ivvv.top/Article/details/gt2tnnsickh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.quarkkingdee.top/Article/details/gt2chxcfxzx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hysaishi.cn/Article/details/gt2wlykfmdm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhixingplan.top/Article/details/gt2zfjauate.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.aibaodan.cn/Article/details/gt2memyepjh.html

[I04] 正则替换
来源：http://dali.birdmap.top/Article/details/gt2lntmffmy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.316326.xyz/Article/details/gt2fysbcbez.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.redwolf501.top/Article/details/gt2vmhchjck.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.redwolf501.top/Article/details/gt2wpqjakkl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gt2rfgkxgce.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.aibaodan.cn/Article/details/gt2ewaabgul.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shzxlz.cn/Article/details/gt2yunndzpv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hnqzz.top/Article/details/gt2unvrdvnh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.0kj1m.cn/Article/details/gt2xhhksbwx.html

[I05] 按正则拆分
来源：http://dali.hfpthk.cn/Article/details/gt2xzhwgkjf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jsesrptm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gzhubu.top/Article/details/gt2spvgdnrp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gt2kxytflvp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gt2sdllxqxl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.bjfxy.top/Article/details/gt2pemxyicm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.c1oappe.top/Article/details/gt2jgtjtkvb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.snrcjt.cn/Article/details/gt2jnurjdml.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.snrcjt.cn/Article/details/gt2agbnxyul.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigfzy.top/Article/details/gt2hjdipvuu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yongpay.top/Article/details/gt2ihxqgoul.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2biyibgmt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wagheefr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sweek.top/Article/details/gt2vqfneemr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.tanke756.top/Article/details/gt2bysuzgxe.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yangfankeji.com/Article/details/gt2uzzroeht.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinqigfzy.top/Article/details/gt2texorklg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.316326.xyz/Article/details/gt2olwcqmwb.html

[I07] 忽略大小写与多行模式
来源：http://dali.mhx1999.top/Article/details/gt2djwtbwgm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hysaishi.cn/Article/details/gt2ngsjqspm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.aibaodan.cn/Article/details/gt2zfbgcofd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258.top/Article/details/gt2xtuaxtzz.html

TS:   /error/gim
来源：http://dali.zhixingplan.top/Article/details/gt2zsuvsknh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nanxinkj.top/Article/details/gt2glutueci.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nwbrower.top/Article/details/gt2hlrxwemg.html

Ruby: s.scan(/error/i)
来源：http://dali.hnqzz.top/Article/details/gt2hoovmkiz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ybcxt.top/Article/details/gt2bugbeepe.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.mhx1999.top/Article/details/gt2ucpsgked.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daria6918.cn/Article/details/gt2frfuimiv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.havefunace.top/Article/details/gt2elpiaaor.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gt2lwsfwgta.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rarhrmct.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xuanzx.com/Article/details/gt2efqhcrlo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hongshengwenyu.top/Article/details/gt2jhzufdjg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yuanzhike.top/Article/details/gt2ybqnlpld.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.svipenyu.cn/Article/details/gt2shzoxqac.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2gxhtbsuo.html

J. 日期与时间
来源：http://dali.dianchejie.cn/Article/details/gt2gpadppck.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2kffmjyqn.html

[J01] 获取当前时间
来源：http://dali.bjfxy.top/Article/details/gt2ldppifmi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.wangdashe.top/Article/details/gt2mxumzcct.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gt2xvtctqfj.html

JS:   new Date();  Date.now()
来源：http://dali.guannengcc.top/Article/details/gt2dxkvinol.html

TS:   new Date();  Date.now()
来源：http://dali.pycfn.com/Article/details/gt2xuktivvn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ehwqpu.com/Article/details/gt2biegesoe.html

Go:   time.Now()
来源：http://dali.daxiang520.top/Article/details/gt2nfdojhhr.html

Ruby: Time.now
来源：http://dali.hfpthk.cn/Article/details/gt2gutptqvc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.feifeiyinyue.top/Article/details/gt2hvtdwdtr.html

[J02] 格式化输出
来源：http://dali.yj20258888.top/Article/details/gt2iknlrpmd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gaohongyu789.top/Article/details/gt2tbtyyanu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hysaishi.cn/Article/details/gt2tfwitrqt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.redwolf501.top/Article/details/gt2jmmqmvyw.html

TS:   d.toISOString()
来源：http://dali.jqgufenzy.top/Article/details/gt2wetazeyt.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yueranfly.top/Article/details/gt2xkmbnlxd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nanxinkj.top/Article/details/gt2bozvoshi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cdnleiting.top/Article/details/gt2oaotaywp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.316326.xyz/Article/details/gt2thgtvnhw.html

[J03] 字符串解析为日期
来源：http://dali.jiagoushi.top/Article/details/gt2pooobfch.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nwbrower.top/Article/details/gt2omhfhgce.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sysykeji.top/Article/details/gt2eboefdny.html

JS:   new Date("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gt2eqhidcsk.html

TS:   new Date("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gt2cbhndbdv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2rfwomyoh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gt2tohaozus.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gt2syokiamd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rhuwdnnr.html

[J04] 时间戳与日期互转
来源：http://dali.jqgfzy.top/Article/details/gt2qrzmeune.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hnxiangtu.top/Article/details/gt2xpjthlll.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tanke756.top/Article/details/gt2ftovqdrt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shzxlz.cn/Article/details/gt2jmaqitre.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj20258888.top/Article/details/gt2ddusvioc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xziqi.cn/Article/details/gt2ewssdmse.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ivvv.top/Article/details/gt2sodwsmpi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgufenzy.top/Article/details/gt2nuicfpbb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yvedp.cn/Article/details/gt2ozdqdfht.html

[J05] 时间加减（加 7 天）
来源：http://dali.jiagoushi.top/Article/details/gt2vbucpfum.html

Py:   now + timedelta(days=7)
来源：http://dali.hnxiangtu.top/Article/details/gt2xpylxpcb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dtfsdafg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sweek.top/Article/details/gt2xlszsclm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2isplaxpk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yuanzhike.top/Article/details/gt2spqolpmd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jqgfzy.top/Article/details/gt2ntnylyom.html

Ruby: Time.now + 7 * 86400
来源：http://dali.aibaodan.cn/Article/details/gt2xrtimluu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cuputljt.html

[J06] 计算两时间之差
来源：http://dali.yonumen.top/Article/details/gt2cuhwrihq.html


<!-- 参考信息 -->