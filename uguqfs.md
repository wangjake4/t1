代发 wailian999

Ruby: super
来源：http://dali.cheryme.top/Article/details/gt2rkjmjjwu.html

C#:   base.Greet();
来源：http://dali.aibaodan.cn/Article/details/gt2yirctzgb.html

[G08] 静态方法与属性
来源：http://dali.yueranfly.top/Article/details/gt2tvlmwyxx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sysykeji.top/Article/details/gt2mmbdytik.html

PHP:  public static function f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2vmzyrfqg.html

JS:   static f() {}
来源：http://dali.aibaodan.cn/Article/details/gt2hspsbqby.html

TS:   static f(): void {}
来源：http://dali.fzhhl.top/Article/details/gt2xyoivmqz.html

Java: static void f() {}
来源：http://dali.kuanghao11.cn/Article/details/gt2akkuamuq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258.top/Article/details/gt2tlphxbyd.html

Ruby: def self.f; end
来源：http://dali.svipenyu.cn/Article/details/gt2szepzmyv.html

C#:   public static void F() {}
来源：http://dali.ivvv.top/Article/details/gt2hnqryzuy.html

[G09] 接口 / 抽象类
来源：http://dali.tianlin.xyz/Article/details/gt2azywxwon.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.316326.xyz/Article/details/gt2pdzjseql.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jbnnlixp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nwbrower.top/Article/details/gt2gouqvkbu.html

TS:   interface Shape { area(): number; }
来源：http://dali.hammf.cn/Article/details/gt2atkrkoih.html

Java: interface Shape { double area(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fjztolna.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xinyue.icu/Article/details/gt2aavysycj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nwbrower.top/Article/details/gt2ocaohtvl.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2uvlzcphl.html

[G10] 访问控制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mtuefjle.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqdfmxr.html

PHP:  public / protected / private
来源：http://dali.cheryme.top/Article/details/gt2friflgmp.html

JS:   #private 字段；其余公开
来源：http://dali.zhixingplan.top/Article/details/gt2mbynpwnx.html

TS:   public / protected / private
来源：http://dali.fzhhl.top/Article/details/gt2jmfatxbn.html

Java: public / protected / private / 默认包级
来源：http://dali.cucudq.cn/Article/details/gt2wphhizni.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yangfankeji.com/Article/details/gt2hpotkuwx.html

Ruby: public / protected / private
来源：http://dali.jianghu66.top/Article/details/gt2csbfnqsv.html

C#:   public / protected / private / internal
来源：http://dali.daria6918.cn/Article/details/gt2tvjdoxag.html

[G11] getter / setter
来源：http://dali.shzxlz.cn/Article/details/gt2btszxcth.html

Py:   @property 与 @x.setter
来源：http://dali.jiagoushi.top/Article/details/gt2jifidkbl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gt2jxbxltob.html

JS:   get name() { return this._name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ghhwdysk.html

TS:   get name(): string { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hgoyasot.html

Java: public String getName() { return name; }
来源：http://dali.aizwys.cn/Article/details/gt2xtjdhvka.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gt2anephudp.html

Ruby: attr_accessor :name
来源：http://dali.xuetiantiany.cn/Article/details/gt2ojgokygz.html

C#:   public string Name { get; set; }
来源：http://dali.9152youxi.cn/Article/details/gt2jnxfhhmm.html

[G12] 对象转字符串
来源：http://dali.havefunace.top/Article/details/gt2cfkjgfqy.html

Py:   def __str__(self): return self.name
来源：http://dali.gogol.net.cn/Article/details/gt2fodkfrzq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gt2lgluirtt.html

JS:   toString() { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gt2aeubnywh.html

TS:   toString(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gt2mprenobi.html

Java: @Override public String toString() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gt2duiocjgi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gt2qmzzmoyd.html

Ruby: def to_s; @name; end
来源：http://dali.daria6918.cn/Article/details/gt2yuwgrjbn.html

C#:   public override string ToString() => Name;
来源：http://dali.xziqi.cn/Article/details/gt2nkdhoebm.html

[G13] 判断对象类型
来源：http://dali.316326.xyz/Article/details/gt2zblbtooz.html

Py:   isinstance(u, User)
来源：http://dali.nanxuanxn.top/Article/details/gt2fxewrahi.html

PHP:  $u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gt2daqafgui.html

JS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gt2hhngtkrx.html

TS:   u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gt2hlbbmnsw.html

Java: u instanceof User
来源：http://dali.xinyue.icu/Article/details/gt2lkpjydfh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uxijxwks.html

Ruby: u.is_a?(User)
来源：http://dali.fengsongda.top/Article/details/gt2qnaunuiq.html

C#:   u is User
来源：http://dali.havefunace.top/Article/details/gt2bsinvzxg.html

[G14] 数据类 / record
来源：http://dali.hnxiangtu.top/Article/details/gt2smsrlsbp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.redwolf501.top/Article/details/gt2tmddithb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shuidangran.top/Article/details/gt2ijqfwfbu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenjidiqi.icu/Article/details/gt2vrgjtjdc.html

TS:   type User = { name: string; age: number };
来源：http://dali.zdqjudy.top/Article/details/gt2rmwoumfb.html

Java: record User(String name, int age) {}
来源：http://dali.zycfv.cn/Article/details/gt2fshstthk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.9152youxi.cn/Article/details/gt2vildhltm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yuxming.cn/Article/details/gt2aumkinpz.html

C#:   record User(string Name, int Age);
来源：http://dali.shangyingyoupin.top/Article/details/gt2zeqnmmva.html

[G15] 枚举
来源：http://dali.wangdashe.top/Article/details/gt2zqhwsdrw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ybcxt.top/Article/details/gt2ojdkmptr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ydzc1.top/Article/details/gt2fdvanurk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cashguo.top/Article/details/gt2ktjeikdt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guowangkeji.top/Article/details/gt2blsabvwn.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jfiavcvh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhixingplan.top/Article/details/gt2ybphynpz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gzhubu.top/Article/details/gt2fybotske.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gt2rxmqpghi.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258888.top/Article/details/gt2mkqjnafx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sweek.top/Article/details/gt2uzllgooy.html

PHP:  get_object_vars($obj);
来源：http://dali.xziqi.cn/Article/details/gt2qivundog.html

JS:   Object.entries(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2szbnwjlh.html

TS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2dbbvrlky.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yongpay.top/Article/details/gt2hdnoofeo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sysykeji.top/Article/details/gt2htbuftri.html

Ruby: obj.instance_variables
来源：http://dali.hfpthk.cn/Article/details/gt2garmrxrq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhoulong.xyz/Article/details/gt2zidtqmpn.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2kaypvwdj.html

H. 异常与错误处理
来源：http://dali.nwbrower.top/Article/details/gt2hchilyrn.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2dsuoydtk.html

[H01] try / catch 基础
来源：http://dali.cheryme.top/Article/details/gt2oiopysak.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nemggsih.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.dianchejie.cn/Article/details/gt2bjjbuadw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zxrrfjvd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gt2rjjqtuug.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnxiangtu.top/Article/details/gt2rbpkumqh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.pengpengdd.cyou/Article/details/gt2nkzfgtfs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258888.top/Article/details/gt2iyoweovx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hysaishi.cn/Article/details/gt2gemndwkx.html

[H02] finally / ensure 收尾
来源：http://dali.wangdashe.top/Article/details/gt2czeaeetj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgfzy.top/Article/details/gt2xshhgdmx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gt2jkheggvf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gt2meckoqqg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ffkfnwrv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gt2qrpafwhu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shangyingyoupin.top/Article/details/gt2pvuakibp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dianchejie.cn/Article/details/gt2ztnamihq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gt2phjqinry.html

[H03] 主动抛出异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uammbrpv.html

Py:   raise ValueError("错误信息")
来源：http://dali.yueranfly.top/Article/details/gt2tjwtqinu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gt2pzsdxcyx.html

JS:   throw new Error("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2bdfwyrrq.html

TS:   throw new Error("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gt2esxyqstr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gt2wdlrhcgy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hkpeznis.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aizwys.cn/Article/details/gt2rxtaesfu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gt2ylihzgzx.html

[H04] 自定义异常类型
来源：http://dali.vqdsnc.cn/Article/details/gt2ghgnyeca.html

Py:   class MyError(Exception): pass
来源：http://dali.dashuyun.cn/Article/details/gt2abdagjaz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.quarkkingdee.top/Article/details/gt2ptfqzkmr.html

JS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gt2jniibvyl.html

TS:   class MyError extends Error {}
来源：http://dali.hammf.cn/Article/details/gt2ftbfkyhj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinqigfzy.top/Article/details/gt2lsjtbquu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.kuanghao11.cn/Article/details/gt2cyyguids.html

Ruby: class MyError < StandardError; end
来源：http://dali.fzhhl.top/Article/details/gt2sdtexaju.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2calqaavk.html

[H05] 捕获特定类型
来源：http://dali.yj202588.top/Article/details/gt2criowvym.html

Py:   except ValueError as e:
来源：http://dali.sweek.top/Article/details/gt2lczcawre.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.316326.xyz/Article/details/gt2qlvowupg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gt2teckohky.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gt2pdowgsko.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2wolddwvj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xylfe.cn/Article/details/gt2yjzwlugc.html

Ruby: rescue ArgumentError => e
来源：http://dali.tian-w.cn/Article/details/gt2vcjjkykd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tanke756.top/Article/details/gt2oeuuvzkv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenjidiqi.icu/Article/details/gt2xivfwilg.html

Py:   value = d.get("k") or default
来源：http://dali.shuidangran.top/Article/details/gt2pahalhuz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gt2coisacpr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxinkj.top/Article/details/gt2styyynra.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.snrcjt.cn/Article/details/gt2jwdylmjp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hywenlv.cn/Article/details/gt2losgwrus.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigufen.top/Article/details/gt2vrvfnjyn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yueranfly.top/Article/details/gt2rsfqvgro.html

C#:   obj?.A?.B ?? default
来源：http://dali.cashguo.top/Article/details/gt2ikihdwkh.html

[H07] 断言
来源：http://dali.yanxiufei.cn/Article/details/gt2aifbrxxe.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ehwqpu.com/Article/details/gt2fkksnuzd.html

PHP:  assert($x > 0);
来源：http://dali.tanke756.top/Article/details/gt2zklqjumb.html

JS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gt2tlulbsbv.html

TS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gt2qevhzjjb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxinkj.top/Article/details/gt2gnnrnwlp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gaohongyu789.top/Article/details/gt2dvcaesaj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sufxvd.cn/Article/details/gt2afwrguiw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gt2dronomxt.html

[H08] 获取错误信息与堆栈
来源：http://dali.aibaodan.cn/Article/details/gt2jefambri.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2paqbafdk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.c1oappe.top/Article/details/gt2nojthwqo.html

JS:   e.message;  e.stack
来源：http://dali.dashuyun.cn/Article/details/gt2wrelpdlg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ivvv.top/Article/details/gt2dubozvkh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yuanzhike.top/Article/details/gt2jpknmslk.html

Go:   err.Error()
来源：http://dali.fzhhl.top/Article/details/gt2ssunesqs.html

Ruby: e.message;  e.backtrace
来源：http://dali.iojbl.cn/Article/details/gt2oljsyufw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.haohaochexian.top/Article/details/gt2vubxplxy.html

[H09] 带错误码的异常
来源：http://dali.yanxiufei.cn/Article/details/gt2rogunvdh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xuetiantiany.cn/Article/details/gt2keeqhcwm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pycfn.com/Article/details/gt2ksutckke.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.guannengcc.top/Article/details/gt2ukeacqjd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.snrcjt.cn/Article/details/gt2gvwjtvfr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ydzc1.top/Article/details/gt2sgiiwrxc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnxiangtu.top/Article/details/gt2vngxutng.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.316326.xyz/Article/details/gt2gmelzwfv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.bjfxy.top/Article/details/gt2jkcjumry.html

[H10] 资源自动释放
来源：http://dali.yonumen.top/Article/details/gt2rcbnahdp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhengqikj.top/Article/details/gt2ybbgczuk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhongyouzk.top/Article/details/gt2jjilvbdy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangshuangyany.cn/Article/details/gt2npoblvcb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gzhubu.top/Article/details/gt2swppjowy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.wangdashe.top/Article/details/gt2lqzemynx.html

Go:   defer f.Close()
来源：http://dali.jqgfzy.top/Article/details/gt2fryeonfx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xuanzx.com/Article/details/gt2rtfgrchd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2rtvzkgqm.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2ihykqfjn.html

I. 正则表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uaphggbu.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2pfbxcjbb.html

[I01] 判断是否匹配
来源：http://dali.zhengqikj.top/Article/details/gt2pzhnrzgl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jqgfzy.top/Article/details/gt2cxfkvodz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shzxlz.cn/Article/details/gt2pfwxdvvs.html

JS:   /\d+/.test(s)
来源：http://dali.pycfn.com/Article/details/gt2wlehmlsf.html

TS:   /\d+/.test(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ciprcddh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yueranfly.top/Article/details/gt2phnsijqi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2glldgdtm.html

Ruby: s.match?(/\d+/)
来源：http://dali.ehwqpu.com/Article/details/gt2wyuhsskt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tian-w.cn/Article/details/gt2dbsqthfq.html

[I02] 提取所有匹配
来源：http://dali.guowangkeji.top/Article/details/gt2tbmztxvi.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shzxlz.cn/Article/details/gt2idtgropg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hammf.cn/Article/details/gt2yboscwgq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.fengsongda.top/Article/details/gt2eyjiydja.html

TS:   s.match(/\d+/g)
来源：http://dali.yj202588.top/Article/details/gt2cngxmhxt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhongyouzk.top/Article/details/gt2risdndjt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ydzc1.top/Article/details/gt2qrorftvh.html

Ruby: s.scan(/\d+/)
来源：http://dali.hnxiangtu.top/Article/details/gt2kamvxzyl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.c1oappe.top/Article/details/gt2iwdomxuc.html

[I03] 提取捕获分组
来源：http://dali.xylfe.cn/Article/details/gt2mrbihhjs.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.guowangkeji.top/Article/details/gt2eylwnfup.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qcnkdxqj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jianghu66.top/Article/details/gt2unrllptn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sweek.top/Article/details/gt2kvyiewrm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ybcxt.top/Article/details/gt2exsdvpay.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nanxinkj.top/Article/details/gt2dxrbyqtj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.aibaodan.cn/Article/details/gt2xjxwlgem.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.iojbl.cn/Article/details/gt2yljhnjgo.html

[I04] 正则替换
来源：http://dali.fengsongda.top/Article/details/gt2byzhoaaw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2uexgdbgo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnxiangtu.top/Article/details/gt2rcytehin.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zdqjudy.top/Article/details/gt2ysovdsfx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uhvsoubm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jqgufenzy.top/Article/details/gt2ruhlzqfk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ppjwa.cn/Article/details/gt2qvnrnupt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gogol.net.cn/Article/details/gt2hugqxltf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.aibaodan.cn/Article/details/gt2jritvtzi.html

[I05] 按正则拆分
来源：http://dali.yonumen.top/Article/details/gt2pxhudpcr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cucudq.cn/Article/details/gt2qnxpiezn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hammf.cn/Article/details/gt2rmomebvi.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gt2lmvsbcpa.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gt2giulncpd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhiwuduotai.top/Article/details/gt2zbbeqmfi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenzaomai.com/Article/details/gt2aqutdzwk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gt2hnwpqrgz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.redwolf501.top/Article/details/gt2azvlurwo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hysaishi.cn/Article/details/gt2vykzwcxp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gt2rtujxytd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yanxiufei.cn/Article/details/gt2eeeumvld.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gt2azoxcdws.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuanzhike.top/Article/details/gt2rheiejqz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj202588.top/Article/details/gt2nggioxbv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj20258888.top/Article/details/gt2bcxwscbc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ehwqpu.com/Article/details/gt2zklnrczv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gt2tnrbfiie.html

[I07] 忽略大小写与多行模式
来源：http://dali.yuxming.cn/Article/details/gt2xofbsxmm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dashuyun.cn/Article/details/gt2ogaflfcl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sysykeji.top/Article/details/gt2ywhinvnq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yonumen.top/Article/details/gt2ajnvwkqm.html

TS:   /error/gim
来源：http://dali.cqqwz.cn/Article/details/gt2icvgyrfp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gzhubu.top/Article/details/gt2vlpqqkda.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cheryme.top/Article/details/gt2nkkoggzm.html

Ruby: s.scan(/error/i)
来源：http://dali.c1oappe.top/Article/details/gt2dtrotzsk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhixingplan.top/Article/details/gt2poacraqg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cdnleiting.top/Article/details/gt2azivmmsy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yynqyjpv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.vqdsnc.cn/Article/details/gt2bwqbggie.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tianlin.xyz/Article/details/gt2loakjpkf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gt2qwuethyf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.daxiang520.top/Article/details/gt2alxpthva.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ppjwa.cn/Article/details/gt2sgkgyfjz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2odjchbjs.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kmrfbbqd.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2jhcauvpl.html

J. 日期与时间
来源：http://dali.redwolf501.top/Article/details/gt2cscqsihq.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rfngqhfc.html

[J01] 获取当前时间
来源：http://dali.chenzaomai.com/Article/details/gt2sdzwdldh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hnqzz.top/Article/details/gt2hkyojoud.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.fzhhl.top/Article/details/gt2qlwzriox.html

JS:   new Date();  Date.now()
来源：http://dali.yueranfly.top/Article/details/gt2dkpijvob.html

TS:   new Date();  Date.now()
来源：http://dali.snrcjt.cn/Article/details/gt2bsaafagc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenlongwang.top/Article/details/gt2jrzkapmk.html

Go:   time.Now()
来源：http://dali.ydzc1.top/Article/details/gt2tuougsvh.html

Ruby: Time.now
来源：http://dali.sysykeji.top/Article/details/gt2uglyoert.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yuxming.cn/Article/details/gt2wflltxmy.html

[J02] 格式化输出
来源：http://dali.jianghu66.top/Article/details/gt2iermsznd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangshuangyany.cn/Article/details/gt2yhkbxmie.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gaohongyu789.top/Article/details/gt2txbzsifk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jqgfzy.top/Article/details/gt2yyhvuush.html

TS:   d.toISOString()
来源：http://dali.cqqwz.cn/Article/details/gt2fkxtnnjb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.iojbl.cn/Article/details/gt2itxrauqa.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.quarkkingdee.top/Article/details/gt2xoqpsijs.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gogol.net.cn/Article/details/gt2mzntjxta.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ydzc1.top/Article/details/gt2npjmljwj.html

[J03] 字符串解析为日期
来源：http://dali.kuanghao11.cn/Article/details/gt2fhgzmgbx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yueranfly.top/Article/details/gt2wkdcrxox.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ivvv.top/Article/details/gt2gwtbnlxw.html

JS:   new Date("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gt2egqqimvi.html

TS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2czckvyxg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gt2zvmuxplx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gt2ntjhhlme.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gt2mqqxnotx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xziqi.cn/Article/details/gt2uaibdnyq.html

[J04] 时间戳与日期互转
来源：http://dali.zhixingplan.top/Article/details/gt2mxcowktj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hysaishi.cn/Article/details/gt2vfoweupz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cheryme.top/Article/details/gt2buedtlws.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2msbrltyb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hnxiangtu.top/Article/details/gt2rvzwafbq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yanxiufei.cn/Article/details/gt2fiqpeump.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2avselply.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kzjhybbk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.redwolf501.top/Article/details/gt2wjhhnqyf.html

[J05] 时间加减（加 7 天）
来源：http://dali.shangyingyoupin.top/Article/details/gt2nmtdoimd.html

Py:   now + timedelta(days=7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cdsxaqjh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jiagoushi.top/Article/details/gt2mpzqvtnm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aizwys.cn/Article/details/gt2nskyxmbb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.kuanghao11.cn/Article/details/gt2hwyoejrm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fzhhl.top/Article/details/gt2nyhkloxc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.snrcjt.cn/Article/details/gt2rtdaslgg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cucudq.cn/Article/details/gt2uknesfus.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ybcxt.top/Article/details/gt2wcltpbqx.html

[J06] 计算两时间之差
来源：http://dali.guannengcc.top/Article/details/gt2qnqyuiya.html


<!-- 参考信息 -->