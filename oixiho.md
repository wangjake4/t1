代发 wailian999

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gt2ppfvmsyp.html

JS:   greet() { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gt2ovjqtowb.html

TS:   greet(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gt2fcmhbitl.html

Java: String greet() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gt2sqmecdfs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gt2sbuyvvkg.html

Ruby: def greet; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2ooxywzey.html

C#:   public string Greet() => Name;
来源：http://dali.cdnleiting.top/Article/details/gt2ijywnbie.html

[G05] 继承
来源：http://dali.yj202588.top/Article/details/gt2nyglfunm.html

Py:   class Admin(User): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jxulwfxb.html

PHP:  class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gt2dbcwsrml.html

JS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2hqmcnfxz.html

TS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gt2duoxewbq.html

Java: class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gt2hcwqewsa.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2fsohrutg.html

Ruby: class Admin < User; end
来源：http://dali.jyoumei.cn/Article/details/gt2tqwejdto.html

C#:   class Admin : User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2manrojcg.html

[G06] 重写方法
来源：http://dali.aibaodan.cn/Article/details/gt2obqumjhd.html

Py:   def greet(self): return "admin"
来源：http://dali.svipenyu.cn/Article/details/gt2qqfixqsn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gt2yukkpgyn.html

JS:   greet() { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gt2elsrtqur.html

TS:   greet(): string { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2haofefdy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2qlifrbln.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nanxinkj.top/Article/details/gt2bwmhafap.html

Ruby: def greet; "admin"; end
来源：http://dali.hfpthk.cn/Article/details/gt2gygagdwc.html

C#:   public override string Greet() => "admin";
来源：http://dali.yuanzhike.top/Article/details/gt2brlhipnn.html

[G07] 调用父类方法
来源：http://dali.jinqigfzy.top/Article/details/gt2yhmoxmwj.html

Py:   super().greet()
来源：http://dali.xylfe.cn/Article/details/gt2wvivoqoa.html

PHP:  parent::greet();
来源：http://dali.chenlongwang.top/Article/details/gt2rehfhmhk.html

JS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gt2hihlpusj.html

TS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gt2orqpaaep.html

Java: super.greet();
来源：http://dali.chenlongwang.top/Article/details/gt2bvhpobtr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.daria6918.cn/Article/details/gt2uxiaesyj.html

Ruby: super
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vfybwvgf.html

C#:   base.Greet();
来源：http://dali.wangshuangyany.cn/Article/details/gt2adttkomg.html

[G08] 静态方法与属性
来源：http://dali.xinyue.icu/Article/details/gt2hraykcsa.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jiagoushi.top/Article/details/gt2wjldkvak.html

PHP:  public static function f() {}
来源：http://dali.vqdsnc.cn/Article/details/gt2xixqcajb.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nielgrfb.html

TS:   static f(): void {}
来源：http://dali.nwbrower.top/Article/details/gt2xqmmeqgg.html

Java: static void f() {}
来源：http://dali.yuxming.cn/Article/details/gt2bzotfqub.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.kuanghao11.cn/Article/details/gt2ykqyutev.html

Ruby: def self.f; end
来源：http://dali.jqgfzy.top/Article/details/gt2ajjjwsci.html

C#:   public static void F() {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ivwdgnzb.html

[G09] 接口 / 抽象类
来源：http://dali.zhoulong.xyz/Article/details/gt2mkbaakqh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shuidangran.top/Article/details/gt2ixlfdhmo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenlongwang.top/Article/details/gt2iwcfklhq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ybcxt.top/Article/details/gt2yixzfzic.html

TS:   interface Shape { area(): number; }
来源：http://dali.yuxming.cn/Article/details/gt2pidemdvh.html

Java: interface Shape { double area(); }
来源：http://dali.cdnleiting.top/Article/details/gt2nmjgcbny.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ppjwa.cn/Article/details/gt2qpbyjygf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xylfe.cn/Article/details/gt2epqvxcjo.html

C#:   interface IShape { double Area(); }
来源：http://dali.shzxlz.cn/Article/details/gt2qlmqvfwl.html

[G10] 访问控制
来源：http://dali.chenlongwang.top/Article/details/gt2aknwozzi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.9152youxi.cn/Article/details/gt2ffigvtnj.html

PHP:  public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gt2nwwhxbbm.html

JS:   #private 字段；其余公开
来源：http://dali.tanke756.top/Article/details/gt2nlwwwtgn.html

TS:   public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gt2ibewrstb.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigufen.top/Article/details/gt2qohurkyf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shzxlz.cn/Article/details/gt2swraxzsw.html

Ruby: public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gt2zsabibyh.html

C#:   public / protected / private / internal
来源：http://dali.cashguo.top/Article/details/gt2qouvfrko.html

[G11] getter / setter
来源：http://dali.xziqi.cn/Article/details/gt2ybduytvt.html

Py:   @property 与 @x.setter
来源：http://dali.hnqzz.top/Article/details/gt2tuxvgzyr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gt2bbcxrrki.html

JS:   get name() { return this._name; }
来源：http://dali.iojbl.cn/Article/details/gt2fnyrkvto.html

TS:   get name(): string { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gt2ggnrldxe.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqstsyu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gt2nfhacnee.html

Ruby: attr_accessor :name
来源：http://dali.yj202588.top/Article/details/gt2qwqtcnxn.html

C#:   public string Name { get; set; }
来源：http://dali.hnxiangtu.top/Article/details/gt2gocqjblq.html

[G12] 对象转字符串
来源：http://dali.svipenyu.cn/Article/details/gt2bbxgdhqm.html

Py:   def __str__(self): return self.name
来源：http://dali.c1oappe.top/Article/details/gt2jmpqhofw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gt2deyovxuy.html

JS:   toString() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2yxrkwsno.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2arupdwig.html

Java: @Override public String toString() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2uwsfspvv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gt2pkmmaarp.html

Ruby: def to_s; @name; end
来源：http://dali.svipenyu.cn/Article/details/gt2simcitnq.html

C#:   public override string ToString() => Name;
来源：http://dali.jlsjyb.cn/Article/details/gt2vkgmyrft.html

[G13] 判断对象类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2lianglem.html

Py:   isinstance(u, User)
来源：http://dali.fzhhl.top/Article/details/gt2kjsdjhom.html

PHP:  $u instanceof User
来源：http://dali.ydzc1.top/Article/details/gt2cmeakwuu.html

JS:   u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gt2qgrdiphv.html

TS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gt2gytfskjp.html

Java: u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gt2dogwqwtb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinqigufen.top/Article/details/gt2eultypjx.html

Ruby: u.is_a?(User)
来源：http://dali.sufxvd.cn/Article/details/gt2mrpoxnsu.html

C#:   u is User
来源：http://dali.hammf.cn/Article/details/gt2mpkdpzba.html

[G14] 数据类 / record
来源：http://dali.ppjwa.cn/Article/details/gt2uvmhaaaw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yvedp.cn/Article/details/gt2oblccsik.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yvedp.cn/Article/details/gt2aemhvkml.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jgsejksg.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenlongwang.top/Article/details/gt2hprwdeae.html

Java: record User(String name, int age) {}
来源：http://dali.zhengqikj.top/Article/details/gt2vfjewwza.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnxiangtu.top/Article/details/gt2ulzaglqh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xuetiantiany.cn/Article/details/gt2qswqhwsq.html

C#:   record User(string Name, int Age);
来源：http://dali.sufxvd.cn/Article/details/gt2hlfdvyql.html

[G15] 枚举
来源：http://dali.yuxming.cn/Article/details/gt2hdipbsqk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj202588.top/Article/details/gt2wdmxihnr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yonumen.top/Article/details/gt2mbomfwle.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.snrcjt.cn/Article/details/gt2spvmtnag.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gt2yviiqpkz.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigufen.top/Article/details/gt2stqvcjks.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gzhubu.top/Article/details/gt2edijdsaa.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxinkj.top/Article/details/gt2hknpchtq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gt2zjeomamo.html

[G16] 对象转数组 / 字典
来源：http://dali.redwolf501.top/Article/details/gt2swzqqfme.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zycfv.cn/Article/details/gt2vvzlbwin.html

PHP:  get_object_vars($obj);
来源：http://dali.gogol.net.cn/Article/details/gt2cbdylccr.html

JS:   Object.entries(obj)
来源：http://dali.316326.xyz/Article/details/gt2sjovgldh.html

TS:   Object.entries(obj)
来源：http://dali.tanke756.top/Article/details/gt2fwyiwtjp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.aizwys.cn/Article/details/gt2jawqeekn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj202588.top/Article/details/gt2idnhpfev.html

Ruby: obj.instance_variables
来源：http://dali.yvedp.cn/Article/details/gt2pzuifkjd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gt2thchrfcq.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ihcvhvtj.html

H. 异常与错误处理
来源：http://dali.gzhubu.top/Article/details/gt2fijeybnd.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2ommornvc.html

[H01] try / catch 基础
来源：http://dali.cheryme.top/Article/details/gt2edswdysi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.havefunace.top/Article/details/gt2sjegvadu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tian-w.cn/Article/details/gt2fhiycred.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hcpjesdx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gt2neklauea.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gsfqlikb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cqqwz.cn/Article/details/gt2zrdwlcbi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2ctwdnaay.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iqzocteh.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zzbfrrpm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ppjwa.cn/Article/details/gt2kwpnkfdv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2mzxdzful.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2xwmxbhut.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gt2bvxybilk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gt2arigkfxq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.guannengcc.top/Article/details/gt2skyivbxn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ivvv.top/Article/details/gt2cppsgzoa.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2ydffdhfp.html

[H03] 主动抛出异常
来源：http://dali.haohaochexian.top/Article/details/gt2utavzphd.html

Py:   raise ValueError("错误信息")
来源：http://dali.hammf.cn/Article/details/gt2vkpftnkq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gt2iilapltp.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gt2sgnkppei.html

TS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gt2gwwlqcyj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gt2yanmfanu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.0kj1m.cn/Article/details/gt2hjdaeqxd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.iojbl.cn/Article/details/gt2taireptn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ptfkhoah.html

[H04] 自定义异常类型
来源：http://dali.shuidangran.top/Article/details/gt2uatwwhzh.html

Py:   class MyError(Exception): pass
来源：http://dali.0kj1m.cn/Article/details/gt2vugxnvhw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gt2rhgnvxgt.html

JS:   class MyError extends Error {}
来源：http://dali.wangdashe.top/Article/details/gt2urgspjhg.html

TS:   class MyError extends Error {}
来源：http://dali.zycfv.cn/Article/details/gt2zyqwiuhd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ydzc1.top/Article/details/gt2rreakldl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.smart0.xyz/Article/details/gt2xrmgkhjn.html

Ruby: class MyError < StandardError; end
来源：http://dali.aizwys.cn/Article/details/gt2axuzaoul.html

C#:   class MyException : Exception {}
来源：http://dali.wangdashe.top/Article/details/gt2kgndarrg.html

[H05] 捕获特定类型
来源：http://dali.quarkkingdee.top/Article/details/gt2uglxyoov.html

Py:   except ValueError as e:
来源：http://dali.jinqigfzy.top/Article/details/gt2jkuwxatc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.aibaodan.cn/Article/details/gt2cvevfdmn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2gvvcmedo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xuanzx.com/Article/details/gt2qwtlhqqs.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.havefunace.top/Article/details/gt2kkrubxax.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yvedp.cn/Article/details/gt2ycqxovyb.html

Ruby: rescue ArgumentError => e
来源：http://dali.iojbl.cn/Article/details/gt2aucnyvjm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj20258.top/Article/details/gt2rawibdoa.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xylfe.cn/Article/details/gt2jgtjyaqk.html

Py:   value = d.get("k") or default
来源：http://dali.cashguo.top/Article/details/gt2ddidlqpp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhongyouzk.top/Article/details/gt2rxifupfl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gt2gsidxinf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gt2gjjnxrii.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wwlilyca.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cdnleiting.top/Article/details/gt2ibvetafh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.0kj1m.cn/Article/details/gt2jpljayif.html

C#:   obj?.A?.B ?? default
来源：http://dali.haohaochexian.top/Article/details/gt2kfvjqnfi.html

[H07] 断言
来源：http://dali.snrcjt.cn/Article/details/gt2gvoxenph.html

Py:   assert x > 0, "必须为正"
来源：http://dali.pycfn.com/Article/details/gt2qjsmykiz.html

PHP:  assert($x > 0);
来源：http://dali.zhixingplan.top/Article/details/gt2wldrnzhe.html

JS:   console.assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gt2jleicifb.html

TS:   console.assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gt2dkyqizif.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yongpay.top/Article/details/gt2onhtpjqo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jyoumei.cn/Article/details/gt2warowhwg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hammf.cn/Article/details/gt2qqxvdsbp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gt2ngcmvdqr.html

[H08] 获取错误信息与堆栈
来源：http://dali.pycfn.com/Article/details/gt2zbxvekjs.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangdashe.top/Article/details/gt2ekrfbgxj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigfzy.top/Article/details/gt2ilakfmhg.html

JS:   e.message;  e.stack
来源：http://dali.wangshuangyany.cn/Article/details/gt2mivvqihu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.iojbl.cn/Article/details/gt2ohwlzgdu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xinyue.icu/Article/details/gt2jddvrvbh.html

Go:   err.Error()
来源：http://dali.yongpay.top/Article/details/gt2hvzfgvyf.html

Ruby: e.message;  e.backtrace
来源：http://dali.daxiang520.top/Article/details/gt2dheoffmp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ybcxt.top/Article/details/gt2xhnkvrhs.html

[H09] 带错误码的异常
来源：http://dali.hnxiangtu.top/Article/details/gt2jxsxpzgq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pycfn.com/Article/details/gt2fihwyhpy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dashuyun.cn/Article/details/gt2yyulxvvv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.meibo888.top/Article/details/gt2vjtyrbwo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhengqikj.top/Article/details/gt2jhfpfbfy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.guowangkeji.top/Article/details/gt2hvotypjh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuxming.cn/Article/details/gt2iswzdmrs.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xylfe.cn/Article/details/gt2yrxzsllt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.feifeiyinyue.top/Article/details/gt2lwimuyvw.html

[H10] 资源自动释放
来源：http://dali.chenjidiqi.icu/Article/details/gt2rlikujje.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2quivwdlt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sweek.top/Article/details/gt2nsfkvwbq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gt2qzlxztni.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gzhubu.top/Article/details/gt2aeuhwdvi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.fzhhl.top/Article/details/gt2vuibwhaq.html

Go:   defer f.Close()
来源：http://dali.ivvv.top/Article/details/gt2ytxmjqxn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj20258.top/Article/details/gt2pszuhdag.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2kvysnppq.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2zdxvjewu.html

I. 正则表达式
来源：http://dali.chenzaomai.com/Article/details/gt2clfggttz.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2gcrfdysw.html

[I01] 判断是否匹配
来源：http://dali.ehwqpu.com/Article/details/gt2ynlrzwbi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gt2bauliyts.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2bkgrufem.html

JS:   /\d+/.test(s)
来源：http://dali.yangfankeji.com/Article/details/gt2irjullsd.html

TS:   /\d+/.test(s)
来源：http://dali.yj202588.top/Article/details/gt2gvhhjest.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.wangdashe.top/Article/details/gt2rhjswwev.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.haohaochexian.top/Article/details/gt2vxdwtjon.html

Ruby: s.match?(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gt2flbsuzmd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dashuyun.cn/Article/details/gt2vbakpstl.html

[I02] 提取所有匹配
来源：http://dali.shzxlz.cn/Article/details/gt2koagblms.html

Py:   re.findall(r"\d+", s)
来源：http://dali.fzhhl.top/Article/details/gt2stbqeihz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nanxinkj.top/Article/details/gt2sghxhqup.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.vqdsnc.cn/Article/details/gt2dfmlhrsy.html

TS:   s.match(/\d+/g)
来源：http://dali.guowangkeji.top/Article/details/gt2dkfspykk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cqqwz.cn/Article/details/gt2ltbmsifd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.fzhhl.top/Article/details/gt2kkfyvfji.html

Ruby: s.scan(/\d+/)
来源：http://dali.daxiang520.top/Article/details/gt2yxrfmkde.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oeucicyn.html

[I03] 提取捕获分组
来源：http://dali.cashguo.top/Article/details/gt2vizywsku.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jianghu66.top/Article/details/gt2nmqyblzx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sxryk.cn/Article/details/gt2xvcmnfcd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tanke756.top/Article/details/gt2nkxikhvl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jgrkcfgi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jiagoushi.top/Article/details/gt2eahyygdu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.guowangkeji.top/Article/details/gt2uezpcxxd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sysykeji.top/Article/details/gt2rhyurrfj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.andypj.xyz/Article/details/gt2lklulanq.html

[I04] 正则替换
来源：http://dali.mhx1999.top/Article/details/gt2sywlrkzb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj20258888.top/Article/details/gt2cahjzjhx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.quarkkingdee.top/Article/details/gt2vmgwnxso.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.vqdsnc.cn/Article/details/gt2slgdguqg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.haohaochexian.top/Article/details/gt2wegpogik.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ppjwa.cn/Article/details/gt2mzkdynea.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yangfankeji.com/Article/details/gt2lekwlzbb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2krjjiowr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gzhubu.top/Article/details/gt2zxnqstzw.html

[I05] 按正则拆分
来源：http://dali.birdmap.top/Article/details/gt2awdyljmi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj202588.top/Article/details/gt2ostxqatv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258.top/Article/details/gt2tzlfvjzl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gt2bhixvier.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jreyfaqc.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jiagoushi.top/Article/details/gt2ryhcahhc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hammf.cn/Article/details/gt2iqhlwnvn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gt2neamhwsx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zycfv.cn/Article/details/gt2nmahymtc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.daxiang520.top/Article/details/gt2pzqpqlmp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gt2eiaqshrf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.quarkkingdee.top/Article/details/gt2nfrsezql.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gt2uelbfhus.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sysykeji.top/Article/details/gt2joefodan.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gt2hpczjdro.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.0kj1m.cn/Article/details/gt2mgwjbhjd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.guowangkeji.top/Article/details/gt2ojpabvua.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gt2vrahjlyv.html

[I07] 忽略大小写与多行模式
来源：http://dali.yanxiufei.cn/Article/details/gt2xdatabns.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.0kj1m.cn/Article/details/gt2onmxpdsw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.daria6918.cn/Article/details/gt2xayzdvez.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.wangshuangyany.cn/Article/details/gt2yasbennl.html

TS:   /error/gim
来源：http://dali.redwolf501.top/Article/details/gt2nvmaucwi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yuxming.cn/Article/details/gt2ymjlnull.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.c1oappe.top/Article/details/gt2ygssazgp.html

Ruby: s.scan(/error/i)
来源：http://dali.sweek.top/Article/details/gt2ytpbdmrw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yongpay.top/Article/details/gt2sidxlbdh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ehwqpu.com/Article/details/gt2cjytppgc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.birdmap.top/Article/details/gt2xhmdmypu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fzcwwzfk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xinyue.icu/Article/details/gt2qwbwtytm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ivvv.top/Article/details/gt2sxcwyxiw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gt2pptkdjrv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hywenlv.cn/Article/details/gt2deectnhh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.quarkkingdee.top/Article/details/gt2wdodmszb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj20258888.top/Article/details/gt2iqptmnsb.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2yyytjuss.html

J. 日期与时间
来源：http://dali.sufxvd.cn/Article/details/gt2tqsgopuc.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2cjkpcvaz.html

[J01] 获取当前时间
来源：http://dali.xinyue.icu/Article/details/gt2azfsdhvz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yuanzhike.top/Article/details/gt2reoqfhmw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.dianchejie.cn/Article/details/gt2zrwyyzju.html

JS:   new Date();  Date.now()
来源：http://dali.gogol.net.cn/Article/details/gt2ngmulnzp.html

TS:   new Date();  Date.now()
来源：http://dali.cashguo.top/Article/details/gt2btlropcd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.daxiang520.top/Article/details/gt2biaaxkso.html

Go:   time.Now()
来源：http://dali.sufxvd.cn/Article/details/gt2gizwkgcs.html

Ruby: Time.now
来源：http://dali.sxryk.cn/Article/details/gt2cnosvqts.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gt2kuthxrnd.html

[J02] 格式化输出
来源：http://dali.yvedp.cn/Article/details/gt2mhptnhax.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ybcxt.top/Article/details/gt2mtwmhpcz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhongyouzk.top/Article/details/gt2gzrvvilq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj20258888.top/Article/details/gt2zabfjkmt.html

TS:   d.toISOString()
来源：http://dali.c1oappe.top/Article/details/gt2xvxwkpnz.html


<!-- 参考信息 -->