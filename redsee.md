代发 wailian999

JS:   this.name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtqoraztcj.html

TS:   name: string = "x";
来源：http://dali.fengsongda.top/Article/details/gtkeduujvg.html

Java: private String name;
来源：http://dali.0kj1m.cn/Article/details/gtssirgjjr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hysaishi.cn/Article/details/gttvlgszpu.html

Ruby: @name = "x"
来源：http://dali.sweek.top/Article/details/gtvnnvxvua.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dashuyun.cn/Article/details/gteosenemz.html

[G04] 定义方法
来源：http://dali.fzhhl.top/Article/details/gtixchuttb.html

Py:   def greet(self): return self.name
来源：http://dali.yangfankeji.com/Article/details/gtfxtjhykn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gtzecpogod.html

JS:   greet() { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtoxucqotj.html

TS:   greet(): string { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtxwilabvm.html

Java: String greet() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtilnzdtvf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnribrvyi.html

Ruby: def greet; @name; end
来源：http://dali.hammf.cn/Article/details/gtbphlehxm.html

C#:   public string Greet() => Name;
来源：http://dali.xuetiantiany.cn/Article/details/gtnffyqbam.html

[G05] 继承
来源：http://dali.ppjwa.cn/Article/details/gtvlehuzto.html

Py:   class Admin(User): pass
来源：http://dali.sweek.top/Article/details/gtqpviqdjr.html

PHP:  class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtjludalfp.html

JS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtqyuhjbpv.html

TS:   class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtsoabiylf.html

Java: class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gteglxlqii.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.daxiang520.top/Article/details/gtrmncfmfr.html

Ruby: class Admin < User; end
来源：http://dali.ydzc1.top/Article/details/gtzzvfbcpm.html

C#:   class Admin : User {}
来源：http://dali.tanke756.top/Article/details/gttecdisqw.html

[G06] 重写方法
来源：http://dali.shangyingyoupin.top/Article/details/gtrdisizep.html

Py:   def greet(self): return "admin"
来源：http://dali.andypj.xyz/Article/details/gtpeanjhvl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtbvizfatz.html

JS:   greet() { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtxnrbbswz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gthlpwiyhx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtybztgezz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.guowangkeji.top/Article/details/gtkziweinp.html

Ruby: def greet; "admin"; end
来源：http://dali.fzhhl.top/Article/details/gttsvdohsg.html

C#:   public override string Greet() => "admin";
来源：http://dali.wangshuangyany.cn/Article/details/gtamknesxf.html

[G07] 调用父类方法
来源：http://dali.aizwys.cn/Article/details/gtysnzfrdo.html

Py:   super().greet()
来源：http://dali.ydzc1.top/Article/details/gtyiumthse.html

PHP:  parent::greet();
来源：http://dali.smart0.xyz/Article/details/gtmzeoxzis.html

JS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gtmkmyjmzd.html

TS:   super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtyagvvbpp.html

Java: super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbajuura.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gogol.net.cn/Article/details/gtbluraqrq.html

Ruby: super
来源：http://dali.hywenlv.cn/Article/details/gtlbeuhzmb.html

C#:   base.Greet();
来源：http://dali.zhongyouzk.top/Article/details/gtobdnfwdn.html

[G08] 静态方法与属性
来源：http://dali.daria6918.cn/Article/details/gtdrcnodzk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jyoumei.cn/Article/details/gtmrncnxck.html

PHP:  public static function f() {}
来源：http://dali.yj202588.top/Article/details/gtkhjrdveb.html

JS:   static f() {}
来源：http://dali.jinqigufen.top/Article/details/gtitfnlacg.html

TS:   static f(): void {}
来源：http://dali.shzxlz.cn/Article/details/gtjedwstft.html

Java: static void f() {}
来源：http://dali.nanxuanxn.top/Article/details/gtbtwwqyvs.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.aizwys.cn/Article/details/gtxrphqpzy.html

Ruby: def self.f; end
来源：http://dali.yangfankeji.com/Article/details/gtdpzjvabt.html

C#:   public static void F() {}
来源：http://dali.dianchejie.cn/Article/details/gtvngkprqi.html

[G09] 接口 / 抽象类
来源：http://dali.fengsongda.top/Article/details/gtuxcwinjf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jqgfzy.top/Article/details/gtrxolyehv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hammf.cn/Article/details/gtogtxymae.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhixingplan.top/Article/details/gtpgortgem.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenjidiqi.icu/Article/details/gtnbyfpzky.html

Java: interface Shape { double area(); }
来源：http://dali.zhongyouzk.top/Article/details/gtporsoaft.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.bjfxy.top/Article/details/gtxyeiejpl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hywenlv.cn/Article/details/gttdyhthep.html

C#:   interface IShape { double Area(); }
来源：http://dali.svipenyu.cn/Article/details/gtivxxhddo.html

[G10] 访问控制
来源：http://dali.nanxinkj.top/Article/details/gthxqekkdb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj20258888.top/Article/details/gtpyqfozkv.html

PHP:  public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtxebqbsjp.html

JS:   #private 字段；其余公开
来源：http://dali.zycfv.cn/Article/details/gtumaxbupm.html

TS:   public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtpowcqnsn.html

Java: public / protected / private / 默认包级
来源：http://dali.gzhubu.top/Article/details/gthebnsvzx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuanzx.com/Article/details/gtqweoxgil.html

Ruby: public / protected / private
来源：http://dali.iojbl.cn/Article/details/gtuhilvrop.html

C#:   public / protected / private / internal
来源：http://dali.guannengcc.top/Article/details/gtzqnvnvet.html

[G11] getter / setter
来源：http://dali.yvedp.cn/Article/details/gtzsifqlnk.html

Py:   @property 与 @x.setter
来源：http://dali.mhx1999.top/Article/details/gtuxentkgy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gtatrmuobb.html

JS:   get name() { return this._name; }
来源：http://dali.yangfankeji.com/Article/details/gtnosahcxw.html

TS:   get name(): string { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gtxwpjreqh.html

Java: public String getName() { return name; }
来源：http://dali.hammf.cn/Article/details/gtvtmvixqf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gtlqvtkfzu.html

Ruby: attr_accessor :name
来源：http://dali.yj20258.top/Article/details/gtahzdrpvh.html

C#:   public string Name { get; set; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxervjszv.html

[G12] 对象转字符串
来源：http://dali.zdqjudy.top/Article/details/gtnoitozqt.html

Py:   def __str__(self): return self.name
来源：http://dali.kuanghao11.cn/Article/details/gtjiiiorxw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gtdcapjeif.html

JS:   toString() { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtjredisdb.html

TS:   toString(): string { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtvxgidewp.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtrikzwmsw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtdakiyyca.html

Ruby: def to_s; @name; end
来源：http://dali.jianghu66.top/Article/details/gtgufdpvwh.html

C#:   public override string ToString() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gtzwnwhbcy.html

[G13] 判断对象类型
来源：http://dali.xinyue.icu/Article/details/gtbiohmcru.html

Py:   isinstance(u, User)
来源：http://dali.yangfankeji.com/Article/details/gtbqxokxjs.html

PHP:  $u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtxztrfpgv.html

JS:   u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gtudlfxnmj.html

TS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gtudiqcykf.html

Java: u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtqfhuaafu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.andypj.xyz/Article/details/gtxkwovdzm.html

Ruby: u.is_a?(User)
来源：http://dali.jqgfzy.top/Article/details/gtjrcivdjn.html

C#:   u is User
来源：http://dali.hysaishi.cn/Article/details/gtsuwcemfu.html

[G14] 数据类 / record
来源：http://dali.nanxinkj.top/Article/details/gtaxaimokm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cucudq.cn/Article/details/gtejcdzlek.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnxiangtu.top/Article/details/gtzjqefwsb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.dianchejie.cn/Article/details/gtmglscdtt.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigfzy.top/Article/details/gtvlseuksw.html

Java: record User(String name, int age) {}
来源：http://dali.jyoumei.cn/Article/details/gtrgcnbtey.html

Go:   type User struct { Name string; Age int }
来源：http://dali.svipenyu.cn/Article/details/gtkuvdonqo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhongyouzk.top/Article/details/gthpncspja.html

C#:   record User(string Name, int Age);
来源：http://dali.yueranfly.top/Article/details/gtjmhunrtn.html

[G15] 枚举
来源：http://dali.sufxvd.cn/Article/details/gthyncxfww.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.fzhhl.top/Article/details/gtisxkpdhq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.iojbl.cn/Article/details/gtbprmdnoa.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.haohaochexian.top/Article/details/gtoqvxtkzk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gtypqugtsu.html

Java: enum Color { RED, GREEN }
来源：http://dali.xuetiantiany.cn/Article/details/gtkypmtqpa.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangdashe.top/Article/details/gtjdsjkinp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.svipenyu.cn/Article/details/gtzxuqseqh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuanzhike.top/Article/details/gtrvafgbyx.html

[G16] 对象转数组 / 字典
来源：http://dali.ybcxt.top/Article/details/gtwulodnmu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.c1oappe.top/Article/details/gtosjxtril.html

PHP:  get_object_vars($obj);
来源：http://dali.0kj1m.cn/Article/details/gtkvkzxuey.html

JS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbccpzsct.html

TS:   Object.entries(obj)
来源：http://dali.daxiang520.top/Article/details/gttiqmiuyq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.haohaochexian.top/Article/details/gtgkezdpba.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shanyushiyangtech.top/Article/details/gtuovvffeg.html

Ruby: obj.instance_variables
来源：http://dali.shuidangran.top/Article/details/gtmjfytynl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gtujkkyhjv.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtexykyqop.html

H. 异常与错误处理
来源：http://dali.tian-w.cn/Article/details/gtzeizqjmx.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtqdtpnpzh.html

[H01] try / catch 基础
来源：http://dali.yuanzhike.top/Article/details/gtiawmtrsk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sxryk.cn/Article/details/gtesffmrgo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sufxvd.cn/Article/details/gtvmdsfrcu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gtiirioptv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gtesihxinb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hfpthk.cn/Article/details/gtkiepquhu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xziqi.cn/Article/details/gtlqztfzkx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yongpay.top/Article/details/gtgtmpwlmq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nwbrower.top/Article/details/gtagrlfqus.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gtysiwyapv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbnnuhsr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gthypgksfy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtbwgqtiig.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtblzlsxip.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtpyiijtvz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuanzx.com/Article/details/gtgrgfzspd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhengqikj.top/Article/details/gtopydxhse.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtsamvqpak.html

[H03] 主动抛出异常
来源：http://dali.c1oappe.top/Article/details/gtfogxifil.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuanzhike.top/Article/details/gtgnqwquov.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtludbdict.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtctetshjs.html

TS:   throw new Error("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtnmygtfff.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtegtbfhpk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.fzhhl.top/Article/details/gtriysrtsh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnxiangtu.top/Article/details/gtnzqmwayo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtopmogfbh.html

[H04] 自定义异常类型
来源：http://dali.hnqzz.top/Article/details/gtcvmspwfo.html

Py:   class MyError(Exception): pass
来源：http://dali.hnqzz.top/Article/details/gtowqswdky.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gtbyqmycng.html

JS:   class MyError extends Error {}
来源：http://dali.xylfe.cn/Article/details/gtscyoezvn.html

TS:   class MyError extends Error {}
来源：http://dali.chenlongwang.top/Article/details/gtadidaqap.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gteymhdnti.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shzxlz.cn/Article/details/gtlbkakovw.html

Ruby: class MyError < StandardError; end
来源：http://dali.gaohongyu789.top/Article/details/gtzfpxaqdm.html

C#:   class MyException : Exception {}
来源：http://dali.gaohongyu789.top/Article/details/gtjkbsupqy.html

[H05] 捕获特定类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtxufybore.html

Py:   except ValueError as e:
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwjleijkd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xziqi.cn/Article/details/gtmgwvxbvg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenlongwang.top/Article/details/gtklstywbi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhoulong.xyz/Article/details/gtztqlhlzd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sweek.top/Article/details/gtsvlcautn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shuidangran.top/Article/details/gtwkqigbok.html

Ruby: rescue ArgumentError => e
来源：http://dali.9152youxi.cn/Article/details/gtbgdnyvuv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhengqikj.top/Article/details/gtpznwcjzi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cheryme.top/Article/details/gtjodcxtqp.html

Py:   value = d.get("k") or default
来源：http://dali.jinghuilouyu.cn/Article/details/gtvofffagk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gttzetxqha.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gtfsvqwmsg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gtuugypfdg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj20258888.top/Article/details/gtbedujmuu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.birdmap.top/Article/details/gtoflfskui.html

Ruby: d&.dig(:a, :b)
来源：http://dali.daria6918.cn/Article/details/gtchzqxqxa.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenlongwang.top/Article/details/gtqbqacjhx.html

[H07] 断言
来源：http://dali.zhiwuduotai.top/Article/details/gtwcqhtikq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yueranfly.top/Article/details/gtixbezfhe.html

PHP:  assert($x > 0);
来源：http://dali.smart0.xyz/Article/details/gtikjolrdy.html

JS:   console.assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gttrofueof.html

TS:   console.assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtssgfrilr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigufen.top/Article/details/gtyvxhzhss.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yuanzhike.top/Article/details/gtmzausomy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gtwqqpsyzp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gtqtiorbbv.html

[H08] 获取错误信息与堆栈
来源：http://dali.ybcxt.top/Article/details/gtkozrrhhp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cucudq.cn/Article/details/gtfcvsygye.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hywenlv.cn/Article/details/gtbwxpjpwj.html

JS:   e.message;  e.stack
来源：http://dali.yanxiufei.cn/Article/details/gtffaakmcx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jyoumei.cn/Article/details/gtytqubnsu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenlongwang.top/Article/details/gtwlmslpfp.html

Go:   err.Error()
来源：http://dali.xinyue.icu/Article/details/gtbuymfapn.html

Ruby: e.message;  e.backtrace
来源：http://dali.fengsongda.top/Article/details/gtztlaeehs.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nwbrower.top/Article/details/gthqzjvhqi.html

[H09] 带错误码的异常
来源：http://dali.shangyingyoupin.top/Article/details/gtdauswvbx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xuanzx.com/Article/details/gtfczturpz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tanke756.top/Article/details/gtnsplbncm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fzhhl.top/Article/details/gtozfohuwa.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nanxinkj.top/Article/details/gteqnauhgz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.guowangkeji.top/Article/details/gtkdtizken.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ivvv.top/Article/details/gthizorvjo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hywenlv.cn/Article/details/gtpavkkrwo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pengpengdd.cyou/Article/details/gtmkrvsxrg.html

[H10] 资源自动释放
来源：http://dali.gzhubu.top/Article/details/gtgkehnswn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgufenzy.top/Article/details/gtqavjvfsp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgxjxhibr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pycfn.com/Article/details/gticxhcvpr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.c1oappe.top/Article/details/gtjohiugmx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yuanzhike.top/Article/details/gtjqntdgyd.html

Go:   defer f.Close()
来源：http://dali.dianchejie.cn/Article/details/gtsubrvgtd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.vqdsnc.cn/Article/details/gtdjjhrysx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtxophiuyq.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtdgvfwwdm.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gtaqoaigqw.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtqjewxyvm.html

[I01] 判断是否匹配
来源：http://dali.hywenlv.cn/Article/details/gtcvpamhuu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yuanzhike.top/Article/details/gtwckpaofj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj20258888.top/Article/details/gtxxobewsd.html

JS:   /\d+/.test(s)
来源：http://dali.shangyingyoupin.top/Article/details/gthmcpwgsg.html

TS:   /\d+/.test(s)
来源：http://dali.redwolf501.top/Article/details/gtpunqpwiy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hammf.cn/Article/details/gtpeunphga.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hnxiangtu.top/Article/details/gtshyhuzva.html

Ruby: s.match?(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gtxgpigvaw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shzxlz.cn/Article/details/gtwjawsklw.html

[I02] 提取所有匹配
来源：http://dali.yj20258888.top/Article/details/gtjopkkfnl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.pycfn.com/Article/details/gtzrfhhibl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gzhubu.top/Article/details/gtvutyisio.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.fzhhl.top/Article/details/gtqjaculus.html

TS:   s.match(/\d+/g)
来源：http://dali.yj202588.top/Article/details/gtynecricj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhongyouzk.top/Article/details/gtmyofnhwh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.feifeiyinyue.top/Article/details/gthnkagyda.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gtuhwutkjl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtmukmcinh.html

[I03] 提取捕获分组
来源：http://dali.tanke756.top/Article/details/gtxztytbiw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258888.top/Article/details/gtaolhakfl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.dashuyun.cn/Article/details/gtbklcydhm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ehwqpu.com/Article/details/gtniifckzb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yanxiufei.cn/Article/details/gtsmpxhsny.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinqigfzy.top/Article/details/gtetandnza.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nanxuanxn.top/Article/details/gtvvleoeie.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sxryk.cn/Article/details/gtpdyruouj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbqsnstse.html

[I04] 正则替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifjiibbz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gotoacloud.top/Article/details/gthjudnesf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hammf.cn/Article/details/gtbvlboweo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cqqwz.cn/Article/details/gtomflegnz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.aibaodan.cn/Article/details/gthdoroobq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sysykeji.top/Article/details/gtcqtsvlwb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xinyue.icu/Article/details/gtladvoxxe.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.bjfxy.top/Article/details/gtxqslbeus.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tian-w.cn/Article/details/gtbfqjjrpx.html

[I05] 按正则拆分
来源：http://dali.9152youxi.cn/Article/details/gtasrahbyj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xylfe.cn/Article/details/gtcocnsaau.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yangfankeji.com/Article/details/gtbzbpqrxc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zycfv.cn/Article/details/gtdbiuwoaf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjqenzaa.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cashguo.top/Article/details/gtgbwnpjst.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtacqfhbps.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gtolxudspr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xuanzx.com/Article/details/gtfzuxevyq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xinyue.icu/Article/details/gtovmkyydk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gtgklafccn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cucudq.cn/Article/details/gturljafse.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xziqi.cn/Article/details/gtzqzmxdna.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jlsjyb.cn/Article/details/gteqoistye.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.birdmap.top/Article/details/gtglfgafnd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yangfankeji.com/Article/details/gtiupzaydh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj202588.top/Article/details/gttdjjjyet.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gtfildzqwv.html

[I07] 忽略大小写与多行模式
来源：http://dali.xylfe.cn/Article/details/gtqqdjpdip.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yueranfly.top/Article/details/gtteqxqfij.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gtofvmpzsc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nwbrower.top/Article/details/gtqsysqvlm.html

TS:   /error/gim
来源：http://dali.xylfe.cn/Article/details/gtammsfwob.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.bjfxy.top/Article/details/gtrwosmnyx.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sweek.top/Article/details/gthwkwmqap.html

Ruby: s.scan(/error/i)
来源：http://dali.dianchejie.cn/Article/details/gtjhnbsxqr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.bjfxy.top/Article/details/gtajmypmqm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gttuevoavj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.iojbl.cn/Article/details/gtxkiwwqsz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gtewakagll.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gtjhlycuyh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shangyingyoupin.top/Article/details/gtpcvkknpb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hywenlv.cn/Article/details/gtfnansipf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gotoacloud.top/Article/details/gthvxufszd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinqigufen.top/Article/details/gtwlwmxrwd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yuanzhike.top/Article/details/gtawjapieg.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtquaqjxrw.html

J. 日期与时间
来源：http://dali.chenjidiqi.icu/Article/details/gtfzwoqqwp.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gttleyystk.html

[J01] 获取当前时间
来源：http://dali.gzhubu.top/Article/details/gtonfrvpbt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shzxlz.cn/Article/details/gterxbhdno.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.chenlongwang.top/Article/details/gtachnmlxv.html

JS:   new Date();  Date.now()
来源：http://dali.sxryk.cn/Article/details/gtpxjwpvqc.html

TS:   new Date();  Date.now()
来源：http://dali.daxiang520.top/Article/details/gteiadrieo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shzxlz.cn/Article/details/gtsxpshfwv.html


<!-- 参考信息 -->