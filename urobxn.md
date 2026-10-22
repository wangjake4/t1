代发 wailian999

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gt2jwksjyrz.html

Ruby: def greet; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gt2qrqizwgb.html

C#:   public string Greet() => Name;
来源：http://dali.jqgfzy.top/Article/details/gt2ejsbghqb.html

[G05] 继承
来源：http://dali.jinqigfzy.top/Article/details/gt2hyumdhdd.html

Py:   class Admin(User): pass
来源：http://dali.yj20258888.top/Article/details/gt2busvowyj.html

PHP:  class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gt2ceecijyg.html

JS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gt2nufftfdq.html

TS:   class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gt2dzhtyovk.html

Java: class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gt2mstublmt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gogol.net.cn/Article/details/gt2knsmifxt.html

Ruby: class Admin < User; end
来源：http://dali.jqgufenzy.top/Article/details/gt2npgaropp.html

C#:   class Admin : User {}
来源：http://dali.xinyue.icu/Article/details/gt2okmebxts.html

[G06] 重写方法
来源：http://dali.shzxlz.cn/Article/details/gt2ikzcqayl.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258888.top/Article/details/gt2fzjxuert.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2syilzlcm.html

JS:   greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gt2rtcaremk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gt2djkfsetc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gt2vwzmpexq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.c1oappe.top/Article/details/gt2dzzsjnig.html

Ruby: def greet; "admin"; end
来源：http://dali.tianlin.xyz/Article/details/gt2hstalede.html

C#:   public override string Greet() => "admin";
来源：http://dali.cheryme.top/Article/details/gt2qdomwyii.html

[G07] 调用父类方法
来源：http://dali.zhengqikj.top/Article/details/gt2kyvxwkdn.html

Py:   super().greet()
来源：http://dali.shzxlz.cn/Article/details/gt2odzoylmy.html

PHP:  parent::greet();
来源：http://dali.yj20258888.top/Article/details/gt2pggnxhor.html

JS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gt2xeumchim.html

TS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gt2mdwbpgsy.html

Java: super.greet();
来源：http://dali.hysaishi.cn/Article/details/gt2usudgljj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.meibo888.top/Article/details/gt2xbtmqspp.html

Ruby: super
来源：http://dali.nwbrower.top/Article/details/gt2adeqqwun.html

C#:   base.Greet();
来源：http://dali.fzhhl.top/Article/details/gt2zdmmiprg.html

[G08] 静态方法与属性
来源：http://dali.yvedp.cn/Article/details/gt2ilfipzez.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ydzc1.top/Article/details/gt2tlxcjlxr.html

PHP:  public static function f() {}
来源：http://dali.gogol.net.cn/Article/details/gt2cocldcwb.html

JS:   static f() {}
来源：http://dali.ppjwa.cn/Article/details/gt2eqecbpnt.html

TS:   static f(): void {}
来源：http://dali.jqgufenzy.top/Article/details/gt2cfnjdkzf.html

Java: static void f() {}
来源：http://dali.yonumen.top/Article/details/gt2mtprgnsl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gzhubu.top/Article/details/gt2lszwaobo.html

Ruby: def self.f; end
来源：http://dali.zdqjudy.top/Article/details/gt2kfqslcko.html

C#:   public static void F() {}
来源：http://dali.nanxinkj.top/Article/details/gt2zsmlybvi.html

[G09] 接口 / 抽象类
来源：http://dali.snrcjt.cn/Article/details/gt2zccjsedj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.mhx1999.top/Article/details/gt2wkijdzdp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cheryme.top/Article/details/gt2iqypfxio.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yvedp.cn/Article/details/gt2srakcrtn.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj20258888.top/Article/details/gt2gvkohuee.html

Java: interface Shape { double area(); }
来源：http://dali.hammf.cn/Article/details/gt2vnulguny.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sysykeji.top/Article/details/gt2chncvnpr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jyoumei.cn/Article/details/gt2wbkuuenj.html

C#:   interface IShape { double Area(); }
来源：http://dali.cheryme.top/Article/details/gt2wuxuqbzb.html

[G10] 访问控制
来源：http://dali.xuetiantiany.cn/Article/details/gt2qudmyicc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.0kj1m.cn/Article/details/gt2ibseuqgp.html

PHP:  public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gt2gznyuzqk.html

JS:   #private 字段；其余公开
来源：http://dali.tianlin.xyz/Article/details/gt2rabygfag.html

TS:   public / protected / private
来源：http://dali.yonumen.top/Article/details/gt2vlzeilej.html

Java: public / protected / private / 默认包级
来源：http://dali.9152youxi.cn/Article/details/gt2iwenddwo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tian-w.cn/Article/details/gt2uaufoyeq.html

Ruby: public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gt2ekxuiqsd.html

C#:   public / protected / private / internal
来源：http://dali.cqqwz.cn/Article/details/gt2uergzbmv.html

[G11] getter / setter
来源：http://dali.zhengqikj.top/Article/details/gt2wqsmwjei.html

Py:   @property 与 @x.setter
来源：http://dali.hnxiangtu.top/Article/details/gt2cuhhebbo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gt2lhdesnay.html

JS:   get name() { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gt2xwdisaqa.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ximdhhsm.html

Java: public String getName() { return name; }
来源：http://dali.yueranfly.top/Article/details/gt2emlihhjc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gt2yncdkgzn.html

Ruby: attr_accessor :name
来源：http://dali.hammf.cn/Article/details/gt2elbpdcrz.html

C#:   public string Name { get; set; }
来源：http://dali.jyoumei.cn/Article/details/gt2ifvxgirb.html

[G12] 对象转字符串
来源：http://dali.yj20258.top/Article/details/gt2klmngime.html

Py:   def __str__(self): return self.name
来源：http://dali.gzhubu.top/Article/details/gt2ccsmzcbt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gt2plikvzxg.html

JS:   toString() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gt2pdwsjjqt.html

TS:   toString(): string { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gt2apzonuyx.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2jefnkbdj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gt2tqrxvhtt.html

Ruby: def to_s; @name; end
来源：http://dali.yvedp.cn/Article/details/gt2wipzerzr.html

C#:   public override string ToString() => Name;
来源：http://dali.iojbl.cn/Article/details/gt2kjgamudl.html

[G13] 判断对象类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2mklazbze.html

Py:   isinstance(u, User)
来源：http://dali.ivvv.top/Article/details/gt2vxrsqsqu.html

PHP:  $u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gt2obsxkrhf.html

JS:   u instanceof User
来源：http://dali.tanke756.top/Article/details/gt2hlgrxlzd.html

TS:   u instanceof User
来源：http://dali.pycfn.com/Article/details/gt2tesyoyxj.html

Java: u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gt2rhfpofxp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nwbrower.top/Article/details/gt2pkuanozl.html

Ruby: u.is_a?(User)
来源：http://dali.yuxming.cn/Article/details/gt2ttooedgv.html

C#:   u is User
来源：http://dali.andypj.xyz/Article/details/gt2ugtdgsip.html

[G14] 数据类 / record
来源：http://dali.sxryk.cn/Article/details/gt2tandcbrb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.vqdsnc.cn/Article/details/gt2nzfqijes.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hysaishi.cn/Article/details/gt2rcxfnqyz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.dianchejie.cn/Article/details/gt2xfqvwyvv.html

TS:   type User = { name: string; age: number };
来源：http://dali.redwolf501.top/Article/details/gt2bmtjldmw.html

Java: record User(String name, int age) {}
来源：http://dali.ppjwa.cn/Article/details/gt2iewhsqpy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hywenlv.cn/Article/details/gt2jcqfdsny.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ybcxt.top/Article/details/gt2nrzhnltb.html

C#:   record User(string Name, int Age);
来源：http://dali.yonumen.top/Article/details/gt2lvblryca.html

[G15] 枚举
来源：http://dali.gaohongyu789.top/Article/details/gt2gjcwjjsn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhongyouzk.top/Article/details/gt2ryweybfu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.aizwys.cn/Article/details/gt2uvxkpygm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangdashe.top/Article/details/gt2qmayyaao.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2nudgdrjo.html

Java: enum Color { RED, GREEN }
来源：http://dali.xylfe.cn/Article/details/gt2twdspogb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinqigufen.top/Article/details/gt2mwbgucki.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guowangkeji.top/Article/details/gt2zrhohrxp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gt2cnpdbtlf.html

[G16] 对象转数组 / 字典
来源：http://dali.cheryme.top/Article/details/gt2hlotgtdi.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cheryme.top/Article/details/gt2jnntwoqx.html

PHP:  get_object_vars($obj);
来源：http://dali.nwbrower.top/Article/details/gt2trlrtzhc.html

JS:   Object.entries(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2akmkxrti.html

TS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2xwvbfnjr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhengqikj.top/Article/details/gt2tflrcwul.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.pycfn.com/Article/details/gt2cqqmzybg.html

Ruby: obj.instance_variables
来源：http://dali.yj202588.top/Article/details/gt2ymdpllyk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhoulong.xyz/Article/details/gt2hiwwnfok.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2mdthuofa.html

H. 异常与错误处理
来源：http://dali.xziqi.cn/Article/details/gt2mhrunuvt.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2lluzslgv.html

[H01] try / catch 基础
来源：http://dali.ppjwa.cn/Article/details/gt2ywmofhcu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.kuanghao11.cn/Article/details/gt2rrioqmrr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cdnleiting.top/Article/details/gt2hesjhntz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gt2wuuhqclh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gt2oroiokdv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgufenzy.top/Article/details/gt2zkbjxstt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.dashuyun.cn/Article/details/gt2bffbkcmf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.mhx1999.top/Article/details/gt2dqjkekzl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigufen.top/Article/details/gt2rqdskhcg.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258.top/Article/details/gt2fkptuszd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhixingplan.top/Article/details/gt2wqlwakyb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2bsjxoliw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gt2seikykgl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gt2rvcuoowh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2zroiycat.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yanxiufei.cn/Article/details/gt2vwsxqdrm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hfpthk.cn/Article/details/gt2yfqmrwhy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2jxaybino.html

[H03] 主动抛出异常
来源：http://dali.yj20258888.top/Article/details/gt2jlzlrqvg.html

Py:   raise ValueError("错误信息")
来源：http://dali.haohaochexian.top/Article/details/gt2omnytcba.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gt2orrgjdrx.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sytolooe.html

TS:   throw new Error("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gt2ornrmkvn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gt2posguoao.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.havefunace.top/Article/details/gt2yylgjzlp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.andypj.xyz/Article/details/gt2yzcotpqj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gt2jzgkeobx.html

[H04] 自定义异常类型
来源：http://dali.ivvv.top/Article/details/gt2tvaoiamf.html

Py:   class MyError(Exception): pass
来源：http://dali.birdmap.top/Article/details/gt2wxemgydw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dianchejie.cn/Article/details/gt2jljqesui.html

JS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gt2rqozwzzv.html

TS:   class MyError extends Error {}
来源：http://dali.yangfankeji.com/Article/details/gt2azwzpjge.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2fpconagq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hnqzz.top/Article/details/gt2ffpqydkx.html

Ruby: class MyError < StandardError; end
来源：http://dali.316326.xyz/Article/details/gt2eddzoekw.html

C#:   class MyException : Exception {}
来源：http://dali.shuidangran.top/Article/details/gt2cjcxgtrb.html

[H05] 捕获特定类型
来源：http://dali.hfpthk.cn/Article/details/gt2lyyexche.html

Py:   except ValueError as e:
来源：http://dali.yj202588.top/Article/details/gt2ndgyfqpm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.vqdsnc.cn/Article/details/gt2yxjbnotp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shuidangran.top/Article/details/gt2mahvlayw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gt2jfekasmm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.mhx1999.top/Article/details/gt2iademhuj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.snrcjt.cn/Article/details/gt2ctritqtt.html

Ruby: rescue ArgumentError => e
来源：http://dali.yangfankeji.com/Article/details/gt2hifnqigq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2hmftdzud.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guowangkeji.top/Article/details/gt2jyiaezgg.html

Py:   value = d.get("k") or default
来源：http://dali.yuanzhike.top/Article/details/gt2whfqbinb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hongshengwenyu.top/Article/details/gt2fcmxhiic.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenzaomai.com/Article/details/gt2emttaxyp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenzaomai.com/Article/details/gt2ucgvdabt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhixingplan.top/Article/details/gt2naqqwzyk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jianghu66.top/Article/details/gt2qqdqwosl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nwbrower.top/Article/details/gt2wjvjjvqi.html

C#:   obj?.A?.B ?? default
来源：http://dali.bjfxy.top/Article/details/gt2jsokikhy.html

[H07] 断言
来源：http://dali.wangshuangyany.cn/Article/details/gt2mbpbhtmc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.svipenyu.cn/Article/details/gt2dvmcnwfj.html

PHP:  assert($x > 0);
来源：http://dali.hysaishi.cn/Article/details/gt2dmlsqhrx.html

JS:   console.assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qyfinobt.html

TS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gt2ceaaprfl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.andypj.xyz/Article/details/gt2xvcgagtz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.iojbl.cn/Article/details/gt2hmcgkrgx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xziqi.cn/Article/details/gt2jmybexys.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2utwcgvwg.html

[H08] 获取错误信息与堆栈
来源：http://dali.jqgfzy.top/Article/details/gt2jrrddquz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.fzhhl.top/Article/details/gt2ejzwfjtx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tanke756.top/Article/details/gt2gvwjumrz.html

JS:   e.message;  e.stack
来源：http://dali.vqdsnc.cn/Article/details/gt2bnwfmebb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.havefunace.top/Article/details/gt2ttaiwtpz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hongshengwenyu.top/Article/details/gt2jaxmyhsw.html

Go:   err.Error()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ziidzrzx.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhoulong.xyz/Article/details/gt2aotgebyq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.daxiang520.top/Article/details/gt2phwyxpfz.html

[H09] 带错误码的异常
来源：http://dali.cucudq.cn/Article/details/gt2bdsdvxrl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kxcjnuno.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.guowangkeji.top/Article/details/gt2aoaeulql.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sxryk.cn/Article/details/gt2cfjqtjfj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangdashe.top/Article/details/gt2jkakuusu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ehwqpu.com/Article/details/gt2zxotypha.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ydzc1.top/Article/details/gt2gqnuefko.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.fzhhl.top/Article/details/gt2cjfnosgg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.9152youxi.cn/Article/details/gt2uyfltrio.html

[H10] 资源自动释放
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nbbxdirw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.mhx1999.top/Article/details/gt2jszhmdra.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.andypj.xyz/Article/details/gt2xgjbcrzp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gt2rlfaoagc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gt2dgvcpnoy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yuxming.cn/Article/details/gt2yespxbvl.html

Go:   defer f.Close()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2piuypfkh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.aizwys.cn/Article/details/gt2aaukultp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2tglfigkk.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2pefjkxgy.html

I. 正则表达式
来源：http://dali.dianchejie.cn/Article/details/gt2ehjsespe.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2zomczqyj.html

[I01] 判断是否匹配
来源：http://dali.snrcjt.cn/Article/details/gt2bfdvjivl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shzxlz.cn/Article/details/gt2ffzvigle.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zaabfjby.html

JS:   /\d+/.test(s)
来源：http://dali.tian-w.cn/Article/details/gt2jisanalg.html

TS:   /\d+/.test(s)
来源：http://dali.cheryme.top/Article/details/gt2zmzltzen.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.svipenyu.cn/Article/details/gt2odoxlttu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.aibaodan.cn/Article/details/gt2cyfyfsbb.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhongyouzk.top/Article/details/gt2ojwqluwo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dianchejie.cn/Article/details/gt2nepfatsg.html

[I02] 提取所有匹配
来源：http://dali.yj20258.top/Article/details/gt2lsacinoq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.aibaodan.cn/Article/details/gt2iclnddgu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.iojbl.cn/Article/details/gt2ngoulezv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hyrrmmmg.html

TS:   s.match(/\d+/g)
来源：http://dali.cdnleiting.top/Article/details/gt2yygozmpd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yonumen.top/Article/details/gt2duaoplzd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yuxming.cn/Article/details/gt2dtlvgyrx.html

Ruby: s.scan(/\d+/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2uhobmgjc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gt2ygtzejsy.html

[I03] 提取捕获分组
来源：http://dali.ivvv.top/Article/details/gt2xdqhgflk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.0kj1m.cn/Article/details/gt2ncumobpe.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hysaishi.cn/Article/details/gt2gcjpnqtm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kegodbkd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj20258.top/Article/details/gt2pphutjjz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinqigufen.top/Article/details/gt2yundnsmf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cucudq.cn/Article/details/gt2fsfrozvf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhengqikj.top/Article/details/gt2mhuqrtiq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jyoumei.cn/Article/details/gt2oofpmzwm.html

[I04] 正则替换
来源：http://dali.ydzc1.top/Article/details/gt2azchkjje.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.svipenyu.cn/Article/details/gt2zjdhmoks.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xziqi.cn/Article/details/gt2geisurmt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gt2oiojofmr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cashguo.top/Article/details/gt2mjtalugi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zdqjudy.top/Article/details/gt2egwxhmkj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jlsjyb.cn/Article/details/gt2amkdggba.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.snrcjt.cn/Article/details/gt2gtopcdie.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ttsvodkc.html

[I05] 按正则拆分
来源：http://dali.jinqigfzy.top/Article/details/gt2vdhlulwm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xjfzuazi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2vckorksl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fmdjxdlq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ggvolroq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ydzc1.top/Article/details/gt2raxltglc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhengqikj.top/Article/details/gt2fikdnkdk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gt2tvevmmap.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cucudq.cn/Article/details/gt2amihksjj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gogol.net.cn/Article/details/gt2idbthtqc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gt2rswkjvmy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinghuilouyu.cn/Article/details/gt2frmqdbcz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jyoumei.cn/Article/details/gt2spcfkaoo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinghuilouyu.cn/Article/details/gt2johcmehn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gt2upgehqrj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pengpengdd.cyou/Article/details/gt2udoyawxi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yanxiufei.cn/Article/details/gt2mqivdfli.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gt2dybmzrpz.html

[I07] 忽略大小写与多行模式
来源：http://dali.wangshuangyany.cn/Article/details/gt2vzehfzwa.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tkcnpofb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jqgfzy.top/Article/details/gt2lkhyjbzw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cqqwz.cn/Article/details/gt2iguyeqws.html

TS:   /error/gim
来源：http://dali.ehwqpu.com/Article/details/gt2rxabfymd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fuccgwsa.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ybcxt.top/Article/details/gt2wuzciizs.html

Ruby: s.scan(/error/i)
来源：http://dali.chenjidiqi.icu/Article/details/gt2cvmxaase.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.mhx1999.top/Article/details/gt2hoeaayql.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gogol.net.cn/Article/details/gt2azykqenh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ehwqpu.com/Article/details/gt2wvugjuhd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gaohongyu789.top/Article/details/gt2owopptzn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigfzy.top/Article/details/gt2dxzibkia.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yonumen.top/Article/details/gt2tkraxxeo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sxryk.cn/Article/details/gt2adomlosn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gzhubu.top/Article/details/gt2ijvdesqt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2monvlfnx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.guowangkeji.top/Article/details/gt2rcwewqim.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2qnarvnyz.html

J. 日期与时间
来源：http://dali.kuanghao11.cn/Article/details/gt2zgccdker.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2csfpaabk.html

[J01] 获取当前时间
来源：http://dali.guannengcc.top/Article/details/gt2vgvwmnxl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.snrcjt.cn/Article/details/gt2iuuxddrz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yanxiufei.cn/Article/details/gt2szrngxqp.html

JS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gt2iyggotag.html

TS:   new Date();  Date.now()
来源：http://dali.smart0.xyz/Article/details/gt2swnjrcjp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.havefunace.top/Article/details/gt2ksjcdmwp.html

Go:   time.Now()
来源：http://dali.zhoulong.xyz/Article/details/gt2bmnvjkrs.html

Ruby: Time.now
来源：http://dali.zhixingplan.top/Article/details/gt2ujfflhqc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.0kj1m.cn/Article/details/gt2lelrrsws.html

[J02] 格式化输出
来源：http://dali.andypj.xyz/Article/details/gt2qstjuvej.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.meibo888.top/Article/details/gt2dscghdua.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhengqikj.top/Article/details/gt2bzdjnqed.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuanzx.com/Article/details/gt2ddtvkrba.html

TS:   d.toISOString()
来源：http://dali.ydzc1.top/Article/details/gt2qpoworum.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.mhx1999.top/Article/details/gt2vvvjigln.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hfpthk.cn/Article/details/gt2yqbpqbvq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gt2svxhdwhn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gzhubu.top/Article/details/gt2mxtwpjof.html


<!-- 参考信息 -->