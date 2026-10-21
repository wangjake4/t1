代发 wailian999

Ruby: @name = "x"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqjgpjfp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jiagoushi.top/Article/details/gtjjypjvbw.html

[G04] 定义方法
来源：http://dali.hongshengwenyu.top/Article/details/gtnmeowkmb.html

Py:   def greet(self): return self.name
来源：http://dali.xuetiantiany.cn/Article/details/gthdrzsyzh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gtxmkdguyt.html

JS:   greet() { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtsbfhgumd.html

TS:   greet(): string { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gtviapczvx.html

Java: String greet() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gthzcznoza.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shuidangran.top/Article/details/gtlcpinsjh.html

Ruby: def greet; @name; end
来源：http://dali.yuxming.cn/Article/details/gttparzhkm.html

C#:   public string Greet() => Name;
来源：http://dali.iojbl.cn/Article/details/gtvffzxknl.html

[G05] 继承
来源：http://dali.pengpengdd.cyou/Article/details/gtzbohmcry.html

Py:   class Admin(User): pass
来源：http://dali.sysykeji.top/Article/details/gtcyvtbsri.html

PHP:  class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtphelevln.html

JS:   class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gtcfpizmdd.html

TS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtvpapxzol.html

Java: class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtmsuwazci.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ppjwa.cn/Article/details/gtanhoweda.html

Ruby: class Admin < User; end
来源：http://dali.haohaochexian.top/Article/details/gtvvvgeezi.html

C#:   class Admin : User {}
来源：http://dali.guannengcc.top/Article/details/gtdtvnfdyp.html

[G06] 重写方法
来源：http://dali.gaohongyu789.top/Article/details/gtukqvgqzq.html

Py:   def greet(self): return "admin"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrzdxykgj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzsdxpbeo.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtfcwmtgll.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gtfobtdtew.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwcqeymka.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenzaomai.com/Article/details/gtugqtdoci.html

Ruby: def greet; "admin"; end
来源：http://dali.gaohongyu789.top/Article/details/gtcjcawjiq.html

C#:   public override string Greet() => "admin";
来源：http://dali.aibaodan.cn/Article/details/gtxpxynnvd.html

[G07] 调用父类方法
来源：http://dali.wangdashe.top/Article/details/gtgcsuxgil.html

Py:   super().greet()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggyouwys.html

PHP:  parent::greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtkcprnlqg.html

JS:   super.greet();
来源：http://dali.yuxming.cn/Article/details/gtdlsnzihl.html

TS:   super.greet();
来源：http://dali.xylfe.cn/Article/details/gttzggmssb.html

Java: super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtxlmzhvlt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yonumen.top/Article/details/gtucubejgk.html

Ruby: super
来源：http://dali.hywenlv.cn/Article/details/gtosrpzomk.html

C#:   base.Greet();
来源：http://dali.daxiang520.top/Article/details/gtmepgmtdx.html

[G08] 静态方法与属性
来源：http://dali.zhoulong.xyz/Article/details/gtqqogfetz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhongyouzk.top/Article/details/gtwaiktaaw.html

PHP:  public static function f() {}
来源：http://dali.nanxuanxn.top/Article/details/gtxxijnmwh.html

JS:   static f() {}
来源：http://dali.svipenyu.cn/Article/details/gtvlbqjjct.html

TS:   static f(): void {}
来源：http://dali.bjfxy.top/Article/details/gtocquurbg.html

Java: static void f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtwapmwrsg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hongshengwenyu.top/Article/details/gtarixnmyx.html

Ruby: def self.f; end
来源：http://dali.jianghu66.top/Article/details/gtlvliyttb.html

C#:   public static void F() {}
来源：http://dali.yueranfly.top/Article/details/gtbqhmvzcl.html

[G09] 接口 / 抽象类
来源：http://dali.jianghu66.top/Article/details/gtspzxpyzq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yuxming.cn/Article/details/gtgfuakbul.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenzaomai.com/Article/details/gtesawkxnc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ybcxt.top/Article/details/gtdcnvgdgd.html

TS:   interface Shape { area(): number; }
来源：http://dali.tian-w.cn/Article/details/gtowtjpmvc.html

Java: interface Shape { double area(); }
来源：http://dali.zhengqikj.top/Article/details/gtxckiftsl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zdqjudy.top/Article/details/gtyscwkhdb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhengqikj.top/Article/details/gtnxjuwsop.html

C#:   interface IShape { double Area(); }
来源：http://dali.cqqwz.cn/Article/details/gtwmssiyxw.html

[G10] 访问控制
来源：http://dali.xuanzx.com/Article/details/gtfzhakgpc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.smart0.xyz/Article/details/gtkyxdouwl.html

PHP:  public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gttewrsmol.html

JS:   #private 字段；其余公开
来源：http://dali.zycfv.cn/Article/details/gtspvfqqjn.html

TS:   public / protected / private
来源：http://dali.yj20258.top/Article/details/gttygdzmlu.html

Java: public / protected / private / 默认包级
来源：http://dali.chenlongwang.top/Article/details/gttxhekxat.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jlsjyb.cn/Article/details/gtfywlrsvr.html

Ruby: public / protected / private
来源：http://dali.cashguo.top/Article/details/gtbsbjches.html

C#:   public / protected / private / internal
来源：http://dali.feifeiyinyue.top/Article/details/gtwrmnwyls.html

[G11] getter / setter
来源：http://dali.hnxiangtu.top/Article/details/gtyauquxdn.html

Py:   @property 与 @x.setter
来源：http://dali.haohaochexian.top/Article/details/gtcazowwal.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gtmjielizr.html

JS:   get name() { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtyqczstdi.html

TS:   get name(): string { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gtctytpqrb.html

Java: public String getName() { return name; }
来源：http://dali.yj20258.top/Article/details/gtodjcphtr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gtmnzsacye.html

Ruby: attr_accessor :name
来源：http://dali.zdqjudy.top/Article/details/gtknmwlbas.html

C#:   public string Name { get; set; }
来源：http://dali.zhoulong.xyz/Article/details/gtiumfybqi.html

[G12] 对象转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gticpxzmdi.html

Py:   def __str__(self): return self.name
来源：http://dali.chenlongwang.top/Article/details/gtjbhtwntt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gtbyjtlqmw.html

JS:   toString() { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gtwyyrdktd.html

TS:   toString(): string { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtlcqalqwf.html

Java: @Override public String toString() { return name; }
来源：http://dali.shuidangran.top/Article/details/gthjrrwhmi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gtgfwpohgj.html

Ruby: def to_s; @name; end
来源：http://dali.kuanghao11.cn/Article/details/gtetrfhrkp.html

C#:   public override string ToString() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwsdohgo.html

[G13] 判断对象类型
来源：http://dali.fzhhl.top/Article/details/gtspqpytym.html

Py:   isinstance(u, User)
来源：http://dali.fzhhl.top/Article/details/gtsjhgtbjx.html

PHP:  $u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtgyiihqfa.html

JS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtinrerwyk.html

TS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtzdbynyxk.html

Java: u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gtcoxyoomn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sxryk.cn/Article/details/gtuoexvncx.html

Ruby: u.is_a?(User)
来源：http://dali.cheryme.top/Article/details/gtyloenwbl.html

C#:   u is User
来源：http://dali.andypj.xyz/Article/details/gtyxechozg.html

[G14] 数据类 / record
来源：http://dali.xuetiantiany.cn/Article/details/gtubtvxfqh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxuanxn.top/Article/details/gthoymfzyq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhongyouzk.top/Article/details/gtdbhnkxbg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nwbrower.top/Article/details/gtisqpxtlm.html

TS:   type User = { name: string; age: number };
来源：http://dali.smart0.xyz/Article/details/gtmnjyoqbk.html

Java: record User(String name, int age) {}
来源：http://dali.hnqzz.top/Article/details/gtwttoofpu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hywenlv.cn/Article/details/gtesqinzxo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jyoumei.cn/Article/details/gtzaaiexfs.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxuanxn.top/Article/details/gtnrjaasrw.html

[G15] 枚举
来源：http://dali.haohaochexian.top/Article/details/gtmbyayzlz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gotoacloud.top/Article/details/gtlxnlzviy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yueranfly.top/Article/details/gtnzhihrkz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhixingplan.top/Article/details/gtombcnpwb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hysaishi.cn/Article/details/gtwkvkhuhf.html

Java: enum Color { RED, GREEN }
来源：http://dali.nwbrower.top/Article/details/gtmiepjzig.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpqvehvos.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvouldxcy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtckqqxfeu.html

[G16] 对象转数组 / 字典
来源：http://dali.0kj1m.cn/Article/details/gtshkaxxra.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.pengpengdd.cyou/Article/details/gtjvsauird.html

PHP:  get_object_vars($obj);
来源：http://dali.zhixingplan.top/Article/details/gtbcztzhav.html

JS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gtnufwxdvi.html

TS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gtkicdnknw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.havefunace.top/Article/details/gtyygywywj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shangyingyoupin.top/Article/details/gtdmhthwpr.html

Ruby: obj.instance_variables
来源：http://dali.kuanghao11.cn/Article/details/gtofrqtqyf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gtvhfnktmj.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtcquuioji.html

H. 异常与错误处理
来源：http://dali.cucudq.cn/Article/details/gtcrihfamr.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtlqryzcap.html

[H01] try / catch 基础
来源：http://dali.gaohongyu789.top/Article/details/gtdmzhpunk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj202588.top/Article/details/gtsgknmtbs.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yanxiufei.cn/Article/details/gtcwabphvj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenlongwang.top/Article/details/gtzbldgmbx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gtlggtdilj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yongpay.top/Article/details/gteppcqjyw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tianlin.xyz/Article/details/gtrbowvsvd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.svipenyu.cn/Article/details/gtjinhrdhg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nanxuanxn.top/Article/details/gtyzyucnag.html

[H02] finally / ensure 收尾
来源：http://dali.guowangkeji.top/Article/details/gtfjuipnds.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.andypj.xyz/Article/details/gtjfmgrwty.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtczfkhahr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtctwuyeha.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtofzdnvym.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtbuipyamx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.haohaochexian.top/Article/details/gtsyjysjvp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangdashe.top/Article/details/gtbdwlpfty.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtmanpxxnv.html

[H03] 主动抛出异常
来源：http://dali.hywenlv.cn/Article/details/gtganjwopr.html

Py:   raise ValueError("错误信息")
来源：http://dali.fengsongda.top/Article/details/gtrsynpxbk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtzlrvanrp.html

JS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtvpkyoufn.html

TS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtidjupeds.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtjulqczdy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hammf.cn/Article/details/gtgqnkeloz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenjidiqi.icu/Article/details/gtsvhjdwxs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gthxndbmvt.html

[H04] 自定义异常类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxjoqekoh.html

Py:   class MyError(Exception): pass
来源：http://dali.jyoumei.cn/Article/details/gtigbjfunf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gtrgazluxp.html

JS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gtzoiwklfr.html

TS:   class MyError extends Error {}
来源：http://dali.zhengqikj.top/Article/details/gtjrpajdsu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gtojpmvvdl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.iojbl.cn/Article/details/gtmgtuuzev.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhiwuduotai.top/Article/details/gtxelqgatf.html

C#:   class MyException : Exception {}
来源：http://dali.feifeiyinyue.top/Article/details/gterrcrfgy.html

[H05] 捕获特定类型
来源：http://dali.aizwys.cn/Article/details/gtymdeqteu.html

Py:   except ValueError as e:
来源：http://dali.quarkkingdee.top/Article/details/gtkjsvqpno.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigufen.top/Article/details/gtpmiibqus.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shuidangran.top/Article/details/gtqmmesewg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gtidwbgeaj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.svipenyu.cn/Article/details/gtyplkdmkf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.andypj.xyz/Article/details/gttljgster.html

Ruby: rescue ArgumentError => e
来源：http://dali.ivvv.top/Article/details/gtgvpwncpt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cheryme.top/Article/details/gthyhjldvk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yvedp.cn/Article/details/gtjdytwmks.html

Py:   value = d.get("k") or default
来源：http://dali.fzhhl.top/Article/details/gteyvqcxac.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gtnakmfmcr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.meibo888.top/Article/details/gtpbkurbhj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhoulong.xyz/Article/details/gtvfvvdfjw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xuanzx.com/Article/details/gtacvwhnct.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.guannengcc.top/Article/details/gtowwhbnlw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenjidiqi.icu/Article/details/gtxxhfcihr.html

C#:   obj?.A?.B ?? default
来源：http://dali.pycfn.com/Article/details/gtpwiwjhni.html

[H07] 断言
来源：http://dali.zhoulong.xyz/Article/details/gtlwnerogc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aibaodan.cn/Article/details/gtpnhntppi.html

PHP:  assert($x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtvhjqzxur.html

JS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gthjwzspml.html

TS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gtofgppgqw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shuidangran.top/Article/details/gtssjhssfs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cashguo.top/Article/details/gtrntxxnke.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ydzc1.top/Article/details/gthwlttlnk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sweek.top/Article/details/gtikltydmm.html

[H08] 获取错误信息与堆栈
来源：http://dali.yuanzhike.top/Article/details/gtgqzqhqlz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinqigfzy.top/Article/details/gtwjhmxgfc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cqqwz.cn/Article/details/gtvhrzsdcz.html

JS:   e.message;  e.stack
来源：http://dali.ybcxt.top/Article/details/gtkrvsdsik.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenlongwang.top/Article/details/gtjolasspv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sufxvd.cn/Article/details/gtaobzoihz.html

Go:   err.Error()
来源：http://dali.pycfn.com/Article/details/gtutwfnwlk.html

Ruby: e.message;  e.backtrace
来源：http://dali.yueranfly.top/Article/details/gtowxljrsd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.guannengcc.top/Article/details/gtwnbtzeoj.html

[H09] 带错误码的异常
来源：http://dali.svipenyu.cn/Article/details/gtuvdhuubp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbijoelx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nanxuanxn.top/Article/details/gtjsiwifgd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shuidangran.top/Article/details/gtzihodden.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ybcxt.top/Article/details/gtznygpkwa.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.feifeiyinyue.top/Article/details/gtzzyfldlb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sweek.top/Article/details/gtstyhgvzq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sweek.top/Article/details/gtrnexgojb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yuxming.cn/Article/details/gtkxpgqngz.html

[H10] 资源自动释放
来源：http://dali.mhx1999.top/Article/details/gtttmyxdhe.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jlsjyb.cn/Article/details/gtoacrqjmo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pycfn.com/Article/details/gtjdobmhtf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gtldlwbupv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgfzy.top/Article/details/gtbhlqtemr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yonumen.top/Article/details/gtmgdirjgk.html

Go:   defer f.Close()
来源：http://dali.aibaodan.cn/Article/details/gtjxxhxgtp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sysykeji.top/Article/details/gtdcfbzqoe.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gteceaijdu.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtuhtqovkt.html

I. 正则表达式
来源：http://dali.snrcjt.cn/Article/details/gtvnulglnd.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtkmbakwol.html

[I01] 判断是否匹配
来源：http://dali.zhixingplan.top/Article/details/gtylrhcyhs.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.iojbl.cn/Article/details/gthvkfdywu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cucudq.cn/Article/details/gtdvchigyg.html

JS:   /\d+/.test(s)
来源：http://dali.jianghu66.top/Article/details/gtadzhzpbm.html

TS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gtfcyxzarc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinqigufen.top/Article/details/gtckhswtno.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.snrcjt.cn/Article/details/gtkvorryuj.html

Ruby: s.match?(/\d+/)
来源：http://dali.hnxiangtu.top/Article/details/gtswsmwnag.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangshuangyany.cn/Article/details/gtybyilrgp.html

[I02] 提取所有匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtmvxbnkpk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sxryk.cn/Article/details/gtrqconlgf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nanxinkj.top/Article/details/gtbxehedsz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gaohongyu789.top/Article/details/gtosnnlpto.html

TS:   s.match(/\d+/g)
来源：http://dali.cheryme.top/Article/details/gtbyzsanim.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sxryk.cn/Article/details/gtouzhtxzu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.vqdsnc.cn/Article/details/gtfnunrocj.html

Ruby: s.scan(/\d+/)
来源：http://dali.quarkkingdee.top/Article/details/gtmgyayjjx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hfpthk.cn/Article/details/gtznwxvzyt.html

[I03] 提取捕获分组
来源：http://dali.pengpengdd.cyou/Article/details/gtqduycugt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258.top/Article/details/gtointlxxh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.daxiang520.top/Article/details/gtvfbpdlsm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xylfe.cn/Article/details/gthsppuuxb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xinyue.icu/Article/details/gtdnhxramu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cheryme.top/Article/details/gtoxmowmel.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nanxuanxn.top/Article/details/gtfxljwceb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhoulong.xyz/Article/details/gtmzfvxgxd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gaohongyu789.top/Article/details/gteivgwmjz.html

[I04] 正则替换
来源：http://dali.cheryme.top/Article/details/gtfybolfcc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sysykeji.top/Article/details/gtifplzxbw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gaohongyu789.top/Article/details/gttsqlvxsd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.dashuyun.cn/Article/details/gtyzthjzjp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gtbdhnzkuq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj20258.top/Article/details/gtdalxzypt.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daxiang520.top/Article/details/gtswxjqzjv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yvedp.cn/Article/details/gtpkjnstem.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gtxylxcdfn.html

[I05] 按正则拆分
来源：http://dali.zycfv.cn/Article/details/gtijfexvek.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinqigfzy.top/Article/details/gteosvevbl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.c1oappe.top/Article/details/gtzfccdkfs.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gtdlglpren.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gthgcuvdkp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtflesddcz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhiwuduotai.top/Article/details/gtcxpgghfs.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gtpwuppbsb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhixingplan.top/Article/details/gtcifvfjja.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.snrcjt.cn/Article/details/gtvjisqngj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gtadgljbky.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yueranfly.top/Article/details/gtadfwgmdp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigufen.top/Article/details/gtyeozlahn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nwbrower.top/Article/details/gtwlnysreq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gtukengawo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jlsjyb.cn/Article/details/gtgkzfirva.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hysaishi.cn/Article/details/gtiwzabrat.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.fengsongda.top/Article/details/gthmjocwya.html

[I07] 忽略大小写与多行模式
来源：http://dali.jianghu66.top/Article/details/gttzwvlofh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.kuanghao11.cn/Article/details/gtmelimvpj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.316326.xyz/Article/details/gtokmzpsqy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.snrcjt.cn/Article/details/gtvmphtmpn.html

TS:   /error/gim
来源：http://dali.cdnleiting.top/Article/details/gtazfecbhw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.svipenyu.cn/Article/details/gtxdegoehr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hnqzz.top/Article/details/gtpkfivyod.html

Ruby: s.scan(/error/i)
来源：http://dali.jqgfzy.top/Article/details/gtqsdtjflg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.svipenyu.cn/Article/details/gtivryqaky.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yonumen.top/Article/details/gtyeczewnr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.0kj1m.cn/Article/details/gtijlvhsje.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxinkj.top/Article/details/gtuvqlsnha.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.bjfxy.top/Article/details/gtsbjuakjh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hongshengwenyu.top/Article/details/gtcspjvqda.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gtjcbjkaca.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinqigufen.top/Article/details/gtkaixpuml.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnmpydmle.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhongyouzk.top/Article/details/gtuvzhvbvx.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtsmfurxcd.html

J. 日期与时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfkpvzqb.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtskpzwrkr.html

[J01] 获取当前时间
来源：http://dali.pycfn.com/Article/details/gtdyfxifum.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.9152youxi.cn/Article/details/gtovbggzis.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.chenlongwang.top/Article/details/gtthijoyil.html

JS:   new Date();  Date.now()
来源：http://dali.pengpengdd.cyou/Article/details/gticttobtd.html

TS:   new Date();  Date.now()
来源：http://dali.zhengqikj.top/Article/details/gtzuojbsko.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yongpay.top/Article/details/gtwowasnax.html

Go:   time.Now()
来源：http://dali.cdnleiting.top/Article/details/gtexnlzgwj.html

Ruby: Time.now
来源：http://dali.smart0.xyz/Article/details/gtifowxxiq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aibaodan.cn/Article/details/gtkugnzasd.html

[J02] 格式化输出
来源：http://dali.feifeiyinyue.top/Article/details/gtszlrtjvi.html


<!-- 参考信息 -->