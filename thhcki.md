代发 wailian999

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtdlgigtff.html

JS:   greet() { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtrofnutfy.html

TS:   greet(): string { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtxxgruzcg.html

Java: String greet() { return name; }
来源：http://dali.tanke756.top/Article/details/gttsfvcgmp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gtorixtppe.html

Ruby: def greet; @name; end
来源：http://dali.yangfankeji.com/Article/details/gtjyoanxjn.html

C#:   public string Greet() => Name;
来源：http://dali.316326.xyz/Article/details/gtoevryyev.html

[G05] 继承
来源：http://dali.gaohongyu789.top/Article/details/gtjouwleql.html

Py:   class Admin(User): pass
来源：http://dali.dashuyun.cn/Article/details/gtiajanjwd.html

PHP:  class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtxhxqvzix.html

JS:   class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtskbyakuu.html

TS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtazwqzkxr.html

Java: class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtizmdcbgk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.havefunace.top/Article/details/gthfbjenhn.html

Ruby: class Admin < User; end
来源：http://dali.smart0.xyz/Article/details/gtsbpbwyti.html

C#:   class Admin : User {}
来源：http://dali.sufxvd.cn/Article/details/gtkaykdpel.html

[G06] 重写方法
来源：http://dali.zdqjudy.top/Article/details/gtzdjtstpi.html

Py:   def greet(self): return "admin"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcmqsbxxa.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtzoxihnub.html

JS:   greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtnhorwcvz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gtumwgbyou.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwiedxrxi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ydzc1.top/Article/details/gtveirimxb.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtbfojcmdh.html

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpvqlmtcy.html

[G07] 调用父类方法
来源：http://dali.gotoacloud.top/Article/details/gtofdcczex.html

Py:   super().greet()
来源：http://dali.9152youxi.cn/Article/details/gtblstvoiy.html

PHP:  parent::greet();
来源：http://dali.yj202588.top/Article/details/gtuqitwoiq.html

JS:   super.greet();
来源：http://dali.redwolf501.top/Article/details/gtkjyyobub.html

TS:   super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gtfrzlmdsj.html

Java: super.greet();
来源：http://dali.ybcxt.top/Article/details/gtiljvtcqp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sysykeji.top/Article/details/gtxoaywdci.html

Ruby: super
来源：http://dali.birdmap.top/Article/details/gtqwzbaomh.html

C#:   base.Greet();
来源：http://dali.hfpthk.cn/Article/details/gtmhijbxsd.html

[G08] 静态方法与属性
来源：http://dali.yvedp.cn/Article/details/gtnebuiieo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ybcxt.top/Article/details/gtcpvfrrri.html

PHP:  public static function f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtrszjqgnm.html

JS:   static f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtqbwyqzni.html

TS:   static f(): void {}
来源：http://dali.havefunace.top/Article/details/gthslhgxun.html

Java: static void f() {}
来源：http://dali.cdnleiting.top/Article/details/gtuzhnpmdz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.smart0.xyz/Article/details/gtthxzhtfa.html

Ruby: def self.f; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkcxqhddk.html

C#:   public static void F() {}
来源：http://dali.yuanzhike.top/Article/details/gtbkhufjfc.html

[G09] 接口 / 抽象类
来源：http://dali.ydzc1.top/Article/details/gtbpkvlfwq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ppjwa.cn/Article/details/gtgigswfvi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yangfankeji.com/Article/details/gtlajcruio.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.dashuyun.cn/Article/details/gtuvzlclmz.html

TS:   interface Shape { area(): number; }
来源：http://dali.daxiang520.top/Article/details/gtdkbcavsc.html

Java: interface Shape { double area(); }
来源：http://dali.hnqzz.top/Article/details/gtormhlgvs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.aibaodan.cn/Article/details/gtzaslhplv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.meibo888.top/Article/details/gtbtlmvejy.html

C#:   interface IShape { double Area(); }
来源：http://dali.cucudq.cn/Article/details/gtutljxwft.html

[G10] 访问控制
来源：http://dali.sysykeji.top/Article/details/gtqjzsfugx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yanxiufei.cn/Article/details/gtuamhxyzq.html

PHP:  public / protected / private
来源：http://dali.ydzc1.top/Article/details/gtcqwjhgpq.html

JS:   #private 字段；其余公开
来源：http://dali.iojbl.cn/Article/details/gtzifwqcnh.html

TS:   public / protected / private
来源：http://dali.aizwys.cn/Article/details/gtlabhadfe.html

Java: public / protected / private / 默认包级
来源：http://dali.mhx1999.top/Article/details/gtuslempmr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ppjwa.cn/Article/details/gtcexskkfs.html

Ruby: public / protected / private
来源：http://dali.birdmap.top/Article/details/gtkijyonwy.html

C#:   public / protected / private / internal
来源：http://dali.yj20258888.top/Article/details/gtxohkrbgg.html

[G11] getter / setter
来源：http://dali.yj20258888.top/Article/details/gtwgrfrdvv.html

Py:   @property 与 @x.setter
来源：http://dali.zycfv.cn/Article/details/gtgyevakow.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtzkyehrfc.html

JS:   get name() { return this._name; }
来源：http://dali.dashuyun.cn/Article/details/gthyafgfiy.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtjutxmjua.html

Java: public String getName() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gthqiujqex.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gtpmvltlfd.html

Ruby: attr_accessor :name
来源：http://dali.9152youxi.cn/Article/details/gtzxylldux.html

C#:   public string Name { get; set; }
来源：http://dali.hammf.cn/Article/details/gtzpksktxi.html

[G12] 对象转字符串
来源：http://dali.jlsjyb.cn/Article/details/gtzbeduhmt.html

Py:   def __str__(self): return self.name
来源：http://dali.hfpthk.cn/Article/details/gtatvbuyhy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtemytagll.html

JS:   toString() { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtshjcdliu.html

TS:   toString(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtvgdfojev.html

Java: @Override public String toString() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtzrsdvyxw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gthtschhzp.html

Ruby: def to_s; @name; end
来源：http://dali.zhiwuduotai.top/Article/details/gtenwbgtrn.html

C#:   public override string ToString() => Name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttuwpankt.html

[G13] 判断对象类型
来源：http://dali.yonumen.top/Article/details/gtesklpqla.html

Py:   isinstance(u, User)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdkecokl.html

PHP:  $u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtbrluzhgl.html

JS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gtdgbljvae.html

TS:   u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gtoamqnrld.html

Java: u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtsxaoehfb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.0kj1m.cn/Article/details/gteqghsddg.html

Ruby: u.is_a?(User)
来源：http://dali.andypj.xyz/Article/details/gthehxzsrz.html

C#:   u is User
来源：http://dali.fengsongda.top/Article/details/gttuqcpjyn.html

[G14] 数据类 / record
来源：http://dali.nanxinkj.top/Article/details/gtofmhtylt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.bjfxy.top/Article/details/gtbtxfylhl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.andypj.xyz/Article/details/gtysaimflj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.dashuyun.cn/Article/details/gtomarbdwx.html

TS:   type User = { name: string; age: number };
来源：http://dali.dashuyun.cn/Article/details/gtkzshlgix.html

Java: record User(String name, int age) {}
来源：http://dali.zycfv.cn/Article/details/gtmhwtqure.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cdnleiting.top/Article/details/gthjrywgnj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj20258888.top/Article/details/gttmftkhgt.html

C#:   record User(string Name, int Age);
来源：http://dali.xylfe.cn/Article/details/gtofoubvfo.html

[G15] 枚举
来源：http://dali.haohaochexian.top/Article/details/gtgsgaaatf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.birdmap.top/Article/details/gtqnbuaksf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuanzx.com/Article/details/gtdujvjgay.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ppjwa.cn/Article/details/gtfiqrqnss.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xylfe.cn/Article/details/gtgsrorkda.html

Java: enum Color { RED, GREEN }
来源：http://dali.yvedp.cn/Article/details/gtovybdbwe.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xuetiantiany.cn/Article/details/gtjxqxmqka.html

Ruby: Color = %i[red green].freeze
来源：http://dali.iojbl.cn/Article/details/gtzfwikqbb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtbvscunct.html

[G16] 对象转数组 / 字典
来源：http://dali.iojbl.cn/Article/details/gtqgvhgtfq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxuanxn.top/Article/details/gtbblxduji.html

PHP:  get_object_vars($obj);
来源：http://dali.ydzc1.top/Article/details/gtrixueuhz.html

JS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbaxrjmzj.html

TS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjpsguyr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.vqdsnc.cn/Article/details/gtutyrfypj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cdnleiting.top/Article/details/gtdpmjvprl.html

Ruby: obj.instance_variables
来源：http://dali.zdqjudy.top/Article/details/gtteehjcdp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gthswlapik.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtocisndxj.html

H. 异常与错误处理
来源：http://dali.yuxming.cn/Article/details/gtrucvclah.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnwelfucz.html

[H01] try / catch 基础
来源：http://dali.zdqjudy.top/Article/details/gtnnloyenx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tian-w.cn/Article/details/gtqculrwtx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ivvv.top/Article/details/gttegxedyv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gtcqeczzrr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gtycnizbtd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jlsjyb.cn/Article/details/gtktzuxneq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvjpritvq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxinkj.top/Article/details/gtfbcatxju.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hammf.cn/Article/details/gttqeyhkma.html

[H02] finally / ensure 收尾
来源：http://dali.smart0.xyz/Article/details/gtqbdtraim.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtautrpxzp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnuaetiro.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtnfllbfpk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtgtmqbrwb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtixpvewvc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.snrcjt.cn/Article/details/gthdxydhsp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.pycfn.com/Article/details/gtscngzjpb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtupaygnnl.html

[H03] 主动抛出异常
来源：http://dali.jinqigfzy.top/Article/details/gtrcqvfigm.html

Py:   raise ValueError("错误信息")
来源：http://dali.wangshuangyany.cn/Article/details/gtxfybklyr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtsgtfzced.html

JS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtcligxdbq.html

TS:   throw new Error("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gttqmevvcx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtmxdhluee.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwcrmdyld.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenjidiqi.icu/Article/details/gtonycxkam.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtlbssevxv.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gtpwofdiwa.html

Py:   class MyError(Exception): pass
来源：http://dali.haohaochexian.top/Article/details/gtmsovsxlq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gteqgbmvxt.html

JS:   class MyError extends Error {}
来源：http://dali.yangfankeji.com/Article/details/gtqpvyywws.html

TS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gtiaanfcnu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tianlin.xyz/Article/details/gtrxebuwsy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhixingplan.top/Article/details/gthnqwstts.html

Ruby: class MyError < StandardError; end
来源：http://dali.vqdsnc.cn/Article/details/gttyomnycp.html

C#:   class MyException : Exception {}
来源：http://dali.yuanzhike.top/Article/details/gtrqtwsnii.html

[H05] 捕获特定类型
来源：http://dali.ybcxt.top/Article/details/gtsrooysgd.html

Py:   except ValueError as e:
来源：http://dali.sysykeji.top/Article/details/gtaeeoxieg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.havefunace.top/Article/details/gtpqpmwile.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hnxiangtu.top/Article/details/gtancfcpva.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ivvv.top/Article/details/gtqwukizst.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtgbakrgua.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.quarkkingdee.top/Article/details/gtjvoldjmo.html

Ruby: rescue ArgumentError => e
来源：http://dali.daxiang520.top/Article/details/gtlvktccon.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gteenmllcn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cucudq.cn/Article/details/gtncjmnlbp.html

Py:   value = d.get("k") or default
来源：http://dali.ivvv.top/Article/details/gtgimzrvev.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jianghu66.top/Article/details/gtfrphtyuf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258888.top/Article/details/gtfupfgwxs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tianlin.xyz/Article/details/gtofdaalcj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenlongwang.top/Article/details/gtnsrenlci.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgufenzy.top/Article/details/gtlhewzulm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenjidiqi.icu/Article/details/gtmdxttkvh.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnxiangtu.top/Article/details/gtbvbgmpaz.html

[H07] 断言
来源：http://dali.smart0.xyz/Article/details/gtigsqnrmz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aibaodan.cn/Article/details/gtlztxckiw.html

PHP:  assert($x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtmnuknfpb.html

JS:   console.assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gtyhnoajkw.html

TS:   console.assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gtkwbyhhgd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jiagoushi.top/Article/details/gtdpwaqush.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhongyouzk.top/Article/details/gtejjxugpu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.quarkkingdee.top/Article/details/gtoymvjlxi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtreqsteeo.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwcrzjzez.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cheryme.top/Article/details/gtaufrioqx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.daria6918.cn/Article/details/gtadoolbwq.html

JS:   e.message;  e.stack
来源：http://dali.smart0.xyz/Article/details/gtwipibwfq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jyoumei.cn/Article/details/gtwirbznnz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.fzhhl.top/Article/details/gtyqroaapa.html

Go:   err.Error()
来源：http://dali.pycfn.com/Article/details/gtfgnezdmi.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhiwuduotai.top/Article/details/gthkvrwzub.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhengqikj.top/Article/details/gtioiqjsct.html

[H09] 带错误码的异常
来源：http://dali.guowangkeji.top/Article/details/gtthjjtgzp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shanyushiyangkeji.top/Article/details/gtygbdzjyx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.aizwys.cn/Article/details/gttrbxipxh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zycfv.cn/Article/details/gtyzoxcvyc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ydzc1.top/Article/details/gtdhichuuk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xylfe.cn/Article/details/gtzanhrung.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ehwqpu.com/Article/details/gtezjpdehy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xylfe.cn/Article/details/gtmbbanyqv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nwbrower.top/Article/details/gtqgrrikyc.html

[H10] 资源自动释放
来源：http://dali.cheryme.top/Article/details/gtbdklmqaw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daxiang520.top/Article/details/gtryergflo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yuxming.cn/Article/details/gtrynyazth.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gtdxsuybcb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aizwys.cn/Article/details/gtujktccvt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.bjfxy.top/Article/details/gtwfhnxbnh.html

Go:   defer f.Close()
来源：http://dali.c1oappe.top/Article/details/gtqmhekvni.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cashguo.top/Article/details/gtizobqxcy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtgudbjepw.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtizyrygtb.html

I. 正则表达式
来源：http://dali.daria6918.cn/Article/details/gttrhxbgeo.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gttmgfhmad.html

[I01] 判断是否匹配
来源：http://dali.bjfxy.top/Article/details/gtwjyvyaab.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gtwajolmwy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.dashuyun.cn/Article/details/gtymhyoqvc.html

JS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gtmiejjoks.html

TS:   /\d+/.test(s)
来源：http://dali.cheryme.top/Article/details/gtzsuhvmor.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenjidiqi.icu/Article/details/gthmxcohks.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.mhx1999.top/Article/details/gtkxmdyznp.html

Ruby: s.match?(/\d+/)
来源：http://dali.dianchejie.cn/Article/details/gtvxrclrhs.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangdashe.top/Article/details/gtcxqqcynr.html

[I02] 提取所有匹配
来源：http://dali.hfpthk.cn/Article/details/gtlyeojyrx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zdqjudy.top/Article/details/gtqnujcjnv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.guannengcc.top/Article/details/gtccogjagp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ydzc1.top/Article/details/gtbfaxthpk.html

TS:   s.match(/\d+/g)
来源：http://dali.yanxiufei.cn/Article/details/gtzlisnpwf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nwbrower.top/Article/details/gthccioybo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yuxming.cn/Article/details/gtwmmrrqxd.html

Ruby: s.scan(/\d+/)
来源：http://dali.dashuyun.cn/Article/details/gtvjsabbmy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.havefunace.top/Article/details/gtvakpnhtp.html

[I03] 提取捕获分组
来源：http://dali.dashuyun.cn/Article/details/gtnlfcaatt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.wangdashe.top/Article/details/gtjrjczycp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnxiangtu.top/Article/details/gtigmveukw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.andypj.xyz/Article/details/gtratsgwrk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jiagoushi.top/Article/details/gtmtgrwtgv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ehwqpu.com/Article/details/gttbmfqbjq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinqigfzy.top/Article/details/gtqxesvdir.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sysykeji.top/Article/details/gtbcgupsmz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.svipenyu.cn/Article/details/gtdjusyjde.html

[I04] 正则替换
来源：http://dali.shzxlz.cn/Article/details/gtmxwawsdv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zycfv.cn/Article/details/gtjsysunsv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hywenlv.cn/Article/details/gtyszazdkd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gtnzwfsgty.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.pycfn.com/Article/details/gtvnjorlso.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtfpqnvmao.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtsggimlok.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtapfdildj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yuxming.cn/Article/details/gtgrxjnjek.html

[I05] 按正则拆分
来源：http://dali.hysaishi.cn/Article/details/gtceygspkb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ydzc1.top/Article/details/gtsiorctpr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtaabzavyy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gttprnbpvm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteuddyban.html

Java: s.split("\\s*,\\s*")
来源：http://dali.wangshuangyany.cn/Article/details/gtaubbkeoo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gtyxwepvtc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gtnzrzvjjk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhiwuduotai.top/Article/details/gtzytqjuua.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pengpengdd.cyou/Article/details/gtikjvytvn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gtztgpitjh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gtjjfzsogx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hywenlv.cn/Article/details/gthgwzfnyj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jlsjyb.cn/Article/details/gthpauonst.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gtjvcayeoc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.redwolf501.top/Article/details/gtuycgrptl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nanxinkj.top/Article/details/gtcnimrrxy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gtbwrftlao.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinghuilouyu.cn/Article/details/gtnpvesmws.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhixingplan.top/Article/details/gtwkgnngll.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.wangshuangyany.cn/Article/details/gttgvkglbe.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.c1oappe.top/Article/details/gtggdevvsw.html

TS:   /error/gim
来源：http://dali.jyoumei.cn/Article/details/gtwgvjiocg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.snrcjt.cn/Article/details/gtscjovycu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yueranfly.top/Article/details/gtukfjvmxt.html

Ruby: s.scan(/error/i)
来源：http://dali.zhoulong.xyz/Article/details/gtgszvsfqc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.fengsongda.top/Article/details/gtggwgpznw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtjlhaucka.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinqigufen.top/Article/details/gtvfzxfbbx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xinyue.icu/Article/details/gtgneybtph.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.mhx1999.top/Article/details/gtgaiyjjxg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yonumen.top/Article/details/gtkbxffdvh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.aizwys.cn/Article/details/gtdrchzvsx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jianghu66.top/Article/details/gtzvvgldwr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.havefunace.top/Article/details/gtdqgebvlz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjqbvejc.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtviifyiqs.html

J. 日期与时间
来源：http://dali.wangshuangyany.cn/Article/details/gtgxgwzpsr.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtycjicdnh.html

[J01] 获取当前时间
来源：http://dali.xuetiantiany.cn/Article/details/gtvfyxxdtv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.wangdashe.top/Article/details/gtloxfszpc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhixingplan.top/Article/details/gtpuiyrvrb.html

JS:   new Date();  Date.now()
来源：http://dali.quarkkingdee.top/Article/details/gtcdpftyvu.html

TS:   new Date();  Date.now()
来源：http://dali.hnqzz.top/Article/details/gtybtkzfnr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.redwolf501.top/Article/details/gtasxgsjyr.html

Go:   time.Now()
来源：http://dali.pengpengdd.cyou/Article/details/gtkcbydjnc.html

Ruby: Time.now
来源：http://dali.svipenyu.cn/Article/details/gtwcvhksau.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nanxinkj.top/Article/details/gtddpgkzpn.html

[J02] 格式化输出
来源：http://dali.aizwys.cn/Article/details/gtqzimienl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gtmejrzkmh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.daxiang520.top/Article/details/gtjhngicqw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.dianchejie.cn/Article/details/gtgxvohkfx.html

TS:   d.toISOString()
来源：http://dali.pycfn.com/Article/details/gtchyencxc.html


<!-- 参考信息 -->