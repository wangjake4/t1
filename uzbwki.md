代发 wailian999

Ruby: @name = "x"
来源：http://dali.shzxlz.cn/Article/details/gtdxpeiext.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj20258.top/Article/details/gthalrfwuz.html

[G04] 定义方法
来源：http://dali.yuxming.cn/Article/details/gtdzwbilsd.html

Py:   def greet(self): return self.name
来源：http://dali.nanxuanxn.top/Article/details/gtwnugwqcv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gtiryaccbs.html

JS:   greet() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtwspztrkr.html

TS:   greet(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtblxsbfts.html

Java: String greet() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcrytbtop.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gtbzurmhwj.html

Ruby: def greet; @name; end
来源：http://dali.wangdashe.top/Article/details/gtnloumlym.html

C#:   public string Greet() => Name;
来源：http://dali.tian-w.cn/Article/details/gtimhfxcie.html

[G05] 继承
来源：http://dali.quarkkingdee.top/Article/details/gtuplungyz.html

Py:   class Admin(User): pass
来源：http://dali.ppjwa.cn/Article/details/gtxiurgkuf.html

PHP:  class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtrxpbqioo.html

JS:   class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtzqxnbzsg.html

TS:   class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtgjsepuva.html

Java: class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtqhpgesqn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj20258.top/Article/details/gtuaaasrab.html

Ruby: class Admin < User; end
来源：http://dali.hnxiangtu.top/Article/details/gtafkjxeab.html

C#:   class Admin : User {}
来源：http://dali.aizwys.cn/Article/details/gtfyhkqcyb.html

[G06] 重写方法
来源：http://dali.aibaodan.cn/Article/details/gtsgqaxkbn.html

Py:   def greet(self): return "admin"
来源：http://dali.ehwqpu.com/Article/details/gtfpsyajsh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtjtpsvneu.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtshhfudio.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gthzguhnqx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtrtkohdsc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.aibaodan.cn/Article/details/gtihullmpd.html

Ruby: def greet; "admin"; end
来源：http://dali.guannengcc.top/Article/details/gthkdbpkjz.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuetiantiany.cn/Article/details/gtjyqqefoc.html

[G07] 调用父类方法
来源：http://dali.aibaodan.cn/Article/details/gtmpcvzduf.html

Py:   super().greet()
来源：http://dali.guannengcc.top/Article/details/gttbfdzpre.html

PHP:  parent::greet();
来源：http://dali.tianlin.xyz/Article/details/gtsfpjpnsg.html

JS:   super.greet();
来源：http://dali.cheryme.top/Article/details/gtycshbftr.html

TS:   super.greet();
来源：http://dali.guowangkeji.top/Article/details/gtyanyygyf.html

Java: super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gtiojggwmy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvnnnfyei.html

Ruby: super
来源：http://dali.jqgufenzy.top/Article/details/gtmfafaeoa.html

C#:   base.Greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbrgfmbm.html

[G08] 静态方法与属性
来源：http://dali.9152youxi.cn/Article/details/gtbakydicf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ppjwa.cn/Article/details/gtcsbyyjqy.html

PHP:  public static function f() {}
来源：http://dali.zhixingplan.top/Article/details/gtkbyypldp.html

JS:   static f() {}
来源：http://dali.yj20258888.top/Article/details/gtgohiruyo.html

TS:   static f(): void {}
来源：http://dali.9152youxi.cn/Article/details/gtnnjfxjcc.html

Java: static void f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtegawhjtv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuetiantiany.cn/Article/details/gtogcpatcq.html

Ruby: def self.f; end
来源：http://dali.gaohongyu789.top/Article/details/gtjlddutpg.html

C#:   public static void F() {}
来源：http://dali.feifeiyinyue.top/Article/details/gttfczklaj.html

[G09] 接口 / 抽象类
来源：http://dali.zhongyouzk.top/Article/details/gtckcwfmxr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.iojbl.cn/Article/details/gtpnidfnek.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jlsjyb.cn/Article/details/gtfbglqrqe.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pengpengdd.cyou/Article/details/gtbrjsewzi.html

TS:   interface Shape { area(): number; }
来源：http://dali.yueranfly.top/Article/details/gtqyfopofh.html

Java: interface Shape { double area(); }
来源：http://dali.xuanzx.com/Article/details/gtijqgtdfi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yueranfly.top/Article/details/gthmjrcwdz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fengsongda.top/Article/details/gtghifdcue.html

C#:   interface IShape { double Area(); }
来源：http://dali.guannengcc.top/Article/details/gtoisctvdo.html

[G10] 访问控制
来源：http://dali.kuanghao11.cn/Article/details/gtzxpkpglp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhiwuduotai.top/Article/details/gtbzasqwoa.html

PHP:  public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gtgftetjxl.html

JS:   #private 字段；其余公开
来源：http://dali.sweek.top/Article/details/gtfbfeyogn.html

TS:   public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gtgqwpholl.html

Java: public / protected / private / 默认包级
来源：http://dali.hongshengwenyu.top/Article/details/gtjwxoozrm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shuidangran.top/Article/details/gtwcdqfibc.html

Ruby: public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gteeyczdat.html

C#:   public / protected / private / internal
来源：http://dali.jyoumei.cn/Article/details/gtudovluob.html

[G11] getter / setter
来源：http://dali.jinghuilouyu.cn/Article/details/gtvoexycby.html

Py:   @property 与 @x.setter
来源：http://dali.kuanghao11.cn/Article/details/gtwsxwwudb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gtdkctklqt.html

JS:   get name() { return this._name; }
来源：http://dali.daria6918.cn/Article/details/gtgdqqdsti.html

TS:   get name(): string { return this._name; }
来源：http://dali.kuanghao11.cn/Article/details/gteaphypvb.html

Java: public String getName() { return name; }
来源：http://dali.havefunace.top/Article/details/gtervcabhx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gtkcnqcntv.html

Ruby: attr_accessor :name
来源：http://dali.bjfxy.top/Article/details/gtbevonllt.html

C#:   public string Name { get; set; }
来源：http://dali.jqgfzy.top/Article/details/gtbyrbahqf.html

[G12] 对象转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtycorsbzq.html

Py:   def __str__(self): return self.name
来源：http://dali.sysykeji.top/Article/details/gtxlwvbcod.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gtdlemglob.html

JS:   toString() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtbyvlwwkh.html

TS:   toString(): string { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtqpvrrzhm.html

Java: @Override public String toString() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtgmxjcndl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shuidangran.top/Article/details/gtshosbraq.html

Ruby: def to_s; @name; end
来源：http://dali.ybcxt.top/Article/details/gtcuddxdcd.html

C#:   public override string ToString() => Name;
来源：http://dali.svipenyu.cn/Article/details/gtzqulhqjx.html

[G13] 判断对象类型
来源：http://dali.zdqjudy.top/Article/details/gtyykwlcql.html

Py:   isinstance(u, User)
来源：http://dali.guowangkeji.top/Article/details/gtshvcqpsa.html

PHP:  $u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtvujxijjt.html

JS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gtylzrbvjt.html

TS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtlekwowja.html

Java: u instanceof User
来源：http://dali.ivvv.top/Article/details/gtijwahtck.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dianchejie.cn/Article/details/gthqvoauzs.html

Ruby: u.is_a?(User)
来源：http://dali.ehwqpu.com/Article/details/gtmmnvkiph.html

C#:   u is User
来源：http://dali.redwolf501.top/Article/details/gtkstviegb.html

[G14] 数据类 / record
来源：http://dali.wangshuangyany.cn/Article/details/gtfhjgilro.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hywenlv.cn/Article/details/gtrtkphbbx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ydzc1.top/Article/details/gtmjzxyhki.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.quarkkingdee.top/Article/details/gtxunelfil.html

TS:   type User = { name: string; age: number };
来源：http://dali.xuetiantiany.cn/Article/details/gtfrfbfdvh.html

Java: record User(String name, int age) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtodbsbrqo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xuetiantiany.cn/Article/details/gtlgkqocem.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gzhubu.top/Article/details/gthdbygija.html

C#:   record User(string Name, int Age);
来源：http://dali.quarkkingdee.top/Article/details/gtyunylcwo.html

[G15] 枚举
来源：http://dali.jinqigufen.top/Article/details/gtjsusilfd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ybcxt.top/Article/details/gtpmghcnkx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ehwqpu.com/Article/details/gtpkjuwkvo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jyoumei.cn/Article/details/gtthaiqvqa.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gtlfvflarf.html

Java: enum Color { RED, GREEN }
来源：http://dali.kuanghao11.cn/Article/details/gtqayaqsod.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfaqjdsio.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnqzz.top/Article/details/gtviujppff.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gtrivbekqa.html

[G16] 对象转数组 / 字典
来源：http://dali.sweek.top/Article/details/gtxetzoumc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.quarkkingdee.top/Article/details/gthzhahetf.html

PHP:  get_object_vars($obj);
来源：http://dali.ehwqpu.com/Article/details/gtlarjsxan.html

JS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtkwlpfmyh.html

TS:   Object.entries(obj)
来源：http://dali.yongpay.top/Article/details/gtjhqbgjey.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xziqi.cn/Article/details/gtawbvugla.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gtwyrxdxuf.html

Ruby: obj.instance_variables
来源：http://dali.hnqzz.top/Article/details/gtodfucmhk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gtimrpnpfo.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtbhhiqide.html

H. 异常与错误处理
来源：http://dali.sufxvd.cn/Article/details/gtiygixyxe.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtiaawejid.html

[H01] try / catch 基础
来源：http://dali.jinghuilouyu.cn/Article/details/gtfdahnacj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.vqdsnc.cn/Article/details/gtgbogdjvr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cheryme.top/Article/details/gtowtoczqt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gtetuzitqh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gtvbulcrvl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgfzy.top/Article/details/gtknujmdyd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjqfwinpk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hongshengwenyu.top/Article/details/gtkmbbffce.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.kuanghao11.cn/Article/details/gtulwsxzho.html

[H02] finally / ensure 收尾
来源：http://dali.shangyingyoupin.top/Article/details/gtobqfizpx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tanke756.top/Article/details/gtsartzyff.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtsuzhrovk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtjlpctnuh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtckrvrpow.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtmpzzjsyb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shuidangran.top/Article/details/gtabrzqdbz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shuidangran.top/Article/details/gttmetrdkd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtjokxrnwp.html

[H03] 主动抛出异常
来源：http://dali.xziqi.cn/Article/details/gthxsmvmmh.html

Py:   raise ValueError("错误信息")
来源：http://dali.meibo888.top/Article/details/gtslwmimwg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtfopbjdjr.html

JS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtilqksknz.html

TS:   throw new Error("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtdmbrdijx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtitdextyq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhongyouzk.top/Article/details/gtirvcttoh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tanke756.top/Article/details/gtcajhaoxr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtwkyrqcgw.html

[H04] 自定义异常类型
来源：http://dali.dianchejie.cn/Article/details/gtsgmlaewh.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxuanxn.top/Article/details/gtzrtdaluv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.0kj1m.cn/Article/details/gtslpvlgsf.html

JS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gtoffethkh.html

TS:   class MyError extends Error {}
来源：http://dali.cqqwz.cn/Article/details/gtofkvwfyt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.mhx1999.top/Article/details/gtgfuyjjmi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.kuanghao11.cn/Article/details/gtnnrkdwrr.html

Ruby: class MyError < StandardError; end
来源：http://dali.daria6918.cn/Article/details/gtesddkqsk.html

C#:   class MyException : Exception {}
来源：http://dali.xuetiantiany.cn/Article/details/gtymutzmwn.html

[H05] 捕获特定类型
来源：http://dali.sysykeji.top/Article/details/gthqtxzmpy.html

Py:   except ValueError as e:
来源：http://dali.jqgufenzy.top/Article/details/gtghuxeurh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jlsjyb.cn/Article/details/gtzttgacdv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.iojbl.cn/Article/details/gtmgcrtxyg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtllgkpwrq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtnloghuol.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.0kj1m.cn/Article/details/gtcdqiaivi.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohivkbbd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhengqikj.top/Article/details/gtyyrerecu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zdqjudy.top/Article/details/gtypvlvxyv.html

Py:   value = d.get("k") or default
来源：http://dali.zhoulong.xyz/Article/details/gtcdrkkpso.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sxryk.cn/Article/details/gtebrdijuh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gtkdsgwkfs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tian-w.cn/Article/details/gtefcrmsyd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ydzc1.top/Article/details/gtwjlgdbuk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.9152youxi.cn/Article/details/gtquwjhgjv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlfmoykbi.html

C#:   obj?.A?.B ?? default
来源：http://dali.meibo888.top/Article/details/gtovuwirxd.html

[H07] 断言
来源：http://dali.xuetiantiany.cn/Article/details/gtnulzoiis.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cdnleiting.top/Article/details/gtyuxbjbep.html

PHP:  assert($x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtwjocttul.html

JS:   console.assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gtynqszwxb.html

TS:   console.assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtaleqseny.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yongpay.top/Article/details/gtkfgypyxf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nanxinkj.top/Article/details/gtwwomqojr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gzhubu.top/Article/details/gtaowaljpc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gtfywiwiqu.html

[H08] 获取错误信息与堆栈
来源：http://dali.jiagoushi.top/Article/details/gtinpimkqn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xuetiantiany.cn/Article/details/gthswysuvf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtubjfwwjp.html

JS:   e.message;  e.stack
来源：http://dali.yonumen.top/Article/details/gtjabtjyfr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.guannengcc.top/Article/details/gttzaxlbjg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.dashuyun.cn/Article/details/gtnujajxpj.html

Go:   err.Error()
来源：http://dali.wangdashe.top/Article/details/gtmpjvwocs.html

Ruby: e.message;  e.backtrace
来源：http://dali.cucudq.cn/Article/details/gtjgfndvdu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cqqwz.cn/Article/details/gtrwblbpfu.html

[H09] 带错误码的异常
来源：http://dali.hongshengwenyu.top/Article/details/gtgjgswdme.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yonumen.top/Article/details/gtflwkdytg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkurpdjwh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jlsjyb.cn/Article/details/gtwjpykgkn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hysaishi.cn/Article/details/gtrmqoprje.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hfpthk.cn/Article/details/gtspfuzimg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.316326.xyz/Article/details/gtlhgjvvfh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shzxlz.cn/Article/details/gtemhwzacf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhengqikj.top/Article/details/gtlftjqqwi.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gtwlzjnakd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xuanzx.com/Article/details/gtcldhzfud.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.havefunace.top/Article/details/gtetxtdtvl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gtukncmpop.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tianlin.xyz/Article/details/gttucccqoi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.mhx1999.top/Article/details/gtmqbgduwq.html

Go:   defer f.Close()
来源：http://dali.zhongyouzk.top/Article/details/gtozszqfcp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hysaishi.cn/Article/details/gtomlkvinb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gttpbobyua.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtcznjhkzt.html

I. 正则表达式
来源：http://dali.sysykeji.top/Article/details/gtolmgwpcv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtxkucnqgj.html

[I01] 判断是否匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtlvdaujpe.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zycfv.cn/Article/details/gtosravngo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtlyroqvem.html

JS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gtqwfgajxo.html

TS:   /\d+/.test(s)
来源：http://dali.daxiang520.top/Article/details/gtvsdrxuat.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.vqdsnc.cn/Article/details/gtamihhuzv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tianlin.xyz/Article/details/gtjpzsxehh.html

Ruby: s.match?(/\d+/)
来源：http://dali.ivvv.top/Article/details/gtnmizzfjv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jianghu66.top/Article/details/gtvhrfwzez.html

[I02] 提取所有匹配
来源：http://dali.andypj.xyz/Article/details/gtfcwkpsog.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cdnleiting.top/Article/details/gtsopocfqr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xziqi.cn/Article/details/gtfymztucc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ehwqpu.com/Article/details/gtpkkgqwfo.html

TS:   s.match(/\d+/g)
来源：http://dali.cucudq.cn/Article/details/gtvpqfxepk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhongyouzk.top/Article/details/gtfkzmrhhm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hammf.cn/Article/details/gtkooodrkz.html

Ruby: s.scan(/\d+/)
来源：http://dali.0kj1m.cn/Article/details/gtnhrdayeq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdnvvetzm.html

[I03] 提取捕获分组
来源：http://dali.zycfv.cn/Article/details/gtkveqdblk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.redwolf501.top/Article/details/gtbcvxmagg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.svipenyu.cn/Article/details/gtadermtss.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yuxming.cn/Article/details/gtlmahlwek.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hysaishi.cn/Article/details/gthxtaaycv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenjidiqi.icu/Article/details/gtwyklzmlh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tanke756.top/Article/details/gtwkdytrpm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sweek.top/Article/details/gtrqaegjdx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hywenlv.cn/Article/details/gtyfgppmlm.html

[I04] 正则替换
来源：http://dali.yangfankeji.com/Article/details/gttlexapbk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.c1oappe.top/Article/details/gtdftcuwhc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ivvv.top/Article/details/gtoujburlr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ydzc1.top/Article/details/gtoeuqyhxp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtoxlnpmcz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hywenlv.cn/Article/details/gtziiaeufc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszppnrds.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.svipenyu.cn/Article/details/gthzjnlrbi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmxribdg.html

[I05] 按正则拆分
来源：http://dali.hywenlv.cn/Article/details/gtawxhcydp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ydzc1.top/Article/details/gtfuseuvis.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtyykxzsta.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gtfotgtdhg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gttqtksxik.html

Java: s.split("\\s*,\\s*")
来源：http://dali.daxiang520.top/Article/details/gtmieyndok.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.dashuyun.cn/Article/details/gtrjclwfup.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gtiykaqhic.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cashguo.top/Article/details/gtudzxluyx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guowangkeji.top/Article/details/gtlubxaqls.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gtskaqhshy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyihvhxjy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shzxlz.cn/Article/details/gtoahgimev.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhengqikj.top/Article/details/gtxtskkzui.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gtsiaotxce.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhiwuduotai.top/Article/details/gtvyumazel.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.guowangkeji.top/Article/details/gtltnzjvvi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gtcgybevsb.html

[I07] 忽略大小写与多行模式
来源：http://dali.xuanzx.com/Article/details/gtislurumk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cheryme.top/Article/details/gtpccnsodg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.birdmap.top/Article/details/gtdgsaecty.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.haohaochexian.top/Article/details/gtlztmsgvc.html

TS:   /error/gim
来源：http://dali.yj20258.top/Article/details/gtjknzvstc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.meibo888.top/Article/details/gtlhygctiu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xinyue.icu/Article/details/gtlmnwtntc.html

Ruby: s.scan(/error/i)
来源：http://dali.hnqzz.top/Article/details/gtddcreixb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yueranfly.top/Article/details/gtutqqgbuj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ydzc1.top/Article/details/gtwehsjojh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.wangshuangyany.cn/Article/details/gtazaywhyu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.vqdsnc.cn/Article/details/gtfsbbyhsq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258888.top/Article/details/gtywmyzrma.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gogol.net.cn/Article/details/gtlvyrykzc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.pengpengdd.cyou/Article/details/gtqsibougu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjlusihd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.daxiang520.top/Article/details/gtrpvaejxi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xuetiantiany.cn/Article/details/gtyiviyicq.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtdiqwqxrd.html

J. 日期与时间
来源：http://dali.guowangkeji.top/Article/details/gtnaajlokf.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtgdidiurk.html

[J01] 获取当前时间
来源：http://dali.ivvv.top/Article/details/gtlgniqbeg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ydzc1.top/Article/details/gtwhlkhvqz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gtxwnhgavi.html

JS:   new Date();  Date.now()
来源：http://dali.ydzc1.top/Article/details/gtmzstbban.html

TS:   new Date();  Date.now()
来源：http://dali.dianchejie.cn/Article/details/gtkzfeiinx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gtpcyehzxf.html

Go:   time.Now()
来源：http://dali.jqgufenzy.top/Article/details/gtbovcynza.html

Ruby: Time.now
来源：http://dali.cucudq.cn/Article/details/gtbaxcampy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zdqjudy.top/Article/details/gtcktpvwfk.html

[J02] 格式化输出
来源：http://dali.cqqwz.cn/Article/details/gtabibevim.html


<!-- 参考信息 -->