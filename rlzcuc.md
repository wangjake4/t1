代发 wailian999

Java: class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gt2aqutijnj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sxryk.cn/Article/details/gt2impijjgv.html

Ruby: class Admin < User; end
来源：http://dali.redwolf501.top/Article/details/gt2ogrvfzig.html

C#:   class Admin : User {}
来源：http://dali.gogol.net.cn/Article/details/gt2dbfihyhp.html

[G06] 重写方法
来源：http://dali.sysykeji.top/Article/details/gt2abcyyswb.html

Py:   def greet(self): return "admin"
来源：http://dali.dianchejie.cn/Article/details/gt2cjnawgjx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gt2nfdbxzvs.html

JS:   greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gt2ueepkjqn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gt2seqekzaf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gt2ojyvceaa.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sufxvd.cn/Article/details/gt2lypddwuf.html

Ruby: def greet; "admin"; end
来源：http://dali.jqgufenzy.top/Article/details/gt2zcbqmvlp.html

C#:   public override string Greet() => "admin";
来源：http://dali.xziqi.cn/Article/details/gt2nogzyunc.html

[G07] 调用父类方法
来源：http://dali.shzxlz.cn/Article/details/gt2dyzlkbkx.html

Py:   super().greet()
来源：http://dali.jyoumei.cn/Article/details/gt2omslhoue.html

PHP:  parent::greet();
来源：http://dali.guannengcc.top/Article/details/gt2ugumqgpr.html

JS:   super.greet();
来源：http://dali.yueranfly.top/Article/details/gt2aokzjemm.html

TS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gt2vsmkvrxj.html

Java: super.greet();
来源：http://dali.cdnleiting.top/Article/details/gt2hjoyfoyz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aibaodan.cn/Article/details/gt2jctladuj.html

Ruby: super
来源：http://dali.chenjidiqi.icu/Article/details/gt2tgauxgkf.html

C#:   base.Greet();
来源：http://dali.zhiwuduotai.top/Article/details/gt2nbhohuki.html

[G08] 静态方法与属性
来源：http://dali.snrcjt.cn/Article/details/gt2ihjjmjez.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tianlin.xyz/Article/details/gt2fqhfmlft.html

PHP:  public static function f() {}
来源：http://dali.xylfe.cn/Article/details/gt2uqkrsyou.html

JS:   static f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2izruwkpu.html

TS:   static f(): void {}
来源：http://dali.zhengqikj.top/Article/details/gt2fvepgdam.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gxythqcr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sxryk.cn/Article/details/gt2wnrzqosu.html

Ruby: def self.f; end
来源：http://dali.yongpay.top/Article/details/gt2bzksdilz.html

C#:   public static void F() {}
来源：http://dali.bjfxy.top/Article/details/gt2zlipfopo.html

[G09] 接口 / 抽象类
来源：http://dali.dianchejie.cn/Article/details/gt2zlnowtso.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj20258.top/Article/details/gt2ihxldvom.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ydzc1.top/Article/details/gt2cjezlbgo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tian-w.cn/Article/details/gt2zjcrqamh.html

TS:   interface Shape { area(): number; }
来源：http://dali.quarkkingdee.top/Article/details/gt2nabmvxmt.html

Java: interface Shape { double area(); }
来源：http://dali.hywenlv.cn/Article/details/gt2pepixzox.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yuanzhike.top/Article/details/gt2dwjiptoz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daria6918.cn/Article/details/gt2zsvvianw.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj20258.top/Article/details/gt2mxhusjhd.html

[G10] 访问控制
来源：http://dali.yanxiufei.cn/Article/details/gt2bormqskf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zaswlyyj.html

PHP:  public / protected / private
来源：http://dali.sxryk.cn/Article/details/gt2stafyxje.html

JS:   #private 字段；其余公开
来源：http://dali.shuidangran.top/Article/details/gt2lcsnjnqk.html

TS:   public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gt2uzjecfia.html

Java: public / protected / private / 默认包级
来源：http://dali.vqdsnc.cn/Article/details/gt2gquxyreo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenzaomai.com/Article/details/gt2kngncbit.html

Ruby: public / protected / private
来源：http://dali.zycfv.cn/Article/details/gt2dozbmelm.html

C#:   public / protected / private / internal
来源：http://dali.yongpay.top/Article/details/gt2efjbpwik.html

[G11] getter / setter
来源：http://dali.cucudq.cn/Article/details/gt2vubtyivn.html

Py:   @property 与 @x.setter
来源：http://dali.yonumen.top/Article/details/gt2vhdclyfn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gt2jrvcezpb.html

JS:   get name() { return this._name; }
来源：http://dali.yvedp.cn/Article/details/gt2nonzzgjk.html

TS:   get name(): string { return this._name; }
来源：http://dali.havefunace.top/Article/details/gt2ouhpspbt.html

Java: public String getName() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2moasnuac.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gt2gipqdmsn.html

Ruby: attr_accessor :name
来源：http://dali.pengpengdd.cyou/Article/details/gt2xzoinrko.html

C#:   public string Name { get; set; }
来源：http://dali.kuanghao11.cn/Article/details/gt2tjljwtyx.html

[G12] 对象转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2stlasrys.html

Py:   def __str__(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gt2egqdhjan.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gt2ipjaowsh.html

JS:   toString() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gt2ajcuopzq.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gt2mrioruoq.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2jobshbkb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gt2grncrkjx.html

Ruby: def to_s; @name; end
来源：http://dali.yongpay.top/Article/details/gt2nybwxqoy.html

C#:   public override string ToString() => Name;
来源：http://dali.sysykeji.top/Article/details/gt2xyaaiaai.html

[G13] 判断对象类型
来源：http://dali.gzhubu.top/Article/details/gt2xomdsxcc.html

Py:   isinstance(u, User)
来源：http://dali.gzhubu.top/Article/details/gt2ifjwqsbk.html

PHP:  $u instanceof User
来源：http://dali.wangdashe.top/Article/details/gt2dpqcyzuc.html

JS:   u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gt2vttyvizv.html

TS:   u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gt2cjltmwbu.html

Java: u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gt2riilkxeo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xinyue.icu/Article/details/gt2chpyumkj.html

Ruby: u.is_a?(User)
来源：http://dali.jyoumei.cn/Article/details/gt2writklyp.html

C#:   u is User
来源：http://dali.xziqi.cn/Article/details/gt2jtmtkkzn.html

[G14] 数据类 / record
来源：http://dali.shangyingyoupin.top/Article/details/gt2gmxqigem.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hammf.cn/Article/details/gt2hzkhwkkq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.vqdsnc.cn/Article/details/gt2bhaewdop.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guannengcc.top/Article/details/gt2yafvjmbl.html

TS:   type User = { name: string; age: number };
来源：http://dali.mhx1999.top/Article/details/gt2zbygurcd.html

Java: record User(String name, int age) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2emekvkey.html

Go:   type User struct { Name string; Age int }
来源：http://dali.andypj.xyz/Article/details/gt2nvodgdxx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jqgufenzy.top/Article/details/gt2bpguyrob.html

C#:   record User(string Name, int Age);
来源：http://dali.tanke756.top/Article/details/gt2agoabijs.html

[G15] 枚举
来源：http://dali.0kj1m.cn/Article/details/gt2vqnntsxb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenlongwang.top/Article/details/gt2chkmgpdd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ybcxt.top/Article/details/gt2eehhnhtt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hongshengwenyu.top/Article/details/gt2xxfkvosp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ollkhtmm.html

Java: enum Color { RED, GREEN }
来源：http://dali.hfpthk.cn/Article/details/gt2wbhutrji.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ojpoiufh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.redwolf501.top/Article/details/gt2lrrtjwjb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.haohaochexian.top/Article/details/gt2znwfchuj.html

[G16] 对象转数组 / 字典
来源：http://dali.guannengcc.top/Article/details/gt2tzwpjbsa.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xziqi.cn/Article/details/gt2qbhmczqg.html

PHP:  get_object_vars($obj);
来源：http://dali.yonumen.top/Article/details/gt2yabxaevb.html

JS:   Object.entries(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2fonsdzuo.html

TS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ehufmzgd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.andypj.xyz/Article/details/gt2ngkgxnae.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gaohongyu789.top/Article/details/gt2qefvnyzo.html

Ruby: obj.instance_variables
来源：http://dali.andypj.xyz/Article/details/gt2nhtjhdbl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yangfankeji.com/Article/details/gt2oaknivph.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2deligorc.html

H. 异常与错误处理
来源：http://dali.xylfe.cn/Article/details/gt2slotbksj.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2rkntjbbp.html

[H01] try / catch 基础
来源：http://dali.gaohongyu789.top/Article/details/gt2wqhzrqaa.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tanke756.top/Article/details/gt2fkaaivra.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2jylbydbm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gt2tjxdnkab.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vzzsxrfv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2elhckutt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.andypj.xyz/Article/details/gt2fopfifew.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.havefunace.top/Article/details/gt2mqlnfxkc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.mhx1999.top/Article/details/gt2xoouofgw.html

[H02] finally / ensure 收尾
来源：http://dali.cqqwz.cn/Article/details/gt2bnspzsze.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.havefunace.top/Article/details/gt2iwyixozy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gt2vcwphbmf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2uwrnfybi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gt2rnfojgqu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gt2lvzmswmc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuetiantiany.cn/Article/details/gt2emyiqyzt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cheryme.top/Article/details/gt2cpenvsfh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gt2btpkkiuc.html

[H03] 主动抛出异常
来源：http://dali.pengpengdd.cyou/Article/details/gt2nijattdt.html

Py:   raise ValueError("错误信息")
来源：http://dali.birdmap.top/Article/details/gt2dhqsqacq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2yoatgpzo.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gt2ifuuuvxw.html

TS:   throw new Error("错误信息");
来源：http://dali.daxiang520.top/Article/details/gt2tbctmygj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2xdbkvffe.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.havefunace.top/Article/details/gt2bcvifltq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnxiangtu.top/Article/details/gt2xtnsjjfr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gt2kuakyora.html

[H04] 自定义异常类型
来源：http://dali.yangfankeji.com/Article/details/gt2etjhesfa.html

Py:   class MyError(Exception): pass
来源：http://dali.meibo888.top/Article/details/gt2fxvuxsxr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cdnleiting.top/Article/details/gt2kmtqvvdg.html

JS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gt2roydhefc.html

TS:   class MyError extends Error {}
来源：http://dali.9152youxi.cn/Article/details/gt2qfqiqvba.html

Java: class MyException extends RuntimeException {}
来源：http://dali.bjfxy.top/Article/details/gt2teaidyyx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigfzy.top/Article/details/gt2uhvdrmxs.html

Ruby: class MyError < StandardError; end
来源：http://dali.cqqwz.cn/Article/details/gt2rumtkvse.html

C#:   class MyException : Exception {}
来源：http://dali.ehwqpu.com/Article/details/gt2hzlyazhf.html

[H05] 捕获特定类型
来源：http://dali.sysykeji.top/Article/details/gt2alokigyf.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wzjydlhi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2xkddyyrv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2cnlpeeow.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.redwolf501.top/Article/details/gt2bovbdgav.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cdnleiting.top/Article/details/gt2tqwmzcvz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hysaishi.cn/Article/details/gt2wtfitwwo.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2orhuwngu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nanxinkj.top/Article/details/gt2swofxnwv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.feifeiyinyue.top/Article/details/gt2kubhmmhc.html

Py:   value = d.get("k") or default
来源：http://dali.wangdashe.top/Article/details/gt2wxasrjbh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kwhpquwg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cheryme.top/Article/details/gt2yvoqpkob.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenzaomai.com/Article/details/gt2fntzcafm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gzhubu.top/Article/details/gt2opfloize.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yueranfly.top/Article/details/gt2pouqlqvj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinqigufen.top/Article/details/gt2nvtfsvmx.html

C#:   obj?.A?.B ?? default
来源：http://dali.cqqwz.cn/Article/details/gt2kvnqudze.html

[H07] 断言
来源：http://dali.nanxinkj.top/Article/details/gt2pksmsjqh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gaohongyu789.top/Article/details/gt2ysdnolif.html

PHP:  assert($x > 0);
来源：http://dali.yongpay.top/Article/details/gt2apbeoylo.html

JS:   console.assert(x > 0);
来源：http://dali.sweek.top/Article/details/gt2noypafba.html

TS:   console.assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gt2fwaxkmqr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.daxiang520.top/Article/details/gt2imexnjyj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aizwys.cn/Article/details/gt2peeuecri.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yongpay.top/Article/details/gt2xmdzraqw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gt2jgdszsqq.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuetiantiany.cn/Article/details/gt2fjqzbtgq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ivvv.top/Article/details/gt2cuywhuyg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.kuanghao11.cn/Article/details/gt2gvpwckio.html

JS:   e.message;  e.stack
来源：http://dali.hnqzz.top/Article/details/gt2pkvihzce.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxinkj.top/Article/details/gt2nvccuvlq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sufxvd.cn/Article/details/gt2ykheufik.html

Go:   err.Error()
来源：http://dali.haohaochexian.top/Article/details/gt2wbghykuh.html

Ruby: e.message;  e.backtrace
来源：http://dali.smart0.xyz/Article/details/gt2oqhvniew.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shzxlz.cn/Article/details/gt2hiaiwztn.html

[H09] 带错误码的异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jcstylsc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj20258888.top/Article/details/gt2cwanvhlj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.svipenyu.cn/Article/details/gt2gygejbvh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ydzc1.top/Article/details/gt2emvgizzi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xuanzx.com/Article/details/gt2pssaxked.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.quarkkingdee.top/Article/details/gt2zvijqajj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.svipenyu.cn/Article/details/gt2jfprboow.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.svipenyu.cn/Article/details/gt2mnjlwhum.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tian-w.cn/Article/details/gt2zmknzbpo.html

[H10] 资源自动释放
来源：http://dali.chenzaomai.com/Article/details/gt2xgrfzwty.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ydzc1.top/Article/details/gt2oshwcczl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fmlcmrgf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gt2iobhrrns.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shzxlz.cn/Article/details/gt2qeyqbrbx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhongyouzk.top/Article/details/gt2edbyidae.html

Go:   defer f.Close()
来源：http://dali.havefunace.top/Article/details/gt2ykwqbgjg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.dashuyun.cn/Article/details/gt2hbhjyipt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2rekuhsjz.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2ycncvtzo.html

I. 正则表达式
来源：http://dali.zhiwuduotai.top/Article/details/gt2hdaqlaxm.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2wgismryk.html

[I01] 判断是否匹配
来源：http://dali.zhoulong.xyz/Article/details/gt2atdekvvj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gt2psrglfom.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ppjwa.cn/Article/details/gt2pzkapaxd.html

JS:   /\d+/.test(s)
来源：http://dali.yongpay.top/Article/details/gt2xusxdalk.html

TS:   /\d+/.test(s)
来源：http://dali.aibaodan.cn/Article/details/gt2nmnubame.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jqgfzy.top/Article/details/gt2hbatkdly.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xinyue.icu/Article/details/gt2zhlnpgle.html

Ruby: s.match?(/\d+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2posbezsd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xuetiantiany.cn/Article/details/gt2gkxtddqi.html

[I02] 提取所有匹配
来源：http://dali.gotoacloud.top/Article/details/gt2phfltbdi.html

Py:   re.findall(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gt2mptdvvya.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dianchejie.cn/Article/details/gt2ozhwmsyq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zdqjudy.top/Article/details/gt2xwckjemx.html

TS:   s.match(/\d+/g)
来源：http://dali.cheryme.top/Article/details/gt2iezsqerl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yangfankeji.com/Article/details/gt2yejwyrnm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jlsjyb.cn/Article/details/gt2bgsniruu.html

Ruby: s.scan(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gt2nirlgkwk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.0kj1m.cn/Article/details/gt2uhkhsemj.html

[I03] 提取捕获分组
来源：http://dali.aibaodan.cn/Article/details/gt2ewwmpnak.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.9152youxi.cn/Article/details/gt2nxwxpybr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.daria6918.cn/Article/details/gt2jzvannyg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yongpay.top/Article/details/gt2oueypxvc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.meibo888.top/Article/details/gt2zshwkwvn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yangfankeji.com/Article/details/gt2npnjfems.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jyoumei.cn/Article/details/gt2eaezmstr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.quarkkingdee.top/Article/details/gt2tafefhgd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.vqdsnc.cn/Article/details/gt2itjrasin.html

[I04] 正则替换
来源：http://dali.cheryme.top/Article/details/gt2terfgnlv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hnxiangtu.top/Article/details/gt2gvvudrur.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hammf.cn/Article/details/gt2qgdmeabj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tian-w.cn/Article/details/gt2vwjhvvbj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigufen.top/Article/details/gt2zrqaepou.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.dianchejie.cn/Article/details/gt2ijkytfee.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pycfn.com/Article/details/gt2fcdkgavx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daxiang520.top/Article/details/gt2cgilyyts.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zycfv.cn/Article/details/gt2bcpcnnth.html

[I05] 按正则拆分
来源：http://dali.shangyingyoupin.top/Article/details/gt2puvnlpvo.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhongyouzk.top/Article/details/gt2tytutmbw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gt2lttgstpk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gt2qmiykrmg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gt2xlygmpms.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xuetiantiany.cn/Article/details/gt2istkmlvm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jyoumei.cn/Article/details/gt2jfkelqef.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2llngpbda.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xuanzx.com/Article/details/gt2jvuvdkui.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yueranfly.top/Article/details/gt2zyymyyxu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gt2rojoddtb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.birdmap.top/Article/details/gt2qvcrfmtt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.0kj1m.cn/Article/details/gt2wbrhqskh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fzhhl.top/Article/details/gt2vyjrogqm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gt2edftvcqu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.birdmap.top/Article/details/gt2ffmizffq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hnqzz.top/Article/details/gt2tuqujpkb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gt2pgtharxp.html

[I07] 忽略大小写与多行模式
来源：http://dali.wangdashe.top/Article/details/gt2tbuvralx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zdqjudy.top/Article/details/gt2fmoxvnkn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hysaishi.cn/Article/details/gt2htlpygqp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xuanzx.com/Article/details/gt2wtyaekmb.html

TS:   /error/gim
来源：http://dali.gogol.net.cn/Article/details/gt2xixqikqg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.havefunace.top/Article/details/gt2tedszaxp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.fzhhl.top/Article/details/gt2ymkedqmb.html

Ruby: s.scan(/error/i)
来源：http://dali.316326.xyz/Article/details/gt2rvoubmfo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhixingplan.top/Article/details/gt2bhtwlnvz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xziqi.cn/Article/details/gt2jhjqpgtc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenzaomai.com/Article/details/gt2fobbutyd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxuanxn.top/Article/details/gt2xlobmphn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gt2xjdiviuu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuanzhike.top/Article/details/gt2erghrajt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sufxvd.cn/Article/details/gt2apyerxyu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bsdopaxn.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ehwqpu.com/Article/details/gt2hsqycrof.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hongshengwenyu.top/Article/details/gt2agsnpuak.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2ggsxvceo.html

J. 日期与时间
来源：http://dali.cucudq.cn/Article/details/gt2dtwnfnbc.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2jnosgrgy.html

[J01] 获取当前时间
来源：http://dali.hywenlv.cn/Article/details/gt2gbiuinbf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj20258.top/Article/details/gt2mmxmekom.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yonumen.top/Article/details/gt2swzgyeso.html

JS:   new Date();  Date.now()
来源：http://dali.yanxiufei.cn/Article/details/gt2nwyigkuv.html

TS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gt2tvtbbirg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zycfv.cn/Article/details/gt2hxvbwsfd.html

Go:   time.Now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ddquokec.html

Ruby: Time.now
来源：http://dali.gzhubu.top/Article/details/gt2ydamfurw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hnxiangtu.top/Article/details/gt2yqpqvawr.html

[J02] 格式化输出
来源：http://dali.mhx1999.top/Article/details/gt2yshxgrvl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cdnleiting.top/Article/details/gt2qfhlisnf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.9152youxi.cn/Article/details/gt2gahfntrh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.0kj1m.cn/Article/details/gt2zyftopgx.html

TS:   d.toISOString()
来源：http://dali.jlsjyb.cn/Article/details/gt2hdqjpfsg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hnqzz.top/Article/details/gt2pncjoomj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yanxiufei.cn/Article/details/gt2uhowkmrr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xylfe.cn/Article/details/gt2dxgsbdmq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhengqikj.top/Article/details/gt2zbrkcuwl.html

[J03] 字符串解析为日期
来源：http://dali.cashguo.top/Article/details/gt2lfcclcmy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.mhx1999.top/Article/details/gt2mlxmlqhl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cashguo.top/Article/details/gt2oywiwdyh.html

JS:   new Date("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gt2kfzhpazm.html

TS:   new Date("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gt2tkjtcmkr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gt2kdfqfkwq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2gnovgeax.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gt2eewspphh.html


<!-- 参考信息 -->