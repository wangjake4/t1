代发 wailian999

Ruby: @name = "x"
来源：http://dali.ivvv.top/Article/details/gtbvilhdil.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtdwyqxzae.html

[G04] 定义方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnbmnzfa.html

Py:   def greet(self): return self.name
来源：http://dali.cucudq.cn/Article/details/gtacqityhz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gtrsgelgiz.html

JS:   greet() { return this.name; }
来源：http://dali.316326.xyz/Article/details/gtgobheilt.html

TS:   greet(): string { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtudpdhszu.html

Java: String greet() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtfchwbkdr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gtokexxkug.html

Ruby: def greet; @name; end
来源：http://dali.nwbrower.top/Article/details/gtenoeogrj.html

C#:   public string Greet() => Name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjzvbtiwj.html

[G05] 继承
来源：http://dali.ivvv.top/Article/details/gtqqkulclo.html

Py:   class Admin(User): pass
来源：http://dali.zdqjudy.top/Article/details/gtgncjpakl.html

PHP:  class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtkngdtrju.html

JS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gttmsfaokq.html

TS:   class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtldaevbxn.html

Java: class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gttuydhxwc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jlsjyb.cn/Article/details/gtwqpmhwtt.html

Ruby: class Admin < User; end
来源：http://dali.fengsongda.top/Article/details/gtqooevhkk.html

C#:   class Admin : User {}
来源：http://dali.aibaodan.cn/Article/details/gtmqyeumpp.html

[G06] 重写方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnvketdhh.html

Py:   def greet(self): return "admin"
来源：http://dali.bjfxy.top/Article/details/gtopydeoxk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtmneiwpmy.html

JS:   greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtlfllmqrj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtsqzpdrte.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtwvjudmuy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yueranfly.top/Article/details/gttnzsgsin.html

Ruby: def greet; "admin"; end
来源：http://dali.yj202588.top/Article/details/gtsgffzepf.html

C#:   public override string Greet() => "admin";
来源：http://dali.cdnleiting.top/Article/details/gtugpsmpts.html

[G07] 调用父类方法
来源：http://dali.iojbl.cn/Article/details/gtfuvnzeau.html

Py:   super().greet()
来源：http://dali.sufxvd.cn/Article/details/gtiwgaqiij.html

PHP:  parent::greet();
来源：http://dali.tianlin.xyz/Article/details/gtcjzmxgqv.html

JS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gtaiuddejg.html

TS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gtxjyaerhn.html

Java: super.greet();
来源：http://dali.fengsongda.top/Article/details/gtlezlcese.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cqqwz.cn/Article/details/gtnkidtosg.html

Ruby: super
来源：http://dali.c1oappe.top/Article/details/gtxnmrliyl.html

C#:   base.Greet();
来源：http://dali.tianlin.xyz/Article/details/gtvardaiwv.html

[G08] 静态方法与属性
来源：http://dali.cucudq.cn/Article/details/gtofuwylhw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.daria6918.cn/Article/details/gtfqugbwef.html

PHP:  public static function f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrxkvobl.html

JS:   static f() {}
来源：http://dali.jqgfzy.top/Article/details/gtwouibcgo.html

TS:   static f(): void {}
来源：http://dali.cheryme.top/Article/details/gtlgcnftnl.html

Java: static void f() {}
来源：http://dali.hnqzz.top/Article/details/gthltddoxw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.bjfxy.top/Article/details/gtmsztpnpu.html

Ruby: def self.f; end
来源：http://dali.zhixingplan.top/Article/details/gtjbewedql.html

C#:   public static void F() {}
来源：http://dali.gaohongyu789.top/Article/details/gtcilqhvbl.html

[G09] 接口 / 抽象类
来源：http://dali.hnqzz.top/Article/details/gtuzwxwbix.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daria6918.cn/Article/details/gteffzrmfv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cucudq.cn/Article/details/gtsmmfxyrb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yuanzhike.top/Article/details/gtjrlfypaq.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhongyouzk.top/Article/details/gtpgopbzdm.html

Java: interface Shape { double area(); }
来源：http://dali.zhengqikj.top/Article/details/gtihxnofxq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yangfankeji.com/Article/details/gtgupjwthe.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hammf.cn/Article/details/gtcjzsitkg.html

C#:   interface IShape { double Area(); }
来源：http://dali.gogol.net.cn/Article/details/gtmlbneetm.html

[G10] 访问控制
来源：http://dali.sxryk.cn/Article/details/gtmzynhzib.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jyoumei.cn/Article/details/gttugaikke.html

PHP:  public / protected / private
来源：http://dali.yongpay.top/Article/details/gtjtddrpcx.html

JS:   #private 字段；其余公开
来源：http://dali.zhoulong.xyz/Article/details/gtrzlgwoum.html

TS:   public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtzlxwhgwv.html

Java: public / protected / private / 默认包级
来源：http://dali.shangyingyoupin.top/Article/details/gtbcamjmet.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gotoacloud.top/Article/details/gtlbaabfna.html

Ruby: public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gtvacgwzbf.html

C#:   public / protected / private / internal
来源：http://dali.snrcjt.cn/Article/details/gtgsspcvta.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gtavxgsfyj.html

Py:   @property 与 @x.setter
来源：http://dali.meibo888.top/Article/details/gtjsqbkapo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gturhysfja.html

JS:   get name() { return this._name; }
来源：http://dali.jinqigfzy.top/Article/details/gthbpluzwd.html

TS:   get name(): string { return this._name; }
来源：http://dali.ehwqpu.com/Article/details/gtkiecbsqi.html

Java: public String getName() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gtpulblarm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gtdixrettj.html

Ruby: attr_accessor :name
来源：http://dali.gaohongyu789.top/Article/details/gttbplwars.html

C#:   public string Name { get; set; }
来源：http://dali.zycfv.cn/Article/details/gtrwbtmbbz.html

[G12] 对象转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtvhwvcvdt.html

Py:   def __str__(self): return self.name
来源：http://dali.daxiang520.top/Article/details/gtvnqcqkcl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gtvzldrdup.html

JS:   toString() { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gtlsjusgbh.html

TS:   toString(): string { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtmzepqyid.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj20258888.top/Article/details/gtglpmvgsi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtouwwetfi.html

Ruby: def to_s; @name; end
来源：http://dali.xziqi.cn/Article/details/gtwgbotknp.html

C#:   public override string ToString() => Name;
来源：http://dali.yvedp.cn/Article/details/gtuqmjvcdv.html

[G13] 判断对象类型
来源：http://dali.meibo888.top/Article/details/gtkefbsfdj.html

Py:   isinstance(u, User)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtauepjkqq.html

PHP:  $u instanceof User
来源：http://dali.ybcxt.top/Article/details/gtmoxinlbf.html

JS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtylqgmetu.html

TS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtynwzwqfv.html

Java: u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtsttxyxnl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hywenlv.cn/Article/details/gtwbrkyxji.html

Ruby: u.is_a?(User)
来源：http://dali.jqgfzy.top/Article/details/gtjucuudar.html

C#:   u is User
来源：http://dali.feifeiyinyue.top/Article/details/gthliivocq.html

[G14] 数据类 / record
来源：http://dali.shangyingyoupin.top/Article/details/gtvoxutbvs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xziqi.cn/Article/details/gtumlhaxmr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shanyushiyangkeji.top/Article/details/gteextedrg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guannengcc.top/Article/details/gthzlbklot.html

TS:   type User = { name: string; age: number };
来源：http://dali.pengpengdd.cyou/Article/details/gtaxsmehip.html

Java: record User(String name, int age) {}
来源：http://dali.zhongyouzk.top/Article/details/gtyjfumpng.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nanxinkj.top/Article/details/gtryyglkvd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ehwqpu.com/Article/details/gtlkckztil.html

C#:   record User(string Name, int Age);
来源：http://dali.meibo888.top/Article/details/gtlprnvbox.html

[G15] 枚举
来源：http://dali.hongshengwenyu.top/Article/details/gtnsniuxam.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.iojbl.cn/Article/details/gtovbvnlog.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.svipenyu.cn/Article/details/gtoozrtqkk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zdqjudy.top/Article/details/gtmosjcyov.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtooenscbz.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhengqikj.top/Article/details/gtwpunivqf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenjidiqi.icu/Article/details/gtmgpqvwtm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinqigfzy.top/Article/details/gtbmrlrlpw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtvicixgqm.html

[G16] 对象转数组 / 字典
来源：http://dali.yonumen.top/Article/details/gtwzjuyfgz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yueranfly.top/Article/details/gtqdehxycw.html

PHP:  get_object_vars($obj);
来源：http://dali.guannengcc.top/Article/details/gtntlturyb.html

JS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gtggxjniyj.html

TS:   Object.entries(obj)
来源：http://dali.c1oappe.top/Article/details/gtvxrbvkap.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.vqdsnc.cn/Article/details/gtffqkxwel.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gttctxdqfz.html

Ruby: obj.instance_variables
来源：http://dali.jqgfzy.top/Article/details/gteexudabv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj202588.top/Article/details/gtcefkglsq.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtqcezuuar.html

H. 异常与错误处理
来源：http://dali.yuxming.cn/Article/details/gtfwelfvpa.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtznluojah.html

[H01] try / catch 基础
来源：http://dali.hnqzz.top/Article/details/gtxffjrztl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jqgufenzy.top/Article/details/gtdnkxatdp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigufen.top/Article/details/gtznldhyzp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gtsftnctec.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gtwxvzqett.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.wangdashe.top/Article/details/gtpxyxpgrr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gotoacloud.top/Article/details/gtdbbfcygi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yuxming.cn/Article/details/gtxodlhwmd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnqzz.top/Article/details/gtrdljhmfx.html

[H02] finally / ensure 收尾
来源：http://dali.yongpay.top/Article/details/gtvcpkuyhc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xuetiantiany.cn/Article/details/gtydfjczxv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtahcztork.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtnvrofmyy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtodxyhchd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtqxqegjpk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhongyouzk.top/Article/details/gtpmwzvzet.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hywenlv.cn/Article/details/gtsbuxgkgu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtgyfjzznx.html

[H03] 主动抛出异常
来源：http://dali.ppjwa.cn/Article/details/gtvwtwkkuv.html

Py:   raise ValueError("错误信息")
来源：http://dali.svipenyu.cn/Article/details/gtogkvwhai.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtifpmarhq.html

JS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gttpmtduny.html

TS:   throw new Error("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtctopaekr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gtyixvwzxn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.redwolf501.top/Article/details/gtgnvgmibo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zdqjudy.top/Article/details/gtnjsqzqsv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtlljgyxvk.html

[H04] 自定义异常类型
来源：http://dali.hongshengwenyu.top/Article/details/gtvhsvvuiv.html

Py:   class MyError(Exception): pass
来源：http://dali.birdmap.top/Article/details/gtpxeehxnv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hywenlv.cn/Article/details/gtuumnqkuf.html

JS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gtlqezmmpn.html

TS:   class MyError extends Error {}
来源：http://dali.ybcxt.top/Article/details/gtiettpnjo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.pycfn.com/Article/details/gtqiilijjx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jlsjyb.cn/Article/details/gtxxtbfadd.html

Ruby: class MyError < StandardError; end
来源：http://dali.fzhhl.top/Article/details/gtcccbhjht.html

C#:   class MyException : Exception {}
来源：http://dali.tian-w.cn/Article/details/gttazqpadp.html

[H05] 捕获特定类型
来源：http://dali.jiagoushi.top/Article/details/gtumbanoth.html

Py:   except ValueError as e:
来源：http://dali.nanxinkj.top/Article/details/gtmhzmefjp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ehwqpu.com/Article/details/gtcdwljeip.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenlongwang.top/Article/details/gtwtaazzbt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gtxwykvycf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinqigufen.top/Article/details/gtrhqomxyw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gotoacloud.top/Article/details/gtggitjxgx.html

Ruby: rescue ArgumentError => e
来源：http://dali.wangdashe.top/Article/details/gtkgxyadcv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gthpjnpugo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nwbrower.top/Article/details/gtyphcsrhh.html

Py:   value = d.get("k") or default
来源：http://dali.tianlin.xyz/Article/details/gtanlhsxgv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gthzaguvve.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gtyerczzhg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenlongwang.top/Article/details/gtkjzrckan.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhiwuduotai.top/Article/details/gtrsfnrbgb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yonumen.top/Article/details/gtdhzbxhga.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ppjwa.cn/Article/details/gthedxjwgj.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gttlretmrd.html

[H07] 断言
来源：http://dali.tianlin.xyz/Article/details/gtlnvhkfrz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jyoumei.cn/Article/details/gtswfbsfnw.html

PHP:  assert($x > 0);
来源：http://dali.mhx1999.top/Article/details/gtjnwokzpm.html

JS:   console.assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gtveoqawlr.html

TS:   console.assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gtniyprllw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.9152youxi.cn/Article/details/gtmrqihebb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hongshengwenyu.top/Article/details/gtptywgdzr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yongpay.top/Article/details/gtpobcxqke.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gttjagdhgn.html

[H08] 获取错误信息与堆栈
来源：http://dali.ppjwa.cn/Article/details/gtfdbachor.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ppjwa.cn/Article/details/gtkxruirxv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.daxiang520.top/Article/details/gtduzkqqro.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangtech.top/Article/details/gtkgtemjen.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yonumen.top/Article/details/gtoexwomyo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.snrcjt.cn/Article/details/gtxzdolxsq.html

Go:   err.Error()
来源：http://dali.xuanzx.com/Article/details/gtnyrslqya.html

Ruby: e.message;  e.backtrace
来源：http://dali.zycfv.cn/Article/details/gtrmeioers.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cheryme.top/Article/details/gtemdsjfgd.html

[H09] 带错误码的异常
来源：http://dali.wangdashe.top/Article/details/gtlvjkolsj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuanzhike.top/Article/details/gttxtpzqiw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhoulong.xyz/Article/details/gtyattwgas.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cashguo.top/Article/details/gtwkaqpakl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj20258888.top/Article/details/gtrsddtmdm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sufxvd.cn/Article/details/gtzgddhnrq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.pengpengdd.cyou/Article/details/gtnlvqydux.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hywenlv.cn/Article/details/gtthlombot.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhixingplan.top/Article/details/gtpxuupufx.html

[H10] 资源自动释放
来源：http://dali.ybcxt.top/Article/details/gtjurycdjy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hfpthk.cn/Article/details/gtrpebrgwg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sysykeji.top/Article/details/gthplrzern.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gtvhixsodi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ybcxt.top/Article/details/gthbmmnyfi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yuanzhike.top/Article/details/gtoyrcgfkl.html

Go:   defer f.Close()
来源：http://dali.yj20258.top/Article/details/gtdcohlvnm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ppjwa.cn/Article/details/gtrozvffdw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtwqefomah.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtengupxsf.html

I. 正则表达式
来源：http://dali.jqgfzy.top/Article/details/gtamvtvaat.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtvfbtabmc.html

[I01] 判断是否匹配
来源：http://dali.vqdsnc.cn/Article/details/gtgrfvshrp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jianghu66.top/Article/details/gtracozrou.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtzbqauprx.html

JS:   /\d+/.test(s)
来源：http://dali.hammf.cn/Article/details/gtcvhrtpia.html

TS:   /\d+/.test(s)
来源：http://dali.ppjwa.cn/Article/details/gtutclhyjo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ydzc1.top/Article/details/gtuuwaodcl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtieebfubu.html

Ruby: s.match?(/\d+/)
来源：http://dali.shuidangran.top/Article/details/gtyjziydnm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuanzhike.top/Article/details/gtphoskcmf.html

[I02] 提取所有匹配
来源：http://dali.jiagoushi.top/Article/details/gtshpafudc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.aibaodan.cn/Article/details/gtyxtsoasj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.haohaochexian.top/Article/details/gtfuckajqt.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cucudq.cn/Article/details/gtieousnqj.html

TS:   s.match(/\d+/g)
来源：http://dali.cheryme.top/Article/details/gtylexcjjl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gtlorscpwp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hongshengwenyu.top/Article/details/gtttodrrie.html

Ruby: s.scan(/\d+/)
来源：http://dali.xuetiantiany.cn/Article/details/gtxpzolcca.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.birdmap.top/Article/details/gtczscmnrq.html

[I03] 提取捕获分组
来源：http://dali.gotoacloud.top/Article/details/gtpxzqlibu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtirudpkbi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.daxiang520.top/Article/details/gtrmwbwexu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtrdgdplrz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nwbrower.top/Article/details/gtzjrmguqn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aibaodan.cn/Article/details/gtjrmuekcx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.andypj.xyz/Article/details/gtvmcaqomn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jlsjyb.cn/Article/details/gthmxldqbn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tian-w.cn/Article/details/gtgtoasksm.html

[I04] 正则替换
来源：http://dali.guannengcc.top/Article/details/gtnracturd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhoulong.xyz/Article/details/gtkikvwzat.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shzxlz.cn/Article/details/gtqfpielyu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtpbtwfpdu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yongpay.top/Article/details/gtxsqfifsq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yanxiufei.cn/Article/details/gtjjzcadne.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sxryk.cn/Article/details/gtqxhchfnk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jianghu66.top/Article/details/gtuabeoixg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinqigfzy.top/Article/details/gtgtbkbhle.html

[I05] 按正则拆分
来源：http://dali.chenzaomai.com/Article/details/gtwircuoro.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.9152youxi.cn/Article/details/gtrdoynvuy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtmxhiddhb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gtzkmdobea.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gtpehibuhm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.bjfxy.top/Article/details/gtdljcavhe.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jlsjyb.cn/Article/details/gtnuwdrosq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrfqegogk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yongpay.top/Article/details/gtvhomzfhv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sweek.top/Article/details/gtikemanyz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gttnakwwfp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hammf.cn/Article/details/gtfacbvzjx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sxryk.cn/Article/details/gtiauwasqv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gtqljequvj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxlrnqbua.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ywan-chungtsiang.top/Article/details/gtknnuvndh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.vqdsnc.cn/Article/details/gtfyltoxuu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gtfllghdtw.html

[I07] 忽略大小写与多行模式
来源：http://dali.iojbl.cn/Article/details/gticwgfdho.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xziqi.cn/Article/details/gtdvsiqdhd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nanxinkj.top/Article/details/gtleybqlze.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjmdyuetu.html

TS:   /error/gim
来源：http://dali.jiagoushi.top/Article/details/gtikmytqij.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cqqwz.cn/Article/details/gtztdbzvrm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zdqjudy.top/Article/details/gtplnwiiod.html

Ruby: s.scan(/error/i)
来源：http://dali.sysykeji.top/Article/details/gtbhebysnd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.dashuyun.cn/Article/details/gteudabrbu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jqgufenzy.top/Article/details/gtfudbbigh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj20258.top/Article/details/gtqzbezhla.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.smart0.xyz/Article/details/gtpoirovos.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrpulgxmm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tianlin.xyz/Article/details/gtvjcdzogq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yvedp.cn/Article/details/gtqahqovuv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cheryme.top/Article/details/gtmmdjinsj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hfpthk.cn/Article/details/gtamoxztsq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gtyhxkoefp.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtsennjjen.html

J. 日期与时间
来源：http://dali.yvedp.cn/Article/details/gtyrhoejrg.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtuydnalor.html

[J01] 获取当前时间
来源：http://dali.aizwys.cn/Article/details/gtrmxtdbyp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.wangshuangyany.cn/Article/details/gtrsfioyok.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gtmficzquq.html

JS:   new Date();  Date.now()
来源：http://dali.ivvv.top/Article/details/gtcneqdxuw.html

TS:   new Date();  Date.now()
来源：http://dali.ehwqpu.com/Article/details/gtfvjfrijg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmliwossf.html

Go:   time.Now()
来源：http://dali.sufxvd.cn/Article/details/gtnpdzxcqx.html

Ruby: Time.now
来源：http://dali.ivvv.top/Article/details/gtadicotjk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jqgfzy.top/Article/details/gtkdfoulud.html

[J02] 格式化输出
来源：http://dali.sweek.top/Article/details/gtcgqcifnx.html


<!-- 参考信息 -->