代发 wailian999

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gtpujtjhus.html

JS:   greet() { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtbhqwrajd.html

TS:   greet(): string { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqzjehbxm.html

Java: String greet() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtdoksmidn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gtmoxvyoav.html

Ruby: def greet; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtxtsntqdh.html

C#:   public string Greet() => Name;
来源：http://dali.xylfe.cn/Article/details/gttpmyfkik.html

[G05] 继承
来源：http://dali.dashuyun.cn/Article/details/gtofzbzbkc.html

Py:   class Admin(User): pass
来源：http://dali.smart0.xyz/Article/details/gtjiyknppz.html

PHP:  class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gthtzgswat.html

JS:   class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gtzoqlzalq.html

TS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtyjakwikv.html

Java: class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtkoviyvyv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jiagoushi.top/Article/details/gtbrjrvtok.html

Ruby: class Admin < User; end
来源：http://dali.smart0.xyz/Article/details/gtcfibcyqx.html

C#:   class Admin : User {}
来源：http://dali.chenlongwang.top/Article/details/gtwglnniar.html

[G06] 重写方法
来源：http://dali.316326.xyz/Article/details/gtbonfagzo.html

Py:   def greet(self): return "admin"
来源：http://dali.yuanzhike.top/Article/details/gthkfjztln.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtgujgfroj.html

JS:   greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtfmkcmflx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtqorxlmhb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtzplntjjh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgfzy.top/Article/details/gtznuyaxjh.html

Ruby: def greet; "admin"; end
来源：http://dali.bjfxy.top/Article/details/gtdysgsidq.html

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjoduuikn.html

[G07] 调用父类方法
来源：http://dali.daria6918.cn/Article/details/gtrfbcvkug.html

Py:   super().greet()
来源：http://dali.jqgfzy.top/Article/details/gtuyzwvjjf.html

PHP:  parent::greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtsnmemkmt.html

JS:   super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gtastghhte.html

TS:   super.greet();
来源：http://dali.zhixingplan.top/Article/details/gtciqbmcgw.html

Java: super.greet();
来源：http://dali.xziqi.cn/Article/details/gtubkcljbo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sweek.top/Article/details/gtjhlpxfse.html

Ruby: super
来源：http://dali.cdnleiting.top/Article/details/gtwfjeamzq.html

C#:   base.Greet();
来源：http://dali.hysaishi.cn/Article/details/gtvfjqravb.html

[G08] 静态方法与属性
来源：http://dali.jyoumei.cn/Article/details/gtfbsyyyur.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.redwolf501.top/Article/details/gtwedcfton.html

PHP:  public static function f() {}
来源：http://dali.redwolf501.top/Article/details/gtazbsenuo.html

JS:   static f() {}
来源：http://dali.ydzc1.top/Article/details/gtcozpckdo.html

TS:   static f(): void {}
来源：http://dali.hysaishi.cn/Article/details/gtvydsyjtz.html

Java: static void f() {}
来源：http://dali.xylfe.cn/Article/details/gtojwelwoc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shangyingyoupin.top/Article/details/gtrosrjdux.html

Ruby: def self.f; end
来源：http://dali.xziqi.cn/Article/details/gtvesfhfat.html

C#:   public static void F() {}
来源：http://dali.xuanzx.com/Article/details/gtuqvtojtj.html

[G09] 接口 / 抽象类
来源：http://dali.cqqwz.cn/Article/details/gtqxdvppgh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pycfn.com/Article/details/gtdxkemtzs.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhoulong.xyz/Article/details/gtqxtodpyf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ppjwa.cn/Article/details/gtsksfcigy.html

TS:   interface Shape { area(): number; }
来源：http://dali.sysykeji.top/Article/details/gttxbcxalx.html

Java: interface Shape { double area(); }
来源：http://dali.yvedp.cn/Article/details/gtjrkeacth.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxrmajeak.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhixingplan.top/Article/details/gtfuglbesr.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlcxzackm.html

[G10] 访问控制
来源：http://dali.gzhubu.top/Article/details/gtycmcnmnr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.aibaodan.cn/Article/details/gtfvqdczmi.html

PHP:  public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gtzdhaicum.html

JS:   #private 字段；其余公开
来源：http://dali.xylfe.cn/Article/details/gtynvjugjb.html

TS:   public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gtsawzgzza.html

Java: public / protected / private / 默认包级
来源：http://dali.hongshengwenyu.top/Article/details/gthahpgdvq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guannengcc.top/Article/details/gtluumgfgt.html

Ruby: public / protected / private
来源：http://dali.sweek.top/Article/details/gthpypuuml.html

C#:   public / protected / private / internal
来源：http://dali.yueranfly.top/Article/details/gtdcdbpxgz.html

[G11] getter / setter
来源：http://dali.tian-w.cn/Article/details/gtlslfgdis.html

Py:   @property 与 @x.setter
来源：http://dali.gaohongyu789.top/Article/details/gttvrvczgk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjnroaef.html

JS:   get name() { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gtbbrozbxu.html

TS:   get name(): string { return this._name; }
来源：http://dali.xylfe.cn/Article/details/gtmgvztooq.html

Java: public String getName() { return name; }
来源：http://dali.cheryme.top/Article/details/gtakaqpmdg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gtievfdldf.html

Ruby: attr_accessor :name
来源：http://dali.meibo888.top/Article/details/gtxmhdhnoa.html

C#:   public string Name { get; set; }
来源：http://dali.sufxvd.cn/Article/details/gtpriigsax.html

[G12] 对象转字符串
来源：http://dali.cucudq.cn/Article/details/gtyvlkjvnl.html

Py:   def __str__(self): return self.name
来源：http://dali.yvedp.cn/Article/details/gtamxejrvf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvzudqhwi.html

JS:   toString() { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtjculgwri.html

TS:   toString(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtkccjhvlr.html

Java: @Override public String toString() { return name; }
来源：http://dali.meibo888.top/Article/details/gtxfurbpfk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gtbtfcujgd.html

Ruby: def to_s; @name; end
来源：http://dali.nanxuanxn.top/Article/details/gtaycpepdn.html

C#:   public override string ToString() => Name;
来源：http://dali.aibaodan.cn/Article/details/gtikmlgjyd.html

[G13] 判断对象类型
来源：http://dali.zhixingplan.top/Article/details/gtevgfjsan.html

Py:   isinstance(u, User)
来源：http://dali.ppjwa.cn/Article/details/gtpcmbqera.html

PHP:  $u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtlofpmmqc.html

JS:   u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gtvatnlohr.html

TS:   u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtrwzfxbre.html

Java: u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtfofndbfz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hysaishi.cn/Article/details/gtzfjfbnmf.html

Ruby: u.is_a?(User)
来源：http://dali.sufxvd.cn/Article/details/gtoauhqoml.html

C#:   u is User
来源：http://dali.yuanzhike.top/Article/details/gtyjxmzycq.html

[G14] 数据类 / record
来源：http://dali.nwbrower.top/Article/details/gtjetdwuse.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gotoacloud.top/Article/details/gtetstofdw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yonumen.top/Article/details/gtymbtwtxy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgfzy.top/Article/details/gtdypsyhjz.html

TS:   type User = { name: string; age: number };
来源：http://dali.aibaodan.cn/Article/details/gtnygmohon.html

Java: record User(String name, int age) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqoakubtw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zdqjudy.top/Article/details/gtomgvcyxr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hysaishi.cn/Article/details/gtgydxvoyy.html

C#:   record User(string Name, int Age);
来源：http://dali.iojbl.cn/Article/details/gtltppvwdb.html

[G15] 枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmugazuev.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gogol.net.cn/Article/details/gticyrhccs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.vqdsnc.cn/Article/details/gttnzlffjb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigufen.top/Article/details/gtzrbdqtfx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gtceaquvwp.html

Java: enum Color { RED, GREEN }
来源：http://dali.nanxuanxn.top/Article/details/gthplbbops.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhengqikj.top/Article/details/gtjxnpkimi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sufxvd.cn/Article/details/gtkpynichk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gtnglvgpos.html

[G16] 对象转数组 / 字典
来源：http://dali.haohaochexian.top/Article/details/gtplfwgupd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjfqhwbjv.html

PHP:  get_object_vars($obj);
来源：http://dali.ybcxt.top/Article/details/gtwwffokvu.html

JS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gtryoqusyt.html

TS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvpkjuezd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xuanzx.com/Article/details/gtmuhsntnk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqcihhwe.html

Ruby: obj.instance_variables
来源：http://dali.gogol.net.cn/Article/details/gttjiliduy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gtjurdhnqi.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gttostcyzc.html

H. 异常与错误处理
来源：http://dali.ppjwa.cn/Article/details/gtsejqruol.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtrgejhgcf.html

[H01] try / catch 基础
来源：http://dali.hywenlv.cn/Article/details/gtlqselvux.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yongpay.top/Article/details/gtpjkbqkfv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.bjfxy.top/Article/details/gtrkqgknvt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gttwrttxit.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlrxaghvd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtuqvsaimk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.316326.xyz/Article/details/gtzhjsqopj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhixingplan.top/Article/details/gtzbjkkphj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cashguo.top/Article/details/gtqfofsxmi.html

[H02] finally / ensure 收尾
来源：http://dali.quarkkingdee.top/Article/details/gtnrltsoli.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sysykeji.top/Article/details/gtbxlzflee.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtyzvgydzn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtadqsifeb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gttvzjcpcx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtnzjhubjt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ywan-chungtsiang.top/Article/details/gttupkobla.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ydzc1.top/Article/details/gtbrrcnley.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtusgvfthn.html

[H03] 主动抛出异常
来源：http://dali.andypj.xyz/Article/details/gtgrtzhwmo.html

Py:   raise ValueError("错误信息")
来源：http://dali.iojbl.cn/Article/details/gtvawppvga.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gttgcbqnsz.html

JS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtqywilxpv.html

TS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtezjnyltb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtlpmxvlwj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.c1oappe.top/Article/details/gtuxicrutc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tian-w.cn/Article/details/gtcrhkdrdm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtimbyfvlw.html

[H04] 自定义异常类型
来源：http://dali.cdnleiting.top/Article/details/gtmydaimrj.html

Py:   class MyError(Exception): pass
来源：http://dali.shangyingyoupin.top/Article/details/gtldcvsjjm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinqigufen.top/Article/details/gtscujancj.html

JS:   class MyError extends Error {}
来源：http://dali.yueranfly.top/Article/details/gtpqaasgey.html

TS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gtwhnnhvga.html

Java: class MyException extends RuntimeException {}
来源：http://dali.feifeiyinyue.top/Article/details/gtoiaeenqw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuxming.cn/Article/details/gtkiyxufcy.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenzaomai.com/Article/details/gtxpkoehfa.html

C#:   class MyException : Exception {}
来源：http://dali.xziqi.cn/Article/details/gtwygiqreo.html

[H05] 捕获特定类型
来源：http://dali.dianchejie.cn/Article/details/gtlbwqbetk.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangtech.top/Article/details/gtdkypjqex.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jqgfzy.top/Article/details/gttvconttr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gtnjcnthkx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gtllpimjgd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ppjwa.cn/Article/details/gtacomslcw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwlbuqsir.html

Ruby: rescue ArgumentError => e
来源：http://dali.kuanghao11.cn/Article/details/gtxhgkgogd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj20258888.top/Article/details/gtxzklqccl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yanxiufei.cn/Article/details/gtvowqnjlp.html

Py:   value = d.get("k") or default
来源：http://dali.cucudq.cn/Article/details/gtxsvvygfr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.birdmap.top/Article/details/gtxsfelnzk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gtrcruddhd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuanzx.com/Article/details/gtucokqjqr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tianlin.xyz/Article/details/gtxpktkrmh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cdnleiting.top/Article/details/gtlwdhswji.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gzhubu.top/Article/details/gtiimehpqy.html

C#:   obj?.A?.B ?? default
来源：http://dali.ehwqpu.com/Article/details/gtsopxpgaa.html

[H07] 断言
来源：http://dali.cashguo.top/Article/details/gthqmlmvva.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gogol.net.cn/Article/details/gtgquygppm.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gttsqwyahw.html

JS:   console.assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gtmimenelq.html

TS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtmglrjaho.html

Java: assert x > 0 : "必须为正";
来源：http://dali.iojbl.cn/Article/details/gtfvvsfzff.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenzaomai.com/Article/details/gtyizzzbtp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gogol.net.cn/Article/details/gtstoyyedj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtlyqlvcjr.html

[H08] 获取错误信息与堆栈
来源：http://dali.ppjwa.cn/Article/details/gtgsmeervw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.vqdsnc.cn/Article/details/gtflhymldc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.redwolf501.top/Article/details/gtmffbcrdc.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangtech.top/Article/details/gtgffvkbld.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkuxqwcic.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnqzz.top/Article/details/gtfjevotff.html

Go:   err.Error()
来源：http://dali.chenzaomai.com/Article/details/gtruaemlmj.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj202588.top/Article/details/gtqlabrgrq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xziqi.cn/Article/details/gtbheutdcv.html

[H09] 带错误码的异常
来源：http://dali.wangshuangyany.cn/Article/details/gtpbezoawm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jqgfzy.top/Article/details/gtawvtdwzn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gogol.net.cn/Article/details/gtrphmkkab.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aizwys.cn/Article/details/gtfkwixjsl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.guowangkeji.top/Article/details/gtumqufbrm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ivvv.top/Article/details/gttavwduzz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yueranfly.top/Article/details/gtypmsppzs.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.dashuyun.cn/Article/details/gtebbsqebs.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ppjwa.cn/Article/details/gtruxieixr.html

[H10] 资源自动释放
来源：http://dali.aizwys.cn/Article/details/gtmtlgyruy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cdnleiting.top/Article/details/gtthsvkqzx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.vqdsnc.cn/Article/details/gtpscsmhvh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjpueavia.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangtech.top/Article/details/gtncqilqbd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.haohaochexian.top/Article/details/gtjvbjomks.html

Go:   defer f.Close()
来源：http://dali.zhengqikj.top/Article/details/gtdrydtpwh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenlongwang.top/Article/details/gtdtgzbqcm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtqgwitipf.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtbbfkckmf.html

I. 正则表达式
来源：http://dali.xinyue.icu/Article/details/gtvwkirbpj.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtyvecwkix.html

[I01] 判断是否匹配
来源：http://dali.hammf.cn/Article/details/gtcpylxkww.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jianghu66.top/Article/details/gtiddhiycy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtjlsqsvtu.html

JS:   /\d+/.test(s)
来源：http://dali.sufxvd.cn/Article/details/gtiqcmihff.html

TS:   /\d+/.test(s)
来源：http://dali.kuanghao11.cn/Article/details/gtncqmqctf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.wangshuangyany.cn/Article/details/gtbmtxjtku.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nanxinkj.top/Article/details/gtiksjnjet.html

Ruby: s.match?(/\d+/)
来源：http://dali.pycfn.com/Article/details/gtqhrnnvkp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xziqi.cn/Article/details/gthmnftqfd.html

[I02] 提取所有匹配
来源：http://dali.shuidangran.top/Article/details/gtwvvgoltw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.meibo888.top/Article/details/gtijnczytv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jyoumei.cn/Article/details/gtplsqqwul.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.snrcjt.cn/Article/details/gtgjqdtuln.html

TS:   s.match(/\d+/g)
来源：http://dali.yvedp.cn/Article/details/gtyjojkmsh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hysaishi.cn/Article/details/gtkwmaofam.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgotitlfw.html

Ruby: s.scan(/\d+/)
来源：http://dali.mhx1999.top/Article/details/gtiwnbqxiq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtxvmwhbek.html

[I03] 提取捕获分组
来源：http://dali.pengpengdd.cyou/Article/details/gtbufhdsbz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yuxming.cn/Article/details/gtxoiooliv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.c1oappe.top/Article/details/gtndqpxfpu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yongpay.top/Article/details/gtydnhnvcf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sxryk.cn/Article/details/gtimwanmvb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yanxiufei.cn/Article/details/gtpwfvuvbi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tian-w.cn/Article/details/gtfmknlrjx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtjiqbxcks.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.c1oappe.top/Article/details/gtaojuvtri.html

[I04] 正则替换
来源：http://dali.vqdsnc.cn/Article/details/gtheeazarx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zycfv.cn/Article/details/gtbshcfoha.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspznqqro.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.aizwys.cn/Article/details/gtpdducfmt.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yuanzhike.top/Article/details/gthhbcaetc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gtbjwykwki.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jiagoushi.top/Article/details/gtsucmaksx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtzziacxgt.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nanxuanxn.top/Article/details/gtjfpsmohc.html

[I05] 按正则拆分
来源：http://dali.dianchejie.cn/Article/details/gthxoglfds.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jqgufenzy.top/Article/details/gtgrocztfg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtxhxxzucx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gtrrczkzrr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gthsodcerm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gotoacloud.top/Article/details/gtkkebehbj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhiwuduotai.top/Article/details/gtrcqwcgjr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gtmvjfoqlw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cashguo.top/Article/details/gtcybtbtca.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.haohaochexian.top/Article/details/gtboiidqdk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gtxguudpra.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xylfe.cn/Article/details/gtzspbgdif.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yueranfly.top/Article/details/gtebypgrrz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gtjkxtlajv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gtmmubiiqt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jianghu66.top/Article/details/gtltvoeqep.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenzaomai.com/Article/details/gtjqnmrfwx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gtidahrspo.html

[I07] 忽略大小写与多行模式
来源：http://dali.sysykeji.top/Article/details/gtbmxpuxhc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.iojbl.cn/Article/details/gtgwxulkrc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gtsbowaedr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cucudq.cn/Article/details/gtscevgtxy.html

TS:   /error/gim
来源：http://dali.birdmap.top/Article/details/gtjysrgidm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhongyouzk.top/Article/details/gtavowvwua.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhixingplan.top/Article/details/gtkicaxddi.html

Ruby: s.scan(/error/i)
来源：http://dali.feifeiyinyue.top/Article/details/gtyzcjscbm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shuidangran.top/Article/details/gtkzbmufee.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jiagoushi.top/Article/details/gtpbzssavg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shanyushiyangtech.top/Article/details/gticwbavfp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nwbrower.top/Article/details/gtevqnlvkf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnxiangtu.top/Article/details/gtijmmpdjm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hysaishi.cn/Article/details/gtranzzamj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sufxvd.cn/Article/details/gtkoaslrne.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.guowangkeji.top/Article/details/gtgglzkcet.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258888.top/Article/details/gtektrzebf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shzxlz.cn/Article/details/gtszvcefuc.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtelmppiwo.html

J. 日期与时间
来源：http://dali.hfpthk.cn/Article/details/gtxfqcibcv.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazdltzmt.html

[J01] 获取当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gttxxcmnwg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.quarkkingdee.top/Article/details/gtznzxbaqr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.andypj.xyz/Article/details/gtpiftbxmi.html

JS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gtunzkzuga.html

TS:   new Date();  Date.now()
来源：http://dali.jqgfzy.top/Article/details/gtlakbardp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.pengpengdd.cyou/Article/details/gtwalpcgsg.html

Go:   time.Now()
来源：http://dali.chenzaomai.com/Article/details/gteqhbyejl.html

Ruby: Time.now
来源：http://dali.zhixingplan.top/Article/details/gtdtlrcwgb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aizwys.cn/Article/details/gtfvzsjifv.html

[J02] 格式化输出
来源：http://dali.gogol.net.cn/Article/details/gtkxlpnmum.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gtiqmiqgjr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gttbitkgdc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.redwolf501.top/Article/details/gtkavficex.html

TS:   d.toISOString()
来源：http://dali.cashguo.top/Article/details/gtgqcmefwm.html


<!-- 参考信息 -->