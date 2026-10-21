代发 wailian999

Ruby: @name = "x"
来源：http://dali.snrcjt.cn/Article/details/gtqmttwlup.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yonumen.top/Article/details/gtegtuleie.html

[G04] 定义方法
来源：http://dali.feifeiyinyue.top/Article/details/gtajhjnnpd.html

Py:   def greet(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gtlhqsyxah.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gtndqyxbse.html

JS:   greet() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtpnohlvjg.html

TS:   greet(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtzzgycipa.html

Java: String greet() { return name; }
来源：http://dali.xuanzx.com/Article/details/gtwdfzwzil.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtepwmtaww.html

Ruby: def greet; @name; end
来源：http://dali.yj20258.top/Article/details/gtctfpobkq.html

C#:   public string Greet() => Name;
来源：http://dali.dashuyun.cn/Article/details/gtubylndno.html

[G05] 继承
来源：http://dali.sysykeji.top/Article/details/gtjaeuztko.html

Py:   class Admin(User): pass
来源：http://dali.shzxlz.cn/Article/details/gtzhgntsyj.html

PHP:  class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtllfvmbno.html

JS:   class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gthxsnszam.html

TS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtfcwczxvm.html

Java: class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gttseuworq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgfzy.top/Article/details/gtxrvnhtgw.html

Ruby: class Admin < User; end
来源：http://dali.shangyingyoupin.top/Article/details/gtalgfvfnq.html

C#:   class Admin : User {}
来源：http://dali.fengsongda.top/Article/details/gtbndfvqmi.html

[G06] 重写方法
来源：http://dali.jqgufenzy.top/Article/details/gtcmgfpfct.html

Py:   def greet(self): return "admin"
来源：http://dali.zhoulong.xyz/Article/details/gthvimodra.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtkeifxybz.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtpbzdccdb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtfoztwlps.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtbasbzbdw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.316326.xyz/Article/details/gtvhcxghqw.html

Ruby: def greet; "admin"; end
来源：http://dali.xuetiantiany.cn/Article/details/gtxymloyop.html

C#:   public override string Greet() => "admin";
来源：http://dali.mhx1999.top/Article/details/gtoielhzom.html

[G07] 调用父类方法
来源：http://dali.zdqjudy.top/Article/details/gtbslgiglf.html

Py:   super().greet()
来源：http://dali.hammf.cn/Article/details/gtuzsphukp.html

PHP:  parent::greet();
来源：http://dali.hysaishi.cn/Article/details/gtsbgrwaol.html

JS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtcmakzanj.html

TS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gtpiqktoap.html

Java: super.greet();
来源：http://dali.svipenyu.cn/Article/details/gtbtqpahxx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhoulong.xyz/Article/details/gtnbzebzhw.html

Ruby: super
来源：http://dali.jlsjyb.cn/Article/details/gtzcxyfnml.html

C#:   base.Greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtonshixog.html

[G08] 静态方法与属性
来源：http://dali.hysaishi.cn/Article/details/gtsrbnsynk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.iojbl.cn/Article/details/gtuxgixnsw.html

PHP:  public static function f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxkoqdem.html

JS:   static f() {}
来源：http://dali.xylfe.cn/Article/details/gtdapaejnm.html

TS:   static f(): void {}
来源：http://dali.jlsjyb.cn/Article/details/gtirhavajt.html

Java: static void f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gteeltemky.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shuidangran.top/Article/details/gtgrzbyxmg.html

Ruby: def self.f; end
来源：http://dali.zdqjudy.top/Article/details/gtxlxylvtp.html

C#:   public static void F() {}
来源：http://dali.316326.xyz/Article/details/gthhxeevwz.html

[G09] 接口 / 抽象类
来源：http://dali.ydzc1.top/Article/details/gtfdlvnfgy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sxryk.cn/Article/details/gtyvvjzyje.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hywenlv.cn/Article/details/gtztsztfqv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.9152youxi.cn/Article/details/gtnogbspji.html

TS:   interface Shape { area(): number; }
来源：http://dali.xziqi.cn/Article/details/gtpxwvvqkd.html

Java: interface Shape { double area(); }
来源：http://dali.sweek.top/Article/details/gtijhjzmoo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jiagoushi.top/Article/details/gtmwkiswym.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jqgfzy.top/Article/details/gtuufkxnbe.html

C#:   interface IShape { double Area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtzcyfjhqy.html

[G10] 访问控制
来源：http://dali.gaohongyu789.top/Article/details/gtwteiegit.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.pycfn.com/Article/details/gtcktizafn.html

PHP:  public / protected / private
来源：http://dali.meibo888.top/Article/details/gtxcjbklbb.html

JS:   #private 字段；其余公开
来源：http://dali.shanyushiyangtech.top/Article/details/gtjcwrpxbv.html

TS:   public / protected / private
来源：http://dali.yueranfly.top/Article/details/gtigonbqle.html

Java: public / protected / private / 默认包级
来源：http://dali.cqqwz.cn/Article/details/gtpsjcamnd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.bjfxy.top/Article/details/gturjxeodd.html

Ruby: public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gtssrlogbt.html

C#:   public / protected / private / internal
来源：http://dali.c1oappe.top/Article/details/gtpnpfiohe.html

[G11] getter / setter
来源：http://dali.jinghuilouyu.cn/Article/details/gttiptylva.html

Py:   @property 与 @x.setter
来源：http://dali.gaohongyu789.top/Article/details/gtmlopwpcz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtjskqyvpo.html

JS:   get name() { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gtsizmxplz.html

TS:   get name(): string { return this._name; }
来源：http://dali.ydzc1.top/Article/details/gtotahcdsa.html

Java: public String getName() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtobugmfdj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gthopkoevn.html

Ruby: attr_accessor :name
来源：http://dali.gotoacloud.top/Article/details/gtfrfcnpld.html

C#:   public string Name { get; set; }
来源：http://dali.tian-w.cn/Article/details/gthahaorfi.html

[G12] 对象转字符串
来源：http://dali.redwolf501.top/Article/details/gtlxmwpaxs.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258.top/Article/details/gtttdojcnd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtfizjcari.html

JS:   toString() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gtbeuvuals.html

TS:   toString(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtmokfzfky.html

Java: @Override public String toString() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtkfjguzqo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gtccqignjy.html

Ruby: def to_s; @name; end
来源：http://dali.vqdsnc.cn/Article/details/gtqgdbzznj.html

C#:   public override string ToString() => Name;
来源：http://dali.zhiwuduotai.top/Article/details/gtlqgfafnf.html

[G13] 判断对象类型
来源：http://dali.wangshuangyany.cn/Article/details/gtbmnpnhsm.html

Py:   isinstance(u, User)
来源：http://dali.sxryk.cn/Article/details/gtefrunmqi.html

PHP:  $u instanceof User
来源：http://dali.pycfn.com/Article/details/gtuwrescsj.html

JS:   u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtcjnaeckt.html

TS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtbbjrvtnb.html

Java: u instanceof User
来源：http://dali.wangdashe.top/Article/details/gticvgqdus.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ybcxt.top/Article/details/gtjkzmtkdm.html

Ruby: u.is_a?(User)
来源：http://dali.pycfn.com/Article/details/gtfkiztgpj.html

C#:   u is User
来源：http://dali.jyoumei.cn/Article/details/gtnpnokrnd.html

[G14] 数据类 / record
来源：http://dali.yongpay.top/Article/details/gtlechbein.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.redwolf501.top/Article/details/gtohsmokjn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jyoumei.cn/Article/details/gtrrgubfyx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hysaishi.cn/Article/details/gthyxqbhck.html

TS:   type User = { name: string; age: number };
来源：http://dali.shangyingyoupin.top/Article/details/gtkwsyklcb.html

Java: record User(String name, int age) {}
来源：http://dali.nwbrower.top/Article/details/gtjpunrpys.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenlongwang.top/Article/details/gtfopeguqx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cucudq.cn/Article/details/gtitmmhuls.html

C#:   record User(string Name, int Age);
来源：http://dali.aibaodan.cn/Article/details/gtucmkdybd.html

[G15] 枚举
来源：http://dali.cqqwz.cn/Article/details/gtrhdwniyh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenzaomai.com/Article/details/gtcvonymyw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sweek.top/Article/details/gtyqdvkxnd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hywenlv.cn/Article/details/gtgzjvdxse.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsexsvhev.html

Java: enum Color { RED, GREEN }
来源：http://dali.hfpthk.cn/Article/details/gtchlfuuup.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xinyue.icu/Article/details/gtdfijrlyz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.pengpengdd.cyou/Article/details/gtsogvanpp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.andypj.xyz/Article/details/gtdeqengky.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangtech.top/Article/details/gtnphbhapw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.feifeiyinyue.top/Article/details/gtfxbkbeew.html

PHP:  get_object_vars($obj);
来源：http://dali.dashuyun.cn/Article/details/gtagadmnsf.html

JS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gtskiogdil.html

TS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwgbfeit.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gzhubu.top/Article/details/gthaxudwnm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbsdghjja.html

Ruby: obj.instance_variables
来源：http://dali.hammf.cn/Article/details/gtzhjtboeu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cheryme.top/Article/details/gtbajonteu.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtrpyfixhc.html

H. 异常与错误处理
来源：http://dali.gaohongyu789.top/Article/details/gtirugtfid.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtneyvmvif.html

[H01] try / catch 基础
来源：http://dali.nanxuanxn.top/Article/details/gthakojifj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.havefunace.top/Article/details/gtjfanaioz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tian-w.cn/Article/details/gtqgcfarxu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gtapxmydbs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hammf.cn/Article/details/gtpnhtvkcs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yongpay.top/Article/details/gtaiprrjjk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sufxvd.cn/Article/details/gttcdxvnjm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aibaodan.cn/Article/details/gtchaufuso.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.0kj1m.cn/Article/details/gtsylqwwaz.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfzqiykbs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hnqzz.top/Article/details/gtgaihvwmr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtkwvygiba.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtlpsssakk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtlrbtekwh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtvirixgrk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.aizwys.cn/Article/details/gtsjebwwpb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.mhx1999.top/Article/details/gtzlikpsax.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sweek.top/Article/details/gtfbjqsxpo.html

[H03] 主动抛出异常
来源：http://dali.jlsjyb.cn/Article/details/gtbuiswjhk.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnxiangtu.top/Article/details/gtadafypss.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtcnyctegn.html

JS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtsitoyrtk.html

TS:   throw new Error("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gttfpjfdil.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkkukketw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gzhubu.top/Article/details/gtwwicesza.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzdawbagd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gticqugmyz.html

[H04] 自定义异常类型
来源：http://dali.hongshengwenyu.top/Article/details/gtklvitskb.html

Py:   class MyError(Exception): pass
来源：http://dali.aizwys.cn/Article/details/gtkthfjvod.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gtqvlsihun.html

JS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gtnzdkjkbr.html

TS:   class MyError extends Error {}
来源：http://dali.havefunace.top/Article/details/gttustqmui.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xylfe.cn/Article/details/gtuqjmivnv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.c1oappe.top/Article/details/gtwowcszlc.html

Ruby: class MyError < StandardError; end
来源：http://dali.cdnleiting.top/Article/details/gttktpzipe.html

C#:   class MyException : Exception {}
来源：http://dali.smart0.xyz/Article/details/gtpiypttbg.html

[H05] 捕获特定类型
来源：http://dali.316326.xyz/Article/details/gtvfvifhwv.html

Py:   except ValueError as e:
来源：http://dali.sxryk.cn/Article/details/gteptlihnu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xinyue.icu/Article/details/gtcedxdzxz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nanxuanxn.top/Article/details/gtsmbdbhbk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.pycfn.com/Article/details/gtcurxmmcg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tian-w.cn/Article/details/gtkztacipa.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yueranfly.top/Article/details/gtxhjktxmb.html

Ruby: rescue ArgumentError => e
来源：http://dali.birdmap.top/Article/details/gtslbtwbel.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yonumen.top/Article/details/gtgqsuhcwl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jianghu66.top/Article/details/gtniceclud.html

Py:   value = d.get("k") or default
来源：http://dali.yongpay.top/Article/details/gteurpnqxx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yuanzhike.top/Article/details/gtruuljmap.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmqjourr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstyfxbxo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xuetiantiany.cn/Article/details/gtajafadfn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtssrfmdhp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yanxiufei.cn/Article/details/gtcdflawky.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj20258.top/Article/details/gtxzqaoxiu.html

[H07] 断言
来源：http://dali.zycfv.cn/Article/details/gteqrahnvc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.fzhhl.top/Article/details/gteydkzqoc.html

PHP:  assert($x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtjlhvszkc.html

JS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtpotobfqf.html

TS:   console.assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gtsovbqpwg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.dashuyun.cn/Article/details/gtcysfsabh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yueranfly.top/Article/details/gtwryefxrn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.aizwys.cn/Article/details/gthszbojrb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtlguzkple.html

[H08] 获取错误信息与堆栈
来源：http://dali.tian-w.cn/Article/details/gtkgvywzwz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yueranfly.top/Article/details/gtafaiwhwt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj202588.top/Article/details/gtacyenyir.html

JS:   e.message;  e.stack
来源：http://dali.nwbrower.top/Article/details/gtljjdylly.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yuanzhike.top/Article/details/gtlrlsgirq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xuetiantiany.cn/Article/details/gtdaqzeeuo.html

Go:   err.Error()
来源：http://dali.wangdashe.top/Article/details/gtqktgajcb.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhengqikj.top/Article/details/gtdtywbuwx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuanzx.com/Article/details/gtkcrguloo.html

[H09] 带错误码的异常
来源：http://dali.mhx1999.top/Article/details/gtffpzoytb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.meibo888.top/Article/details/gtekpmnrxa.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinyuanbaomall.cn/Article/details/gteaxaqzvf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yongpay.top/Article/details/gtdohdinmp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xylfe.cn/Article/details/gtkodkcydf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.pycfn.com/Article/details/gthiuskcmt.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcixhxjfn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnqzz.top/Article/details/gtksyboeqo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hysaishi.cn/Article/details/gtwieikfyf.html

[H10] 资源自动释放
来源：http://dali.quarkkingdee.top/Article/details/gtioxiughl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.birdmap.top/Article/details/gthpxrvxoj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nwbrower.top/Article/details/gtdctztcmh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmhinplfu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aibaodan.cn/Article/details/gtjxuujbrn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.wangdashe.top/Article/details/gtepxxacfi.html

Go:   defer f.Close()
来源：http://dali.quarkkingdee.top/Article/details/gtdgihewwb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuanzhike.top/Article/details/gtiqzexpba.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtjxewprvs.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtaabxdfgc.html

I. 正则表达式
来源：http://dali.zhoulong.xyz/Article/details/gtfzuqidzi.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtdllqjeet.html

[I01] 判断是否匹配
来源：http://dali.mhx1999.top/Article/details/gtyrdzcpma.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jiagoushi.top/Article/details/gtsacnlxou.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gzhubu.top/Article/details/gtzzkhpzxz.html

JS:   /\d+/.test(s)
来源：http://dali.aibaodan.cn/Article/details/gtntnwahyd.html

TS:   /\d+/.test(s)
来源：http://dali.hysaishi.cn/Article/details/gtrhogrqnh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tian-w.cn/Article/details/gttddbbxme.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtjodjazfs.html

Ruby: s.match?(/\d+/)
来源：http://dali.wangshuangyany.cn/Article/details/gtcfuwwctk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258.top/Article/details/gtzgmxuhxt.html

[I02] 提取所有匹配
来源：http://dali.zhixingplan.top/Article/details/gtacqkuzay.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhiwuduotai.top/Article/details/gtztdoclhe.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shzxlz.cn/Article/details/gtkdkbddtr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258.top/Article/details/gtjbzcvlfr.html

TS:   s.match(/\d+/g)
来源：http://dali.sysykeji.top/Article/details/gtxjkrzlpv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.aibaodan.cn/Article/details/gtvxdbknoj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hnqzz.top/Article/details/gtyygnexcg.html

Ruby: s.scan(/\d+/)
来源：http://dali.gzhubu.top/Article/details/gtgfbvaklb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtbkyrhskk.html

[I03] 提取捕获分组
来源：http://dali.mhx1999.top/Article/details/gtkwxsjuzq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ydzc1.top/Article/details/gtpwieyjfn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.birdmap.top/Article/details/gtfwnlqqdy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqaporxaq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.aibaodan.cn/Article/details/gttaxwayhb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gotoacloud.top/Article/details/gtmzipdomy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cucudq.cn/Article/details/gtipilmbzq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hnqzz.top/Article/details/gtgwmxsqrk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangtech.top/Article/details/gtbhfmrtoz.html

[I04] 正则替换
来源：http://dali.zycfv.cn/Article/details/gtdgwiublc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shzxlz.cn/Article/details/gtvxayvrnl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jyoumei.cn/Article/details/gtxvqjtgbu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yongpay.top/Article/details/gtrwbeutxy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shuidangran.top/Article/details/gtlcjzrnkh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jqgufenzy.top/Article/details/gtmzwxarcw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sysykeji.top/Article/details/gtchdmzgmz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.dianchejie.cn/Article/details/gtftbyfpvr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtsdmdmcce.html

[I05] 按正则拆分
来源：http://dali.zhiwuduotai.top/Article/details/gtzbdasujh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zycfv.cn/Article/details/gtyvotletp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtibteioky.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gtgvhkbykt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gtkugfdzln.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cqqwz.cn/Article/details/gtwyybubkt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.wangdashe.top/Article/details/gtoijfkdyz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gtivbxslhl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.dianchejie.cn/Article/details/gtsuhgkipt.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jianghu66.top/Article/details/gtgdhovczj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gtspgcvmpz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ydzc1.top/Article/details/gtvtzpljcz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.vqdsnc.cn/Article/details/gtlwkqeunb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hfpthk.cn/Article/details/gtxxyxaypu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.havefunace.top/Article/details/gtzsuqqieu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.9152youxi.cn/Article/details/gtfhnmsslu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhiwuduotai.top/Article/details/gtgdihawfd.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gtdqbcaito.html

[I07] 忽略大小写与多行模式
来源：http://dali.nanxuanxn.top/Article/details/gtqgvscxto.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shangyingyoupin.top/Article/details/gtprbalogf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gtuqhftclq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.bjfxy.top/Article/details/gtqcmiseaj.html

TS:   /error/gim
来源：http://dali.hnqzz.top/Article/details/gtkeamvotc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.dianchejie.cn/Article/details/gtpntcwdre.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ybcxt.top/Article/details/gtowhohfjt.html

Ruby: s.scan(/error/i)
来源：http://dali.wangshuangyany.cn/Article/details/gtgobwcmxl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.dianchejie.cn/Article/details/gtdwphiabp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cheryme.top/Article/details/gtlskbftgz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenzaomai.com/Article/details/gtvhfahzif.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sysykeji.top/Article/details/gtzrmtvvnw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtarjymoyd.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gtorxvhmco.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xylfe.cn/Article/details/gtnnwbdsed.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtttlmnlte.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yangfankeji.com/Article/details/gtmlrykdih.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hammf.cn/Article/details/gtklcmlilr.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtjrrcqdfp.html

J. 日期与时间
来源：http://dali.pycfn.com/Article/details/gtpvobwauk.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtlcizjwfs.html

[J01] 获取当前时间
来源：http://dali.guannengcc.top/Article/details/gtkusamhip.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zycfv.cn/Article/details/gtkhmziors.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shanyushiyangtech.top/Article/details/gtxkxwlsjo.html

JS:   new Date();  Date.now()
来源：http://dali.chenjidiqi.icu/Article/details/gtakioqnxa.html

TS:   new Date();  Date.now()
来源：http://dali.sysykeji.top/Article/details/gtxocbrlux.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gaohongyu789.top/Article/details/gtjrxovscm.html

Go:   time.Now()
来源：http://dali.andypj.xyz/Article/details/gttfeemfhg.html

Ruby: Time.now
来源：http://dali.ybcxt.top/Article/details/gtywswuovf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cdnleiting.top/Article/details/gtzcquxipy.html

[J02] 格式化输出
来源：http://dali.daria6918.cn/Article/details/gtnuqdbbue.html


<!-- 参考信息 -->