代发 wailian999

C#:   public override string Greet() => "admin";
来源：http://dali.yueranfly.top/Article/details/gtngllutuh.html

[G07] 调用父类方法
来源：http://dali.shuidangran.top/Article/details/gtiqnwigoh.html

Py:   super().greet()
来源：http://dali.sweek.top/Article/details/gtzdpxkyth.html

PHP:  parent::greet();
来源：http://dali.c1oappe.top/Article/details/gtwbmtpwzs.html

JS:   super.greet();
来源：http://dali.zycfv.cn/Article/details/gtzkxzmgdc.html

TS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gtskoqnonl.html

Java: super.greet();
来源：http://dali.hfpthk.cn/Article/details/gtfudarpnq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.havefunace.top/Article/details/gtuctyrosh.html

Ruby: super
来源：http://dali.yueranfly.top/Article/details/gtbrksovpd.html

C#:   base.Greet();
来源：http://dali.316326.xyz/Article/details/gtqkauaohd.html

[G08] 静态方法与属性
来源：http://dali.zhiwuduotai.top/Article/details/gtybwowmsj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shzxlz.cn/Article/details/gtroclajoa.html

PHP:  public static function f() {}
来源：http://dali.nanxuanxn.top/Article/details/gtjbqekkzu.html

JS:   static f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtzzrkcblk.html

TS:   static f(): void {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzswkuubq.html

Java: static void f() {}
来源：http://dali.dashuyun.cn/Article/details/gtiqguoziw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258.top/Article/details/gterkoodqt.html

Ruby: def self.f; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlnkffqsi.html

C#:   public static void F() {}
来源：http://dali.mhx1999.top/Article/details/gtjycsqbah.html

[G09] 接口 / 抽象类
来源：http://dali.yangfankeji.com/Article/details/gttewsnkul.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwzbsvfi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daria6918.cn/Article/details/gtgdgkerkd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xuetiantiany.cn/Article/details/gttepnlosk.html

TS:   interface Shape { area(): number; }
来源：http://dali.yvedp.cn/Article/details/gtkkckzgnu.html

Java: interface Shape { double area(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtkypmwoho.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zycfv.cn/Article/details/gtbnteozwn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.haohaochexian.top/Article/details/gtjqdilutr.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtvjbjprjg.html

[G10] 访问控制
来源：http://dali.yanxiufei.cn/Article/details/gtikmfuorx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ehwqpu.com/Article/details/gtcvhlcinw.html

PHP:  public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gttfcycutk.html

JS:   #private 字段；其余公开
来源：http://dali.jlsjyb.cn/Article/details/gtfvuwnxnp.html

TS:   public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gtqlcjkwgw.html

Java: public / protected / private / 默认包级
来源：http://dali.quarkkingdee.top/Article/details/gtoolubmjq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hammf.cn/Article/details/gtpknuxino.html

Ruby: public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtoenwakjw.html

C#:   public / protected / private / internal
来源：http://dali.yangfankeji.com/Article/details/gtxsniigdk.html

[G11] getter / setter
来源：http://dali.jinqigfzy.top/Article/details/gtpbpbjzgq.html

Py:   @property 与 @x.setter
来源：http://dali.shangyingyoupin.top/Article/details/gtfergyloj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtjxjmdddj.html

JS:   get name() { return this._name; }
来源：http://dali.cashguo.top/Article/details/gtkeffxssa.html

TS:   get name(): string { return this._name; }
来源：http://dali.yvedp.cn/Article/details/gtbgosrbbb.html

Java: public String getName() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtcnklkmzv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gtdmowafmq.html

Ruby: attr_accessor :name
来源：http://dali.daria6918.cn/Article/details/gtuxglimqw.html

C#:   public string Name { get; set; }
来源：http://dali.gzhubu.top/Article/details/gtfscixnuo.html

[G12] 对象转字符串
来源：http://dali.svipenyu.cn/Article/details/gtrhvsniww.html

Py:   def __str__(self): return self.name
来源：http://dali.yangfankeji.com/Article/details/gtqqgcfzux.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gteqouvbvn.html

JS:   toString() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlpmnxfrw.html

TS:   toString(): string { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gtkewofayc.html

Java: @Override public String toString() { return name; }
来源：http://dali.fzhhl.top/Article/details/gtwwrizccj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gtnmmotbtu.html

Ruby: def to_s; @name; end
来源：http://dali.gzhubu.top/Article/details/gtbydzdnby.html

C#:   public override string ToString() => Name;
来源：http://dali.yuanzhike.top/Article/details/gtbyyslgrp.html

[G13] 判断对象类型
来源：http://dali.jinqigfzy.top/Article/details/gtnffivfjd.html

Py:   isinstance(u, User)
来源：http://dali.wangdashe.top/Article/details/gthwyambpj.html

PHP:  $u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gthqzuckln.html

JS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtjstmsrjm.html

TS:   u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gthmhxzzki.html

Java: u instanceof User
来源：http://dali.316326.xyz/Article/details/gtsqmkqcvk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuanzx.com/Article/details/gtedsocwdi.html

Ruby: u.is_a?(User)
来源：http://dali.aizwys.cn/Article/details/gtgsgotmbv.html

C#:   u is User
来源：http://dali.yj20258.top/Article/details/gtoavnunzz.html

[G14] 数据类 / record
来源：http://dali.daxiang520.top/Article/details/gtepnqgtpf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xylfe.cn/Article/details/gtkwkovhqx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jianghu66.top/Article/details/gttkzbejre.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.0kj1m.cn/Article/details/gtrxiemiyq.html

TS:   type User = { name: string; age: number };
来源：http://dali.yuxming.cn/Article/details/gtdmmpvyfx.html

Java: record User(String name, int age) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtdqhocswo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shzxlz.cn/Article/details/gtgomluces.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.redwolf501.top/Article/details/gtkqjmqruv.html

C#:   record User(string Name, int Age);
来源：http://dali.iojbl.cn/Article/details/gtvztcnmce.html

[G15] 枚举
来源：http://dali.andypj.xyz/Article/details/gttglcqiod.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nanxinkj.top/Article/details/gtiaaeaovd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sweek.top/Article/details/gtzklvnmsd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cdnleiting.top/Article/details/gtyiyvdfgr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtlprcumra.html

Java: enum Color { RED, GREEN }
来源：http://dali.guannengcc.top/Article/details/gtczzxedkh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinghuilouyu.cn/Article/details/gtegspoxto.html

Ruby: Color = %i[red green].freeze
来源：http://dali.9152youxi.cn/Article/details/gtrqnfjixk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gtopqrtrwo.html

[G16] 对象转数组 / 字典
来源：http://dali.nanxuanxn.top/Article/details/gtbzlzxjcr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenzaomai.com/Article/details/gtoodhzbew.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gtfuwnskof.html

JS:   Object.entries(obj)
来源：http://dali.jianghu66.top/Article/details/gttumsfgcf.html

TS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gtjfegiqpj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.snrcjt.cn/Article/details/gtoeilcotn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinqigfzy.top/Article/details/gtxmrxqhxc.html

Ruby: obj.instance_variables
来源：http://dali.yanxiufei.cn/Article/details/gtvsmhmagy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jyoumei.cn/Article/details/gtmdyxcjra.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtjxsekafk.html

H. 异常与错误处理
来源：http://dali.xuetiantiany.cn/Article/details/gtcfpblhyp.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtcvvdyeph.html

[H01] try / catch 基础
来源：http://dali.svipenyu.cn/Article/details/gtojpmcixy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cdnleiting.top/Article/details/gtbjklpwdh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.9152youxi.cn/Article/details/gtsczsyafx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gtzqrdkfzh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gtlwvwydsc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.pengpengdd.cyou/Article/details/gtukdhlyog.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwkxekznp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangshuangyany.cn/Article/details/gtknzrglei.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxzqngwlp.html

[H02] finally / ensure 收尾
来源：http://dali.pengpengdd.cyou/Article/details/gtxhrffttu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shangyingyoupin.top/Article/details/gtzofomsyh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtpffuiqyn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtsmoogdot.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtofzcdmkq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtzsnppejw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnqzz.top/Article/details/gtxsnbqgnh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdrackgsx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gticwccpen.html

[H03] 主动抛出异常
来源：http://dali.yuanzhike.top/Article/details/gtgvchavhv.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuanzx.com/Article/details/gttmuqkees.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtbfryjull.html

JS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gtvqfonmbn.html

TS:   throw new Error("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtqpezihuc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtyftdlkhq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.guowangkeji.top/Article/details/gtzzwgvihr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yvedp.cn/Article/details/gtitqvritg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gtzxfvtfok.html

[H04] 自定义异常类型
来源：http://dali.ybcxt.top/Article/details/gttzrnutkx.html

Py:   class MyError(Exception): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfcvpnqs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinqigfzy.top/Article/details/gttfabffxo.html

JS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gtqflpdpco.html

TS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrnykaxi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shangyingyoupin.top/Article/details/gtnfwuomgc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ppjwa.cn/Article/details/gtpeocxsmf.html

Ruby: class MyError < StandardError; end
来源：http://dali.bjfxy.top/Article/details/gtdsowzfom.html

C#:   class MyException : Exception {}
来源：http://dali.xziqi.cn/Article/details/gtguotedao.html

[H05] 捕获特定类型
来源：http://dali.gogol.net.cn/Article/details/gthxfllepb.html

Py:   except ValueError as e:
来源：http://dali.iojbl.cn/Article/details/gtvmslzanh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuetiantiany.cn/Article/details/gthgxcypil.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nanxinkj.top/Article/details/gtrfofrjrx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gtatbidttq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sxryk.cn/Article/details/gteoxgqhyv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.birdmap.top/Article/details/gtreugpzas.html

Ruby: rescue ArgumentError => e
来源：http://dali.xziqi.cn/Article/details/gtcxxusugh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.feifeiyinyue.top/Article/details/gthtozfqcq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jianghu66.top/Article/details/gttcvuovgz.html

Py:   value = d.get("k") or default
来源：http://dali.hongshengwenyu.top/Article/details/gtgoaxqjje.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinghuilouyu.cn/Article/details/gtbggxnbwi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gtitwmhywb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jlsjyb.cn/Article/details/gtjplerepx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gotoacloud.top/Article/details/gtjrzwjixc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cheryme.top/Article/details/gttrzlsdft.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tian-w.cn/Article/details/gtzfmovkcu.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigufen.top/Article/details/gttveakkiw.html

[H07] 断言
来源：http://dali.feifeiyinyue.top/Article/details/gtkauxasay.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimpqyfrq.html

PHP:  assert($x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gttijjsgjq.html

JS:   console.assert(x > 0);
来源：http://dali.dianchejie.cn/Article/details/gtixangqwm.html

TS:   console.assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtjlbagqae.html

Java: assert x > 0 : "必须为正";
来源：http://dali.birdmap.top/Article/details/gtqvoigatr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pengpengdd.cyou/Article/details/gtyzgzavij.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hnqzz.top/Article/details/gtsrfgrkem.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gtpfuddifp.html

[H08] 获取错误信息与堆栈
来源：http://dali.smart0.xyz/Article/details/gtijniqpzi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xinyue.icu/Article/details/gtudbpmkgb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sxryk.cn/Article/details/gtlbkxolhv.html

JS:   e.message;  e.stack
来源：http://dali.ehwqpu.com/Article/details/gtcxcooera.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cashguo.top/Article/details/gtwttiuptl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cucudq.cn/Article/details/gtothhrldm.html

Go:   err.Error()
来源：http://dali.ydzc1.top/Article/details/gtcxtjphyx.html

Ruby: e.message;  e.backtrace
来源：http://dali.shzxlz.cn/Article/details/gtcwdprzgz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnxiangtu.top/Article/details/gtnauupwhw.html

[H09] 带错误码的异常
来源：http://dali.wangshuangyany.cn/Article/details/gtxosrjsfi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cashguo.top/Article/details/gtfyuhplyw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.smart0.xyz/Article/details/gtrqkzkqge.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.pengpengdd.cyou/Article/details/gtofcogort.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tanke756.top/Article/details/gtcxfilrnc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cheryme.top/Article/details/gtsuknowha.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shuidangran.top/Article/details/gtvxzpnarb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tian-w.cn/Article/details/gtrmyfojmc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.daria6918.cn/Article/details/gtcfublyyf.html

[H10] 资源自动释放
来源：http://dali.shuidangran.top/Article/details/gtrnmscbeq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xuetiantiany.cn/Article/details/gthuqgjmoz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gzhubu.top/Article/details/gtjrnmvljf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hywenlv.cn/Article/details/gthnxgmkri.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pengpengdd.cyou/Article/details/gtshcejrlt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yangfankeji.com/Article/details/gtbdfwxxcy.html

Go:   defer f.Close()
来源：http://dali.nwbrower.top/Article/details/gtwntxbjob.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yonumen.top/Article/details/gtwwafmxdd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtafwkcihr.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtmqkmgmdk.html

I. 正则表达式
来源：http://dali.yvedp.cn/Article/details/gtrvqsokwo.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtmlgxutya.html

[I01] 判断是否匹配
来源：http://dali.jqgufenzy.top/Article/details/gtuslznfpw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.birdmap.top/Article/details/gtldoflhhe.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.andypj.xyz/Article/details/gtthgaysvi.html

JS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gtqlmumxer.html

TS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gtlzumseuh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tanke756.top/Article/details/gtofpohjio.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nanxinkj.top/Article/details/gtsbxtdtzo.html

Ruby: s.match?(/\d+/)
来源：http://dali.hammf.cn/Article/details/gtzesvphjb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.redwolf501.top/Article/details/gtdqcqpwlk.html

[I02] 提取所有匹配
来源：http://dali.316326.xyz/Article/details/gtrowhdurs.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gtdvqjosox.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.haohaochexian.top/Article/details/gtwlopagwe.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tian-w.cn/Article/details/gtiyqtoofj.html

TS:   s.match(/\d+/g)
来源：http://dali.aibaodan.cn/Article/details/gtedqdwdol.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ehwqpu.com/Article/details/gtetqzkmyd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ydzc1.top/Article/details/gtbacacxtp.html

Ruby: s.scan(/\d+/)
来源：http://dali.sufxvd.cn/Article/details/gtxyachtzv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtxvfxmfxk.html

[I03] 提取捕获分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtgcqduusk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jiagoushi.top/Article/details/gtctkqucei.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fengsongda.top/Article/details/gtarzrrpcx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdnbcsyem.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.quarkkingdee.top/Article/details/gtekblwvax.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.havefunace.top/Article/details/gtpdqnqmwm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hfpthk.cn/Article/details/gtmryptfbg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhongyouzk.top/Article/details/gtxirlufll.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gthtqureex.html

[I04] 正则替换
来源：http://dali.yueranfly.top/Article/details/gtqebutpsx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cashguo.top/Article/details/gtxmmemfnc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cucudq.cn/Article/details/gtznitnzct.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.316326.xyz/Article/details/gtrfzyuyes.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtjevkzdae.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shuidangran.top/Article/details/gtbtxslbjo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.svipenyu.cn/Article/details/gtjsmymvxs.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.wangdashe.top/Article/details/gtpakymsol.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.guowangkeji.top/Article/details/gtcbahrihr.html

[I05] 按正则拆分
来源：http://dali.zhixingplan.top/Article/details/gtffztkdzi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.fengsongda.top/Article/details/gtzwofvgyt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfazfwqg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gtncvaryxn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gtfxjsnied.html

Java: s.split("\\s*,\\s*")
来源：http://dali.kuanghao11.cn/Article/details/gtghmwessc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cashguo.top/Article/details/gteticlbta.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gtdcbffgll.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tian-w.cn/Article/details/gtyedpcfbz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhoulong.xyz/Article/details/gtdwzlmiuw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gtyegovtvt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cdnleiting.top/Article/details/gtpmpwflqk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.andypj.xyz/Article/details/gtppmbzujr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuetiantiany.cn/Article/details/gtkbwnoafx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gtfmtwfdqw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ehwqpu.com/Article/details/gtfevfdorf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj20258888.top/Article/details/gttcbvnlos.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gtbcprmdod.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinqigfzy.top/Article/details/gtvgrttspi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.haohaochexian.top/Article/details/gtrntbszom.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zycfv.cn/Article/details/gtcbppvsfv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.guannengcc.top/Article/details/gtgrewvdzf.html

TS:   /error/gim
来源：http://dali.daxiang520.top/Article/details/gttdebcvdo.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gogol.net.cn/Article/details/gtgestieup.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhoulong.xyz/Article/details/gtqucglugr.html

Ruby: s.scan(/error/i)
来源：http://dali.gzhubu.top/Article/details/gtwcvobnqa.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nanxinkj.top/Article/details/gthgurqwta.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenlongwang.top/Article/details/gtqizwetrm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nanxuanxn.top/Article/details/gtmamchysq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jianghu66.top/Article/details/gtooprftho.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gtenzdbeqq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gthhicbrhu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.birdmap.top/Article/details/gtwokzfccf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinqigfzy.top/Article/details/gtndpspbiv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.andypj.xyz/Article/details/gtvtdtpaan.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.iojbl.cn/Article/details/gtmizfuneg.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtswbfagap.html

J. 日期与时间
来源：http://dali.pycfn.com/Article/details/gtcycchgvd.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtlqksxkxf.html

[J01] 获取当前时间
来源：http://dali.jinqigufen.top/Article/details/gtygncnrgj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.birdmap.top/Article/details/gthzkfdbjf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.dashuyun.cn/Article/details/gtownuxbbt.html

JS:   new Date();  Date.now()
来源：http://dali.shuidangran.top/Article/details/gtapwqmxsv.html

TS:   new Date();  Date.now()
来源：http://dali.ehwqpu.com/Article/details/gtwidftmdz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.9152youxi.cn/Article/details/gtaxiejuzx.html

Go:   time.Now()
来源：http://dali.redwolf501.top/Article/details/gthbgmfgyb.html

Ruby: Time.now
来源：http://dali.sxryk.cn/Article/details/gtuvwcbyrh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gaohongyu789.top/Article/details/gttjhppwqu.html

[J02] 格式化输出
来源：http://dali.nanxinkj.top/Article/details/gtramftksd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258888.top/Article/details/gtrqdnlzoo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtigvrlube.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zycfv.cn/Article/details/gtudvupnbt.html

TS:   d.toISOString()
来源：http://dali.xinyue.icu/Article/details/gtwvcpvydn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hywenlv.cn/Article/details/gtlefrjlef.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.aizwys.cn/Article/details/gtxipyshml.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hysaishi.cn/Article/details/gtxapkxsly.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.guannengcc.top/Article/details/gtuzytmmpv.html

[J03] 字符串解析为日期
来源：http://dali.ybcxt.top/Article/details/gtcmnvqflp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cheryme.top/Article/details/gtsesacmqu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.quarkkingdee.top/Article/details/gtdqccmupb.html

JS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtoouklmnc.html

TS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtmdchnukr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gthwvpzvsf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtuiuasubo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtkhyvbkjl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cheryme.top/Article/details/gthzqpdrzs.html

[J04] 时间戳与日期互转
来源：http://dali.smart0.xyz/Article/details/gtjzktycgc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.pycfn.com/Article/details/gtdfslxvqe.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tianlin.xyz/Article/details/gtbywngfwu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.svipenyu.cn/Article/details/gtgncmiuac.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.bjfxy.top/Article/details/gtnjbjoipm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shuidangran.top/Article/details/gtlaidrvek.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtreniusvu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.havefunace.top/Article/details/gtnasdtdqf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnqzz.top/Article/details/gtvepyzrqc.html

[J05] 时间加减（加 7 天）
来源：http://dali.meibo888.top/Article/details/gtytqoqkvx.html

Py:   now + timedelta(days=7)
来源：http://dali.haohaochexian.top/Article/details/gtfrkegjdh.html


<!-- 参考信息 -->